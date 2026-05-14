<div align="center">
    <img src="assets/chapter-i/logo-upc.png" alt="Logo de la Universidad"/>    
    <h1>Informe de Trabajo Final</h1>
    <p><strong>Universidad:</strong> Universidad Peruana de Ciencias Aplicadas</p>
    <p><strong>Carrera:</strong> Ingeniería de Software</p>
    <p><strong>Ciclo:</strong> 2026-10</p>
    <p><strong>Código del Curso:</strong> 1ASI0729</p>
    <p><strong>Nombre del Curso:</strong> Desarrollo de Aplicaciones Open Source</p>
    <p><strong>Sección:</strong> 2610</p>
    <p><strong>Profesor:</strong> Alberto Wilmer Sánchez Seña</p>
    <p><strong>Startup:</strong> Safelab</p>
    <p><strong>Nombre del Producto:</strong> Safelab</p>
</div>

<h3 align="center">Relación de Integrantes:</h3>

<div align="center">
    <table>
        <tr>
            <th><strong>Código</strong></th>
            <th><strong>Apellidos y Nombres</strong></th>
        </tr>
        <tr>
            <td>U201817507</td>
            <td>Manuel Angel Sanchez Arenas</td>
        </tr>
        <tr>
            <td>U201919096</td>
            <td>Jean Niels Arizabal Condori</td>
        </tr>
        <tr>
            <td>U20241B761</td>
            <td>Esteban Eduardo Chavez Bardales</td>
        </tr>
        <tr>
            <td>U202520310</td>
            <td>Jhon Jordy Jaramillo Mayta</td>
        </tr>
    </table>
</div>

<p align="center"><strong>Mes y Año:</strong> Abril 2025</p>

## Registro de Versiones del Informe

<table border="1" cellpadding="6" cellspacing="0">
    <thead>
        <tr>
            <th>Versión</th>
            <th>Fecha</th>
            <th>Autor(es)</th>
            <th>Descripción de Modificación</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <td><strong>1.0</strong></td>
          <td>2026-04-25</td>
          <td>
              - Sanchez Arenas, Manuel Angel<br>
              - Arizabal Condori, Jean Niels<br>
              - Chavez Bardales, Esteban Eduardo<br>
              - Jaramillo Mayta, Jhon Jordy
          </td>
          <td>
              <strong>Se incluye:</strong><br>
              -Carátula, Registro de versiones, Student Outcome y Contenido de Informe<br>
              -Capitulo I: Introducción<br>
              -Capitulo II: Requirements Elicitation & Analysis<br>
              -Capitulo III: Especificación de Requerimientos<br>
              -Capitulo IV: Diseño del Producto<br>
              -Capitulo V: Implementación, Validación y Despliegue del Producto<br>
          </td>
        </tr>
        <tr>
          <td><strong>2.0</strong></td>
          <td>2026-05-14</td>
          <td>
              - Sanchez Arenas, Manuel Angel<br>
              - Arizabal Condori, Jean Niels<br>
              - Chavez Bardales, Esteban Eduardo<br>
              - Jaramillo Mayta, Jhon Jordy
          </td>
          <td>
              <strong>Se incluye:</strong><br>
              -Corrección de Capitulo III: User Stories<br>
              -Capitulo V: Documentación del Sprint 2 (Sprint Backlog, Deployment Evidence, Software Documentation)<br>
          </td>
        </tr>
    </tbody>
</table>

## Project Report Collaboration Insights

