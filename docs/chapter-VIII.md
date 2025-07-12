# Chapter VIII : Experiment-Driven Development
## 8.1. Experiment Planning
### 8.1.1. As-Is Summary
#### Estado Actual del Sector Vitivinícola
El sector de producción vitivinícola y de pisco presenta una fragmentación significativa en la gestión de procesos productivos. Los productores artesanales y de pequeña escala enfrentan desafíos considerables en la coordinación eficiente de las distintas etapas de vinificación: fermentación, clarificación, prensado, añejamiento y embotellado.

#### Problemática Identificada

**Pain Points Principales:**
- **Gestión fragmentada**: Los productores utilizan métodos manuales dispersos (Excel, cuadernos, registros físicos) que no ofrecen integración entre etapas del proceso
- **Falta de trazabilidad**: Ausencia de visibilidad en tiempo real sobre el estado de cada lote en el proceso productivo
- **Errores en registros manuales**: Alta probabilidad de errores humanos que afectan la calidad y consistencia del producto final
- **Ineficiencia operativa**: Procesos descoordinados que generan pérdidas de tiempo, recursos y oportunidades de optimización
- **Limitada capacidad de análisis**: Dificultad para generar reportes y tomar decisiones basadas en datos históricos del proceso

#### Actores del Ecosistema Actual

**Productores de Vino (Segmento Principal):**
- Vinicultores artesanales con operaciones pequeñas a medianas
- Productores familiares con tradición de 20-50 años en el sector
- Asistentes de bodega que gestionan operaciones diarias
- Técnicos especializados en enología y control de calidad

#### Métodos Actuales de Gestión

Según las entrevistas realizadas, los productores actualmente:
- Utilizan Excel para registros de inventario y control básico
- Mantienen cuadernos físicos para anotaciones de campo
- Gestionan manualmente las cuentas y seguimiento de procesos
- Carecen de integración entre las diferentes etapas productivas
- Dependen de memoria y experiencia para toma de decisiones críticas

---

### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

#### Top 5 Assumptions (Supuestos Clave)

* **A1:** Los productores artesanales de vino están dispuestos a adoptar una solución digital integral que centralice la gestión de todas las etapas de vinificación, reemplazando sus métodos manuales actuales (Excel y cuadernos).

* **A2:** La implementación de herramientas de monitoreo en tiempo real para fermentación, clarificación, prensado, añejamiento y embotellado mejorará la calidad del producto final en un 20% y reducirá problemas operativos en un 15%.

* **A3:** Un sistema de trazabilidad completa desde el lote de uva hasta el embotellado aumentará la confianza del productor y mejorará la precisión del control de stock en un 30%, reduciendo incidencias por desabastecimiento en un 25%.

* **A4:** Una interfaz intuitiva y accesible específicamente diseñada para productores con experiencia tecnológica limitada reducirá la curva de aprendizaje y las consultas de soporte en un 20%, aumentando la adopción activa en un 15%.

* **A5:** El modelo de suscripción escalonado (Básico, Intermedio, Avanzado) permitirá que al menos el 30% de los productores adopten planes premium, generando ingresos recurrentes sostenibles para EventWine.

#### Top 5 Knowledge Gaps (Brechas de Conocimiento)

* **KG1:** ¿Cuál es la disposición real de pago de los productores artesanales por una solución digital, considerando sus márgenes operativos y presupuestos tecnológicos actuales?

* **KG2:** ¿Qué nivel de conectividad a internet y infraestructura tecnológica tienen los productores en zonas rurales como Lunahuaná, y cómo esto afecta la adopción de una plataforma cloud?

* **KG3:** ¿Cuánto tiempo requiere realmente un productor artesanal para completar cada etapa del proceso de vinificación, y cómo esto impacta en la frecuencia de uso de la plataforma?

* **KG4:** ¿Qué regulaciones específicas existen en Perú para el registro digital de procesos vitivinícolas y cómo pueden afectar los requerimientos funcionales de EventWine?

* **KG5:** ¿Cuál es la tasa de rotación de personal en bodegas artesanales y cómo esto influye en la necesidad de capacitación continua y simplicidad de la interfaz?

#### Top 5 Ideas (Oportunidades de Innovación)

* **I1:** Aplicación móvil híbrida (Android/iOS) que permita a los trabajadores de campo registrar datos directamente desde el viñedo y la bodega, sincronizando automáticamente con la plataforma web.

* **I2:** Sistema de alertas inteligentes basado en parámetros críticos (temperatura de fermentación, tiempos de clarificación, densidad) que notifique proactivamente cuando se requiera intervención.

* **I3:** Módulo de reportes automáticos que genere documentación completa del lote al finalizar el embotellado, facilitando la trazabilidad y certificación del producto.

* **I4:** Integration con sensores IoT de bajo costo para monitoreo automático de temperatura, humedad y otros parámetros críticos durante fermentación y añejamiento.

* **I5:** Marketplace interno donde productores puedan compartir mejores prácticas, recetas de vinificación y conectarse con proveedores de insumos especializados.

#### Top 5 Claims (Afirmaciones a Validar)

