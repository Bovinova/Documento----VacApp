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
| TB1         | 23/08/2024  | Sergio André Gómez Vallejos       | Implementación de contenido en el Student Outcome   | 
| TB1         | 23/08/2024  | Sergio André Gómez Vallejos       | Solution Profile y Antecendetes y problemática  | 
| TB1         | 23/08/2024  | Sergio André Gómez Vallejos       |  Competidores y Desarrollo del perfil de integrante  | 
| TB1         | 23/08/2024  | Sergio André Gómez Vallejos       |  Analisis Competitivo  |  
| TB1         | 24/08/2024  | Sergio André Gómez Vallejos       | Registro de 1 entrevista del segmento objetivo Productores Ganadores independientes |  



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
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software | 1. Gómez Vallejos, Sergio André: desarrollo de secciones clave como el Solution Profile, Antecedentes y problemática, el análisis de Competidores, y el Análisis competitivo. También realicé el Tactical-Level Domain-Driven Design y el Bounded Context Database Design Diagram. Para ello, estudié conceptos de diseño táctico, arquitectura basada en dominios y modelado de datos. <br><br> 2. Rojas Velasquez, Maycol Jhordan ------ <br><br> 3. Aranda Vallejos, Oscar Gabriel ------ <br><br> 4. Ticona Panduro, Estrella del Pilar ------ <br><br> 5. Durand Vera, Gianfranco Angel ------ <br><br> 6. Miranda Sinarahua, Piero Stephano ------ <br><br> |Sergio André Gómez Vallejo: A través de estas acciones, adquirí conocimientos actualizados en diseño de software y arquitectura de dominios. Esto me permitió tomar decisiones fundamentadas para el desarrollo del proyecto, mejorar mi capacidad técnica y entender mejor el valor del análisis estructurado para una solución eficaz. |  
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software |  1. Gómez Vallejos, Sergio André:  Para cada sección del trabajo investigué nuevas metodologías de análisis competitivo, bases de Domain-Driven Design, y enfoques de diseño de bases de datos adaptados a contextos delimitados. Utilicé documentación especializada, artículos académicos y experiencias de la industria como base para mis decisiones de diseño. <br><br> 2. Rojas Velasquez, Maycol Jhordan ------ <br><br> 3. Aranda Vallejos, Oscar Gabriel ------ <br><br> 4. Ticona Panduro, Estrella del Pilar ------ <br><br> 5. Durand Vera, Gianfranco Angel ------ <br><br> 6. Miranda Sinarahua, Piero Stephano ------ <br><br> | Sergio André Gómez Vallejos: Reafirmé que el aprendizaje continuo es esencial en el mundo tecnológico actual. Este proyecto me ayudó a incorporar nuevos enfoques que antes no dominaba y fortaleció mi compromiso con seguir aprendiendo y adaptándome a los cambios del entorno profesional. |

# OBJETIVOS SMART

| Estudiante | Objetivo SMART |
|------------|-----------|
|Maycol Jhordan Rojas Velasquez | Mi Objetivo es poder alcanzar un desempeño profesional en analisis forense y en el diseño de nuevas apliaciones moviles, que ayuden en la sociedad, siguiendo todo lo aprendido y gestionando correctamente las buenas practicas.
|Sergio André Gómez Vallejos | Mi objetivo es desarrollarme profesionalmente en el área de ciberseguridad (SOC) y en el desarrollo de aplicaciones móviles, demostrando los conocimientos adquiridos y creciendo continuamente a través de la experiencia y el tiempo.

# 1. CAPÍTULO I: Presentacion
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

__Nombre del Start:__ VacApp

VacApp es una avanzada aplicación movil diseñada para capacitar a los ganaderos en la gestión eficiente y sostenible de su ganado. Esta plataforma ofrece una amplia gama de herramientas integrales que permiten a los usuarios realizar un seguimiento detallado de la salud, alimentación y reproducción de sus animales, lo que facilita una mejor toma de decisiones en la granja. Con VacApp, los ganaderos pueden optimizar sus operaciones y maximizar sus ingresos, al tiempo que promueven prácticas agrícolas sostenibles y éticas, lo que contribuye al bienestar de los animales y al desarrollo sostenible de la industria ganadera.

