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
Nuestros competidores principales seran los siguientes:

<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <td><strong>iPark</strong><br>
      link: <a href="https://ipark.pe/propuesta/">https://ipark.pe/</a>
    </td>
    <td>
      iPark es una plataforma digital orientada a la gestión de estacionamientos. Ofrece soluciones como pago con QR, cámaras ANPR, app móvil para conductores y un panel administrativo para los operadores. Su enfoque está en la automatización y maximización de ingresos.
    </td>
  </tr>
  <tr>
    <td><strong>ACCIST Perú</strong><br>
      link: <a href="https://accistperu.com/">https://accistperu.com/</a>
    </td>
    <td>
      ACCIST es una empresa especializada en control de asistencia y acceso. Ofrece soluciones biométricas, molinetes y otros dispositivos de seguridad, que aunque no están centrados en estacionamientos, pueden competir indirectamente en espacios como edificios o universidades.
    </td>
  </tr>
  <tr>
    <td><strong>Smelpro</strong><br>
      link: <a href="https://smelpro.com/">https://smelpro.com/</a>
    </td>
    <td>
      Smelpro desarrolla soluciones tecnológicas basadas en IoT e inteligencia artificial para monitoreo en tiempo real. Aunque no enfocado exclusivamente en estacionamientos, sus productos pueden adaptarse a este sector, compitiendo en innovación e integración tecnológica.
    </td>
  </tr>
</table>

#### 2.1.1. Análisis competitivo
<table border="1" cellspacing="0" cellpadding="6">
  <!-- Título -->
  <tr>
    <th colspan="6" align="left">Competitive Analysis Landscape</th>
  </tr>

  <!-- Propósito del análisis -->
  <tr>
    <td rowspan="2"><strong>¿Por qué llevar a cabo este análisis?</strong></td>
    <td colspan="5">Para entender el panorama competitivo actual, descubrir oportunidades de mercado y tomar decisiones informadas sobre producto, marketing y crecimiento.</td>
  </tr>
  <tr></tr>

  <!-- Cabecera de competidores -->
<tr>
  <td colspan="2"><strong>Competidores</strong></td>
  <td>
    <img src="https://sdmntpreastus2.oaiusercontent.com/files/00000000-8a80-51f6-90a0-88e7b552b64a/raw?se=2025-04-03T03%3A15%3A57Z&sp=r&sv=2024-08-04&sr=b&scid=16ed7b95-5ee5-51b0-97e1-0155b3ce15f7&skoid=ac1d63ad-0c69-4017-8785-7a50eb04382c&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-04-02T16%3A06%3A22Z&ske=2025-04-03T16%3A06%3A22Z&sks=b&skv=2024-08-04&sig=F4HIgtzY80Y1lvuyIhq6i/9qMNyLcWF8/Z0Z3hG%2B1bk%3D" alt="SmartParking Logo" width="80"><br>
    <strong>SmartParking</strong><br>
  </td>
  <td>
    <img src="https://ipark.pe/wp-content/uploads/2024/01/Posts-IG-iPark-2-1024x1024.png" alt="iPark Logo" width="80"><br>
    <strong>iPark</strong><br>
  </td>
  <td>
    <img src="https://th.bing.com/th/id/OIP.Lhn3-9yGaWYE_WCI6tqPiQHaHa?rs=1&pid=ImgDetMain" alt="ACCIST Logo" width="80"><br>
    <strong>ACCIST</strong><br>
  </td>
  <td>
    <img src="https://yt3.googleusercontent.com/ytc/AIdro_kLh8cpQNXdQhBhVEFgyBsQ7zg5aU5he9wf69N9wtVyfw=s900-c-k-c0x00ffffff-no-rj" alt="Smelpro Logo" width="80"><br>
    <strong>Smelpro</strong><br>
  </td>
