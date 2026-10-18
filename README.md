# Mi Agenda v2.0

Aplicacion web de un solo archivo (index.html) para control de turnos,
clientes e ingresos de servicios de manicura.

## Novedad de esta version
- Nuevo icono de marca: calendario + frasco de esmalte (reemplaza el
  icono anterior de libreta con espiral), integrado en:
  - El encabezado de la app
  - El icono para instalar en la pantalla de inicio de Android (manifest)
  - El favicon de la pestaña del navegador

## Funciones completas
- Registro de turnos: cliente, servicio, fecha, hora y costo
- Costo editable y opcional al crear el turno, y editable tambien tocando
  directamente el valor en la lista de turnos (edicion rapida)
- Los turnos se muestran en el mismo orden en que se van ingresando
- Formato de hora (24 horas / 12 horas AM-PM), elegible desde "Seguridad"
- Editar o eliminar turnos
- Panel con clientes ingresados, pendientes, atendidos e ingresos
- Exportar los datos a Excel (.xlsx)
- Modo claro / oscuro (manual o segun el sistema)
- Seguridad opcional (seccion "Seguridad" dentro de la app):
  - Contrasena numerica (PIN de 4 a 6 digitos) o alfanumerica
  - Boton para quitar la contrasena en cualquier momento
  - Desbloqueo biometrico (huella / Face unlock) en dispositivos compatibles
- Notificaciones de turnos pendientes (navegador)
- Instalable en la pantalla de inicio de Android como una app

## Instalar en Android (pantalla de inicio)
1. Abre el sitio publicado en Chrome para Android.
2. Toca el menu de tres puntos (esquina superior derecha).
3. Elige "Agregar a pantalla de inicio" o "Instalar aplicacion".
4. Confirma: quedara con su propio icono (el nuevo de calendario + esmalte)
   y se abrira a pantalla completa.

## Subir a GitHub
Puedes hacerlo de dos formas:

**A) Como continuacion del mismo repositorio:**
Reemplaza el index.html existente por este y sube los cambios (commit).

**B) Como un repositorio nuevo:**
1. Crea un repositorio nuevo en GitHub (por ejemplo "mi-agenda-v2").
2. Sube este index.html (y este README) a la raiz.
3. Si quieres GitHub Pages, activalo en Settings > Pages.

No requiere servidor, base de datos ni build: es HTML/CSS/JS autocontenido.
Los datos de cada usuaria se guardan en el navegador de su propio
dispositivo (localStorage), no en el repositorio.

## Version
v2.0 - nuevo icono de marca (calendario + esmalte), reemplazando el icono
anterior en toda la app.
