# Brio · web

Sitio de Brio, agencia de gestión creativa de redes. "Las cosas se hacen con ganas."

Es una página estática: `index.html` + la carpeta `assets/`. No necesita instalar nada.

## Verla en tu compu

Abrí `index.html` en el navegador.

## Pendientes antes de publicar

- En `index.html` hay tres datos que se cargan una sola vez y se aplican a toda la página:
  - `const WHATSAPP = '[NUMERO]'`: número con código de país, solo dígitos (ej: `59899123456`).
  - `const TELEFONO = '[TELEFONO]'`: para el botón Llamar, mismo formato.
  - `const INSTAGRAM = '[USUARIO_BRIO]'`: usuario de Instagram, sin @.
- Videos de los trabajos: en `index.html`, en la lista `STORIES`, completá `video` con la ruta de cada reel (ej: `assets/reels/cliente1.mp4`).
- Todo lo que está entre `[CORCHETES]`: clientes, reels, testimonio, mail y dos respuestas de preguntas frecuentes.

## Publicar

Conectá este repo en Vercel o Netlify (sitio estático, sin build). Cada push publica la versión nueva.

## Marca

Colores, tipografía (Outfit) y logo salen del manual de marca de Brio. El logo y los patrones están en `assets/` en vector.
