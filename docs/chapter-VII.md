# Capítulo VII: DevOps Practices


## 7.1. Continuous Integration


### 7.1.1. Tools and Practices.


En el desarrollo y pruebas de software con .NET, es crucial contar con herramientas y enfoques que aseguren tanto la calidad del código como la eficiencia en el equipo de desarrollo. A lo largo del ciclo de vida del software, empleamos diversas herramientas que apoyan desde la codificación inicial hasta la validación funcional y automatización de pruebas.

Seguimos metodologías como el Desarrollo Orientado por Comportamiento (BDD) y el Desarrollo Orientado por Pruebas (TDD), lo cual nos permite construir soluciones alineadas a los requerimientos del negocio, manteniendo al mismo tiempo altos estándares técnicos.

A continuación, se presentan las principales herramientas utilizadas:


| Herramienta | Tipo                           | Descripción                                                                                                                                   | Propósito                                                                                                        |
|-------------|--------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| NUnit       | Herramienta para pruebas (TDD) | Framework de pruebas unitarias para .NET que permite verificar funcionalidades específicas de manera automática y aislada.                    | Facilita la detección de errores en funciones individuales y garantiza que los módulos funcionen como se espera. |
| SpecFlow    | Herramienta de BDD             | Herramienta basada en Gherkin que permite escribir escenarios comprensibles por todos y vincularlos con código C# para pruebas automatizadas. | Permite desarrollar pruebas centradas en el comportamiento esperado por el usuario final o el negocio.           |



### 7.1.2. Build & Test Suite Pipeline Components

Durante el desarrollo del proyecto, se configuró un entorno de integración continua que permite ejecutar automáticamente la compilación del backend y la ejecución de las pruebas automatizadas. A continuación, se describen los componentes involucrados:

**Herramientas utilizadas:**
.NET SDK (v8 y v9): para compilar el backend y ejecutar pruebas.

Rider IDE: como entorno de desarrollo con soporte integrado para ejecutar pruebas NUnit y SpecFlow.

SpecFlow + NUnit: para pruebas de aceptación BDD basadas en archivos .feature.

Terminal / PowerShell: para ejecutar pruebas vía dotnet test.

Azure App Service: para despliegue del backend.

GitHub: para control de versiones y documentación colaborativa.

**Flujo del pipeline:**
Compilación del Backend (dotnet build)

Ejecución de pruebas automatizadas (dotnet test)

Visualización de resultados en la terminal y en Rider (Test Explorer)

**Tipos de pruebas integradas:**
Unit Tests: (pendiente implementar para entidades principales)

Integration Tests: (pendiente para futuras integraciones entre microservicios)

BDD Tests: implementados para los siguientes módulos:

US04 – Fermentación

US05 – Clarificación

US06 – Prensado

US07 – Añejamiento

US08 – Embotellado


### 7.2. Continuous Delivery

Su objetivo es el de automatizar la integración y pruebas del código, manteniendo todo listo para un
despliegue cuando sea necesario.

### 7.2.1. Tools and Practices.


En el desarrollo del proyecto con tecnologías .NET, seguimos un enfoque de Entrega Continua (Continuous Delivery) que nos permite tener versiones del software listas para producción en cualquier momento. Este enfoque garantiza un control riguroso sobre lo que se libera, manteniendo al mismo tiempo un alto nivel de automatización y consistencia.

#### Herramientas utilizadas

- **GitHub Actions**: Se utiliza para automatizar los flujos de integración y entrega. Permite compilar, probar y dejar lista la aplicación para su despliegue. Sin embargo, el paso a producción se realiza manualmente para asegurar un mayor control.

- **Trello**: Se emplea para organizar tareas y gestionar el proceso de aprobación del despliegue. Luego de completar el pipeline de validación, se requiere que un miembro del equipo apruebe manualmente el despliegue a producción.

#### Prácticas aplicadas

- **Feature Branching**: Cada nueva funcionalidad se desarrolla en una rama independiente. Estas ramas se integran a la rama principal solo después de pasar las pruebas automáticas correspondientes.

- **Validación en staging**: Antes de llegar a producción, la aplicación se despliega en un entorno de staging donde se realizan pruebas manuales y revisiones por parte del equipo. Esto permite detectar posibles errores en un entorno que simula el real.

- **Despliegue semiautomático**: El pipeline automatiza todos los pasos hasta dejar la aplicación lista para producción. Sin embargo, el despliegue final se ejecuta únicamente cuando es aprobado manualmente por un miembro responsable del equipo.

- **Aprobación manual**: Antes del despliegue, se requiere que el responsable del proyecto revise los resultados de las pruebas y los reportes generados. Solo después de su aprobación se procede con el despliegue.

- **Rollback manual**: En caso de errores críticos, el equipo puede realizar una reversión manual a la versión anterior estable. Esto permite mantener la continuidad operativa mientras se resuelve el problema.



### 7.2.2. Stages Deployment Pipeline Components


