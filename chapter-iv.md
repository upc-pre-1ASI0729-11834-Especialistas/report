# Capítulo IV: Product Design

## 4.1. Style Guidelines

En esta sección se presentan los estándares que definen el formato y el diseño de la solución, asegurando la calidad en su implementación.

### 4.1.1. General Style Guidelines

**Color**

La paleta de colores que hemos seleccionado para nuestra plataforma se compone principalmente de tonos azules, violetas y blancos, con acentos en verde y rojo para resaltar elementos clave. El azul transmite confianza, mientras que el violeta aporta un toque de innovación y creatividad. El blanco se utiliza para mantener una apariencia limpia y ordenada, facilitando la legibilidad y la navegación.

![Color Palette](assets/chapter-iv/color-palette.png)

**Tipografia**

La tipografía que hemos elegido para nuestra plataforma es "Inter", una fuente sans-serif bastante sobria y versátil que ofrece una excelente legibilidad tanto en pantallas
grandes como pequeñas.
Además, su diseño moderno y limpio complementa la estética general de nuestra marca, transmitiendo profesionalismo y confianza a nuestros clientes.

![Fonts](assets/chapter-iv/fonts.png)

**Branding**

Bautizamos a la aplicación como Safelab, un nombre que transmite seguridad para una plataforma que busca facilitar el monitoreo de laboratorios. El logo de Safelab se compone de un color azul claro que simboliza confianza y profesionalismo, reflejando la misión de nuestro producto de ofrecer una solución segura y confiable para el seguimiento de laboratorios.

![Safelab Logo](assets/chapter-iv/safelab-logo.png)

### 4.1.2. Web Style Guidelines

Esta sección define las pautas de diseño de la interfaz web de Safelab basadas en los mockups correspondientes.

**Layout**

El diseño de la interfaz web de Safelab se basa en una estructura de cuadrícula que organiza el contenido de manera clara y accesible. La página principal presenta un menú de navegación en la parte lateral izquierda, seguido de secciones claramente definidas para cada funcionalidad clave:
- Dashboard
- Laboratories
- Alerts
- History
- Settings

Cada sección está diseñada para ser intuitiva, con botones y enlaces destacados que guían al usuario a través de las diferentes acciones disponibles. El uso de espacios en blanco y una jerarquía visual clara contribuyen a una experiencia de usuario fluida y agradable.

**Responsive Design**

La interfaz web de Safelab está diseñada para ser completamente responsive, adaptándose a diferentes tamaños de pantalla y dispositivos. En dispositivos móviles, el menú lateral se transforma en un menú desplegable accesible desde un ícono de hamburguesa, mientras que el contenido se reorganiza para mantener la legibilidad y funcionalidad. En tabletas, el diseño se ajusta para aprovechar el espacio adicional sin perder la claridad visual. Esta adaptabilidad garantiza que los usuarios puedan acceder a todas las funcionalidades de Safelab de manera eficiente, independientemente del dispositivo que estén utilizando.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

**Landing Page**

La landing page de Safelab está diseñada para presentar de manera clara los beneficios y características principales de la plataforma.

La organización de la información sigue una estructura jerárquica que guía al usuario a través de un recorrido lógico, comenzando con una introducción impactante, seguida de secciones detalladas sobre las funcionalidades, testimonios de clientes y el pricing respectivo.

Cada sección está claramente diferenciada mediante el uso de encabezados, imágenes y llamados a la acción (CTAs) estratégicamente ubicados para fomentar la conversión.

**Web Application**

La aplicación web de Safelab se organiza para facilitar la interacción entre los usuarios y las funcionalidades clave de la plataforma.

La información se presenta de manera estructurada, con un menú de navegación lateral que permite acceder rápidamente a las diferentes secciones.

Cada sección está diseñada para ser intuitiva, con una disposición clara de los elementos y un enfoque en la usabilidad a través del uso de tarjetas e indicadores de métricas, asegurando que los usuarios puedan realizar sus tareas mediante un flujo de trabajo eficiente.

Los módulos en el flujo de trabajo incluyen:

- Dashboard: Proporciona una visión general del estado de los laboratorios, con gráficos y estadísticas clave.
- Laboratories: Permite a los usuarios gestionar y monitorear los laboratorios registrados, con opciones para agregar, editar o eliminar laboratorios.
- Alerts: Muestra las alertas generadas por el sistema, con detalles sobre cada alerta y opciones para marcar como leídas o resolverlas.
- History: Ofrece un historial detallado de las actividades y eventos relacionados con los laboratorios, permitiendo a los usuarios revisar acciones pasadas y generar reportes.
- Settings: Permite a los usuarios configurar sus preferencias, gestionar su cuenta y ajustar las notificaciones.

