# Chapter III

## 3.1 To-Be Scenario Mapping

![ToBe](/assets/img/chapter-III/RF.jpg)

## 3.2 User Stories

En este punto, se encuentran una serie de historias de usuario que han sido creadas para capturar las necesidades y expectativas clave del producto. Estas historias servirán como base para la planificación, el desarrollo y la validación del software.

| EpicID  | Titulo                                                | Descripción                                                                                                                                                                                                                                                                                    |
| ------- |-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| EPIC-01 | Experiencia de logeo                                  | Como vinicultor, quiero poder registrarme de manera exitosa al moemento de querer usar la aplicacion (register and login)                                                                                                                                                                      |
| EPIC-02 | Gestión del proceso de vinificación.                  | Como vinicultor, quiero gestionar todas las fases del proceso de vinificación (fermentación, clarificación, prensado, añejamiento y embotellado), para asegurar que el proceso sea monitoreado y controlado en cada etapa, garantizando la calidad del producto final.                         |
| EPIC-03 | Experiencia de Usuario (UX) Mejorada                  | Como usuario, quiero tener una experiencia de usuario fluida e intuitiva dentro de la plataforma, para que todas las funcionalidades sean fáciles de encontrar y usar.                                                                                                                         |
| EPIC-04 | Experiencia Integral del Visitante en la Landing Page | Como visitante de la landing page de Elixir Control, quiero tener una experiencia de navegación fluida, con información clara sobre la aplicación, sus beneficios, precios, y acceso a soporte, para tomar decisiones informadas y sentirme seguro al considerar la adopción de la aplicación. |

