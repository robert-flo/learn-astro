# Workspace Instructions

Estas instrucciones aplican a todo el workspace.

## Comentarios en el código

- Comenta los archivos cuando agregues lógica que no sea obvia para una persona que está empezando.
- Escribe los comentarios en español
- Mantén los comentarios breves, claros y descriptivos.
- Explica el objetivo del bloque, no solo lo que hace una línea.
- Usa comentarios antes de bloques importantes, como:
  - frontmatter de Astro
  - lógica dinámica en `<script>`
  - manipulación del DOM
  - condicionales o cálculos que puedan confundir a un principiante
- Evita comentar líneas triviales o sintaxis evidente.
- Si el código cambia, actualiza o elimina comentarios que ya no coincidan con el comportamiento real.
- En archivos Astro, usa como modelo este estilo de comentarios:
  - `// Variables definidas en el servidor antes de renderizar la página.`
  - `<!-- Título principal visible en la página -->`
  - `<!-- Este texto se actualiza desde JavaScript cuando la página carga -->`
  - `<!-- Este valor se calcula al renderizar el servidor -->`
  - `// Buscamos el elemento del tiempo para poder cambiar su texto.`
  - `// Función que obtiene la hora actual y la muestra en pantalla.`
  - `// Mostramos la hora apenas carga la página y luego la actualizamos cada segundo.`
  - `// Obtenemos el año actual para escribirlo en el footer.`
  - `// Si el footer existe, colocamos el año dentro.`

- Si necesitas crear comentarios nuevos, imita ese tono: simple, didáctico y enfocado en ayudar a alguien que está aprendiendo.

## Estilo general

- Prioriza claridad sobre brevedad cuando el archivo sea didáctico.
- No agregues comentarios largos si un comentario corto basta.
- Evita duplicar comentarios que digan lo mismo de forma distinta.
