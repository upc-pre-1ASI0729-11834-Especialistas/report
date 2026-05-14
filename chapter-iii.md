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
