# Mis Turnos — PWA

Esta carpeta contiene la versión instalable como aplicación web (PWA) de **Mis Turnos**.

## Archivos
- `index.html`: aplicación original con los cambios mínimos necesarios para PWA.
- `manifest.json`: nombre, iconos y configuración de instalación.
- `service-worker.js`: caché de la aplicación para poder abrirla sin conexión después de la primera visita.
- `icons/`: iconos de la aplicación.

## Datos
Los turnos se guardan en el almacenamiento local del navegador del dispositivo. Este paquete no incorpora un servidor ni una base de datos para sincronizar turnos.

La función de exportación a Excel carga su librería desde jsDelivr cuando se utiliza; por tanto, esa exportación puede necesitar conexión a Internet.
