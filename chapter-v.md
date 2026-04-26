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

## 5.1.3. Source Code Style Guide & Conventions

Para garantizar la calidad, mantenibilidad y legibilidad del código de SafeLab, el equipo ha adoptado las siguientes convenciones de estilo. Siguiendo los estándares de la industria y las exigencias del curso, todo el código fuente (nombres de variables, clases, métodos y comentarios) se escribirá estrictamente en inglés.


#### HTML & CSS
Se seguirá la **Google HTML/CSS Style Guide**.


* **HTML:** Se utilizará una estructura semántica (uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`). La indentación será de 2 espacios. Los atributos de los elementos deben estar en minúsculas y los valores entre comillas dobles.


* **CSS:** Se utilizará la metodología **BEM (Block Element Modifier)** para el nombramiento de clases, facilitando el mantenimiento de los componentes de la interfaz.


* **Naming Convention:** Se aplicará `kebab-case` para IDs y nombres de clases (ej. `sensor-card`, `alert-status-critical`).


* **Colors & Units:** Se priorizará el uso de variables CSS para la paleta de colores corporativa y unidades relativas (`rem`, `em`, `%`) para asegurar que el diseño sea adaptable (responsive).


#### JavaScript & TypeScript
Se seguirá la **Google TypeScript Style Guide**.


* **Variables y Funciones:** Se utilizará `camelCase` (ej. `getSensorReading`, `updateLaboratoryStatus`). Los nombres deben ser semánticos; se prefiere `isTemperatureHigh` sobre `tempCheck`.


* **Clases e Interfaces:** Se utilizará `PascalCase` (ej. `EnvironmentMonitor`, `ISensorData`). Las interfaces llevarán el prefijo "I" para distinguirlas claramente.


* **Estructura:** Se utilizará `const` por defecto y `let` solo si el valor requiere reasignación. Se evitará el uso de `var`. Se implementarán funciones de flecha (**Arrow Functions**) para una sintaxis más limpia.


* **Asincronía:** Se utilizará exclusivamente `async/await` para el manejo de peticiones al API, evitando el anidamiento de promesas.


#### Java (Backend - Spring Boot)
Se seguirá la **Google Java Style Guide** y las convenciones oficiales de **Spring Framework**.


* **Naming:** `PascalCase` para clases (ej. `LaboratoryController`, `SensorService`) y `camelCase` para métodos y variables (ej. `calculateAverageHumidity`).


* **Arquitectura:** Se respetará estrictamente el patrón por capas: Controller, Service, Repository, Entity y DTO (Data Transfer Object).


* **API REST:** Los endpoints utilizarán sustantivos en plural y minúsculas (ej. `/api/v1/laboratories`, `/api/v1/sensors/{id}/logs`). Se aplicarán los verbos HTTP de forma correcta (GET para consulta, POST para creación, etc.).


* **Annotations:** Se emplearán anotaciones de **Lombok** (como `@Getter`, `@Setter`, `@NoArgsConstructor`) para mantener el código limpio y libre de boilerplate.


#### Gherkin
Para las especificaciones de pruebas de aceptación, se aplicarán las **Gherkin Conventions**.


* **Idioma:** Se redactarán en inglés para mantener la consistencia con el código fuente y las mejores prácticas de desarrollo open source.


* **Estructura:** Uso de palabras clave: **Scenario:**, **Given**, **When**, **Then**, **And**.


* **Claridad:** Los pasos deben describir el comportamiento del negocio.


* **Ejemplo:**
  * `Given the temperature sensor "T-01" exceeds 30°C`
  * `When the system processes the signal`
  * `Then a critical alert should be generated`

## 5.1.4. Software Deployment Configuration

En esta sección se especifica la configuración y los pasos necesarios para el despliegue de cada uno de los productos que conforman la solución SafeLab. Se ha adoptado un enfoque de despliegue continuo (**Continuous Deployment**) para asegurar que los cambios validados en los repositorios de GitHub se reflejen automáticamente en los entornos de producción.


| Producto | Entorno de Despliegue | Pipeline / Herramienta |
| :--- | :--- | :--- |
| **Landing Page** | Vercel / GitHub Pages | GitHub Actions |
| **Web Services (API)** | Azure App Service / Render | Docker / Maven Build |
| **Web Application** | Firebase Hosting / Vercel | Angular CLI / GitHub Actions |


#### Configuración por Componente:

**1. Landing Page:**
* **Tecnología:** HTML5, CSS3 (SASS) y JavaScript.


* **Proceso:** El despliegue se activa automáticamente al realizar un `merge` en la rama `main`. Se utiliza **Vercel** por su optimización para sitios estáticos y soporte nativo para HTTPS, garantizando un tiempo de carga mínimo para los usuarios interesados en el modelo de negocio.


**2. Web Services (Backend):**
* **Tecnología:** Java 17 con Spring Boot.


* **Proceso:** Se utiliza **Maven** para la gestión de dependencias y construcción del archivo ejecutable (JAR). La aplicación se despliega en **Azure App Service**, configurando una instancia de base de datos **Azure Database for MySQL**. Se han configurado variables de entorno (`ENVIRONMENT_VARIABLES`) para proteger las credenciales de la base de datos y las llaves del servicio externo de monitoreo.


* **Documentación:** Una vez desplegado, el contrato de la API es accesible a través de **Swagger UI** para facilitar la integración con el equipo de frontend.


**3. Frontend Web Application:**
* **Tecnología:** Angular Framework.


* **Proceso:** Se ejecuta el comando `ng build --configuration production` para generar los archivos de distribución optimizados. Estos archivos son cargados en **Firebase Hosting**, aprovechando su red de entrega de contenidos (CDN) para asegurar que el Dashboard de monitoreo en tiempo real sea fluido y responsivo en cualquier dispositivo.


#### Consideraciones de Seguridad y Dominio:

* **SSL/TLS:** Todos los productos cuentan con certificados de seguridad para garantizar que la transmisión de datos entre los sensores de laboratorio y la aplicación sea cifrada.


* **Integración:** La Web Application está configurada para consumir los servicios del RESTful API mediante el intercambio de recursos de origen cruzado (**CORS**), permitiendo únicamente peticiones desde los dominios autorizados de la solución.