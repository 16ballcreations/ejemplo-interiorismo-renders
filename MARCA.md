# Vano Estudio: identidad

**Marca ficticia.** Vano Estudio no existe: es la marca de un sitio de ejemplo que hizo
16 Ball Creations para mostrar a estudios de interiorismo y render cómo puede verse su
marca y su página. Cualquier parecido con una empresa real es casualidad. Manual visual:
`marca/index.html`. Si algo aquí y en el manual no coincide, manda este archivo.

## De dónde sale

- **El nombre.** En arquitectura, el *vano* es el hueco de una pared: la ventana, la
  puerta, el lugar por donde entra la luz. Un estudio de interiorismo trabaja justo ahí:
  en cómo entra la luz y en cómo se pasa de un espacio a otro.
- **La V.** La letra del nombre, en serif de alto contraste, es también la forma de una
  ventana vista en corte: dos jambas que se abren hacia arriba. Es el sello.
- **La cota.** La línea de medida de los planos. Antes de construir, todo se mide; la
  cota dice «esto está medido»: plazo y presupuesto hechos dibujo.
- **El render.** Lo que vende el estudio es ver el espacio antes de construirlo. Por eso
  la marca siempre dice qué es render y qué es foto real.

## Esencia

- **Propósito:** que cualquier familia pueda vivir en el espacio que imaginó, viéndolo
  antes de construirlo.
- **Promesa:** ves tu espacio en render antes de construirlo, y lo entregamos en la
  fecha y el presupuesto que acordamos.
- **Personalidad** (deciden cualquier duda):
  - **Luminosa:** luz, aire y pocas cosas bien puestas. Si sobra algo, se quita.
  - **Precisa:** todo medido y dicho antes de empezar: alcance, fecha y costo.
  - **Cálida:** materiales nobles, tonos de tierra, trato cercano.
- **Audiencia:** familias y propietarios que recibieron su apartamento en obra gris o
  quieren renovar casa, apartamento u oficina. Deciden viendo (render, boceto, antes y
  después) y confiando en que se cumplan el tiempo y el precio. La marca siempre termina
  en el mismo lugar: **una cotización sin costo por WhatsApp**.
- **Lo que hacemos** (nombres oficiales):
  - Diseño de espacios y renders: el proyecto en imágenes fotorrealistas antes de construir.
  - De obra gris a hogar: entrega completa del apartamento nuevo, con acabados.
  - Remodelaciones: cocinas, baños, pisos e iluminación.
  - Restauraciones: devolverle la vida a lo que ya existe.
  - Acabados: revestimiento, drywall, pintura y enchape.
  - Asesorías: acompañamiento para decidir antes de invertir.
- **Es / no es:** cercana, no informal · cálida, no rústica · clara con el precio, no
  barata · actual, no de moda pasajera · puntual, no apurada.
- **Palabras propias:** luz, espacio, hogar, medir, ver antes, a tu medida, a tiempo,
  render, boceto, obra gris, acabados.
- **Frase de marca:** «Primero lo ves. Después lo construimos.»
- **Los cinco compromisos** (en este orden): Lo ves antes · Fecha desde el primer día ·
  A la medida de tu presupuesto · Materiales que duran · Un solo equipo de principio a fin.

## Logotipo

- **Construcción:** «Vano» en Instrument Serif 400; a su derecha, tras un filete fino, dos
  líneas en Instrument Sans 500 mayúsculas espaciadas: «ESTUDIO» e «INTERIORISMO &
  RENDER»; debajo, la cota en arcilla de lado a lado. Proporción 600 × 160 (3,75 : 1).
- **Unidad X:** la altura de la V.
- **Versiones:** sobre pizarra (texto cal, cota arcilla) · sobre cal (texto pizarra, cota
  arcilla) · reducida: solo la V con la cota debajo (es el sello) · sobre foto: solo con
  velo pizarra al 60 % o sobre una zona limpia.
- **Dónde va cada versión:** el logotipo completo donde hay ancho (pie de la web,
  tarjetas, cotizaciones, documentos); el sello donde no cabe (menú de la web, favicon,
  avatar, firma, bordado, marca de agua).
- **Área de reserva:** ½ X por los cuatro lados; en impresos pequeños, mínimo 4 mm.
- **Tamaños mínimos:** logotipo completo 160 px / 35 mm de ancho; sello 24 px / 8 mm.
- **Usos incorrectos:** degradados o brillos; contorno o sombra; estirar o rotar; cambiar
  la fuente; poner el logotipo sobre un render cargado sin velo; la cota en otro color que
  no sea arcilla; separar la cota del nombre.