* **C1:** "EventWine reducirá el tiempo de gestión administrativa de procesos de vinificación de 3-4 horas semanales a menos de 1 hora, permitiendo que los productores se enfoquen más en la calidad del producto."

* **C2:** "Los productores que implementen EventWine experimentarán una reducción del 90% en errores de registro (de 5% actual a 0.5%) y una mejora del 25% en eficiencia operativa durante el primer año de uso."

* **C3:** "La plataforma alcanzará una tasa de retención del 85% entre productores artesanales después de 6 meses de uso, debido a la mejora tangible en control de calidad y trazabilidad."

* **C4:** "EventWine será adoptado por al menos 100 productores en la región de Lima (Lunahuaná, Cañete) durante los primeros 18 meses, capturando el 15% del mercado local de productores artesanales."

* **C5:** "El costo de adquisición de clientes (CAC) será inferior a $150 USD por productor, con un lifetime value (LTV) de al menos $800 USD, generando un ratio LTV/CAC de 5:1 sostenible."

---

### 8.1.3. Experiment-Ready Questions

| **Question** | **Confidence** | **Risk** | **Impact** | **Interest** | **Total Score** |
|--------------|----------------|----------|------------|--------------|-----------------|
| ¿Adoptarán los productores artesanales EventWine reemplazando sus métodos manuales actuales (Excel, cuadernos) por una plataforma digital integral? | 6 - Tenemos entrevistas iniciales positivas, pero necesitamos validar adopción real a escala. | 4 - Riesgo alto de resistencia al cambio en productores tradicionales. | 8 - Fundamental para viabilidad del negocio y propuesta de valor central. | 7 - Crítico para entender nuestro mercado objetivo y estrategia de producto. | **25** |
| ¿Mejorará EventWine la eficiencia operativa y calidad del producto en cada etapa de vinificación vs métodos manuales? | 7 - La lógica es sólida, pero necesitamos métricas cuantificables reales. | 3 - Riesgo bajo, es mejora técnica clara sobre procesos manuales. | 9 - Impacto directo en ROI del cliente y justificación del pricing. | 8 - Esencial para validar nuestras claims de valor y diferenciación. | **27** |
| ¿Podrán productores con experiencia tecnológica limitada usar EventWine efectivamente con mínima capacitación? | 5 - Diseño intuitivo planificado, pero sin testing real con usuarios target. | 5 - Riesgo alto si UX no es suficientemente simple para adoptantes tardíos. | 7 - Afecta adoption rate y customer satisfaction significativamente. | 6 - Importante para diseño de onboarding y soporte al cliente. | **23** |
| ¿Qué modelo de pricing (básico $25, intermedio $50, premium $100) optimiza adopción y revenue para EventWine? | 4 - Pricing basado en competencia, sin validación de willingness to pay real. | 6 - Riesgo alto de pricing incorrecto afecta unit economics y adopción. | 8 - Determinante para sustainability financiera y growth strategy. | 7 - Crítico para go-to-market strategy y investor attractiveness. | **25** |
| ¿Cuáles canales de adquisición (referidos, asociaciones, eventos) son más efectivos para reach productores artesanales? | 3 - Conocimiento limitado del buyer journey en este segmento específico. | 4 - Riesgo medio de CAC alto si elegimos canales incorrectos. | 6 - Impacta efficiency de marketing spend y growth rate. | 5 - Necesario para scaling strategy pero no bloquea MVP launch. | **18** |

---

### 8.1.4. Question Backlog

| **Prioridad (1,2,3,5,8)** | **Pregunta** |
|---------------------------|--------------|
| **1** | ¿Adoptarán los productores artesanales EventWine reemplazando sus métodos manuales actuales (Excel, cuadernos) por una plataforma digital integral? |
| **1** | ¿Mejorará EventWine la eficiencia operativa y calidad del producto en cada etapa de vinificación vs métodos manuales? |
| **2** | ¿Podrán productores con experiencia tecnológica limitada usar EventWine efectivamente con mínima capacitación? |
| **2** | ¿Qué modelo de pricing (básico $25, intermedio $50, premium $100) optimiza adopción y revenue para EventWine? |
| **3** | ¿Cuáles canales de adquisición (referidos, asociaciones, eventos) son más efectivos para reach productores artesanales? |

---

### 8.1.5. Experiment Cards

#### Experiment Card 1: Technology Adoption Readiness

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿En qué medida los productores artesanales de vino están preparados tecnológicamente y dispuestos a migrar de sus métodos actuales a una plataforma digital integral? |
| **Why** | Para validar si existe receptividad real hacia la digitalización entre nuestro target market y identificar barreras específicas de adopción tecnológica que debemos abordar en el diseño del producto. |
| **What** | Realizar entrevistas en profundidad con 30 productores artesanales, análisis de su infraestructura tecnológica actual, y pruebas de usabilidad con prototipos de EventWine durante 2 semanas. |
| **Hypothesis** | **Creemos que** al menos el 70% de los productores artesanales encuestados indicarán, mediante pregunta cerrada antes y después del piloto, estar dispuestos a migrar a una plataforma digital, y que al menos el 85% podrán completar tareas básicas (como registrar un lote o actualizar fermentación) en menos de 5 minutos tras una capacitación de 2 horas, **ya que** las entrevistas iniciales revelaron frustración con los métodos actuales y apertura a soluciones tecnológicas más simples.|

