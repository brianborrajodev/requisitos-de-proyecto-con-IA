# StudyFlow: requisitos del Producto Mínimo Viable

Este documento especifica el comportamiento verificable de las tres capacidades incluidas en el alcance del MVP descrito en `planificador-mvp.md`.

## Requisitos funcionales y criterios de aceptación

### RF-1. Crear tareas
- Se pueden registrar el nombre de la tarea, la asignatura y la fecha de entrega.
- No se guarda la tarea si falta alguno de estos datos y se indica cuál debe completarse.
- Al guardar una tarea válida, aparece en la lista de tareas pendientes.

### RF-2. Consultar tareas pendientes
- La lista muestra las tareas no completadas y excluye las completadas.
- Las tareas se ordenan por fecha de entrega ascendente, con la fecha más próxima primero.
- Si no hay tareas pendientes, se muestra un estado vacío claro.

### RF-3. Marcar tareas como completadas
- Cada tarea pendiente permite cambiar su estado a completada.
- Al completarla, deja de aparecer en la lista de tareas pendientes.

## Suposiciones
- El MVP es para una persona que utiliza un solo dispositivo.
- La fecha de entrega es una fecha de calendario, sin hora.
- Las tareas vencidas siguen siendo pendientes y se ordenan antes que las futuras.
- No se requieren cuentas ni sincronización entre dispositivos.


## Alcance del MVP

La primera versión de StudyFlow incluirá únicamente la creación de tareas, la consulta de tareas pendientes y la posibilidad de marcarlas como completadas.

Quedan fuera del alcance las notificaciones automáticas, la sincronización con calendarios externos, las cuentas de usuario y las funciones de inteligencia artificial integradas en la aplicación.

## Métrica de éxito

En una prueba con cinco estudiantes, al menos cuatro deberán completar sin ayuda el flujo completo: registrar una tarea, localizarla en la lista ordenada y marcarla como completada.

Se considera que un estudiante completa el flujo sin ayuda si no recibe instrucciones ni pistas durante la prueba.

## Estado del documento

Documento inicial de requisitos del MVP, pendiente de validación mediante pruebas con usuarios.