### 4.2.2. Labeling Systems

Las etiquetas que utilizaremos para la página serán diseñadas para ser claras, directas y fáciles de entender, enfocándose en la eficiencia y simplicidad para usuarios con distintos niveles de experiencia tecnológica.

**Principios generales**

- Se limita el uso de **2-3 palabras** por ítem.
- Se mantiene la **consistencia terminológica** en todas las pantallas.
- Las etiquetas son descriptivas y responden a acciones directas, estados o categorías claras.

Algunas de las etiquetas principales de nuestras secciones serán las siguientes:

**Dashboard de Laboratorios**
- `Tendencia de temperatura`
- `Indicadores clave`
- `Alertas recientes`
- `Ver Laboratorios`

**Detalle de Laboratorio**
- `Métricas en tiempo real`
- `Indicadores de status`
- `Programaciones activas`
- `Actividad reciente`

**Alertas**
- `Lista de alertas`
- `Detalle de alerta`
- `Barra de filtros`
- `Indicadores de prioridad`

**Historial**
- `Vistas de línea de tiempo de eventos`
- `Detalle de eventos`
- `Filtros de búsqueda`
- `Indicadores de tipo de evento`

### 4.2.3. SEO Tags and Meta Tag

**Landing Page**:
- Title (SEO Tag): Safelab | Smart Lab Management
- Description (Meta Tag): Optimize your lab management process with Safelab — a centralized platform for researchers and lab managers to record experiments, upload documents, and track progress.
- Keywords (Meta Tag): Lab management, Monitoring, System Alerts, Scientific workflow
- Author (Meta Tag): Safelab Team

**Web Application**:
- Title (SEO Tag): Safelab | Monitor Laboratories in Real Time
- Description (Meta Tag): Access your dashboard to monitor your laboratories, export reports, and program schedules.
- Keywords (Meta Tag): Lab management, Monitoring, System Alerts, Scientific workflow
- Author (Meta Tag): Safelab Team

### 4.2.4. Searching Systems

Para garantizar navegación fluida y centrada al servicio del usuario, vamos a implementar los siguiente estándares tanto para la Landing Page como para la Web Application:

- <u>Menú de navegación</u>:
    
    Utilizaremos la Navigation Bar, que contendrá enlaces visibles a las secciones y opciones más importantes de la Landing Page y Web Application respectivamente.

    De esta forma, los nuevos usuarios se informarán rápidamente y a los usuarios existentes les permitirán acceder a sus cuentas fácilmente.

- <u>Navegación Visual Guiada</u>:
    
    El contenido de la Landing Page estará  organizado en bloques visuales de las secciones determinadas en la barra principal, permitiendo al usuario desplazarse verticalmente para descubrir las funcionalidades de manera fluida.

    Por otro lado, la Web Application tendrá un menú lateral fijo que permitirá a los usuarios acceder rápidamente a las secciones principales, como el Dashboard, Laboratories, Alerts, History y Settings.

- <u>Responsive Design</u>:

    Ambos productos serán construidos para adaptarse al tipo de dispositivo del usuario.
    
    Por ejemplo, la resolución de la pagina estará optimizada según como sea redimensionada y tendrá compatibilidad tanto en dispositivos de escritorio como en portatiles.
    
    De esta forma, los usuarios realizarán sus tareas independientemente del dispositivo que utilicen.

### 4.2.5. Navigation Systems

**Landing Page**

Para la Landing Page de Safelab, implementaremos un sistema de navegación basado en una barra de navegación horizontal ubicada en la parte superior de la página. Esta barra de navegación incluirá enlaces a las secciones principales de la página, como Features, Pricing y Contact. Además, se incluirán botones de llamada a la acción (CTA o Call To Action) para que los usuarios sean redirigidos a la aplicación y puedan registrarse o iniciar sesión fácilmente.

**Web Application**

Para la plataforma de Safelab implementaremos un sistema de navegación basado en una barra lateral fija que permitirá a los usuarios acceder rápidamente a las secciones principales de la aplicación web, como el Dashboard, Laboratories, Alerts, History y Settings. Esta barra lateral estará diseñada para ser intuitiva y fácil de usar, con íconos claros y etiquetas descriptivas para cada sección.

