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


##### 5.2.1.2. Sprint Backlog 1.

<!--Status -> (To-do / In-Process / To-Review / Done) -->

<table>
    <thead>
        <tr>
            <th colspan="7">Srpint #</th>
            <th> Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <!--FILA 1-->
        <tr>
            <td colspan="1">User Story</td>
            <td colspan="15">Work-Item / Task</td>
        </tr>
        <!--FILA 2-->
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Description</td>
            <td>Estimation (hours)</td>
            <td>Assigned To</td>
            <td>Status</td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td rowspan="4" >US-001</td>
            <td rowspan="4" >Hipervínculos en el encabezado</td>
            <td>T001</td>
            <td>Definir enlaces del encabezado	</td>
            <td>Identificar y organizar los enlaces del encabezado.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 4-->
        <tr>
            <td>T002</td>
            <td>Implementar hipervínculos</td>
            <td>Añadir hipervínculos en HTML</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 5-->
        <tr>
            <td>T003</td>
            <td>Estilizar con CSS	</td>
            <td>Aplicar estilos básicos a los enlaces del encabezado</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td>T004</td>
            <td>Pruebas de funcionamiento	</td>
            <td>Asegurarse de que los hipervínculos funcionen correctamente.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td rowspan="3"> US-002	</td>
            <td rowspan="3">Información sobre beneficios o servicios de la app</td>
            <td> T005 </td>
            <td>Recopilar información de beneficios</td>
            <td>Obtener y redactar la información sobre los beneficios de la aplicación.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>T006</td>
            <td>Implementar en el sitio	</td>
            <td>Incluir la información de beneficios en la página correspondiente.	</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>T007</td>
            <td>Pruebas de visualización	</td>
            <td>Asegurarse de que la información esté visible y bien organizada.	</td>
            <td>1</td>
            <td></td> 
            <td>Done</td>
        </tr>
        <!--FILA 10-->
        <tr>
            <td rowspan="3"> US-003	</td>
            <td rowspan="3">Mostrar los planes disponibles</td>
            <td> T008 </td>
            <td>Definir estructura de precios</td>
            <td>Establecer la estructura de precios a seguir en la sección.</td>
            <td>4</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 11-->  
        <tr>
            <td>T009</td>
            <td>Implementar la funcionalidad de los planes	</td>
            <td>Crear la estructura de precios en HTML.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <!--FILA 12-->  
        <tr>
            <td>T010</td>
            <td>Estilizar con CSS	</td>
            <td>Aplicar estilos a la estructura de precios.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 13-->
        <tr>
            <td rowspan="5"> US-004	</td>
            <td rowspan="5">Información util en el footer </td>
            <td> T011 </td>
            <td>Recopilar opiniones</td>
            <td>Obtener y redactar opiniones de usuarios.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <!--FILA 14-->
        <tr>
            <td>T012</td>
            <td>Recopilar información útil	</td>
            <td>Organizar y decidir qué información incluir en el footer.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 15-->  
        <tr>
            <td>T013</td>
            <td>Implementar contenido en el footer</td>
            <td>Añadir la información útil al footer.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 16-->
        <tr>
            <td>T014</td>
            <td>Estilizar footer</td>
            <td> Dar estilo y formato al footer utilizando CSS.</td>
            <td>1</td>
            <td></td>
            <td>Done</td>   
        </tr>
        <!--FILA 17-->  
        <tr>
            <td> T015 </td>
            <td>Pruebas de visualización</td>
            <td>Verificar que la información sea clara y legible.	</td>
            <td>1</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td rowspan="4"> US-005	</td>
            <td rowspan="4">Información sobre el producto	</td>
            <td> T016 </td>
            <td>Definir contenido sobre el producto	</td>
            <td>Recopilar y escribir la información relevante sobre el producto.	</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <!--FILA 14-->
        <tr>
            <td>T017</td>
            <td>Implementar el contenido en el sitio	</td>
            <td>Incluir la información en la página adecuada.</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 15-->  
        <tr>
            <td>T018</td>
            <td>Estilizar y ajustar visualización	</td>
            <td>Ajustar el diseño y la visualización del contenido.	</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr>
        <!--FILA 16-->
        <tr>
            <td>T019</td>
            <td>Pruebas de visualización</td>
            <td> Comprobar que la información sea visible y bien organizada.</td>
            <td>1</td>
            <td></td>
            <td>Done</td>   
        </tr>
        <!--FILA 17-->  
        <tr>
            <td rowspan="4"> US-018	</td>
            <td rowspan="4">Implementar opción de cambio de idioma	</td>
            <td> T020 </td>
            <td>Añadir la funcionalidad para cambiar el idioma de la aplicación en Angular.	</td>
            <td>5</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td> T021 </td>
            <td>Definir textos traducidos</td>
            <td>Proveer textos traducidos en los diferentes idiomas soportados.</td>
            <td>4</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td> T022 </td>
            <td>Pruebas de funcionalidad de idiomas</td>
            <td>Verificar que el cambio de idioma funcione correctamente en toda la aplicación.	</td>
            <td>3</td>
            <td></td>
            <td>Done</td>
        </tr> 
        <tr>
            <td rowspan="4"> US-018	</td>
            <td rowspan="4">Implementar opción de cambio de idioma	</td>
            <td> T026 </td>
            <td>Implementar diseño responsive utilizando CSS</td>
            <td>5</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td> T027 </td>
            <td>Pruebas de visualización en diferentes dispositivos</td>
            <td>Probar el diseño en varios dispositivos (móvil, tablet, desktop).	</td>
            <td>4</td>
            <td></td>
            <td>Done</td> 
        </tr>
        <tr>
            <td> T028 </td>
            <td>Ajustes finales de responsividad</td>
            <td>Realizar ajustes finales para asegurar una experiencia responsive óptima.		</td>
            <td>2</td>
            <td></td>
            <td>Done</td>
        </tr> 
    </tbody>
</table>


##### 5.2.2.2. Sprint Backlog 2
<table>
  <thead>
    <tr>
      <th>User Story</th>
      <th>Title</th>
      <th>Id</th>
      <th>Title</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
      <th>Status</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-009</td>
      <td>Integración de Validadores en Formularios de la App Web</td>
      <td>T001</td>
      <td>Login de distribuidor y productor.</td>
      <td>Implementar formulario para logeo de distribuidores y productores.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-031</td>
      <td>Registro de Datos de Productores</td>
      <td>T002</td>
      <td>Registro de productor.</td>
      <td>Implementar formulario para registro de nuevos productores.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-006</td>
      <td>Registro de Entrada de Insumos</td>
      <td>T003</td>
      <td>Registro de insumos.</td>
      <td>Agregar función para registrar insumos en el inventario.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-007</td>
      <td>Registro de Salida de Productos Terminados</td>
      <td>T004</td>
      <td>Salida de productos.</td>
      <td>Agregar función para actualizar el inventario.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-008</td>
      <td>Visualizar Datos de Solicitud</td>
      <td>T005</td>
      <td>Mostrar datos de solicitud.</td>
      <td>Añadir función para mostrar los datos de solicitud y filtrarlos.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-020</td>
      <td>Gestión de Lotes de Producción</td>
      <td>T006</td>
      <td>Visualización de lotes.</td>
      <td>Añadir funcionalidad para que el usuario pueda visualizar todos los lotes que ha gestionado.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-032</td>
      <td>Edición de Lotes</td>
      <td>T007</td>
      <td>Editar lotes.</td>
      <td>Añadir funcionalidad para que el usuario pueda modificar la información de un lote.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-033</td>
      <td>Eliminación de lotes</td>
      <td>T008</td>
      <td>Eliminar lote seleccionado.</td>
      <td>Añadir funcionalidad para que el usuario pueda eliminar un lote seleccionado.</td>
      <td>2</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-009</td>
      <td>Registro de Datos de Clientes</td>
      <td>T009</td>
      <td>Registro de nuevo cliente.</td>
      <td>Agregar opción para poder registrar un nuevo cliente con sus datos.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-034</td>
      <td>Visualización de detalles de cliente</td>
      <td>T010</td>
      <td>Visualizar informacion del cliente.</td>
      <td>Implementar funcionalidad para ver los detalles del cliente seleccionado.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-035</td>
      <td>Edición de información del cliente</td>
      <td>T011</td>
      <td>Modificar datos del cliente</td>
      <td>Implementar función para poder modificar los datos del cliente.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-036</td>
      <td>Eliminación de cliente</td>
      <td>T012</td>
      <td>Eliminar el cliente de la lista</td>
      <td>Implementar función para eliminar un cliente de la lista.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-011</td>
      <td>Registro de Pedidos de Clientes</td>
      <td>T013</td>
      <td>Registro de pedido.</td>
      <td>Agregar formulario para que el usuario registre su pedido.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-037</td>
      <td>Visualización de pedidos</td>
      <td>T014</td>
      <td>Visualizar lista de pedidos.</td>
      <td>Agregar funcionalidad para que el usuario vea la lista de pedidos.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-012</td>
      <td>Visualización de Productos Disponibles</td>
      <td>T015</td>
      <td>Visualización de productos.</td>
      <td>Añadir función para que el usuario pueda ver la lista de productos.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-038</td>
      <td>Búsqueda de productos</td>
      <td>T016</td>
      <td>Sistema de búsqueda de productos.</td>
      <td>Añadir funcionalidad para que el usuario pueda realizar la búsqueda de un pedido.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-013</td>
      <td>Visualizar Historial de Pedidos</td>
      <td>T017</td>
      <td>Acceso al historial.</td>
      <td>Agregar opción para que el usuario pueda ver la lista de pedidos realizados.</td>
      <td>3</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-039</td>
      <td>Filtrado por fecha.</td>
      <td>T018</td>
      <td>Filtrado de pedido por fecha.</td>
      <td>Agregar opción de poder filtrar un pedido específico usando un rango de fechas.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
    <tr>
      <td>US-40</td>
      <td>Detalles del Pedido</td>
      <td>T019</td>
      <td>Detalles del pedido.</td>
      <td>Agregar opción para mostrar los detalles completos de un pedido.</td>
      <td>4</td>
      <td></td>
      <td>To-do</td>
    </tr>
  </tbody>
</table>

#### 5.2.3.2.Sprint Backlog 3.


<!--Status -> (To-do / In-Process / To-Review / Done) -->

