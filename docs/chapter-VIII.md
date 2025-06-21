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
| **Hypothesis** | Creemos que el 70% de los productores artesanales están dispuestos a adoptar una solución digital que simplifique sus procesos, y que el 85% pueden usar efectivamente una interfaz intuitiva después de 2 horas de capacitación básica, ya que las entrevistas iniciales mostraron interés y los métodos actuales generan frustración por su ineficiencia. |

#### Experiment Card 2: Process Efficiency Impact

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Cómo impacta la implementación de EventWine en la eficiencia operativa y calidad del producto en cada etapa del proceso de vinificación comparado con métodos manuales? |
| **Why** | Para cuantificar el valor real que EventWine aporta a los productores y validar nuestras afirmaciones sobre mejora en eficiencia (25%) y reducción de errores (90%) para justificar la propuesta de valor. |
| **What** | Implementar EventWine en 10 bodegas piloto durante un ciclo completo de producción (3-6 meses), midiendo tiempo de gestión, errores de registro, y métricas de calidad vs grupo control usando métodos tradicionales. |
| **Hypothesis** | Creemos que EventWine reducirá el tiempo de gestión administrativa de 3-4 horas semanales a menos de 1 hora (75% reducción) y disminuirá errores de registro del 5% al 0.5% (90% reducción), ya que la automatización y validaciones del sistema eliminan procesos manuales propensos a error. |

#### Experiment Card 3: User Experience Optimization

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Cuál es la curva de aprendizaje real de productores con experiencia tecnológica limitada al usar EventWine y qué elementos de UX más contribuyen a una adopción exitosa? |
| **Why** | Para optimizar la interfaz y flujo de usuario específicamente para nuestro target (productores artesanales con experiencia tecnológica limitada) y minimizar barreras de adopción relacionadas con usabilidad. |
| **What** | Realizar sesiones de testing de usabilidad con 20 productores, medir tiempo de completar tareas clave, identificar puntos de fricción, y iterar el diseño basado en feedback directo durante 4 semanas. |
| **Hypothesis** | Creemos que los productores podrán completar tareas básicas (registrar lote, actualizar fermentación) en menos de 5 minutos después de 1 hora de capacitación, y que el 90% considerará la interfaz "fácil de usar" después de 1 semana de uso, ya que el diseño se enfoca en simplicidad y flujos familiares similar a aplicaciones que ya conocen. |

#### Experiment Card 4: Pricing Model Validation

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Qué modelo de pricing genera mayor adopción entre productores artesanales manteniendo unit economics positivos para EventWine? |
| **Why** | Para determinar la estrategia de monetización óptima que balancee accesibilidad para productores pequeños con viabilidad económica de EventWine, validando nuestra estrategia de pricing escalonado. |
| **What** | Testear 3 modelos de pricing diferentes (freemium vs suscripción fija vs pago por uso) con 60 productores divididos en grupos, midiendo conversion rate, retention y willingness to pay durante 3 meses. |
| **Hypothesis** | Creemos que el modelo de suscripción escalonada ($25 básico, $50 intermedio, $100 avanzado) generará un 40% de adoption rate en plan básico y 25% upgrade a planes premium, ya que permite acceso inicial a productores pequeños mientras captura mayor valor de operaciones más grandes. |

#### Experiment Card 5: Market Penetration Effectiveness

| **Campo** | **Contenido** |
|-----------|---------------|
| **Question** | ¿Cuáles son los canales de adquisición más efectivos para alcanzar y convertir productores artesanales en usuarios activos de EventWine? |
| **Why** | Para desarrollar una estrategia de go-to-market eficiente que minimice el CAC (Customer Acquisition Cost) y maximice la conversión de prospects a usuarios activos, especialmente considerando el target de productores artesanales. |
| **What** | Ejecutar campañas paralelas en 5 canales diferentes (referidos directos, asociaciones, eventos del sector, redes sociales, partnerships con proveedores) midiendo CAC, conversion rate y calidad de leads durante 6 meses. |
| **Hypothesis** | Creemos que las referencias directas de productores existentes generarán el menor CAC ($50 vs $150 promedio otros canales) y mayor LTV ($800+), mientras que partnerships con asociaciones de productores proporcionarán el mayor volumen de leads calificados, ya que este mercado valora altamente las recomendaciones peer-to-peer y la validación por autoridades del sector. |

