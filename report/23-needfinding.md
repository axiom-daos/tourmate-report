
## 2.3. Needfinding
 
En esta sección se presentan los artefactos resultantes del proceso de análisis de la información recolectada durante la fase de Needfinding. A partir de las entrevistas realizadas a los segmentos objetivo y del análisis competitivo desarrollado en el capítulo anterior, el equipo ha sintetizado los hallazgos en artefactos que permiten visualizar de forma estructurada las características, comportamientos, motivaciones y necesidades de los usuarios potenciales de VitalTrek. Estos artefactos servirán como base para la definición de requerimientos funcionales y de diseño de la solución, asegurando que cada decisión esté centrada en el usuario y respaldada por evidencia recolectada en campo.
 
### 2.3.1. User Personas
 
A continuación se presentan las fichas de User Persona elaboradas para cada uno de los dos segmentos objetivo de VitalTrek, identificados previamente en la sección de Segmentos Objetivo del capítulo anterior. La elaboración de estos arquetipos se sustenta en el análisis cualitativo de las entrevistas realizadas a representantes de cada segmento, así como en los hallazgos obtenidos del análisis competitivo, donde se evidenciaron brechas en la oferta actual de productos digitales para turismo de aventura en zonas de baja conectividad.
 
Las principales características consideradas para la construcción de los User Personas incluyen los datos demográficos, ocupación, comportamiento digital, motivaciones, frustraciones, objetivos personales y profesionales, así como el nivel de adopción tecnológica de cada segmento. Esta información fue contrastada con las debilidades detectadas en competidores como TrekkSoft, Wayward y AllTrails, especialmente en lo referente a la operatividad sin conectividad, la captura de signos vitales y la falta de personalización para el contexto peruano. De esta manera, los arquetipos no solo representan a los usuarios, sino que también encapsulan las oportunidades de diferenciación que VitalTrek puede capitalizar.
 
Se ha elaborado una ficha de User Persona por cada segmento objetivo, utilizando la herramienta UXPressia siguiendo las mejores prácticas de la industria. El primer User Persona, Ana Lucía Quispe, representa al segmento de agencias y operadores de turismo de aventura, mientras que el segundo, Marco Rodriguez, representa al segmento de turistas de aventura nacionales y extranjeros que contratan los servicios de estas agencias.
 
**User Persona 1: Ana Lucía Quispe - Segmento de Dueños o Responsables de Agencias de Turismo de Aventura**
 
![](assets/images/User-Persona1.png)

Representa al segmento de agencias y operadores de turismo de aventura. Este arquetipo encarna a la gerente de operaciones de una agencia mediana en Cusco, responsable de coordinar guías, supervisar tours simultáneos y garantizar la seguridad de los grupos en zonas remotas. Sus motivaciones giran en torno a la profesionalización operativa, la reducción del tiempo de respuesta ante emergencias y la diferenciación competitiva mediante el uso de tecnología. Sus principales frustraciones se relacionan con la pérdida de comunicación con los guías por horas, la dependencia de WhatsApp y radios analógicas, y la ausencia de herramientas digitales adaptadas al contexto y al presupuesto de una micro o pequeña empresa peruana.

**User Persona 2: Marco Rodriguez - Segmento de Turistas de Aventura**
 
![](assets/images/User-Persona2.png)

Representa al segmento de turistas de aventura nacionales y extranjeros. Este arquetipo encarna al viajero europeo experimentado, con alto poder adquisitivo, dominio tecnológico y pasión por las experiencias outdoor auténticas. Sus motivaciones se centran en vivir aventuras seguras y memorables, mantener informados a sus familiares durante el recorrido y enriquecer su experiencia con información cultural e histórica del entorno. Sus frustraciones más relevantes son la incertidumbre sobre su ubicación al perder señal GPS, la imposibilidad de avisar a su familia durante varios días, y la carencia de aplicaciones móviles que funcionen sin conectividad continua en zonas remotas del Perú.

### 2.3.2. User Task Matrix

A continuación se presenta el User Task Matrix, artefacto que concentra las principales tareas que los User Personas realizan para cumplir sus objetivos en el dominio del turismo de aventura. Es importante precisar que las tareas listadas corresponden a actividades que ambos segmentos llevan a cabo de manera independiente a la existencia de VitalTrek, ya que reflejan el comportamiento natural y las responsabilidades inherentes a cada rol dentro del ecosistema del turismo de aventura. Los segmentos considerados en esta matriz son las agencias y operadores de turismo de aventura, representados por Ana Lucía Quispe, y los turistas de aventura nacionales y extranjeros, representados por Marco Rodriguez.

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