Además, cada pantalla dentro de la aplicación web contará con una barra de filtros y opciones de navegación adicionales que permitirán a los usuarios refinar su búsqueda y acceder a funcionalidades específicas dentro de cada sección. Por ejemplo, en la sección de Laboratories, los usuarios podrán filtrar por tipo de laboratorio, estado o fecha de creación, mientras que en la sección de Alerts podrán filtrar por prioridad o tipo de alerta.

---
## 4.3. Landing Page UI Design
Para el diseño de la interfaz de la Landing Page de Safelab, el equipo ha traducido las necesidades de monitoreo crítico en una experiencia visual que transmite seguridad, limpieza y precisión.


La arquitectura de información se estructuró siguiendo un modelo de **"AIDA" (Atención, Interés, Deseo y Acción)**, asegurando que los responsables de laboratorios encuentren rápidamente la propuesta de valor: la prevención de incidentes mediante inteligencia analítica. Se priorizó una navegación vertical fluida, donde cada sección refuerza la confianza del usuario antes de llegar a los planes de suscripción.

### 4.3.1. Landing Page Wireframe

Los wireframes de Safelab fueron diseñados con un enfoque **Mobile-First**, garantizando que la jerarquía de contenido sea clara tanto en navegadores de escritorio como en dispositivos móviles.


* **Principios de Diseño:** Se aplicó el principio de proximidad para agrupar las funcionalidades clave (Dashboard, Alertas, Historial) y el uso de espacios en blanco (*negative space*) para reducir la carga cognitiva del usuario.


* **Diseño Inclusivo:** La disposición de los elementos sigue un orden lógico de lectura (patrón en F), facilitando la accesibilidad para lectores de pantalla. Los botones de acción (CTAs) como "Solicitar Demo" cuentan con un tamaño táctil adecuado para dispositivos móviles.


* **Arquitectura de Información:** Se utilizó una estructura de cuadrícula (*grid system*) de 12 columnas para Desktop y 4 para Mobile, permitiendo que bloques como "El Problema" y "La Solución" se apilen de forma coherente, manteniendo siempre la visibilidad de los beneficios principales.

![Landing Page - Wireframe](assets/chapter-iv/landingwireframe.png)

### 4.3.2. Landing Page Mock-up

El paso al Mock-up integra el *Design System* de Safelab, aplicando la paleta de colores azul y violeta para evocar profesionalismo tecnológico.


* **Elementos de Diseño:** Se incorporaron iconografías personalizadas para cada funcionalidad, utilizando estilos lineales que mantienen la estética moderna. Las tarjetas de "Planes de Laboratorio" utilizan sombras sutiles (*box-shadows*) para generar profundidad y destacar el plan "Pro" como la opción recomendada.


* **Identidad Visual y Branding:** El logotipo de Safelab se ubica estratégicamente en el *header* persistente. Se seleccionó la tipografía **Inter** por su alta legibilidad en entornos técnicos, asegurando que las métricas y precios sean fáciles de leer.


* **Continuidad de Experiencia:** En la versión Mobile, el menú de navegación se sintetiza en un componente de "hamburguesa", mientras que los testimonios de los especialistas se presentan en un formato de carrusel optimizado para gestos táctiles. El uso de imágenes de alta fidelidad para el dashboard dentro del mock-up permite al usuario previsualizar la robustez de la herramienta antes de la conversión.

![Landing Page - Mockup](assets/chapter-iv/landingmockup.png)

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

**Login**
- Descripción: Esta pantalla muestra el formulario para que el usuario ingrese sus credenciales y acceda la pantalla de inicio de la aplicación.
![Web Application - Wireframe 1](assets/chapter-iv/wireframe-1.png)

**Dashboard**
- Descripción: En esta pantalla se pueden visualizar las métricas más importantes de los sistemas de los laboratorios, como la temperatura, ventilación, detección de elementos extraños, entre otros. Esta información se muestra en gráficos y pequeñas listas para facilitar la comprensión de la información.
![Web Application - Wireframe 2](assets/chapter-iv/wireframe-2.png)

**Laboratorios**
- Descripción: En esta pantalla se optó por una grilla de tarjetas para visualizar los laboratorios registrados en el sistema, con información resumida de cada uno, como temperatura, ubicación, entre otros.
![Web Application - Wireframe 3](assets/chapter-iv/wireframe-3.png)

