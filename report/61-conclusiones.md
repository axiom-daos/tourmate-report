## Conclusiones

### Sprint 1 – Landing Page y documentación del proyecto

- **Sobre el análisis del problema y la investigación del usuario:** Se concluye que las entrevistas realizadas a dueños de agencias de tours y turistas de aventura permitieron identificar necesidades, expectativas y puntos de dolor relevantes para el desarrollo de SpotGo. La información recopilada fue fundamental para la definición de *User Personas*, *Empathy Maps* y *Journey Maps*, los cuales sirvieron como base para la priorización de funcionalidades y la elaboración del *Problem Statement*.

- **Sobre la propuesta de valor y validación inicial:** La elaboración de la *Landing Page* permitió comunicar de forma clara los objetivos, beneficios y funcionalidades principales de TourMate, funcionando como un medio de validación temprana de la idea de negocio. Se evidenció que presentar una interfaz informativa y accesible favorece la comprensión del problema y fortalece el interés de potenciales usuarios y clientes B2B.

- **Sobre la documentación y modelado del proyecto:** La construcción del reporte técnico permitió consolidar los hallazgos del *Problem Statement*, *Needfinding*, *User Personas*, *Empathy Maps*, *Journey Maps*, *Event Storming* y *Ubiquitous Language*, generando una visión integral del dominio del negocio. Asimismo, el uso de metodologías como *Domain-Driven Design (DDD)* facilitó la identificación de *Bounded Contexts* y responsabilidades del sistema desde etapas tempranas.

- **Sobre la definición de requerimientos:** La especificación inicial de *User Stories* y criterios de aceptación permitió transformar necesidades de usuarios en funcionalidades concretas, proporcionando una guía estructurada para el desarrollo de los siguientes sprints y reduciendo ambigüedades en la planificación técnica.

### Sprint 2 – Web Application Frontend y Servicios Mock

- **Sobre la arquitectura Single Page Application (SPA) en Angular:** La adopción de Angular 19 con componentes independientes (*Standalone Components*), señales reactivas (*Angular Signals*) e inyección de dependencias moderna permitió estructurar una aplicación altamente modular, desacoplada y mantenible. La separación por capas (dominio, aplicación, infraestructura y presentación) en cada *Bounded Context* garantizó que las reglas de negocio del frontend permanecieran independientes de los mecanismos de transporte HTTP.

- **Sobre la estrategia de desacoplamiento con MockAPI:** El uso de servicios simulados en la nube (*MockAPI.io*) durante la etapa intermedia de desarrollo posibilitó avanzar en la construcción de interfaces de usuario complejas y flujos interactivos (tales como la gestión de planes, el dashboard de suscripciones y el monitoreo en vivo) sin bloquearse por la disponibilidad inmediata de los servicios backend, validando la lógica de presentación de forma temprana.

- **Sobre la experiencia de usuario y accesibilidad:** La implementación de un sistema de diseño consistente con Angular Material, complementado con internacionalización dinámica (*ngx-translate*) en inglés y español y diseño responsivo adaptativo, mejoró significativamente la usabilidad de la plataforma tanto en dispositivos de escritorio para las agencias como en pantallas móviles para guías y turistas.

### Sprint 3 – Backend RESTful, Arquitectura DDD y Validación Heurística

- **Sobre la arquitectura orientada al dominio (DDD) y CQRS en Spring Boot:** La implementación del backend con Spring Boot 3 y Java 21 bajo los patrones de *Domain-Driven Design* y la segregación de responsabilidades de comando y consulta (*CQRS*) demostró ser altamente eficaz para modelar la complejidad del negocio. La encapsulación de la lógica en Agregados, Entidades y *Value Objects* inmutables garantizó la consistencia de los datos y simplificó la trazabilidad de operaciones críticas como el procesamiento de pagos, el control de expediciones activas y el reporte de incidentes.

- **Sobre la persistencia relacional con PostgreSQL y JPA/Hibernate:** La integración de Spring Data JPA con PostgreSQL proporcionó una capa de persistencia robusta y escalable. El uso de convertidores JPA personalizados y ensambladores de persistencia evitó la fuga de modelos relacionales hacia el dominio, asegurando transacciones atómicas y facilitando la inicialización del sistema mediante seeders automáticos.

- **Sobre la estandarización de contratos y documentación OpenAPI:** La adopción rigurosa de OpenAPI 3.0 / Swagger UI permitió formalizar los contratos de comunicación entre el frontend y el backend, reduciendo la fricción durante la integración. Asimismo, la configuración de deserialización resiliente en Jackson y el esquema de seguridad basado en tokens JWT (`bearerAuth`) consolidaron una plataforma segura y preparada para entornos productivos.

- **Sobre la validación empírica y evaluación heurística:** Las entrevistas de validación realizadas a usuarios reales y la posterior evaluación según las 10 Heurísticas de Nielsen permitieron contrastar las hipótesis iniciales de diseño frente a la realidad operativa del turismo de aventura. Los hallazgos obtenidos evidenciaron fortalezas en la claridad del monitoreo en vivo y la gestión de planes, así como áreas puntuales de optimización en retroalimentación de errores y simplificación visual de bitácoras de campo.

### Conclusiones y Recomendaciones Generales

- **Coordinación y sincronización de contratos tempranos:** Como lección aprendida fundamental para futuras entregas, se recomienda formalizar los contratos de datos (DTOs) en las fases iniciales del sprint mediante especificaciones *API-First*, reduciendo el esfuerzo de homologación y permitiendo una integración continua más fluida entre los desarrolladores de frontend y backend.
- **Evolución hacia microservicios y telemetría en tiempo real:** Se recomienda que las futuras versiones de TourMate incorporen comunicación bidireccional vía WebSockets o Server-Sent Events (SSE) para el monitoreo de ubicación en vivo y la recepción inmediata de alertas críticas de seguridad, así como la paquetización de cada *Bounded Context* en contenedores Docker independientes orquestados en la nube.

### Bibliografía

- Brown, S. (2020). *The C4 model for visualising software architecture*. C4Model.com. Recuperado de [https://c4model.com](https://c4model.com)
- Driessen, V. (2010). *A successful Git branching model*. Nvie. Recuperado de [https://nvie.com/posts/a-successful-git-branching-model](https://nvie.com/posts/a-successful-git-branching-model)
- Evans, E. (2003). *Domain-Driven Design: Tackling Complexity in the Heart of Software*. Addison-Wesley Professional. Recuperado de [https://www.domainlanguage.com/ddd](https://www.domainlanguage.com/ddd)
- Freeman, A. (2022). *Pro Angular 16*. Apress. Recuperado de [https://link.springer.com/book/10.1007/978-1-4842-8823-8](https://link.springer.com/book/10.1007/978-1-4842-8823-8)
- Newman, S. (2021). *Building Microservices: Designing Fine-Grained Systems* (2nd ed.). O'Reilly Media. Recuperado de [https://samnewman.io/books/building_microservices_2nd_edition](https://samnewman.io/books/building_microservices_2nd_edition)
- Walls, C. (2022). *Spring in Action* (6th ed.). Manning Publications. Recuperado de [https://www.manning.com/books/spring-in-action-sixth-edition](https://www.manning.com/books/spring-in-action-sixth-edition)
