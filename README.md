# learning-assets — imágenes y audios de "Aprender"

Repositorio **público** [`app-video-assets`](https://github.com/alvarez25leo/app-video-assets), incluido en el
proyecto como **submódulo git** en `app-video/learning-assets/`. Cada push a `main` lo publica en GitHub Pages
(`.github/workflows/pages.yml`):

```
https://alvarez25leo.github.io/app-video-assets/images/animals/cow/illustration-512.webp
└──────────────── LEARNING_ASSETS_BASE_URL ─────────────┘└──────── clave + tamaño ────────┘
```

Los scripts viven en el repo principal (`tools/learning-assets/`, `backend/scripts/`) y trabajan sobre esta
carpeta; tu código sigue privado y solo las imágenes/audio son públicos.

### Trabajar con el submódulo

```bash
git clone --recurse-submodules https://github.com/alvarez25leo/app_video.git   # clon nuevo con assets
git submodule update --init                                                      # si ya clonaste sin assets

cd learning-assets && git add -A && git commit -m "…" && git push   # 1) publica los assets
cd .. && git add learning-assets && git commit -m "Actualiza assets"  # 2) el proyecto apunta a esa versión
```

El repo principal guarda **qué commit** de assets usa: después de cada push de assets, haz también el commit
del paso 2 para que el proyecto quede apuntando a la versión nueva.

El backend guarda solo la **clave relativa** (`images/animals/cow/illustration`), los tamaños disponibles y un
hash. La URL final la arma la API con `LEARNING_ASSETS_BASE_URL`, así que el día que quieras pasar a
Cloudflare R2, S3 o un CDN **solo cambias esa variable**: no se toca la base ni las apps.

## Estructura

```
learning-assets/
├── _originals/                  ← tus PNG/JPG/audio originales (NO van a git, NO se publican)
│   ├── images/animals/cow/illustration.png
│   └── audio/animals/cow/sound.wav
├── images/                      ← generado por build_assets.py (sí se publica)
│   ├── animals/
│   │   └── cow/
│   │       ├── illustration-1024.webp
│   │       ├── illustration-512.webp
│   │       ├── illustration-256.webp
│   │       ├── illustration-128.webp
│   │       └── photo-1-512.webp …        (fotos reales, opcional)
│   ├── fruits/  body/  vehicles/ …
│   ├── categories/animals-farm/cover-512.webp …
│   └── medals/primeros-pasos/medal-256.webp …
├── audio/                       ← generado (sí se publica)
│   └── animals/cow/
│       ├── sound.m4a            (el "muuu")
│       ├── name.es.m4a          (pronunciación "vaca", opcional)
│       └── name.en.m4a          (pronunciación "cow", opcional)
├── manifest.json                ← generado: lista de archivos con tamaños, bytes y sha256
├── credits.json                 ← licencias de material de terceros
└── PROMPTS.md                   ← generado: un prompt por imagen para el skill de ChatGPT
```

### Por qué así (y no `animals/cow/cow-1024.png`)

- **La carpeta es el nombre del item** (`animals/cow/`): no hace falta repetirlo en el archivo.
- **El archivo dice qué es** (`illustration`, `photo-1`, `sound`, `name.es`): un item puede tener ilustración,
  varias fotos reales (aprendisaje.md §18), sonido y pronunciación en cada idioma.
- **El dominio no es la categoría**: la vaca vive en `animals/` aunque en la app esté en "Animales de granja".
  Si mañana reorganizas categorías, **no se mueve ningún archivo**.
- **WebP**: 30–70 % más liviano que PNG con la misma calidad, transparencia incluida; iOS y Android lo leen
  nativo. **4 tamaños** (128/256/512/1024, lado mayor): la app baja el que necesita (una opción de respuesta
  usa 256, la pantalla de explorar 1024). Nunca se agranda una imagen chica.
- **`?v=<hash>`** en cada URL: si reemplazas una imagen, cambia el hash y las apps no muestran la vieja de caché.

## Flujo para agregar imágenes

1. **Genera los prompts** (ya está hecho; repite si cambias el contenido):
   ```bash
   python3 tools/learning-assets/generate_prompts.py
   ```
2. **Genera cada imagen** con el skill `chatgpt-image-generator` usando el bloque de `PROMPTS.md` y guárdala en
   la ruta que indica (siempre bajo `_originals/`). Puedes ir de a poco: mientras falte una imagen, la app
   muestra el emoji del item.
3. **Genera tamaños + manifest**:
   ```bash
   python3 tools/learning-assets/build_assets.py            # incremental
   python3 tools/learning-assets/build_assets.py --force    # regenera todo
   python3 tools/learning-assets/build_assets.py --sizes 128,256,512,1024,2048   # otros tamaños
   ```
4. **Publica el catálogo en la base** (vincula los archivos a sus items por el nombre de carpeta):
   ```bash
   cd backend && pnpm learning:sync
   ```
5. **Sube este repo** (desde `learning-assets/`): `git add -A && git commit -m "…" && git push`. El workflow publica en Pages en ~1 min.

> Orden recomendado en producción: **primero push** (para que las URLs existan) y **luego `learning:sync`**
> contra la base de producción. Si lo haces al revés, durante unos minutos la app pedirá imágenes que aún no
> están publicadas (verá el emoji hasta que lleguen).

## Qué NO necesita imagen

Números, colores, formas y letras los **dibuja la app** a partir de `attributes` del item (`value`, `hex`,
`shape`, `glyph`): se ven nítidos a cualquier tamaño y pesan cero.

## Audio

| Archivo | Para qué | ¿Obligatorio? |
|---|---|---|
| `sound.m4a` | sonido del animal/vehículo | Solo para las actividades "¿Quién hace este sonido?". Sin sonidos, esas actividades se ocultan solas. |
| `name.es.m4a`, `name.en.m4a` | pronunciación | No. Si falta, la app usa la voz del sistema (iOS `AVSpeechSynthesizer`) con el nombre del item. |

`build_assets.py` convierte WAV/MP3/AIFF a **AAC mono 64 kbps (.m4a)** con `afconvert` (viene en macOS).

### Licencias (aprendisaje.md §66–67)

Los **sonidos se tratan como material de terceros**: no se publican hasta que agregues su licencia en
`credits.json` con `"verified": true` (el script de sync lo avisa). Fuentes recomendadas con licencia libre:
Freesound (filtra por CC0), Wikimedia Commons. Las imágenes que generas tú con IA y las pronunciaciones no
necesitan entrada en `credits.json`.

```json
"audio/animals/cow/sound": {
  "origin": "THIRD_PARTY", "license": "CC0-1.0", "author": "Autor",
  "sourceUrl": "https://freesound.org/people/.../sounds/12345/", "attribution": "Cow moo by Autor (CC0)",
  "verified": true
}
```

## GitHub Pages (una sola vez)

En este repo: Settings → Pages → Build and deployment → Source: **GitHub Actions**. Como el repo es público,
funciona con la cuenta gratuita.

Límites de Pages: sitio ≤ 1 GB y archivos ≤ 100 MB. Con WebP, 500 items × 4 tamaños ≈ 150 MB: sobra espacio.
