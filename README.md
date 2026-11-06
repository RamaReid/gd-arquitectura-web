# GD · Arquitectura, Diseño y Construcción

Sitio público de GD en Tandil, con portfolio de diez casas y mapa de 54 ubicaciones confirmadas.

## Publicación

GitHub Actions extrae `website.zip` y `hero-images.zip` en `_site/` y publica ese contenido en GitHub Pages. Ambos paquetes conservan las rutas originales del sitio. Se separan para respetar el límite de carga por archivo del navegador.

Para actualizar, reemplazar los paquetes con la nueva versión y guardar los cambios en `main`. El workflow verifica las sumas SHA-256 declaradas antes de publicar; actualizar también esas sumas al reemplazar los paquetes.
