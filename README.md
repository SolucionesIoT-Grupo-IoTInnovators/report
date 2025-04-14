# Informe de Trabajo Final - TB1

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br><br>
    <img src="https://www.upc.edu.pe/static/img/logo_upc_red.png"></img><br><br>
    <strong>Ingeniería de Software - 202510</strong><br>
    <strong>Ciclo: 07</strong><br><br>
    <strong>1ASI0572 - Desarrollo de Soluciones IOT - 2971</strong><br><br>
    <strong>Profesor: Velasquez Nuñez, Angel Augusto</strong><br><br>
    <strong>INFORME DE TRABAJO FINAL - TB1 </strong> 
</p>
<p align="center">
    <strong>Startup: IoT Innovators </strong><br>
    <strong>Producto:  SmartParking </strong>
</p>

### Relación de integrantes

| Apellidos y Nombres                    | Código     |
| :------------------------------------  | :--------: |
| Arroyo Ormeño, André Alonso            | u202114714 |
| Castilla Pachas, César Antonio         | u202218735 |
| Cortés Casas, Joaquin Marcelo          | u202114545 |
| Diaz Silva, Fernando Josué             | u202112722 |
| Godoy, Johan Príncipe                  | u202014511 |
| Tafur Gonzales, Josty Gerardo          | u20201c069 |
| Zarate Caceres, Victor Ernesto         | u202112907 |


**Marzo, 2025**

## Registro de Versiones del Informe
|  Versión  |    Fecha   |      Autor     | Descripción de modificación |
| :------:  | :--------: | :------------- | :-------------------------- |
|   1.0.0   | 01/04/2025 | Ernesto Zarate | Avance de Capitulo 1: Descripcion de la Startup |

## Project Report Collaboration Insights

## Contenido

**Tabla de contenidos**

