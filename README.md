# COGNITIV · cognitiv.softwareinabox.eu

Web del producto **COGNITIV** (servidor de IA soberano sobre Lenovo ThinkSystem), una de las líneas de **Software in a Box** (https://www.softwareinabox.eu).

- Publicación: GitHub Pages (rama `main`, raíz) con dominio propio `cognitiv.softwareinabox.eu` (archivo `CNAME`), detrás de Cloudflare.
- Páginas: Design Components (`.dc.html`) servidas con `support.js`.
- Hasta noviembre de 2026 esta web estaba en la raíz de www.softwareinabox.eu; allí quedan redirecciones a este subdominio.

## Idiomas
El español es la fuente (páginas de la raíz). Las versiones `/en/`, `/fr/`, `/de/`, `/nl/`, `/pt/` e `/it/` se generan con `i18n/build.py` a partir de `i18n/<idioma>.json`, y el mismo script añade hreflang, canonical, selector de idioma y `sitemap.xml`. Tras editar una página en español: `python3 i18n/build.py extract`, traducir los textos nuevos y `python3 i18n/build.py build`. No editar a mano las carpetas de idioma.