**Detalles de Laboratorio**
- Descripción: En esta pantalla se muestra información detallada de cada laboratorio, con gráficos en tiempo real de las métricas más importantes, como temperatura, ventilación, entre otros. Además, se muestran los indicadores de status del laboratorio, programaciones activas y actividad reciente.
![Web Application - Wireframe 4](assets/chapter-iv/wireframe-4.png)

**Alertas**
- Descripción: En esta pantalla se muestran las alertas generadas por el sistema. Para mostrarlas, se optó por una columna de tarjetas, donde cada tarjeta representa una alerta, con información resumida como el mensaje de la alerta, su prioridad, entre otros. Para ver la información detallada de la alerta, emerge un panel lateral derecho al hacer clic sobre ella. Además, se incluyen filtros para facilitar la búsqueda de alertas específicas.
![Web Application - Wireframe 5](assets/chapter-iv/wireframe-5.png)

**Historial**
- Descripción: En esta pantalla se muestra el historial de eventos relacionados con los laboratorios. Para mostrar esta información, se optó por una vista de línea de tiempo, donde cada evento se ordena de forma cronológica, con información resumida del evento. Al hacer clic sobre un evento, emerge un panel lateral derecho con la información detallada del evento. Además, se incluyen filtros para facilitar la búsqueda de eventos específicos.
![Web Application - Wireframe 6](assets/chapter-iv/wireframe-6.png)

**Nuevo Laboratorio**
- Descripción: En esta pantalla se muestra un formulario para registrar un nuevo laboratorio en el sistema. El formulario se divide en secciones para facilitar su llenado, como información general del laboratorio, sistemas y sensores, entre otros.
![Web Application - Wireframe 7](assets/chapter-iv/wireframe-7.png)

### 4.4.2. Web Applications Wireflow Diagrams

### **Wireflow 1**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo registrar un nuevo laboratorio en el sistema. Para ello, debo llenar la información del laboratorio y los detalles de sus sistemas y sensores.
![wireflow 1](assets/chapter-iv/wireflow-1.png)

### **Wireflow 2**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo visualizar la información detallada de un laboratorio existente.
![wireflow 2](assets/chapter-iv/wireflow-2.png)

### **Wireflow 3**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo revisar las alertas de alta prioridad generadas por el sistema para tomar acciones correctivas. Para ello, debo usar los filtros disponibles.
![wireflow 3](assets/chapter-iv/wireflow-3.png)

### 4.4.3. Web Applications Mock-ups

**Login**
- Objetivo: Permitir al usuario ingresar sus credenciales y acceder a la aplicación.
![Web Application - mockup 1](assets/chapter-iv/mockup-1.png)

**Dashboard**
- Objetivo: Mostrar las métricas más importantes de los sistemas de los laboratorios.
![Web Application - mockup 2](assets/chapter-iv/mockup-2.png)

**Laboratorios**
- Objetivo: Visualizar los laboratorios existentes y registrados en el sistema. Facilitar la búsqueda mediante filtros y presentación de información resumida de cada laboratorio.
![Web Application - mockup 3](assets/chapter-iv/mockup-3.png)

**Detalles de Laboratorio**
- Objetivo: Mostrar la información detallada de de los sistemas de mantenimiento de cada laboratorio.
Se muestra la actividad reciente del laboratorio, programaciones activas y los indicadores de status del laboratorio.
![Web Application - mockup 4](assets/chapter-iv/mockup-4.png)

**Alertas**
- Objetivo: Mostrar las alertas generadas por el sistema y permitir su gestión. Para resolver las alertas se muestra información detallada de cada alerta, como el mensaje, su prioridad, entre otros. Además, se incluyen filtros para facilitar la búsqueda de alertas específicas.
![Web Application - mockup 5](assets/chapter-iv/mockup-5.png)

**Historial**
- Objetivo: Mostrar el historial de eventos relacionados con los laboratorios. Por defecto, se muestra la información en una vista de línea de tiempo, donde cada evento se ordena de forma cronológica, con información resumida del evento.
![Web Application - mockup 6](assets/chapter-iv/mockup-6.png)

**Nuevo Laboratorio**
- Descripción: En esta pantalla se muestra un formulario para registrar un nuevo laboratorio en el sistema. El formulario se divide en secciones para facilitar su llenado, como información general del laboratorio, sistemas y sensores, entre otros.
![Web Application - mockup 7](assets/chapter-iv/mockup-7.png)

