# By Dyzz — portafolio web

Sitio de una sola página para Dyzz (@_filmdyzz), director y creador audiovisual en Santiago de Chile.

## Estructura
- `index.html`: toda la página (HTML + CSS + JS en un solo archivo, sin frameworks ni build).
- `media/`: fotos (`.jpg`), logo (`logo.png`) y clips de video (`clip-01.mp4` … `clip-13.mp4`, 12 s, sin audio, 540p).
- Deploy: Vercel como sitio estático. Cada push a `main` publica solo.

## Identidad visual (no cambiar sin pedirlo)
- Colores: negro `#0C0C0D`, hueso `#EFEDE6`, papel `#ECEAE2`, gris `#9C9A94`, verde lima `#C6FF33`, violeta `#5B2BB5` (solo en la frase de cierre de "Quién soy").
- Tipografías (Google Fonts): Anton para títulos en mayúsculas, Space Grotesk para texto, Space Mono para etiquetas.
- Márgenes laterales con `--gut`; ancho máximo `--max: 1600px`.

## Secciones (en orden)
Portada → Quién soy → /01 Backstage (grilla + Superarte World Tour) → /02 Video (Videoclips + eventos, Moda + concepto) → /03 Foto → Artistas, escenarios + marcas → Servicios → Cotización → Contacto.

## Convenciones
- Cada trabajo es un `<article class="card">` con `.frame` (video o foto) y `.cap` (título + link a Instagram).
- Videos: `<video src poster muted loop playsinline preload="none">`; el script del final los reproduce solo cuando están en pantalla.
- Contacto: WhatsApp +56 9 5019 3962 (`https://wa.me/56950193962`). Falta el correo.
- La cotización no muestra precios: cada fila tiene un link "Cotizar" a WhatsApp con mensaje prellenado.
- Copy en español de Chile, directo y sin frases de agencia.

## Para probar en local
Abrir `index.html` en el navegador, o `npx serve .`