<table>
    <thead>
        <tr>
            <th colspan="7">Srpint 3</th>
            <th> Sprint 3</th>
        </tr>
    </thead>
    <tbody>
        <!--====================================================================-->
        <tr>
            <td colspan="1">User Story</td>
            <td colspan="15">Work-Item / Task</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Description</td>
            <td>Estimation (hours)</td>
            <td>Assigned To</td>
            <td>Status</td>
        </tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="3" >  TS-01  </td>
            <td rowspan="3" > Obtener Datos de los procesos de vinificación</td>
            <td> TS-01-T-01 </td>
            <td> Crear modelo de datos de vinificación </td>
            <td> Definir el modelo de datos del proceso de vinificación en la base de datos, incluyendo campos de lote, fase y fechas de cada etapa.	</td>
            <td>ESTIMACIÓN</td>
            <td>Janover Saldaña</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td> TS-01-T-02 </td>
            <td> Implementar endpoint GET para lotes </td>
            <td> Configurar el endpoint GET (/api/v1/vinificacion/lotes) para consultar información detallada de cada lote en el proceso de vinificación.	</td>
            <td>5</td>
            <td>Janover Saldaña</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td> TS-01-T-03 </td>
            <td> Implementar endpoint GET para etapas </td>
            <td> Crear endpoints GET (/api/v1/vinificacion/{lote}/etapa) para consultar el estado de cada etapa (fermentación, prensado, clarificación, etc.) de un lote.	</td>
            <td> 5 </td>
            <td> Janover Saldaña </td>
            <td> Done </td>
        </tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="2"> TS-03 </td>
            <td rowspan="2"> Eliminar Datos de los Procesos de Vinificación	</td>
            <td> TS-03-T01 </td>
            <td> Implementar endpoint DELETE para lotes	</td>
            <td> Configurar el endpoint DELETE (/api/v1/vinificacion/lotes/{id}) para eliminar un lote completo, incluyendo sus datos de cada etapa del proceso.	</td>
            <td> 5 </td>
            <td> Janover Saldaña < /td>
            <td> Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td> TS-03-T02 </td>
            <td> Desarrollar capa de servicio para eliminación	</td>
            <td> Crear la lógica de servicio para eliminar un lote y sus datos relacionados en la base de datos, asegurando integridad referencial.	</td>
            <td> 5</td>
            <td> Janover Saldaña </td>
            <td> Done </td>
        </tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="1"> TS-04 </td>
            <td rowspan="1"> Registro de Lotes en el Proceso de Vinificación </td>
            <td> TS-04-T01</td>
            <td> Implementar endpoint POST para lotes	</td>
            <td> Crear el endpoint POST (/api/v1/vinificacion/lotes) para registrar nuevos lotes, incluyendo información básica como tipo de uva y fecha de inicio.	</td>
            <td> 5 </td>
            <td> Janover Saldaña </td>
            <td> Done </td>
        </tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="1"> TS-05 </td>
            <td rowspan="1"> Registro de Etapas en el Proceso de Vinificación </td>
            <td> TS-05-T-01 </td>
            <td> Implementar endpoint POST para etapas	</td>
            <td> Crear el endpoint POST (/api/v1/vinificacion/{lote}/etapas) para registrar nuevas etapas de fermentación, prensado, clarificación, envejecimiento y embotellado.	</td>
            <td> 6 </td>
            <td> Janover Saldaña </td>
            <td> Done</td>
        </tr>
        <!--==================================USER STORY==================================-->
   <tr>
    <td rowspan="4"> TS-14 </td>
    <td rowspan="4"> Ver detalles de un ítem del inventario</td>
    <td> TS-14-T-01 </td>
    <td> Ver detalle del ítem exitosamente </td>
    <td> Implementar un endpoint y un JSON con la información del ítem cuando se proporciona un ID válido. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
    </tr>
        <!--====================================================================-->
   <tr>
    <td> TS-14-T-02 </td>
    <td> Diseño de la Estructura de la API </td>
    <td> Definir la estructura y los endpoints de la API para acceder a los detalles del ítem del inventario (/api/inventory/items/{id}). </td>
    <td> 1h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
    </tr>
        <!--====================================================================-->
 <tr>
    <td> TS-14-T-03 </td>
    <td> Manejo de Control de Errores </td>
    <td> Implementar un manejo adecuado de errores para las respuestas de la API, como el mensaje de error 404. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
        <!--====================================================================-->
<tr>
    <td> TS-14-T-04 </td>
    <td> Prueba Unitaria para la API </td>
    <td> Desarrollar pruebas unitarias que verifiquen el comportamiento correcto del endpoint para cada uno de los escenarios definidos, incluyendo: 
        - Prueba para un ID válido.
        - Prueba para un ID inexistente.
        - Prueba para solicitud sin autorización.
    </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
      <!--==================================USER STORY==================================-->
<tr>
    <td rowspan="4"> TS-16 </td>
    <td rowspan="4"> Agregar nuevo ítem al inventario</td>
    <td> TS-16-T-01 </td>
    <td> Implementar endpoint para agregar ítem </td>
    <td> Implementar un endpoint y un JSON para agregar un nuevo ítem al inventario. </td>
    <td> 1h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> TS-16-T-02 </td>
    <td> Validar datos del ítem </td>
    <td> Asegurarse de que los datos del nuevo ítem cumplan con las validaciones necesarias antes de ser agregados. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> TS-16-T-03 </td>
    <td> Manejo de errores en la API </td>
    <td> Implementar manejo de errores para situaciones como datos inválidos o problemas de conexión. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> TS-16-T-04 </td>
    <td> Pruebas unitarias para agregar ítem </td>
    <td> Desarrollar pruebas unitarias que verifiquen el correcto funcionamiento del endpoint para agregar un nuevo ítem. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done</td>
</tr>
       <!--==================================USER STORY==================================-->
<tr>
    <td rowspan="4"> US-32 </td>
    <td rowspan="4"> Filtrar insumos del inventario por categoría</td>
    <td> US-32-T-01 </td>
    <td> Implementar endpoint de filtrado </td>
    <td> Implementar un endpoint que permita filtrar insumos del inventario según la categoría seleccionada. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> US-32-T-02 </td>
    <td> Validar categorías disponibles </td>
    <td> Asegurarse de que las categorías disponibles para el filtrado sean correctas y estén actualizadas. </td>
    <td> 1h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> US-32-T-03 </td>
    <td> Manejo de errores en el filtrado </td>
    <td> Implementar manejo de errores para situaciones como categorías no encontradas o problemas en la consulta. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> US-32-T-04 </td>
    <td> Pruebas unitarias para el filtrado </td>
    <td> Desarrollar pruebas unitarias que verifiquen el correcto funcionamiento del endpoint de filtrado por categoría. </td>
    <td> 1h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
       <!--==================================USER STORY==================================-->
<tr>
    <td rowspan="4"> US-33 </td>
    <td rowspan="4"> Buscar insumos en el inventario</td>
    <td> US-33-T-01 </td>
    <td> Implementar endpoint de búsqueda </td>
    <td> Implementar un endpoint que permita buscar insumos en el inventario utilizando diferentes criterios. </td>
    <td> 1h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> US-33-T-02 </td>
    <td> Filtrar resultados por atributos </td>
    <td> Permitir a los usuarios filtrar los resultados de búsqueda por atributos específicos, como nombre, categoría y cantidad. </td>
    <td> 1h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> US-33-T-03 </td>
    <td> Manejo de errores en la búsqueda </td>
    <td> Implementar manejo de errores para situaciones como insumos no encontrados o problemas en la consulta. </td>
    <td> 2h </td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> US-33-T-04 </td>
    <td> Pruebas unitarias para la búsqueda </td>
    <td> Desarrollar pruebas unitarias que verifiquen el correcto funcionamiento del endpoint de búsqueda de insumos. </td>
    <td> 1h < td>
    <td> Luis Villegas </td>
    <td> Done </td>
</tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="3">TS-09</td>
            <td rowspan="3">Registrar un pedido</td>
            <td>TS-09-T-01</td>
            <td>Implementar endpoint de pedidos</td>
            <td>Implementar la lógica para agregar una nueva orden</td>
            <td>3h</td>
            <td>Vicente</td>
            <td>Done</td> 
        </tr>
        <!--====================================================================-->
        <tr>
            <td>TS-09-T-02</td>
            <td>Crear endpoint</td>
            <td>Crear el endpoint "/api/v1/order" en el controlador</td>
            <td>4h</td>
            <td>Vicente</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>TS-09-T-03</td>
            <td>validar endpoint</td>
            <td>Validar que el endpoint maneje correctamente las respuestas</td>
            <td>1h</td>
            <td>Vicente</td>
            <td>Done</td>
        </tr>
 <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="6"> US-16	</td>
            <td rowspan="6">Crear un cliente distribuidor</td>
            <td>US-16: TASK-01</td>
            <td>Crear formulario de cliente distribuidor	</td>
            <td>Desarrollar un formulario para registrar y gestionar los datos de clientes distribuidores, asegurando que la información necesaria esté completa y estructurada para facilitar la administración y consulta posterior.	</td>
            <td>1h</td>
            <td>Gustavo</td>
            <td>Done</td> 
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-16: TASK-02 </td>
            <td>Configurar validaciones de campos obligatorios	</td>
            <td>Configura los campos esenciales como obligatorios para asegurar que se complete toda la información necesaria antes de enviar el formulario.	</td>
            <td>2h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-16: TASK-03</td>
            <td>Desarrollar método de creación en ClientsService	</td>
            <td>Crear un método en ClientsService que permita enviar los datos de un cliente nuevo a la API, realizando una solicitud POST para registrar la información en el servidor.	</td>
            <td>2h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-16: TASK-04</td>
            <td>Conectar el formulario con el método de creación del servicio	</td>
            <td>Implementar la conexión entre el formulario de cliente distribuidor y el método que permite registrar un nuevo cliente. Esto incluye obtener los datos del formulario al enviarlo y gestionar la respuesta para confirmar la creación exitosa y manejar posibles errores.</td>
            <td>2h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-16: TASK-05</td>
            <td>Mostrar notificación de éxito	</td>
            <td>Implementar una notificación que informe al usuario sobre el registro exitoso del cliente, asegurando que sea clara y se cierre automáticamente después de unos segundos..</td>
            <td>1h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
<!--====================================================================-->
        <tr>
            <td>US-16: TASK-06</td>
            <td>Redirigir a la lista de clientes distribuidores	</td>
            <td> Redirigir al usuario a la lista de clientes distribuidores tras un registro exitoso, asegurando que la navegación sea intuitiva y rápida.</td>
            <td>1h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
 <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="6"> US-17	</td>
            <td rowspan="6">Editar un cliente distribuidor</td>
            <td>US-17: TASK-01</td>
            <td>Crear componente de edición	</td>
            <td>Desarrollar ClientEditComponent.vue para editar los datos de un cliente, cargando la información actual y permitiendo su actualización a través de un formulario.	</td>
            <td>3h</td>
            <td>Gustavo</td>
            <td>Done</td> 
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-17: TASK-02</td>
            <td>Implementar método de actualización en ClientsService	</td>
            <td>Desarrollar un método en ClientsService que permita actualizar los datos de un cliente existente mediante una solicitud PUT a la API.	</td>
            <td>2h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-17: TASK-03</td>
            <td>Configurar validaciones de datos	</td>
            <td>Implementar las validaciones necesarias en el formulario de edición para asegurar que todos los campos requeridos sean completados correctamente antes de permitir la actualización de los datos del cliente.	</td>
            <td>1h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
 <!--====================================================================-->
        <tr>
            <td>US-17: TASK-04</td>
            <td>Conectar el formulario de edición con el servicio de actualización	</td>
            <td> Integrar el formulario de edición con el método de actualización del servicio, asegurando que los datos ingresados se envíen correctamente para actualizar la información del cliente en la API.	</td>
            <td>1h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
 <!--====================================================================-->
        <tr>
            <td>US-17: TASK-05</td>
            <td> Mostrar notificación de éxito de edición	</td>
            <td>Implementar una notificación que informe al usuario sobre la edición exitosa de los datos del cliente, asegurando que sea clara y visible, y que se cierre automáticamente después de unos segundos.	</td>
            <td>2h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