Entre las principales diferencias se observa que las tareas relacionadas con la supervisión de grupos, la generación de reportes operativos, la gestión de facturación y la coordinación con guías son exclusivas del User Persona de la agencia, mientras que las tareas vinculadas a la documentación de la experiencia, el acceso a información cultural y el compartir contenido en redes sociales son predominantes en el User Persona del turista. Esta diferenciación valida el enfoque dual de la propuesta de valor de VitalTrek, donde la plataforma debe atender tanto las necesidades operativas y de control de las agencias como las expectativas experienciales y de seguridad personal de los turistas.

#### 2.3.3. User Journey Mapping

El User Journey Mapping es una herramienta que permite visualizar de forma estructurada la experiencia del usuario a lo largo de su interacción con un producto o servicio. Realizamos los User Journey Maps en su versión As-Is para los tres segmentos objetivos.

<b>User Journey Map del 1er segmento objetivo – agencias y operadores de turismo</b>
![](assets/images/jm-segmento-1.png)

<b>User Journey Map del 2do segmento objetivo - turistas de aventura </b>
![](assets/images/jm-segmento-2.png)

### 2.3.4. Empathy Mapping

El Empathy Mapping es una herramienta que nos permite profundizar en la experiencia emocional y cognitiva del usuario. A través de categorías como lo que el usuario piensa, siente, dice y hace, se busca comprender su contexto, así como sus principales miedos, frustraciones y motivaciones.

Para VitalTrek, elaborar un Empathy Mapping para cada segmento objetivo fue clave para entender no solo cómo las agencias planifican la logística y cómo los turistas viven la experiencia outdoor, sino también cómo enfrentan la incertidumbre de la desconexión en zonas remotas, los retos de seguridad y la respuesta ante posibles emergencias. Esta comprensión más empática nos permite diseñar un ecosistema tecnológico que responda a sus necesidades reales, brindando tranquilidad y reduciendo los puntos de dolor presentes en la gestión actual de las rutas de aventura.

<b>Empathy Mapping del 1er segmento objetivo – agencias y operadores de turismo</b>
![](assets/images/Empathy-Map1.png)

<b>Empathy Mapping del 2do segmento objetivo – turistas de aventura </b>
![](assets/images/Empathy-Map2.png)

### 2.3.5. As-is Scenario Mapping.

El As-is Scenario Mapping permite representar cómo los usuarios realizan actualmente sus actividades antes de utilizar VitalTrek. Este análisis se construye a partir de las entrevistas, los User Personas, el User Task Matrix, los User Journey Maps y los Empathy Maps. Su objetivo es identificar acciones, pensamientos, emociones y oportunidades de mejora dentro del flujo actual de trabajo de cada segmento.

### As-is Scenario Mapping: Agencia y Operador de Turismo de Aventura

**User Persona:** Ana Lucía Quispe  
**Escenario:** Coordinación y supervisión manual de tours en zonas remotas sin herramientas digitales de monitoreo.

| Etapa | Actividades actuales | Pensamientos del usuario | Emociones | Pain points | Oportunidades para VitalTrek |
|-------|----------------------|--------------------------|-----------|-------------|-------------------------------|
| Planificación del tour | Organiza el itinerario, asigna guías y coordina la logística mediante hojas de cálculo y conversaciones directas con su equipo. | "Espero no haber olvidado coordinar algo con los guías." | Concentración y responsabilidad. | La planificación depende de múltiples canales dispersos, sin un sistema único de gestión. | Centralizar la creación y gestión de tours, guías y rutas en un solo panel operativo. |
| Salida del grupo a campo | Envía a los guías con instrucciones verbales o por WhatsApp y radios analógicas, sin visibilidad continua de su ubicación. | "Una vez que salen a la ruta, ya no sé mucho de ellos hasta que regresan o me escriben." | Incertidumbre y confianza forzada. | La ausencia de monitoreo en tiempo real genera una desconexión total durante horas. | Ofrecer un dashboard con ubicación y estado de los grupos en tiempo real, incluso en zonas sin señal continua. |
| Seguimiento durante el recorrido | Espera mensajes intermitentes de los guías cuando logran obtener señal, sin poder anticipar problemas de salud o seguridad. | "Si algo pasa y no tengo señal, no me voy a enterar a tiempo." | Ansiedad y sensación de vulnerabilidad. | La dependencia de la señal celular expone a la agencia a horas de comunicación perdida. | Habilitar sincronización asincrónica y alertas automáticas ante anomalías en signos vitales o ubicación. |
| Reacción ante una emergencia | Recibe la noticia del incidente tarde, muchas veces horas después, y debe improvisar una respuesta sin protocolo definido. | "Necesito saber de inmediato si algo sale mal, no cuando ya sea demasiado tarde." | Urgencia y estrés. | La falta de un botón de emergencia y protocolos claros retrasa la respuesta y pone en riesgo a los turistas. | Implementar alertas críticas con protocolo de respuesta sugerido y contacto inmediato con el guía en campo. |
| Cierre del tour y reportes | Reconstruye manualmente lo ocurrido durante el tour a partir de mensajes, notas y el relato de los guías para generar reportes y facturación. | "Ojalá pueda armar el reporte con la información que tengo, aunque esté incompleta." | Cansancio y falta de respaldo documentado. | La información dispersa dificulta la elaboración de reportes confiables y la trazabilidad del servicio. | Generar reportes operativos y financieros automáticos a partir de los datos registrados durante el tour. |

