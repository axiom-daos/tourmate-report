# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### **Branding**

La identidad visual de la nueva landing page está orientada a transmitir una estética relacionada con la naturaleza, la aventura y una experiencia cercana y humana. El diseño combina tonalidades verdes y neutras con acentos cálidos, generando una apariencia sobria y natural.

La interfaz utiliza principalmente una paleta clara, donde el color de fondo tipo arena y las tonalidades verdes constituyen la base visual. Los colores cálidos se emplean como elementos de acento para destacar determinados componentes de la interfaz.

La identidad visual se complementa con fotografías relacionadas con expediciones y actividades de aventura. La misma imagen principal de la sección **Hero** es reutilizada en otras secciones mediante diferentes filtros de color y saturación para mantener coherencia visual.

### **Tone of Communication**

El tono de comunicación de la landing page se caracteriza por ser:

| Eje | Posición |
|---|---|
| Divertido / Serio | **Serio y cercano** — se busca comunicar profesionalismo sin generar una experiencia visual fría. |
| Formal / Casual | **Casual y directo** — el contenido utiliza mensajes breves y fáciles de comprender. |
| Respetuoso / Irreverente | **Respetuoso** — la comunicación mantiene una presentación profesional. |
| Entusiasta / Sereno | **Sereno con elementos de aventura** — las imágenes y los acentos visuales transmiten dinamismo sin sobrecargar la interfaz. |

La interfaz utiliza el español como idioma principal, establecido mediante `lang="es"` en el documento HTML.

### **Colors**

La paleta de colores está definida principalmente mediante variables CSS dentro de `:root`, permitiendo mantener consistencia entre los diferentes componentes de la landing page.

### **Color Palette**

| Variable / Color | Valor | Uso |
|---|---|---|
| `--background` / `--sand` | `#f8f7f2` | Fondo principal de la interfaz. |
| `--foreground` / `--primary` / `--forest` | `#29433a` | Color principal, textos destacados y elementos de navegación. |
| `--primary-foreground` | `#f8f7f2` | Texto utilizado sobre fondos de color primario. |
| `--border` | `#d9ded5` | Bordes de componentes y tarjetas. |
| `--muted` | `#6e7d73` | Variable definida para textos secundarios, aunque actualmente no presenta referencias en CSS. |
| `--sage` | `#dfe9dc` | Fondos y elementos visuales secundarios. |
| `--clay` | `#b87859` | Color de acento para elementos destacados. |
| `--white` | `#fffefb` | Fondos y elementos blancos. |

También se utilizan colores definidos directamente en el CSS para determinados componentes:

| Color | Valor | Uso |
|---|---|---|
| Peach | `#efc5a6` | Énfasis visual en determinados encabezados. |
| Green light | `#718078` | Variación de color para textos. |
| Green medium | `#65756c` | Variación de color para textos. |
| Green dark | `#496457` | Variación de color para textos. |
| Green hover | `#416253` | Estado `hover` de botones oscuros. |
| Peach hover | `#f1d4bd` | Estado `hover` de botones claros. |
| Clay light | `#c98b6c` | Fondo de la sección de contacto. |
| Traveler background | `#eee9df` | Fondo utilizado en la sección de viajeros. |
| Footer background | `#20362e` | Fondo del footer. |

El **Hero** utiliza además un gradiente verde con valores `rgba(35, 63, 53, ...)`, reforzando la integración visual de las imágenes con la paleta de la interfaz.

### **Typography**

La landing page utiliza principalmente la familia tipográfica **Geist**, complementada con **Geist Mono** y la familia serif **Georgia** en elementos específicos.

| Familia | Peso / Uso | Rol |
|---|---|---|
| Geist | `400`, `420`, `430`, `650` y otros pesos definidos por el diseño | Tipografía principal de títulos, cuerpo, navegación y componentes. |
| Geist Mono | Definida en el proyecto | Familia monoespaciada disponible en el sistema, sin uso visual identificado actualmente. |
| Georgia | `38px` en elementos específicos | Iniciales mostradas en las fotografías de los miembros y determinados elementos de énfasis. |