#### Experiment Card 2: Process Efficiency Impact

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Cómo impacta la implementación de EventWine en la eficiencia operativa y calidad del producto en cada etapa del proceso de vinificación comparado con métodos manuales? |
| **Why** | Para cuantificar el valor real que EventWine aporta a los productores y validar nuestras afirmaciones sobre mejora en eficiencia (25%) y reducción de errores (90%) para justificar la propuesta de valor. |
| **What** | Implementar EventWine en 10 bodegas piloto durante un ciclo completo de producción (3-6 meses), midiendo tiempo de gestión, errores de registro, y métricas de calidad vs grupo control usando métodos tradicionales. |
| **Hypothesis** | **Creemos que** EventWine reducirá en al menos un 75% el tiempo total de gestión administrativa, medido por la suma de los tiempos cronometrados por etapa (registro de lote, verificación, embotellado, etc.), **ya que** el sistema automatiza procesos repetitivos que actualmente se realizan de forma manual y dispersa en planillas o cuadernos.|

#### Experiment Card 3: User Experience Optimization

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Cuál es la curva de aprendizaje real de productores con experiencia tecnológica limitada al usar EventWine y qué elementos de UX más contribuyen a una adopción exitosa? |
| **Why** | Para optimizar la interfaz y flujo de usuario específicamente para nuestro target (productores artesanales con experiencia tecnológica limitada) y minimizar barreras de adopción relacionadas con usabilidad. |
| **What** | Realizar sesiones de testing de usabilidad con 20 productores, medir tiempo de completar tareas clave, identificar puntos de fricción, y iterar el diseño basado en feedback directo durante 4 semanas. |
| **Hypothesis** | **Creemos que** al menos el 90% de los productores con experiencia tecnológica limitada calificarán la interfaz como “fácil de usar” (escala Likert 4 o 5) luego de una semana de uso, y podrán completar al menos 3 tareas clave (registrar lote, actualizar fermentación, emitir reporte) en menos de 5 minutos cada una tras una capacitación de 1 hora, **ya que** el diseño de EventWine está basado en principios de simplicidad y patrones visuales similares a aplicaciones conocidas por el usuario.|

#### Experiment Card 4: Pricing Model Validation

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Qué modelo de pricing genera mayor adopción entre productores artesanales manteniendo unit economics positivos para EventWine? |
| **Why** | Para determinar la estrategia de monetización óptima que balancee accesibilidad para productores pequeños con viabilidad económica de EventWine, validando nuestra estrategia de pricing escalonado. |
| **What** | Testear 3 modelos de pricing diferentes (freemium vs suscripción fija vs pago por uso) con 60 productores divididos en grupos, midiendo conversion rate, retention y willingness to pay durante 3 meses. |
| **Hypothesis** | **Creemos que** el modelo de suscripción escalonada ($25 básico, $50 intermedio, $100 avanzado) generará al menos un 40% de adopción en el plan básico y un 25% de upgrade a planes premium, **ya que** permite a productores pequeños iniciar con una inversión accesible mientras que aquellos con mayor volumen perciben valor en las funciones avanzadas, según validaciones previas y disposición de pago reportada.|

#### Experiment Card 5: Market Penetration Effectiveness

| **Campo** | **Contenido**                                                                                                                                                                                                                        |
|-----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Question** | ¿Cuáles son los canales de adquisición más efectivos para alcanzar y convertir productores artesanales en usuarios activos de EventWine?                                                                                             |
| **Why** | Para desarrollar una estrategia de go-to-market eficiente que minimice el CAC (Customer Acquisition Cost) y maximice la conversión de prospects a usuarios activos, especialmente considerando el target de productores artesanales. |
| **What** | Ejecutar campañas paralelas en 5 canales diferentes (referidos directos, asociaciones, eventos del sector, redes sociales, partnerships con proveedores) midiendo CAC, conversion rate y calidad de leads durante 6 meses.           |
| **Hypothesis** | **Creemos que** las referencias directas de productores existentes generarán un CAC al menos 30% menor que el promedio de otros canales y un LTV superior al 25%, **ya que** los productores artesanales valoran las recomendaciones de pares y la validación por asociaciones del sector, lo cual influye directamente en su decisión de adopción de tecnología.|

___

## 8.2. Experiment Design
### 8.2.1. Hypotheses.


