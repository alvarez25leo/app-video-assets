# Prompts de imágenes — Aprender

> Archivo generado por `tools/learning-assets/generate_prompts.py` a partir de `backend/learning-content`.
> No lo edites a mano: cambia el contenido o el script y vuelve a generarlo.
> **88 imágenes** en total.

**Cómo usarlo:** cada bloque es **una imagen**. Pásale el prompt al skill `chatgpt-image-generator` y guarda el PNG
exactamente en la ruta indicada. Cuando tengas un lote, corre:

```bash
python3 tools/learning-assets/build_assets.py   # genera 1024/512/256/128 en WebP + manifest
cd backend && pnpm learning:sync                # publica en la base
```

Mientras una imagen no exista, la app muestra el emoji del item: puedes ir completando de a poco.
Números, colores, formas y letras **no necesitan imagen** (la app los dibuja).

## 1. Items (animales, frutas, cuerpo)

### Animales de granja (8)

#### Vaca · `animals/cow`

- **Guardar en:** `learning-assets/_originals/images/animals/cow/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una vaca lechera blanca con manchas negras, nariz rosada y una campanita al cuello.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cerdo · `animals/pig`

- **Guardar en:** `learning-assets/_originals/images/animals/pig/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un cerdito rosado y regordete con hocico redondo y cola en espiral.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Gallo · `animals/rooster`

- **Guardar en:** `learning-assets/_originals/images/animals/rooster/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un gallo colorido con cresta roja, plumas doradas y cola verde tornasolada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Caballo · `animals/horse`

- **Guardar en:** `learning-assets/_originals/images/animals/horse/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un potrillo (caballo bebé) de pelaje dorado claro tipo palomino, crin y cola cortas color crema, una estrellita blanca en la frente y patas largas, de pie en cuatro patas y con la boca cerrada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Oveja · `animals/sheep`

- **Guardar en:** `learning-assets/_originals/images/animals/sheep/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una oveja con lana blanca muy esponjosa y carita gris.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cabra · `animals/goat`

- **Guardar en:** `learning-assets/_originals/images/animals/goat/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una cabra blanca con cuernitos cortos y barbita.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pato · `animals/duck`

- **Guardar en:** `learning-assets/_originals/images/animals/duck/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un pato blanco con pico y patas naranjas.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Burro · `animals/donkey`

- **Guardar en:** `learning-assets/_originals/images/animals/donkey/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Dibuja un burrito bebé de pelaje marrón claro y suave, panza color crema, orejas largas con puntas oscuras, crin corta y esponjosa y una florcita amarilla en una oreja, sentado y sonriendo con la boca cerrada.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, tierna y amigable, colores vivos, formas redondeadas, ojos grandes y expresivos, sonrisa suave. Un solo sujeto de cuerpo entero, centrado, mirando al frente y ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.

IMPORTANTE: diseño de personaje 100 % original. No debe parecerse a ningún personaje conocido de películas, series, videojuegos, libros ni marcas (ni en la forma, ni en los colores característicos, ni en la expresión). Solo debe reconocerse como el animal u objeto descrito.
```

### Animales salvajes (10)

#### León · `animals/lion`

- **Guardar en:** `learning-assets/_originals/images/animals/lion/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un león adulto de pelaje arena claro con una melena redonda y esponjosa color naranja rojizo que le rodea la cara como un sol, sentado en cuatro patas y con la boca cerrada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Elefante · `animals/elephant`

- **Guardar en:** `learning-assets/_originals/images/animals/elephant/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un elefante adulto gris cálido con orejas medianas, colmillos cortitos color marfil y piel con arruguitas suaves, de pie en cuatro patas y con la trompa hacia abajo.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Jirafa · `animals/giraffe`

- **Guardar en:** `learning-assets/_originals/images/animals/giraffe/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una jirafa bebé de manchas color canela con bordes claros y cuernitos con puntas oscuras, de pie en cuatro patas (debe entrar completa en el cuadro).

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cebra · `animals/zebra`