<table table border="1">
    <thead>
        <tr>
            <th>Story ID</th>
            <th>Título</th>
            <th>Descripción</th>
            <th>Criterios de Aceptación</th>
            <th>Epic ID</th>
        </tr>
    </thead>
    <tbody>
        <!-- User Story 01-->
        <tr>
            <td>US-01</td>
            <td>Hipervínculos en el encabezado</td>
            <td>
                Como visitante que llega a la landing page 
                quiero que los hipervínculos en el encabezado sean claramente visibles y funcionales
                para poder navegar fácilmente por la aplicación.	        
            </td>
            <td>
                <strong>Scenario 1: Hipervínculos están claramente visibles</strong>
                <br>
                Given un visitante en la landing page
                When el sitio web se carga completamente
                Then los hipervínculos en el encabezado están disponibles para el usuario
                <br><br>
                <strong>Scenario 2: Hipervínculos permiten navegación correcta</strong> 
                <br>
                Given un visitante en la landing page
                When el visitante hace clic en cualquier hipervínculo en el encabezado
                Then es redirigido a la sección correspondiente de la landing page.
            </td>
            <td>EPIC-04</td>
        </tr>
        <!-- User Story 02 -->
        <tr>
            <td>US-02</td>
            <td>Información sobre beneficios de la aplicación</td>
            <td>
                Como usuario, quiero tener acceso a información clara sobre los beneficios de la aplicación para entender cómo puede ayudarme en mis actividades.
            </td>
            <td>
                <strong>Scenario 1: Introducción visible al visitante</strong>
                <br>
                Given un visitante en la landing page
                When el visitante llega al sitio web
                Then la introducción de la aplicación está visible y presenta claramente el propósito de Elixir Control.
                <br><br>
                <strong>Scenario 2: Introducción comunica el propósito de la aplicación</strong>
                <br>
                Given un visitante en la landing page
                When el visitante lee la introducción
                Then puede entender el propósito de la aplicación y cómo ayuda en el proceso productivo de vinos.
            </td>
            <td>EPIC-04</td>
        </tr>
        <!-- User Story 03 -->
        <tr> 
            <td>US-03</td> 
            <td>Información útil en el footer</td> 
            <td> 
                Como usuario, quiero que el footer contenga información útil, como datos de contacto y enlaces a políticas, para facilitar mi navegación. 
            </td> 
            <td> 
                <strong>Scenario 1: Visualización de datos de contacto</strong><br> 
                Given el usuario navega hacia el final de la página<br> 
                When llega al footer
                <br> Then puede visualizar claramente los datos de contacto de la empresa.<br><br>
                <strong>Scenario 2: Enlaces funcionales a políticas</strong><br>
                Given el usuario está en el footer<br>
                When hace clic en un enlace a políticas (privacidad, cookies, etc.)<br>
                Then es redirigido correctamente a la sección o documento correspondiente.
            </td>
            <td>EPIC-04</td>
        </tr>
        <!-- User Story 04 -->
        <tr>
            <td>US-04</td>
            <td>Registro del estado de fermentación </td>
            <td>
               Como usuario con rol de vinicultor,quiero registrar y monitorear el estado de la fermentación de mis lotes,para asegurar que las condiciones iniciales y los parámetros  del proceso se controlen correctamente y queden documentados. 
            </td>
            <td>
                <strong> Scenario 1: Registro exitoso de la finalización de la fermentación </strong><br>
                Given el vinicultor está monitoreando la fase de fermentación
                When el proceso de fermentación llega a su tiempo final
                Then el sistema actualiza el estado a "Fermentación completada"
                And registra el tiempo y la temperatura final en el historial.
                <br><br>
                <strong> Scenario 2: Fallo en el registro de tiempo de fermentación </strong><br>
                Given el vinicultor está en la fase de fermentación
                When el sistema no puede registrar el tiempo final por error de conexión
                Then el sistema muestra una alerta de error de registro
                And solicita la intervención manual para completar el registro. 
            </td>
            <td>EPIC-02</td>
        </tr>
        <!-- User Story 05 -->
        <tr>
            <td>US-05</td>
            <td>Registro del estado de clarificación </td>
            <td>
                Como usuario con rol de vinicultor, quiero registrar y actualizar los datos relacionados con la clarificación de mis lotes,para asegurarme de que los agentes clarificantes y las fechas del proceso se gestionen adecuadamente y queden registrados en el sistema.
            </td>
            <td>
                <strong> Scenario 1: Registro   exitoso de agentes    clarificantes añadidos </strong><br>
                Given el vinicultor está en la  fase de clarificación
                When se añaden los agentes  clarificantes correctamente
                Then el sistema actualiza el estado a "Clarificación en proceso"
                And registra el tipo y cantidad de agentes en el historial de la fase.
                <br><br>
                <strong> Scenario 2: Registro   exitoso de finalización del   proceso de clarificación </strong><br>
                Given el vinicultor ha  completado el tiempo de  clarificación
                When el proceso de clarificación finaliza
                Then el sistema actualiza el    estado a "Clarificación    completada"
                And registra la fecha y hora de finalización.
            </td>
            <td>EPIC-02</td>
        </tr>
        <!-- User Story 06 -->
        <tr>
            <td>US-06</td>
            <td>Registro del estado de prensado</td>
            <td>
                Como usuario con rol de vinicultor, quiero registrar el inicio, progreso y  finalización del prensado de mis lotes,para controlar y documentar de manera precisa la cantidad de jugo extraído y los detalles del proceso.
            </td>
            <td>
                <strong> Scenario 1: Registro del inicio del prensado </strong><br>
                Given el vinicultor está comenzando la fase de prensado
                When registra los detalles del lote y el inicio del proceso
                Then el sistema actualiza el estado a "Prensado en proceso"
                And almacena los detalles del lote y la fecha de inicio en el registro.
                <br><br>
                <strong> Scenario 2: Error en el registro de prensado </strong><br>
                Given el vinicultor intenta registrar el inicio del prensado
                When ocurre un fallo en la app durante el registro
                Then el sistema muestra una alerta de fallo y ofrece opciones para reintentar.
                <strong> Scenario 3: Registro de cantidad de jugo extraído </strong><br>
                Given el prensado ha sido completado
                When el vinicultor registra la cantidad de jugo extraído en la app
                Then el sistema actualiza el estado a "Prensado completado"
                And almacena los detalles del rendimiento en el historial del lote.
            </td>
            <td>EPIC-02</td>
        </tr>
        <!-- User Story 07 -->
        <tr>
            <td>US-07</td>
            <td>Registro del estado de añejamiento </td>
            <td>
                Como usuario con rol de vinicultor, quiero registrar las condiciones y fechas del añejamiento de mis vinos,
                para asegurar que el proceso se documente correctamente y monitorear la evolución del producto a lo largo del tiempo.
            </td>
            <td>
                <strong>  Scenario 1: Registro de inicio del añejamiento </strong><br>
                Given el vinicultor inicia el añejamiento de un lote
                When registra la fecha y condiciones de almacenamiento (temperatura, barrica)
                Then el sistema actualiza el estado a "Añejamiento en proceso"
                And almacena los detalles del lote y las condiciones de inicio.
                <br><br>
                <strong> Scenario 2: Fallo en el registro de parámetros de añejamiento </strong><br>
                Given el vinicultor intenta registrar las condiciones del añejamiento
                When hay un error en la app al guardar los datos
                Then el sistema muestra un mensaje de error y solicita corrección.<br><br>
                <strong> Scenario 3: Registro de la finalización del añejamiento </strong><br>
                Given el vinicultor ha completado el añejamiento
                When registra la fecha de finalización y las condiciones de salida
                Then el sistema actualiza el estado a "Añejamiento completado"
                And guarda los datos de calidad y fecha final en el historial del lote.  
            </td>
            <td>EPIC-02</td>
        </tr>
        <!-- User Story 08 -->
        <tr>
            <td>US-08</td>
            <td>Registro del estado de embotellado </td>
            <td>
                Como usuario con rol de vinicultor, quiero registrar el inicio y finalización del proceso de embotellado, incluyendo la cantidad de botellas producidas, para asegurar que esta etapa esté bien documentada y se refleje correctamente en los registros del lote. 
            </td>
            <td>
                <strong> Scenario 1: Registro   de inicio del embotellado </strong><br>
                Given el vinicultor comienza el     embotellado de un lote
                When registra el número de lote     y la cantidad de botellas en la app
                Then el sistema actualiza el    estado a "Embotellado en   proceso"
                And almacena los detalles del   lote y la cantidad embotellada.<br><br>
                <strong> Scenario 2: Error en   el registro de embotellado </strong><br>
                Given el vinicultor está    embotellando el lote
                When ocurre un error al     registrar el lote en la app
                Then el sistema muestra una     alerta de fallo y solicita  corrección manual.<br><br>
                <strong> Scenario 3: Registro   de finalización del embotellado   </strong><br>
                Given el vinicultor ha  finalizado el embotellado
                When registra la cantidad final     de botellas y la fecha
                Then el sistema actualiza el    estado a "Embotellado  completado"
                And guarda los detalles finales     en el historial del lote.
            </td>
            <td>EPIC-02</td>
        </tr>
        <!-- User Story 09 -->
        <tr>
            <td>US-09</td>
            <td>Reportes Personalizados</td>
            <td>
                Como vinicultor, quiero poder crear reportes personalizados para analizar datos específicos de producción. 
            </td>
            <td>
                <strong>Scenario 01: Generación automática al completar el proceso</strong><br>
                Given un lote ha completado todas las fases del proceso productivo (prensado, fermentación, clarificación, añejamiento y embotellado),<br>
                When se registra la finalización del embotellado,<br>
                Then el sistema genera automáticamente un reporte completo con toda la información registrada del lote.<br><br>
                <strong>Scenario 02: Visualización del reporte generado</strong><br>
                Given el vinicultor ha finalizado el proceso productivo de un lote,<br>
                When accede al historial de producción,<br>
                Then puede visualizar el reporte generado para ese lote, incluyendo fechas, parámetros, insumos utilizados y rendimiento final.<br><br>
            </td>
            <td>EPIC-01</td>
        </tr>
        <!-- User Story 10 -->
        <tr> 
            <td>US-10</td> 
            <td>Visualizar Home de la Plataforma</td> 
            <td> 
                Como usuario, quiero visualizar la página de inicio de la plataforma para acceder fácilmente a las principales funcionalidades. 
            </td> 
            <td> 
                <strong>Scenario 1: Visualización correcta del home</strong><br> Given el usuario accede a la plataforma<br> When se carga la página principal<br>    Then se muestra correctamente la página de inicio con las funcionalidades destacadas visibles.<br><br>
                <strong>Scenario 2: Acceso a funcionalidades desde el home</strong><br>
                Given el usuario está en la página de inicio<br>
                When hace clic en un botón de acceso rápido<br>
                Then es dirigido a la funcionalidad correspondiente sin errores.
            </td>
            <td>EPIC-03</td>
        </tr>
        <!-- User Story 11 -->
        <tr> 
            <td>US-11</td> 
            <td>Integración de Validadores en Formularios</td> 
            <td> 
                Como usuario, quiero que los formularios tengan validadores para asegurar que los datos ingresados sean correctos. 
            </td> 
            <td> 
                <strong>Scenario 1: Validación de campos obligatorios</strong><br> 
                Given el usuario está completando un formulario<br> 
                When deja un campo obligatorio vacío<br> 
                Then el sistema muestra un mensaje indicando que el campo debe completarse.<br><br>
                <strong>Scenario 2: Validación de formato de datos</strong><br>
                Given el usuario está ingresando datos<br>
                When introduce un formato inválido (por ejemplo, un correo incorrecto)<br>
                Then el sistema muestra un mensaje de error y no permite enviar el formulario hasta corregirlo.
            </td>
            <td>EPIC-03</td>
        </tr>
        <!-- User Story 12 -->
        <tr> 
            <td>US-12</td> 
            <td>Mejora de la Experiencia del Usuario</td> 
            <td> 
                Como usuario, quiero que la aplicación sea intuitiva y fácil de navegar para mejorar mi experiencia general. 
            </td> 
            <td> 
                <strong>Scenario 1: Interfaz clara y navegable</strong><br> 
                Given el usuario está usando la aplicación<br> 
                When navega por las distintas secciones<br> 
                Then puede entender fácilmente cómo utilizarla sin necesidad de ayuda adicional.<br><br>
                <strong>Scenario 2: Reducción de pasos innecesarios</strong><br>
                Given el usuario realiza una acción frecuente<br>
                When completa el flujo<br>
                Then la aplicación optimiza el número de pasos para completar la tarea de forma eficiente.
            </td>
            <td>EPIC-03</td>
        </tr>
        <!-- User Story 14 -->
        <tr> 
            <td>US-14</td> 
            <td>Implementación de Funcionalidad de Búsqueda</td> 
            <td> 
                Como usuario, quiero poder realizar búsquedas en la aplicación para encontrar rápidamente la información que necesito. 
            </td> 
            <td> 
                <strong>Scenario 1: Campo de búsqueda accesible</strong><br> 
                Given el usuario está en la app<br> 
                When necesita buscar información específica<br> 
                Then puede acceder fácilmente al campo de búsqueda en la interfaz.<br><br>
                <strong>Scenario 2: Resultados relevantes</strong><br>
                Given el usuario ingresa un término de búsqueda<br>
                When hace clic en buscar<br>
                Then el sistema muestra resultados relevantes y actualizados.<br><br>
                <strong>Scenario 3: Sin resultados</strong><br>
                Given el usuario realiza una búsqueda sin coincidencias<br>
                When no se encuentra información<br>
                Then el sistema muestra un mensaje indicando que no hay resultados disponibles.
            </td>
            <td>EPIC-03</td>
        </tr>
    </tbody>