### 4.4.4. Web Applications User Flow Diagrams

**Userflow 1**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo registrar un nuevo laboratorio en el sistema. Para ello, debo llenar la información del laboratorio y los detalles de sus sistemas y sensores.
- Happy Paths:
    - El sistema muestra un mensaje indicando que el pedido fue creado exitosamente.
    - El nuevo laboratorio se muestra en la sección de laboratorios registrados.
- Unhappy Paths:
    - El sistema muestra un mensaje de error indicando que el pedido no pudo ser creado.

![userflow 1](assets/chapter-iv/userflow-1.png)

**Userflow 2**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo visualizar la información detallada de un laboratorio existente.
- Happy Paths:
    - El sistema muestra la información detallada del laboratorio seleccionado.
- Unhappy Paths:
    - El sistema muestra un pop-up que indica que no se pudo cargar la información del laboratorio.

![userflow 2](assets/chapter-iv/userflow-2.png)

**Userflow 3**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo revisar las alertas de alta prioridad generadas por el sistema para tomar acciones correctivas. Para ello, debo usar los filtros disponibles.
- Happy Paths:
    - El sistema muestra las alertas filtradas por alta prioridad.
- Unhappy Paths:
    - El sistema muestra un pop-up que indica que no se pudieron cargar las alertas filtradas.

![userflow 3](assets/chapter-iv/userflow-3.png)

## 4.5. Web Applications Prototyping

**Desktop Web Application**
![desktop-web](assets/chapter-iv/evidence-desktop-prototype.png)

Link:

**Mobile Web Application**
![mobile-web](assets/chapter-iv/evidence-mobile-prototype.png)

Link:

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

En esta fase, el equipo realizó una inmersión técnica de nivel detallado para refinar el flujo de trabajo de **SafeLab**. A diferencia de la etapa anterior, el *Design-Level Event Storming* permitió identificar no solo qué sucede en el sistema (**Eventos**), sino también quién inicia la acción (**Actores**), qué intención tienen (**Comandos**) y qué reglas rigen el comportamiento del software (**Políticas**).


Durante una sesión de diseño enfocada, se estructuraron los elementos siguiendo la lógica de los sub-dominios críticos para una plataforma SaaS de monitoreo clínico. El resultado es un modelo que integra la captura de datos de sensores, la gestión de activos hospitalarios y la automatización inteligente, garantizando que cada interacción esté alineada con el lenguaje ubicuo y los objetivos de "Desperdicio Cero" de la startup.

![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext.jpg)

---


### Explicación de los Bounded Contexts Identificados

A continuación, se detallan los cinco contextos delimitados que componen la arquitectura de la solución:


#### 1. IoT Telemetry & Environment Monitoring
Este contexto actúa como la capa de ingesta de datos. Se encarga de la comunicación directa con el hardware (sensores) y la normalización de las métricas ambientales. Su responsabilidad es garantizar que cada lectura de temperatura o CO2 sea capturada y validada antes de ser procesada por el resto del sistema, gestionando además la salud de la conexión de los dispositivos.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext11.jpg)


#### 2. Lab Asset & Infrastructure Management
Orientado a la gestión de recursos físicos, este contexto administra el ciclo de vida de las refrigeradoras, congeladores y sistemas de ventilación (HVAC). Su enfoque principal es el mantenimiento preventivo y la organización jerárquica del laboratorio (edificios, pisos y áreas), asegurando que la infraestructura física sea apta para el almacenamiento bioclínico.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext2.jpg)


#### 3. Intelligent Alerting & Incident Response
Representa el cerebro reactivo de la plataforma. Analiza las anomalías detectadas en la telemetría para clasificar incidentes según su gravedad (*Critical/Warning*). Gestiona la omnicanalidad de las notificaciones hacia el personal de turno y rastrea las acciones de mitigación tomadas por los biólogos, cerrando la brecha entre la falla técnica y la intervención humana.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext3.jpg)


#### 4. Operational Compliance & Activity Logging
Este contexto de soporte garantiza la integridad legal de la operación. Registra de forma inmutable cada evento relevante del sistema, desde calibraciones de sensores hasta resoluciones de alertas. Su función principal es la generación automatizada de reportes de cumplimiento (*Compliance Reports*) que permitan al laboratorio superar auditorías normativas como la ISO 15189.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext4.jpg)