| Campo | Hipótesis |
|-------|-----------|
| **Question** | ¿En qué medida los productores artesanales de vino están preparados tecnológicamente y dispuestos a migrar de sus métodos actuales a una plataforma digital integral? |
| **Belief** | Los productores artesanales muestran interés en la digitalización debido a la frustración con la ineficiencia de sus métodos actuales, y pueden adaptarse a interfaces intuitivas con capacitación básica. |
| **Hypothesis** | **Creemos que** al menos el 70% de los productores artesanales encuestados indicarán, mediante pregunta cerrada antes y después del piloto, estar dispuestos a migrar a una plataforma digital, y que al menos el 85% podrán completar tareas básicas (como registrar un lote o actualizar fermentación) en menos de 5 minutos tras una capacitación de 2 horas, **ya que** las entrevistas iniciales revelaron frustración con los métodos actuales y apertura a soluciones tecnológicas más simples.|
| **Null Hypothesis** | Menos del 50% de los productores artesanales encuestados estarán dispuestos a adoptar una plataforma digital, y menos del 60% podrán completar tareas clave en la plataforma (registrar lote, actualizar fermentación) en menos de 5 minutos, incluso después de una capacitación de 2 horas.|




| Campo | Hipótesis |
|-------|-----------|
| **Question** | ¿Cómo impacta la implementación de EventWine en la eficiencia operativa y calidad del producto en cada etapa del proceso de vinificación comparado con métodos manuales? |
| **Belief** | La automatización y validaciones del sistema EventWine eliminan procesos manuales propensos a error, generando mejoras significativas en eficiencia y reducción de errores. |
| **Hypothesis** | **Creemos que** EventWine reducirá en al menos un 75% el tiempo total de gestión administrativa, medido por la suma de los tiempos cronometrados por etapa (registro de lote, verificación, embotellado, etc.), **ya que** el sistema automatiza procesos repetitivos que actualmente se realizan de forma manual y dispersa en planillas o cuadernos.|
| **Null Hypothesis** | La implementación de EventWine no reducirá el tiempo total de gestión administrativa en más del 25%, y la disminución en errores de registro será menor al 30% comparado con los métodos manuales.|




| Campo | Hipótesis |
|-------|-----------|
| **Question** | ¿Cuál es la curva de aprendizaje real de productores con experiencia tecnológica limitada al usar EventWine y qué elementos de UX más contribuyen a una adopción exitosa? |
| **Belief** | El diseño enfocado en simplicidad y flujos familiares, similar a aplicaciones conocidas, facilitará la adopción por parte de usuarios con experiencia tecnológica limitada. |
| **Hypothesis** | **Creemos que** al menos el 90% de los productores con experiencia tecnológica limitada calificarán la interfaz como “fácil de usar” (escala Likert 4 o 5) luego de una semana de uso, y podrán completar al menos 3 tareas clave (registrar lote, actualizar fermentación, emitir reporte) en menos de 5 minutos cada una tras una capacitación de 1 hora, **ya que** el diseño de EventWine está basado en principios de simplicidad y patrones visuales similares a aplicaciones conocidas por el usuario.|
| **Null Hypothesis** | Menos del 60% de los usuarios calificarán la plataforma como “fácil de usar” (escala Likert 4 o 5) después de una semana de uso, y más del 40% tardarán más de 10 minutos en completar tareas básicas, incluso después de una hora de capacitación.|




| Campo | Hipótesis |
|-------|-----------|
| **Question** | ¿Qué modelo de pricing genera mayor adopción entre productores artesanales manteniendo unit economics positivos para EventWine? |
| **Belief** | Un modelo de suscripción escalonada permite acceso inicial a productores pequeños mientras captura mayor valor de operaciones más grandes, optimizando adopción y rentabilidad. |
| **Hypothesis** | **Creemos que** el modelo de suscripción escalonada ($25 básico, $50 intermedio, $100 avanzado) generará al menos un 40% de adopción en el plan básico y un 25% de upgrade a planes premium, **ya que** permite a productores pequeños iniciar con una inversión accesible mientras que aquellos con mayor volumen perciben valor en las funciones avanzadas, según validaciones previas y disposición de pago reportada.|
| **Null Hypothesis** | El modelo de suscripción escalonada no generará una tasa de adopción superior al 20% en el plan básico ni más del 10% de upgrades a planes premium, durante el periodo de validación.|




| Campo | Hipótesis |
|-------|-----------|
| **Question** | ¿Cuáles son los canales de adquisición más efectivos para alcanzar y convertir productores artesanales en usuarios activos de EventWine? |
| **Belief** | Los productores artesanales valoran altamente las recomendaciones peer-to-peer y la validación por autoridades del sector, haciendo que referencias y partnerships sean más efectivos. |
| **Hypothesis** | **Creemos que** las referencias directas de productores existentes generarán un CAC al menos 30% menor que el promedio de otros canales y un LTV superior al 25%, **ya que** los productores artesanales valoran las recomendaciones de pares y la validación por asociaciones del sector, lo cual influye directamente en su decisión de adopción de tecnología.|
| **Null Hypothesis** | No habrá diferencias significativas en el CAC entre canales (variación menor al 10%), y las referencias directas no generarán un LTV superior al 10% comparado con otros canales como redes sociales o eventos.|

### 8.2.2. Measures.


