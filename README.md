# Vestuario · Alquiler de trajes y accesorios

Página: https://alquiler-trajes.github.io/Alquiler-Trajes/

El catálogo ofrece 34 trajes y 14 accesorios o kits. El inicio conserva Danzas y princesas, Profesiones y disfraces, y un acceso sencillo a Accesorios.

Piloto se ofrece únicamente como traje completo en Profesiones, con una nueva imagen de camisa blanca, pantalón negro, gorra, corbata, charreteras e insignia colocados en el uniforme. La tercera entrega agrega conjuntos completos de marinero, caballero años 20, baile, pirata y vampiro, además de nuevas opciones de accesorios. Los colores comparten ficha y pueden actualizar la fotografía. Se conservan separados los juegos con distinto contenido.

Se prepararon veinte imágenes de estudio sin personas, anuncios ni interfaz de compra. Se mantuvieron las fichas existentes de Astronauta, Hada violeta y Jasmine. El catálogo utiliza 63 imágenes e identifica las presentaciones editadas con IA.

Las 296 unidades registradas y los doce modelos culturales con alquiler x1 o x6 se conservan. Las nuevas combinaciones comparten sus piezas físicas. Las cantidades, tallas y tarifas pendientes no se inventaron.

Esta entrega contiene:

- github-pages-listo.zip: catálogo compilado para GitHub Pages.
- github-pages.sha256: comprobación del paquete antes de publicar.
- vestuario-fuente.zip: código fuente, dependencias, migraciones, scripts y pruebas.

Se verificaron tipos, compilación estática, doce pruebas de navegador en escritorio/móvil, la importación idempotente y las referencias de stock compartido. El Excel se actualizó de forma privada, conservando sus cuatro hojas y campos numéricos anteriores. El Excel no se incluye en la página ni se sincroniza automáticamente con la web.

La selección pública no confirma reservas. La aplicación completa de inventario y reservas requiere Node.js y PostgreSQL; GitHub Pages aloja el catálogo estático.

## Actualizar

Extraer el código fuente y seguir su README. Ejecutar pnpm pages:snapshot, pnpm pages:build y pnpm pages:test. Empaquetar el contenido de apps/web/out y reemplazar juntos github-pages-listo.zip y github-pages.sha256. El siguiente commit comprueba el paquete y vuelve a publicar. Credenciales, datos privados, originales y copias de respaldo quedan fuera del repositorio público.