<!--====================================================================-->
        <tr>
            <td>US-17: TASK-06</td>
            <td> Actualizar vista de detalles	</td>
            <td>Actualizar la vista de detalles del cliente para mostrar la información más reciente después de la edición..	</td>
            <td>1h</td>
            <td>Gustavo</td>
            <td>Done</td>
        </tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="3"> TS-21 </td>
            <td rowspan="3"> Creación de pedidos de vinos </td>
            <td> TS-21-T-01 </td>
            <td> Implementar formulario de creación de pedidos </td>
            <td> Desarrollar el formulario de pedidos que permita seleccionar el tipo de producto y la cantidad deseada. </td>
            <td> 3h </td>
            <td> OscarArmas </td>
            <td> Done </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td> TS-21-T-02 </td>
            <td> Configurar endpoint para la creación de pedidos </td>
            <td> Configurar el endpoint POST (/api/v1/pedidos) para procesar la creación de nuevos pedidos de vino. </td>
            <td> 3h </td>
            <td> OscarArmas </td>
            <td> Done </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td> TS-21-T-03 </td>
            <td> Validar los datos del pedido </td>
            <td> Implementar validaciones en el formulario de pedidos para asegurar que los datos sean correctos y completos antes de procesarlos. </td>
            <td> 3h </td>
            <td> OscarArmas </td>
            <td> Done </td>
        </tr>
        <!--==================================USER STORY==================================-->
        <tr>
            <td rowspan="3"> US-34	</td>
            <td rowspan="3">Obtener detalles de un pedido</td>
            <td>US-34: TASK-01</td>
            <td>Order details	</td>
            <td>Desarrollo del componente visual order-details	</td>
            <td>4h</td>
            <td>Vicente</td>
            <td>Done</td> 
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-34: TASK-02</td>
            <td>Añadir campos en entity	</td>
            <td>Añadir los campos necesarios en el entity model para que maneje todos los detalles necesarios del pedido	</td>
            <td>2h</td>
            <td>Vicente</td>
            <td>Done</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>US-34: TASK-03</td>
            <td>Validar que el service funcione</td>
            <td>Validar que el service retorne todos los datos del order-details</td>
            <td>1h</td>
            <td>Vicente</td>
            <td>Done</td>
        </tr>
        <!--==================================USER STORY==================================-->
<tr>
    <td rowspan="4"> TS-19 </td>
    <td rowspan="4"> Despliegue del Servicio Web </td>
    <td> TS-19-TASK-01 </td>
    <td> Activar Modo Producción y Configurar Swagger </td>
    <td> Configurar el proyecto para funcionar en modo producción y habilitar Swagger para acceso en producción. </td>
    <td> 2h </td>
    <td> Gustavo </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td> TS-19-TASK-02 </td>
    <td> Configurar y Activar WebDeploy en el Hosting </td>
    <td> Activar la cuenta de WebDeploy en el panel de control de MonsterASP y preparar el perfil de publicación. </td>
    <td> 2h </td>
    <td> Gustavo </td>
    <td> Done </td>
</tr>
<!--====================================================================-->
<tr>
    <td>TS-19-TASK-03</td>
    <td>Desplegar el Proyecto en el Servidor</td>
    <td>Publicar el proyecto en el servidor utilizando el perfil de publicación de WebDeploy.</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--====================================================================-->
<tr>
    <td>TS-19-TASK-04</td>
    <td>Verificar el Funcionamiento de la API y Swagger</td>
    <td>Comprobar que la API y la interfaz de Swagger están accesibles y funcionando correctamente en el entorno de producción.</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>

<!--================================== USER STORY TS-05 ==================================-->
<tr>
    <td rowspan="3">TS-05</td>
    <td rowspan="3">Crear un cliente distribuidor</td>
    <td>TS-05: TASK-01</td>
    <td>Implementar lógica de cliente</td>
    <td>Implementar la lógica para agregar un nuevo cliente distribuidor</td>
    <td>3h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-05: TASK-02</td>
    <td>Crear endpoint</td>
    <td>Crear el endpoint "/api/v1/clients" en el controlador</td>
    <td>2h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-05: TASK-03</td>
    <td>Validar respuestas del endpoint</td>
    <td>Validar que el endpoint maneje correctamente las respuestas</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>

<!--================================== USER STORY TS-08 ==================================-->
<tr>
    <td rowspan="3">TS-08</td>
    <td rowspan="3">Ver los detalles de un cliente distribuidor</td>
    <td>TS-08: TASK-01</td>
    <td>Implementar lógica de detalles de cliente</td>
    <td>Implementar la lógica para obtener los detalles de un cliente distribuidor</td>
    <td>3h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-08: TASK-02</td>
    <td>Crear endpoint de detalles</td>
    <td>Crear el endpoint "/api/v1/clients/{id}" en el controlador</td>
    <td>2h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-08: TASK-03</td>
    <td>Validar respuestas de detalles</td>
    <td>Validar que el endpoint maneje correctamente las respuestas</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<!--================================== USER STORY TS-18 ==================================-->
<tr>
    <td rowspan="3">TS-18</td>
    <td rowspan="3">Eliminar un cliente distribuidor</td>
    <td>TS-18: TASK-01</td>
    <td>Agregar botón de eliminación</td>
    <td>Agregar un botón en la lista de clientes para permitir la eliminación de un cliente distribuidor</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-18: TASK-02</td>
    <td>Desarrollar método de eliminación</td>
    <td>Desarrollar el método de eliminación en el servicio ClientsService para manejar la eliminación de clientes</td>
    <td>2h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>
<tr>
    <td>TS-18: TASK-03</td>
    <td>Implementar diálogo de confirmación</td>
    <td>Implementar un diálogo de confirmación que solicite al usuario la verificación antes de eliminar el cliente</td>
    <td>1h</td>
    <td>Gustavo</td>
    <td>Done</td>
</tr>


</table>








### 5.2.2. Implemented Landing Page Evidence


### 5.2.1. Sprint 1

En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo gestionamos las tareas en Pivotal Tracker.

Repositorio: [https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page](https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page)

Landing Page Deployed:



### 5.2.1. Sprint 1

En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del
diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica
que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials
o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo
gestionamos las tareas en Jira Software.

#### 5.2.1.1. Sprint Planning 1.

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--FILA 1-->
        <tr>
            <td>Date</td>
            <td>21-08-2024</td>
        </tr>
        <!--FILA 2-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--FILA 3-->
        <tr>
            <td>Location</td>
            <td>Discord</td>
        </tr>
         <!--FILA 4-->
        <tr>
            <td>Prepared By</td>
            <td>Janover Saldaña</td>
        </tr>
         <!--FILA 5-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Jhordi Carranza - Oscar Armas - Luis Villegas - Juan Llamccaya </td>
        </tr>
        <!--FILA 6-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--FILA 7-->
        <tr>
            <td>Sprint 1 Goal</td>
            <td> 
              Nuestro enfoque está en implementar la landing page de ElixirControl, incluyendo todas las 
              secciones acordadas y el requisito de cambio de idioma para la aplicación. Creemos que esto
              mejora la accesibilidad y la experiencia del usuario, permitiendo que más vinicultores y 
              distribuidores se conecten con la plataforma. Esto se confirmará cuando la landing page 
              esté completa, funcional y los usuarios puedan navegar por las secciones en su idioma 
              preferido, reportando satisfacción con la interfaz y la usabilidad.
            </td>
        </tr>
        <!--FILA 8-->
        <tr>
            <td>Sprint 1 Velocity</td>
            <td> 20 </td>
        </tr>
        <!--FILA 9-->
        <tr>
            <td>Sum of Story Points</td>
            <td> 20 </td>
        </tr>
    </tbody>
</table>

##### 5.2.1.3. Development Evidence for Sprint Review.


<table>
    <thead>
        <tr>
            <th rowspan="" >Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
        <!--FILA 1 -->
        <tr>
            <td rowspan="14">https://github.com/SV51-MetaSoft-App-Web/ElixirControl-Landing-Page</td>
            <td>main</td>
            <td>ca7aff9e22b71a4a96e8d823c0e61c347240df9c</td>
            <td>Initial commit</td>
            <td></td>
            <td>13/08/2024</td>
        </tr>
        <!--FILA 2 -->
        <tr>
            <td>develop</td>
            <td>23d5ab43ce3f6f11fe2a2fd4f9b81111ca927cd3</td>
            <td>feat: Added the base structure of the project.</td>
            <td></td>
            <td>21/08/2024</td>
        </tr>
        <!--FILA 3 -->
        <tr>
            <td>feature/nav</td>
            <td>c6a3d0698ef363310ca9a3c96d9d1ae658118f5b</td>
            <td>feat: Added header and navigation section.</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 4 -->
        <tr>
            <td>feature/hero</td>
            <td>456e8089d0e5e7805a2819885be2972e3d221aef</td>
            <td>feat(hero): Added hero section.</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 5 -->
        <tr>
            <td>feature/services</td>
            <td>c3e661b693063ca547c171ba3db89fd194255fc1</td>
            <td>feat(services): Added services section</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 6 -->
        <tr>
            <td>feature/services</td>
            <td>1462bee8ba47ca2f878468b262302d7586e0633e</td>
            <td>feat(services): Updated the styles of the services section.</td>
            <td></td>
            <td>5/09/2024</td>
        </tr>
        <!--FILA 7 -->
        <tr>
            <td>feature/testimonials</td>
            <td>79ef0471340e7e312c05d0e1c854cd7f0e562b19</td>
            <td>feat(testimonials): Added Testimonials section.</td>
            <td></td>
            <td>06/09/2024</td>
        </tr>
        <!--FILA 8 -->
        <tr>
            <td>feature/plans</td>
            <td>d706c364023e2d4addf47df3aa8cf0e8dcf937ed</td>
            <td>feat(plans): Added structure of plans in Spanish</td>
            <td></td>
            <td>7/09/2024</td>
        </tr>
        <!--FILA 9 -->
        <tr>
            <td>feature/plans</td>
            <td>2d7b2b5497c5ad9d77740d17b66fcca4fd529842</td>
            <td>feat(plans): Added structure of plans in English</td>
            <td></td>
            <td>7/09/2024</td>
        </tr>
        <!--FILA 10 -->
        <tr>
            <td>feature/plans</td>
            <td>98620905ab1a4b86b797b55133f26e0ecc69dd28</td>
            <td>feat(plans): Added styles for the plans section.</td>
            <td></td>
            <td>7/09/2024</td>
        </tr>
        <!--FILA 11 -->
        <tr>
            <td>feature/about-the-team</td>
            <td>775e984a0b45a388f19cfcea2a4cbf42e82f29ba</td> 
            <td>feat(about-the-team): Added content and styles to the About Team section</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
        <tr>
            <td>feature/about-the-team</td>
            <td>9b3fe2fe56a55c7ecd7e88eea28a0e5c83d7ee29</td> 
            <td>feat(about-the-team): Added content and styles to the About Team section</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
        <tr>
            <td>feature/footer</td>
            <td>636f5902fdec78f18206aa842c9ed10eb591ac05</td> 
            <td>feat(footer): Added content and styles to the footer section.</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
        <tr>
            <td>feature/about-the-app</td>
            <td>f5ddbc9174940b126b2dbfb87c58a8ded713beb7</td> 
            <td>feat(about-the-app): Added content and styles in about the app section.</td> 
            <td></td>
            <td>7/09/2024</td>   
        </tr> 
    </tbody>
