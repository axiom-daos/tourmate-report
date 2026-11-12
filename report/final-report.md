<div style="font-size: 16px; line-height: 1.65;">

<br/>
<div align="center">
  <img src="../assets/images/upc-logoo.png" alt="UPC Logo" width="80">
</div>
<br/>
<h2 align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></h2>
<h2 align="center"><strong>Carrera de Ingeniería de Software</strong></h2>

<h2 align="center"><strong>1ASI0729</strong></h2>
<h2 align="center"><strong>Desarrollo de Aplicaciones Open Source</strong></h2>
<h2 align="center">NRC</h2>
<h2 align="center"><strong>7760</strong></h2>
<h2 align="center"><strong>Informe del Trabajo Final</strong></h2>
<h2 align="center">Docente</h2>
<h2 align="center"><strong>Flores Moroco, Juan Antonio</strong></h2>
<h2 align="center">Equipo</h2>
<h2 align="center"><strong>Axiom</strong></h2>
<h2 align="center">Proyecto</h2>
<h2 align="center"><strong>TourMate</strong></h2>

<h2 align="center"><strong>Integrantes:</strong></h2>

<table align="center" style="width: auto; margin: 0 auto;">
<tr>
<td>

| Código      | Nombre                               |
|:-----------:|:-------------------------------------|
| U202323010  | Carrillo Acho, Matias Renato         |
| U202319057  | Huingo Tello, Frank Anthony          |
| U20241F714  | Quispe Palomino, Tony Jhunior        |
| U202419483  | Verastigue Martinez, Giancarlo Jose  |
| U20221G231  | Molina Vasquez, Manuel Alejandro     |

</td>
</tr>
</table>

<h2 align="center"><strong>Período 202620</strong></h2>
<h2 align="center"><strong>Noviembre 2026</strong></h2>

<div style="page-break-before: always;"></div>

</div>

---
# Registro de versiones del informe

| Versión |   Fecha    |                Autor                | Descripción de modificación                                                           |
| :-----: | :--------: | :---------------------------------: | ------------------------------------------------------------------------------------- |
|   1.0   | 08/09/2026 | Verastigue Martinez, Giancarlo Jose | Creación y estructuración del documento de trabajo en formato markdown               |
|   1.0   | 10/09/2026 | Quispe Palomino, Tony Jhunior       | Desarrollo de los capítulos I y II                                                    |
|   1.0   | 10/09/2026 | Huingo Tello, Frank Anthony         | Desarrollo de los capítulos III y IV                                                  |
|   1.0   | 10/09/2026 | Molina Vasquez, Manuel Alejandro    | Desarrollo del capítulo IV                                                            |
|   1.0   | 10/09/2026 | Carrillo Acho, Matias Renato        | Desarrollo del capítulo IV                                                            |
|   1.0   | 10/09/2026 | Verastigue Martinez, Giancarlo Jose | Desarrollo del capítulo V                                                             |
|   2.0   | 06/10/2026 | Verastigue Martinez, Giancarlo Jose | Desarrollo del Sprint 2, landing page (sección planes) y configuración SCM en GitHub  |
|   2.0   | 06/10/2026 | Quispe Palomino, Tony Jhunior       | Refinamiento de Product Backlog, Big Picture EventStorming y User Stories Sprint 2     |
|   2.0   | 06/10/2026 | Huingo Tello, Frank Anthony         | Actualización de arquitectura de software, diagramas de contexto y Student Outcome TB1|
|   2.0   | 06/10/2026 | Molina Vasquez, Manuel Alejandro    | Documentación del modelo de incidentes, protocolos de emergencia y archivos i18n     |
|   2.0   | 06/10/2026 | Carrillo Acho, Matias Renato        | Documentación de interfaces de usuario, mockups y contratos para tours en Angular     |
|   3.0   | 10/11/2026 | Verastigue Martinez, Giancarlo Jose | Bounded Context Active Tours & Profiles, diagramas de clases y evaluación heurística  |
|   3.0   | 10/11/2026 | Quispe Palomino, Tony Jhunior       | Bounded Context Feedback & Reviews, controladores RESTful y entrevistas de validación |
|   3.0   | 10/11/2026 | Huingo Tello, Frank Anthony         | Bounded Context Subscriptions & Payments con CQRS, video About-the-Product y Student Outcome AV2 |
|   3.0   | 10/11/2026 | Molina Vasquez, Manuel Alejandro    | Bounded Context Safety & Incidents, endpoints REST y análisis de métricas de calidad  |
|   3.0   | 10/11/2026 | Carrillo Acho, Matias Renato        | Bounded Context Tour Management, Docker Compose (`compose.yaml`) y Sprint Review 3    |


# Project Report Collaboration Insights

- URL del repositorio para el reporte del proyecto: https://github.com/axiom-daos/tourmate-report
- URL del repositorio para la Landing Page: https://github.com/axiom-daos/tourmate-landing



**AV1**

Para el desarrollo del informe perteneciente a la entrega AV1, se dividió la implementación de secciones de la siguiente forma para cada integrante del equipo:



<div align="center">

| Integrante       | Tareas Asignadas                                                                                                                                                                           |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Quispe Palomino, Tony Jhunior | Desarrollo del Capítulo I y del Capítulo II en formato markdown.                                                             |
| Huingo Tello, Frank Anthony     | Desarrollo del Capítulo III, parte del capítulo IV en formato markdown.                                                  |
| Molina Vasquez, Manuel Alejandro      | Desarrollo del Capítulo IV enfocado en desarrollo de UX/UI Design.                                                                               |
| Carrillo Acho, Matias Renato  | Desarrollo del Capítulo IV enfocado en system design, así como colaboración en el capítulo V del documento en formato markdown.                                                                               |
| Verastigue Martinez, Giancarlo Jose  | Desarrollo del Capítulo V, despliegue de Landing Page |

</div>

El trabajo se desarrolló mediante commits continuos en el repositorio de la organización, asegurando trazabilidad y colaboración activa del equipo.

*Report Insights AV1*
![insigths-report-av1](../assets/images/commits-report1.png)

*Report Insights AV2*
![insigths-report-av2](../assets/images/commits-report2.png)

---

# Contenido
# Tabla de Contenido 
## Student Outcome

## Capítulo I: Introducción
### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup
#### 1.1.2. Perfiles de integrantes del equipo
### 1.2. Solution Profile
#### 1.2.1 Antecedentes y problemática
#### 1.2.2 Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
##### 1.2.2.2. Lean UX Assumptions
##### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.4. Lean UX Canvas
### 1.3. Segmentos objetivo

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores
#### 2.1.1. Análisis competitivo
#### 2.1.2. Estrategias y tácticas frente a competidores
### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
#### 2.2.2. Registro de entrevistas
#### 2.2.3. Análisis de entrevistas
### 2.3. Needfinding
#### 2.3.1. User Personas
#### 2.3.2. User Task Matrix
#### 2.3.3. User Journey Mapping
#### 2.3.4. Empathy Mapping
### 2.4. Big Picture EventStorming
### 2.5. Ubiquitous Language

## Capítulo III: Requirements Specification
### 3.1. User Stories
### 3.2. Impact Mapping
### 3.3. Product Backlog

## Capítulo IV: Product Design
### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines
#### 4.1.2. Web Style Guidelines
### 4.2. Information Architecture
#### 4.2.1. Organization Systems
#### 4.2.2. Labeling Systems
#### 4.2.3. SEO Tags and Meta Tags
#### 4.2.4. Searching Systems
#### 4.2.5. Navigation Systems
### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
#### 4.3.2. Landing Page Mock-up
### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.4. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Design-Level EventStorming
#### 4.6.2. Software Architecture Context Diagram
#### 4.6.3. Software Architecture Container Diagrams
#### 4.6.4. Software Architecture Components Diagrams
### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
##### 4.7.1.1. Bounded Context: Shared Kernel
##### 4.7.1.2. Bounded Context: Identity and Access Management
##### 4.7.1.3. Bounded Context: Tour Management
##### 4.7.1.4. Bounded Context: Tour Monitoring
##### 4.7.1.5. Bounded Context: Safety and Incident Management
##### 4.7.1.6. Bounded Context: Feedback and Tour Reviews
##### 4.7.1.7. Bounded Context: Subscriptions and Payment Management
### 4.8. Database Design
#### 4.8.1. Database Diagrams

## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration
### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint n
##### 5.2.X.1. Sprint Planning n
##### 5.2.X.2. Aspect Leaders and Collaborators
##### 5.2.X.3. Sprint Backlog n
##### 5.2.X.4. Development Evidence for Sprint Review
##### 5.2.X.5. Execution Evidence for Sprint Review
##### 5.2.X.6. Services Documentation Evidence for Sprint Review
##### 5.2.X.7. Software Deployment Evidence for Sprint Review
##### 5.2.X.8. Team Collaboration Insights during Sprint
### 5.3. Validation Interviews
#### 5.3.1. Diseño de Entrevistas
#### 5.3.2. Registro de Entrevistas
#### 5.3.3. Evaluaciones según heurísticas
### 5.4. Video About-the-Product

## Conclusiones
### Conclusiones y recomendaciones
#### Sprint 1 – Landing Page y documentación del proyecto
#### Sprint 2 – Web Application Frontend y Servicios Mock
#### Sprint 3 – Backend RESTful, Arquitectura DDD y Validación Heurística

### Bibliografía
### Anexos

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET - EAC - Student Outcome 3,  capacidad de comunicarse efectivamente con un
rango de audiencias. .


| Criterio específico | Acciones realizadas | Conclusiones | 
| --- | --- | --- |
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | **Carrillo Acho, Matias Renato (U202323010)**<br>**AV1:** Práctica de modulación de voz y control de tiempos durante ensayos grupales, lo que permitió desarrollar la habilidad de exponer la problemática del negocio de manera persuasiva ante una audiencia evaluadora.<br><br>**TB1:** Exposición técnica en el Sprint Review sobre la gestión de tours y el nuevo sidebar de navegación, adecuando el lenguaje para explicar flujos funcionales al equipo y valor operativo a usuarios no técnicos.<br><br>**AV2:** Sustentación técnica durante el Sprint Review 3 de la arquitectura de backend para el Bounded Context de Tours y la contenerización con Docker Compose (`compose.yaml`), comunicando con solvencia la portabilidad y escalabilidad de los microservicios tanto a evaluadores académicos como a miembros del equipo de desarrollo.<br><br>**Huingo Tello, Frank Anthony (U202319057)**<br>**AV1:** Organización y esquematización de las ideas clave mediante mapas mentales antes de la exposición, mejorando la articulación verbal para explicar decisiones de diseño a un público no técnico.<br><br>**TB1:** Sustentación del flujo de suscripciones y pagos durante las reuniones de sincronización, logrando comunicar con claridad tanto los estados reactivos al equipo técnico como el modelo de planes a la audiencia evaluadora.<br><br>**AV2:** Exposición técnica en el Sprint Review 3 sobre la implementación del flujo transaccional de suscripciones y pagos con CQRS en Spring Boot 3, explicando de manera clara y didáctica las transiciones de estado de cobro, la persistencia en PostgreSQL y los beneficios del comprobante fiscal ante el jurado y compañeros de equipo.<br><br>**Quispe Palomino, Tony Jhunior (U20241F714)**<br>**AV1:** Recepción y aplicación de feedback de los compañeros sobre claridad del discurso, mejorando su capacity asertiva en la comunicación oral de los resultados de las entrevistas y el Needfinding.<br><br>**TB1:** Demostración oral del módulo de calificaciones y feedback en los ensayos de equipo, transmitiendo con tono claro y estructurado el impacto de las reseñas turísticas para audiencias técnicas y de negocio.<br><br>**AV2:** Fortalecimiento de las habilidades de comunicación oral mediante la explicación y demostración de las funcionalidades desarrolladas en TourMate, especialmente del Bounded Context *Feedback and Tour Reviews*. Se practicó la presentación de los procesos de gestión de reseñas y comentarios, su interacción entre componentes de frontend en Angular y controladores RESTful en Spring Boot, la persistencia en PostgreSQL y la verificación funcional mediante Swagger UI. Asimismo, se preparó y ejecutó el guion de entrevista de validación dirigido a representantes de agencias de turismo de aventura, adaptando el lenguaje técnico para facilitar la comprensión y recopilación de retroalimentación de los usuarios.<br><br>**Verastigue Martinez, Giancarlo Jose (U202419483)**<br>**AV1:** Ejercicios de adaptación de terminología técnica para lograr explicar conceptos complejos de la arquitectura de software (DDD, C4) a diferentes tipos de stakeholders sin perder el rigor técnico en el discurso oral.<br><br>**TB1:** Liderazgo en la presentación oral del Sprint 2 y monitoreo de tours, articulando de forma dinámica los avances del despliegue y la arquitectura del sistema tanto a evaluadores como a compañeros.<br><br>**AV2:** Demostración en vivo del monitoreo en tiempo real de expediciones activas y visualización de perfiles de usuario, articulando fluidamente las capacidades de geolocalización y sincronización de datos para transmitir el valor de seguridad operativa ante una audiencia diversa de stakeholders y evaluadores.<br><br>**Molina Vasquez, Manuel Alejandro (U20221G231)**<br>**AV1:** Simulaciones de presentación frente al grupo, desarrollando la capacidad de comunicar oralmente decisiones visuales o de UX mediante argumentos estructurados orientados a las necesidades del usuario.<br><br>**TB1:** Presentación guiada del módulo de incidentes y seguridad durante el Sprint Review, facilitando la comprensión de protocolos de emergencia y estados críticos mediante explicaciones directas y empáticas ante diferentes perfiles.<br><br>**AV2:** Sustentación oral de la arquitectura de monitoreo de incidentes y protocolos de auxilio turístico en el Sprint Review 3, comunicando con tono formal y estructurado la jerarquía de severidad de riesgos y los flujos de contingencia tanto para perfiles de rescate como para administradores del sistema. | **AV1:** El equipo ejerció liderazgo conjunto al coordinar responsabilidades y tomar decisiones colaborativas, permitiendo organizar el primer entregable y alinear TourMate con las necesidades de los usuarios.<br><br>**TB1:** El equipo consolidó una comunicación oral articulada durante las revisiones del Sprint 2, demostrando destreza para alternar explicaciones técnicas del código con demostraciones funcionales de cara al usuario.<br><br>**AV2:** Durante el Sprint Review 3, el equipo demostró un elevado nivel de madurez y versatilidad comunicativa, logrando alternar con soltura entre el rigor técnico (patrones DDD, CQRS, Docker y especificaciones OpenAPI 3.0) y la presentación de valor de negocio orientada a la experiencia de usuario y seguridad turística ante el jurado evaluador. |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | **Carrillo Acho, Matias Renato (U202323010)**<br>**AV1:** Aplicación de iteraciones de revisión de textos para depurar inconsistencias, desarrollando así la capacidad de redactar de forma estructurada, técnica y sin ambigüedades en la sección introductoria.<br><br>**TB1:** Redacción formal de contratos de servicios e interfaces para la gestión de tours en el informe, asegurando consistencia en la documentación de endpoints y claridad técnica para los desarrolladores.<br><br>**AV2:** Formalización técnica por escrito de los contratos RESTful y esquemas OpenAPI 3.0 para `ToursController`, redactando además la guía de configuración y despliegue local mediante Docker Compose con explicaciones paso a paso legibles para cualquier integrante del equipo de desarrollo.<br><br>**Huingo Tello, Frank Anthony (U202319057)**<br>**AV1:** Estudio y aplicación de buenas prácticas de redacción técnica para documentar artefactos (como modelos de datos), afinando la habilidad de escribir descripciones exactas y claras para públicos técnicos.<br><br>**TB1:** Elaboración de especificaciones técnicas detalladas para el bounded context de suscripciones y pagos, redactando historias de usuario con criterios Gherkin y contratos de API comprensibles para perfiles técnicos y de negocio.<br><br>**AV2:** Redacción rigurosa de las especificaciones de API para el módulo de suscripciones y pagos, esquemas de DTOs y validaciones Swagger UI, así como el diseño del guion técnico y storyboard para el video About-the-Product y la consolidación integral del reporte final bajo lineamientos académicos.<br><br>**Quispe Palomino, Tony Jhunior (U20241F714)**<br>**AV1:** Ejercicio de síntesis de la vasta información cualitativa obtenida de las entrevistas, perfeccionando la habilidad de transformar datos complejos en reportes ejecutivos escritos y de fácil comprensión.<br><br>**TB1:** Documentación y refinamiento del Product Backlog y Big Picture EventStorming en Markdown, estructurando requerimientos y eventos de dominio de forma comprensible para evaluadores y miembros del proyecto.<br><br>**AV2:** Desarrollo de habilidades de documentación técnica mediante la estructuración y descripción de las funcionalidades implementadas en el Bounded Context *Feedback and Tour Reviews*, incluyendo operaciones CRUD, reglas de negocio, validaciones e integración con PostgreSQL. Se verificó el correcto funcionamiento del backend mediante 58 pruebas automatizadas exitosas y se actualizaron las especificaciones de endpoints en Swagger al estándar en inglés. Adicionalmente, se elaboraron los instrumentos y el guion estructurado para las entrevistas de validación y la matriz de evaluación heurística de Nielsen, organizando la información de manera formal y comprensible tanto para públicos técnicos como del sector turístico.<br><br>**Verastigue Martinez, Giancarlo Jose (U202419483)**<br>**AV1:** Construcción y documentación en equipo del Lenguaje Ubicuo (EventStorming), lo que consolidó su capacidad para plasmar de forma escrita un lenguaje de negocio compartido entre perfiles técnicos y no técnicos.<br><br>**TB1:** Redacción técnica de las directrices del Sprint 2, configuración de software (SCM) y sección de planes en la landing page, garantizando documentación formal, clara y trazable en el repositorio.<br><br>**AV2:** Documentación técnica de los diagramas de clases tácticos bajo DDD para el Bounded Context de Active Tours & Profiles, redacción de especificaciones de contratos de datos para la geolocalización de expediciones y registro de hallazgos heurísticos en el informe.<br><br>**Molina Vasquez, Manuel Alejandro (U20221G231)**<br>**AV1:** Participación como revisor (proofreader) de la gramática y jerarquía de la información, practicando habilidades de control de calidad para garantizar que el entregable escrito cumpla con altos estándares formales.<br><br>**TB1:** Documentación escrita del modelo de incidentes y elaboración de archivos de traducción (i18n) para la plataforma, manteniendo rigor técnico y accesibilidad léxica en inglés y español para audiencias internacionales.<br><br>**AV2:** Elaboración y documentación escrita de los contratos de servicio para la gestión de incidentes y seguridad turística (`IncidentsController`), detallando códigos de estado HTTP, restricciones de validación en Swagger y manuales de respuesta a incidentes en la plataforma. | **AV1:** La planificación y el trabajo colaborativo permitieron cumplir los objetivos dentro del plazo establecido, manteniendo comunicación constante y orientación.<br><br>**TB1:** La estandarización documental en Markdown y la disciplina en los commits convencionales permitieron generar un reporte técnico coherente, facilitando la integración de los bounded contexts para la evaluación académica.<br><br>**AV2:** El equipo consolidó una cultura documental técnica homogénea y de alta calidad académica mediante el uso estandarizado de Markdown, contratos OpenAPI 3.0 interactivos y trazabilidad de commits semánticos, garantizando que el reporte del proyecto sea una guía clara, accesible y precisa tanto para evaluadores académicos como para futuros desarrolladores. |

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Axiom es una startup tecnológica enfocada en el desarrollo de soluciones para el turismo de aventura en el Perú, orientada a mejorar la seguridad, trazabilidad y gestión operativa en entornos de baja conectividad. Surge para cubrir la falta de sistemas que permitan el monitoreo en tiempo real de turistas en zonas remotas.

Su producto principal, TourMate, es una plataforma web y móvil que centraliza la gestión de tours, permitiendo a las agencias supervisar la ubicación, estado y progreso de sus grupos mediante dashboards y alertas ante anomalías. A su vez, los turistas acceden a herramientas de navegación offline, registro de su experiencia y visualización de información contextual del recorrido.

A nivel técnico, TourMate integra un ecosistema IoT con dispositivos wearables y checkpoints Bluetooth que capturan datos de geolocalización y signos vitales. Estos se sincronizan de forma asincrónica, asegurando operatividad incluso sin conexión continua, lo que permite un sistema escalable, resiliente y orientado a la prevención de riesgos.


### 1.1.2 Perfiles de integrantes del equipo 

|||
|------|-------------|
|<br>![Foto](../assets/images/Frank_foto.png) |<br>**Huingo Tello, Frank Anthony**<br><br> Código de Estudiante: U202319057<br><br> Mi nombre es Frank Anthony Huingo Tello, estudiante de Ingeniería de Software. Me considero una persona paciente y perseverante en mis proyectos y metas, a nivel académico cuento con conocimientos en programación en el lenguaje de C++, Python y JS, tengo experiencia trabajando en equipo y bajo presión. Considero que organizandonos bien puedo usar mis conocimientos para aportar mucho a este grupo  .<br><br>|
|<br>![Foto](../assets/images/Giancarlo_foto.png) |<br>**Verastigue Martinez, Giancarlo Jose**<br><br> Código de Estudiante: U202419483<br><br> Mi nombre es Giancarlo Jose Verastigue Martinez, estudiante de Ingeniería de Software. Soy una persona responsable y enfocada en sus proyectos y metas, a nivel académico cuento con conocimientos en programación en el lenguaje de C++, con experiencia trabajando en equipo y bajo presión. Considero que soy organizado y detallista en mis proyectos. La experiencia laboral y la universidad me han hecho desarrollar habilidades para afrontar problemas o dificultades de manera exitosa, habilidades que aportaré a este grupo de trabajo y de esta manera sacar adelante nuestro proyecto.<br><br>|
|<br>![Foto](../assets/images/Tony_foto.png) |<br>**Quispe Palomino, Tony Jhunior**<br><br> Código de Estudiante: u20241f714<br><br> Mi nombre es Tony Jhunior Quispe Palomino, soy estudiante de la carrera de Ingeniería de Software y actualmente me encuentro cursando el quinto ciclo. Tengo 20 años y me considero una persona amable, empática, perseverante y capaz de adaptarme a los cambios. En cuanto a mis conocimientos de programación, tengo una base sólida en C++, Python y conceptos básicos en HTML, CSS y un poco de JavaScript. En este proyecto, espero poder contribuir con mis conocimientos y habilidades, al mismo tiempo que fortalezco mis competencias en trabajo en equipo.<br><br>|
|<br>![MANUEL ALEJANDRO MOLINA VASQUEZ .jpg](../assets/images/MANUEL%20ALEJANDRO%20MOLINA%20VASQUEZ%20.jpg)|Manuel Alejandro Molina Vasquez<br><br> Código de Estudiante: U20221G231<br><br> Mi nombre es Manuel Alejandro Molina Vasquez, estudiante de Ingeniería de Software. Me considero una persona responsable y comprometida con mis proyectos y metas. A nivel académico, cuento con conocimientos en programación en los lenguajes de C++, Python y JavaScript, así como experiencia trabajando en equipo y bajo presión. Considero que mi capacidad de organización y mi enfoque en los detalles me permiten aportar significativamente a este grupo de trabajo.<br><br>|
|<br>![Foto](../assets/images/MatiasCarrillo.png) |<br>**Carrillo Acho, Matias Renato**<br><br> Código de Estudiante: u202323010<br><br> Me llamo Matias Renato Carrillo Acho, estudiante de ingeniería de Software. Gracias a la formación dentro de la carrera adquirí conocimientos sólidos en la programación en lenguajes de programación como C++, Python, Java y JavaScript, además tengo conocimientos básicos de HTML5, CCS3. Considero que tengo desarrollado el pensamiento crítico lo que me permite analizar y diseñar proyectos grandes en equipo. Ser alguien responsable y sobre todo ser empático son habilidades que me identifican y que aportaré al equipo.<br><br>|
---

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

En los últimos años, el turismo de aventura en el Perú ha presentado un crecimiento constante debido al interés de turistas nacionales e internacionales por actividades como trekking, montañismo y exploración en zonas naturales. El Ministerio de Comercio Exterior y Turismo ([MINCETUR](https://www.gob.pe/institucion/mincetur/noticias/563063-se-aprueban-veintidos-modalidades-de-turismo-de-aventura)) reconoce al turismo de aventura como un segmento importante dentro de la actividad turística nacional y ha aprobado diversas modalidades para fortalecer su desarrollo y regulación.

Muchas de estas actividades se desarrollan en áreas alejadas de centros urbanos, donde la cobertura de red móvil es limitada o inexistente debido a las condiciones geográficas del territorio peruano. Según reportes del Organismo Supervisor de Inversión Privada en Telecomunicaciones ([OSIPTEL](https://www.osiptel.gob.pe/portal-del-usuario/noticias/checa-tu-senal-asi-puedes-verificar-la-cobertura-movil-en-tu-distrito/)), todavía existen zonas del país con limitaciones de cobertura móvil y variaciones en la calidad del servicio, especialmente en áreas rurales y de difícil acceso.

Actualmente, las agencias de turismo y los guías dependen principalmente de teléfonos móviles y aplicaciones convencionales de comunicación y geolocalización para coordinar recorridos y mantener contacto con los grupos. Sin embargo, estas herramientas presentan limitaciones en zonas sin señal, generando dificultades para el monitoreo continuo de los turistas y la atención oportuna ante situaciones de emergencia. Esta problemática evidencia la necesidad de implementar soluciones tecnológicas adaptadas al contexto geográfico y operativo del turismo de aventura en el país.

| Pregunta | Formulación | Respuesta |
|----------|-------------|-----------|
| **Who?** | ¿Quiénes son los afectados? | Las agencias de turismo de aventura, los guías turísticos y los turistas nacionales e internacionales que realizan expediciones en zonas remotas del Perú, donde la limitada cobertura móvil dificulta el monitoreo y la comunicación durante el recorrido. |
| **What?** | ¿Cuál es el problema? | La falta de un sistema integrado de monitoreo en tiempo real de ubicación y signos vitales limita la capacidad de respuesta ante emergencias y reduce la seguridad de los turistas durante actividades de aventura en zonas sin cobertura de red. |
| **Where?** | ¿Dónde ocurre? | El problema se presenta en rutas de turismo de aventura ubicadas en zonas remotas del Perú, especialmente en circuitos de trekking de los Andes, selva alta y áreas naturales con geografía compleja y cobertura móvil limitada o inexistente. |
| **When?** | ¿Cuándo se hace más evidente? | Durante el desarrollo de las expediciones, principalmente en situaciones de separación de grupos, cambios climáticos bruscos, recorridos de alta dificultad o ante emergencias médicas como fatiga extrema, deshidratación o mal de altura. |
| **Why?** | ¿Por qué ocurre? | Debido a que las herramientas de comunicación y geolocalización utilizadas actualmente dependen de conexión móvil o internet para funcionar correctamente. En zonas remotas del Perú, la cobertura es limitada o inexistente, lo que genera pérdida de comunicación y dificultades para el monitoreo en tiempo real. |
| **How?** | ¿Cómo se manifiesta? | Se manifiesta mediante pérdida de comunicación entre integrantes del grupo, dificultades para ubicar turistas en tiempo real, retrasos en la atención de emergencias y dependencia de aplicaciones móviles que dejan de funcionar correctamente en zonas sin cobertura. |
| **How Much?** | ¿Cuánta es la magnitud? | El crecimiento sostenido del turismo de aventura en el Perú ha incrementado la cantidad de expediciones realizadas en zonas de difícil acceso. Sin embargo, gran parte de estas áreas presenta limitaciones de conectividad, lo que incrementa los riesgos de accidentes, extravíos y retrasos en la respuesta ante emergencias, afectando tanto la seguridad de los turistas como la capacidad operativa de las agencias. |

---

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

*Domain*

Tourmate opera en la intersección de la gestión logística turística, la seguridad preventiva y la telemetría IoT. El entorno de acción se ubica en el turismo de aventura y expediciones al aire libre, específicamente en geografías caracterizadas por la ausencia o intermitencia de infraestructura de telecomunicaciones tradicionales.

*Customer Segments*

El modelo de servicio atiende a dos actores fundamentales en el ecosistema turístico:

- *Segmento B2B (Operativo):* Agencias de turismo de aventura, operadores logísticos, directores de ruta y guías de montaña que gestionan expediciones en zonas remotas del Perú.
- *Segmento B2C (Usuario Final):* Turistas, senderistas y exploradores, nacionales e internacionales, que contratan estos servicios y transitan por rutas de baja o nula conectividad.

*Pain Points*

- *Para las agencias:* La supervisión actual depende de reportes manuales o radiocomunicaciones inestables, generando una ceguera operativa. Desconocen la ubicación exacta y el estado fisiológico de sus clientes en tiempo real, lo que provoca tiempos de reacción lentos ante emergencias, elevando los costos de rescate y exponiendo a la empresa a riesgos legales y reputacionales.
- *Para los turistas:* La desconexión total en zonas remotas genera ansiedad e inseguridad. La incapacidad de acceder a mapas interactivos o información del entorno sin conexión disminuye la autonomía y empobrece la experiencia general del recorrido.

*Gap*

Existe una clara desconexión entre la necesidad de seguridad continua y las herramientas disponibles. Las soluciones satelitales actuales son financieramente prohibitivas para equipar a cada turista de forma individual. Las aplicaciones móviles estándar quedan completamente inoperativas al perder la señal celular. No existe actualmente un sistema híbrido y accesible que integre monitoreo biométrico y geolocalización de forma autónoma, sin depender de redes 4G/5G en tiempo real.

*Vision / Strategy*

Nuestra visión es establecer a Tourmate como el estándar tecnológico para la gestión de riesgo en el turismo de aventura en el Perú. La estrategia se basa en desplegar una arquitectura de hardware y software resiliente: un ecosistema IoT asincrónico mediante wearables de bajo costo y checkpoints Bluetooth estratégicamente ubicados, que capturen signos vitales y datos de ubicación sincronizados en ráfagas. Esto permitirá transformar la gestión de las agencias de un modelo reactivo a uno predictivo, mediante dashboards centralizados y alertas automatizadas, mientras se dota al turista de herramientas robustas de navegación offline.

*Initial Segment*

El despliegue inicial apuntará a agencias de turismo de aventura de tamaño mediano a grande que operan rutas de trekking de alta exigencia, como circuitos de alta montaña o selva densa. Estas agencias manejan volúmenes considerables de turistas, enfrentan los mayores riesgos operativos por la nula conectividad de sus zonas de trabajo y tienen urgencia por elevar sus estándares internacionales de seguridad.

¿Cómo podemos mejorar la capacidad de respuesta y supervisión en rutas de aventura, logrando que las agencias actúen de manera preventiva y los turistas se sientan seguros incluso sin conexión?

#### 1.2.2.2. Lean UX Assumptions

*Assumptions Worksheet*

*Business Assumptions*

- *Creo que mis clientes tienen la necesidad de* mantener una supervisión constante sobre la ubicación y el estado de salud de los grupos de turistas en zonas remotas, reduciendo la incertidumbre y los tiempos de respuesta ante emergencias, sin depender de redes de telecomunicaciones tradicionales.

- *Estas necesidades pueden resolverse con* Tourmate, una plataforma web integrada con un ecosistema IoT (wearables y checkpoints Bluetooth) que captura y sincroniza de forma asincrónica datos biométricos y de geolocalización, dotando a las agencias de dashboards de control y a los turistas de herramientas de navegación offline.

- *Mis clientes iniciales son:*
    - *Segmento B2B:* Agencias de turismo de aventura y guías de alta montaña que gestionan rutas en zonas de baja o nula conectividad.
    - *Segmento B2C:* Turistas y senderistas que buscan experiencias al aire libre seguras y desean registrar su progreso.

- *El principal valor que un cliente quiere obtener de mi servicio es* seguridad preventiva y visibilidad operativa en tiempo real de toda la expedición, con autonomía total frente a la falta de cobertura celular.

- *También pueden obtener estos beneficios adicionales:*
    - Para las agencias: reducción de costos en misiones de búsqueda y rescate, y mejora en certificaciones de seguridad internacionales.
    - Para los turistas: acceso a mapas interactivos offline, información contextual del recorrido y registro digital de su experiencia.

- *Adquiriré la mayoría de mis clientes a través de* venta directa B2B a agencias consolidadas, alianzas con asociaciones de guías de montaña y federaciones de andinismo, y presencia en ferias de turismo de aventura.

- *Ganaré dinero mediante* un modelo híbrido HaaS/SaaS: venta o alquiler de infraestructura física (wearables y checkpoints Bluetooth) combinado con suscripción mensual o anual por el uso de la plataforma, almacenamiento en la nube y gestión de alertas.

- *Mi principal competencia en el mercado será* sistemas de comunicación por radio (VHF/UHF), dispositivos de mensajería satelital como Garmin inReach, y la gestión logística puramente manual.

- *Superaremos a la competencia debido a* nuestro enfoque escalable y preventivo: a diferencia de los dispositivos satelitales costosos por usuario, Tourmate permite monitorear automáticamente a decenas de turistas simultáneamente, detectando anomalías fisiológicas antes de que se conviertan en emergencias críticas.

- *El mayor riesgo de mi producto es* que la latencia en la sincronización asincrónica sea demasiado alta para ser útil en una emergencia médica aguda, o que el hardware sufra averías en condiciones climáticas extremas.

- *Lo resolveremos mediante* un diseño de arquitectura de red que priorice la transmisión de alertas críticas en ráfagas cortas de datos, y certificaciones de resistencia industrial para todo el hardware IoT.

- *Otras suposiciones que, si se demuestran falsas, harán que nuestro negocio fracase:*
    - Que las agencias de turismo estén dispuestas a invertir en infraestructura tecnológica preventiva.
    - Que los turistas acepten utilizar wearables de la agencia sin percibir invasión a su privacidad.

*User Assumptions*

- *¿Quién es el usuario?*
    - El operador (B2B): directores de agencias y guías líderes que necesitan herramientas logísticas para garantizar el retorno seguro de sus grupos.
    - El turista (B2C): personas apasionadas por el trekking que valoran la seguridad y exigen herramientas digitales modernas para enriquecer su viaje.

- *¿Dónde encaja nuestro producto en su vida?* En la fase de ejecución operativa del turismo. Para el guía y la agencia, es su centro de comando durante las expediciones. Para el turista, es su herramienta de navegación y seguridad mientras recorre la ruta.

- *¿Qué problemas soluciona nuestro producto?*
    - La ceguera operativa de las agencias sobre la ubicación exacta de sus grupos.
    - La incapacidad de detectar a tiempo problemas de salud como hipotermia, mal de altura o taquicardia.
    - La desorientación del turista por la inutilidad de aplicaciones tradicionales sin señal.

- *¿Cuándo y cómo se utiliza nuestro producto?*
    - En campo (continuo): los turistas llevan el wearable que recopila datos automáticamente y consultan la app para navegación offline.
    - En base (monitoreo): el personal de la agencia visualiza el dashboard web recibiendo actualizaciones asincrónicas conforme los grupos pasan por los checkpoints.

- *¿Qué características son importantes?* Robustez y tolerancia a fallos de red (offline-first), alertas automatizadas configurables por rangos de signos vitales, sincronización Bluetooth de baja energía transparente, y mapas topográficos descargables optimizados para dispositivos móviles.

- *¿Cómo debe verse y comportarse nuestro producto?* Diseño minimalista, profesional y funcional, con interfaces de alto contraste para facilitar la lectura en exteriores, priorizando la claridad de datos de salud, ubicación y cartografía sin elementos visuales superfluos.

*Feature Assumptions*

- Creemos que nuestros clientes necesitan una plataforma que opere sin conexión continua a internet, sincronizando datos de forma asincrónica mediante checkpoints Bluetooth, para garantizar la trazabilidad logística en zonas de nula o baja conectividad.

- Estas necesidades se pueden resolver con una arquitectura offline-first que capture signos vitales y geolocalización mediante wearables IoT, los almacene localmente y los sincronice en ráfagas cuando el turista pase por un checkpoint BLE.

- El valor principal que un cliente quiere de nuestro servicio es la capacidad de monitorear en tiempo cuasi-real la ubicación y el estado de salud de múltiples grupos simultáneos desde un dashboard centralizado, sin depender de cobertura celular.

- El cliente también puede obtener estos beneficios adicionales: generación automática de reportes de expedición, registro digital de la experiencia del turista compartible en redes sociales, y alertas tempranas configurables por umbrales de signos vitales que permiten intervención preventiva antes de que ocurra una emergencia.

- Vamos a adquirir la mayoría de nuestros clientes a través de pilotos gratuitos de tres meses con agencias de turismo de aventura en Cusco y Áncash, demostraciones en campo y alianzas con DIRCETUR y asociaciones gremiales del sector.

- Haremos dinero a través de un modelo híbrido: suscripción mensual o anual por el uso de la plataforma según el volumen de turistas gestionados, combinado con alquiler o venta de la infraestructura física de wearables y checkpoints Bluetooth.

- Nuestra competencia principal en el mercado serán TrekkSoft, AllTrails y Garmin inReach, además de métodos tradicionales como radiocomunicación VHF/UHF, coordinación por WhatsApp y seguimiento manual por parte de los guías.

- Los venceremos debido a que Tourmate es la única plataforma que integra gestión operativa para agencias, navegación offline para turistas e IoT biométrico en un solo ecosistema diseñado específicamente para el contexto peruano de baja conectividad.

- Nuestro mayor riesgo de producto es que la latencia entre checkpoints sea demasiado alta para responder oportunamente ante una emergencia médica aguda, o que las agencias rechacen la inversión inicial en hardware por considerarla elevada.

- Resolveremos esto a través de una arquitectura de red que priorice la transmisión de alertas críticas, un modelo de alquiler de hardware que elimine la barrera de inversión inicial, y validaciones tempranas en campo con usuarios reales de los segmentos objetivo.

- Otra suposición es que los turistas estarán dispuestos a utilizar los wearables proporcionados por la agencia durante todo el recorrido. Si esto resulta falso, el sistema de monitoreo biométrico no podrá operar, lo que afectaría la propuesta de valor central de la plataforma.

*Business Outcomes*

- Reducción del 40% en evacuaciones médicas de emergencia durante los primeros seis meses de uso en campo.
- Registro exitoso del paso del 95% de los turistas por los puntos de control con una pérdida de paquetes de datos inferior al 5%.
- Tasa de conversión del 25% de agencias que pasan de piloto gratuito a suscripción anual pagada dentro de los primeros 3 meses.
- Calificación de sensación de seguridad como "Alta" o "Muy Alta" por al menos el 85% de los turistas en encuestas post-tour.

#### 1.2.2.3. Lean UX Hypothesis Statements

#### Hypothesis Statement 01

**Creemos que** lograremos incrementar la adopción de Tourmate por parte de las agencias de turismo de aventura.

**Si** las agencias de turismo de aventura

**Obtienen** una solución que les permita ofrecer expediciones más seguras mediante el monitoreo continuo de sus turistas.

**Con** una plataforma integrada con wearables IoT para el seguimiento de signos vitales y ubicación en tiempo real.

---

#### Hypothesis Statement 02

**Creemos que** lograremos aumentar la confianza de las agencias de turismo en nuestra solución tecnológica.

**Si** las agencias de turismo de aventura

**Obtienen** la posibilidad de supervisar expediciones incluso en zonas sin cobertura de Internet.

**Con** una infraestructura basada en checkpoints Bluetooth Low Energy (BLE) que sincroniza automáticamente la información recolectada.

---

#### Hypothesis Statement 03

**Creemos que** lograremos incrementar la preferencia de los turistas por las agencias que utilicen Tourmate.

**Si** los turistas

**Obtienen** una experiencia de navegación segura y continua durante toda la expedición.

**Con** una aplicación móvil con mapas topográficos completamente disponibles en modo offline.

---

#### Hypothesis Statement 04

**Creemos que** lograremos mejorar la eficiencia operativa de las agencias de turismo, permitiéndoles administrar un mayor número de expediciones de manera simultánea.

**Si** los operadores y guías de turismo

**Obtienen** una visualización centralizada del estado, ubicación y alertas de todos los grupos.

**Con** un dashboard web de monitoreo en tiempo casi real.

---

#### Hypothesis Statement 05

**Creemos que** lograremos fortalecer la reputación y competitividad de las agencias de turismo que utilicen Tourmate.

**Si** las agencias de turismo de aventura

**Obtienen** notificaciones automáticas que les permitan responder oportunamente ante posibles incidentes durante las expediciones.

**Con** un sistema inteligente de alertas basado en parámetros biométricos.

---

#### Hypothesis Statement 06

**Creemos que** lograremos incrementar la fidelización de los turistas y generar una mayor recomendación de los servicios ofrecidos por las agencias.

**Si** los turistas

**Obtienen** un registro digital de sus expediciones con estadísticas, logros y recorridos realizados.

**Con** un resumen interactivo generado automáticamente al finalizar cada experiencia.

---

#### Hypothesis Statement 07

**Creemos que** lograremos aumentar la comercialización y escalabilidad de Tourmate como solución tecnológica para el turismo de aventura.

**Si** las agencias de turismo de aventura

**Obtienen** acceso a una plataforma con un modelo de pago flexible, sin necesidad de realizar una elevada inversión inicial en infraestructura.

**Con** un modelo de negocio basado en suscripción SaaS complementado con el alquiler de wearables IoT y checkpoints Bluetooth Low Energy (BLE).

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas es una herramienta utilizada en el marco del diseño centrado en el usuario (UX) y la metodología Lean, cuyo objetivo es apoyar la creación y mejora de productos de manera ágil y eficiente. Su propósito principal es proporcionar una estructura organizada que fomente la colaboración entre equipos multidisciplinarios. A continuación, se presenta el Lean UX Canvas elaborado por el equipo utilizando la plataforma digital Mural.

![Lean-UX-canvas-Tourmate](../assets/images/lean-ux-canvas.png)

Enlace para acceder al Lean UX Canvas en Mural: [https://l1nq.com/oa73grw](https://l1nq.com/oa73grw)

---

## 1.3 Segmentos Objetivo
 
A partir del análisis del dominio del problema, la falta de sistemas de monitoreo en tiempo real para turismo de aventura en zonas remotas del Perú, se han identificado dos segmentos objetivo claramente diferenciados a los que Tourmate dirige su propuesta de valor. El primero corresponde a las agencias y operadores turísticos de aventura que requieren herramientas de gestión, supervisión y trazabilidad operativa de sus tours; el segundo corresponde a los turistas de aventura nacionales y extranjeros que demandan experiencias seguras, guiadas y enriquecidas en entornos naturales del país. A continuación se describen ambos segmentos junto con sus características demográficas y la información estadística que sustenta su relevancia.
 
*Segmento 1: Agencias y Operadores de Turismo de Aventura*
 
**Descripción**
 
Empresas formalmente constituidas, registradas en el Directorio Nacional de Prestadores de Servicios Turísticos del MINCETUR, dedicadas a la organización y operación de tours de aventura: trekking, montañismo, canotaje, ciclismo de montaña, escalada y actividades de ecoturismo. Su operación se concentra principalmente en regiones con alto potencial de turismo de aventura como Cusco, Áncash, Arequipa, Puno, Madre de Dios y San Martín, donde la conectividad celular es intermitente o inexistente. Estas agencias enfrentan limitaciones operativas para supervisar el estado y la ubicación de sus grupos durante los recorridos, así como para responder de forma oportuna ante anomalías o emergencias.
 
**Características demográficas y de negocio**
 
- Tipo de empresa: Micro y pequeñas empresas (MYPEs) en su mayoría, con entre 5 y 50 colaboradores entre guías, choferes y personal administrativo.
- Ubicación geográfica: Cusco, Áncash (Huaraz), Arequipa, Puno, Madre de Dios, Lima y San Martín.
- Antigüedad operativa: Mayoritariamente con más de 3 años en el mercado y registradas en DIRCETUR/GERCETUR.
- Capacidad operativa: Atienden grupos de entre 4 y 20 turistas por tour, con frecuencia diaria o semanal según temporada.
- Perfil tecnológico: Adopción digital baja a media, con uso predominante de WhatsApp y radios para comunicación, y escaso uso de plataformas integradas de gestión.

**Información estadística de sustento**
 
- Solo en Cusco, la Asociación de Agencias de Turismo del Cusco (AATC) representa a más de 190 agencias activas dedicadas a turismo de aventura, místico, ecológico y tradicional, lo que evidencia la concentración del mercado objetivo en regiones específicas.
- Según MINCETUR, en el 2025 se registraron 14.1 millones de visitas a sitios turísticos del país, un crecimiento del 33.2% frente al 2024, con una recuperación del 95.4% respecto al nivel prepandemia, lo que se traduce en una mayor demanda de servicios para los operadores.
- El 83% de los operadores turísticos del segmento aventura reportó incremento de ingresos en 2025, y un 46% indicó que estos crecieron por encima del 26% según el estudio anual de la Adventure Travel Trade Association (ATTA), lo que demuestra capacidad de inversión en herramientas tecnológicas.
- El sector turismo aportó aproximadamente el 2.9% del PBI nacional en 2025, según estimaciones del MINCETUR a partir de las Cuentas Satélite del Turismo, consolidando a las agencias como un mercado de alto valor económico.

*Segmento 2: Turistas de Aventura*
 
**Descripción**
 
Personas que viajan al Perú, ya sea desde el extranjero o desde otras regiones del país, motivadas por experiencias de naturaleza, deporte y exploración en entornos remotos. Buscan vivir recorridos como el Camino Inca, Salkantay, Choquequirao, Huayhuash, Colca o la Amazonía, contratando agencias formales que les brinden seguridad, organización y guías especializados. Demandan herramientas digitales que les permitan navegar offline, registrar su experiencia y acceder a información contextual del recorrido sin depender de conectividad continua.
 
**Características demográficas**
 
- Edad: El 49% de los viajeros de aventura a nivel mundial se ubica entre los 41 y 60 años; en Sudamérica esta franja sube al 54%, mientras que un 26% tiene menos de 40 años.
- Género: Predominio femenino, con 53% de mujeres frente a 46% de hombres realizando viajes de aventura, según ATTA 2024.
- Composición del grupo de viaje: El 36% viaja en pareja, 24% en grupo y 21% en familia. En Sudamérica, la familia (26%) supera a los grupos como segunda modalidad más popular.
- Procedencia: Mayoritariamente turistas extranjeros provenientes de Sudamérica (51.7%), Norteamérica (23.8%) y Europa (16.8%), complementados por turistas nacionales que viajan dentro del territorio peruano.
- Nivel socioeconómico: Medio-alto y alto, con capacidad de pagar paquetes turísticos completos y seguros de viaje con cobertura para deportes de riesgo.

**Información estadística de sustento**
 
- En el 2025, el Perú recibió 3.2 millones de turistas internacionales, un crecimiento del 29% frente al 2024, con proyecciones de alcanzar las cifras prepandemia de 4.4 millones en los próximos años.
- Se estima que el país alcanzará 43.5 millones de viajes por turismo interno al cierre de 2025, un 16.9% más que en 2024, ampliando significativamente la base potencial de turistas nacionales que demandan experiencias de aventura.
- El segmento global de turismo de aventura registró un crecimiento del 65% en número de viajeros atendidos respecto al 2019, y un 54% adicional respecto al 2022, consolidándose como uno de los nichos de mayor expansión a nivel mundial.
- El 51.5% de las visitas registradas en sitios turísticos peruanos en 2025 corresponde a turistas internacionales y el 48.5% a nacionales, lo que confirma que la propuesta de Tourmate debe atender a ambos perfiles bajo experiencias multilingües y adaptadas culturalmente.
- Regiones clave para el turismo de aventura como Cusco e Ica ya están a solo 2.6% y 3.6% de alcanzar sus cifras prepandemia, evidenciando la consolidación de los destinos donde opera el segmento.

<div style="page-break-before: always;"></div>

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En esta sección se identifican y describen los principales competidores directos que operan en el dominio del problema que Tourmate aborda: la gestión, monitoreo y trazabilidad de tours de aventura mediante productos digitales similares. Los tres competidores seleccionados comparten con Tourmate el modelo de negocio basado en plataformas digitales orientadas al turismo de aventura, con funcionalidades superpuestas en gestión de tours, navegación, seguimiento en tiempo real y experiencia del turista.

**TrekkSoft:** Empresa suiza fundada en 2010 en Interlaken, conocida como la capital europea de la aventura. Ofrece una plataforma de reservas y gestión operativa orientada a operadores turísticos de aventura, con módulos de pago, sincronización con OTAs, gestión de inventario y panel administrativo. Su enfoque comercial está dirigido a agencias pequeñas y medianas en mercados europeos y latinoamericanos.

**Wayward:** Plataforma estadounidense especializada en software para operadores de turismo de aventura, rallies y experiencias outdoor. Combina en una sola solución gestión de reservas, seguimiento de viaje en vivo (Live Trip Tracking), chat en tiempo real entre guías y turistas, waivers digitales, itinerarios personalizados y comunicación con contactos de emergencia. Es uno de los competidores directos más cercanos a Tourmate por su enfoque integral en seguridad y trazabilidad durante el recorrido.

**AllTrails:** Aplicación móvil desarrollada en Estados Unidos, líder mundial en navegación para senderismo y trekking. Posee un catálogo superior a 500,000 rutas en todo el mundo, navegación GPS giro a giro, mapas offline para suscriptores premium y una comunidad activa de senderistas. Se posiciona como la herramienta de referencia para turistas que realizan rutas de aventura por su cuenta o con agencias.

### 2.1.1. Análisis Competitivo

**Competitive Analysis Landscape**

A continuación se presenta el cuadro Competitive Analysis Landscape, en el cual se contrasta el perfil de Nexum Devs y su producto Tourmate frente a los tres competidores directos identificados, considerando dimensiones de perfil, marketing, producto y análisis SWOT.

<html>
<body>
    <table>
        <tr>
           <td colspan="6" class="sub">  <h1>Competitive Analysis Landscape</h1></td>
        </tr>
        <tr>
            <td colspan="2" rowspan="2" class="sub">¿Por qué llevar a cabo este análisis?</td>
            <td colspan="4" class="sub"><h3>¿Quiénes son nuestros principales competidores?</h3></td>
        </tr>
        <tr>
            <td colspan="4">El objetivo es comprender el posicionamiento real de los competidores en el mercado de gestión y monitoreo de turismo de aventura, identificar brechas en sus propuestas de valor y validar los espacios de oportunidad que Tourmate puede ocupar en el mercado peruano.</td>
        </tr>
        <tr>
            <td rowspan="3" class="sub">PERFIL</td>
            <td rowspan="2" class="sub">Overview</td>
            <td> Tourmate <img src="../assets/images/Logo_Tourmate.jpeg"></td>
            <td> TrekkSoft <img src="../assets/images/trekk-soft.png"></td>
            <td> Wayward <img src="../assets/images/wayward.png"></td>
            <td> AllTrails <img src="../assets/images/all-trails.png"></td> 
        </tr>
        <tr>
            <td>Plataforma web y móvil peruana que centraliza la gestión de tours de aventura para agencias y ofrece a turistas navegación offline, registro de experiencia e información contextual del recorrido, integrando un ecosistema IoT con wearables y checkpoints Bluetooth.</td>
            <td>Plataforma suiza de software como servicio para reservas y gestión operativa de operadores turísticos, con foco en pagos online y conexión con OTAs.</td>
            <td>Plataforma estadounidense todo en uno para operadores de aventura, con énfasis en seguimiento de viaje en vivo, chat en tiempo real entre guías y viajeros, waivers digitales e itinerarios personalizados.</td>
            <td>Aplicación móvil estadounidense con el mayor catálogo mundial de rutas de senderismo, navegación GPS y comunidad de usuarios.</td>      
        </tr>
        <tr>
            <td class="sub">Ventaja Competitiva ¿Qué valor ofrece a los clientes?</td>
            <td>Solución integral con sincronización asincrónica que opera sin conexión continua, dashboards de monitoreo en tiempo real para agencias, alertas ante anomalías y captura de signos vitales mediante wearables. Diseñada específicamente para el contexto peruano.</td>
            <td>Reduce la fricción del proceso de reserva y centraliza pagos. Permite a agencias vender sus tours en múltiples canales desde una sola plataforma.</td>
            <td>Unifica reservas, comunicación, seguridad y experiencia del viajero en una sola interfaz. Permite a las agencias mostrar la marca propia sin que aparezca el branding de Wayward, y comparte la ubicación con contactos de emergencia.</td>
            <td>Acceso instantáneo a más de 500,000 rutas verificadas con reseñas, fotografías y mapas offline en versión premium.</td>      
        </tr>
        <tr>
            <td rowspan="2" class="sub">PERFIL DEL MARKETING</td>
            <td class="sub" >Mercado Objetivo</td>
            <td>Agencias formales de turismo de aventura y turistas nacionales y extranjeros que realizan rutas en regiones del Perú con baja conectividad como Cusco, Áncash, Arequipa, Puno y Madre de Dios.</td>
            <td>Operadores turísticos de actividades y tours en Europa y Latinoamérica, principalmente pequeñas y medianas empresas con foco en ventas online.</td>
            <td>Operadores de turismo de aventura, organizadores de rallies, retiros outdoor y organizaciones turísticas regionales (DMOs) en Norteamérica y Europa.</td>
            <td>Senderistas, ciclistas, corredores y turistas de aventura individuales a nivel global, mayoritariamente en Norteamérica y Europa.</td>
        </tr>
        <tr>
            <td class="sub">Estrategias de Marketing</td>
            <td>Marketing digital orientado a segmentos B2B mediante alianzas con DIRCETUR, asociaciones de agencias como AATC y participación en ferias de turismo. Estrategia B2C centrada en redes sociales, contenido de valor sobre rutas peruanas y posicionamiento SEO local.</td>
            <td>Marketing de contenidos en blog corporativo, webinars para operadores, presencia en plataformas de reseñas como Capterra y participación en eventos de la industria turística europea.</td>
            <td>Marketing basado en casos de éxito de operadores reales, alianzas con DMOs regionales, contenido educativo para gestores de turismo y enfoque en testimonios sobre seguridad y conexión con viajeros.</td>
            <td>Modelo freemium con conversión a suscripción AllTrails Plus. Crecimiento basado en comunidad de usuarios, contenido generado por usuarios y posicionamiento orgánico en buscadores.</td>
        </tr>
        <tr>
            <td rowspan="3" class="sub">PERFIL DEL PRODUCTO</td>
            <td class="sub">Productos & Servicios</td>
            <td>Plataforma web para agencias con dashboard de monitoreo, gestión de tours y alertas. Aplicación móvil para turistas con mapas offline y registro de experiencia. Wearables IoT y checkpoints Bluetooth para captura de geolocalización y signos vitales.</td>
            <td>Software de reservas, gestión de pagos, sincronización con OTAs como Viator y GetYourGuide, panel de control y aplicación para guías.</td>
            <td>Plataforma con seguimiento de ubicación en vivo, chat instantáneo entre guías y viajeros, waivers digitales, encuestas posteriores al viaje, mapas con itinerarios destacados y módulo de reservas con marca personalizada.</td>
            <td>Aplicación móvil con búsqueda de rutas, navegación GPS giro a giro, mapas offline en plan Plus, registro de actividad y comunidad social.</td>
        </tr>
        <tr>
            <td class="sub">Precios & Costos</td>
            <td>Modelo de suscripción mensual diferenciado para agencias según tamaño y volumen de tours. Aplicación móvil gratuita para turistas con funciones premium opcionales. Costo adicional por hardware de wearables y checkpoints.</td>
            <td>Planes mensuales para operadores turísticos con comisión sobre reservas. Tarifas variables según volumen y módulos contratados.</td>
            <td>Precios bajo cotización personalizada según tamaño del operador y módulos contratados. Modelo SaaS sin comisión por reserva.</td>
            <td>Versión gratuita con funciones básicas. Suscripción AllTrails Plus alrededor de 35.99 dólares anuales para mapas offline y funcionalidades avanzadas.</td>
        </tr>
        <tr>
            <td class="sub">Canales de distribución (web/móvil)</td>
            <td>Plataforma web responsive para agencias y aplicación móvil nativa Android e iOS para turistas. Distribución directa a través del sitio web corporativo y alianzas con asociaciones de agencias.</td>
            <td>Aplicación web SaaS y aplicación móvil para guías. Distribución mediante sitio corporativo, comparadores de software y partnerships.</td>
            <td>Plataforma web SaaS y experiencia móvil para viajeros sin necesidad de descargar aplicación adicional, accesible vía enlace directo. Distribución a través del sitio web corporativo.</td>
            <td>Aplicación móvil Android e iOS, sitio web complementario. Distribución a través de App Store, Google Play y posicionamiento orgánico.</td>        
        </tr>
        <tr>
            <td rowspan="4" class="sub">ANÁLISIS SWOT</td>
            <td class="sub">Fortalezas</td>
            <td>Solución integral única en el mercado peruano que combina gestión para agencias, experiencia para turistas e integración IoT. Funcionamiento offline mediante sincronización asincrónica. Conocimiento profundo del contexto local y rutas peruanas. Captura de signos vitales para prevención de riesgos.</td>
            <td>Plataforma robusta y madura con más de quince años en el mercado. Integración consolidada con OTAs líderes. Reconocimiento en el sector europeo de actividades de aventura.</td>
            <td>Propuesta integral que une seguridad, comunicación y reservas. Live Tracking validado por operadores de rallies y aventuras de varios días. Experiencia móvil sin fricción, sin login para el viajero.</td>
            <td>Comunidad masiva de usuarios y volumen de rutas inigualable. Marca reconocida globalmente. Interfaz intuitiva y experiencia de usuario altamente pulida.</td>
        </tr>
        <tr>
            <td class="sub">Debilidades</td>
            <td>Marca nueva sin reconocimiento en el mercado. Necesidad de inversión inicial en desarrollo y despliegue de hardware. Curva de adopción tecnológica en agencias con baja madurez digital.</td>
            <td>Plataforma orientada principalmente a reservas, sin capacidades de monitoreo en tiempo real ni integración con dispositivos de tracking en campo. Interfaz no diseñada para uso en zonas sin conectividad.</td>
            <td>Su tracking depende de la conectividad celular del dispositivo del viajero, lo que limita su utilidad en zonas remotas sin señal. No incorpora hardware IoT propio ni captura de signos vitales. Presencia inexistente en el mercado peruano.</td>
            <td>No ofrece herramientas de gestión para agencias ni dashboards de supervisión. Cobertura limitada de rutas peruanas. Mapas offline restringidos a la versión de pago. Sin integración con dispositivos IoT.</td>  
        </tr>
        <tr>
            <td class="sub">Oportunidades</td>
            <td>Crecimiento sostenido del turismo de aventura en el Perú con 14.1 millones de visitas a sitios turísticos en 2025 y aumento del 33.2 por ciento respecto a 2024. Alta demanda de soluciones de seguridad por parte de turistas y agencias. Bajo nivel de digitalización del sector permite posicionarse como referente.</td>
            <td>Expansión hacia mercados latinoamericanos donde su presencia es limitada. Demanda creciente de digitalización en operadores turísticos.</td>
            <td>Expansión hacia mercados emergentes de turismo de aventura como Sudamérica y Asia. Integración futura con dispositivos satelitales o IoT podría ampliar su propuesta de valor.</td>
            <td>Incorporación de funcionalidades para agencias podría ampliar su mercado. Crecimiento del turismo experiencial a nivel global.</td> 
        </tr>
        <tr>
            <td class="sub">Amenazas</td>
            <td>Llegada de competidores internacionales con mayor capital al mercado peruano. Adopción masiva de tecnologías satelitales como Starlink Direct to Cell que reduzcan la barrera de la conectividad. Competencia con plataformas globales con mayor presupuesto de marketing.</td>
            <td>Aparición de competidores locales con propuestas adaptadas culturalmente. Posible canibalización por parte de plataformas como Bokun o FareHarbor en mercados emergentes.</td>
            <td>Competidores con soluciones más completas que integren hardware propio. Saturación del mercado norteamericano de software para turismo.</td>
            <td>Competidores especializados en navegación offline regional con mejor cobertura local. Apps de mapas gratuitos como Google Maps incorporando funciones similares.</td>          
        </tr>
    </table>
</body>
</html>

### 2.1.2. Estrategias y Tácticas frente a Competidores

A partir del análisis competitivo realizado, hemos definido un conjunto de estrategias y tácticas preliminares orientadas a afrontar las fortalezas de los competidores, aprovechar sus debilidades y posicionar a Tourmate como la solución de referencia para turismo de aventura en el Perú.

**Estrategia de diferenciación por integralidad:** Mientras los competidores actuales atacan únicamente uno de los frentes del problema, ya sea reservas, navegación o seguimiento dependiente de conectividad celular, Tourmate se posiciona como la única plataforma que integra los tres componentes en un solo ecosistema con respaldo de hardware IoT propio. La táctica asociada consiste en comunicar de forma clara este diferencial mediante demostraciones en vivo durante visitas comerciales a agencias, casos de uso documentados y material audiovisual que muestre el flujo completo desde la gestión del tour hasta la finalización del recorrido por parte del turista.

**Estrategia de penetración local con conocimiento del contexto:** Frente a la presencia internacional de TrekkSoft, Wayward y AllTrails, la ventaja competitiva más relevante de Nexum Devs es el conocimiento profundo del mercado peruano y de sus rutas específicas. La táctica consiste en establecer alianzas estratégicas con asociaciones gremiales como la AATC en Cusco y entidades regionales de DIRCETUR, validar el producto con agencias piloto en Áncash y Cusco, y construir un repositorio de rutas peruanas verificadas con información contextual cultural e histórica que ningún competidor global ofrece.

**Estrategia de precios accesible para MYPEs:** Considerando que el mercado objetivo está compuesto principalmente por micro y pequeñas empresas con capacidad limitada de inversión tecnológica, Tourmate aplicará un modelo de precios escalonado y accesible. La táctica consiste en ofrecer planes diferenciados según tamaño de la agencia y volumen de tours, periodos de prueba gratuita de tres meses para agencias pioneras y financiamiento del hardware IoT mediante esquemas de leasing o suscripción combinada.

**Estrategia de funcionamiento offline como ventaja estructural:** Mientras AllTrails restringe los mapas offline a su plan de pago, TrekkSoft no opera sin conexión y Wayward depende de la cobertura celular del dispositivo del viajero, la sincronización asincrónica de Tourmate se convierte en su mayor fortaleza estructural. La táctica consiste en posicionar la operatividad sin internet como mensaje principal de la propuesta de valor en todo el material comercial, demostrando funcionalidad real en zonas remotas durante demos comerciales y certificando el desempeño en escenarios de baja conectividad mediante pruebas en campo.

**Estrategia de mitigación frente a la amenaza satelital emergente:** Ante el avance de tecnologías como Starlink Direct to Cell que podrían reducir la dependencia de hardware satelital costoso, Tourmate prevé mantener una arquitectura modular que permita integrar futuras tecnologías de conectividad sin rediseñar la plataforma. La táctica consiste en diseñar la capa de comunicaciones bajo principios de abstracción que permitan reemplazar o complementar wearables Bluetooth con módulos satelitales económicos cuando estos estén disponibles en el mercado peruano, manteniendo la propuesta de valor centrada en software y datos más que en el dispositivo.

**Estrategia de captación de turistas mediante experiencia enriquecida:** Frente a AllTrails, cuya propuesta es funcional pero impersonal, y a Wayward, que se concentra en la dimensión operativa, Tourmate apunta a ofrecer una experiencia turística enriquecida con información cultural, registro fotográfico contextualizado y narrativa del recorrido. La táctica consiste en colaborar con guías locales certificados para construir contenido auténtico, integrar elementos de gamificación que motiven al turista a completar la ruta y generar memorias digitales compartibles que sirvan también como herramienta de marketing orgánico para las agencias asociadas.

## 2.2. Entrevistas

#### 2.2.1. Diseño de Entrevistas

Las entrevistas constituyen la principal técnica de investigación cualitativa para la validación del problema y la propuesta de valor de Tourmate. El objetivo es comprender en profundidad las necesidades, frustraciones, comportamientos actuales y expectativas de los dos segmentos de usuario identificados: los **dueños o responsables de agencias de turismo de aventura** y los **turistas de aventura**.

---

##### Objetivos Generales del Proceso de Entrevistas

1. Validar la existencia y criticidad del problema de monitoreo y seguridad en tours de aventura en zonas remotas del Perú.
2. Comprender cómo gestionan actualmente sus operaciones las agencias de turismo de aventura, identificando herramientas utilizadas, brechas y puntos de dolor.
3. Explorar la disposición de las agencias a adoptar una solución tecnológica integrada y su sensibilidad al precio.
4. Entender la experiencia del turista durante el tour: qué información desearía tener, qué situaciones de riesgo ha vivido y qué herramientas digitales ya usa.
5. Identificar funcionalidades prioritarias y posibles fricciones en la adopción del producto desde la perspectiva de ambos segmentos.

---

##### Segmento 1: Dueños o Responsables de Agencias de Turismo de Aventura

**Perfil del entrevistado:** propietarios, directores de operaciones o guías principales de agencias que operen rutas de trekking, montañismo, expediciones o turismo de naturaleza en zonas remotas del Perú. Preferiblemente agencias medianas o pequeñas con operaciones activas en sierra, selva alta o circuitos andinos.

---

**Preguntas de apertura y contexto**

1. ¿Podría contarme brevemente cómo funciona su agencia? ¿Qué tipo de tours opera y en qué zonas del país?
2. ¿Cuántos guías y turistas maneja típicamente en una temporada alta? ¿Cuántos grupos simultáneos puede llegar a tener activos?

**Preguntas sobre gestión operativa actual**

3. ¿Cómo realiza actualmente el seguimiento de sus grupos de turistas cuando están en campo? ¿Qué herramientas o medios utiliza (radio, celular, reportes manuales, apps)?
4. ¿Con qué frecuencia sus guías o grupos se quedan sin señal durante el recorrido? ¿Cómo manejan esa situación actualmente?
5. ¿Cómo coordina internamente a su equipo (guías, base de operaciones, contactos de emergencia) durante el desarrollo de un tour?
6. ¿Lleva algún registro de los recorridos realizados, incidentes ocurridos o datos de los turistas durante el tour? ¿De qué forma?

**Preguntas sobre seguridad y gestión de emergencias**

7. ¿Ha vivido alguna situación de emergencia o incidente grave durante algún tour? ¿Cómo fue la respuesta? ¿Qué falló o qué hubiera necesitado tener disponible en ese momento?
8. ¿Cómo determina si un turista está en una condición de riesgo (fatiga extrema, mal de altura, extravío) cuando no está físicamente con el guía?
9. ¿Qué protocolos de seguridad tiene establecidos actualmente? ¿Los considera suficientes?
10. ¿Ha recibido alguna vez una queja, reclamo o acción legal relacionada con un incidente de seguridad? ¿Cómo afectó eso a su operación?

**Preguntas sobre tecnología y adopción**

11. ¿Utiliza actualmente alguna herramienta digital o software para gestionar sus operaciones (reservas, logística, comunicación con guías)? ¿Cuál es su experiencia con ella?
12. ¿Ha intentado implementar alguna solución tecnológica para el monitoreo en campo? ¿Qué resultó y qué no?
13. ¿Qué barreras considera que existen para que agencias como la suya adopten soluciones tecnológicas de monitoreo?

**Preguntas sobre disposición y expectativas**

14. Si existiera una plataforma que le permitiera ver en tiempo real la ubicación y estado de todos sus grupos activos desde un panel centralizado, ¿qué tan valiosa sería para usted? ¿Qué condiciones necesitaría para adoptarla?
15. ¿Estaría dispuesto a pagar una suscripción mensual por una solución así? ¿Qué rango de precio consideraría razonable?
16. ¿Qué funcionalidades consideraría indispensables y cuáles serían un plus? ¿Qué debería tener sí o sí desde el primer día?

---

##### Segmento 2: Turistas de Aventura

**Perfil del entrevistado:** personas que hayan realizado al menos una actividad de turismo de aventura en el Perú en los últimos dos años (trekking, montañismo, expedición en selva o ruta de naturaleza en zonas remotas), ya sean nacionales o extranjeros residentes en el país.

---

**Preguntas de apertura y contexto**

1. ¿Podría contarme sobre la última actividad de aventura que realizó en el Perú? ¿A dónde fue, qué ruta hizo y con quién?
2. ¿Con qué frecuencia realiza este tipo de actividades? ¿Suele contratar agencias o prefiere organizar sus propias expediciones?

**Preguntas sobre seguridad y experiencias previas**

3. Durante ese recorrido, ¿hubo momentos en los que se sintió inseguro o sin saber bien dónde estaba o cómo pedir ayuda? ¿Puede contarme ese momento?
4. ¿Alguna vez ha vivido o presenciado una emergencia o incidente durante un tour de aventura? ¿Cómo respondió la agencia o el guía?
5. ¿Siente que las agencias con las que ha viajado tienen mecanismos adecuados para garantizar su seguridad en caso de emergencia? ¿Por qué?
6. ¿Le preocupa la falta de conectividad o la dificultad para pedir ayuda cuando está en zonas remotas? ¿Cómo lo maneja actualmente?

**Preguntas sobre herramientas y tecnología usada**

7. ¿Qué aplicaciones o dispositivos utiliza durante sus actividades de aventura? (GPS, mapas offline, reloj deportivo, etc.) ¿Cuál es su experiencia con ellas?
8. ¿Comparte su ubicación con alguien (familiar, contacto de emergencia) durante el recorrido? ¿Cómo lo hace?
9. ¿Ha usado alguna aplicación que le permita ver su recorrido, registrar datos de salud (ritmo cardíaco, altitud) o documentar su experiencia durante el tour?

**Preguntas sobre expectativas e información durante el tour**

10. Durante un tour, ¿qué información le gustaría tener disponible en todo momento? (su posición en el mapa, distancia recorrida, signos vitales, clima, información sobre el lugar, etc.)
11. ¿Le resultaría útil poder ver en su teléfono información contextual del recorrido, como datos históricos del lugar, puntos de interés o alertas de riesgo específicas de la ruta?
12. ¿Cómo le gustaría registrar su experiencia durante el tour? ¿Fotos georreferenciadas, registros automáticos, notas de voz?

**Preguntas sobre confianza y adopción**

13. Si la agencia que contrató le ofreciera un dispositivo wearable que monitoree su ubicación y signos vitales durante el tour, ¿lo usaría? ¿Qué preguntas o dudas tendría al respecto?
14. ¿Tiene alguna preocupación sobre la privacidad de sus datos si una agencia monitorea su ubicación y salud en tiempo real?
15. ¿Cuánto influiría en su decisión de contratar una agencia el hecho de que esta cuente con tecnología de monitoreo en tiempo real y protocolos de emergencia avanzados?

---

##### Consideraciones Metodológicas

**Cantidad de entrevistas:** mínimo 3 y máximo 5 entrevistas por segmento (total: entre 6 y 10 entrevistas) para alcanzar saturación temática en una etapa de descubrimiento.

**Registro:** Las entrevistas deben ser grabadas con consentimiento del entrevistado para su posterior análisis. Se recomienda el uso de una guía de toma de notas que permita capturar citas textuales relevantes.

**Análisis:** Los resultados serán procesados mediante agrupamiento de respuestas por temática, identificando patrones comunes, necesidades no cubiertas y citas representativas para validar o refutar las hipótesis de problema y solución.

**Ética:** Antes de cada entrevista se informará al participante sobre el propósito de la investigación, la confidencialidad de sus respuestas y su derecho a retirarse en cualquier momento. No se recopilará información personal identificable más allá de la necesaria para el reclutamiento.

---

### 2.2.2. Registro de Entrevistas

##### Segmento 1: Dueños o responsables de agencia de turismo de aventura



**Entrevista 1:**

![Entrevista 1](../assets/images/New-Entrevista-2.png)

| | |
| :--- | :--- |
| **Entrevistador:** | Tony Jhunior Quispe Palomino |
| **Entrevistado:** | Mateo Escudero |
| **Edad:** | 22 años |
| **Segmento:** | Dueño o responsable de agencia de turismo de aventura |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | 11:05 min |
| **Enlace:** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQCf3pj989dtRqsxlQP-cphyAdmHJbpSw14HLGTRks5qOyM?e=L98d2n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D |

**Resumen:** Mateo Escudero, de 22 años y guía en Adventure Perú, apoya en la gestión de expediciones de turismo de aventura (principalmente trekking, montañismo y campamentos) en zonas como Cusco, Áncash y Madre de Dios. Nos comenta que la agencia maneja un equipo de 10 guías y atiende de 40 a 70 turistas en temporada alta, operando entre 4 y 7 grupos simultáneos. Actualmente, coordinan la operación mediante radios, llamadas, WhatsApp y hojas de cálculo o formularios básicos. Esto les genera dolores de cabeza importantes: la falta de señal de internet en las rutas de montaña dificulta la comunicación en tiempo real y la actualización oportuna de la ubicación de los grupos, además de provocar retrasos en la sincronización de datos y reportes dispersos. Asimismo, mencionó que se han enfrentado a situaciones críticas por mal de altura y fallas en la comunicación en zonas alejadas. Finalmente, muestra un gran interés en una solución tecnológica, señalando que se valoraría contar con mapas offline funcionales, un panel centralizado de monitoreo de grupos y un botón de pánico accesible incluso sin internet, considerando un rango de precio razonable de suscripción de 100 a 150 soles mensuales. Como principal barrera, destaca los costos, la necesidad de capacitación del personal y la falta de dispositivos avanzados en algunos guías.

---

**Entrevista 2:**

![Enrevista 2](../assets/images/Enrevista%203.png)

| |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| :--- |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistador:** | Molina Vásquez Manuel Alejandro                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Entrevistado:** | Aarón Espinosa                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Edad:** | 21 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Segmento:** | Dueño o responsable de agencia de turismo de aventura                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Inicio de la entrevista:** | 0:00                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Duración:** | 9:22 min                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Enlace:** | [Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAofZYR8ATPSbWHvKq3vOSvAZ1mk5uCZxK_sr8rN9qoqI4?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=CzroE4) https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAofZYR8ATPSbWHvKq3vOSvAZ1mk5uCZxK_sr8rN9qoqI4?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=CzroE4  |

**Resumen:** Aarón Espinosa representa a una agencia pequeña enfocada en turismo de aventura, caminatas, trekking y visitas culturales en la sierra peruana (principalmente Cusco, Arequipa y alrededores). En temporadas altas llegan a coordinar entre 10 y 15 guías simultáneamente, atendiendo de 50 a 100 turistas al día distribuidos en 5 a 8 grupos en ruta. Actualmente, el monitoreo lo realizan mediante llamadas telefónicas, la función de ubicación compartida y grupos de WhatsApp, mientras que la información operativa la manejan de forma dispersa en hojas de Microsoft Excel y chats. Manifiesta que la pérdida total de señal móvil en zonas de altura y senderos aislados es sumamente frecuente; ante ello, no cuentan con contingencias técnicas y se limitan a esperar a que el guía recupere cobertura para reportar. Toda la supervisión de la condición física de los turistas recae exclusivamente en la observación presencial del guía. Entre los incidentes habituales reporta casos de descompensación por mal de altura y agotamiento físico extremo. Señala que la falta de conectividad dificulta actuar con rapidez desde la base, lo que deriva en reclamos de clientes y deteriora la reputación de la empresa. Aarón considera indispensable una solución que funcione sin señal móvil (almacenando datos localmente hasta reconectar), que centralice la ubicación y ofrezca comunicación directa con alertas tempranas. Como funcionalidades de valor agregado destaca los reportes de recorridos y el historial de incidentes. Estaría dispuesto a adoptar un modelo de suscripción mensual con un rango de pago estimado entre S/. 150 y S/. 300.

**Entrevista 3:**

![Entrevista 3](../assets/images/Entrevista%207.png)

| |                                                                                                                                                                                                                                                                                                                                              |
| :--- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistador:** | Frank Anthony Huingo Tello                                                                                                                                                                                                                                                                                                             |
| **Entrevistado:** | Carlos Gutierrez                                                                                                                                                                                                                                                                                                                      |
| **Edad:** | 20 años                                                                                                                                                                                                                                                                                                                                      |
| **Segmento:** | Dueño o responsable de agencia de turismo de aventura                                                                                                                                                                                                                                                                                                                      |
| **Inicio de la entrevista:** | 0:00                                                                                                                                                                                                                                                                                                                                         |
| **Duración:** | 5:05 min                                                                                                                                                                                                                                                                                                                                    |
| **Enlace:** | [Entrevista-7](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202319057_upc_edu_pe/IQBoi_IK-HcUQI1SdenjhHQkAbMGfRPdITIGilUq4MH0xug?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=RhDf3F)|

**Resumen:** Carlos Gutiérrez representa a una agencia enfocada en tours de trekking y naturaleza, principalmente en los circuitos andinos del sur, como Cusco y Huaraz, trabajando con guías locales especializados. Durante temporada alta manejan entre 5 y 10 guías, aproximadamente 100 turistas al mes y hasta 3 grupos simultáneos activos en ruta. Actualmente, el seguimiento en campo se realiza mediante radios VHF en zonas sin señal y llamadas o WhatsApp cuando existe cobertura celular, mientras que los recorridos e incidentes se registran manualmente en bitácoras de papel y posteriormente se trasladan a hojas de Excel. Señala que la pérdida de señal es muy frecuente en quebradas y zonas de alta montaña, por lo que utilizan puntos de reporte obligatorios en campamentos o cumbres y dependen de los reportes del guía para conocer el estado de los pasajeros. Entre los principales problemas identifica la demora en la comunicación durante emergencias, especialmente ante casos de soroche y fatiga, así como las dificultades para actuar rápidamente cuando el guía se encuentra sin cobertura. Aunque cuentan con protocolos básicos de evacuación, considera que la falta de comunicación en tiempo real los vuelve lentos y puede generar reclamos por retrasos en la atención. Actualmente utilizan Excel para reservas y WhatsApp para la coordinación, pero no cuentan con software especializado debido principalmente al costo, la resistencia del personal a aplicaciones complejas y la falta de conectividad. Carlos considera que una plataforma de monitoreo en tiempo real sería sumamente valiosa para mejorar la tranquilidad y capacidad de respuesta de la agencia. Estaría dispuesto a pagar una suscripción mensual de entre $30 y $80, siempre que el costo sea adecuado para una agencia pequeña o mediana. Entre las funcionalidades indispensables desde el primer día destaca un botón SOS de emergencia, mapas offline y visualización básica de la ubicación de los grupos.

---

##### Segmento 2: Turistas de Aventura

**Entrevista 4:**

![Entrevista 4](../assets/images/New-Entrevista-4.png)

| | |
| :--- | :--- |
| **Entrevistador:** | Tony Jhunior Quispe Palomino |
| **Entrevistado:** | Sofia Mendoza |
| **Edad:** | 20 años |
| **Segmento:** | Turista de Aventura |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | 11:48 min |
| **Enlace:** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQBPxk5ihQP7Qpk1EiObhUKMAcqE0PkmidpljYmgsKZhw60?e=y94DfE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D |

**Resumen:** Sofía Mendoza, de 20 años y aficionada a las actividades de aventura, nos comparte su experiencia participando en excursiones y viajes en el Perú, como sus recorridos en bicicleta en Lambayeque o sus visitas a la reserva de Paracas. Nos comenta que suele realizar estas actividades unas tres veces al año durante sus vacaciones y que prefiere organizarlas por cuenta propia o guiada cuando no tiene conocimiento previo del lugar. Respecto a sus principales preocupaciones y dolores de cabeza, destaca la falta de conectividad e internet en zonas remotas de montaña o rutas peligrosas, la dificultad para pedir ayuda o ubicarse ante imprevistos, y el mal estado de las carreteras debido a lluvias o bloqueos, recordando un incidente crítico por el clima cuando viajaba hacia la selva y las agencias no ofrecieron protocolos o advertencias de seguridad adecuados. Finalmente, muestra un gran interés en una solución tecnológica o dispositivo que le permita ver información contextual en tiempo real —como mapas, clima, historia del lugar y puntos de interés—, valorando positivamente que cuente con monitoreo o protocolos de emergencia avanzados, siempre y cuando sea accesible y no exceda su presupuesto.

---

**Entrevista 5:**

![Entrevista 5](../assets/images/Entrevista%205.png)

| |                                                                                                                                                                                                                                                                                                                                              |
| :--- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistador:** | Manuel Alejandro Molina Vásquez                                                                                                                                                                                                                                                                                                              |
| **Entrevistado:** | Romina Antonella Molina Vásquez                                                                                                                                                                                                                                                                                                              |
| **Edad:** | 18 años                                                                                                                                                                                                                                                                                                                                      |
| **Segmento:** | Turista de Aventura                                                                                                                                                                                                                                                                                                                          |
| **Inicio de la entrevista:** | 0:00                                                                                                                                                                                                                                                                                                                                         |
| **Duración:** | min                                                                                                                                                                                                                                                                                                                                          |
| **Enlace:** | [Entrevista5](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAQPNKuz_cKS4krk8KnLmoKAaAOQuWIL6WmZXL4T30cJJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=B3HGgd) https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAQPNKuz_cKS4krk8KnLmoKAaAOQuWIL6WmZXL4T30cJJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=B3HGgd |

**Resumen:** Romina Antonella es una usuaria joven que realiza actividades de aventura y trekking durante sus periodos vacacionales (aproximadamente una vez cada dos semanas). Suelen ser salidas en grupos de amigos de forma independiente en expediciones cortas (como caminatas hacia lagunas en Caraz), o mediante agencias turísticas cuando visita destinos tradicionales como Cusco y Machu Picchu. Durante sus recorridos no lleva equipamiento especializado; suele portar únicamente su teléfono móvil y audífonos, empleando la función nativa de ubicación compartida en tiempo real de WhatsApp para reportarse con sus padres. Manifiesta preocupación frente a la pérdida total de cobertura celular en zonas remotas, reconociendo la incertidumbre de no saber cómo comunicarse con sus familiares o pedir ayuda si ocurriese un accidente grave; ante ello, actualmente solo depende de la confianza en sus acompañantes. Si bien no ha presenciado emergencias extremas (solo incidentes médicos menores resueltos por guías locales), expresa que la información más valiosa que desearía tener disponible en todo momento son las alertas de riesgo y la identificación de zonas seguras ante peligros naturales (terremotos o avalanchas). Asimismo, documenta activamente sus recorridos tomando fotos, grabando videos y generando contenido para redes sociales en el trayecto. Respecto al uso de dispositivos wearables y tecnología de monitoreo biométrico y de geolocalización provista por una agencia, afirma que estaría totalmente dispuesta a usarlos si se le explican claramente su funcionamiento y propósitos. No le genera inconvenientes la privacidad de sus datos de salud o ubicación mientras este rastreo se limite estrictamente a la duración de la excursión. Aunque actualmente la adopción de tecnología avanzada no determina de forma crítica su elección de agencia (dada la escasa oferta tecnológica en el mercado local), considera que implementar estos sistemas sería una adición positiva y valiosa para modernizar el sector.

**Entrevista 6:**

![Entrevista 6](../assets/images/Entrevista-6.png)

| |                                                                                                                                                                                                                                                                                                                                              |
| :--- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistador:** | Giancarlo Verastigue Martinez                                                                                                                                                                                                                                                                                                                |
| **Entrevistado:** | Miler Rodriguez                                                                                                                                                                                                                                                                                                                              |
| **Edad:** | 22 años                                                                                                                                                                                                                                                                                                                                      |
| **Segmento:** | Turista de Aventura                                                                                                                                                                                                                                                                                                                          |
| **Inicio de la entrevista:** | 0:00                                                                                                                                                                                                                                                                                                                                         |
| **Duración:** | 10:05 min                                                                                                                                                                                                                                                                                                                                    |
| **Enlace:** | [Entrevista-6](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDe0UWGvKUwRojgbs_XPIuJAclsUfNSUJK04_8jjCFOE7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Szx6cw) https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDe0UWGvKUwRojgbs_XPIuJAclsUfNSUJK04_8jjCFOE7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Szx6cw|

**Resumen:**

El análisis de la entrevista con Miller, un viajero que realiza trekking de manera ocasional, revela información clave sobre el comportamiento y las necesidades urgentes de los aventureros en zonas remotas. Aunque suele organizarse de forma independiente con amigos para rutas conocidas, Miller prefiere contratar agencias y guías para trayectos más complejos. Durante estas expediciones, su principal punto de dolor es la pérdida de señal celular, lo cual genera una gran incertidumbre sobre la ubicación exacta y la ruta a seguir. A esto se suma la percepción de que las agencias a menudo carecen de protocolos de emergencia claros frente a problemas de salud o fatiga extrema del grupo. Si bien actualmente intenta mitigar estos riesgos compartiendo su ubicación y descargando mapas sin conexión, estas herramientas terminan perdiendo su utilidad principal al no contar con cobertura de red.


**Entrevista 7:**

![Entrevista 7](../assets/images/entrevista7.png)

| |                                                                                                                                                                                                                                                                                                                                              |
| :--- |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Entrevistador:** | Matias Renato Carrillo Acho                                                                                                                                                                                                                                                                  |
| **Entrevistado:** | Alberto Joaquin Alfaro Mallma                                                                                                                                                                                                                                                                                                                              |
| **Edad:** | 25 años                                                                                                                                                                                                                                                                                                                                      |
| **Segmento:** | Turista de Aventura                                                                                                                                                                                                                                                                                                                          |
| **Inicio de la entrevista:** | 0:00                                                                                                                                                                                                                                                                                                                                         |
| **Duración:** | 06:25 min                                                                                                                                                                                                                                                                                                                                    |
| **Enlace:** | [Entrevista-7](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202323010_upc_edu_pe/IQAUJbSUxGQ-RrATzxOjZawRAVmvkpuEsfg7qOf-p29IYXk?e=BFlFkq&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)|

**Resumen:** Alberto Joaquin Alfaro Mallma, 25 años. Su ultimo viaje fue hacia la laguna 69 en la cordillera blanca, además señala que contrato a una agencia con guía incluido. Frecuentemente prefiere contratar a una agencia turistica para realizar viajes o tours, tambien señala que ha vivido percances durante el tour siendo uno de estos la falta de señal y comunicación. Menciona que la seguridad en tours depende exclusivamente de la agencia y de la preparación de los guías designados, además señala que utiliza mapas offlines, gps y relojes inteligentes como herramientas durante el tour.

---


## 2.3. Needfinding
 
En esta sección se presentan los artefactos resultantes del proceso de análisis de la información recolectada durante la fase de Needfinding. A partir de las entrevistas realizadas a los segmentos objetivo y del análisis competitivo desarrollado en el capítulo anterior, el equipo ha sintetizado los hallazgos en artefactos que permiten visualizar de forma estructurada las características, comportamientos, motivaciones y necesidades de los usuarios potenciales de Tourmate. Estos artefactos servirán como base para la definición de requerimientos funcionales y de diseño de la solución, asegurando que cada decisión esté centrada en el usuario y respaldada por evidencia recolectada en campo.
 
### 2.3.1. User Personas
 
A continuación se presentan las fichas de User Persona elaboradas para cada uno de los dos segmentos objetivo de Tourmate, identificados previamente en la sección de Segmentos Objetivo del capítulo anterior. La elaboración de estos arquetipos se sustenta en el análisis cualitativo de las entrevistas realizadas a representantes de cada segmento, así como en los hallazgos obtenidos del análisis competitivo, donde se evidenciaron brechas en la oferta actual de productos digitales para turismo de aventura en zonas de baja conectividad.
 
Las principales características consideradas para la construcción de los User Personas incluyen los datos demográficos, ocupación, comportamiento digital, motivaciones, frustraciones, objetivos personales y profesionales, así como el nivel de adopción tecnológica de cada segmento. Esta información fue contrastada con las debilidades detectadas en competidores como TrekkSoft, Wayward y AllTrails, especialmente en lo referente a la operatividad sin conectividad, la captura de signos vitales y la falta de personalización para el contexto peruano. De esta manera, los arquetipos no solo representan a los usuarios, sino que también encapsulan las oportunidades de diferenciación que Tourmate puede capitalizar.
 
Se ha elaborado una ficha de User Persona por cada segmento objetivo, utilizando la herramienta UXPressia siguiendo las mejores prácticas de la industria. El primer User Persona, Ana Lucía Quispe, representa al segmento de agencias y operadores de turismo de aventura, mientras que el segundo, Marco Rodriguez, representa al segmento de turistas de aventura nacionales y extranjeros que contratan los servicios de estas agencias.
 
**User Persona 1: Ana Lucía Quispe - Segmento de Dueños o Responsables de Agencias de Turismo de Aventura**
 
![](../assets/images/User-Persona1.png)

Representa al segmento de agencias y operadores de turismo de aventura. Este arquetipo encarna a la gerente de operaciones de una agencia mediana en Cusco, responsable de coordinar guías, supervisar tours simultáneos y garantizar la seguridad de los grupos en zonas remotas. Sus motivaciones giran en torno a la profesionalización operativa, la reducción del tiempo de respuesta ante emergencias y la diferenciación competitiva mediante el uso de tecnología. Sus principales frustraciones se relacionan con la pérdida de comunicación con los guías por horas, la dependencia de WhatsApp y radios analógicas, y la ausencia de herramientas digitales adaptadas al contexto y al presupuesto de una micro o pequeña empresa peruana.

**User Persona 2: Marco Rodriguez - Segmento de Turistas de Aventura**
 
![](../assets/images/User-Persona2.png)

Representa al segmento de turistas de aventura nacionales y extranjeros. Este arquetipo encarna al viajero europeo experimentado, con alto poder adquisitivo, dominio tecnológico y pasión por las experiencias outdoor auténticas. Sus motivaciones se centran en vivir aventuras seguras y memorables, mantener informados a sus familiares durante el recorrido y enriquecer su experiencia con información cultural e histórica del entorno. Sus frustraciones más relevantes son la incertidumbre sobre su ubicación al perder señal GPS, la imposibilidad de avisar a su familia durante varios días, y la carencia de aplicaciones móviles que funcionen sin conectividad continua en zonas remotas del Perú.

### 2.3.2. User Task Matrix

A continuación se presenta el User Task Matrix, artefacto que concentra las principales tareas que los User Personas realizan para cumplir sus objetivos en el dominio del turismo de aventura. Es importante precisar que las tareas listadas corresponden a actividades que ambos segmentos llevan a cabo de manera independiente a la existencia de Tourmate, ya que reflejan el comportamiento natural y las responsabilidades inherentes a cada rol dentro del ecosistema del turismo de aventura. Los segmentos considerados en esta matriz son las agencias y operadores de turismo de aventura, representados por Ana Lucía Quispe, y los turistas de aventura nacionales y extranjeros, representados por Marco Rodriguez.

Para cada User Persona se evalúan dos dimensiones por tarea. La frecuencia indica con qué regularidad realiza la tarea, expresada en una escala cualitativa de Muy Alta, Alta, Media, Baja o Muy Baja. La importancia indica el grado en que la tarea es crítica para el cumplimiento de los objetivos del User Persona, expresada en la misma escala. Cuando una tarea no aplica para un User Persona específico, se indica con la abreviatura N/A.

| **User Task**                                                         | **Ana Lucía Quispe (Frecuencia)** | **Ana Lucía Quispe (Importancia)** | **Marco Rodríguez (Frecuencia)** | **Marco Rodríguez (Importancia)** |
|-----------------------------------------------------------------------|-----------------------------------|------------------------------------|----------------------------------|-----------------------------------|
| Planificar el itinerario y la logística del recorrido                 | Always                            | Very High                          | Often                            | High                              |
| Coordinar con guías y personal operativo en campo                     | Always                            | Very High                          | N/A                              | N/A                               |
| Supervisar la ubicación y el estado de los grupos durante el tour     | Always                            | Very High                          | N/A                              | N/A                               |
| Comunicarse con familiares para informar el estado durante el viaje   | Rarely                            | Medium                             | Always                           | Very High                         |
| Reaccionar ante emergencias o anomalías en ruta                       | Sometimes                         | Very High                          | Rarely                           | Very High                         |
| Registrar la asistencia y datos personales de los turistas            | Often                             | High                               | Often                            | Medium                            |
| Investigar y comparar agencias o servicios turísticos                 | Sometimes                         | High                               | Always                           | Very High                         |
| Reservar y pagar los servicios de tours de aventura                   | Often                             | High                               | Often                            | Very High                         |
| Orientarse y navegar durante el recorrido en zonas remotas            | Sometimes                         | High                               | Always                           | Very High                         |
| Documentar la experiencia mediante fotografías y notas                | Rarely                            | Medium                             | Always                           | High                              |
| Acceder a información cultural e histórica del recorrido              | Rarely                            | Medium                             | Often                            | Very High                         |
| Monitorear los signos vitales y el estado físico durante la actividad | Rarely                            | High                               | Often                            | High                              |
| Generar reportes operativos y financieros del tour                    | Always                            | Very High                          | N/A                              | N/A                               |
| Recopilar feedback y reseñas posteriores al servicio                  | Often                             | High                               | Sometimes                        | Medium                            |
| Compartir la experiencia en redes sociales y comunidades de viajeros  | Sometimes                         | Medium                             | Often                            | High                              |
| Gestionar la facturación y los pagos a guías o proveedores            | Always                            | Very High                          | N/A                              | N/A                               |
| Capacitarse en protocolos de seguridad y rutas nuevas                 | Sometimes                         | High                               | Rarely                           | Medium                            |

**Análisis de los resultados de la matriz**

A partir del análisis de la matriz se identifican patrones claros que evidencian las prioridades y comportamientos de cada User Persona, así como los puntos de convergencia y divergencia entre ambos segmentos:

En el caso de Ana Lucía Quispe, las tareas con mayor frecuencia e importancia se concentran en la dimensión operativa y de supervisión. La planificación del itinerario, la coordinación con guías, la supervisión de la ubicación y estado de los grupos, la generación de reportes operativos y la gestión de la facturación constituyen el núcleo de su actividad diaria. Estas tareas reflejan su rol como gerente de operaciones y subrayan la criticidad de contar con herramientas que faciliten la trazabilidad y la comunicación con los equipos en campo. Adicionalmente, la reacción ante emergencias, aunque presenta una frecuencia media, mantiene una importancia muy alta debido al impacto que tiene sobre la seguridad de los turistas y la reputación de la agencia.

En el caso de Marco Rodriguez, las tareas con mayor frecuencia e importancia se orientan hacia la dimensión experiencial y de seguridad personal. La investigación y comparación de agencias previa al viaje, la reserva y pago de servicios, la orientación y navegación en zonas remotas, la comunicación con familiares y el acceso a información cultural e histórica constituyen las actividades centrales de su comportamiento como turista de aventura. La documentación de la experiencia mediante fotografías y notas también ocupa un lugar relevante, lo que refleja el perfil del viajero contemporáneo que busca compartir y conservar memorias de sus aventuras.

Entre las principales coincidencias entre ambos User Personas destaca la relevancia que ambos otorgan a la planificación del itinerario y a la reserva de servicios, aunque desde perspectivas distintas. Mientras Ana Lucía planifica la logística operativa del lado de la oferta, Marco planifica su experiencia desde el lado de la demanda. Otra coincidencia importante es la criticidad de la reacción ante emergencias, que aunque ocurre con baja frecuencia, ambos consideran muy importante por sus implicancias en seguridad y bienestar. Finalmente, ambos User Personas comparten la necesidad de orientarse y navegar en zonas remotas, lo cual refuerza la importancia de contar con herramientas digitales que operen sin conectividad continua.

Entre las principales diferencias se observa que las tareas relacionadas con la supervisión de grupos, la generación de reportes operativos, la gestión de facturación y la coordinación con guías son exclusivas del User Persona de la agencia, mientras que las tareas vinculadas a la documentación de la experiencia, el acceso a información cultural y el compartir contenido en redes sociales son predominantes en el User Persona del turista. Esta diferenciación valida el enfoque dual de la propuesta de valor de Tourmate, donde la plataforma debe atender tanto las necesidades operativas y de control de las agencias como las expectativas experienciales y de seguridad personal de los turistas.

#### 2.3.3. User Journey Mapping

El User Journey Mapping es una herramienta que permite visualizar de forma estructurada la experiencia del usuario a lo largo de su interacción con un producto o servicio. Realizamos los User Journey Maps en su versión As-Is para los tres segmentos objetivos.

<b>User Journey Map del 1er segmento objetivo – agencias y operadores de turismo</b>
![](../assets/images/jm-segmento-1.png)

<b>User Journey Map del 2do segmento objetivo - turistas de aventura </b>
![](../assets/images/jm-segmento-2.png)

### 2.3.4. Empathy Mapping

El Empathy Mapping es una herramienta que nos permite profundizar en la experiencia emocional y cognitiva del usuario. A través de categorías como lo que el usuario piensa, siente, dice y hace, se busca comprender su contexto, así como sus principales miedos, frustraciones y motivaciones.

Para Tourmate, elaborar un Empathy Mapping para cada segmento objetivo fue clave para entender no solo cómo las agencias planifican la logística y cómo los turistas viven la experiencia outdoor, sino también cómo enfrentan la incertidumbre de la desconexión en zonas remotas, los retos de seguridad y la respuesta ante posibles emergencias. Esta comprensión más empática nos permite diseñar un ecosistema tecnológico que responda a sus necesidades reales, brindando tranquilidad y reduciendo los puntos de dolor presentes en la gestión actual de las rutas de aventura.

<b>Empathy Mapping del 1er segmento objetivo – agencias y operadores de turismo</b>
![](../assets/images/Empathy-Map1.png)

<b>Empathy Mapping del 2do segmento objetivo – turistas de aventura </b>
![](../assets/images/Empathy-Map2.png)

### 2.3.5. As-is Scenario Mapping.

El As-is Scenario Mapping permite representar cómo los usuarios realizan actualmente sus actividades antes de utilizar Tourmate. Este análisis se construye a partir de las entrevistas, los User Personas, el User Task Matrix, los User Journey Maps y los Empathy Maps. Su objetivo es identificar acciones, pensamientos, emociones y oportunidades de mejora dentro del flujo actual de trabajo de cada segmento.

### As-is Scenario Mapping: Agencia y Operador de Turismo de Aventura

**User Persona:** Ana Lucía Quispe  
**Escenario:** Coordinación y supervisión manual de tours en zonas remotas sin herramientas digitales de monitoreo.

| Etapa | Actividades actuales | Pensamientos del usuario | Emociones | Pain points | Oportunidades para Tourmate |
|-------|----------------------|--------------------------|-----------|-------------|-------------------------------|
| Planificación del tour | Organiza el itinerario, asigna guías y coordina la logística mediante hojas de cálculo y conversaciones directas con su equipo. | "Espero no haber olvidado coordinar algo con los guías." | Concentración y responsabilidad. | La planificación depende de múltiples canales dispersos, sin un sistema único de gestión. | Centralizar la creación y gestión de tours, guías y rutas en un solo panel operativo. |
| Salida del grupo a campo | Envía a los guías con instrucciones verbales o por WhatsApp y radios analógicas, sin visibilidad continua de su ubicación. | "Una vez que salen a la ruta, ya no sé mucho de ellos hasta que regresan o me escriben." | Incertidumbre y confianza forzada. | La ausencia de monitoreo en tiempo real genera una desconexión total durante horas. | Ofrecer un dashboard con ubicación y estado de los grupos en tiempo real, incluso en zonas sin señal continua. |
| Seguimiento durante el recorrido | Espera mensajes intermitentes de los guías cuando logran obtener señal, sin poder anticipar problemas de salud o seguridad. | "Si algo pasa y no tengo señal, no me voy a enterar a tiempo." | Ansiedad y sensación de vulnerabilidad. | La dependencia de la señal celular expone a la agencia a horas de comunicación perdida. | Habilitar sincronización asincrónica y alertas automáticas ante anomalías en signos vitales o ubicación. |
| Reacción ante una emergencia | Recibe la noticia del incidente tarde, muchas veces horas después, y debe improvisar una respuesta sin protocolo definido. | "Necesito saber de inmediato si algo sale mal, no cuando ya sea demasiado tarde." | Urgencia y estrés. | La falta de un botón de emergencia y protocolos claros retrasa la respuesta y pone en riesgo a los turistas. | Implementar alertas críticas con protocolo de respuesta sugerido y contacto inmediato con el guía en campo. |
| Cierre del tour y reportes | Reconstruye manualmente lo ocurrido durante el tour a partir de mensajes, notas y el relato de los guías para generar reportes y facturación. | "Ojalá pueda armar el reporte con la información que tengo, aunque esté incompleta." | Cansancio y falta de respaldo documentado. | La información dispersa dificulta la elaboración de reportes confiables y la trazabilidad del servicio. | Generar reportes operativos y financieros automáticos a partir de los datos registrados durante el tour. |

### As-is Scenario Mapping: Turista de Aventura

**User Persona:** Marco Rodriguez  
**Escenario:** Exploración de rutas remotas dependiendo de aplicaciones sin funcionamiento offline y sin monitoreo de salud.

| Etapa | Actividades actuales | Pensamientos del usuario | Emociones | Pain points | Oportunidades para Tourmate |
|-------|----------------------|--------------------------|-----------|-------------|-------------------------------|
| Investigación previa al viaje | Compara agencias y servicios turísticos en internet y redes sociales antes de reservar su tour de aventura. | "Quiero elegir una agencia que realmente me garantice seguridad en la ruta." | Expectativa y cautela. | La información sobre seguridad y protocolos de las agencias suele ser limitada o poco verificable. | Mostrar de forma transparente las capacidades de monitoreo y seguridad que ofrece la agencia asociada a Tourmate. |
| Inicio del recorrido | Utiliza aplicaciones de mapas convencionales para orientarse y comparte su ubicación con familiares antes de perder señal. | "Espero que la señal aguante un poco más antes de entrar a la zona sin cobertura." | Entusiasmo mezclado con preocupación. | Las aplicaciones dependen de conexión continua, lo que genera vacíos de información apenas se pierde la señal. | Ofrecer navegación y registro de ubicación con funcionamiento offline mediante sincronización asincrónica. |
| Pérdida de señal en zona remota | Continúa el recorrido sin poder confirmar su ubicación exacta ni informar a su familia sobre su estado. | "No sé si mi familia sabe que sigo bien, y yo tampoco puedo confirmarlo." | Incertidumbre y aislamiento. | La imposibilidad de comunicarse durante varios días genera ansiedad tanto en el turista como en sus familiares. | Registrar y sincronizar automáticamente la ubicación y el estado del turista apenas se recupera la conectividad. |
| Actividad física exigente | Realiza la actividad de aventura sin ningún dispositivo que monitoree su estado físico o signos vitales. | "Si algo me pasara aquí, nadie lo sabría hasta que sea muy tarde." | Vulnerabilidad y autoexigencia. | La falta de monitoreo de signos vitales limita la capacidad de reacción ante una emergencia médica. | Capturar signos vitales mediante wearables IoT y generar alertas ante anomalías detectadas durante la actividad. |
| Cierre del recorrido | Documenta su experiencia con fotografías y notas personales, sin registro contextual automático del recorrido realizado. | "Me hubiera gustado tener más información histórica y cultural mientras avanzaba en la ruta." | Satisfacción parcial y nostalgia. | La experiencia carece de información contextual enriquecida y de un registro digital estructurado del recorrido. | Ofrecer información contextual del recorrido y registro automático de experiencia, fotos y ruta completada. |

---

## 2.3.6. To-be Scenario Mapping.

El To-be Scenario Mapping representa cómo los usuarios realizarán sus actividades una vez implementada la plataforma Tourmate, contrastando directamente con el As-is Scenario Mapping presentado anteriormente. Este análisis muestra cómo las funcionalidades del ecosistema (monitoreo en tiempo real, sincronización asincrónica, wearables IoT y alertas automáticas) transforman las etapas identificadas, reduciendo la incertidumbre, el tiempo de reacción y la dependencia de procesos manuales.

### To-be Scenario Mapping: Agencia y Operador de Turismo de Aventura

**User Persona:** Ana Lucía Quispe  
**Escenario:** Coordinación y supervisión de tours en zonas remotas mediante el dashboard en tiempo real de Tourmate.

| Etapa | Actividades con Tourmate | Pensamientos del usuario | Emociones | Mejora respecto al As-is | Valor entregado por Tourmate |
|-------|----------------------------|---------------------------|-----------|---------------------------|-------------------------------|
| Planificación del tour | Crea el tour desde el panel web, define checkpoints, asigna guías y turistas, y publica el itinerario en un solo flujo. | "Todo el tour queda armado y visible para mi equipo desde el primer momento." | Organización y control. | Reemplaza hojas de cálculo y coordinación dispersa por un flujo único de creación de tour. | Centraliza la planificación en el módulo de Tour Management. |
| Salida del grupo a campo | Verifica el estado de los wearables y del grupo antes de iniciar la expedición, con confirmación automática en el sistema. | "Puedo confirmar que todos los dispositivos están activos antes de que salgan a ruta." | Confianza y tranquilidad. | Elimina la incertidumbre de enviar al grupo sin visibilidad; ahora hay una verificación previa registrada. | El flujo de inicio de expedición asegura que el monitoreo esté activo desde el primer checkpoint. |
| Seguimiento durante el recorrido | Supervisa la ubicación y signos vitales de cada turista en el dashboard Live Monitoring, incluso con datos sincronizados de forma asincrónica. | "Aunque no haya señal continua, sé que la información llegará apenas se recupere la conexión." | Seguridad y control continuo. | Sustituye la espera pasiva de mensajes por un panel activo con datos estructurados por participante. | La sincronización asincrónica y el dashboard matricial permiten monitoreo sin depender de señal constante. |
| Reacción ante una emergencia | Recibe una alerta automática generada por anomalías en signos vitales o ubicación, y responde siguiendo el protocolo sugerido por el sistema. | "En cuanto algo se sale de lo normal, el sistema me avisa antes de que se convierta en una emergencia mayor." | Rapidez y seguridad operativa. | Reduce el tiempo de reacción de horas a minutos, reemplazando la espera de un mensaje de auxilio. | Las alertas automáticas y el módulo de Incidents agilizan la respuesta y dejan registro trazable del evento. |
| Cierre del tour y reportes | Genera automáticamente el reporte operativo del tour a partir de los datos registrados durante la expedición. | "El reporte ya está armado con toda la información real del recorrido." | Satisfacción y respaldo documentado. | Elimina la reconstrucción manual de lo ocurrido a partir de mensajes y notas sueltas. | Los reportes post-tour se generan a partir de la telemetría y los checkpoints registrados en el sistema. |

### To-be Scenario Mapping: Turista de Aventura

**User Persona:** Marco Rodriguez  
**Escenario:** Exploración de rutas remotas utilizando la aplicación móvil de Tourmate con navegación offline y monitoreo de salud.

| Etapa | Actividades con Tourmate | Pensamientos del usuario | Emociones | Mejora respecto al As-is | Valor entregado por Tourmate |
|-------|----------------------------|---------------------------|-----------|---------------------------|-------------------------------|
| Investigación previa al viaje | Revisa el perfil de la agencia y confirma que utiliza Tourmate para monitoreo y seguridad antes de reservar. | "Esta agencia sí muestra cómo cuidan a sus turistas en ruta." | Confianza y expectativa positiva. | Sustituye la incertidumbre sobre la seguridad de la agencia por información verificable. | La integración con Tourmate se convierte en un diferenciador visible para el turista al elegir agencia. |
| Inicio del recorrido | Descarga el mapa y la ruta desde la app antes de salir, y su wearable comienza a sincronizarse con el sistema. | "Ya tengo todo descargado, no dependo de que haya señal." | Preparación y tranquilidad. | Reemplaza la dependencia de aplicaciones de mapas online por navegación 100% offline. | El módulo de Navigation & Exploration permite descargar rutas y operar sin conexión continua. |
| Pérdida de señal en zona remota | Continúa el recorrido con normalidad; la app sigue registrando ubicación y signos vitales localmente para sincronizarlos después. | "No tengo señal, pero sé que mi información se está guardando y se enviará apenas se pueda." | Calma y confianza en el sistema. | Elimina la ansiedad y el aislamiento comunicativo que antes generaba la pérdida de señal. | La sincronización asincrónica asegura continuidad de datos sin necesidad de conexión constante. |
| Actividad física exigente | Su wearable monitorea continuamente su frecuencia cardíaca y SpO₂, enviando una alerta automática si detecta una anomalía. | "Si algo me pasara, mi guía y la agencia lo sabrían de inmediato." | Seguridad y confianza en su propio cuerpo. | Sustituye la ausencia total de monitoreo por vigilancia constante de signos vitales con alertas activas. | El ecosistema de wearables IoT y las alertas automáticas habilitan una respuesta médica más rápida. |
| Cierre del recorrido | Recibe automáticamente su diario de viaje generado con fotos georreferenciadas, ruta completada y datos de salud del recorrido. | "Tengo un registro completo de mi experiencia sin haber tenido que armarlo yo mismo." | Satisfacción y sensación de logro. | Reemplaza la documentación manual y dispersa por un registro automático y enriquecido de la experiencia. | El módulo de registro automático (auto-generated journal) entrega contexto, fotos y datos de salud sin intervención manual. |

En conjunto, el To-be Scenario Mapping evidencia que Tourmate no elimina la naturaleza riesgosa del turismo de aventura, pero sí transforma la forma en que agencias y turistas se preparan, se comunican y reaccionan ante ella: la incertidumbre pasiva del escenario As-is es reemplazada por visibilidad activa, respuesta automatizada y registro trazable en cada etapa del recorrido.

---

## 2.4. Big Picture Event Storming

En esta sección se presenta el Big Picture Event Storming del proyecto TourMate, elaborado como una visión general del dominio del turismo de aventura (Adventure Tourism) en zonas de baja conectividad. Mediante una sesión colaborativa, el equipo identificó y ordenó los eventos más importantes que ocurren durante un tour, desde la planificación hasta el cierre.

Ahora, aquí se va a explicar a paso a paso como se desarrollo el Big Picture Event Storming:

* Para empezar, antes de poner los Post-its, dividimos todo este Event Storming en Etapas, basandonos en el As-is Scenario Mapping:

![Big Picture EventStorming 1](../assets/images/New-Big-Picture-Evenstorming-1.png)

* Luego, ubicamos todos los Post-its, que representan los Eventos de Dominio (Domain Events) en sus respectivas etapas:

![Big Picture EventStorming 2](../assets/images/NewBigPictureEvenstorming2.jpeg)

* Después de esto, creamos la sección de "Problems", donde identificamos todos los problemas que se pueden presentar en las etapas del turismo:

![Big Picture EventStorming 3](../assets/images/NewBigPictureEvenstorming3.jpeg)

* Finalmente, en la sección de "Opportunities" identificamos todas las oportunidades de mejora:

![Big Picture EventStorming](../assets/images/NewBigPictureEvenstorming.jpeg)

Mediante este proceso, al identificar las oportunidades de mejora, logramos definir mejor el cómo vamos a desarrollar nuestra plataforma.

---

## 2.5 Ubiquitous Language

### Introducción

El siguiente glosario define los términos clave del dominio de turismo de aventura en zonas de baja conectividad. Su propósito es establecer un lenguaje común entre todos los stakeholders, evitando ambigüedades y facilitando la comunicación dentro del proyecto.

### Glosario

| Term (English)              | Término (Español)                | Definition (Definición)                                                                                                                                  |
| :--------------------------- | :-------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Adventure Tour**            | Tour de Aventura                  | Actividad organizada que involucra recorridos en entornos naturales, generalmente con cierto nivel de riesgo y condiciones variables. |
| **Tour Operator**             | Operador de Turismo / Agencia     | Entidad responsable de planificar, organizar y supervisar tours de aventura, asegurando la logística y seguridad del grupo. |
| **Tour Guide**                | Guía de Turismo                   | Persona encargada de liderar al grupo durante el recorrido, brindando orientación, asistencia y apoyo en situaciones de riesgo. |
| **Traveler**                  | Turista / Viajero                 | Persona que participa en el tour de aventura y busca experiencias recreativas en entornos naturales. |
| **Route**                     | Ruta                              | Camino o trayecto definido que los participantes siguen durante el recorrido, el cual puede incluir distintos niveles de dificultad y riesgo. |
| **Remote Area**               | Zona Remota                       | Entorno geográfico con acceso limitado a infraestructura, caracterizado por baja o nula conectividad y dificultad para recibir asistencia inmediata. |
| **Low Connectivity**          | Baja Conectividad                 | Condición en la que la comunicación digital es limitada o inexistente, afectando la transmisión de información en tiempo real. |
| **Checkpoint**                | Punto de Control                  | Ubicación dentro de la ruta donde se registra el paso de los participantes o se valida su progreso durante el recorrido. |
| **Group Tracking**            | Seguimiento de Grupo              | Proceso de supervisar la ubicación y el estado general de los participantes durante el desarrollo del tour. |
| **Health Monitoring**         | Monitoreo de Salud                | Seguimiento de las condiciones físicas del turista durante la actividad, especialmente en entornos exigentes como altura o esfuerzo físico prolongado. |
| **Vital Signs**               | Signos Vitales                    | Indicadores básicos del estado de salud de una persona, como frecuencia cardíaca o nivel de oxígeno, relevantes en contextos de riesgo. |
| **Incident**                  | Incidente                         | Evento inesperado que afecta la seguridad o el bienestar de los participantes durante el recorrido. |
| **Emergency Response**        | Respuesta a Emergencias           | Acciones tomadas para atender un incidente, incluyendo comunicación, asistencia y evacuación si es necesario. |
| **Situational Awareness**     | Conciencia Situacional            | Capacidad de comprender lo que ocurre en el entorno del tour en un momento determinado, incluyendo ubicación, condiciones y riesgos. |
| **Risk Level**                | Nivel de Riesgo                   | Grado de peligro asociado a una ruta o actividad, determinado por factores como terreno, clima y dificultad. |
| **Safety Protocol**           | Protocolo de Seguridad            | Conjunto de medidas y procedimientos establecidos para prevenir y responder a incidentes durante el recorrido. |
| **Offline Navigation**        | Navegación sin Conexión           | Capacidad de orientarse y seguir una ruta sin depender de conexión a internet. |
| **Tour Completion**           | Finalización del Tour             | Momento en el que el grupo completa la ruta y concluye la actividad planificada. |
| **Post-Tour Evaluation**      | Evaluación Post-Tour              | Proceso de revisión de la experiencia, incluyendo desempeño, incidentes y oportunidades de mejora. |
| **Tour Experience**           | Experiencia del Tour              | Percepción general del usuario respecto a la calidad, seguridad y disfrute del recorrido. |

<div style="page-break-before: always;"></div>

---


# Capítulo III: Requirements Specification

## 3.1. User Stories

La presente sección consolida el conjunto completo de Epics, User Stories, 
Landing Page Stories y Technical Stories que definen los requerimientos 
funcionales del sistema Tourmate. Los requerimientos han sido identificados 
a partir del análisis realizado en los capítulos previos, considerando los 
hallazgos del Needfinding, las características de los segmentos objetivo, el 
resultado del análisis competitivo y las brechas detectadas en las soluciones 
existentes del mercado.

Para garantizar la coherencia del lenguaje a lo largo del documento, se 
establecen dos términos clave del dominio. El término **tour** se refiere a 
la configuración comercial del recorrido tal como es ofrecido por la agencia, 
incluyendo su ruta, checkpoints, información asociada y participantes. El 
término **expedición** se refiere a la instancia activa de un tour, es decir, 
al recorrido en ejecución durante el cual se generan datos de ubicación, 
telemetría e incidentes. Esta distinción se mantiene de forma consistente en 
todas las historias de la presente sección.

El cuadro presentado a continuación incluye historias agrupadas en tres 
categorías. La primera corresponde a las User Stories de la aplicación web y 
móvil, organizadas en Epics funcionales que reflejan los cinco bounded 
contexts del sistema: **Identity & Access**, **Tour Management**, 
**Navigation & Exploration**, **Safety & Monitoring** y **Notification & 
Profile**. Estas historias están redactadas desde la perspectiva de los roles 
definidos en el dominio del problema: turista, administrador de agencia, guía 
de tour y usuario registrado. La segunda categoría corresponde a las Landing 
Page Stories, redactadas desde el rol visitante o subconjuntos por segmento 
objetivo, que recogen los requerimientos del sitio web estático orientado a 
comunicar la propuesta de valor de la plataforma. La tercera categoría 
corresponde a las Technical Stories, redactadas desde el rol developer, que 
documentan los requerimientos técnicos asociados a los endpoints del RESTful 
API que sustentan la operación del sistema.

Cada historia incluye su descripción en formato estándar y un conjunto de 
criterios de aceptación redactados siguiendo la estructura Gherkin 
(Given-When-Then). Los criterios de aceptación se han redactado en tiempo 
presente, tercera persona, sin referencia a detalles de interfaz de usuario, 
garantizando que sean comprobables mediante pruebas funcionales. Las únicas 
excepciones a esta estructura corresponden a reglas de negocio o restricciones 
que no dependen de condiciones específicas, las cuales se declaran de forma 
directa cuando aplican.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Relacionado con (Epic ID) |
|---|---|---|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| **EP01** | **Identidad y Acceso** | Agrupa las funcionalidades relacionadas con el registro, autenticación, verificación, recuperación de credenciales, gestión de sesiones y ciclo de vida de la cuenta de los usuarios de la plataforma. | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | — |
| US01 | Registro de turista | Como turista, quiero registrarme en la plataforma para acceder a los tours y funcionalidades disponibles del sistema. | **Escenario 1: Registro exitoso**<br>Dado que el turista proporciona información válida y completa<br>Cuando envía la solicitud de registro<br>Entonces el sistema crea la cuenta correctamente y retorna confirmación de registro<br><br>**Escenario 2: Registro mediante autenticación externa**<br>Dado que el turista opta por registrarse mediante una cuenta de Google válida<br>Cuando autoriza el acceso a sus datos<br>Entonces el sistema crea la cuenta automáticamente con la información obtenida del proveedor externo y autentica al turista<br><br>**Escenario 3: Correo ya registrado**<br>Dado que el correo proporcionado ya existe en el sistema<br>Cuando el turista envía la solicitud de registro<br>Entonces el sistema retorna un error indicando que el correo ya se encuentra registrado                                                                                                                         | EP01 |
| US02 | Registro de administrador de agencia | Como administrador de agencia, quiero registrar mi agencia en la plataforma para gestionar tours y monitorear a los turistas asignados. | **Escenario 1: Registro exitoso**<br>Dado que el administrador de agencia proporciona información válida de la empresa<br>Cuando envía la solicitud de registro<br>Entonces el sistema crea la cuenta con el rol correspondiente y retorna confirmación<br><br>**Escenario 2: Correo duplicado**<br>Dado que el correo proporcionado ya está asociado a una cuenta existente<br>Cuando el administrador de agencia envía la solicitud de registro<br>Entonces el sistema retorna un error indicando que el correo ya está registrado<br><br>**Escenario 3: Datos inválidos**<br>Dado que el administrador de agencia ingresa datos con formato incorrecto<br>Cuando envía la solicitud de registro<br>Entonces el sistema retorna un error indicando los campos con formato inválido                                                                                                                                                        | EP01 |
| US03 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a las funcionalidades de la plataforma según mi rol. | **Escenario 1: Credenciales válidas**<br>Dado que el usuario registrado proporciona credenciales correctas<br>Cuando envía la solicitud de autenticación<br>Entonces el sistema valida las credenciales y retorna un token de acceso con el rol asociado<br><br>**Escenario 2: Credenciales inválidas**<br>Dado que el usuario registrado proporciona credenciales incorrectas<br>Cuando envía la solicitud de autenticación<br>Entonces el sistema retorna un error sin revelar cuál de los campos es incorrecto<br><br>**Escenario 3: Cuenta inactiva**<br>Dado que la cuenta del usuario se encuentra deshabilitada<br>Cuando el usuario envía la solicitud de autenticación<br>Entonces el sistema retorna un error indicando que la cuenta no está activa                                                                                                                                                                              | EP01 |
| US04 | Recuperación de contraseña | Como usuario registrado, quiero recuperar mi contraseña para no perder el acceso a mi cuenta en la plataforma. | **Escenario 1: Solicitud exitosa**<br>Dado que el usuario registrado proporciona un correo válido y registrado<br>Cuando envía la solicitud de recuperación<br>Entonces el sistema genera un enlace de recuperación con vigencia limitada y lo envía al correo indicado<br><br>**Escenario 2: Enlace expirado**<br>Dado que el enlace de recuperación ha superado su tiempo de validez<br>Cuando el usuario intenta utilizarlo<br>Entonces el sistema retorna un error indicando que el enlace ya no es válido<br><br>**Escenario 3: Correo no registrado**<br>Dado que el correo proporcionado no existe en el sistema<br>Cuando el usuario envía la solicitud de recuperación<br>Entonces el sistema retorna un error indicando que el correo no está registrado                                                                                                                                                                          | EP01 |
| US05 | Verificación de correo electrónico | Como turista, quiero verificar mi correo electrónico tras el registro para confirmar la validez de mi cuenta. | **Escenario 1: Verificación exitosa**<br>Dado que el turista recibe el enlace de verificación tras el registro<br>Cuando confirma la verificación mediante el enlace<br>Entonces el sistema activa la cuenta del turista y retorna confirmación<br><br>**Escenario 2: Enlace expirado**<br>Dado que el enlace de verificación ha superado su tiempo de validez<br>Cuando el turista intenta utilizarlo<br>Entonces el sistema retorna un error e indica al turista que puede solicitar un nuevo enlace de verificación<br><br>**Escenario 3: Reenvío de correo de verificación**<br>Dado que el turista solicita el reenvío del correo de verificación<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema genera un nuevo enlace de verificación y lo envía al correo registrado                                                                                                                                              | EP01 |
| US06 | Cambio de contraseña | Como usuario registrado, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta. | **Escenario 1: Cambio exitoso**<br>Dado que el usuario registrado proporciona la contraseña actual correcta y una nueva contraseña válida<br>Cuando envía la solicitud de cambio<br>Entonces el sistema actualiza la contraseña correctamente e invalida las sesiones activas distintas a la actual<br><br>**Escenario 2: Contraseña actual incorrecta**<br>Dado que el usuario registrado proporciona una contraseña actual incorrecta<br>Cuando envía la solicitud de cambio<br>Entonces el sistema retorna un error indicando que la contraseña actual es incorrecta<br><br>**Escenario 3: Nueva contraseña no cumple requisitos**<br>Dado que la nueva contraseña no cumple los requisitos de seguridad definidos<br>Cuando el usuario envía la solicitud de cambio<br>Entonces el sistema retorna un error indicando los requisitos no cumplidos                                                                                       | EP01 |
| US07 | Cierre de sesiones activas | Como usuario registrado, quiero cerrar todas mis sesiones activas en otros dispositivos para proteger mi cuenta. | **Escenario 1: Cierre exitoso**<br>Dado que el usuario registrado tiene sesiones activas en otros dispositivos<br>Cuando solicita el cierre de sesiones<br>Entonces el sistema invalida todos los tokens de sesión activos distintos al actual<br><br>**Escenario 2: Sin sesiones adicionales**<br>Dado que el usuario registrado no tiene otras sesiones activas<br>Cuando solicita el cierre de sesiones<br>Entonces el sistema retorna una respuesta indicando que no existen sesiones adicionales que cerrar<br><br>**Escenario 3: Desactivación de cuenta**<br>Dado que el usuario registrado confirma la desactivación de su cuenta<br>Cuando envía la solicitud de desactivación<br>Entonces el sistema marca la cuenta como inactiva, invalida todas las sesiones activas y retorna confirmación                                                                                                                                    | EP01 |
| US08 | Vincular dispositivo wearable | Como turista, quiero vincular un dispositivo wearable a mi cuenta para que el sistema capture mis signos vitales durante la expedición. | **Escenario 1: Vinculación exitosa**<br>Dado que el turista dispone de un wearable compatible y proporciona el identificador del dispositivo<br>Cuando envía la solicitud de vinculación<br>Entonces el sistema asocia el dispositivo a la cuenta del turista y retorna confirmación<br><br>**Escenario 2: Dispositivo ya vinculado**<br>Dado que el identificador del dispositivo ya está asociado a otra cuenta<br>Cuando el turista envía la solicitud de vinculación<br>Entonces el sistema retorna un error indicando que el dispositivo ya está vinculado<br><br>**Escenario 3: Desvinculación durante expedición activa**<br>Dado que el dispositivo está transmitiendo datos durante una expedición activa<br>Cuando el turista envía la solicitud de desvinculación<br>Entonces el sistema retorna un error indicando que no es posible desvincular un dispositivo activo durante una expedición                                   | EP01 |
| **EP02** | **Gestión de Tours** | Agrupa las funcionalidades de creación, edición, eliminación, duplicación, asignación y consulta de tours por parte del administrador de agencia, así como la búsqueda, filtrado y confirmación de asistencia por parte del turista. | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | — |
| US09 | Crear tour | Como administrador de agencia, quiero crear un tour para organizar rutas y ponerlas a disposición de los turistas. | **Escenario 1: Creación exitosa**<br>Dado que el administrador de agencia proporciona información válida y completa del tour<br>Cuando envía la solicitud de creación<br>Entonces el sistema registra el tour correctamente y retorna confirmación<br><br>**Escenario 2: Campos obligatorios incompletos**<br>Dado que el administrador de agencia omite campos obligatorios<br>Cuando envía la solicitud de creación<br>Entonces el sistema retorna un error indicando los campos requeridos faltantes<br><br>**Escenario 3: Datos con formato inválido**<br>Dado que el administrador de agencia ingresa datos con formato incorrecto<br>Cuando envía la solicitud de creación<br>Entonces el sistema retorna un error indicando los campos con formato inválido                                                                                                                                                                          | EP02 |
| US10 | Editar tour | Como administrador de agencia, quiero editar la información de un tour para mantener actualizados los datos del recorrido. | **Escenario 1: Edición exitosa**<br>Dado que el administrador de agencia modifica información válida de un tour existente<br>Cuando envía la solicitud de actualización<br>Entonces el sistema aplica los cambios correctamente y retorna confirmación<br><br>**Escenario 2: Datos inválidos**<br>Dado que el administrador de agencia ingresa datos con formato incorrecto<br>Cuando envía la solicitud de actualización<br>Entonces el sistema retorna un error indicando los campos con formato inválido<br><br>**Escenario 3: Tour no encontrado**<br>Dado que el administrador de agencia intenta modificar un tour inexistente<br>Cuando envía la solicitud de actualización<br>Entonces el sistema retorna un error indicando que el recurso no existe                                                                                                                                                                               | EP02 |
| US11 | Eliminar tour | Como administrador de agencia, quiero eliminar un tour para mantener actualizado el catálogo de la agencia. | **Escenario 1: Eliminación exitosa**<br>Dado que el administrador de agencia confirma la eliminación de un tour existente<br>Cuando envía la solicitud de eliminación<br>Entonces el sistema elimina el tour de forma permanente y retorna confirmación<br><br>**Escenario 2: Tour con expedición en curso**<br>Dado que el administrador de agencia intenta eliminar un tour cuya expedición se encuentra activa<br>Cuando envía la solicitud de eliminación<br>Entonces el sistema retorna un error indicando que no es posible eliminar un tour con expedición activa<br><br>**Escenario 3: Tour no encontrado**<br>Dado que el administrador de agencia intenta eliminar un tour inexistente<br>Cuando envía la solicitud de eliminación<br>Entonces el sistema retorna un error indicando que el recurso no existe                                                                                                                     | EP02 |
| US12 | Duplicar tour | Como administrador de agencia, quiero duplicar un tour existente para crear uno nuevo basado en una configuración previamente validada. | **Escenario 1: Duplicación exitosa**<br>Dado que el administrador de agencia selecciona un tour existente<br>Cuando envía la solicitud de duplicación<br>Entonces el sistema crea una copia del tour con estado borrador y retorna confirmación<br><br>**Escenario 2: Tour origen no disponible**<br>Dado que el administrador de agencia intenta duplicar un tour eliminado o inaccesible<br>Cuando envía la solicitud de duplicación<br>Entonces el sistema retorna un error indicando que el tour origen no existe<br><br>**Escenario 3: Error durante la duplicación**<br>Dado que ocurre un fallo interno al procesar la duplicación<br>Cuando el administrador de agencia envía la solicitud<br>Entonces el sistema retorna un error indicando que la operación no pudo completarse                                                                                                                                                   | EP02 |
| US13 | Asignar turistas a un tour | Como administrador de agencia, quiero asignar turistas a un tour para conformar el grupo de participantes del recorrido. | **Escenario 1: Asignación exitosa**<br>Dado que el administrador de agencia selecciona turistas registrados para un tour disponible<br>Cuando envía la solicitud de asignación<br>Entonces el sistema registra la asignación correctamente y retorna confirmación<br><br>**Escenario 2: Turista ya asignado**<br>Dado que el turista seleccionado ya pertenece al tour<br>Cuando el administrador de agencia envía la solicitud de asignación<br>Entonces el sistema retorna un error indicando que el turista ya está asignado<br><br>**Escenario 3: Tour cerrado o cancelado**<br>Dado que el tour se encuentra cerrado o cancelado<br>Cuando el administrador de agencia intenta asignar turistas<br>Entonces el sistema retorna un error indicando que el tour no acepta nuevas asignaciones                                                                                                                                            | EP02 |
| US14 | Desasignar turista de un tour | Como administrador de agencia, quiero desasignar a un turista de un tour para actualizar la composición del grupo. | **Escenario 1: Desasignación exitosa**<br>Dado que el administrador de agencia selecciona un turista asignado a un tour<br>Cuando envía la solicitud de desasignación<br>Entonces el sistema retira al turista del tour y retorna confirmación<br><br>**Escenario 2: Expedición ya iniciada**<br>Dado que el administrador de agencia intenta desasignar a un turista de un tour cuya expedición se encuentra en curso<br>Cuando envía la solicitud de desasignación<br>Entonces el sistema requiere confirmación adicional antes de procesar la solicitud<br><br>**Escenario 3: Turista no asignado al tour**<br>Dado que el turista seleccionado no pertenece al tour indicado<br>Cuando el administrador de agencia envía la solicitud de desasignación<br>Entonces el sistema retorna un error indicando que el turista no está asignado a ese tour                                                                                     | EP02 |
| US15 | Confirmar asistencia | Como turista, quiero confirmar mi asistencia a un tour para asegurar mi participación en el recorrido. | **Escenario 1: Confirmación exitosa**<br>Dado que el turista está asignado a un tour disponible<br>Cuando envía la solicitud de confirmación de asistencia<br>Entonces el sistema actualiza el estado de participación correctamente<br><br>**Escenario 2: Cancelación de participación**<br>Dado que el turista ha confirmado previamente su asistencia<br>Cuando envía la solicitud de cancelación<br>Entonces el sistema actualiza el estado de participación y notifica al administrador de agencia<br><br>**Escenario 3: Expedición ya iniciada**<br>Dado que la expedición del tour al que pertenece el turista ya ha comenzado<br>Cuando el turista envía la solicitud de cancelación<br>Entonces el sistema retorna un error indicando que no es posible modificar la participación                                                                                                                                                 | EP02 |
| US16 | Buscar y filtrar tours | Como turista, quiero buscar y filtrar los tours disponibles para encontrar opciones acordes a mis intereses y preferencias. | **Escenario 1: Búsqueda con resultados**<br>Dado que el turista proporciona un término de búsqueda válido<br>Cuando el sistema procesa la consulta<br>Entonces el sistema retorna los tours cuya información coincide con el término ingresado<br><br>**Escenario 2: Filtro con resultados**<br>Dado que el turista aplica criterios de filtrado válidos<br>Cuando el sistema procesa la consulta<br>Entonces el sistema retorna los tours que cumplen los criterios indicados<br><br>**Escenario 3: Búsqueda sin coincidencias**<br>Dado que el término o criterios proporcionados no coinciden con ningún tour disponible<br>Cuando el sistema procesa la consulta<br>Entonces el sistema retorna una respuesta vacía indicando que no hay coincidencias                                                                                                                                                                                  | EP02 |
| US17 | Consultar detalle del tour | Como turista, quiero acceder a la información completa de un tour para tomar una decisión informada antes de participar. | **Escenario 1: Consulta exitosa**<br>Dado que el tour solicitado existe en el sistema<br>Cuando el turista solicita el detalle<br>Entonces el sistema retorna la información completa del recorrido incluyendo ruta, checkpoints y dificultad<br><br>**Escenario 2: Tour no encontrado**<br>Dado que el tour solicitado no existe en el sistema<br>Cuando el turista solicita el detalle<br>Entonces el sistema retorna un error indicando que el recurso no existe<br><br>**Escenario 3: Consulta de turistas asignados**<br>Dado que el administrador de agencia solicita la lista de turistas de un tour existente<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna los datos relevantes de cada turista asignado junto con su estado de confirmación                                                                                                                                                            | EP02 |
| US18 | Consultar tours de la agencia | Como administrador de agencia, quiero consultar todos los tours registrados por mi agencia para gestionarlos de forma centralizada. | **Escenario 1: Consulta con resultados**<br>Dado que la agencia tiene tours registrados en el sistema<br>Cuando el administrador de agencia solicita la consulta<br>Entonces el sistema retorna el listado completo de tours con su estado actual<br><br>**Escenario 2: Filtro por estado**<br>Dado que el administrador de agencia aplica un filtro por estado del tour<br>Cuando el sistema procesa la consulta<br>Entonces el sistema retorna únicamente los tours que coinciden con el estado indicado<br><br>**Escenario 3: Sin tours registrados**<br>Dado que la agencia no tiene tours registrados<br>Cuando el administrador de agencia solicita la consulta<br>Entonces el sistema retorna una respuesta vacía indicando la ausencia de tours                                                                                                                                                                                     | EP02 |
| **EP03** | **Navegación y Exploración** | Agrupa las funcionalidades relacionadas con la ejecución de expediciones, navegación de ruta, visualización de checkpoints, progreso del recorrido, registro de experiencias, consulta de clima y operación en campo por parte del guía de tour. | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | — |
| US19 | Iniciar expedición | Como guía de tour, quiero marcar el inicio de la expedición para activar el monitoreo y registro del recorrido. | **Escenario 1: Inicio exitoso**<br>Dado que el guía de tour está asignado a un tour pendiente de iniciar<br>Cuando envía la solicitud de inicio<br>Entonces el sistema activa la expedición y retorna confirmación<br><br>**Escenario 2: Expedición ya iniciada**<br>Dado que la expedición del tour seleccionado ya se encuentra activa<br>Cuando el guía de tour envía la solicitud de inicio<br>Entonces el sistema retorna un error indicando que la expedición ya se encuentra en curso<br><br>**Escenario 3: Guía no asignado al tour**<br>Dado que el guía de tour no está asignado al tour que intenta iniciar<br>Cuando envía la solicitud de inicio<br>Entonces el sistema retorna un error indicando que no tiene permisos para iniciar esa expedición                                                                                                                                                                           | EP03 |
| US20 | Visualizar ruta del tour | Como turista, quiero acceder a la ruta del tour para orientarme durante el recorrido. | **Escenario 1: Acceso con conexión**<br>Dado que el turista tiene una expedición activa asignada y conexión disponible<br>Cuando solicita la información de la ruta<br>Entonces el sistema retorna los datos completos del recorrido<br><br>**Escenario 2: Acceso sin conexión**<br>Dado que el turista descargó previamente la ruta y no tiene conexión<br>Cuando solicita la información de la ruta<br>Entonces el sistema retorna los datos desde el almacenamiento local<br><br>**Escenario 3: Ruta no disponible**<br>Dado que el turista no tiene una expedición activa y no ha descargado ninguna ruta<br>Cuando solicita la información<br>Entonces el sistema retorna un error indicando que no hay rutas disponibles                                                                                                                                                                                                              | EP03 |
| US21 | Descargar ruta offline | Como turista, quiero descargar la información de la ruta de un tour para utilizarla sin conexión durante el recorrido. | **Escenario 1: Descarga exitosa**<br>Dado que el turista solicita la descarga de una ruta disponible<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema almacena la información localmente y retorna confirmación<br><br>**Escenario 2: Acceso posterior sin conexión**<br>Dado que el turista descargó previamente la información y no tiene conexión<br>Cuando solicita acceso a la ruta<br>Entonces el sistema retorna la información desde el almacenamiento local sin requerir conexión<br><br>**Escenario 3: Ruta no disponible para descarga**<br>Dado que el turista intenta descargar una ruta que no existe en el sistema<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna un error indicando que la ruta no está disponible                                                                                                                                                                | EP03 |
| US22 | Visualizar checkpoints del recorrido | Como turista, quiero conocer los checkpoints del tour para identificar mi progreso durante el recorrido. | **Escenario 1: Consulta de checkpoints**<br>Dado que el turista tiene una expedición activa<br>Cuando solicita la información de checkpoints<br>Entonces el sistema retorna los checkpoints diferenciando los completados de los pendientes<br><br>**Escenario 2: Checkpoint detectado automáticamente**<br>Dado que el turista se aproxima a un checkpoint registrado<br>Cuando el sistema procesa la proximidad<br>Entonces el sistema marca el checkpoint como completado y actualiza el progreso del turista<br><br>**Escenario 3: Sin expedición activa**<br>Dado que el turista no tiene una expedición activa<br>Cuando solicita la información de checkpoints<br>Entonces el sistema retorna un error indicando que no existe una expedición activa asociada                                                                                                                                                                        | EP03 |
| US23 | Visualizar progreso del recorrido | Como turista, quiero consultar mi avance en el tour para conocer cuánto resta por completar. | **Escenario 1: Consulta de progreso**<br>Dado que el turista tiene una expedición activa<br>Cuando solicita la información de progreso<br>Entonces el sistema retorna el porcentaje completado y los checkpoints restantes<br><br>**Escenario 2: Actualización automática**<br>Dado que el turista completa un tramo o checkpoint del recorrido<br>Cuando el sistema procesa el evento<br>Entonces el sistema actualiza el porcentaje de avance del turista<br><br>**Escenario 3: Recorrido completado**<br>Dado que el turista ha completado todos los checkpoints de la expedición<br>Cuando el sistema procesa el último evento de progreso<br>Entonces el sistema retorna un porcentaje de avance del cien por ciento y notifica la finalización del recorrido                                                                                                                                                                          | EP03 |
| US24 | Registrar checkpoint manual | Como guía de tour, quiero registrar manualmente el paso del grupo por un checkpoint para garantizar la trazabilidad cuando la detección automática no es posible. | **Escenario 1: Registro exitoso**<br>Dado que el guía de tour confirma el paso del grupo por un checkpoint válido<br>Cuando envía la solicitud de registro<br>Entonces el sistema marca el checkpoint como completado para el grupo y retorna confirmación<br><br>**Escenario 2: Checkpoint ya registrado**<br>Dado que el checkpoint seleccionado ya está marcado como completado<br>Cuando el guía de tour envía la solicitud de registro<br>Entonces el sistema retorna un error indicando que el checkpoint ya fue registrado<br><br>**Escenario 3: Checkpoint no pertenece a la expedición activa**<br>Dado que el checkpoint seleccionado no pertenece a la expedición que el guía tiene activa<br>Cuando envía la solicitud de registro<br>Entonces el sistema retorna un error indicando que el checkpoint no corresponde a la expedición en curso                                                                                  | EP03 |
| US25 | Registrar experiencia del recorrido | Como turista, quiero registrar notas durante el tour para documentar mi experiencia. | **Escenario 1: Registro exitoso**<br>Dado que el turista proporciona contenido válido durante una expedición activa<br>Cuando envía la solicitud de registro<br>Entonces el sistema almacena la información asociada al tour y al punto del recorrido<br><br>**Escenario 2: Consulta del historial**<br>Dado que el turista solicita el historial de experiencias registradas<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna las experiencias asociadas a los tours del turista<br><br>**Escenario 3: Sin expedición activa**<br>Dado que el turista intenta registrar una experiencia sin tener una expedición activa<br>Cuando envía la solicitud de registro<br>Entonces el sistema retorna un error indicando que no es posible registrar experiencias fuera de una expedición activa                                                                                                                         | EP03 |
| US26 | Consultar clima del recorrido | Como turista, quiero consultar la información climática del recorrido para prepararme con el equipamiento adecuado. | **Escenario 1: Consulta con conexión**<br>Dado que el turista solicita información climática con conexión activa<br>Cuando el sistema consulta el servicio externo de clima<br>Entonces el sistema retorna información actualizada para la zona del recorrido<br><br>**Escenario 2: Consulta sin conexión**<br>Dado que el turista solicita información climática sin conexión<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna la última información climática almacenada localmente<br><br>**Escenario 3: Servicio externo no disponible**<br>Dado que el servicio externo de clima no responde<br>Cuando el sistema intenta obtener la información<br>Entonces el sistema retorna un error indicando que el servicio no está disponible temporalmente                                                                                                                                                            | EP03 |
| US27 | Sincronización asincrónica de datos offline | Como turista, quiero que los datos capturados durante la expedición se sincronicen automáticamente al recuperar la conexión para no perder ningún registro generado. | **Escenario 1: Sincronización exitosa**<br>Dado que el dispositivo del turista tiene datos almacenados localmente y recupera la conexión<br>Cuando el sistema procesa la sincronización<br>Entonces el sistema transmite los datos al servidor y retorna confirmación<br><br>**Escenario 2: Datos duplicados**<br>Dado que algunos registros ya fueron sincronizados previamente<br>Cuando el sistema procesa la sincronización<br>Entonces el sistema descarta los duplicados y procesa únicamente los registros nuevos<br><br>**Escenario 3: Error durante la sincronización**<br>Dado que ocurre un fallo durante la transmisión de datos<br>Cuando el sistema procesa la sincronización<br>Entonces el sistema conserva los datos localmente y agenda un nuevo intento de transmisión                                                                                                                                                   | EP03 |
| US28 | Finalizar expedición | Como guía de tour, quiero marcar la finalización de la expedición para cerrar formalmente el monitoreo del recorrido. | **Escenario 1: Finalización exitosa**<br>Dado que el guía de tour está asignado a una expedición activa<br>Cuando envía la solicitud de finalización<br>Entonces el sistema cierra la expedición y retorna confirmación<br><br>**Escenario 2: Expedición ya finalizada**<br>Dado que la expedición seleccionada ya se encuentra cerrada<br>Cuando el guía de tour envía la solicitud de finalización<br>Entonces el sistema retorna un error indicando que la expedición ya fue finalizada<br><br>**Escenario 3: Finalización con progreso parcial**<br>Dado que el turista no completó todos los checkpoints de la expedición<br>Cuando el guía envía la solicitud de finalización<br>Entonces el sistema registra la expedición con el progreso alcanzado y la agrega al historial como completada parcialmente                                                                                                                           | EP03 |
| **EP04** | **Seguridad y Monitoreo** | Agrupa las funcionalidades de monitoreo de ubicación, estado de salud, telemetría IoT, detección de anomalías, gestión de alertas y reporte de incidentes durante las expediciones. | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | — |
| US29 | Monitorear ubicación de turistas | Como administrador de agencia, quiero consultar la ubicación de los turistas para supervisar su seguridad durante la expedición. | **Escenario 1: Ubicaciones disponibles**<br>Dado que existen registros de ubicación activos para los turistas de una expedición<br>Cuando el administrador de agencia solicita el estado de ubicación<br>Entonces el sistema retorna las coordenadas actuales de cada turista<br><br>**Escenario 2: Turista sin señal**<br>Dado que un turista ha dejado de transmitir datos de ubicación<br>Cuando el administrador de agencia solicita el estado<br>Entonces el sistema retorna la última ubicación registrada junto con la marca de tiempo<br><br>**Escenario 3: Expedición sin datos activos**<br>Dado que no existen registros de ubicación para la expedición consultada<br>Cuando el administrador de agencia solicita el estado<br>Entonces el sistema retorna una respuesta vacía indicando que no hay datos disponibles                                                                                                           | EP04 |
| US30 | Consultar estado general del grupo | Como administrador de agencia, quiero consultar el estado general de los turistas para detectar situaciones de riesgo durante la expedición. | **Escenario 1: Estado consolidado disponible**<br>Dado que existen datos activos de los participantes de una expedición<br>Cuando el administrador de agencia solicita el estado general<br>Entonces el sistema retorna información consolidada del estado de cada participante<br><br>**Escenario 2: Anomalía detectada**<br>Dado que el sistema identifica una condición fuera del rango establecido<br>Cuando procesa los datos del grupo<br>Entonces el sistema genera una notificación de alerta al administrador de agencia responsable<br><br>**Escenario 3: Sin datos activos**<br>Dado que la expedición no tiene participantes con datos activos<br>Cuando el administrador de agencia solicita el estado general<br>Entonces el sistema retorna una respuesta indicando que no existen datos disponibles                                                                                                                         | EP04 |
| US31 | Recibir alertas por anomalías | Como administrador de agencia, quiero recibir alertas ante situaciones de riesgo para responder oportunamente durante las expediciones. | **Escenario 1: Desvío de ruta detectado**<br>Dado que un turista se encuentra fuera del área definida para el recorrido<br>Cuando el sistema procesa los datos de ubicación<br>Entonces el sistema genera una alerta y la notifica al administrador de agencia responsable<br><br>**Escenario 2: Pérdida de comunicación**<br>Dado que un turista deja de transmitir datos durante un periodo superior al umbral configurado<br>Cuando el sistema detecta la interrupción<br>Entonces el sistema genera una alerta de pérdida de conexión y la notifica al administrador de agencia<br><br>**Escenario 3: Signos vitales fuera de rango**<br>Dado que los datos biométricos de un turista superan los umbrales críticos configurados<br>Cuando el sistema procesa los datos<br>Entonces el sistema genera una alerta preventiva de salud y la notifica al administrador de agencia                                                          | EP04 |
| US32 | Consultar estado de salud básico | Como guía de tour, quiero consultar alertas básicas del estado de salud de los turistas para actuar oportunamente ante posibles emergencias. | **Escenario 1: Datos biométricos disponibles**<br>Dado que existen datos biométricos activos para los turistas de una expedición<br>Cuando el guía de tour solicita el estado de salud<br>Entonces el sistema retorna el estado de salud básico de cada turista<br><br>**Escenario 2: Valores críticos detectados**<br>Dado que el sistema identifica valores biométricos fuera del rango normal<br>Cuando procesa los datos del turista<br>Entonces el sistema genera una alerta preventiva y la notifica al guía de tour responsable<br><br>**Escenario 3: Sin datos biométricos disponibles**<br>Dado que el dispositivo del turista no transmite datos biométricos<br>Cuando el guía de tour solicita el estado de salud<br>Entonces el sistema retorna el último estado registrado junto con la marca de tiempo                                                                                                                        | EP04 |
| US33 | Reportar incidente | Como turista, quiero reportar incidentes para alertar oportunamente al personal responsable durante la expedición. | **Escenario 1: Reporte con conexión**<br>Dado que el turista genera un reporte con información válida y tiene conexión activa<br>Cuando envía el reporte<br>Entonces el sistema registra el incidente y notifica al administrador de agencia responsable<br><br>**Escenario 2: Reporte sin conexión**<br>Dado que el dispositivo del turista no tiene conexión a internet<br>Cuando el turista envía el reporte<br>Entonces el sistema almacena el incidente localmente y lo sincroniza cuando se recupera la conexión<br><br>**Escenario 3: Información incompleta**<br>Dado que el turista envía un reporte con campos obligatorios faltantes<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna un error indicando los campos requeridos                                                                                                                                                                           | EP04 |
| US34 | Reportar incidente desde el rol guía | Como guía de tour, quiero reportar incidentes detectados en campo para informar oportunamente al administrador de agencia. | **Escenario 1: Reporte exitoso con conexión**<br>Dado que el guía de tour proporciona información válida del incidente y tiene conexión<br>Cuando envía el reporte<br>Entonces el sistema registra el incidente y notifica al administrador de agencia responsable<br><br>**Escenario 2: Reporte sin conexión**<br>Dado que el dispositivo del guía de tour no tiene conexión<br>Cuando envía el reporte<br>Entonces el sistema almacena el incidente localmente y lo sincroniza al recuperar la conexión<br><br>**Escenario 3: Resolución de incidente**<br>Dado que el administrador de agencia recibe un incidente reportado<br>Cuando registra la resolución con una nota válida<br>Entonces el sistema actualiza el estado del incidente a resuelto y retorna confirmación                                                                                                                                                             | EP04 |
| US35 | Recibir datos biométricos del wearable | Como turista, quiero que el sistema reciba los datos biométricos capturados por mi wearable para que sean utilizados en el monitoreo de mi salud durante la expedición. | **Escenario 1: Recepción exitosa**<br>Dado que el wearable transmite datos biométricos válidos durante una expedición activa<br>Cuando el sistema procesa la transmisión<br>Entonces el sistema registra los datos asociados al turista y a la expedición correspondiente<br><br>**Escenario 2: Datos con formato inválido**<br>Dado que el wearable transmite datos con formato incorrecto<br>Cuando el sistema procesa la transmisión<br>Entonces el sistema descarta los datos y registra un evento de error<br><br>**Escenario 3: Sin expedición activa**<br>Dado que el turista no tiene una expedición activa en el momento de la transmisión<br>Cuando el sistema recibe los datos<br>Entonces el sistema descarta los datos y registra un evento informativo indicando que no había una expedición activa                                                                                                                           | EP04 |
| US36 | Consultar estado del wearable | Como turista, quiero consultar el estado de mi wearable para verificar su nivel de batería y conectividad antes de iniciar el recorrido. | **Escenario 1: Estado disponible**<br>Dado que el wearable está vinculado y activo<br>Cuando el turista solicita el estado del dispositivo<br>Entonces el sistema retorna información sobre nivel de batería, conectividad y última sincronización<br><br>**Escenario 2: Dispositivo desconectado**<br>Dado que el wearable no está transmitiendo datos<br>Cuando el turista solicita el estado del dispositivo<br>Entonces el sistema retorna el último estado registrado junto con la marca de tiempo<br><br>**Escenario 3: Dispositivo no vinculado**<br>Dado que el turista no tiene ningún wearable vinculado a su cuenta<br>Cuando solicita el estado del dispositivo<br>Entonces el sistema retorna un error indicando que no existe un dispositivo asociado a la cuenta                                                                                                                                                             | EP04 |
| US37 | Exportar reportes de expedición | Como administrador de agencia, quiero exportar reportes de las expediciones para analizar la información operativa. | **Escenario 1: Exportación exitosa**<br>Dado que existen datos disponibles para la expedición solicitada<br>Cuando el administrador de agencia solicita la exportación<br>Entonces el sistema genera correctamente el archivo con la información de la expedición<br><br>**Escenario 2: Sin datos disponibles**<br>Dado que no existen datos registrados para la expedición solicitada<br>Cuando el administrador de agencia solicita la exportación<br>Entonces el sistema retorna un error indicando que no hay información disponible para exportar<br><br>**Escenario 3: Formato de exportación inválido**<br>Dado que el administrador de agencia solicita un formato de exportación no soportado<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna un error indicando los formatos disponibles                                                                                                                 | EP04 |
| **EP05** | **Notificaciones y Perfil** | Agrupa las funcionalidades relacionadas con la administración del perfil personal del usuario, la configuración de preferencias de notificaciones y la recepción de notificaciones relevantes sobre eventos del sistema. | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | — |
| US38 | Gestionar perfil personal | Como usuario registrado, quiero gestionar mi información personal para mantener actualizados los datos asociados a mi cuenta. | **Escenario 1: Actualización exitosa**<br>Dado que el usuario proporciona información válida<br>Cuando envía la solicitud de actualización<br>Entonces el sistema aplica los cambios correctamente y retorna confirmación<br><br>**Escenario 2: Datos inválidos**<br>Dado que el usuario ingresa información con formato incorrecto<br>Cuando envía la solicitud de actualización<br>Entonces el sistema retorna un error indicando los campos con formato inválido<br><br>**Escenario 3: Campos obligatorios vacíos**<br>Dado que el usuario omite campos obligatorios<br>Cuando envía la solicitud de actualización<br>Entonces el sistema retorna un error indicando los campos requeridos faltantes                                                                                                                                                                                                                                     | EP05 |
| US39 | Actualizar foto de perfil | Como usuario registrado, quiero actualizar mi foto de perfil para personalizar mi cuenta en la plataforma. | **Escenario 1: Actualización exitosa**<br>Dado que el usuario proporciona un archivo de imagen con formato y tamaño válidos<br>Cuando envía la solicitud de actualización<br>Entonces el sistema almacena la imagen y la asocia al perfil del usuario<br><br>**Escenario 2: Formato de archivo inválido**<br>Dado que el usuario proporciona un archivo con extensión no soportada<br>Cuando envía la solicitud de actualización<br>Entonces el sistema retorna un error indicando los formatos de imagen aceptados<br><br>**Escenario 3: Tamaño de archivo excedido**<br>Dado que el archivo proporcionado supera el tamaño máximo permitido<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna un error indicando el límite de tamaño permitido                                                                                                                                                                     | EP05 |
| US40 | Configurar preferencias de notificaciones | Como usuario registrado, quiero configurar las preferencias de notificaciones para recibir únicamente las que considero relevantes. | **Escenario 1: Configuración exitosa**<br>Dado que el usuario proporciona preferencias válidas<br>Cuando envía la solicitud de configuración<br>Entonces el sistema aplica las preferencias y retorna confirmación<br><br>**Escenario 2: Restaurar preferencias por defecto**<br>Dado que el usuario solicita restablecer las preferencias a los valores predeterminados<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema aplica la configuración por defecto y retorna confirmación<br><br>**Escenario 3: Configuración inválida**<br>Dado que el usuario proporciona preferencias con formato incorrecto<br>Cuando envía la solicitud de configuración<br>Entonces el sistema retorna un error indicando los parámetros inválidos                                                                                                                                                                                         | EP05 |
| US41 | Recibir notificaciones de seguridad | Como usuario registrado, quiero recibir notificaciones de alerta de seguridad para mantenerme informado sobre eventos críticos relacionados con mi expedición. | **Escenario 1: Notificación generada por alerta**<br>Dado que el sistema detecta una condición crítica asociada a la expedición del usuario<br>Cuando procesa el evento de seguridad<br>Entonces el sistema genera y envía la notificación al usuario correspondiente a través del canal configurado<br><br>**Escenario 2: Notificaciones de seguridad deshabilitadas**<br>Dado que el usuario tiene deshabilitadas las notificaciones de alerta en su configuración<br>Cuando ocurre un evento de seguridad que generaría una notificación<br>Entonces el sistema no envía la notificación y registra el evento internamente<br><br>**Escenario 3: Canal de notificación no disponible**<br>Dado que el canal de notificación configurado no está disponible en el momento del evento<br>Cuando el sistema intenta enviar la notificación<br>Entonces el sistema reintenta el envío por un canal alternativo y registra el intento fallido | EP05 |
| US42 | Recibir notificaciones de tour | Como turista, quiero recibir notificaciones sobre actualizaciones de mi tour para mantenerme informado sobre cambios en mi participación. | **Escenario 1: Notificación de asignación**<br>Dado que el turista es asignado a un tour por el administrador de agencia<br>Cuando el sistema procesa la asignación<br>Entonces el sistema envía una notificación al turista informando sobre su nueva asignación<br><br>**Escenario 2: Notificación de inicio de expedición**<br>Dado que la expedición a la que pertenece el turista es iniciada por el guía<br>Cuando el sistema registra el inicio<br>Entonces el sistema envía una notificación al turista indicando que la expedición ha comenzado<br><br>**Escenario 3: Notificación de cancelación**<br>Dado que el tour al que pertenece el turista es cancelado por el administrador de agencia<br>Cuando el sistema registra la cancelación<br>Entonces el sistema envía una notificación al turista informando sobre la cancelación del tour                                                                                    | EP05 |
| US43 | Consultar historial de notificaciones | Como usuario registrado, quiero consultar el historial de notificaciones recibidas para revisar eventos pasados relacionados con mi cuenta. | **Escenario 1: Consulta con resultados**<br>Dado que el usuario tiene notificaciones registradas en el sistema<br>Cuando solicita el historial de notificaciones<br>Entonces el sistema retorna el listado de notificaciones ordenadas cronológicamente<br><br>**Escenario 2: Marcar notificación como leída**<br>Dado que el usuario selecciona una notificación no leída<br>Cuando envía la solicitud de marcado<br>Entonces el sistema actualiza el estado de la notificación a leída y retorna confirmación<br><br>**Escenario 3: Sin notificaciones registradas**<br>Dado que el usuario no tiene notificaciones en el sistema<br>Cuando solicita el historial<br>Entonces el sistema retorna una respuesta vacía indicando la ausencia de notificaciones                                                                                                                                                                              | EP05 |
| **EP06** | **Landing Page** | Agrupa las funcionalidades del sitio web estático que comunica la propuesta de valor de TourMate a los visitantes de cada segmento objetivo, permitiendo conocer las funcionalidades, beneficios y acceder al registro de la plataforma. | —                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | — |
| US-LP01 | Conocer la propuesta de valor | Como visitante, quiero conocer la propuesta de valor de Tourmate para evaluar si la plataforma se ajusta a mis necesidades. | **Escenario 1: Contenido principal disponible**<br>Dado que el visitante accede a la landing page<br>Cuando el sistema entrega el contenido principal<br>Entonces el sistema retorna la información que comunica el propósito y el beneficio central de la plataforma<br><br>**Escenario 2: Acceso desde dispositivo móvil**<br>Dado que el visitante accede a la landing page desde un dispositivo móvil<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema entrega el contenido adaptado al tamaño del dispositivo<br><br>**Escenario 3: Contenido no disponible**<br>Dado que ocurre un fallo al entregar el contenido principal<br>Cuando el visitante accede a la landing page<br>Entonces el sistema retorna un mensaje indicando que el contenido no está disponible temporalmente                                                                                                                                     | EP06 |
| US-LP02 | Navegar entre secciones | Como visitante, quiero acceder a las distintas secciones de la landing page para conocer las funcionalidades del sistema. | **Escenario 1: Navegación exitosa**<br>Dado que el visitante accede a la landing page<br>Cuando solicita acceder a una sección específica<br>Entonces el sistema redirige al contenido correspondiente a la sección seleccionada<br><br>**Escenario 2: Acceso desde dispositivo móvil**<br>Dado que el visitante accede desde un dispositivo móvil<br>Cuando solicita acceder a una sección<br>Entonces el sistema entrega el contenido adaptado al tamaño del dispositivo<br><br>**Escenario 3: Sección no disponible**<br>Dado que el visitante solicita una sección que no se encuentra disponible<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna un mensaje indicando que la sección no está disponible temporalmente                                                                                                                                                                                         | EP06 |
| US-LP03 | Conocer beneficios para turistas | Como visitante del segmento turista, quiero conocer los beneficios específicos de la plataforma para comprender cómo mejora mi experiencia durante las expediciones. | **Escenario 1: Acceso al contenido del segmento turista**<br>Dado que el visitante del segmento turista solicita el contenido dirigido a su segmento<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna información sobre las funcionalidades de seguridad y navegación offline orientadas al turista<br><br>**Escenario 2: Acceso al registro desde el segmento turista**<br>Dado que el visitante del segmento turista solicita iniciar el registro<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema redirige al proceso de registro correspondiente al segmento turista<br><br>**Escenario 3: Contenido no disponible**<br>Dado que ocurre un fallo al entregar el contenido del segmento turista<br>Cuando el visitante solicita el contenido<br>Entonces el sistema retorna un mensaje indicando que el contenido no está disponible temporalmente                                               | EP06 |
| US-LP04 | Conocer beneficios para agencias | Como visitante del segmento agencia, quiero conocer los beneficios específicos de la plataforma para comprender cómo mejora la gestión y monitoreo de expediciones. | **Escenario 1: Acceso al contenido del segmento agencia**<br>Dado que el visitante del segmento agencia solicita el contenido dirigido a su segmento<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna información sobre las funcionalidades de monitoreo, alertas y gestión de expediciones<br><br>**Escenario 2: Acceso al registro desde el segmento agencia**<br>Dado que el visitante del segmento agencia solicita iniciar el registro<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema redirige al proceso de registro correspondiente al segmento agencia<br><br>**Escenario 3: Contenido no disponible**<br>Dado que ocurre un fallo al entregar el contenido del segmento agencia<br>Cuando el visitante solicita el contenido<br>Entonces el sistema retorna un mensaje indicando que el contenido no está disponible temporalmente                                                       | EP06 |
| US-LP05 | Conocer las funcionalidades principales | Como visitante, quiero conocer las funcionalidades principales de la plataforma para entender el funcionamiento general del sistema. | **Escenario 1: Acceso al contenido**<br>Dado que el visitante solicita el contenido de funcionalidades principales<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna información sobre las funcionalidades principales de Tourmate<br><br>**Escenario 2: Acceso a funcionalidad offline**<br>Dado que el visitante solicita información sobre la compatibilidad offline de la plataforma<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna información sobre la operatividad sin conexión de forma clara<br><br>**Escenario 3: Contenido no disponible**<br>Dado que ocurre un fallo al entregar el contenido de funcionalidades<br>Cuando el visitante solicita la información<br>Entonces el sistema retorna un mensaje indicando que el contenido no está disponible temporalmente                                                                                                         | EP06 |
| US-LP06 | Acceder al registro desde la landing | Como visitante, quiero acceder rápidamente al registro desde la landing page para comenzar a utilizar la plataforma. | **Escenario 1: Redirección al registro de turista**<br>Dado que el visitante del segmento turista solicita iniciar el registro<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema redirige al proceso de registro del segmento turista<br><br>**Escenario 2: Redirección al registro de agencia**<br>Dado que el visitante del segmento agencia solicita iniciar el registro<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema redirige al proceso de registro del segmento agencia<br><br>**Escenario 3: Servicio de registro no disponible**<br>Dado que el servicio de registro no se encuentra disponible<br>Cuando el visitante solicita iniciar el registro<br>Entonces el sistema retorna un mensaje indicando que el servicio no está disponible temporalmente                                                                                                                                         | EP06 |
| US-LP07 | Conocer testimonios y casos de uso | Como visitante, quiero conocer testimonios y casos de uso reales para tomar una decisión informada sobre la plataforma. | **Escenario 1: Testimonios disponibles**<br>Dado que el visitante solicita el contenido de testimonios<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna los testimonios y casos de uso registrados<br><br>**Escenario 2: Sin testimonios disponibles**<br>Dado que no existen testimonios registrados<br>Cuando el visitante solicita el contenido<br>Entonces el sistema retorna un mensaje indicando que no hay testimonios disponibles por el momento<br><br>**Escenario 3: Contenido no disponible**<br>Dado que ocurre un fallo al entregar el contenido de testimonios<br>Cuando el visitante solicita la información<br>Entonces el sistema retorna un mensaje indicando que el contenido no está disponible temporalmente                                                                                                                                                                                   | EP06 |
| US-LP08 | Contactar al equipo de Tourmate | Como visitante, quiero contactar al equipo de Tourmate para resolver dudas relacionadas con la plataforma. | **Escenario 1: Mensaje enviado correctamente**<br>Dado que el visitante proporciona información válida en el formulario de contacto<br>Cuando envía la solicitud de contacto<br>Entonces el sistema registra el mensaje correctamente y retorna confirmación de recepción<br><br>**Escenario 2: Datos inválidos**<br>Dado que el visitante ingresa información con formato incorrecto<br>Cuando envía la solicitud de contacto<br>Entonces el sistema retorna un error indicando los campos con formato inválido<br><br>**Escenario 3: Servicio de contacto no disponible**<br>Dado que el servicio de contacto no se encuentra disponible<br>Cuando el visitante envía la solicitud<br>Entonces el sistema retorna un mensaje indicando que el servicio no está disponible temporalmente                                                                                                                                                   | EP06 |
| US-LP09 | Conocer al equipo de la startup | Como visitante, quiero conocer al equipo detrás de Tourmate para construir confianza en la propuesta de valor. | **Escenario 1: Información del equipo disponible**<br>Dado que el visitante solicita el contenido del equipo<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna información sobre los miembros del equipo de Axiom<br><br>**Escenario 2: Acceso desde dispositivo móvil**<br>Dado que el visitante accede al contenido del equipo desde un dispositivo móvil<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema retorna la información adaptada al tamaño del dispositivo<br><br>**Escenario 3: Contenido no disponible**<br>Dado que ocurre un fallo al entregar el contenido del equipo<br>Cuando el visitante solicita el contenido<br>Entonces el sistema retorna un mensaje indicando que el contenido no está disponible temporalmente                                                                                                                                                            | EP06 |
| US-LP10 | Acceder a una demostración del sistema | Como visitante, quiero acceder a una demostración del sistema para comprender el funcionamiento de la plataforma antes de registrarme. | **Escenario 1: Demostración disponible**<br>Dado que el visitante solicita la demostración del sistema<br>Cuando el sistema procesa la solicitud<br>Entonces el sistema provee acceso al recurso de demostración correctamente<br><br>**Escenario 2: Interacción con la demostración**<br>Dado que el visitante interactúa con la demostración<br>Cuando el sistema procesa cada interacción<br>Entonces el sistema responde correctamente a cada acción del visitante<br><br>**Escenario 3: Demostración no disponible**<br>Dado que el recurso de demostración no se encuentra disponible<br>Cuando el visitante solicita la demostración<br>Entonces el sistema retorna un mensaje indicando que el recurso no está disponible temporalmente | EP06 |
| US-LP11 | Visualizar video institucional 'About-the-Team' | Como visitante de la landing page, quiero reproducir un video institucional sobre el equipo de desarrollo para conocer a los integrantes de la startup, sus roles y la visión del proyecto. | **Escenario 1: Reproducción exitosa del video del equipo**<br>Dado que el visitante navega a la sección del equipo en la landing page<br>Cuando interactúa con el reproductor multimedia o modal interactivo<br>Entonces el sistema inicia la reproducción del video institucional 'About-the-Team' en alta definición con controles accesibles de pausa y volumen<br><br>**Escenario 2: Adaptabilidad y reproducción en dispositivos móviles**<br>Dado que el visitante accede a la landing page desde un smartphone o tablet<br>Cuando inicia la reproducción del video<br>Entonces el contenedor multimedia adapta su relación de aspecto (16:9 responsivo) sin desbordar el viewport ni degradar la experiencia de usuario<br><br>**Escenario 3: Enlace alternativo y fallback por conectividad**<br>Dado que la conexión a internet del visitante presenta latencia o bloqueo de iframes externos<br>Cuando falla la carga del reproductor embebido<br>Entonces el sistema muestra un enlace directo alternativo al repositorio de video institucional y un mensaje descriptivo accesible | EP06 |
| US-LP12 | Visualizar video demostrativo 'About-the-Product' | Como visitante o cliente potencial (agencia o turista), quiero ver un video demostrativo del producto para comprender de forma dinámica el funcionamiento de TourMate, sus funcionalidades clave y su propuesta de valor antes de iniciar el registro. | **Escenario 1: Reproducción fluida de la demostración del producto**<br>Dado que el visitante se encuentra en la sección principal o de características de la landing page<br>Cuando presiona el botón de reproducción del video 'About-the-Product'<br>Entonces el sistema despliega el video promocional destacando la telemetría en tiempo real, gestión de tours y respuesta a incidentes<br><br>**Escenario 2: Apertura en modal interactivo con overlay**<br>Dado que el usuario solicita la visualización inmersiva del video<br>Cuando hace clic en el CTA de vista previa<br>Entonces el video se ejecuta dentro de una ventana modal con fondo oscurecido y botón de cierre visible que retorna al flujo de navegación previo al cerrarse<br><br>**Escenario 3: Llamado a la acción (CTA) posterior al video**<br>Dado que el visitante concluye la visualización del video demostrativo<br>Cuando el video finaliza<br>Entonces la interfaz presenta botones de llamado a la acción destacados que guían al usuario hacia el registro de cuenta o la selección de planes comerciales | EP06 |
| **EP07** | **RESTful API** | Agrupa los endpoints RESTful que exponen las funcionalidades del sistema a los componentes del frontend, dispositivos IoT y servicios externos, siguiendo los estándares de diseño de API REST. | — | — |
| TS01 | Endpoint de registro y autenticación | Como developer, quiero exponer endpoints que registren usuarios y validen credenciales para que los clientes puedan crear cuentas y autenticarse de forma segura en la plataforma. | **Escenario 1: Registro exitoso**<br>Given que el request contiene un body con información válida y completa<br>When el cliente consume el endpoint POST /api/v1/users<br>Then el sistema retorna una respuesta con código 201 y los datos del usuario creado<br><br>**Escenario 2: Autenticación exitosa**<br>Given que el request contiene credenciales válidas y registradas<br>When el cliente consume el endpoint POST /api/v1/auth/login<br>Then el sistema retorna una respuesta con código 200 y el token de acceso generado<br><br>**Escenario 3: Correo duplicado en registro**<br>Given que el correo del request ya existe en el sistema<br>When el cliente consume el endpoint POST /api/v1/users<br>Then el sistema retorna una respuesta con código 409 indicando que el recurso ya existe<br><br>**Escenario 4: Token expirado**<br>Given que el token de acceso del cliente ha superado su tiempo de validez<br>When el cliente consume un endpoint protegido<br>Then el sistema retorna una respuesta con código 401 indicando que el token no es válido | EP07 |
| TS02 | Endpoint de gestión de tours | Como developer, quiero exponer endpoints para la creación, consulta, actualización y eliminación de tours para que el frontend pueda administrar el catálogo de la agencia. | **Escenario 1: Creación exitosa**<br>Given que el request contiene información válida del tour y un token de acceso válido<br>When el cliente consume el endpoint POST /api/v1/tours<br>Then el sistema retorna una respuesta con código 201 y los datos del tour creado<br><br>**Escenario 2: Consulta exitosa**<br>Given que existen tours registrados y el token es válido<br>When el cliente consume el endpoint GET /api/v1/tours<br>Then el sistema retorna una respuesta con código 200 y la lista de tours disponibles<br><br>**Escenario 3: Tour no encontrado**<br>Given que el identificador del tour solicitado no existe<br>When el cliente consume el endpoint GET /api/v1/tours/{id}<br>Then el sistema retorna una respuesta con código 404 indicando que el recurso no existe<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |
| TS03 | Endpoint de gestión de expediciones | Como developer, quiero exponer endpoints para iniciar, consultar y finalizar expediciones para que el frontend pueda gestionar el ciclo de vida de cada recorrido activo. | **Escenario 1: Inicio exitoso**<br>Given que el request contiene un tourId válido y un token de guía autorizado<br>When el cliente consume el endpoint POST /api/v1/expeditions<br>Then el sistema retorna una respuesta con código 201 y los datos de la expedición iniciada<br><br>**Escenario 2: Consulta de checkpoints**<br>Given que existen registros de checkpoints para la expedición solicitada<br>When el cliente consume el endpoint GET /api/v1/expeditions/{id}/checkpoints<br>Then el sistema retorna una respuesta con código 200 y la lista de checkpoints con su estado<br><br>**Escenario 3: Finalización exitosa**<br>Given que la expedición se encuentra en estado activo<br>When el cliente consume el endpoint PUT /api/v1/expeditions/{id}/finish<br>Then el sistema retorna una respuesta con código 200 confirmando el cierre de la expedición<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |
| TS04 | Endpoint de monitoreo de ubicación | Como developer, quiero exponer endpoints que registren y expongan las ubicaciones de los turistas en tiempo real para que el frontend pueda supervisar la seguridad de los participantes durante la expedición. | **Escenario 1: Registro exitoso**<br>Given que el request contiene coordenadas válidas, el identificador del turista y un token válido<br>When el cliente consume el endpoint POST /api/v1/locations<br>Then el sistema retorna una respuesta con código 201 confirmando el registro de ubicación<br><br>**Escenario 2: Consulta exitosa**<br>Given que existen registros de ubicación para la expedición solicitada<br>When el cliente consume el endpoint GET /api/v1/expeditions/{id}/locations<br>Then el sistema retorna una respuesta con código 200 y los datos de ubicación de los participantes<br><br>**Escenario 3: Sin datos disponibles**<br>Given que no existen registros de ubicación para la expedición consultada<br>When el cliente consume el endpoint GET /api/v1/expeditions/{id}/locations<br>Then el sistema retorna una respuesta con código 200 y una lista vacía<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |
| TS05 | Endpoint de gestión de incidentes | Como developer, quiero exponer endpoints que registren y expongan los incidentes reportados durante las expediciones para que el administrador de agencia pueda responder oportunamente. | **Escenario 1: Registro exitoso**<br>Given que el request contiene información válida del incidente y un token válido<br>When el cliente consume el endpoint POST /api/v1/incidents<br>Then el sistema retorna una respuesta con código 201 y los datos del incidente registrado<br><br>**Escenario 2: Consulta exitosa**<br>Given que existen incidentes registrados para la expedición solicitada<br>When el cliente consume el endpoint GET /api/v1/expeditions/{id}/incidents<br>Then el sistema retorna una respuesta con código 200 y la lista de incidentes<br><br>**Escenario 3: Datos incompletos**<br>Given que el request omite campos obligatorios del incidente<br>When el cliente consume el endpoint POST /api/v1/incidents<br>Then el sistema retorna una respuesta con código 400 indicando los campos requeridos faltantes<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |
| TS06 | Endpoint de sincronización offline | Como developer, quiero exponer un endpoint que procese los datos almacenados localmente al recuperar conexión para que no se pierdan registros generados durante la expedición. | **Escenario 1: Sincronización exitosa**<br>Given que el request contiene datos válidos almacenados localmente<br>When el cliente consume el endpoint POST /api/v1/sync<br>Then el sistema procesa los datos correctamente y retorna una respuesta con código 200 confirmando la sincronización<br><br>**Escenario 2: Datos duplicados**<br>Given que el request contiene registros previamente sincronizados<br>When el cliente consume el endpoint POST /api/v1/sync<br>Then el sistema ignora los duplicados y retorna una respuesta con código 200 indicando los procesados y los omitidos<br><br>**Escenario 3: Error durante la sincronización**<br>Given que ocurre un fallo interno al procesar los datos<br>When el cliente consume el endpoint POST /api/v1/sync<br>Then el sistema retorna una respuesta con código 500 indicando que la sincronización no pudo completarse | EP07 |
| TS07 | Endpoint de gestión de alertas | Como developer, quiero exponer endpoints que generen y expongan alertas ante anomalías detectadas para que el administrador de agencia y el guía de tour puedan responder oportunamente. | **Escenario 1: Alerta generada exitosamente**<br>Given que el sistema detecta una condición que supera los umbrales configurados<br>When el endpoint procesa los datos recibidos<br>Then el sistema registra la alerta y retorna una respuesta con código 201 con los datos de la alerta generada<br><br>**Escenario 2: Consulta de alertas activas**<br>Given que existen alertas activas para la expedición solicitada<br>When el cliente consume el endpoint GET /api/v1/expeditions/{id}/alerts<br>Then el sistema retorna una respuesta con código 200 y la lista de alertas activas<br><br>**Escenario 3: Parámetros inválidos**<br>Given que el request contiene datos con formato incorrecto<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 400 indicando los parámetros inválidos<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |
| TS08 | Endpoint de ingesta de telemetría IoT | Como developer, quiero exponer un endpoint que reciba y procese la telemetría enviada por los dispositivos wearables para que la información biométrica esté disponible para el monitoreo en tiempo real. | **Escenario 1: Ingesta exitosa**<br>Given que el request contiene telemetría válida proveniente de un dispositivo registrado<br>When el cliente consume el endpoint POST /api/v1/telemetry<br>Then el sistema registra la telemetría asociada al turista y retorna una respuesta con código 201<br><br>**Escenario 2: Dispositivo no registrado**<br>Given que el identificador del dispositivo no está registrado en el sistema<br>When el cliente consume el endpoint POST /api/v1/telemetry<br>Then el sistema retorna una respuesta con código 403 indicando que el dispositivo no está autorizado<br><br>**Escenario 3: Telemetría con formato inválido**<br>Given que el request contiene datos con formato incorrecto<br>When el cliente consume el endpoint POST /api/v1/telemetry<br>Then el sistema retorna una respuesta con código 400 indicando los parámetros inválidos<br><br>**Escenario 4: Solicitud sin credenciales del dispositivo**<br>Given que el request no contiene las credenciales del dispositivo<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación del dispositivo | EP07 |
| TS09 | Endpoint de perfil y notificaciones | Como developer, quiero exponer endpoints para gestionar el perfil del usuario y sus preferencias de notificaciones para que el frontend pueda personalizar la experiencia de cada usuario. | **Escenario 1: Consulta de perfil exitosa**<br>Given que el request contiene un token válido del usuario autenticado<br>When el cliente consume el endpoint GET /api/v1/profile<br>Then el sistema retorna una respuesta con código 200 y los datos del perfil del usuario<br><br>**Escenario 2: Actualización de preferencias exitosa**<br>Given que el request contiene preferencias válidas y un token válido<br>When el cliente consume el endpoint PUT /api/v1/profile/preferences<br>Then el sistema retorna una respuesta con código 200 confirmando la actualización<br><br>**Escenario 3: Consulta de notificaciones**<br>Given que existen notificaciones registradas para el usuario autenticado<br>When el cliente consume el endpoint GET /api/v1/notifications<br>Then el sistema retorna una respuesta con código 200 y la lista de notificaciones<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |
| TS10 | Endpoint de exportación de reportes | Como developer, quiero exponer un endpoint que genere reportes exportables de las expediciones para que el administrador de agencia pueda analizar la información operativa. | **Escenario 1: Exportación exitosa**<br>Given que existen datos disponibles para la expedición solicitada<br>When el cliente consume el endpoint GET /api/v1/expeditions/{id}/reports/export<br>Then el sistema retorna una respuesta con código 200 y el archivo generado en el formato solicitado<br><br>**Escenario 2: Sin datos para exportar**<br>Given que no existen datos registrados para la expedición<br>When el cliente consume el endpoint de exportación<br>Then el sistema retorna una respuesta con código 404 indicando que no hay información disponible<br><br>**Escenario 3: Formato no soportado**<br>Given que el request especifica un formato de exportación no disponible<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 400 indicando los formatos soportados<br><br>**Escenario 4: Solicitud sin autorización**<br>Given que el request no contiene un token de acceso válido<br>When el cliente consume el endpoint<br>Then el sistema retorna una respuesta con código 401 indicando que se requiere autenticación | EP07 |

## 3.2. Impact Mapping

El Impact Mapping es una herramienta de planificación estratégica que nos permite conectar los objetivos de negocio de Tourmate con los comportamientos de cada segmento objetivo.

### Impact Map - Segmento 1: Dueños o Responsables de Agencias de Turismo de Aventura

![Impact Map - Segmento 1: Agencias de Turismo](../assets/images/New-Impact-Map-1.png)

### Impact Map - Segmento 2: Turistas de Aventura

![Impact Map - Segmento 2: Turistas de Aventura](../assets/images/New-Impact-Map-2.png)

### 3.3. Product Backlog

A continuación se presenta el Product Backlog de Tourmate con la priorización y estimación de todas las historias identificadas. El orden refleja el valor para el negocio, priorizando las funcionalidades del Landing Page, las historias de usuario de los distintos roles y las tareas técnicas de desarrollo.

Para acceder al Product Backlog en la herramienta de gestión del equipo, visitar el siguiente enlace: [Product Backlog — Tourmate](https://trello.com/invite/b/6aa7135dcbb03c6075b9944b/ATTI3d6ca6c13b23e9df6f2ebe962e859d9aE7098EAF/tourmate-product-backlog)

![Product Backlog Tourmate](../assets/images/New-Product-Backlog.png)
| # Orden | User Story Id | Título | Descripción | Story Points  |
|---|---|---|---|---|
| 1 | US-LP01 | Conocer la propuesta de valor | Como visitante, quiero conocer la propuesta de valor de Tourmate para evaluar si la plataforma se ajusta a mis necesidades. | 2 |
| 2 | US-LP02 | Navegar entre secciones | Como visitante, quiero acceder a las distintas secciones de la landing page para conocer las funcionalidades del sistema. | 1 |
| 3 | US-LP03 | Conocer beneficios para turistas | Como visitante del segmento turista, quiero conocer los beneficios específicos de la plataforma para comprender cómo mejora mi experiencia durante las expediciones. | 2 |
| 4 | US-LP04 | Conocer beneficios para agencias | Como visitante del segmento agencia, quiero conocer los beneficios específicos de la plataforma para comprender cómo mejora la gestión y monitoreo de expediciones. | 2 |
| 5 | US-LP05 | Conocer las funcionalidades principales | Como visitante, quiero conocer las funcionalidades principales de la plataforma para entender el funcionamiento general del sistema. | 2 |
| 6 | US-LP06 | Acceder al registro desde la landing | Como visitante, quiero acceder rápidamente al registro desde la landing page para comenzar a utilizar la plataforma. | 1 |
| 7 | US-LP07 | Conocer testimonios y casos de uso | Como visitante, quiero conocer testimonios y casos de uso reales para tomar una decisión informada sobre la plataforma. | 2 |
| 8 | US-LP08 | Contactar al equipo de Tourmate | Como visitante, quiero contactar al equipo de Tourmate para resolver dudas relacionadas con la plataforma. | 3 |
| 9 | US-LP09 | Conocer al equipo de la startup | Como visitante, quiero conocer al equipo detrás de Tourmate para construir confianza en la propuesta de valor. | 1 |
| 10 | US-LP10 | Acceder a una demostración del sistema | Como visitante, quiero acceder a una demostración del sistema para comprender el funcionamiento de la plataforma antes de registrarme. | 5 |
| 11 | US09 | Crear tour | Como administrador de agencia, quiero crear un tour para organizar rutas y ponerlas a disposición de los turistas. | 5 |
| 12 | US10 | Editar tour | Como administrador de agencia, quiero editar la información de un tour para mantener actualizados los datos del recorrido. | 3 |
| 13 | US11 | Eliminar tour | Como administrador de agencia, quiero eliminar un tour para mantener actualizado el catálogo de la agencia. | 2 |
| 14 | US12 | Duplicar tour | Como administrador de agencia, quiero duplicar un tour existente para crear uno nuevo basado en una configuración previamente validada. | 3 |
| 15 | US13 | Asignar turistas a un tour | Como administrador de agencia, quiero asignar turistas a un tour para conformar el grupo de participantes del recorrido. | 3 |
| 16 | US14 | Desasignar turista de un tour | Como administrador de agencia, quiero desasignar a un turista de un tour para actualizar la composición del grupo. | 2 |
| 17 | US15 | Confirmar asistencia | Como turista, quiero confirmar mi asistencia a un tour para asegurar mi participación en el recorrido. | 2 |
| 18 | US16 | Buscar y filtrar tours | Como turista, quiero buscar y filtrar los tours disponibles para encontrar opciones acordes a mis intereses y preferencias. | 5 |
| 19 | US17 | Consultar detalle del tour | Como turista, quiero acceder a la información completa de un tour para tomar una decisión informada antes de participar. | 3 |
| 20 | US18 | Consultar tours de la agencia | Como administrador de agencia, quiero consultar todos los tours registrados por mi agencia para gestionarlos de forma centralizada. | 3 |
| 21 | US19 | Iniciar expedición | Como guía de tour, quiero marcar el inicio de la expedición para activar el monitoreo y registro del recorrido. | 3 |
| 22 | US20 | Visualizar ruta del tour | Como turista, quiero acceder a la ruta del tour para orientarme durante el recorrido. | 5 |
| 23 | US21 | Descargar ruta offline | Como turista, quiero descargar la información de la ruta de un tour para utilizarla sin conexión durante el recorrido. | 8 |
| 24 | US22 | Visualizar checkpoints del recorrido | Como turista, quiero conocer los checkpoints del tour para identificar mi progreso durante el recorrido. | 3 |
| 25 | US23 | Visualizar progreso del recorrido | Como turista, quiero consultar mi avance en el tour para conocer cuánto resta por completar. | 3 |
| 26 | US24 | Registrar checkpoint manual | Como guía de tour, quiero registrar manualmente el paso del grupo por un checkpoint para garantizar la trazabilidad cuando la detección automática no es posible. | 3 |
| 27 | US25 | Registrar experiencia del recorrido | Como turista, quiero registrar notas durante el tour para documentar mi experiencia. | 3 |
| 28 | US26 | Consultar clima del recorrido | Como turista, quiero consultar la información climática del recorrido para prepararme con el equipamiento adecuado. | 5 |
| 29 | US27 | Sincronización asincrónica de datos offline | Como turista, quiero que los datos capturados durante la expedición se sincronicen automáticamente al recuperar la conexión para no perder ningún registro generado. | 8 |
| 30 | US28 | Finalizar expedición | Como guía de tour, quiero marcar la finalización de la expedición para cerrar formalmente el monitoreo del recorrido. | 3 |
| 31 | US29 | Monitorear ubicación de turistas | Como administrador de agencia, quiero consultar la ubicación de los turistas para supervisar su seguridad durante la expedición. | 8 |
| 32 | US30 | Consultar estado general del grupo | Como administrador de agencia, quiero consultar el estado general de los turistas para detectar situaciones de riesgo durante la expedición. | 5 |
| 33 | US31 | Recibir alertas por anomalías | Como administrador de agencia, quiero recibir alertas ante situaciones de riesgo para responder oportunamente durante las expediciones. | 5 |
| 34 | US32 | Consultar estado de salud básico | Como guía de tour, quiero consultar alertas básicas del estado de salud de los turistas para actuar oportunamente ante posibles emergencias. | 3 |
| 35 | US33 | Reportar incidente | Como turista, quiero reportar incidentes para alertar oportunamente al personal responsable durante la expedición. | 3 |
| 36 | US34 | Reportar incidente desde el rol guía | Como guía de tour, quiero reportar incidentes detectados en campo para informar oportunamente al administrador de agencia. | 3 |
| 37 | US35 | Recibir datos biométricos del wearable | Como turista, quiero que el sistema reciba los datos biométricos capturados por mi wearable para que sean utilizados en el monitoreo de mi salud durante la expedición. | 8 |
| 38 | US36 | Consultar estado del wearable | Como turista, quiero consultar el estado de mi wearable para verificar su nivel de batería y conectividad antes de iniciar el recorrido. | 3 |
| 39 | US37 | Exportar reportes de expedición | Como administrador de agencia, quiero exportar reportes de las expediciones para analizar la información operativa. | 5 |
| 40 | US38 | Gestionar perfil personal | Como usuario registrado, quiero gestionar mi información personal para mantener actualizados los datos asociados a mi cuenta. | 3 |
| 41 | US39 | Actualizar foto de perfil | Como usuario registrado, quiero actualizar mi foto de perfil para personalizar mi cuenta en la plataforma. | 2 |
| 42 | US40 | Configurar preferencias de notificaciones | Como usuario registrado, quiero configurar las preferencias de notificaciones para recibir únicamente las que considero relevantes. | 3 |
| 43 | US41 | Recibir notificaciones de seguridad | Como usuario registrado, quiero recibir notificaciones de alerta de seguridad para mantenerme informado sobre eventos críticos relacionados con mi expedición. | 5 |
| 44 | US42 | Recibir notificaciones de tour | Como turista, quiero recibir notificaciones sobre actualizaciones de mi tour para mantenerme informado sobre cambios en mi participación. | 3 |
| 45 | US43 | Consultar historial de notificaciones | Como usuario registrado, quiero consultar el historial de notificaciones recibidas para revisar eventos pasados relacionados con mi cuenta. | 2 |
| 46 | TS02 | Endpoint de gestión de tours | Como developer, quiero exponer endpoints para la creación, consulta, actualización y eliminación de tours para que el frontend pueda administrar el catálogo de la agencia. | 5 |
| 47 | TS03 | Endpoint de gestión de expediciones | Como developer, quiero exponer endpoints para iniciar, consultar y finalizar expediciones para que el frontend pueda gestionar el ciclo de vida de cada recorrido activo. | 5 |
| 48 | TS04 | Endpoint de monitoreo de ubicación | Como developer, quiero exponer endpoints que registren y expongan las ubicaciones de los turistas en tiempo real para que el frontend pueda supervisar la seguridad de los participantes durante la expedición. | 5 |
| 49 | TS05 | Endpoint de gestión de incidentes | Como developer, quiero exponer endpoints que registren y expongan los incidentes reportados durante las expediciones para que el administrador de agencia pueda responder oportunamente. | 3 |
| 50 | TS06 | Endpoint de sincronización offline | Como developer, quiero exponer un endpoint que procese los datos almacenados localmente al recuperar conexión para que no se pierdan registros generados durante la expedición. | 8 |
| 51 | TS07 | Endpoint de gestión de alertas | Como developer, quiero exponer endpoints que generen y expongan alertas ante anomalías detectadas para que el administrador de agencia y el guía de tour puedan responder oportunamente. | 5 |
| 52 | TS08 | Endpoint de ingesta de telemetría IoT | Como developer, quiero exponer un endpoint que reciba y procese la telemetría enviada por los dispositivos wearables para que la información biométrica esté disponible para el monitoreo en tiempo real. | 8 |
| 53 | TS09 | Endpoint de perfil y notificaciones | Como developer, quiero exponer endpoints para gestionar el perfil del usuario y sus preferencias de notificaciones para que el frontend pueda personalizar la experiencia de cada usuario. | 3 |
| 54 | TS10 | Endpoint de exportación de reportes | Como developer, quiero exponer un endpoint que genere reportes exportables de las expediciones para que el administrador de agencia pueda analizar la información operativa. | 5 |
| 55 | US01 | Registro de turista | Como turista, quiero registrarme en la plataforma para acceder a los tours y funcionalidades disponibles del sistema. | 3 |
| 56 | US02 | Registro de administrador de agencia | Como administrador de agencia, quiero registrar mi agencia en la plataforma para gestionar tours y monitorear a los turistas asignados. | 3 |
| 57 | US03 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a las funcionalidades de la plataforma según mi rol. | 3 |
| 58 | US04 | Recuperación de contraseña | Como usuario registrado, quiero recuperar mi contraseña para no perder el acceso a mi cuenta en la plataforma. | 3 |
| 59 | US05 | Verificación de correo electrónico | Como turista, quiero verificar mi correo electrónico tras el registro para confirmar la validez de mi cuenta. | 2 |
| 60 | US06 | Cambio de contraseña | Como usuario registrado, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta. | 2 |
| 61 | US07 | Cierre de sesiones activas | Como usuario registrado, quiero cerrar todas mis sesiones activas en otros dispositivos para proteger mi cuenta. | 3 |
| 62 | US08 | Vincular dispositivo wearable | Como turista, quiero vincular un dispositivo wearable a mi cuenta para que el sistema capture mis signos vitales durante la expedición. | 5 |
| 63 | TS01 | Endpoint de registro y autenticación | Como developer, quiero exponer endpoints que registren usuarios y validen credenciales para que los clientes puedan crear cuentas y autenticarse de forma segura en la plataforma. | 5 |
# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### **Branding**

La identidad visual de la nueva landing page está orientada a transmitir una estética relacionada con la naturaleza, la aventura y una experiencia cercana y humana. El diseño combina tonalidades verdes y neutras con acentos cálidos, generando una apariencia sobria y natural.

La interfaz utiliza principalmente una paleta clara, donde el color de fondo tipo arena y las tonalidades verdes constituyen la base visual. Los colores cálidos se emplean como elementos de acento para destacar determinados componentes de la interfaz.

La identidad visual se complementa con fotografías relacionadas con expediciones y actividades de aventura. La misma imagen principal de la sección **Hero** es reutilizada en otras secciones mediante diferentes filtros de color y saturación para mantener coherencia visual.

### **Tone of Communication**

El tono de comunicación de la landing page se caracteriza por ser:

| Eje | Posición |
|---|---|
| Divertido / Serio | **Serio y cercano** — se busca comunicar profesionalismo sin generar una experiencia visual fría. |
| Formal / Casual | **Casual y directo** — el contenido utiliza mensajes breves y fáciles de comprender. |
| Respetuoso / Irreverente | **Respetuoso** — la comunicación mantiene una presentación profesional. |
| Entusiasta / Sereno | **Sereno con elementos de aventura** — las imágenes y los acentos visuales transmiten dinamismo sin sobrecargar la interfaz. |

La interfaz utiliza el español como idioma principal, establecido mediante `lang="es"` en el documento HTML.

### **Colors**

La paleta de colores está definida principalmente mediante variables CSS dentro de `:root`, permitiendo mantener consistencia entre los diferentes componentes de la landing page.

### **Color Palette**

| Variable / Color | Valor | Uso |
|---|---|---|
| `--background` / `--sand` | `#f8f7f2` | Fondo principal de la interfaz. |
| `--foreground` / `--primary` / `--forest` | `#29433a` | Color principal, textos destacados y elementos de navegación. |
| `--primary-foreground` | `#f8f7f2` | Texto utilizado sobre fondos de color primario. |
| `--border` | `#d9ded5` | Bordes de componentes y tarjetas. |
| `--muted` | `#6e7d73` | Variable definida para textos secundarios, aunque actualmente no presenta referencias en CSS. |
| `--sage` | `#dfe9dc` | Fondos y elementos visuales secundarios. |
| `--clay` | `#b87859` | Color de acento para elementos destacados. |
| `--white` | `#fffefb` | Fondos y elementos blancos. |

También se utilizan colores definidos directamente en el CSS para determinados componentes:

| Color | Valor | Uso |
|---|---|---|
| Peach | `#efc5a6` | Énfasis visual en determinados encabezados. |
| Green light | `#718078` | Variación de color para textos. |
| Green medium | `#65756c` | Variación de color para textos. |
| Green dark | `#496457` | Variación de color para textos. |
| Green hover | `#416253` | Estado `hover` de botones oscuros. |
| Peach hover | `#f1d4bd` | Estado `hover` de botones claros. |
| Clay light | `#c98b6c` | Fondo de la sección de contacto. |
| Traveler background | `#eee9df` | Fondo utilizado en la sección de viajeros. |
| Footer background | `#20362e` | Fondo del footer. |

El **Hero** utiliza además un gradiente verde con valores `rgba(35, 63, 53, ...)`, reforzando la integración visual de las imágenes con la paleta de la interfaz.

### **Typography**

La landing page utiliza principalmente la familia tipográfica **Geist**, complementada con **Geist Mono** y la familia serif **Georgia** en elementos específicos.

| Familia | Peso / Uso | Rol |
|---|---|---|
| Geist | `400`, `420`, `430`, `650` y otros pesos definidos por el diseño | Tipografía principal de títulos, cuerpo, navegación y componentes. |
| Geist Mono | Definida en el proyecto | Familia monoespaciada disponible en el sistema, sin uso visual identificado actualmente. |
| Georgia | `38px` en elementos específicos | Iniciales mostradas en las fotografías de los miembros y determinados elementos de énfasis. |

### **Escala tipográfica**

| Elemento | Familia | Tamaño | Peso | Uso |
|---|---|---|---|---|
| H1 | Geist | `clamp(54px, 8vw, 104px)` | `430` | Título principal del Hero. |
| H2 | Geist | `clamp(39px, 5.3vw, 70px)` | `420` | Encabezados principales de las secciones. |
| Eyebrow / Section label | Geist | `10px` | `650` | Etiquetas superiores de las secciones. |

El **H1** utiliza además un `letter-spacing` de `-0.07em`, mientras que los elementos **eyebrow** utilizan `letter-spacing: 0.18em`. Estos valores permiten establecer contraste entre los diferentes niveles de información.

### **Principios tipográficos**

La jerarquía tipográfica se construye principalmente mediante variaciones de tamaño, peso y espaciado dentro de la familia Geist. Los encabezados utilizan tamaños considerablemente mayores para establecer una jerarquía visual clara.

El **H1** utiliza la función `clamp()` para permitir una adaptación fluida de su tamaño según el ancho de la pantalla.

La familia **Georgia** se utiliza de manera puntual para aportar contraste visual en determinados elementos gráficos.

### **Spacing**

El diseño no utiliza una escala formal de espaciado basada en tokens, sino valores definidos directamente según las necesidades de cada sección.

Los principales valores identificados son:

| Valor | Uso principal |
|---|---|
| `12%` | Separación utilizada en determinados layouts. |
| `18px` | Gaps y espaciados internos. |
| `36px` | Separación entre determinados elementos. |
| `45px` | Gaps principales en componentes. |
| `108px` | Espaciado vertical de la sección de contacto. |
| `118px` | Espaciado utilizado en la sección del equipo. |
| `120px` | Espaciado estándar de determinadas secciones. |
| `88px` | Espaciado vertical utilizado en mobile. |

El contenedor principal utiliza un ancho máximo de `1160px`, acompañado de márgenes horizontales de `24px`.

### **Border Radius**

La interfaz utiliza diferentes niveles de redondeado según el componente:

| Valor | Uso |
|---|---|
| `999px` | Elementos tipo pill y botones redondeados. |
| `18px` | Tarjetas de miembros del equipo. |
| `50%` | Iconos circulares, como los elementos `.check-icon`. |

No se utilizan variables CSS específicas para definir tokens de `border-radius`.

### **Shadows**

La interfaz utiliza un enfoque visual plano y **no presenta sombras (`box-shadow`) en sus componentes**.

La sensación de profundidad se consigue principalmente mediante diferencias de color, bordes y transformaciones durante las interacciones. En particular, los botones utilizan una transformación de `translateY(-2px)` durante el estado `hover`.


### 4.1.2. Web Style Guidelines

### **Layout y Grid System**

La estructura de la landing page utiliza principalmente **Flexbox** para organizar los elementos de navegación y diferentes componentes de la interfaz, complementándose con estructuras de layout específicas para cada sección.

El contenido principal está limitado a un ancho máximo de:

`max-width: min(1160px, calc(100% - 48px))`

Esto establece un ancho máximo de **1160px** y mantiene un margen horizontal de **24px** en pantallas donde el contenido necesita adaptarse.

Las diferentes secciones utilizan distribuciones que se adaptan al tamaño disponible de la pantalla mediante reglas responsive.

### **Navbar**

La barra de navegación se presenta de forma transparente sobre la sección Hero.

Características principales:

- Padding superior de `26px`.
- Distribución mediante Flexbox.
- Links de navegación ubicados en la parte central/derecha.
- Separación de `42px` entre determinados elementos de navegación.
- No utiliza posición `fixed` ni `sticky`.
- No implementa un menú hamburguesa.
- En pantallas de hasta `780px`, los links de navegación dejan de mostrarse.

La navegación incluye además una etiqueta accesible mediante `aria-label="Navegación principal"`.

### **Buttons**

La landing page utiliza dos variantes principales de botones:

| VarianteAparienciaUso |                             |                                                     |
| --------------------- | --------------------------- | --------------------------------------------------- |
| `.button-light`       | Fondo claro con texto verde | Acciones principales sobre fondos oscuros o verdes. |
| `.button-dark`        | Fondo verde con texto claro | Acciones principales sobre fondos claros.           |

Los botones modifican su apariencia durante el estado `hover`. La variante clara utiliza el color `#f1d4bd`, mientras que la variante oscura utiliza `#416253`.

También existen enlaces de texto mediante `.text-link`, con variantes `.light-link` y `.dark-link` según el fondo donde se presentan.

Los botones utilizan una transformación visual de `translateY(-2px)` durante el estado hover para proporcionar retroalimentación visual al usuario.

### **Cards**

Las tarjetas utilizan un estilo visual plano y minimalista.

La tarjeta de miembros del equipo (`.member-card`) presenta:

- Fondo color arena.
- Borde de `1px`.
- `border-radius: 18px`.
- `overflow: hidden`.

La sección de fotografía de cada miembro utiliza:

- Fondo color sage.
- Altura mínima de `145px`.
- Iniciales representadas mediante Georgia con un tamaño de `38px`.

### **Section Elements**

Los elementos tipo eyebrow utilizados como identificadores de sección presentan:

- Tamaño de fuente de `10px`.
- Peso `650`.
- `letter-spacing: 0.18em`.

Estos elementos funcionan como etiquetas visuales que preceden a los encabezados principales y ayudan a establecer una jerarquía clara dentro de cada sección.

### **Hero Images**

La imagen utilizada en el Hero corresponde a `hero-expedition.png`.

Esta misma imagen se reutiliza en diferentes secciones de la landing page aplicando modificaciones visuales mediante CSS:

- Para la sección relacionada con agencias se utiliza `filter: saturate(.7)`.
- Para la sección relacionada con viajeros se utiliza `filter: saturate(.55) hue-rotate(8deg)`.

Estas variaciones permiten reutilizar el recurso visual manteniendo una apariencia diferenciada entre las secciones.

### **Responsive Breakpoints**

La landing page utiliza un único breakpoint responsive:

| BreakpointValorDescripción |                    |                                                                            |
| -------------------------- | ------------------ | -------------------------------------------------------------------------- |
| Mobile                     | `max-width: 780px` | Adapta la navegación y distribución del contenido para pantallas pequeñas. |

En pantallas de hasta `780px`, los links de navegación dejan de mostrarse y determinados layouts modifican su distribución.

El footer utiliza una distribución de dos columnas en mobile, mientras que el elemento correspondiente a la identidad de la marca ocupa el ancho completo.

No se utiliza un breakpoint independiente para tablet.

### **Accessibility**

La landing page incorpora diferentes elementos orientados a mejorar la accesibilidad:

- Uso de elementos semánticos como `<main>`, `<section>`, `<nav>`, `<footer>`, `<article>`, `<ul>` y `<li>`.
- La navegación utiliza `aria-label="Navegación principal"`.
- Los elementos SVG decorativos utilizan `aria-hidden="true"`.
- Las imágenes implementadas mediante fondos CSS utilizan `role="img"` y `aria-label` para proporcionar una descripción accesible.
- Las fotografías de los miembros cuentan con `aria-label`.
- El documento HTML establece `lang="es"`.
- Se utiliza antialiasing para mejorar la representación visual de los textos.

Actualmente no se encuentra implementado un tratamiento específico mediante `:focus-visible` ni una configuración de `prefers-reduced-motion`.

### **Internationalization**

La implementación actual de la landing page establece el español como idioma del documento mediante:

`<html lang="es">`

No se identifica en la implementación actual un sistema de internacionalización que permita alternar entre diferentes idiomas.

# 4.2. Information Architecture

La arquitectura de información de Tourmate está diseñada para un landing page de una sola página. El contenido se organiza mediante secciones verticales, navegación interna por anclas, llamadas a la acción y un pie de página con enlaces adicionales. La estructura permite presentar progresivamente la propuesta de valor, diferenciar el contenido según las principales audiencias y conducir al usuario hacia el contacto.

No se observan pantallas independientes, autenticación, perfiles, áreas privadas, sistemas de búsqueda ni filtros. Por ello, la arquitectura se centra principalmente en la organización del contenido, el etiquetado, la navegación y la presentación de información dentro de una única página.

---

#### 4.2.1. Organization Systems

**Organización visual del contenido**

La información del landing page se distribuye en las siguientes secciones principales:

- **Inicio (`#inicio`)**: presenta la identidad de Tourmate, el mensaje principal y las primeras llamadas a la acción.
- **Nuestra idea (`#vision`)**: explica el propósito de la propuesta y presenta los conceptos “Más claridad”, “Más confianza” y “Más recuerdos”.
- **Agencias (`#agencias`)**: comunica el valor de la propuesta para agencias y guías.
- **Viajeros (`#viajeros`)**: presenta el valor de la propuesta para las personas que desean viajar.
- **Team Development (`#team-development`)**: presenta al equipo y sus áreas de trabajo.
- **Contacto (`#contacto`)**: contiene el cierre de la propuesta y una llamada a la acción.
- **Footer**: agrupa enlaces de exploración, contacto y redes sociales.

Esta organización permite recorrer la propuesta desde una presentación general hacia explicaciones específicas por audiencia y, finalmente, hacia una acción de contacto.

***Jerarquía visual (Visual Hierarchy)***

La jerarquía visual se utiliza para establecer diferentes niveles de importancia dentro del contenido. Se construye mediante:

- Un mensaje principal destacado en el hero: **“Más camino. Menos ruido.”**
- Títulos de sección con elementos destacados en cursiva, como “conexión”, “bien acompañada”, “historia”, “en equipo” y “algo más sencillo”.
- Etiquetas superiores de sección, como:
    - “TURISMO DE AVENTURA, SIN COMPLICACIONES”
    - “UNA FORMA MÁS NATURAL DE VIAJAR”
    - “PARA AGENCIAS Y GUÍAS”
    - “PARA VIAJEROS”
    - “TEAM DEVELOPMENT”
    - “EL PRÓXIMO DESTINO EMPIEZA AQUÍ”
- Listas de beneficios en las secciones dirigidas a agencias y viajeros.
- Diferenciación mediante imágenes, fondos de color, botones, enlaces subrayados y separadores.

La jerarquía orienta al usuario primero hacia la propuesta de valor, posteriormente hacia los públicos principales y finalmente hacia el contacto.

***Organización secuencial (Step-by-step)***

Se aplica una organización secuencial o narrativa mediante el orden vertical de las secciones. El recorrido principal es:

**Presentación de la marca → Nuestra idea → Agencias/Viajeros → Team Development → Contacto → Footer**

Esta secuencia acompaña al usuario desde el conocimiento inicial de Tourmate hasta una posible acción de contacto.

***Organización por audiencia (Audience-based)***

La categorización por audiencia se aplica de forma explícita en el landing page. El contenido dirigido a los principales públicos se separa en dos secciones:

| Audiencia | Sección | Contenido |
|---|---|---|
| Agencias y guías | Agencias | Presentación de recorridos, acompañamiento de grupos y construcción de confianza |
| Viajeros | Viajeros | Elección de experiencias, preparación del viaje y búsqueda de una experiencia acorde |

Esta organización permite que cada audiencia identifique rápidamente el contenido relacionado con sus intereses.

***Organización temática (Topic-based)***

El contenido también se organiza mediante diferentes temas:

- Propuesta general de Tourmate.
- Claridad, confianza y recuerdos.
- Servicios o beneficios para agencias y guías.
- Experiencia para viajeros.
- Equipo de trabajo.
- Contacto y canales externos.

Esta organización permite presentar diferentes aspectos de la propuesta sin mezclar los contenidos dirigidos a cada contexto.

***Organización matricial (Matrix)***

No implementado. El landing page no contiene tablas de datos, matrices comparativas, catálogos ni estructuras que permitan consultar simultáneamente diferentes categorías o atributos.

***Organización cronológica (Chronological)***

No implementado. El contenido no se organiza mediante fechas, eventos históricos, publicaciones ni información ordenada cronológicamente.

***Organización jerárquica (Hierarchical)***

Sí está implementada a nivel de página. Existe una estructura principal compuesta por el hero, las secciones de contenido, la sección de contacto y el footer. Dentro de cada sección se utilizan títulos, subtítulos, párrafos, listas, imágenes y llamadas a la acción con diferentes niveles de importancia.

---

#### 4.2.2. Labeling Systems

Las etiquetas utilizadas en Tourmate buscan identificar de forma directa las diferentes secciones y acciones disponibles en el landing page.

***Etiquetas de navegación principal***

| Etiqueta | Destino | Función |
|---|---|---|
| TOURMATE | `#inicio` | Identifica la marca y permite regresar al inicio |
| Agencias | `#agencias` | Dirige a la sección para agencias y guías |
| Viajeros | `#viajeros` | Dirige a la sección para viajeros |
| Team Development | `#team-development` | Dirige a la sección del equipo |
| Nuestra idea | `#vision` | Dirige a la explicación de la propuesta |
| Conocer más | `#contacto` | Dirige a la sección de contacto |

La navegación principal se encuentra dentro de un elemento `<nav>` que utiliza la etiqueta accesible **“Navegación principal”**.

***Etiquetas de acciones principales***

| Etiqueta | Destino | Función |
|---|---|---|
| Conoce Tourmate | `#vision` | Dirige a la explicación de la propuesta |
| Descubre para quién es | `#agencias` | Dirige hacia la segmentación principal por audiencia |
| Hablemos | `#contacto` | Dirige al contacto desde la sección de agencias |
| Quiero explorar | `#contacto` | Dirige al contacto desde la sección de viajeros |
| Conoce la propuesta | `#agencias` | Dirige hacia la sección dirigida a agencias |

Las etiquetas de las llamadas a la acción utilizan textos breves relacionados directamente con el contenido o la acción que el usuario puede realizar.

***Títulos y etiquetas de contenido***

| Etiqueta o título | Sección |
|---|---|
| Más camino. Menos ruido. | Inicio |
| Todo empieza con una buena conexión. | Nuestra idea |
| Más claridad | Beneficios generales |
| Más confianza | Beneficios generales |
| Más recuerdos | Beneficios generales |
| Tu experiencia, bien acompañada. | Agencias y guías |
| Elige tu próxima historia. | Viajeros |
| Construimos el viaje en equipo. | Team Development |
| Hagamos del viaje algo más sencillo. | Contacto |

***Etiquetas del footer***

| Categoría | Enlaces |
|---|---|
| Explora | Nuestra idea, Para agencias, Para viajeros |
| Conversemos | hola@tourmate.experience, Quiero conocer más |
| Síguenos | Instagram, LinkedIn, Facebook |

Los enlaces de redes sociales existentes apuntan actualmente a `#inicio`. No se implementan destinos externos específicos para dichas redes.

---

#### 4.2.3. SEO Tags and Meta Tags

Los metadatos del landing page se definen principalmente en `app/layout.tsx`.

| Elemento | Valor actual | Propósito |
|---|---|---|
| `<title>` | `Tourmate \| Gestión de experiencias al aire libre` | Define el título mostrado por el navegador y utilizado por los buscadores |
| `description` | `La plataforma que conecta agencias, guías y viajeros para crear expediciones más claras, seguras y memorables.` | Resume el contenido principal del sitio |
| `generator` | `v0.app` | Identifica la herramienta de generación del proyecto |
| `lang` | `es` | Indica que el documento está en español |
| `themeColor` | `#f4f1e9` | Define el color asociado a la interfaz del navegador |
| `colorScheme` | `light` | Declara que el sitio utiliza un esquema visual claro |
| `userScalable` | `true` | Permite el escalado del contenido por parte del usuario |
| `icons.icon` | `/icon-light-32x32.png`, `/icon-dark-32x32.png`, `/icon.svg` | Define los iconos del sitio |
| `icons.apple` | `/apple-icon.png` | Define el icono para dispositivos Apple |

Los siguientes elementos no se encuentran implementados explícitamente:

- `keywords`: No implementado.
- `author`: No implementado.
- Open Graph: No implementado.
- Twitter Cards: No implementado.
- `robots`: No implementado.
- Canonical URL: No implementado.
- Datos estructurados Schema.org: No implementado.

La etiqueta `lang="es"` sí se encuentra implementada en el elemento `<html>`.

---

#### 4.2.4. Searching Systems

***Landing Page***

La landing page no implementa un sistema de búsqueda textual debido a que su contenido es estático y se encuentra organizado en secciones claramente diferenciadas.

Tampoco se implementan:

- Búsqueda textual.
- Filtros.
- Búsqueda por categorías.
- Ordenamiento de resultados.
- Autocompletado.
- Campos de búsqueda.
- Página de resultados.

En lugar de un sistema de búsqueda, la navegación mediante anclas permite localizar directamente las diferentes secciones. El usuario puede acceder al contenido mediante la navegación principal, las llamadas a la acción y los enlaces del footer.

Esta solución resulta adecuada para la estructura actual del proyecto, ya que el contenido corresponde a una landing page informativa y no a un catálogo o repositorio con grandes cantidades de información.

---

#### 4.2.5. Navigation Systems

***Landing Page***

La landing page implementa un sistema de navegación interna mediante enlaces a las diferentes secciones de la página. Estos enlaces utilizan identificadores HTML y permiten desplazarse directamente hacia el contenido correspondiente.

| Enlace | Destino |
|---|---|
| TOURMATE | `#inicio` |
| Agencias | `#agencias` |
| Viajeros | `#viajeros` |
| Team Development | `#team-development` |
| Nuestra idea | `#vision` |
| Conocer más | `#contacto` |

El documento utiliza `scroll-behavior: smooth`, por lo que el desplazamiento hacia las anclas se realiza de manera suave.

***CTA del Hero***

El hero contiene dos acciones principales:

- **“Conoce Tourmate”** → `#vision`
- **“Descubre para quién es”** → `#agencias`

Estas acciones conducen al usuario desde la introducción hacia la explicación de la propuesta y posteriormente hacia la segmentación por audiencia.

***Navegación contextual***

Dentro del contenido también existen enlaces que continúan el recorrido del usuario:

- **“Conoce la propuesta”** → `#agencias`
- **“Hablemos”** → `#contacto`
- **“Quiero explorar”** → `#contacto`

No existe navegación entre páginas independientes ni un sistema de breadcrumbs.

***Comportamiento Desktop***

En desktop, la barra de navegación presenta:

- La marca a la izquierda.
- Los enlaces principales en la zona central o derecha.
- El CTA **“Conocer más”** al extremo derecho.

La navbar no está implementada como un elemento fijo o sticky. Forma parte del hero y deja de estar visible al avanzar por la página.

***Comportamiento Responsive / Mobile***

En resoluciones de hasta `780px`:

- Los enlaces de `.nav-links` dejan de mostrarse.
- El CTA **“Conocer más”** permanece visible.
- No se implementa un menú hamburguesa.
- El contenido principal se reorganiza en una sola columna en las secciones correspondientes.
- Las acciones del hero se apilan verticalmente.
- El footer adopta una distribución de dos columnas, mientras la marca ocupa todo el ancho.

Por lo tanto, la versión móvil utiliza una navegación reducida y no implementa un menú alternativo para acceder a todos los enlaces de la navegación principal.

***Footer***

El footer funciona como un sistema de navegación complementario y se organiza en cuatro áreas principales:

**Marca**

- Tourmate
- “Viajes con sentido, conexiones más humanas.”

**Explora**

- Nuestra idea → `#vision`
- Para agencias → `#agencias`
- Para viajeros → `#viajeros`

**Conversemos**

- `hola@tourmate.experience` → enlace `mailto:`
- Quiero conocer más → `#contacto`

**Síguenos**

- Instagram → `#inicio`
- LinkedIn → `#inicio`
- Facebook → `#inicio`

El footer también muestra:

- © 2026 Tourmate
- “Experiencias para recordar.”

***Recorrido esperado del usuario***

El recorrido principal propuesto por la arquitectura actual es:

**Inicio → Nuestra idea → Agencias / Viajeros → Team Development → Contacto → Footer**

El usuario también puede saltar directamente a una sección utilizando los enlaces de la navegación principal, las llamadas a la acción o los enlaces del footer.

No se implementan flujos de registro, compra, autenticación, búsqueda, filtrado ni navegación hacia un área privada.

## 4.3 Landing Page UI Design
###  4.3.1 Landing Page Wireframe
Para la landing page se realizaron low-fi Wireframes de cada una de las pantallas del sitio:

![WF hero.png](../assets/images/WF%20hero.png)
![WF intro.png](../assets/images/WF%20intro.png)
![WF agentes.png](../assets/images/WF%20agentes.png)
![WF viajes.png](../assets/images/WF%20viajes.png)
![WF team.png](../assets/images/WF%20team.png)
![WF footer.png](../assets/images/WF%20footer.png)

### 4.3.2 Landing Page Mock-up

**Estructura general y lineamientos visuales**

El Mock-Up de la landing page de Tourmate se desarrolla con un nivel de fidelidad alta, empleando contenido real, imágenes representativas y componentes visuales funcionales, siguiendo una línea gráfica moderna orientada a los viajes, la conexión entre personas y las experiencias al aire libre.

**Aplicación del Branding**

Se incorporan los elementos de identidad visual de Tourmate, como el logotipo, el icono lineal de montaña, la paleta cromática y los mensajes principales de la marca. El logotipo se ubica en la parte superior izquierda dentro de la barra de navegación, fortaleciendo el reconocimiento de marca.

La propuesta visual transmite confianza, cercanía y conexión con la naturaleza mediante el uso de verdes, tonos arena, blanco y terracota, asociados con los viajes, la exploración y las experiencias al aire libre.

**Estructura visual:**

- **Zona superior:** barra de navegación con el logotipo de Tourmate, enlaces principales hacia las secciones de la landing page y botón de llamada a la acción “Conocer más”.


- **Sección principal (Hero):** mensaje central “Más camino. Menos ruido.”, acompañado por una imagen relacionada con viajes y naturaleza, un texto introductorio y los botones “Conoce Tourmate” y “Descubre para quién es”.


- **Sección Nuestra idea:** presentación del propósito de Tourmate mediante el mensaje “Todo empieza con una buena conexión”, acompañado de los conceptos “Más claridad”, “Más confianza” y “Más recuerdos”.


- **Sección Agencias y guías:** presentación de la propuesta dirigida a agencias y guías mediante el mensaje “Tu experiencia, bien acompañada.”, incluyendo una descripción, beneficios y una llamada a la acción.


- **Sección Viajeros:** presentación de la propuesta dirigida a los usuarios que buscan nuevas experiencias mediante el mensaje “Elige tu próxima historia.”, acompañado de contenido descriptivo y elementos visuales relacionados con los viajes.


- **Sección Team Development:** presentación de los integrantes del equipo mediante tarjetas que incluyen el nombre, rol o área de trabajo y un espacio visual para cada integrante.


- **Zona de contacto:** sección con fondo terracota que presenta el mensaje “Hagamos del viaje algo más sencillo.”, un texto de cierre y el botón de llamada a la acción “Hablemos”.


- **Zona inferior (Footer):** presentación de la identidad de Tourmate, enlaces de navegación, correo de contacto y enlaces a redes sociales.

**Aplicación de guía de estilos:**

- **Tipografía:** uso de Geist como tipografía principal, con títulos de gran tamaño y peso ligero para generar una apariencia moderna y editorial.


- **Jerarquía tipográfica:**
    - Títulos principales: 48–64 px.
    - Títulos secundarios: 32–40 px.
    - Texto base: 16–18 px.
  

- **Paleta cromática:**
    - Verde oscuro (#29433A) como color principal para textos, botones y fondos.
    - Verde suave (#DFE9DC) para superficies secundarias.
    - Arena (#F8F7F2) y blanco (#FFFEFB) para fondos claros.
    - Terracota (#B87859) como color de acento y llamados a la acción.
    - Gris verdoso (#6E7D73) para textos secundarios.
  

- **Elementos visuales:** botones con forma de píldora, bordes sutiles, tarjetas con esquinas redondeadas, líneas horizontales y espacios amplios entre secciones.

- **Layout:** estructura modular basada principalmente en bloques de una y dos columnas, con imágenes y contenido textual distribuidos de manera equilibrada. En dispositivos móviles, las columnas se reorganizan verticalmente para mantener la legibilidad.

**Principios de diseño y arquitectura de la información:**

El contenido se organiza de manera progresiva para conducir al usuario desde la presentación de Tourmate hasta sus propuestas para agencias, guías y viajeros, finalizando con una llamada a la acción.

Se prioriza la claridad mediante títulos directos, textos breves y secciones diferenciadas. La jerarquía visual se establece mediante el tamaño de los títulos, el contraste de colores, las imágenes y la ubicación estratégica de los botones.

La consistencia se mantiene mediante el uso repetido de la paleta cromática, tipografía, botones y estilos de contenido. Asimismo, los enlaces internos permiten desplazarse entre las diferentes secciones de la landing page y facilitan el recorrido del usuario.

**Diseño inclusivo:**

El Mock-Up considera principios de accesibilidad mediante una estructura semántica, textos legibles, contraste adecuado entre fondos y contenidos, botones visibles y navegación claramente identificable.

La interfaz también presenta un diseño responsive que adapta las columnas, imágenes, botones y contenidos a diferentes tamaños de pantalla. En dispositivos móviles, las acciones principales se apilan verticalmente y los contenidos se reorganizan para facilitar la lectura y navegación.

![hero section](../assets/images/hero-mockup.png)
![intro section](../assets/images/intro-mockup.png)
![agencia section.png](../assets/images/agencia-mockup.png)
![viajeros section.png](../assets/images/viajeros-mockup.png)
![team section.png](../assets/images/team-mockup.png)
![footer](../assets/images/footer-mockup.png)

# 4.4. Web Applications UX/UI Design



## 4.4.1. Web Applications Wireframes

![wirefrane 1.png](../assets/images/wirefrane%201.png)
![wireframe 2.png](../assets/images/wireframe%202.png)
![wireframe 3.png](../assets/images/wireframe%203.png)
![wireframe 4.png](../assets/images/wireframe%204.png)
![wireframe 5.png](../assets/images/wireframe%205.png)
![wireframe6.png](../assets/images/wireframe6.png)
![wireframe 7.png](../assets/images/wireframe%207.png)
![wireframe 8.png](../assets/images/wireframe%208.png)
![wireframe 9.png](../assets/images/wireframe%209.png)
![wireframe 10.png](../assets/images/wireframe%2010.png)
![wireframe 11.png](../assets/images/wireframe%2011.png)
![wireframe 12.png](../assets/images/wireframe%2012.png)
![wireframe 13.png](../assets/images/wireframe%2013.png)
![wireframe 14.png](../assets/images/wireframe%2014.png)
![wireframe 15.png](../assets/images/wireframe%2015.png)



## 4.4.2. Web Applications Wireflow Diagrams

User Goal: Crear una ruta comercial con puntos de control BLE preconfigurados, verificar el inventario de hardware IoT y conformar el grupo de turistas asignando dispositivos y un guía líder antes de la salida a campo.
![wireflow 1.png](../assets/images/wireflow%201.png)

User Goal: Supervisar la posición y constantes vitales de los participantes en rutas de baja conectividad, detectar desvíos o anomalías biométricas de manera oportuna y ejecutar el protocolo de emergencia hasta el cierre formal del incidente.
![wireflow 2.png](../assets/images/wireflow%202.png)

User Goal: Finalizar administrativamente un tour completado, auditar los tiempos reales frente a los proyectados y generar informes técnicos en PDF y CSV para clientes y auditorías de seguridad.
![wireflow 3.png](../assets/images/wireflow%203.png)

## 4.4.3. Web Applications Mock-ups
![mock-up 1.png](../assets/images/mock-up%201.png)
![mock-up 2.png](../assets/images/mock-up%202.png)
![mock-up 3.png](../assets/images/mock-up%203.png)
![mock-up 4.png](../assets/images/mock-up%204.png)
![mock-up 5.png](../assets/images/mock-up%205.png)
![mock-up 6.png](../assets/images/mock-up%206.png)
![mock-up 7.png](../assets/images/mock-up%207.png)
![mock-up 8.png](../assets/images/mock-up%208.png)
![mock-up 9.png](../assets/images/mock-up%209.png)
![mock-up 10.png](../assets/images/mock-up%2010.png)
![mock-up 11.png](../assets/images/mock-up%2011.png)
![mock-up 12.png](../assets/images/mock-up%2012.png)
![mock-up 13.png](../assets/images/mock-up%2013.png)
![mock-up 14.png](../assets/images/mock-up%2014.png)
![mock-up 15.png](../assets/images/mock-up%2015.png)

## 4.4.4. Web Applications User Flow Diagrams

User Goal: Crear una ruta comercial con puntos de control BLE preconfigurados, verificar el inventario de hardware IoT y conformar el grupo de turistas asignando dispositivos y un guía líder antes de la salida a campo.
![User Flow Diagrams 1.png](../assets/images/User%20Flow%20Diagrams%201.png)

User Goal: Supervisar la posición y constantes vitales de los participantes en rutas de baja conectividad, detectar desvíos o anomalías biométricas de manera oportuna y ejecutar el protocolo de emergencia hasta el cierre formal del incidente.
![User Flow Diagrams 2.png](../assets/images/User%20Flow%20Diagrams%202.png)

User Goal: Finalizar administrativamente un tour completado, auditar los tiempos reales frente a los proyectados y generar informes técnicos en PDF y CSV para clientes y auditorías de seguridad.
![User Flow Diagrams 3.png](../assets/images/User%20Flow%20Diagrams%203.png)

### 4.5. Web Applications Prototyping
![Web Applications Prototyping.png](../assets/images/Web%20Applications%20Prototyping.png)
Link del figma: [Enlace](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=tXUhENNxmbTL7x4j-1)

![video user flow diagram.png](../assets/images/video%20user%20flow%20diagram.png)
Link del video de la explicación del prototipo: [Enlace](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQCuFKbOpmiiSJeRYyHyCHURAbzlqqLM2OWZEzgkSSqIqzo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=pKQoRJ)

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

En esta sección se presenta el Design-Level EventStorming del proyecto Tourmate, el cúal se desarrollo en 4 pasos, los cúales se van a explicar a continuación:

* Para empezar, identificamos todos los Domain Events de Tourmate. En esta etapa analizamos cada funcionalidad obtenida durante el análisis del negocio y registramos todos los eventos importantes que modifican el estado del sistema, como el registro de usuarios, la creación de tours, el inicio de recorridos, el reporte de incidentes o la generación de reportes:

![Event Storming](../assets/images/Design-Level-EventStorming-1.png)

* Luego, procedimos a organizar los Domain Events, eliminando los eventos repetidos, agrupamos aquellos que pertenecían al mismo flujo de negocio y ordenamos la secuencia lógica de cada proceso. Este refinamiento permitió obtener una visión más clara de los distintos procesos que forman parte de Tourmate antes de incorporar elementos adicionales del modelo:

![Event Storming](../assets/images/Design-Level-EventStorming-2.png)


* Después de esto, comenzamos a construir cada flujo funcional. Para cada Domain Event identificamos el comando que lo desencadena, representado por notas azules. Además, agregamos los actores responsables de ejecutar cada comando mediante notas amarillas, cada Read Model para la toma de decisiones de los actores antes de realizar un comando y las políticas representadas en color morado, las cuales automatizan determinadas acciones cuando ocurre un evento. De esta manera logramos modelar el comportamiento completo de cada proceso de negocio:

![Event Storming](../assets/images/Design-Level-EventStorming-3.png)

* Finalmente, integramos todos los flujos individuales en los respectivos Bounded Context del dominio:

![Event Storming](../assets/images/Design-Level-EventStorming-4.png)

Enlace para acceder al tablero de Miro:
https://miro.com/app/board/uXjVHrbqRdA=/?share_link_id=127054225300

### 4.6.2. Software Architecture Context Level Diagram

![ContexDiagram](../assets/images/context-level-diagram.png)

### 4.6.3. Software Architecture Container Level Diagrams

![ContainerDiagram](../assets/images/container-level-diagram.png)

### 4.6.4. Software Architecture Component Level Diagrams

#### 4.6.4.1. Subscriptions and Payment Management Component Diagram
![ComponentDiagram](../assets/images/subscriptions-payment-components.png)

#### 4.6.4.2. Tour Monitoring Component Diagram
![ComponentDiagram](../assets/images/tour-monitoring-components.png)

#### 4.6.4.3. Safety Incident Component Diagram
![ComponentDiagram](../assets/images/safety-incident-components.png)

#### 4.6.4.4. Tour Management Component Diagram
![ComponentDiagram](../assets/images/tour-management-components.png)

#### 4.6.4.5. Feedback and Review Component Diagram
![ComponentDiagram](../assets/images/feedback-review-components.png)

#### 4.6.4.6. IAM Component Diagram
![ComponentDiagram](../assets/images/iam-components.png)

## 4.7. Software Object-Oriented Design

El diseño orientado a objetos de TourMate se fundamenta en los principios de **Domain-Driven Design (DDD)** y **Clean Architecture**, asegurando que el modelo de clases refleje con fidelidad las entidades, agregados e invariantes del negocio identificados durante la fase de análisis de dominio. La arquitectura desacopla la lógica del sistema en contextos delimitados (*Bounded Contexts*) independientes, los cuales interactúan entre sí mediante contratos estrictos, Value Objects inmutables e interfaces de comunicación limpias.

### 4.7.1. Class Diagrams

A continuación, se presenta la arquitectura de clases del ecosistema TourMate, iniciando con el diagrama general del sistema y profundizando posteriormente en cada uno de los *Bounded Contexts* que lo integran:

#### Diagrama de Clases General de TourMate

Este diagrama proporciona una visión integradora y holística de la arquitectura de clases del sistema, evidenciando las relaciones estructurales, asociaciones y dependencias entre los distintos contextos delimitados:

![TourMate General Class Diagram](../assets/images/TourMate_ClassDiagram.png)

---

#### 4.7.1.1. Bounded Context: Shared Kernel

Agrupa los Value Objects transversales reutilizados a lo largo de todo el dominio de la aplicación para garantizar consistencia semántica, tipado fuerte y prevenir el uso de tipos primitivos dispersos (*Primitive Obsession*):
- **Value Objects:** `Money` (encapsula monto decimal y moneda con operaciones aritméticas seguras), `Currency` (código ISO normalizado), `Coordinates` (latitud y longitud geográficas con métodos de cálculo de distancia haversine), e identificadores universales únicos (*UUID-based VOs*): `ActiveTourId`, `TourId`, `TourScheduleId`, `AgencyId` y `UserId`.

![Shared Class Diagram](../assets/images/TourMate_Shared_ClassDiagram.png)

---

#### 4.7.1.2. Bounded Context: Identity and Access Management

Gestiona el registro, autenticación, control de sesiones y ciclo de vida de las cuentas de usuario y perfiles organizacionales de la plataforma:
- **Aggregate Root:** `User` (administra email, hash de credenciales, estado de activación de cuenta y rol asignado).
- **Aggregates y Entidades:** `TourGuide` (perfil profesional del guía turístico, idiomas y acreditaciones) y `Agency` (perfil empresarial, razón social, RUC/Tax ID y datos de contacto comercial).
- **Value Objects:** `EmailAddress`, `Password`, `PersonName`, `PhoneNumber`, `ContactInfo`, `BusinessName`.
- **Enumeraciones:** `Role` (`ADMIN`, `TOURIST`, `AGENCY_OWNER`, `TOUR_GUIDE`).

![Identity & Access Class Diagram](../assets/images/TourMate_IdentityAccess_ClassDiagram.png)

---

#### 4.7.1.3. Bounded Context: Tour Management

Controla la creación, configuración, publicación y administración del catálogo de experiencias turísticas ofrecidas por las agencias:
- **Aggregate Root:** `Tour` (encapsula título, descripción, nivel de dificultad, precio base, estado de visibilidad y la colección ordenada de paradas turísticas).
- **Aggregates y Entidades:** `TourSchedule` (representa una fecha y hora programada de expedición, gestionando capacidad máxima de cupos y lista de turistas asignados), `Checkpoint` (parada intermedia con nombre, coordenadas de geolocalización y orden secuencial) y `Participant` (turista asignado con fecha de inscripción y estado).
- **Value Objects:** `TourId`, `CheckpointId`, `TourDetails`, `DepartureDateTime`.
- **Enumeraciones:** `TourStatus` (`DRAFT`, `PUBLISHED`, `UNAVAILABLE`) y `TourScheduleStatus` (`OPENED`, `CLOSED`).

![Tour Management Class Diagram](../assets/images/TourMate_TourManagement_ClassDiagram.png)

---

#### 4.7.1.4. Bounded Context: Tour Monitoring

Gestiona la supervisión en tiempo real de las expediciones en curso, calculando el progreso del recorrido, verificando la presencia del grupo y registrando telemetría operativa:
- **Aggregate Root:** `ActiveTour` (coordina la expedición activa en campo, registrando el guía asignado, tiempos de inicio/finalización, coordenadas actuales y estado operacional).
- **Operaciones de Dominio:** `startTour()`, `updateLocation()`, `completeCheckpoint()`, `finishTour()`.
- **Interacciones:** Se comunica con el contexto de navegación para recibir coordenadas GPS y con el contexto de seguridad para alertar anomalías, desvíos o retrasos críticos durante el recorrido.

![Tour Monitoring Class Diagram](../assets/images/Tourmate_TourMonitoring_ClassDiagram.png)

---

#### 4.7.1.5. Bounded Context: Safety and Incident Management

Supervisa los signos vitales, alertas biométricas y la documentación formal de incidentes o emergencias médicas y mecánicas durante las expediciones:
- **Aggregate Root:** `Incident` (registra el reporte formal de una eventualidad, usuario afectado, expedición asociada, coordenadas geográficas, fecha de ocurrencia y estado de resolución).
- **Value Objects:** `IncidentId`, `Coordinates`.
- **Enumeraciones:** `IncidentStatus` (`REPORTED`, `RESOLVED`).
- **Lógica de Negocio:** Permite la detección automática de umbrales biométricos anómalos y el despacho inmediato de notificaciones de emergencia tanto a la agencia como a brigadas de socorro.

![Safety & Incident Management Class Diagram](../assets/images/Tourmate_Safety_Incident_Management_ClassDiagram.png)

---

#### 4.7.1.6. Bounded Context: Feedback and Tour Reviews

Administra las valoraciones cuantitativas y reseñas cualitativas generadas por los turistas al finalizar un tour, fortaleciendo la reputación del servicio:
- **Aggregate Root:** `Review` (encapsula el tour calificado, turista autor, puntuación global y fecha de emisión).
- **Entidades asociadas:** `Comment` (texto detallado con validación de contenido y moderación).
- **Value Objects:** `Rating` (valor numérico tipado de 0 a 5 estrellas con validación de rango).

![Feedback & Tour Reviews Class Diagram](../assets/images/Tourmate_FeedbackTourReview_ClassDiagram.png)

---

#### 4.7.1.7. Bounded Context: Subscriptions and Payment Management

Gestiona los planes comerciales de suscripción y el procesamiento de transacciones financieras para las agencias y usuarios de la plataforma TourMate:
- **Aggregate Roots:** `Subscription` (controla la vigencia del servicio, plan contratado y estado de renovación), `Plan` (define nombre del plan comercial, precio recurrente y características operativas incluidas como `Feature`), y `Payment` (procesa la orden de cobro, monto, pasarela de pago y estado de la transacción).
- **Value Objects:** `SubscriptionId`, `PlanId`, `PaymentId`, `Feature`, `Money`.
- **Enumeraciones:** `SubscriptionStatus` (`ACTIVE`, `CANCELLED`) y `PaymentStatus` (`REQUESTED`, `PROCESSED`, `REJECTED`).

![Subscriptions & Payment Class Diagram](../assets/images/subscription-classDiagram.png)

## 4.8. Database Design
### 4.8.1. Database Diagrams

El diseño de base de datos de Tourmate está estructurado en 6 bounded contexts con  tablas, siguiendo los principios de Domain-Driven Design para garantizar modularidad, escalabilidad y mantenibilidad. Cada contexto —Safety and Incident Management, Tour Monitoring, Identity and Access Management, Tour Management,  Feedback and Tour Reviews y Subscriptions and Payment Management— gestiona de forma autónoma una parte específica del sistema, pero todos están integrados mediante claves foráneas UUID que reflejan el flujo operativo del negocio: desde el registro del usuario y la configuración del tour, hasta la ejecución de la expedición, el monitoreo de seguridad en tiempo real y la creación de Reviews. Esta arquitectura desacoplada pero conectada logicamente garantiza trazabilidad completa del recorrido, monitoreo biométrico continuo, sincronización y una gestión eficiente de toda la operación de turismo de aventura.

#### 4.8.1.1. IAM Component Diagram
![Imagen de la base de datos](../assets/images/db_IAM.png)

#### 4.8.1.2. Tour Management Component Diagram
![Imagen de la base de datos](../assets/images/db_TourManagement.png)

#### 4.8.1.3. Tour Monitoring Component Diagram
![Imagen de la base de datos](../assets/images/db_TourMonitoring.png)

#### 4.8.1.4. Safety Incident Component Diagram
![Imagen de la base de datos](../assets/images/db_SafetyIncidents.png)

#### 4.8.1.5. Feedback and Review Component Diagram
![Imagen de la base de datos](../assets/images/db_feedbackTour.png)

#### 4.8.1.6. Subscriptions and Payment Management Component Diagram
![Imagen de la base de datos](../assets/images/db_Subscriptions.png)

<div style="page-break-before: always;"></div>

---

## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
Con el objetivo de garantizar un desarrollo fluido, estandarizado y consistente entre todos los miembros del equipo, se ha definido el siguiente entorno de desarrollo para el ecosistema TourMate:

| Actividad                              | Producto                 | Propósito / Uso                                                                 |
|---------------------------------------|--------------------------|----------------------------------------------------------------------------------|
| Project Management                    | Trello                   | Gestión del Product Backlog, planificación de Sprints y seguimiento de tareas.  |
| Requirements Management               | UXPressia                | Elaboración de artefactos de descubrimiento (User Personas, Empathy Maps, Journey Maps) para la definición de requisitos. |
| UX/UI Design                          | Figma                    | Diseño de la guía de estilo, prototipos de baja fidelidad (wireframes) y alta fidelidad (mockups). |
| User Flows & Wireflows                | LucidChart               | Elaboración de Wireflows y User Flows.                                          |
| Class Diagrams & Data Base Design     | PlantUML                 | Elaboración de diagramas de clases y diseño de base de datos.                   |
| Software Development (Backend)        | JetBrains Rider          | IDE para el desarrollo de Web Services bajo estilo RESTful utilizando ASP.NET Core y C#. |
| Software Development (Frontend)       | JetBrains WebStorm       | IDE para el desarrollo de la Web Application con Vue Framework, PrimeVue (HTML5, CSS3, JS). |
| Software Development (Landing Page)   | Visual Studio Code       | IDE para el desarrollo de la Landing Page con HTML5, CSS y JS.                  |
| Version Control                       | GitHub                   | Alojamiento de repositorios y gestión de versiones aplicando GitFlow y Conventional Commits. |
| Documentation                         | Markdown                 | Documentación del reporte del proyecto.                                         |

#### 5.1.2. Source Code Management

El código fuente del proyecto se gestionará utilizando **Git** como sistema de control de versiones y **GitHub** como plataforma de alojamiento, bajo una organización pública. Se adoptará un enfoque estructurado que favorezca la colaboración, la modularidad y el despliegue continuo mediante repositorios independientes para cada componente del sistema.

- **Report:** [https://github.com/axiom-daos/tourmate-report](https://github.com/axiom-daos/tourmate-report)
- **Landing Page:** [https://github.com/axiom-daos/tourmate-landing](https://github.com/axiom-daos/tourmate-landing)
- **Frontend Web Application:** [https://github.com/axiom-daos/tourmate-web-application](https://github.com/axiom-daos/tourmate-web-application)
- **RESTful Web Services:** [https://github.com/axiom-daos/tourmate-platform](https://github.com/axiom-daos/tourmate-platform)

#### Estrategia de Ramas (GitFlow)

Se implementará un flujo de trabajo basado en GitFlow con el objetivo de garantizar la estabilidad y trazabilidad del desarrollo:

- **main**: Rama principal que contiene únicamente código estable, probado y desplegado en producción. Cada versión liberada deberá estar debidamente etiquetada.

- **develop**: Rama de integración continua donde se consolidan los avances del desarrollo antes de su liberación a producción.

- **feature/[nombre]**: Ramas temporales creadas a partir de *develop* para el desarrollo de nuevas funcionalidades o User Stories  
  (ej. *feature/order-registration*). Una vez finalizadas, se integran nuevamente a *develop* mediante un Pull Request (PR).

- **hotfix/[nombre]**: Ramas destinadas a la corrección de errores críticos detectados en producción (*main*), que requieren una solución inmediata.

#### Convención de Commits (Conventional Commits)

Para mantener un historial claro, consistente y facilitar la generación automática de *changelogs*, todos los commits deberán seguir el estándar de **Conventional Commits**:

#### Tipos permitidos

- **feat**: Nueva funcionalidad  
  (ej. *feat(ordering): add automated order validation policy*)

- **fix**: Corrección de errores  
  (ej. *fix(auth): resolve token expiration on mobile devices*)

- **docs**: Cambios en documentación  
  (ej. *docs(interviews): update stakeholder interview records*)

- **style**: Cambios de formato que no afectan la lógica del código (espacios, indentación, etc.)

#### 5.1.3. Source Code Style Guide & Conventions

Para mantener la legibilidad y calidad del código, todo el equipo aplicará **nomenclatura estrictamente en inglés** para clases, variables, métodos y bases de datos. Además, se adoptan las siguientes guías de estilo oficiales:

- **HTML & CSS:** Se seguirán las directrices de la [HTML Style Guide and Coding Conventions](https://www.w3schools.com/html/html5_syntax.asp) de W3C y la [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html).
- **Frontend (Angular / TypeScript):** Se respetará la [Angular Coding Style Guide](https://angular.io/guide/styleguide). Las clases usarán `PascalCase`, variables/métodos `camelCase`, y archivos `kebab-case`. Se utilizará Prettier y ESLint para automatizar el formato.
- **Backend (Spring Boot / Java):** Se aplicará la [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html). La arquitectura se dividirá en capas estrictas (Controllers, Services, Repositories, Entities). Los endpoints RESTful usarán sustantivos en plural (ej. `GET /api/v1/parking-spots`).
- **Requerimientos:** Se emplearán las [Gherkin Conventions](https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/) para la redacción estructurada de los criterios de aceptación (Given/When/Then).


#### 5.1.4. Software Deployment Configuration
En esta sección se describe la configuración del despliegue de la solución TourMate, detallando los pasos necesarios para publicar los productos digitales a partir de sus repositorios de código fuente.

Para el presente proyecto, el despliegue se realiza utilizando GitHub como plataforma de alojamiento, aprovechando el servicio de **GitHub Pages** para la publicación de contenido estático.

#### Landing Page

El despliegue de la Landing Page y del reporte del proyecto se realiza mediante GitHub Pages, siguiendo los siguientes pasos:

1. Creación del repositorio en GitHub bajo la organización del equipo.
2. Configuración de la rama de despliegue (main o gh-pages).
3. Subida del código fuente mediante commits y push al repositorio remoto.
4. Activación de GitHub Pages desde la configuración del repositorio.
5. Selección de la rama y carpeta raíz como fuente de publicación.
6. Generación automática de la URL pública del sitio.

Una vez configurado, cada actualización enviada al repositorio se refleja automáticamente en la versión publicada del sitio.

#### Consideraciones

- El despliegue está orientado a contenido estático (HTML, CSS, JavaScript).
- No se requiere infraestructura adicional ni servidores externos.
- El acceso al sitio es público mediante una URL generada por GitHub Pages.

### 5.2.1. Sprint 1

#### *5.2.1.1. Sprint Planning 1*

Para el desarrollo del primer sprint nos centramos en el desarrollo de la landing page de nuestra aplicación. Para ello designamos tareas específicas para cada sección, de modo que podamos repartirnos estas tareas entre los integrantes del grupo por sección de la landing, agilizando su desarrollo. Dentro de la landing se presenta quienes somos, funcionalidades, planes, manera de contactarnos y sobre la organización.

| **Sprint #** | 1                                                                                                                                                                                                                                        |
| --- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                                                                          |
| **Date** | 2026-09-10                                                                                                                                                                                                                               |
| **Time** | 4:00 PM                                                                                                                                                                                                                                  |
| **Location** | Reunión virtual                                                                                                                                                                                                                          |
| **Prepared By** | Giancarlo Verastigue Martinez                                                                                                                                                                                                            |
| **Attendees** | Giancarlo Verastigue Martinez, Matias Carrillo Acho, Frank Anthony Huingo Tello, Manuel Alejandro Molina Vasquez, Tony Jhunior Quispe Palomino                                                                                                                                                                     |
| **Sprint n – 1 Review Summary** | N/A (Primer Sprint del proyecto. Se establecieron las bases de la arquitectura, infraestructura en la nube y repositorios).                                                                                                              |
| **Sprint n – 1 Retrospective Summary** | N/A (Primer Sprint. El equipo acordó usar GitFlow y Conventional Commits rigurosamente desde el primer día).                                                                                                                             |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                          |
| **Sprint 1 Goal** | Our focus is on delivering a fast, static Landing Page (HTML/CSS/JS) with language support to attract clients and validate our value proposition. This will be confirmed when the Landing Page is deployed and fully navigable by users. |
| **Sprint 1 Velocity** | 10 Story Points (Velocidad estimada para el primer ciclo del equipo).                                                                                                                                                                    |
| **Sum of Story Points** | 10                                                                                                                                                                                                                                       |

#### *5.2.1.2. Aspect Leaders and Collaborators*

A continuación se detalla la matriz de liderazgo y colaboración (LACX) para brindar claridad en la comunicación del equipo durante el desarrollo de las tareas de este Sprint.

| Team Member (Last Name, First Name) | GitHub Username | Landing Page UI/UX | Landing Page Structure | Basic Funcs | Special Funcs |
|-------------------------------------|-----------------| --- | --- | --- | --- |
| Verastigue Martinez, Giancarlo      | @CaLoVM         | C | L | C | C |
| Carrillo Acho, Matias               | @lonybreux      | C | C | C | L |
| Huingo Tello, Frank Anthony         | @Franz2308      | C | C | L | C |
| Molina Vasquez, Manuel Alejandro    | @AleDusty       | C | C | L | C |
| Quispe Palomino, Tony Jhunior     | @GonzJunior18p  | L | C | C | C |

#### *5.2.1.3. Sprint Backlog 1*


El objetivo principal de este Sprint es desarrollar el sitio web estático (Landing Page) de TourMate, encargado de comunicar la propuesta de valor de la plataforma a los dos segmentos objetivo: turistas y agencias. Durante este Sprint se implementarán las secciones de contenido principal, navegación, beneficios diferenciados por segmento, funcionalidades del producto, testimonios, información del equipo y el formulario de contacto, además de los flujos de acceso al registro y el manejo de estados de error/no disponibilidad definidos en las User Stories asociadas a EP06.

**Trello link:** [https://trello.com/b/gCKcMjVR/tourmate-sprint-1)

![Sprint Backlog 1](../assets/images/s1-sprint-backlog.png)
## Sprint 1

| User Story Id | User Story Title | Work-Item / Task Id | Work-Item / Task Title | Description                                                                                    | Estimation (Hours) | Assigned To | Status |
| --- | --- |---------------------| --- |------------------------------------------------------------------------------------------------| --- | --- |--------|
| US-LP01 | Conocer la propuesta de valor | TS-LP01.1           | Setup base del proyecto Landing | Inicializar el repositorio con la estructura base HTML5/CSS para la Landing Page.              | 2 | @lonybreux | Done   |
| US-LP01 | Conocer la propuesta de valor | TS-LP01.2           | Implementar Hero Section | Desarrollar la sección principal con el propósito y beneficio central de TourMate.             | 4 | @lonybreux | Done  |
| US-LP02 | Navegar entre secciones | TS-LP02.1           | Implementar Navbar | Crear el componente de navegación con enlaces a cada sección de la Landing.                    | 2 | @Franz2308 | Done  |
| US-LP03 | Conocer beneficios para turistas | TS-LP03.1           | Diseñar sección de beneficios – Turista | Maquetar la sección con los beneficios orientados al segmento turista.                         | 3 | @GonzJunior18p | Done  |
| US-LP03 | Conocer beneficios para turistas | TS-LP03.2           | Contenido de seguridad y navegación offline | Redactar e integrar el contenido sobre funcionalidades de seguridad y modo offline.            | 2 | @lonybreux | Done  |
| US-LP03 | Conocer beneficios para turistas | TS-LP03.3           | CTA de registro – Turista | Implementar botón que redirige al proceso de registro del segmento turista.                    | 1 | @CaLoVM | Done  |
| US-LP04 | Conocer beneficios para agencias | TS-LP04.1           | Diseñar sección de beneficios – Agencia | Maquetar la sección con los beneficios orientados al segmento agencia.                         | 3 | @Franz2308 | Done  |
| US-LP04 | Conocer beneficios para agencias | TS-LP04.2           | Contenido de monitoreo, alertas y gestión | Redactar e integrar el contenido sobre funcionalidades de monitoreo y gestión de expediciones. | 2 | @Franz2308 | Done  |
| US-LP04 | Conocer beneficios para agencias | TS-LP04.3           | CTA de registro – Agencia | Implementar botón que redirige al proceso de registro del segmento agencia.                    | 1 | @AleDusty | Done  |
| US-LP05 | Conocer las funcionalidades principales | TS-LP05.1           | Sección de funcionalidades principales | Desarrollar grid/cards con las funcionalidades clave de TourMate.                              | 3 | @AleDusty | Done  |
| US-LP05 | Conocer las funcionalidades principales | TS-LP05.2           | Contenido de operatividad offline | Integrar contenido claro sobre la compatibilidad y uso sin conexión.                           | 2 | @GonzJunior18p | Done  |
| US-LP08 | Contactar al equipo de Tourmate | TS-LP08.1           | Formulario de contacto | Maquetar el formulario de contacto con los campos requeridos.                                  | 3 | @Franz2308 | Done  |
| US-LP08 | Contactar al equipo de Tourmate | TS-LP08.2           | Endpoint de envío de mensaje | Implementar el servicio que registra el mensaje y retorna confirmación de recepción.           | 4 | @GonzJunior18p | Done  |
| US-LP09 | Conocer al equipo de la startup | TS-LP09.1           | Sección "Sobre el equipo" | Maquetar la sección con la información de los miembros de Axiom.                               | 2 | @CaLoVM | Done  |

#### *5.2.1.4. Development Evidence for Sprint Review*

En la siguiente tabla se resumen los principales commits realizados en los repositorios de Axiom correspondientes al alcance del primer Sprint, aplicando Conventional Commits.


| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| axiom/tourmate-landing | feature/plans-section | da1f6c1 | style: add smooth scrolling and enhance plans section layout and resp... | Añade desplazamiento suave (smooth scrolling) y mejora el diseño y la adaptabilidad de la sección de planes. | 2026-09-17 |
| axiom/tourmate-landing | feature/plans-section | d820385 | feat: add plans section with pricing options for tourists and agencies | Implementa la sección de planes con las opciones de precios para turistas y agencias. | 2026-09-17 |
| axiom/tourmate-landing | feature/team-development-section | b9d8364 | feat: add social media links for team members in the team section | Añade los enlaces a las redes sociales de los miembros en la sección del equipo. | 2026-09-16 |
| axiom/tourmate-landing | feature/team-development-section | 0cb46b6 | style: enhance team section layout and responsiveness | Mejora el diseño y la adaptabilidad de la sección del equipo para dispositivos móviles. | 2026-09-16 |
| axiom/tourmate-landing | feature/navigation | 9208502 | style: enhance navigation links with hover effects and transitions | Mejora los enlaces de navegación añadiendo efectos hover y transiciones visuales. | 2026-09-16 |
| axiom/tourmate-landing | refactor | e4f16c0 | refactor: rename sections for clarity and consistency in index.html | Refactoriza y renombra las secciones en el archivo index.html para mantener consistencia y claridad. | 2026-09-16 |
| axiom/tourmate-landing | main | 8b89273 | fix(i18n): move team-dev block out of nested plans object in en.json | Corrige la ubicación del bloque team-dev sacándolo del objeto anidado en el archivo de traducciones al inglés. | 2026-09-16 |
| axiom/tourmate-landing | main | c343560 | chore: delete docs file | Elimina el archivo de documentación innecesario del repositorio. | 2026-09-16 |
| axiom/tourmate-landing | feature/team-development-section | 83b3f1d | feat: add Matias Carrillo photo in team development section | Añade la fotografía de Matias Carrillo a la sección del equipo de desarrollo. | 2026-09-16 |
| axiom/tourmate-landing | feature/inicio-section | 16c1f03 | fix: resolve i18n error in hero section | Resuelve un error de internacionalización (i18n) en la sección hero. | 2026-09-16 |
| axiom/tourmate-landing | feature/team-development-section | c764aa8 | fix: delete team section styles and put it on global styles css | Elimina los estilos locales de la sección de equipo y los unifica en los estilos globales. | 2026-09-16 |
| axiom/tourmate-landing | develop | 898542c | Merge branch 'feature/team-development-section' into develop | Integra los cambios de la rama de la sección de equipo de desarrollo en la rama develop. | 2026-09-16 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | aaa60ed | fix: delete test button in viajeros-turistas section | Elimina un botón de prueba que había quedado en la sección de viajeros/turistas. | 2026-09-16 |
| axiom/tourmate-landing | develop | 99e6cd7 | Merge branch 'feature/inicio-section' into develop | Integra los cambios de la rama de la sección de inicio en la rama develop. | 2026-09-16 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | 2d01fd1 | fix: add agencias-viajeros section styles to global styles | Mueve y añade los estilos de la sección de agencias y viajeros a los estilos globales. | 2026-09-16 |
| axiom/tourmate-landing | develop | 651f25e | Merge branch 'feature/agencias-viajeros-section' into develop | Integra los cambios de la rama de la sección de agencias y viajeros en la rama develop. | 2026-09-16 |
| axiom/tourmate-landing | feature/inicio-section | 9da572d | Merge branch 'develop' into feature/inicio-section | Actualiza la rama de la sección de inicio con los últimos cambios de develop. | 2026-09-16 |
| axiom/tourmate-landing | feature/vision-section | 79a74f9 | feat: add i18n to vision section | Implementa el soporte de múltiples idiomas (i18n) para la sección de visión. | 2026-09-16 |
| axiom/tourmate-landing | feature/team-development-section | 7a20af0 | feat: add team development section with responsive design | Implementa la sección del equipo de desarrollo asegurando que su diseño sea responsivo. | 2026-09-15 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | f5d0426 | feat(landing): add agencias and viajeros sections with language support and structure | Añade la estructura y soporte de idiomas para las secciones de agencias y viajeros en la landing. | 2026-09-15 |
| axiom/tourmate-landing | main | 0ede294 | feat(i18n): implement core i18n engine with language toggle and DOM translation support | Implementa el motor central de internacionalización, incluyendo el cambio de idioma y soporte de traducción en el DOM. | 2026-09-15 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | b12acba | feat(i18n): add Spanish translations for agencias and viajeros sections | Añade las traducciones al español para los textos de las secciones de agencias y viajeros. | 2026-09-15 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | 314f9f5 | feat(i18n): add English translations for agencias and viajeros sections | Añade las traducciones al inglés para los textos de las secciones de agencias y viajeros. | 2026-09-15 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | 54d6f63 | feat(styles): add agencia-viajeros section styles | Implementa los estilos visuales principales para la sección de agencias y viajeros. | 2026-09-15 |
| axiom/tourmate-landing | feature/agencias-viajeros-section | d727252 | feat(assets): add viajeros-mockup.png | Agrega la imagen de mockup correspondiente a la sección de viajeros a los recursos del proyecto. | 2026-09-15 |
| axiom/tourmate-landing | feature/inicio-section | c983833 | feat(landing): add hero-expedition.png | Agrega la imagen hero-expedition a los recursos del proyecto para la sección de inicio. | 2026-09-15 |
| axiom/tourmate-landing | main | eea0313 | add | Añade archivos o cambios generales al repositorio. | 2026-09-15 |
| axiom/tourmate-landing | main | 1da7469 | added the logo | Añade el archivo del logo oficial al proyecto. | 2026-09-15 |
| axiom/tourmate-landing | feature/inicio-section | 672a92f | feat: add hero section and navigation to feature/inicio-section | Implementa la sección hero y la barra de navegación dentro de la rama de inicio. | 2026-09-15 |
| axiom/tourmate-landing | feature/contact-footer | ab8aed9 | feat: add contact and footer sections with responsive design | Implementa las secciones de contacto y el footer garantizando un diseño adaptable a diferentes dispositivos. | 2026-09-14 |
| axiom/tourmate-landing | feature/vision-section | a300ccd | feat: add vision section styles | Implementa y aplica los estilos visuales para la sección de visión. | 2026-09-14 |
| axiom/tourmate-landing | feature/vision-section | 2e2e0c2 | Merge branch 'develop' into feature/vision-section | Actualiza la rama de la sección de visión con los cambios más recientes de la rama develop. | 2026-09-14 |
| axiom/tourmate-landing | feature/vision-section | 65c74bd | feat: add vision section structure | Construye el marcado HTML y la estructura principal para la sección de visión. | 2026-09-14 |
| axiom/tourmate-landing | main | 01f9539 | chore: add project directories | Crea y organiza los directorios y carpetas base del proyecto. | 2026-09-14 |
| axiom/tourmate-landing | main | 1ad6c2b | add initial structure | Implementa la estructura base y los archivos iniciales del código. | 2026-09-14 |
| axiom/tourmate-landing | main | 1607422 | Initial commit | Realiza el commit inicial configurando la base del repositorio. | 2026-09-01 |

#### *5.2.1.5. Execution Evidence for Sprint Review*

Durante este Sprint, el equipo logró implementar la versión inicial del Landing Page funcional, rápido y estático, incluido el sistema de idiomas.

*Figura  (Landing Page)*
![Landing Page](../assets/images/landing-page-full.png)

**Landing Page Demonstration Video:** [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDPy8lARpAQRp4FrzFWEwqxAe1KOWcMdKkZwhyLW45DKmo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jmEFH0](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDPy8lARpAQRp4FrzFWEwqxAe1KOWcMdKkZwhyLW45DKmo?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jmEFH0)

#### *5.2.1.6. Services Documentation Evidence for Sprint Review*

Durante el Sprint 1 el esfuerzo de desarrollo se enfocó exclusivamente en la creación del sitio web estático promocional (Landing Page), por lo que aún no se han implementado APIs RESTful ni Endpoints backend que requieran ser documentados a través de Swagger/OpenAPI. Esta documentación se estructurará a partir del Sprint 2.

#### *5.2.1.7. Software Deployment Evidence for Sprint Review*

#### Despliegue de la Landing Page
El despliegue de la Landing Page de TourMate se realizó utilizando GitHub Pages, aprovechando sus capacidades para publicar sitios web estáticos directamente desde un repositorio. Este enfoque permitió una implementación sencilla, automatizada y accesible sin necesidad de servicios externos adicionales.

#### Infraestructura de Despliegue

- **Repositorio de código fuente:** GitHub
- **Plataforma de despliegue:** GitHub Pages
- **Tipo de aplicación:** Landing Page estática (HTML, CSS, JavaScript)
- **Acceso:** URL pública generada por GitHub

#### Proceso de Despliegue

1. **Creación del repositorio**
    - Se creó un repositorio en GitHub que contiene todos los archivos de la Landing Page (HTML, CSS, imágenes y scripts).
    - Se organizó el proyecto asegurando que el archivo principal sea `index.html`, requerido por GitHub Pages.

   ![Deployment](../assets/images/Deployment-Create-Repository.png)

2. **Subida del código**
    - Se realizó el `push` del proyecto a la rama principal (`main`) del repositorio.
    - Se verificó que todos los recursos estén correctamente enlazados (rutas relativas).

   ![Deployment](../assets/images/Deployment-Push.png)

3. **Configuración de GitHub Pages**
    - En la sección *Settings* del repositorio, se habilitó **GitHub Pages**.
    - Se seleccionó la rama `main` como fuente de despliegue.
    - Se definió la carpeta raíz (`/root`) como directorio de publicación.

   ![Deployment](../assets/images/Deployment-GHPages.png)

4. **Publicación automática**
    - GitHub Pages procesó automáticamente el contenido del repositorio.
    - En pocos minutos, generó una URL pública donde la Landing Page quedó disponible.

   ![Deployment](../assets/images/Deployment-URL.png)

5. **Actualizaciones**
    - Cada vez que se realiza un nuevo `push` a la rama `main`, GitHub Pages actualiza automáticamente la página.
    - Esto permite mantener la Landing Page sincronizada con los cambios del repositorio sin intervención manual adicional.

#### Resultado
La Landing Page de TourMate fue desplegada exitosamente mediante GitHub Pages, permitiendo su acceso público a través de una URL estable. Esto facilita la presentación del producto a usuarios potenciales y valida la propuesta de valor del sistema de manera rápida y efectiva.

URL: https://axiom-daos.github.io/tourmate-landing/

#### *5.2.1.8. Team Collaboration Insights during Sprint*

Todos los miembros del equipo han participado activamente en la implementación de los productos del Sprint 1, lo cual se evidencia mediante los reportes de actividad y contribución del repositorio de GitHub de la organización Axiom.

**Insights**
![Team Insights Sprint 1](../assets/images/insights-landing.png)

**Contributors**
![Team Insights Sprint 1](../assets/images/contribuciones-landing.png)

**Network graph**
![Team Insights Sprint 1](../assets/images/gitflow-sprint1.png)



### 5.2.2. Sprint 2

#### *5.2.2.1. Sprint Planning 2*
Para el desarrollo del segundo sprint, nos centraremos en la implementación del frontend de nuestra aplicación web. Hemos diseñado tareas específicas basadas en las historias de usuario orientadas a la gestión de tours, el monitoreo en tiempo real, el soporte de rutas offline y la configuración de perfiles. Al subdividir cada historia de usuario en múltiples tareas técnicas, podemos distribuir la carga de trabajo de manera eficiente entre los desarrolladores del equipo, asegurando la construcción de una interfaz interactiva, escalable y lista para integrarse con nuestra API.

| **Sprint #** | 2 |
| --- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** | |
| **Date** | 2026-09-28 |
| **Time** | 4:00 PM |
| **Location** | Reunión virtual |
| **Prepared By** | Giancarlo Verastigue Martinez |
| **Attendees** | Giancarlo Verastigue Martinez, Matias Carrillo Acho, Frank Anthony Huingo Tello, Manuel Alejandro Molina Vasquez, Tony Jhunior Quispe Palomino |
| **Sprint n – 1 Review Summary** | La Landing Page fue completada y desplegada exitosamente. Se lograron los objetivos de comunicar la propuesta de valor y habilitar las rutas de redirección hacia el registro para turistas y agencias. |
| **Sprint n – 1 Retrospective Summary** | El equipo mantuvo una buena comunicación y uso de GitFlow. Se acordó mejorar la granularidad de las estimaciones dividiendo obligatoriamente cada Historia de Usuario en al menos dos tareas (Tasks) para un seguimiento más preciso. |
| **Sprint Goal & User Stories** | |
| **Sprint 2 Goal** | Our focus is on delivering the core frontend application for TourMate, including tour management, interactive live maps, offline capabilities, and user profiles. This will be confirmed when all UI components are built and functional mockups are ready. |
| **Sprint 2 Velocity** | 133 Story Points (Velocidad estimada sumando la carga completa de las vistas e integraciones Frontend proyectadas para este ciclo). |
| **Sum of Story Points** | 133 |

#### *5.2.2.2. Aspect Leaders and Collaborators*

A continuación se detalla la matriz de liderazgo y colaboración (LACX) para brindar claridad en la comunicación del equipo durante el desarrollo de las tareas de este Sprint.

Para este segundo sprint, los aspectos se han definido en base a los módulos principales del Frontend: Gestión de Tours (Tour Management), Mapas y Monitoreo (Maps & Tracking), Capacidades Offline (Offline & Sync), y Perfiles y Alertas (Profile & Alerts).

| Team Member (Last Name, First Name) | GitHub Username | Tour Management Views | Maps & Tracking UI | Offline & Sync Modules | Profile & Alerts Settings |
|-------------------------------------|-----------------| --- | --- | --- | --- |
| Verastigue Martinez, Giancarlo      | @CaLoVM         | C | C | C | L |
| Carrillo Acho, Matias               | @lonybreux      | C | L | C | C |
| Huingo Tello, Frank Anthony         | @Franz2308      | L | C | C | C |
| Molina Vasquez, Manuel Alejandro    | @AleDusty       | L | C | C | C |
| Quispe Palomino, Tony Jhunior       | @GonzJunior18p  | C | C | L | C |

#### *5.2.2.3. Sprint Backlog 2*

El objetivo principal de este segundo Sprint es desarrollar e implementar la primera versión completamente funcional de la aplicación web (*Frontend Web Application*) de TourMate utilizando Angular y Angular Material, orientada a los dos segmentos principales de usuarios: turistas y agencias operadoras. A lo largo de este ciclo, el equipo se enfoca en materializar las interfaces de usuario interactivas para la gestión integral de paquetes turísticos (creación, edición, visualización detallada y eliminación estructurada de tours correspondientes a la épica EP02), el catálogo dinámico con filtrado de expediciones, la visualización de rutas geográficas mediante componentes de mapas y el diseño base de los tableros de control (*dashboards*) para el turista y la agencia. Todas las User Stories asignadas a este Sprint han sido descompuestas en tareas de ingeniería frontend (*Engineering Tasks* identificadas como `TS-Fxx.x`), abarcando maquetación de vistas, lógica de componentes reactivos, validación en tiempo real de formularios y consumo de servicios simulados (mocking de API).

**Trello link:** [https://trello.com/b/5MJg6UUc](https://trello.com/b/5MJg6UUc)

![Sprint Backlog 2](../assets/images/s2-sprint-backlog.png)


| User Story Id | User Story Title | Work-Item / Task Id | Work-Item / Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| US09 | Crear tour | TS-F09.1 | Maquetar formulario de creación | Desarrollar la interfaz (UI) del formulario con campos estructurados para crear un tour. | 4 | @lonybreux | To Do |
| US09 | Crear tour | TS-F09.2 | Integración y validaciones (Crear Tour) | Implementar validaciones en el cliente y enviar el payload al endpoint correspondiente. | 3 | @CaLoVM | To Do |
| US10 | Editar tour | TS-F10.1 | Interfaz de edición de tour | Reutilizar el componente de formulario y adaptarlo para pre-poblar los datos del tour existente. | 2 | @AleDusty | To Do |
| US10 | Editar tour | TS-F10.2 | Lógica de actualización (Editar Tour) | Capturar los cambios del formulario y enviarlos a la API para confirmar la actualización. | 2 | @Franz2308 | To Do |
| US11 | Eliminar tour | TS-F11.1 | Modal de confirmación de eliminación | Diseñar e implementar el cuadro de diálogo para evitar eliminaciones accidentales. | 1 | @GonzJunior18p | To Do |
| US11 | Eliminar tour | TS-F11.2 | Integración de eliminación | Conectar la acción del modal con el endpoint DELETE y actualizar el listado de la UI localmente. | 2 | @lonybreux | To Do |
| US12 | Duplicar tour | TS-F12.1 | Acción de duplicar en listado | Agregar la opción visual de duplicado en el menú de acciones de la tarjeta/tabla de tour. | 1 | @CaLoVM | To Do |
| US12 | Duplicar tour | TS-F12.2 | Lógica de duplicación | Consumir el endpoint de clonación y redirigir al usuario al nuevo tour en estado borrador. | 3 | @AleDusty | To Do |
| US13 | Asignar turistas a un tour | TS-F13.1 | Buscador y selector de turistas | Construir el componente UI que permite buscar turistas registrados y seleccionarlos. | 3 | @Franz2308 | To Do |
| US13 | Asignar turistas a un tour | TS-F13.2 | Envío de asignación a API | Vincular la lista seleccionada con la API de gestión para actualizar los participantes del tour. | 2 | @GonzJunior18p | To Do |
| US14 | Desasignar turista de un tour | TS-F14.1 | Botón de remoción en tabla de participantes | Añadir la opción gráfica para quitar a un turista de la lista del tour activo. | 1 | @lonybreux | To Do |
| US14 | Desasignar turista de un tour | TS-F14.2 | Lógica de desasignación | Enviar la solicitud de remoción a la API y refrescar la tabla de la interfaz. | 2 | @CaLoVM | To Do |
| US15 | Confirmar asistencia | TS-F15.1 | Vista de tours asignados al turista | Diseñar la pantalla donde el turista visualiza sus invitaciones pendientes con botones de acción. | 3 | @AleDusty | To Do |
| US15 | Confirmar asistencia | TS-F15.2 | Integración de confirmación/cancelación | Conectar las acciones de aceptar/rechazar con los estados en el backend. | 2 | @Franz2308 | To Do |
| US16 | Buscar y filtrar tours | TS-F16.1 | Barra de búsqueda y panel de filtros | Desarrollar los inputs reactivos (texto, selects, checkboxes) para la búsqueda de tours. | 4 | @GonzJunior18p | To Do |
| US16 | Buscar y filtrar tours | TS-F16.2 | Lógica de filtrado en cliente | Manejar el estado del filtro e integrar la llamada a la API con query params. | 4 | @lonybreux | To Do |
| US17 | Consultar detalle del tour | TS-F17.1 | Maquetación de página de detalles | Diseñar la estructura visual completa (ruta, checkpoints, descripción) del tour. | 3 | @CaLoVM | To Do |
| US17 | Consultar detalle del tour | TS-F17.2 | Carga dinámica de información | Consumir los datos del tour específico desde la API y renderizarlos en la vista de detalle. | 2 | @AleDusty | To Do |
| US18 | Consultar tours de la agencia | TS-F18.1 | Grid/Tabla de dashboard de agencia | Crear la vista estructurada para listar todos los tours propios con soporte de paginación UI. | 3 | @Franz2308 | To Do |
| US18 | Consultar tours de la agencia | TS-F18.2 | Integración del catálogo | Conectar el grid con el listado de la API y manejar estados de carga y error. | 3 | @GonzJunior18p | To Do |
| US19 | Iniciar expedición | TS-F19.1 | Vista previa a la expedición | Implementar la pantalla con los detalles y el botón principal "Iniciar Expedición". | 2 | @lonybreux | To Do |
| US19 | Iniciar expedición | TS-F19.2 | Controlador de inicio | Consumir el endpoint de inicio y redirigir automáticamente a la interfaz del mapa en vivo. | 2 | @CaLoVM | To Do |
| US20 | Visualizar ruta del tour | TS-F20.1 | Integración de motor de mapas | Añadir librería de mapas (ej. Leaflet/Mapbox) y configurar vista base en la interfaz. | 4 | @AleDusty | To Do |
| US20 | Visualizar ruta del tour | TS-F20.2 | Renderizado de ruta (Polylines) | Dibujar los trazados del tour sobre el mapa utilizando las coordenadas obtenidas del backend. | 3 | @Franz2308 | To Do |
| US21 | Descargar ruta offline | TS-F21.1 | Gestor de caché local | Configurar IndexedDB o Cache API para almacenar la información de rutas y mapas base. | 5 | @GonzJunior18p | To Do |
| US21 | Descargar ruta offline | TS-F21.2 | Interfaz de gestión de descargas | Crear un panel donde el turista pueda descargar, ver y borrar sus rutas offline. | 4 | @lonybreux | To Do |
| US22 | Visualizar checkpoints del recorrido | TS-F22.1 | Marcadores en mapa interactivo | Desarrollar componentes visuales para colocar los checkpoints sobre la interfaz de mapa. | 3 | @CaLoVM | To Do |
| US22 | Visualizar checkpoints del recorrido | TS-F22.2 | Estilizado dinámico de estado | Cambiar el color/icono del checkpoint en tiempo real según pase de pendiente a completado. | 2 | @AleDusty | To Do |
| US23 | Visualizar progreso del recorrido | TS-F23.1 | Componente de barra de progreso | Diseñar un indicador circular o lineal (progress bar) fijo en la interfaz de expedición. | 2 | @Franz2308 | To Do |
| US23 | Visualizar progreso del recorrido | TS-F23.2 | Cálculo reactivo de avance | Actualizar dinámicamente la barra de progreso a medida que el estado global de checkpoints avanza. | 2 | @GonzJunior18p | To Do |
| US24 | Registrar checkpoint manual | TS-F24.1 | Botón de check-in de guía | Añadir la acción de validación manual accesible desde la tarjeta de detalle de cada checkpoint. | 2 | @lonybreux | To Do |
| US24 | Registrar checkpoint manual | TS-F24.2 | Integración del registro manual | Ejecutar llamada a API y actualizar el estado visual para todo el grupo localmente. | 2 | @CaLoVM | To Do |
| US25 | Registrar experiencia del recorrido | TS-F25.1 | Formulario de notas flotante | Crear un modal de acceso rápido que permita ingresar texto/notas durante la expedición activa. | 2 | @AleDusty | To Do |
| US25 | Registrar experiencia del recorrido | TS-F25.2 | Envío e historial de experiencias | Conectar el formulario al backend y crear una lista UI para que el usuario visualice sus notas. | 2 | @Franz2308 | To Do |
| US26 | Consultar clima del recorrido | TS-F26.1 | Widget visual de clima | Maquetar el componente que mostrará iconos climáticos, temperaturas y advertencias. | 3 | @GonzJunior18p | To Do |
| US26 | Consultar clima del recorrido | TS-F26.2 | Integración de servicio climático | Consumir la API de clima y adaptar los datos para renderizarlos en el widget. | 3 | @lonybreux | To Do |
| US27 | Sincronización asincrónica de datos offline | TS-F27.1 | Listener de estado de red | Implementar lógica para detectar eventos 'online'/'offline' y mostrar alertas al usuario en UI. | 3 | @CaLoVM | To Do |
| US27 | Sincronización asincrónica de datos offline | TS-F27.2 | Cola de peticiones en background | Implementar sistema para encolar acciones localmente y procesarlas al recuperar la conexión. | 6 | @AleDusty | To Do |
| US28 | Finalizar expedición | TS-F28.1 | Componente de finalización | Diseñar botón de "Cerrar Expedición" con modal de doble confirmación para el guía. | 2 | @Franz2308 | To Do |
| US28 | Finalizar expedición | TS-F28.2 | Cierre y redirección | Llamar al endpoint de finalización y transicionar la vista a la pantalla de resumen del tour. | 2 | @GonzJunior18p | To Do |
| US29 | Monitorear ubicación de turistas | TS-F29.1 | Captura de geolocalización | Utilizar Geolocation API en el cliente para emitir coordenadas constantemente a la app. | 4 | @lonybreux | To Do |
| US29 | Monitorear ubicación de turistas | TS-F29.2 | Vista de rastreo en agencia | Mostrar avatares o marcadores de los turistas sobre el mapa del panel de administración en vivo. | 5 | @CaLoVM | To Do |
| US30 | Consultar estado general del grupo | TS-F30.1 | Dashboard de métricas del grupo | Crear un grid con tarjetas de estado simplificadas por cada turista asignado a la expedición. | 4 | @AleDusty | To Do |
| US30 | Consultar estado general del grupo | TS-F30.2 | Lógica de refresco (Polling/Sockets) | Implementar actualizaciones periódicas en el cliente para refrescar los datos del panel en vivo. | 4 | @Franz2308 | To Do |
| US31 | Recibir alertas por anomalías | TS-F31.1 | Componente visual de alerta crítica | Diseñar notificaciones intrusivas (banners rojos/modales) para advertir riesgos de seguridad. | 2 | @GonzJunior18p | To Do |
| US31 | Recibir alertas por anomalías | TS-F31.2 | Procesamiento de eventos anómalos | Escuchar los eventos de alerta generados por la telemetría y disparar el componente de alerta UI. | 4 | @lonybreux | To Do |
| US32 | Consultar estado de salud básico | TS-F32.1 | Tarjetas de biométricos en UI | Maquetar indicadores de frecuencia cardíaca/oxígeno dentro de la lista de turistas del guía. | 2 | @CaLoVM | To Do |
| US32 | Consultar estado de salud básico | TS-F32.2 | Binding de datos de salud | Enlazar el flujo de datos para actualizar los iconos y valores de salud dinámicamente. | 2 | @AleDusty | To Do |
| US33 | Reportar incidente | TS-F33.1 | UI de botón de pánico / SOS | Implementar un formulario de acceso súper rápido desde la vista de turista para emergencias. | 2 | @Franz2308 | To Do |
| US33 | Reportar incidente | TS-F33.2 | Envío de incidente y cache offline | Enviar el payload a la API, manejando fallos de red con almacenamiento temporal seguro. | 3 | @GonzJunior18p | To Do |
| US34 | Reportar incidente desde el rol guía | TS-F34.1 | Panel de gestión de incidentes | Construir la tabla visual para que el guía visualice, edite y cierre reportes en el terreno. | 2 | @lonybreux | To Do |
| US34 | Reportar incidente desde el rol guía | TS-F34.2 | Integración del workflow del incidente | Conectar las acciones (abrir, actualizar notas, marcar como resuelto) a la API REST. | 2 | @CaLoVM | To Do |
| US35 | Recibir datos biométricos del wearable | TS-F35.1 | Integración con Web Bluetooth API | Implementar la clase/servicio en el frontend capaz de descubrir y parear el wearable. | 5 | @AleDusty | To Do |
| US35 | Recibir datos biométricos del wearable | TS-F35.2 | Transmisión de telemetría | Capturar el flujo de datos (stream) del dispositivo, formatear JSON y enviarlo al backend. | 5 | @Franz2308 | To Do |
| US36 | Consultar estado del wearable | TS-F36.1 | Icono de batería y conectividad | Maquetar indicadores en la barra superior (navbar/status bar) para el hardware emparejado. | 2 | @GonzJunior18p | To Do |
| US36 | Consultar estado del wearable | TS-F36.2 | Lógica de refresco de hardware | Interpretar la data básica del reloj/pulsera para pintar dinámicamente su porcentaje y status. | 2 | @lonybreux | To Do |
| US37 | Exportar reportes de expedición | TS-F37.1 | Controles de exportación | Colocar menú con opciones (Descargar PDF, Exportar CSV) en expediciones finalizadas. | 2 | @CaLoVM | To Do |
| US37 | Exportar reportes de expedición | TS-F37.2 | Manejo de descarga de archivos Blob | Consumir el endpoint de exportación, convertir la respuesta y forzar la descarga en el navegador. | 3 | @AleDusty | To Do |
| US38 | Gestionar perfil personal | TS-F38.1 | Maquetación del formulario de perfil | Diseñar la página principal de configuración personal con validación de inputs gráficos. | 2 | @Franz2308 | To Do |
| US38 | Gestionar perfil personal | TS-F38.2 | Integración de actualización | Recuperar datos para precargar y enviar el payload del formulario a la API del usuario. | 2 | @GonzJunior18p | To Do |
| US39 | Actualizar foto de perfil | TS-F39.1 | Componente uploader con previsualización | Desarrollar un drag & drop/file input que renderice localmente la foto seleccionada. | 2 | @lonybreux | To Do |
| US39 | Actualizar foto de perfil | TS-F39.2 | Lógica de subida multipart | Manejar y procesar el envío del archivo como FormData hacia los servidores. | 1 | @CaLoVM | To Do |
| US40 | Configurar preferencias de notificaciones | TS-F40.1 | Vista de 'Switches' (Toggles) | Diseñar los selectores booleanos (on/off) para las distintas categorías de alertas de la cuenta. | 2 | @AleDusty | To Do |
| US40 | Configurar preferencias de notificaciones | TS-F40.2 | Sincronización de preferencias | Conectar los cambios de UI inmediatamente con el backend del usuario para guardado automático. | 2 | @Franz2308 | To Do |
| US41 | Recibir notificaciones de seguridad | TS-F41.1 | Layout de notificaciones críticas | Crear plantillas diferenciadas (colores llamativos, iconos de alerta) en el gestor de notificaciones UI. | 3 | @GonzJunior18p | To Do |
| US41 | Recibir notificaciones de seguridad | TS-F41.2 | Interceptor de sockets/alertas | Suscribir el cliente a los eventos críticos para desplegar el modal sin importar en qué vista esté. | 3 | @lonybreux | To Do |
| US42 | Recibir notificaciones de tour | TS-F42.1 | Dropdown de campana (Notificaciones) | Añadir la "campanita" y su respectiva lista desplegable rápida en la navegación del usuario. | 2 | @CaLoVM | To Do |
| US42 | Recibir notificaciones de tour | TS-F42.2 | Acciones 'Marcar leída' / Polling | Implementar la funcionalidad para descontar el contador rojo y leer desde la API. | 2 | @AleDusty | To Do |
| US43 | Consultar historial de notificaciones | TS-F43.1 | Página dedicada al historial | Maquetar una sección de lista extendida con filtros y ordenación por fecha. | 2 | @Franz2308 | To Do |
| US43 | Consultar historial de notificaciones | TS-F43.2 | Integración de listado completo | Consumir la API de notificaciones implementando infinite scroll o paginación estándar. | 2 | @GonzJunior18p | To Do |

#### *5.2.2.4. Development Evidence for Sprint Review*

En la siguiente tabla evidencia los commits realizados en los repositorios de Axiom correspondientes al alcance del Sprint 2, aplicando Conventional Commits.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| axiom/tourmate-frontend | develop | a37c3c3[cite: 9] | Merge branch 'feature/fix' into develop # Please enter a commit message[cite: 9] | Integra la rama de correcciones hacia la rama de desarrollo (develop). | 2026-10-06[cite: 9] |
| axiom/tourmate-frontend | feature/api-endpoints | 560d09c[cite: 9] | feat(api-endpoints): update API base URLs for active tours, agencies, checkpoints, incidents, participants, payments, plans, subscriptions, tour guides, tour schedules, and users[cite: 9] | Actualiza las URLs base de la API para todos los módulos de gestión principales. | 2026-10-06[cite: 9] |
| axiom/tourmate-frontend | main | 7be53fc[cite: 9] | Merge pull request #2 from axiom-daos/feedback-and-tour-reviews2[cite: 9] | Integra el pull request #2 asociado al módulo de reseñas y feedback. | 2026-10-06[cite: 9] |
| axiom/tourmate-frontend | fix/reviews | 82d824f[cite: 9] | fix(reviews): fix store delete and create id synchronization issues[cite: 9] | Corrige problemas de sincronización de IDs al crear y eliminar elementos en el store de reseñas. | 2026-10-06[cite: 9] |
| axiom/tourmate-frontend | feature/accessibility | cf3a3f3[cite: 9] | feat(accessibility): improve accessibility features across various components[cite: 9] | Mejora las características de accesibilidad en múltiples componentes de la aplicación. | 2026-10-06[cite: 9] |
| axiom/tourmate-frontend | feature/review-list | 87aa8ee[cite: 9] | feat(review-list): enhance review list with improved UI, translations, and dynamic user/tour information[cite: 9] | Mejora la lista de reseñas agregando una interfaz optimizada, traducciones e información dinámica. | 2026-10-06[cite: 9] |
| axiom/tourmate-frontend | feature/active-tour-list | 7eef9ac[cite: 9] | feat(active-tour-list): enhance active tour list with responsive card layout and sorting functionality[cite: 9] | Mejora la lista de tours activos implementando diseño responsivo de tarjetas y ordenamiento. | 2026-10-05[cite: 9] |
| axiom/tourmate-frontend | feature/active-tour | 88f10a2[cite: 9] | feat(active-tour): enhance active tour form with improved validation and UI elements[cite: 9] | Mejora el formulario de tour activo incluyendo validaciones avanzadas y elementos de interfaz. | 2026-10-05[cite: 9] |
| axiom/tourmate-frontend | feature/styles | 67fad92[cite: 9] | feat(styles): add feedback and reviews link in sidebar[cite: 9] | Añade enlaces visuales en la barra lateral para la sección de feedback y reseñas. | 2026-10-05[cite: 9] |
| axiom/tourmate-frontend | fix/incident-form | a963a19[cite: 9] | fix(incident-form): dix duplicate import TranslatePipe[cite: 9] | Corrige la importación duplicada de TranslatePipe en el formulario de incidentes. | 2026-10-05[cite: 9] |
| axiom/tourmate-frontend | develop | 618dc53[cite: 9] | Merge branch 'feature/desing' into develop[cite: 9] | Integra la rama con actualizaciones de diseño general hacia la rama develop. | 2026-10-05[cite: 9] |
| axiom/tourmate-frontend | main | 8f28c87[cite: 10] | Merge pull request #1 from axiom-daos/feedback-and-tour-reviews2[cite: 10] | Integra el pull request #1 relacionado al sistema de retroalimentación de tours. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/reviews | 7a1f832[cite: 10] | feat(reviews): implement complete CRUD, i18n support, and UI design parity[cite: 10] | Implementa operaciones CRUD completas, soporte de idiomas y paridad de diseño para reseñas. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/tour-schedule | b1b9300[cite: 10] | (tour-schedule-list): change font weight to max capacity cell[cite: 10] | Modifica el peso de la fuente en la celda de capacidad máxima de la lista de horarios. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/tour-list | 877e82e[cite: 10] | feat: add tour-list cards grid[cite: 10] | Añade una estructura de cuadrícula de tarjetas (grid) para la vista de listado de tours. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/feedback | 9f4b701[cite: 10] | Merge remote-tracking branch 'origin/develop' into feedback-and-tour-reviews2[cite: 10] | Sincroniza la rama de reseñas con los últimos cambios remotos de develop. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/incident-list | 5a27732[cite: 10] | feat(incident-list): add translation support for incident list component[cite: 10] | Implementa soporte de traducciones para el componente de lista de incidentes. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/incident-form | 443edeb[cite: 10] | feat(incident-form): implement translation for incident form labels and placeholders[cite: 10] | Aplica traducciones en las etiquetas y textos temporales del formulario de incidentes. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/incident | 73294db[cite: 10] | feat(incident): add English and Spanish translations for incident management[cite: 10] | Agrega soporte en inglés y español para el gestor de incidentes. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/active-tour | b02edb6[cite: 10] | feat(active-tour): redesign active tour list with enhanced UI and new columns for tour title and guide name[cite: 10] | Rediseña la lista de tours activos agregando columnas de título y nombre del guía. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/active-tour | 19f91be[cite: 10] | feat(active-tour): enhance active tour list with tour title and guide name columns[cite: 10] | Optimiza las columnas de nombre de guía y título en el registro de tours. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/active-tour | 89ae3dc[cite: 10] | feat(active-tour): integrate TourGuide entity and update active tour management[cite: 10] | Integra la entidad de guía de turismo dentro de la gestión de tours activos. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/live-monitoring | 87f06bd[cite: 10] | feat(live-monitoring): add navigation to live monitoring and update translations[cite: 10] | Añade navegación y actualizaciones de texto al sistema de monitoreo en tiempo real. | 2026-10-05[cite: 10] |
| axiom/tourmate-frontend | feature/reviews | c6bfde0[cite: 10] | feat(reviews): stabilize feedback and tour reviews UI and JSON server integration[cite: 10] | Estabiliza la vista de reseñas y su integración de datos con el servidor JSON. | 2026-10-04[cite: 10] |
| axiom/tourmate-frontend | style/reviews | 7fd0fff[cite: 10, 11] | style(reviews): align review-form layout and solid dark buttons with team UI standards[cite: 10, 11] | Alinea los estilos del formulario de revisión y botones oscuros a los estándares del equipo. | 2026-10-04[cite: 10, 11] |
| axiom/tourmate-frontend | fix/layout | cec70c4[cite: 10, 11] | fix: resolve merge conflicts with develop on layout and include feedback reviews navigation[cite: 10, 11] | Resuelve conflictos de integración de diseño en develop y añade la navegación de reseñas. | 2026-10-04[cite: 10, 11] |
| axiom/tourmate-frontend | feature/reviews | 47527cb[cite: 11] | feat(reviews): fix mat-table rendering and integrate ReviewStore signals for feedback and tour reviews[cite: 11] | Arregla el renderizado de la tabla material e integra señales (signals) de ReviewStore. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/tour-list | d0093f2[cite: 11] | add status-tag-inactive in tour-list[cite: 11] | Añade la etiqueta visual de estado inactivo dentro del listado de tours. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/live-monitoring | 8c84e1f[cite: 11] | feat(live-monitoring): implement live monitoring component with participant management and route visualization[cite: 11] | Implementa el componente de monitoreo en vivo con visualización de participantes y rutas. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/agency | 0c0f5ac[cite: 11] | feat(agency): add Agency entity, assembler, and API endpoint for managing agencies[cite: 11] | Agrega entidades, adaptadores y rutas de API para administrar el módulo de agencias. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/tour-guide | 0434f68[cite: 11] | feat(tour-guide): add TourGuide entity, assembler, and API endpoint for managing tour guides[cite: 11] | Implementa la base de datos local y endpoints para administrar los guías turísticos. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/environment | cbaee66[cite: 11] | feat(environment, localization): update environment variables and add live monitoring translations for enhanced functionality[cite: 11] | Actualiza variables de entorno y añade traducciones del módulo de monitoreo. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/app | 53ff216[cite: 11] | feat(app): enhance application shell and localization support for improved user experience[cite: 11] | Refuerza la estructura general de la app (app shell) y mejora el manejo de localización. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/incident | d675610[cite: 11] | feat(incident): enhance incident form and list UI for improved usability and responsiveness[cite: 11] | Optimiza los componentes de formulario y lista de incidentes mejorando usabilidad y adaptabilidad. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/tour | 6efac0d[cite: 11] | feat(tour): enhance tour form and list UI for improved usability and responsiveness[cite: 11] | Optimiza los componentes de interfaz para la gestión general de listado y formularios de tour. | 2026-10-04[cite: 11] |
| axiom/tourmate-frontend | feature/active-tour | 404d7bd[cite: 12] | feat(active-tour): redesign active tour form and list for improved usability and responsiveness[cite: 12] | Aplica rediseño general a los formularios de administración de tours activos. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | feature/core | c59b001[cite: 12] | feat(about, home, not-found): enhance UI components and layout for improved user experience[cite: 12] | Añade y mejora las vistas estáticas principales como Home, About y vista de errores 404. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | refactor/tour | a00f9f5[cite: 12] | refactor(tour): remove TourSchedule entity and related components for simplification[cite: 12] | Simplifica el sistema eliminando la entidad compleja TourSchedule y sus dependencias. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | refactor/tour | 8c02bd7[cite: 12] | refactor(tour): update import paths for TourSchedule and streamline tour response structure[cite: 12] | Arregla rutas de importación afectadas y optimiza la estructura de respuestas. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | refactor/tour | 7a0d396[cite: 12] | refactor(tour): update import paths for TourSchedule and streamline tour response structure[cite: 12] | Consolida los ajustes en rutas de importaciones tras la eliminación de módulos previos. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | feature/environment | c1efc6f[cite: 12] | feat(environment): add new API endpoints for subscriptions, active tours, and payments[cite: 12] | Conecta las variables de entorno para manejar llamadas sobre pagos, suscripciones y tours. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | refactor/routes | c3c7810[cite: 12] | refactor(routes): update tour monitoring paths for consistency[cite: 12] | Estandariza la estructura de rutas (URLs internas) para el área de monitoreo. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | feature/tour-monitoring | 4a06b66[cite: 12] | Merge branch 'develop' into feature/tour-monitoring[cite: 12] | Actualiza la rama de monitoreo con las bases más recientes provenientes de develop. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | develop | 0494a5d[cite: 12] | Merge branch 'feature/subscriptions-and-payment-management' into develop[cite: 12] | Integra todo el desarrollo de suscripciones y pagos hacia la rama principal de pruebas. | 2026-10-04[cite: 12] |
| axiom/tourmate-frontend | refactor/incident-form | 83cddba[cite: 12] | refactor(incident-form): remove unused NgIf import[cite: 12] | Limpia el código eliminando importaciones de NgIf sin utilizar en incidentes. | 2026-10-03[cite: 12] |
| axiom/tourmate-frontend | fix/subscription | cfeaf37[cite: 12] | fix(subscription): replace mat-error with error-banner to avoid unnecessary form-field dependency[cite: 12] | Cambia el sistema de alertas de error nativo por componentes globales tipo banner. | 2026-10-03[cite: 12] |
| axiom/tourmate-frontend | feature/subscriptions | 1585b1c[cite: 12] | Merge branch 'develop' into feature/subscriptions-and-payment-management[cite: 12] | Sincroniza la rama de pagos y suscripciones antes de integrarla definitivamente. | 2026-10-03[cite: 12] |
| axiom/tourmate-frontend | feature/layout | 477d197[cite: 12] | feat: add left sidebar with main content[cite: 12] | Construye la estructura visual de navegación lateral izquierda (sidebar) para usuarios logueados. | 2026-10-03[cite: 12] |
| axiom/tourmate-frontend | chore/subscription | 5977824[cite: 13] | chore(subscription): clean up unused imports and optimize component declarations[cite: 13] | Optimiza y purga el código sin usar en los componentes del módulo de suscripciones. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | fix/subscription | b8bd5d9[cite: 13] | fix(subscription): resolve text spacing, horizontal overflow, and footer overlap[cite: 13] | Soluciona desbordamientos horizontales de texto y colisiones visuales con el pie de página. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/subscription | c2b6db4[cite: 13] | feat(subscription): integrate subscription navigation and i18n translations[cite: 13] | Habilita traducciones en múltiples idiomas y enlaces directos para el gestor de suscripciones. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/subscription | 095526a[cite: 13] | feat(subscription): add subscription dashboard and plan selection views with routing[cite: 13] | Añade vistas principales para elegir planes de agencia con su enrutado correspondiente. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/subscription | db2856e[cite: 13] | feat(subscription): implement SubscriptionStore with Angular signals and state management[cite: 13] | Establece un store reactivo usando Angular Signals para controlar los datos de pagos locales. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/subscription | 6e43cd7[cite: 13] | feat(subscription): add response contracts, assemblers, endpoints and API facade[cite: 13] | Crea interfaces base, mapeadores y la fachada para consumir APIs financieras. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/subscription | 92a4fca[cite: 13] | feat(subscription): add domain entities and value objects for plans, subscriptions and payments[cite: 13] | Modela las entidades de negocio asociadas a los pagos y planes de suscripción. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | fix/routes | df60668[cite: 13] | fix(routes): add management deleted route[cite: 13] | Restaura una ruta de administración accidentalmente eliminada. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/safety | be9671e[cite: 13] | Merge branch 'develop' into feature/safety-and-incident-management[cite: 13] | Mantiene actualizada la rama de incidentes de seguridad absorbiendo bases de develop. | 2026-10-03[cite: 13] |
| axiom/tourmate-frontend | feature/safety | e8bb0ec[cite: 13, 14] | feat(safety): update incident list component with English translations[cite: 13, 14] | Incorpora archivos de internacionalización (inglés) a la tabla de reportes de anomalías. | 2026-10-03[cite: 13, 14] |
| axiom/tourmate-frontend | feature/safety | a24bfbf[cite: 13, 14] | feat(safety): update incident list component with English translations[cite: 13, 14] | Ajustes secundarios de traducciones en el listado de fallos y problemas. | 2026-10-03[cite: 13, 14] |
| axiom/tourmate-frontend | feature/safety | d0c7506[cite: 13, 14] | feat(safety): update incident list component with English translations[cite: 13, 14] | Refuerza la cobertura del idioma en toda la grilla de alertas. | 2026-10-03[cite: 13, 14] |
| axiom/tourmate-frontend | feature/safety | e36389f[cite: 13, 14] | feat(safety): update incident form component with improved layout and English translations[cite: 13, 14] | Repara y traduce los diseños internos del formulario de creación de advertencias. | 2026-10-03[cite: 13, 14] |
| axiom/tourmate-frontend | feature/safety | cdbc4dd[cite: 13, 14] | feat(safety): enhance styling and layout for incident form component[cite: 13, 14] | Potencia la apariencia gráfica y estructura base de formularios vinculados a la seguridad del tour. | 2026-10-03[cite: 13, 14] |
| axiom/tourmate-frontend | chore | f04ccc8[cite: 13, 14] | chore: stop tracking environment files[cite: 13, 14] | Excluye del repositorio en línea los archivos de entorno (variables sensibles). | 2026-10-03[cite: 13, 14] |
| axiom/tourmate-frontend | chore | 65817c7[cite: 14] | update .gitignore[cite: 14] | Configura el sistema de exclusiones de git para ignorar binarios y configuraciones locales. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | f7ed4ac[cite: 14] | feat: add tour schedule form[cite: 14] | Añade el formulario especializado en registrar calendarios de visitas turísticas. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | b4a0d95[cite: 14] | feat: add tour schedule list view[cite: 14] | Construye la vista visual para leer los cronogramas registrados. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | acf7063[cite: 14] | feat: add tour schedules http methods in tour-management-store[cite: 14] | Expande el store central habilitando lógica de llamadas HTTP hacia calendarios. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | 2b5a2fa[cite: 14] | feat: add tour schedules http methods in tour-management-api[cite: 14] | Crea la conexión interna para que Angular invoque los endpoints. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | 8a153e7[cite: 14] | feat: add tour schedule api endpoint[cite: 14] | Enruta el endpoint consumible hacia el área de cronograma. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | 936ae0e[cite: 14] | feat: add tour schedule assembler[cite: 14] | Diseña adaptadores (assemblers) que formatean los esquemas recibidos. | 2026-10-03[cite: 14] |
| axiom/tourmate-frontend | feature/tour-schedule | 392d147[cite: 15] | feat: add tour schedule domain model[cite: 15] | Modela matemáticamente o define lógicamente cómo interactúan las fechas. | 2026-10-03[cite: 15] |
| axiom/tourmate-frontend | feature/tour-schedule | 0885af5[cite: 15] | feat: add tour schedule response[cite: 15] | Tipa correctamente las respuestas del servidor orientadas al módulo. | 2026-10-03[cite: 15] |
| axiom/tourmate-frontend | feature/tour | 6c94e6f[cite: 15] | feat: add tour form view[cite: 15] | Implementa y expone al navegador el formulario base de expediciones y tours genéricos. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | be26205[cite: 15] | feat(safety): simplify routing for safety and incident management[cite: 15] | Redirige más fácilmente las URLs a los submódulos de seguridad acortando los paths. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | 8e999ef[cite: 15] | feat(safety): add routing for incident list and form components[cite: 15] | Enlaza los componentes visuales de listar/crear con sus direcciones web internas en Angular. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | 662813a[cite: 15] | feat(safety): add incident list component with table actions and pagination[cite: 15] | Dota a la tabla de anomalías de soporte visual para cambiar de páginas y presionar botones. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | b66820a[cite: 15] | feat(safety): add incident list component with table layout and actions[cite: 15] | Completa la plantilla principal HTML para visualizar reportes. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | 3a34f5f[cite: 15] | feat(safety): add CSS styles for incident list layout[cite: 15] | Adiciona capas de CSS para dejar limpio y ordenado el diseño tabular. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | 646fe82[cite: 15] | feat(safety): implement incident form component for creating and editing incidents[cite: 15] | Construye un elemento TS capaz de manejar eventos de creación de avisos manuales. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | b98b880[cite: 15] | feat(safety): add incident management form layout in incident-form.html[cite: 15] | Estructura los inputs y contenedores para avisos y pánicos de tour. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | 0196b88[cite: 15] | feat(safety): add CSS styles for incident management form layout[cite: 15] | Aplica hojas de estilo de manera focalizada para el área de reportes. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | fix/safety | 95b33d7[cite: 15] | fix(safety): update default incident status from REPORTED to OPEN[cite: 15] | Homologa los valores estándar (modificando reportado por abierto) en la lógica empresarial. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/safety | 4d18cb7[cite: 15] | feat(safety): add route for safety and incident management module[cite: 15] | Introduce la ruta padre en el proyecto orientada netamente al área de seguridad de campo. | 2026-10-02[cite: 15] |
| axiom/tourmate-frontend | feature/active-tour | 7ead078[cite: 16] | add max capacity column to active tours list[cite: 16] | Renderiza una celda con el indicador del aforo o cantidad límite permitida por grupo turístico. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/active-tour | c8eb5e6[cite: 16] | add tour schedule association to active tours[cite: 16] | Liga o amarra las entidades de tours disponibles a sus fechas y horas establecidas en calendario. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/safety | 48a18e6[cite: 16] | feat(safety): implement IncidentStore with Angular signals and state management[cite: 16] | Utiliza reactividad moderna de Angular para almacenar temporalmente reportes de anomalías. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/safety | 7999ac8[cite: 16] | feat(safety): implement IncidentApi infrastructure facade[cite: 16] | Instala el servicio de consumo REST diseñado expresamente para incidentes. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/safety | eadac6b[cite: 16] | feat(safety): create IncidentApiEndpoint for REST operations[cite: 16] | Conecta el endpoint oficial que recibirá notificaciones y reportes generados. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | refactor/safety | 07b51a0[cite: 16] | refactor(safety): implement IncidentAssembler for data mapping[cite: 16] | Refina y limpia cómo la data externa se mapea a los modelos del frontend en incidentes. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | refactor/safety | fdaeecf[cite: 16] | refactor(safety): add incident response and resource contracts[cite: 16] | Clarifica mediante contratos (interfaces) qué estructura devuelve el servidor. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/safety | 35dc5b9[cite: 16] | feat(safety): implement Incident aggregate root entity[cite: 16] | Genera el objeto de negocio principal que regirá sobre eventos y advertencias. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/safety | 8f09151[cite: 16] | feat(safety): add IncidentStatus enumeration[cite: 16] | Inserta una enumeración (ENUM) para estandarizar etiquetas (abierto, resuelto, ignorado). | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/safety | 0d78263[cite: 16] | feat(safety): add IncidentId value object[cite: 16] | Configura patrones de diseño implementando ID específicos e inmutables para reportes. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/participants | 46d187d[cite: 16] | add participants management functionality with CRUD operations[cite: 16] | Dota al panel del guía con opciones completas para modificar o remover integrantes del viaje. | 2026-10-02[cite: 16] |
| axiom/tourmate-frontend | feature/participants | 036d469[cite: 16, 17] | add participant entity, assembler, and API endpoint for CRUD operations[cite: 16, 17] | Complementa las opciones visuales mapeando toda su respectiva lógica hacia la base de datos externa. | 2026-10-02[cite: 16, 17] |
| axiom/tourmate-frontend | feature/tour | 9c2cd9e[cite: 16, 17] | feat: add tour list view[cite: 16, 17] | Configura el contenedor general que alberga múltiples expediciones resumidas. | 2026-10-02[cite: 16, 17] |
| axiom/tourmate-frontend | feature/tour-schedule | b27f929[cite: 16, 17] | add tour schedules management functionality with CRUD operations[cite: 16, 17] | Incluye vistas funcionales e interactivas de calendarios operativos al administrador. | 2026-10-02[cite: 16, 17] |
| axiom/tourmate-frontend | feature/environment | 104a018[cite: 16, 17] | add tour guides endpoint path to environment configurations[cite: 16, 17] | Provee a la aplicación central de la URL adecuada para ubicar empleados. | 2026-10-02[cite: 16, 17] |
| axiom/tourmate-frontend | feature/tour-guide | f51cbc0[cite: 17] | add tour guide management functionality with CRUD operations[cite: 17] | Permite a la agencia crear, consultar, modificar y remover guías de su equipo desde el panel. | 2026-10-02[cite: 17] |
| axiom/tourmate-frontend | feature/tour-guide | 83857df[cite: 17] | add tour guide entity, assembler, and response definitions[cite: 17] | Habilita todo el flujo tipado en Typescript para recibir data de guías con exactitud. | 2026-10-02[cite: 17] |
| axiom/tourmate-frontend | feature/tour | 938779b[cite: 17] | feat: add tour-management store with loadTours function[cite: 17] | Introduce en memoria global una rutina optimizada para cargar listados asíncronos. | 2026-10-02[cite: 17] |
| axiom/tourmate-frontend | feature/tour | 09042f5[cite: 17] | feat: add tour management api and tours api endpoint[cite: 17] | Finaliza el flujo de comunicación vinculando los archivos locales TS a la red de backend. | 2026-10-01[cite: 17] |
| axiom/tourmate-frontend | feature/tour | c5e2257[cite: 17] | feat: add tour-assembler[cite: 17] | Acondiciona y formatea el JSON puro enviado por TourMate al modelo local esperado. | 2026-10-01[cite: 17] |
| axiom/tourmate-frontend | feature/tour | ab11ae8[cite: 17] | feat: add tour entity model[cite: 17] | Describe propiedades como latitud, nombre, descripción para el modelo principal de ruta. | 2026-10-01[cite: 17] |
| axiom/tourmate-frontend | feature/tour | 8a208d7[cite: 18] | feat: add BaseResource and BaseResponse in tours-response[cite: 18] | Implementa clases universales genéricas para que todos los fetch cuenten con metadatos. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | feature/tour | 6eaf560[cite: 18] | feat: add tour-response interface[cite: 18] | Desarrolla la máscara técnica obligatoria para entender la carga JSON orientada a tours. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | chore/db | 6be8f5e[cite: 18] | chore(server/db.json): fix tours json structure[cite: 18] | Alinea y arregla los objetos estáticos mockeados utilizados en pruebas de red locales. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | feature/active-tour | edc07b4[cite: 18] | rename active tours entity and assembler to singular form; update types and routes accordingly[cite: 18] | Mejora la convención de nombramiento pasándolo a singular en todo el ecosistema de tours en tránsito. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | chore/db | 4ef601d[cite: 18] | chore(server/db.json): fix tours and tour_schedules status field[cite: 18] | Corrige datos de simulación inválidos reemplazando estados obsoletos en el archivo db.json. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | chore/db | decf51c[cite: 18] | update user and agency IDs in db.json for consistency and clarity[cite: 18] | Asegura que la información de agencias y perfiles simulados guarden relación íntegra entre sí. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | feature/active-tour | 560e199[cite: 18] | add active tours entity, assembler, and response definitions[cite: 18] | Crea la base estructural TS para diferenciar y manipular expediciones que actualmente están en ruta. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | refactor/core | eb07343[cite: 18] | refactor JSON keys for consistency in naming conventions[cite: 18] | Reemplaza o modifica nombres de atributos generales (ej. camelCase) para facilitar su mantenimiento. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | refactor/core | b33165a[cite: 18] | refactor JSON keys for consistency and clarity[cite: 18] | Continúa los procesos de limpieza semántica en archivos fuente principales. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | feature/core | 4f9460a[cite: 18] | add initial project structure with core components, styles, and routing[cite: 18] | Configura la cascada de directorios, librerías, y módulos de diseño básicos para iniciar. | 2026-10-01[cite: 18] |
| axiom/tourmate-frontend | main | e3fbdca[cite: 18] | initial structure[cite: 18] | Crea y registra la versión fundacional del repositorio. | 2026-09-30[cite: 18] |

#### *5.2.2.5. Execution Evidence for Sprint Review*

En este segundo Sprint, el equipo se enfocó de lleno en la construcción y desarrollo del Frontend core de TourMate, logrando consolidar la interfaz de usuario y la interactividad de los módulos principales de la plataforma. Se alcanzó satisfactoriamente el objetivo del Sprint al entregar componentes visuales funcionales, responsivos y estructurados, dejándolos listos para su futura integración con la API REST.

Entre los logros más destacados de este ciclo se encuentra el módulo de Gestión de Tours, donde se implementaron las vistas dinámicas para que las agencias puedan crear, editar, duplicar y administrar recorridos, además de gestionar la asignación de turistas. Asimismo, se avanzó significativamente en el módulo de Mapas y Monitoreo, integrando visores interactivos que permiten renderizar rutas (polylines), visualizar checkpoints y proyectar el progreso de la expedición en tiempo real.

*Figura  (Home)*
![Home](../assets/images/wepapp-home.png)

*Figura  (Gestion de Tours)*
![Gestion de Tours](../assets/images/gestion.png)

*Figura  (Monitoreo de Tours)*
![Monitoreo de Tours](../assets/images/monitoreo.png)

*Figura  (Incidentes)*
![Incidentes](../assets/images/incidentes.png)

*Figura  (Planes)*
![Planes](../assets/images/planes.png)

**Web Application Demonstration Video:** [https://upcedupe-my.sharepoint.com/personal/u20221g231_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20221g231%5Fupc%5Fedu%5Fpe%2FDocuments%2FDAOS%2Fvideo%20de%20presentaci%C3%B3n%20TourMate%20DAOS%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E4e7e89ea%2D2cfe%2D4bbb%2D9ff3%2De20be40ad469](https://upcedupe-my.sharepoint.com/personal/u20221g231_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20221g231%5Fupc%5Fedu%5Fpe%2FDocuments%2FDAOS%2Fvideo%20de%20presentaci%C3%B3n%20TourMate%20DAOS%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E4e7e89ea%2D2cfe%2D4bbb%2D9ff3%2De20be40ad469)

#### *5.2.2.6. Services Documentation Evidence for Sprint Review*

Durante este segundo Sprint, la documentación y estructuración de los Web Services se abordó mediante la creación de un Mock API (JSON Server y MockAPI.io) fundamentado en nuestro esquema central `db.json`.Esta implementación nos permitió establecer y probar los contratos de datos (Data Contracts) reales que regirán la comunicación cliente-servidor, desbloqueando así el desarrollo interactivo de las vistas. Se han definido los esquemas de petición y respuesta para los módulos de gestión de tours, monitoreo en vivo (incidentes), perfiles (agencias/usuarios) y calendarios operativos.

**Repositorio y Commits Relacionados**
La configuración de estos servicios, al estar orientada al consumo del cliente en esta fase, se encuentra versionada en el repositorio del Frontend:
* **URL del Repositorio:** `https://github.com/axiom-daos/tourmate-web-application`
* **Commits de Configuración de Endpoints:** `560d09c` (Actualización de URLs base de la API para active tours, agencies, checkpoints, incidents, etc.), `c1efc6f` (Adición de endpoints de subscriptions y payments).

#### Tabla General de Endpoints (Mock API)

| Módulo / Recurso | Base URL / Entorno de Pruebas | Endpoint Path | Acciones Soportadas |
|---|---|---|---|
| **Users** | `https://6a06fa34c83ba8ad9b3e3ccf.mockapi.io/api/v1` | `/users` | GET, POST, PUT, DELETE |
| **Agencies** | `https://6ac5699354a61668c5f7294a.mockapi.io/api/v1` | `/agencies` | GET, POST, PUT, DELETE |
| **Tours** | `https://6ac551d354a61668c5f71aa1.mockapi.io/api/v1` | `/tours` | GET, POST, PUT, DELETE |
| **Active Tours** | `https://6ac55bd454a61668c5f72410.mockapi.io/api/v1` | `/active_tours` | GET, POST, PUT |
| **Incidents** | `https://6ac551e654a61668c5f71abf.mockapi.io/api/v1` | `/incidents` | GET, POST, PUT, DELETE |
| **Participants** | `https://6ac55bd454a61668c5f72410.mockapi.io/api/v1` | `/participants` | GET, POST, DELETE |
| **Tour Schedules** | `https://6ac551d354a61668c5f71aa1.mockapi.io/api/v1` | `/tour_schedules` | GET, POST, PUT, DELETE |
| **Checkpoints** | `https://6ac5699354a61668c5f7294a.mockapi.io/api/v1` | `/checkpoints` | GET, POST, PUT, DELETE |

---

#### Especificación de Acciones y Contratos de Datos

A continuación, se detallan las especificaciones de llamada basándonos en el esquema oficial de datos establecido en este Sprint para dos recursos principales: `Tours` e `Incidents`.

##### 1. Gestión de Tours (`/tours`)
Permite al administrador de agencia consultar el catálogo de expediciones disponibles y registrar nuevas rutas.

*   **GET `/tours`**
    *   **Descripción:** Retorna la lista de todos los tours registrados en el sistema con su estructura detallada.
    *   **Parámetros:** Opcionales vía Query String para filtros.
    *   **Ejemplo de Response (200 OK):**
        El sistema devuelve un arreglo de objetos JSON con la estructura validada en base de datos.
        ```json
        [
          {
            "id": 1,
            "agencyId": 1,
            "title": "Machu Picchu Clásico",
            "description": "Visita guiada a la ciudadela inca de Machu Picchu.",
            "duration": "1 día",
            "difficulty": "MEDIUM",
            "priceAmount": 180,
            "priceCurrency": "USD",
            "status": "ACTIVE"
          }
        ]
        ```

*   **POST `/tours`**
    *   **Descripción:** Crea un nuevo registro de tour en el sistema para una agencia específica.
    *   **Sintaxis de Llamada (Payload):**
        ```json
        {
          "agencyId": 3,
          "title": "Ascenso al Misti",
          "description": "Ascenso al volcán Misti (5,822 m).",
          "duration": "2 días",
          "difficulty": "HARD",
          "priceAmount": 320,
          "priceCurrency": "USD",
          "status": "INACTIVE"
        }
        ```
    *   **Explicación del Response (201 Created):** Retorna el mismo objeto enviado, anexando el identificador único (`id`) generado automáticamente por el servidor.


*Incidents*
![Incidents Endpoint](../assets/images/incidents-endpoint.png)

---

##### 2. Gestión de Incidentes de Seguridad (`/incidents`)
Recurso utilizado por turistas y guías para reportar emergencias u observaciones de seguridad asociadas a una expedición activa.

*   **POST `/incidents`**
    *   **Descripción:** Registra un nuevo incidente detectado en el terreno vinculándolo al tour activo correspondiente.
    *   **Sintaxis de Llamada (Payload):** Debe incluir las coordenadas de geolocalización, el ID del reporte, descripción y estado inicial.
        ```json
        {
          "uuid": "",
          "activeTourId": 1,
          "reportedByUserId": 9,
          "description": "Un participante se torció el tobillo en el sendero.",
          "latitude": -13.156,
          "longitude": -72.526,
          "reportedAt": "2026-10-01T09:20:00",
          "status": "RESOLVED"
        }
        ```
    *   **Explicación del Response (201 Created):** El sistema confirma la recepción guardando el registro y asignándole un `id` secuencial para futuros rastreos y actualizaciones por parte del administrador de la agencia.

*   **PUT `/incidents/:id`**
    *   **Descripción:** Actualiza un incidente existente. Habitualmente utilizado para cambiar la trazabilidad del estado.
    *   **Sintaxis de Llamada (Payload parcial):**
        ```json
        {
          "activeTourId": 2,
          "reportedByUserId": 8,
          "description": "Retraso por bloqueo en la vía hacia Chivay.",
          "latitude": -15.7,
          "longitude": -71.55,
          "reportedAt": "2026-10-01T08:40:00",
          "status": "IN_REVIEW"
        }
        ```

*Tours*
![Tours Endpoint](../assets/images/tours-endpoint.png)

**MockApi Evidencia**

*Active Tours*
![Active Tours Endpoint](../assets/images/active-tours-endpoint.png)

*Participants*
![Participants Endpoint](../assets/images/participants-endpoint.png)

#### *5.2.2.7. Software Deployment Evidence for Sprint Review*


Durante este Sprint, las actividades de despliegue se centraron en la puesta en producción de la aplicación web principal (Frontend) utilizando Firebase Hosting y en la actualización continua de la Landing Page a través de GitHub Pages. Para los Web Services, se mantuvo el alojamiento automático en la nube provisto por la plataforma MockAPI.io. A continuación, se detallan los procesos, herramientas y configuraciones implementadas para la distribución de cada producto.

#### 1. Web Services (Mock API)
Como se detalló en la sección de documentación de servicios, el backend actual opera sobre MockAPI. El despliegue de esta herramienta es automático y gestionado directamente por la plataforma en la nube tan pronto como se definen los esquemas de datos.

#### 2. Landing Page (GitHub Pages)
El sitio web estático promocional (Landing Page) fue desplegado durante el primer Sprint utilizando GitHub Pages. Durante este segundo Sprint, la actualización del despliegue fue completamente automática. Las nuevas características, traducciones y ajustes de diseño integrados en la rama principal (`main`) dispararon la reconstrucción y publicación automática del sitio gracias a las integraciones nativas de GitHub.

![Deployment](../assets/images/Deployment-GHPages.png)

#### 3. Web Application (Firebase Hosting)
Para el despliegue del Frontend interactivo de la plataforma TourMate, se optó por Firebase Hosting debido a su optimización para aplicaciones Single-Page Application (SPA) desarrolladas en Angular. El proceso consistió en la compilación del proyecto, configuración del entorno cloud y ejecución mediante la interfaz de línea de comandos (CLI).

**Paso 1: Build del Proyecto**
Se generó la versión optimizada para producción del código fuente ejecutando el siguiente comando en la terminal del IDE:
```bash
ng build
```
Este proceso empaquetó la aplicación y la depositó en el directorio de salida por defecto (`dist/tourmate-web-application/browser`).

![Build](../assets/images/build.png)

**Paso 2: Creación de Hosting en Firebase Console**
Se accedió a la consola web de Firebase (`https://firebase.google.com/`) autenticando con una cuenta de Google autorizada por el equipo.
* Se seleccionó la opción **Create a new Firebase project**.
* Se ingresó el identificador del proyecto ( `tourmate`).
* Se deshabilitaron las opciones *Enable Gemini in Firebase* y *Enable Google Analytics for this project* para mantener el entorno ligero, procediendo con la creación del proyecto.
* En el panel lateral, se navegó a **Hosting** y se inicializó el servicio seleccionando **Get started**.

*Firebase creación*
![Firebase](../assets/images/firebase1.png)

**Paso 3: Instalación y Configuración del CLI de Firebase**
Se instalaron las herramientas de Firebase globalmente en el entorno de desarrollo y se realizó la vinculación de credenciales:
```bash
npm install -g firebase-tools
firebase login
```


Posteriormente, se inicializó la configuración del proyecto en el directorio raíz de la aplicación Angular:
```bash
firebase init
```
Durante el asistente de inicialización, se aplicaron las siguientes configuraciones críticas para una SPA:
* **Feature:** `Hosting: Configure files for Firebase Hosting...`
* **Project Setup:** `Use an existing project` (Se seleccionó el proyecto `tourmate-frontend` creado en el paso 2).
* **Public directory:** `dist/tourmate-frontend/browser` (Apuntando directamente a los archivos estáticos compilados por Angular).
* **Single-page app configuration:** `Y` (Para reescribir todas las rutas hacia `index.html`, evitando errores 404 al navegar).
* **GitHub Actions deploy:** `N` (Despliegue manual para este Sprint).
* **Overwrite index.html:** `N` (Para preservar el archivo generado por el build de Angular).

*Firebase Init*
![Firebase](../assets/images/firebase2.png)

**Paso 4: Deployment en Firebase**
Una vez enlazado el proyecto local con la nube y definidos los directorios, se procedió a subir los archivos a los servidores de Firebase:
```bash
firebase deploy
```
El proceso finalizó exitosamente, proveyendo la URL pública de producción. La aplicación TourMate ahora se encuentra accesible y operando correctamente en su entorno real.

*Firebase Deploy*
![Firebase](../assets/images/firebase3.png)

*Web Application*
![Home](../assets/images/wepapp-home.png)

**URL Web Application desplegada:** [https://tourmate-e66ff.web.app/](https://tourmate-e66ff.web.app/)

#### *5.2.2.8. Team Collaboration Insights during Sprint*

Todos los miembros del equipo han participado activamente en la implementación de los productos del Sprint 2, lo cual se evidencia mediante los reportes de actividad y contribución del repositorio de GitHub de la organización Axiom.

**Insights**
![Team Insights Sprint 2](../assets/images/insights2.png)

**Contributors**
![Team Insights Sprint 2](../assets/images/contribuciones2.png)

**Commits**
![Team Insights Sprint 2](../assets/images/commits2.png)



### 5.2.3. Sprint 3

#### *5.2.3.1. Sprint Planning 3*

Para el desarrollo del tercer sprint, nuestro esfuerzo se dividirá y centrará en dos aspectos fundamentales para la plataforma. Por el lado del frontend (Web Application), terminaremos de implementar la lógica de negocio pendiente, asegurando que la interactividad y los flujos de datos en las vistas sean precisos. Por el lado del backend (Web Services), nos enfocaremos en la construcción de nuestra API RESTful, implementando los endpoints CRUD reales y los controladores necesarios. Esta evolución nos permitirá migrar de los servicios simulados (MockAPI) a nuestra propia infraestructura backend, integrando ambas capas para consolidar el funcionamiento real de TourMate.

| **Sprint #** | 3 |
| --- |------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** | |
| **Date** | 2026-10-30 |
| **Time** | 4:00 PM |
| **Location** | Reunión virtual |
| **Prepared By** | Giancarlo Verastigue Martinez |
| **Attendees** | Giancarlo Verastigue Martinez, Matias Carrillo Acho, Frank Anthony Huingo Tello, Manuel Alejandro Molina Vasquez, Tony Jhunior Quispe Palomino |
| **Sprint n – 1 Review Summary** | El Frontend de la aplicación web fue estructurado exitosamente y conectado a servicios simulados (MockAPI). Se lograron los objetivos visuales, de navegación y de diseño responsivo para los módulos de gestión de tours, monitoreo en vivo y perfiles. |
| **Sprint n – 1 Retrospective Summary** | El equipo mantuvo un excelente ritmo de trabajo gracias a la división detallada de tareas. Se acordó que para este nuevo ciclo es crítico priorizar la construcción del backend real para reemplazar los mocks y evitar cuellos de botella en la integración final de la lógica de negocio. |
| **Sprint Goal & User Stories** | |
| **Sprint 3 Goal** | Our focus is on finalizing the frontend business logic and developing the backend RESTful API with core CRUD operations for TourMate. This will be confirmed when frontend components successfully consume the real backend endpoints and business rules are fully functional. |
| **Sprint 3 Velocity** | 120 Story Points (Velocidad estimada sumando la carga de finalización de lógica Frontend y la construcción completa de los controladores y servicios Backend proyectados para este ciclo). |
| **Sum of Story Points** | 120 |

#### *5.2.3.2. Aspect Leaders and Collaborators*


A continuación se detalla la matriz de liderazgo y colaboración (LACX) para brindar claridad en la comunicación del equipo durante el desarrollo de las tareas de este Sprint.

Para este tercer sprint, los aspectos se han redefinido para alinearse con los objetivos duales del ciclo: finalizar el lado cliente y construir el backend real. Por ello, las áreas clave son: Lógica de Negocio Frontend (Frontend Business Logic), Servicios de Tours y Monitoreo (Tours & Tracking API), Servicios de Seguridad e Incidentes (Safety & Incidents API), y Arquitectura Core y Perfiles (Core API & Profiles).

| Team Member (Last Name, First Name) | GitHub Username | Frontend Business Logic | Tours & Tracking API | Safety & Incidents API | Core API & Profiles |
|-------------------------------------|-----------------| --- | --- | --- | --- |
| Verastigue Martinez, Giancarlo      | @CaLoVM         | C | L | C | C |
| Carrillo Acho, Matias               | @lonybreux      | C | C | L | C |
| Huingo Tello, Frank Anthony         | @Franz2308      | L | C | C | C |
| Molina Vasquez, Manuel Alejandro    | @AleDusty       | L | C | C | C |
| Quispe Palomino, Tony Jhunior       | @GonzJunior18p  | C | C | C | L |

#### *5.2.3.3. Sprint Backlog 3*

El objetivo principal de este tercer Sprint se dividió en dos frentes complementarios: por un lado, la evolución de la *Landing Page* institucional mediante la incorporación de secciones multimedia interactivas (*About-the-Team* y *About-the-Product*) para consolidar la propuesta de valor; y por otro lado, la construcción, integración y despliegue de los servicios backend RESTful (*Server-Side Software*) de la plataforma TourMate, estableciendo una arquitectura robusta basada en *Domain-Driven Design* (DDD) y el patrón CQRS (*Command Query Responsibility Segregation*) desarrollada con Spring Boot 3.x, Java 21 y persistencia relacional en PostgreSQL. Durante este ciclo se implementa la lógica de negocio y persistencia transversal dividida en cuatro *Bounded Contexts* clave: la asignación, confirmación y consulta paramétrica de tours (*BC: Tour Management*), el seguimiento en tiempo real y transiciones de estado de expediciones activas (*BC: Tour Monitoring*), la gestión de alertas, persistencia de incidentes y umbrales biométricos (*BC: Safety & Incidents*), y el control de perfiles, bitácoras de experiencia y servicios de geolocalización (*BC: IAM & Profiles*). Las User Stories y Technical Stories planificadas han sido rigurosamente descompuestas en tareas de ingeniería (*Engineering Tasks* bajo las nomenclaturas `TS-LPxx.x` para Landing Page y `TS-Bxx.x` para Backend), cubriendo la creación de controladores REST, casos de uso/servicios de aplicación, modelos y agregados del dominio, validación de reglas de negocio, componentes de interfaz interactivos y documentación viva bajo OpenAPI/Swagger.

**Trello link:** [https://trello.com/b/GFgdnufq/tourmate-sprint-3](https://trello.com/b/GFgdnufq/tourmate-sprint-3)

![Sprint Backlog 3](../assets/images/s3-sprint-backlog.png)

| User Story Id | User Story Title | Work-Item / Task Id | Work-Item / Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| US-LP11 | Visualizar video institucional 'About-the-Team' | TS-LP11.1 | Integración multimedia de video About-the-Team | Desarrollar el componente responsivo con contenedor 16:9 y controles de reproducción para presentar al equipo de Axiom en la Landing Page. | 3 | @Franz2308 | Done |
| US-LP11 | Visualizar video institucional 'About-the-Team' | TS-LP11.2 | Optimización y adaptabilidad móvil de video | Validar la reproducción fluida en navegadores móviles/escritorio y agregar fallback accesible ante fallas de red. | 2 | @GonzJunior18p | Done |
| US-LP12 | Visualizar video demostrativo 'About-the-Product' | TS-LP12.1 | Integración de modal interactivo About-the-Product | Implementar el modal/lightbox con overlay interactivo para reproducir el video demostrativo del producto y propuesta de valor de TourMate. | 3 | @CaLoVM | Done |
| US-LP12 | Visualizar video demostrativo 'About-the-Product' | TS-LP12.2 | Vinculación con Call-to-Action y registro | Vincular los llamados a la acción posteriores a la visualización del video hacia la vista de selección de planes y registro. | 2 | @AleDusty | Done |
| US13 | Asignar turistas a un tour | TS-B13.1 | Implementar servicio de asignación | Desarrollar la lógica de negocio en el backend para vincular turistas a un tour específico. | 3 | @lonybreux | Done |
| US13 | Asignar turistas a un tour | TS-B13.2 | Validaciones de capacidad y estado | Implementar reglas de negocio para evitar sobrecupo o asignación a tours ya cerrados/cancelados. | 2 | @CaLoVM | To Do |
| US14 | Desasignar turista de un tour | TS-B14.1 | Implementar servicio de remoción | Crear el método en el backend para eliminar de forma segura la relación entre turista y tour. | 2 | @AleDusty | To Do |
| US14 | Desasignar turista de un tour | TS-B14.2 | Validación de expedición en curso | Agregar lógica para denegar o requerir confirmación extra si se intenta desasignar con la expedición iniciada. | 2 | @Franz2308 | To Do |
| US15 | Confirmar asistencia | TS-B15.1 | Lógica de confirmación de estado | Desarrollar el servicio para actualizar y persistir el estado de confirmación de asistencia del participante. | 2 | @GonzJunior18p | To Do |
| US15 | Confirmar asistencia | TS-B15.2 | Manejo de cancelaciones | Implementar regla de negocio que permita cancelar asistencia notificando al administrador correspondiente. | 3 | @lonybreux | To Do |
| US16 | Buscar y filtrar tours | TS-B16.1 | Implementar consultas JPQL/SQL dinámicas | Crear repositorios con soporte de filtros paramétricos para búsquedas complejas de tours. | 4 | @CaLoVM | To Do |
| US16 | Buscar y filtrar tours | TS-B16.2 | Optimización y paginación de resultados | Aplicar soporte de paginación (ej. Pageable) a los resultados devueltos por la base de datos. | 3 | @AleDusty | To Do |
| US19 | Iniciar expedición | TS-B19.1 | Transición de estado a 'IN_PROGRESS' | Implementar servicio para actualizar el estado del schedule y generar el registro histórico de la expedición. | 3 | @Franz2308 | To Do |
| US19 | Iniciar expedición | TS-B19.2 | Validación de permisos de guía | Verificar mediante control de roles que únicamente el guía asignado pueda disparar el evento de inicio. | 2 | @GonzJunior18p | To Do |
| US20 | Visualizar ruta del tour | TS-B20.1 | Modelo de datos de ruta y waypoints | Configurar entidades espaciales y mapeos de JPA para almacenar secuencias de coordenadas ordenadas. | 4 | @lonybreux | To Do |
| US20 | Visualizar ruta del tour | TS-B20.2 | Servicio de serialización geográfica | Preparar los datos y construir respuestas en formato JSON eficiente para el motor de mapas del cliente. | 3 | @CaLoVM | To Do |
| US23 | Visualizar progreso del recorrido | TS-B23.1 | Motor de cálculo de avance | Crear un servicio interno que evalúe y calcule el porcentaje de avance en base a checkpoints validados. | 3 | @AleDusty | To Do |
| US23 | Visualizar progreso del recorrido | TS-B23.2 | Eventos de finalización automática | Implementar triggers para marcar hitos de avance o detectar el 100% para notificar el cierre. | 2 | @Franz2308 | To Do |
| US25 | Registrar experiencia del recorrido | TS-B25.1 | Repositorio de notas y experiencias | Configurar la entidad, relaciones y el acceso a datos para las anotaciones textuales de cada turista. | 2 | @GonzJunior18p | To Do |
| US25 | Registrar experiencia del recorrido | TS-B25.2 | Validaciones de contexto activo | Restringir y validar que el registro de experiencias se asocie obligatoriamente a una expedición en curso. | 2 | @lonybreux | To Do |
| US28 | Finalizar expedición | TS-B28.1 | Transición de estado a 'FINISHED' | Desarrollar servicio para cerrar formalmente el tour, detener rastreos y asentar el evento. | 3 | @CaLoVM | To Do |
| US28 | Finalizar expedición | TS-B28.2 | Consolidación de reporte final | Implementar lógica para consolidar métricas de la expedición (avance logrado, horas, incidencias). | 3 | @AleDusty | To Do |
| US29 | Monitorear ubicación de turistas | TS-B29.1 | Servicio de ingesta de coordenadas | Desarrollar la lógica optimizada para persistir en lote (batch) o streaming las coordenadas recibidas. | 5 | @Franz2308 | To Do |
| US29 | Monitorear ubicación de turistas | TS-B29.2 | Agrupación de ubicaciones por tour | Construir consultas de alta velocidad que retornen únicamente la última coordenada conocida por turista. | 4 | @GonzJunior18p | To Do |
| US30 | Consultar estado general del grupo | TS-B30.1 | Agregación de métricas de grupo | Crear un Data Transfer Object (DTO) y servicio para resumir el estado de salud y posición de todo el grupo. | 4 | @lonybreux | To Do |
| US30 | Consultar estado general del grupo | TS-B30.2 | Cacheo de estado en tiempo real | Configurar un mecanismo de caché en memoria (ej. Redis) para soportar accesos concurrentes de monitoreo. | 4 | @CaLoVM | To Do |
| US32 | Consultar estado de salud básico | TS-B32.1 | Motor de umbrales biométricos | Desarrollar algoritmos base para clasificar los signos vitales obtenidos como valores normales o de riesgo. | 3 | @AleDusty | To Do |
| US32 | Consultar estado de salud básico | TS-B32.2 | Servicio de consulta de salud | Mapear la última lectura biométrica registrada para ser expuesta rápidamente al rol del guía. | 2 | @Franz2308 | To Do |
| US33 | Reportar incidente | TS-B33.1 | Persistencia de incidentes de seguridad | Modelar la entidad, el repositorio y el servicio de creación para guardar los reportes de anomalías (SOS). | 3 | @GonzJunior18p | To Do |
| US33 | Reportar incidente | TS-B33.2 | Despacho de notificaciones a agencia | Configurar eventos de dominio para alertar internamente a la agencia inmediatamente al crearse un reporte. | 3 | @lonybreux | To Do |
| TS02 | Endpoint de gestión de tours | TS-B02.1 | API REST Controllers de Tours | Construir y exponer formalmente los endpoints GET, POST, PUT, DELETE asociándolos a los servicios creados. | 4 | @CaLoVM | To Do |
| TS02 | Endpoint de gestión de tours | TS-B02.2 | Documentación OpenAPI de Tours | Anotar los controladores con definiciones Swagger para tipar respuestas y requerimientos JSON. | 2 | @AleDusty | To Do |
| TS03 | Endpoint de gestión de expediciones | TS-B03.1 | API REST Controllers de Expediciones | Exponer las rutas HTTP correspondientes para el control del ciclo de vida (iniciar, finalizar) de expediciones. | 4 | @Franz2308 | To Do |
| TS03 | Endpoint de gestión de expediciones | TS-B03.2 | Manejo global de excepciones | Configurar controladores de consejo (Advices) para devolver códigos HTTP correctos (400, 401, 404, 409). | 3 | @GonzJunior18p | To Do |
| TS04 | Endpoint de monitoreo de ubicación | TS-B04.1 | API REST Controllers de Localización | Implementar el endpoint POST preparado para alta concurrencia desde los dispositivos de campo. | 4 | @lonybreux | To Do |
| TS04 | Endpoint de monitoreo de ubicación | TS-B04.2 | Endpoint GET de estado geoespacial | Construir la interfaz de salida HTTP para que la UI de monitoreo consuma posiciones en vivo (polling). | 3 | @CaLoVM | To Do |
| TS07 | Endpoint de gestión de alertas | TS-B07.1 | API REST Controllers de Alertas | Configurar y exponer las rutas REST encargadas de servir el registro activo de alertas generadas. | 3 | @AleDusty | To Do |
| TS07 | Endpoint de gestión de alertas | TS-B07.2 | Validación de payloads (DTOs) | Aplicar decoradores de validación estricta a las cargas útiles de entrada para garantizar la integridad. | 2 | @Franz2308 | To Do |
| TS09 | Endpoint de perfil y notificaciones | TS-B09.1 | API REST Controllers de Perfiles | Implementar los endpoints seguros que permitan exponer y actualizar la información de cuenta del usuario logueado. | 3 | @GonzJunior18p | To Do |
| TS09 | Endpoint de perfil y notificaciones | TS-B09.2 | Endpoints de historial de notificaciones | Exponer el listado de eventos de sistema ordenados para alimentar el panel de notificaciones frontend. | 3 | @lonybreux | To Do |

#### *5.2.3.4. Development Evidence for Sprint Review*

Durante el Sprint 3, el equipo de desarrollo aplicó la metodología GitFlow y el estándar de Conventional Commits (`feat`, `fix`, `docs`, `chore`, `test`) para asegurar la trazabilidad, atomicidad y consistencia del código fuente entre el frontend (`tourmate-web-application`) y el backend (`tourmate-platform`). 

A continuación, se presentan las tablas consolidadas de commits representativos realizados durante el ciclo de desarrollo del Sprint 3 por cada miembro del equipo:

##### Repositorio Backend: `tourmate-platform`

| Hash | Tipo | Módulo / Bounded Context | Descripción del Commit | Autor |
| :--- | :---: | :--- | :--- | :---: |
| `a01a307` | Merge | Subscriptions & Payment Management | Merge branch 'feature/subscriptions-and-payment-management' into develop | @Franz2308 |
| `c15d41d` | Fix | Subscriptions & Payment Management | fix(subscription): configure resilient deserialization and ignore unknown payload properties | @Franz2308 |
| `df57ebd` | Merge | Feedback and Tour Reviews | Merge branch 'feature/feedback-and-tour-reviews' into develop | @GonzJunior18p |
| `1bc5d06` | Fix | Feedback and Tour Reviews | fix(feedback-and-tour-reviews): make review and comment request resources ignore unknown properties | @GonzJunior18p |
| `868aaaa` | Chore | Infrastructure / DevOps | chore: add compose.yaml for PostgreSQL runtime containerization | @CarrilloMatias |
| `279ea83` | Chore | Configuration | chore: remove docker compose from tracking | @CarrilloMatias |
| `b42bfcc` | Feat | Tour Management | feat: add tour controller with full CRUD endpoints | @CarrilloMatias |
| `4d37d6a` | Feat | Tour Management | feat: add tour transforms and resource assemblers | @CarrilloMatias |
| `b0c70e9` | Feat | Tour Management | feat: add tour resources and OpenAPI schema definitions | @CarrilloMatias |
| `cf184ac` | Feat | Tour Management | feat: add tour services implementations and application layer | @CarrilloMatias |
| `69565db` | Feat | Tour Management | feat: add tour query service interface | @CarrilloMatias |
| `8d2931b` | Feat | Tour Management | feat: add tour command service interface | @CarrilloMatias |
| `9313dc5` | Feat | Subscriptions & Payment Management | feat(subscription): add subscription plans database seeder for runtime bootstrap | @Franz2308 |
| `a3a473e` | Feat | Subscriptions & Payment Management | feat(subscription): implement rest controllers and resource assemblers for plans, subscriptions, and payments | @Franz2308 |
| `de9f352` | Feat | Subscriptions & Payment Management | feat(subscription): declare rest request and response resources with openapi schema documentation | @Franz2308 |
| `55faaba` | Feat | Subscriptions & Payment Management | feat(subscription): implement command and query application services with result handling | @Franz2308 |
| `708e7b5` | Feat | Subscriptions & Payment Management | feat(subscription): implement repository adapters connecting domain contracts with jpa persistence | @Franz2308 |
| `81492c0` | Refactor | Tour Monitoring | Refactor ActiveToursController and resources to standardize terminology and improve documentation clarity | @CaLoVM |
| `3a44f6b` | Merge | Tour Monitoring | Merge branch 'feature/tour-monitoring' into develop | @CaLoVM |
| `2c33f15` | Feat | Safety and Incident Management | feat: add detailed documentation for UpdateIncidentResource parameters | @AleDusty |
| `af157bc` | Feat | Safety and Incident Management | feat: add detailed documentation for SafetyMonitoringController endpoints | @AleDusty |
| `c059112` | Feat | Safety and Incident Management | feat: enhance IncidentsController with detailed documentation for incident management endpoints | @AleDusty |

##### Repositorio Frontend: `tourmate-web-application`

| Hash | Tipo | Módulo / Bounded Context | Descripción del Commit | Autor |
| :--- | :---: | :--- | :--- | :---: |
| `f69fd8e` | Merge | Subscriptions & Payment Management | Merge branch 'feature/subscriptions-and-payment-management-business-logic' into develop | @Franz2308 |
| `bcb2323` | Feat | Subscriptions & Payment Management | feat(subscription): enhance API endpoints and assemblers for resilient backend and query integration | @Franz2308 |
| `4581dc2` | Merge | Feedback and Tour Reviews | Merge branch 'feedback-and-tour-reviews2-business-logic' into develop | @GonzJunior18p |
| `0bdf0b6` | Fix | Feedback and Tour Reviews | fix(feedback-and-tour-reviews): sanitize review creation payload and optimize comment queries by review id | @GonzJunior18p |
| `b25aac9` | Fix | Profiles & IAM | fix(profiles): update difficulty translation key to difficulty_label in localization files | @CaLoVM |
| `0bc589e` | Feat | Profiles & IAM | feat(profiles): add routing and localization for My Profile section | @CaLoVM |
| `2464e2c` | Feat | Profiles & IAM | feat(profiles): add ProfileTours component with HTML, CSS, and TypeScript logic for managing assigned tours | @CaLoVM |
| `c995159` | Feat | Profiles & IAM | feat(profiles): add ProfileToursStore and assigned tour management logic | @CaLoVM |
| `8398c25` | Feat | Profiles & IAM | feat(profiles): implement ProfileAssembler and related API endpoint for profile management | @CaLoVM |
| `2c507a3` | Feat | Profiles & IAM | feat(profiles): add Profile entity and ProfileRole enum for user profiles | @CaLoVM |
| `090df13` | Feat | Subscriptions & Payment Management | feat(subscription): add digital payment receipt modal with fiscal details and print action | @Franz2308 |
| `ec273bc` | Feat | Subscriptions & Payment Management | feat(subscription): introduce financial KPI summary cards and cancellation dialog in subscription dashboard | @Franz2308 |
| `0837984` | Feat | Subscriptions & Payment Management | feat(subscription): add interactive checkout confirmation modal and localized plan features in plan selection view | @Franz2308 |
| `a047d3f` | Feat | Subscriptions & Payment Management | feat(subscription): implement expenditure computation, renewal date estimation, and cancellation reason logging in store | @Franz2308 |
| `cd814c8` | Feat | Subscriptions & Payment Management | feat(subscription): add comprehensive i18n keys for subscription metrics, receipts, and checkout dialogs | @Franz2308 |
| `1501fcb` | Feat | Tour Monitoring | feat(active-tour-form): add loading state and enhance form handling for active tours | @CaLoVM |
| `5cf550b` | Feat | Feedback and Tour Reviews | feat(feedback-and-tour-reviews): enhance UI and visual design of the dashboard | @GonzJunior18p |

---

#### *5.2.3.5. Execution Evidence for Sprint Review*

Para validar la correcta ejecución de los servicios backend desarrollados en Spring Boot 3 y su persistencia en PostgreSQL, se estableció un protocolo de verificación en tres niveles: persistencia de datos relacionales, ejecución de endpoints mediante clientes REST (Postman / REST Client) y verificación visual mediante la interfaz Swagger UI.

##### Guía Metodológica de Ejecución para el Equipo

1. **Verificación de Persistencia Relacional (PostgreSQL / pgAdmin):**  
   Confirmar la creación automática de tablas mediante Hibernate JPA (`spring.jpa.hibernate.ddl-auto=update`), verificando las relaciones de clave foránea, índices y la presencia de datos sembrados (seeder) en las tablas `plans`, `subscriptions`, `payments`, `users`, `roles`, `active_tours`, `incidents`, `reviews`, `comments`, `tours` y `tour_schedules`.
2. **Ejecución de Peticiones RESTful:**  
   Probar las operaciones de creación (POST) verificando el código de respuesta HTTP `201 Created` junto con el encabezado `Location` o el recurso devuelto en formato JSON. Asimismo, validar las operaciones de lectura (GET) con código HTTP `200 OK`, validando el correcto mapeo de Value Objects (coordenadas, monedas y fechas ISO-8601).
3. **Manejo Resiliente de Errores:**  
   Probar peticiones con identificadores inexistentes para confirmar la emisión de códigos HTTP `404 Not Found`, y peticiones con payloads incompletos para validar códigos HTTP `400 Bad Request` gestionados por el `GlobalExceptionHandler`.

##### Evidencias de Ejecución

**Evidencia de Persistencia en Base de Datos PostgreSQL:**

*A continuación, se documenta la estructura de tablas relacionales generadas y pobladas automáticamente durante la inicialización de la plataforma:*

![Tablas de Base de Datos PostgreSQL](../assets/images/sprint3-database-evidence.png)
*Figura 5.X. Esquema de tablas generadas por JPA/Hibernate en la base de datos PostgreSQL `tour_mate`.*

**Evidencia de Ejecución de Servicios REST (Peticiones POST y GET):**

*A continuación, se presentan las capturas de peticiones REST ejecutadas de forma satisfactoria sobre los controladores de la plataforma:*

![Ejecución de Petición REST - Creación Exitosa](../assets/images/sprint3-postman-execution-1.png)
*Figura 5.X. Ejecución de petición HTTP POST devolviendo código de estado 201 Created con el DTO serializado en JSON.*

![Ejecución de Petición REST - Consulta de Recursos](../assets/images/sprint3-postman-execution-2.png)
*Figura 5.X. Ejecución de petición HTTP GET devolviendo código de estado 200 OK con el listado de recursos persistidos.*

---

#### *5.2.3.6. Services Documentation Evidence for Sprint Review*

El backend de TourMate cuenta con documentación interactiva estandarizada bajo la especificación **OpenAPI 3.0**, generada dinámicamente mediante la dependencia `springdoc-openapi-starter-webmvc-ui`. La documentación se encuentra accesible localmente en la ruta `http://localhost:8092/swagger-ui/index.html` y en el entorno desplegado en la nube.

##### Características Clave de la Documentación OpenAPI Implementada:

* **Categorización por Bounded Contexts:** Los controladores REST están etiquetados mediante la anotación `@Tag` (ej. `ActiveTours`, `Plans`, `Subscriptions`, `Payments`, `Incidents`, `Reviews`, `Comments`, `Tours`, `Users`, `Roles`), agrupando lógicamente las operaciones del sistema.
* **Especificación de Contratos de Datos (Schemas / DTOs):** Cada DTO de entrada (*Request*) y salida (*Response*) está tipado con `@Schema`, documentando tipos de datos, ejemplos representativos (`example`) y restricciones de obligatoriedad (`requiredMode`).
* **Códigos de Estado HTTP Documentados:** Se documentan explícitamente los códigos de respuesta esperados mediante `@ApiResponses` y `@ApiResponse` (`200 OK`, `201 Created`, `400 Bad Request`, `401 Unauthorized`, `403 Forbidden`, `404 Not Found`).
* **Seguridad y Autorización:** Se incorpora el esquema de seguridad global `bearerAuth` (`@SecurityRequirement(name = "bearerAuth")`), indicando qué endpoints exigen cabeceras HTTP `Authorization: Bearer <token_jwt>` para su consumo.

![Interfaz Swagger UI de la Plataforma TourMate](../assets/images/sprint3-swagger-ui-overview.png)
*Figura 5.X. Catálogo de servicios RESTful y esquemas OpenAPI interactivos en Swagger UI.*

---

#### *5.2.3.7. Software Deployment Evidence for Sprint Review*

Para el despliegue del software en el Sprint 3, se implementó una estrategia orientada a microservicios contenerizados y servicios en la nube, garantizando disponibilidad, aislamiento de procesos y escalabilidad.

##### Arquitectura de Despliegue:

```mermaid
flowchart LR
    A["Cliente Frontend<br>(Angular SPA / Firebase Hosting)"] -->|HTTPS / JSON API| B["Servicio Backend REST<br>(Spring Boot / Render Cloud)"]
    B -->|JDBC Connection Pool| C[("Base de Datos Gestionada<br>(PostgreSQL Cloud / Render)")]
    D["Desarrollo Local<br>(Docker Compose)"] -.->|compose.yaml| E[("Contenedor Local<br>tourmate-db:5432")]
```

##### Pasos Técnicos para el Despliegue del Backend en Render / Cloud:

1. **Aprovisionamiento de la Base de Datos Gestionada:**  
   Se crea una instancia gestionada de PostgreSQL en Render (`tourmate-db`), obteniendo los parámetros de conexión seguros (Host, Puerto, Database Name, Usuario y Contraseña).
2. **Contenerización y Configuración de Docker:**  
   Se utiliza el archivo `compose.yaml` para levantar contenedores locales idénticos al entorno productivo, asegurando paridad de entornos de desarrollo y producción (*12-Factor App methodology*).
3. **Inyección de Variables de Entorno Productivas:**  
   En el panel de configuración de Render, se definen las variables de entorno sin exponer secretos en el repositorio:
   * `SPRING_PROFILES_ACTIVE=prod`
   * `DATABASE_URL=jdbc:postgresql://<render_postgres_host>:5432/tour_mate`
   * `DATABASE_USER=<render_user>`
   * `DATABASE_PASSWORD=<render_password>`
   * `PORT=8092`
   * `AUTHORIZATION_JWT_SECRET=<secret_key>`
4. **Compilación y Construcción del Artefacto:**  
   El motor de construcción ejecuta `./mvnw clean package -DskipTests` y levanta el servicio ejecutando el binario JAR generado (`java -jar target/tourmate-platform-0.0.1-SNAPSHOT.jar`).
5. **Verificación de Disponibilidad (*Health Check*):**  
   Se valida el acceso al endpoint de documentación en vivo y la correcta ejecución de las migraciones/tablas en la base de datos remota.

![Evidencia de Despliegue en Render](../assets/images/sprint3-deployment-render-evidence.png)
*Figura 5.X. Panel de administración del servicio web y base de datos desplegados en la plataforma Render en estado "Live".*

---

#### *5.2.3.8. Team Collaboration Insights during Sprint*

Todos los miembros del equipo han participado activamente en la implementación de los productos del Sprint 3, lo cual se evidencia mediante los reportes de actividad y contribución del repositorio de GitHub de la organización Axiom.

**Insights**
![Team Insights Sprint 2](../assets/images/insights3.png)

**Contributors**
![Team Insights Sprint 2](../assets/images/contribuciones3.png)

**Commits**
![Team Insights Sprint 2](../assets/images/commits3.png)

---

### 5.3. Validation Interviews

#### 5.3.1. Diseño de Entrevistas

Las entrevistas de validación constituyen la principal técnica de investigación cualitativa para evaluar la propuesta de valor, la utilidad práctica y la experiencia de uso de TourMate en un escenario real. A diferencia de la etapa de descubrimiento inicial, estas entrevistas se centran en interactuar con los usuarios finales tras su aproximación o uso simulado de la aplicación, obteniendo perspectivas críticas que alimentan el reporte técnico.

---

##### Objetivos Generales del Proceso de Entrevistas

1. Validar la efectividad del monitoreo y la respuesta a incidentes: Evaluar si el sistema de alertas tempranas, el seguimiento de ubicación y la telemetría IoT responden adecuadamente a las necesidades reales de seguridad en zonas de baja conectividad.
2. Medir la usabilidad y la experiencia offline: Comprobar la facilidad de uso de la aplicación móvil (para turistas y guías) y el panel web centralizado (para agencias) bajo condiciones de operación sin conexión continua.
3. Analizar la percepción de valor y disposición de adopción: Determinar el impacto del uso de dispositivos wearables y checkpoints Bluetooth (BLE) en la confianza del turista y en la eficiencia operativa de la agencia.
4. Identificar fricciones y oportunidades de mejora: Recoger feedback directo sobre flujos específicos (creación de tours, asignación de equipos, reporte de incidentes y sincronización asincrónica) para enriquecer las conclusiones del reporte final.

---

##### Segmento 1: Dueños o Responsables de Agencias de Turismo de Aventura

**Perfil del entrevistado:** Propietarios, gerentes de operaciones, administradores o guías principales de agencias que operan rutas de trekking, montañismo o turismo de aventura en zonas de baja conectividad del Perú.

---

**Apertura y Contexto Operativo**

1. ¿Cómo ha venido manejando la coordinación y supervisión de sus grupos en expediciones recientes en comparación con sus métodos tradicionales?
2. Tras conocer el funcionamiento del dashboard centralizado y los reportes de TourMate, ¿qué tan alineada se encuentra esta herramienta con la realidad operativa de su agencia?

**Validación del Monitoreo y Gestión de Incidentes**

3. Durante la simulación o uso del panel de control en vivo, ¿la visualización de la ubicación de los grupos y el estado de los checkpoints BLE le otorga la claridad necesaria para prevenir situaciones de riesgo?
4. ¿Cómo evalúa el sistema de alertas automáticas ante anomalías (desvíos de ruta o signos vitales fuera de rango)? ¿Considera que agiliza la toma de decisiones frente a los métodos convencionales?

**Funcionalidad Offline y Sincronización Asincrónica**

5. Teniendo en cuenta las zonas sin señal celular en las rutas peruanas, ¿qué tan útil le resulta el mecanismo de sincronización asincrónica para asegurar la trazabilidad de los datos al retornar la conectividad?
6. ¿Encontró alguna limitación o complejidad técnica al registrar o auditar el avance de las expediciones desde la plataforma?

**Adopción, Costos y Expectativas de Negocio**

7. ¿Considera que el modelo de suscripción SaaS combinado con la infraestructura de hardware se ajusta al presupuesto y capacidad de inversión de una Mypeta turística en el Perú?
8. ¿Qué funcionalidades considera que son absolutamente indispensables desde el primer día de implementación en campo y cuáles podrían incorporarse en fases posteriores?

**Gestión de Catálogo y Planificación de Tours**

9. Al momento de crear un nuevo tour y configurar sus checkpoints Bluetooth (BLE), ¿qué tan intuitivo le parece definir las rutas y asociar a los guías líderes?
10. ¿Qué dificultades encuentra actualmente al momento de realizar la asignación de pasajeros, gestionar la nómina oficial y entregar los equipos antes de que los grupos inicien el recorrido?
11. ¿Cómo le beneficia contar con un historial de rutas pasadas para estructurar nuevos itinerarios o planificar el mantenimiento preventivo de la logística?

---

##### Segmento 2: Turistas de Aventura

**Perfil del entrevistado:** Personas nacionales o extranjeras que hayan realizado o participado en actividades de turismo de aventura en zonas remotas de los Andes o la selva peruana en los últimos años.

---

**Apertura y Experiencia con la Aplicación**

1. ¿Con qué frecuencia realiza viajes de aventura o trekking y cuáles son los principales desafíos o temores a los que se enfrenta al recorrer zonas aisladas?
2. ¿Cómo calificaría su experiencia al utilizar la aplicación móvil de TourMate durante la navegación de la ruta y el registro de su recorrido?
3. En comparación con aplicaciones de mapas genéricas, ¿qué tan útil le pareció contar con mapas offline y la visualización de los checkpoints del tour?

**Seguridad, Privacidad y Uso de Dispositivos Wearables**

4. Si la agencia le proporciona un dispositivo wearable para el monitoreo pasivo de su ubicación y signos vitales durante el viaje, ¿generó esto mayor tranquilidad y confianza en su seguridad personal?
5. ¿Le causó alguna preocupación respecto a su privacidad el hecho de que sus datos de salud y ubicación fueran monitoreados temporalmente durante la expedición? ¿Qué condiciones le harían sentir más seguro al respecto?
6. ¿Qué dudas o reparos tendría antes de colocarse un dispositivo de monitoreo biométrico provisto por la agencia al iniciar una expedición exigente?
7. En caso de sufrir una emergencia o extraviarse, ¿qué tan cómodo se sentiría utilizando un botón de pánico físico o digital integrado en la aplicación móvil?

**Funcionalidades de Experiencia y Contexto**

8. ¿Qué tan valioso considera el acceso a información contextual (clima, datos históricos de la ruta, puntos de interés) y el resumen digital automático (diario de viaje con fotos y estadísticas) al finalizar el recorrido?
9. ¿Influyó positivamente el uso de esta tecnología en su decisión de elegir una agencia de turismo frente a otras alternativas tradicionales del mercado?
10. ¿Cómo califica la utilidad de recibir alertas tempranas o notificaciones sobre cambios climáticos repentinos o advertencias de terreno durante la caminata?
11. ¿Qué opina sobre la generación automática de un diario de viaje digital al finalizar la expedición para compartirlo con familiares o amigos?

---

##### Consideraciones Metodológicas

**Cantidad de entrevistas:** mínimo 3 y máximo 5 entrevistas por segmento (total: entre 6 y 10 entrevistas) para alcanzar saturación temática en una etapa de descubrimiento.

**Registro:** Las entrevistas deben ser grabadas con consentimiento del entrevistado para su posterior análisis. Se recomienda el uso de una guía de toma de notas que permita capturar citas textuales relevantes.

**Análisis:** Los resultados serán procesados mediante agrupamiento de respuestas por temática, identificando patrones comunes, necesidades no cubiertas y citas representativas para validar o refutar las hipótesis de problema y solución.

**Ética:** Antes de cada entrevista se informará al participante sobre el propósito de la investigación, la confidencialidad de sus respuestas y su derecho a retirarse en cualquier momento. No se recopilará información personal identificable más allá de la necesaria para el reclutamiento.

---

#### 5.3.2. Registro de Entrevistas

En esta sección se documentan las entrevistas de validación realizadas a los usuarios objetivo de ambos segmentos tras interactuar con la plataforma TourMate. Cada registro incluye los datos del participante, la evidencia audiovisual de la sesión y una síntesis estructurada del feedback cualitativo recibido sobre la funcionalidad, usabilidad y valor de la solución.

##### Segmento 1: Dueños o Responsables de Agencias de Turismo de Aventura

**Entrevista de Validación 1:**

![Entrevista de Validación 1](../assets/images/validation-interview-1.png)

| | |
| :--- | :--- |
| **Entrevistador:** | Frank Anthony Huingo Tello |
| **Entrevistado:** | Carlos Gutierrez |
| **Cargo / Agencia:** | Responsable operativo de Agencia de Turismo de Aventura (Trekking y Montañismo) |
| **Edad:** | 20 años |
| **Segmento:** | Dueño o responsable de agencia de turismo de aventura |
| **Fecha:** | 08/11/2026 |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | 9:07 min |
| **Enlace:** | https://upcedupe-my.sharepoint.com/:v:/g/personal/u202319057_upc_edu_pe/IQCKEmttzH5dQry3cq63kqcnAYH04uQeaWWmC9FCgY6ubTc?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=HrRfsH |

**Resumen:** En esta sesión de validación, Carlos Gutiérrez (20 años), responsable de operaciones en rutas de trekking y alta montaña en el sur del país, interactuó con la versión funcional de la plataforma TourMate para evaluar su aplicabilidad en escenarios reales. Durante la prueba, navegó por el panel de administración de la agencia, validando el flujo de creación y configuración de paquetes turísticos, la asignación de cupos y fechas de salida programadas, y el módulo de visualización de expediciones activas. Carlos destacó positivamente la centralización de la información operativa en un único dashboard, señalando que reduce drásticamente los tiempos muertos frente a su método tradicional de bitácoras físicas y reportes dispersos por radio VHF. Asimismo, valoró la claridad en la visualización de rutas mediante waypoints y la estructura transparente de los planes de suscripción para agencias. En cuanto a oportunidades de mejora, recomendó incorporar alertas visuales más inmediatas al guardar cambios en los tours y permitir la duplicación rápida de expediciones frecuentes para optimizar el flujo de trabajo diario. Concluyó confirmando su alta disposición de adopción de la herramienta, resaltando que brindará mayor certidumbre y control sobre los grupos en campo.

---

**Entrevista de Validación 2:**

![Entrevista de Validación 2](../assets/images/validation-interview-2.png)

| | |
| :--- | :--- |
| **Entrevistador:** | [Nombre del Entrevistador (Equipo Axiom)] |
| **Entrevistado:** | [Nombre y Apellidos del Entrevistado] |
| **Cargo / Agencia:** | [Rol / Nombre de la Agencia de Turismo] |
| **Edad:** | [Edad] años |
| **Segmento:** | Dueño o responsable de agencia de turismo de aventura |
| **Fecha:** | [DD/MM/2026] |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | [MM:SS] min |
| **Enlace:** | [URL del video en OneDrive / SharePoint / YouTube] |

**Resumen:** [Síntesis cualitativa de la entrevista: contexto del entrevistado, funcionalidades de la aplicación web que evaluó, aspectos destacados de la solución, principales observaciones de usabilidad identificadas y feedback sobre la disposición de pago/adopción del servicio].

---

**Entrevista de Validación 3:**

![Entrevista de Validación 3](../assets/images/validation-interview-3.png)

| | |
| :--- | :--- |
| **Entrevistador:** | [Nombre del Entrevistador (Equipo Axiom)] |
| **Entrevistado:** | [Nombre y Apellidos del Entrevistado] |
| **Cargo / Agencia:** | [Rol / Nombre de la Agencia de Turismo] |
| **Edad:** | [Edad] años |
| **Segmento:** | Dueño o responsable de agencia de turismo de aventura |
| **Fecha:** | [DD/MM/2026] |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | [MM:SS] min |
| **Enlace:** | [URL del video en OneDrive / SharePoint / YouTube] |

**Resumen:** [Síntesis cualitativa de la entrevista: contexto del entrevistado, funcionalidades de la aplicación web que evaluó, aspectos destacados de la solución, principales observaciones de usabilidad identificadas y feedback sobre la disposición de pago/adopción del servicio].

---

##### Segmento 2: Turistas de Aventura

**Entrevista de Validación 4:**

![Entrevista de Validación 4](../assets/images/validation-interview-4.png)

| | |
| :--- | :--- |
| **Entrevistador:** | [Nombre del Entrevistador (Equipo Axiom)] |
| **Entrevistado:** | [Nombre y Apellidos del Entrevistado] |
| **Edad:** | [Edad] años |
| **Segmento:** | Turista de Aventura |
| **Fecha:** | [DD/MM/2026] |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | [MM:SS] min |
| **Enlace:** | [URL del video en OneDrive / SharePoint / YouTube] |

**Resumen:** [Síntesis cualitativa de la entrevista: perfil del turista y frecuencia de viajes de aventura, experiencia al explorar el catálogo de tours y detalles de las rutas en la Web App, percepción sobre el sistema de seguimiento de expedición y seguridad, dudas encontradas en la interfaz y sugerencias de diseño].

---

**Entrevista de Validación 5:**

![Entrevista de Validación 5](../assets/images/validation-interview-5.png)

| | |
| :--- | :--- |
| **Entrevistador:** | [Nombre del Entrevistador (Equipo Axiom)] |
| **Entrevistado:** | [Nombre y Apellidos del Entrevistado] |
| **Edad:** | [Edad] años |
| **Segmento:** | Turista de Aventura |
| **Fecha:** | [DD/MM/2026] |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | [MM:SS] min |
| **Enlace:** | [URL del video en OneDrive / SharePoint / YouTube] |

**Resumen:** [Síntesis cualitativa de la entrevista: perfil del turista y frecuencia de viajes de aventura, experiencia al explorar el catálogo de tours y detalles de las rutas en la Web App, percepción sobre el sistema de seguimiento de expedición y seguridad, dudas encontradas en la interfaz y sugerencias de diseño].

---

**Entrevista de Validación 6:**

![Entrevista de Validación 6](../assets/images/validation-interview-6.png)

| | |
| :--- | :--- |
| **Entrevistador:** | [Nombre del Entrevistador (Equipo Axiom)] |
| **Entrevistado:** | [Nombre y Apellidos del Entrevistado] |
| **Edad:** | [Edad] años |
| **Segmento:** | Turista de Aventura |
| **Fecha:** | [DD/MM/2026] |
| **Inicio de la entrevista:** | 0:00 |
| **Duración:** | [MM:SS] min |
| **Enlace:** | [URL del video en OneDrive / SharePoint / YouTube] |

**Resumen:** [Síntesis cualitativa de la entrevista: perfil del turista y frecuencia de viajes de aventura, experiencia al explorar el catálogo de tours y detalles de las rutas en la Web App, percepción sobre el sistema de seguimiento de expedición y seguridad, dudas encontradas en la interfaz y sugerencias de diseño].

---

#### 5.3.3. Evaluaciones según heurísticas

A partir de las sesiones de interacción y entrevistas de validación realizadas con los usuarios de ambos segmentos (agencias y turistas), se llevó a cabo una **evaluación heurística consolidada** basada en los diez principios generales para el diseño de interfaces de usuario propuestos por **Jakob Nielsen**.

Para priorizar las oportunidades de mejora encontradas, se empleó la escala estándar de severidad de Nielsen:
- **0 - Sin problema:** No se considera un problema de usabilidad.
- **1 - Problema cosmético:** No interfiere en la tarea; solo se corrige si sobra tiempo.
- **2 - Problema menor:** Dificultad leve de uso; baja prioridad de resolución.
- **3 - Problema mayor:** Dificultad importante; afecta la experiencia y debe corregirse con alta prioridad.
- **4 - Catástrofe de usabilidad:** Impide al usuario completar la tarea esencial; resolución imperativa.

---

##### Matriz Consolidada de Evaluación Heurística (TourMate Web Application)

| N° | Principio Heurístico de Nielsen | Problema / Hallazgo Detectado en la Validación | Severidad | Propuesta de Solución / Mejora de Diseño |
|:---:|:---|:---|:---:|:---|
| **1** | **Visibilidad del estado del sistema** | Al guardar o editar un tour, el usuario no recibía confirmación visual inmediata del procesamiento ni del guardado exitoso en el backend. | **2** | Implementar notificaciones tipo *snackbar* / *toast* reactivas y *spinners* de carga durante las peticiones asíncronas HTTP. |
| **2** | **Coincidencia entre el sistema y el mundo real** | Algunos términos técnicos en la vista de monitoreo de expedición resultaban poco familiares para los guías y turistas. | **1** | Adecuar la terminología hacia el lenguaje ubicuo del turismo de aventura (ej. reemplazar *lat/lng payload* por *Punto de Control*, *Waypoints* y *Altitud*). |
| **3** | **Control y libertad del usuario** | En el formulario de creación de tours no existía una opción clara para cancelar o descartar los cambios sin tener que recargar el navegador. | **3** | Agregar un botón explícito de *"Cancelar / Descartar"* con modal de confirmación para evitar pérdida accidental de datos. |
| **4** | **Consistencia y estándares** | El botón de acción principal (*CTA*) presentaba variaciones de color y posición entre la vista del catálogo y la vista de detalle del tour. | **2** | Estandarizar la jerarquía visual de botones con los tokens de diseño definidos en la guía de estilos de Angular Material. |
| **5** | **Prevención de errores** | En los campos de capacidad de turistas y precio por persona se permitían valores negativos o caracteres no numéricos antes de enviar el formulario. | **3** | Incorporar validadores reactivos en tiempo real (`Validators.min`, `Validators.pattern`) que deshabiliten el botón de envío ante entradas no válidas. |
| **6** | **Reconocimiento antes que recuerdo** | Para asignar guías a un tour, el administrador debía recordar y escribir el identificador manualmente en lugar de seleccionarlo. | **3** | Reemplazar el campo de texto libre por un componente de selección desplegable (`mat-select`) con búsqueda predictiva y avatares de guías disponibles. |
| **7** | **Flexibilidad y eficiencia de uso** | Usuarios recurrentes de agencias solicitaron atajos o una opción de duplicar tours existentes para no llenar todos los campos desde cero. | **2** | Añadir la acción de *"Clonar / Duplicar Tour"* en la tabla de gestión de tours para agilizar la creación de expediciones similares. |
| **8** | **Estética y diseño minimalista** | La tarjeta de resumen del tour contenía exceso de texto secundario que dificultaba escanear rápidamente la información clave (precio, duración, dificultad). | **2** | Rediseñar las tarjetas aplicando arquitectura de información limpia con *badges* destacados para dificultad, duración y precio. |
| **9** | **Ayudar a reconocer, diagnosticar y recuperarse de errores** | Los mensajes de error de la API mostraban descripciones técnicas genéricas (ej. *Error 400 Bad Request*) sin explicar qué campo falló. | **3** | Interceptar respuestas HTTP de error en el frontend para mostrar mensajes amigables y contextuales (ej. *"La fecha de inicio debe ser posterior al día de hoy"*). |
| **10** | **Ayuda y documentación** | En el apartado de bitácoras y monitoreo de emergencias, los usuarios primerizos no tenían una guía introductoria sobre el significado de cada estado. | **1** | Incorporar tooltips informativos y un botón flotante de ayuda rápida con preguntas frecuentes sobre el funcionamiento del monitoreo. |

---

### 5.4. Video About-the-Product

El video *About-the-Product* constituye el artefacto audiovisual de validación demostrativa de la plataforma TourMate. Su objetivo principal es exponer el valor de negocio, la interacción de los usuarios y la operatividad técnica de los servicios implementados a lo largo de los tres Sprints de desarrollo, integrando el frontend en Angular con los servicios backend RESTful en Spring Boot.

#### Ficha Técnica del Video de Producto

| Parámetro | Detalle |
| :--- | :--- |
| **Título del Video:** | TourMate - Plataforma Web para Gestión y Monitoreo Seguro de Turismo de Aventura |
| **Duración:** | [MM:SS] min *(Recomendado entre 3 y 5 minutos)* |
| **Fecha de Producción:** | [DD/MM/AAAA] |
| **Plataforma / Enlace:** | [Enlace al video en YouTube / OneDrive / SharePoint] |
| **Presentadores / Miembros:** | Frank Anthony Huingo Tello, Matias Renato Carrillo Acho, Giancarlo Jose Verastigue Martinez, Manuel Alejandro Molina Vasquez, Tony Jhunior Quispe Palomino |

---

#### Estructura y Guion de Escenas del Video

```mermaid
flowchart LR
    A["Escena 1<br>Propuesta de Valor & Landing"] --> B["Escena 2<br>Autenticación & Perfiles (IAM)"]
    B --> C["Escena 3<br>Planes & Checkout (Suscripciones)"]
    C --> D["Escena 4<br>Gestión & Monitoreo en Vivo (Tours)"]
    D --> E["Escena 5<br>Reporte de Alertas & Emergencias"]
    E --> F["Escena 6<br>Feedback, Reseñas & Cierre"]
```

1. **Escena 1: Presentación y Propuesta de Valor (0:00 - 0:45)**  
   Demostración de la *Landing Page* institucional de TourMate, explicando la problemática de seguridad y coordinación que enfrentan las agencias de turismo de aventura y los turistas en rutas de trekking sin señal celular continua.
2. **Escena 2: Autenticación y Gestión de Identidad (0:45 - 1:30)**  
   Demostración del flujo de inicio de sesión (*Sign-in*) y registro (*Sign-up*) con asignación de roles de usuario (Agencia, Guía, Turista, Administrador) y emisión de credenciales seguras mediante tokens JWT en Spring Boot.
3. **Escena 3: Catálogo de Planes y Checkout Interactivo (1:30 - 2:30)**  
   Visualización interactiva del catálogo de planes de suscripción para operadores turísticos, comparación de funcionalidades por nivel (básico, profesional, empresarial), simulación de pasarela de pago segura y emisión automática del comprobante de recibo fiscal digital con opción de impresión.
4. **Escena 4: Creación de Tours y Monitoreo de Expedición en Vivo (2:30 - 3:45)**  
   Recorrido por la creación y programación de tours, asignación de guías de campo y visualización en tiempo real del mapa de expedición con telemetría de ubicación y checkpoints georreferenciados.
5. **Escena 5: Bitácora de Seguridad y Reporte de Incidentes (3:45 - 4:30)**  
   Simulación de una alerta de emergencia reportada desde la expedición, visualización en el dashboard de control de la agencia con coordenadas exactas, nivel de severidad y registro de resolución de incidentes.
6. **Escena 6: Calificaciones, Reseñas Turísticas y Cierre (4:30 - Conclusión)**  
   Registro y consulta de reseñas turísticas por parte de los participantes tras culminar el recorrido, demostrando la integración completa y la robustez de los servicios desarrollados en el ciclo de vida del proyecto.

---

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

#

## Anexos

<div style="page-break-before: always;"></div>

### Anexo A. Videos de exposiciones

- Exposición AV1: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDffa4P9uW3SqlkTMvmZIkDAdNuNWS0YpS-94osKLniRPY?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=gXbFhx

<div style="page-break-before: always;"></div>

### Anexo B. Videos de entrevistas

- Entrevista 1 - Mateo Escudero, Agencia de Tour: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQCf3pj989dtRqsxlQP-cphyAdmHJbpSw14HLGTRks5qOyM?e=L98d2n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D
- Entrevista 2 - Aarón Espinosa, Agencia de Tour: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAofZYR8ATPSbWHvKq3vOSvAZ1mk5uCZxK_sr8rN9qoqI4?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=CzroE4
- Entrevista 3 - Carlos Gutierrez, Agencia de Tour: https://upcedupe-my.sharepoint.com/personal/u202319057_upc_edu_pe/_layouts/15/stream.aspx?id=/personal/u202319057_upc_edu_pe/Documents/Entrevista+DAOP.mp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp.Web&referrerScenario=AddressBarCopied.view.2461ff76-283b-41f2-bb72-df3bc61e4215&ClientRender=1
- Entrevista 4 - Sofia Mendoza, Turista de aventura: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241f714_upc_edu_pe/IQBPxk5ihQP7Qpk1EiObhUKMAcqE0PkmidpljYmgsKZhw60?e=y94DfE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXcifX0%3D
- Entrevista 5 - Romina Antonella Molina Vásquez, Turista de aventura: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221g231_upc_edu_pe/IQAQPNKuz_cKS4krk8KnLmoKAaAOQuWIL6WmZXL4T30cJJQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6IldpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=B3HGgd
- Entrevista 6 - Miler Rodriguez, Turista de aventura: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202419483_upc_edu_pe/IQDe0UWGvKUwRojgbs_XPIuJAclsUfNSUJK04_8jjCFOE7A?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=Szx6cw



### Anexo D. Materiales de ideación y diseño

- Lean UX Canvas del proyecto TourMate: 
- Big Picture EventStorming y Design-Level EventStorming: [https://miro.com/app/board/uXjVHl1uCrg=/?share_link_id=456387536744](https://miro.com/app/board/uXjVHl1uCrg=/?share_link_id=456387536744)
- Wireframe de la landing page: [https://www.figma.com/design/byMOHsD6I3IV3fdNwVPg3C/Tourmate-Landing-Page-Mockup?node-id=0-1&t=tADie7c5MlXe8uc4-1](https://www.figma.com/design/byMOHsD6I3IV3fdNwVPg3C/Tourmate-Landing-Page-Mockup?node-id=0-1&t=tADie7c5MlXe8uc4-1)
- Mock-up de la landing page: [https://www.figma.com/design/GVX1ocXvc77A9A24OnWhom/Tourmate-Mockup?node-id=0-1&t=5e7BZiJAVQvdoPjv-1](https://www.figma.com/design/GVX1ocXvc77A9A24OnWhom/Tourmate-Mockup?node-id=0-1&t=5e7BZiJAVQvdoPjv-1)
- Wireframes de la aplicación web: [https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)
- Wireflows de la aplicación web: [https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)
- Mock-ups de la aplicación web: [https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)
- Prototipo de la aplicación web: [https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1](https://www.figma.com/design/SKEFgPxKRE4cJmEnGjuAx3/DAOS_final?node-id=0-1&t=yXf7imx6mdAPUOiO-1)



### Anexo E. Repositorios y despliegues

- Repositorio del informe del proyecto: https://github.com/axiom-daos/tourmate-report
- Repositorio de la landing page: https://github.com/axiom-daos/tourmate-landing
- Repositorio del Web Application: https://github.com/axiom-daos/tourmate-web-application
- Repositorio del Backend: https://github.com/axiom-daos/tourmate-platform
- Despliegue de la landing page: https://axiom-daos.github.io/tourmate-landing/
- Tablero del Sprint Backlog 1: https://trello.com/b/gCKcMjVR/tourmate-sprint-1


### Anexo F. Herramientas utilizadas

- Trello, para gestión del backlog y tareas del proyecto: https://trello.com
- Gherkin, para criterios de aceptación en formato Given-When-Then: https://cucumber.io/docs/gherkin/
- Miro, para dinámicas de EventStorming: https://miro.com/
- Figma, para wireframes, mock-ups y prototipos: https://www.figma.com
- Canva, para recursos visuales del producto: https://www.canva.com
- UXPressia, para User Personas y Customer Journey Maps: https://uxpressia.com
- Lucidchart, para diagramas del sistema: https://www.lucidchart.com/ / https://lucidchart.com
- GitHub, para control de versiones y colaboración: https://github.com
- Visual Studio Code, para edición de código y archivos Markdown: https://code.visualstudio.com/
- GitHub Pages, para despliegue de la landing page y frontend web: https://pages.github.com
- Structurizr, para diagramas C4: https://structurizr.com
- Vertabelo, para diagramas de base de datos: https://vertabelo.com


### Anexo G. Referencias bibliográficas con enlace

- Guía para ejecutar Big Picture Event Storming: https://bit.ly/bpes-guide
- Guía práctica de EventStorming remoto: https://ddd-practitioners.com/2023/03/20/remote-eventstorming-workshop/
- Material sobre historias de usuario: https://www.scrummanager.com/files/scrum_manager_historias_usuario.pdf
- Libro de ingeniería de software usado como referencia: https://www.javier8a.com/itc/bd1/ld-Ingenieria.de.software.enfoque.practico.7ed.Pressman.PDF