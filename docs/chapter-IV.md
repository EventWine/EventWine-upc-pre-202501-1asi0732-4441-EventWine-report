# Capítulo IV: Product Design

## 4.1. Style Guidelines.

### 4.1.1. General Style Guidelines.

**1) Branding**

- **Logo y Marca:** El logo se mostrará en la parte superior izquierda de la pantalla de manera clara y visualmente agradable, tal como se ve en las pantallas del login.
- **Paleta de Colores:**
    - **Primarios:**
        - **Vino Tinto (#8B0000):** Dominante en el diseño, utilizado en los encabezados, bordes principales y títulos principales.
        - **Verde Oliva (#556B2F):** Utilizado para botones de acción (Principal, secundaria y de navegación), tales como "Agregar cliente", "Guardar", "Ver pedidos", etc.
        - **Beige Suave (#F5F5DC):** Color principal de fondo, brindando una apariencia clara y minimalista.
        - **Marrón bodega (#5D4037):** Color utilizado en el pie de página o footer, también en bordes de botones.
        - **Dorado Metálico (#DAA520):** Se utiliza para destacar elementos importantes o de acento, como botones de acción.
    - **Secundarios:**
        - **Rojo (#FF6347):** Color de advertencia o para resaltar elementos interactivos.
        - **Gris Pizarra (#708090):** Se utiliza para áreas de fondo secundarias o inactivas.
        - **Oro Antiguo (#CFAE75):** Para detalles elegantes y áreas de énfasis.
    - **Neutrales:** Blanco (#FFFFFF) para fondo y Gris medio (#333333) para textos.

**2) Typography**
- **Fuente Principal:**
    - **Nombre:** Lora (Serif) - Se utilizará para encabezados y textos de cuerpo. Da la sensación de elegancia y tradición, adecuada para el tema del viñedo.
    - **Tamaños:**
        - H1: 80px
        - H2: 50px
        - H3: 35px
        - Texto de cuerpo: 25px
        - Subtítulos y textos menores: 16px
- **Fuente Secundaria:**
    - **Nombre:** Open Sans (Sans-Serif) - Se utilizará para textos secundarios, botones, y etiquetas.

**3) Colors**
- **Backgrounds:**
    - Principal: Blanco (#FFFFFF) para la mayoría de las páginas.
    - Secundario: Beige Suave (#F5F5DC) para secciones diferenciadas.
- **Textos:**
    - Primario: Vino Tinto (#8B0000) para el contenido principal.
    - Secundario: Negro (#000000) para subtítulos y textos complementarios.
- **Elementos Interactivos:**
    - Botones: Oro Antiguo (#CFAE75) con texto en Marrón Bodega (#5D4037).
    - Hover: Burdeos (#800020) para resaltar interacciones.

**4) Spacing**
- **Margenes y Padding:**
    - Margen general de 16px alrededor del contenido.
    - Espaciado de 8px entre elementos relacionados.
    - Uso de espacio en blanco para asegurar una lectura cómoda y evitar la saturación visual.

**5) Tono de Comunicación y Lenguaje**
- **Tono:** Formal y Respetuoso, reflejando la seriedad y profesionalismo en la gestión del viñedo.
- **Lenguaje:** Claro y Preciso, evitando tecnicismos innecesarios pero manteniendo la profesionalidad.

**6) Assets**
- **Iconos:**
    - **Set de Iconos:** Se usarán set de iconos de un proveedor de iconos open source como Font Awesome o Material Icons. Se tratará en lo posible buscar un estilo lineal y minimalista.
    - **Formato:** Los iconos estarán en formato SVG para asegurar la escalabilidad y la calidad en diferentes resoluciones.
    - **Nombres de Archivos:** Los iconos serán nombrados de manera coherente y descriptiva para facilitar su uso y referencia dentro del equipo (por ejemplo, `icon-tractor.svg`, `icon-grape.svg`).

- **Imágenes:**
    - **Banco de Imágenes:** Las imagenes serán almacenadas en un repositorio de manera organizada. Estás estarán optimizadas para web en formatos de JPEG o WebP.
    - **Resolución:** Asegurar que las imágenes de alta calidad tengan una resolución adecuada para pantallas retina (2x) y no retina.
    - **Carpetas:** Organizar las imágenes en carpetas según su uso (por ejemplo, `/assets/images/landscape`, `/assets/images/products`).
    - **Nombres de Archivos:** Se nombrarán las imágenes de manera clara y coherente para facilitar su búesqueda y reutilización (por ejemplo, `vineyard-sunset.jpg`, `grape-cluster.webp`).

- **Logo:**
    - **Variantes de Logo:** Se incluirá versiones del logo para fondos claroa y oscuros en los formatos PNG y SVG.

- **Componentes de UI:**
    - **Design System:** Se implementará un sistema de diseño que incluirá componentes reutilizables como botones, tarjetas, formularios, etc., con su correspondiente documentación.
    - **Formato:** Los componentes estarán disponibles en formato Sketch, Figma o Adobe XD.
    -
**7) Fonts**
- **Fuentes Primarias:**
    - **Lora:** Esta fuente se utilizará para títulos y textos principales.
    - **Open Sans:** Se utilizará para textos secundarios, menús y etiquetas.


- **Implementación Web:**
    - **CDN:** Podremos incluir las fuentes usando Content Delivery Network (CDN) como Google Fonts.
    - **Cargas Locales:** Contaremos con una opción para poder cargar las fuentes localmente desde el servidor.
- **Jerarquía Tipográfica:**
    - Se definirán tamaños y pesos específicos para cada tipo de texto (h1, h2, párrafos).


### 4.1.2. Web Style Guidelines.

**1) Layout**
- **Sistema de Grid:** Basado en un layout de columnas para garantizar flexibilidad y adaptabilidad en diferentes tamaños de pantalla.
- **Headers y Footers:** Fijos en la parte superior e inferior de la pantalla con espacio para navegación principal, búsqueda, y acceso rápido a secciones clave.
- **Cards:** Usados para mostrar módulos individuales como  con sombras y bordes redondeados para un aspecto moderno.

**2) Responsive Design**
- **Desktop:** Columnas de contenido principal, con menús laterales y una barra de búsqueda.
- **Tablet:** Columnas de contenido, con navegación accesible desde un menú desplegable y expandido para adaptarse a la pantalla extendida.
- **Mobile:** Columnas de contenido, navegación a través de un menú desplegable.

**3) Interaction Design**
- **Botones:** Grandes y fáciles de interactuar, con animaciones para indicar interactividad.
- **Formularios:** Campos claros y espaciados, con validación en tiempo real y mensajes de error amigables.

**4) Images and Icons**
- **Imágenes:** De alta calidad y representativas del viñedo y sus operaciones, optimizadas para web.
- **Íconos:** Set de íconos de estilo lineal y minimalista.

**5) Repositorio Central**
- **Organización:**
    - **Carpeta de Estilos:** Se creará una carpeta donde se almacenen todos los archivos CSS y SASS.
    - **Repositorio de Assets:** Todos los activos visuales como imágenes, iconos y logos estarán centralizados en una carpeta con subcarpetas organizadas por tipo.
    - **Versionado:** Se usará Git para rastrear cambios en los archivos de estilos y para asegurarse de que todos los miembros del equipo trabajen con la versión más reciente.

## 4.2. Information Architecture.

### 4.2.1. Organization Systems.

- **Jerarquía de Contenidos:**
    - La información se organiza en niveles jerárquicos que van de lo general a lo específico, facilitando la navegación progresiva.
    - **Secciones Principales:** Incluyen áreas clave, como por ejemplo "Gestión del Viñedo", "Planificación", y "Reportes".
    - **Subsecciones:** Cada sección principal se divide en subsecciones más específicas, por ejemplo dentro de "Gestión del Viñedo" se pueden encontrar "Mantenimiento", "Cosecha", "Riego", etc.

- **Agrupación de Contenidos:**
    - El contenido relacionado se agrupa en módulos o categorías claras, facilitando la comprensión del usuario.
    - Se prioriza la coherencia y la lógica en la agrupación, evitando redundancias y asegurando que cada elemento esté en el lugar más intuitivo posible.

### 4.2.2. Labeling Systems.

- **Nomenclatura:**
    - Se utiliza un lenguaje claro y directo, evitando tecnicismos y jergas que puedan confundir al usuario.
    - Los nombres de secciones, botones y enlaces son descriptivos, reflejando exactamente lo que el usuario encontrará al hacer clic.

- **Consistencia:**
    - Se mantiene una nomenclatura uniforme en toda la aplicación, evitando la confusión que podría generar el uso de términos diferentes para referirse al mismo concepto.

- **Lenguaje Adaptativo:**
    - El lenguaje utilizado se adapta al contexto del usuario, asegurando que sea fácil de entender tanto para usuarios nuevos como experimentados.

### 4.2.3. SEO Tags and Meta Tags

- **Title Tags:**
    - **Landing Page:** "Gestión del Viñedo - Optimiza tu Producción y Control"
    - **Web Application:** "Panel de Control - Gestión Integral del Viñedo"

- **Meta Description:**
    - **Landing Page:** "Optimiza la producción y gestión de tu viñedo con nuestra aplicación web, diseñada para simplificar la administración y mejorar la eficiencia operativa."
    - **Web Application:** "Accede a todas las herramientas necesarias para la gestión integral de tu viñedo, desde la planificación agrícola hasta la monitorización en tiempo real."

- **Keywords:**
    - **Landing Page:** "gestión de viñedo, administración de viñedo, software agrícola, producción de vino, optimización agrícola"
    - **Web Application:** "panel de control viñedo, herramientas de gestión viñedo, software de viñedo, administración de cosechas, planificación agrícola"

- **Meta Author:**
    - **Landing Page y Web Application:** "Equipo de Desarrollo de Aplicaciones para la Gestión de Viñedos"

- **Meta Charset:**
    - `"UTF-8"`

- **Meta Viewport:**
    - `"width=device-width, initial-scale=1.0"`

### 4.2.4. Searching Systems.

- **Barra de Búsqueda:**
    - La barra de búsqueda estará ubicada de manera prominente en el header, accesible desde cualquier página.
    - Se implementará un sistema de búsqueda predictiva que sugiere resultados mientras el usuario escribe, mejorando la velocidad y precisión de las búsquedas.

- **Filtros y Facetas:**
    - Los usuarios podrán refinar sus resultados de búsqueda mediante filtros y facetas, permitiendo una búsqueda más dirigida y efectiva.

- **Historial de Búsqueda:**
    - Se incluirá una función de historial de búsqueda para que los usuarios puedan acceder rápidamente a búsquedas anteriores.

- **Resultados Relevantes:**
    - Los resultados de búsqueda se ordenarán por relevancia, basados en la frecuencia de uso y la importancia del contenido.

### 4.2.5. Navigation Systems.

- **Navegación Global:**
    - Un menú principal ubicado en el header proporcionará acceso a las secciones clave de la aplicación.
    - El menú estará siempre visible en dispositivos de escritorio.

- **Navegación Contextual:**
    - Menús y enlaces contextuales dentro de cada sección permitirán al usuario profundizar en tareas específicas sin perder la orientación dentro de la aplicación.

- **Navegación Secundaria:**
    - En la barra lateral se presentarán opciones de navegación adicionales, como accesos directos a herramientas y recursos utilizados frecuentemente.

## 4.3. Landing Page UI Design.

El landing page juega un papel esencial en atraer la atención de los visitantes y guiarlos hacia acciones concretas, como inscribirse, adquirir un producto o informarse sobre un servicio. En este apartado, se tratará el diseño de la interfaz de usuario del landing page, enfocándose en los elementos clave que optimizan la experiencia del usuario, creando una página interactiva y fácil de usar.

### 4.3.1. Landing Page Wireframe.
En esta sección se presentan las representaciones de bajo nivel (wireframes) del landing page, diseñadas para dispositivos móviles y de escritorio.  [Wireframe - EvenWine](https://www.figma.com/design/8Z5H7EbcYVg6pBjgebw6eW/Sin-t%C3%ADtulo?node-id=2-29)

**Desktop Web Browser**

![eventwine-landing-wireframe.png](../assets/img/chapter-IV/eventwine-landing-wireframe.png)

Seccion "Sobre Nosotros"

![eventwine-aboutus-wireframe.png](../assets/img/chapter-IV/eventwine-aboutus-wireframe.png)

**Mobile Web Browser**

![eventwine-landing-mobile-wireframe 1.png](../assets/img/chapter-IV/eventwine-landing-mobile-wireframe%201.png)

Seccion "Sobre Nosotros"

![eventwine-aboutus-mobile-wireframe 1.png](../assets/img/chapter-IV/eventwine-aboutus-mobile-wireframe%201.png)

### 4.3.2. Landing Page Mock-up.
**Landing Page Mock-up de nuestra Web Application**
<br>

En esta sección se muestran los mock-ups del landing page, que sirven como una representación visual de alta fidelidad para anticipar cómo se verá y funcionará la interfaz final. Están diseñados tanto para dispositivos móviles como para escritorio.  [Wireframe - EvenWine](https://www.figma.com/design/8Z5H7EbcYVg6pBjgebw6eW/Sin-t%C3%ADtulo?node-id=2-29)

**Desktop Web Browser**

![eventwine-landing.png](../assets/img/chapter-IV/eventwine-landing.png)

Seccion "**Sobre Nosotros**"

![eventwine-aboutus.png](../assets/img/chapter-IV/eventwine-aboutus.png)
<br>

**Mobile Web Browser**

![eventwine-landing-mobile-mockup 1.png](../assets/img/chapter-IV/eventwine-landing-mobile-mockup%201.png)
<br>
Seccion "**Sobre Nosotros**"

![eventwine-aboutus-mobile-mockup 1.png](../assets/img/chapter-IV/eventwine-aboutus-mobile-mockup%201.png)


### 4.4. Mobile Applications UX/UI Design.
### 4.4.1. Mobile Applications Wireframes.

- Acceso a la aplicación
- ![wireframe-mobile (1).png](../assets/img/chapter-IV/wireframe-mobile%20%281%29.png)

- Acuerdos del Servicio (SaaS)
- ![wireframe-mobile (5).png](../assets/img/chapter-IV/wireframe-mobile%20%285%29.png)

- Pantallas de Inicio
- ![wireframe-mobile (4).png](../assets/img/chapter-IV/wireframe-mobile%20%284%29.png)
- 

- Proceso de Vinificación
- ![wireframe-mobile (3).png](../assets/img/chapter-IV/wireframe-mobile%20%283%29.png)
- ![wireframe-mobile (2).png](../assets/img/chapter-IV/wireframe-mobile%20%282%29.png)
- ![wireframe-mobile (6).png](../assets/img/chapter-IV/wireframe-mobile%20%286%29.png)

### 4.4.2. Mobile Applications Wireflow Diagrams.
### 4.4.3. Mobile Applications Mock-ups.

- Acceso a la aplicación
- ![Mockup-mobile (1).png](../assets/img/chapter-IV/Mockup-mobile%20%281%29.png)

- Acuerdos del Servicio (SaaS)  
- ![Mockup-mobile (3).png](../assets/img/chapter-IV/Mockup-mobile%20%283%29.png)

- Pantallas de Inicio
- ![Mockup-mobile (2).png](../assets/img/chapter-IV/Mockup-mobile%20%282%29.png)

- Proceso de Vinificación
- ![mockup-mobile-process-vinification (1).png](../assets/img/chapter-IV/mockup-mobile-process-vinification%20%281%29.png) 
- ![mockup-mobile-process-vinification (2).png](../assets/img/chapter-IV/mockup-mobile-process-vinification%20%282%29.png) 
- ![mockup-mobile-process-vinification (3).png](../assets/img/chapter-IV/mockup-mobile-process-vinification%20%283%29.png) 
- ![mockup-mobile-process-vinification (4).png](../assets/img/chapter-IV/mockup-mobile-process-vinification%20%284%29.png) 
- ![mockup-mobile-process-vinification (5).png](../assets/img/chapter-IV/mockup-mobile-process-vinification%20%285%29.png) 
- ![mockup-mobile-process-vinification (6).png](../assets/img/chapter-IV/mockup-mobile-process-vinification%20%286%29.png) 
- 
### 4.4.4. Mobile Applications User Flow Diagrams.
### 4.5. Mobile Applications Prototyping.
### 4.5.1. Android Mobile Applications Prototyping.



## 4.6. Web Applications UX/UI Design.

El objetivo de esta sección Web Applications UX/UI Design es detallar el enfoque y las estrategias utilizadas en el diseño de la experiencia y la interfaz de usuario para la aplicación web. Se busca explicar cómo las decisiones tomadas en términos de diseño visual y funcionalidad contribuyen a mejorar la usabilidad, accesibilidad y satisfacción del usuario final. Además, se pretende mostrar cómo estos elementos de diseño ayudan a cumplir los objetivos comerciales del proyecto, asegurando una interacción fluida y eficiente para los usuarios en diferentes dispositivos.

### 4.6.1. Web Applications Wireframes.

En esta sección se muestran los wireframes realizados para nuestro Web Application.

![Wireframe-Login.png](../assets/img/chapter-IV/Wireframe-Login.png)

![Wireframe-registrar-productor.png](../assets/img/chapter-IV/Wireframe-registrar-productor.png)

![Wireframes-Home - Productor.png](../assets/img/chapter-IV/Wireframes-Home%20-%20Productor.png)

![Wireframes-Home - Productor - menu.png](../assets/img/chapter-IV/Wireframes-Home%20-%20Productor%20-%20menu.png)

![Wireframes-Login -Asistente - Elixir Control.png](../assets/img/chapter-IV/Wireframes-Login%20-Asistente%20-%20Elixir%20Control.png)

![Wireframes-Registrar - Asistente- Event-Wine.png](../assets/img/chapter-IV/Wireframes-Registrar%20-%20Asistente-%20Event-Wine.png)
![Wireframes-Registrar - Productor  - Event-Wine.png](../assets/img/chapter-IV/Wireframes-Registrar%20-%20Productor%20%20-%20Event-Wine.png)

![Wireframes-Event-Wine Management-Aging.png](../assets/img/chapter-IV/Wireframes-Event-Wine%20Management-Aging.png)

![Wireframes-Event-Wine Management-Batches.png](../assets/img/chapter-IV/Wireframes-Event-Wine%20Management-Batches.png)

![Wireframes-Event-Wine Management-Bottling.png](../assets/img/chapter-IV/Wireframes-Event-Wine%20Management-Bottling.png)

![Wireframes-Event-Wine Management-Clarification.png](../assets/img/chapter-IV/Wireframes-Event-Wine%20Management-Clarification.png)

![Wireframes-Event-Wine Management-Fermentation.png](../assets/img/chapter-IV/Wireframes-Event-Wine%20Management-Fermentation.png)

![Wireframes-Event-Wine Management-Pressing.png](../assets/img/chapter-IV/Wireframes-Event-Wine%20Management-Pressing.png)


### 4.6.2. Web Applications Wireflow Diagrams.

Los Wireflows se emplean principalmente en el diseño de la experiencia de usuario (UX) y son especialmente útiles para aplicaciones que incluyen flujos de trabajo e interacciones complejas.

![alt text](<../assets/img/MetaSoft-App-Web-SV51 (1).png>)

### 4.6.3. Web Applications Mock-ups.

En esta sección se muestran los mock-ups realizados para nuestro Web Application.

**Login - EventWine**

En esta sección se muestra el diseño del login de la aplicación web, con opciones para iniciar sesión como asistente o productor de vinos y piscos artesanales.

![Login - Event-Wine.png](../assets/img/chapter-IV/Login%20-%20Event-Wine.png)

**Login - Productor - EventWine**

En el caso del login de Productor, se muestra un formulario de inicio de sesión con los campos email y contraseña.

![Inicio de sesión- Productor Event-Wine.png](../assets/img/chapter-IV/Inicio%20de%20sesi%C3%B3n-%20Productor%20Event-Wine.png)

**Login - Asistente - EventWine**

En el caso del login de Asistente, se muestra un formulario de inicio de sesión con los campos Productor al que se encuentra asociado y nombre de usuario.

![Login -Asistente - Event-Wine.png](../assets/img/chapter-IV/Login%20-Asistente%20-%20Event-Wine.png)

**Registrar - Productor  - EventWine**

En esta sección se muestra un formulario para registrar nuevos productores de vinos, con campos para ingresar información de la empresa y credenciales.

![Registrar - Productor  - Event-Wine.png](../assets/img/chapter-IV/Registrar%20-%20Productor%20%20-%20Event-Wine.png)

**Registrar - Asistente - EventWine**

En esta sección se muestra un formulario para registrar nuevos asistentes, con campos para ingresar datos personales y credenciales.

![Registrar - Asistente-Event-Wine.png](../assets/img/chapter-IV/Registrar%20-%20Asistente-Event-Wine.png)

**Home Productor**

![Home - Productor.png](../assets/img/chapter-IV/Home%20-%20Productor.png) 

**Home Productor - Menú Lateral**

![Home - Productor - menu.png](../assets/img/chapter-IV/Home%20-%20Productor%20-%20menu.png)


**Proceso de Vinificación - EventWine**

* **Batches**

* ![Event-Wine Management-Batches.png](../assets/img/chapter-IV/Event-Wine%20Management-Batches.png)

* **Fermentation**

* ![Event-Wine Management-Fermentation.png](../assets/img/chapter-IV/Event-Wine%20Management-Fermentation.png)

* **Clarification**

* ![Event-Wine Management-Clarification.png](../assets/img/chapter-IV/Event-Wine%20Management-Clarification.png)
* 
* **Pressing**
* 
* ![Event-Wine Management-Pressing.png](../assets/img/chapter-IV/Event-Wine%20Management-Pressing.png)
* **Aging**
* 
* ![Event-Wine Management-Aging.png](../assets/img/chapter-IV/Event-Wine%20Management-Aging.png)
* 
* **Bottling**
* 
* ![Event-Wine Management-Bottling.png](../assets/img/chapter-IV/Event-Wine%20Management-Bottling.png)
*

----

### 4.6.4. Web Applications User Flow Diagrams.

![userFlow.png](../assets/img/chapter-IV/userFlow.png)


## 4.7. Web Applications Prototyping.

El prototipado de aplicaciones web es esencial porque permite visualizar y probar el diseño y la funcionalidad de una aplicación antes de su desarrollo completo. Este proceso es clave para detectar posibles problemas de usabilidad y asegurar que el producto final cumpla con las expectativas de los usuarios y clientes.

![prototype-evenWine-v1.png](../assets/img/chapter-IV/v1-prototype-eventWine.png)

Enlace del video:

Enlace figma: https://www.figma.com/design/8Z5H7EbcYVg6pBjgebw6eW/Sin-t%C3%ADtulo?node-id=0-1&t=cTHuHsoqjyPNkdl2-1 
## 4.8. Domain-Driven Software Architecture.

El sistema Event Wine se ha construido aplicando el enfoque Domain-Driven Design (DDD), organizando su lógica en dos Bounded Contexts: WinemakingProcess. Esta arquitectura facilita la separación de responsabilidades y mejora la escalabilidad. A continuación, se presentan los diagramas de contexto, contenedores y componentes usando el modelo C4.
## 4.8.1. Software Architecture Context Diagram.

El diagrama de contexto representa la vista más general del sistema Event wine. En él se muestran los dos tipos de usuarios principales: el vinicultor, que accede a través de la plataforma web para gestionar todo el proceso de producción, y el trabajador de campo, que utiliza tanto la aplicación web como la aplicación móvil para actualizar datos y visualizar el estado de los lotes. El sistema se despliega mediante distintos servicios en la nube, utilizando Vercel para el frontend (Vue.js), Azure App Service para el backend (Spring Boot) y Azure MySQL como base de datos. Este diagrama permite identificar claramente los límites del sistema y sus principales relaciones externas.

![](../assets/img/chapter-IV/Context%20Diagram.png)

### 4.8.2. Software Architecture Container Diagrams.

El diagrama de contenedores presenta la descomposición tecnológica interna de Event wine. El sistema cuenta con un frontend web desarrollado en Vue.js, una aplicación móvil creada con Flutter, un backend construido en Spring Boot y una base de datos MySQL desplegada en Azure. Tanto la aplicación móvil como la web se comunican con el backend mediante APIs REST. Esta arquitectura permite una separación de responsabilidades clara entre la interfaz de usuario, la lógica de negocio y la persistencia de datos. El diseño favorece la escalabilidad del sistema y su mantenimiento independiente por plataforma.

![](../assets/img/chapter-IV/Container%20Diagram.png)



### 4.8.3. Software Architecture Components Diagrams.

El backend de Event wine ha sido implementado siguiendo los principios de Domain-Driven Design (DDD), y se estructura en dos Bounded Contexts principales: WinemakingProcess. Cada contexto contiene sus propios componentes independientes, entre ellos controladores REST, servicios de aplicación y repositorios. En el caso del proceso de vinificación, se han modelado subdominios específicos como fermentación, clarificación, prensado y añejamiento, cada uno con su lógica aislada. Esta separación modular permite un desarrollo más enfocado, facilita las pruebas, y mejora la mantenibilidad y extensibilidad del sistema conforme evolucione el negocio.

![](../assets/img/chapter-IV/component%20diagram.png)


## 4.9. Software Object-Oriented Design.

Esta sección presenta el diseño orientado a objetos del sistema, en el cual se modelan las principales clases, atributos, métodos y relaciones entre componentes. Se incluye un diagrama de clases que representa la estructura interna del backend y un diccionario de clases que describe de forma detallada cada entidad relevante.


### 4.9.1. Class Diagrams.
El siguiente diagrama de clases muestra las entidades centrales del sistema, sus relaciones de asociación, composición y herencia, así como los atributos principales. Está alineado con el diseño aplicado en el backend, basado en agregados de dominio como Lote, Fermentación, entre otros.

![](../assets/img/chapter-IV/class%20diagram.png)


### 4.9.2. Class Dictionary.

A continuación, se detalla el diccionario de clases, que incluye una descripción individual de cada clase del sistema, sus atributos y responsabilidades. Este diccionario sirve como referencia técnica para comprender la estructura y funciones del modelo de dominio.


### Clase: `BatchService`

**Descripción:** Servicio de aplicación para ejecutar acciones sobre el ciclo de vida de un lote.

**Métodos:**
- `createBatch(cmd)`
- `updateBatch(cmd)`
- `deleteBatch(cmd)`
- `addFermentationToBatch(cmd)`
- `addClarificationToBatch(cmd)`
- `addPressingToBatch(cmd)`
- `addAgingToBatch(cmd)`



### Clase: `Batch`

**Descripción:** Representa un lote de vino en proceso.

**Atributos:**  
`id`, `grapeVariety`, `harvestDate`, `vineyardCode`, `status`

---

### Clase: `Fermentation`

**Descripción:** Proceso de fermentación aplicado a un lote.

**Atributos:**  
`id`, `batchId`, `startDate`, `endDate`, `initialDensity`, `finalPh`

---

### Clase: `Clarification`

**Descripción:** Proceso de clarificación de un lote.

**Atributos:**  
`id`, `batchId`, `method`, `filtrationDate`, `clarityLevel`

---

### Clase: `Pressing`

**Descripción:** Representa la etapa de prensado del vino.

**Atributos:**  
`id`, `batchId`, `pressType`, `mustVolume`, `appliedPressure`

---

### Clase: `Aging`

**Descripción:** Representa el añejamiento del vino.

**Atributos:**  
`id`, `batchId`, `barrelType`, `durationMonths`, `inspectionResult`

---

### Clase: `User`

**Descripción:** Usuario del sistema vinculado a un perfil.

**Atributos:**  
`id`, `username`, `passwordHash`, `profileId`

---

### Clase: `Profile`

**Descripción:** Productor de vino con datos personales y de empresa.

**Atributos:**  
`id`, `firstName`, `lastName`, `emailAddress`, `ruc`, `companyName`, etc.




---

## 4.10. Database Design.

El diseño de la base de datos es un aspecto crucial en el desarrollo de software, ya que define cómo se estructuran y almacenan los datos. A continuación se presenta el diagrama de la base de datos, que ilustra las tablas, sus atributos y las relaciones entre ellas.

### 4.10.1. Database Diagram

El siguiente diagrama muestra la estructura lógica de la base de datos relacional implementada. Las tablas reflejan los objetos del dominio, tales como productores, lotes, procesos de vinificación. Se incluyen las claves primarias y foráneas, así como los tipos de relaciones entre entidades.

![](../assets/img/chapter-IV/database%20diagram.png)

El diseño se centra en la tabla batches, que actúa como entidad principal para el seguimiento del proceso vinícola. Cada batch se relaciona con etapas como fermentation, clarification, pressing y aging, permitiendo una trazabilidad completa del producto. Además, la tabla profiles vincula la operación con los datos del productor y los insumos utilizados. Esta estructura respeta las mejores prácticas de normalización y facilita las operaciones CRUD desde la capa de aplicación.

 