</table>


##### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Para este primer sprint no se realizaron testing.

##### 5.2.1.5. Execution Evidence for Sprint Review.

Después de completar el Sprint 1, logramos implementar todas las secciones de nuestra Landing Page para garantizar una visualización perfecta. Además, le dimos un formato atractivo que captura la atención del usuario hacia sus diferentes componentes. También agregamos métodos de navegación en la página, como botones ubicados al principio, que te permiten moverte fácilmente de una sección a otra. A continuación, te mostraremos los avances a través de imágenes del resultado obtenido.

Es importante destacar que el objetivo principal de la Landing Page es convertir a los visitantes en futuros clientes o usuarios habituales de nuestro servicio. Para lograrlo, utilizamos llamados a la acción (Call To Action) que los guían hacia la aplicación web.

A continuación, te presentamos capturas de pantalla del desarrollo de la Landing Page:


**Encabezado y botones de desplazamiento:**

En la parte superior, se encuentra el encabezado (Header) que incluye botones de inicio (Home), beneficios (benefits), Pricing (Pricing), sobre la aplicación (about), testimonios de usuarios (testimonials), un formulario para que nos contacten (Contact), un apartado para saber sobre el equipo (About us) y un botón para cambiar el idioma entre inglés y español. Estos elementos permiten a los visitantes desplazarse fácilmente a la sección que deseen visualizar.

Imagen 01: Encabezado y botones de desplazamiento

![header-landing-page.png](../assets/img/chapter-V/sprint-1/header-landing-page.png)

**Sección Hero:**

Se presenta la sección "Hero", que incluye una breve descripción y una frase representativa de ElixirControl. Además, permite iniciar el uso del servicio web y proporciona una imagen relacionada con el mismo.

Imagen 02: Sección Hero

![hero-landing-page.png](../assets/img/chapter-V/sprint-1/hero-landing-page.png)


**Sección Services:**

Se presenta la sección de servicio que ofrecemos para nuestros segmentos objetivos. En esta sección, se describen los beneficios y características de ElixirControl, lo que permite a los visitantes conocer más sobre el servicio.

Imagen 03: Sección Services
![services-landing-page.png](../assets/img/chapter-V/sprint-1/services-landing-page.png)


**Sección Pricing:**

En la sección de precios, se detallan los planes y precios de ElixirControl. Esta información es esencial para que los visitantes conozcan las opciones disponibles y puedan elegir la que mejor se adapte a sus necesidades.

Imagen 04: Sección Pricing
![plans-landing-page.png](../assets/img/chapter-V/sprint-1/plans-landing-page.png)


**Sección About the App:**

En esta sección, se presenta información detallada sobre la aplicación ElixirControl, sus características y funcionalidades. Esto permite a los visitantes conocer más sobre la aplicación y cómo puede ayudarles en su día a día.

Imagen 05: Sección About the App

![about-the-app-landing-page.png](../assets/img/chapter-V/sprint-1/about-the-app-landing-page.png)


**Sección Testimonials:**

En la sección de testimonios, se presentan opiniones y comentarios de usuarios reales que han utilizado ElixirControl. Esto ayuda a generar confianza en los visitantes y a mostrarles la experiencia positiva de otros usuarios.

Imagen 06: Sección Testimonials

![testimonials-landing-page.png](../assets/img/chapter-V/sprint-1/testimonials-landing-page.png)

**Sección About the Team:**

En la sección "About the Team", se presenta información sobre el equipo de desarrollo de ElixirControl. Esto permite a los visitantes conocer a las personas detrás del servicio y generar confianza en la calidad y profesionalismo del equipo.

![about-the-team-landing-page.png](../assets/img/chapter-V/sprint-1/about-the-team-landing-page.png)

**Sección Contact:**

En la sección de contacto, se presenta un formulario que permite a los visitantes enviar consultas, comentarios o solicitudes de información sobre ElixirControl. Esto facilita la comunicación con los usuarios y permite responder a sus necesidades de manera eficiente.

![contact-landing-page.png](../assets/img/chapter-V/sprint-1/contact-landing-page.png)

**Footer:**

En el pie de página (Footer), se incluyen enlaces a las redes sociales de ElixirControl, información de contacto y un botón para volver al inicio de la página. Esto permite a los visitantes acceder a más información y mantenerse conectados con el servicio.

![footer-landing-page.png](../assets/img/chapter-V/sprint-1/footer-landing-page.png)


##### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En el primer Sprint el equipo de desarrollo de MetaSoft ha diseñado, programado y puesto en funcionamiento el sitio web (Landing Page) Para presentar la aplicación Web propuesta denominada "ElixirControl". En este sitio web (Landing Page), se lográ visualizar varias secciones que ilustran en que consiste "ElixirControl", cada integrante del equipo de desarrollo de Metasoft estuvo a cargo de una sección en especifico.

<table>
  <thead>
    <tr>
      <th>End Point</th>
      <th> Funciones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/</td>
        <td>Mostrar la Landing Page Desplegada</td>
    </tr>
  </tbody>
</table>


##### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la implementación de nuestro sitio web, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "realease-V1.0" que previamente se encontrba en la rama release-1.0.

[Landing Page ElexirControl](https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/) - https://sv51-metasoft-app-web.github.io/ElixirControl-Landing-Page/







### 5.2.3. Implemented Frontend-Web Application Evidence

#### 5.2.2. Sprint 2
En esta etapa de nuestro proyecto, nos hemos enfocado en implementar la funcionalidad de gestión y trazabilidad del proceso de vinificación dentro de nuestra aplicación ElixirControl, utilizando Vite y Vue en WebStorm como herramientas de desarrollo. Al finalizar este Sprint, se espera que todas las funcionalidades relacionadas, incluyendo la creación, edición y visualización de pedidos, estén completamente operativas. A continuación, se incluyen imágenes que muestran cómo gestionamos las tareas en nuestro tablero de Jira Software, reflejando el progreso y la asignación de responsabilidades del equipo.

##### 5.2.2.1. Sprint Planning 2

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 3</th>
        </tr>
    </thead>
    <tbody>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Date</td>
            <td>14-09-2024</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Location</td>
            <td>Modalidad Remota a través de la plataforma Discord</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Prepared By</td>
            <td>Janover Saldaña</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Oscar Armas - Luis Villegas - Gustavo Huanca - Vicente Quijandria</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 1 Review Summary</td>
            <td> 
              En este sprint, el equipo completó con éxito la implementación de la landing page de 
              ElixirControl, incluyendo todas las secciones acordadas y la funcionalidad de cambio de idioma. 
              Esto mejora la accesibilidad y la experiencia del usuario, permitiendo una navegación 
              intuitiva en su idioma preferido. Recibimos comentarios positivos sobre la usabilidad 
              y estética de la página, lo que valida el impacto positivo de nuestro trabajo. No 
              obstante, identificamos oportunidades de mejora en la optimización de elementos 
              visuales y en la precisión de las traducciones. Con estos logros y aprendizajes, nos 
              preparamos para seguir aportando valor a nuestros vinicultores y distribuidores en el 
              próximo sprint.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 1 Retrospective Summary</td>
            <td>
              En este sprint, el equipo enfrentó desafíos en la comunicación y la gestión de tareas, 
              lo que impactó la colaboración y el flujo de trabajo. A pesar de estas dificultades,
              logramos completar la landing page de ElixirControl y la funcionalidad de cambio de 
              idioma, demostrando nuestra capacidad de adaptación. Los miembros del equipo resaltaron 
              la necesidad de mejorar la coordinación y clarificar roles para optimizar el uso del 
              tiempo y recursos. A pesar de los obstáculos, mantuvimos un fuerte compromiso con el 
              proyecto. De cara al próximo sprint, es crucial aplicar las lecciones aprendidas para 
              fortalecer nuestra dinámica de trabajo y asegurar que todos estén alineados en 
              nuestros objetivos.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Goal</td>
            <td> 
              Nuestro enfoque está en implementar la interfaz de usuario para la gestión de procesos 
              vitivinícolas, incluyendo la visualización y envío de solicitudes de pedidos a 
              vinicultores, la creación y visualización de procesos de vinificación, la gestión
              de datos de inventario del vinicultor y la administración de información de clientes. 
              Creemos que esto proporcionará una experiencia de usuario más ágil y efectiva para 
              vinicultores y distribuidores. Esto se confirmará cuando todas las funcionalidades 
              del frontend sean probadas con éxito, se utilicen activamente en la aplicación y los 
              usuarios reporten una mejora en la eficiencia de sus flujos de trabajo y satisfacción 
              con las nuevas características visuales implementadas.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Velocity</td>
            <td> Por definir </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sum of Story Points</td>
            <td> Por Definir </td>
        </tr>
        <!--====================================================================-->
    </tbody>
</table>