</tr>



  <!-- Overview -->
  <tr>
    <td rowspan="1"><strong>Perfil</strong></td>
    <td>Overview</td>
    <td>SmartParking es una plataforma inteligente que conecta conductores con estacionamientos disponibles mediante una app móvil, y brinda a propietarios herramientas web para gestionar, analizar y monetizar sus espacios de forma eficiente.</td>
    <td>Sistema digital para gestión de estacionamientos en la nube con app móvil, QR y panel de administración.</td>
    <td>Empresa peruana con más de 20 años en soluciones de asistencia, control de acceso y seguridad electrónica.</td>
    <td>Empresa tecnológica enfocada en soluciones IoT, IA e Industria 4.0 para sectores como energía, agua, agricultura y logística.</td>
  </tr>

  <!-- Perfil de Marketing -->
  <tr>
    <td rowspan="3"><strong>Perfil de Marketing</strong></td>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td>Acceso en tiempo real a disponibilidad, precios dinámicos y reserva desde app móvil; más analítica avanzada para propietarios.</td>
    <td>Optimiza ingresos y eficiencia en la operación de estacionamientos con sistemas inteligentes.</td>
    <td>Soluciones personalizadas en control de acceso, asistencia y seguridad para empresas de distintos tamaños.</td>
    <td>Soluciones integrales de monitoreo y control en tiempo real con conectividad inalámbrica y plataformas propias.</td>
  </tr>
  <tr>
    <td>Mercado objetivo</td>
    <td>Conductores urbanos que buscan estacionamiento optimizado y propietarios de estacionamientos en zonas de alta rotación.</td>
    <td>Empresas que administran estacionamientos públicos o privados.</td>
    <td>Instituciones, empresas privadas, entidades educativas y de salud que necesiten controlar accesos y personal.</td>
    <td>Industria, agricultura, transporte, energía y empresas que requieren automatización y sensores inteligentes.</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>Alianzas con comercios, integración con apps de navegación, descuentos promocionales y campañas digitales geolocalizadas.</td>
    <td>Modelo SaaS escalable, con soporte técnico incluido y enfoque en retorno de inversión.</td>
    <td>Relaciones comerciales directas, demostraciones personalizadas y atención postventa.</td>
    <td>Casos de éxito, enfoque consultivo, propuesta a medida y acompañamiento técnico completo.</td>
  </tr>

  <!-- Perfil de Producto -->
  <tr>
    <td rowspan="3"><strong>Perfil de Producto</strong></td>
    <td>Productos & Servicios</td>
    <td>App móvil para búsqueda y reserva; panel web de gestión; sensores IoT; reportes analíticos; alertas dinámicas.</td>
    <td>App móvil, pagos QR, cámaras ANPR, kioscos de pago, dashboard online.</td>
    <td>Controles biométricos, molinetes, cámaras, sistemas de asistencia, impresoras de fotochecks.</td>
    <td>Diseño electrónico, impresión 3D, software embebido, dashboards, sensores, redes LoRa/IoT.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Modelo SaaS mensual o anual para propietarios; venta de hardware IoT por unidad; planes freemium para conductores.</td>
    <td>Planes desde $150 a $650 mensuales según cantidad de transacciones.</td>
    <td>Precios varían según personalización, productos a medida.</td>
    <td>Costos según proyecto; soluciones completamente adaptadas.</td>
  </tr>
  <tr>
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td>App móvil, portal web, atención en línea, redes sociales y soporte técnico remoto.</td>
    <td>App Android, panel web de gestión, soporte remoto.</td>
    <td>Sitio web, contacto comercial directo, atención personalizada.</td>
    <td>Sitio web, redes sociales, contacto directo, soporte técnico propio.</td>
  </tr>

  <!-- Análisis SWOT -->
  <tr>
    <td rowspan="5"><strong>Análisis SWOT</strong></td>
    <td colspan="5">Realice esto para su startup y sus competidores. Las fortalezas deberían apoyar las oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>Doble enfoque (usuario + propietario), funcionalidades completas, visión escalable.</td>
    <td>Modelo SaaS claro, app moderna, soporte técnico.</td>
    <td>Experiencia de 20+ años, soluciones variadas, soporte.</td>
    <td>Alta innovación, integración tecnológica completa.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Se requiere adopción tecnológica de propietarios, inversión inicial en hardware.</td>
    <td>Público objetivo limitado a estacionamientos.</td>
    <td>Dependencia de hardware específico.</td>
    <td>Soluciones técnicas requieren conocimiento especializado del cliente.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Demanda creciente de soluciones sostenibles y reducción de congestión vehicular.</td>
    <td>Expansión a edificios corporativos y malls.</td>
    <td>Integrarse a plataformas de RRHH o ERP.</td>
    <td>Aplicaciones en smart cities y gestión pública.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competidores con infraestructura ya instalada, resistencia al cambio en operadores tradicionales.</td>
    <td>Competencia con soluciones genéricas más baratas.</td>
    <td>Importaciones informales de equipos sin soporte.</td>
    <td>Avance rápido de nuevas tecnologías internacionales.</td>
  </tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores
Nuestras estrategias y tácticas para hacer frente a nuestros competidores serían las siguientes:
- Para enfrentar a los competidores adoptaremos estrategias enfocadas en la diferenciación tecnológica y la experiencia del usuario para competir con empresas ya posicionadas en el sector. Buscaremos aprovechar oportunidades relacionadas con la digitalización urbana, el auge de las soluciones sin contacto y el crecimiento de las smart cities. Para afrontar las fortalezas de competidores consolidados, ofreceremos una propuesta más flexible, integrada y enfocada tanto en conductores como en propietarios. Frente a las debilidades del mercado, se posicionará como una alternativa accesible, moderna y adaptable. A su vez, anticiparemos amenazas mediante alianzas estratégicas, escalabilidad tecnológica y atención personalizada.
### 2.2. Entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.1. Diseño de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.2. Registro de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.3. Análisis de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 2.3. Needfinding
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.3.1. User Personas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.3.2. User Task Matrix
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.3.3. User Journey Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.3.4. Empathy Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.3.5. As-is Scenario Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 2.4. Ubiquitous Language
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 3.2. User Stories
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 3.3. Impact Mapping
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 3.4. Product Backlog
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

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