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
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software | 1. Gómez Vallejos, Sergio André ------ <br><br> 2. Rojas Velasquez, Maycol Jhordan ------ <br><br> 3. Aranda Vallejos, Oscar Gabriel <br> TB1 <br> Participé en el proceso del eventstorming, actualizando los conceptos y técnicas aprendidas del Domain Driven Design. <br><br> 4. Ticona Panduro, Estrella del Pilar ------ <br><br> 5. Durand Vera, Gianfranco Angel ------ <br><br> 6. Miranda Sinarahua, Piero Stephano ------ <br><br> |------- |  
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software |  1. Gómez Vallejos, Sergio André ------ <br><br> 2. Rojas Velasquez, Maycol Jhordan ------ <br><br> 3. Aranda Vallejos, Oscar Gabriel <br> TB1 <br> Reconocí la importancia de realizar un buen diseño en el DDD Estratégico para determinar de manera clara y objetiva nuestros bounded context y sus responsabilidades. <br><br> 4. Ticona Panduro, Estrella del Pilar ------ <br><br> 5. Durand Vera, Gianfranco Angel ------ <br><br> 6. Miranda Sinarahua, Piero Stephano ------ <br><br> | ---- |

# OBJETIVOS SMART

| Estudiante | Objetivo SMART |
|------------|-----------|
|Maycol Jhordan Rojas Velasquez | Mi Objetivo es poder alcanzar un desempeño profesional en analisis forense y en el diseño de nuevas apliaciones moviles, que ayuden en la sociedad, siguiendo todo lo aprendido y gestionando correctamente las buenas practicas.
|Oscar Gabriel Aranda Vallejos | Mi objetivo es poder especializarme en el desarrollo web full stack, integrando tecnologías emergentes para crear soluciones innovadoras que impacten positivamente en la sociedad. Para ello continuaré aprendiendo y participando en proyectos de desarrollo de aplicaciones web.

# 1. CAPÍTULO I: Presentacion
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

__Nombre del Start:__ VacApp

VacApp es una avanzada aplicación movil diseñada para capacitar a los ganaderos en la gestión eficiente y sostenible de su ganado. Esta plataforma ofrece una amplia gama de herramientas integrales que permiten a los usuarios realizar un seguimiento detallado de la salud, alimentación y reproducción de sus animales, lo que facilita una mejor toma de decisiones en la granja. Con PecuarioPro, los ganaderos pueden optimizar sus operaciones y maximizar sus ingresos, al tiempo que promueven prácticas agrícolas sostenibles y éticas, lo que contribuye al bienestar de los animales y al desarrollo sostenible de la industria ganadera.

<img src="./assets/Bovinova.png" alt="vacapp Logo" style="width: 250px; height: 250px;">

### **Colaboraciones Estrategicas:**

En Bovinova, estamos comprometidos a establecer solidad alianzas con cadenas de ganaderia, pequeños ganaderos y empresas ganaderas. Trabajamos en estrecha colaboración con estos socios para garantizar que nuestras soluciones tecnológicas respondan a sus necesidades operativas, facilitando la gestión diaria y mejorando la satisfacción del cliente. Invitamos a los ganaderos a integrar nuestras soluciones para optimizar la administración de ganado, la gestión de alimentacion, y la atención al cliente, creando una experiencia más fluida y eficiente.

### **Innovación y Tecnología**
Nuestra plataforma utiliza tecnologías avanzadas para ofrecer una experiencia optimizada en la gestión ganadera. Desde el monitoreo de la salud, alimentación y reproducción del ganado, hasta la automatización de procesos clave en la granja, **VacApp** busca transformar la forma en que los ganaderos administran sus actividades diarias. Queremos que cada productor pecuario se sienta respaldado por una solución tecnológica que le permita tomar decisiones informadas, mejorar la eficiencia operativa y promover una producción sostenible y ética.

### **Comunidad y Funciones Sociales**
**VacApp** no es solo una herramienta de gestión; es también un espacio de aprendizaje y colaboración entre ganaderos. La plataforma incluye funciones que permiten a los usuarios compartir buenas prácticas, estrategias de manejo y mantenerse actualizados con las últimas innovaciones en el sector pecuario. Esta comunidad activa fomenta la mejora continua, el intercambio de conocimientos y el fortalecimiento de una red ganadera comprometida con el desarrollo sostenible y el bienestar animal.

### **Visión**
Visualizamos un mundo donde la tecnología y la ganadería se integran para impulsar una producción más eficiente, responsable y rentable. Nuestro objetivo es que **VacApp** sea sinónimo de innovación en el manejo ganadero, un aliado indispensable para los productores que desean evolucionar hacia un modelo más moderno, conectado y sostenible. Aspiramos a liderar una transformación positiva en la industria, basada en la tecnología, la ética y el compromiso con el campo.