##### 5.2.2.3. Development Evidence for Sprint Review
<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
    <td>https://github.com/SV51-MetaSoft-App-Web/ElixirControl-FrontEnd.git</td>
    <td>Master</td>
    <td>7f851107203c3991fc1fe0d251782570f03545a8</td>
    <td>Chore: initial commit</td>
    <td></td>
    <td>Sep 19, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>7568ba72396e0ef2642a8a2b80ac0d550e955b0f</td>
    <td>Chore: clean up project</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>410beb3309b6bfc3b2ee7fd19e2f25a9d244277f</td>
    <td>Chore: added initial project configuration</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Develop</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/customer-management</td>
    <td>29c992c042ea81ee18785d764f06877138612f83</td>
    <td>Chore: create db.json</td>
    <td></td>
    <td>Sep 27, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/distributor-profile</td>
    <td>e8e82c48b77706b8ee8f20412a76f0c67e73bbbc</td>
    <td>Feat(distrubutor-profile): added db.json file to simulate the API</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>56974485b42a727becd17f1e65558c9af334fb5c</td>
    <td>feat(distributor-profile): update App.vue component to improve the design</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>33399c36ae71240f7ee69a2a28992da55e6f71da</td>
    <td>feat(distributor-profile): entities and services corresponding to the distributor profile order history section have been added</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>c12ef7575564e2680bb1e6098c8891d7d04bf7b3</td>
    <td>feat(distributor-profile): delete other entities and services dont corresponding to the distributor profile order history section have been added</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/inventory-management</td>
    <td>c6cdbc0dfea0c84aaf59ea49f1b86708a014c675</td>
    <td>feat(inventory-management): added db.json file to simulate the API</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>1d11d40e488cca8c5007bb53316a726c55a6c45c</td>
    <td>feat(inventory-management): update App.vue component to improve the design</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>e4b658a0d4ab734cd8c1ee4f596bc6f6843b33bc</td>
    <td>feat(inventory-management): entities and services corresponding to the inventory management have been added.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/producer-management</td>
    <td>f82742e28e0414009dfd0854e36faf0bd194bf94</td>
    <td>feat(winemaking-process): Entities and services corresponding to the winemaking process have been added.</td>
    <td></td>
    <td>Sep 23, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/winemaking-process</td>
    <td>d4bc3b86517a15e6032fe4827abdfca3e9adf1c2</td>
    <td>feat(winemaking-process): Added components for creating and editing objects.</td>
    <td></td>
    <td>Sep 24, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>45437600b7b04a168285c4af5fb6582a0e216412</td>
    <td>feat(winemaking-process): Added CRUD to the table with batch information.</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>113c3afe8a4bb5c43bb85421daa11adcca12a755</td>
    <td>feat(winemaking-process): Added CRUD to the table with fermentation information.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>0d5411dfec6057d3c2dbf1fa2e4b88387a915526</td>
    <td>feat(winemaking-process): Added CRUD to the table with aging information.</td>
    <td></td>
    <td>Sep 26, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>208f92424d3a0901c97c3e5d1c81cd882fcb2d2d</td>
    <td>feat(winemaking-process): Added CRUD to the table with bottling information.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>51082f2a5ac747e5179a278b4488d1c8b5e3530b</td>
    <td>feat(winemaking-process): Added CRUD to the table with clarification and pressing information.</td>
    <td></td>
    <td>Sep 27, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>49f65887335478860a0ac6c0d86a345ecc764f0d</td>
    <td>feat(winemaking-process): Added web app navigation bar.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>Feature/security</td>
    <td>70e035609157b60943f11454652b905b90d8492d</td>
    <td>feat(security): added "en.json" and "es.json" files.</td>
    <td></td>
    <td>Sep 25, 2024</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>aec471b4dae50e2e04b12112153338e826fc6f7c</td>
    <td>feat(security): added content of "index.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>0df6f357e4aee9314c137a477ea3e8bd8c8c1088</td>
    <td>feat(security): added pages in "views" section.</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>c517242c4af0a179ef98eae9f9f8cc3679643bd9</td>
    <td>feat(security): added content of "App.vue" and "main.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>cb0a0b2c9e4095d8d52cabb7915c047a5744c78f</td>
    <td>feat(security): added content of "i18n.js" and "style.css".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>6810bd939a24f60aabba0049ea5e1642a265c5e9</td>
    <td>feat(security): added content of "vite.config.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>dec1b180326dec39db5801f8af263227a3ba8059</td>
    <td>feat(security): updated "style.css" and "vite.config.js".</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>bd4043a36ffd972f4496196bb32bcb4b6b99fb46</td>
    <td>feat(security): added the component "Header.vue".</td>
    <td></td>
    <td></td>
  </tr>
</table>


##### 5.2.2.4. Testing Suite Evidence for Sprint Review

##### 5.2.2.5. Execution Evidence for Sprint Review
En este Sprint, nos hemos enfocado en el desarrollo y la implementación de la interfaz de gestión de pedidos, un componente esencial para mejorar la experiencia del usuario en nuestra aplicación. A través de un diseño intuitivo y funcional, buscamos facilitar la creación, edición y visualización de pedidos, permitiendo a los usuarios gestionar sus transacciones de manera eficiente y efectiva. Durante este período, hemos trabajado en varias vistas clave que contribuyen a esta funcionalidad. A continuación, se presentan las capturas de pantalla que ilustran las diferentes etapas del proceso de gestión de pedidos, destacando las características y mejoras implementadas. A continuación, te presentamos capturas de pantalla del desarrollo del front-end:

![img.png](../assets/img/chapter-V/sprint-2/front1.png)

![img.png](../assets/img/chapter-V/sprint-2/front2.png)

![img.png](../assets/img/chapter-V/sprint-2/front3.png)

![img.png](../assets/img/chapter-V/sprint-2/front4.png)

![img.png](../assets/img/chapter-V/sprint-2/front5.png)


##### 5.2.2.6. Services Documentation Evidence for Sprint Review
Durante este Sprint, se ha llevado a cabo la documentación de los endpoints necesarios para la gestión de pedidos, utilizando OpenAPI como herramienta de referencia. Este proceso es fundamental para asegurar que todos los miembros del equipo, así como los desarrolladores futuros, tengan acceso a información clara y detallada sobre cómo interactuar con la API. La tabla a continuación detalla los endpoints documentados, proporcionando una visión clara de las acciones disponibles, los métodos HTTP asociados, y ejemplos de respuestas esperadas. Esta documentación no solo facilita el trabajo del equipo de desarrollo, sino que también mejora la comunicación entre los diferentes actores del proyecto.

| Endpoint | Acción | Verbo HTTP | Descripción | Ejemplo de Response |
|----------|--------|------------|-------------|---------------------|
| /api/pedidos | Crear Pedido | POST | Crea un nuevo pedido | { "id": 1, "status": "creado" } |
| /api/pedidos/{id} | Editar Pedido | PUT | Actualiza un pedido existente | { "id": 1, "status": "actualizado" } |
| /api/pedidos | Listar Pedidos | GET | Retorna la lista de pedidos | [{ "id": 1, "status": "creado" }, { "id": 2, "status": "enviado" }] |

La correcta implementación de estos endpoints en la aplicación, desarrollada con Vite y Vue en WebStorm, garantiza que los usuarios puedan gestionar sus pedidos de manera eficiente. Este enfoque no solo optimiza el flujo de trabajo, sino que también asegura que la experiencia del usuario sea fluida y satisfactoria. Además, la estandarización de la documentación mediante OpenAPI promueve una mejor colaboración entre equipos y una integración más sencilla con otros servicios en el futuro.

##### 5.2.2.7. Software Deployment Evidence for Sprint Review
Durante este Sprint, se llevó a cabo el proceso de despliegue de la aplicación utilizando Vite y Vue en WebStorm. La implementación se realizó en un entorno de producción, garantizando que todas las características desarrolladas fueran accesibles para los usuarios finales. El despliegue se realizó siguiendo una serie de pasos estructurados que incluyeron la preparación del entorno, la construcción del proyecto y la configuración del servidor. A continuación, se describen las etapas clave del proceso:
1. **Preparación del Entorno:** Se verificó que el entorno de producción estuviera configurado adecuadamente. Esto incluyó la instalación de las dependencias necesarias y la configuración de variables de entorno para asegurar que la aplicación funcionara correctamente en producción.
2. **Construcción del Proyecto:** Utilizando Vite, se ejecutó el comando de construcción, lo que permitió generar los archivos optimizados para producción. Este proceso optimiza el tamaño de los archivos y mejora el rendimiento de la aplicación.
3. **Configuración del Servidor:** Una vez construidos los archivos, se configuró el servidor para servir la aplicación. Esto incluyó la configuración de redirecciones adecuadas y la optimización de la entrega de contenido estático, asegurando que la aplicación se cargara rápidamente para los usuarios.
4. **Despliegue en Producción:** Finalmente, se subieron los archivos generados al repositorio de GitHub del grupo de trabajo. Como cada integrante trabajó en una rama diferente, se hizo “merge” para garantizar la recopilación general del proyecto.




### 5.2.4. Acuerdo de Servicio SaaS

#### EventWine - Acuerdo de Servicio de Software como Servicio (SaaS)

Este Acuerdo de Servicio regula el acceso y uso de la plataforma EventWine ("el Servicio"), desarrollada por el equipo MetaSoft, por parte de los usuarios ("Usuarios"). Al utilizar EventWine, los Usuarios aceptan las condiciones establecidas en este Acuerdo.

#### 1. Definiciones
- **EventWine**: Plataforma SaaS que permite gestionar procesos de producción vinícola, incluyendo la gestión de inventarios, lotes de producción, clientes y pedidos.
- **Usuario**: Persona natural o jurídica que accede y utiliza el Servicio ofrecido por EventWine.
- **Servicio**: Todos los servicios, funcionalidades y APIs expuestos a través de la plataforma EventWine.

#### 2. Derechos de Uso
EventWine concede al Usuario una licencia limitada, no exclusiva, intransferible para utilizar el Servicio, únicamente para fines de gestión de producción y operaciones vinícolas.

#### 3. Restricciones
El Usuario se compromete a:
- No copiar, modificar, descompilar o distribuir el contenido o código fuente de EventWine.
- No utilizar el Servicio para actividades ilícitas o que contravengan las normativas aplicables.
- No intentar acceder a funcionalidades no autorizadas o vulnerar la seguridad del Servicio.

#### 4. Responsabilidad del Proveedor
El equipo MetaSoft se compromete a realizar esfuerzos razonables para mantener la disponibilidad y funcionamiento del Servicio, incluyendo el acceso a la Landing Page, Aplicación Web, y servicios desplegados en MonsterASP.net y AWS LightSail.

#### 5. Limitaciones de Responsabilidad
EventWine no será responsable de interrupciones, pérdidas de datos o daños indirectos derivados de:
- Fallos de infraestructura de terceros (como MonsterASP.net o AWS).
- Uso indebido del Servicio por parte del Usuario.
- Incidentes fuera del control razonable del equipo MetaSoft.

#### 6. Modificaciones al Servicio
El equipo MetaSoft se reserva el derecho de realizar actualizaciones, modificaciones o mejoras en el Servicio. Se procurará notificar oportunamente a los Usuarios sobre cambios relevantes.

#### 7. Terminación
El acceso al Servicio podrá ser suspendido o terminado si el Usuario incumple las disposiciones de este Acuerdo o hace un uso indebido del Servicio.

#### 8. Ley Aplicable
Este Acuerdo se rige por las leyes de la República del Perú. Cualquier disputa relacionada con este Acuerdo se resolverá ante los tribunales competentes de Lima, Perú.

#### 9. Aceptación de Términos
Al utilizar EventWine, el Usuario acepta expresamente todos los términos y condiciones establecidos en el presente Acuerdo.

#### 10. Contacto
Para consultas relacionadas con este Acuerdo o con el uso del Servicio, los Usuarios pueden comunicarse a través del formulario de contacto disponible en la Landing Page de EventWine.

---






### 5.2.5. Implemented Native-Mobile Application Evidence



### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

#### 5.2.3.1.Spring Planning 3.



