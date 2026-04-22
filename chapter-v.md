# 5.1. Software Configuration Management
## 5.1.1. Software Development Environment Configuration

Para el desarrollo de SafeLab, utilizaremos el siguiente conjunto de herramientas, respetando las restricciones tecnológicas del curso:

| Actividad | Producto | Propósito / Uso |
| :--- | :--- | :--- |
| Project Management | Jira Software | Gestión del Product Backlog, planificación de Sprints y seguimiento de tareas mediante tableros Kanban. |
| Requirements Management | UXPressia | Elaboración de artefactos de descubrimiento (User Personas, Empathy Maps) para la definición de requisitos. |
| UX/UI Design | Figma | Diseño de la guía de estilo, prototipos de baja fidelidad (wireframes) y alta fidelidad (mockups). |
| Software Development (Backend) | IntelliJ IDEA | IDE para el desarrollo de los RESTful Web Services utilizando Java y Spring Boot. |
| Software Development (Frontend) | Visual Studio Code | IDE para el desarrollo de la Web Application (Angular) y el Landing Page. |
| Version Control | GitHub | Sistema de control de versiones distribuido para el alojamiento y gestión de repositorios. |
| Documentation (API) | Swagger / OpenAPI | Herramienta para la documentación técnica y pruebas de los endpoints de la API. |
## 5.1.2. Source Code Management


El control de versiones se realizará en GitHub bajo una organización pública. Se han implementado repositorios independientes para garantizar la modularidad y el despliegue continuo de cada componente:


* **Landing Page Repository:** [https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page](https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page)


### Estrategia de Branching (GitFlow)

Se implementará el modelo GitFlow para asegurar un ciclo de vida de desarrollo robusto y ordenado:


* **main branch:** Contiene exclusivamente el código en producción. Cada cambio en esta rama debe estar etiquetado con una versión estable.


* **develop branch:** Rama principal de integración donde reside el código más reciente de desarrollo.


* **feature branches:** Ramas temporales para el desarrollo de nuevas User Stories.
    * Convención: `feature/short-description` (ej. `feature/order-registration`).


* **release branches:** Ramas de preparación para despliegues a producción, permitiendo correcciones menores y preparación de metadatos.
    * Convención: `release/vX.Y.Z` (siguiendo Semantic Versioning).


* **hotfix branches:** Para correcciones críticas inmediatas en la rama main.
    * Convención: `hotfix/issue-description`.


### Mensajes de Commit (Conventional Commits)

Para mantener un historial de cambios legible y facilitar la generación automática de changelogs, se utilizará el estándar de Conventional Commits:


* **Estructura:** `<tipo>(<scope>): <descripción>`


* **Tipos permitidos:**
    * **feat:** Nueva funcionalidad.
    * **fix:** Corrección de un error.
    * **docs:** Cambios solo en la documentación.
    * **style:** Cambios de formato (espacios, puntos y comas) que no afectan el código.
    * **refactor:** Cambio de código que no corrige un error ni añade una función.


* **Ejemplos:**
    * `feat(ordering): add automated order validation policy`
    * `fix(auth): resolve token expiration on mobile devices`
    * `docs(interviews): update stakeholder interview records`