| Campo | Contenido |
|-------|-----------|
| **Question** | ¿En qué medida los productores artesanales de vino están preparados tecnológicamente y dispuestos a migrar de sus métodos actuales a una plataforma digital integral? |
| **Measure** | Medir el nivel de preparación tecnológica mediante encuestas de infraestructura actual, análisis de herramientas digitales utilizadas, y evaluación de disposición al cambio a través de entrevistas estructuradas. Complementar con pruebas de usabilidad cronometradas para evaluar capacidad de adopción efectiva de la plataforma. |


| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Cómo impacta la implementación de EventWine en la eficiencia operativa y calidad del producto en cada etapa del proceso de vinificación comparado con métodos manuales? |
| **Measure** | Medir tiempo de gestión administrativa semanal antes y después de implementar EventWine, registrar número de errores en el proceso de vinificación, y evaluar métricas de calidad del producto mediante análisis comparativo entre grupo experimental y grupo control durante un ciclo completo de producción. |


| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Cuál es la curva de aprendizaje real de productores con experiencia tecnológica limitada al usar EventWine y qué elementos de UX más contribuyen a una adopción exitosa? |
| **Measure** | Medir el tiempo requerido para completar tareas específicas (registrar lote, actualizar fermentación) mediante sesiones de testing cronometradas, evaluar satisfacción de usabilidad con escalas de valoración, y identificar puntos de fricción a través de análisis de interacciones y feedback cualitativo durante sesiones de uso real. |


| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Qué modelo de pricing genera mayor adopción entre productores artesanales manteniendo unit economics positivos para EventWine? |
| **Measure** | Medir tasas de conversión para cada modelo de pricing (freemium, suscripción fija, pago por uso), evaluar retención de usuarios por plan, analizar willingness to pay mediante encuestas de precio, y calcular métricas de unit economics (CAC, LTV, churn rate) para cada segmento de pricing durante el período de prueba. |


| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Cuáles son los canales de adquisición más efectivos para alcanzar y convertir productores artesanales en usuarios activos de EventWine? |
| **Measure** | Medir el CAC (Customer Acquisition Cost) por canal de adquisición, evaluar conversion rate de leads a usuarios activos, analizar calidad de leads mediante scoring de engagement y retention, y calcular LTV (Lifetime Value) para usuarios adquiridos por cada canal durante un período de 6 meses de campañas paralelas. |

### 8.2.3. Conditions.


| Campo | Contenido |
|-------|-----------|
| **Question** | ¿En qué medida los productores artesanales de vino están preparados tecnológicamente y dispuestos a migrar de sus métodos actuales a una plataforma digital integral? |
| **Measure** | Medir el nivel de preparación tecnológica mediante encuestas de infraestructura actual, análisis de herramientas digitales utilizadas, y evaluación de disposición al cambio a través de entrevistas estructuradas. Complementar con pruebas de usabilidad cronometradas para evaluar capacidad de adopción efectiva de la plataforma. |



| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Cómo impacta la implementación de EventWine en la eficiencia operativa y calidad del producto en cada etapa del proceso de vinificación comparado con métodos manuales? |
| **Measure** | Medir tiempo de gestión administrativa semanal antes y después de implementar EventWine, registrar número de errores en el proceso de vinificación, y evaluar métricas de calidad del producto mediante análisis comparativo entre grupo experimental y grupo control durante un ciclo completo de producción. |



| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Cuál es la curva de aprendizaje real de productores con experiencia tecnológica limitada al usar EventWine y qué elementos de UX más contribuyen a una adopción exitosa? |
| **Measure** | Medir el tiempo requerido para completar tareas específicas (registrar lote, actualizar fermentación) mediante sesiones de testing cronometradas, evaluar satisfacción de usabilidad con escalas de valoración, y identificar puntos de fricción a través de análisis de interacciones y feedback cualitativo durante sesiones de uso real. |



| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Qué modelo de pricing genera mayor adopción entre productores artesanales manteniendo unit economics positivos para EventWine? |
| **Measure** | Medir tasas de conversión para cada modelo de pricing (freemium, suscripción fija, pago por uso), evaluar retención de usuarios por plan, analizar willingness to pay mediante encuestas de precio, y calcular métricas de unit economics (CAC, LTV, churn rate) para cada segmento de pricing durante el período de prueba. |



| Campo | Contenido |
|-------|-----------|
| **Question** | ¿Cuáles son los canales de adquisición más efectivos para alcanzar y convertir productores artesanales en usuarios activos de EventWine? |
| **Measure** | Medir el CAC (Customer Acquisition Cost) por canal de adquisición, evaluar conversion rate de leads a usuarios activos, analizar calidad de leads mediante scoring de engagement y retention, y calcular LTV (Lifetime Value) para usuarios adquiridos por cada canal durante un período de 6 meses de campañas paralelas. |

### 8.2.4. Scale Calculations and Decisions.

Se utiliza un enfoque basado en métricas para validar nuestras hipótesis de producto de forma rigurosa y alineada con el comportamiento real de los usuarios. Cada hipótesis se vincula a una métrica clave que nos permite medir su impacto. Si el resultado alcanza el valor objetivo, consideramos que la hipótesis se cumple de forma óptima. Si el resultado se encuentra entre un mínimo aceptable y el ideal, lo evaluamos como satisfactorio, pero sujeto a posibles ajustes. En cambio, si el desempeño queda por debajo del umbral mínimo, interpretamos que la hipótesis no se valida y es necesario replantearla.