- **Guardar en:** `learning-assets/_originals/images/animals/zebra/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una cebra bebé de rayas marrón oscuro y crema como los potrillos reales, con crin corta en cepillo, de pie en cuatro patas y con la boca cerrada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Mono · `animals/monkey`

- **Guardar en:** `learning-assets/_originals/images/animals/monkey/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un monito tití de pelaje gris y marrón, con mechones blancos en las orejas y cola larga anillada, sentado y con la boca cerrada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Tigre · `animals/tiger`

- **Guardar en:** `learning-assets/_originals/images/animals/tiger/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un cachorro de tigre de Bengala de pelaje naranja suave, rayas negras finas y panza blanca, echado sobre la panza con las patas delanteras estiradas.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Oso · `animals/bear`

- **Guardar en:** `learning-assets/_originals/images/animals/bear/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un osezno (oso bebé) de pelaje color chocolate y hocico canela, sentado en cuatro patas como un oso real.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Hipopótamo · `animals/hippo`

- **Guardar en:** `learning-assets/_originals/images/animals/hippo/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un hipopótamo bebé de piel gris rosada, orejitas pequeñas y ojos en lo alto de la cabeza, de pie en cuatro patas y redondito.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cocodrilo · `animals/crocodile`

- **Guardar en:** `learning-assets/_originals/images/animals/crocodile/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un cocodrilo bebé verde oliva con escamas redondeadas y panza amarillo pálido, echado en cuatro patas y con la boca cerrada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Rinoceronte · `animals/rhino`

- **Guardar en:** `learning-assets/_originals/images/animals/rhino/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un rinoceronte bebé gris claro con un cuerno corto y redondeado y piel con pliegues suaves, de pie en cuatro patas.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

### Animales marinos (8)

#### Delfín · `animals/dolphin`

- **Guardar en:** `learning-assets/_originals/images/animals/dolphin/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un delfín nariz de botella gris azulado con la panza clara, nadando de costado con la boca cerrada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pez payaso · `animals/clownfish`

- **Guardar en:** `learning-assets/_originals/images/animals/clownfish/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un pez payaso de la especie de Clark: cuerpo color chocolate, aletas amarillas y dos franjas blancas, visto de costado.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Tortuga · `animals/turtle`

- **Guardar en:** `learning-assets/_originals/images/animals/turtle/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una tortuga marina carey con caparazón ámbar de dibujo tipo mosaico café y pico curvo, nadando con las aletas abiertas.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pulpo · `animals/octopus`

- **Guardar en:** `learning-assets/_originals/images/animals/octopus/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un pulpo color lila con puntitos más claros y ocho tentáculos enrollados en espirales suaves.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Ballena · `animals/whale`

- **Guardar en:** `learning-assets/_originals/images/animals/whale/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una ballena jorobada gris azulada con la panza de pliegues claros y aletas largas, nadando.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cangrejo · `animals/crab`

- **Guardar en:** `learning-assets/_originals/images/animals/crab/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un cangrejo azul con pinzas de puntas celestes, visto de frente y con las pinzas abajo.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Estrella de mar · `animals/starfish`

- **Guardar en:** `learning-assets/_originals/images/animals/starfish/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una estrella de mar naranja con cinco brazos gruesos y textura de puntitos, vista desde arriba.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Foca · `animals/seal`

- **Guardar en:** `learning-assets/_originals/images/animals/seal/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una foca bebé de pelaje blanco y esponjoso con ojos oscuros, echada sobre la panza.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

### Mascotas (6)

#### Perro · `animals/dog`

- **Guardar en:** `learning-assets/_originals/images/animals/dog/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un perrito beagle marrón y blanco con la lengua afuera.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Gato · `animals/cat`

- **Guardar en:** `learning-assets/_originals/images/animals/cat/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un gatito gris atigrado sentado.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Conejo · `animals/rabbit`

- **Guardar en:** `learning-assets/_originals/images/animals/rabbit/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un conejito blanco con orejas largas y nariz rosada.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Hámster · `animals/hamster`

- **Guardar en:** `learning-assets/_originals/images/animals/hamster/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un hámster dorado y redondito con los cachetes llenos.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Loro · `animals/parrot`

- **Guardar en:** `learning-assets/_originals/images/animals/parrot/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un loro verde con cabeza amarilla y pico curvo.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pececito · `animals/goldfish`

