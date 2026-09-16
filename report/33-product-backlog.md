### 3.3. Product Backlog

A continuación se presenta el Product Backlog de Tourmate con la priorización y estimación de todas las historias identificadas. El orden refleja el valor para el negocio, priorizando las funcionalidades del Landing Page y las capacidades core de monitoreo y seguridad en campo.

Para acceder al Product Backlog en la herramienta de gestión del equipo, visitar el siguiente enlace: [Product Backlog — Tourmate](https://trello.com/invite/b/6aa7135dcbb03c6075b9944b/ATTI3d6ca6c13b23e9df6f2ebe962e859d9aE7098EAF/tourmate-product-backlog)

![Product Backlog Tourmate](../assets/images/New-Product-Backlog.png)

| #Orden | User Story ID | Título | Descripción | Story Points |
| :---: | :--- | :--- | :--- | :---: |
| 1 | TS01 | Endpoint de registro de usuarios | Como developer, quiero exponer un endpoint que registre usuarios validando los datos del request para que los clientes puedan crear cuentas de forma segura en la plataforma. | 5 |
| 2 | TS02 | Endpoint de autenticación | Como developer, quiero exponer un endpoint que valide credenciales y genere tokens de acceso para que los clientes puedan autenticarse y consumir recursos protegidos del sistema. | 5 |
| 3 | US01 | Registro de turista | Como turista, quiero registrarme en la plataforma para acceder a los tours y funcionalidades disponibles del sistema. | 5 |
| 4 | US02 | Registro de administrador de agencia | Como administrador de agencia, quiero registrar mi agencia en la plataforma para gestionar tours y monitorear a los turistas asignados. | 5 |
| 5 | US03 | Inicio de sesión | Como usuario registrado, quiero iniciar sesión de forma segura para acceder a las funcionalidades de la plataforma según mi rol. | 3 |
| 6 | US05 | Verificación de correo electrónico | Como turista, quiero verificar mi correo electrónico tras el registro para confirmar la validez de mi cuenta. | 2 |
| 7 | US04 | Recuperación de contraseña | Como usuario registrado, quiero recuperar mi contraseña para no perder el acceso a mi cuenta en la plataforma. | 3 |
| 8 | US06 | Cambio de contraseña | Como usuario registrado, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta. | 2 |
| 9 | US48 | Cerrar sesión actual | Como usuario registrado, quiero cerrar mi sesión actual para proteger el acceso a mi cuenta cuando termino de utilizar la plataforma. | 1 |
| 10 | US07 | Cierre de sesiones activas | Como usuario registrado, quiero cerrar todas mis sesiones activas en otros dispositivos para proteger mi cuenta. | 2 |
| 11 | US49 | Desactivar cuenta personal | Como usuario registrado, quiero desactivar mi cuenta para dejar de utilizar la plataforma cuando lo considere necesario. | 2 |
| 12 | TS03 | Endpoint de gestión de tours | Como developer, quiero exponer endpoints para la creación, consulta, actualización y eliminación de tours para que el frontend pueda administrar la información de las expediciones. | 5 |
| 13 | US08 | Crear tour | Como administrador de agencia, quiero crear un tour para organizar rutas y ponerlas a disposición de los turistas. | 5 |
| 14 | US09 | Editar tour | Como administrador de agencia, quiero editar la información de un tour para mantener actualizados los datos del recorrido. | 3 |
| 15 | US10 | Eliminar tour | Como administrador de agencia, quiero eliminar un tour para mantener actualizado el catálogo de la agencia. | 2 |
| 16 | US16 | Duplicar tour | Como administrador de agencia, quiero duplicar un tour existente para crear uno nuevo basado en una configuración previamente validada. | 3 |
| 17 | US14 | Consultar tours de la agencia | Como administrador de agencia, quiero consultar todos los tours registrados por mi agencia para gestionarlos de forma centralizada. | 2 |
| 18 | US11 | Asignar turistas a un tour | Como administrador de agencia, quiero asignar turistas a un tour para conformar el grupo de participantes del recorrido. | 5 |
| 19 | US12 | Desasignar turista de un tour | Como administrador de agencia, quiero desasignar un turista de un tour para actualizar la composición del grupo. | 3 |
| 20 | US15 | Consultar turistas asignados a un tour | Como administrador de agencia, quiero consultar la información de los turistas asignados a un tour para conocer la composición del grupo. | 2 |
| 21 | US17 | Buscar tours | Como turista, quiero buscar tours mediante términos para localizar opciones acordes a mis intereses. | 3 |
| 22 | US18 | Filtrar tours | Como turista, quiero filtrar los tours disponibles según criterios definidos para encontrar opciones ajustadas a mis preferencias. | 3 |
| 23 | US19 | Consultar detalle del tour | Como turista, quiero acceder a la información completa de un tour para tomar una decisión informada antes de participar. | 2 |
| 24 | US13 | Confirmar asistencia | Como turista, quiero confirmar mi asistencia a un tour para asegurar mi participación en el recorrido. | 2 |
| 25 | US38 | Gestionar perfil personal | Como usuario registrado, quiero gestionar mi información personal para mantener actualizados los datos asociados a mi cuenta. | 2 |
| 26 | US25 | Consultar información del recorrido | Como turista, quiero acceder a la información detallada del recorrido para prepararme adecuadamente antes y durante la expedición. | 2 |
| 27 | US26 | Consultar clima del recorrido | Como turista, quiero consultar la información climática del recorrido para prepararme con el equipamiento adecuado. | 3 |
| 28 | US20 | Visualizar ruta del tour | Como turista, quiero acceder a la ruta del tour para orientarme durante el recorrido. | 8 |
| 29 | US21 | Descargar ruta offline | Como turista, quiero descargar la información de la ruta de un tour para utilizarla sin conexión durante el recorrido. | 8 |
| 30 | US22 | Visualizar checkpoints del recorrido | Como turista, quiero conocer los checkpoints del tour para identificar mi progreso durante el recorrido. | 5 |
| 31 | US23 | Visualizar progreso del recorrido | Como turista, quiero consultar mi avance en el tour para conocer cuánto resta por completar. | 5 |
| 32 | US24 | Finalizar tour | Como turista, quiero marcar un tour como finalizado para cerrar formalmente mi participación en el recorrido. | 2 |
| 33 | US27 | Registrar experiencia del recorrido | Como turista, quiero registrar notas e imágenes durante el tour para documentar mi experiencia. | 3 |
| 34 | TS04 | Endpoint de monitoreo de ubicación | Como developer, quiero exponer endpoints que registren y expongan las ubicaciones de los turistas en tiempo real para que el frontend pueda supervisar la seguridad de los participantes durante la expedición. | 8 |
| 35 | TS05 | Endpoint de gestión de incidentes | Como developer, quiero exponer endpoints que registren y expongan los incidentes reportados durante las expediciones para que el administrador de agencia pueda responder oportunamente. | 5 |
| 36 | TS07 | Endpoint de gestión de alertas | Como developer, quiero exponer endpoints que generen y expongan alertas ante anomalías detectadas para que el administrador de agencia y el guía de tour puedan responder oportunamente. | 5 |
| 37 | US28 | Monitorear ubicación de turistas | Como administrador de agencia, quiero consultar la ubicación de los turistas para supervisar su seguridad durante la expedición. | 8 |
| 38 | US29 | Consultar estado general del grupo | Como administrador de agencia, quiero consultar el estado general de los turistas para detectar situaciones de riesgo durante la expedición. | 8 |
| 39 | US30 | Recibir alertas por anomalías | Como administrador de agencia, quiero recibir alertas ante situaciones de riesgo para responder oportunamente durante las expediciones. | 5 |
| 40 | US31 | Consultar estado de salud básico | Como guía de tour, quiero consultar alertas básicas del estado de salud de los turistas para actuar oportunamente ante posibles emergencias. | 5 |
| 41 | US32 | Reportar incidentes | Como turista, quiero reportar incidentes para alertar oportunamente al personal responsable durante la expedición. | 3 |
| 42 | US33 | Exportar reportes de expedición | Como administrador de agencia, quiero exportar reportes de las expediciones para analizar la información operativa. | 5 |
| 43 | TS08 | Endpoint de exportación de reportes | Como developer, quiero exponer un endpoint que genere reportes exportables de las expediciones para que el administrador de agencia pueda analizar la información operativa. | 5 |
| 44 | US34 | Iniciar expedición | Como guía de tour, quiero marcar el inicio de la expedición para activar el monitoreo y registro del recorrido. | 3 |
| 45 | US35 | Registrar paso por checkpoint manual | Como guía de tour, quiero registrar manualmente el paso del grupo por un checkpoint para garantizar la trazabilidad cuando la detección automática no es posible. | 3 |
| 46 | US36 | Reportar incidente desde el rol guía | Como guía de tour, quiero reportar incidentes detectados en campo para informar oportunamente al administrador de agencia. | 3 |
| 47 | US37 | Comunicar estado del grupo | Como guía de tour, quiero comunicar periódicamente el estado del grupo al administrador de agencia para mantener la trazabilidad durante el recorrido. | 3 |
| 48 | US38 | Finalizar expedición como guía | Como guía de tour, quiero marcar la finalización de la expedición para cerrar formalmente el monitoreo del recorrido. | 2 |
| 49 | TS09 | Endpoint de ingesta de telemetría IoT | Como developer, quiero exponer un endpoint que reciba y procese la telemetría enviada por los dispositivos wearables para que la información biométrica esté disponible para el monitoreo en tiempo real. | 8 |
| 50 | TS10 | Endpoint de gestión de dispositivos wearables | Como developer, quiero exponer endpoints para vincular, desvincular y consultar dispositivos wearables para que los turistas puedan administrar los dispositivos asociados a su cuenta. | 5 |
| 51 | TS06 | Endpoint de sincronización offline | Como developer, quiero exponer un endpoint que procese los datos almacenados localmente al recuperar conexión para que no se pierdan registros generados durante la expedición. | 8 |
| 52 | US39 | Vincular dispositivo wearable | Como turista, quiero vincular un dispositivo wearable a mi cuenta para que el sistema capture mis signos vitales durante la expedición. | 3 |
| 53 | US40 | Recibir datos biométricos del wearable | Como turista, quiero que el sistema reciba los datos biométricos capturados por mi wearable para que sean utilizados en el monitoreo de mi salud durante la expedición. | 5 |
| 54 | US41 | Detección automática por checkpoint Bluetooth | Como turista, quiero que el sistema detecte automáticamente mi paso por checkpoints Bluetooth para registrar mi progreso sin intervención manual. | 8 |
| 55 | US42 | Sincronización asincrónica de telemetría | Como turista, quiero que los datos capturados durante la expedición se sincronicen automáticamente al recuperar la conexión para no perder ningún registro generado. | 8 |
| 56 | US43 | Consultar estado del wearable | Como turista, quiero consultar el estado de mi wearable para verificar su nivel de batería y conectividad antes de iniciar el recorrido. | 2 |
| 57 | US44 | Desvincular dispositivo wearable | Como turista, quiero desvincular un dispositivo wearable de mi cuenta para gestionar los dispositivos asociados a mi perfil. | 2 |
| 58 | US46 | Recibir notificaciones | Como usuario registrado, quiero recibir notificaciones relevantes para mantenerme informado sobre eventos importantes relacionados con mi cuenta o expedición. | 5 |
| 59 | US47 | Configurar preferencias de notificaciones | Como usuario registrado, quiero configurar las preferencias de notificaciones para recibir únicamente las que considero relevantes. | 3 |
| 60 | US-LP01 | Conocer la propuesta de valor | Como visitante, quiero conocer la propuesta de valor de Tourmate para evaluar si la plataforma se ajusta a mis necesidades. | 3 |
| 61 | US-LP02 | Navegar entre secciones de la landing | Como visitante, quiero acceder a las distintas secciones de la landing page para conocer las funcionalidades del sistema. | 2 |
| 62 | US-LP03 | Conocer beneficios para turistas | Como visitante del segmento turista, quiero conocer los beneficios específicos de la plataforma para comprender cómo mejora mi experiencia durante las expediciones. | 2 |
| 63 | US-LP04 | Conocer beneficios para administradores de agencia | Como visitante del segmento agencia, quiero conocer los beneficios específicos de la plataforma para comprender cómo mejora la gestión y monitoreo de expediciones. | 2 |
| 64 | US-LP05 | Conocer las funcionalidades principales | Como visitante, quiero conocer las funcionalidades principales de la plataforma para entender el funcionamiento general del sistema. | 2 |
| 65 | US-LP06 | Acceder al registro desde la landing | Como visitante, quiero acceder rápidamente al registro desde la landing page para comenzar a utilizar la plataforma. | 1 |
| 66 | US-LP07 | Acceder a una demostración del sistema | Como visitante, quiero acceder a una demostración del sistema para comprender el funcionamiento de la plataforma antes de registrarme. | 3 |
| 67 | US-LP08 | Conocer la compatibilidad offline | Como visitante, quiero conocer la compatibilidad offline de la plataforma para confiar en su funcionamiento en zonas sin cobertura. | 1 |
| 68 | US-LP09 | Contactar al equipo de Tourmate | Como visitante, quiero contactar al equipo de Tourmate para resolver dudas relacionadas con la plataforma. | 3 |
| 69 | US-LP10 | Conocer las medidas de seguridad de datos | Como visitante, quiero conocer cómo la plataforma protege la información personal para confiar en el sistema. | 1 |
| 70 | US-LP11 | Conocer testimonios y casos de uso | Como visitante, quiero conocer testimonios y casos de uso reales para tomar una decisión informada sobre la plataforma. | 2 |
| 71 | US-LP12 | Conocer el equipo de la startup | Como visitante, quiero conocer al equipo detrás de Tourmate para construir confianza en la propuesta de valor. | 2 |