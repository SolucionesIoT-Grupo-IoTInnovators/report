# Informe de Trabajo Final

**Universidad Peruana de Ciencias Aplicadas**  
**Ingenieria de Software**  
**Ciclo 07**  

**Código del curso:**  
**Desarrollo de Soluciones IOT**  
**NRC:**  

**Profesor: Velasquez Nuñez, Angel Augusto**

**Startup: IoT Innovators**  

**Producto: SmartParking**  

### Relación de integrantes

| Apellidos y Nombres                    | Código     |
| :------------------------------------: | :-------: |
| Arroyo Ormeño, André Alonso            | u202114714 |
| Castilla Pachas, César Antonio         | u202218735 |
| Cortés Casas, Joaquin Marcelo          | u202114545 |
| Diaz Silva, Fernando Josué            | u202112722 |
| Godoy, Johan Príncipe                  | u202014511 |
| Tafur Gonzales, Josty Gerardo          | u20201c069 |
| Zarate Caceres, Victor Ernesto        | u202112907 |


**Marzo, 2025**

## Registro de Versiones del Informe

## Contenido

**Tabla de contenidos**

- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - [4.1.1. EventStorming](#411-eventstorming)
      - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
      - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](#412-context-mapping)
    - [4.1.3. Software Architecture](#413-software-architecture)
      - [4.1.3.1. System Quality Attributes](#4131-system-quality-attributes)
      - [4.1.3.2. Architectural Design Backlog](#4132-architectural-design-backlog)
      - [4.1.3.3. Software Architecture System Landscape Diagram](#4133-software-architecture-system-landscape-diagram)
      - [4.1.3.4. Software Architecture Context Level Diagrams](#4134-software-architecture-context-level-diagrams)
      - [4.1.3.5. Software Architecture Container Level Diagrams](#4135-software-architecture-container-level-diagrams)
      - [4.1.3.6. Software Architecture Deployment Diagrams](#4136-software-architecture-deployment-diagrams)
  - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: <Bounded Context Name>](#42x-bounded-context-bounded-context-name)
      - [4.2.X.1. Domain Layer](#42x1-domain-layer)
      - [4.2.X.2. Interface Layer](#42x2-interface-layer)
      - [4.2.X.3. Application Layer](#42x3-application-layer)
      - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
      - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
      - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
      - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)

## Student Outcome

Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Capítulo I: Introducción

### 1.1. Startup Profile
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 1.1.1. Descripción de la Startup
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 1.1.2. Perfiles de integrantes del equipo
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 1.2. Solution Profile
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 1.2.1. Antecedentes y problemática
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 1.2.2. Lean UX Process
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 1.2.2.1. Lean UX Problem Statements
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 1.2.2.2. Lean UX Assumptions
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 1.2.2.3. Lean UX Hypothesis Statements
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 1.2.2.4. Lean UX Canvas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 1.3. Segmentos objetivo
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.1.1. Análisis competitivo
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.1.2. Estrategias y tácticas frente a competidores
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 2.2. Entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.1. Diseño de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.2. Registro de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.3. Análisis de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 2.3. Needfinding
En esta sección se presentarán los artefactos resultantes del proceso de análisis de la información recolectada de los segmentos objetivos. Aquí se incluyen secciones internas para User Personas, User Task Matrix, User Journey Maps, Empathy Mapping y As-Is Scenario Mapping.
#### 2.3.1. User Personas
En esta sección se presentarán las fichas de User Persona, las cuales son representaciones ficticias de los usuarios basadas en los hallazgos obtenidos a partir de las entrevistas realizadas. Estas fichas se centran en los segmentos objetivos identificados, incluyendo productores agrícolas y distribuidores. La elaboración de estas User Personas se fundamenta en el análisis de las características comunes y necesidades detectadas en las entrevistas, así como en la observación de la competencia. Al comprender mejor a nuestros usuarios, podremos diseñar soluciones más efectivas y alineadas con sus expectativas y desafíos, lo que resulta fundamental para el desarrollo de nuestra aplicación. Cada ficha incluirá detalles sobre las características demográficas, motivaciones, frustraciones y necesidades específicas de cada arquetipo, asegurando que nuestras decisiones de diseño se basen en información relevante y real.

**Segmento Propietario de Estacionamiento:** <br>
Alejandro Torres es un empresario peruano que administra varios estacionamientos en Perú. Con formación en administración de empresas y un perfil racional, Alejandro está constantemente buscando formas de mejorar la rentabilidad de su negocio. Su objetivo es aumentar la ocupación de sus espacios, reducir los tiempos en que sus estacionamientos están vacíos y ofrecer una experiencia más cómoda y eficiente para sus clientes. Aunque está abierto a la tecnología, solo invierte en herramientas que demuestren un impacto claro en la eficiencia operativa o el incremento de ingresos. Se siente frustrado por la falta de visibilidad en tiempo real sobre el comportamiento de sus usuarios y por la carga que implica la gestión manual de pagos y reservas.
![user persona de propietario de estacionamiento](chapterII-images/user%20persona-%20Propietario%20de%20estacionamiento.png)

**Segmento Conductor:** <br>
Diego Ramírez utiliza su vehículo diariamente para cumplir con una agenda exigente de reuniones y visitas a clientes. Aunque es una persona organizada y con buena planificación, uno de sus mayores desafíos diarios es encontrar estacionamiento en zonas de alta demanda, lo que le genera estrés y pérdida de tiempo. Interesado en la tecnología, Diego busca soluciones digitales que le permitan reservar espacios con anticipación, recibir alertas sobre disponibilidad y comparar precios en tiempo real. Su motivación principal es optimizar su tiempo y evitar contratiempos que afecten su productividad laboral. Se frustra al no tener visibilidad de los espacios disponibles y cuando los costos son altos o inesperados.
![user persona de conductor](chapterII-images/user%20persona%20-%20conductor.png)

#### 2.3.2. User Task Matrix

En esta sección se presenta el **User Task Matrix**, que concentra las tareas que los **User Personas** realizan para cumplir sus objetivos. Se consideran dos segmentos: **propietarios de estacionamiento** y **conductores**. Las tareas identificadas representan actividades que los usuarios deben realizar independientemente de la existencia de una solución de software.

| **Task**                                 | **Propietario de Estacionamiento** |                 | **Conductor**  |                 |
|------------------------------------------|------------------------------------|-----------------|----------------|-----------------|
|                                          | **Frecuencia**                     | **Importancia** | **Frecuencia** | **Importancia** |
| Establecer horarios y tarifas            | High                               | High            | -              | -               |
| Gestionar la disponibilidad del espacio  | High                               | High            | -              | -               |
| Supervisar ocupación del estacionamiento | Medium                             | High            | -              | -               |
| Cobrar o verificar pagos                 | High                               | High            | -              | -               |
| Coordinar con clientes                   | Medium                             | Medium          | Medium         | Medium          |
| Buscar estacionamiento                   | -                                  | -               | High           | High            |
| Evaluar seguridad del lugar              | -                                  | -               | High           | High            |
| Comparar precios y distancias            | -                                  | -               | High           | Medium          |
| Reservar espacio de estacionamiento      | -                                  | -               | High           | High            |
| Verificar disponibilidad en tiempo real  | -                                  | -               | High           | High            |
| Gestionar historial de reservas/pagos    | Medium                             | Medium          | Medium         | Medium          |

### Explicación

Al analizar las tareas de los segmentos de **propietarios de estacionamiento** y **conductores**, se observan diferencias claras en los objetivos y responsabilidades, así como algunas coincidencias importantes.

#### Tareas con Mayor Frecuencia e Importancia

1. **Establecer horarios y tarifas** (propietarios): Es esencial para gestionar correctamente su espacio y maximizar ingresos. Tiene alta frecuencia, especialmente si los precios varían según el día o la demanda.

2. **Gestionar disponibilidad del espacio** (propietarios): Es una tarea clave que impacta directamente en la operación eficiente del estacionamiento.

3. **Buscar estacionamiento**, **reservar espacio** y **verificar disponibilidad en tiempo real** (conductores): Estas tareas son el núcleo de la experiencia del conductor, siendo realizadas de manera constante para resolver su necesidad inmediata.

4. **Evaluar seguridad del lugar** (conductores): La percepción de seguridad influye fuertemente en la elección del estacionamiento.

#### Principales Diferencias

- Los **propietarios** están enfocados en la **gestión operativa y financiera** del estacionamiento (tarifas, disponibilidad, pagos).
- Los **conductores** están enfocados en **localizar, evaluar y asegurar** su experiencia al aparcar.

#### Coincidencias

Ambos perfiles realizan la tarea de **coordinar con clientes** (por ejemplo, para resolver inconvenientes o dar indicaciones) y **gestionar historial** (sea de pagos o reservas), lo cual resalta una necesidad compartida de trazabilidad y buena comunicación.

Estas diferencias y coincidencias subrayan la necesidad de una solución que contemple tanto la eficiencia operativa para los propietarios como la conveniencia y seguridad para los conductores.

#### 2.3.3. User Journey Mapping

La sección de User Journey Maps muestra el recorrido completo de los usuarios de la app de parking, desde que conocen por primera vez la solución hasta el momento en que la dejan de utilizar. El mapeo evidencia las acciones, metas, emociones y problemas experimentados por los dos segmentos clave: propietarios de estacionamiento y conductores. Además, se identifican oportunidades de mejora que pueden guiar el desarrollo de nuevas funcionalidades o ajustes en la experiencia del usuario.

Para los **Propietarios de Estacionamiento**, el journey inicia cuando descubren la app como una forma de rentabilizar espacios disponibles. A lo largo del proceso, sus emociones evolucionan desde la curiosidad hasta la confianza, aunque pueden experimentar frustraciones relacionadas con la gestión de clientes o la flexibilidad del servicio. Las oportunidades incluyen mejoras en la personalización, asistencia en la fijación de precios y funciones de pausa del servicio.

**Segmento Propietario de Estacionamiento:**

<img src="https://github.com/SolucionesIoT-Grupo-IoTInnovators/report/blob/165729b4a8060773766191d14f61a13c0b8669df/ChapterII-images/user_journey_mapping_owner.png?raw=true" alt="Segmento Propietario de Estacionamiento">


El journey de los **Conductores** comienza al descubrir la app como una solución rápida y confiable para encontrar estacionamiento. A medida que la utilizan, pasan de la expectativa inicial al alivio de evitar pérdidas de tiempo, aunque también pueden encontrar frustraciones si la información está desactualizada o el proceso no es fluido. Las oportunidades detectadas incluyen mejoras en la verificación de parqueos, soporte activo, y opciones para personalizar la experiencia.

**Segmento Conductor:**

<img src="https://github.com/SolucionesIoT-Grupo-IoTInnovators/report/blob/165729b4a8060773766191d14f61a13c0b8669df/ChapterII-images/user_journey_mapping_conductor.png?raw=true" alt="Segmento Conductor">

#### 2.3.4. Empathy Mapping
En esta sección se presentan los Empathy Maps para cada User Persona, que ayudan a entender sus experiencias y emociones. Se colocó al User Persona en el centro y se recolectaron observaciones del equipo sobre lo que necesita hacer, dice y siente. También se identificaron sus preocupaciones y cómo nuestra solución puede ayudar. A continuación, se incluyen las capturas de los Empathy Maps realizados.

**Segmento Propietario de Estacionamiento:** <br>
Alejandro Torres es propietario de varios estacionamientos en la ciudad y busca maximizar la rentabilidad de su negocio. Aunque tiene experiencia en gestión, enfrenta desafíos como baja ocupación en horarios específicos y la falta de datos sobre el comportamiento de los clientes. Le interesa implementar herramientas tecnológicas que le permitan automatizar reservas y pagos, así como obtener reportes detallados que le ayuden a tomar mejores decisiones. Su principal frustración es la dificultad de administrar los espacios de manera eficiente sin una plataforma digital que optimice la operación. Su objetivo es mejorar la ocupación de sus estacionamientos, aumentar sus ingresos y ofrecer una mejor experiencia a sus clientes.
![emphaty mapping de propietario de estacionamiento](chapterII-images/emphaty%20map%20-%20propietario%20de%20estacionamiento.png)

**Segmento Conductor:** <br>
Diego Ramírez utiliza su vehículo diariamente para moverse por la ciudad y asistir a reuniones. Su apretada agenda hace que encontrar estacionamiento sea un problema frecuente, especialmente en zonas de alta demanda. Se frustra al perder tiempo buscando un espacio disponible, enfrentarse a tarifas imprevistas o no tener información en tiempo real sobre la disponibilidad. Como usuario de tecnología, busca soluciones que optimicen su tiempo y le brinden mayor comodidad, como aplicaciones móviles que le permitan reservar espacios con antelación y recibir notificaciones sobre estacionamientos cercanos y sus costos. Su objetivo principal es reducir el estrés de encontrar estacionamiento y asegurarse de que su vehículo esté seguro mientras realiza su trabajo.
![emphaty mapping de conductor](chapterII-images/emphaty%20map%20-%20conductor.png)

**Proceso de Elaboración** <br>
1. **Preparación y Enfoque en el User Persona** <br>
Cada mapa comenzó con la identificación del User Persona en el centro:
   - **Alejandro Torres**: Propietario de varios estacionamientos en Santiago, busca optimizar la ocupación de sus espacios y mejorar la rentabilidad de su negocio mediante herramientas digitales.
   - **Diego Ramírez**: Persona que usa su vehículo diariamente y enfrenta dificultades para encontrar estacionamiento de manera rápida y eficiente.
    

2. **Captura de Observaciones**:  
   Para cada User Persona, se recopilaron observaciones del equipo en las secciones del Empathy Map:

    - **¿Con quién estamos empatizando?**:  
       - **Alejandro Torres**: Un empresario que administra estacionamientos y busca mejorar la eficiencia y rentabilidad de su negocio.
        - **Diego Ramírez**: Un conductor que necesita estacionar rápidamente en zonas de alta demanda y evitar pérdidas de tiempo en su rutina diaria.

    - **¿Qué necesitan hacer?**:
        - **Alejandro Torres**
          - Aumentar la ocupación de su estacionamiento y optimizar la gestión de espacios.
          - Obtener reportes y métricas sobre la demanda de estacionamientos.
          - Automatizar reservas y pagos para mejorar la experiencia del cliente.
        - **Diego Ramírez**
          - Encontrar estacionamiento de manera rápida y sin estrés.
          - Reservar espacios con antelación en zonas concurridas.
          - Recibir información en tiempo real sobre disponibilidad y precios.

    - **¿Qué están viendo?**:
        - **Alejandro Torres**
          - Estacionamientos vacíos en horarios específicos.
          - Competencia implementando nuevas tecnologías para atraer clientes.
          - Dificultades en la gestión manual de pagos y espacios.
        - **Diego Ramírez**
          - Falta de espacios disponibles en zonas comerciales.
          - Precios elevados y cambios inesperados en las tarifas.
          - Conductores compitiendo por los mismos espacios.

    - **¿Qué están escuchando?**:
        - **Alejandro Torres**
          - Sugerencias de su equipo sobre cómo mejorar la ocupación.
          - Comentarios de clientes que buscan mayor comodidad y eficiencia.
          - Información sobre tendencias en gestión de estacionamientos.
        - **Diego Ramírez**
          - Opiniones de otros conductores sobre la falta de estacionamientos.
          - Recomendaciones de apps y herramientas para facilitar el proceso.
          - Quejas sobre la seguridad en algunos estacionamientos.

    - **¿Qué están diciendo?**:
        - **Alejandro Torres**
          - "Necesito una mejor manera de gestionar mis estacionamientos."
          - "Es difícil predecir la demanda sin datos claros."
          - "Automatizar pagos y reservas me ahorraría muchos problemas."
        - **Diego Ramírez**
          - "Perder tiempo buscando estacionamiento es frustrante."
          - "Sería ideal poder reservar con anticipación."
          - "No quiero pagar más de la cuenta sin previo aviso."

    - **¿Qué están haciendo?**:
        - **Alejandro Torres**
          - Analizando la ocupación de su estacionamiento y ajustando tarifas.
          - Supervisando la operación y gestionando pagos manualmente.
          - Evaluando herramientas digitales para mejorar la eficiencia.
        - **Diego Ramírez**
          - "Perder tiempo buscando estacionamiento es frustrante."
          - "Sería ideal poder reservar con anticipación."
          - "No quiero pagar más de la cuenta sin previo aviso."

    - **¿Cómo se sienten y qué piensan?**:
       - **Alejandro Torres**
          - Siente presión por aumentar la rentabilidad de su negocio.
          - Está interesado en nuevas herramientas, pero solo si generan beneficios reales.
          - Quiere reducir la carga operativa y mejorar la experiencia de sus clientes.
        - **Diego Ramírez**
          - Se siente estresado cuando no encuentra estacionamiento a tiempo.
          - Siente frustración por la falta de información clara y actualizada.
          - Quiere soluciones tecnológicas que faciliten su día a día.

    - **Gains**:
       - **Alejandro Torres**
          - Incremento en la ocupación y rentabilidad de su estacionamiento.
          - Optimización del negocio con reportes y análisis de datos.
          - Automatización de procesos para mejorar la eficiencia operativa.
        - **Diego Ramírez**
          - Ahorro de tiempo y reducción del estrés diario.
          - Mayor seguridad y comodidad al estacionar.
          - Capacidad de planificar mejor su día sin preocuparse por el estacionamiento.

    - **Pains**:
       - **Alejandro Torres**
          - Baja ocupación en ciertos horarios y días.
          - Falta de datos para mejorar la toma de decisiones.
          - Complejidad en la gestión manual de pagos y reservas.
        - **Diego Ramírez**
          - Pérdida de tiempo buscando estacionamiento.
          - Falta de información en tiempo real sobre precios y disponibilidad.
          - Riesgo de multas o retrasos por no encontrar espacio a tiempo.

Estos Empathy Maps proporcionan una visión clara de las necesidades y desafíos de los usuarios, ayudando a desarrollar soluciones alineadas con sus expectativas y mejorando la experiencia en la gestión y búsqueda de estacionamientos.

#### 2.3.5. As-is Scenario Mapping
**Segmento Propietario de Estacionamiento:** <br>
![emphaty mapping de propietario de estacionamiento](chapterII-images/As%20is%20Scenario%20Mapping-propietario%20de%20estacionamiento.jpg)
- **Positive points**:
  - **Cobra en efectivo o por app según el cliente:** Ofrece flexibilidad de pago, lo que facilita la experiencia del cliente.
  - **Verifica ingresos y ocupación del día:** Tiene una visión general del negocio, lo que le permite tomar decisiones con cierta base.
- **Negative points**:
  - **Revisa manualmente el estado del estacionamiento:** No cuenta con automatización para visualizar ocupación en tiempo real.
  - **Asigna espacios manualmente:** Esto genera errores, ineficiencia y pérdida de tiempo, especialmente en horas pico.
  - **Registra datos en Excel al final del día:** La falta de digitalización completa limita su capacidad para analizar tendencias en tiempo real.
- **Blank points**:
  - **Espero que hoy tengamos buena ocupación:** Es necesario entender cómo planifica la ocupación diaria y qué variables usa para proyectar la demanda.
  - **Espero que todos paguen sin problemas:** Habría que analizar qué porcentaje de clientes usa efectivo vs. apps, y si esto genera problemas operativos.
  - **Podría ganar más si tuviera más reservas anticipadas:** Es importante investigar si Alejandro está dispuesto a adoptar un sistema de reservas online y qué barreras percibe.

**Segmento Conductor:** <br>
![emphaty mapping de propietario de estacionamiento](chapterII-images/As%20is%20Scenario%20Mapping-conductor.jpg)
- **Positive points**:
  - **Usa apps como Google Maps o Waze para planear su ruta:** Diego confía en la tecnología para planificar sus trayectos, lo que le permite evitar zonas con tráfico y llegar más rápido a sus destinos.
- **Negative points**:
  - **Sale con tiempo ajustado para reuniones:** Suele estar apurado, lo que le genera estrés adicional si no encuentra estacionamiento a tiempo.
  - **Recorre varias calles buscando espacio libre:** La falta de información sobre disponibilidad en tiempo real le obliga a dar vueltas innecesarias.
  - **Encuentra espacio con costo inesperado:** Se siente frustrado cuando estaciona y se entera del precio al final, sin poder comparar previamente.
  - **Camina desde el lugar donde estacionó:** Aunque esto es normal, a veces debe caminar más de lo deseado o se siente inseguro por el lugar.
- **Blank points**:
  - **¿Habrá estacionamiento disponible cuando llegue?:** Se requiere entender mejor cómo los conductores manejan la incertidumbre de disponibilidad al momento de planear su viaje.
  - **Ojalá no me multen o remolquen:** Hay que investigar si los usuarios verifican la legalidad del lugar donde estacionan o si simplemente arriesgan por falta de tiempo o información.

### 2.4. Ubiquitous Language
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping
En esta sección se presentan los To-Be Scenario Mapping para cada segmento objetivo donde se reflejarán, a partir de los As-is Scenario Mapping, la experiencia de usuario ideal si se resuelven los puntos de dolor y necesidades. La herramienta empleada para su desarrollo ha sido Miro.

**Segmento Propietario de Estacionamiento:** <br>
![emphaty mapping de propietario de estacionamiento](chapterII-images/To-be%20Scenario%20Mapping-propietario%20de%20estacionamiento.jpg)

**Cambios Claves**
  - Eliminación del registro manual gracias a paneles automáticos y visualización en tiempo real.
  - Disminuye la carga operativa y aumenta la eficiencia, lo que permite dedicar más tiempo a la estrategia.
  - Acceso a datos analíticos facilita la toma de decisiones y mejora la rentabilidad.

**Segmento Conductor:** <br>
![emphaty mapping de propietario de estacionamiento](chapterII-images/To-be%20Scenario%20Mapping-conductor.jpg)

**Cambios Claves**
  - La incertidumbre por la disponibilidad y precios desaparece gracias a la reserva previa y visibilidad en tiempo real.
  - Se eliminan las vueltas innecesarias y el estrés por llegar tarde.
  - Mejora la confianza y seguridad, tanto en el trayecto como en el uso del espacio reservado.

### 3.2. User Stories
<div align="justify">
  <table>
    <tr>
      <td>Epic / Story ID</td>
      <td>Título</td>
      <td>Descripción</td>
      <td>Criterios de Aceptación</td>
      <td>Relacionado con (Epic ID)</td>
    </tr>
    <!--Epicas-->
    <tr>
      <td>EP01</td>
      <td>Disponibilidad en Tiempo Real</td>
      <td>Implementar la integración de sensores IoT que detecten en tiempo real la disponibilidad de espacios en el estacionamiento, de modo que los conductores puedan ver en la app información actualizada al instante.</td>
      <td>
        Scenario: Ver espacios de estacionamiento disponibles en tiempo real<br>
        Given que el usuario ha iniciado sesión en la aplicación móvil<br>
        When accede al mapa de estacionamientos<br>
        Then podrá ver los espacios disponibles actualizados automáticamente cada 30 segundos<br><br>
        Scenario: Manejo de error en sensores IoT<br>
        Given que un sensor deja de enviar datos válidos<br>
        When el sistema detecta la falla<br>
        Then el espacio asociado se mostrará como no disponible o marcado con una alerta
      </td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP02</td>
      <td>Sistema de Reserva y Pago Automatizado</td>
      <td>Desarrollar un sistema integral que permita a los conductores reservar un espacio de estacionamiento y procesar el pago de forma automatizada, ofreciendo una experiencia fluida y sin fricciones.</td>
      <td>
        Scenario: Reservar un espacio de estacionamiento<br>
        Given que el conductor visualiza un espacio disponible<br>
        When selecciona el espacio y presiona “Reservar”<br>
        Then el sistema deberá bloquear el espacio para ese usuario<br><br>
        Scenario: Confirmación de pago exitoso<br>
        Given que el usuario ha reservado un espacio<br>
        When realiza el pago mediante la aplicación<br>
        Then se le mostrará una confirmación y recibirá una notificación con los detalles<br><br>
        Scenario: Ver detalle de reserva<br>
        Given que el usuario tiene una reserva activa<br>
        When accede a la sección “Mis reservas”<br>
        Then verá la ubicación, tiempo y código del espacio asignado
      </td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP03</td>
      <td>Panel de Gestión para Propietarios</td>
      <td>Crear una plataforma web para los propietarios de estacionamientos que permita gestionar la ocupación, automatizar pagos y acceder a análisis y reportes en tiempo real para optimizar la administración y maximizar ingresos.</td>
      <td>
        Scenario: Ver estadísticas de ocupación en el dashboard<br>
        Given que el propietario ha iniciado sesión en la plataforma web<br>
        When accede a la sección de estadísticas<br>
        Then visualizará información en tiempo real sobre ocupación y tarifas<br><br>
        Scenario: Generar reportes de uso y rentabilidad<br>
        Given que el propietario necesita un resumen de uso<br>
        When presiona “Generar reporte” en el panel de control<br>
        Then podrá descargar el archivo en formato PDF o Excel<br><br>
        Scenario: Notificación ante baja ocupación<br>
        Given que la ocupación cae por debajo del 20%<br>
        When el sistema detecta este evento<br>
        Then el propietario recibe una alerta por email o en el panel
      </td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP04</td>
      <td>Integración y Confiabilidad del Sistema IoT</td>
      <td>Garantizar una integración robusta y confiable de los dispositivos IoT en el estacionamiento, con un sistema de monitoreo que minimice errores y garantice la exactitud de los datos transmitidos.</td>
      <td>
        Scenario: Transmisión de datos de sensores IoT<br>
        Given que los sensores están instalados y operativos<br>
        When detectan la entrada o salida de un vehículo<br>
        Then el sistema actualiza el estado del espacio en menos de 5 segundos<br><br>
        Scenario: Manejo de errores del sensor<br>
        Given que un sensor presenta fallas<br>
        When no responde por más de 1 minuto<br>
        Then el sistema lo marca como inactivo y genera una alerta al administrador<br><br>
        Scenario: Mantenimiento remoto de sensores<br>
        Given que un administrador desea actualizar el firmware<br>
        When accede al módulo de mantenimiento<br>
        Then podrá iniciar la actualización de los sensores remotamente
      </td>
      <td>-</td>
    </tr>
    <tr>
      <td>EP05</td>
      <td>Estrategia de Adopción y Crecimiento Orgánico</td>
      <td>Diseñar e implementar funcionalidades que mejoren la experiencia del usuario, fomenten el boca a boca y aseguren la adopción de la plataforma tanto por conductores como por propietarios, impulsando el crecimiento orgánico.</td>
      <td>
        Scenario: Registro de usuarios por recomendación<br>
        Given que un nuevo usuario descarga la app desde un enlace de invitación<br>
        When completa el registro<br>
        Then el sistema lo clasifica como adquisición por referencia<br><br>
        Scenario: Medir satisfacción del usuario<br>
        Given que el usuario ha utilizado la app por más de una semana<br>
        When se le envía una encuesta de satisfacción<br>
        Then debe completarla y el sistema almacenará la puntuación<br><br>
        Scenario: Incentivo por recomendación<br>
        Given que un usuario refiere a un nuevo usuario<br>
        When este se registre y realice una primera reserva<br>
        Then el usuario original recibe una recompensa en su cuenta
      </td>
      <td>-</td>
    </tr>
    <!--User Stories-->
    <tr>
      <td>US01</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US02</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US03</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US04</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US05</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US06</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US07</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US08</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US09</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US10</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US10</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US11</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US12</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US13</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US14</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US15</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US16</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US17</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US18</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US19</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US20</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US21</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US22</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US23</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US24</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>US25</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TS01</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TS02</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TS03</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TS04</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TS05</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </table>
</div>

### 3.3. Impact Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 3.4. Product Backlog
<div align="justify">
  <table>
    <tr>
      <td># Orden</td>
      <td>User Story Id</td>
      <td>Título</td>
      <td>Descripción</td>
      <td>Story Points (1 / 2 / 3 / 5 / 8)</td>
    </tr>
    <tr>
      <td>US</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>TS</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </table>
</div>

## Capítulo IV: Solution Software Design
### 4.1. Strategic-Level Domain-Driven Design
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 4.1.1. EventStorming
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.1.1. Candidate Context Discovery
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.1.2. Domain Message Flows Modeling
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.1.3. Bounded Context Canvases
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 4.1.2. Context Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 4.1.3. Software Architecture
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.3.1. System Quality Attributes
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.3.2. Architectural Design Backlog
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.3.3. Software Architecture System Landscape Diagram
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.3.4. Software Architecture Context Level Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.3.5. Software Architecture Container Level Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.1.3.6. Software Architecture Deployment Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 4.2. Tactical-Level Domain-Driven Design
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 4.2.X. Bounded Context: <Bounded Context Name>
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.X.1. Domain Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.X.2. Interface Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.X.3. Application Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.X.4. Infrastructure Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

###### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

###### 4.2.X.6.2. Bounded Context Database Design Diagram
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Conclusiones

### Conclusiones y recomendaciones
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### Video About-the-Team
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Bibliografia
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Anexos
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.