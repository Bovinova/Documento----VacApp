<div style="text-align:center;">
    <h1>UNIVERSIDAD PERUANA<br> DE CIENCIAS APLICADAS</h1>
        <img src="https://hackmd.io/_uploads/ryJoz7YcR.png" alt="Logo" style="width:200px;height:auto;">
    <h2>1ACC0238 - Aplicaciones para Dispositivos Móviles</h2>
        <p><strong>NRC:</strong> 353</p>
        <p><strong>Carrera:</strong> Ingeniería de Software</p>
        <p><strong>Ciclo:</strong> 6</p>
        <p><strong>Profesor:</strong> Jorge Luis Mayta Guillermo</p>
    <h3>"Informe de Trabajo Final"</h3>
    <h4>TB1</h4>
        <p><strong>Tema:</strong> Gestion de ganaderia </p>
        <p><strong>Producto:</strong> VacApp de Bovinova</p>
        <p><strong>Abril 2025</strong></p>
</div>
<div style="text-align:left;">
    <h3>Integrantes:</h3>
        <ul>
            <li>Gómez Vallejos, Sergio André - U20221D401</li>
            <li>Rojas Velasquez, Maycol Jhordan - U202219984</li>
            <li>Aranda Vallejos, Oscar Gabriel - U202218167</li>
            <li>Ticona Panduro, Estrella del Pilar - U202210659</li>
            <li>Durand Vera, Gianfranco Angel - U20201f640</li>
            <li>Miranda Sinarahua, Piero Stephano - U20181g752</li>
        </ul>
</div>


<p style="text-align: center;">
  <strong>Registro de versiones de informe:</strong><br>
</p>

| Entregables | Fecha       | Autor                             | Descripción de modificación                                                                                      |  
|-------------|-------------|-----------------------------------|------------------------------------------------------------------------------------------------------------------|

**Project Report Collaboration Insights**

### URL del Repositorio 
https://github.com/orgs/Bovinova/repositories



<p style="text-align: center; font-weight: bold;">
  Tabla de contenido
  
</p>

