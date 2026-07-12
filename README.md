# La Aventura del Tiempo — PWA

## Qué contiene
- `index.html`: juego completo.
- `manifest.webmanifest`: configuración instalable.
- `sw.js`: caché para funcionamiento sin conexión.
- `icons/`: iconos del reloj.

## Importante: instalación inicial
Para que Chrome permita instalar una PWA, debe abrirse desde **HTTPS**. Un servidor LAN por
`http://192.168...` normalmente no permite registrar el Service Worker ni instalarla como PWA.

La solución más sencilla es publicar esta carpeta gratis en:
- GitHub Pages
- Cloudflare Pages
- Netlify

Una vez publicada:
1. Abre la URL HTTPS en Chrome desde la tablet.
2. Espera unos segundos con conexión a Internet para que se descarguen Tailwind y las fuentes.
3. Pulsa el botón amarillo `Instalar` o Chrome ⋮ → `Añadir a pantalla de inicio`.
4. Abre la aplicación una vez instalada.
5. Después puede usarse de viaje sin conexión.

## Prueba de funcionamiento offline
Después de instalar:
1. Abre el juego una vez con Internet.
2. Activa el modo avión.
3. Cierra y vuelve a abrir el icono de la aplicación.
