# Vestuario · Alquiler de trajes

Catálogo público de trajes culturales y disfraces: 28 modelos, fotografías de estudio, doce vistas de juegos x6, filtros y selección para compartir con el negocio.

La página se publica en **https://alquiler-trajes.github.io/Alquiler-Trajes/** cuando termina correctamente el flujo de GitHub Pages.

Este repositorio contiene la entrega verificada:

- `github-pages-listo.zip`: página compilada, lista para GitHub Pages. El flujo de publicación extrae este paquete.
- `vestuario-fuente.zip`: código fuente completo del proyecto, dependencias declaradas, migraciones, scripts y pruebas. Se excluyen credenciales, datos privados, originales con rostros y copias de seguridad.

Se verificaron 65 pruebas y las compilaciones de la aplicación y del catálogo público. La página estática permite explorar fotos y tallas, elegir x1 o x6, guardar la selección en el navegador y copiar o descargar su resumen. Los precios pendientes se indican como tarifa por confirmar. La disponibilidad y la reserva se acuerdan con el negocio.

## Actualizar

Extraer el código fuente en una carpeta local y seguir su README. Con el inventario local disponible, ejecutar `pnpm pages:snapshot`, `pnpm pages:build` y `pnpm pages:test`. Volver a empaquetar el contenido de `apps/web/out`, reemplazar `github-pages-listo.zip` y actualizar su SHA-256 en el flujo `.github/workflows/pages.yml`. El siguiente commit vuelve a publicar.

La aplicación completa de inventario y reservas requiere un servidor Node.js y PostgreSQL. GitHub Pages aloja el catálogo estático. El número de WhatsApp y las tarifas reales deben configurarse desde el negocio antes de ofrecer esas funciones.