<img src="./assets/Bovinova.png" alt="vacapp Logo" style="width: 250px; height: 250px;">

### **Colaboraciones Estrategicas:**

En va, estamos comprometidos a establecer solidad alianzas con cadenas de ganaderia, pequeños ganaderos y empresas ganaderas. Trabajamos en estrecha colaboración con estos socios para garantizar que nuestras soluciones tecnológicas respondan a sus necesidades operativas, facilitando la gestión diaria y mejorando la satisfacción del cliente. Invitamos a los ganaderos a integrar nuestras soluciones para optimizar la administración de ganado, la gestión de alimentacion, y la atención al cliente, creando una experiencia más fluida y eficiente.

### **Innovación y Tecnología**
Nuestra plataforma utiliza tecnologías avanzadas para ofrecer una experiencia optimizada en la gestión ganadera. Desde el monitoreo de la salud, alimentación y reproducción del ganado, hasta la automatización de procesos clave en la granja, **VacApp** busca transformar la forma en que los ganaderos administran sus actividades diarias. Queremos que cada productor VacApp se sienta respaldado por una solución tecnológica que le permita tomar decisiones informadas, mejorar la eficiencia operativa y promover una producción sostenible y ética.

### **Comunidad y Funciones Sociales**
**VacApp** no es solo una herramienta de gestión; es también un espacio de aprendizaje y colaboración entre ganaderos. La plataforma incluye funciones que permiten a los usuarios compartir buenas prácticas, estrategias de manejo y mantenerse actualizados con las últimas innovaciones en el sector VacApp. Esta comunidad activa fomenta la mejora continua, el intercambio de conocimientos y el fortalecimiento de una red ganadera comprometida con el desarrollo sostenible y el bienestar animal.

### **Visión**
Visualizamos un mundo donde la tecnología y la ganadería se integran para impulsar una producción más eficiente, responsable y rentable. Nuestro objetivo es que **VacApp** sea sinónimo de innovación en el manejo ganadero, un aliado indispensable para los productores que desean evolucionar hacia un modelo más moderno, conectado y sostenible. Aspiramos a liderar una transformación positiva en la industria, basada en la tecnología, la ética y el compromiso con el campo.

### **Misión**
Nos esforzamos por ofrecer una plataforma integral que empodere a los ganaderos con herramientas inteligentes de gestión, mejorando su productividad y calidad de vida. Estamos decididos a utilizar la tecnología como motor de cambio en el sector VacApp, contribuyendo al bienestar animal, la sostenibilidad ambiental y el desarrollo económico de las comunidades rurales. **VacApp**, impulsado por **va**, será símbolo de excelencia, innovación y compromiso con el futuro de la ganadería.


### 1.1.2. Perfiles de integrantes del equipo