#### 5. Smart Automation & Scheduling
Es el componente proactivo que permite a SafeLab ejecutar acciones correctivas automáticas. Gestiona horarios de funcionamiento y reglas lógicas (por ejemplo, activación de ventilación ante picos de CO2). Este contexto permite que el sistema actúe sobre los actuadores físicos, reduciendo la dependencia de la intervención manual constante.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext5.jpg)

### 4.6.2. Software Architecture Context Diagram

### 4.6.3. Software Architecture Container Diagrams

### 4.6.4. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

El diagrama de clases de SafeLab representa la estructura estática del sistema, detallando las entidades fundamentales, sus atributos, comportamientos (métodos) y las relaciones que permiten la lógica de negocio. El diseño se ha organizado siguiendo los límites de los *Bounded Contexts* identificados en el *Event Storming*, asegurando que la implementación técnica respete el lenguaje ubicuo del dominio.


Se destacan las jerarquías de monitoreo ($Laboratory \rightarrow Unidad \rightarrow Sensor$) y el desacoplamiento entre la captura de datos y la respuesta ante incidentes, permitiendo que el sistema sea escalable y mantenible.

![Database Diagram](assets/chapter-iv/UML.png)

---

### 4.7.2. Class Dictionary

| Clase | Descripción | Atributos Clave |
| :--- | :--- | :--- |
| **Laboratory** | Representa el entorno físico de nivel superior donde se agrupan los activos. | `id`, `name`, `location`, `safetyLevel` |
| **ColdStorageUnit** | Equipos de refrigeración o HVAC monitoreados por el sistema. | `id`, `serialNumber`, `nextMaintenanceDate` |
| **Sensor** | Dispositivos IoT encargados de la captura física de parámetros ambientales. | `id`, `sensorType`, `status`, `batteryLevel` |
| **TelemetryReading** | Registro individual de una métrica capturada en un momento específico. | `id`, `value`, `unit`, `timestamp` |
| **Alert** | Notificación generada automáticamente cuando una lectura viola un umbral. | `id`, `severity`, `status`, `createdAt` |
| **Incident** | Registro detallado de la causa y resolución de una alerta crítica. | `id`, `rootCause`, `mitigationAction` |
| **User** | Actores del sistema con roles definidos (Biólogo, Coordinador). | `id`, `name`, `role`, `email` |
| **ComplianceReport** | Documento legal generado para auditorías de cumplimiento normativo. | `id`, `generatedAt`, `digitalSignature` |
| **AuditLog** | Registro inmutable de toda actividad realizada en la plataforma. | `id`, `actionType`, `timestamp`, `hashValue` |
| **AutomationRule** | Lógica condicional definida para activar actuadores automáticamente. | `id`, `condition`, `thresholdValue` |
| **Schedule** | Programación horaria para el funcionamiento de equipos de ventilación. | `id`, `startTime`, `endTime`, `daysOfWeek` |

## 4.8. Database Design

### 4.8.1. Database Diagram
### 4.8. Database Design

El diseño de la base de datos de **SafeLab** ha sido normalizado para garantizar la integridad referencial y la eficiencia en la consulta de grandes volúmenes de telemetría. A diferencia del diagrama de clases, este modelo se enfoca en la persistencia de datos mediante el uso de Claves Primarias (**PK**) y Claves Foráneas (**FK**).


El modelo está diseñado para soportar la trazabilidad exigida por la norma **ISO 15189**, conectando cada lectura de sensor con su respectivo equipo y, en caso de anomalías, vinculando la alerta directamente con el registro de intervención del usuario. Los registros de auditoría (`audit_logs`) incluyen campos de hash para asegurar que la historia de operaciones no sea alterada, cumpliendo con los estándares de seguridad bioclínica.


#### Puntos clave del diseño:

* **Escalabilidad:** Las lecturas de telemetría están indexadas por tiempo y sensor para permitir búsquedas rápidas en grandes conjuntos de datos.


* **Integridad:** Las relaciones foráneas aseguran que no existan alertas huérfanas sin una lectura de origen claramente identificada.


* **Seguridad:** Los perfiles de usuario y logs están centralizados para facilitar las auditorías de acceso y el cumplimiento normativo.
![Database Diagram](assets/chapter-iv/BaseDatosDiagrama.png)