### As-is Scenario Mapping: Turista de Aventura

**User Persona:** Marco Rodriguez  
**Escenario:** Exploración de rutas remotas dependiendo de aplicaciones sin funcionamiento offline y sin monitoreo de salud.

| Etapa | Actividades actuales | Pensamientos del usuario | Emociones | Pain points | Oportunidades para VitalTrek |
|-------|----------------------|--------------------------|-----------|-------------|-------------------------------|
| Investigación previa al viaje | Compara agencias y servicios turísticos en internet y redes sociales antes de reservar su tour de aventura. | "Quiero elegir una agencia que realmente me garantice seguridad en la ruta." | Expectativa y cautela. | La información sobre seguridad y protocolos de las agencias suele ser limitada o poco verificable. | Mostrar de forma transparente las capacidades de monitoreo y seguridad que ofrece la agencia asociada a VitalTrek. |
| Inicio del recorrido | Utiliza aplicaciones de mapas convencionales para orientarse y comparte su ubicación con familiares antes de perder señal. | "Espero que la señal aguante un poco más antes de entrar a la zona sin cobertura." | Entusiasmo mezclado con preocupación. | Las aplicaciones dependen de conexión continua, lo que genera vacíos de información apenas se pierde la señal. | Ofrecer navegación y registro de ubicación con funcionamiento offline mediante sincronización asincrónica. |
| Pérdida de señal en zona remota | Continúa el recorrido sin poder confirmar su ubicación exacta ni informar a su familia sobre su estado. | "No sé si mi familia sabe que sigo bien, y yo tampoco puedo confirmarlo." | Incertidumbre y aislamiento. | La imposibilidad de comunicarse durante varios días genera ansiedad tanto en el turista como en sus familiares. | Registrar y sincronizar automáticamente la ubicación y el estado del turista apenas se recupera la conectividad. |
| Actividad física exigente | Realiza la actividad de aventura sin ningún dispositivo que monitoree su estado físico o signos vitales. | "Si algo me pasara aquí, nadie lo sabría hasta que sea muy tarde." | Vulnerabilidad y autoexigencia. | La falta de monitoreo de signos vitales limita la capacidad de reacción ante una emergencia médica. | Capturar signos vitales mediante wearables IoT y generar alertas ante anomalías detectadas durante la actividad. |
| Cierre del recorrido | Documenta su experiencia con fotografías y notas personales, sin registro contextual automático del recorrido realizado. | "Me hubiera gustado tener más información histórica y cultural mientras avanzaba en la ruta." | Satisfacción parcial y nostalgia. | La experiencia carece de información contextual enriquecida y de un registro digital estructurado del recorrido. | Ofrecer información contextual del recorrido y registro automático de experiencia, fotos y ruta completada. |

---

## 2.3.6. To-be Scenario Mapping.

El To-be Scenario Mapping representa cómo los usuarios realizarán sus actividades una vez implementada la plataforma VitalTrek, contrastando directamente con el As-is Scenario Mapping presentado anteriormente. Este análisis muestra cómo las funcionalidades del ecosistema (monitoreo en tiempo real, sincronización asincrónica, wearables IoT y alertas automáticas) transforman las etapas identificadas, reduciendo la incertidumbre, el tiempo de reacción y la dependencia de procesos manuales.

### To-be Scenario Mapping: Agencia y Operador de Turismo de Aventura

**User Persona:** Ana Lucía Quispe  
**Escenario:** Coordinación y supervisión de tours en zonas remotas mediante el dashboard en tiempo real de VitalTrek.

