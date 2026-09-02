## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

En esta sección se presenta el Design-Level EventStorming del proyecto Tourmate, el cúal se desarrollo en 4 pasos, los cúales se van a explicar a continuación:

* Para empezar, identificamos todos los Domain Events de Tourmate. En esta etapa analizamos cada funcionalidad obtenida durante el análisis del negocio y registramos todos los eventos importantes que modifican el estado del sistema, como el registro de usuarios, la creación de tours, el inicio de recorridos, el reporte de incidentes o la generación de reportes:

![Event Storming](assets/images/Design-Level-EventStorming-1.jpg)

* Luego, procedimos a organizar los Domain Events, eliminando los eventos repetidos, agrupamos aquellos que pertenecían al mismo flujo de negocio y ordenamos la secuencia lógica de cada proceso. Este refinamiento permitió obtener una visión más clara de los distintos procesos que forman parte de Tourmate antes de incorporar elementos adicionales del modelo:

![Event Storming](assets/images/Design-Level-EventStorming-2.jpg)

* Después de esto, comenzamos a construir cada flujo funcional. Para cada Domain Event identificamos el comando que lo desencadena, representado por notas azules. Además, agregamos los actores responsables de ejecutar cada comando mediante notas amarillas y las políticas representadas en color morado, las cuales automatizan determinadas acciones cuando ocurre un evento. De esta manera logramos modelar el comportamiento completo de cada proceso de negocio:

![Event Storming](assets/images/Design-Level-EventStorming-3.jpg)

* Finalmente, integramos todos los flujos individuales en un único modelo del dominio:

![Event Storming](assets/images/Design-Level-EventStorming-4.jpg)

Versión completa del Design-Level EventStorming:

![Event Storming](assets/images/Design-Level-EventStorming.jpg)

Enlace para acceder al:
https://miro.com/app/board/uXjVHcmAuSg=/

### 4.6.2. Software Architecture Context Diagram

![ContexDiagram](assets/images/contex-diagram.png)

### 4.6.3. Software Architecture Container Diagrams

![ContainerDiagram](assets/images/container-diagram.png)

### 4.6.4. Software Architecture Components Diagrams

![ComponentDiagram](assets/images/component-diagram.png)
