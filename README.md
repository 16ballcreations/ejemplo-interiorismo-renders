# Vano Estudio — sitio de ejemplo (interiorismo y render)

**Sitio de ejemplo de 16 Ball Creations. Vano Estudio es una marca ficticia. Con `noindex`.**

Página web y marca completas para un estudio de interiorismo y render que **no existe**. Sirve
para enseñarle a cualquier prospecto del rubro (estudios de interiorismo, renderistas,
remodeladores, empresas de acabados u obra gris) cómo puede verse su marca y su página, antes
de empezar su propio proyecto con [16 Ball Creations](https://16ballcreations.com).

- Todas las imágenes son de stock con licencia libre ([Unsplash](https://unsplash.com/license)),
  optimizadas a WebP. Origen, autor y licencia de cada una: [CREDITOS-IMAGENES.md](CREDITOS-IMAGENES.md)
  y la página `creditos/` del sitio.
- Sin datos reales: WhatsApp abre sin número, el correo es `hola@vanoestudio.example` (dominio
  reservado) y la ciudad va sin dirección.
- El sitio muestra un aviso fijo «Sitio de ejemplo · 16 Ball Creations» y lo repite en el pie.

## La marca

- **Nombre:** Vano Estudio · Interiorismo & Render. El *vano* es el hueco de una pared, por donde
  entra la luz. Se revisó que no corresponda a un estudio conocido en Colombia.
- **Sello:** la V en Instrument Serif con la cota debajo. **Logotipo:** «Vano» + «ESTUDIO /
  INTERIORISMO & RENDER» + la cota. Todo en curvas en `assets/img/marca/`.
- **Paleta:** pizarra, cal, arcilla (acento), arcilla clara, piedra y salvia; en el tema claro,
  papel y arcilla profunda.
- **Frase:** «Primero lo ves. Después lo construimos.»
- **La cota**, la línea de medida de los planos, es el recurso gráfico propio.

La guía completa está en [MARCA.md](MARCA.md); el manual visual, en `marca/`.

## Secciones de la portada

| # | Sección | Qué hace |
|---|---|---|
| 0 | Menú | El sello y enlaces con «+» repartidos de lado a lado; botón de tema claro/oscuro |
| 1 | Portada | El nombre a todo lo ancho con la cota debajo, la franja 32:9, la frase entre paréntesis y la sala a todo lo ancho |
| 2 | Compromisos | Titular, anillo de imágenes que gira en 3D entre dos datos y los cinco compromisos |
| 3 | Proyectos | Tarjetas escalonadas; la primera es el comparador del boceto al render |
| 4 | Proceso | La escena queda fija y cada tercio del recorrido muestra un paso (1/3, 2/3, 3/3) |
| 5 | Obra gris | Titular, foto de obra y tarjeta oscura con el botón a WhatsApp |
| 6 | Servicios | Pantalla partida: la tarjeta cambia con flechas y la imagen grande con ella |
| 7 | Acabados | Tres fotos y la lista numerada |
| 8 | Preguntas | Acordeón |
| 9 | Pie | La frase, tres columnas, botón y logotipo; aviso de sitio de ejemplo |

Páginas internas: Proyectos (listado y siete detalles), Servicios, Nosotros, Ideas, Contacto (el
formulario arma el mensaje y lo abre en WhatsApp; no guarda datos), Créditos y el manual de marca.

Lo que en un sitio real daría el cliente (historia, equipo, testimonios, fotos del terminado) se
ve como **pendiente** (recuadro punteado «Por confirmar»): así se le muestra al prospecto qué
tendría que aportar.

## Cómo se edita

Las páginas se **generan**; no se editan los `index.html` a mano.

```bash
node herramientas/construir.mjs
```

```bash
node herramientas/servir.mjs 4350
```

| Ruta | Qué es |
|---|---|
| `fuente/marco.html` | `<head>` (con `og:`), menú, pie y aviso de ejemplo compartidos |
| `fuente/paginas/*.html` | El cuerpo de inicio, servicios, nosotros, ideas, contacto y créditos |
| `fuente/proyectos.json` | Los proyectos: de aquí salen el listado y cada detalle (`null` = pendiente) |
| `herramientas/construir.mjs` | Genera las páginas; arriba están `WA` (enlace de WhatsApp) y `URL_SITIO` (para `og:image`) |
| `marca/` | Manual de marca visual (doce secciones) |
| `MARCA.md` | La guía en texto; manda sobre el manual |
| `assets/css/marca.css` | Tokens de color, tipografía y la cota |
| `assets/css/sitio.css` | Estilos de todas las páginas, con el tema claro |
| `assets/js/sitio.js` | Cotas, apariciones, menú, comparador, proceso, servicios, formulario y tema |
| `assets/img/marca/` | Logotipo y sello en curvas, favicons PNG |
| `assets/img/web/` | Imágenes de stock en WebP y `og-image.jpg` (1200 × 630) |

## Para convertirlo en el sitio de un cliente

1. Cambiar nombre, logotipo, sello y paleta (`MARCA.md`, `marca.css`, `assets/img/marca/`, `fuente/marco.html`).
2. Poner el número real en `WA` (`construir.mjs`, `sitio.js`, enlaces de `fuente/paginas/`) y la URL pública en `URL_SITIO`.
3. Reemplazar las imágenes por las del cliente, rotuladas, y llenar los pendientes.
4. Quitar el aviso de ejemplo (`fuente/marco.html`, clase `aviso-ejemplo`), la página de créditos si ya no aplica y el `noindex` al publicar.
