# Instrucciones para agentes · Vano Estudio (sitio de ejemplo)

Vano Estudio es una **marca ficticia**: este repositorio es un sitio de ejemplo de 16 Ball Creations
para mostrar a estudios de interiorismo y render. No se mezcla con datos de clientes reales.

1. Lee primero `MARCA.md`: es la fuente de verdad de color, tipografía, la cota, tono y fotografía.
2. Usa solo los tokens de `assets/css/marca.css`; no agregues colores ni fuentes.
3. Toda imagen va rotulada «Render», «Foto real» o «Boceto». Un render nunca pasa por obra terminada. Solo imágenes de stock con licencia libre (Unsplash, Pexels, Pixabay), anotadas en `CREDITOS-IMAGENES.md` y en `fuente/paginas/creditos.html`.
4. Nada que parezca dato real: ni cifras, ni años, ni plazos, ni nombres de clientes, teléfonos, direcciones o redes.
5. Máximo dos cotas visibles por pantalla (el logotipo cuenta como una).
6. Todas las páginas llevan `<meta name="robots" content="noindex">` y el aviso de sitio de ejemplo con enlace a 16ballcreations.com.
7. Revisión local: `node herramientas/servir.mjs 4350`, en escritorio y a 375 px, sin desborde horizontal.
8. Las páginas se generan: edita `fuente/` (marco, páginas y `proyectos.json`) y corre `node herramientas/construir.mjs`. No edites los `index.html` generados.
9. Lo que en un sitio real daría el cliente va como pendiente (`null` en `proyectos.json`, clase `pendiente` o `pendiente-dato`), nunca inventado.
10. Revisa los dos temas (botón sol/luna del menú): el texto de acento pequeño en el tema claro va en `--arcilla-profunda`.
