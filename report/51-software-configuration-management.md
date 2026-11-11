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
| Software Development (Backend)        | IntelliJ IDEA / VS Code  | IDE para el desarrollo de Web Services bajo estilo RESTful utilizando Java 21, Spring Boot 3.x, Spring Data JPA y PostgreSQL. |
| Software Development (Frontend)       | Visual Studio Code       | IDE para el desarrollo de la Web Application SPA con Angular 19, TypeScript, Angular Material y SCSS. |
| Software Development (Landing Page)   | Visual Studio Code       | IDE para el desarrollo de la Landing Page con HTML5, CSS3 y JavaScript vanilla. |
| Version Control                       | GitHub                   | Alojamiento de repositorios y gestión de versiones aplicando GitFlow y Conventional Commits. |
| Continuous Deployment & Hosting       | Firebase Hosting / GitHub Pages | Alojamiento y entrega continua de la aplicación Web Frontend y la Landing Page. |
| Documentation                         | Markdown                 | Documentación del reporte del proyecto.                                         |

#### 5.1.2. Source Code Management

El código fuente del proyecto se gestionará utilizando **Git** como sistema de control de versiones y **GitHub** como plataforma de alojamiento, bajo una organización pública. Se adoptará un enfoque estructurado que favorezca la colaboración, la modularidad y el despliegue continuo mediante repositorios independientes para cada componente del sistema.

- **Report:** [https://github.com/axiom-daos/tourmate-report](https://github.com/axiom-daos/tourmate-report)
- **Landing Page:** [https://github.com/axiom-daos/tourmate-landing](https://github.com/axiom-daos/tourmate-landing)
- **Frontend Web Application:** [https://github.com/axiom-daos/tourmate-web-application](https://github.com/axiom-daos/tourmate-web-application)
- **RESTful Web Services:** [https://github.com/axiom-daos/tourmate-platform](https://github.com/axiom-daos/tourmate-platform)

#### Estrategia de Ramas y Flujo de Colaboración (GitFlow Workflow)

Para asegurar la integridad, trazabilidad y estabilidad del código fuente a lo largo del ciclo de vida del desarrollo, el equipo adopta el modelo **GitFlow** como flujo de trabajo estándar de ramificación (*branching*) y colaboración. Este flujo define reglas estrictas para el aislamiento de funcionalidades, la integración continua y el despliegue seguro a producción:

```mermaid
gitGraph
    commit id: "v0.1.0" tag: "v0.1.0"
    branch develop
    checkout develop
    commit id: "init-develop"
    branch feature/tour-mgmt
    checkout feature/tour-mgmt
    commit id: "feat: tour entity"
    commit id: "feat: tour service"
    checkout develop
    merge feature/tour-mgmt id: "PR #1 merge"
    branch feature/tour-tracking
    checkout feature/tour-tracking
    commit id: "feat: tracking gps"
    checkout develop
    merge feature/tour-tracking id: "PR #2 merge"
    branch release/v1.0.0
    checkout release/v1.0.0
    commit id: "chore: bump version"
    checkout main
    merge release/v1.0.0 id: "release v1.0.0" tag: "v1.0.0"
    checkout develop
    merge release/v1.0.0 id: "sync develop"
    checkout main
    branch hotfix/fix-auth
    checkout hotfix/fix-auth
    commit id: "fix: token auth"
    checkout main
    merge hotfix/fix-auth id: "merge hotfix" tag: "v1.0.1"
    checkout develop
    merge hotfix/fix-auth id: "sync hotfix"
```

##### Roles y Ciclo de Vida de las Ramas

1. **Ramas Principales (Permanentes):**
   - **`main`**: Alberga exclusivamente el código en estado de producción. Todo commit en esta rama corresponde a una versión estable, probada y empaquetada, acompañada de un tag semántico (ej. `v1.0.0`). Los desarrolladores tienen prohibido realizar commits directos sobre `main`.
   - **`develop`**: Rama base de integración continua. Refleja el estado consolidado de las funcionalidades desarrolladas para el próximo Sprint o entrega. Todo el trabajo nuevo se desprende de `develop` y se reintegra a ella tras pasar por revisión de código.

2. **Ramas de Soporte (Temporales / Efímeras):**
   - **`feature/[nombre-funcionalidad]`**: Ramas creadas exclusivamente a partir de `develop` para desarrollar una User Story o tarea de ingeniería específica (ej. `feature/US13-tour-assignment`, `feature/subscriptions-and-payment-management`). Al concluirse y superar las pruebas locales, se solicita su fusión hacia `develop` mediante un Pull Request. Una vez fusionada, la rama remota se elimina.
   - **`release/[versión]`**: Ramas destinadas a la estabilización previa a un hito o entrega de Sprint (ej. `release/sprint-3`). Permiten pulir documentación, corregir detalles menores de configuración y preparar los metadatos de versión sin bloquear el trabajo de nuevas features en `develop`. Al finalizar, se fusiona tanto a `main` (creando el tag) como de regreso a `develop`.
   - **`hotfix/[nombre-incidencia]`**: Ramas críticas generadas a partir de `main` para solventar errores severos detectados en producción que no pueden esperar al siguiente ciclo de desarrollo. Una vez solucionado el fallo, se integran inmediatamente a `main` y a `develop`.

##### Políticas de Colaboración y Revisión de Código (Code Review)

- **Pull Requests (PR) Obligatorios:** Ningún miembro del equipo puede fusionar código directamente sobre `develop` o `main`. Todo cambio debe tramitarse mediante un Pull Request en GitHub.
- **Revisión por Pares (Peer Review):** Todo PR requiere al menos una aprobación explícita de un compañero de equipo antes del merge, verificando el cumplimiento de la guía de estilos, la arquitectura DDD/Clean Architecture y la ausencia de deuda técnica.
- **Trazabilidad y Conventional Commits:** Los títulos de los PR y los commits deben referenciar la tarea o User Story correspondiente y adherirse a Conventional Commits.
- **Resolución de Conflictos:** En caso de conflicto de integración, el autor de la rama feature debe actualizar su rama con la última versión de `develop` (`git merge develop` o `git rebase develop`) y resolver los conflictos localmente antes de solicitar la fusión.

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