# Boards

Componente de Azure que gestiona el ALM (Gestión de Flujos que se encuentran en el proyecto)

Se organiza a través de:
  - WorkItems: Items de Trabajo, componente.
    - Bug, Epic, Feature, Impediment, ProductBacklog, Task, Test Care.
    - EPIC: Tarea principal. Ej: Módulo de Pagos.
    - FEATURE: Característica asociada al EPIC. Ej: Realizar Pago.
    - BACKLOGS: Crear pequeños módulos de la Feature. Ej: Crear API para integrar los Pagos recibidos.
    - TASK: Tareas más pequeñas del Backlog. Ej: Generar método para Obtener Usuario. *Tareas que se puedan realizar en un día*.
  - Boards: Vistas por Workitems, Backlogs o Item. Permite administrar como Dashboard y establecer las finalizaciones de los items.
  - Backlogs: PBI dentro del Sprint, se pueden agregar tareas. Permite analítica del estado del trabajo.
  - Sprint: Visualización del proceso por sprint(Periodo de Tiempo estimado del proyecto), Visual general.
  - Queries: Consultas para obtener el estado del proyecto. Tareas.
  
## Creación Proyecto
- Epi: Creación de la tienda de ropa.
- Feature: App movil.
- Feature: App Web.
- Feature: Api rest.
- Backlog: Creacion SQL, Creacion Autenticación, Creación Estructura, etc.
- Task: Tareas puntuales asociadas: Crear Entidades SQl, Crear Relaciones, Cargar Datos Iniciales.

Se manejan estados dentro de cada sprint; New (Tarea asignada), Active (Tarea en proceso de elaboración), Resolver (Equipo finalizó su fase), Closed (Se realizó el despliegue a producción).

La vista de Sprint tiene cuatro vistas:
- Taskboard: Donde se ve todo el panel de las tareas.
- Backlog: Vista de Backlog y sus tareas asociadas (Vista más estructurada como lista).
- Capacity: Permite asignar el esfuerzo que tiene determinado recurso en un sprint.
- Analytics: Permite ver todas las métricas por usuarios, equipos, etc.

# Repos
Permite almacenar el código generado y ser cargado de diferentes formas. Funciona igual que github.

# Pipelines

# Test Plans

# Artifacts 