- Todo el logotipo va en curvas: `assets/img/marca/logotipo.svg` y `logotipo-claro.svg`.

## Sello

La V en Instrument Serif sobre pizarra con una cota corta de arcilla debajo. Retícula de
64 × 64: V a 46 de cuerpo, cota de x 16 a 48 a la altura 51. No se separa la cota de la
V. Usos: menú de la página web (sin el cuadro: la V del color del texto y la cota en
arcilla), favicon (SVG + PNG de 32 y de 180 para iPhone), avatar de redes (cabe en el
recorte circular), firma de correo (PNG de 96 px mostrado a 48), bordado y marca de agua
en renders (esquina inferior derecha, 8 % del lado corto, 70 % de opacidad). Archivos, en
curvas: `assets/img/marca/sello.svg`, `favicon-32.png`, `apple-touch-icon.png`, `sello-96.png`.

## Color

| Token | Hex | Nombre | Uso | % |
|---|---|---|---|---|
| `--pizarra` | #171B1A | Pizarra | Fondo principal, texto sobre claro | 55 |
| `--cal` | #EFEAE2 | Cal | Fondo claro, texto sobre oscuro | 28 |
| `--arcilla` | #B5603A | Arcilla | La cota, botones, la palabra en itálica de un titular | 8 |
| `--arcilla-clara` | #E0A07A | Arcilla clara | Texto de acento pequeño sobre pizarra | 4 |
| `--piedra` | #68635B | Piedra | Texto secundario y filetes sobre cal | 3 |
| `--salvia` | #45503F | Salvia | Detalles menores: etiquetas sobre cal, sellos de estado | 2 |

**Contrastes** (calculados, WCAG 2):
- Cal sobre pizarra 14,5 (AAA): todo el texto.
- Arcilla clara sobre pizarra 7,9 (AAA): etiquetas y enlaces en hojas oscuras; botón de acento con texto pizarra.
- Salvia sobre cal 7,1 (AAA): etiquetas y textos cortos en hojas claras.
- Piedra sobre cal 5,0 (AA): texto secundario.
- Arcilla sobre pizarra 3,9 y sobre cal 3,7 (AA grande): la cota, el círculo de la flecha
  del botón y la palabra en itálica de titulares ≥ 24 px. Nunca texto pequeño.
- Piedra sobre pizarra 2,9: solo filetes y elementos gráficos, no texto.