- **Guardar en:** `learning-assets/_originals/images/animals/goldfish/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un pececito dorado con aletas grandes y transparentes.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

### Cuerpo humano (15)

#### Cabeza · `body/head`

- **Guardar en:** `learning-assets/_originals/images/body/head/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de la cabeza sonriente de un niño de dibujo animado, de frente.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Ojos · `body/eyes`

- **Guardar en:** `learning-assets/_originals/images/body/eyes/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de dos ojos grandes y brillantes de dibujo animado con cejas, sin el resto de la cara.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Nariz · `body/nose`

- **Guardar en:** `learning-assets/_originals/images/body/nose/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de la cara de un niño de dibujo animado con la nariz resaltada por un brillo suave.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Boca · `body/mouth`

- **Guardar en:** `learning-assets/_originals/images/body/mouth/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una boca sonriente de dibujo animado mostrando dientes blancos.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Orejas · `body/ears`

- **Guardar en:** `learning-assets/_originals/images/body/ears/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de la cabeza de un niño de dibujo animado de perfil con la oreja resaltada por un brillo suave.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Dientes · `body/teeth`

- **Guardar en:** `learning-assets/_originals/images/body/teeth/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un diente blanco sonriente con brillo, estilo mascota de cepillado.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Lengua · `body/tongue`

- **Guardar en:** `learning-assets/_originals/images/body/tongue/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una boca de dibujo animado sacando la lengua de forma graciosa.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Manos · `body/hands`

- **Guardar en:** `learning-assets/_originals/images/body/hands/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de dos manos infantiles abiertas saludando.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Dedos · `body/fingers`

- **Guardar en:** `learning-assets/_originals/images/body/fingers/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una mano infantil mostrando los cinco dedos abiertos.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Brazos · `body/arms`

- **Guardar en:** `learning-assets/_originals/images/body/arms/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un niño de dibujo animado mostrando los brazos fuertes, pose alegre.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Piernas · `body/legs`

- **Guardar en:** `learning-assets/_originals/images/body/legs/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un niño de dibujo animado corriendo, con las piernas resaltadas por un brillo suave.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pies · `body/feet`

- **Guardar en:** `learning-assets/_originals/images/body/feet/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de dos pies infantiles descalzos, tiernos.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cerebro · `body/brain`

- **Guardar en:** `learning-assets/_originals/images/body/brain/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un cerebro rosado amistoso de caricatura con carita sonriente (no realista).

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Corazón · `body/heart`

- **Guardar en:** `learning-assets/_originals/images/body/heart/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un corazón anatómico de caricatura, rojo y amistoso, con carita sonriente (no realista).

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pulmones · `body/lungs`

- **Guardar en:** `learning-assets/_originals/images/body/lungs/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de dos pulmones rosados de caricatura con carita sonriente (no realistas).

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

### Frutas (9)

#### Manzana · `fruits/apple`

- **Guardar en:** `learning-assets/_originals/images/fruits/apple/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una manzana roja brillante con una hoja verde.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Plátano · `fruits/banana`

- **Guardar en:** `learning-assets/_originals/images/fruits/banana/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un plátano amarillo maduro.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Fresa · `fruits/strawberry`

- **Guardar en:** `learning-assets/_originals/images/fruits/strawberry/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una fresa roja con semillitas y hojas verdes.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Naranja · `fruits/orange`

- **Guardar en:** `learning-assets/_originals/images/fruits/orange/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una naranja con una hoja verde.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Uvas · `fruits/grapes`

- **Guardar en:** `learning-assets/_originals/images/fruits/grapes/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de un racimo de uvas moradas.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Pera · `fruits/pear`

- **Guardar en:** `learning-assets/_originals/images/fruits/pear/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una pera verde.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Sandía · `fruits/watermelon`

- **Guardar en:** `learning-assets/_originals/images/fruits/watermelon/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una tajada de sandía roja con semillas negras.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Piña · `fruits/pineapple`

- **Guardar en:** `learning-assets/_originals/images/fruits/pineapple/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una piña con corona de hojas verdes.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

#### Cerezas · `fruits/cherries`