<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 3</th>
        </tr>
    </thead>
    <tbody>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Planning Background </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Date</td>
            <td>19-10-2024</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Time</td>
            <td> 10:00 p.m </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Location</td>
            <td>Modalidad Remota a través de la plataforma Discord</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Prepared By</td>
            <td>Janover Saldaña</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Attendees (to planning meeting)</td>
            <td>Oscar Armas - Luis Villegas - Gustavo Huanca - Vicente Quijandria</td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Review Summary</td>
            <td> 
              Durante el Sprint #2, el equipo logró avances en la implementación de la gestión de 
              inventarios, gestión de productos terminados, gestión del proceso de vinificación por lotes 
              de cosecha de uvas, gestión de cartera de clientes de los vinicultores y el historial de 
              solicitudes de compra a vinicultores por parte de los distribuidores
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 2 Retrospective Summary</td>
            <td>
              Durante este sprint, el equipo enfrentó algunos desafíos significativos, especialmente con el 
              retiro de dos integrantes que no mostraron el compromiso esperado y tenían limitaciones en sus
              conocimientos sobre el desarrollo del frontend. Esto afectó la comunicación y la gestión de 
              tareas, generando dificultades en el flujo de trabajo. A pesar de estos obstáculos, logramos 
              cumplir con los objetivos establecidos, gracias al compromiso y la colaboración de los demás
              miembros. A través de la resiliencia y el apoyo mutuo, completamos las entregas, demostrando
              que, incluso en situaciones adversas, el trabajo en equipo es fundamental. Identificamos 
              varias oportunidades para mejorar la claridad en los roles y fortalecer el seguimiento de 
              tareas, lo que nos ayudará a optimizar nuestra dinámica en futuros sprints. Nuestro desempeño
              refleja un camino claro hacia el cumplimiento de los objetivos del próximo sprint, 
              asegurando una mejor eficiencia en el uso de recursos y tiempo.
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td colspan="2"> <p1 style="text-align: center;"> Sprint Goal & User Stories </p1></td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 3 Goal</td>
            <td> 
              Nuestro enfoque está en implementar endpoints para la gestión de procesos vitivinícolas, 
              incluyendo solicitudes de pedidos a vinicultores, creación y obtención de procesos de 
              vinificación, datos de inventario del vinicultor y gestión de datos de clientes. Creemos 
              que esto proporciona operaciones más ágiles y una mejor experiencia de usuario a los 
              vinicultores y distribuidores. Esto se confirmará cuando todos los endpoints sean probados
              con éxito y se utilicen activamente en la aplicación, y cuando los usuarios informen sobre 
              una mejora en la eficiencia de sus flujos de trabajo y satisfacción con las nuevas 
              características visuales del frontend. 
            </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sprint 3 Velocity</td>
            <td> Por definir </td>
        </tr>
        <!--====================================================================-->
        <tr>
            <td>Sum of Story Points</td>
            <td> Por Definir </td>
        </tr>
        <!--====================================================================-->
    </tbody>
</table>




#### 5.2.3.3.Development Evidence for Sprint Review.


<table>
    <thead>
        <tr>
            <th rowspan="" >Repository</th>
            <th>Branch</th>
            <th>Commit Id</th>
            <th>Commit Message</th>
            <th>Commit Message Body</th>
            <th>Commited on (Date)</th>
        </tr>
    </thead>
    <tbody>
    <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="10">ElixirControl-Landing-Page</td>
            <td>main</td>
            <td>d3ec381</td>
            <td>chore(call-to-actin): Added the web application route in the call to action</td>
            <td>Added the web application route in the call to action</td>
            <td>Commited on 28/09/2024</td>
        </tr>
        <tr>
            <td>main</td>
            <td>d54a8d8</td>
            <td>feat: Updated the styles and html of the About The App section.</td>
            <td>Updated the styles and html of the About The App section.</td>
            <td>Commited on 02/11/2024</td>
        </tr>
    </tbody>
    <tbody>
    <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="21">ElixirControl-FrontEnd</td>
            <td>feature/winemaking-process</td>
            <td>e049e2f</td>
            <td>feat(winemaking-process): The structure of the components of the winemaking process has been updated.</td>
            <td>The structure of the components of the winemaking process has been updated.</td>
            <td>Commited on 09/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>9ee3db4</td>
            <td>feat(customer-management): clients.service added.</td>
            <td>clients.service added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>0bc2260</td>
            <td>feat(customer-management): clients.service added.</td>
            <td>clients.service added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>4399fe8</td>
            <td>feat(customer-management): client create and edit component added.</td>
            <td>client create and edit component added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>2dade9e</td>
            <td>feat(customer-management): client management added.</td>
            <td>client management added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b0ff73a</td>
            <td>feat(customer-management): client service added.</td>
            <td>client service added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b0ff73a</td>
            <td>feat(customer-management): massage, skeleton, panel and divider from PrimeVue added.</td>
            <td>massage, skeleton, panel and divider from PrimeVue added.</td>
            <td>Commited on 18/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>3716964</td>
            <td>feat(oder-management): added order management structure.</td>
            <td>added order management structure.</td>
            <td>Commited on 14/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>bf4e1d1</td>
            <td>feat(order): added order entity</td>
            <td>added order entity.</td>
            <td>Commited on 17/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>dabe65c</td>
            <td>feat(order): added order create and edit component</td>
            <td>added order create and edit component</td>
            <td>Commited on 17/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>b0ebd9a</td>
            <td>feat(order): created order service</td>
            <td>created order service</td>
            <td>Commited on 17/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>382a5bb</td>
            <td>feat(navbar-elixir-control.component.vue):  added the navbar elixir control component</td>
            <td>added the navbar elixir control component</td>
            <td>Commited on 19/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>a81e7d3</td>
            <td>feat(order-details):  added the order details card component</td>
            <td>added the order details card component</td>
            <td>Commited on 19/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>c7f9dc1</td>
            <td>refactor(order-management): edited the order management page</td>
            <td>edited the order management page</td>
            <td>Commited on 19/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>bd2a699</td>
            <td>refactor(order-api.service): applied the new endpoints of the db.json</td>
            <td>applied the new endpoints of the db.json</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>ee5ec86</td>
            <td>feat(order-management): added the status button and its now displaying with a certain color depending on the status</td>
            <td>added the status button and its now displaying with a certain color depending on the status</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>9800bda</td>
            <td>refactor(index.js): changed the order details and my orders routes</td>
            <td>changed the order details and my orders routes</td>
            <td>Commited on 20/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>cd5e1ab</td>
            <td>feat(order-create-and-edit): added more inputs for the new attributes of the order</td>
            <td>added more inputs for the new attributes of the order</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>661eb7d</td>
            <td>feat(order.entity): added more attributes to the order entity</td>
            <td>added more attributes to the order entity</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>be0e883</td>
            <td>feat(order-details): added more details of the new attributes of the order</td>
            <td>added more details of the new attributes of the order</td>
            <td>Commited on 27/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>0c95e8a</td>
            <td>refactor(order-management): fixed an error of the details button not displaying correctly</td>
            <td>fixed an error of the details button not displaying correctly</td>
            <td>Commited on 27/10/2024</td>
        </tr>
    </tbody>
    <tbody>
        <!--======================================REPOSITORY======================================-->
        <tr>
            <td rowspan="44">ElixirControl-Platform</td>
            <td>feature/customer-management</td>
            <td>96a3929</td>
            <td>feat(customer-management): client command service added.</td>
            <td>client command service added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>9ee3db4</td>
            <td>chore(develop): Added the base structure of bounded contexts.</td>
            <td>Added the base structure of bounded contexts.</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>3ed3156</td>
            <td>chore(customer-management): Added the order management bounded context structure.</td>
            <td>Added the order management bounded context structure.</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>713529c</td>
            <td>feat(customer-management): class client added.</td>
            <td>class client added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>487c5dc</td>
            <td>feat(customer-management): db context of clients added.</td>
            <td>db context of clients added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>3c32ce3</td>
            <td>feat(customer-management): client repository added.</td>
            <td>client repository added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>d89597e</td>
            <td>feat(customer-management): client resource added.</td>
            <td>client resource added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b4f8bdb</td>
            <td>feat(customer-management): client resource from entity assembles added.</td>
            <td>client resource from entity assembles added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>df2045a</td>
            <td>feat(customer-management): end points added.</td>
            <td>end points added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>0cc12a8</td>
            <td>feat(customer-management): create client command from resource assembler added.</td>
            <td>create client command from resource assembler added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>2233cbc</td>
            <td>feat(customer-management): interface client query service added.</td>
            <td>interface client query service added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>7738dea</td>
            <td>feat(customer-management): dependency injection of clients added.</td>
            <td>dependency injection of clients added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>b2a5d3d</td>
            <td>feat(customer-management): create client resource added.</td>
            <td>create client resource added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>34ace70</td>
            <td>feat(customer-management): client query service added.</td>
            <td>client query service added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/customer-management</td>
            <td>1bd6da8</td>
            <td>feat(customer-management): find all clients async method added.</td>
            <td>find all clients async method added.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>06ca584</td>
            <td>chore(inventory-management): Added the inventory management bounded context structure.</td>
            <td>Added the inventory management bounded context structure.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>b515735</td>
            <td>feat(inventory-management): Added resources and application layer for inventory.</td>
            <td>Added resources and application layer for inventory.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>4c1b464</td>
            <td>feat(inventory-management): Added transform and application layer for inventory.</td>
            <td>Added transform and application layer for inventory.</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/inventory-management</td>
            <td>b8979ff</td>
            <td>feat(inventory-management): added interface inventory controller</td>
            <td>added interface inventory controller</td>
            <td>Commited on 31/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>b6a4487</td>
            <td>feat(CreateOrderCommand): added the command for Create Order</td>
            <td>added the command for Create Order</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>b8e13b2</td>
            <td>feat(GetOrderByIdQuery): created the Get Order by Id Query</td>
            <td>created the Get Order by Id Query</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>730d4b5</td>
            <td>feat(Order): created the order entity on the domain</td>
            <td>created the order entity on the domain</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>ccc505d</td>
            <td>feat(IOrderQueryService): added the Order Query Service interface</td>
            <td>added the Order Query Service interface</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>e06ad04</td>
            <td>feat(IOrderCommandService): added the OrderCommandService interface for handling the CreateOrderCommand</td>
            <td>added the OrderCommandService interface for handling the CreateOrderCommand</td>
            <td>Commited on 30/10/2024</td>
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>7fc94a6</td>
            <td>feat: added order controller repository and entityassembler</td>
            <td>added order controller repository and entityassembler</td>
            <td>Commited on 30/10/2024</td> 
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>ce81dc3</td>
            <td>feat(Orders): added the Orders agreggate</td>
            <td>added the Orders agreggate</td>
            <td>Commited on 30/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-management</td>
            <td>25c5b31</td>
            <td>refactor(example): deleted the example md files</td>
            <td>deleted the example md files</td>
            <td>Commited on 30/10/2024</td>   
        </tr>
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>cd0147d</td>
            <td>chore(order-request):Added the order request bounded context structure.</td>
            <td>Added the order request bounded context structure.</td>
            <td>Commited on 30/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>4406efb</td>
            <td>feat(order-request): Create Order Command From Resource Assembler added.</td>
            <td>Create Order Command From Resource Assembler added.</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>9f72938</td>
            <td>feat(order-request): Get All Orders Query added</td>
            <td>Get All Orders Query added</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>a5370e1</td>
            <td>feat(order-request): Order Controller added.</td>
            <td>Order Controller added.</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>90f1cda</td>
            <td>feat(order-request): Order Command Service added.</td>
            <td>Order Command Service added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>b3a2a98</td>
            <td>feat(order-request): Order Resource From Entity Assembler added.</td>
            <td>Order Resource From Entity Assembler added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>f50146b</td>
            <td>feat(order-request): Order Resource added.</td>
            <td>Order Resource added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/order-request</td>
            <td>8ebe465</td>
            <td>feat(order-request): Order Query Service added.</td>
            <td>Order Query Service added.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>30e4f42</td>
            <td>feat(winemaking-process): Added entity and command to add the clarification process to a batch.</td>
            <td>Added entity and command to add the clarification process to a batch.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>e816564</td>
            <td>chore(winemaking-process): Added the winemaking process bounded context structure.</td>
            <td>Added the winemaking process bounded context structure.</td>
            <td>Commited on 28/10/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>92089e4</td>
            <td>feat(winemaking-process): Added the controller that creates the "Clarification" process for the batch.</td>
            <td>Added the controller that creates the "Clarification" process for the batch.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>b03da24</td>
            <td>feat(winemaking-process): Added endpoints that return the winemaking processes (Fermentation, Clarification)</td>
            <td>Added endpoints that return the winemaking processes (Fermentation, Clarification)</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>9eff846</td>
            <td>feat(winemaking-process): Added infrastructure and application layer for batches.</td>
            <td>Added infrastructure and application layer for batches.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>14ccb3a</td>
            <td>feat(winemaking-process): Added REST resources and transforms to add batch clarification stage.</td>
            <td>Added REST resources and transforms to add batch clarification stage.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>6e291d4</td>
            <td>feat(winemaking-process): Added implementation of the Service that returns the fermentation process by BatchID.</td>
            <td>Added implementation of the Service that returns the fermentation process by BatchID.</td>
            <td>Commited on 01/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>84a1137</td>
            <td>feat(winemaking-process): Added the end point to create the fermentation state of a batch.</td>
            <td>Added the end point to create the fermentation state of a batch.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
        <!--=========================================FILA======================================-->
        <tr>
            <td>feature/winemaking-process</td>
            <td>70f11e5</td>
            <td>feat(winemaking-process): Added endpoints to create and return the batch pressing process.</td>
            <td>Added endpoints to create and return the batch pressing process.</td>
            <td>Commited on 02/11/2024</td>  
        </tr> 
    </tbody>