___

## 8.2. Experiment Design
### 8.2.1. Hypotheses.
### 8.2.2. Measures.
### 8.2.3. Conditions.
### 8.2.4. Scale Calculations and Decisions.
### 8.2.5. Methods Selection.
### 8.2.6. Data Analytics: Goals, KPIs and Metrics Selection.
### 8.2.7. Web and Mobile Tracking Plan.
## 8.3. Experimentation


### 8.3.1. To-Be User Stories


| **Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|-------------|------------|----------------|----------------------------|-------------------------------|
| **US-14** | **Registro de múltiples fermentaciones por lote** | Como vinicultor, quiero registrar varias fermentaciones para un mismo lote cuando se usan distintos tanques. | **Escenario 1:** Agregar segunda fermentación.<br>Given un lote con fermentación ya registrada,<br>When hago clic en "Añadir fermentación",<br>Then el sistema permite ingresar nuevos datos.<br>**Escenario 2:** Límite de fermentaciones.<br>When intento agregar una tercera fermentación,<br>Then el sistema muestra alerta "Máximo 2 por lote". | EPIC-02 |
| **US-15** | **Editar clarificaciones registradas** | Como asistente, quiero corregir errores en los datos de clarificación antes de completar la etapa. | **Escenario 1:** Editar agente clarificante.<br>Given una clarificación no finalizada,<br>When cambio el tipo de agente,<br>Then el sistema actualiza el registro.<br>**Escenario 2:** Editar fecha inválida.<br>When ingreso una fecha futura,<br>Then el sistema muestra error. | EPIC-02 |
| **US-16** | **Ver historial completo de un lote** | Como productor, quiero ver todas las etapas de un lote (fermentación, prensado, etc.) en una sola pantalla. | **Escenario 1:** Visualizar resumen.<br>Given un lote completado,<br>When hago clic en "Ver historial",<br>Then el sistema muestra una línea de tiempo con todas las etapas.<br>**Escenario 2:** Lote incompleto.<br>When un lote está en progreso,<br>Then las etapas faltantes aparecen como "Pendientes". | EPIC-02 |
| **US-17** | **Exportar datos a Excel** | Como enólogo, quiero exportar los datos de fermentación y clarificación a Excel para análisis externo. | **Escenario 1:** Exportar lote específico.<br>Given un lote seleccionado,<br>When hago clic en "Exportar a Excel",<br>Then se descarga un archivo .xlsx con los datos.<br>**Escenario 2:** Exportar vacío.<br>When no hay datos registrados,<br>Then el Excel incluye solo los encabezados. | EPIC-02 |
| **US-18** | **Filtrar lotes por tipo de uva** | Como técnico, quiero filtrar los lotes por variedad de uva para comparar procesos. | **Escenario 1:** Filtrar por Malbec.<br>Given 10 lotes (3 de Malbec),<br>When aplico el filtro "Malbec",<br>Then solo muestran esos 3.<br>**Escenario 2:** Reiniciar filtros.<br>When hago clic en "Limpiar filtros",<br>Then se muestran todos los lotes. | EPIC-02 |

### 8.3.2. To-Be Product Backlog

| **Orden** | **User Story Id** | **Título** | **Descripción** | **Story Points** |
|-----------|------------------|------------|----------------|------------------|
| 1 | US-14 | Registro de múltiples fermentaciones | Permite agregar hasta 2 fermentaciones por lote. | 5 |
| 2 | US-15 | Editar clarificaciones | Corregir datos de clarificación antes de finalizar. | 3 |
| 3 | US-16 | Historial completo de lote | Muestra todas las etapas . | 8 |
| 4 | US-17 | Exportar a Excel | Genera archivos Excel por lote. | 5 |
| 5 | US-18 | Filtrar por tipo de uva | Filtrado básico por variedad de uva. | 3 |
| 6 | US-19 | Validación de fechas | Impide registrar fechas incoherentes (ej: embotellado antes de fermentación). | 5 |
| 8 | US-21 | Búsqueda por ID de lote | Buscar lotes ingresando su ID exacto. | 2 |
| 10 | US-23 | Notificaciones de etapas críticas | Alertas web cuando una etapa supera el tiempo estimado. | 8 |