- **Guardar en:** `learning-assets/_originals/images/fruits/cherries/illustration.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de dos cerezas rojas unidas por el tallo.

Estilo: ilustración 3D infantil, tierna y amigable, con diseño propio y original: colores vivos, formas redondeadas, ojos grandes y brillantes, sonrisa pequeña y serena. Debe verse como un animal real simplificado, con la anatomía natural de su especie (en cuatro patas si corresponde), no como un personaje de caricatura de película: sin cejas humanas, sin expresiones exageradas, sin poses humanas, sin ropa ni accesorios. Un solo sujeto de cuerpo entero, centrado, en pose de tres cuartos, ocupando cerca del 80 % del lienzo. Iluminación suave de estudio. FONDO TRANSPARENTE (PNG con canal alfa), sin suelo, sin sombras proyectadas, sin texto, sin marcos y sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años: nada aterrador ni agresivo. Debe verse igual de claro en miniatura (128 px) que en grande.
```

## 2. Portadas de categorías

#### Animales

- **Guardar en:** `learning-assets/_originals/images/categories/animals/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Animales»: un gallo, una vaca y un perrito juntos en el pasto verde, felices.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Animales de granja

- **Guardar en:** `learning-assets/_originals/images/categories/animals-farm/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Animales de granja»: una granja con granero rojo, una vaca, un gallo y un cerdito en primer plano.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Animales salvajes

- **Guardar en:** `learning-assets/_originals/images/categories/animals-wild/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Animales salvajes»: un león, un elefante y una jirafa en la sabana africana con árboles de acacia.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Animales marinos

- **Guardar en:** `learning-assets/_originals/images/categories/animals-sea/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Animales marinos»: un delfín, un pez payaso y una tortuga marina bajo el mar con corales.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Mascotas

- **Guardar en:** `learning-assets/_originals/images/categories/animals-pets/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Mascotas»: un perrito, un gatito y un conejito en una sala acogedora.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Números

- **Guardar en:** `learning-assets/_originals/images/categories/numbers/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Números»: los números 1, 2 y 3 en 3D, gorditos y de colores (rojo, amarillo, azul), con destellos.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Colores

- **Guardar en:** `learning-assets/_originals/images/categories/colors/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Colores»: una paleta de pintor de madera con manchas de colores y un pincel.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Formas

- **Guardar en:** `learning-assets/_originals/images/categories/shapes/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Formas»: una esfera roja, un cubo azul, una estrella amarilla y una pirámide verde en 3D.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### ABC

- **Guardar en:** `learning-assets/_originals/images/categories/letters/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «ABC»: las letras A, B y C en 3D, gorditas y de colores (rojo, azul, verde).

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Cuerpo humano

- **Guardar en:** `learning-assets/_originals/images/categories/body/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Cuerpo humano»: un niño de dibujo animado sonriente con los brazos abiertos.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

#### Frutas

- **Guardar en:** `learning-assets/_originals/images/categories/fruits/cover.png`
- **Tamaño:** 1024×1024, con fondo

```text
Crea una imagen de portada para la categoría infantil «Frutas»: una canasta con manzanas, plátanos, uvas y fresas.

Estilo: ilustración 3D de animación infantil con diseño de personaje original, colores vivos, luz cálida, escena alegre con fondo completo. Composición centrada con aire en los bordes (la app puede recortarlos). Sin texto, sin letras, sin marcas de agua. Cuadrado 1024×1024. Para niños de 3 a 6 años.
```

## 3. Medallas

#### Primeros pasos (bronze)

- **Guardar en:** `learning-assets/_originals/images/medals/primeros-pasos/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de bronce cálido para premiar a un niño: «Primeros pasos» (Terminaste tu primera actividad.). En el centro, un ícono grande y simple que represente 🌱 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Explorador (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/explorador/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Explorador» (Terminaste 10 actividades.). En el centro, un ícono grande y simple que represente 🧭 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Súper explorador (gold)

- **Guardar en:** `learning-assets/_originals/images/medals/super-explorador/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de oro brillante para premiar a un niño: «Súper explorador» (Terminaste 50 actividades.). En el centro, un ícono grande y simple que represente 🚀 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### ¡Perfecto! (bronze)

