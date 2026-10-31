# Brio · web

Sitio de Brio, agencia de gestión creativa de redes. "Las cosas se hacen con ganas."

Es una página estática: `index.html` + la carpeta `assets/`. No necesita instalar nada.

## Verla en tu compu

Abrí `index.html` en el navegador.

## Pendientes antes de publicar

- En `index.html` hay tres datos que se cargan una sola vez y se aplican a toda la página:
  - `const WHATSAPP = '59898123700'`: número con código de país, solo dígitos (ya cargado).
  - `const TELEFONO = '[TELEFONO]'`: para el botón Llamar, mismo formato.
  - `const INSTAGRAM = 'brio.comunicacion'`: usuario de Instagram, sin @ (ya cargado).
- Videos de los trabajos: en `index.html`, en la lista `STORIES`, completá `video` con la ruta de cada reel (ej: `assets/reels/cliente1.mp4`).
- Todo lo que está entre `[CORCHETES]`: clientes, reels y testimonio.

## Publicar

Conectá este repo en Vercel o Netlify (sitio estático, sin build). Cada push publica la versión nueva.

## Marca

Colores, tipografía (Outfit) y logo salen del manual de marca de Brio. El logo y los patrones están en `assets/` en vector.
