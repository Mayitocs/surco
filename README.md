# Surco

App web para planear, controlar y cerrar un ciclo de papa: presupuesto, calendario, bitácora, almacén de agroquímicos, contratos, gastos y venta por trailer.

Es un sitio estático: no necesita servidor ni base de datos. Los datos de cada persona se guardan en su propio navegador.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `surco`).
2. Sube todos los archivos de esta carpeta a la raíz del repositorio: `index.html`, `sw.js`, `manifest.webmanifest`, `icon.svg`, `icon-192.png`, `icon-512.png`.
3. En el repositorio: Settings, Pages, Source: "Deploy from a branch", rama `main`, carpeta `/ (root)`. Guarda.
4. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/surco/`.

## Instalar en el celular

Abre el enlace una vez con internet. En Android (Chrome): menú de tres puntos, "Instalar app". En iPhone (Safari): botón de compartir, "Agregar a inicio". Después funciona sin señal.

## Importante

- Los datos viven en el navegador y por dirección web. Si cambias el enlace del sitio, lo capturado no pasa al nuevo: usa "Descargar respaldo" en Ajustes y "Restaurar" en el nuevo.
- Para sacar una versión nueva, reemplaza `index.html` y cambia `V = 'surco-v1'` por `'surco-v2'` en `sw.js`.
- Los costos iniciales son una referencia de FIRA 2023-24 (Sinaloa). Cada productor debe sustituirlos por sus cotizaciones.