1. [CAPÍTULO I: Presentacion](#CAPÍTULO-I-Introducción)<br>
    1.1. [Startup Profile](#Startup-Profile)<br>
      1.1.1. [Descripción de la Startup](#Descripción-de-la-Startup)<br>
      1.1.2. [Perfiles de integrantes del equipo](#Perfiles-de-integrantes-del-equipo)<br>
   1.2. [Solution Profile](#Solution-Profile)<br>
      1.2.1. [Antecedentes y problemática](#Antecedentes-y-problemática)<br>
      1.2.2. [Lean UX Process](#Lean-UX-Process)<br>
        1.2.2.1 [Lean UX Problem Statements](#Lean-UX-Problem-Statements)<br>
        1.2.2.2 [Lean UX Assumptions](#Lean-US-Assumptions)<br>
        1.2.2.3 [Lean UX Hypothesis Statements](#Lean-UX-Hypothesis-Statements)<br>
        1.2.2.4 [Lean UX Canvas](#Lean-UX-Canvas) <br>
    1.3. [Segmentos objetivo](#Segmentos-objetivo) <br>
2. [CAPÍTULO II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis) <br>
   2.1. [Competidores](#Competidores) <br>
      2.1.1. [Análisis competitivo](#Análisis-competitivo) <br>
      2.1.2. [Estrategias y tácticas frente a competidores](#Estrategias-y-tácticas-frente-a-competidores) <br>
   2.2. [Entrevistas](#Entrevistas) <br>
      2.2.1. [Diseño de entrevistas](#Diseño-de-entrevistas) <br>
      2.2.2. [Registro de entrevistas](#Registro-de-entrevistas)<br> 
      2.2.3. [Análisis de entrevistas](#Análisis-de-entrevistas)<br> 
   2.3. [Needfinding](#Needfinding) <br>
      2.3.1. [User Personas](#User-Personas) <br>
      2.3.2. [User Task Matrix](#User-Task-Matrix) <br>
      2.3.3. [User Journey Mapping](#User-Journey-Mapping) <br>
      2.3.4. [Empathy Mapping](#Empathy-Mapping) <br>
      2.3.5. [As-is Scenario Mapping](#As-is-Scenario-Mapping) <br>
   2.4. [Ubiquitous Language](#Ubiquitous-Language) <br>
3. [CAPÍTULO III: Requirements Specification](#Capítulo-III-Requirements-Specification) <br>
   3.1. [To-Be Scenario Mapping](#To-Be-Scenario-Mapping) <br>
   3.2. [User Stories](#User-Stories) <br>
   3.3. [Impact Mapping](#Impact-Mapping) <br>
   3.4. [Product Backlog](#Product-Backlog) <br>
4. [CAPÍTULO IV: Solution Software Design](#capítulo-iv-solution-software-design) <br>
   4.1. [Strategic-Level Domain-Driven Design](#strategic-level-domain-driven-design) <br>
      4.1.1. [EventStorming](#eventstorming) <br>
         4.1.1.1. [Candidate Context Discovery](#candidate-context-discovery) <br>
         4.1.1.2. [Domain Message Flows Modeling](#domain-message-flows-modeling) <br>
         4.1.1.3. [Bounded Context Canvases](#bounded-context-canvases) <br>
      4.1.2. [Context Mapping](#context-mapping) <br>
      4.1.3. [Software Architecture](#software-architecture) <br>
         4.1.3.1. [Software Architecture Context Level Diagrams](#software-architecture-context-level-diagrams) <br>
         4.1.3.2. [Software Architecture Container Level Diagrams](#software-architecture-container-level-diagrams) <br>
         4.1.3.3. [Software Architecture Deployment Diagrams](#software-architecture-deployment-diagrams) <br>
   4.2. [Tactical-Level Domain-Driven Design](#tactical-level-domain-driven-design) <br>
      4.2.X. [Bounded Context: &lt;Bounded Context Name&gt;](#bounded-context-bounded-context-name) <br>
         4.2.X.1. [Domain Layer](#domain-layer) <br>
         4.2.X.2. [Interface Layer](#interface-layer) <br>
         4.2.X.3. [Application Layer](#application-layer) <br>
         4.2.X.4. [Infrastructure Layer](#infrastructure-layer) <br>
         4.2.X.5. [Bounded Context Software Architecture Component Level Diagrams](#bounded-context-software-architecture-component-level-diagrams) <br>
         4.2.X.6. [Bounded Context Software Architecture Code Level Diagrams](#bounded-context-software-architecture-code-level-diagrams) <br>
            4.2.X.6.1. [Bounded Context Domain Layer Class Diagrams](#bounded-context-domain-layer-class-diagrams) <br>
            4.2.X.6.2. [Bounded Context Database Design Diagram](#bounded-context-database-design-diagram) <br>


   # STUDENT OUTCOME
El curso contribuye al cumplimiento del Student Outcome ABET: 
##### ABET – EAC - Student Outcome 7 
Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea
necesario, utilizando estrategias de aprendizaje apropiadas.


| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |  
|-------------------------|------------------------|------------------|  
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software | 1. Gómez Vallejos, Sergio André ------ <br><br> 2. Rojas Velasquez, Maycol Jhordan ------ <br><br> 3. Aranda Vallejos, Oscar Gabriel ------ <br><br> 4. Ticona Panduro, Estrella del Pilar ------ <br><br> 5. Durand Vera, Gianfranco Angel ------ <br><br> 6. Miranda Sinarahua, Piero Stephano ------ <br><br> |------- |  
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software |  1. Gómez Vallejos, Sergio André ------ <br><br> 2. Rojas Velasquez, Maycol Jhordan ------ <br><br> 3. Aranda Vallejos, Oscar Gabriel ------ <br><br> 4. Ticona Panduro, Estrella del Pilar ------ <br><br> 5. Durand Vera, Gianfranco Angel ------ <br><br> 6. Miranda Sinarahua, Piero Stephano ------ <br><br> | ---- |

# OBJETIVOS SMART


# 1. CAPÍTULO I: Presentacion
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
#### Descripción de la Startup:

### 1.1.2. Perfiles de integrantes del equipo

**Gómez Vallejos, Sergio André - U20221D401**
<br>--------------------------------------------<br>

**Rojas Velasquez, Maycol Jhordan - U202219984**
<br>--------------------------------------------<br>

**Aranda Vallejos, Oscar Gabriel - U202218167**
<br>--------------------------------------------<br>

**Ticona Panduro, Estrella del Pilar - U202210659**
<br>--------------------------------------------<br>

**Durand Vera, Gianfranco Angel - U20201f640**
<br>--------------------------------------------<br>

**Miranda Sinarahua, Piero Stephano - U20181g752**
<br>--------------------------------------------<br>

## 1.2. Solution Profile
## 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# 2. CAPÍTULO II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

# 3. CAPÍTULO III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# 4. CAPÍTULO IV: Solution Software Design
## 4.1. Strategic-Level Domain-Driven Design
### 4.1.1. EventStorming
#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases
### 4.1.2. Context Mapping
### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams
#### 4.1.3.3. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design
### 4.2.X. Bounded Context: <Bounded Context Name>
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram





