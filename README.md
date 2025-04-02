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
    - [4.2.1. Bounded Context: <Bounded Context Name>](#421-bounded-context-bounded-context-name)
      - [4.2.1.1. Domain Layer](#4211-domain-layer)
      - [4.2.1.2. Interface Layer](#4212-interface-layer)
      - [4.2.1.3. Application Layer](#4213-application-layer)
      - [4.2.1.4. Infrastructure Layer](#4214-infrastructure-layer)
      - [4.2.1.5. Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - [4.2.1.6. Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - [4.2.1.6.1. Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - [4.2.1.6.2. Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

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

| Integrante |  Perfil |Foto|
| :--------- |---------|----|
| Arroyo Ormeño, André Alonso (202114714)   |Perfil|![Foto Andre]()|
| Castilla Pachas, César Antonio (202218735)|Perfil|![Foto César]()|
| Cortés Casas, Joaquin Marcelo (202114545) |Perfil|![Foto Joaquin]()|
| Diaz Silva, Fernando Josué (202112722)    |Perfil|![Foto Fernando]()|
| Godoy, Johan Príncipe (202014511)         |Perfil|![Foto Johan]()|
| Tafur Gonzales, Josty Gerardo (20201c069) |Perfil|![Foto Josty]()|
| Zarate Caceres, Victor Ernesto (202112907)| Soy Ernesto Zarate, estudiante de Ingeniería de Software. Me considero una persona responsable, capaz de aportar distintas ideas y de organizar el trabajo para el desarrollo de nuevos proyectos. Tengo el compromiso de trabajar eficientemente y realizar las entregas en el plazo indicado|![Foto Ernesto](https://intranet.upc.edu.pe/programas/Imagen/Fotos/Upc/0540202112907.jpg)|

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática
<div align="justify">
  <ul>
    <li>
      <b>What (Qué): </b> 
    </li>
    <li>
      <b>When (Cuándo): </b>
    </li>
    <li>
      <b>Where (Dónde): </b>
    </li>
    <li>
      <b>Who (Quién): </b>
    </li>
    <li>
      <b>Why (Por qué): </b>
    </li>
    <li>
      <b>How (Cómo): </b>
    </li>
    <li>
      <b>How Much (Cuánto):</b>
    </li>
  </ul>
</div>

#### 1.2.2. Lean UX Process
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
    <li>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.</li>
    <li>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit.</li>
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