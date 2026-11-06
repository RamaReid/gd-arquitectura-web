# GD · Arquitectura, Diseño y Construcción

Sitio público de GD en Tandil, con portfolio de diez casas y mapa de 54 ubicaciones confirmadas.

## Publicación

GitHub Actions verifica `checksums.txt`, extrae los paquetes `site-part-*.zip` en `_site/` y publica el contenido en GitHub Pages. Los ocho paquetes conservan las rutas originales y se separan para respetar los límites de carga del navegador.

Para actualizar, reemplazar los paquetes correspondientes y sus sumas SHA-256 en `checksums.txt`, y guardar los cambios en `main`. Para editar localmente, extraer todos los paquetes en una misma carpeta y abrirla con un servidor HTTP estático.
