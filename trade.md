# Changelog

## [1.2.11] - 2018-10-18
### Mejora
- Se cambia los texto del envio de correo.

## [1.2.10] - 2018-10-18
### Mejora
- Se oculta formulario multimedia

## [1.2.9] - 2018-10-16
### Cambio
- Se agrega la funcionalidad para el envio de correo cuando olvidan contraseña
- Se cambia llave del password en SimpleCrypto.decodePwd

## [1.2.8] - 2018-10-15
### Cambio
- ProyectoController se envia el parametro de usuario en la funciones listadoReportesGuardados,avanceProyectos

## [1.2.7] - 2018-07-20
### Cambios
- Se agrega URL que redirecciona al "Aviso de Privacidad"

## [1.2.6] - 2018-05-31
### Cambios
- Se agrega el tipo de reporte con id 6 para reportes de inventario.

## [1.2.5] - 2018-05-29
### Cambios
- Se corrige un bug en el reporte de inventario que impedia generarlo de forma correcta.

## [1.2.4] - 2018-05-14
### Cambios
- Se activa la pregunta "lector de codigo de barras".

## [1.2.1] - 2018-05-14
### Cambios
- El equipo de upax ajusta funcionalidad de asignacion masiva.

## [1.2.0] - 2018-05-11
### Cambios
- Se muestran los campos de porcentajes al crear y editar un proyecto.

### Nuevo
- Se integra la nueva carga de asignaciones desarrollada por el equipo de upax.

## [1.1.0] - 2018-05-10
### Nuevo
- Se agrega el campo tipo en la asignacion de ubicaciones de un proyecto.
- Al crear un proyecto, se oculta la opcion tipo y se deja "encuesta" por default.
- En los pagos de una nueva tarea se muestra solo el pais Mexico.
- Se quita laopcion reconocimiento facial al crear una tarea.
- Se oculta el tipo de pregunta: codigo de barras.
- Se oculta el tipo de pregunta: captura INE.
- Se oculta el tipo de pregunta: fecha con rango.
- Se quita el tipo de encuesta "bienestar" y "call center".
- Se muestra la primera opcion de tipo de pregunta por default en el editor de encuestas.
- Se quita la validacion de llave de caja (por base de datos).
- Se agregan columnas de año, mes y dia en los reportes en lista (base de datos).

## [1.0.3] - 2018-05-04
### Nuevo
- Se agregan las llaves para el servicio de correo de AWS.

### Cambios
- Se homologa el nombre de la app de UPAXER a UPAX TRADE.
- Se deshabilitaron opciones del menu.
- Se modificaron las opciones de las listas de selección al crear proyectos y al crear usuarios.
- Se agregaron encabezados de codificacion para corregir caracteres especiales.
- Se cambia la lla ve del servicio de notificaciones push de firebase.

### Eliminado
- Se quita del flujo de proyectos la creación de cotizaciones.

## [1.0.1] - 2018-04-25
### Nuevo
- Se agrega un tag en cada archivo .jsp para mostrar el contenido codificado en utf-8.
- Se aplica nuevo tema al editor de encuestas.

### Cambios
- Se ajustaron los textos con acentos remplazando los caracteres no reconocidos.

### Eliminado
-