Adicionalmente, cuando una métrica supera el objetivo previsto en un 25% o más, lo consideramos un éxito sobresaliente, que puede señalar oportunidades no previstas para potenciar el producto. Este enfoque nos permite tomar decisiones basadas en datos concretos, ajustando o reforzando nuestras estrategias de desarrollo, especialmente en áreas críticas como la captación de productores artesanales, la fidelización de asistentes a eventos y la mejora de la experiencia general en la plataforma.

## Tabla de Scale Calculations y Decisiones

| Scale Calculation                                                                                                                                                                                                                                                                                                                                                                                                 | Decision                                                                                                                                                                                       | Factor                                                |               |           |               |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|---------------|-----------|---------------|
|                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                                                                                                                                                                | **Desfavorable**                                      | **Aceptable** | **Ideal** | **Excelente** |
| **Creemos que** realizar focus group con productores y pruebas de usabilidad con productores artesanales **causará** una validación clara de su disposición tecnológica y capacidad de adopción de EventWine. **Sabremos que esto es cierto cuando** observemos que al menos el 70% muestra disposición a adoptar la plataforma y el 85% puede usar efectivamente la interfaz después de 2 horas de capacitación. | Implementar un programa de capacitación tecnológica escalonado que permita a los productores adaptarse gradualmente a la plataforma digital, mejorando así la comodidad y confianza en el uso. | < 50% disposición y < 60% efectividad                 | x             |           |               |
| **Creemos que** implementar EventWine en bodegas piloto durante un ciclo completo de producción **causará** mejoras significativas en eficiencia operativa y reducción de errores comparado con métodos manuales. **Sabremos que esto es cierto cuando** observemos una reducción del 75% en tiempo de gestión administrativa y del 90% en errores de registro.                                                   | Desarrollar un sistema de automatización integral que optimice los procesos de vinificación, reduciendo la carga administrativa y minimizando errores humanos en el registro de datos.         | < 25% reducción tiempo y < 30% reducción errores      | x             |           |               |
| **Creemos que** optimizar la interfaz y flujo de usuario específicamente para productores con experiencia tecnológica limitada **causará** una curva de aprendizaje acelerada y alta satisfacción de usabilidad. **Sabremos que esto es cierto cuando** los productores completen tareas básicas en menos de 5 minutos después de 1 hora de capacitación y el 90% considere la interfaz fácil de usar.            | Implementar un diseño de UX intuitivo con elementos familiares y flujos simplificados que faciliten la adopción por parte de usuarios con experiencia tecnológica limitada.                    | > 10 minutos para tareas básicas y < 60% satisfacción |               |           | x             |
| **Creemos que** implementar un modelo de suscripción escalonada ($25, $50, $100) **causará** mayor adopción entre productores artesanales manteniendo unit economics positivos. **Sabremos que esto es cierto cuando** logremos un 40% de adoption rate en plan básico y 25% de upgrade a planes premium.                                                                                                         | Establecer una estrategia de pricing diferenciada que balancee accesibilidad para productores pequeños con captura de valor de operaciones más grandes, optimizando la penetración de mercado. | < 20% adoption básico y < 10% upgrade premium         |               |           | x             |
| **Creemos que** ejecutar campañas de adquisición enfocadas en referencias directas y partnerships con asociaciones **causará** menor CAC y mayor LTV comparado con otros canales. **Sabremos que esto es cierto cuando** las referencias generen CAC de $50 vs $150 promedio y LTV de $800+, mientras partnerships proporcionen el mayor volumen de leads calificados.                                            | Desarrollar una estrategia de go-to-market centrada en referencias peer-to-peer y validación por autoridades del sector, aprovechando la confianza inherente en estas relaciones comerciales.  | CAC > $150 y LTV < $400                               | x             |           |               |


### 8.2.5. Methods Selection.


Al momento de elegir la escala para los experimentos de EventWine, se ajustará el nivel de significancia estadística al 5% estándar para minimizar los errores atribuibles al azar. Se determinará el efecto mínimo detectable (MDE) para establecer la magnitud de la diferencia que debe identificarse en cada métrica. Se seleccionará un nivel de potencia estadística del 80-95% para reducir la probabilidad de errores Tipo II. Finalmente, se utilizarán datos representativos de productores artesanales para asegurar que los hallazgos sean aplicables al target market.

**Considerando los factores identificados en Scale Calculations**, donde se esperan resultados desfavorables en adopción tecnológica y eficiencia operativa, aceptables en penetración de mercado, y excelentes en UX y pricing, la selección de herramientas debe priorizarse según la criticidad de cada experimento.