| Etapa | Actividades con VitalTrek | Pensamientos del usuario | Emociones | Mejora respecto al As-is | Valor entregado por VitalTrek |
|-------|----------------------------|---------------------------|-----------|---------------------------|-------------------------------|
| Planificación del tour | Crea el tour desde el panel web, define checkpoints, asigna guías y turistas, y publica el itinerario en un solo flujo. | "Todo el tour queda armado y visible para mi equipo desde el primer momento." | Organización y control. | Reemplaza hojas de cálculo y coordinación dispersa por un flujo único de creación de tour. | Centraliza la planificación en el módulo de Tour Management. |
| Salida del grupo a campo | Verifica el estado de los wearables y del grupo antes de iniciar la expedición, con confirmación automática en el sistema. | "Puedo confirmar que todos los dispositivos están activos antes de que salgan a ruta." | Confianza y tranquilidad. | Elimina la incertidumbre de enviar al grupo sin visibilidad; ahora hay una verificación previa registrada. | El flujo de inicio de expedición asegura que el monitoreo esté activo desde el primer checkpoint. |
| Seguimiento durante el recorrido | Supervisa la ubicación y signos vitales de cada turista en el dashboard Live Monitoring, incluso con datos sincronizados de forma asincrónica. | "Aunque no haya señal continua, sé que la información llegará apenas se recupere la conexión." | Seguridad y control continuo. | Sustituye la espera pasiva de mensajes por un panel activo con datos estructurados por participante. | La sincronización asincrónica y el dashboard matricial permiten monitoreo sin depender de señal constante. |
| Reacción ante una emergencia | Recibe una alerta automática generada por anomalías en signos vitales o ubicación, y responde siguiendo el protocolo sugerido por el sistema. | "En cuanto algo se sale de lo normal, el sistema me avisa antes de que se convierta en una emergencia mayor." | Rapidez y seguridad operativa. | Reduce el tiempo de reacción de horas a minutos, reemplazando la espera de un mensaje de auxilio. | Las alertas automáticas y el módulo de Incidents agilizan la respuesta y dejan registro trazable del evento. |
| Cierre del tour y reportes | Genera automáticamente el reporte operativo del tour a partir de los datos registrados durante la expedición. | "El reporte ya está armado con toda la información real del recorrido." | Satisfacción y respaldo documentado. | Elimina la reconstrucción manual de lo ocurrido a partir de mensajes y notas sueltas. | Los reportes post-tour se generan a partir de la telemetría y los checkpoints registrados en el sistema. |

### To-be Scenario Mapping: Turista de Aventura

**User Persona:** Marco Rodriguez  
**Escenario:** Exploración de rutas remotas utilizando la aplicación móvil de VitalTrek con navegación offline y monitoreo de salud.

| Etapa | Actividades con VitalTrek | Pensamientos del usuario | Emociones | Mejora respecto al As-is | Valor entregado por VitalTrek |
|-------|----------------------------|---------------------------|-----------|---------------------------|-------------------------------|
| Investigación previa al viaje | Revisa el perfil de la agencia y confirma que utiliza VitalTrek para monitoreo y seguridad antes de reservar. | "Esta agencia sí muestra cómo cuidan a sus turistas en ruta." | Confianza y expectativa positiva. | Sustituye la incertidumbre sobre la seguridad de la agencia por información verificable. | La integración con VitalTrek se convierte en un diferenciador visible para el turista al elegir agencia. |
| Inicio del recorrido | Descarga el mapa y la ruta desde la app antes de salir, y su wearable comienza a sincronizarse con el sistema. | "Ya tengo todo descargado, no dependo de que haya señal." | Preparación y tranquilidad. | Reemplaza la dependencia de aplicaciones de mapas online por navegación 100% offline. | El módulo de Navigation & Exploration permite descargar rutas y operar sin conexión continua. |
| Pérdida de señal en zona remota | Continúa el recorrido con normalidad; la app sigue registrando ubicación y signos vitales localmente para sincronizarlos después. | "No tengo señal, pero sé que mi información se está guardando y se enviará apenas se pueda." | Calma y confianza en el sistema. | Elimina la ansiedad y el aislamiento comunicativo que antes generaba la pérdida de señal. | La sincronización asincrónica asegura continuidad de datos sin necesidad de conexión constante. |
| Actividad física exigente | Su wearable monitorea continuamente su frecuencia cardíaca y SpO₂, enviando una alerta automática si detecta una anomalía. | "Si algo me pasara, mi guía y la agencia lo sabrían de inmediato." | Seguridad y confianza en su propio cuerpo. | Sustituye la ausencia total de monitoreo por vigilancia constante de signos vitales con alertas activas. | El ecosistema de wearables IoT y las alertas automáticas habilitan una respuesta médica más rápida. |
| Cierre del recorrido | Recibe automáticamente su diario de viaje generado con fotos georreferenciadas, ruta completada y datos de salud del recorrido. | "Tengo un registro completo de mi experiencia sin haber tenido que armarlo yo mismo." | Satisfacción y sensación de logro. | Reemplaza la documentación manual y dispersa por un registro automático y enriquecido de la experiencia. | El módulo de registro automático (auto-generated journal) entrega contexto, fotos y datos de salud sin intervención manual. |

En conjunto, el To-be Scenario Mapping evidencia que VitalTrek no elimina la naturaleza riesgosa del turismo de aventura, pero sí transforma la forma en que agencias y turistas se preparan, se comunican y reaccionan ante ella: la incertidumbre pasiva del escenario As-is es reemplazada por visibilidad activa, respuesta automatizada y registro trazable en cada etapa del recorrido.

---