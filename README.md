# Vestuario · Alquiler de trajes

Catálogo público de trajes culturales y disfraces: 28 modelos, fotografías de estudio y doce vistas de juegos x6.

El inicio ofrece dos colecciones: **Danzas y princesas** (20 modelos) y **Profesiones y disfraces** (8). Los trajes se muestran en parejas, en el orden culturales, princesas, profesiones y disfraces. Incluye marcos suaves, letra legible, animaciones discretas, filtros plegados y navegación **Inicio / Mis trajes**.

La página se publica en **https://alquiler-trajes.github.io/Alquiler-Trajes/** cuando termina correctamente el flujo de GitHub Pages.

Este repositorio contiene la entrega verificada:

- `github-pages-listo.zip`: página compilada, lista para GitHub Pages. El flujo de publicación extrae este paquete.
- `github-pages.sha256`: suma de comprobación del paquete, verificada antes de publicar.
- `vestuario-fuente.zip`: código fuente completo del proyecto, dependencias declaradas, migraciones, scripts y pruebas. Se excluyen credenciales, datos privados, originales con rostros y copias de seguridad.

Se verificaron 70 pruebas y las compilaciones de la aplicación y del catálogo público. La página permite explorar fotos y tallas, elegir x1 o x6 con un solo selector, guardar «Mis trajes» y copiar o descargar el resumen. Se comprobaron teclado, movimiento reducido, escritorio, móvil y pantalla de 320 px. Los precios pendientes se indican como precio a consultar. La disponibilidad y la reserva se acuerdan con el negocio.

## Actualizar

Extraer el código fuente en una carpeta local y seguir su README. Con el inventario local disponible, ejecutar `pnpm pages:snapshot`, `pnpm pages:build` y `pnpm pages:test`. Volver a empaquetar el contenido de `apps/web/out` y reemplazar juntos `github-pages-listo.zip` y su archivo `github-pages.sha256`. El siguiente commit verifica el paquete y vuelve a publicar.

La aplicación completa de inventario y reservas requiere un servidor Node.js y PostgreSQL. GitHub Pages aloja el catálogo estático. El número de WhatsApp y las tarifas reales deben configurarse desde el negocio antes de ofrecer esas funciones.
