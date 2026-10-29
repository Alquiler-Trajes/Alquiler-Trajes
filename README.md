# Vestuario · Alquiler de trajes y accesorios

Página: https://alquiler-trajes.github.io/Alquiler-Trajes/

El catálogo ofrece 29 trajes y 9 accesorios o kits. El inicio conserva Danzas y princesas, Profesiones y disfraces, y un acceso sencillo a Accesorios. Piloto se ofrece como traje completo y como kit de accesorios, con enlaces entre las dos opciones. Su foto actual muestra el kit y se indica que la foto del uniforme está pendiente.

La selección permite reunir trajes y accesorios. Los doce modelos culturales conservan alquiler x1 o juego x6. Las 296 unidades registradas se conservan; las cantidades de accesorios y del uniforme de piloto, y las tarifas, están por confirmar. Tres fotos de accesorios se editaron para retirar personas y anuncios, con identificación de edición con IA.

Esta entrega contiene:

- github-pages-listo.zip: catálogo compilado para GitHub Pages.
- github-pages.sha256: comprobación del paquete antes de publicar.
- vestuario-fuente.zip: código fuente, dependencias declaradas, migraciones, scripts y pruebas.

Se verificaron 23 pruebas unitarias, 26 de integración, 10 de navegador en escritorio/móvil, tipos y compilación estática. También se auditó el stock compartido entre piloto completo y su kit.

El Excel con fotos se entrega de forma privada y no se incluye en la página. La selección pública no confirma reservas. La aplicación completa de inventario y reservas requiere Node.js y PostgreSQL; GitHub Pages aloja el catálogo estático.

## Actualizar

Extraer el código fuente y seguir su README. Ejecutar pnpm pages:snapshot, pnpm pages:build y pnpm pages:test. Empaquetar el contenido de apps/web/out y reemplazar juntos github-pages-listo.zip y github-pages.sha256. El siguiente commit comprueba el paquete y vuelve a publicar. Los datos privados, credenciales y originales con rostros se conservan fuera del repositorio público.