- **Guardar en:** `learning-assets/_originals/images/medals/perfecto/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de bronce cálido para premiar a un niño: «¡Perfecto!» (Todo bien a la primera en una actividad.). En el centro, un ícono grande y simple que represente 🌟 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Campeón (gold)

- **Guardar en:** `learning-assets/_originals/images/medals/cinco-perfectas/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de oro brillante para premiar a un niño: «Campeón» (Cinco actividades perfectas.). En el centro, un ícono grande y simple que represente 🏆 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Amigo de la granja (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/amigo-de-la-granja/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Amigo de la granja» (Aprendiste 6 animales de granja.). En el centro, un ícono grande y simple que represente 🐄 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Rey de la selva (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/rey-de-la-selva/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Rey de la selva» (Aprendiste 6 animales salvajes.). En el centro, un ícono grande y simple que represente 🦁 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Explorador del mar (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/explorador-del-mar/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Explorador del mar» (Aprendiste 5 animales marinos.). En el centro, un ícono grande y simple que represente 🐬 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Amigo de las mascotas (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/amigo-de-las-mascotas/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Amigo de las mascotas» (Aprendiste 4 mascotas.). En el centro, un ícono grande y simple que represente 🐶 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Cuento hasta 5 (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/cuenta-hasta-5/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Cuento hasta 5» (Ya conoces los números del 1 al 5.). En el centro, un ícono grande y simple que represente 🖐️ (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Cuento hasta 10 (gold)

- **Guardar en:** `learning-assets/_originals/images/medals/cuenta-hasta-10/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de oro brillante para premiar a un niño: «Cuento hasta 10» (Ya conoces los números del 1 al 10.). En el centro, un ícono grande y simple que represente 🔟 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Contador (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/contador/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Contador» (Contaste bien 15 veces.). En el centro, un ícono grande y simple que represente 🧮 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Súper sumador (gold)

- **Guardar en:** `learning-assets/_originals/images/medals/sumador/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de oro brillante para premiar a un niño: «Súper sumador» (Resolviste 10 sumas.). En el centro, un ícono grande y simple que represente ➕ (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Arcoíris (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/arcoiris/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Arcoíris» (Aprendiste 6 colores.). En el centro, un ícono grande y simple que represente 🌈 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Maestro de formas (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/maestro-de-formas/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Maestro de formas» (Aprendiste 5 formas.). En el centro, un ícono grande y simple que represente 🔷 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Mis primeras letras (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/abc-inicial/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Mis primeras letras» (Aprendiste 5 letras.). En el centro, un ícono grande y simple que represente 🔤 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Conozco mi cuerpo (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/mi-cuerpo/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Conozco mi cuerpo» (Aprendiste 6 partes del cuerpo.). En el centro, un ícono grande y simple que represente 🧍 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Frutero (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/fruteria/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Frutero» (Aprendiste 5 frutas.). En el centro, un ícono grande y simple que represente 🍓 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Oído de oro (silver)

- **Guardar en:** `learning-assets/_originals/images/medals/oido-de-oro/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de plata brillante para premiar a un niño: «Oído de oro» (Reconociste 15 sonidos.). En el centro, un ícono grande y simple que represente 👂 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### Bilingüe (gold)

- **Guardar en:** `learning-assets/_originals/images/medals/bilingue/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de oro brillante para premiar a un niño: «Bilingüe» (20 respuestas correctas en inglés.). En el centro, un ícono grande y simple que represente 🌎 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```

#### ¡A jugar con animales! (bronze)

- **Guardar en:** `learning-assets/_originals/images/medals/nivel-animales/medal.png`
- **Tamaño:** 1024×1024, fondo transparente

```text
Crea una imagen de una medalla de bronce cálido para premiar a un niño: «¡A jugar con animales!» (Superaste el nivel 2 de animales.). En el centro, un ícono grande y simple que represente 🎯 (dibujado en 3D, no el emoji literal).

Estilo: medalla/insignia 3D brillante de videojuego infantil, redonda, con cinta, relieve y destellos suaves. FONDO TRANSPARENTE (PNG con canal alfa), sin texto ni números salvo que se pida, sin marcas de agua. Cuadrado 1024×1024. Debe entenderse en miniatura (128 px).
```