**URL del Repositorio:**  
[Repositorio de GitHub](https://github.com/upc-pre-1ASI0729-11834-Especialistas/report)

Este informe ha sido desarrollado de forma colaborativa mediante GitHub, empleando GitFlow y Conventional Commits. Cada miembro del equipo ha contribuido con commits y ramas individuales durante el desarrollo del proyecto.

**Participación del equipo:**

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Integrante</th>
      <th>Usuario GitHub</th>
      <th>Aportaciones destacadas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Manuel Sanchez</td>
      <td>@manuels7a</td>
      <td>Desarrollo de secciones del capítulo V relacionadas a la documentación del Sprint 2 (Desarollo y despliegue de la aplicación web y fake API)</td>
    </tr>
    <tr>
      <td>Jean Niels Arizabal Condori</td>
      <td>@JeanArizabal</td>
      <td>Coordinación de la estructura de la fake API a usar en la aplicación web</td>
    </tr>
    <tr>
      <td>Esteban Eduardo Chavez Bardales</td>
      <td>@ECEB0704</td>
      <td>Correcciones de las User Stories y Rediseño de los Event Storming para mejorar la calidad de los requerimientos</td>
    </tr>
    <tr>
      <td>Jhon Jordy Jaramillo Mayta</td>
      <td>@Marklnz1</td>
      <td>Desarrollo del Bounded Context Telemetry y Labs. Correcciones de la carpeta Shared.</td>
    </tr>
  </tbody>
</table>

## Contenido

- [Carátula](#carátula)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
  - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 User Stories](#31-user-stories)
  - [3.2 Impact Mapping](#32-impact-mapping)
  - [3.3 Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
  - [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation System](#425-navigation-system)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
  - [4.8 Database Design](#48-database-design)
    - [4.8.1 Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1 Sprint 1](#521-sprint-1)
      - [5.2.1.1 Sprint Planning](#5211-sprint-planning-1)
      - [5.2.1.2 Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3 Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4 Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5 Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6 Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7 Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8 Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2 Sprint 2](#522-sprint-2)
      - [5.2.2.1 Sprint Planning](#5221-sprint-planning-2)
      - [5.2.2.2 Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3 Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4 Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5 Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6 Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7 Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8 Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
- [Anexos](#anexos)
- [Bibliografia](#bibliografia)

## Student Outcome

> Criterio: El estudiante comunica resultados y proceso de ingeniería aplicado para el ciclo de desarrollo y despliegue de una solución web distribuida bajo una arquitectura orientada a servicios, que satisface requisitos para empresas o público en general, con un enfoque innovador e inclusivo, desplegada sobre plataformas Server Side o Cloud, haciendo uso de tecnologías open-source basadas en el lenguaje de programación Java para la lógica de lado servidor y tecnologías open-source para los componentes de la aplicación.

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Criterio Específico</th>
      <th>Acciones Realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Comunica oralmente con efectividad a diferentes rangos de audiencia</strong></td>
      <td>
        <strong>Manuel Sanchez</strong><br>
        AV1: Expongo con efectividad la propuestas del diseño de la aplicación.<br>
        AV2: A través de las reuniones de equipo, comparto las ideas y avances del proyecto.<br><br>
        <strong>Jean Arizabal</strong><br>
        AV1: Presento la propuesta de solución de forma detallada considerando los antecedentes, el perfil de la solución, el análisis competitivo y el needfinding.<br>
        AV2: Comunico a mi equipo mis ideas para el desarrollo del proyecto y para poder trabajar sin conflictos <br><br>
        <strong>Esteban Chavez</strong><br>
        AV1: Explico detalladamente el event storming, desde el inicio hasta el final, los diagramas, tanto de clase como de base de datos y el diseño de la landing page.<br>
        AV2: Explico a mis compañeros las modificaciones y correcciones de los requisitos del proyecto para ajustar el desarrollo de la aplicación.<br><br>
        <strong>Jhon Jaramillo</strong><br>
        AV1: Expongo y sustento las decisiones arquitectónicas del proyecto utilizando los diagramas C4, además de presentar el diseño, flujo y propósito de la landing page al equipo.<br>
        AV2: Consulto mis dudas con mis compañeros y busco orientación para resolver los desafíos del proyecto.<br><br>
      </td>
      <td>
        <strong>AV1:</strong> Para poder comunicar efectivamente nuestras ideas fue necesario trabajar en nuestra capacidad de expresión y en la claridad de nuestra comunicación.<br>
        <strong>AV2:</strong> Para poder entregar un producto alineado a los requisitos fue necesario comprender las modificaciones de los requisitos. Para ello, la comunicación entre los miembros del equipo fue fundamental.<br>
      </td>
    </tr>
    <tr>
      <td><strong>Comunica por escrito con efectividad a diferentes rangos de audiencia</strong></td>
      <td>
        <strong>Manuel Sanchez</strong><br>
        AV1: Redacto documentos claros y objetivos sobre las historias de usuario de Safelab.<br>
        AV2: Redacto la documentación técnica del sprint del proyecto a través de estándares apropiados para su correcta lectura.<br><br>
        <strong>Jean Arizabal</strong><br>
        AV1: Redacto con detenimiento detalles sobre la startup, el perfil de la solución, el análisis competitivo y el needfinding.<br>
        AV2: Redacto propuestas de corrección para mejorar la calidad del producto. Hago correcciones puntutales para alinear el producto con los requisitos.<br><br>
        <strong>Esteban Chavez</strong><br>
        AV1: Escribo claramente la informacion necesaria que cada diagrama, e imagen necesita, de forma sencilla y tecnica, demostrando conocimientos especificos para las diferentes secciones.<br>
        AV2: Recibo el feeback y coordino las correcciones necesarias siguiendo los estándares del informe.<br><br>
        <strong>Jhon Jaramillo</strong><br>
        AV1: Redacto historias de usuario claras y detalladas para estructurar la landing page, y documento la arquitectura del sistema elaborando diagramas de contexto y contenedores bajo el modelo C4.<br>
        AV2: Documento las decisiones en las reuniones del equipo para asegurar la alineación y el progreso del proyecto.<br><br>
      </td>
      <td>
        <strong>AV1: </strong>Para poder comunicar efectivamente nuestras ideas en el reporte fue necesario tener un bien planteada nuestra propuesta.<br>
        <strong>AV2: </strong>A través del feedback del informe, logramos optimizar lac comunicación de la propuesta de nuestro producto en el documento.<br>
      </td>
    </tr>
  </tbody>  
</table>

---

# **Capítulo I: Introducción**

## **1.1. Startup Profile**

### **1.1.1. Descripción de la Startup**

SafeLab es una startup tecnológica dedicada a la transformación digital y la seguridad operativa del sector bioclínico y farmacéutico. Nuestra organización nace de la necesidad de resolver una vulnerabilidad crítica en la industria de la salud: la incertidumbre y las ineficiencias asociadas al almacenamiento de materiales biológicos altamente sensibles. Como empresa emergente, canalizamos todos nuestros esfuerzos técnicos y estratégicos en nuestro primer gran despliegue en el mercado: el desarrollo de un ecosistema digital innovador que garantice la preservación absoluta de la cadena de frío clínica. En SafeLab, no solo desarrollamos software; construimos infraestructuras de confianza que blindan la calidad del diagnóstico y la sostenibilidad de los recursos médicos.

El núcleo de nuestra propuesta de valor es una plataforma integral de monitoreo ambiental automatizado, diseñada específicamente para las rigurosas exigencias de laboratorios, hospitales y redes de farmacias. A través de la integración de dispositivos de hardware con un dashboard centralizado, el producto de SafeLab sustituye la vulnerable supervisión humana intermitente por una vigilancia continua y predictiva. Nuestra solución permite a los profesionales de la salud configurar reglas precisas de alerta y mitigación automática, previniendo activamente la degradación química de reactivos y vacunas. Nuestra misión es empoderar al personal clínico, eliminando el desgaste asociado a las tareas mecánicas de documentación y permitiéndoles enfocar su tiempo y experiencia exclusivamente en la gestión analítica y el cuidado del paciente.

Desde una perspectiva operativa y comercial, SafeLab estructura sus servicios bajo un modelo B2B (Business-to-Business) sustentado en una arquitectura SaaS (Software as a Service). Este enfoque nos permite dotar a las instituciones de salud de una solución altamente escalable y de rápida implementación, donde una suscripción corporativa garantiza el acceso ininterrumpido a herramientas de auditoría en tiempo real, reportes automatizados para el cumplimiento normativo y una inmutabilidad total en la retención de datos históricos. La visión a largo plazo de SafeLab es convertirse en el estándar regional para la gestión inteligente de inventarios biológicos, impulsando a las instituciones de salud hacia un modelo operativo guiado por la innovación pragmática y un compromiso innegociable con la cultura del "Desperdicio Cero".

### **1.1.2. Perfiles de integrantes del equipo**

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Foto</th>
      <th>Nombre completo</th>
      <th>Código</th>
      <th>Carrera</th>
      <th>Habilidades técnicas y rol</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><img src="assets/chapter-i/foto-manuel.png" alt="Manuel Sanchez" width="80"></td>
      <td>Manuel Sanchez</td>
      <td>u201817507</td>
      <td>Ingeniería de Software</td>
      <td>Desarrollo Fullstack: ASP.NetCORE MVC con Razor. Java básico. React.js</td>
    </tr>
    <tr>
      <td><img src="assets/chapter-i/foto-jean.png" alt="Jean Arizabal" width="80"></td>
      <td>Jean Arizabal</td>
      <td>U201919096</td>
      <td>Ingeniería de Software</td>
      <td>Desarrollo backend: node.js ASP.net</td>
    </tr>
    <tr>
      <td><img src="assets/chapter-i/foto-esteban.png" alt="Esteban Mendoza" width="80"></td>
      <td>Esteban Chavez</td>
      <td>U20241B761</td>
      <td>Ingeniería de Software</td>
      <td>Conocimientos y habilidades: C++, html, css, java. Responsable, creativa, y con diferentes conocimientos para el curso. Me destaco por mi creatividad e innovación.</td>
    </tr>
    <tr>
      <td><img src="assets/chapter-i/foto-jhon.png" alt="Jhon Jaramillo" width="80"></td>
      <td>Jhon Jaramillo</td>
      <td>U202520310</td>
      <td>Ingeniería de Software</td>
      <td>Habilidades técnicas y rol: Desarrollo FullStack</td>
    </tr>
  </tbody>
</table>

## **1.2. Solution Profile**

### **1.2.1 Antecedentes y Problemática**

La gestión de la cadena de frío en entornos bioclínicos no es únicamente un desafío logístico, sino un pilar crítico para la seguridad del paciente. Cuando los reactivos de diagnóstico, muestras biológicas y vacunas se exponen a excursiones térmicas (fluctuaciones fuera de los rangos normativos de 2 °C a 8 °C), sufren alteraciones moleculares que comprometen drásticamente su eficacia y estabilidad (Kumru et al., 2014). Un reactivo degradado térmicamente que sea utilizado en pruebas de laboratorio puede generar falsos negativos o alterar métricas diagnósticas, representando un riesgo clínico inminente que afecta directamente las decisiones médicas y la salud de los pacientes.

En segundo plano, esta vulnerabilidad operativa se traduce en un impacto financiero severo para las instituciones de salud. La Organización Mundial de la Salud (OMS, 2020) señala que las deficiencias en el control de temperatura obligan al descarte preventivo de lotes enteros de productos biológicos de alto costo. Esta pérdida económica (desperdicio de stock) se agrava por el desgaste humano: el personal invierte un volumen considerable de horas laborales documentando parámetros en bitácoras físicas. Este esfuerzo administrativo resulta ineficiente, ya que no previene el daño del material, sino que apenas lo registra de forma forense y tardía.

La raíz de este problema es bidimensional. Por un lado, existe un factor de infraestructura: las instalaciones de salud a menudo enfrentan cortes de suministro eléctrico o dependen de equipos de refrigeración que carecen de sistemas de respaldo térmico. Por otro lado, y de forma más crítica, los métodos convencionales de monitoreo manual generan "puntos ciegos" en la supervisión. Un análisis sistemático sobre la cadena de frío demuestra que las revisiones esporádicas durante los turnos diurnos dejan al inventario completamente vulnerable durante la madrugada, los fines de semana y los días festivos (Matthias et al., 2007). Es precisamente en estos intervalos de nula vigilancia donde ocurren la mayoría de las fallas irreversibles, obligando al descarte de los insumos ante la incertidumbre del tiempo de exposición.

Para delimitar el problema de manera estructurada, aplicamos la técnica The 5 'W's y 2 'H's:

- **Who (Quién)**: Coordinadores de laboratorio, técnicos de farmacia y personal administrativo responsable de la viabilidad clínica y la gestión presupuestal del inventario biológico.

- **What (Qué)**: Riesgo clínico elevado por la potencial utilización de insumos degradados, sumado a pérdidas económicas significativas debido al descarte obligatorio de reactivos y vacunas tras excursiones térmicas.

- **Where (Dónde)**: Cuartos fríos, refrigeradores de laboratorio y áreas de almacenamiento en farmacias clínicas y hospitalarias.

- **When (Cuándo)**: El riesgo es permanente, pero los incidentes críticos ocurren durante fallas de infraestructura eléctrica y, especialmente, durante los "puntos ciegos" de la supervisión manual (madrugadas, fines de semana y feriados).

- **Why (Por qué)**: Excesiva dependencia de la supervisión humana intermitente mediante bitácoras físicas, combinada con la falta de mecanismos que notifiquen proactivamente el mal funcionamiento del hardware de refrigeración.

- **How (Cómo)**: El personal constata la temperatura visualmente en intervalos de varias horas. Si ocurre un apagón o una falla técnica entre dos lecturas, es imposible determinar con exactitud el tiempo que el reactivo estuvo fuera de rango, lo que invalida su uso clínico.

- **How Much (Cuánto)**: Compromiso incalculable en la fiabilidad diagnóstica de los pacientes, sumado a la pérdida de miles de dólares por lote descartado y cientos de horas-hombre desperdiciadas anualmente en tareas mecánicas de documentación (Kumru et al., 2014; OMS, 2020).

### **1.2.2 Lean UX Process**

#### **1.2.2.1. Lean UX Problem Statements**

- **Contexto**: Las instituciones de salud, como laboratorios clínicos y farmacias hospitalarias, dependen de la integridad de inventarios biológicos (reactivos, vacunas y muestras) que requieren un control térmico estricto, generalmente entre 2 °C y 8 °C. La precisión de los diagnósticos médicos y la rentabilidad institucional están directamente ligadas a la estabilidad de estos insumos.

- **Observación del problema**: Se ha identificado que el proceso actual de control de la cadena de frío es mayoritariamente manual y reactivo. Profesionales altamente especializados, como biólogos y químicos, dedican hasta un 25% de su jornada a registrar temperaturas en bitácoras físicas. Este método genera "puntos ciegos" críticos durante las madrugadas y fines de semana, periodos en los que no existe supervisión activa ni capacidad de respuesta ante fallas de infraestructura o cortes eléctricos.

- **Impacto**: Esta deficiencia operativa provoca un elevado riesgo clínico por el uso potencial de insumos degradados y genera pérdidas económicas que pueden alcanzar miles de dólares por cada incidente térmico. Asimismo, la falta de una trazabilidad digital inmutable expone a las instituciones a sanciones legales y regulatorias por parte de entidades como DIGEMID o la FDA, además de comprometer certificaciones de calidad como la ISO 15189 (Kumru et al., 2014; Organización Mundial de la Salud, 2020).

#### **1.2.2.2. Lean UX Assumptions**

- **User Assumptions**:
    - Creemos que nuestros usuarios son biólogos y coordinadores de laboratorio con una carga laboral excesiva y altos niveles de estrés.
    - Creemos que estos profesionales poseen un criterio científico riguroso que les hace valorar la precisión de los datos sobre la facilidad administrativa.
    - Creemos que el personal siente una profunda desconfianza hacia las bitácoras manuales debido a su inherente margen de error.
    - Creemos que los usuarios tienen la competencia técnica necesaria para operar interfaces web modernas sin requerir capacitaciones extensas.
    - Creemos que las auditorías externas y el cumplimiento normativo representan la principal fuente de fricción y preocupación laboral para el personal.

- **User Outcome Assumptions**:
    - Creemos que el usuario obtendrá tranquilidad mental al disponer de visibilidad remota de sus equipos de frío las 24 horas del día.
    - Creemos que el éxito del sistema para el usuario implica la eliminación absoluta de las bitácoras de papel y los errores de transcripción.
    - Creemos que el personal podrá actuar preventivamente antes de que un reactivo sufra una degradación irreversible gracias a las alertas tempranas.
    - Creemos que el usuario logrará una curva de adopción técnica inmediata sin depender de manuales complejos o del departamento de sistemas.
    - Creemos que la automatización liberará tiempo valioso para que el personal se enfoque en tareas analíticas de alto valor clínico.

- **Business Assumptions**:
    - Creemos que las pérdidas económicas por desperdicio de reactivos son significativamente mayores al costo de suscripción de nuestro software.
    - Creemos que los laboratorios medianos optarán por un modelo B2B SaaS si el Retorno de Inversión (ROI) es demostrable en el corto plazo.
    - Creemos que la facilidad de uso del software es vital para evitar la resistencia operativa en entornos clínicos tradicionales.
    - Creemos que la creciente rigurosidad de los entes reguladores sanitarios actuará como el principal motor de ventas para nuestra solución.
    - Creemos que la reputación de SafeLab se consolidará mediante la reducción comprobada de mermas en los primeros clientes adoptantes.

- **Business Outcome Assumptions**:
    - Creemos que la plataforma logrará reducir el desperdicio de material biológico en un 95% durante el primer año de implementación.
    - Creemos que alcanzaremos una tasa de retención de clientes superior al 90% anual debido al valor crítico que aporta el sistema.
    - Creemos que los costos operativos de gestión de calidad en las clínicas disminuirán en un 60% al automatizar la recolección de datos.
    - Creemos que la usabilidad de la plataforma permitirá que el tiempo de capacitación y adopción del personal clínico se reduzca a menos de 2 horas por laboratorio.
    - Creemos que la acumulación de datos históricos permitirá ofrecer servicios de analítica predictiva como una fuente de ingresos adicional.

- **Feature Assumptions**:
    - Creemos que un Dashboard SPA (Single Page Application) es la interfaz más eficiente para centralizar el monitoreo de múltiples equipos.
    - Creemos que un motor de alertas configurable por umbrales permitirá adaptar el sistema a la sensibilidad térmica específica de cada reactivo.
    - Creemos que un módulo de exportación de reportes PDF automatizados garantizará el cumplimiento de los estándares de auditoría.
    - Creemos que un flujo de configuración guiada (onboarding nativo) en la plataforma facilitará la adopción autónoma del sistema.
    - Creemos que una base de datos inmutable es esencial para asegurar la veracidad de la trazabilidad ante inspecciones legales.

#### **1.2.2.3. Lean UX Hypothesis Statements**

- **Creemos que** reduciremos el desperdicio de material biológico en un 95%<br>
    **Si** los biólogos y coordinadores de laboratorio<br>
    **Obtienen** la capacidad de anticiparse a fallas térmicas críticas antes de que ocurra el daño<br>
    **Con** el motor de alertas preventivas en tiempo real configurables por umbrales.<br>
- **Creemos que** disminuiremos los costos operativos administrativos en un 60%<br>
    **Si** los coordinadores de operaciones clínicas<br>
    **Obtienen** la eliminación total del registro manual y la transcripción de datos físicos<br>
    **Con** el módulo automatizado de generación de reportes normativos en PDF.<br>
- **Creemos que** lograremos reducir el tiempo de capacitación y adopción a menos de 2 horas por laboratorio<br>
    **Si** el personal de salud<br>
    **Obtiene** una curva de aprendizaje inmediata sin depender del departamento de sistemas<br>
    **Con** el flujo de configuración guiada (onboarding nativo) integrado en la plataforma.<br>
- **Creemos que** lograremos una retención de clientes superior al 90% anual<br>
    **Si** los responsables de laboratorio y biólogos<br>
    **Obtienen** tranquilidad operativa y visibilidad absoluta de su infraestructura 24/7<br>
    **Con** el Dashboard SPA que centraliza toda la telemetría en una interfaz minimalista.<br>
- **Creemos que** el éxito en auditorías de trazabilidad será del 100% para nuestros clientes<br>
    **Si** los gerentes de calidad y entes reguladores<br>
    **Obtienen** acceso a registros históricos de temperatura inalterables y detallados<br>
    **Con** la implementación de una base de datos persistente e inmutable.<br>

#### **1.2.2.4. Lean UX Canvas**

![LeanUX Canvas](./assets/chapter-i/LeanUX_canvas_SafeLab.png)
Nota: Elaboración propia.

## **1.3. Segmentos Objetivo**

**El Coordinador de Operaciones Bioclínicas**

El mercado objetivo de SafeLab se concentra en el sector de la salud descentralizado, específicamente enfocado en laboratorios clínicos y farmacias hospitalarias ubicados en ciudades emergentes o provincias con poblaciones menores a 250,000 habitantes. Desde una perspectiva firmográfica y geográfica, estas instituciones representan un nicho altamente desatendido; mientras que los grandes complejos hospitalarios en metrópolis ya cuentan con ecosistemas de automatización de grado corporativo, los laboratorios en ciudades medianas y pequeñas operan con presupuestos más restringidos y dependen de infraestructura tecnológica rezagada. Al carecer de acceso a soluciones automatizadas accesibles, estas instituciones sufren de manera desproporcionada los impactos económicos de las excursiones térmicas, convirtiéndose en el ecosistema ideal para la adopción de un modelo B2B SaaS de rápida implementación.

A nivel demográfico, este segmento está compuesto por hombres y mujeres en un rango de edad amplio, situado entre los 24 y 60 años. Esta amplitud etaria abarca desde profesionales de la salud recién egresados que asumen roles de supervisión técnica, hasta directores de laboratorio con décadas de trayectoria. Todos comparten un nivel educativo superior (grados universitarios en biología, farmacia, biotecnología o tecnología médica). En el contexto institucional, estos profesionales poseen un poder de decisión híbrido: actúan como usuarios finales (End Users) que sufren directamente las ineficiencias del proceso diario, pero al mismo tiempo ejercen el rol de influenciadores críticos (Decision Influencers) frente a la gerencia médica. Si bien no siempre son quienes firman los presupuestos de la clínica, su aval técnico es el requisito indispensable para la adquisición de cualquier herramienta o equipamiento de laboratorio.

Desde un enfoque psicográfico y de comportamiento, el coordinador bioclínico se caracteriza por un rigor científico inquebrantable, moldeado por años de formación académica. Son individuos meticulosos y altamente analíticos, cuyo mayor temor profesional es la validación de un falso negativo derivado del uso de un reactivo degradado. Comportamentalmente, viven en un estado de alerta constante, experimentando altos niveles de estrés laboral al tener que equilibrar el procesamiento de muestras con tareas mecánicas de transcripción en bitácoras físicas. La presión por cumplir con normativas de calidad y superar auditorías sorpresa de entes reguladores rige su rutina diaria, generándoles una profunda frustración al saber que sus métodos de control manual son reactivos, propensos al error humano y consumen tiempo que debería ser destinado al análisis clínico.

Finalmente, el perfil tecnográfico de este segmento revela una dualidad interesante. En su entorno de trabajo, suelen interactuar con computadoras compartidas (generalmente PCs de escritorio con sistemas operativos heredados) y carecen de un departamento de soporte técnico (TI) dedicado exclusivamente a ellos. Sin embargo, en su vida personal, son usuarios asiduos de dispositivos móviles inteligentes (smartphones Android o iOS) y consumen información ágilmente. Esta realidad exige que las soluciones tecnológicas dirigidas a ellos no requieran instalaciones complejas ni mantenimientos locales; necesitan plataformas como aplicaciones web (SPA) que sean intuitivas, accesibles desde cualquier navegador o dispositivo móvil, y que ofrezcan una experiencia de usuario fluida que contrarreste la obsolescencia técnica de su entorno laboral.

# **Capítulo II: Requirements Elicitation & Analysis**

## **2.1. Competidores**

### **2.1.1. Análisis competitivo**

**¿Por qué llevar a cabo este análisis?**
Identificar las barreras de entrada (tecnológicas y económicas) que imponen los líderes globales del monitoreo IoT, con el fin de validar que existe un nicho desatendido en instituciones de salud medianas y pequeñas. Este análisis nos permitirá posicionar a SafeLab como una alternativa ágil, específica para el flujo clínico y económicamente accesible.

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Atributo</th>
      <th>SafeLab</th>
      <th>SmartSense</th>
      <th>SenseAnywhere</th>
      <th>Monnit</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Overview</strong></td>
      <td>Startup B2B SaaS enfocada en erradicar mermas biológicas mediante automatización ágil y accesible.</td>
      <td>Plataforma corporativa IoT de alto nivel para trazabilidad y cumplimiento en redes hospitalarias y farmacéuticas.</td>
      <td>Sistema europeo de monitoreo en la nube, enfocado en hardware ultra duradero y logística de cadena de frío.</td>
      <td>Proveedor global de soluciones de monitoreo remoto con sensores inalámbricos para múltiples industrias.</td>
    </tr>
    <tr>
      <td><strong>Ventaja Competitiva</strong></td>
      <td>Plataforma agnóstica de hardware, altamente contextualizada al flujo de trabajo de biólogos.</td>
      <td>Capacidad masiva de escala e integración con sistemas ERP y cumplimiento estricto normativo (FDA).</td>
      <td>Confiabilidad extrema del hardware y registro ininterrumpido en la nube sin mantenimiento local.</td>
      <td>Accesibilidad económica inicial y personalización extrema para monitorear casi cualquier variable.</td>
    </tr>
    <tr>
      <td><strong>Mercado Objetivo</strong></td>
      <td>Laboratorios clínicos y farmacias hospitalarias en ciudades emergentes o periféricas.</td>
      <td>Grandes hospitales, cadenas de farmacias nacionales y logística farmacéutica global.</td>
      <td>Almacenes de alta tecnología, laboratorios farmacéuticos y empresas de transporte logístico.</td>
      <td>Pequeñas y medianas empresas (PyMEs) de cualquier sector (agricultura, IT, alimentos, clínicas).</td>
    </tr>
    <tr>
      <td><strong>Estrategias de Marketing</strong></td>
      <td>Inbound marketing enfocado en la "Cultura de Desperdicio Cero" y la simplificación de auditorías de calidad locales.</td>
      <td>Ventas corporativas B2B, enfocadas en el retorno de inversión (ROI) por mitigación de riesgos legales.</td>
      <td>Presencia en ferias farmacéuticas globales.</td>
      <td>Marketing digital masivo, e-commerce directo y posicionamiento en buscadores por bajo costo.</td>
    </tr>
    <tr>
      <td><strong>Productos y Servicios</strong></td>
      <td>Web Application SPA + Integración API con hardware genérico y económico de terceros.</td>
      <td>Software empresarial + Gateways + Sensores IoT propietarios.</td>
      <td>SenseAnywhere Cloud + AiroSensors (Hardware propietario cerrado).</td>
      <td>Plataforma iMonnit + Sensores ALTA inalámbricos.</td>
    </tr>
    <tr>
      <td><strong>Precios y Costos</strong></td>
      <td>Bajo. Modelo puramente SaaS con pagos mensuales/anuales, permitiendo reutilizar equipos genéricos.</td>
      <td>Muy alto. Contratos empresariales anuales que incluyen hardware costoso e instalación.</td>
      <td>Medio-Alto. Depende de la importación de sus sensores europeos especializados.</td>
      <td>Bajo-Medio. Hardware asequible y suscripciones mensuales o anuales escalonadas.</td>
    </tr>
    <tr>
      <td><strong>Canales de distribución</strong></td>
      <td>Venta directa B2B y self-onboarding.</td>
      <td>Venta directa corporativa. Plataforma Web y App Móvil.</td>
      <td>Red de distribuidores oficiales. Plataforma Web SaaS.</td>
      <td>Tienda online propia y distribuidores. Plataforma Web y Móvil.</td>
    </tr>
    <tr>
      <td><strong>Fortalezas</strong></td>
      <td>Alta agilidad para pivotar, bajo costo estructural e interfaz diseñada puramente para el usuario clínico</td>
      <td>Reputación de marca inquebrantable y certificaciones internacionales.</td>
      <td>Hardware líder en el mercado (10 años sin carga) y software muy estable.</td>
      <td>Amplísimo catálogo de sensores e interfaz altamente personalizable.</td>
    </tr>
    <tr>
      <td><strong>Oportunidades</strong></td>
      <td>Existencia de un inmenso mercado de laboratorios medianos que utilizan procesos de papel por no poder pagar a los grandes competidores.</td>
      <td>Absorción de competidores menores y contratos gubernamentales.</td>
      <td>Expansión en mercados emergentes y mejora de su integración API.</td>
      <td>Crecimiento constante en la digitalización post-pandemia en clínicas medianas.</td>
    </tr>
    <tr>
      <td><strong>Debilidades</strong></td>
      <td>Ausencia de hardware propietario y falta de reconocimiento de marca en la etapa inicial.</td>
      <td>Inaccesible para clínicas pequeñas. Requiere procesos lentos de implementación corporativa.</td>
      <td>Modelo de hardware cerrado; si se daña un sensor, hay que importar otro del fabricante.</td>
      <td>Plataforma demasiado genérica; no está diseñada específicamente para flujos de trabajo específicos.</td>
    </tr>
    <tr>
      <td><strong>Amenazas</strong></td>
      <td>Desconfianza inicial del sector salud hacia plataformas nuevas o ingreso de un gigante tecnológico al mercado de bajo costo.</td>
      <td>Surgimiento de startups ágiles y económicas en mercados locales.</td>
      <td>Problemas en cadenas de suministro global de microchips que encarecen su hardware.</td>
      <td>Soluciones de nicho que roben a sus clientes del sector salud por tener interfaces más especializadas.</td>
    </tr>
  </tbody>
</table>

### **2.1.2. Estrategias y tácticas frente a competidores**

**Estrategias Ofensivas**<br>
*Penetración por Hiper-especialización y Bajo Costo*<br>
Al cruzar nuestra fortaleza de tener una arquitectura de software agnóstica (sin hardware propietario) con el inmenso mercado desatendido en ciudades de menos de 250,000 habitantes, nuestra táctica principal será ofrecer un modelo SaaS puramente enfocado en el flujo clínico. Mientras los competidores obligan a comprar costosos paquetes de sensores cerrados, SafeLab permitirá a los laboratorios medianos digitalizar sus procesos utilizando sensores genéricos locales, democratizando el acceso a la tecnología de calidad y capturando rápidamente este nicho en expansión.
<br><br>
**Estrategias Adaptativas**<br>
*Alianzas Estratégicas de Distribución B2B*<br>
Para contrarrestar nuestra principal debilidad (la ausencia de hardware propio y el bajo reconocimiento de marca inicial), aprovecharemos la creciente necesidad de digitalización post-pandemia mediante alianzas. La táctica será asociarnos con distribuidores locales de refrigeradoras médicas y proveedores de sensores IoT genéricos, ofreciendo SafeLab como un "valor agregado" o software nativo en sus ventas. Esto nos permite llegar al cliente final a través de un canal que ya goza de confianza, mitigando el costo de adquisición.
<br><br>
**Estrategias Defensivas**<br>
*Diferenciación por Usabilidad Clínica (Self-Onboarding)*<br>
Ante la amenaza de la desconfianza del sector salud hacia nuevas tecnologías o el posible ingreso de gigantes tecnológicos con soluciones de bajo costo, utilizaremos nuestra agilidad y diseño centrado en el usuario clínico como escudo. La táctica es construir un flujo de onboarding "Plug & Play" y una interfaz (dashboard/reportes PDF) tan milimétricamente adaptada al estrés de las auditorías locales (ej. ISO 15189), que cualquier otra plataforma genérica se perciba como torpe e inadecuada para un biólogo.
<br><br>
**Estrategias de Supervivencia**<br>
*Validación Temprana y Cumplimiento Normativo Estricto*<br>
La combinación de ser una marca nueva (debilidad) en un sector altamente desconfiado y regulado (amenaza) es el mayor riesgo para la startup. Para sobrevivir a esta barrera, la táctica desde el "Día 1" será la estandarización estricta. El software se diseñará exclusivamente bajo los formatos exigidos por los entes reguladores de salud. Además, se implementarán programas piloto (pruebas Beta gratuitas) en laboratorios clave de ciudades secundarias para generar casos de éxito comprobables y métricas de ROI reales, sustituyendo la falta de reputación inicial por evidencia empírica irrefutable.
<br>

## **2.2. Entrevistas**

### **2.2.1. Diseño de entrevistas**

**Segmento: Coordinador**

1. ¿Podrías indicarnos tu nombre, edad, estado civil y en qué distrito resides?
2. Cuéntanos un poco sobre tí y qué sueles hacer en tu tiempo libre. ¿Cómo te describirías en tres palabras?
3. ¿Cuál es tu cargo actualmente y cuántos años de experiencia tienes? ¿Tienes un objetivo profesional a corto plazo?
4. En tu día a día, ¿qué dispositivos tecnológicos utilizas más (smartphone, tablet, laptop), qué sistema operativo y navegador prefieres?
5. ¿Cómo es actualmente el proceso de monitoreo en tu laboratorio/farmacia en el día a día?
6. ¿Cuánto tiempo estimas que le dedicas a registrar estas bitácoras y elaborar los reportes?
7. Háblame de la última vez que tuvieron un evento crítico, como una alta desviación de temperatura o una pérdida de reactivos/vacunas.
8. ¿Qué es lo que más te frustra o te estresa de tu trabajo actualmente?
9. Si existiera un sistema ideal para resolver tus problemas, ¿cómo sería?
10. Si un sistema te enviará una alerta a tu celular de que el refrigerador esté fallando, ¿preferirías solo recibir la notificación o que el sistema intente ejecutar una acción de contingencia?
11. Para que confíes al 100% en este sistema, ¿qué información o garantías tendría que mostrarte?
12. ¿Hay algo más sobre tu trabajo que creas que es importante discutir?

### **2.2.2. Registro de entrevistas**

Enlace de las entrevistas: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201919096_upc_edu_pe/IQBdqMlL_u9rToY2ZTeE2nSjAQadDXLFwRLG9-oDESdV8MU?e=vSyiF7&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

**Segmento: Coordinador**

* **Entrevista 1**: Abdul Muchica
    * **Inicio**: 00:00
    * **Duración**: 09:56
    * **Captura**: <br>![Abdul Muchica](./assets/chapter-ii/Abdul%20Muchica.png)
    * **Resumen**: Abdul Muchica es un biólogo de 29 años con experiencia en las áreas de microbiología y laboratorio clínico en los hospitales Honorio Delgado y Manuel Nuñez Butron. Se describe a sí mismo como una persona atlética y empática.
Su trabajo empieza monitoreando refrigeradoras en un banco de sangre, toma la temperatura manualmente usando un termómetro digital independiente de la refrigeradora y registra la hora, la persona responsable y la temperatura en una hoja de papel. Este procedimiento lo realiza tres veces por turno y le toma aproximadamente cinco minutos cada uno. Nos cuenta que a veces los termómetros pueden no ser manipulados correctamente y terminan siendo descalibrados. Lo que lo frustra es que no dispone de mucho espacio dentro del laboratorio, le es difícil manipular sus herramientas, y más aún cuando está en un apuro.
Le gustaría que los datos con los que trabaja no los tenga que medir y que estén disponibles para él por medio de su celular para más comodidad. Prefiere que, en caso suceda un problema, el sistema se encargue de arreglarlo por sí mismo, aunque expresa escepticismo en el caso de laboratorios con menor presupuesto. Considera de alta importancia, además de tener información sobre las temperaturas de las refrigeradoras, saber el estado de los equipos para prevenir que estos dejen de operar en momentos críticos.

<br>

* **Entrevista 2**: Fabrizio Palomino
    * **Inicio**: 09:57
    * **Duración**: 09:20
    * **Captura**: <br>![Fabrizio Palomino](./assets/chapter-ii/Fabrizio%20Palomino.png)
    * **Resumen**: Fabrizio Palomino es un biólogo de 24 años con dos años de experiencia en microbiología. Se describe a sí mismo como una persona entusiasta y cooperativa.
Su trabajo empieza con un control de calidad, revisa refrigeradoras donde guarda reactivos, algunos cuentan con termómetros, otros no. El control es manual, la temperatura y humedad son anotados en un cuaderno y a fin de mes debe generar un reporte con las variaciones de temperatura y averías que los equipos hayan sufrido. Le toma aproximadamente unos 5 minutos cada inspección. Algunos de los equipos no pueden ser examinados correctamente e inevitablemente fallan. Cuando esto sucede, le estresa el proceso de licitación para adquirir uno nuevo, él solo quiere tener un nuevo equipo funcionando lo más antes posible.
Lo principal que busca en una nueva aplicación es que demuestre confiabilidad, que la aplicación lo informe y esté disponible en todo momento. Prefiere que se envíen alertas siempre que suceda un imprevisto, priorizando al personal que se encuentre de turno en el momento de la falla. Espera que la aplicación muestre variación de temperatura entre periodos, preferiblemente entre semanas y meses.

<br>

* **Entrevista 3**: Efrain Palomino
    * **Inicio**: 09:57
    * **Duración**: 09:20
    * **Captura**: <br>![Efrain Palomino](./assets/chapter-ii/Efrain%20Palomino.png)
    * **Resumen**: Efrain Palomino es un biólogo de 65 años que trabaja en el servicio de laboratorio de EsSalud, tiene 26 años de experiencia en el área de microbiología. Se describe a sí mismo como una persona solidaria y trabajadora.
Al ingresar a trabajar, lo primero que hace es registrar las temperaturas de sus equipos, lo hace de forma manual, tres veces al día y tarda 35 minutos aproximadamente a lo largo de una semana. Estos registros se archivan diariamente en un “registro de incidencias”. Indica que no ha sufrido ninguna experiencia crítica hasta el momento, lo atribuye a un buen trabajo en equipo. Lo que lo estresa son las fallas administrativas al enfrentar ausencia de insumos y fallos de equipos.
Lo que más le importa es la constante comunicación entre el personal, aunque actualmente usa WhatsApp, le gustaría que esto se integre formalmente a su trabajo; menciona la necesidad de personalizar alertas para filtrar información y actuar inmediatamente. Requiere que esta app le muestre información de incidentes, estado de insumos y de equipos. Para finalizar, recalca la necesidad de las alarmas para que todo el personal esté informado sobre el estado de su servicio.

<br>

### **2.2.3. Análisis de entrevistas**

**Segmento: Coordinador**

**Características**
* **Sexo:** Masculino
* **Edad:** 24 - 65 años
* **Dispositivos:** Celular, Laptop
* **Sistemas Operativos:** Android, Windows
* **Navegadores:** Chrome
* **Influencia de Marcas:** Equipo de refrigeración (BioRack, BioBase, Helmer Inc), Insumos (Wiener), Comunicación (WhatsApp)

**Objetivos Comunes**
* Dejar de depender de procesos manuales al examinar sus equipos e insumos.
* Tener información detallada de sus equipos.
* Estandarizar sus controles y protocolos.
* Obtener rápida respuesta desde el nivel administrativo.

**Motivaciones Comunes**
* Contar con la seguridad de que sus equipos operan de forma correcta.
* Tener información que prevenga averías antes de que el equipo deje de funcionar.
* Contar con nuevos equipos totalmente operativos a la brevedad cuando uno deje de funcionar.

**Frustraciones Comunes**
* Procesos manuales sujetos a errores.
* Alcance a información superficial insuficiente.
* Largos tiempos de espera por procesos burocráticos debido a la falta de estandarización.

## **2.3. Needfinding**

### **2.3.1. User Personas**

**Segmento: Coordinador**

![User Persona Carlos](./assets/chapter-ii/Carlos%20Mendoza.png)
Nota: Elaboración propia.

### **2.3.2. User Task Matrix**

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>#</th>
      <th>Tarea</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Monitoreo rutinario de temperatura</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Respuesta ante incidentes de equipo</td>
      <td>Baja</td>
      <td>Crítica</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Elaboración de reportes de calidad</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Traspaso de información entre turnos</td>
      <td>Alta</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Gestión administrativa de reposición</td>
      <td>Muy Baja</td>
      <td>Media</td>
    </tr>
  </tbody>
</table>

### **2.3.3. User Journey Mapping**

**Segmento: Coordinador**

![User Journey Mapping](./assets/chapter-ii/Carlos%20Journey%20Map.png)
Nota: Elaboración propia.

### **2.3.4. Empathy Mapping**

**Segmento: Coordinador**

![User Empathy Mapping](./assets/chapter-ii/Carlos%20Empathy%20map.png)
Nota: Elaboración propia.

## **2.4. Big Picture Event Storming**

El equipo llevó a cabo una sesión de **Big Picture Event Storming** con el objetivo de obtener una visión holística y compartida del dominio de **SafeLab**. A diferencia de un análisis técnico detallado, este proceso se centró en mapear el "landscape" del negocio, identificando los eventos de dominio más significativos desde que un sensor captura una lectura hasta que se genera un reporte de cumplimiento legal.

Durante esta fase, se priorizó la exploración del flujo de trabajo clínico y los puntos críticos de contacto entre el personal de laboratorio y la infraestructura tecnológica. El proceso se dividió en las siguientes etapas:

* **Identificación de Eventos de Dominio (Naranja):** Se plasmaron de forma cronológica todos los cambios de estado relevantes en el sistema (por ejemplo, el inicio de una excursión térmica o el reconocimiento de una alerta), utilizando un lenguaje común libre de tecnicismos excesivos.

* **Detección de Puntos de Fricción o Pain Points (Rosa):** De manera simultánea, el equipo identificó cuellos de botella, riesgos operativos y vacíos en la supervisión manual, como la fatiga por alarmas o la desconfianza en la integridad de los datos manuales durante los turnos nocturnos.

Esta primera aproximación visual permitió al equipo exponer oportunidades de mejora, como la automatización de acciones correctivas, y sentó las bases para delimitar los contextos de la solución, asegurando que la arquitectura de software propuesta responda fielmente a las necesidades críticas de seguridad bioclínica identificadas.

![Event_Storming](./assets/chapter-ii/2.4.jpg)
Nota: Elaboración propia en Miro.

## **2.5. Ubiquitous Language**

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Ubiquitous Term</th>
      <th>Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Cold Chain</strong></td>
      <td>El proceso continuo e ininterrumpido de almacenamiento a temperatura controlada que garantiza la estabilidad y viabilidad de los insumos en el laboratorio.</td>
    </tr>
    <tr>
      <td><strong>Biological Reagent</strong></td>
      <td>Cualquier sustancia, reactivo clínico, vacuna o muestra de pacientes que requiera refrigeración estricta y sea altamente sensible a las variaciones térmicas.</td>
    </tr>
    <tr>
      <td><strong>Cold Storage Unit</strong></td>
      <td>El contenedor físico (refrigeradora médica, congeladora o cuarto frío) utilizado por el laboratorio para salvaguardar los insumos biológicos.</td>
    </tr>
    <tr>
      <td><strong>IoT Sensor</strong></td>
      <td>El dispositivo de hardware colocado en el interior del equipo de frío encargado de capturar la temperatura en tiempo real y transmitirla de forma inalámbrica a la plataforma.</td>
    </tr>
    <tr>
      <td><strong>Temperature Reading</strong></td>
      <td>El valor métrico exacto de temperatura o humedad capturado por un sensor en una marca de tiempo (timestamp) específica.</td>
    </tr>
    <tr>
      <td><strong>Safe Temperature Threshold</strong></td>
      <td>El rango numérico de temperatura permitido (usualmente entre 2 °C y 8 °C) dentro del cual un insumo biológico mantiene su integridad sin riesgo de daño.</td>
    </tr>
    <tr>
      <td><strong>Thermal Excursion</strong></td>
      <td>Evento crítico que ocurre cuando la temperatura de un equipo se desvía por fuera de su Safe Temperature Threshold, poniendo en riesgo la utilidad del reactivo.</td>
    </tr>
    <tr>
      <td><strong>Spoilage</strong></td>
      <td>La pérdida económica e irreversible (merma o desperdicio) de un lote de insumos biológicos debido a una exposición prolongada a una falla térmica.</td>
    </tr>
    <tr>
      <td><strong>Preventive Alert</strong></td>
      <td>Notificación automática generada por el sistema y enviada al personal de turno cuando la temperatura se acerca peligrosamente a los límites del umbral, antes de que ocurra la merma.</td>
    </tr>
    <tr>
      <td><strong>Incident Log</strong></td>
      <td>El registro inmutable y centralizado de todas las anomalías detectadas, incluyendo los comentarios sobre qué miembro del personal respondió a una alerta y qué acción correctiva tomó.</td>
    </tr>
    <tr>
      <td><strong>Compliance Report</strong></td>
      <td>Documento oficial generado automáticamente que consolida el historial de lecturas y el registro de incidencias en un formato normativo válido para superar auditorías de calidad (ej. ISO 15189, DIGEMID).</td>
    </tr>
  </tbody>
</table>

# Capítulo III: Requirements Specification

## Epics

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP01</td>
      <td>Landing Page</td>
      <td>Landing page para la presentación y promoción del sistema SafeLab.</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Gestión de Laboratorios</td>
      <td>Permitir a los usuarios crear, visualizar, administrar y monitorear sus laboratorios junto con sus sensores y sistemas ambientales en tiempo real.</td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Gestión de Alertas e Historial</td>
      <td>Permitir la detección, gestión, seguimiento y análisis de incidentes y alertas generadas por los laboratorios.</td>
    </tr>
    <tr>
      <td>EP04</td>
      <td>Cuenta, Seguridad y Experiencia del Usuario</td>
      <td>Gestionar la autenticación, la sesión, las preferencias del usuario y las notificaciones del sistema.</td>
    </tr>
  </tbody>
</table>

## 3.1 User Stories

<table border="1" cellspacing="0" cellpadding="8">
  <thead>
    <tr>
      <th>Epic / Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US01</td>
      <td>Optimización de la Vigilancia de Activos Críticos</td>
      <td>Como: Jefe de Calidad / Investigador. Quiero: Consultar las capacidades de monitoreo en tiempo real y los protocolos de alerta del sistema. Para: Asegurar que el laboratorio cuenta con las herramientas necesarias para mantener la integridad de las muestras y cumplir con los estándares de bioseguridad.</td>
      <td>
        <b>Escenario 1 (Happy Path): Visualización de herramientas de control</b><br>
        Dado que el Jefe de Calidad se encuentra en la sección "Características" de la Landing Page,<br>
        Cuando revisa las funciones de "Monitoreo 24/7" y "Alertas Inteligentes",<br>
        Entonces el sistema debe presentar una descripción clara de cómo cada función contribuye a reducir el margen de error humano en la medición de temperatura.<br><br>
        <b>Escenario 2 (Unhappy Path): Falta de claridad en las especificaciones técnicas</b><br>
        Dado que el usuario busca información sobre el cumplimiento de una norma específica (ej. ISO 15189) en las características,<br>
        Cuando la información visualizada es demasiado genérica o no carga correctamente,<br>
        Entonces el sistema debe facilitar un botón de "Más información" o "Descargar ficha técnica" para evitar que el usuario abandone el sitio por falta de sustento técnico.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US02</td>
      <td>Selección de Capacidades según el Volumen de Activos</td>
      <td>Como: Administrador de Laboratorio. Quiero: Evaluar y seleccionar un plan de suscripción basado en el número de sensores y unidades de almacenamiento. Para: Garantizar que la infraestructura de software soporte la escala operativa de mi laboratorio sin interrupciones en el monitoreo.</td>
      <td>
        <b>Escenario 1 (Happy Path):</b><br>
        Dado que el Administrador se encuentra en la sección "Nuestros Planes",<br>
        Cuando selecciona un plan (Basic, Standard o Enterprise) que cubre su cantidad de equipos,<br>
        Entonces el sistema debe mostrar el desglose de beneficios técnicos y el botón para iniciar la suscripción.<br><br>
        <b>Escenario 2 (Unhappy Path):</b><br>
        Dado que el usuario intenta seleccionar un plan que no se ajusta a las normativas de su región,<br>
        Cuando hace clic en "Comenzar", el sistema detecta que el laboratorio requiere auditorías ISO no incluidas en ese plan,<br>
        Entonces el sistema debe sugerir el plan "Enterprise" para asegurar el cumplimiento legal.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US03</td>
      <td>Validación Técnica y Solicitud de Información</td>
      <td>Como: Gerente de Laboratorio. Quiero: Enviar una solicitud de contacto detallando las necesidades específicas de mi cadena de frío. Para: Recibir una asesoría técnica personalizada que valide la compatibilidad de los sensores SafeLab con mis activos biológicos.</td>
      <td>
        <b>Escenario 1 (Happy Path):</b><br>
        Dado que el Gerente completa el formulario de la sección "Contáctanos",<br>
        Cuando ingresa su nombre, correo corporativo y mensaje técnico,<br>
        Entonces el sistema debe confirmar el envío exitoso y registrar la solicitud en el CRM de soporte.<br><br>
        <b>Escenario 2 (Unhappy Path):</b><br>
        Dado que el usuario ingresa un formato de correo inválido o deja el campo de "Mensaje" vacío,<br>
        Cuando intenta enviar el formulario,<br>
        Entonces el sistema debe marcar los campos en rojo y bloquear el envío para evitar registros de contacto incompletos.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US04</td>
      <td>Acceso Seguro al Ecosistema de Monitoreo</td>
      <td>Como: Usuario Registrado (Técnico/Admin). Quiero: Autenticarme mediante el portal de acceso seguro utilizando credenciales gestionadas por IAM. Para: Entrar al Dashboard y gestionar incidentes térmicos de acuerdo a mis permisos asignados.</td>
      <td>
        <b>Escenario 1 (Happy Path):</b><br>
        Dado que el técnico hace clic en el botón "Iniciar Sesión" del menú principal,<br>
        Cuando ingresa sus credenciales válidas y el sistema confirma su identidad,<br>
        Entonces el sistema debe cargar el Dashboard con los datos en tiempo real de sus unidades de almacenamiento.<br><br>
        <b>Escenario 2 (Unhappy Path):</b><br>
        Dado que un usuario intenta acceder desde una IP no autorizada o con credenciales erróneas,<br>
        Cuando presiona "Ingresar",<br>
        Entonces el sistema debe denegar el acceso y registrar un intento fallido en el Audit Entry para prevenir intrusiones.
      </td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>US05</td>
      <td>Monitoreo Térmico en Tiempo Real y Detección de Riesgos</td>
      <td>Como: Coordinador de Laboratorio quiero visualizar el estado térmico de todas las unidades de almacenamiento en tiempo real y de forma centralizada para detectar desviaciones críticas de temperatura de manera inmediata y prevenir la degradación de los reactivos o muestras biológicas.</td>
      <td>
        <b>Escenario 1: Monitoreo de Integridad de la Cadena de Frío (Happy Path)</b><br>
        Dado que el Coordinador ha iniciado sesión y accede al Dashboard principal,<br>
        Cuando el sistema recibe las lecturas sincronizadas de los sensores instalados,<br>
        Entonces el sistema debe mostrar los indicadores de temperatura actualizados, señalando si cada unidad se encuentra dentro del Safe Temperature Threshold definido.<br><br>
        <b>Escenario 2: Priorización visual ante Excursiones Térmicas (Unhappy Path / Alerta)</b><br>
        Dado que una o más unidades de almacenamiento superan los límites críticos de temperatura,<br>
        Cuando el Coordinador visualiza el Dashboard,<br>
        Entonces el sistema debe resaltar visualmente las unidades en riesgo (color rojo/parpadeo) y mostrar el tiempo transcurrido desde que se detectó la anomalía para facilitar la toma de decisiones urgente.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US06</td>
      <td>Análisis de Estabilidad Térmica mediante Tendencias Históricas</td>
      <td>Como: Jefe de Aseguramiento de la Calidad. Quiero: Analizar el gráfico de tendencias de temperatura de las últimas 24 horas. Para: Identificar patrones de comportamiento inestable en los equipos de frío antes de que ocurra una avería total.</td>
      <td>
        <b>Escenario 1 (Happy Path):</b><br>
        Dado que el Jefe de Calidad visualiza el gráfico de líneas del Dashboard,<br>
        Cuando selecciona un rango de tiempo específico,<br>
        Entonces el sistema debe mostrar la fluctuación de la temperatura comparada con el límite superior e inferior permitido, permitiendo detectar micro-variaciones sospechosas.<br><br>
        <b>Escenario 2 (Unhappy Path):</b><br>
        Dado que hay una pérdida de conexión con el sensor durante un periodo,<br>
        Cuando se genera el gráfico de tendencia,<br>
        Entonces el sistema debe marcar claramente el "gap" o vacío de información con una alerta de "Datos no confiables", evitando que se tome la falta de datos como una temperatura estable.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US07</td>
      <td>Identificación de Puntos Críticos vía Mapa de Calor (Heatmap)</td>
      <td>Como: Técnico de Mantenimiento. Quiero: Visualizar el mapa de calor de las unidades de almacenamiento distribuidas en el laboratorio. Para: Identificar qué zonas o racks específicos están sufriendo mayor estrés térmico y priorizar la revisión física de esos equipos.</td>
      <td>
        <b>Escenario 1 (Happy Path):</b><br>
        Dado que el Técnico observa el panel de "Heatmap" en el Dashboard,<br>
        Cuando una celda cambia a un color de alerta (ej. naranja o rojo intenso),<br>
        Entonces el sistema debe permitir hacer clic en dicha celda para identificar exactamente el nombre del equipo y su ubicación física (Rack/Estante).<br><br>
        <b>Escenario 2 (Unhappy Path):</b><br>
        Dado que todos los sensores reportan temperaturas normales pero el sistema detecta una anomalía de energía en un rack,<br>
        Cuando se visualiza el Heatmap,<br>
        Entonces el sistema debe sombrear la zona afectada indicando "Sensor no disponible/Falla eléctrica", impidiendo que el técnico asuma erróneamente que la zona está a temperatura correcta.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US08</td>
      <td>Trazabilidad de Alertas Críticas Recientes</td>
      <td>Como: Auditor de Cumplimiento (Compliance Officer). Quiero: Supervisar el log de alertas recientes disparadas por el sistema en el Dashboard. Para: Verificar que cada evento de riesgo térmico tenga una trazabilidad clara y cumpla con los tiempos de respuesta exigidos por la normativa bioclínica.</td>
      <td>
        <b>Escenario 1: Visualización de alertas activas (Happy Path)</b><br>
        Dado que han ocurrido fluctuaciones de temperatura en el laboratorio,<br>
        Cuando el Auditor revisa el panel de alertas en el Dashboard,<br>
        Entonces el sistema debe mostrar una lista cronológica indicando el tipo de alerta (ej. Thermal Excursion), la unidad afectada y el nivel de severidad (Low, Medium, High).<br><br>
        <b>Escenario 2: Alertas sin atención inmediata (Unhappy Path)</b><br>
        Dado que una alerta crítica aparece en el panel y no ha sido "Reconocida" por un técnico,<br>
        Cuando transcurre el tiempo límite definido en la Escalation Policy,<br>
        Entonces el sistema debe marcar la alerta en el Dashboard con un indicador de "Escalamiento Pendiente", notificando visualmente la brecha en el protocolo de seguridad.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Respuesta Rápida ante Alertas desde el Dashboard</td>
      <td>Como: Técnico de Laboratorio. Quiero: Interactuar con las alertas recientes directamente desde el panel del Dashboard. Para: Iniciar las acciones correctivas de forma inmediata sin navegar por menús complejos, reduciendo el tiempo de exposición al riesgo de las muestras.</td>
      <td>
        <b>Escenario 1: Inicio de Acción Correctiva (Happy Path)</b><br>
        Dado que el Técnico identifica una nueva alerta crítica en el Dashboard,<br>
        Cuando hace clic sobre la alerta para reconocerla,<br>
        Entonces el sistema debe abrir una ventana emergente que le permita registrar la Corrective Action inicial (ej. "Revisión de puerta abierta") y cambiar el estado del incidente a "En Proceso".<br><br>
        <b>Escenario 2: Reconocimiento fallido de alerta (Unhappy Path)</b><br>
        Dado que el Técnico intenta reconocer una alerta que ya fue asignada a otro usuario,<br>
        Cuando intenta realizar una acción sobre ella,<br>
        Entonces el sistema debe mostrar un mensaje de error indicando que el incidente ya está siendo atendido, evitando duplicidad de esfuerzos y registros inconsistentes.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Gestión Preventiva basada en Métricas Ambientales</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Analizar las métricas combinadas (temperatura, vibraciones y humedad) para ejecutar acciones preventivas sobre los equipos de almacenamiento. Para: Mitigar riesgos antes de que ocurra una falla crítica en la cadena de frío y asegurar condiciones óptimas según el tipo de muestra.</td>
      <td>
        <b>Escenario 1: Ajuste de Operación por Estrés Ambiental (Happy Path)</b><br>
        Dado que el Coordinador observa una correlación entre el aumento de la vibración del equipo y una leve inestabilidad térmica en los gráficos,<br>
        Cuando el sistema identifica esta tendencia como un riesgo de falla mecánica inminente,<br>
        Entonces el sistema debe permitir al Coordinador programar una "Acción de Mantenimiento Preventivo" directamente desde el panel de métricas, notificando al equipo técnico.<br><br>
        <b>Escenario 2: Notificación de Invalidez de Lectura (Unhappy Path)</b><br>
        Dado que un sensor de ambiente (vibración o humedad) reporta valores fuera de su rango de calibración técnica,<br>
        Cuando el usuario intenta basar una decisión operativa en dichos datos,<br>
        Entonces el sistema debe mostrar una advertencia de "Lectura no confiable: Requiere recalibración", bloqueando la capacidad de marcar el estado del laboratorio como "Seguro" hasta que se verifique el sensor.
      </td>
      <td>EP02</td>
    </tr>
        <tr>
      <td>US11</td>
      <td>Gestión Priorizada de Sedes y Laboratorios</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Visualizar la lista de laboratorios con filtros avanzados por estado de criticidad y ubicación. Para: Identificar de inmediato qué sedes presentan anomalías térmicas y priorizar la supervisión en los puntos de mayor riesgo.</td>
      <td>
        <b>Escenario 1 (Happy Path): Filtrado por Estado Crítico</b><br>
        Dado que el Coordinador se encuentra en la sección de "Laboratories",<br>
        Cuando aplica el filtro de "Estado: Crítico",<br>
        Entonces el sistema debe mostrar únicamente aquellos laboratorios que tengan al menos una Thermal Excursion activa, permitiendo una respuesta inmediata.<br><br>
        <b>Escenario 2 (Unhappy Path): Laboratorio sin conexión de datos</b><br>
        Dado que un laboratorio ha perdido la conexión con el Gateway de sensores,<br>
        Cuando el usuario visualiza la grilla de laboratorios,<br>
        Entonces el sistema debe mostrar el laboratorio con un estado de "Desconectado" y deshabilitar las métricas en tiempo real para evitar la lectura de datos obsoletos.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Gestión Operativa y Control de Unidades de Almacenamiento</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Acceder al panel de control detallado de un laboratorio específico para gestionar sus unidades de almacenamiento y sensores. Para: Ejecutar decisiones operativas como el ajuste de umbrales o el mantenimiento preventivo de los equipos de frío.</td>
      <td>
        <b>Escenario 1 (Happy Path): Ajuste de Umbrales de Seguridad</b><br>
        Dado que el Coordinador está en el detalle del laboratorio,<br>
        Cuando identifica que una unidad requiere un enfriamiento más estricto y ajusta el Temperature Threshold,<br>
        Entonces el sistema debe actualizar la política de alertas para ese sensor y registrar el cambio en el Audit Log por temas de cumplimiento.<br><br>
        <b>Escenario 2 (Unhappy Path): Intento de acción sin permisos suficientes</b><br>
        Dado que un Técnico intenta modificar los parámetros de configuración global de un laboratorio,<br>
        Cuando intenta guardar los cambios en la sección de detalles,<br>
        Entonces el sistema debe denegar la acción, solicitar la validación del Coordinador y mantener los parámetros anteriores para asegurar la integridad de la cadena de frío.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Registro y Vinculación Técnica de Sensores</td>
      <td>Como: Técnico de Laboratorio. Quiero: Registrar y vincular nuevos sensores a unidades de almacenamiento específicas (Racks/Refrigeradores). Para: Expandir la red de monitoreo y asegurar que cada activo biológico tenga un sensor asignado correctamente.</td>
      <td>
        <b>Escenario 1:</b><br>
        Dado que el técnico inicia el proceso de registro,<br>
        Cuando ingresa un ID de dispositivo nuevo,<br>
        Entonces el sistema valida que el ID del sensor sea único y lo asocia a la ubicación física seleccionada.<br><br>
        <b>Escenario 2:</b><br>
        Dado que el técnico intenta registrar un sensor ya activo,<br>
        Cuando el sistema detecta que el sensor ya está asignado a otro laboratorio,<br>
        Entonces el sistema impide la duplicidad y muestra un error de vinculación.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Monitoreo de Salud y Calibración de Dispositivos</td>
      <td>Como: Jefe de Mantenimiento. Quiero: Consultar el estado de batería y la fecha de última calibración de cada sensor. Para: Programar servicios técnicos preventivos y evitar interrupciones en la captura de datos críticos.</td>
      <td>
        <b>Escenario 1:</b><br>
        Dado que el sistema monitorea el hardware,<br>
        Cuando el nivel de energía disminuye significativamente,<br>
        Entonces el sistema muestra un indicador de batería baja cuando el sensor está por debajo del 15%.<br><br>
        <b>Escenario 2:</b><br>
        Dado que el sensor requiere mantenimiento normativo,<br>
        Cuando el certificado de calibración está vencido,<br>
        Entonces el sistema marca las lecturas como "No Certificadas" para alertar al departamento de Calidad.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Activación de Sistemas de Mitigación y Respuesta Automatizada</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Activar o desactivar los sistemas de mitigación (ventilación/refrigeración auxiliar) bajo reglas de validación técnica. Para: Reaccionar de forma segura ante una excursión térmica y estabilizar el ambiente sin comprometer la integridad de otros equipos.</td>
      <td>
        <b>Escenario 1: Activación Sujeta a Reglas de Seguridad (Happy Path)</b><br>
        Dado que la temperatura de una unidad de almacenamiento ha superado el límite crítico (Thermal Excursion),<br>
        Cuando el Coordinador intenta activar manualmente el sistema de ventilación de emergencia desde el panel de control,<br>
        Entonces el sistema debe validar que no existan alertas de "Falla Eléctrica" activas y proceder con la activación, registrando el evento como una "Acción de Mitigación" en el historial de seguridad.<br><br>
        <b>Escenario 2: Bloqueo por Condición Crítica (Unhappy Path)</b><br>
        Dado que el laboratorio presenta una alerta de "Humedad Extrema" o "Falla de Sensor de Presión",<br>
        Cuando el usuario intenta activar el sistema de ventilación,<br>
        Entonces el sistema debe bloquear la activación y mostrar un mensaje de error: "Activación denegada: Riesgo de contaminación cruzada por falla de filtros/presión", forzando al usuario a resolver la condición crítica primero.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Archivado y Custodia de Historial de Laboratorios</td>
      <td>Como: Administrador de Laboratorio. Quiero: Archivar o dar de baja laboratorios que ya no están operativos. Para: Mantener la organización del sistema sin perder la trazabilidad histórica de los datos térmicos exigida por las auditorías.</td>
      <td>
        <b>Escenario 1: Archivado Seguro con Retención de Datos (Happy Path)</b><br>
        Dado que un laboratorio ha cesado sus operaciones,<br>
        Cuando el Administrador solicita la eliminación/baja del laboratorio,<br>
        Entonces el sistema no debe borrar los datos permanentemente, sino cambiar su estado a "Archivado", moviendo los registros de incidentes y temperaturas a un repositorio de solo lectura para futuras auditorías.<br><br>
        <b>Escenario 2: Restricción de Eliminación por Alertas Activas (Unhappy Path)</b><br>
        Dado que un laboratorio tiene incidentes críticos de "Excursión Térmica" aún abiertos o sin resolución,<br>
        Cuando el usuario intenta eliminar el laboratorio,<br>
        Entonces el sistema debe bloquear la acción y mostrar un mensaje de error: "Operación denegada: No se puede eliminar un laboratorio con incidentes críticos pendientes de cierre", garantizando que no se borren evidencias de fallas de seguridad.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Gestión y Resolución de Incidentes Críticos</td>
      <td>Como: Técnico de Laboratorio / Coordinador. Quiero: Gestionar las alertas activas mediante la ejecución y registro de acciones correctivas. Para: Mitigar el impacto de las excursiones térmicas y asegurar que el incidente sea resuelto bajo los protocolos de bioseguridad.</td>
      <td>
        <b>Escenario 1: Ejecución de Acción Correctiva (Happy Path)</b><br>
        Dado que existe una alerta activa de severidad "Alta" por temperatura fuera de rango,<br>
        Cuando el Técnico selecciona la alerta y registra una Corrective Action (ej. "Traslado de muestras a unidad de respaldo"),<br>
        Entonces el sistema debe cambiar el estado de la alerta a "Resuelto", registrar el sello de tiempo (timestamp) y el usuario responsable, y emitir una notificación de "Ambiente Estabilizado".<br><br>
        <b>Escenario 2: Bloqueo de Cierre Inadecuado (Unhappy Path)</b><br>
        Dado que un técnico intenta marcar una alerta como "Resuelta" sin haber ingresado una descripción de la acción tomada,<br>
        Cuando presiona el botón de confirmar resolución,<br>
        Entonces el sistema debe impedir el cierre del incidente y mostrar un mensaje de error: "Campo obligatorio: Se requiere evidencia técnica de la acción correctiva para cumplir con la auditoría".
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Gestión del Ciclo de Vida y Cierre de Incidentes</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Gestionar el estado de las alertas críticas hasta su cierre definitivo. Para: Mantener el control operativo del incidente y asegurar que se ha recuperado la estabilidad térmica en la unidad de almacenamiento.</td>
      <td>
        <b>Escenario 1: Cierre Formal de Incidente (Happy Path)</b><br>
        Dado que una alerta de "Excursión Térmica" ha sido atendida y la temperatura ha regresado al rango seguro,<br>
        Cuando el Coordinador marca el incidente como "Cerrado",<br>
        Entonces el sistema debe solicitar una confirmación final y cambiar el estado del laboratorio a "Estable", bloqueando cualquier edición posterior sobre ese evento.<br><br>
        <b>Escenario 2: Registro en el Log de Auditoría (Unhappy Path)</b><br>
        Dado que se completa el cambio de estado a "Resuelto",<br>
        Cuando el sistema procesa la actualización,<br>
        Entonces debe generar automáticamente un asiento inmutable en el historial de auditoría, incluyendo el ID del usuario, el timestamp y la descripción de la resolución.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Trazabilidad y Auditoría de Cumplimiento Normativo</td>
      <td>Como: Auditor de Calidad. Quiero: Consultar el historial detallado de eventos, alertas y acciones ejecutadas en el sistema. Para: Generar reportes de cumplimiento para entidades regulatorias (ej. ISO, DIGEMID) y verificar la integridad de la cadena de frío en periodos pasados.</td>
      <td>
        <b>Escenario 1: Consulta de Trazabilidad Forense (Happy Path)</b><br>
        Dado que el Auditor accede a la sección de "Auditoría / Historial",<br>
        Cuando aplica filtros por rango de fecha, sensor específico y técnico responsable,<br>
        Entonces el sistema debe mostrar la línea de tiempo completa, correlacionando la fluctuación térmica con la respuesta humana y el sello digital de integridad.<br><br>
        <b>Escenario 2: Verificación de Integridad de Datos (Unhappy Path)</b><br>
        Dado que el Auditor sospecha de una alteración manual en los registros,<br>
        Cuando solicita la validación de un bloque de datos históricos,<br>
        Entonces el sistema debe ejecutar una verificación de firmas digitales y emitir una alerta si detecta que algún registro de temperatura fue modificado después de su captura original.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Inicialización de Entornos de Monitoreo (Crear Lab)</td>
      <td>Como: Administrador de Laboratorio. Quiero: Registrar un nuevo laboratorio configurando sus parámetros técnicos y políticas de seguridad desde el inicio. Para: Establecer una infraestructura de monitoreo que cumpla con los estándares específicos de las muestras que se almacenarán.</td>
      <td>
        <b>Escenario 1: Registro con Configuración de Umbrales (Happy Path)</b><br>
        Dado que el Administrador completa el registro de una nueva sede,<br>
        Cuando define los Safe Temperature Thresholds (Umbrales de Seguridad) y asigna la Escalation Policy,<br>
        Entonces el sistema debe validar que los parámetros sean técnicamente coherentes y habilitar el laboratorio para la vinculación de sensores.<br><br>
        <b>Escenario 2: Rechazo por Incumplimiento de Reglas (Unhappy Path)</b><br>
        Dado que el Administrador intenta crear un laboratorio sin asignar una política de escalamiento de alertas,<br>
        Cuando intenta guardar la configuración,<br>
        Entonces el sistema debe bloquear la creación y mostrar un mensaje de error de dominio: "Regla de Negocio Incumplida: Todo laboratorio de misión crítica debe tener una ruta de escalamiento definida para emergencias térmicas".
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Actualización de Parámetros Técnicos y Normativos</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Modificar la configuración técnica y los parámetros de seguridad de un laboratorio. Para: Adaptar el monitoreo a nuevos protocolos de bioseguridad o cambios en la infraestructura física de la sede.</td>
      <td>
        <b>Escenario 1: Actualización exitosa de umbrales (Happy Path)</b><br>
        Dado que el Coordinador necesita restringir el rango de temperatura de un laboratorio de vacunas,<br>
        Cuando modifica los Safe Temperature Thresholds y guarda los cambios,<br>
        Entonces el sistema debe aplicar los nuevos límites de inmediato y registrar quién hizo el cambio y por qué en el Audit Log.<br><br>
        <b>Escenario 2: Intento de configuración insegura (Unhappy Path)</b><br>
        Dado que el usuario intenta establecer un umbral de alerta que es físicamente imposible para el equipo de frío,<br>
        Cuando presiona "Guardar",<br>
        Entonces el sistema debe rechazar la edición y mostrar una advertencia: "Configuración Inválida: El umbral excede la capacidad técnica del hardware asignado".
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US24</td>
      <td>Detección Automática de Excursión Térmica</td>
      <td>Como: Sistema de Monitoreo Inteligente. Quiero: Analizar las lecturas de los sensores en tiempo real contra los umbrales de seguridad definidos (Safe Thresholds). Para: Identificar automáticamente excursiones térmicas y prevenir el uso de reactivos o muestras cuya integridad haya sido comprometida.</td>
      <td>
        <b>Escenario 1 (Happy Path): Detección y Marcado de Riesgo</b><br>
        Dado que un sensor está vinculado a una unidad con un rango de 2°C a 8°C,<br>
        Cuando la lectura recibida es de 9°C por un periodo superior al tiempo de tolerancia,<br>
        Entonces el sistema debe generar automáticamente un evento de Thermal Excursion, cambiar el estado del laboratorio a "Crítico" y disparar la alerta inmediata.<br><br>
        <b>Escenario 2 (Unhappy Path): Validación de Consistencia de Datos</b><br>
        Dado que el sistema recibe una lectura físicamente imposible (ej. -100°C) debido a un fallo del sensor,<br>
        Cuando el motor de análisis procesa el dato,<br>
        Entonces el sistema no debe marcar una excursión térmica, sino generar una alerta de "Falla Técnica/Sensor Defectuoso" para evitar falsos positivos en el reporte de calidad.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US25</td>
      <td>Generación de Alertas Preventivas basadas en Tendencias</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Recibir notificaciones preventivas cuando la tendencia de temperatura indique una proximidad al límite crítico. Para: Ejecutar acciones de mitigación antes de que ocurra una pérdida real de material biológico.</td>
      <td>
        <b>Escenario 1 (Happy Path): Alerta por Incremento Constante</b><br>
        Dado que la temperatura se mantiene dentro del rango seguro pero muestra un incremento constante de 0.5°C por hora,<br>
        Cuando el algoritmo de predicción proyecta que se superará el umbral en menos de 2 horas,<br>
        Entonces el sistema debe emitir una "Alerta Preventiva" al técnico de turno para que revise el sistema de refrigeración.<br><br>
        <b>Escenario 2 (Unhappy Path): Notificación de Umbral Predictivo</b><br>
        Dado que el sistema intenta enviar una alerta preventiva,<br>
        Cuando el canal de comunicación principal (Push/SMS) falla,<br>
        Entonces el sistema debe registrar el intento fallido y activar el canal secundario (Email corporativo) para garantizar que el aviso preventivo sea entregado.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US26</td>
      <td>Escalamiento Automático de Incidentes no Atendidos</td>
      <td>Como: Gerente de Operaciones. Quiero: Que el sistema aplique la política de escalamiento (Escalation Policy) si una alerta crítica no es reconocida en el tiempo establecido. Para: Garantizar que el personal de mayor jerarquía intervenga en situaciones de alto riesgo que no han sido gestionadas a tiempo.</td>
      <td>
        <b>Escenario 1 (Happy Path): Escalamiento a Nivel Superior</b><br>
        Dado que se ha disparado una alerta crítica y han pasado 15 minutos sin que un técnico la "Reconozca",<br>
        Cuando se cumple el tiempo límite de la política de escalamiento,<br>
        Entonces el sistema debe notificar automáticamente al Coordinador de Sede y al Gerente de Operaciones con el detalle del incidente.<br><br>
        <b>Escenario 2 (Unhappy Path): Interrupción del Escalamiento</b><br>
        Dado que un técnico reconoce la alerta justo antes de que expire el tiempo de escalamiento,<br>
        Cuando el sistema evalúa la siguiente acción,<br>
        Entonces el proceso de escalamiento automático debe detenerse, registrando que el técnico X ha tomado control del incidente.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US27</td>
      <td>Registro Obligatorio de Acciones Correctivas</td>
      <td>Como: Técnico de Laboratorio. Quiero: Documentar formalmente las medidas tomadas para resolver una anomalía térmica. Para: Cumplir con los protocolos de trazabilidad y permitir el análisis de causa raíz en el futuro.</td>
      <td>
        <b>Escenario 1 (Happy Path): Cierre con Evidencia Técnica</b><br>
        Dado que el técnico ha estabilizado la temperatura de una unidad,<br>
        Cuando registra la Corrective Action detallando la solución aplicada (ej. "Cambio de compresor"),<br>
        Entonces el sistema debe permitir el cierre del incidente y vincular la acción al log histórico de la unidad afectada.<br><br>
        <b>Escenario 2 (Unhappy Path): Rechazo de Documentación Insuficiente</b><br>
        Dado que el técnico intenta cerrar un incidente crítico con una descripción de menos de 10 caracteres o vacía,<br>
        Cuando presiona "Confirmar Resolución",<br>
        Entonces el sistema debe impedir el cierre y exigir una justificación técnica válida para asegurar la calidad de la auditoría.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US28</td>
      <td>Generación de Reporte de Auditoría Regulatoria</td>
      <td>Como: Director de Calidad / Auditor Externo. Quiero: Generar reportes consolidados e inmutables de todas las lecturas e incidentes de un periodo determinado. Para: Presentar evidencia ante entidades regulatorias (DIGEMID/ISO) que certifique la integridad de la cadena de frío.</td>
      <td>
        <b>Escenario 1 (Happy Path): Reporte con Sello Digital</b><br>
        Dado que el auditor solicita el reporte de cumplimiento del último mes,<br>
        Cuando el sistema procesa los datos y genera el PDF,<br>
        Entonces el documento debe incluir un sello digital de integridad que certifique que los datos no han sido modificados manualmente.<br><br>
        <b>Escenario 2 (Unhappy Path): Alerta por Datos Incompletos</b><br>
        Dado que hubo periodos de desconexión donde no se capturaron datos por fallas de red,<br>
        Cuando se genera el reporte de auditoría,<br>
        Entonces el sistema debe resaltar claramente los "Gaps" o vacíos de información en el reporte, indicando que esos periodos no pueden ser certificados como seguros.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US29</td>
      <td>Ejecución y Registro de Calibración de Sensores</td>
      <td>Como: Técnico de Calibración / Soporte. Quiero: Ejecutar el proceso de calibración de los sensores directamente desde el panel de configuración. Para: Garantizar la precisión de las lecturas según la norma ISO 17025 y evitar desviaciones legales en los reportes de temperatura.</td>
      <td>
        <b>Escenario 1 (Happy Path): Actualización de certificado de calibración</b><br>
        Dado que un sensor (ej. Ultra-Low Temp) muestra el estado "Needs Calibration",<br>
        Cuando el técnico completa el proceso y presiona el botón "Calibrate",<br>
        Entonces el sistema debe actualizar la fecha de "Last Cal", reiniciar el contador de cumplimiento y registrar el nuevo certificado.<br><br>
        <b>Escenario 2 (Unhappy Path): Sensor fuera de tolerancia física</b><br>
        Dado que el técnico intenta calibrar un sensor que reporta un error de hardware interno,<br>
        Cuando el sistema detecta que la desviación es mayor a la permitida técnicamente,<br>
        Entonces el sistema debe rechazar la calibración, marcar el sensor como "Out of Service" y emitir una alerta de reemplazo obligatorio.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US30</td>
      <td>Personalización de Canales de Alerta y Resúmenes de Actividad</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Configurar los canales de recepción de alertas y la frecuencia de los reportes de actividad. Para: Optimizar la comunicación de incidentes según la gravedad y evitar la "fatiga de alertas" en el personal de turno.</td>
      <td>
        <b>Escenario 1 (Happy Path): Activación de notificaciones multicanal</b><br>
        Dado que el Coordinador desea recibir alertas críticas en su móvil,<br>
        Cuando activa los interruptores de "Email Notifications" e "In-App Notifications",<br>
        Entonces el sistema debe aplicar la regla de envío inmediato para cualquier desviación categorizada como "Critical Level".<br><br>
        <b>Escenario 2 (Unhappy Path): Configuración de umbral inconsistente</b><br>
        Dado que el usuario intenta configurar un "Warning Level" mayor al "Critical Level",<br>
        Cuando intenta guardar la configuración de umbrales,<br>
        Entonces el sistema debe mostrar un error de validación lógica, impidiendo que la alerta de advertencia se dispare después de que el daño ya sea crítico.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US31</td>
      <td>Fortalecimiento de Identidad mediante Autenticación de Dos Factores (2FA)</td>
      <td>Como: Administrador del Sistema / Senior Lab Manager. Quiero: Habilitar el segundo factor de autenticación (2FA) para mi cuenta de SafeLab. Para: Añadir una capa extra de seguridad que proteja el acceso a datos sensibles de investigación contra intentos de acceso no autorizados.</td>
      <td>
        <b>Escenario 1 (Happy Path): Vinculación exitosa de dispositivo móvil</b><br>
        Dado que el usuario se encuentra en el panel de "Security & Access",<br>
        Cuando selecciona "Enable 2FA" y vincula su dispositivo móvil,<br>
        Entonces el sistema debe exigir el código de verificación en el próximo inicio de sesión, validando que solo el dueño del dispositivo pueda acceder.<br><br>
        <b>Escenario 2 (Unhappy Path): Intento de acceso con 2FA fallido</b><br>
        Dado que un usuario ingresa la contraseña correcta pero el código de 2FA es erróneo,<br>
        Cuando intenta finalizar el login,<br>
        Entonces el sistema debe bloquear el acceso, registrar el intento fallido en el log de seguridad y notificar al usuario sobre una posible brecha de cuenta.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US32</td>
      <td>Auditoría de Sesiones Activas y Control de Acceso Geográfico</td>
      <td>Como: Responsable de Seguridad (Security Officer). Quiero: Monitorear las sesiones activas y el historial de login (ubicación e IP) de mi cuenta. Para: Identificar ingresos sospechosos desde ubicaciones inusuales y revocar sesiones que puedan comprometer la integridad del laboratorio.</td>
      <td>
        <b>Escenario 1 (Happy Path): Revocación de sesión remota</b><br>
        Dado que el usuario visualiza una sesión activa en una ubicación desconocida (ej. "Zurich, CH"),<br>
        Cuando selecciona la opción de cerrar dicha sesión remota,<br>
        Entonces el sistema debe desconectar inmediatamente ese dispositivo y forzar un cambio de credenciales por seguridad.<br><br>
        <b>Escenario 2 (Unhappy Path): Visibilidad de estado de cuenta degradado</b><br>
        Dado que el sistema detecta que el usuario no ha actualizado su contraseña en el tiempo reglamentario,<br>
        Cuando se visualiza el "Account Status",<br>
        Entonces el sistema debe marcar el estado como "At Risk" (En Riesgo) y limitar el acceso a funciones críticas hasta que se cumpla con el protocolo de seguridad.
      </td>
      <td>EP04</td>
    </tr>        
    <tr>
      <td>US33</td>
      <td>Búsqueda de laboratorios</td>
      <td>Como usuario, quiero buscar laboratorios por nombre para encontrarlos rápidamente.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario escribe en la barra de búsqueda, cuando ingresa texto, entonces el sistema filtra los resultados en tiempo real.<br><br>
        <b>Escenario 2:</b> Dado que no hay coincidencias, cuando finaliza la búsqueda, entonces se muestra un mensaje de resultados vacíos.
      </td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>US34</td>
      <td>Filtrado de alertas</td>
      <td>Como usuario, quiero filtrar alertas por diferentes criterios para priorizar mis necesidades.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario selecciona un filtro de severidad o fecha, cuando aplica el filtro, entonces solo se muestran alertas correspondientes.<br><br>
        <b>Escenario 2:</b> Dado que elimina el filtro, cuando lo desactiva, entonces se muestran todas las alertas nuevamente.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US35</td>
      <td>Detalle completo de alerta</td>
      <td>Como usuario, quiero ver el detalle completo de una alerta para comprender el incidente.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario selecciona una alerta, cuando abre el detalle, entonces visualiza fecha, sensor, laboratorio y descripción.<br><br>
        <b>Escenario 2:</b> Dado que la alerta tiene acciones registradas, cuando revisa el detalle, entonces ve el historial de acciones.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US36</td>
      <td>Gestión de notificaciones por correo</td>
      <td>Como usuario, quiero activar o desactivar las notificaciones por correo para controlar cómo recibo las alertas de los laboratorios.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario accede a la configuración de notificaciones, cuando activa o desactiva el envío por correo, entonces el sistema guarda la preferencia.<br><br>
        <b>Escenario 2:</b> Dado que ocurre una alerta crítica, cuando el envío por correo está activado, entonces el sistema envía la notificación al email registrado.<br><br>
        <b>Escenario 3:</b> Dado que el envío por correo está desactivado, cuando ocurre una alerta, entonces el sistema no envía correos.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US37</td>
      <td>Visualización de tendencias históricas</td>
      <td>Como usuario, quiero visualizar tendencias de eventos para analizar patrones.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario accede a History, cuando selecciona rango de fechas, entonces el sistema filtra los eventos.<br><br>
        <b>Escenario 2:</b> Dado que existen datos suficientes, cuando revisa la vista, entonces se muestran gráficos de tendencias.
      </td>
      <td>EP03</td>
    </tr>
    <tr>
      <td>US38</td>
      <td>Edición de perfil de usuario</td>
      <td>Como usuario, quiero editar mi información personal para mantener mis datos actualizados.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario accede a su perfil, cuando modifica nombre, foto o correo, entonces el sistema permite guardar los cambios.<br><br>
        <b>Escenario 2:</b> Dado que el usuario cambia su correo electrónico, cuando confirma la actualización, entonces el sistema solicita verificación del nuevo correo.<br><br>
        <b>Escenario 3:</b> Dado que los cambios se guardan correctamente, cuando vuelve a acceder al perfil, entonces visualiza la información actualizada.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US39</td>
      <td>Notificaciones del sistema en tiempo real</td>
      <td>Como usuario, quiero recibir notificaciones visuales tras acciones importantes.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario realiza una acción exitosa, cuando el proceso termina, entonces se muestra mensaje de confirmación.<br><br>
        <b>Escenario 2:</b> Dado que ocurre un error, cuando el sistema falla, entonces se muestra notificación de error.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US40</td>
      <td>Cierre de sesión</td>
      <td>Como usuario, quiero cerrar sesión para proteger el acceso a la plataforma.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario selecciona cerrar sesión, cuando confirma, entonces el sistema finaliza la sesión activa.<br><br>
        <b>Escenario 2:</b> Dado que la sesión finaliza, cuando intenta acceder a rutas privadas, entonces es redirigido al login.
      </td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>US41</td>
      <td>Persistencia de sesión</td>
      <td>Como usuario, quiero mantener mi sesión activa para no iniciar sesión constantemente.</td>
      <td>
        <b>Escenario 1:</b> Dado que el usuario vuelve al sistema, cuando su sesión es válida, entonces accede directamente al dashboard.<br><br>
        <b>Escenario 2:</b> Dado que la sesión expira, cuando intenta acceder, entonces el sistema solicita autenticación nuevamente.
      </td>
      <td>EP04</td>
    </tr>
  </tbody>
</table>

## 3.2 Impact Mapping

![Impact Map](assets/chapter-iii/impact-mapping.png)

## 3.3 Product Backlog

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>#Orden</th>
      <th>ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01</td>
      <td>US-01</td>
      <td>Navegación a secciones principales</td>
      <td>Como visitante, quiero acceder a las distintas secciones informativas desde un menú principal para encontrar la información deseada rápidamente.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>02</td>
      <td>US-02</td>
      <td>Navegación en dispositivos móviles</td>
      <td>Como visitante desde móvil, quiero disponer de un menú adaptable para acceder a las secciones sin saturar la pantalla.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>03</td>
      <td>US-03</td>
      <td>Acceso a demo y características</td>
      <td>Como gerente de laboratorio, quiero solicitar una demo o ver características desde el primer vistazo.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>04</td>
      <td>US-04</td>
      <td>Visualización de interfaz del sistema</td>
      <td>Como prospecto, quiero ver imágenes de la plataforma para conocer su apariencia.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>05</td>
      <td>US-05</td>
      <td>Consulta de herramientas</td>
      <td>Como investigador, quiero consultar funciones principales estructuradas.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>06</td>
      <td>US-06</td>
      <td>Comparativa de solución</td>
      <td>Como jefe de calidad, quiero comparar método tradicional vs plataforma.</td>
      <td>4</td>
    </tr>
    <tr>
      <td>07</td>
      <td>US-07</td>
      <td>Revisión de testimonios</td>
      <td>Como responsable de compras, quiero leer testimonios para ganar confianza.</td>
      <td>6</td>
    </tr>
    <tr>
      <td>08</td>
      <td>US-08</td>
      <td>Consulta de planes y precios</td>
      <td>Como administrador, quiero comparar planes y funcionalidades.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>09</td>
      <td>US-09</td>
      <td>Información legal y soporte</td>
      <td>Como visitante, quiero encontrar políticas y soporte en el footer.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US-10</td>
      <td>Acceso a portal de usuarios</td>
      <td>Como visitante, quiero acceder a login y registro.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

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

Nota: Elaboración propia.

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

### 4.2.3. SEO Tags and Meta Tags

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

## 4.3. Landing Page UI Design
Para el diseño de la interfaz de la Landing Page de Safelab, el equipo ha traducido las necesidades de monitoreo crítico en una experiencia visual que transmite seguridad, limpieza y precisión.


La arquitectura de información se estructuró siguiendo un modelo de **"AIDA" (Atención, Interés, Deseo y Acción)**, asegurando que los responsables de laboratorios encuentren rápidamente la propuesta de valor: la prevención de incidentes mediante inteligencia analítica. Se priorizó una navegación vertical fluida, donde cada sección refuerza la confianza del usuario antes de llegar a los planes de suscripción.

### 4.3.1. Landing Page Wireframe

Los wireframes de Safelab fueron diseñados con un enfoque **Mobile-First**, garantizando que la jerarquía de contenido sea clara tanto en navegadores de escritorio como en dispositivos móviles.


* **Principios de Diseño:** Se aplicó el principio de proximidad para agrupar las funcionalidades clave (Dashboard, Alertas, Historial) y el uso de espacios en blanco (*negative space*) para reducir la carga cognitiva del usuario.


* **Diseño Inclusivo:** La disposición de los elementos sigue un orden lógico de lectura (patrón en F), facilitando la accesibilidad para lectores de pantalla. Los botones de acción (CTAs) como "Solicitar Demo" cuentan con un tamaño táctil adecuado para dispositivos móviles.


* **Arquitectura de Información:** Se utilizó una estructura de cuadrícula (*grid system*) de 12 columnas para Desktop y 4 para Mobile, permitiendo que bloques como "El Problema" y "La Solución" se apilen de forma coherente, manteniendo siempre la visibilidad de los beneficios principales.

![Landing Page - Wireframe](assets/chapter-iv/landingwireframe.png)

Nota: Elaboración propia en Figma.

### 4.3.2. Landing Page Mock-up

El paso al Mock-up integra el *Design System* de Safelab, aplicando la paleta de colores azul y violeta para evocar profesionalismo tecnológico.


* **Elementos de Diseño:** Se incorporaron iconografías personalizadas para cada funcionalidad, utilizando estilos lineales que mantienen la estética moderna. Las tarjetas de "Planes de Laboratorio" utilizan sombras sutiles (*box-shadows*) para generar profundidad y destacar el plan "Pro" como la opción recomendada.


* **Identidad Visual y Branding:** El logotipo de Safelab se ubica estratégicamente en el *header* persistente. Se seleccionó la tipografía **Inter** por su alta legibilidad en entornos técnicos, asegurando que las métricas y precios sean fáciles de leer.


* **Continuidad de Experiencia:** En la versión Mobile, el menú de navegación se sintetiza en un componente de "hamburguesa", mientras que los testimonios de los especialistas se presentan en un formato de carrusel optimizado para gestos táctiles. El uso de imágenes de alta fidelidad para el dashboard dentro del mock-up permite al usuario previsualizar la robustez de la herramienta antes de la conversión.

![Landing Page - Mockup](assets/chapter-iv/landingmockup.png)

Nota: Elaboración propia en Figma.

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

**Login**
- Descripción: Esta pantalla muestra el formulario para que el usuario ingrese sus credenciales y acceda la pantalla de inicio de la aplicación.
![Web Application - Wireframe 1](assets/chapter-iv/wireframe-1.png)
  Nota: Elaboración propia en Figma.

**Dashboard**
- Descripción: En esta pantalla se pueden visualizar las métricas más importantes de los sistemas de los laboratorios, como la temperatura, ventilación, detección de elementos extraños, entre otros. Esta información se muestra en gráficos y pequeñas listas para facilitar la comprensión de la información.
![Web Application - Wireframe 2](assets/chapter-iv/wireframe-2.png)
  Nota: Elaboración propia en Figma.

**Laboratorios**
- Descripción: En esta pantalla se optó por una grilla de tarjetas para visualizar los laboratorios registrados en el sistema, con información resumida de cada uno, como temperatura, ubicación, entre otros.
![Web Application - Wireframe 3](assets/chapter-iv/wireframe-3.png)
  Nota: Elaboración propia en Figma.

**Detalles de Laboratorio**
- Descripción: En esta pantalla se muestra información detallada de cada laboratorio, con gráficos en tiempo real de las métricas más importantes, como temperatura, ventilación, entre otros. Además, se muestran los indicadores de status del laboratorio, programaciones activas y actividad reciente.
![Web Application - Wireframe 4](assets/chapter-iv/wireframe-4.png)
  Nota: Elaboración propia en Figma.

**Alertas**
- Descripción: En esta pantalla se muestran las alertas generadas por el sistema. Para mostrarlas, se optó por una columna de tarjetas, donde cada tarjeta representa una alerta, con información resumida como el mensaje de la alerta, su prioridad, entre otros. Para ver la información detallada de la alerta, emerge un panel lateral derecho al hacer clic sobre ella. Además, se incluyen filtros para facilitar la búsqueda de alertas específicas.
![Web Application - Wireframe 5](assets/chapter-iv/wireframe-5.png)
  Nota: Elaboración propia en Figma.

**Historial**
- Descripción: En esta pantalla se muestra el historial de eventos relacionados con los laboratorios. Para mostrar esta información, se optó por una vista de línea de tiempo, donde cada evento se ordena de forma cronológica, con información resumida del evento. Al hacer clic sobre un evento, emerge un panel lateral derecho con la información detallada del evento. Además, se incluyen filtros para facilitar la búsqueda de eventos específicos.
![Web Application - Wireframe 6](assets/chapter-iv/wireframe-6.png)
  Nota: Elaboración propia en Figma.

**Nuevo Laboratorio**
- Descripción: En esta pantalla se muestra un formulario para registrar un nuevo laboratorio en el sistema. El formulario se divide en secciones para facilitar su llenado, como información general del laboratorio, sistemas y sensores, entre otros.
![Web Application - Wireframe 7](assets/chapter-iv/wireframe-7.png)
  Nota: Elaboración propia en Figma.

### 4.4.2. Web Applications Wireflow Diagrams

### **Wireflow 1**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo registrar un nuevo laboratorio en el sistema. Para ello, debo llenar la información del laboratorio y los detalles de sus sistemas y sensores.
![wireflow 1](assets/chapter-iv/wireflow-1.png)
  Nota: Elaboración propia.

### **Wireflow 2**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo visualizar la información detallada de un laboratorio existente.
![wireflow 2](assets/chapter-iv/wireflow-2.png)
  Nota: Elaboración propia.

### **Wireflow 3**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo revisar las alertas de alta prioridad generadas por el sistema para tomar acciones correctivas. Para ello, debo usar los filtros disponibles.
![wireflow 3](assets/chapter-iv/wireflow-3.png)
  Nota: Elaboración propia.

### 4.4.3. Web Applications Mock-ups

**Login**
- Objetivo: Permitir al usuario ingresar sus credenciales y acceder a la aplicación.
![Web Application - mockup 1](assets/chapter-iv/mockup-1.png)
  Nota: Elaboración propia en Figma.

**Dashboard**
- Objetivo: Mostrar las métricas más importantes de los sistemas de los laboratorios.
![Web Application - mockup 2](assets/chapter-iv/mockup-2.png)
  Nota: Elaboración propia en Figma.

**Laboratorios**
- Objetivo: Visualizar los laboratorios existentes y registrados en el sistema. Facilitar la búsqueda mediante filtros y presentación de información resumida de cada laboratorio.
![Web Application - mockup 3](assets/chapter-iv/mockup-3.png)
  Nota: Elaboración propia en Figma.

**Detalles de Laboratorio**
- Objetivo: Mostrar la información detallada de de los sistemas de mantenimiento de cada laboratorio.
Se muestra la actividad reciente del laboratorio, programaciones activas y los indicadores de status del laboratorio.
![Web Application - mockup 4](assets/chapter-iv/mockup-4.png)
  Nota: Elaboración propia en Figma.

**Alertas**
- Objetivo: Mostrar las alertas generadas por el sistema y permitir su gestión. Para resolver las alertas se muestra información detallada de cada alerta, como el mensaje, su prioridad, entre otros. Además, se incluyen filtros para facilitar la búsqueda de alertas específicas.
![Web Application - mockup 5](assets/chapter-iv/mockup-5.png)
  Nota: Elaboración propia en Figma.

**Historial**
- Objetivo: Mostrar el historial de eventos relacionados con los laboratorios. Por defecto, se muestra la información en una vista de línea de tiempo, donde cada evento se ordena de forma cronológica, con información resumida del evento.
![Web Application - mockup 6](assets/chapter-iv/mockup-6.png)
  Nota: Elaboración propia en Figma.

**Nuevo Laboratorio**
- Descripción: En esta pantalla se muestra un formulario para registrar un nuevo laboratorio en el sistema. El formulario se divide en secciones para facilitar su llenado, como información general del laboratorio, sistemas y sensores, entre otros.
![Web Application - mockup 7](assets/chapter-iv/mockup-7.png)
  Nota: Elaboración propia en Figma.

**Configuracion**
- La sección de Settings de Safelab está diseñada como el centro neurálgico de personalización y control del sistema. Su objetivo principal es permitir que los responsables de laboratorio y administradores ajusten la precisión de los instrumentos de medición, gestionen la seguridad de los datos y personalicen la experiencia de usuario.
![Web Application - mockup 7](assets/chapter-iv/settings1.png)
![Web Application - mockup 7](assets/chapter-iv/settings2.png)
![Web Application - mockup 7](assets/chapter-iv/settings3.png)
![Web Application - mockup 7](assets/chapter-iv/settings4.png)

Nota: Elaboración propia en Figma.


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
Nota: Elaboración propia.

**Userflow 2**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo visualizar la información detallada de un laboratorio existente.
- Happy Paths:
    - El sistema muestra la información detallada del laboratorio seleccionado.
- Unhappy Paths:
    - El sistema muestra un pop-up que indica que no se pudo cargar la información del laboratorio.

![userflow 2](assets/chapter-iv/userflow-2.png)
Nota: Elaboración propia.

**Userflow 3**
- User Persona: Supervisor de laboratorio
- User Goal: Como supervisor de laboratorio, deseo revisar las alertas de alta prioridad generadas por el sistema para tomar acciones correctivas. Para ello, debo usar los filtros disponibles.
- Happy Paths:
    - El sistema muestra las alertas filtradas por alta prioridad.
- Unhappy Paths:
    - El sistema muestra un pop-up que indica que no se pudieron cargar las alertas filtradas.

![userflow 3](assets/chapter-iv/userflow-3.png)
Nota: Elaboración propia.

## 4.5. Web Applications Prototyping

**Landing Page Presentation**

![landing page presentation evidence](assets/chapter-iv/landing-page-presentation-evidence.png)

[Link de la presentación](https://upcedupe-my.sharepoint.com/:v:/g/personal/u201817507_upc_edu_pe/IQCmLmkatLNfRodxmcXY4QRUAahuQUi-b5KDhY58uA4VZxE?e=Gj9ceu&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

En esta fase, el equipo realizó una inmersión técnica de nivel detallado para refinar el flujo de trabajo de **SafeLab**. A diferencia de la etapa anterior, el *Design-Level Event Storming* permitió identificar no solo qué sucede en el sistema (**Eventos**), sino también quién inicia la acción (**Actores**), qué intención tienen (**Comandos**) y qué reglas rigen el comportamiento del software (**Políticas**).

Durante una sesión de diseño enfocada, se estructuraron los elementos siguiendo la lógica de los sub-dominios críticos para una plataforma SaaS de monitoreo clínico. El resultado es un modelo que integra la captura de datos de sensores, la gestión de activos hospitalarios y la automatización inteligente, garantizando que cada interacción esté alineada con el lenguaje ubicuo y los objetivos de "Desperdicio Cero" de la startup.

![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext.jpg)
Nota: Elaboración propia en Miro.

---

### Explicación de los Bounded Contexts Identificados

A continuación, se detallan los cinco contextos delimitados que componen la arquitectura de la solución:

#### 1. IoT Telemetry & Environment Monitoring
Este contexto actúa como la capa de ingesta de datos. Se encarga de la comunicación directa con el hardware (sensores) y la normalización de las métricas ambientales. Su responsabilidad es garantizar que cada lectura de temperatura o CO2 sea capturada y validada antes de ser procesada por el resto del sistema, gestionando además la salud de la conexión de los dispositivos.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext11.jpg)
Nota: Elaboración propia en Miro.

#### 2. Lab Asset & Infrastructure Management
Orientado a la gestión de recursos físicos, este contexto administra el ciclo de vida de las refrigeradoras, congeladores y sistemas de ventilación (HVAC). Su enfoque principal es el mantenimiento preventivo y la organización jerárquica del laboratorio (edificios, pisos y áreas), asegurando que la infraestructura física sea apta para el almacenamiento bioclínico.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext2.jpg)
Nota: Elaboración propia en Miro.

#### 3. Intelligent Alerting & Incident Response
Representa el cerebro reactivo de la plataforma. Analiza las anomalías detectadas en la telemetría para clasificar incidentes según su gravedad (*Critical/Warning*). Gestiona la omnicanalidad de las notificaciones hacia el personal de turno y rastrea las acciones de mitigación tomadas por los biólogos, cerrando la brecha entre la falla técnica y la intervención humana.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext3.jpg)
Nota: Elaboración propia en Miro.

#### 4. Operational Compliance & Activity Logging
Este contexto de soporte garantiza la integridad legal de la operación. Registra de forma inmutable cada evento relevante del sistema, desde calibraciones de sensores hasta resoluciones de alertas. Su función principal es la generación automatizada de reportes de cumplimiento (*Compliance Reports*) que permitan al laboratorio superar auditorías normativas como la ISO 15189.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext4.jpg)
Nota: Elaboración propia en Miro.

#### 5. Smart Automation & Scheduling
Es el componente proactivo que permite a SafeLab ejecutar acciones correctivas automáticas. Gestiona horarios de funcionamiento y reglas lógicas (por ejemplo, activación de ventilación ante picos de CO2). Este contexto permite que el sistema actúe sobre los actuadores físicos, reduciendo la dependencia de la intervención manual constante.
![EventStorming_Desing-Level](assets/chapter-iv/BoundedContext5.jpg)
Nota: Elaboración propia en Miro.

### 4.6.2. Software Architecture Context Diagram

El diagrama de contexto del sistema muestra la relación entre el sistema y los actores externos, proporcionando una visión general de la arquitectura del sistema y sus interacciones con el entorno externo.

![Software Architecture Context Diagram](./assets/chapter-iv/4.6.2_Software_Architecture_Context_Diagram.png)
Nota: Elaboración propia en Structurizr.

### 4.6.3. Software Architecture Container Diagrams

Los diagramas de contenedores representan los distintos elementos que conforman el sistema, como aplicaciones web, bases de datos o microservicios, y muestran cómo se relacionan entre ellos. Ofrecen una perspectiva general de la arquitectura, resaltando las funciones de cada contenedor y la forma en que interactúan.

![Software Architecture Container Diagrams](./assets/chapter-iv/4.6.3_Software_Architecture_Container_Diagrams.png)
Nota: Elaboración propia en Structurizr.

### 4.6.4. Software Architecture Components Diagrams

En esta sección, se presentan los diagramas de componentes de la arquitectura de software. Estos diagramas detallan los diferentes componentes que conforman el sistema, sus responsabilidades y cómo interactúan entre sí. 

Para el diseño interno de cada **Bounded Context**, se ha implementado una **Arquitectura en Capas Orientada al Dominio**. Como se observa en los diagramas, el flujo mantiene un alto nivel de cohesión:

- **Controladores:** Actúan como la capa de presentación (interfaces de entrada).
- **Servicios de Aplicación:** Orquestan los casos de uso interactuando con la lógica del dominio subyacente.
- **Repositorios:** Abstraen la capa de infraestructura garantizando que el modelo de negocio sea agnóstico a la tecnología de persistencia.

---

#### Bounded Context: Intelligent Alerting & Incident Response

Este bounded context engloba la gestión completa del ciclo de vida de las incidencias, desde su detección inicial hasta su resolución. Los componentes aquí dibujados coordinan la evaluación de lecturas contra umbrales, clasificación por gravedad y notificaciones multicanal, orquestando las entidades `Alert`, `Incident`, `Threshold` y `Notification`.

![Bounded Context: Intelligent Alerting & Incident Response](./assets/chapter-iv/Bounded_Context_Intelligent_Alerting_Incident_Response.png)
Nota: Elaboración propia en Structurizr.

#### Bounded Context: IoT Telemetry & Environment Monitoring

Este bounded context es el motor de fuerza bruta del sistema, encargado de la ingesta masiva de datos provenientes de los sensores de hardware, la normalización de unidades de medida (ºC, ppm, %) y la provisión del estado Live para los tableros. En este diagrama se incluyen componentes para las entidades de `Sensor`, `Metric`, `Reading` y `EnvironmentalGateway`.

![Bounded Context: IoT Telemetry & Environment Monitoring](./assets/chapter-iv/Bounded_Context_IoT_Telemetry_Environment_Monitoring.png)
Nota: Elaboración propia en Structurizr.

#### Bounded Context: Lab Asset & Infrastructure Management

Este bounded context asume la responsabilidad de controlar el ciclo de vida de los espacios físicos y el hardware estructural del laboratorio, así como la programación de mantenimientos preventivos y correctivos. Sus diagramas de componentes incluyen la gestión de entidades como `Laboratory`, `Equipment` (Refrigeradores, HVAC), `MaintenanceSchedule` y `Location`.

![Bounded Context: Lab Asset & Infrastructure Management](./assets/chapter-iv/Bounded_Context_Lab_Asset_Infrastructure_Management.png)
Nota: Elaboración propia en Structurizr.

#### Bounded Context: Operational Compliance & Activity Logging

Este bounded context actúa como el cerebro auditor del sistema. Registra de manera inmutable el **quién, cuándo y qué** de cada evento operativo para garantizar la trazabilidad requerida por las normas ISO y entidades reguladoras. Sus entidades principales son `ActivityLog`, `AuditReport` y `ComplianceStandard`.

![Bounded Context: Operational Compliance & Activity Logging](./assets/chapter-iv/Bounded_Context_Operational_Compliance_Activity_Logging.png)
Nota: Elaboración propia en Structurizr.

#### Bounded Context: Smart Automation & Scheduling

Este bounded context se encarga de ejecutar acciones mecánicas o lógicas de forma automatizada, basadas en temporizadores o reglas de negocio reactivas. En este diagrama se representa la interacción entre componentes que manejan las entidades `Schedule`, `AutomationRule` y `ActuatorCommand`.

![Bounded Context: Smart Automation & Scheduling](./assets/chapter-iv/Bounded_Context_Smart_Automation_Scheduling.png)
Nota: Elaboración propia en Structurizr.

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

El diagrama de clases de SafeLab representa la estructura estática del sistema, detallando las entidades fundamentales, sus atributos, comportamientos (métodos) y las relaciones que permiten la lógica de negocio. El diseño se ha organizado siguiendo los límites de los *Bounded Contexts* identificados en el *Event Storming*, asegurando que la implementación técnica respete el lenguaje ubicuo del dominio.

El siguiente Diagrama de Clases ha sido diseñado aplicando estrictamente los principios de Domain-Driven Design (DDD) para modelar el núcleo de negocio de SafeLab. A diferencia de un modelo de datos tradicional (CRUD), este diagrama refleja el comportamiento y las reglas de negocio de un sistema de misión crítica. La arquitectura se divide en Bounded Contexts (Contextos Delimitados) altamente desacoplados, comunicados mediante referencias por ID y Domain Events (Eventos de Dominio). Se ha hecho una clara distinción entre Aggregate Roots (raíces de agregación que garantizan la consistencia), Entities (objetos con identidad a lo largo del tiempo) y Value Objects (objetos inmutables que describen características).

![Class Diagram](./assets/chapter-iv/diagramadeclasesfinal.png)
Nota: Elaboración propia.

### Laboratory Management
Este es el contexto estructural del dominio. Modela la jerarquía física y operativa de la infraestructura a través del Aggregate Root Laboratory, que contiene StorageUnits (unidades de almacenamiento). Aquí residen las reglas de negocio sobre la integridad física y la capacidad de reaccionar ante emergencias, orquestando acciones como la activación de MitigationSystems (sistemas de ventilación o enfriamiento de respaldo) en base a los umbrales térmicos configurados.

![Class Diagram](./assets/chapter-iv/diagramadeclases1.png)
Nota: Elaboración propia.

### Monitoring
El motor telemétrico de SafeLab. Gestionado por el Aggregate Root Sensor, este contexto procesa el flujo continuo de lecturas de temperatura. No solo almacena datos, sino que aplica lógica de hardware crítico: verifica el estado de la batería, administra los certificados de calibración técnica (CalibrationRecord) y, lo más importante, es el encargado de detectar desviaciones térmicas y emitir el evento de dominio ThermalExcursionDetected para alertar al resto del sistema.

![Class Diagram](./assets/chapter-iv/diagramadeclases2.png)
Nota: Elaboración propia.

### Incident Management
Diseñado para la gestión reactiva y correctiva. Su Aggregate Root, Incident, escucha los eventos del contexto de monitoreo e inicia un ciclo de vida de resolución. Aplica reglas de negocio vitales como la EscalationPolicy (escalamiento jerárquico si una alerta no es atendida a tiempo) y exige el registro obligatorio de una CorrectiveAction (acción correctiva con sustento técnico) antes de permitir que un incidente crítico sea marcado como resuelto.

![Class Diagram](./assets/chapter-iv/diagramadeclases3.png)
Nota: Elaboración propia.

### Compliance
El contexto legal y regulatorio. Es un entorno de solo lectura que consolida la información para auditorías. Registra un AuditTrail (trazabilidad forense inmutable) de cada acción crítica y resolución de incidentes, generando el ComplianceReport. Su diseño garantiza que los datos históricos no puedan ser manipulados, cumpliendo con las normativas ISO y los estándares de entidades reguladoras de salud.


![Class Diagram](./assets/chapter-iv/diagramadeclases4.png)
Nota: Elaboración propia.

### IAM
Encargado de la seguridad perimetral y el control de acceso corporativo. Su Aggregate Root es User, el cual gestiona la autenticación, la protección contra fuerza bruta y el control de sesiones. Se incluyen funcionalidades avanzadas de seguridad como el estado de la cuenta (AccountStatus) y la activación del segundo factor de autenticación (enable2FA), garantizando que solo personal autorizado y con roles específicos pueda tomar decisiones operativas.


![Class Diagram](./assets/chapter-iv/diagramadeclases5.png)
Nota: Elaboración propia.

### Shared
Este contexto actúa como el núcleo de tipos de datos compartidos en todo el sistema. Contiene Value Objects inmutables como TemperatureReading, Threshold y TimeRange. Al encapsular lógica de validación básica (como verificar si una temperatura excede un límite) dentro de estos objetos, evitamos la duplicación de código y garantizamos que los conceptos fundamentales del dominio se traten de manera uniforme en todos los demás contextos.

![Class Diagram](./assets/chapter-iv/diagramadeclases6.png)
Nota: Elaboración propia.


## 4.8. Database Design

### 4.8.1. Database Diagrams

El diseño de la base de datos de **SafeLab** ha sido normalizado para garantizar la integridad referencial y la eficiencia en la consulta de grandes volúmenes de telemetría. A diferencia del diagrama de clases, este modelo se enfoca en la persistencia de datos mediante el uso de Claves Primarias (**PK**) y Claves Foráneas (**FK**).

El siguiente Diagrama de Entidad-Relación (ERD) representa la persistencia física del modelo de dominio de SafeLab en una base de datos relacional (como PostgreSQL). El diseño traduce la arquitectura DDD en esquemas de datos altamente optimizados y normalizados. Como decisión arquitectónica clave, los Value Objects del modelo de dominio (como Location o Threshold) han sido aplanados (flattening); es decir, en lugar de crear tablas separadas que requerirían uniones (JOINs) costosas en rendimiento, sus propiedades se han integrado como columnas directas en las tablas de sus entidades anfitrionas (ej. threshold_min y threshold_max dentro de la tabla storage_units). Además, se mantiene el principio de desacoplamiento entre contextos mediante el uso estricto de Foreign Keys y el almacenamiento de datos semi-estructurados usando JSONB (para la gestión dinámica de permisos). La trazabilidad está garantizada mediante la tabla centralizada audit_trails, la cual indexa las acciones operativas sin acoplar rígidamente el contexto de Compliance con el resto del sistema, logrando así una base de datos robusta, escalable y lista para auditorías regulatorias.

![Database Diagram](./assets/chapter-iv/diagramabasedatosfinal.png)
Nota: Elaboración propia.

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

## 5.1.1. Software Development Environment Configuration

Para el desarrollo de SafeLab, utilizaremos el siguiente conjunto de herramientas, respetando las restricciones tecnológicas del curso:

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Actividad</th>
      <th>Producto</th>
      <th>Propósito / Uso</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Project Management</td>
      <td>Jira Software</td>
      <td>Gestión del Product Backlog, planificación de Sprints y seguimiento de tareas mediante tableros Kanban.</td>
    </tr>
    <tr>
      <td>Requirements Management</td>
      <td>UXPressia</td>
      <td>Elaboración de artefactos de descubrimiento (User Personas, Empathy Maps) para la definición de requisitos.</td>
    </tr>
    <tr>
      <td>UX/UI Design</td>
      <td>Figma</td>
      <td>Diseño de la guía de estilo, prototipos de baja fidelidad (wireframes) y alta fidelidad (mockups).</td>
    </tr>
    <tr>
      <td>Software Development (Backend)</td>
      <td>IntelliJ IDEA</td>
      <td>IDE para el desarrollo de los RESTful Web Services utilizando Java y Spring Boot.</td>
    </tr>
    <tr>
      <td>Software Development (Frontend)</td>
      <td>Visual Studio Code</td>
      <td>IDE para el desarrollo de la Web Application (Angular) y el Landing Page.</td>
    </tr>
    <tr>
      <td>Version Control</td>
      <td>GitHub</td>
      <td>Sistema de control de versiones distribuido para el alojamiento y gestión de repositorios.</td>
    </tr>
    <tr>
      <td>Documentation (API)</td>
      <td>Swagger / OpenAPI</td>
      <td>Herramienta para la documentación técnica y pruebas de los endpoints de la API.</td>
    </tr>
  </tbody>
</table>

## 5.1.2. Source Code Management

El control de versiones se realizará en GitHub bajo una organización pública. Se han implementado repositorios independientes para garantizar la modularidad y el despliegue continuo de cada componente:

* **Landing Page Repository:** [https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page](https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page)

**A. Estrategia de Branching (GitFlow)**

Se implementará el modelo GitFlow para asegurar un ciclo de vida de desarrollo robusto y ordenado:

* **main branch:** Contiene exclusivamente el código en producción. Cada cambio en esta rama debe estar etiquetado con una versión estable.

* **develop branch:** Rama principal de integración donde reside el código más reciente de desarrollo.

* **feature branches:** Ramas temporales para el desarrollo de nuevas User Stories.
  * Convención: `feature/short-description` (ej. `feature/order-registration`).

* **release branches:** Ramas de preparación para despliegues a producción, permitiendo correcciones menores y preparación de metadatos.
  * Convención: `release/vX.Y.Z` (siguiendo Semantic Versioning).

* **hotfix branches:** Para correcciones críticas inmediatas en la rama main.
  * Convención: `hotfix/issue-description`.

**B. Mensajes de Commit (Conventional Commits)**

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

**A. HTML & CSS**
Se seguirá la **Google HTML/CSS Style Guide**.

* **HTML:** Se utilizará una estructura semántica (uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`). La indentación será de 2 espacios. Los atributos de los elementos deben estar en minúsculas y los valores entre comillas dobles.

* **CSS:** Se utilizará la metodología **BEM (Block Element Modifier)** para el nombramiento de clases, facilitando el mantenimiento de los componentes de la interfaz.

* **Naming Convention:** Se aplicará `kebab-case` para IDs y nombres de clases (ej. `sensor-card`, `alert-status-critical`).

* **Colors & Units:** Se priorizará el uso de variables CSS para la paleta de colores corporativa y unidades relativas (`rem`, `em`, `%`) para asegurar que el diseño sea adaptable (responsive).

**B. JavaScript & TypeScript**
Se seguirá la **Google TypeScript Style Guide**.

* **Variables y Funciones:** Se utilizará `camelCase` (ej. `getSensorReading`, `updateLaboratoryStatus`). Los nombres deben ser semánticos; se prefiere `isTemperatureHigh` sobre `tempCheck`.

* **Clases e Interfaces:** Se utilizará `PascalCase` (ej. `EnvironmentMonitor`, `ISensorData`). Las interfaces llevarán el prefijo "I" para distinguirlas claramente.

* **Estructura:** Se utilizará `const` por defecto y `let` solo si el valor requiere reasignación. Se evitará el uso de `var`. Se implementarán funciones de flecha (**Arrow Functions**) para una sintaxis más limpia.

* **Asincronía:** Se utilizará exclusivamente `async/await` para el manejo de peticiones al API, evitando el anidamiento de promesas.

**C. Java (Backend - Spring Boot)**
Se seguirá la **Google Java Style Guide** y las convenciones oficiales de **Spring Framework**.

* **Naming:** `PascalCase` para clases (ej. `LaboratoryController`, `SensorService`) y `camelCase` para métodos y variables (ej. `calculateAverageHumidity`).

* **Arquitectura:** Se respetará estrictamente el patrón por capas: Controller, Service, Repository, Entity y DTO (Data Transfer Object).

* **API REST:** Los endpoints utilizarán sustantivos en plural y minúsculas (ej. `/api/v1/laboratories`, `/api/v1/sensors/{id}/logs`). Se aplicarán los verbos HTTP de forma correcta (GET para consulta, POST para creación, etc.).

* **Annotations:** Se emplearán anotaciones de **Lombok** (como `@Getter`, `@Setter`, `@NoArgsConstructor`) para mantener el código limpio y libre de boilerplate.

**D. Gherkin**
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

<table border="1" cellpadding="6" cellspacing="0">
  <thead>
    <tr>
      <th>Producto</th>
      <th>Entorno de Despliegue</th>
      <th>Pipeline / Herramienta</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Landing Page</strong></td>
      <td>Vercel / GitHub Pages</td>
      <td>GitHub Actions</td>
    </tr>
    <tr>
      <td><strong>Web Services (API)</strong></td>
      <td>Azure App Service / Render</td>
      <td>Docker / Maven Build</td>
    </tr>
    <tr>
      <td><strong>Web Application</strong></td>
      <td>Firebase Hosting / Vercel</td>
      <td>Angular CLI / GitHub Actions</td>
    </tr>
  </tbody>
</table>

**CONFIGURACIÓN POR COMPONENTE:**

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

**CONSIDERACIONES DE SEGURIDAD Y DOMINIO:**

* **SSL/TLS:** Todos los productos cuentan con certificados de seguridad para garantizar que la transmisión de datos entre los sensores de laboratorio y la aplicación sea cifrada.

* **Integración:** La Web Application está configurada para consumir los servicios del RESTful API mediante el intercambio de recursos de origen cruzado (**CORS**), permitiendo únicamente peticiones desde los dominios autorizados de la solución.

## 5.2. Landing Page, Services & Applications Implementation

## 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

<table border="1" cellspacing="0" cellpadding="6">
    <tr>
        <th><strong>Sprint #</strong></th>
        <td>Sprint 1</td>
    </tr>
    <tr>
        <th><strong>Resumen del Sprint Planning</strong></th>
        <td></td>
    </tr>
    <tr>
        <th><strong>Fecha</strong></th>
        <td>2026-04-14</td>
    </tr>
    <tr>
        <th><strong>Hora</strong></th>
        <td>3:00 PM</td>
    </tr>
    <tr>
        <th><strong>Ubicación</strong></th>
        <td>Google Meet</td>
    </tr>
    <tr>
        <th><strong>Preparado por</strong></th>
        <td>Manuel Angel Sanchez Arenas</td>
    </tr>
    <tr>
        <th><strong>Asistentes a la reunión de planificación</strong></th>
        <td>
            Manuel Angel Sanchez Arenas,<br>
            Jean Niels Arizabal Condori,<br>
            Esteban Eduardo Chavez Bardales,<br>
            Jhon Jordy Jaramillo Mayta
        </td>
    </tr>
    <tr>
        <th><strong>Resumen del Sprint 0 (Revisión)</strong></th>
        <td>No hubo Sprint 0 previo.</td>
    </tr>
    <tr>
        <th><strong>Resumen del Sprint 0 (Retrospectiva)</strong></th>
        <td>No hubo Sprint 0 previo.</td>
    </tr>
</table>

**Objetivo del Sprint y User Stories**

<table border="1" cellspacing="0" cellpadding="6">
  <tr>
    <th><strong>Item</strong></th>
    <th><strong>Descripción</strong></th>
  </tr>
  <tr>
    <td><strong>Objetivo del Sprint 1</strong></td>
    <td>
      Nuestro enfoque está en implementar la versión inicial de la Landing Page de Safelab.<br>
      Creemos que entrega una primera aproximación completa de la plataforma a los clientes.<br>
      Esto se confirmará cuando la Landing Page esté desplegada en vivo en GitHub Pages y sea accesible desde cualquier dispositivo.
    </td>
  </tr>
  <tr>
    <td><strong>Velocidad del Sprint 1</strong></td>
    <td>32 Story Points</td>
  </tr>
  <tr>
    <td><strong>Suma de Story Points</strong></td>
    <td>32</td>
  </tr>
</table>

### 5.2.1.2. Aspect Leaders and Collaborators

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Miembro del equipo</th>
      <th>Usuario de GitHub</th>
      <th>Landing Page (L/C)</th>
      <th>Documentación (L/C)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Manuel Sanchez</td>
      <td>@manuels7a</td>
      <td>C</td>
      <td>L</td>
    </tr>
    <tr>
      <td>Jean Arizabal</td>
      <td>@JeanArizabal</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Esteban Chavez</td>
      <td>@ECEB0704</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Jhon Jaramillo</td>
      <td>@Marklnz1</td>
      <td>L</td>
      <td>C</td>
    </tr>
  </tbody>
</table>

### 5.2.1.3. Sprint Backlog 1
**Sprint Objective:**
Implementar las secciones de la Landing Page como Funcionalidades, Beneficios, Pricing y Contacto.

<h4>Tabla de Sprint Backlog</h4>

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Historia de Usuario</th>
      <th>Elemento de trabajo / Tarea</th>
      <th>Descripción</th>
      <th>Estimación (Horas)</th>
      <th>Asignado a</th>
      <th>Estado</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-01</td>
      <td>Navegación a secciones principales</td>
      <td>Como visitante, quiero acceder a las distintas secciones informativas desde un menú principal para encontrar la información deseada rápidamente.</td>
      <td>3</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US-02</td>
      <td>Navegación en dispositivos móviles</td>
      <td>Como visitante desde móvil, quiero disponer de un menú adaptable para acceder a las secciones sin saturar la pantalla.</td>
      <td>7</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US-03</td>
      <td>Acceso a demo y características</td>
      <td>Como gerente de laboratorio, quiero solicitar una demo o ver características desde el primer vistazo.</td>
      <td>8</td>
      <td>Jhon Jaramillo</td>
      <td>Pendiente</td>
    </tr>
    <tr>
      <td>US-04</td>
      <td>Visualización de interfaz del sistema</td>
      <td>Como prospecto, quiero ver imágenes de la plataforma para conocer su apariencia.</td>
      <td>5</td>
      <td>Jean Niels</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US-05</td>
      <td>Consulta de herramientas</td>
      <td>Como investigador, quiero consultar funciones principales estructuradas.</td>
      <td>3</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US-06</td>
      <td>Comparativa de solución</td>
      <td>Como jefe de calidad, quiero comparar método tradicional vs plataforma.</td>
      <td>2</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    </tr>
    <tr>
      <td>US-07</td>
      <td>Revisión de testimonios</td>
      <td>Como responsable de compras, quiero leer testimonios para ganar confianza.</td>
      <td>3</td>
      <td>Esteban Chavez</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US-08</td>
      <td>Consulta de planes y precios</td>
      <td>Como administrador, quiero comparar planes y funcionalidades.</td>
      <td>5</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    </tr>
    <tr>
      <td>US-09</td>
      <td>Información legal y soporte</td>
      <td>Como visitante, quiero encontrar políticas y soporte en el footer.</td>
      <td>1</td>
      <td>Manuel Sanchez</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US-10</td>
      <td>Acceso a portal de usuarios</td>
      <td>Como visitante, quiero acceder a login y registro.</td>
      <td>5</td>
      <td>Jhon Jaramillo</td>
      <td>Pendiente</td>
    </tr>
  </tbody>
</table>

### 5.2.1.4. Development Evidence for Sprint Review

Esta tabla lista los commits realizados durante los primeros sprints de desarrollo, incluyendo el trabajo en la Landing Page, documentación y configuración del proyecto.

<table border="1">
  <thead>
    <tr>
      <th>Repositorio</th>
      <th>Rama</th>
      <th>ID de Commit</th>
      <th>Mensaje de Commit</th>
      <th>Descripción de Commit</th>
      <th>Fecha de Commit</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>landing-page</td><td>main</td><td>bf714a3</td><td>docs: minor documentation update and code cleanup</td><td></td><td>26/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>c80a160</td><td>Merge pull request #2 from upc-pre-1ASI0729-11834-Especialistas/develop</td><td></td><td>24/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>e9d8c85</td><td>feat: enhance feature cards with incident management, forensic audit and automated response</td><td></td><td>24/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>80584ca</td><td>feat: replace testimonial placeholder icons with real avatar images</td><td></td><td>23/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>dbb9177</td><td>Merge pull request #1 from upc-pre-1ASI0729-11834-Especialistas/develop</td><td></td><td>23/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>42e0112</td><td>feat: add testimonials section with user reviews and navigation links</td><td></td><td>23/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>e64e083</td><td>Merge branch 'release/v1.0.0' into main for production</td><td></td><td>20/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>7c53f7f</td><td>feat(landing): add responsive footer with brand info and navigation links</td><td></td><td>20/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>5637bab</td><td>feat(landing): add pricing section and fix navigation ux</td><td></td><td>20/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>5c48a3d</td><td>feat: implement interactive hero carousel and refine UI styles</td><td></td><td>20/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>a710920</td><td>style: align feature card titles to the right of icons</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>659bc84</td><td>Merge branch 'feature/funcionalidades' into develop</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>7beeabc</td><td>feat: create card grid for key features</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>38e41ca</td><td>style: enhance comparison section shadow and contrast</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>fae6194</td><td>Merge branch 'feature/problema-solucion' into develop</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>16a225e</td><td>feat: add problem and solution comparison section</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>98fe9c2</td><td>chore: remove unused assets folder</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>72d2a4d</td><td>Merge branch 'feature/hero-section' into develop</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>5a4d700</td><td>feat: build hero section</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>efac5ac</td><td>Merge branch 'feature/navbar' into develop</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>26d4302</td><td>feat: build responsive navbar</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>264037c</td><td>Merge branch 'feature/setup-inicial' into develop</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>2420f21</td><td>chore: initial setup and global CSS variables</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>ee1f6dc</td><td>chore: fix .gitignore encoding</td><td></td><td>18/04/2026</td></tr>
    <tr><td>landing-page</td><td>main</td><td>8b944ed</td><td>chore: initial commit con gitignore</td><td></td><td>17/04/2026</td></tr>
  </tbody>
</table>

### 5.2.1.5. Execution Evidence for Sprint Review

Las principales secciones de la Landing Page de Safelab fueron desarrolladas y desplegadas exitosamente. A continuación se presentan las evidencias correspondientes de la implementación.

<ul>
  <li><strong>Hero Section</strong><br><img src="./assets/chapter-v/evidence-hero-section.png" alt="Hero Section"></li>
  <li><strong>Features Section</strong><br><img src="./assets/chapter-v/evidence-features-section.png" alt="Features Section"></li>
  <li><strong>Solution Section</strong><br><img src="./assets/chapter-v/evidence-solution-section.png" alt="Solution Section"></li>
  <li><strong>Pricing Section</strong><br><img src="./assets/chapter-v/evidence-pricing-section.png" alt="Pricing Section"></li>
  <li><strong>Testimonial Section</strong><br><img src="./assets/chapter-v/evidence-testimonial-section.png" alt="Testimonial Section"></li>
</ul>

<p><strong>Enlace a Demo en Vivo:</strong><br>
<a href="https://upc-pre-1asi0729-11834-especialistas.github.io/landing-page/#">Safelab Landing Page</a></p>

### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este Sprint el equipo se enfocó en el desarrollo y el despliegue de la Landing Page de Safelab, motivo por el cual no se implementaron ni documentaron endpoints relacionados a Web Services.
Los avances relacionados al desarrollo del frontend y backend, así como la documentación de la API con OpenAPI, están programados para los próximos Sprints, donde se abordarán las funcionalidades específicas del sistema de monitoreo de laboratorios y la integración con sensores IoT.

### 5.2.1.7. Software Deployment Evidence for Sprint Review

El despliegue inicial de la Landing Page de FuelTrack fue realizado exitosamente utilizando GitHub Pages.

<ul>
  <li><strong>URL de la Landing Page:</strong> <a href="https://upc-pre-1asi0729-11834-especialistas.github.io/landing-page/#" target="_blank">https://upc-pre-1asi0729-11834-especialistas.github.io/landing-page/#</a></li>
  <li><strong>Repositorio:</strong> <a href="https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page" target="_blank">https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page</a></li>
</ul>

### 5.2.1.8. Team Collaboration Insights during Sprint

Nuestro grupo, Especialistas, gestionó los entregables mediante GitHub, WhatsApp y Google Meet durante el Sprint. Las actividades principales se centraron en el desarrollo y despliegue de la Landing Page.

**Evidencia de Colaboración:**

![Team Collaboration Evidence](assets/chapter-v/evidence-team-collaboration-insights.png)

**Principales Herramientas de Comunicación:**
- Github: Para el control de versiones, gestión de issues y revisión de código.
- WhatsApp: Para comunicación rápida, coordinación de tareas y apoyo mutuo.
- Google Meet: Para reuniones de planificación, revisión de avances y aclaración de dudas específicas.

## 5.2.2. Sprint 2

### 5.2.2.1. Sprint Planning 2

<table border="1" cellspacing="0" cellpadding="6">
    <tr>
        <th><strong>Sprint #</strong></th>
        <td>Sprint 2</td>
    </tr>
    <tr>
        <th><strong>Resumen del Sprint Planning</strong></th>
        <td>Distribución de tareas y asignación de desarrollo de vistas incluyendo fake-api</td>
    </tr>
    <tr>
        <th><strong>Fecha</strong></th>
        <td>2026-05-02</td>
    </tr>
    <tr>
        <th><strong>Hora</strong></th>
        <td>1:00 PM</td>
    </tr>
    <tr>
        <th><strong>Ubicación</strong></th>
        <td>Google Meet</td>
    </tr>
    <tr>
        <th><strong>Preparado por</strong></th>
        <td>Manuel Angel Sanchez Arenas</td>
    </tr>
    <tr>
        <th><strong>Asistentes a la reunión de planificación</strong></th>
        <td>
            - Manuel Angel Sanchez Arenas,<br>
            - Jean Niels Arizabal Condori,<br>
            - Esteban Eduardo Chavez Bardales,<br>
            - Jhon Jordy Jaramillo Mayta
        </td>
    </tr>
    <tr>
        <th><strong>Resumen del Sprint 1 (Revisión)</strong></th>
        <td>El Sprint 1 se enfocó en la implementación de la Landing Page de Safelab. Las tareas fueron completadas exitosamente. Las secciones requeridas en la página fueron desarrolladas y probadas.</td>
    </tr>
</table>

**Objetivo del Sprint y User Stories**

<table border="1" cellspacing="0" cellpadding="6">
  <tr>
    <th><strong>Item</strong></th>
    <th><strong>Descripción</strong></th>
  </tr>
  <tr>
    <td><strong>Objetivo del Sprint 2</strong></td>
    <td>
      Nos enfocamos en la implementación de las vistas principales de la aplicación web.<br>
      Creemos que este avance permitirá a nuestros usuarios mostrar las funcionalidades core de la plataforma.<br>
      Esto se confirmará cuando las vistas estén desarrolladas, integradas con el backend y desplegadas en un entorno de staging para pruebas internas.
    </td>
  </tr>
  <tr>
    <td><strong>Velocidad del Sprint 2</strong></td>
    <td>-- Story Points</td>
  </tr>
  <tr>
    <td><strong>Suma de Story Points</strong></td>
    <td>--</td>
  </tr>
</table>

### 5.2.2.2. Aspect Leaders and Collaborators

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Miembro del equipo</th>
      <th>Usuario de GitHub</th>
      <th>Web Application (L/C)</th>
      <th>Fake Api (L/C)</th>
      <th>Documentación (L/C)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Manuel Sanchez</td>
      <td>@manuels7a</td>
      <td>L</td>
      <td>L</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Jean Arizabal</td>
      <td>@JeanArizabal</td>
      <td>C</td>
      <td>C</td>
      <td>L</td>
    </tr>
    <tr>
      <td>Esteban Chavez</td>
      <td>@ECEB0704</td>
      <td>C</td>
      <td>C</td>
      <td>C</td>
    </tr>
    <tr>
      <td>Jhon Jaramillo</td>
      <td>@Marklnz1</td>
      <td>C</td>
      <td>C</td>
      <td>C</td>
    </tr>
  </tbody>
</table>

### 5.2.2.3. Sprint Backlog 2
**Sprint Objective:**
Implementar las vistas principales (core) de la aplicación web.

<h4>Tabla de Sprint Backlog</h4>

<table border="1" cellspacing="0" cellpadding="6">
  <thead>
    <tr>
      <th>Historia de Usuario</th>
      <th>Elemento de trabajo / Tarea</th>
      <th>Descripción</th>
      <th>Estimación (Horas)</th>
      <th>Asignado a</th>
      <th>Estado</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US08</td>
      <td>Trazabilidad de Alertas Críticas Recientes</td>
      <td>Como: Auditor de Cumplimiento (Compliance Officer). Quiero: Supervisar el log de alertas recientes disparadas por el sistema en el Dashboard. Para: Verificar que cada evento de riesgo térmico tenga una trazabilidad clara y cumpla con los tiempos de respuesta exigidos por la normativa bioclínica.</td>
      <td>6</td>
      <td>Manuel Sanchez</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US09</td>
      <td>Respuesta Rápida ante Alertas desde el Dashboard</td>
      <td>Como: Técnico de Laboratorio. Quiero: Interactuar con las alertas recientes directamente desde el panel del Dashboard. Para: Iniciar las acciones correctivas de forma inmediata sin navegar por menús complejos, reduciendo el tiempo de exposición al riesgo de las muestras.</td>
      <td>7</td>
      <td>Manuel Sanchez</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US10</td>
      <td>Gestión Preventiva basada en Métricas Ambientales</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Analizar las métricas combinadas (temperatura, vibraciones y humedad) para ejecutar acciones preventivas sobre los equipos de almacenamiento. Para: Mitigar riesgos antes de que ocurra una falla crítica en la cadena de frío y asegurar condiciones óptimas según el tipo de muestra.</td>
      <td>8</td>
      <td>Jean Arizabal</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Gestión Operativa y Control de Unidades de Almacenamiento</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Acceder al panel de control detallado de un laboratorio específico para gestionar sus unidades de almacenamiento y sensores. Para: Ejecutar decisiones operativas como el ajuste de umbrales o el mantenimiento preventivo de los equipos de frío.</td>
      <td>8</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Registro y Vinculación Técnica de Sensores</td>
      <td>Como: Técnico de Laboratorio. Quiero: Registrar y vincular nuevos sensores a unidades de almacenamiento específicas (Racks/Refrigeradores). Para: Expandir la red de monitoreo y asegurar que cada activo biológico tenga un sensor asignado correctamente.</td>
      <td>5</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US17</td>
    <td>Gestión y Resolución de Incidentes Críticos</td>
    <td>Como: Técnico de Laboratorio / Coordinador. Quiero: Gestionar las alertas activas mediante la ejecución y registro de acciones correctivas. Para: Mitigar el impacto de las excursiones térmicas y asegurar que el incidente sea resuelto bajo los protocolos de bioseguridad.</td>
      <td>4</td>
      <td>Manuel Sanchez</td>
      <td>Finalizado</td>
    </tr>
    </tr>
    <tr>
      <td>US18</td>
      <td>Gestión del Ciclo de Vida y Cierre de Incidentes</td>
      <td>Como: Coordinador de Laboratorio. Quiero: Gestionar el estado de las alertas críticas hasta su cierre definitivo. Para: Mantener el control operativo del incidente y asegurar que se ha recuperado la estabilidad térmica en la unidad de almacenamiento.</td>
      <td>6</td>
      <td>Jean Arizabal</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Trazabilidad y Auditoría de Cumplimiento Normativo</td>
      <td>Como: Auditor de Calidad. Quiero: Consultar el historial detallado de eventos, alertas y acciones ejecutadas en el sistema. Para: Generar reportes de cumplimiento para entidades regulatorias (ej. ISO, DIGEMID) y verificar la integridad de la cadena de frío en periodos pasados.</td>
      <td>8</td>
      <td>Jean Arizabal</td>
      <td>Finalizado</td>
    </tr>
    </tr>
    <tr>
      <td>US20</td>
      <td>Inicialización de Entornos de Monitoreo (Crear Lab)</td>
      <td>Como: Administrador de Laboratorio. Quiero: Registrar un nuevo laboratorio configurando sus parámetros técnicos y políticas de seguridad desde el inicio. Para: Establecer una infraestructura de monitoreo que cumpla con los estándares específicos de las muestras que se almacenarán.</td>
      <td>6</td>
      <td>Jhon Jaramillo</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US33</td>
      <td>Búsqueda de laboratorios</td>
      <td>Como usuario, quiero buscar laboratorios por nombre para encontrarlos rápidamente.</td>
      <td>4</td>
      <td>Jean Arizabal</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US36</td>
      <td>Gestión de notificaciones por correo</td>
      <td>Como usuario, quiero activar o desactivar las notificaciones por correo para controlar cómo recibo las alertas de los laboratorios.</td>
      <td>8</td>
      <td>Esteban Chavez</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US37</td>
      <td>Visualización de tendencias históricas</td>
      <td>Como usuario, quiero visualizar tendencias de eventos para analizar patrones.</td>
      <td>5</td>
      <td>Jean Arizabal</td>
      <td>Finalizado</td>
    </tr>
    <tr>
      <td>US39</td>
      <td>Notificaciones del sistema en tiempo real</td>
      <td>Como usuario, quiero recibir notificaciones visuales tras acciones importantes.</td>
      <td>Esteban Chavez</td>
      <td>7</td>
      <td>Finalizado</td>
    </tr>
  </tbody>
</table>

### 5.2.2.4. Development Evidence for Sprint Review

Esta tabla lista los commits realizados durante el sprint, incluyendo el desarrollo de la web app y documentación.

<table border="1">
  <thead>
    <tr>
      <th>Repositorio</th>
      <th>Rama</th>
      <th>ID de Commit</th>
      <th>Mensaje de Commit</th>
      <th>Descripción de Commit</th>
      <th>Fecha de Commit</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>frontend</td><td>develoment</td><td>d045080</td><td>fix: new max angular budget</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>4b2ebf6</td><td>feat: new fake-api provider</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>e5f1b62</td><td>fix: removed unused imports</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>62b6c2b</td><td>fix: db.json structure</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>1ff7bf1</td><td>Merge pull request #5 from upc-pre-1ASI0729-11834-Especialistas/feat/telemetry</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>8024832</td><td>Merge branch 'development' into feat/telemetry</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>ccafd82</td><td>Merge pull request #4 from upc-pre-1ASI0729-11834-Especialistas/feat/labs</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>develoment</td><td>a02f8ab</td><td>Merge branch 'development' into feat/labs</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>development</td><td>3b63717</td><td>Merge pull request #3 from upc-pre-1ASI0729-11834-Especialistas/feat/history</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>b5ef17c</td><td>Merge branch 'development' into feat/history</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>7d40b69</td><td>feat: add history endpoint path to environment configurations</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>7f2fe54</td><td>feat: populate history data with recent event records</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>9072d04</td><td>feat: update routing to use history page component for history view</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>74ec439</td><td>feat: create history page with summary cards, filters, and event details drawer</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>667cd28</td><td>feat: add history placeholder dialog component for functionalities not developed yet</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>d835a3f</td><td>feat: add history timeline component for displaying grouped history records</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>bee66c8</td><td>feat: implement history store for managing history records and operations</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>ee3f83a</td><td>feat: implement history api service for managing history records</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>5cba7f8</td><td>feat: add history apiendpoint for interacting with history records</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>2deb956</td><td>feat: implement history assembler for converting between entities and resources</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>a747a6c</td><td>feat: add history response interfaces for history records</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/history</td><td>5180e78</td><td>feat: add history record entity with properties and methods</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>development</td><td>0903f4b</td><td>Merge pull request #2 from upc-pre-1ASI0729-11834-Especialistas/feat/automation</td><td>-</td><td>14/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>d6b930c</td><td>feat(labs): add breadcrumb navigation and action header to add-laboratory-page</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>5b02ab5</td><td>feat(automation): add NotificationPreferenceStore for managing notification preferences and loading state</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>4640ac7</td><td>feat(automation): add initial data structure for general settings, user profiles, sensor configurations, notification preferences, and security accesses</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>5b5454f</td><td>feat(automation): refactor SecurityAccess entity to manage permissions, roles, and audit information</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>2220eeb</td><td>feat(automation): add SettingsPageComponent with layout, styles, and logic for managing general settings and user profile</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>41005ab</td><td>feat(automation): refactor UserProfile entity to manage user information with fullName, role, email, and avatarUrl</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>86d9614</td><td>feat(automation): add SensorConfigurationPageComponent with template, styles, and logic for managing sensor configurations</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>de3bf08</td><td>feat(automation): add SecurityAccessPageComponent with template, styles, and logic for managing account credentials and security preferences</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>cba95bc</td><td>feat(automation): add AlertsNotificationsPageComponent with template, styles, and logic for configuring alerts and notifications</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>4cbff95</td><td>feat(automation): add UserProfileCardComponent with template, styles, and logic for displaying user profile information and editing actions</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>0ef679f</td><td>feat(automation): add SettingsCardComponent with template, styles, and logic for displaying settings information and actions</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>ecbbfea</td><td>feat(automation): add SensorListItemComponent with template, styles, and logic for displaying sensor details and actions</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>913a03d</td><td>feat(automation): add UserProfilesApi, UserProfilesApiEndpoint, UserProfileAssembler, and response models for managing user profiles</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>1ecba29</td><td>feat(automation): add SensorConfigurationsApi, SensorConfigurationsApiEndpoint, SensorConfigurationAssembler, and response models for managing sensor configurations</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>c7c8d0d</td><td>feat(automation): add SecurityAccessesApi, SecurityAccessesApiEndpoint, SecurityAccessAssembler, and response models for managing security access data</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>f519b48</td><td>feat(automation): add routing for settings, sensor configuration, alerts notifications, and security access pages</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>e4d0a3c</td><td>feat(automation): add NotificationPreferencesApi, NotificationPreferencesApiEndpoint, NotificationPreferenceAssembler, and response models for managing notification preferences</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>62d0652</td><td>feat(automation): add GeneralSettingsApi, GeneralSettingsApiEndpoint, GeneralSettingAssembler, and response models for managing general settings</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>8e1486e</td><td>fix(automation): correct import path for SecurityAccessStore</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>bfe0b4a</td><td>feat(automation): add SensorConfiguration and UserProfile entities for managing sensor and user profile data</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>e456518</td><td>feat(automation): add NotificationPreference entity for managing notification preferences</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>0f214d3</td><td>feat(automation): add GeneralSetting and NotificationPreference entities for managing general settings and notification preferences</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>8a3168e</td><td>feat(automation): add SensorConfigurationStore and UserProfileStore for managing sensor and user profile data</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>b04f044</td><td>feat(automation): add SecurityAccessStore for managing security access data</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>f299c5a</td><td>feat(automation): fix import path for NotificationPreferenceStore</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>98c7f1f</td><td>feat(settings): update import path for NotificationPreferenceStore</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/automation</td><td>ad23a20</td><td>feat(settings): implement automation store and general settings management</td><td>-</td><td>13/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>16142a0</td><td>feat(labs): implement laboratory-detail-page with stats, alerts, schedules and shared components</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>1cf043c</td><td>feat(labs): implement add-laboratory-page with stepper form components</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>3247008</td><td>feat(labs): implement laboratories-page with list, toolbar, pagination and detail-card components</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>7142e98</td><td>feat(labs): add laboratory store and mock data for JSON server</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>952f411</td><td>feat(labs): implement infrastructure layer with DTOs, assembler and API service</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/labs</td><td>8756930</td><td>feat(labs): define domain model entities and environment configuration</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>7b47a87</td><td>fix(telemetry): add missing apexcharts and ng-apexcharts dependencies to package.json</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>ba0b292</td><td>feat(telemetry): implement dashboard page and integrate telemetry routes</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>4b00171</td><td>feat(telemetry): implement laboratory-card, recent-alerts and temperature-chart components</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>e61c484</td><td>feat(shared): add reusable card, icon-badge, stat-card and status-badge components</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>1749224</td><td>feat(telemetry): add reactive signal stores and mock data for JSON server</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>ee8e620</td><td>feat(telemetry): implement infrastructure layer with DTOs, assemblers and API services</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/telemetry</td><td>d0d6692</td><td>feat(telemetry): define domain entities and environment endpoints</td><td>-</td><td>12/05/2026</td></tr>
    <tr><td>frontend</td><td>development</td><td>a5e4f4e</td><td>Merge pull request #1 from upc-pre-1ASI0729-11834-Especialistas/feat/alerts</td><td>-</td><td>08/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/alerts</td><td>9684920</td><td>fix: folder structure for ddd & angular material refactor</td><td>-</td><td>08/05/2026</td></tr>
    <tr><td>frontend</td><td>feat/alerts</td><td>ddc62f5</td><td>feat: configured routes, defined layout, alerts page added</td><td>-</td><td>07/05/2026</td></tr>
    <tr><td>frontend</td><td>main</td><td>1fcfd75</td><td>feat: initial ddd structure and basic packages added</td><td>-</td><td>06/05/2026</td></tr>
    <tr><td>frontend</td><td>main</td><td>ae4c8f9</td><td>initial commit</td><td>-</td><td>06/05/2026</td></tr>
  </tbody>
</table>

### 5.2.2.5. Execution Evidence for Sprint Review

Las vistas principales de la aplicación web fueron desarrolladas y desplegadas exitosamente. A continuación se presentan las evidencias correspondientes de la implementación.

**Web Application Views:**
<ul>
  <li><strong>Dashboard View</strong><br><img src="./assets/chapter-v/evidence-dashboard-view.png" alt="Dashboard View"></li>
  <li><strong>Laboratories View</strong><br><img src="./assets/chapter-v/evidence-laboratories-view.png" alt="Laboratories View"></li>
  <li><strong>History View</strong><br><img src="./assets/chapter-v/evidence-history-view.png" alt="History View"></li>
  <li><strong>Alerts View</strong><br><img src="./assets/chapter-v/evidence-alerts-view.png" alt="Alerts View"></li>
  <li><strong>Settings View</strong><br><img src="./assets/chapter-v/evidence-settings-view.png" alt="Settings View"></li>
</ul>

<p><strong>Despliegue de la aplicación:</strong><br>
<a href="https://frontend-jade-seven-fwvgy3syck.vercel.app/">Safelab Web Application</a></p>

### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante este Sprint, el equipo se centró en el desarrollo de las vistas principales de la aplicación web, por lo que no se implementaron ni documentaron endpoints relacionados a Web Services.
Sin embargo, se establecieron las bases para la integración futura con el backend y con ello el desarrollo de una fake API para simular las interacciones con el sistema, lo que permitirá una documentación detallada de los servicios en los próximos Sprints.

**Fake API Endpoints:**
<ul>
  <li><strong>Laboratories Endpoint</strong><br><img src="./assets/chapter-v/evidence-laboratories-endpoint.png" alt="Laboratories Endpoint"></li>
  <li><strong>Telemetry Endpoint</strong><br><img src="./assets/chapter-v/evidence-telemetry-endpoint.png" alt="Telemetry Endpoint"></li>
  <li><strong>History Endpoint</strong><br><img src="./assets/chapter-v/evidence-history-endpoint.png" alt="History Endpoint"></li>
  <li><strong>Alerts Endpoint</strong><br><img src="./assets/chapter-v/evidence-alerts-endpoint.png" alt="Alerts Endpoint"></li>
  <li><strong>Settings Endpoint</strong><br><img src="./assets/chapter-v/evidence-settings-endpoint.png" alt="Settings Endpoint"></li>
</ul>

<p><strong>Despliegue del fake API:</strong><br>
<a href="https://fake-api-production-0033.up.railway.app/">Safelab Fake API</a></p>

### 5.2.2.7. Software Deployment Evidence for Sprint Review

El primer despliegue de la web application se realizó exitosamente en Vercel, mientras que la fake API se desplegó en Railway, lo que permitió validar la funcionalidad de la aplicación y su integración con el backend simulado. A continuación se presentan las evidencias de ambos despliegues:

**Web Application Deployment:**
<ul>
  <li>
    <strong>URL de la Web Application:</strong>
    <a href="https://frontend-j71vgadc7-manuel-sanchezs-projects-f772331f.vercel.app/" target="_blank">https://frontend-j71vgadc7-manuel-sanchezs-projects-f772331f.vercel.app/</a>
  </li>
  <li>
    <strong>Repositorio:</strong>
    <a href="https://github.com/upc-pre-1ASI0729-11834-Especialistas/frontend" target="_blank">https://github.com/upc-pre-1ASI0729-11834-Especialistas/frontend</a>
  </li>
  <li>
    <strong>Despliegue en Vercel:</strong><br>
    <img src="./assets/chapter-v/evidence-web-app-deployment.png" alt="Web Application Deployment">
  </li>
</ul>

**Fake API Deployment:**
<ul>
  <li>
    <strong>URL de la Fake API:</strong>
    <a href="https://fake-api-production-0033.up.railway.app/" target="_blank">https://fake-api-production-0033.up.railway.app/</a>
  </li>
  <li>
    <strong>Repositorio:</strong>
    <a href="https://github.com/upc-pre-1ASI0729-11834-Especialistas/fake-api" target="_blank">https://github.com/upc-pre-1ASI0729-11834-Especialistas/fake-api</a>
  </li>
  <li>
    <strong>Despliegue en Railway:</strong><br>
    <img src="./assets/chapter-v/evidence-fake-api-deployment.png" alt="Fake API Deployment">
</ul>

### 5.2.2.8. Team Collaboration Insights during Sprint

Nuestro grupo, Especialistas, gestionó los entregables mediante GitHub, WhatsApp y Google Meet durante el Sprint. Las actividades principales se centraron en el desarrollo y despliegue de la Web Application y documentación.

**Evidencia de Colaboración:**

![Team Collaboration Evidence](assets/chapter-v/evidence-team-collaboration-insights-sprint-2.png)

**Principales Herramientas de Comunicación:**
- Github: Para el control de versiones, gestión de issues y revisión de código.
- WhatsApp: Para comunicación rápida, coordinación de tareas y apoyo mutuo.
- Google Meet: Para reuniones de planificación, revisión de avances y aclaración de dudas específicas.

# Conclusiones

Durante el Sprint 2, el equipo completó en el plazo establecido el desarrollo de las vistas principales de la aplicación web, así como el despliegue exitoso de la misma y de la fake API. Además, se establecieron las bases para la integración futura con el backend y se documentaron los endpoints de la fake API, lo que permitirá una documentación detallada de los servicios en los próximos Sprints.

A partir de este nuevo avance, llegamos a las siguientes conclusiones:

- Gracias a gitflow, logramos segmentar los avances en ramas específicas para cada Bounded Context, lo que facilitó la gestión de tareas y la integración de funcionalidades.
- La comunicación fluida a través de WhatsApp y Google Meet permitió resolver dudas rápidamente y mantener a todo el equipo alineado con los objetivos del Sprint.
- La coordinación para definir los objetos y estructuras de datos de la fake API fue clave para asegurar que el desarrollo de la aplicación web se realizara de manera coherente y con una visión clara de las interacciones futuras con el backend.

# Anexos

**Repositorios**
- Repositorio de la Landing Page: https://github.com/upc-pre-1ASI0729-11834-Especialistas/landing-page
- Repositorio del fake API: https://github.com/upc-pre-1ASI0729-11834-Especialistas/fake-api
- Repositorio del frontend: https://github.com/upc-pre-1ASI0729-11834-Especialistas/frontend
- Repositorio del informe: https://github.com/upc-pre-1ASI0729-11834-Especialistas/report

**Despliegues**
- Despliegue de la Landing Page: https://upc-pre-1asi0729-11834-especialistas.github.io/landing-page/
- Despliegue del fake API: https://fake-api-production-0033.up.railway.app/
- Despliegue de la Web Application: https://frontend-j71vgadc7-manuel-sanchezs-projects-f772331f.vercel.app/