### **Escala tipográfica**

| Elemento | Familia | Tamaño | Peso | Uso |
|---|---|---|---|---|
| H1 | Geist | `clamp(54px, 8vw, 104px)` | `430` | Título principal del Hero. |
| H2 | Geist | `clamp(39px, 5.3vw, 70px)` | `420` | Encabezados principales de las secciones. |
| Eyebrow / Section label | Geist | `10px` | `650` | Etiquetas superiores de las secciones. |

El **H1** utiliza además un `letter-spacing` de `-0.07em`, mientras que los elementos **eyebrow** utilizan `letter-spacing: 0.18em`. Estos valores permiten establecer contraste entre los diferentes niveles de información.

### **Principios tipográficos**

La jerarquía tipográfica se construye principalmente mediante variaciones de tamaño, peso y espaciado dentro de la familia Geist. Los encabezados utilizan tamaños considerablemente mayores para establecer una jerarquía visual clara.

El **H1** utiliza la función `clamp()` para permitir una adaptación fluida de su tamaño según el ancho de la pantalla.

La familia **Georgia** se utiliza de manera puntual para aportar contraste visual en determinados elementos gráficos.

### **Spacing**

El diseño no utiliza una escala formal de espaciado basada en tokens, sino valores definidos directamente según las necesidades de cada sección.

Los principales valores identificados son:

| Valor | Uso principal |
|---|---|
| `12%` | Separación utilizada en determinados layouts. |
| `18px` | Gaps y espaciados internos. |
| `36px` | Separación entre determinados elementos. |
| `45px` | Gaps principales en componentes. |
| `108px` | Espaciado vertical de la sección de contacto. |
| `118px` | Espaciado utilizado en la sección del equipo. |
| `120px` | Espaciado estándar de determinadas secciones. |
| `88px` | Espaciado vertical utilizado en mobile. |

El contenedor principal utiliza un ancho máximo de `1160px`, acompañado de márgenes horizontales de `24px`.

### **Border Radius**

La interfaz utiliza diferentes niveles de redondeado según el componente:

| Valor | Uso |
|---|---|
| `999px` | Elementos tipo pill y botones redondeados. |
| `18px` | Tarjetas de miembros del equipo. |
| `50%` | Iconos circulares, como los elementos `.check-icon`. |

No se utilizan variables CSS específicas para definir tokens de `border-radius`.

### **Shadows**

La interfaz utiliza un enfoque visual plano y **no presenta sombras (`box-shadow`) en sus componentes**.

La sensación de profundidad se consigue principalmente mediante diferencias de color, bordes y transformaciones durante las interacciones. En particular, los botones utilizan una transformación de `translateY(-2px)` durante el estado `hover`.


### 4.1.2. Web Style Guidelines

### **Layout y Grid System**

La estructura de la landing page utiliza principalmente **Flexbox** para organizar los elementos de navegación y diferentes componentes de la interfaz, complementándose con estructuras de layout específicas para cada sección.

El contenido principal está limitado a un ancho máximo de:

`max-width: min(1160px, calc(100% - 48px))`

Esto establece un ancho máximo de **1160px** y mantiene un margen horizontal de **24px** en pantallas donde el contenido necesita adaptarse.

Las diferentes secciones utilizan distribuciones que se adaptan al tamaño disponible de la pantalla mediante reglas responsive.

### **Navbar**

La barra de navegación se presenta de forma transparente sobre la sección Hero.

Características principales:

- Padding superior de `26px`.
- Distribución mediante Flexbox.
- Links de navegación ubicados en la parte central/derecha.
- Separación de `42px` entre determinados elementos de navegación.
- No utiliza posición `fixed` ni `sticky`.
- No implementa un menú hamburguesa.
- En pantallas de hasta `780px`, los links de navegación dejan de mostrarse.