| Herramienta               | Selenium                                                                                                                                                                     | Survey Analytics                                                                                                                             | RedLine13 - AWS                                                                                      | Financial Analytics                                                                                                                  |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|
| **Precio**                | Open source gratuito, costos de infraestructura para ejecución                                                                                                               | Herramientas gratuitas (Google Forms) y premium (Typeform $25/mes)                                                                           | Gratuito con limitaciones, planes basados en uso de AWS                                              | Plan gratuito, herramientas especializadas desde $100/mes                                                                            |
| **Capacidad de Análisis** | Automatización de pruebas funcionales, validación de workflows críticos y testing de regresión para verificar funcionalidades de EventWine                                   | Análisis descriptivo e inferencial de respuestas, segmentación demográfica y correlaciones                                                   | Análisis orientado a pruebas de carga y rendimiento de aplicaciones bajo condiciones de tráfico real | Análisis financiero exhaustivo de CAC, LTV, churn rate y unit economics                                                              |
| **Sencillez**             | Requiere conocimientos técnicos para scripting y configuración, pero altamente flexible                                                                                      | Interface intuitiva, fácil creación de encuestas y análisis automático                                                                       | Información detallada y resumida sobre rendimiento de la plataforma                                  | Requiere configuración de tracking financiero y métricas personalizadas                                                              |
| **Ventajas**              | Esencial para validar automáticamente funcionalidades clave que impactan adopción tecnológica y eficiencia operativa. Permite testing continuo de workflows de vinificación  | Fundamental para entender factores desfavorables en disposición tecnológica y optimizar elementos que ya muestran potencial excelente (UX)   | Validar escalabilidad técnica cuando otros experimentos alcancen niveles aceptables o superiores     | Optimizar elementos excelentes (pricing) y mejorar factores aceptables (penetración de mercado) mediante análisis de ROI detallado   |


### 8.2.6. Data Analytics: Goals, KPIs and Metrics Selection.
Se llevaron a cabo pruebas de rendimiento, accesibilidad y mejores prácticas con Lighthouse en nuestra 
aplicación EventWine para evaluar su desempeño y optimizar la experiencia de usuario. 

![1](/assets/img/chapter-VIII/l1.png)

![2](/assets/img/chapter-VIII/l2.png)

![3](/assets/img/chapter-VIII/l3.png)

![4](/assets/img/chapter-VIII/l4.png)

![5](/assets/img/chapter-VIII/l5.png)

![6](/assets/img/chapter-VIII/l6.png)

### 8.2.7. Web and Mobile Tracking Plan.
Para EventWine, nuestro objetivo es optimizar y monitorear tanto la aplicación web como la futura versión móvil, con el fin de facilitar la gestión operativa de los productores de vino y mejorar su experiencia dentro de la plataforma. A medida que avancemos hacia las etapas finales del desarrollo, estableceremos un plan de seguimiento riguroso que nos permitirá evaluar de forma efectiva las mejoras implementadas.

**Etapas de Monitoreo de Funcionalidades**<br>
1. Implementación Inicial
Durante esta fase, nos enfocaremos en el despliegue de nuevas funcionalidades, así como en la recopilación de datos iniciales que sirvan como línea base para futuras comparaciones.

**Recopilación de Datos:**

- Métricas de Uso: Se registrarán indicadores clave como el número de usuarios activos, duración promedio de sesiones, uso de formularios y frecuencia de exportación de datos (por ejemplo, a Excel).

- Interacciones de los Usuarios: Se recopilará información sobre el comportamiento de los usuarios, como clics en botones de guardado, navegación por las etapas del proceso productivo y acciones críticas como eliminación de registros.

- Feedback de Usuarios: A través de encuestas breves y herramientas de retroalimentación dentro de la plataforma, se recogerán opiniones relacionadas a la usabilidad, claridad del diseño y satisfacción general con las nuevas funcionalidades.

**Análisis Comparativo:**

Los datos recopilados durante esta etapa se contrastarán con registros anteriores a las actualizaciones, para evaluar el impacto directo de las mejoras implementadas.

2. Seguimiento Continuo
Tras la implementación inicial, se establecerá un sistema continuo de seguimiento para evaluar el rendimiento de la plataforma y realizar ajustes evolutivos según sea necesario.

**Recopilación de Datos:**

- Métricas en Tiempo Real: Se emplearán herramientas de análisis web para monitorear el uso en tiempo real y detectar rápidamente cualquier problema de usabilidad o cuellos de botella.

- Segmentación de Usuarios: La actividad será segmentada por tipo de usuario (por ejemplo, productores principiantes vs. expertos), para identificar necesidades específicas y optimizar la experiencia de cada perfil.

- Tasa de Retención: Se analizará cuántos usuarios regresan a la plataforma después de su primer uso, y si las nuevas funcionalidades influyen positivamente en el compromiso a largo plazo.

**Evaluación y Ajustes:**

- Informes Periódicos: Se elaborarán informes mensuales que resuman el comportamiento del usuario, problemas detectados y oportunidades de mejora.

- Iteración Basada en Datos: Las decisiones sobre rediseño o ajustes funcionales se basarán directamente en los datos recopilados y en la retroalimentación de los usuarios, garantizando que EventWine evolucione de forma centrada en el usuario.

Este enfoque permitirá que EventWine continúe mejorando de manera continua, basada en datos objetivos y necesidades reales del usuario, asegurando así una plataforma robusta, funcional y alineada con las expectativas del sector vitivinícola.

