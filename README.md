# Mi Día

Organizador personal de tareas y horarios. PWA gratuita, sin anuncios y con almacenamiento local en el dispositivo.

## Plataformas

- **Android:** se puede instalar desde Chrome como PWA.
- **iPhone / iPad:** se puede añadir a la pantalla de inicio desde Safari (compatibilidad sujeta a la versión de iOS).
- **Windows:** se puede utilizar en el navegador y, en navegadores compatibles, instalar como aplicación web.
- **macOS:** se puede utilizar en el navegador y como aplicación web en navegadores compatibles.

## Recordatorios: limitación importante

Los avisos de la PWA se comprueban mediante JavaScript **mientras la aplicación está abierta y ejecutándose**. **No se garantizan notificaciones puntuales cuando está cerrada, suspendida o el teléfono está bloqueado**. Conceder permisos para notificaciones no elimina esa limitación. En iOS existen notificaciones Web Push para aplicaciones web instaladas bajo ciertas condiciones, pero este proyecto **no implementa un servicio push**.

Para compromisos importantes, utiliza también las alarmas del sistema operativo. Se prevé una futura aplicación Android con notificaciones locales programadas, sin servidor.

## Privacidad y datos

Las tareas se guardan en el almacenamiento local del navegador o de la aplicación instalada. No hay cuenta ni sincronización entre dispositivos. Exporta un respaldo JSON desde **Horario → Mis datos** antes de borrar datos, cambiar de navegador o migrar a una futura aplicación nativa.

## Instalación y uso sin conexión

Abre [Mi Día](https://chorizo1414.github.io/Organizador-de-tareas-y-d-a-/) en un navegador compatible y utiliza su opción de instalar o añadir a la pantalla de inicio. Después de cargarla correctamente, la PWA puede funcionar sin conexión gracias al service worker.

## Desarrollo

Primero se completará y probará la PWA. Después se evaluarán versiones Android, Windows y macOS compartiendo la mayor parte del código.