La navegación incluye además una etiqueta accesible mediante `aria-label="Navegación principal"`.

### **Buttons**

La landing page utiliza dos variantes principales de botones:

| VarianteAparienciaUso |                             |                                                     |
| --------------------- | --------------------------- | --------------------------------------------------- |
| `.button-light`       | Fondo claro con texto verde | Acciones principales sobre fondos oscuros o verdes. |
| `.button-dark`        | Fondo verde con texto claro | Acciones principales sobre fondos claros.           |

Los botones modifican su apariencia durante el estado `hover`. La variante clara utiliza el color `#f1d4bd`, mientras que la variante oscura utiliza `#416253`.

También existen enlaces de texto mediante `.text-link`, con variantes `.light-link` y `.dark-link` según el fondo donde se presentan.

Los botones utilizan una transformación visual de `translateY(-2px)` durante el estado hover para proporcionar retroalimentación visual al usuario.

### **Cards**

Las tarjetas utilizan un estilo visual plano y minimalista.

La tarjeta de miembros del equipo (`.member-card`) presenta:

- Fondo color arena.
- Borde de `1px`.
- `border-radius: 18px`.
- `overflow: hidden`.

La sección de fotografía de cada miembro utiliza:

- Fondo color sage.
- Altura mínima de `145px`.
- Iniciales representadas mediante Georgia con un tamaño de `38px`.

### **Section Elements**

Los elementos tipo eyebrow utilizados como identificadores de sección presentan:

- Tamaño de fuente de `10px`.
- Peso `650`.
- `letter-spacing: 0.18em`.

Estos elementos funcionan como etiquetas visuales que preceden a los encabezados principales y ayudan a establecer una jerarquía clara dentro de cada sección.

### **Hero Images**

La imagen utilizada en el Hero corresponde a `hero-expedition.png`.

Esta misma imagen se reutiliza en diferentes secciones de la landing page aplicando modificaciones visuales mediante CSS:

- Para la sección relacionada con agencias se utiliza `filter: saturate(.7)`.
- Para la sección relacionada con viajeros se utiliza `filter: saturate(.55) hue-rotate(8deg)`.

Estas variaciones permiten reutilizar el recurso visual manteniendo una apariencia diferenciada entre las secciones.

### **Responsive Breakpoints**

La landing page utiliza un único breakpoint responsive:

| BreakpointValorDescripción |                    |                                                                            |
| -------------------------- | ------------------ | -------------------------------------------------------------------------- |
| Mobile                     | `max-width: 780px` | Adapta la navegación y distribución del contenido para pantallas pequeñas. |

En pantallas de hasta `780px`, los links de navegación dejan de mostrarse y determinados layouts modifican su distribución.

El footer utiliza una distribución de dos columnas en mobile, mientras que el elemento correspondiente a la identidad de la marca ocupa el ancho completo.

No se utiliza un breakpoint independiente para tablet.

### **Accessibility**

La landing page incorpora diferentes elementos orientados a mejorar la accesibilidad:

- Uso de elementos semánticos como `<main>`, `<section>`, `<nav>`, `<footer>`, `<article>`, `<ul>` y `<li>`.
- La navegación utiliza `aria-label="Navegación principal"`.
- Los elementos SVG decorativos utilizan `aria-hidden="true"`.
- Las imágenes implementadas mediante fondos CSS utilizan `role="img"` y `aria-label` para proporcionar una descripción accesible.
- Las fotografías de los miembros cuentan con `aria-label`.
- El documento HTML establece `lang="es"`.
- Se utiliza antialiasing para mejorar la representación visual de los textos.

Actualmente no se encuentra implementado un tratamiento específico mediante `:focus-visible` ni una configuración de `prefers-reduced-motion`.

### **Internationalization**

La implementación actual de la landing page establece el español como idioma del documento mediante:

`<html lang="es">`

No se identifica en la implementación actual un sistema de internacionalización que permita alternar entre diferentes idiomas.