- [Informe de Trabajo Final - TB1](#informe-de-trabajo-final---tb1)
    - [Relación de integrantes](#relación-de-integrantes)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido](#contenido)
  - [Student Outcome](#student-outcome)
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
  - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
      - [4.2.1. Bounded Context: ](#421-bounded-context-)
        - [4.2.1.1. Domain Layer](#4211-domain-layer)
        - [4.2.1.2. Interface Layer](#4212-interface-layer)
        - [4.2.1.3. Application Layer](#4213-application-layer)
        - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
        - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
        - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
          - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
          - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
  - [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Video About-the-Team](#video-about-the-team)
  - [Bibliografia](#bibliografia)
  - [Anexos](#anexos)

## Student Outcome
<div align="justify">
  <table align="justify">
    <tr>
      <td>
        Criterio específico
      </td>
      <td>
        Acciones realizadas
      </td>
      <td>
        Conclusiones
      </td>
    </tr>
    <!--Primer Criterio-->
    <tr>
      <td>
        Trabaja en equipo para proporcionar liderazgo en forma conjunta
      </td>
      <!--Ingresar Accion Realizada por Entregable-->
      <td>
        <!--Andre Alonso-->
        Arroyo Ormeño, André Alonso: <br>
        TB1:<br>
        <br>
        <!--Cesar-->
        Castilla Pachas, César Antonio <br>
        TB1:<br>
        <br>
        <!--Joaquin-->
        Cortés Casas, Joaquin Marcelo <br>
        TB1:<br>
        <br>
        <!--Fernando-->
        Diaz Silva, Fernando Josué <br>
        TB1:<br>
        <br>
        <!--Johan-->
        Godoy, Johan Príncipe <br>
        TB1:<br>
        <br>
        <!--Josty-->
        Tafur Gonzales, Josty Gerardo <br>
        TB1:<br>
        <br>
        <!--CeVictorsar-->
        Zarate Caceres, Victor Ernesto  <br>
        TB1:<br>
        <br>
      </td>
      <!--Ingresar Conclusion por Entregable-->
      <td>
        TB1:<br>
      </td>
    </tr>
    <!--Segundo Criterio-->
    <tr>
      <td>
        Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.
      </td>
      <!--Ingresar Accion Realizada por Entregable-->
      <td>
        <!--Andre Alonso-->
        Arroyo Ormeño, André Alonso: <br>
        TB1:<br>
        <br>
        <!--Cesar-->
        Castilla Pachas, César Antonio <br>
        TB1:<br>
        <br>
        <!--Joaquin-->
        Cortés Casas, Joaquin Marcelo <br>
        TB1:<br>
        <br>
        <!--Fernando-->
        Diaz Silva, Fernando Josué <br>
        TB1:<br>
        <br>
        <!--Johan-->
        Godoy, Johan Príncipe <br>
        TB1:<br>
        <br>
        <!--Josty-->
        Tafur Gonzales, Josty Gerardo <br>
        TB1:<br>
        <br>
        <!--Victor-->
        Zarate Caceres, Victor Ernesto  <br>
        TB1:<br>
        <br>
      </td>
      <!--Ingresar Conclusion por Entregable-->
      <td>
        TB1:<br>
      </td>
    </tr>
  </table>
</div>

## Capítulo I: Introducción

### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup
<div align="justify">
    SmartParking nace como respuesta ante la falta de eficiencia en la gestión de estacionamientos en espacios públicos de alto tráfico. En muchas ciudades, los conductores pierden un tiempo considerable buscando espacios de estacionamiento disponibles, lo que genera congestión vehicular, aumenta la contaminación ambiental y reduce la satisfacción del usuario.
    Nuestra solución utiliza tecnología IoT para optimizar la administración de grandes estacionamientos, permitiendo la detección en tiempo real de espacios libres, la reserva de estacionamientos a través de una aplicación móvil y la integración con sistemas de pago automatizados. Con SmartParking, buscamos mejorar la movilidad urbana y hacer que el uso de los estacionamientos sea más eficiente y sostenible.<br>
    <ul>
      <li>
        <b>Misión:</b>
      </li>
      Revolucionar la gestión de estacionamientos a través de la tecnología IoT, proporcionando una solución inteligente que optimice el uso del espacio, reduzca el tiempo de búsqueda y mejore la experiencia del usuario.
      <li>
        <b>Visión:</b>
      </li>
      Ser la plataforma líder de estacionamientos inteligentes a nivel nacional, contribuyendo a la movilidad eficiente, promoviendo soluciones tecnológicas sostenibles.
    </ul>
</div>

#### 1.1.2. Perfiles de integrantes del equipo
Los integrantes que conforman la startup son:

| Integrante | Perfil                                                                                                                                                                                                                                                                                                                        |Foto|
| :--------- |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----|
| Arroyo Ormeño, André Alonso (202114714)   | Perfil                                                                                                                                                                                                                                                                                                                        |![Foto Andre]()|
| Castilla Pachas, César Antonio (202218735)| Tengo 21 años y estudió la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Me encanta crear páginas web y dar soluciones creativas, soy una persona responsable y puntual. Además, me encanta trabajar en equipo. Cada día me gusta aprender algo nuevo y poder ampliar mis conocimientos. |![Foto César](https://github.com/Aplicaciones-Web-Grupo-CodeRush/Informe-Final/raw/Chapter-01/assets/imgs/cesar.png)|
| Cortés Casas, Joaquin Marcelo (202114545) | Perfil                                                                                                                                                                                                                                                                                                                        |![Foto Joaquin]()|
| Diaz Silva, Fernando Josué (202112722)    | Perfil                                                                                                                                                                                                                                                                                                                        |![Foto Fernando]()|
| Godoy, Johan Príncipe (202014511)         | Perfil                                                                                                                                                                                                                                                                                                                        |![Foto Johan]()|
| Tafur Gonzales, Josty Gerardo (20201c069) | Soy Josty Tafur, estudiante de Ing. de software, cursando el décimo ciclo. Me apasiona aprender cosas nuevas y estoy siempre en busqueda de nuevos desafios que me ayuden a mejorar mis habilidades. Me considero una persona responsable, solidaria y con grabn capacidad de trabajar en equipo.                             |![Foto Josty](https://intranet.upc.edu.pe/programas/Imagen/Fotos/Upc/054020201c069.jpg)|
| Zarate Caceres, Victor Ernesto (202112907)| Soy Ernesto Zarate, estudiante de Ingeniería de Software. Me considero una persona responsable, capaz de aportar distintas ideas y de organizar el trabajo para el desarrollo de nuevos proyectos. Tengo el compromiso de trabajar eficientemente y realizar las entregas en el plazo indicado                                |![Foto Ernesto](https://intranet.upc.edu.pe/programas/Imagen/Fotos/Upc/0540202112907.jpg)|

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática
<div align="justify">
  <ul>
    <li>
      <b>What (Qué):</b> Desarrollar una solución IoT para la gestión inteligente de estacionamientos públicos, que permita:
      <ul>
        <li>Monitorear en tiempo real la disponibilidad de espacios.</li>
        <li>Reducir el tiempo de búsqueda de estacionamiento, disminuyendo la congestión vehicular</li>
        <li>Optimizar el cobro automatizado y la fiscalización mediante sensores y aplicaciones móviles.</li>
      </ul>
    </li>
    <li>
      <b>When (Cuándo): </b>La congestión por falta de estacionamiento es un problema persistente, pero se ha agravado en la última década debido al crecimiento vehicular. Un informe de la Asociación Automotriz del Perú (2023) señala que Lima un crecimiento de más de 100000 vehículos al año, lo que ocasiona cada vez más tráfico, que empeora durante las horas pico (7:00 - 9:00 AM y 5:00 - 8:00 PM).
    </li>
    <li>
      <b>Where (Dónde): </b>La problemática es crítica en ciudades con alta densidad vehicular, como Lima, Arequipa y Trujillo. Según un estudio de Lima Cómo Vamos (2022), el 60% del tráfico en distritos como Miraflores y San Isidro se debe a vehículos buscando estacionamiento.
    </li>
    <li>
      <b>Who (Quién): </b> La problemática afecta principalmente a conductores que buscan estacionamiento en zonas urbanas congestionadas. Según el Instituto Nacional de Estadística e Informática (INEI, 2022), el movimiento vehicular crecio en un 5,7%, lo que exacerba la demanda de espacios de estacionamiento. Además, las autoridades locales enfrentan desafíos en la fiscalización y gestión eficiente de estos espacios.
    </li>
    <li>
      <b>Why (Por qué): </b>La falta de gestión eficiente de estacionamientos genera:
      <ul>
        <li>Pérdidas económicas por tiempo improductivo en búsqueda de estacionamiento</li>
        <li>Contaminación ambiental debido a emisiones innecesarias.¿</li>
        <li>Estrés en conductores, reduciendo la calidad de vida urbana</li>
      </ul>
    </li>
    <li>
      <b>How (Cómo): </b>La solución propuesta integra:
      <ul>
        <li>Sensores IoT para detectar ocupación en tiempo real</li>
        <li>Plataforma centralizada para gestionar datos y procesar pagos digitales</li>
        <li>App móvil que guíe a los conductores a espacios disponibles</li>
        <li>Sistema de cobro automatizado para reducir evasión y mejorar ingresos municipales</li>
      </ul>
    </li>
    <li>
      <b>How Much (Cuánto):</b>
      <ul>
        <li>Impacto económico: Reducción del 30% en tiempo de búsqueda de estacionamiento</li>
        <li>Impacto ambiental: Disminución de emisiones de CO₂ en un 15% al reducir la congestión</li>
        <li>Retorno de inversión: Las municipalidades podrían aumentar ingresos mediante tarifas dinámicas y multas automatizadas.</li>
      </ul>
    </li>
  </ul>
</div>

#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
<div align="justify"> 
  <b>Problem Statement 1</b>
  <p>
    Hemos notado que los conductores en zonas urbanas de alto tráfico dedican una cantidad considerable de tiempo a buscar estacionamiento, lo que genera frustración, estrés y pérdida de productividad. La falta de información en tiempo real sobre la disponibilidad de espacios complica la experiencia del usuario, incrementando además la congestión vehicular y las emisiones contaminantes.
    Por lo tanto, se identificó la necesidad de proporcionar una herramienta que permita a los conductores localizar y reservar estacionamientos de manera rápida y eficiente.<br>
    <p>¿Cómo podemos ayudar a los conductores a encontrar y acceder a estacionamientos disponibles en tiempo real para optimizar su tiempo y reducir la congestión?</p>
  </p>

  <b>Problem Statement 2</b>
  <p>
    Se ha observado que los propietarios de estacionamientos enfrentan dificultades para gestionar de manera efectiva la ocupación de sus espacios. Los métodos manuales y sistemas obsoletos dificultan la obtención de datos en tiempo real, lo que afecta la capacidad de responder ante la variabilidad de la demanda y limita la optimización de los ingresos. Esto genera problemas en la asignación eficiente de los espacios disponibles y en la automatización de los cobros, reduciendo la rentabilidad de los estacionamientos.
    Por lo tanto, se identificó la necesidad de desarrollar un sistema centralizado que integre tecnología IoT para monitorear y gestionar de forma automatizada la ocupación y los pagos en los estacionamientos, facilitando la toma de decisiones basada en datos actualizados y maximizando la rentabilidad para los propietarios.<br>
    <p>
    ¿Cómo podemos optimizar la gestión de estacionamientos para que los propietarios puedan maximizar la ocupación de sus espacios y aumentar sus ingresos de manera eficiente?
    </p>
  </p>
</div>


##### 1.2.2.2. Lean UX Assumptions
<div>
  <b>Business Assumptions</b>
  <ul>
    <li>
      <b>Necesidad del mercado:</b>
      <p>
        Creemos que los conductores y propietarios de estacionamientos en ciudades de alta densidad requieren soluciones sencillas y eficientes. Los conductores necesitan encontrar y reservar estacionamientos de forma rápida y recibir información en tiempo real, mientras que los propietarios buscan optimizar la ocupación de sus espacios, gestionar pagos y obtener análisis detallados para maximizar sus ingresos.
      </p>
    </li>
    <li>
      <b>Solución Integral:</b>
      <p>
        Suponemos que el problema de la congestión vehicular y la baja eficiencia en la administración de estacionamientos se puede mitigar mediante una plataforma centralizada que integre sensores IoT para monitoreo en tiempo real, una app móvil para conductores y una aplicación web para propietarios, complementada con un sistema automatizado de pagos y notificaciones.
      </p>
    </li>
    <li>
      <b>Clientes iniciales:</b>
      <p>Nuestros principales clientes serán dos segmentos:</p>
      <ol type="1">
        <li>
          <b>Conductores:</b>
          Que demandan una experiencia fluida para buscar, reservar y pagar estacionamientos, recibiendo información actualizada y notificaciones sobre espacios libres o cambios en los precios.
        </li>
        <li>
          <b>Propietarios de estacionamientos:</b>
          Que necesitan optimizar la gestión de sus espacios a través de herramientas de análisis, reportes de ocupación en tiempo real y sistemas de cobro automatizados, para incrementar la rentabilidad de sus inversiones.
        </li>
      </ol>
    </li>
    <li>
      <b>Propuesta de valor:</b>
      <p>
        El valor principal de SmartParking es ofrecer una solución integral que combine la detección en tiempo real de espacios disponibles y un sistema de reserva y pago automatizado, facilitando la experiencia de los conductores y permitiendo a los propietarios gestionar sus estacionamientos de forma eficiente. Los beneficios adicionales incluyen:
      </p>
      <ul>
        <li>Reducción del tiempo de búsqueda para los conductores.</li>
        <li>Optimización en la ocupación y gestión de estacionamientos para los propietarios.</li>
        <li>Acceso a estadísticas y análisis detallados para la toma de decisiones.</li>
        <li>Integración con sistemas de navegación y plataformas de movilidad compartida.</li>
      </ul>
    </li>
    <li>
      <b>Estrategia de adquisición:</b>
      <p>
        Adquiriremos clientes mediante alianzas estratégicas con operadores privados de estacionamientos y campañas de marketing digital dirigidas a conductores y propietarios. Se implementarán demostraciones piloto en zonas urbanas de alta demanda y se promoverán casos de éxito para generar confianza y adopción.
      </p>
    </li>
    <li>
      <b>Modelo de Ingresos:</b>
      <p>
        La monetización se basará en suscripciones mensuales o anuales para propietarios, la venta de dispositivos IoT para el monitoreo de espacios, y servicios premium para ambos segmentos. Estos servicios premium ofrecerán funcionalidades avanzadas, como integración con apps de navegación y plataformas de movilidad compartida, y reportes analíticos personalizados.
      </p>
    </li>
    <li>
      <b>Competencia y Diferenciación:</b>
      <p>
        Competimos contra aplicaciones parciales y métodos manuales de gestión de estacionamientos. Nuestra ventaja radica en ofrecer una solución centralizada, integral y respaldada por tecnología IoT, que proporciona datos precisos en tiempo real y herramientas de análisis que benefician tanto a conductores como a propietarios.
      </p>
    </li>
    <li>
      <b>Principales Riesgos:</b>
      <p>
        Los riesgos principales incluyen fallos en los sensores IoT, baja adopción de la plataforma por parte de conductores o propietarios, y problemas en la integración de sistemas de pago. Mitigaremos estos riesgos mediante pruebas piloto, mantenimiento continuo y una estrategia de comunicación que destaque el valor agregado y la eficiencia del sistema.
      </p>
    </li>
    <li>
      <b>Indicadores de Éxito:</b>
      <p>
        Consideraremos que hemos alcanzado el éxito cuando:
      </p>
      <ul>
        <li>Los conductores experimenten una reducción del 30% en el tiempo de búsqueda de estacionamientos.</li>
        <li>Se observe un aumento significativo en la ocupación de los estacionamientos gestionados a través de la plataforma.</li>
        <li>Ambos segmentos muestren una alta tasa de adopción y satisfacción, evidenciada por el uso recurrente y la retroalimentación positiva.</li>
      </ul>
    </li>
  </ul>
    
  <b>User Assumptions</b>
  <ul>
    <li>
      <b>¿Quién es el usuario?</b>
      <p>
        - <b>Conductores:</b> Personas que transitan en ciudades de alta densidad y requieren una solución rápida y confiable para buscar, reservar y pagar estacionamientos.<br>
        - <b>Propietarios de estacionamientos:</b> Empresarios o administradores que necesitan herramientas para gestionar eficientemente sus espacios, analizar la demanda y maximizar la rentabilidad.
      </p>
    </li>
    <li>
      <b>¿Dónde encaja nuestro producto?</b>
      <p>
        - <b>En la vida diaria de los conductores:</b> La app móvil se integra en su rutina, facilitando la búsqueda y reserva de estacionamientos, reduciendo el estrés y optimizando su tiempo.<br>
        - <b>En el ámbito laboral de los propietarios:</b> La plataforma web ofrece herramientas de gestión y análisis que permiten controlar la ocupación y administrar los pagos, apoyando decisiones estratégicas para aumentar ingresos.
      </p>
    </li>
    <li>
      <b>Problemas Identificados y Soluciones Propuestas:</b>
      <p>
        - <b>Baja adopción por parte de los conductores:</b> Si los conductores no utilizan activamente la app, la efectividad del sistema se verá comprometida. <br><i>Solución:</i> Campañas de promoción, diseño de una interfaz intuitiva y mejoras basadas en la retroalimentación del usuario.<br>
        - <b>Ineficiencia en la gestión de estacionamientos:</b> Los propietarios pueden enfrentar dificultades para optimizar la ocupación y gestionar pagos de forma manual, lo que afecta la rentabilidad.<br><i>Solución:</i> Automatización de la gestión, reportes en tiempo real y herramientas analíticas que faciliten la toma de decisiones.
      </p>
    </li>
    <li>
      <b>¿Cuándo y cómo se usa nuestro producto?</b>
      <p>
        - <b>Conductores:</b> Utilizan la app móvil para visualizar mapas interactivos, reservar espacios y efectuar pagos en tiempo real, recibiendo notificaciones sobre disponibilidad y precios.<br>
        - <b>Propietarios:</b> Acceden a la plataforma web para monitorear la ocupación de sus estacionamientos, gestionar tarifas y analizar estadísticas de uso que les permitan mejorar su operatividad.
      </p>
    </li>
    <li>
      <b>Características Importantes:</b>
      <p>
        - Geolocalización en tiempo real para identificar espacios disponibles.<br>
        - Integración con sensores IoT que aseguren datos precisos y actualizados.<br>
        - Sistema de reserva y pago automatizado para simplificar la experiencia del usuario.<br>
        - Interfaz intuitiva tanto en la app móvil como en la plataforma web.
      </p>
    </li>
    <li>
      <b>Aspecto y Comportamiento del Producto:</b>
      <p>
        - <b>Interfaz de usuario (UI):</b> Moderna, limpia y adaptada a dispositivos móviles y web, facilitando la navegación y la visualización de información clave.<br>
        - <b>Experiencia de usuario (UX):</b> Simple y eficiente, permitiendo acciones rápidas (reservar, pagar, analizar) en pocos pasos.<br>
        - Disponibilidad continua para responder en tiempo real a las necesidades de los conductores y propietarios.
      </p>
    </li>
    <li>
      <b>Features Principales:</b>
      <p>
        - Registro y autenticación para conductores y propietarios.<br>
        - Mapas interactivos con ubicación de estacionamientos.<br>
        - Integración de sensores IoT para monitoreo en tiempo real.<br>
        - Sistema de reserva y pago en línea para conductores y panel de gestión para propietarios.<br>
        - Notificaciones y actualizaciones en tiempo real.
      </p>
    </li>
  </ul>
</div>

##### 1.2.2.3. Lean UX Hypothesis Statements
En relación con la propuesta descrita en la sección "Descripción de la Startup" de SmartParking, tenemos las siguientes hipótesis:

- **Hipótesis para Conductores:**  
  Creemos que, al brindar a los conductores información en tiempo real sobre la disponibilidad de estacionamientos (a través de geolocalización, notificaciones y datos precisos de sensores IoT), la aplicación les permitirá reducir significativamente el tiempo de búsqueda y reserva.  
  Sabremos que hemos tenido éxito cuando se registre una reducción del 30% en el tiempo de búsqueda de estacionamientos, medido a través de análisis de uso y feedback de los usuarios.

- **Hipótesis para Propietarios de Estacionamientos:**  
  Creemos que, al ofrecer a los propietarios una plataforma web con herramientas de gestión, análisis en tiempo real y reportes detallados sobre la ocupación y demanda de sus espacios, podrán optimizar la administración y maximizar sus ingresos.  
  Sabremos que hemos tenido éxito cuando se observe un aumento significativo en la ocupación de los estacionamientos (por ejemplo, un incremento del 20% en la tasa de ocupación) y una mejora en la rentabilidad, validado a través de estudios de caso y análisis financiero.

- **Hipótesis de Integración Tecnológica:**  
  Creemos que la integración de dispositivos IoT con la app móvil y la plataforma web permitirá una comunicación fluida y precisa entre los sensores, el sistema de reservas y el procesamiento de pagos.  
  Sabremos que hemos tenido éxito cuando se detecte una reducción en los errores de datos (por ejemplo, menos del 5% de discrepancias) y se mejore la fiabilidad de la información, comprobado mediante pruebas piloto y métricas de rendimiento.

- **Hipótesis de Viralidad y Crecimiento Orgánico:**  
  Creemos que la experiencia positiva de uso tanto en la app móvil como en la plataforma web incentivará a los usuarios a recomendar SmartParking a familiares y amigos, aumentando el alcance orgánico.
  Sabremos que hemos tenido éxito cuando al menos el 30% de los nuevos usuarios registrados mensualmente provengan de fuentes orgánicas, medido a través de análisis de crecimiento y fuentes de adquisición.

##### 1.2.2.4. Lean UX Canvas
<div align="justify">
  <table width="100%" border="1" cellpadding="10" cellspacing="0">
      <tr>
          <td width="33%" valign="top">
              <h4>Business Problem</h4>
              <ul>
                <li>Alta demanda de estacionamientos en zonas urbanas con congestión vehicular y falta de disponibilidad de espacios.</li>
                <li>Procesos manuales y poco eficientes en la gestión de estacionamientos por parte de propietarios, lo que genera baja ocupación y pérdida de ingresos.</li>
                <li>Los conductores pierden tiempo buscando estacionamiento, lo que incrementa el tráfico y el estrés urbano.</li>
              </ul>
          </td>
          <td rowspan="2" width="33%" valign="top">
              <h4>Solutions</h4>
              <ul>
                <li>Aplicación móvil para conductores con búsqueda, reserva y pago de estacionamiento.</li>
                <li>Plataforma web para propietarios con monitoreo de ocupación, estadísticas y gestión de ingresos.</li>
                <li>Integración de dispositivos IoT para monitoreo en tiempo real de espacios disponibles.</li>
                <li>Sistema de notificaciones sobre disponibilidad, precios y vencimiento de reservas.</li>
                <li>Visualización de espacios libres mediante geolocalización en tiempo real.</li>
              </ul>
          </td>
          <td width="33%" valign="top">
              <h4>Business Outcomes</h4>
              <ul>
                <li>Aumento en la ocupación de estacionamientos al optimizar el uso de los espacios disponibles.</li>
                <li>Reducción del tiempo de búsqueda de estacionamiento para conductores.</li>
                <li>
                Mayor eficiencia en la gestión de estacionamientos para los propietarios mediante herramientas de análisis y monitoreo en tiempo real.</li>
                <li>Monetización efectiva mediante suscripciones, comisiones por transacción y venta de dispositivos IoT.</li>
              </ul>
          </td>
      </tr>
      <tr>
          <td valign="top">
              <h4>Users</h4>
              <ul>
                <li>Conductores que buscan estacionamiento de forma rápida y eficiente.</li>
                <li>Propietarios de estacionamientos que desean maximizar la ocupación y optimizar la gestión de sus espacios.</li>
              </ul>
          </td>
          <td valign="top">
              <h4>User Outcomes & Benefits</h4>
              <ul>
                <li>Menor tiempo de búsqueda de estacionamiento para los conductores.</li>
                <li>Incremento en la ocupación de espacios para los propietarios.</li>
                <li>Interacción fluida y en tiempo real a través de la app móvil y la plataforma web.</li>
                <li>Proceso de pago automatizado y seguro.</li>
              </ul>
          </td>
      </tr>
      <tr>
          <td valign="top">
              <h4>Hypotheses</h4>
              <ul>
                <li>Creemos que ofrecer información en tiempo real sobre la disponibilidad de estacionamientos permitirá a los conductores reducir el tiempo de búsqueda en un 30%. Sabremos que hemos tenido éxito cuando veamos una reducción del tiempo promedio de búsqueda registrada en la app.</li>
                <li>Creemos que la implementación de un sistema de gestión centralizado aumentará la ocupación de estacionamientos en un 20%. Sabremos que tuvimos éxito cuando los propietarios reporten un aumento significativo en el uso de sus espacios.</li>
                <li>Creemos que ofrecer un sistema automatizado de pagos mejorará la experiencia del usuario, reduciendo los errores y tiempos de procesamiento. Sabremos que tuvimos éxito cuando el 90% de los pagos se realicen a través de la app.</li>
                <li>Creemos que una experiencia positiva de uso fomentará recomendaciones orgánicas, aumentando el número de usuarios. Sabremos que tuvimos éxito cuando al menos el 30% de los nuevos registros provengan de referencias.</li>
              </ul>
          </td>
          <td valign="top">
              <h4>What's the most important thing we need to learn first?</h4>
              <ul>
                <li>Identificar los principales puntos de dolor de los conductores al buscar estacionamiento en zonas congestionadas.</li>
                <li>Analizar los métodos actuales de gestión utilizados por los propietarios de estacionamientos.</li>
                <li>Conocer el comportamiento de los usuarios respecto al uso de aplicaciones similares en el mercado.</li>
                <li>Validar el interés de los propietarios en adoptar tecnología IoT para el monitoreo de espacios.</li>
              </ul>
          </td>
          <td valign="top">
              <h4>What's the least amount of work we need to do to learn the next most important thing?</h4>
              <ul>
                <li>Realizar encuestas a conductores sobre problemas comunes al buscar estacionamiento.</li>
                <li>Entrevistar a propietarios sobre su interés en digitalizar la gestión de sus espacios.</li>
                <li>Implementar un prototipo funcional con las características esenciales para evaluar su aceptación.</li>
                <li>Realizar pruebas piloto en zonas urbanas con alta demanda de estacionamiento para validar el impacto del sistema.</li>
              </ul>
          </td>
      </tr>
    </table>
</div>

### 1.3. Segmentos objetivo
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores
#### 2.1.1. Análisis competitivo
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.1.2. Estrategias y tácticas frente a competidores
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.2. Registro de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

#### 2.2.3. Análisis de entrevistas
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

### 2.3. Needfinding
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

#### 4.2.1. Bounded Context: <Bounded Context Name>
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.1.1. Domain Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.1.2. Interface Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.1.3. Application Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.1.4. Infrastructure Layer
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

##### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

###### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

###### 4.2.1.6.2. Bounded Context Database Design Diagram
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Conclusiones
### Conclusiones y recomendaciones
<div align="justify">
  <ul>
    <li>Conclusiones</li>
    <ul>
      <li>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.</li>
    </ul>
    <li>Recomendaciones</li>
    <ul>
      <li>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.</li>
    </ul>
  </ul>
</div>

### Video About-the-Team
Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.

## Bibliografia
<div align="justify">
  <ul>
    <li>Asociación Automotriz del Perú. (2023). <em>INFORME DEL SECTOR AUTOMOTOR: Diciembre 2024.</em> Recuperado de: https://aap.org.pe/informes-estadisticos/diciembre-2024/Informe-Diciembre-2024.pdf [Consulta: 02 de abril de 2025]</li>
    <li>INEI. (2022). <em>Estadísticas de transporte urbano en el Perú. </em>Recuperado de: https://m.inei.gob.pe/prensa/noticias/movimiento-de-vehiculos-a-nivel-nacional-aumento-39-en-febrero-de-2024-15125/ [Consulta: 02 de abril de 2025]</li>
    <li>Lima Cómo Vamos. (2023). <em>Reporte de movilidad urbana 2023.</em> Recuperado de: https://www.limacomovamos.org/wp-content/uploads/2022/06/Reporte-%C2%BFCo%CC%81mo-nos-movemos__LCV-LE-2022_compressed.pdf [Consulta: 02 de abril de 2025]</li>
  </ul>
</div>

## Anexos
<table>
	<tr>
		<td>Sección</td>
    <td>Características del video</td>
  </tr>
	<tr>
		<td>Exposición</td>
		<td>
			Cantidad de videos: 1<br><br>
			Nomenclatura: upc-pre-202510-1asi0572-2971-Iot_Innovators-expo-tb1<br>
			Formato: .mp4<br>
			Duración:<br>
			Enlace:<br>
		</td>
	</tr>
	<tr>
		<td>Entrevistas</td>
		<td>
			Cantidad de videos: 1<br><br>
			Nomenclatura: <br>
			Formato: .mp4<br>
			Duración: <br>
			Enlace:<br>
		</td>
	</tr>
</table>