</table>

## 3.3 Impact Mapping

![ToBe](/assets/img/chapter-III/RFIM.png)

## 3.4 Product Backlog

<table border="1">
  <thead>
    <tr>
      <th>Orden</th>
      <th>User Story Id</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>US-01</td>
      <td>Hipervínculos en el encabezado</td>
      <td>Como visitante de la landing page, quiero que las opciones del encabezado me dirijan a las diferentes secciones de la Landing Page para poder navegar de forma rápida y fluida.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>2</td>
      <td>US-02</td>
      <td>Información sobre beneficios de la aplicación</td>
      <td>Como usuario, quiero saber más sobre los beneficios de la aplicación web para considerar ser miembro de la aplicación.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>3</td>
      <td>US-03</td>
      <td>Información útil en el footer</td>
      <td>Como usuario, quiero que el footer contenga información útil, como datos de contacto y enlaces a políticas, para facilitar mi navegación.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>4</td>
      <td>US-05</td>
      <td>Registro del estado de clarificación</td>
      <td>Como usuario con rol de vinicultor, quiero registrar y actualizar los datos relacionados con la clarificación de mis lotes,para asegurarme de que los agentes clarificantes y las fechas del proceso se gestionen adecuadamente y queden registrados en el sistema.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US-06</td>
      <td>Registro del estado de prensado</td>
      <td>Como usuario con rol de vinicultor, quiero registrar el inicio, progreso y finalización del prensado de mis lotes,para controlar y documentar de manera precisa la cantidad de jugo extraído y los detalles del proceso.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>6</td>
      <td>US-08</td>
      <td>Resgistro del estado de embotellado</td>
      <td>Como usuario con rol de vinicultor, quiero registrar el inicio y finalización del proceso de embotellado, incluyendo la cantidad de botellas producidas, para asegurar que esta etapa esté bien documentada y se refleje correctamente en los registros del lote.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>7</td>
      <td>US-10</td>
      <td>Visualizar Home de la Plataforma</td>
      <td>Como usuario, quiero visualizar la página de inicio de la plataforma para acceder fácilmente a las principales funcionalidades.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>8</td>
      <td>US-04</td>
      <td>Registro del estado de fermentación</td>
      <td>Como usuario con rol de vinicultor,quiero registrar y monitorear el estado de la fermentación de mis lotes,para asegurar que las condiciones iniciales y los parámetros del proceso se controlen correctamente y queden documentados. </td>
      <td>5</td>
    </tr>
    <tr>
      <td>9</td>
      <td>US-07</td>
      <td>Registro del estado de añejamiento</td>
      <td>Como usuario con rol de vinicultor, quiero registrar las condiciones y fechas del añejamiento de mis vinos, para asegurar que el proceso se documente correctamente y monitorear la evolución del producto a lo largo del tiempo.
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>10</td>
      <td>US-11</td>
      <td>Integración de Validadores en Formularios</td>
      <td>Como usuario, quiero que los formularios tengan validadores para asegurar que los datos ingresados sean correctos.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>11</td>
      <td>US-12</td>
      <td>Mejora de la Experiencia del Usuario</td>
      <td>Como usuario, quiero que la aplicación sea intuitiva y fácil de navegar para mejorar mi experiencia general.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>12</td>
      <td>US-14</td>
      <td>Implementación de Funcionalidad de Búsqueda</td>
      <td>Como usuario, quiero poder realizar búsquedas en la aplicación para encontrar rápidamente la información que necesito.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>13</td>
      <td>US-09</td>
      <td>Reportes Personalizados</td>
      <td>Como vinicultor, quiero poder crear reportes personalizados para analizar datos específicos de producción. </td>
      <td>8</td>
    </tr>
  </tbody>
</table>