**Tema claro de la web:** la página ofrece una variante iluminada con un botón en el menú.
Las zonas oscuras pasan a cal con texto pizarra, y las claras a **papel** (`--papel`
#FAF7F2). El texto de acento pequeño usa **arcilla profunda** (`--arcilla-profunda`
#97461F: 5,5 sobre cal, 6,1 sobre papel). La arcilla normal sigue para la cota, los íconos
y la palabra que se inclina en titulares grandes. El oscuro es el tema de base.

**El botón:** píldora cal con texto pizarra en hojas oscuras, píldora pizarra con texto
cal en hojas claras; a la derecha, un círculo de arcilla con la flecha en pizarra.

**A evitar:** salvia sobre pizarra (2,1); arcilla sobre salvia (1,9); arcilla clara sobre
cal (1,9); texto pequeño en arcilla sobre cualquier fondo; bloques grandes de arcilla (más
de un botón o una franja por pantalla).

## Tipografía

Una familia, dos voces: **Instrument Serif** (400 y su itálica) para la voz grande e
**Instrument Sans** (400 y 500) para la voz que informa. Google Fonts, libres (OFL).

| Nivel | Fuente | Escritorio / móvil | Interletrado | Interlínea |
|---|---|---|---|---|
| Display | Serif 400 | 144 / 52 px | −2 % | 0,92 |
| Titular | Serif 400 | 72 / 36 px | −1,5 % | 1,0 |
| Subtítulo | Serif 400 | 36 / 24 px | −1 % | 1,15 |
| Texto | Sans 400 | 18 / 16 px, máx. 64 caracteres | 0 | 1,6 |
| Etiqueta | Sans 500 mayúsculas | 12 px | +24 % | 1,4 |

Reglas:
- **La palabra que se inclina:** en cada titular, una sola palabra puede ir en itálica
  serif y en arcilla: la que lleva la emoción («Tu *hogar*, a tiempo»). Nunca dos.
- Sin negritas en serif; en sans, 500 como máximo.
- Mayúsculas solo en etiquetas y botones. Titulares en oración.
- Comillas latinas « ». m² con superíndice.
- **Sin la fuente:** Georgia (titulares) + Arial (texto).

## La cota

**Qué es:** la línea de medida de un plano. Dice «esto está medido». Es la puntualidad y
el presupuesto hechos dibujo.

**Construcción:** línea de 1 px (0,25 mm impresa) con dos remates oblicuos a 45° de 9 px en
los extremos. Siempre arcilla. Puede llevar encima una medida o una palabra en la voz de
etiqueta, centrada («A TU MEDIDA», «60 × 120 CM», «A TIEMPO»). Movimiento: se traza de
izquierda a derecha una sola vez al entrar en pantalla, 1,2 s,
`cubic-bezier(0.65, 0, 0.35, 1)`; los remates aparecen al final. Clase `.cota` +
`.trazada` en `assets/css/marca.css`; sin movimiento si el usuario lo pide.

**Dónde sí:** bajo el titular de portada · encabezados de sección · entre el boceto y el
render · junto a cifras de tiempo o medida · el sello y el logotipo.
**Dónde no:** sobre caras o personas · como subrayado de enlaces · en vertical · apilada
en varias líneas seguidas · en otro color · como borde de tarjetas.
**El tope:** máximo **dos cotas visibles** por pantalla o por pieza (el logotipo cuenta como una).

## Composición

Retícula de 12 columnas, máx. 1440 px, margen `clamp(16px, 4vw, 64px)`. Hojas oscuras
(pizarra) y claras (cal) alternadas, como una revista. Mucho aire. Fotos en ángulo recto,
sin marcos ni sombras; solo los botones son píldora. Numeración de secciones en etiqueta
(«01 — Lo que hacemos»). Pie de foto en etiqueta con el tipo de imagen («RENDER · SALA …»
o «FOTO REAL · OBRA …»).

## Tono

**De tú**, siempre. Español neutro de Colombia, frases cortas.

1. **Primero la emoción, después el dato.** Sí: «Llegar a casa y que la luz entre donde
   la imaginaste.» No: «Ofrecemos soluciones integrales de interiorismo.»
2. **Se ve el cambio.** Sí: «Del boceto al render, y del render a tu sala.» No: «Transformamos tu vida.»
3. **El precio sin miedo.** Sí: «Cuéntanos tu presupuesto y diseñamos a partir de ahí.»
   No: «¡Precios increíbles!»
4. **Prometer solo lo que se mide.** Sí: «Te damos fecha de entrega antes de empezar.»
   No: «Los mejores de la ciudad.»
5. **Una idea por pieza.**
6. **Cercanos, no informales.** Sí: «Te ayudamos a decidir.» No: «Holi, ¿qué más?»

Usa / evita: espacio, hogar / inmueble, unidad · a tu medida / económico, barato · a
tiempo / rápido, express · render / foto (cuando es render) · cotización sin costo /
gratis gratis · acabados / premium, lujo.

**Firma:** «Primero lo ves. Después lo construimos.» + «Vano Estudio».
**Cómo nos nombramos:** Vano Estudio; «Vano» a secas en titulares y en el logotipo.

## Fotografía

- **Render o foto real, siempre dicho:** en la web, etiqueta en el pie («RENDER» /
  «FOTO REAL» / «BOCETO»). Un render nunca se presenta como obra terminada.
- **Del boceto al render:** el comparador de la web muestra el boceto a mano alzada y el
  render del mismo encuadre.
- **Toma:** luz de día; temperatura cálida; verticales rectas; nunca ojo de pez; una toma
  de detalle por proyecto.
- **Receta de color:** sombras hacia pizarra (no negras puras), altas luces hacia cal (no
  blancas), maderas y barro hacia arcilla; saturación suave; sin viñeta ni HDR.

**En este sitio de ejemplo** todas las imágenes son de stock con licencia libre
(Unsplash). Cada una está en `CREDITOS-IMAGENES.md` con su autor y su origen.

## Lo que nunca se publica

Dirección exacta ni nombre de clientes sin permiso · precios en público · cifras de
proyectos, años de experiencia o premios sin confirmar · renders presentados como obra
terminada · fotos de personas sin permiso.

## Archivos

- `assets/css/marca.css`: tokens de color, tipografía, retícula y la cota.
- `assets/img/marca/logotipo.svg` / `logotipo-claro.svg`: logotipo en curvas para fondo pizarra / cal.
- `assets/img/marca/sello.svg`, `favicon-32.png`, `apple-touch-icon.png`, `sello-96.png`: el sello.
- `assets/img/web/`: imágenes de stock optimizadas (WebP) y `og-image.jpg`.

## Cambios

- v1.0 · noviembre 2026 · Marca ficticia de ejemplo (16 Ball Creations), a partir del sistema de una propuesta de interiorismo: nombre, sello, logotipo, paleta y textos nuevos.
