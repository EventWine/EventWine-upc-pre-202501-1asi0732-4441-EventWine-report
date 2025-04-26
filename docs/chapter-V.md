# Chapter V: Product Implementation
La implementación, validación y despliegue del producto son esenciales para asegurar que la visión del producto se convierta en una realidad funcional y accesible para nuestros usuarios.

## 5.1. Software Configuration Management.
En esta sección se describen y explican los productos empleados en el proyecto digital, especificando su finalidad, la forma de acceso y respetando las restricciones establecidas.

1. Project Management:
Para la administración del proyecto se utilizaron herramientas de comunicación y control de versiones. Se creó una organización en GitHub para gestionar el código y las versiones del proyecto. Asimismo, se utilizaron plataformas como Google Meet y Discord para coordinar reuniones de equipo y mantener la comunicación interna.

- GitHub: https://github.com/

- Google Meet: https://meet.google.com/

- Discord: https://discord.com/download

2. Requirement Management:
La recopilación, organización y priorización de requisitos se realizó utilizando herramientas específicas. Se utilizó Trello como una solución visual para la organización de tareas mediante tableros personalizados, mientras que Pivotal Tracker se empleó para gestionar y dar seguimiento al Product Backlog del proyecto.

Trello: https://trello.com/es

Pivotal Tracker: https://www.pivotaltracker.com/

3. Product UX/UI Design:
Para el diseño de la experiencia de usuario (UX) y la interfaz de usuario (UI), se utilizó Figma, permitiendo la creación de wireframes, mockups y prototipos interactivos que ayudaron a validar el diseño antes de su desarrollo. Además, UXPressia se empleó para desarrollar User Personas, Empathy Maps, Journey Maps e Impact Maps, mientras que Miro fue utilizado para diseñar los escenarios As-Is y To-Be.

Figma: https://www.figma.com/downloads/

UXPressia: https://uxpressia.com/

Miro: https://miro.com/es/

4. Software Development:
Para construir la Landing Page de la startup se utilizaron HTML5, CSS3 y JavaScript. En cuanto a la Web Application, se optó por Vue.js en el Frontend y ASP.NET Core Framework con C# en el Backend. Para el desarrollo se utilizaron los siguientes entornos de programación, por último para el desarrollo movil se utilizó Flutter.

- Visual Studio Code: Usado principalmente para el desarrollo de la Landing Page y el desarrollo movil, con diversas extensiones que facilitaron la productividad.

- JetBrains Toolbox: Proporcionó un entorno robusto para el desarrollo web, con funcionalidades avanzadas de edición y depuración.

- Visual Studio Code: https://code.visualstudio.com/

- JetBrains Toolbox: https://www.jetbrains.com/toolbox-app/

5. Software Documentation:
La documentación técnica del proyecto se elaboró y almacenó en GitHub, aprovechando su funcionalidad como plataforma de control de versiones y alojamiento de documentación. Se crearon repositorios específicos, utilizando archivos en formato Markdown para facilitar la edición y colaboración entre los miembros del equipo.

GitHub: https://github.com/
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
En este proyecto, emplearemos GitHub como plataforma principal y sistema de control de versiones para gestionar el código fuente de las distintas partes del proyecto dentro de una organización.

**Repositorios en GitHub**
- Organización: https://github.com/EventWine
- Landing Page: https://github.com/EventWine/EventWine-Landing-Page   
- Report : https://github.com/EventWine/EventWine-upc-pre-202501-1asi0732-4441-EventWine-report
- Backend: https://github.com/EventWine/EventWine-Platform-.NET
- ForntEnd Web: https://github.com/EventWine/EventWine-FrontEnd 
- FrontEnd Mobile:

### 5.1.3. Source Code Style Guide & Conventions.
En esta sección se definen las convenciones y prácticas que adoptaremos para el nombramiento de elementos y la programación en los lenguajes y tecnologías utilizados en el proyecto: HTML, CSS, JavaScript, Vue.js, C#, Gherkin y Flutter. Todas las convenciones emplearán nomenclatura en inglés y se basarán en estándares reconocidos de codificación.

1. HTML y CSS:
- Siguiendo las recomendaciones del W3C y buenas prácticas de la comunidad, se establecerán reglas para el nombramiento de elementos HTML y la escritura de estilos en CSS.

- Se adoptarán las guías de estilo de Google para HTML y CSS, que incluyen el uso de indentación de 2 espacios, comillas dobles en atributos y comentarios descriptivos.

- Se utilizará la metodología BEM (Bloque, Elemento, Modificador) para estructurar las clases de CSS, promoviendo modularidad y facilidad de mantenimiento.

-Se aplicará el uso semántico de las etiquetas HTML para describir correctamente el contenido del sitio web.

