# FIO — sitio web

Página de presentación de **FIO**, la app Android que registra y clasifica tus gastos a partir de las notificaciones del banco.

- Contenido: `site/` (HTML y CSS estáticos, sin dependencias ni paso de compilación).
- Publicación: `.github/workflows/deploy.yml` publica `site/` en GitHub Pages en cada push a `main`.
- Ver en local: abre `site/index.html` en el navegador, o `python3 -m http.server -d site`.