| Integrante | Descripción |
| ---- | --- |
| ![Sergio](https://hackmd.io/_uploads/SkU_5d9cR.png) | Sergio André Gómez Vallejos – Ingeniería de Software – u20221d401 <br> Soy una persona resiliente que, sin importar cuántas veces caiga, siempre encuentra la manera de levantarse. Tengo habilidades sociales sólidas y una amplia experiencia en la resolución de problemas de código. Suelo ser el miembro más activo de mi equipo de trabajo. Me apasionan los lenguajes de programación y la tecnología, y constantemente me esfuerzo por alcanzar mis objetivos y contribuir al desarrollo del startup. |
| ![Oscar]() |Aranda Vallejos, Oscar Gabriel - U202218167 <br> |
|<img src="https://hackmd.io/_uploads/B1F_iuso0.jpg" alt="yo-3" style="width: 600px ; height: 200px;">|Maycol Jhordan Rojas Velasquez – Ingeniería de Software – u202219984<br>Elegí la carrera de Ingeniería de Software debido a mi gusto por la innovación y la implementación de la tecnología en cualquier rubro  social, de una manera creativa y en todos los aspectos. Me considero una persona creativa, en busca de ideas, estrategias con mente nueva. También me gusta escuchar ideas de mi equipo, dar ideas de mejora, evaluar las ventajas y desventajas . Además, tengo conocimientos de programación en C + +, HTML, Python,Angular,Backend en Java. Además, Tengo un enfoque responsable y dedicado mediante un aprendizaje rápido así puedo ayudar a mis compañeros en sus dudas. Por otro lado, mis hobbies son ver series, jugar , escuchar música, nadar y  manejar.|
| ![Estrella]()| Ticona Panduro, Estrella del Pilar - U202210659 <br> |
| ![Gianfranco]() | Durand Vera, Gianfranco Angel - U20201f640 <br>|
|![Piero]()| Miranda Sinarahua, Piero Stephano - U20181g752 <br> | 


## 1.2. **Solution Profile**

### **Descripción General de la Solución**

**VacApp** es una innovadora aplicación móvil diseñada específicamente para los ganaderos peruanos, tanto independientes como empresas ganaderas. La plataforma proporciona un conjunto integral de herramientas para la gestión eficiente y sostenible del ganado, incluyendo el monitoreo de la salud, la alimentación y la reproducción de los animales. VacApp tiene como objetivo mejorar la productividad de los ganaderos y promover prácticas éticas y responsables que contribuyan al bienestar animal y al desarrollo sostenible de la ganadería en Perú.

### **Características Clave de la Solución**

- **Monitoreo Integral del Ganado:** La plataforma permite a los usuarios llevar un seguimiento detallado de la salud y el bienestar de sus animales, asegurando que reciban atención adecuada en tiempo y forma.

- **Gestión de Alimentación:** VacApp ayuda a los ganaderos a planificar y gestionar la alimentación del ganado, garantizando que los animales reciban las raciones necesarias para su crecimiento y producción de manera saludable.

- **Gestión Reproductiva:** La aplicación facilita el seguimiento de los ciclos reproductivos, desde el celo hasta el parto, optimizando la producción y la calidad del ganado.

- **Acceso a Servicios Veterinarios:** Ofrece un sistema integrado para gestionar el acceso a consultas veterinarias, mejorando la atención médica de los animales y reduciendo pérdidas económicas por falta de cuidados adecuados.

- **Automatización de Procesos:** Facilita la gestión de los procesos operativos en la granja, ayudando a los ganaderos a ahorrar tiempo y recursos en tareas rutinarias.

- **Espacio Comunitario de Colaboración:** VacApp no solo es una herramienta de gestión, sino también un espacio donde los ganaderos pueden compartir buenas prácticas, consejos y mantenerse informados sobre innovaciones en el sector ganadero.

### **Beneficios de la Solución**

- **Mejor Gestión y Salud Animal:** Los ganaderos tienen acceso a herramientas que les permiten realizar un seguimiento eficiente de la salud y el bienestar de su ganado, reduciendo las pérdidas económicas causadas por enfermedades y accidentes.

- **Optimización de Recursos:** La solución permite una mejor administración de la alimentación y reproducción del ganado, lo que se traduce en una mayor productividad y rentabilidad.

- **Acceso a Tecnología Sostenible:** VacApp promueve prácticas de ganadería sostenible, mejorando las condiciones de vida del ganado y promoviendo el respeto por el medio ambiente.

- **Reducción de Costos:** La automatización y la mejora en la gestión operativa ayudan a reducir los costos en diversas áreas de la granja, mejorando la eficiencia general.

- **Educación y Soporte Continuo:** La plataforma ofrece recursos educativos que permiten a los ganaderos mantenerse actualizados con las mejores prácticas y desarrollos tecnológicos del sector.

### **Tecnología y Arquitectura**

VacApp está diseñada para ser una solución móvil accesible en plataformas Android e iOS, desarrollada con las tecnologías más avanzadas para asegurar su rendimiento y facilidad de uso. La plataforma utiliza un enfoque basado en datos para proporcionar recomendaciones personalizadas y predicciones que mejoren la gestión de la granja. Además, ofrece integración con sistemas de salud animal y automatización de tareas administrativas.

### 1.2.1 **Antecedentes y problemática**

Mediante la técnica de **“5W's & 2H’s”**, hemos identificado los antecedentes y la problemática que enfrentan los ganaderos peruanos en su día a día, lo que ha llevado al desarrollo de **VacApp**.

#### **What? (¿Qué?)**

El sector ganadero en Perú enfrenta desafíos significativos relacionados con la gestión del ganado, la salud, la alimentación, la reproducción y la producción de los animales. Sin embargo, la falta de herramientas tecnológicas adecuadas ha dificultado una gestión eficiente. Los ganaderos, especialmente los pequeños productores, carecen de acceso a sistemas que permitan un seguimiento detallado de sus animales y una toma de decisiones informada, lo que reduce su capacidad para optimizar operaciones y mejorar los ingresos.

#### **When? (¿Cuándo?)**

Este problema es de carácter continuo. La necesidad de una plataforma tecnológica que ayude a gestionar el ganado y optimizar la producción es actual y permanente. Los ganaderos deben contar con un sistema que les permita acceder a información en tiempo real, actualizando constantemente los datos sobre salud, alimentación, reproducción y venta del ganado.

#### **Where? (¿Dónde?)**

La problemática afecta principalmente a las zonas rurales y áreas productivas de Perú, donde la mayoría de los ganaderos se encuentran en condiciones de acceso limitado a servicios veterinarios y tecnológicos. La falta de acceso a internet en algunas regiones también limita el uso de soluciones digitales, pero con el crecimiento de la conectividad móvil, **VacApp** tiene la capacidad de operar en dispositivos móviles accesibles desde cualquier ubicación rural.

#### **Who? (¿Quién?)**

Los principales afectados son los ganaderos peruanos, tanto independientes como grandes empresas ganaderas. Los productores independientes, que poseen pequeñas cantidades de ganado, tienen recursos limitados para acceder a tecnologías y servicios de salud adecuados para sus animales. Por otro lado, las grandes empresas ganaderas también enfrentan dificultades relacionadas con la gestión masiva del ganado y el cumplimiento de estándares de bienestar animal. Además, veterinarios, encargados de alimentación y otros actores del sector ganadero son usuarios clave de la plataforma.

#### **Why? (¿Por qué?)**

La falta de herramientas adecuadas para la gestión eficiente del ganado genera una serie de problemas, como una mala alimentación, enfermedades no tratadas a tiempo, baja productividad, y pérdida económica. La toma de decisiones basadas en información incompleta o errónea afecta directamente el bienestar de los animales y las ganancias de los productores. **VacApp** busca resolver esta problemática proporcionando a los ganaderos una herramienta que les permita optimizar sus operaciones, mejorar la trazabilidad de los animales y facilitar la toma de decisiones informadas.

#### **How? (¿Cómo?)**

La solución propuesta por **VacApp** es una plataforma web y móvil que integra herramientas de gestión ganadera. La aplicación permite a los usuarios realizar un seguimiento detallado de la salud, alimentación y reproducción de sus animales, generar informes, y recibir notificaciones sobre eventos importantes relacionados con su ganado. Utilizando tecnologías modernas de desarrollo web y móvil, **VacApp** se adapta a las necesidades de los ganaderos en zonas rurales, brindando acceso a los datos en tiempo real desde cualquier dispositivo con conexión a internet.

#### **How much? (¿Cuánto?)**

El costo de desarrollar y mantener **VacApp** dependerá de la inversión en infraestructura tecnológica, desarrollo de funcionalidades adicionales y la implementación de soporte técnico. Sin embargo, el impacto económico para los ganaderos será positivo, ya que les permitirá mejorar su rentabilidad, optimizar los recursos y reducir pérdidas derivadas de la mala gestión. La plataforma también permitirá reducir costos en atención veterinaria mediante el acceso oportuno a datos que puedan prevenir enfermedades y mejorar la productividad del ganado.

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

<table>
   <tr>
      <td align="center" colspan="6">Competitive Analysis Landscaspe</td>
   </tr>
   <tr>
      <td colspan="2">¿Porqué llevar a cabo este análisis?</td><td colspan="4">¿Cómo podemos proporcionar un buen servicio entre los restaurantes y los consumidores de manera que la comunicación entre ambos sea efectiva y agradable?</td>
   </tr>
   <tr align="center">
      <td colspan="2"><td>VacApp</td><td>Control Ganadero</td><td>Agroptima</td><td>App Ganadera</td>
   </tr>
   <tr>
      <td rowspan="2">Perfil</td><td>Overview</td><td> VacApp es una plataforma móvil accesible que optimiza la gestión ganadera con enfoque en sostenibilidad, bienestar animal y eficiencia, adaptada a pequeños y grandes productores. </td><td> Es una aplicación español, británico y brasileño en el sector de la ganadería. </td><td> Agroptima es un sitio web multiplataforma cofundado por la unión europea para los países de España, Francia e Inglaterra </td><td> Es una empresa fundada en Colombia que cuenta con una para la gestión de ganado. </td>
   </tr>
   <tr>
      <td>Ventaja competitiva. ¿Qué valor ofrece a los clientes?</td><td>La plataforma se diferencia al integrar tecnología accesible con enfoque en sostenibilidad y bienestar animal, ofreciendo soluciones prácticas para productores de todos los tamaños. </td><td> es una app para la gestión de vacas y enfocada para móviles </td><td> cuenta con multiplataforma cuenta con algoritmos matemáticos para una mayor gestión del ganado. </td><td> Tiene gran variedad de herramientas y gran cantidad de distribuidores </td>
   </tr>
   <tr>
      <td rowspan="2">Perfil de Marketing</td><td>Mercado Objetivo</td><td> Productores ganaderos, tanto independientes como empresas, que buscan optimizar el cuidado del ganado y mejorar su rentabilidad. </td><td> Para ganaderos españoles, brasileños e ingleses. </td><td> Para ganaderos españoles,franceses e ingleses. </td><td> Para ganaderos colombianos </td>
   </tr>
   <tr>
      <td>Estrategias de Marketing</td><td> Difusión en redes sociales y anuncios pagados </td><td> Estrategia de posicionamiento </td><td> Estrategia de segmentación </td><td> Estrategia </td>
   </tr>
   <tr>
      <td rowspan="3">Perfil de Producto</td><td>Productos & Servicios</td><td> Aplicación móvil con herramientas de gestión de ganado, monitoreo de salud, alimentación y reproducción.

 </td><td> Web app de gestión de ganado. </td><td> Web app de gestión de ganado. </td><td> Web app de gestión de ganado. </td>
   </tr>
   <tr>
      <td>Precios & Costos</td><td> Subscripcion Bajo costo </td><td> Subscripcion Bajo costo </td><td> Subscripcion Bajo costo </td><td> Subscripcion Bajo costo </td>
   </tr>
   <tr>
      <td>Canales de distribución (Web y/o Móvil)</td><td> App </td><td> App </td><td> Web y móvil </td><td> App </td>
   </tr>

   <tr>
      <td rowspan="5">Análisis SWOT</td><td>Fortalezas</td><td> Contamos con lo último en tecnología e implementamos lo nuevo en desarrollo para mejorar la productividad del servicio </td><td> Es una app netamente para la gestión de vacas cuenta con buena personalización </td><td> Es famoso por ser bueno en gestión ya que usa algoritmos matemáticos para un mejor cálculo del ganado. </td><td> Su ecosistema está basado en un país de origen conoce muy bien a sus clientes y se adapta a ellos </td>
   </tr>
   <tr>
      <td>Debilidades</td><td> Está en pleno desarrollo puede ser un éxito o fracaso </td><td> Solo es de móvil eso limita que sea multiplataforma </td><td> Solo opera en Europa y se basa en reglas ya establecidas por la unión europea </td><td> Solo es una app y para la zona de Colombia por lo tanto solo está disponible en su país de origen </td>
   </tr>
   <tr>
      <td>Oportunidades</td><td> Puede hacer productivos a los ganaderos y empresas de este rubro mejorando sus tomas de decisiones y eficiencia </td><td> Si planeas ir a Europa es buena idea ya que ese es su público objetivo y contará con más servicios. </td><td> Si planeas ir a Europa es buena idea ya que ese es su público objetivo y contará con más servicios. </td><td> Si eres colombiano estarás contento con la app ya que es de uso nacional. </td>
   </tr>
   <tr>
      <td>Amenazas</td><td> Competencia de otras aplicaciones móviles y el riesgo de cambios regulatorios en la industria ganadera que puedan afectar las operaciones de la plataforma. </td><td> No cuenta con muchos clientes la ganadería sigue siendo a la antigua por tanto no hace falta usarla. </td><td> No cuenta con muchos clientes la ganadería sigue siendo a la antigua por tanto no hace falta usarla. </td><td> Falta de apoyo económico los gobiernos locales de Colombia no ven viable esta innovación puede llegar a su desaparición </td>
   </tr>

</table> 

<br/>

### 2.1.2. Estrategias y tácticas frente a competidores.
Para enfrentarnos a la competencia en el sector ganadero, nuestra estrategia se centrará en ofrecer una plataforma accesible, intuitiva y adaptada a las necesidades locales de los ganaderos peruanos. A diferencia de competidores como Agroptima o Control Ganadero, VacApp destacará por su simplicidad y enfoque en la sostenibilidad y el bienestar animal, facilitando la gestión de la salud, alimentación y reproducción del ganado. Utilizaremos tácticas de marketing digital segmentadas, como campañas en redes sociales y alianzas con organizaciones locales, para aumentar la visibilidad de la aplicación y educar a los usuarios sobre sus beneficios. Además, ofreceremos precios flexibles y modelos de suscripción accesibles, lo que permitirá a pequeños y grandes productores optimizar sus operaciones sin complicaciones, mientras seguimos mejorando continuamente la plataforma para adaptarnos a las necesidades cambiantes del sector ganadero.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas
**Segmento #1: Productores Ganaderos Independientes**

VacApp ha desarrollado preguntas específicas para conocer las necesidades, experiencias y expectativas de los productores ganaderos independientes. Buscamos ayudarlos a gestionar mejor sus operaciones, optimizar el cuidado de sus animales y evaluar su impacto ambiental y social. A través de una plataforma intuitiva, VacApp ofrece herramientas que mejoran la eficiencia, el control de calidad y la conexión con los consumidores, simplificando los procesos diarios del productor.

**Datos Generales del Entrevistado:**

- Nombre: Christian Matos
- Edad: 25
- Tiempo de experiencia en la ganadería: 5 años

<img src="./assets/entrevista.png" alt="vacapp Logo" >


Link del video: https://youtu.be/S0HHlhplbSk

<br>

**Preguntas de la Entrevista:**


1. ¿Cómo decide la dieta de sus animales y qué factores considera al elegir su alimentación? 

   (¿Sigue asesoría veterinaria, experiencia personal o recomendaciones externas?)

1. ¿Qué medidas toma para garantizar la salud y el bienestar de sus animales?
1. ¿Qué aspectos considera más importantes en la gestión de la salud veterinaria de su ganado?
1. ¿Lleva algún tipo de registro sobre la salud y el crecimiento de sus animales? ¿Cómo lo hace?

   (¿Utiliza cuadernos, hojas de cálculo, aplicaciones móviles, etc.?)

1. ¿Cuáles son los principales desafíos que enfrenta al administrar su ganadería?
1. ¿Cómo cree que una aplicación podría ayudarle a resolver esos desafíos?
1. Si contara con una aplicación para apoyar su trabajo ganadero, ¿qué funciones le serían más útiles?
1. ¿Qué tipo de información le gustaría tener siempre disponible desde su celular o computadora?
1. ¿Cómo le gustaría registrar la alimentación y consumo de sus animales dentro de la aplicación?
1. ¿Qué beneficios espera lograr al implementar una solución como VacApp en su ganadería?
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
El diseño táctico en Domain-Driven Design (DDD) se enfoca en la implementación detallada del modelo de dominio dentro de un Bounded Context. A través de patrones como entidades, value objects, agregados, servicios, repositorios y fábricas, permite traducir el conocimiento del dominio en estructuras de software claras, cohesionadas y mantenibles. Esta sección describe cómo se aplican estos patrones en cada capa de la arquitectura.
### 4.2.X. Bounded Context: <Bounded Context Name>
#### 4.2.X.1. Domain Layer
#### 4.2.X.2. Interface Layer
#### 4.2.X.3. Application Layer
#### 4.2.X.4. Infrastructure Layer
#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams
#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams
##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams
##### 4.2.X.6.2. Bounded Context Database Design Diagram





