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