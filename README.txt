# Ashwave Nutrition — prototipo gratuito

## Contenido
- `index.html`: aplicación web.
- `manifest.json`: metadatos para instalación como PWA.
- `service-worker.js`: caché básica para uso sin conexión tras la primera carga.

## Cómo probar
Abre `index.html` en un navegador moderno. Para instalación real desde Safari en iPhone, publica estos archivos en un sitio HTTPS.

## Publicación gratuita con GitHub Pages
1. Crea una cuenta gratuita en GitHub si no tienes una.
2. Crea un repositorio nuevo, por ejemplo `ashwave-nutrition`.
3. Sube los tres archivos (`index.html`, `manifest.json`, `service-worker.js`) a la raíz del repositorio.
4. En Settings → Pages, selecciona publicar desde la rama principal (`main`) y la carpeta raíz (`/root`).
5. Abre la URL HTTPS que GitHub Pages te proporciona desde Safari en el iPhone.
6. Pulsa Compartir → Añadir a pantalla de inicio.

## Importante
Los datos se guardan en `localStorage` del navegador. Exporta copias regularmente desde Objetivos → Exportar copia. Los alimentos son estimaciones aproximadas, no una base de datos clínica. Esta versión no escanea códigos de barras ni consulta automáticamente marcas o restaurantes.