En el caso de Vue.js, se seguirán las convenciones de la comunidad, como el uso de PascalCase para componentes y camelCase para propiedades y métodos.

2. JavaScript:
- Se respetarán las directrices de codificación de MDN y las guías de estilo de Google, incluyendo:
    - Uso de camelCase para variables y funciones.

    - Declaración de variables preferiblemente con let y const.
    - Inclusión de punto y coma al final de las instrucciones.
    - Uso de comillas simples para strings y funciones flecha donde sea apropiado.


3. Vue.js:
- Se seguirán las buenas prácticas recomendadas por la comunidad de Vue, tales como:
    - Uso de abreviaturas en directivas v-bind y v-on.

    - Organización estructurada de componentes en carpetas basadas en su funcionalidad.

    - Correcta gestión del ciclo de vida de los componentes.

4. C# (ASP.NET Core):
- Se aplicarán las convenciones de codificación oficiales de Microsoft:

    - Nombres de clases y métodos en PascalCase.

    - Variables locales y parámetros en camelCase.

-   Documentación mediante comentarios XML.

Se promoverán buenas prácticas en ASP.NET Core, como la inyección de dependencias, separación de capas (Controller, Service, Repository) y el uso de ViewModels para la comunicación entre controladores y vistas.

5. Gherkin:
- Se utilizarán las convenciones recomendadas para escribir especificaciones claras en Gherkin:

    - Uso de palabras clave Given, When, Then.

    - Redacción sencilla, organizada en contexto, acción y resultado.

    - Reutilización de pasos de prueba y modularización de escenarios conforme a las mejores prácticas de Cucumber.

6. Flutter:
- Para el desarrollo de aplicaciones móviles en Flutter:

    - Se adoptarán las convenciones oficiales de Dart y Flutter, como:

    - Uso de camelCase para nombres de variables, funciones y parámetros.

    - Uso de PascalCase para clases, widgets y nombres de archivos de componentes.

    - Organización modular del código, separando widgets, servicios y modelos en carpetas específicas.

Se priorizará el uso de widgets reutilizables, buenas prácticas de manejo de estado y separación clara entre lógica de negocio y presentación.

Además de estas guías, se fomentará el uso de buenas prácticas de ingeniería de software, como modularidad, reutilización de componentes, legibilidad de código, optimización del rendimiento y medidas de seguridad.
Con estas convenciones buscamos garantizar la coherencia, calidad y facilidad de mantenimiento del proyecto a lo largo de su ciclo de vida.

### 5.1.4. Software Deployment Configuration.

En esta sección detallaremos la configuración requerida para llevar a cabo el despliegue exitoso de cada uno de los productos digitales de nuestra solución: la Landing Page, los Web Services (APIs) y las Frontend Web Applications.

- #### Pasos para el despliegue
**Landing Page:**

- Clonar o descargar el repositorio desde GitHub.

- Configurar el servidor web destinado a alojar la Landing Page.

-Transferir los archivos HTML, CSS y JavaScript al directorio correspondiente en el servidor.

-Asegurar la correcta instalación de cualquier dependencia adicional, como bibliotecas de JavaScript o recursos de imagen.

-Comprobar que la Landing Page se visualice adecuadamente en el navegador.

- #### Web Services (API):

- Preparar el código fuente de los servicios web, garantizando una estructura organizada y documentación adecuada.

- Configurar un entorno de desarrollo o pruebas donde se puedan realizar verificaciones exhaustivas antes del despliegue definitivo.

-   Implementar el servicio en un servidor configurado para producción.

- Establecer los mecanismos de seguridad y autenticación necesarios según los requerimientos del sistema.

- Documentar la API utilizando OpenAPI Specification, para facilitar su integración y uso por parte de otras aplicaciones o servicios.

- #### Frontend Web Applications:

- Clonar el repositorio correspondiente desde GitHub.

- Compilar y empaquetar las aplicaciones frontend. Dado que trabajamos con Vue.js, será necesario ejecutar los comandos de construcción (npm run build) para generar los archivos estáticos.

- Una vez generados, los archivos pueden ser alojados en un servidor de aplicaciones compatible con archivos estáticos, como Nginx, o plataformas como GitHub Pages en caso de proyectos estáticos más sencillos.

- Si se requiere, configurar las rutas en el servidor para que correspondan correctamente con las rutas definidas dentro de las aplicaciones frontend.

## 5.2. Product Implementation & Deployment.
### 5.2.1. Sprint Backlogs.

### 5.2.2. Implemented Landing Page Evidence

### 5.2.3. Implemented Frontend-Web Application Evidence

### 5.2.4. Acuerdo de Servicio - SaaS

### 5.2.5. Implemented Native-Mobile Application Evidence

### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

### 5.2.7. RESTful API documentation

### 5.2.8. Team Collaboration Insights

## 5.3. Video About-the-Product