# Propuesta TP DSW

## Grupo

### Integrantes

- 48881 - Calderon, Bruno
- 51392 - Rallip Sanchez, Ismael

### Repositorios

_Aclaracion_: La segunda entrega correspondiente al 24/5 se encuentra subida en su totalidad en la seccion de backend

- frontend app [in progress...]
- [backend app](https://github.com/ismaelrallip/TPdsw.git)

## Tema

### Descripción

Un sistema de gestion de tareas personales estilo Notion, las cuales se clasificaran entre tareas de estudio, trabajo y vida personal. El usuario podra registrar, consultar, modificar, borrar y darles un seguimiento a estas tareas y a las subtareas de las cuales estas se compondran. A su vez cada tarea y subtarea se mostrara clasificada segun el nivel de importancia y urgencia que esta misma tenga.

### Modelo

![Diagrama de clases](Modelo/Diagrama.png)

## Alcance Funcional

_Aclaracion_: Todo el resto de la propuesta a continuacion lo dejamos igual sin ningun cambio debido a que se nos diron de baja dos integrantes por lo que resultara probable que tengamos que reveer el alcance de nuestro proyecto.

### Alcance Mínimo

_Nota_: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel.

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|

Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|

### Alcance Adicional Voluntario

_Nota_: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

| Req      | Detalle                                                                                                                                                                                                             |
| :------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Listados | 1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes |
| CUU/Epic | 1. Consumir servicios<br>2. Cancelación de reserva                                                                                                                                                                  |
| Otros    | 1. Envío de recordatorio de reserva por email                                                                                                                                                                       |