## 8.3. Experimentation


### 8.3.1. To-Be User Stories


| **Story ID**   | **Título**                                        | **Descripción**                                                                                              | **Criterios de Aceptación**                                                                                                                                                                                                                                                                                                                          | **Relacionado con (Epic ID)**   |
|----------------|---------------------------------------------------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|
| **US-14**      | **Registro de múltiples fermentaciones por lote** | Como vinicultor, quiero registrar varias fermentaciones para un mismo lote cuando se usan distintos tanques. | **Escenario 1:** Agregar segunda fermentación.<br>Given un lote con fermentación ya registrada,<br>When hago clic en "Añadir fermentación",<br>Then el sistema permite ingresar nuevos datos.<br>**Escenario 2:** Límite de fermentaciones.<br>When intento agregar una tercera fermentación,<br>Then el sistema muestra alerta "Máximo 2 por lote". | EPIC-02                         |
| **US-15**      | **Editar clarificaciones registradas**            | Como asistente, quiero corregir errores en los datos de clarificación antes de completar la etapa.           | **Escenario 1:** Editar agente clarificante.<br>Given una clarificación no finalizada,<br>When cambio el tipo de agente,<br>Then el sistema actualiza el registro.<br>**Escenario 2:** Editar fecha inválida.<br>When ingreso una fecha futura,<br>Then el sistema muestra error.                                                                    | EPIC-02                         |
| **US-16**      | **Ver historial completo de un lote**             | Como productor, quiero ver todas las etapas de un lote (fermentación, prensado, etc.) en una sola pantalla.  | **Escenario 1:** Visualizar resumen.<br>Given un lote completado,<br>When hago clic en "Ver historial",<br>Then el sistema muestra una línea de tiempo con todas las etapas.<br>**Escenario 2:** Lote incompleto.<br>When un lote está en progreso,<br>Then las etapas faltantes aparecen como "Pendientes".                                         | EPIC-02                         |
| **US-17**      | **Exportar datos a Excel**                        | Como enólogo, quiero exportar los datos de fermentación y clarificación a Excel para análisis externo.       | **Escenario 1:** Exportar lote específico.<br>Given un lote seleccionado,<br>When hago clic en "Exportar a Excel",<br>Then se descarga un archivo .xlsx con los datos.<br>**Escenario 2:** Exportar vacío.<br>When no hay datos registrados,<br>Then el Excel incluye solo los encabezados.                                                          | EPIC-02                         |
| **US-18**      | **Filtrar lotes por tipo de uva**                 | Como técnico, quiero filtrar los lotes por variedad de uva para comparar procesos.                           | **Escenario 1:** Filtrar por Malbec.<br>Given 10 lotes (3 de Malbec),<br>When aplico el filtro "Malbec",<br>Then solo muestran esos 3.<br>**Escenario 2:** Reiniciar filtros.<br>When hago clic en "Limpiar filtros",<br>Then se muestran todos los lotes.                                                                                           | EPIC-02                         |

### 8.3.2. To-Be Product Backlog

| **Orden**   | **User Story Id**  | **Título**                           | **Descripción**                                                               | **Story Points**   |
|-------------|--------------------|--------------------------------------|-------------------------------------------------------------------------------|--------------------|
| 1           | US-14              | Registro de múltiples fermentaciones | Permite agregar hasta 2 fermentaciones por lote.                              | 5                  |
| 2           | US-15              | Editar clarificaciones               | Corregir datos de clarificación antes de finalizar.                           | 3                  |
| 3           | US-16              | Historial completo de lote           | Muestra todas las etapas .                                                    | 8                  |
| 4           | US-17              | Exportar a Excel                     | Genera archivos Excel por lote.                                               | 5                  |
| 5           | US-18              | Filtrar por tipo de uva              | Filtrado básico por variedad de uva.                                          | 3                  |
| 6           | US-19              | Validación de fechas                 | Impide registrar fechas incoherentes (ej: embotellado antes de fermentación). | 5                  |
| 8           | US-21              | Búsqueda por ID de lote              | Buscar lotes ingresando su ID exacto.                                         | 2                  |
| 10          | US-23              | Notificaciones de etapas críticas    | Alertas web cuando una etapa supera el tiempo estimado.                       | 8                  |

### 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle
#### 8.3.3.1. To-Be Sprint Backlogs
#### 8.3.3.2. Implemented To-Be Landing Page Evidence
#### 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence
#### 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence
#### 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence
#### 8.3.3.6. Team Collaboration Insights
### 8.3.4. To-Be Validation Interviews
#### 8.3.4.1. Diseño de Entrevistas.
#### 8.3.4.2. Registro de Entrevistas.
## 8.4. Experiment Aftermath & Analysis
### 8.4.1. Analysis and Interpretation of Results
### 8.4.2. Re-scored and Re-prioritized Question Backlog
## 8.5. Continuous Learning
### 8.5.1. Shareback Session Artifacts: Learning Workflow
## 8.6. To-Be Software Platform Pre-launch
### 8.6.1. About-the-Product Intro Video