Integración Continua (CI):
Al hacer un commit en una rama de desarrollo, el pipeline ejecuta pruebas automáticas y valida
que la aplicación esté lista para ser desplegada. Este paso garantiza que el código siempre esté
en un estado "desplegable".
Validación en Staging:
Una parte importante es tambien la validación del código en un entorno de staging antes de
desplegar a producción. Aquí se simulan escenarios de producción y se pueden realizar pruebas
adicionales, incluyendo pruebas manuales, de carga o seguridad.
Despliegue Manual:
Aunque el código puede estar preparado para su despliegue automático, el paso final del
despliegue requiere la aprobación de una persona. Esto permite una mayor supervisión antes de
afectar a los usuarios finales.
Monitoreo y Feedback:
El pipeline de CD incluye herramientas de monitoreo y análisis que permiten observar cómo el
nuevo código afecta el rendimiento de la aplicación antes de hacer el despliegue completo.
Aprobación del Despliegue:
En este componente, el pipeline queda en espera hasta que un desarrollador, administrador o
equipo de operaciones apruebe el despliegue a producción.


## 7.3. Continuous Deployment

### 7.3.1. Tools and Practices

En este apartado, se detallan las herramientas y prácticas que aseguran un despliegue automatizado y
confiable en producción.
Tools (Herramientas):
• GitHub Actions o GitLab CI: Para automatizar el pipeline de CI/CD. Estas herramientas permiten
configurar workflows que incluyen la ejecución de pruebas y el despliegue automático a
diferentes entornos (desarrollo, staging, producción).
• Docker: Para contenerizar la aplicación backend (Spring Boot). Docker permite empaquetar la
aplicación con todas sus dependencias, asegurando consistencia en los entornos de desarrollo y
producción.
• Railway: Como plataforma para la base de datos MySQL, Railway permite gestionar el
despliegue de forma automatizada, con soporte para migraciones y backups.
• Render: Esta plataforma se encargará del despliegue automático del backend en Spring Boot,
ofreciendo monitoreo y escalabilidad automática.
• Firebase Hosting: Para el frontend en Angular, Firebase Hosting automatiza los despliegues de
la aplicación web y asegura un despliegue rápido y seguro.
Feature Branching:
• Utilizamos una estrategia de ramas en Git donde los desarrolladores trabajan en nuevas
funcionalidades dentro de ramas separadas. Una vez completadas y probadas, estas ramas se
fusionan a la rama develop, que es la encargada de gestionar los despliegues a producción.
• Commit-based deployment (Despliegue basado en commits): Cada vez que se realiza un
commit en la rama develop, el pipeline de CI/CD se activa automáticamente para ejecutar los
procesos de construcción, pruebas y despliegue. Esta rama es la que usamos para que los
cambios se desplieguen directamente, manteniendo el flujo de trabajo ágil y automatizado.
• Rollback automático: En caso de detectar fallos en producción después del despliegue, el
pipeline está configurado para realizar un rollback automático, restaurando la versión anterior
del software y notificando al equipo sobre el error. Esto garantiza estabilidad y una rápida
recuperación de fallos.

### 7. 3. 2. Production Deployment Pipeline Components.

#### Pipeline de despliegue para base de datos y aplicaciones

En el presente proyecto se utilizaron servicios en la nube como **Azure** para la gestión de la base de datos y el despliegue del backend en App Service, así como **Vercel** para el despliegue continuo del frontend. A continuación, se describen los componentes y prácticas que forman parte del pipeline hacia producción:

#### 1. Gestión de migraciones automáticas

El backend desarrollado en .NET aplica cambios en el modelo de datos a través de migraciones controladas por Entity Framework Core. Estas migraciones se ejecutan en Azure, permitiendo mantener sincronizado el esquema de la base de datos con la evolución del código fuente.

#### 2. Copias de seguridad previas

Antes de aplicar migraciones importantes, se realizan respaldos de la base de datos MySQL gestionada en Azure. Esto garantiza que ante cualquier fallo durante la migración, el estado anterior pueda ser restaurado sin pérdida de información.

#### 3. Supervisión del rendimiento

Azure ofrece herramientas de monitoreo que permiten observar el comportamiento de la base de datos en tiempo real. Si se presentan errores de conexión, lentitud o fallos en consultas, el equipo es notificado para tomar acciones inmediatas.

#### 4. Validación del esquema de base de datos

Después de ejecutar una migración, se recomienda validar el estado del esquema mediante pruebas automatizadas. Estas validaciones aseguran que las nuevas columnas, relaciones y restricciones se han aplicado correctamente y que no se ha afectado la integridad de los datos existentes.

#### 5. Despliegue continuo del backend y frontend

Una vez validadas las migraciones y el estado de la base de datos, el backend se despliega automáticamente en Azure App Service como parte del pipeline de CI/CD. Por su parte, el frontend se despliega mediante Vercel, que detecta cambios en la rama principal del repositorio y publica automáticamente una nueva versión en producción.

Este flujo garantiza un proceso ágil y confiable de entrega continua, manteniendo sincronizados el backend, la base de datos y el frontend en sus respectivas plataformas de despliegue.