### **Misión**
Nos esforzamos por ofrecer una plataforma integral que empodere a los ganaderos con herramientas inteligentes de gestión, mejorando su productividad y calidad de vida. Estamos decididos a utilizar la tecnología como motor de cambio en el sector pecuario, contribuyendo al bienestar animal, la sostenibilidad ambiental y el desarrollo económico de las comunidades rurales. **VacApp**, impulsado por **Bovinova**, será símbolo de excelencia, innovación y compromiso con el futuro de la ganadería.


### 1.1.2. Perfiles de integrantes del equipo

| Integrante | Descripción |
| ---- | --- |
| ![Sergio](https://hackmd.io/_uploads/SkU_5d9cR.png) | Sergio André Gómez Vallejos – Ingeniería de Software – u20221d401 <br> Soy una persona resiliente que, sin importar cuántas veces caiga, siempre encuentra la manera de levantarse. Tengo habilidades sociales sólidas y una amplia experiencia en la resolución de problemas de código. Suelo ser el miembro más activo de mi equipo de trabajo. Me apasionan los lenguajes de programación y la tecnología, y constantemente me esfuerzo por alcanzar mis objetivos y contribuir al desarrollo del startup. |
| [![Captura-de-pantalla-2024-09-08-151747.png](https://i.postimg.cc/6qRCcvNF/Captura-de-pantalla-2024-09-08-151747.png)](https://postimg.cc/kRJVXDGy) |Aranda Vallejos, Oscar Gabriel - U202218167 <br> Tengo 20 años y soy estudiante de la carrera de Ingeniería de Software, poseo conocimientos intermedios en Unity, C++, Java, Spring Boot y diseño web. Me considero una persona responsable y perseverante. Siempre estoy dispuesto a aprender nuevos conceptos y elegí esta carrera porque me apasiona el desarrollo de software y la posibilidad de crear soluciones que impacten positivamente en la sociedad. |
|<img src="https://hackmd.io/_uploads/B1F_iuso0.jpg" alt="yo-3" style="width: 600px ; height: 200px;">|Maycol Jhordan Rojas Velasquez – Ingeniería de Software – u202219984<br>Elegí la carrera de Ingeniería de Software debido a mi gusto por la innovación y la implementación de la tecnología en cualquier rubro  social, de una manera creativa y en todos los aspectos. Me considero una persona creativa, en busca de ideas, estrategias con mente nueva. También me gusta escuchar ideas de mi equipo, dar ideas de mejora, evaluar las ventajas y desventajas . Además, tengo conocimientos de programación en C + +, HTML, Python,Angular,Backend en Java. Además, Tengo un enfoque responsable y dedicado mediante un aprendizaje rápido así puedo ayudar a mis compañeros en sus dudas. Por otro lado, mis hobbies son ver series, jugar , escuchar música, nadar y  manejar.|
| ![Estrella]()| Ticona Panduro, Estrella del Pilar - U202210659 <br> |
| ![Gianfranco]() | Durand Vera, Gianfranco Angel - U20201f640 <br>|
|![Piero]()| Miranda Sinarahua, Piero Stephano - U20181g752 <br> | 


## 1.2. Solution Profile
## 1.2.1 Antecedentes y problemática
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements
#### 1.2.2.2. Lean UX Assumptions
#### 1.2.2.3. Lean UX Hypothesis Statements
#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

### Descripción de cada segmento objetivo:

La aplicación VacApp ha sido diseñada pensando en las diversas realidades del sector ganadero peruano, abarcando tanto a pequeños productores independientes como a grandes empresas dedicadas a la actividad pecuaria. Cada segmento presenta necesidades, objetivos y desafíos específicos que nuestra plataforma busca atender con soluciones tecnológicas prácticas, accesibles y sostenibles.

A continuación, se detalla el perfil de nuestros principales segmentos objetivos, identificando sus características, motivaciones y problemáticas, con el fin de adaptar y mejorar constantemente nuestros servicios para ofrecerles el mayor valor posible.

#### Productores Ganadores independientes:
Este segmento objetivo de nuestra plataforma se centra en los ganaderos independientes comprometidos y preocupados por obtener ganancias de manera ética y sostenible, mientras garantizan una excelente calidad en el cuidado de sus animales en propiedad. Este grupo comprende a ganaderos que poseen una variedad de animales, tales como ovejas, vacas, reses, corderos, gallinas, entre otros, y que residen en Perú. Su principal objetivo es asegurarse de que el estado y cuidado de sus animales sea óptimo, priorizando el bienestar y la salud de estos. Además, están interesados en llevar a cabo prácticas de venta honestas, con un enfoque en productos más naturales y de alta calidad. Como obtener información de nuevos métodos de cuidado animal.

#### Empresas Ganaderas:
El segmento objetivo de nuestra plataforma se dirige específicamente a grandes empresas corporativas involucradas en la gestión y cuidado de animales. Estas empresas se destacan por su firme compromiso con prácticas éticas y sostenibles en la producción ganadera. Su principal preocupación radica en garantizar que sus animales reciban una alimentación precisa, óptima y honesta, priorizando la salud y el bienestar de cada individuo. Asimismo, estas empresas se preocupan por brindar un cuidado individual a cada animal, asegurándose de que reciban la atención necesaria para su desarrollo y bienestar. Asimismo, contar con un sistema integral de gestión veterinaria, que garantiza un acceso constante y adecuado a servicios de atención médica veterinaria para sus animales.

### Datos cuantitativos del problema:

#### Productores Ganadores independientes:
Se han registrado numerosos incidentes en los que los productores ganaderos peruanos no reciben una compensación justa en los mercados, y enfrentan dificultades significativas en la gestión del cuidado de sus animales debido a la escasez de recursos económicos y la limitada accesibilidad a servicios veterinarios para consultas y atención adecuada. Estas circunstancias han creado desafíos sustanciales para los ganaderos, quienes luchan por mantener la salud y el bienestar de sus animales mientras buscan asegurar su propio sustento económico en un entorno cada vez más desafiante y competitivo. Se estima que al menos el 15% de los animales muertos en las granjas se debe a la falta de acceso oportuno a servicios veterinarios adecuados, lo que genera pérdidas económicas significativas para los productores, estimadas en un 20% de sus ingresos anuales debido a la falta de compensación justa de los mercados hacia ellos.

#### Empresas Ganaderas:
En el Perú, el bienestar animal en las empresas ganaderas es a menudo insuficiente, con un preocupante porcentaje del 60% de las operaciones que no cumplen con estándares aceptables en este aspecto. Esta deficiencia se refleja en condiciones de vida inadecuadas para el ganado, como la falta de espacio y la alimentación deficiente, lo que afecta negativamente su salud y bienestar. Además, la gestión de residuos en estas empresas es inadecuada en aproximadamente un 70% de los casos, lo que resulta en una incorrecta disposición de los desechos animales y una potencial contaminación del medio ambiente. Esta situación representa un desafío significativo para la industria ganadera, ya que no solo compromete el bienestar de los animales, sino que también puede tener repercusiones negativas en la salud pública y el medio ambiente.

### Variables geográficas, demográficas y psicológicas:

#### Variable geográfica:
- País: Perú
- Ciudad: zonas rurales 

#### Variable demográfica:
- Género: Femenino / Masculino.
- Ocupación: Productores ganaderos 
- Estado civil: Todos los estados
- Edad y etapa de ciclo de vida:
- Ciudadanos mayores a 18 años.

#### Variable psicográfica:
- Nivel Socioeconómico (NSE): todos los niveles socioeconomicos
- Características de personalidad:
 - Altruismo 
 - Perseverante
 - Honestidad

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
En esta sección se describe el proceso utilizado en las decisiones del negocio, aplicando el enfoque de Domain Driven Design. A través de esta metodología, se busca identificar y definir los distintos Bounded Contexts que conforman el sistema, es decir, subconjuntos con límites lógicos y naturales en función del dominio del problema. Para lograrlo, el equipo emplea herramientas como EventStorming y el Bounded Context Canvas, las cuales permiten visualizar, analizar y delimitar las responsabilidades, flujos de eventos y relaciones clave dentro del sistema. 

### 4.1.1. EventStorming
En este apartado se documenta el proceso del Event Storming, una herramienta clave para construir una primera aproximación al modelado general del dominio del negocio. Esta técnica colaborativa permite identificar eventos relevantes, actors, commands y aggregates dentro del sistema. Con ello, el objetivo principal es explorar nuestro dominio para descubrir patrones de software relevantes, límites y conexiones claras entre nuestros bounded context y sentar las bases para una buena arquitectura. Para ello, se realizaron los siguientes pasos en la herramienta Lucidchart bajo la normativa del DDD Estratégico. https://lucid.app/lucidchart/485813a6-b859-4a14-a28a-7e048f209992/edit?viewport_loc=74140%2C-2906%2C11186%2C5074%2C0_0&invitationId=inv_b00dd762-3281-4382-8e1c-aa8db916cbfd

#### 4.1.1.1. Candidate Context Discovery

A continuación se detalla el proceso y la evolución final del event storming.

#### Step 1: Unstructured exploration
Primero tuvimos una lluvia de ideas en la cual nos propusimos identificar exhaustivamente todos los eventos que ocurrirán en nuestro aplicativo, para asegurarnos de abarcar una amplia gama de posibilidades y ofrecer una experiencia completa y satisfactoria a nuestros usuarios. Este paso se puede visualizar con mayor claridad en el siguiente enlace: 

A continuación, se presentan una serie de figuras que evidencian este proceso de exploración inicial.

[![es-step1.png](https://i.postimg.cc/6qfmcs5b/es-step1.png)](https://postimg.cc/JHtx72Xj)
<br>En esta figura se aprecia un mural con todos los eventos del dominio que fueron rescatados de la lluvia de ideas que realizó el equipo.<br>

#### Step 2: Timeline construction
Una vez identificados los eventos, organizamos la secuencia cronológica en la que estos ocurren dentro del flujo del sistema. Esto nos permitió identificar la secuencia natural del negocio y clarificar la narrativa del dominio. Dicha representación se puede encontrar desarrollada en el siguiente enlace: https://lucid.app/lucidchart/485813a6-b859-4a14-a28a-7e048f209992/edit?viewport_loc=-9234%2C-1588%2C7434%2C3010%2C0_0&invitationId=inv_b00dd762-3281-4382-8e1c-aa8db916cbfd

A continuación, se presentan una serie de capturas de pantalla que ilustran cómo estructuramos esta línea temporal. 

[![Step2-1.png](https://i.postimg.cc/TPh6hXh2/Step2-1.png)](https://postimg.cc/qtfYZS8W)
<br>En esta imagen se reflejan los eventos alineados según el orden lógico o temporal de su ocurrencia desde el proceso de adición de un bovino y la gestión del mismo hasta la adición de una nueva vacuna. Esto señala que el proceso natural del sistema consistirá en primero registrar un bovino para después registrar vacunas que serán aplicadas en ese bovino.<br>

[![es-step2-2.png](https://i.postimg.cc/4N6mZWmf/es-step2-2.png)](https://postimg.cc/6yQ9fLrg)
<br>Con esta figura podemos continuar describiendo la ruta de actividades dentro del negocio. A partir de haber sido registrada una vacuna con sus campos correspondientes y ya disponer de bovinos registrados, un servicio de asesoría veterinaria es habilitado para el usuario. <br>

[![es-step2-3.png](https://i.postimg.cc/Znk5zNmv/es-step2-3.png)](https://postimg.cc/hzrB9ffK)
<br>En esta imagen se muestra la secuencia de eventos que ocurren cuando un usuario con una empresa ganadera registra a sus trabajadores y decide crear una campaña. Tras haber sido creada la campaña, el empresario ganadero posee la opción de gestionar la campaña registrada y consultar el clima. Además, se representan los atibutos que tendrá la entidad campaña.<br>

#### Step 3: Pain Points
En este paso identificamos los puntos críticos que requieren especial atención dentro de nuestro dominio, ya sea por su nivel de impacto en el negocio, riesgo potencial o complejidad. Para facilitar su análisis y visualización, se ha elaborado un diagrama colaborativo que refleja dichos puntos críticos.

A continuación, se presentan una serie de figuras que evidencian el proceso realizado durante la identificación y análisis de los puntos críticos del dominio. Estas capturas complementan el diagrama general elaborado en Lucidchart y permiten observar con mayor detalle los elementos clave identificados.

[![Step3-1.png](https://i.postimg.cc/76P6YR0q/Step3-1.png)](https://postimg.cc/063xVcV4)
<br>En esta imagen se aprecia la identificación de incertidumbres sobre cómo realizar la validación de los campos de los bovinos y cómo estos campos serán utilizados para filtrar la búsqueda. Al resolver estas interrogantes, lograremos mejorar la propuesta de diseño y facilitar el proceso de implementación.<br>

[![Step3-2.png](https://i.postimg.cc/50pm6Drg/Step3-2.png)](https://postimg.cc/phhjScR5)
<br>Esta figura muestra los puntos críticos identificados sobre la validación de los campos de una vacuna que además serán utilizados para aplicar filtros de búsqueda en las vacunas. Resolver esto es importante para evitar que datos ajenos a la información de una vacuna real sea introducido.<br>

[![Step3-3.png](https://i.postimg.cc/hPdhP6fq/Step3-3.png)](https://postimg.cc/bsqqm6x6)
<br>Esta figura muestra un punto crítico relacionado al servicio de asistencia veterinaria. Este fue identificado rápidamente debido a la complejidad en la implementación de respuestas a consultas veterinarias en tiempo real.<br>

[![Step3-4.png](https://i.postimg.cc/8sgVKyR2/Step3-4.png)](https://postimg.cc/bSgMd9Fg)
<br>En esta imagen se observa que limitar la capacidad de trabajadores que pueden ser ingresados al sistema es considerado un factor crítico, lo cual es debido al nivel de riesgo presente en recibir grandes volúmenes de datos.<br>

#### Step 4: Pivotal Points
 En esta sección se marcaron los puntos clave que denotan transiciones significativas dentro del proceso de desarrollo, especialmente aquellos eventos o decisiones que implican un cambio en el comportamiento del sistema o en la forma en que los distintos Bounded Contexts interactúan entre sí. Como se puede observar, los pivotal points son sumamente importantes. Por ello, para poder comprender y apreciar el diseño realizado en este paso, se muestran las siguientes imágenes. 

[![es-step4-1.png](https://i.postimg.cc/vZ5j06qS/es-step4-1.png)](https://postimg.cc/w1T0v3dh)<br>

[![es-step4-2.png](https://i.postimg.cc/Kz1Crpdt/es-step4-2.png)](https://postimg.cc/XG02nLNv)<br>

[![es-step4-3.png](https://i.postimg.cc/Jh69XCd1/es-step4-3.png)](https://postimg.cc/zLhtm6rM)<br>

#### Step 5: Commands

En este paso se definen los comandos que representan las acciones que los usuarios pueden ejecutar en el sistema. Estos comandos son fundamentales para desencadenar eventos y modificar el estado del sistema, y deben estar alineados con los eventos identificados previamente. A continuación, se muestran los comandos relevantes para nuestro dominio.

[![es-step5-1.png](https://i.postimg.cc/T398RDV5/es-step5-1.png)](https://postimg.cc/mPtpjh6T)
<br>En este frame tenemos un command para registrar un bovino.<br>

[![es-step5-2.png](https://i.postimg.cc/GphW9mK7/es-step5-2.png)](https://postimg.cc/zy6tc59K)
<br>En esta imagen tenemos commands adicionales para actualizar un bovino y eliminar un bovino. Además podrá ser buscado mediante filtros. <br>

[![es-step5-3.png](https://i.postimg.cc/x1YDDRzS/es-step5-3.png)](https://postimg.cc/D8CY116C)
<br>En este marco se define un command para registrar, actualizar y eliminar una vacuna. Una vez añadida en el sistema también podrá ser buscada mediante filtros.<br>

[![es-step5-4.png](https://i.postimg.cc/xTLD47qR/es-step5-4.png)](https://postimg.cc/0b5B6VYM)
<br>En este marco se define un command con la función de atender una consulta veterinaria, respondiendo de manera satisfactoria.<br>

[![es-step5-5.png](https://i.postimg.cc/8k2gwDkc/es-step5-5.png)](https://postimg.cc/bd95N7tf)
<br>En este frame se define un command para registrar, actualizar y eliminar una campaña. Además, tendremos un command para consultar el clima.<br>

[![es-step5-6.png](https://i.postimg.cc/pybCjsHV/es-step5-6.png)](https://postimg.cc/vxh5FLTC)
<br>En este marco se define un command para registrar, actualizar y eliminar un empleado. Una vez añadido en el sistema también podrá ser buscado mediante filtros.<br>

#### Step 6: Policies
En este paso se describen políticas que rigen decisiones y acciones dentro del sistema, asegurando que este se alinie con las necesidades del usuario y los objetivos del negocio.

Los siguientes frames contienen políticas que indican diferentes restricciones o condiciones descritas a continuación:
- Campos que deben ser validados antes de proceder con la creación y registro de un objeto
- Condiciones para eliminar un objeto
- Condiciones que debe cumplir un objeto para ser creado como, por ejemplo, el caso de un establo que requiere de por lo menos un bovino asignado para existir.   

[![es-step6-1.png](https://i.postimg.cc/ry0LSzk7/es-step6-1.png)](https://postimg.cc/rzkbTVz9)<br>

[![es-step6-2.png](https://i.postimg.cc/kGtwDkLh/es-step6-2.png)](https://postimg.cc/FkN0Bnrj)<br>

[![es-step6-3.png](https://i.postimg.cc/ydGv1VpZ/es-step6-3.png)](https://postimg.cc/0MppZqsk)<br>

[![es-step6-4.png](https://i.postimg.cc/vm30K7WX/es-step6-4.png)](https://postimg.cc/VS09rCZb)<br>

[![es-step6-5.png](https://i.postimg.cc/d0qWnNTL/es-step6-5.png)](https://postimg.cc/TK4q3906)<br>


#### Step 7 & 8: Read Models & External Systems
Estos dos pasos conforman la aparición de los read models y los external systems respectivamente. Por un lado, los read models son proyecciones que representan vistas personalizadas, dashboards, o reportes. Por otro lado, los external systems en DDD representan aquellos componentes o servicios externos con los que el sistema necesita interactuar, como pasarelas de pago, servicios de autenticación, sistemas de terceros, o integraciones con otras plataformas empresariales.

[![es-step7-1.png](https://i.postimg.cc/C15cpZ70/es-step7-1.png)](https://postimg.cc/TL8Vr3BN)
<br>En esta figura podemos apreciar los read models representando vistas de componentes como listas de bovinos.<br>

[![es-step7-2.png](https://i.postimg.cc/Qdg4QZC2/es-step7-2.png)](https://postimg.cc/CR1s0tj7)
<br>En esta figura podemos apreciar un external system coloreado de rojo, el cual representa un servicio externo de asistencia de consultas veterinarias que será integrado al negocio mediante un proveedor de inteligencia artificial que permita responder las consultas de manera eficiente.<br>

[![es-step7-3.png](https://i.postimg.cc/wjY4Rjq5/es-step7-3.png)](https://postimg.cc/6yzfDwGT)
<br>En esta figura también podemos apreciar otro external system coloreado de rojo, el cual representa un servicio para la gestión del clima que indicará el clima en tiempo real y
será integrado al negocio.<br>

#### Step 9 & 10: Aggregates & Bounded Contexts
En los pasos 9 y 10 se introducen dos conceptos clave del Domain-Driven Design: Aggregates y Bounded Contexts. Los aggregates representan unidades de consistencia dentro del modelo de dominio, agrupando entidades y objetos de valor que deben mantenerse coherentes bajo una misma raíz (aggregate root). Por otro lado, los bounded contexts definen límites en los cuales un modelo tiene significado y coherencia, estableciendo una frontera clara para evitar ambigüedades conceptuales.

Bounded Context: Ranch Management<br>
[![es-stepfinal-bc-ranch-management-1.png](https://i.postimg.cc/yxJpcJ3j/es-stepfinal-bc-ranch-management-1.png)](https://postimg.cc/Wqv7P1nq)<br>
[![es-stepfinal-bc-ranch-management-2.png](https://i.postimg.cc/NMjzGCgW/es-stepfinal-bc-ranch-management-2.png)](https://postimg.cc/nsNk0k9k)<br>

Bounded Context: AssistVet Management<br>
[![es-stepfinal-bc-assistvet-consulting-management.png](https://i.postimg.cc/T2S4GcB4/es-stepfinal-bc-assistvet-consulting-management.png)](https://postimg.cc/z3CjFTzC)<br>

Bounded Context: Campaign Management<br>[![es-stepfinal-bc-campaign-management.png](https://i.postimg.cc/nzSwXKrM/es-stepfinal-bc-campaign-management.png)](https://postimg.cc/Q95qPTpr)<br>


Bounded Context: Staff Administration<br>[![es-stepfinal-bc-staff-administration.png](https://i.postimg.cc/LsTWpFMt/es-stepfinal-bc-staff-administration.png)](https://postimg.cc/CZR7Gt55)<br>

#### 4.1.1.2. Domain Message Flows Modeling

En los siguientes gráficos, se representa el proceso seguido para visualizar cómo  deben colaborar los bounded contexts para resolver distintos escenarios que pueden presentarse en el negocio. https://miro.com/welcomeonboard/YlFjbmp4MVZyWklRQkowNWhEOWYyek9SNkdYQ2F6U2t3UDdnbHhRSkNVR1VlMUpKa0pRYTB5RGJ0ZjcyR0ZsUjVoMllXZExLMFFqNDM1aHFabUZHQTR2blhOaG04M0QzMVhhMXlnL3FsR21IUTNDSHQwOHRQREliZVIvMXZPV2RhWWluRVAxeXRuUUgwWDl3Mk1qRGVRPT0hdjE=?share_link_id=723977050478

<br>[![scenario-ranch.png](https://i.postimg.cc/G2YrD0XT/scenario-ranch.png)](https://postimg.cc/629DsPJB)<br>
Este es un escenario donde se requiere editar los datos de una vacuna que aún no ha sido asignada a un bovino. Para ello, primero se registra un bovino con sus atributos correspondientes. Este bovino puede ser designado a un establo y, de ser así, el establo creado queda disponible para una campaña. Además, se puede registrar y asignar una vacuna a un bovino determinado. Secuencialmente, las consultas son habilitadas para el AssistVet y los datos de la vacuna pueden ser editados si el usuario desea actualizar información determinada.<br> 

<br>[![scenario-consulting.png](https://i.postimg.cc/90h2txk8/scenario-consulting.png)](https://postimg.cc/MMdgzYqV)<br>Este es un escenario donde se requiere realizar consultas al asistente veterinario que responderá utilizando inteligencia artificial.<br>

<br>[![scenario-weather.png](https://i.postimg.cc/ZnxSf8tT/scenario-weather.png)](https://postimg.cc/Zvn2ny5g)<br>En esta figura se observa un escenario donde se requiere consultar el clima en tiempo real para evaluar si la campaña procederá o no.<br>

<br>[![scenario-employ.png](https://i.postimg.cc/BZkwjhyH/scenario-employ.png)](https://postimg.cc/yWhT5T78)<br>Esta imagen expresa un escenario donde se requiere registrar y actualizar la lista de empleados que serán asignados a una campaña determinada.<br>

#### 4.1.1.3. Bounded Context Canvases
El Bounded Context Canvas es una herramienta visual del Domain-Driven Design (DDD) que permite definir, entender y comunicar de forma clara los límites, responsabilidades y elementos clave de un Bounded Context. Ayuda a alinear al equipo en torno a una visión compartida del dominio, identificando entidades, eventos, comandos y relaciones externas. Además, elaborar un diseño modular del sistema de manera coherente es posible gracias a las nomenclaturas establecidas por un Bounded Context Canvas. https://miro.com/app/board/uXjVID6SLCE=/?share_link_id=614179168415


**Bounded Context: Ranch Management**<br>
[![Canvas-BC1.png](https://i.postimg.cc/50fhGcsz/Canvas-BC1.png)](https://postimg.cc/3ybf4q5r)<br>

**Description**
<br>​En este bounded context se gestionan los registros de bovinos y vacunas.  

**Strategic Clasification**
<br>Su clasificación estratégica se divide en:

- **Core:** Este bounded context es Core porque gestiona procesos fundamentales del negocio ganadero: el registro de bovinos y el control de vacunaciones.

- **Compliance Enforcer:** Este bounded context es Compliance Enforcer porque es vital para la existencia del negocio. Esto se debe a que, sin un registro controlado del ganado, el negocio no podría operar de manera efectiva y cumplir con los objetivos esperados. Además, documentar correctamente las vacunaciones permite enfrentar inspecciones, auditorías o exportaciones sin riesgos legales ni pérdidas económicas.

- **Custom Built:** En este contexto, la clasificación de la evolución es Custom Built porque cada empresa puede desarrollar su propia versión de este sistema para adaptarlo a sus necesidades particulares, ya sea por diferencias en procesos, normativas locales o integración con otros sistemas internos.

**Domain Role**
<br>Esta área es responsable de ejecutar los procesos operativos clave relacionados con el registro de bovinos y el control de vacunaciones, permitiendo trazabilidad básica del estado vacunal de cada animal. Por lo cual, el tipo de rol asumido es execution context.

**Inbound Communication**
<br>Los Ranchers pueden crear, editar o eliminar registros de bovinos y vacunas.

**Outbound Communication**
<br>Los bovinos registrados y asignados en un establo podrán ser seleccionados para una campaña. Además, tras haber completado el registro de bovinos y vacunas, se habilitará la opción de realizar consultas que serán enviadas y resueltas en AssistVet Management.


<br>**Bounded Context: AssistVet Management**<br>
[![Canvas-BC2.png](https://i.postimg.cc/8CgQRfWt/Canvas-BC2.png)](https://postimg.cc/hXs5gj2d)<br>

**Description**
<br>El propósito de este bounded context es realizar diagnósticos y responder consultas sobre los bovinos y las vacunas mediante el uso de inteligencia artificial especializada. 

**Strategic Clasification**
<br>Su clasificación estratégica se divide en:

- **Supporting:** No logra ser parte del core business; sin embargo, es un área fundamental necesaria para que las funciones core cumplan su propósito. Por lo tanto, es Supporting.

- **Compliance enforcer:** Este bounded context es Compliance enforcer porque incorpora diagnósticos y respuestas que aseguran recomendaciones vitales para respetar regulaciones sanitarias oficiales, como los calendarios de vacunación y alertas sobre enfermedades reportables.

- **Product:** La inteligencia artificial está disponible para todo el mundo con variedad de versiones. Por ello, en este contexto, la clasificación de la evolución es de tipo Product al poder alcanzar el nivel de un producto en el mercado que esté listo para usar con diferentes versiones.

**Domain Role**
<br>Este contexto asume el rol de un Analysis Context, ya que su responsabilidad principal es analizar grandes cantidades de información para generar conocimientos útiles (insights). Utiliza técnicas de inteligencia artificial y lógica de negocio para emitir diagnósticos, sugerencias y respuestas automáticas, apoyando la toma de decisiones basada en datos dentro del sistema veterinario.

**Inbound Communication**
<br>Un Rancher solicita asesoría veterinaria y realiza una consulta al asisten veterinario. El asistente veterinario responde utilizando inteligencia artificial integrada al negocio, lo cual lo convierte en un sistema externo.  

**Outbound Communication**
<br>Los Ranchers reciben sus respuestas y pueden resolver consultas sobre bovinos o vacunas. Con dicha información, recibe sugerencias para tomar acción en la gestión del ganado y actualizar información importante de ser necesario.


<br>**Bounded Context: Campaign Management**<br>
[![Canvas-BC3.png](https://i.postimg.cc/3xvQ0Fyk/Canvas-BC3.png)](https://postimg.cc/PCTRBZQH)<br>

**Description**
<br>Campaign Management consiste en gestionar y coordinar campañas ganaderas, como vacunaciones, control sanitario, evaluaciones reproductivas o nutricionales, a lo largo de períodos definidos. Administra datos como el objetivo de la campaña, duración, fechas, trabajadores asignados y establos involucrados.
  
**Strategic Clasification**
<br>Su clasificación estratégica se divide en:

- **Core:** Este bounded context es Core porque forma parte esencial del negocio ganadero. La ejecución eficiente de campañas incide directamente en la productividad, salud animal y cumplimiento de los objetivos estratégicos del rancho.

- **Compliance Enforcer:** Este contexto se alinea principalmente con un Compliance Enforcer. Esto es debido a que al estructurar y documentar las actividades ganaderas dentro de campañas bien definidas, se asegura el cumplimiento de normativas sanitarias y legales concretas, protegiendo la reputación y la existencia del negocio.

- **Custom Built:** En este contexto, la clasificación de evolución es Custom Built porque las empresas desarrollan sus propias versiones de gestión de campañas adaptadas a sus necesidades específicas, métodos operativos y reglamentaciones locales.

**Domain Role**
<br>Este contexto actúa como un Execution Context, ya que su función principal es planificar, coordinar y ejecutar actividades operativas clave dentro de plazos definidos. Esto incluye campañas de vacunación, desparasitación, inseminación artificial, entre otras.

**Inbound Communication**
<br>El Livestock Rancher puede crear campañas, actualizar su información y cancelarlas de ser necesario. Además, contará con un servicio externo de gestión del clima.

**Outbound Communication**
<br>Ranch Management recibe eventos al momento de ingresar una campaña, permitiendo seleccionar un establo (grupo de bovinos) disponible. Además, el Livestock Rancher recibirá una confirmación para iniciar la campaña.

<br>**Bounded Context: Staff Administration**<br>
[![Canvas-BC4.png](https://i.postimg.cc/xdGrtj3Y/Canvas-BC4.png)](https://postimg.cc/Lqs0spW0)<br>

**Description**
<br>Este bounded context se encarga de administrar la información relacionada con el personal del rancho, incluyendo su registro, asignación a campañas, horarios y disponibilidad. Su propósito es asegurar una gestión organizada del equipo de trabajadores necesario para las campañas ganaderas. 

**Strategic Clasification**
<br>Su clasificación estratégica se divide en:

- **Supporting:** Este bounded context es Supporting porque no forma parte del core business de la ganadería, pero es esencial para que las actividades operativas puedan ejecutarse correctamente con personal disponible y capacitado.

- **Engagement:** Este bounded context es Engagement porque mejora la experiencia y organización del usuario dentro del sistema, permitiendo una mejor coordinación del personal. Es útil y valorado por los usuarios, pero no representa una fuente directa de ingresos, ya que no se paga por él: los usuarios lo aprecian, pero no pagan por ello.

- **Commodity:** En este contexto, la clasificación de evolución es Commodity porque la gestión del personal es una necesidad común en muchas industrias, por lo que puede ser estandarizada o delegada a herramientas de software comunes.

**Domain Role**
<br>Este contexto cumple el rol de Execution Context, ya que ejecuta procesos operativos clave como la asignación de personal y el control de la disponibilidad del mismo. Con llo se permite coordinar al equipo humano en función de las necesidades operativas del rancho y de las campañas.

**Inbound Communication**
<br>El Livestock Rancher puede registrar personal, buscarlos mediante filtros, actualizar su información o eliminar un trabajador del sistema.

**Outbound Communication**
<br>Los trabajadores en su registro son asignados a una campaña que deberán acudir si tienen disponibilidad.<br>


### 4.1.2. Context Mapping

A continuación se presentan las relaciones estructurales entre bounded contextos.

#### Context Map Patterns

![alt text](./assets/context-map-pattern-customer-supplier.png)

![alt text](./assets/context-map-pattern-parternship.png)

![alt text](./assets/context-map-pattern-open-host-service.png)


### 4.1.3. Software Architecture
#### 4.1.3.1. Software Architecture Context Level Diagrams
#### 4.1.3.2. Software Architecture Container Level Diagrams

El Diagrama de Contenedores proporciona un nivel de detalle más profundo, mostrando los contenedores principales dentro de VacApp. Estos incluyen la aplicación web, la aplicación móvil, la API y la base de datos. Este diagrama ilustra cómo los diferentes componentes interactúan entre sí, permitiendo que los usuarios gestionen sus ganados, vacunas, salud y alimentación de manera eficiente. También muestra cómo la aplicación se comunica con sistemas externos, como el servicio de pronóstico del tiempo y las bases de datos de razas.

![containers](./assets/Structurizr-VacAPP-Containers.png)

#### 4.1.3.3. Software Architecture Deployment Diagrams



# 4.2. Tactical-Level Domain-Driven Design

## 4.2.1. Bounded Context: Campaign Management
### 4.2.1.1. Domain Layer
### 4.2.2.3. Application Layer
### 4.2.1.4. Infrastructure Layer
### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

![Campaign Management Containers](./assets/Campaign-Management-Components.png)

### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams
#### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.1.6.2. Bounded Context Database Design Diagram

## 4.2.2. Bounded Context: Ranch Management 
### 4.2.2.1. Domain Layer

### 4.2.2.2. Interface Layer

### 4.2.2.3. Application Layer

### 4.2.2.4. Infrastructure Layer

### 4.2.2.5. Bounded Context Software Architecture Component Level Diagrams

![Ranch Management Containers](./assets/Ranch-Management-Components.png)


### 4.2.2.6. Bounded Context Software Architecture Code Level Diagrams
#### 4.2.2.6.1. Bounded Context Domain Layer Class Diagrams
#### 2.6.2.6.2. Bounded Context Database Design Diagram





