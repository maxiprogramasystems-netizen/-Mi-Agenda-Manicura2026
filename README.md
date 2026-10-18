# Mi Agenda

Aplicacion web de un solo archivo (index.html) para control de turnos,
clientes e ingresos de servicios de manicura. Funciona sin conexion a
internet una vez cargada, y se puede instalar en la pantalla de inicio
del celular (Android/iPhone) como una app.

## Funciones

### Gestion de turnos
- Registrar turnos: cliente, servicio, fecha, hora y costo
- El costo es opcional al crear el turno (se puede dejar en blanco si
  aun no se sabe el precio) y editable en cualquier momento, incluso
  tocando directamente el valor en la lista (edicion rapida)
- Editar o eliminar cualquier turno
- Los turnos se muestran en el mismo orden en que se van ingresando
- Marcar turnos como "atendido"
- Formato de hora configurable: 24 horas o 12 horas (AM/PM)

### Panel e ingresos
- Clientes ingresados, pendientes por agendar/atender, atendidos
- Total de ingresos (suma de turnos atendidos)
- Recordatorios automaticos de turnos dentro de las proximas 48 horas
- Notificaciones del navegador para turnos pendientes

### Exportar
- Exportar todos los turnos a un libro de Excel (.xlsx)

### Apariencia
- Modo claro / oscuro (automatico segun el sistema, o manual)
- Acuarela de colores de fondo (Lila, Rosa, Durazno, Menta, Cielo),
  seleccionable desde la seccion Seguridad
- Logo de marca propio (calendario + frasco de esmalte)

### Seguridad (opcional, se activa cuando se quiere)
- Contrasena numerica (PIN de 4 a 6 digitos) o alfanumerica, con
  casillas individuales estilo codigo de verificacion
- Desbloqueo biometrico (huella / Face ID) en dispositivos compatibles
- Boton para quitar la contrasena en cualquier momento
- Recuperacion si se olvida la contrasena (no borra los turnos)

### Instalable como app
- Icono propio en el encabezado, favicon y pantalla de bloqueo
- Manifest incluido para "Agregar a pantalla de inicio" en Android e
  iPhone, abriendo a pantalla completa sin barra del navegador

## Como probarla antes de publicar
1. Descomprime este paquete.
2. Haz doble clic en `index.html` para abrirla en tu navegador.
3. Pruébala: agrega un turno, exporta a Excel, activa la contraseña,
   cambia el color de fondo, prueba el modo oscuro.

## Como subirla a GitHub (repositorio nuevo)
1. Crea un repositorio nuevo en GitHub (por ejemplo "mi-agenda").
2. Sube `index.html` y este `README.md` a la raíz (usando "uploading
   an existing file" en la página del repo, sin necesidad de Git por
   línea de comandos).
3. Si quieres un link público, activa GitHub Pages en
   Settings > Pages, eligiendo la rama `main` y carpeta `/ (root)`.
4. Una vez publicada por HTTPS (GitHub Pages lo es), la biometría
   (huella/Face ID) funcionará correctamente.

## Instalar en el celular
**Android (Chrome):** menú de tres puntos → "Agregar a pantalla de
inicio" o "Instalar aplicación".
**iPhone (Safari):** ícono de compartir → "Agregar a pantalla de
inicio".

## Datos y privacidad
Todos los datos (turnos, contraseña, preferencias) se guardan
únicamente en el navegador del dispositivo donde se use (localStorage).
No se envían a ningún servidor ni se guardan en el repositorio.

## Version
v1.0 — primera version consolidada del proyecto, reuniendo todas las
funciones desarrolladas y verificadas.
