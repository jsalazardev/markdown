# Changelog
El siguiente documento contiene el control de cambios que la aplicación ha tenido,  
sirve como apoyo a los desarrolladores y colaboradores del sistema.

Visita nuestro sitio administrativo [Upaxer](https://administrador.upaxer.com/).

### [2.13.7] - 2018-10-02
### Merge
#### Calidad Activo - Plan de comunicacion
- Se realiza el merge de los modulos Calidad Activo - Plan de comunicacion.

### [2.13.6] - 2018-09-25
### Changed
#### Plan de comunicacion
- Cambio en titulo de módulo

### [2.13.5] - 2018-09-25
### add
#### Plan de comunicacion
- Validaciones de notificaciones al enviar directas.

### [2.13.4] - 2018-09-24
### add
#### Plan de comunicacion
- Funcionalidad cuando los mensajes se evian correctamente.

### [2.13.3] - 2018-09-21
### Changed
#### Plan de comunicacion
- Adición de validaciones en formulario de Administrador de campaña

### [2.13.2] - 2018-09-21
### Changed
#### Plan de comunicacion
- Se realzia el cambio de URL de push notification.

### [2.13.1] - 2018-09-21
### Bug
#### Plan de comunicacion
- Se realiza la modificacion para intercambio de entidades entre vistas de
  usuarios que se envian notificacion.

### [2.13.0] - 2018-09-20
### Add
#### Plan de comunicacion
- Se agrega nuevo modulo para el envio de notifiaciones.

***

### [2.12.11] - 2018-10-02
### Add
#### Calidad Activo Fijo
- Paginacion para los activos.

### [2.12.10] - 2018-09-19
### Add
#### Calidad Activo Fijo
- Campos Raz y Motivo Baja para Auditoria Calidad.
- Avance Algoritmo para sustituir storeds con tabs.

### [2.12.9] - 2018-09-19
### Add
#### Asignaciones Activo Fijo
- Se ingresa nueva columna FIIDRAZ para activo fijo.

### [2.12.8] - 2018-09-17
### Changed
#### Asignaciones Activo Fijo
- Validadciones de los estatus para la descarga de excel.
- Genera la tarea con el idInventario en cero y ocultar boton inventario

### [2.12.7] - 2018-09-17
### Changed
#### Calidad Activo Fijo
- Se acomodan las reauditorias en 2 columnas.
- Sólo se presentan los activos con preguntas por rehacer en las reauditorías

### [2.12.6] - 2018-09-16
### Changed
#### Calidad Activo Fijo
- Se realiza mejora para realizar fulo de rehacer preguntas.

### [2.12.5] - 2018-09-16
### Changed
#### Calidad Activo Fijo
- Se integra firebase a modulo de reauditar.

### [2.12.4] - 2018-09-16
### Changed
#### Calidad Activo Fijo
- Se cargan por valor y no por índice Marca, Modelo y Denominación.
- Confirmar Auditoria por Detalles Tarea y por Asignaciones.
- Alternar filtros de activos y empleados.
- Inhibir edición para coordinador.
- Model para Confirmar Auditoria antes del proceso.
- Colocar los botones de aceptar a la derecha y cancelar a la izquierda.

### [2.12.3] - 2018-09-15
### Add
#### Calidad Activo Fijo
- Se integra el modulo de auditoria de activo fijo.
- Modulo para auditar, rechazar, rehacer

### [2.12.2] - 2018-09-14
### Add
#### Reporte Activo Fijo
- Se agrega el reporte de activo fijo

### [2.12.1] - 2018-09-14
### Changed
#### Activo Fijo
- Se hace el cambio de tipo de tarea de inventarios de activo fijo.
- Se descrimina las tareas de tipo 2 para la asignacion por zonas (Cambio front).

### [2.12.0] - 2018-09-12
### Add
#### Activo Fijo
- Se agrega modulo activo fijo.
- Se agrega nuevo tipo de proyecto llamado activo fijo.
- Se agrega nueva tipo de tarea llamado activo fijo.
- Las asignaciones (Directa y Programada) soporta las tareas de tipo activo fijo.
- La carga de asignaciones por excel soportan tarea activo fijo.

***

### [2.11.11] - 2018-09-20
### Bug
#### Calidad Mystery Shopper
- Se integra validacion para coordenadas de calidad.

### [2.11.10] - 2018-09-19
### Bug
#### Franquicia
- Se agrega mejora para el alcance de graficas.
- Se incorpora filtros por dashboard.

### [2.11.9] - 2018-09-18
### Bug
#### Asignacion
- Se remueve el valor hardcode para eliminar asignaciones.
    
### [2.11.8] - 2018-09-18
### Bug
#### Calidad Mystery Shopper
- Se agrega validacion para coordenadas, recuperandola en caso de no existir
    en el XML que se registra en base.

### [2.11.7] - 2018-09-14
### Bug
#### Franquicia
- Se corrigue la grafica de avance y el efecto recursivo de emotions.

### [2.11.6] - 2018-09-03
### Bug
#### Franquicia
- Se remueven datos dummy, se agrega mejoras de objetivo por grafica.

### [2.11.5] - 2018-09-03
### Bug
#### Franquicia
- Se corrigen temas de base de datos eliminando Merge y Taf

### [2.11.4] - 2018-09-03
### Add
#### Tarea
- Se agrega columna Imagen Miniatura para tareas uber.

### [2.11.3] - 2018-09-03
### Bug
#### Franquicia
- Se repara la descarga de archivos excel que contiene las fuentes de datos.

### [2.11.2] - 2018-08-30
### Changed
#### Dashboard AT&T
- Se agregan cambios al dashboard para integrar en nuevo Q.

### [2.11.1] - 2018-08-24
### Changed
#### Franquicia
- Se realiza la modificación de la base formulada al boton correcto.

### [2.11.0] - 2018-08-24
### Add
#### Franquicia
- Se agrega nuevo modulo dashboard franquicia.

***

### [2.10.11] - 2018-08-23
### Bug
#### Proyectos Ubicacion
- Se corrige el alta de ubicacion por canal.

### [2.10.10] - 2018-08-21
### Bug
#### Fabrica de videos
- Se corrige el checkbox de fábrica de vídeos en la edición de proyecto

### [2.10.9] - 2018-08-20
### Changed
#### Fabrica de videos
- Se agrega  módulo **Fabrica de videos**.
- Se implementa nueva funcionalidad para la asignación de gestores para **Fabrica de videos**.

#### Dashboard Genérico
- Se remueven los decimales en la grafica **Alcances por ubicación**.

#### Emotions
- Se cambia URL del iframe para que el inicio de sesión sea automatico.

### Add
#### Aclaracion Pagos
- Se agrega modulo para call center que te permite ver los pagos realizados por Upaxer.

### [2.10.3] - 2018-08-02
### Changed
#### Cotización
- Utilizar el mismo folio de **project** en varios proyectos.
- Clonar datos de una **cotización** anterior para crear una nueva.

#### KPIS
- Se agrega el estado **aceptado con modificaciones sin pago** para calidad.
- Se agregan mejoras gráficas para la interfaz.

### Fixed
#### Proyecto Ubicación
- Se agrega filtro de **canal**.
- Se agrega mejora para el manejo de las ubicaciones.
