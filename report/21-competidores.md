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
            <td> Tourmate <img src="assets/images/Tourmate-logo.png"></td>
            <td> TrekkSoft <img src="assets/images/trekk-soft.png"></td>
            <td> Wayward <img src="assets/images/wayward.png"></td>
            <td> AllTrails <img src="assets/images/all-trails.png"></td> 
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