</table>



#### 5.2.3.4.Testing Suite Evidence for Sprint Review.

En esta entrega no se han realizado los test

#### 5.2.3.5.Execution Evidence for Sprint Review.

* Landing Page Execution

Evidencias de ultima version de Landing Page

![fronted.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Ffronted.png)

Evidencia del video de About the product

![aboutapp.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Faboutapp.png)

* Web Application Execution

Evidencias de ultima version de la aplicacion con una mejora en la interfaz de navegacion, mejora en los detalles del inventario
y se completo la seccion de "My Clients"

![frontendv2.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Ffrontendv2.png)

Evidencia de mejora del inventario

![frontendv3.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Ffrontendv3.png)

Evidencia de la seccion de "My Clients"

![frontendv4.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Ffrontendv4.png)

* Web Services Execution

Evidencias de Swagger conectado a nuestro backend:

![api1.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fapi1.png)

![api2.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fapi2.png)

Enlace del Web Services desplegado: http://elixircontrol.runasp.net/swagger/index.html


#### 5.2.3.6.Services Documentation Evidence for Sprint Review.


### Batch Endpoints

| URL                                                | Endpoint                | HTTP Verb | Acción Implementada     | Sintaxis de Llamada                                                                             | Parámetros Posibles     | Ejemplo de Response                                                    | Explicación del Response                |
|----------------------------------------------------|-------------------------|-----------|-------------------------|-------------------------------------------------------------------------------------------------|-------------------------|------------------------------------------------------------------------|-----------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch/{batchId} | GET       | Obtener un lote por ID  | 'accept: application/json'                                                                      | batchId (path)          | `{"id": 0, "vineyardCode": "string", "grapeVariety": "string", ...}`   | Retorna un objeto con detalles del lote |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch           | POST      | Crear un nuevo lote     | 'Content-Type: application/json' -d '{"vineyardCode": "string", "grapeVariety": "string", ...}' | JSON con datos del lote | `{"id": 0, "vineyardCode": "string", "grapeVariety": "string", ...}`   | Retorna el objeto lote creado           |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/batch           | GET       | Obtener todos los lotes | 'accept: application/json'                                                                      | Ninguno                 | `[{"id": 0, "vineyardCode": "string", "grapeVariety": "string", ...}]` | Retorna un array de objetos lote        |

## WinemakingProcessByBatch Endpoints

| URL                                                | Endpoint                                                | HTTP Verb | Acción Implementada             | Sintaxis de Llamada                                                                 | Parámetros Posibles                              | Ejemplo de Response                                                        | Explicación del Response                      |
|----------------------------------------------------|---------------------------------------------------------|-----------|---------------------------------|-------------------------------------------------------------------------------------|--------------------------------------------------|----------------------------------------------------------------------------|-----------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/fermentation  | GET       | Obtener fermentación por lote   | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "startDate": "string", ...}`                      | Retorna objeto con detalles de fermentación   |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/fermentation        | POST      | Añadir fermentación a un lote   | 'Content-Type: application/json' -d '{"batchId": 0, "startDate": "string", ...}'    | batchId (path), JSON con datos de fermentación   | `{"id": 0, "batchId": 0, "startDate": "string", ...}`                      | Retorna el objeto fermentación creado         |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/clarification | GET       | Obtener clarificación por lote  | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "productsUsed": "string", ...}`                   | Retorna objeto con detalles de clarificación  |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/clarification       | POST      | Añadir clarificación a un lote  | 'Content-Type: application/json' -d '{"batchId": 0, "productsUsed": "string", ...}' | batchId (path), JSON con datos de clarificación  | `{"id": 0, "batchId": 0, "productsUsed": "string", ...}`                   | Retorna el objeto clarificación creado        |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/pressing      | GET       | Obtener prensado por lote       | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "pressingDate": "2024-11-03T09:24:52.277Z", ...}` | Retorna objeto con detalles de prensado       |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/pressing            | POST      | Añadir prensado a un lote       | 'Content-Type: application/json' -d '{"batchId": 0, "pressingDate": "string", ...}' | batchId (path), JSON con datos de prensado       | `{"id": 0, "batchId": 0, "pressingDate": "2024-11-03T09:24:52.281Z", ...}` | Retorna el objeto prensado creado             |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/batch/{batchId}/aging         | GET       | Obtener envejecimiento por lote | 'accept: application/json'                                                          | batchId (path)                                   | `{"id": 0, "batchId": 0, "barrelType": "string", ...}`                     | Retorna objeto con detalles de envejecimiento |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/winemakingProcess/{batchId}/aging               | POST      | Añadir envejecimiento a un lote | 'Content-Type: application/json' -d '{"batchId": 0, "barrelType": "string", ...}'   | batchId (path), JSON con datos de envejecimiento | `{"id": 0, "batchId": 0, "barrelType": "string", ...}`                     | Retorna el objeto envejecimiento creado       |

## Orders Endpoints

| URL                                                | Endpoint            | HTTP Verb | Acción Implementada       | Sintaxis de Llamada                                                                              | Parámetros Posibles        | Ejemplo de Response                                                     | Explicación del Response                   |
|----------------------------------------------------|---------------------|-----------|---------------------------|--------------------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------------------|--------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders      | POST      | Crear una nueva orden     | 'Content-Type: application/json' -d '{"businessName": "string", "requestedDate": "string", ...}' | JSON con datos de la orden | `{"id": 0, "businessName": "string", "requestedDate": "string", ...}`   | Retorna el objeto orden creado             |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders      | GET       | Obtener todas las órdenes | 'accept: application/json'                                                                       | Ninguno                    | `[{"id": 0, "businessName": "string", "requestedDate": "string", ...}]` | Retorna un array de objetos orden          |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/orders/{id} | GET       | Obtener una orden por ID  | 'accept: application/json'                                                                       | id (path)                  | `{"id": 0, "businessName": "string", "requestedDate": "string", ...}`   | Retorna un objeto con detalles de la orden |

## Inventory Endpoints

| URL                                                | Endpoint                        | HTTP Verb | Acción Implementada           | Sintaxis de Llamada                                                             | Parámetros Posibles           | Ejemplo de Response                                    | Explicación del Response                      |
|----------------------------------------------------|---------------------------------|-----------|-------------------------------|---------------------------------------------------------------------------------|-------------------------------|--------------------------------------------------------|-----------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory/{inventoryId} | GET       | Obtener inventario por ID     | 'accept: application/json'                                                      | inventoryId (path)            | `{"id": 0, "name": "string", "type": "string", ...}`   | Retorna un objeto con detalles del inventario |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory               | POST      | Crear un nuevo inventario     | 'Content-Type: application/json' -d '{"name": "string", "type": "string", ...}' | JSON con datos del inventario | `{"id": 0, "name": "string", "type": "string", ...}`   | Retorna el objeto inventario creado           |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/inventory               | GET       | Obtener todos los inventarios | 'accept: application/json'                                                      | Ninguno                       | `[{"id": 0, "name": "string", "type": "string", ...}]` | Retorna un array de objetos inventario        |

## Clients Endpoints

| URL                                                | Endpoint                     | HTTP Verb | Acción Implementada        | Sintaxis de Llamada                                                                  | Parámetros Posibles        | Ejemplo de Response                                         | Explicación del Response                       |
|----------------------------------------------------|------------------------------|-----------|----------------------------|--------------------------------------------------------------------------------------|----------------------------|-------------------------------------------------------------|------------------------------------------------|
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients              | POST      | Crear un nuevo cliente     | 'Content-Type: application/json' -d '{"personName": "string", "dni": "string", ...}' | JSON con datos del cliente | `{"id": 0, "personName": "string", "dni": "string", ...}`   | Retorna el objeto cliente creado               |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients              | GET       | Obtener todos los clientes | 'accept: application/json'                                                           | Ninguno                    | `[{"id": 0, "personName": "string", "dni": "string", ...}]` | Retorna un array de objetos cliente            |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients/{id}         | GET       | Obtener un cliente por ID  | 'accept: application/json'                                                           | id (path)                  | `{"id": 0, "personName": "string", "dni": "string", ...}`   | Retorna un objeto con detalles del cliente     |
| http://elixircontrol.runasp.net/swagger/index.html | /api/v1/clients/{dni}/client | GET       | Obtener clientes por DNI   | 'accept: application/json'                                                           | dni (path)                 | `[{"id": 0, "personName": "string", "dni": "string", ...}]` | Retorna un array de objetos cliente con el DNI |

#### 5.2.3.7.Software Deployment Evidence for Sprint Review.


En esta sección se describen los procesos de despliegue de la base de datos y el Web Service realizados durante el Sprint. Para la base de datos, se utilizó AWS LightSail, donde se creó una base MySQL en un plan gratuito. El  Web Service se desplegó en MonsterASP.net, configurando un sitio web gratuito, activando el acceso de web deploy y publicando desde Visual Studio 2022. Ambos componentes quedaron listos para su uso.


### Despliegue de la base de datos

Para el depliegue de la base de datos se utilizo LightSail de AWS.

Inicio sesion con mi usuario de aws, me dirijo a Databases y me dirigo a "Create Database"

![](../assets/img/chapter-V/sprint-3/database1.PNG)

Seleccionamos MySql version 8.0.39

![](../assets/img/chapter-V/sprint-3/database2.PNG)

Elegimos el plan gratuito por 3 meses

![](../assets/img/chapter-V/sprint-3/database3.PNG)

Escribimos el nombre de nuestra base de datos y seleccionamos el boton de "Create database"

![](../assets/img/chapter-V/sprint-3/database4.PNG)

![](../assets/img/chapter-V/sprint-3/database.PNG)

Finalmente nuestra base de datos esta creada y lista para ser utilizada

![](../assets/img/chapter-V/sprint-3/database5.PNG)


### Despliegue del Web Service


Para el despliegue del  Web Service se utilizo MonsterASP.net

Comenzamos con la creacion de cuenta en MonsterASP.net

![](../assets/img/chapter-V/sprint-3/deploy.PNG)


![](../assets/img/chapter-V/sprint-3/deploy2.PNG)

Una vez creada y activada la cuenta nos dirigimos a la seccion de Websites y seleccionamos "Add Website"

![](../assets/img/chapter-V/sprint-3/deploy3.PNG)

Seleccionamos FREE website, especificamos el subdominio "ElixirControl" y seleccionamos "Create"

![](../assets/img/chapter-V/sprint-3/deploy4.PNG)

![](../assets/img/chapter-V/sprint-3/deploy5.PNG)

Una vez creado nos dirigimos a la seccion de "Deploy"

![](../assets/img/chapter-V/sprint-3/deploy6.PNG)

![](../assets/img/chapter-V/sprint-3/deploy7.PNG)

Activamos el web deploy access y descargamos el "publish profile"

![](../assets/img/chapter-V/sprint-3/deploy8.PNG)

Configuramos el program.cs para que Swagger este disponible para produccion

![](../assets/img/chapter-V/sprint-3/swagger.PNG)

Abrimos el proyecto en Visual Studio 2022, seleccionamos la opcion de "Publish" y seleccionamos el archivo descargado anteriormente

![](../assets/img/chapter-V/sprint-3/deploy9.PNG)

![](../assets/img/chapter-V/sprint-3/publish.PNG)

![](../assets/img/chapter-V/sprint-3/deploy10.PNG)


![](../assets/img/chapter-V/sprint-3/deploy11.PNG)

Seleccionamos el boton de publicar y esperamos que complete el proceso

![](../assets/img/chapter-V/sprint-3/deploy12.PNG)

Finalmente nuestro  Web Service esta desplegado y listo para ser utilizado

![](../assets/img/chapter-V/sprint-3/deploy14.PNG)


Link del  Web Service desplegado: [http://elixircontrol.runasp.net/swagger/index.html](http://elixircontrol.runasp.net/swagger/index.html)






### 5.2.7. RESTful API documentation


### 5.2.8. Team Collaboration Insights

##### 5.2.8.1. Team Collaboration Insights during Sprint 1.

En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de commits realizadas por cada integrante del equipo durante el desarrollo de la landing page.

![tb1-pulse.png](../assets/img/chapter-V/sprint-1/tb1-pulse.png)

Los siguientes gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![tb1-traffic.png](../assets/img/chapter-V/sprint-1/tb1-traffic.png)

##### 5.2.8.2. Team Collaboration Insights during Sprint 2

![img.png](../assets/img/chapter-V/sprint-2/img.png)

![img.png](../assets/img/chapter-V/sprint-2/img1.png)

![img.png](../assets/img/chapter-V/sprint-2/img2.png)

#### 5.2.3.8.Team Collaboration Insights during Sprint 3.

En esta entrega, nuestra meta principal fue culminar los servicios tanto del frontend y backend. Se representan los commits realizados por cada miembro del equipo MetaSoft:

A continuación se muestra la cantidad de clonaciones realizadas por cada integrante del equipo durante el desarrollo de los services.

![image (1).png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fimage%20%281%29.png)

![gitclones (1).png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fgitclones%20%281%29.png)

En esta captura se muestra el flujo de las ramas creadas, su creación.

![commits.png](..%2Fassets%2Fimg%2Fchapter-V%2Fsprint-3%2Fcommits.png)

## 5.4. Video About-the-Product.


En esta sección presentamos el video sobre nuestro producto, ElixirControl. Este video ofrece una perspectiva promocional, resumida en el modelo de nuestro negocio, que abarca las funcionalidades y beneficios de la plataforma. También incluye escenas de interacción con el sistema y opiniones de los principales segmentos objetivo: vitivinicultores y distribuidores de vinos y piscos artesanales.

¿Eres un productor vitivinícola que busca una solución integral para gestionar tu inventario, mejorar la trazabilidad de tus productos y optimizar tus procesos? ¿O eres un distribuidor que quiere asegurar una cadena de suministro eficiente y bien organizada? Te presentamos ElixirControl. ElixirControl es nuestra plataforma que facilita la gestión de inventarios, pedidos y el control de calidad, diseñada especialmente para la industria vitivinícola, para que puedas dedicarte a lo que más importa: la creación de productos de alta calidad.

<img src="/assets/img/chapter-V/sprint-3/videoabouttheproduct.png" alt="Foto de video about-the-product">

Link de Microsoft Stream: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201717523_upc_edu_pe/EfKNxQVwL8dCmsXyvgw0ZywBpKddxlXlR_l-C_mZ1km9AA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=1je8Hx

Link de Youtube: https://youtu.be/YTH8Bv54DZs






## 6. Conclusiones, Bibliografía y Anexos.

### Conclusiones


En conclusión, el objetivo de este informe es presentar un análisis detallado que documente la solución de software propuesta, ElixirControl. Para alcanzar este objetivo, es fundamental incluir información clara y concisa sobre el proyecto, que abarque desde la descripción de la idea hasta los requisitos específicos y las funcionalidades deseadas. Este análisis debe ser exhaustivo, proporcionando una visión completa de cómo la solución abordará las necesidades del sector vitivinícola. Las user stories desempeñan un papel crucial en este proceso, ya que permiten describir los requisitos de manera simple y centrada en el usuario. En resumen, las user stories son herramientas valiosas en el desarrollo ágil de software, asegurando que el equipo se enfoque en crear un producto que satisfaga efectivamente las necesidades de los clientes y mejore su experiencia en la gestión de procesos productivos y logísticos.


### Bibliografía

Celis Escudero, F. R. (2001). Elaboración de vino con mosto concentrado de uva borgoña negra (Vitis labrusca) [Tesis, Universidad Nacional de San Martín]. Repositorio UNSM. https://repositorio.unsm.edu.pe/bitstream/11458/58/1/21%272%2700075.pdf

Gómez Rubio, D. J. (2014). Investigación científica y tecnológica de la vinificación de la uva Red Globe (Vitis Vinífera L.) [Tesis, Universidad Católica de Santa María]. Repositorio UCSM. https://repositorio.ucsm.edu.pe/items/8d95b4ac-8c09-4354-8df7-2507eed3c70a

Husnayo Guillermo, E. G. (2012). Análisis económico de la elaboración del vino en Tacna [Tesis, Universidad Nacional Jorge Basadre Grohmann]. Repositorio UNJBG. https://repositorio.unjbg.edu.pe/server/api/core/bitstreams/668098dd-4976-4b2f-9acf-2c7bdb6cfc28/content

Wein Manager App. (n.d.). Track your wine cellar inventory with our professional Wine Cellar Manager app. Retrieved September 27, 2024, from https://winemanager.app

VinoTEC. (n.d.). Software ERP y CRM - Bodegas y cooperativas vitivinícolas. Retrieved September 27, 2024, from https://vinotec.net

Vintrace. (n.d.). Winery software | A better way to make wine. Retrieved September 27, 2024, from https://www.vintrace.com



### Anexos

<table>
<thead>
    <tr>
        <th>Sección</th>
        <th>Características del video</th>
        <th>Sobre el contenido</th>
        <th>Integración y entrega</th>
    </tr>
</thead>
<tbody>
<!--========================================= FILA 1 ======================================-->
<tr>
  <td>Needfinding Interviews</td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-needfinding-sprint-1
    Formato: .mp4
  </td>
  <td> Consolida todas las entrevistas realizadas </td>
  <td> 
    Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923571_upc_edu_pe/EZw-9tmmOSJPsIy_Qcor0FkBBYUZFt8o47YcZmrvLmA8Fg?e=Pyj62I&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D 
</td>
</tr>
<!--========================================= FILA 2 ======================================-->
<tr>
  <td>Exposición</td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-expo-tb1
    Formato: .mp4
  </td>
  <td>Consolida las exposiciones de la TB1	</td>
  <td>
    Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923571_upc_edu_pe/ERTxpx1uyvJKmY3QL8mRb6sB8lFh8XQB4o_F_MernOdpGQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=7R6pjN 
  </td>
</tr>
<!--========================================= FILA 3 ======================================-->
<tr>
  <td>
    Prototypes Navigation / Product Navigation
  </td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-prototype-navigation-sprint-1
    Formato: .mp4
  </td>
  <td>
    Consolida demostración del flujo de navegación de las aplicaciones, priorizando los user flows relacionados con el core business.	
  </td>
  <td>
    Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923571_upc_edu_pe/EQ3ShXzJBlJAllrQ9SJ3yY8Bacs6SF9dXo-7o_dXhgiZYw?e=e6Hn8s&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D
  </td>
</tr>
<!--========================================= FILA 4 ======================================-->
<tr>
  <td>
    Validation Interviews
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
</tr>
<!--========================================= FILA 5 ======================================-->
<tr>
  <td>
    About the Product
  </td>
  <td>
    Cantidad de videos: 1
    Nomenclatura: upc-pre-202402-si730-sv51-metasoft-aboutthe-product-sprint-3
    Formato: .mp4 
  </td>
  <td>
    Orientación promocional, resumiendo el modelo de negocio, las características y beneficios del producto, incluyendo algunas escenas de interacción con el producto y al menos una opinión por cada segmento objetivo.
  </td>
  <td>
    Link:  https://1drv.ms/v/c/cab22ef84dc9095b/Ef6hskhLpFJDiyqCgws149cBkYiR3Z7gNJzAtu0w4I_g5Q?e=B0tbiv
  </td>
</tr>
<!--========================================= FILA 6 ======================================-->
<tr>
  <td>
    About the Team
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
</tr>
<!--========================================= FILA 7 ======================================-->
<tr>
  <td>
    Conclusiones, Bibliografía y Anexos
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
  <td>
    Contenido 
  </td>
</tr>
</tbody>
</table>
