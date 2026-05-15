<div align="center">

<img src="assets/UPC_logo_transparente.png"></img><br>

<h3>Universidad Peruana de Ciencias Aplicadas</h3>
<h4>Facultad de Ingeniería</h4>
<h4>Carrera de Ingeniería de Software</h4>
<h4>Periodo 202610</h4>
<h4>1ASI0730 Aplicaciones Web</h4>
<h4>NRC 20177</h4>
<h4>Docente: Jose Miguel Flores ingaruca</h4>
<h4>Informe del Trabajo Final</h4>
<h4>Startup: ElectroCorp</h4>
<h4>Producto: Smart Control</h4>

| **Código** | **Apellidos y Nombres**               |
| :--------: | :------------------------------------ |
| U20241e179 | Tavara Correa, Sebastian Oswaldo      |
| U20241e107 | Tuncar Vila, Ghorghet Saul|
| U20241e014 | Cabrejos Chocco, Diego Alexander      |
| U202019498 | Fernandez Garfias Alexander Piero     |
| U20241e367 | Toro Turpo Ronal                      |

### Mayo 2026
</div>
<div style="page-break-after: always;"></div>


## Registro de Versiones del Informe

| Versión |  Fecha   |                                       Autor                                        |                                                  Descripción de modificación                                                   |
| :-----: | :------: | :--------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: |
|   TB1   | 22/04/2026 | Todos | Avance del trabajo: Completando el contenido del Documento |
|   TP1   |            |       |                                                            |
|   TB2   |            |       |                                                            |
|   TF1   |            |       |                                                            |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights
A continuación, se detallan los repositorios utilizados a lo largo del proyecto:

#### Link del repositorio del Reporte:

- https://github.com/1ASI0730-2610-20177-Nex/Report

#### Link del repositorio de la Landing Page:

- https://github.com/1ASI0730-2610-20177-Nex/LandingPage

#### Link del repositorio del Frontend:

- https://github.com/1ASI0730-2610-20177-Nex/Frontend

#### Link del repositorio del Backend:

- https://github.com/1ASI0730-2610-20177-Nex/Backend

### **Entrega TB1:**
[text]

##### Participación por integrante:

- 

# Contenido

## Índice

- [Registro de versiones del informe](#registro-de-versiones-del-informe)

- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Contenido](#contenido)

- [Student Outcome](#student-outcome-1)

- [Capítulo I: Introducción](#capitulo-i-introduccion)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de Integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hyphotesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis]()
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Persona](#231-user-persona)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification]()
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design]()
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment]()
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
      - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
      - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews]()
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heuristicas](#533-evaluaciones-segun-heuristicas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

Objetivo general, ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias.
| Criterio Especifico | Acciones realizadas | Conclusiones |
|--|--|--|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Sebastian Tavara <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Diego Cabrejos <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Ghorghet Tuncar <br> TB1: <br> TP1: <br> TB2: <br> TF1: |	 |
| Comunica por escrito con efectividad a diferentes rangos de audiencia | Sebastian Tavara <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Diego Cabrejos <br>TB1:<br> TP1: <br> TB2: <br> TF1: <br> <br> Ghorghet Tuncar <br> TB1: <br> TP1: <br> TB2: <br> TF1: |	 |


# Capitulo I: Introducción

## 1.1. StartUp Profile

### 1.1.1. Descripción de la StartUp
Es una startup de tecnologia enfocada en democratizar la domótica y la eficiencia energética para los hogares peruanos. 
<br><br>
Actualmesnte, el convertir una casa tradicional en un "hogar inteligente" es percibido como un lujo costoso, que requiere modificar el cableado eléctrico, contratar técnicos especializados y lidiar con aplicaciones genéricas que no reflejan la realidad del consumo local o que simplemente son complicados de comprender. Además, los altos costos de energía eléctrica son una preocupación constante para las familias y negocios nuevos.
<br><br>
Hemos desarrollado un ecosistema IoT (Internet de las Cosas) plug-and-play que se instala en minutos sobre los interruptores y enchufes existentes, sin necesidad de romper paredes, quebrar techos, ni alterar la red eléctrica. A través de nuestra plataforma web y móvil, los usuarios pueden controlar sus electrodomésticos de forma remota, podran programar horarios de encendido y monitorear el consumo de energia de su hogar en tiempo real.

---

## Misión

Nuestra misión es brindar a las familias peruanas soluciones de domótica accesibles y de fácil instalación que les permitan tomar el control de su consumo eléctrico, optimizando su presupuesto mediante tecnología inteligente.

---

## Visión

Queremos que ElectroCorp sea el referente en el Perú en gestión energética residencial, transformando los hogares tradicionales en espacios eficientes y sostenibles que alivien la economía familiar y contribuyan al cuidado del medio ambiente.

### 1.1.2. Perfiles de integrantes del equipo
| **Nombre Completo del integrante**    |	**Descripcion de la carrera** | **Fotografia** | **Conocimientos y habilidades**
| :------------------------------------ |:------------------------------------ |:------------------------------------ |:------------------------------------ |
| Tavara Correa, Sebastian Oswaldo      |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas | <img src="assets/foto-carnet-sebastian-tavara.jpg"> | Soy Sebastian Oswaldo Tavara Correa estudiante de la carrera de ingeniería de software, actualmente cursando el 5to ciclo, me considero una persona estudiosa y muy colaborativa al trabajar en grupo. Me adapto rápidamente a cualquier entorno. Me interesa desarrollar soluciones tecnológicas que tengan un impacto positivo. Creo que el desarrollo de software no debe limitarse en buscar la mayor funcionalidad, sino que también en generar bienestar en la sociedad.
| Tuncar Vila, Ghorghet Saul|Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/Ghorghet.png"> | Soy Ghorghet Saul Tuncar Vila, tengo 20 años de edad, estudio ingeniería de software en la UPC y estoy comprometido a seguir aprendiendo tecnologías que me ayuden en mi crecimiento como profesional. Me considero una persona empática, responsable, organizada y perfeccionista. Me apasiona aprender cada tema a profundidad y disfruto ayudando a los demás mientras doy lo mejor de mi en cada actividad.
| Cabrejos Chocco, Diego Alexander      |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas | <img src="assets/Diego_Cabrejos.jpg"> | Soy Diego Alexander Cabrejos Chocco estudiante de la carrera de ingeniería de software, actualmente cursando el 5to ciclo, soy una persona sociable, creativa, que trabaja bien en equipo y busco que todo el equipo participe en las actividades activamente. Me adapto rapidamente a la modalidad de trabajo. Mi meta es poder crear y desarrollar proyectos tecnologicos que tenga un impacto positivo y que sea entretenido. Lo mas interesante de la Software es que cada vez se va expandiendo, y las opciones para poder desarrollar algun proyecto por mas interesante o loco que paresca el tema, no es impedimento para desarrollar lo que desees. (claro que siempre siguiendo el tema legal)
| Fernandez Garfias, Alexander |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/foto_alexander.png"> | Soy Alexander, tengo 21 años y estudio Ingeniería de Software en la UPC. Tengo conocimientos en HTML, CSS y JavaScript, y he trabajado con Angular y Vue. También manejo C++, tengo nociones de Java y Flutter, y conocimientos en Domain-Driven Design (DDD) y Clean Architecture
|Toro Turpo Ronal|Ingenieria de Software Universidad Peruana de Ciencias Aplicadas|<img src="assets/foto_ronal.png">|Soy Ronal, Tengo 21 años y estudio la carrera de ingenieria de software en la UPC. Tengo conocimeintos intermedios en tecnologias como HTML, CSS leguajes de porgramcion como c++, java y java script.


## 1.2 *Solution Profile*
### 1.2.1 Antecedentes y problemática
La energía eléctrica, es uno de los recursos más importantes de nuestra sociedad actual, ayudándonos a desarrollar multiplicidad de tareas, ya sea en hogares, instituciones educativas, espacios publicos, sector empresarial, etc.
En la última década, el ecosistema IoT ha experimentado un crecimiento exponencial, impulsado por la miniaturización de componentes, el abaratamiento de los sensores y la mejora en las infraestructuras de conectividad (como el Wi-Fi de alta velocidad y el 5G). Por ejemplo los enchufes inteligentes, que ayudan al gestionamiento de la energía eléctrica empleando sensores. 
Sin embargo, estas soluciones tecnológicas están diseñadas y comercializadas casi exclusivamente para sectores de alto poder adquisitivo. Los enchufes inteligentes y sistemas de gestión energética suelen encontrarse en residencias exclusivas, hoteles de lujo o infraestructuras corporativas. Pero qué sucede con aquellas personas o familias que quieren gestionar su electricidad o controlar su energía en casa, pero que no cuentan con los recursos necesarios para poder costearse estos lujos.

## "5W" & "2H"

| Elemento | Pregunta | Definición para ElectroCorp |
| :--- | :--- | :--- |
| ("Who") Quién | ¿A quién afecta el problema / Quién es el usuario? | Familias peruanas y dueños de negocios nuevos que buscan reducir sus gastos de luz y modernizar sus espacios, pero no cuentan con el presupuesto o el conocimiento técnico para domótica tradicional. |
| ("What") Qué | ¿Cuál es el problema / Qué se ofrece? | La barrera económica y técnica para tener un hogar inteligente. La solución es un ecosistema IoT *plug-and-play* controlado mediante una plataforma web y móvil para gestionar el consumo eléctrico. |
| ("Where") Dónde | ¿Dónde ocurre el problema / Dónde se usará? | En los hogares tradicionales y negocios (enfocado inicialmente en zonas urbanas del Perú), específicamente sobre los interruptores y enchufes eléctricos ya existentes. |
| ("When") Cuándo | ¿Cuándo ocurre / Cuándo se usará? | De forma continua (24/7). Los usuarios interactuarán con el sistema cada vez que necesiten encender/apagar dispositivos, programar horarios o revisar su facturación proyectada. |
| ("Why") Por qué | ¿Por qué es importante resolverlo? | Porque el alto costo de la energía eléctrica es una preocupación constante que afecta la economía familiar, y la domótica actual es inaccesible, invasiva y compleja. |
| ("How") Cómo | ¿Cómo se va a resolver? | Desarrollando dispositivos que se sobreponen a las instalaciones actuales sin romper paredes ni cables, conectados vía Wi-Fi a una aplicación intuitiva que centraliza el control y monitoreo de la energía. |
| ("How much") Cuánto | ¿Cuánto costará / Cuál es el impacto? | Se requiere mantener un costo de producción y venta significativamente menor al de la domótica invasiva tradicional, garantizando que el ahorro en la factura de luz justifique la inversión del usuario a corto plazo. |

## Objetivos
Objetivo General:
Nuestro objetivo general es el diseñar, desarrollar e implementar un ecosistema de Internet de las Cosas (IoT) de arquitectura plug-and-play de facil entendimiento que permita a las familias y nuevo negocios en el Perú gestionar su consumo eléctrico de manera eficiente, optimizando su gasto económico y fomentando la sostenibilidad a través de una plataforma de software: una app y/o sitio web.

Objetivos Específicos
Desarrollo Tecnológico: Implementar una arquitectura de software escalable que integre una plataforma web y móvil, permitiendo el control remoto y el monitoreo en tiempo real de los dispositivos conectados con una latencia menor a 5 segundos.
Impacto Económico: Desarrollar un algoritmo de análisis de datos que proporcione proyecciones de facturación mensual en soles, facilitando la identificación de hábitos de consumo ineficientes para reducir el gasto eléctrico del hogar.

## Restricciones
Restricciones de Alcance (Scope)
Integración de terceros: En su primera versión, el ecosistema IoT operará exclusivamente a través de la plataforma web y móvil propietaria de ElectroCorp. No se contemplará la integración con asistentes de voz de terceros (como Amazon Alexa, Google Assistant o Apple HomeKit) para mantener el enfoque en la robustez de la interfaz nativa.

Restricciones de Tiempo y Costo
Cronograma de Desarrollo: El ciclo de vida del proyecto está estrictamente sujeto al calendario académico regular. Todas las fases de diseño, desarrollo, pruebas y despliegue deben completarse y documentarse para coincidir con los hitos de entrega programados (TB1, TP1, TB2 y TF1).

### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
Los hogares urbanos y pequeños negocios en el Perú enfrentan grandes dificultades para modernizar su infraestructura eléctrica y adoptar tecnologías de domótica. Actualmente, convertir una vivienda tradicional en un "hogar inteligente" es percibido como un lujo costoso que requiere modificaciones invasivas en el cableado, la ruptura de paredes y la contratación de técnicos especializados. Esta situación limita el acceso a la tecnología y mantiene una preocupación constante por los altos costos de energía eléctrica, los cuales afectan directamente la economía de las familias de clase media y la rentabilidad de los nuevos emprendimientos.

El problema central es que los propietarios y administradores carecen de una herramienta digital accesible y adaptada a la realidad de las viviendas con más de 10 años de antigüedad, que les permita monitorear y controlar el consumo de energía de manera sencilla. Las soluciones actuales en el mercado son complejas de configurar o utilizan aplicaciones genéricas que no reflejan el gasto real en moneda local (Soles). La ausencia de un control eficiente contribuye a desperdicios energéticos y sobrecostos significativos en los recibos de luz, representando una carga económica que impacta el presupuesto mensual de los usuarios.

ElectroCorp responde a esta necesidad con un ecosistema IoT plug-and-play diseñado para instalarse en minutos sobre interruptores y enchufes existentes, sin necesidad de alterar la red eléctrica ni realizar obras civiles. A través de nuestra plataforma web y móvil intuitiva, facilitamos el control remoto de dispositivos, la programación de horarios y el monitoreo del consumo en tiempo real. Esto no solo democratiza el acceso a la domótica en el Perú, sino que empodera al usuario para optimizar su gasto energético y transformar su entorno en un espacio eficiente y sostenible.

#### 1.2.2.1 Lean UX Assumptions

 + **User Assumptions:** 

###### ¿Quién es el usuario?

Los usuarios de ElectroCorp se dividen en dos grupos principales. Primero, los usuarios residenciales, conformados por familias de clase media que viven en zonas urbanas con viviendas de infraestructura antigua y buscan reducir su gasto mensual de luz sin realizar obras civiles. Segundo, los usuarios comerciales, que incluyen dueños y administradores de pequeños negocios (talleres, oficinas y restaurantes) que necesitan optimizar sus costos operativos y asegurar que sus equipos eléctricos funcionen de manera eficiente y segura.

###### ¿Dónde encaja nuestro producto, en su trabajo o en su vida?

En el ámbito residencial, ElectroCorp se integra en la vida diaria y en la planificación financiera del hogar, permitiendo a los usuarios gestionar su entorno de manera remota y consciente. En el ámbito comercial, se convierte en una herramienta estratégica de gestión operativa que ayuda a los dueños de negocios a controlar el gasto energético de sus locales y mejorar la seguridad al finalizar la jornada laboral.

###### ¿Qué problema resuelve nuestro producto?

ElectroCorp soluciona la alta barrera de entrada a la domótica en el Perú, eliminando la necesidad de modificar el cableado eléctrico o realizar costosas remodelaciones. Resuelve la falta de visibilidad sobre el consumo energético real, permitiendo a los usuarios identificar qué dispositivos generan un gasto excesivo y tomar medidas preventivas para reducir el monto de sus recibos de luz en moneda local.

###### ¿Cuándo y cómo se utiliza nuestro producto?

La plataforma se utiliza de forma continua mediante el monitoreo en tiempo real desde dispositivos móviles o web. Los usuarios interactúan con ella principalmente al salir de casa o del negocio para verificar que todo esté apagado, al programar horarios automáticos para electrodomésticos de alto consumo (como termas o maquinaria) y al recibir notificaciones de alerta cuando se detectan picos de consumo inusuales.

###### ¿Qué características son importantes?

- Instalación física no invasiva (Plug & Play) sobre interruptores y enchufes existentes.

- Monitoreo del consumo eléctrico traducido directamente a Soles (S/).

- Control remoto y programación de horarios desde una interfaz web y móvil sencilla.

- Sistema de alertas preventivas ante consumos elevados o dispositivos encendidos innecesariamente.

- Interfaz en español diseñada para ser comprendida por usuarios sin conocimientos técnicos avanzados.

###### ¿Cómo debe verse y comportarse nuestro producto?

ElectroCorp debe proyectar una imagen de modernidad, eficiencia y simplicidad. La interfaz debe ser intuitiva y fluida, con indicadores visuales claros (gráficos de consumo) que faciliten la interpretación de los datos financieros. El comportamiento del sistema debe ser altamente confiable y seguro, transmitiendo al usuario la tranquilidad de tener el control total de su infraestructura eléctrica en la palma de su mano.

 + **Business Outcomes:**

1. **Creo que mis clientes necesitan:** Una forma económica y sencilla de automatizar su hogar y controlar su gasto eléctrico sin hacer obras.

2. **Estas necesidades se pueden resolver con:** Un ecosistema IoT plug-and-play que se instala sobre la infraestructura eléctrica existente.

3. **Mis clientes iniciales son (o serán):** Familias de clase media en zonas urbanas con viviendas de más de 10 años e inquilinos de departamentos.

4. **El valor #1 que un cliente quiere de mi servicio es:** Ahorro de dinero en el recibo de luz y comodidad en el control de sus dispositivos.

5. **El cliente también puede obtener estos beneficios adicionales:** Mayor seguridad al evitar cortocircuitos por equipos encendidos y reportes de consumo detallados.

6. **Voy a adquirir la mayoría de mis clientes a través de:** Publicidad segmentada en redes sociales (Facebook/Instagram) y alianzas con ferreterías locales.

7. **Haré dinero a través de:** La venta directa del hardware (kits) y un modelo de suscripción opcional para funciones avanzadas de análisis de energía.

8. **Mi competencia principal en el mercado será:** Marcas globales como Xiaomi y Sonoff, además de enchufes genéricos en retail.

9. **Los venceremos debido a:** Nuestra instalación no invasiva (sin cables) y la visualización de costos directamente en Soles (S/).

10. **Mi mayor riesgo de producto es:** Que el hardware no encaje físicamente en algunos modelos de interruptores antiguos muy específicos.

11. **Resolveremos esto a través de:** Pruebas piloto con usuarios reales y el diseño de adaptadores universales ajustables.

12. **¿Qué otras suposiciones tenemos?:** Suponemos que la conexión Wi-Fi en los hogares peruanos es lo suficientemente estable para el control remoto.


#### 1.2.2.1 Lean UX Hypothesis Statements

###### Hipótesis 1:

Creemos que al ofrecer dispositivos IoT que no requieren modificar el cableado eléctrico ni realizar obras civiles, lograremos una adopción masiva en hogares urbanos con infraestructura antigua. Esto será posible gracias a un sistema de instalación externa que se coloca sobre los interruptores existentes, eliminando la necesidad de técnicos especializados.

**Business Outcome:** Alta penetración en el mercado de viviendas antiguas y reducción de barreras de entrada para nuevos clientes.  
**Users:** Familias de clase media en viviendas urbanas antiguas e inquilinos que no pueden modificar su infraestructura.  
**User Outcome:** Automatización inmediata del hogar sin costos de instalación profesional ni daños a la propiedad.  
**Feature:** Hardware IoT plug-and-play adaptable a interruptores y enchufes tradicionales.

###### Hipótesis 2:

Consideramos que si proporcionamos una plataforma digital (web y móvil) intuitiva, en español y adaptada al contexto local, los usuarios tendrán mayor confianza y utilizarán el sistema de manera regular para gestionar sus hogares y negocios.

**Business Outcome:** Incremento en la retención de usuarios activos y fidelización de marca mediante una experiencia de uso simplificada.  
**Users:** Usuarios residenciales y dueños de pequeños negocios con diversos niveles de habilidades tecnológicas.  
**User Outcome:** Acceso sencillo y seguro al control de dispositivos eléctricos sin barreras de idioma o complejidad técnica.  
**Feature:** Interfaz de usuario (UI) intuitiva con guías de configuración integradas en español.

###### Hipótesis 3:

Suponemos que al demostrar un ahorro tangible en el recibo de luz mediante el monitoreo del consumo en Soles (S/) en tiempo real, los clientes estarán dispuestos a pagar por el producto y recomendarlo activamente en su entorno.

**Business Outcome:** Crecimiento sostenido de ventas basado en el retorno de inversión (ROI) positivo para el cliente y recomendaciones boca a boca.  
**Users:** Jefes de hogar y administradores de pequeños negocios preocupados por los altos costos fijos de energía.  
**User Outcome:** Reducción del gasto mensual de energía y optimización del presupuesto familiar o comercial. 
**Feature:** Panel de monitoreo de consumo en tiempo real con conversión automática de Watts a Soles (S/).

#### 1.2.2.1 Lean UX Canvas


<table>  
<tr>  
<td>  
<h2>Business Problem</h2>  
- La mayoría de las soluciones de domótica requieren modificar la infraestructura eléctrica, lo que encarece su implementación.  <br>
- Los hogares en el Perú no están diseñados para la automatización, generando barreras técnicas.  <br>
- Existe poca accesibilidad a soluciones IoT económicas para familias de ingresos medios y bajos.
</td>  
<td>  
<h2>Solutions</h2>  
-   Módulo IoT "No-Neutro" ultracompacto: Un dispositivo basado en ESP32 y relé que sea lo suficientemente pequeño para caber en las cajas eléctricas estándar de las paredes peruanas sin requerir el cable neutro. <br>
-   Interruptores _Plug & Play_: Placas de interruptores táctiles o físicos que ya traigan el módulo inteligente integrado y se instalen exactamente igual que un interruptor tradicional. <br>
-  Kits de inicio pre-configurados:** Paquetes como "Kit Habitación" o "Kit Sala" donde los dispositivos ya vienen emparejados entre sí, listos para instalar sin configuraciones complejas.
</td>  
<td>  
<h2>Business Outcomes</h2>  
- Incrementar la adopción de hogares inteligentes en sectores urbanos y semiurbanos.  <br>
- Reducir los costos energéticos en hogares y pequeños negocios mediante control eficiente. <br>  
- Posicionar a SmartHome Control como solución peruana innovadora y accesible.
</td>  
</tr>  
<tr>  
<td>  
<h2>Users</h2>  
- Familias de clase media en zonas urbanas que buscan comodidad y ahorro energético. <br>
- Propietarios de pequeños negocios y oficinas que desean optimizar consumo eléctrico.
</td>  
<td></td>  
<td>  
<h2>User Outcomes & Benefits</h2>  
- Automatizar el control de luces y dispositivos sin hacer modificaciones costosas.  <br>
- Gestionar sus electrodomésticos desde el celular o la computadora, en tiempo real.  <br>
- Obtener reportes o alertas sobre el estado de los dispositivos para mayor seguridad y eficiencia.
</td>  
</tr>  
<tr>  
<td>  
<h2>Hypotheses</h2>  
- Dispositivos sin obras facilitarán la adopción masiva en viviendas antiguas. <br>
- Una app intuitiva en español generará mayor confianza y uso regular. <br>
- Visualizar el ahorro económico en soles (S/) mediante el monitoreo en tiempo real motivará la compra.
</td>  
<td>  
<h2>What’s the most important thing we need to learn first?</h2>  
- Validar la confianza del usuario en la seguridad del hardware no invasivo. <br>
- Confirmar si el monitoreo en Soles (S/) es un factor decisivo de compra. <br>
- Verificar la estabilidad de la conexión Wi-Fi en viviendas de infraestructura antigua.
</td>  
<td>  
<h2>What’s the least amount of work we need to do to learn the next most important thing?</h2>  
- Lanzar una Landing Page con video demostrativo y lista de espera.  <br>
- Realizar entrevistas a profundidad con dueños de hogares y pequeñas empresas.  <br>
- Crear un Mock-up interactivo del panel de control de ahorro en Soles.
</td>  
</tr>  
</table>

## 1.3 Segmentos objetivo
El proyecto busca atender a usuarios que requieren soluciones de automatización accesibles y no invasivas, con un enfoque en dos segmentos principales:

- Hogares urbanos con viviendas antiguas (más de 10 años de construcción).  
Este segmento comprende familias de clase media que residen en departamentos y casas en zonas urbanas, donde la infraestructura eléctrica fue instalada hace más de una década y no está diseñada para la domótica. Según el Censo Nacional 2017 del INEI, aproximadamente 79,3 % de la población peruana vive en áreas urbanas (INEI, 2017). Dada la antigüedad de gran parte de estas viviendas, existe una alta necesidad de modernización mediante soluciones que no requieran remodelaciones eléctricas costosas. Nuestro producto responde directamente a esta problemática al ofrecer automatización sin modificaciones en el cableado.
- Pequeños negocios y talleres en zonas urbanas.  
Este segmento incluye comercios, oficinas, talleres y restaurantes que buscan optimizar el uso de sus dispositivos eléctricos, reducir costos operativos y mejorar la seguridad. En el Perú, las micro y pequeñas empresas representan el 99,2 % del tejido empresarial nacional (Ministerio de la Producción, 2023) y más del 91 % de ellas operan en zonas urbanas (ComexPerú, 2022). Estos negocios generalmente se establecen en locales con instalaciones tradicionales, lo que dificulta la implementación de domótica. SmartHome Control ofrece una solución práctica y económica, adaptada a su infraestructura y a sus necesidades de ahorro energético.
# Capitulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
En este apartado, examinamos el ecosistema de soluciones existentes en el mercado peruano que ofrecen servicios de automatización residencial y gestión de dispositivos eléctricos. 
### 2.1.1 Análisis Competitivo
A través de esta comparativa, buscamos determinar el valor diferencial de ElectroCorp frente a las alternativas globales. El análisis se enfoca en detectar necesidades no resueltas por las grandes marcas, especialmente en lo que respecta a la adaptabilidad a la infraestructura eléctrica peruana (instalación sin obra civil) y la interpretación financiera del consumo energético en moneda local.

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="6"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5"> Queremos saber cómo está posicionado cada posible competidor con nuestro producto, así podemos detectar ventajas competitivas y diferenciar nuestra propuesta de valor.</td>
  </tr>
  <tr>
    <td colspan="2">Nombre y logo de competidor</td>
    <td><b>ElectroCorp <img src="assets/logo_electrocorp.jpeg" alt="Smart" width="120" height="120" /> </b></td>
    <td><b> Sonoff Peru</b> <img src="assets/sonoff.png" width="120" height="120" /> </td>
    <td><b>Xiaomi Mi Smart Plug</b> <img src="assets/xiaomi.png" width="120" height="120" /> </td>
    <td><b>Smart Plugs</b> <img src="assets/promart.png" width="120" height="120" /> </td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td> Startup peruana de tecnología enfocada en democratizar la domótica mediante un ecosistema IoT plug-and-play que se instala sobre interruptores y enchufes existentes sin modificar el cableado eléctrico. </td>
    <td> Ofrece variedad en enchufes, interruptores, relés WIFI y dispositivos para automatización del hogar. Su funcionamiento es simple, se conecta directamente a la red electrica y se controla mediante la app eWeLink.</td>
    <td>Es un enchufre inteligente que convierte cualquier dispositivo electrico en un aparato “inteligente”. Permitiendo asi: encender/apagar remotamente, programar horarios y controlar el consumo electrico desde la app llamada “Xiaomi Home”.</td>
    <td>Promart entre muchos otros productos comercializa enchufes inteligentes (Smart Plugs) Con la funcion de poder encender/apagar remotamente, temporizador, conexion WIFI y control mediante la app.</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td> - Instalación no invasiva (sin técnicos ni obras civiles).<br> - Monitoreo de consumo en Soles (S/) en tiempo real<br>- Una plataforma diseñada específicamente para la realidad del consumo eléctrico en Perú. </td>
    <td> - Variedad en productos que se adaptan a distintos aparatos y situaciones (no solo enchufes, también interruptores y relés). <br> -Precio accesible <br> -Soporte local y venta directa en Perú.</td>
    <td> -Marca reconocida a nivel mundial por su calidad y confiabilidad<br>-Integración directa con el ecosistema Xiaomi (atractivo para personas que cuenten con dispositivos Xiaomi).</td>
    <td> -Disponibilidad, hay tiendas fisicas a nivel nacional<br>-Facilidad de compra y confianza al ser una cadena de empresas conocida en Peru.<br>-Precios competitivos en relacion a productos similares</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>- Familias de clase media en zonas urbanas con viviendas de más de 10 años de antigüedad.<br>- Micro/pequeñas empresas (talleres, restaurantes) que buscan reducir costos operativos.</td>
    <td>-Personas interesadas en automatizar su vivienda a bajo precio y sin necesidad de conocimientos tecnicos.<br>- Personas jovenes y familias que buscan comodidad (encender/apagar)<br>- Emprendedores pequeños (restaurantes, oficinas, talleres).</td>
    <td>-Consumidores que ya tengan productos xiami, ya sea celulares, camaras, aspiradoras)<br>-Jovenes y familias que tengan alto uso de tecnologia y preferencia por marcas reconocidas<br>- Personas que valoran la calidad y seguridad certificada.</td>
    <td>-Familias que son clientes recurrentes de Promart ya se para compras del hogar.<br>- Personas que no tienen conocimiento en tecnologia y buscan algo facil de instalar.</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>- Marketing de contenidos sobre ahorro energético.<br>- Enfoque en la facilidad de autoinstalación ("Hazlo tú mismo").<br>- Presencia activa en canales digitales dirigidos a emprendedores y jefes de hogar.</td>
    <td>-Venta directa online en su tienda web.<br>- Marketing digital por medio de redes sociales (Facebook, Instagram).<br>- Estrategia de precios accesibles al consumidor.</td>
    <td>-Integracion de un dispositivo mas al ecosistema de Xiaomi<br>
- Branding Fuerte, Xiaomi al ser una marca con reconocimiento global, hace transmitir confianza al cliente.</td>
    <td>
-Presencia de tiendas Promart a nivel nacional, lo que da confianza al cliente.<br>
- Promociones y descuentos por temporadas.<br>
- Estrategia de Conveniencia: facil de conseguir, comprar y devolver en casos de problemas.</td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos y Servicios</b></td>
    <td>- Adaptadores IoT para interruptores y enchufes, aplicación móvil en español y plataforma web para programación de horarios y gestión de eficiencia energética. </td>
    <td>-Ofrece enchufes inteligentes, interruptores WIFI, relés, sensores, etc. También ofrece soporte técnico local, tutorías y asesoría de uso básico.</td>
    <td>Su producto principal es el enchufe inteligente compacto, se integra con la app “Xiaomi Home” y con el ecosistema Xiaomi</td>
    <td>-Encufhes inteligentes importados (marcas genéricas).</td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td> Rango de precios accesible para la clase media (aprox. S/ 70 - S/ 120), posicionándose como una inversión de rápido retorno mediante el ahorro de luz.</td>
    <td> Enchufes desde S/ 60 – S/ 100</td>
    <td>Desde S/ 90 a S/ 130.</td>
    <td>Desde S/ 60  a S/ 100</td>
  </tr>
  <tr>
    <td><b>Canales de distribución (Web y/o móvil)</b></td>
    <td>- Plataforma web oficial.<br>- Aplicación móvil propia y posibles alianzas estratégicas con ferreterías locales.</td>
    <td>-Web Principal (sonoffperu.com)<br>
- Distribución en redes sociales y Marketplace peruano</td>
    <td>
-Tiendas Online Oficiales (ShopMi.pe, Linio, MercadoLibre)<br>
-Tiendas fisicas (malls).</td>
    <td>
-Tiendas fisicas Promart. <br>
-Tienda online Promart.pe<br>
- App movil de Promart.</td>
  </tr>
  <tr>
    <td rowspan="5"><b>Análisis SWOT</b></td>
    <td colspan="5">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>- Instalación simple sin obra civil.<br>- Conocimiento profundo del mercado local (tarifas en Soles).<br> - Solución adaptada a infraestructura antigua.</td>
    <td>- Variedad de productos. <br>
    - Precios accesibles<br>
- Soporte tecnico y garantia local<br>
- Compatibilidad con ecosistemas como Google y Alexa</td>
    <td>
- Marca reconocida globalmente.<br>
- Ecosistema bien consolidado<br>
- Fuerte presencia en retail y e-commerce peruanos.</td>
    <td>
- Muchas tiendas fisicas en Peru.<br>
- Disponibilidad inmediata y confianza en la compra.</td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>- Marca nueva con presupuesto limitado para publicidad masiva frente a gigantes globales.</td>
    <td>- Depende de importacion (no produce localmente)</td>
    <td>
- Precios más altos que competidores locales.<br>
- Dependencia del ecosistema Xiaomi.</td>
    <td>
- Productos genericos con poca diferenciacion.<br>
- Sin ecosistema propio.<br>
- Dependencia de proveedores externos.</td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>- Incremento constante de las tarifas eléctricas en el mercado peruano.<br> - Gran volumen de viviendas urbanas que necesitan modernización.</td>
    <td>
- Mercado local con poca competencia especializada.<br>
- Posibilidad de diferenciarse ofreciendo instalación y soporte.</td>
    <td>
- Posibilidad de cross-selling para maximizar ganancias.<br>
- Tendencia global hacia la domótica segura y certificada.</td>
  <td>
- Captar al consumidor no especializado que busca soluciones rápidas.<br>
- Posibilidad de aliarse con marcas reconocidas para diferenciar su oferta.</td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>- Ingreso de nuevos dispositivos genéricos de bajo costo.<br> - Inestabilidad en los precios de componentes electrónicos y módulos Wi-Fi importados.</td>
    <td>
- Competencia de marcas globales con mayor presupuesto de marketing<br>
- Cambios en regulaciones eléctricas o certificaciones necesarias.</td>
    <td>
- Productos genéricos más baratos que cumplen funciones similares<br>
- Cambios en restricciones de importación o alzas en costos logísticos.</td>
    <td>
- Competidores Online que ofrecen más variedad.<br>
- Clientes que buscan marcas con ecosistemas establecidos.</td>
  </tr>
</table>

### **2.1.2 Estrategias y tácticas frente a competidores**
A partir del análisis competitivo realizado, se han definido las siguientes estrategias y tácticas para posicionar a ElectroCorp en el mercado peruano y afrontar las fortalezas de la competencia.

##### **1. Aprovechar la Fortaleza: Instalación No Invasiva y Enfoque en Hogares Peruanos**
**Estrategia**

Posicionarse como la única alternativa de automatización que no requiere modificaciones en el cableado eléctrico ni contratar técnicos especializados, diferenciándose de competidores como Sonoff que exigen instalaciones complejas.

**Tácticas**

- **Guías de Autoinstalación:** Producción de tutoriales en video enfocados en la instalación del sistema sobre interruptores y enchufes estándar de viviendas peruanas.
- **Kits para Departamentos Alquilados:** Desarrollo de paquetes de dispositivos diseñados específicamente para usuarios que no tienen permiso para romper paredes o techos.
- **Demostraciones en Tiendas Locales:** Realización de exhibiciones en ferreterías para mostrar que el hardware se instala en minutos sobre la red eléctrica existente.

**Valor Añadido**

- Eliminación de costos adicionales por contratación de electricistas o técnicos externos.
- Facilidad para retirar los dispositivos y llevarlos a una nueva vivienda sin dejar daños en la infraestructura.

##### **2.  Aprovechar la Oportunidad: Incremento de Tarifas Eléctricas y Necesidad de Ahorro**
**Estrategia**

Centrar la propuesta de valor en el control del presupuesto familiar mediante el monitoreo del consumo de energía en tiempo real y en moneda local (Soles).

**Tácticas**

- **Panel de Control en Soles:** Implementación de una interfaz en la aplicación que traduzca el consumo de Watts a Soles basándose en el pliego tarifario local.
- **Sistema de Alertas de Presupuesto:** Configuración de notificaciones móviles que avisen al usuario cuando el consumo se acerque a un límite de gasto mensual establecido.
- **Reportes de Consumo Real:** Generación de resúmenes semanales que identifiquen qué electrodomésticos generan el mayor gasto energético en el hogar.

**Valor Añadido**

- Gestión eficiente de la economía del hogar mediante información financiera clara y directa.
- Capacidad de tomar acciones preventivas para reducir el monto del recibo de luz antes de que termine el mes.

##### **3.  Afrontar la Amenaza: Presencia de Marcas Globales y Soluciones Genéricas**
**Estrategia**

Mitigar la desconfianza hacia los productos importados mediante la oferta de soporte técnico local y una plataforma adaptada a la realidad del consumo peruano.

**Tácticas**

- **Soporte Técnico por WhatsApp:** Establecimiento de un canal de atención directa en español para resolver dudas sobre la configuración inicial de la plataforma.
- **Garantía de Reemplazo Inmediato:** Implementación de un servicio de cambio de hardware rápido en Lima ante cualquier falla de fábrica, evitando esperas de importación.
- **Actualizaciones Basadas en el Usuario:** Desarrollo de nuevas funcionalidades en la plataforma web y móvil a partir de las sugerencias de los clientes locales.

**Valor Añadido**

- Respaldo y seguridad de una marca con presencia física y técnica en el país.
- Reducción de la incertidumbre al configurar dispositivos inteligentes gracias al acompañamiento personalizado.
## 2.2 Entrevistas
### 2.2.1. Diseño de entrevistas

##### Preguntas Generales

- ¿Cuál es su nombre?
- ¿Cuántos años tiene usted?
- ¿En qué ciudad y distrito reside?
- ¿A qué se dedica y cuál es su formación académica?

##### Preguntas Específicas

###### Segmento 1: Hogares urbanos con viviendas antiguas (mayor a 10 años de construcción)

1. ¿Cómo es el estado de las instalaciones eléctricas en su hogar actualmente?
2. ¿Qué tan seguido revisa su recibo de luz y qué siente al ver el monto final?
3. ¿Ha intentado implementar soluciones de "hogar inteligente"?
4. ¿Cuál es su mayor temor al pensar en contratar a un técnico para remodelar su casa?
5. ¿Qué electrodoméstico le gustaría poder apagar desde su celular si olvida hacerlo al salir?
6. ¿Cuánto tiempo estaría dispuesto a invertir en instalar una solución por su cuenta si no requiere herramientas?
7. ¿Le interesaría ver su consumo de energía traducido a Soles en tiempo real?
8. ¿Qué características buscaría en una aplicación para que sea fácil de usar para toda su familia?

###### Segmento 2: Pequeños negocios y talleres en zonas urbanas

1. ¿Qué equipos eléctricos son críticos para la operación diaria de su negocio o taller?
2. ¿Cómo asegura que todos los equipos queden apagados al cerrar el local?
3. ¿Qué impacto económico tiene el recibo de luz en la rentabilidad de su negocio o taller (bajo, moderado, crítico)?
4. ¿Ha tenido problemas por dejar equipos encendidos accidentalmente después del horario de cierre?
5. ¿Qué canales digitales utiliza para gestionar o promover su negocio actualmente?
6. ¿Qué funciones le darían más tranquilidad: programar horarios de encendido o recibir alertas de sobrecosto?
7. ¿Estaría dispuesto a invertir en una solución tecnológica que no requiera detener sus actividades para su instalación?
8. ¿Cuánto valoraría contar con un reporte que identifique los puntos críticos de desperdicio de energía en su local?


### 2.2.2. Registro de entrevistas 
URL del video:

Segmento 1: Hogares urbanos con viviendas antiguas

| N | Datos |Descripción |Imagen referencial
|--|--|--|--|
|1  | Nombre: Miguel Torres  <br>Edad: 20 <br>Distrito: Chosica|Miguel menciona que en su hogar las instalaciones ya son muy antiguas y algunos interruptores o tomacorrientes ya no funcionan. Por parte de los recibos del consumo energetico mensual, siente frustracion al ver un costo elevado y no saber que objetos o acciones son los que le causan ese consumo elevado. Por otro lado, el comenta que le gustaria poder apagar su cocina electrica, plancha y televisor, por que son los que mas tendencia tiene el a olvidar y piensa que son los que mas consumen energia. <br> El siente que invertiria 1-2 horas en instalar por cuenta propia una solucion de consumo energetico, que tenga un paso a paso y sea muy intuitivo.<br>Finalmente, agrega que si le gustaria que la app convierta su consumo en soles, que sea intuitiva y tenga un soporte tecnico ante cualquier inconveniente.<br> |<img src="assets/ImagenEntrevistaMiguel.jpg">
|2  | Nombre:  Francys <br>Apellido: Quispe <br>Edad: 20<br>Distrito: Chorrillos| Francys estudia diseño y desarrollo de Software. El estado de sus instalaciones electricas en su hogar estan en buenas condiciones ya que le realizan mantenimiento cada ciero tiempo. Ademas, el menciona que el dinero que paga mensual de energia es variable, le gustaria saber el motivo por el cual se eleva o disminuye. Tambien, el penso en implementar soluciones de hogar inteligente, mas por que en la carrera que el esta estudiando, esta rodeado constantemente de nuevas tecnologias.<br> Si el quisiera remodelar sus instalaciones electricas, su mayor temor es que el tecnico no este bien capacitado para realizar el trabajo.<br>Por ultimo, el quiere que la aplicacion sea intuitiva y facil de usar. |<img src="assets/Entrevista-Francys.png">
|3  | Nombre: Margarita<br>Apellido: Espinoza <br>Edad: 49<br>Distrito: Cieneguilla |Margarita representa a una ama de casa:<br>- Tener conectados los artefactos y servicios de cableado "normales"<br>- Controlar la energía empleada en ciertos artefactos<br>- Conocer técnicos especializados en mejorar experiencias de usuario|<img src="assets/Entrevista-Margarita_Espinoza.png">

Segmento 2: Pequeños negocios y talleres en zonas urbanas.


| N | Datos |Descripción |Imagen referencial
|--|--|--|--|
|1  | Nombre: Orlando<br>Apellido: Trinidad <br>Edad: 48<br>Distrito: La Victoria |El entrevistado Orlando Trinidad Parra, es un hombre de 48 años que reside en La Victoria. Se desempeña como microempresario del rubro textil, específicamente en la confección, operando un taller con varias máquinas industriales. Su negocio se encuentra dentro del segmento de pequeñas y medianas empresas (PYME), lo que implica recursos limitados y alta sensibilidad a los costos operativos.<br><br>Se percibe como una persona:<br>- Responsable y organizada ya que tiene trabajadores que limpian y apagan la maquina que trabajan.<br>- Abierta al cambio tecnológico, pero con criterio económico.<br><br>El taller usa diferentes equipos eléctricos tales como:<br>- Maquinas remalladoras.<br>- Maquinas rectas.<br>- Cortadora.<br>Se puede denotar que el consumo energético es alto y critico, impactando directamente la rentabilidad del negocio<br><br>Problemas detectados:<br>- Errores humanos frecuentes, especialmente en personal nuevo.<br>- Equipos que quedan encendidos o conectados innecesariamente.<br>- Desconocimiento del costo exacto por máquina, solo percibe el gasto total.<br><br>El entrevistado muestra interes en soluciones tecnologicas que le permitan:<br>- Medir el costo real por máquina (no solo consumo)<br>- Automatizar encendido/apagado<br>- Obtener reportes de desperdicio energético|<img src="assets/seg2 - img1.png">
|2  | Nombre: <br>Apellido: <br>Edad: <br>Distrito: ||<img src="assets/seg2_entrevista2.PNG">
|3  | Nombre: Lourdes<br>Apellido: Saldarriaga <br>Edad: 46<br>Distrito: La Victoria |Lourdes Saldarriaga, es una mujer de 46 años que reside en La Victoria. Es propietaria de una pequeña tintorería, lo que la ubica dentro del segmento de microempresas o negocios pequeños con operaciones intensivas en uso de equipos eléctricos.<br><br>Se percibe como una persona:<br>- Practica y operativa, enfocada en el funcionamiento diario del negocio más que en análisis detallados<br>- Consciente de riesgos, especialmente después de haber experimentado incidentes (recalentamiento de equipos).<br>- Precavida en inversión, muestra interés condicionado al costo.<br><br>El taller usa diferentes equipos eléctricos tales como:<br>- Lavadoras industriales<br>- Posibles secadoras<br>El negocio tiene dependencia directa de maquinaria eléctrica continua, lo que hace critico el control energético<br><br>Problemas detectados:<br>-Errores humanos: un trabajador olvidó apagar un equipo.<br>- Consecuencia directa: recalentamiento de maquinaria, lo que implica riesgo operativo y económico.<br>- Dependencia del personal para tareas críticas.<br><br>Necesidades detectadas:<br>- Programación automática de encendido y apagado (su prioridad principal)<br>- Monitoreo del consumo energético por máquina y horario<br>- Identificación de picos de consumo| <img src="assets/seg2 - img3.png">


### 2.2.3. Análisis de entrevistas 
#### Segmento 1: Hogares urbanos con viviendas antiguas

Características objetivas del segmento

- Rango de edad: 20 - 59 años.
- Ubicacion: 100% Lima
- Nivel educativo: 100% secundaria completa
- Ocupación: 
-- 75% independientes
-- 25% dependiente
- El segmento esta compuesto por adultos de mediana a mayor edad, con nivel educativo y estabilidad laboral modera.
<br>

Infraestructura del hogar
- 100% viviendas con mas de 10 años 
- 100% consideran que sus instalaciones eléctricas están en buen estado.
-- 25% menciona necesidad de mantenimiento
- Existe una percepción de seguridad y conformidad con la infraestructura actual.

Percepción del consumo
- 25% percepción negativa (preocupados)
- 75% percepción neutral/positiva

Características subjetivas del segmento
- 100% prácticos y orientados a lo funcional.
- 100% conservadores en adopción tecnológica.
- 75% confiados en su situación actual.
- 25 % preocupados activamente por el consumo.

Necesidades y motivaciones
- Control remoto de dispositivos (100%)
- Visualización del consumo en dinero (25%)

Insights clave
- Conformidad
-- 75% esta conforme
-- 25% esta preocupado.
- Interés sin accion.
-- 100% no usa la tecnología pero muestra interés en funciones.
- Simplicidad ante todo
-- el 100% pide facilidad de uso
-- el 75% desconfía de técnicos	
- Valor percibido en dinero
-- El 100% quiere ver el consumo eléctrico en soles.
  
## 2.3. Needfinding
### 2.3.1. User Personas 
Segmento 1: Hogares urbanos con viviendas antiguas

<img src="assets/User Persona - seg1 - Rosa Gutierrez.png" alt="UserPersona Rosa Gutierrez">

Segmento 2: Pequeños negocios y talleres en zonas urbanas.

<img src="assets/User Persona - seg2 - Carlos Mendoza.png" alt="UserPersona Carlos Mendoza">

### 2.3.2. User Task Matrix 

Segmento 1: Hogares urbanos con viviendas antiguas

| Tareas del usuario | Frecuencia | Importancia |
|--|--|--|
| Encender manualmente los dispositivos del hogar | Diario | Alta |
| Apagar manualmente los dispositivos antes de salir o dormir | Diario | Alta |
| Revisar el recibo de luz | Mensual | Alta |
| Supervisar el uso de electrodomésticos en casa | Semanal | Media |
| Ajustar el uso de aparatos según necesidad (uso básico) | Diario | Media |
| Consultar sobre el consumo eléctrico | Mensual/semanal | Media |
| Entender el monto de recibo de luz | Semanal | Alta |

Segmento 2:  Pequeños negocios y talleres en zonas urbanas.

| Tareas (Tasks) | Frecuencia | Importancia |
|--|--|--|
| Encender equipos al iniciar la jornada | Diario | Alta |
| Operar maquinaria durante la producción | Diario | Alta |
| Supervisar el uso correcto de equipos por el personal | Diario | Alta |
| Apagar equipos al finalizar la jornada | Diario | Alta |
| Verificar que todos los equipos estén apagados | Interdiario | Alta |
| Coordinar con el personal sobre el uso de máquinas | Diario | Media |
| Pagar el recibo de electricidad | Mensual | Alta |
| Revisar el gasto eléctrico del negocio | Mensual | Alta |
| Intentar identificar causas de alto consumo eléctrico | Mensual (baja) | Alta |
| Detectar errores o descuidos (equipos encendidos, fallas) | Mensual (baja) | Alta |

### 2.3.3. User Journey Mapping 

Segmento 1: Hogares urbanos con viviendas antiguas

<img src = "assets/UserJourneyMap - seg1.png" alt = "User Journey Map segmento 1">

Segmento 2: Pequeños negocios y talleres en zonas urbanas.

<img src = "assets/UserJourneyMap - seg2.png" alt = "User Journey Map segmento 2">

### 2.3.4. Empathy Mapping
Segmento 1: Hogares urbanos con viviendas antiguas.<br><img src="assets/EmpathyMap - Seg1.png"><br><br>Segmento 2: Pequeños negocios y talleres en zonas urbanas.<br><img src="assets/EmpathyMap - Seg2.png"><br>
## 2.4. Big Picture Event Storming
Nos reunimos como equipo mediante Miro para organizar nuestras ideas y desarrollar el Big Picture del proyecto. Durante la sesión realizamos una lluvia de ideas sobre las principales funcionalidades del sistema, identificando procesos como la vinculación de dispositivos, el control operativo, la automatización de rutinas y la gestión de accesos y seguridad. Esto nos permitió visualizar de manera general cómo interactuaría el usuario con la solución propuesta.<br><br><img src="assets/Big Picture Event Storming.png"><br>
## 2.5. Ubiquitous Language

El "Ubiquitous Language" será una herramienta esencial en nuestro trabajo, ya que nos permitirá establecer un lenguaje
común y compartido entre todos los miembros del equipo, facilitando la comunicación y la comprensión de los conceptos
clave en nuestro proyecto.

**Home User** :  A person who uses the platform to control and monitor the electricity consumption of their home through the mobile app or website.

**Business Owner**: A user who manages electrical devices in a commercial establishment and uses the platform to optimize energy usage, schedules, and access permissions.

**IoT Device**: A smart device connected to the system, such as a smart plug, switch, or meter, that can be monitored and controlled remotely.

**Pairing**: The process through which an IoT device is successfully linked to the user’s account within the platform.

**Guided Installation**: A step-by-step setup process that helps users configure the system easily without requiring technical assistance.

**Custom Device Name**: A personalized label assigned by the user to easily identify each device within the platform.

**Device Status**: The current condition of a device, such as turned on or turned off, displayed in real time.

**Remote Control**: A feature that allows users to turn devices on, turn them off, or manage them through the mobile app or website.

**Automation Routine**: A sequence of scheduled actions executed automatically at specific times, such as turning off devices at night.

**Scheduled Time**: A configured time that determines when a device or routine should start or stop.

**Energy Consumption**: The amount of electricity used by one or more devices during a specific period.

**Consumption History**: A record of energy usage data accumulated daily, weekly, or monthly.

**Consumption Alert**: A notification sent to the user when electricity usage exceeds a defined threshold.

**Saving Recommendation**: A suggestion generated by the system to reduce electricity usage and optimize costs.

**Access Profile**: A secondary or limited account created by the administrator to allow partial control of selected devices.

**Permissions**: Rules that define what actions each user is allowed to perform within the platform.

**Traceability**: A record of actions performed in the system, including who made the change, when it happened, and which device was affected.

**Billing Forecast**: An estimated monthly electricity cost in Peruvian soles, calculated using historical consumption and the current tariff.

# Capitulo III: Requirements Specification
## 3.1. User Stories
|**Epic/User Story ID**|**Título**|**Descripción**|**Criterio de aceptación**|**Relación (EPIC ID)**|
| - | - | - | - | - |
|**US-01**|Visualizar información de la startup y testimonios|<p>Como usuario visitante, quiero acceder a la descripción de la empresa y leer opiniones de usuarios para confirmar la calidad del servicio.</p>|<p>**Escenario 1:** Información consolidada</p><p>Dado que navego en la página,</p><p>Cuando hago scroll por el contenido,</p><p>Entonces leo sobre la democratización de la domótica y los testimonios de clientes reales.</p>|**EP-05**|
|**US-02**|Motor de búsqueda inteligente|<p>Como usuario visitante, quiero usar una barra de búsqueda para encontrar secciones de la página rápidamente.</p>|<p>**Escenario 1:** Búsqueda exitosa</p><p>Dado que busco información de costos,</p><p>Cuando escribo "precios" y doy clic a la lupa,</p><p>Entonces la página hace un scroll suave hacia "Our Plans".</p>|**EP-05**|
|**US-03**|Cambio de idioma (ES/EN)|<p>Como usuario visitante, quiero poder cambiar el idioma de la página web para leerla en mi idioma nativo.</p>|<p>**Escenario 1:** Traducción dinámica</p><p>Dado que la página está en inglés,</p><p>Cuando doy clic al ícono del mundo (ES),</p><p>Entonces todos los textos cambian instantáneamente al español.</p>|**EP-05**|
|**US-04**|Suscripción al boletín de noticias|<p>Como usuario visitante, quiero suscribirme al boletín en un formulario para recibir consejos de ahorro y ofertas.</p>|<p>**Escenario 1:** Envío de formulario</p><p>Dado que ingreso mi email en la sección de contacto,</p><p>Cuando presiono "Submit",</p><p>Entonces aparece un mensaje de agradecimiento temporal y la caja se limpia.</p>|**EP-05**|
|**US-05**|Interfaz interactiva (Menú y Audio)|<p>Como usuario visitante, quiero interactuar con un menú fluido y pausar/reproducir la música de fondo a mi gusto.</p>|<p>**Escenario 1:** Navegación y control</p><p>Dado que estoy en la web,</p><p>Cuando uso el Navbar dinámico o presiono el botón flotante de audio,</p><p>Entonces la página me redirige a la sección deseada o pausa la música (ElectroCorp.mp3).</p>|**EP-05**|
|**US-06**|Comparar planes de servicio|<p>Como usuario visitante, quiero ver las diferencias entre el plan Free y Enterprise para elegir el adecuado.</p>|<p>**Escenario 1:** Tarjetas de precio</p><p>Dado que bajo a la sección "Pricing",</p><p>Cuando visualizo las tarjetas,</p><p>Entonces noto que el plan Enterprise está resaltado como premium.</p>|**EP-05**|
|**US-07**|Registro inicial del usuario|<p>Como usuario del hogar, quiero crear una cuenta en la plataforma para vincular mis dispositivos.</p>|<p>**Escenario 1:** Registro Exitoso</p><p>Dado que el usuario no tiene cuenta,</p><p>Cuando ingresa su email y contraseña,</p><p>Entonces el sistema crea la cuenta.</p>|**EP-01**|
|**US-08**|Emparejar dispositivo|<p>Como usuario, quiero vincular un enchufe inteligente desde la app.</p>|<p>**Escenario 1:** Vinculación exitosa</p><p>Dado que el usuario está en "Agregar",</p><p>Cuando ingresa el código del equipo,</p><p>Entonces el equipo aparece en su lista.</p>|**EP-01**|
|**US-09**|Asistente de instalación|<p>Como usuario nuevo, quiero seguir una guía paso a paso para instalar el sistema.</p>|<p>**Escenario 1:** Tutorial de inicio</p><p>Dado que es el primer inicio de sesión,</p><p>Cuando el usuario entra a la app,</p><p>Entonces se muestra un tutorial de pasos básicos.</p>|**EP-01**|
|**US-10**|Nombrar dispositivos|<p>Como usuario, quiero asignar nombres personalizados a mis dispositivos.</p>|<p>**Escenario 1:** Edición de nombre</p><p>Dado que el equipo fue vinculado,</p><p>Cuando el usuario edita el nombre a "Lámpara",</p><p>Entonces el nuevo nombre se guarda en la base de datos.</p>|**EP-01**|
|**US-11**|Ver estado en tiempo real|<p>Como usuario, quiero ver si un dispositivo está encendido o apagado.</p>|<p>**Escenario 1:** Feedback visual</p><p>Dado que el usuario observa el dashboard,</p><p>Cuando un equipo cambia de estado físico,</p><p>Entonces el icono se actualiza en la app.</p>|**EP-02**|
|**US-12**|Encender y apagar remotamente|<p>Como usuario, quiero controlar mis dispositivos desde el celular.</p>|<p>**Escenario 1:** Acción remota</p><p>Dado que el equipo está apagado,</p><p>Cuando el usuario hace clic en encender,</p><p>Entonces el dispositivo cambia a ON.</p>|**EP-02**|
|**US-13**|Programar horarios de encendido|<p>Como usuario, quiero programar horarios automáticos.</p>|<p>**Escenario 1:** Creación de horario</p><p>Dado que el usuario selecciona un enchufe,</p><p>Cuando configura la hora de encendido,</p><p>Entonces el sistema respeta el horario diariamente.</p>|**EP-02**|
|**US-14**|Crear rutinas automáticas|<p>Como usuario, quiero definir rutinas de automatización general.</p>|<p>**Escenario 1:** Rutina nocturna</p><p>Dado que el usuario crea una rutina "Dormir",</p><p>Cuando llega la hora programada,</p><p>Entonces todos los dispositivos seleccionados se apagan a la vez.</p>|**EP-02**|
|**US-15**|Ver consumo en tiempo real|<p>Como usuario, quiero monitorear el consumo energético en vivo.</p>|<p>**Escenario 1:** Monitor de Watts</p><p>Dado que el enchufe está activo,</p><p>Cuando el usuario abre la gráfica,</p><p>Entonces visualiza los Watts consumidos actualizados.</p>|**EP-03**|
|**US-16**|Consultar historial de consumo|<p>Como usuario, quiero revisar el historial de consumo por día o semana.</p>|<p>**Escenario 1:** Filtro de historial</p><p>Dado que el usuario está en reportes,</p><p>Cuando selecciona "Últimos 7 días",</p><p>Entonces se muestra un gráfico diario.</p>|**EP-03**|
|**US-17**|Recibir alertas por alto consumo|<p>Como usuario, quiero recibir alertas por consumos inusuales de energía.</p>|<p>**Escenario 1:** Alerta en app</p><p>Dado que el límite es 500W,</p><p>Cuando se supera la cifra de manera sostenida,</p><p>Entonces aparece una notificación push.</p>|**EP-03**|
|**US-18**|Ver recomendaciones de ahorro|<p>Como usuario, quiero recibir sugerencias para ahorrar energía.</p>|<p>**Escenario 1:** Tips inteligentes</p><p>Dado que el consumo es ineficiente en cierto horario,</p><p>Cuando revisa el panel de sugerencias,</p><p>Entonces el sistema recomienda crear nuevas rutinas.</p>|**EP-03**|
|**US-19**|Administrar múltiples dispositivos|<p>Como usuario, quiero visualizar todos mis dispositivos en una sola pantalla.</p>|<p>**Escenario 1:** Vista general</p><p>Dado que el usuario tiene 5 equipos,</p><p>Cuando ingresa al inicio,</p><p>Entonces visualiza las 5 tarjetas operables.</p>|**EP-04**|
|**US-20**|Crear perfiles de acceso|<p>Como administrador, quiero dar acceso a familiares con permisos limitados.</p>|<p>**Escenario 1:** Rol de invitado</p><p>Dado que el administrador invita a un familiar,</p><p>Cuando este inicia sesión en su dispositivo,</p><p>Entonces solo puede apagar/encender equipos.</p>|**EP-04**|
|**US-21**|Bloquear acceso no autorizado|<p>Como usuario, quiero proteger mi cuenta de extraños.</p>|<p>**Escenario 1:** Timeout por inactividad</p><p>Dado que la app web queda abierta sin interactuar,</p><p>Cuando pasan 30 minutos sin uso,</p><p>Entonces la sesión expira.</p>|**EP-04**|
|**US-22**|Registrar actividad de control|<p>Como administrador, quiero ver quién controló un equipo.</p>|<p>**Escenario 1:** Log de auditoría</p><p>Dado que se ejecutó una acción,</p><p>Cuando se revisa el log de eventos,</p><p>Entonces se detalla el nombre del usuario y la hora.</p>|**EP-04**|
|**US-23**|Controlar equipos del negocio|<p>Como dueño de negocio, quiero controlar equipos del local desde mi móvil.</p>|<p>**Escenario 1:** Control comercial</p><p>Dado que el dueño está en su domicilio,</p><p>Cuando apaga el grupo de luz del local,</p><p>Entonces se refleja instantáneamente en el negocio.</p>|**EP-02**|
|**US-24**|Programar equipos por horario comercial|<p>Como dueño, quiero automatizar el local según el horario de atención.</p>|<p>**Escenario 1:** Automatización de horario</p><p>Dado que el horario es de 9am a 6pm,</p><p>Cuando se activa la rutina comercial,</p><p>Entonces los equipos siguen automáticamente el horario.</p>|**EP-02**|
|**US-25**|Revisar consumo por área o equipo|<p>Como dueño, quiero identificar qué áreas consumen más.</p>|<p>**Escenario 1:** Desglose por zona</p><p>Dado que hay varios equipos registrados,</p><p>Cuando revisa el reporte corporativo,</p><p>Entonces visualiza un gráfico detallado por zonas.</p>|**EP-03**|
|**US-26**|Compartir acceso con personal|<p>Como dueño, quiero permitir que empleados controlen ciertos equipos.</p>|<p>**Escenario 1:** Control limitado</p><p>Dado que un empleado de almacén entra a la app,</p><p>Cuando visualiza el dashboard principal,</p><p>Entonces solo ve el control de su área correspondiente.</p>|**EP-04**|
|**US-27**|Pagar suscripción con tarjeta|<p>Como usuario, quiero ingresar mi tarjeta de forma segura para adquirir el plan Premium.</p>|<p>**Escenario 1:** Pasarela Stripe</p><p>Dado que el usuario elige el plan Enterprise,</p><p>Cuando ingresa sus datos válidos,</p><p>Entonces Stripe procesa exitosamente el cobro mensual.</p>|**EP-06**|
|**US-28**|Cancelar suscripción Premium|<p>Como usuario, quiero anular mi suscripción para detener cobros.</p>|<p>**Escenario 1:** Detención de cobros</p><p>Dado que el usuario accede a configuración de facturación,</p><p>Cuando confirma la cancelación del servicio,</p><p>Entonces el plan se degrada a final de mes.</p>|**EP-06**|
|**US-29**|Recibir alertas por correo|<p>Como usuario, quiero que el sistema me notifique a mi correo si algo inusual pasa con mi consumo.</p>|<p>**Escenario 1:** Despacho vía Mailchimp</p><p>Dado que hay un evento crítico registrado,</p><p>Cuando el backend lo procesa,</p><p>Entonces recibo un email de alerta inmediata.</p>|**EP-07**|
|**US-30**|Recibir reporte mensual|<p>Como usuario, quiero recibir un resumen mensual en mi email para saber cuánto ahorré.</p>|<p>**Escenario 1:** Envío automatizado</p><p>Dado que es el último día del mes,</p><p>Cuando el cronjob se activa,</p><p>Entonces me envía un correo con mis estadísticas.</p>|**EP-07**|
|**US-31**|Recuperar contraseña|<p>Como usuario, quiero poder restablecer mi contraseña si la olvido.</p>|<p>**Escenario 1:** Email de recuperación</p><p>Dado que el usuario hace clic en "Olvidé mi contraseña",</p><p>Cuando ingresa su email,</p><p>Entonces recibe un enlace seguro por tiempo limitado.</p>|**EP-04**|
|**US-32**|Editar perfil de usuario|<p>Como usuario, quiero cambiar mis datos personales de perfil.</p>|<p>**Escenario 1:** Guardado de cambios</p><p>Dado que el usuario edita su nombre o teléfono,</p><p>Cuando da clic en guardar,</p><p>Entonces la información se actualiza en la base de datos MySQL.</p>|**EP-04**|
|**US-33**|Eliminar cuenta|<p>Como usuario, quiero borrar definitivamente mi cuenta y datos.</p>|<p>**Escenario 1:** Purga de información</p><p>Dado que el usuario confirma la eliminación total,</p><p>Cuando el sistema procesa la solicitud,</p><p>Entonces sus datos se borran irreversiblemente.</p>|**EP-04**|
|**US-34**|Configurar preferencias|<p>Como usuario, quiero elegir qué tipo de alertas me llegan.</p>|<p>**Escenario 1:** Switch de preferencias</p><p>Dado que el usuario apaga el interruptor de correos mensuales,</p><p>Cuando se guarda la preferencia,</p><p>Entonces su email es removido de la lista de envíos de resúmenes.</p>|**EP-07**|
|**US-35**|Simular conexión de equipo|<p>Como desarrollador, quiero simular un dispositivo nuevo para pruebas de la plataforma.</p>|<p>**Escenario 1:** Inyección de dispositivo virtual</p><p>Dado que se dispara el evento simulador mediante API,</p><p>Cuando ocurre la validación,</p><p>Entonces el equipo aparece en la cuenta del usuario.</p>|**EP-01**|
|**US-36**|Filtrar historial por fechas|<p>Como usuario, quiero establecer un rango de fechas para ver consumos pasados.</p>|<p>**Escenario 1:** Filtro de calendario</p><p>Dado que el usuario abre la herramienta de fechas,</p><p>Cuando selecciona desde y hasta,</p><p>Entonces la gráfica se redibuja excluyendo el resto de días.</p>|**EP-03**|
|**US-37**|Exportar historial a Excel|<p>Como usuario corporativo, quiero descargar mis datos de consumo.</p>|<p>**Escenario 1:** Generación de CSV</p><p>Dado que se visualiza la tabla en pantalla,</p><p>Cuando se hace clic en Exportar,</p><p>Entonces el navegador descarga un archivo CSV estructurado.</p>|**EP-03**|
|**US-38**|Agrupar dispositivos|<p>Como usuario, quiero agrupar mis enchufes por habitaciones.</p>|<p>**Escenario 1:** Operación masiva por grupo</p><p>Dado que el usuario ha creado el grupo "Iluminación Sala",</p><p>Cuando apaga el grupo,</p><p>Entonces todos los enchufes asignados a la sala se apagan simultáneamente.</p>|**EP-02**|
|**US-39**|Activar Modo Oscuro|<p>Como usuario, quiero activar un tema oscuro en mi dashboard para evitar la fatiga visual nocturna.</p>|<p>**Escenario 1:** Toggle Dark Mode</p><p>Dado que el usuario entra a configuraciones de UI,</p><p>Cuando activa el switch de Modo Oscuro,</p><p>Entonces los colores de la aplicación SPA cambian a la paleta Dark.</p>|**EP-05**|
|**US-40**|Gestionar múltiples locales|<p>Como dueño de negocio, quiero gestionar distintas sucursales desde una sola cuenta centralizada.</p>|<p>**Escenario 1:** Selector de Sucursal</p><p>Dado que el usuario posee el plan Enterprise,</p><p>Cuando despliega el menú de ubicaciones superior,</p><p>Entonces puede saltar del "Local A" al "Local B" cambiando el dashboard.</p>|**EP-04**|

<br><br>

**TECHNICAL STORIES**

|**Technical story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Epica**|
| - | - | - | - | - |
|**TS-01**|Maquetación y Responsive CSS|<p>**Como** desarrollador frontend</p><p>**Quiero** usar variables `:root` y media queries</p><p>**Para** un diseño escalable y móvil (US-01, US-06).</p>|<p>**Escenario 1: Estructura HTML/CSS**</p><p>Dado el código base de la landing,</p><p>Cuando se renderiza en 768px,</p><p>Entonces el diseño cambia de Flex-Row a Flex-Column.</p>|**EP-05**|
|**TS-02**|Sistema de Traducción i18n|<p>**Como** desarrollador frontend</p><p>**Quiero** un diccionario JSON y JS DOM manipulation</p><p>**Para** cambiar idiomas al instante (US-03).</p>|<p>**Escenario 1: Función applyTranslations**</p><p>Dado que corre el JS,</p><p>Cuando se llama `toggleLanguage()`,</p><p>Entonces los atributos `data-i18n` cambian su texto.</p>|**EP-05**|
|**TS-03**|Motor Búsqueda Inteligente|<p>**Como** desarrollador frontend</p><p>**Quiero** una función JS con diccionario de palabras clave</p><p>**Para** hacer scroll automático (US-02).</p>|<p>**Escenario 1: ScrollIntoView**</p><p>Dado que el evento listener recibe un "Enter",</p><p>Cuando el término existe en el array,</p><p>Entonces hace un `scrollIntoView({ behavior: 'smooth' })`.</p>|**EP-05**|
|**TS-04**|Eventos de Formulario (Newsletter)|<p>**Como** desarrollador frontend</p><p>**Quiero** interceptar el submit con JS</p><p>**Para** mostrar mensajes sin recargar la web (US-04).</p>|<p>**Escenario 1: preventDefault()**</p><p>Dado el clic en Enviar,</p><p>Cuando corre el event listener,</p><p>Entonces usa `e.preventDefault()`, muestra un `div` y hace `.reset()`.</p>|**EP-05**|
|**TS-05**|Controlador de Menú y Audio|<p>**Como** desarrollador frontend</p><p>**Quiero** instanciar un navbar dinámico y un `<audio>`</p><p>**Para** interactuar con la vista y la música (US-05).</p>|<p>**Escenario 1: DOM Events**</p><p>Dado el clic en el botón de música o scroll,</p><p>Cuando cambian los estados booleanos,</p><p>Entonces JS ejecuta `.play()` o altera el background del Header.</p>|**EP-05**|
|**TS-06**|Setup Spring Boot API|<p>**Como** backend developer</p><p>**Quiero** iniciar el servidor web Java</p><p>**Para** alojar los endpoints REST del sistema core.</p>|<p>**Escenario 1: Deploy inicial**</p><p>Dado el pom.xml con dependencias web,</p><p>Cuando compila el proyecto,</p><p>Entonces el contenedor Tomcat levanta en el puerto 8080.</p>|**EP-01**|
|**TS-07**|Conexión JPA - MySQL|<p>**Como** Database Admin</p><p>**Quiero** crear entidades Java anotadas con `@Entity`</p><p>**Para** que JPA cree automáticamente las tablas en MySQL (US-07).</p>|<p>**Escenario 1: Data Source**</p><p>Dado el application.properties configurado,</p><p>Cuando inicia el contexto de Spring,</p><p>Entonces Hibernate realiza la migración DDL en el esquema MySQL.</p>|**EP-01**|
|**TS-08**|Integración Stripe SDK|<p>**Como** backend developer</p><p>**Quiero** incorporar las librerías oficiales de Stripe</p><p>**Para** validar los tokens de pago de forma segura (US-27).</p>|<p>**Escenario 1: Charge API**</p><p>Dado un payload de pago válido,</p><p>Cuando invoca el método createCharge(),</p><p>Entonces Stripe retorna el id de transacción HTTP 200.</p>|**EP-06**|
|**TS-09**|Integración Mailchimp REST|<p>**Como** backend developer</p><p>**Quiero** programar un servicio de RestTemplate</p><p>**Para** disparar emails automatizados (US-29).</p>|<p>**Escenario 1: Post Payload**</p><p>Dado que se dispara una alerta,</p><p>Cuando se construye el JSON del email,</p><p>Entonces hace un POST a la API de Mailchimp y se registra el envío.</p>|**EP-07**|
|**TS-10**|Simulación Telemetría Cronjob|<p>**Como** backend developer</p><p>**Quiero** usar anotaciones `@Scheduled` en Spring Boot</p><p>**Para** inyectar falsos consumos eléctricos (US-35).</p>|<p>**Escenario 1: Tarea en background**</p><p>Dado el servidor en ejecución,</p><p>Cuando pasa el tiempo definido en el cron,</p><p>Entonces se insertan N registros aleatorios en la tabla de telemetría.</p>|**EP-03**|
|**TS-11**|Endpoints CRUD Dispositivos|<p>**Como** backend developer</p><p>**Quiero** programar controladores `@RestController`</p><p>**Para** manejar el listado y actualización de enchufes (US-19).</p>|<p>**Escenario 1: GetMapping**</p><p>Dado el request a `/api/v1/devices`,</p><p>Cuando se procesa la solicitud,</p><p>Entonces devuelve un ResponseEntity con el JSON del listado.</p>|**EP-02**|
|**TS-12**|Setup Angular SPA|<p>**Como** frontend developer</p><p>**Quiero** iniciar el framework SPA (Angular/React)</p><p>**Para** construir el dashboard de monitoreo interno.</p>|<p>**Escenario 1: Router Guard**</p><p>Dado el acceso a `/dashboard`,</p><p>Cuando el token no existe,</p><p>Entonces el sistema redirige al `/login`.</p>|**EP-04**|
|**TS-13**|Generación y Filtro de JWT|<p>**Como** fullstack developer</p><p>**Quiero** configurar Spring Security con un filtro JWT</p><p>**Para** autenticar cada petición HTTP (US-07).</p>|<p>**Escenario 1: Token Auth**</p><p>Dado el Bearer token en el Header,</p><p>Cuando pasa por el filtro de seguridad,</p><p>Entonces desencripta la firma y autoriza el request.</p>|**EP-04**|
|**TS-14**|Implementación librería Chart.js|<p>**Como** frontend developer</p><p>**Quiero** usar la API de Chart.js con un Canvas</p><p>**Para** dibujar las barras de consumo de Watts (US-15).</p>|<p>**Escenario 1: Render del Canvas**</p><p>Dado el array numérico de la API,</p><p>Cuando se pasan como `datasets`,</p><p>Entonces Chart.js dibuja visualmente la progresión.</p>|**EP-03**|
|**TS-15**|Cifrado de Contraseñas BCrypt|<p>**Como** backend developer</p><p>**Quiero** usar BCryptPasswordEncoder</p><p>**Para** no guardar las contraseñas en texto plano (US-07).</p>|<p>**Escenario 1: Hash**</p><p>Dado el formulario de registro,</p><p>Cuando llega la clave `123456`,</p><p>Entonces se guarda como un hash seguro tipo `$2a$10$...`.</p>|**EP-04**|
|**TS-16**|Modo Oscuro Angular UI|<p>**Como** frontend developer</p><p>**Quiero** crear un servicio Angular que modifique la clase del `body`</p><p>**Para** alternar las variables CSS globales (US-39).</p>|<p>**Escenario 1: Clase global**</p><p>Dado que el usuario presiona el switch,</p><p>Cuando el Subject cambia a `true`,</p><p>Entonces se añade la clase `.dark-theme` al document root.</p>|**EP-05**|

<br><br>

## 3.2. Impact Mapping
<img src="assets/Impact Mapping.png"><br>

## 3.3. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points |
|--|--|--|--|--|
| 1 | US-01 | Visualizar info y testimonios | Como visitante, quiero acceder a la descripción de ElectroCorp. | 3 |
| 2 | US-02 | Motor de búsqueda inteligente | Como visitante, quiero buscar por palabras clave y hacer scroll automático. | 5 |
| 3 | US-03 | Cambio de idioma (ES/EN) | Como visitante, quiero cambiar el texto entero de la página mediante el DOM. | 5 |
| 4 | US-04 | Suscripción al boletín | Como visitante, quiero llenar un input de email sin recargar la web. | 3 |
| 5 | US-05 | Interfaz interactiva | Como visitante, quiero navegar fluído y pausar la música con un botón. | 3 |
| 6 | US-06 | Comparar planes de servicio | Como visitante, quiero leer las diferencias del plan Free y Enterprise. | 2 |
| 7 | US-07 | Registro inicial del usuario | Como usuario, quiero crear una cuenta en la plataforma base de datos. | 5 |
| 8 | US-08 | Emparejar dispositivo plug-and-play | Como usuario, quiero vincular mi enchufe inteligente simulado. | 8 |
| 9 | US-09 | Asistente de instalación guiada | Como usuario, quiero un tutorial rápido para empezar. | 5 |
| 10 | US-10 | Nombrar dispositivos | Como usuario, quiero asignarle un alias a mi equipo. | 2 |
| 11 | US-11 | Ver estado en tiempo real | Como usuario, quiero verificar si mi foco virtual está ON u OFF. | 3 |
| 12 | US-12 | Encender y apagar remotamente | Como usuario, quiero enviar señales de apagado por internet. | 5 |
| 13 | US-13 | Programar horarios de encendido | Como usuario, quiero definir a qué hora se enciende mi luz. | 5 |
| 14 | US-14 | Crear rutinas automáticas | Como usuario, quiero configurar grupos de acciones masivas. | 5 |
| 15 | US-15 | Ver consumo en tiempo real | Como usuario, quiero ver una gráfica con el consumo de Watts vivo. | 5 |
| 16 | US-16 | Consultar historial de consumo | Como usuario, quiero ver cómo varió mi consumo durante los 7 días. | 5 |
| 17 | US-17 | Recibir alertas por alto consumo | Como usuario, quiero notificaciones si mis aparatos gastan demasiado. | 3 |
| 18 | US-18 | Ver recomendaciones de ahorro | Como usuario, quiero leer pequeños tips basados en mis propios datos. | 5 |
| 19 | US-19 | Administrar múltiples dispositivos | Como usuario, quiero ver la lista completa de lo que he enlazado. | 3 |
| 20 | US-20 | Crear perfiles de acceso | Como administrador, quiero que otros en casa puedan apagar las luces. | 5 |
| 21 | US-21 | Bloquear acceso no autorizado | Como usuario, quiero que la plataforma se cierre si me olvido abierta. | 3 |
| 22 | US-22 | Registrar actividad de control | Como administrador, quiero revisar un registro de qué se prendió. | 3 |
| 23 | US-23 | Controlar equipos del negocio | Como dueño, quiero gestionar mi pequeño local desde la casa. | 3 |
| 24 | US-24 | Programar equipos por horario comercial | Como dueño, quiero que el local se active de 9 a 6 automatizado. | 5 |
| 25 | US-25 | Revisar consumo por área o equipo | Como dueño, quiero saber si un sector de la oficina consume más luz. | 5 |
| 26 | US-26 | Compartir acceso con personal | Como dueño, quiero aislar los permisos de los empleados a sus sectores. | 5 |
| 27 | US-27 | Pagar suscripción con tarjeta | Como usuario, quiero contratar el Enterprise plan con Stripe. | 8 |
| 28 | US-28 | Cancelar suscripción Premium | Como usuario, quiero regresar al plan Free sin que me sigan cobrando. | 3 |
| 29 | US-29 | Recibir alertas por correo | Como usuario, quiero que un pico de consumo me llegue vía Mailchimp. | 5 |
| 30 | US-30 | Recibir reporte mensual | Como usuario, quiero que en fin de mes se manden mis estadísticas al mail. | 5 |
| 31 | US-31 | Recuperar contraseña | Como usuario, quiero que se envíe un token de reset a mi correo. | 5 |
| 32 | US-32 | Editar perfil de usuario | Como usuario, quiero rectificar mi número de contacto o nombre de perfil. | 2 |
| 33 | US-33 | Eliminar cuenta | Como usuario, quiero un botón rojo para purgar absolutamente todos mis datos. | 3 |
| 34 | US-34 | Configurar preferencias | Como usuario, quiero poder rechazar los boletines desde mi perfil. | 2 |
| 35 | US-35 | Simular conexión de equipo | Como desarrollador, quiero inyectar equipos falsos para probar el sistema. | 5 |
| 36 | US-36 | Filtrar historial por fechas | Como usuario, quiero un calendario de inicio y fin para mis reportes. | 3 |
| 37 | US-37 | Exportar historial a Excel | Como usuario corporativo, quiero bajar una tabla de mis métricas en CSV. | 3 |
| 38 | US-38 | Agrupar dispositivos | Como usuario, quiero juntar varios enchufes bajo la etiqueta "Sala". | 5 |
| 39 | US-39 | Activar Modo Oscuro | Como usuario, quiero activar tema oscuro para descansar mis ojos de noche. | 3 |
| 40 | US-40 | Gestionar múltiples locales | Como dueño Enterprise, quiero saltar entre varias de mis tiendas. | 8 |


# Capitulo IV: Product Design
## 4.1. Style Guidelines

Las pautas de estilo de ElectroCorp están orientadas a comunicar tecnología accesible, control energético y confianza. El diseño visual busca que cualquier usuario pueda entender rápidamente la propuesta de valor  y navegar sin fricción por la landing page.

### 4.1.1. General Style Guidelines

**Consistencia visual**

ElectroCorp mantiene una identidad visual uniforme en toda la landing mediante una estructura de secciones por bloques, botones redondeados, tarjetas con bordes suaves y color acento constante. Esta coherencia facilita el reconocimiento de acciones principales como registro, contacto y navegación por anclas.

**Simplicidad y claridad**

La interfaz prioriza mensajes directos y componentes con una sola intención por bloque: presentación del problema, propuesta de valor, planes, testimonios y contacto. Se evita la sobrecarga de elementos para sostener una lectura rápida desde la primera visita.

**Branding**

La marca ElectroCorp se presenta desde el encabezado con logotipo visible y naming consistente. El discurso visual refuerza modernidad, energía y tecnología accesible para hogares peruanos.

<p align="center">
  <img src="assets/411-branding-logo-electrocorp.png" alt="Branding y logotipo de ElectroCorp">
</p>


**Tipografía**

Se utiliza una familia sans-serif del sistema (`Segoe UI`, `Roboto`, `Helvetica`, `Arial`, `sans-serif`) para asegurar legibilidad, carga rápida y compatibilidad multiplataforma. Los títulos emplean mayor peso tipográfico para jerarquizar contenido y los párrafos usan interlineado amplio para lectura continua.

**Paleta cromática**

La paleta transmite un entorno tecnológico:

- Fondo principal oscuro: `#0a0f18`
- Tarjetas y bloques secundarios: `#111a28`
- Color acento principal (acciones y resaltados): `#00d2ff`
- Color acento secundario para estados hover: `#00a8cc`
- Texto principal claro: `#e0e6ed`
- Texto secundario: `#8b9bb4`

**Spacing y ritmo visual**

El espaciado está definido para equilibrio entre densidad de información y respiración visual:

````
- Secciones: `padding` vertical de 80px
- Títulos de sección: separación inferior de 20px
- Párrafos descriptivos: margen inferior de 30px
- Grillas (cards/imagenes): separación de 30px a 50px
- Botones principales: `padding` de 12px x 30px
````

**Patrón de lectura**

La página aplica un flujo tipo F/Z: encabezado fijo para acceso inmediato, hero con propuesta principal y CTA, seguido por bloques temáticos en orden lógico de descubrimiento a conversión.

<p align="center">
  <img src="assets/411-style-web.png" alt="Guía general de estilo para la landing" width="700">
</p>


### 4.1.2. Web Style Guidelines

**Aplicación de color en web**

El acento cyan (`#00d2ff`) se usa para CTA, enlaces de navegación, líneas de separación y estados interactivos. Los fondos oscuros favorecen contraste y lectura de datos energéticos en contextos nocturnos o de panel.

<p align="center">
  <img src="assets/412-colors-electrocorp.png" alt="Paleta web de ElectroCorp" width="700">
</p>


**Tipografía en interfaz**

Se mantienen tamaños escalables por jerarquía:

- Hero title: 3.5rem
- Títulos de sección: 2rem
- Subtítulos de apoyo: 1.2rem
- Cuerpo descriptivo: 1.1rem aprox.

Esta estructura mantiene legibilidad en desktop y se ajusta en móviles mediante media queries.

**Iconografía**

Se utiliza Font Awesome para iconos funcionales (búsqueda, redes, navegación del carrusel y estados de planes). El criterio de uso prioriza reconocimiento inmediato y baja carga cognitiva.



**Grid System y layout**

La landing combina:

- Grillas flex para galerías y tarjetas (`.grid`, `.service-grid`)
- Bloques centrados con ancho máximo para contenido textual
- Header sticky para navegación persistente

Este esquema mejora escaneo visual y mantiene estabilidad estructural en diferentes resoluciones.

**Botones y estados**

Los botones principales son redondeados, con contraste alto y transición hover. Se diferencia claramente entre:

- Botón primario (`header-btn-primary`)
- Botón secundario/outline (`header-btn-outline`)
- Botón CTA estándar (`.btn`)

**Input System**

Los campos de entrada (buscador y newsletter) usan bordes suaves, fondo oscuro y foco con color acento para dar feedback visual inmediato y consistente.

<p align="center">
  <img src="assets/412-input-button-system.png" alt="Sistema de botones e inputs de ElectroCorp" width="700">
</p>


## 4.2. Information Architecture

La arquitectura de información de ElectroCorp está orientada a conversión y comprensión rápida: primero se presenta el problema energético, luego la solución IoT, la evidencia social (testimonios) y finalmente el contacto/registro.

### 4.2.1. Organization Systems

Se emplea un sistema de organización secuencial por secciones ancladas:

1. `#hero`: mensaje principal y acceso rápido al dashboard.
2. `#description`: contexto del problema y propuesta de valor.
3. `#goals`: objetivos del producto.
4. `#service`: planes y beneficios.
5. `#reviews`: prueba social de usuarios.
6. `#about`: credenciales del equipo.
7. `#device`: evidencia visual del hardware.
8. `#contact`: formulario de conversión.

Además, se utiliza organización jerárquica por prioridad visual (hero > CTA > beneficios > conversión).

<p align="center">
  <img src="assets/LandingPageMockUps1.png">
  <img src="assets/LandingPageMockUps2.png">
  <img src="assets/LandingPageMockUps3.png">
  <img src="assets/LandingPageMockUps4.png">
  <img src="assets/LandingPageMockUps5.png">
  <img src="assets/LandingPageMockUps6.png">
  <img src="assets/LandingPageMockUps7.png">
  <img src="assets/LandingPageMockUps8.png">
</p>

### 4.2.2. Labeling Systems

El sistema de etiquetado usa términos cortos, directos y alineados al idioma activo (ES/EN) mediante `i18n`. Etiquetas principales de navegación:

| Label (EN) | Label (ES) | Propósito |
|------------|------------|-----------|
| Home | Inicio | Punto de entrada y propuesta de valor |
| Description | Descripción | Explica problema y solución |
| Goals | Objetivos | Comunica alcance del producto |
| Pricing | Planes | Presenta opciones comerciales |
| Reviews | Testimonios | Refuerza confianza con casos reales |
| About us | Nosotros | Presenta al equipo |
| Smart Plugs | Enchufes Smart | Muestra componente físico IoT |
| Support | Soporte | Canal de contacto y suscripción |

Etiquetas de acción (CTA):

- Iniciar sesión / Log in
- Registrarse / Sign up
- Ir al dashboard / Go to dashboard
- Empezar gratis / Start for free
- Contactar ventas / Contact sales

Este enfoque reduce ambigüedad y mejora reconocimiento inmediato.

<p align="center">
  <img src="assets/422-labeling-system-menu-es.png" alt="Sistema de etiquetado de navegación y CTA" width="700">
</p>

<p align="center">
  <img src="assets/422-labeling-system-menu-en.png" alt="Sistema de etiquetado de navegación y CTA" width="700">
</p>


### 4.2.3. SEO Tags and Meta Tags

Actualmente la landing incluye:

````
<html lang="en">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ElectroCorp | Smart Energy Management</title>
````

Para fortalecer posicionamiento SEO de ElectroCorp en búsquedas locales, se recomienda añadir:

````
<meta name="description" content="ElectroCorp democratiza la domótica en Perú con enchufes inteligentes plug-and-play para controlar y optimizar el consumo eléctrico en tiempo real.">
<meta name="keywords" content="domótica Perú, enchufes inteligentes, ahorro de energía, IoT hogar, eficiencia energética">
<meta name="author" content="ElectroCorp Team">
<meta name="robots" content="index, follow">
````

### 4.2.4. Searching Systems

ElectroCorp implementa un buscador por palabras clave en la sección hero que redirige a anclas internas según intención del usuario. El sistema está basado en un diccionario de términos (`search.js`) y navegación con `scrollIntoView`.

Funcionamiento:

- El usuario escribe una consulta (ej. "planes", "soporte", "enchufes").
- El script normaliza el texto a minúsculas y evalúa coincidencias.
- Si encuentra match, desplaza suavemente a la sección objetivo.
- Si no encuentra resultados, muestra una alerta orientativa con ejemplos.

Palabras clave relevantes configuradas:

- Inicio/Descripción: `inicio`, `descripcion`, `startup`
- Oferta: `servicios`, `planes`, `precios`, `gratis`, `pagos`
- Confianza: `testimonios`, `opiniones`
- Equipo: `nosotros`, `about`, `team`
- Hardware: `enchufes`, `dispositivos`, `hardware`
- Soporte: `contacto`, `soporte`, `boletin`

Este modelo de búsqueda prioriza rapidez y reducción de fricción para landing pages de una sola pantalla.


### 4.2.5. Navigation Systems

La navegación de ElectroCorp combina un sistema principal por menú superior sticky y navegación contextual por CTA:

- **Navegación global (header fijo):** acceso permanente a todas las secciones por anclas.
- **Navegación por desplazamiento suave:** transición fluida al seleccionar opciones del menú o resultados del buscador.
- **Navegación por CTA:** botones que conducen a registro, dashboard o contacto comercial.
- **Navegación responsive:** reorganización de bloques de cabecera para móviles (brand + acciones + menú).
- **Navegación por carrusel en testimonios:** controles prev/next para explorar evidencia social sin salir de la sección.

Este sistema mejora la encontrabilidad del contenido clave y sostiene una experiencia lineal de descubrimiento -> confianza -> conversión.

<p align="center">
  <img src="assets/425-navigation-system-hero.png" alt="Sistema de navegación en header y hero" width="700">
</p>

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
El wireframe define la estructura básica de la landing page en bloques principales:<br><img src="assets/LandingPageWireframe1.png"><br><img src="assets/LandingPageWireframe2.png"><br><img src="assets/LandingPageWireframe3.png"><br><img src="assets/LandingPageWireframe4.png"><br><img src="assets/LandingPageWireframe5.png"><br><img src="assets/LandingPageWireframe6.png"><br><img src="assets/LandingPageWireframe7.png"><br>
### 4.3.2. Landing Page Mock-up
<img src="assets/LandingPageDashBoardMockUps.png">
<img src="assets/LandingPageCrearSesionMockUps.png">
<img src="assets/LandingPageInicioSesionMockUps.png">
<img src="assets/LandingPageMockUps1.png">
<img src="assets/LandingPageMockUps2.png">
<img src="assets/LandingPageMockUps3.png">
<img src="assets/LandingPageMockUps4.png">
<img src="assets/LandingPageMockUps5.png">
<img src="assets/LandingPageMockUps6.png">
<img src="assets/LandingPageMockUps7.png">
<img src="assets/LandingPageMockUps8.png">

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

<img src="assets/WireframeInicio.png">
<img src="assets/WireframeRegistrarse.png">
<img src="assets/WireframeIniciarSesion.png">
<img src="assets/WireframeInicioApp.png">
<img src="assets/WireframeCentroEnergetico.png">
<img src="assets/WireframeAnaliticaAvanzada.png">
<img src="assets/WireframeDispositivos.png">
<img src="assets/WireframeHistorial.png">
<img src="assets/WireframeIAEnergetica.png">


### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups

![Mockp-Center](assets/Application-Web-MockUp-Center.png)

**Centro Energético:**  
Este mockup representa la vista principal de la aplicación, donde el usuario puede visualizar un resumen general de su consumo energético. Se muestran indicadores clave como el consumo mensual, el gasto estimado, el porcentaje de ahorro y la cantidad de dispositivos registrados. Además, incluye un gráfico de línea que permite analizar el comportamiento del consumo durante la semana. Desde esta sección, el usuario puede agregar nuevos registros de consumo o simular datos para análisis.

---

![Mockp-Analitycs](assets/Application-Web-MockUp-Analytics.png)

**Analítica Avanzada:**  
En esta vista se presentan métricas más detalladas del consumo energético. El usuario puede identificar la hora pico de consumo, el día con mayor uso, el promedio diario y una predicción del gasto mensual. También se incluye un gráfico de barras que distribuye el consumo por dispositivo, facilitando la toma de decisiones informadas para optimizar el uso de energía.

---

![Mockp-Devices](assets/Application-Web-MockUp-Devices.png)

**Gestión de Dispositivos:**  
Este mockup muestra la interfaz para administrar los dispositivos eléctricos del usuario. Permite buscar dispositivos, agregarlos, activarlos o desactivarlos, así como eliminarlos. Cada dispositivo presenta su estado actual, lo que impacta directamente en el cálculo del consumo energético. Esta sección es clave para el control y personalización del sistema.

---

![Mockp-History](assets/Application-Web-MockUp-History.png)

**Historial de Consumo:**  
Aquí se visualizan los registros recientes de consumo energético organizados por día. El usuario puede revisar fácilmente su historial, exportar los datos en formato CSV para análisis externo o limpiar los registros almacenados. Esta sección permite llevar un seguimiento detallado del comportamiento energético a lo largo del tiempo.

---

![Mockp-Suggestions](assets/Application-Web-MockUp-Suggestions.png)

**IA Energética (Insights):**  
Este mockup presenta recomendaciones inteligentes generadas a partir del análisis de los datos de consumo. Se muestran alertas sobre consumo elevado, sugerencias para optimizar el uso de dispositivos y estimaciones de ahorro. Esta funcionalidad busca ayudar al usuario a mejorar su eficiencia energética mediante información clara y accionable.
### 4.4.4. Web Applications User Flow Diagrams
El flujo inicia con el acceso del usuario a la plataforma, seguido de procesos clave como la navegación entre secciones, la interacción con funcionalidades principales y la obtención de resultados esperados. Asimismo, se contemplan escenarios alternativos y puntos de decisión que influyen en la experiencia del usuario, permitiendo comprender cómo se gestionan diferentes situaciones dentro del sistema.

![UserFlowDiagram](assets/UserFlowDiagram.png)


## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level Event Storming

<img src="assets/designLevelEventStorming.png">

### 4.6.2. Software Architecture Context Diagram
En esta sección se presenta el Diagrama de Contexto (Context Level Diagram) correspondiente al Nivel 1 del Modelo C4 para la arquitectura de ElectroCorp. Este diagrama ilustra el panorama general del ecosistema, posicionando al sistema propuesto en el centro para demostrar cómo interactúa directamente con los usuarios finales y los sistemas de software de terceros que complementan su funcionalidad.

<img src="assets/Context-diagram.png">

El entorno del sistema ElectroCorp se compone de los siguientes elementos clave:

**-ElectroCorp User (Actor Principal):** Representa a los propietarios de viviendas o dueños de negocios que interactúan con la plataforma. Su objetivo es monitorear su consumo de energía, configurar límites de presupuesto y establecer rutinas automáticas para sus dispositivos. Adicionalmente, el usuario interactúa con la pasarela de pagos para mantener activa su suscripción mensual y es el receptor final de las alertas del sistema.

**-ElectroCorp System (Sistema Principal):** Es la plataforma integral de software (Web y Móvil) que centraliza la lógica de negocio. Para este alcance del proyecto, el sistema absorbe la responsabilidad de simular el comportamiento y la telemetría de los dispositivos IoT, orquestando las reglas de automatización y el cálculo de tarifas energéticas sin depender de hardware físico externo.

**-Stripe (Sistema Externo de Soporte):** Plataforma comercial externa utilizada como pasarela de pagos. ElectroCorp se comunica con este sistema para delegar el procesamiento seguro de las transacciones financieras y la gestión de las suscripciones de los usuarios.

**-Mailchimp (Sistema Externo de Soporte):** Servicio comercial de envío de correos electrónicos. ElectroCorp le delega el despacho automatizado de reportes mensuales de consumo y la emisión de alertas críticas (por ejemplo, cuando el consumo simulado excede los límites configurados), asegurando que las notificaciones lleguen de manera confiable a la bandeja de entrada del usuario.

### 4.6.3. Software Architecture Container Diagrams
A continuación, se detalla el ecosistema técnico de ElectroCorp, destacando el flujo de información desde que el usuario solicita contenido estático hasta que se procesan las reglas de negocio y se persiste la información

<img src="assets/container-diagram.png">

La arquitectura se basa en una separación clara entre la lógica de presentación y la lógica de negocio, estructurada de la siguiente manera:

**1. Contenedores de Aplicación (Frontend):**

**-ElectroCorp Web App:** Actúa como el servidor de contenido estático (HTML, CSS y JS). Su única responsabilidad es entregar los archivos necesarios al navegador del usuario para inicializar la aplicación.

**-ElectroCorp Single Page Application (SPA):** Desarrollada en Angular (TypeScript), es la aplicación que corre directamente en el cliente. Maneja el renderizado dinámico del dashboard, permitiendo que el usuario interactúe con las gráficas de consumo y configure sus dispositivos sin recargar la página.

**-ElectroCorp Mobile Application:** Construida en Flutter, ofrece una interfaz nativa para dispositivos móviles, consumiendo los mismos servicios que la versión web.

**2. Contenedor de Lógica Central (Backend):**

**-Backend API:** Es el núcleo del sistema, desarrollado en Java con Spring Boot. Implementa los principios de Domain-Driven Design (DDD) y expone endpoints REST. Se encarga de la autenticación de usuarios, la lógica de simulación de consumo energético y la coordinación de alertas.

**3. Contenedores de Persistencia e Infraestructura:**

**-Database (MySQL):** Motor de base de datos relacional encargado de la persistencia de perfiles, configuraciones de horarios y el histórico de telemetría de los enchufes inteligentes.

**4. Interacciones con Sistemas Externos:**

**-Stripe (Payment Gateway):** Se integra con la Backend API mediante HTTPS/JSON para gestionar el flujo de pagos de suscripciones de manera segura.

**-Mailchimp (Notification Service):** Servicio externo utilizado para el despacho de correos electrónicos transaccionales, como alertas de picos de voltaje o resúmenes de consumo mensual.

### 4.6.4. Software Architecture Components Diagrams
Los siguientes diagramas de componentes representan la arquitectura de software del sistema ElectroCorp, diferenciando la vista del frontend y la vista del backend. Estos diagramas permiten identificar los principales componentes del sistema, así como sus responsabilidades y relaciones de interacción dentro de la solución.<br><br>Frontend Components Diagram<br><img src="assets/components-diagram-Frontend.png"><br><br>El diagrama de componentes del frontend muestra la organización de los módulos que conforman la interfaz web de ElectroCorp. En esta vista se incluyen los componentes relacionados con la autenticación, la gestión del estado de la aplicación, la internacionalización, la comunicación con la API y las distintas vistas funcionales, como dispositivos, rutinas, reportes, historial, notificaciones, tiempo real e insights energéticos. Este diagrama permite comprender cómo se estructura la capa cliente para ofrecer una experiencia interactiva, modular y reutilizable.<br><br>Backend Components Diagram<br><img src="assets/component-diagram-Backend.png"><br>El diagrama de componentes del backend presenta la estructura interna del servidor desarrollado con Spring Boot. En él se distinguen los controladores REST, los casos de uso de la capa de aplicación, las entidades y objetos de valor del dominio, los repositorios, los adaptadores de persistencia y la base de datos. Esta representación permite visualizar la arquitectura en capas adoptada por el sistema, así como la manera en que los componentes del backend colaboran para procesar solicitudes, aplicar la lógica de negocio y persistir la información.<br>

## 4.7. Software Object-Oriented Design
4.7.1. Class Diagrams
Los siguientes diagramas de clases presentan el diseño orientado a objetos del sistema ElectroCorp, separados en una vista de frontend y una vista de backend. Ambos diagramas se renderizan de forma online a partir de los archivos fuente PlantUML almacenados en el repositorio, utilizando la versión raw de GitHub.

Frontend Class Diagram
    <img src="assets/471Diagram1.jpeg"></img><br>


El diagrama de clases del frontend representa la estructura del lado cliente de la aplicación. Incluye los principales módulos relacionados con la autenticación, la internacionalización, el consumo de la API, las vistas de la interfaz de usuario, los modales, los gráficos y el estado compartido de la aplicación. Además, muestra cómo colaboran los componentes del frontend para ofrecer funcionalidades interactivas como la gestión de dispositivos, las rutinas, los reportes, las notificaciones, el historial y los insights energéticos.

Backend Class Diagram
    <img src="assets/471Diagram2.jpeg"></img><br>

El diagrama de clases del backend representa el diseño orientado a objetos del lado servidor, implementado con Spring Boot. Incluye los controladores REST, los casos de uso de la aplicación, las entidades y objetos de valor del dominio, los repositorios, los adaptadores de persistencia y las entidades de base de datos. Este diagrama permite visualizar la arquitectura en capas del backend y las relaciones entre la lógica de negocio, la persistencia de datos y la exposición de servicios mediante la API.
## 4.8. Database Design
### 4.8.1. Database Diagrams.
El diagrama de base de datos fue diseñado a partir de los principales procesos identificados en el sistema, como el registro de usuarios, la gestión de dispositivos, la selección de planes de suscripción, el monitoreo del consumo eléctrico y el servicio de notificaciones. A través de este modelo se definieron las entidades principales, como Usuario, Dispositivo, Suscripción, Plan de Suscripción, Consumo Energético y Notificación, junto con sus respectivas relaciones. Esto permite organizar de manera estructurada la información del sistema, facilitando el control de los dispositivos, el análisis del consumo energético y la automatización de alertas dentro de la plataforma.<br>
<img src="assets/DiagramaERD.png"><br>

# Capitulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management

A continuación, se presentará un repositorio central y organizado que servirá como guía para el desarrollo enfocado y consistente de nuestra solución.

### 5.1.1 Software Development Environment Configuration

En esta sección se incluye los links de las aplicaciónes, productos de software realizadas durante el ciclo del proyecto en los programas que se utilizaron. <br>

+ **Project Management**<br>
Esta área se centra en la planificación, organización, coordinación y control de los recursos y actividades necesarias para completar un proyecto de software con éxito. Incluye la gestión del alcance, el tiempo, el costo, la calidad, los riesgos, los recursos humanos y la comunicación para garantizar que el proyecto se entregue dentro del tiempo y el presupuesto establecidos, cumpliendo con los requisitos y objetivos definidos.

  +	<b>Jira Software:</b> Herramienta líder en la industria para la gestión ágil de proyectos. Permite a los equipos planificar, priorizar y realizar un seguimiento del trabajo de manera colaborativa mediante tableros Scrum o Kanban. <br>https://www.atlassian.com/es/software/jira<br><br>

+ **Requirements Management**<br>
Se refiere al proceso de identificar, documentar, verificar y gestionar los requisitos del sistema y del software. Implica entender las necesidades de los usuarios y las partes interesadas, traduciéndolas en requisitos funcionales y no funcionales claros y específicos. El objetivo es garantizar que el software desarrollado satisfaga las necesidades y expectativas de los usuarios finales.

  + **Jira Software:**
Plataforma de gestión centrada en Historias de Usuario (User Stories), que se organizan en Épicas (Epics) y se clasifican por puntaje de esfuerzo (Story Points). Es utilizada para mantener a todos los miembros del equipo al tanto del progreso del Backlog del producto, ofreciendo una vista en tiempo real compartida que facilita la colaboración eficiente.
<br> https://www.atlassian.com/es/software/jira<br><br>

+ **Product UX/UI Design**<br>
Este aspecto se enfoca en el diseño de la experiencia del usuario (UX) y la interfaz de usuario (UI) del producto de software. UX se centra en comprender y mejorar la experiencia general del usuario al interactuar con el software, mientras que UI se refiere al diseño visual y la usabilidad de la interfaz de usuario. En este caso realizar un modelo de sitio web para computadoras y celulares.

  + **Figma:**<br>Herramienta de prototipado web y editor de gráficos vectoriales que se aloja en la web, permitiendo establecer los modelos interactivos para versión en Web Browser y Mobile Browser de manera colaborativa.
https://www.figma.com/design/ 

  + **UXPressia:**<br> Herramienta en línea para el mapeo de la trayectoria del cliente. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map.<br>https://uxpressia.com/ 

  + **MIRO:**<br>Pizarra digital colaborativa en línea, usada para la investigación, la ideación, mapas mentales, flujos as-is / to-be y una variedad de otras actividades colaborativas.<br>https://miro.com/app/dashboard/ 

  + **Lucid Chart:**<br> Es una herramienta de diagramación basada en la web, que permite a los usuarios colaborar y trabajar juntos en tiempo real, creando diseños UML, mapas mentales, prototipos de software y muchos otros tipos de diagrama.
https://lucid.app/documents#/dashboard 

  + **dbdiagram.io:**<br> Herramienta gratuita y basada en la web diseñada para dibujar esquemas de bases de datos de forma rápida e intuitiva mediante código (DBML). Se utilizará para diseñar visualmente el modelo Entidad-Relación (ERD), definir las estructuras de las tablas y exportar ágilmente los scripts SQL necesarios para implementar nuestra base de datos en MySQL.
https://dbdiagram.io/

  + **Structurizr:**<br> Es una herramienta de diseño que soporta el modelo C4, para visualizar la arquitectura de software de nuestra solución. 
https://structurizr.com/ 

+ **Software Development**<br>
Es el proceso de crear, diseñar, programar, probar y mantener el software. Incluye la implementación de los requisitos definidos utilizando diferentes lenguajes de programación, herramientas y tecnologías.

  + **GitHub:**<br>Repositorio comunitario basado en la nube cuya función es almacenar, versionar y gestionar los avances del código fuente elaborado por el equipo. <br>
https://github.com/upc-pre-202610-1asi0729-11896-ECorp


  + **Visual Studio Code:**<br> Editor de código fuente potente y ligero que brinda extensiones personalizables, permitiendo que la función del desarrollador sea más eficiente.<br>
https://code.visualstudio.com/ 

  + **HTML:**<br>  Lenguaje estándar para crear y diseñar sitios web. Utiliza etiquetas para estructurar el contenido. Este lenguaje será utilizado en el presente proyecto para implementar la estructura de la página web.<br>
https://www.jetbrains.com/help/webstorm/editing-html-files.html 

  + **CSS:**<br> : Lenguaje de hojas de estilo utilizado para controlar el diseño y la presentación de páginas web. Permite establecer colores, fuentes y animaciones. Se utilizará para la implementación del diseño visual de nuestra plataforma.<br>
https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion 

  + **JavaScript:**<br> Lenguaje de programación de alto nivel que se utiliza para agregar interactividad y dinamismo a los sitios web (validar formularios, animar elementos, etc.). Se utilizará para la elaboración de la lógica frontend de la plataforma.<br>
https://www.jetbrains.com/help/webstorm/javascript-specific-guidelines.html 


  +  **Java:**<br> Es un lenguaje de programación de alto nivel, robusto y orientado a objetos, diseñado para tener la menor cantidad posible de dependencias de implementación. Es ideal para aplicaciones empresariales, desarrollo de apps móviles (Android) y sistemas de escritorio. Se utilizará para gestionar la lógica de servidor y el procesamiento de datos del proyecto.<br>
https://www.oracle.com/java/technologies/downloads/

+ **Software Testing**<br>
Se refiere a la actividad de verificar y validar el software para garantizar su calidad y funcionamiento correcto. Involucra la ejecución de pruebas funcionales y no funcionales para identificar errores, defectos o problemas en el software antes de su lanzamiento. El objetivo es asegurar que el software sea confiable, robusto y cumpla con los requisitos y expectativas del usuario final.

  + **Lenguaje Gherkin:**<br>Es un lenguaje de dominio específico (DSL) utilizado en el desarrollo de software para escribir pruebas de aceptación en un formato legible por humanos. Utiliza palabras clave como Given, When y Then para describir el estado inicial, la acción y el resultado esperado de un escenario de prueba, lo que facilita la colaboración entre equipos al definir requisitos y pruebas.<br>https://cucumber.io/

+ **Software Deployment**<br>
Es el proceso de implementar y poner en funcionamiento el software en un entorno de producción o en los dispositivos de los usuarios finales. Incluye actividades como la instalación, configuración, migración de datos y puesta en marcha del software. El objetivo es garantizar una implementación exitosa y sin problemas del software en el entorno de producción.

  + **Github Pages:**<br> Servicio de Github que nos permitió alojar nuestra Landing page y nos permitirá alojar nuestro web applications.<br>
https://pages.github.com/ <br>


+	**Software Documentation**<br>Se refiere a la creación y mantenimiento de documentos que describen el software, incluyendo su arquitectura, diseño, funcionamiento, instalación, configuración, uso y mantenimiento. La documentación proporciona información útil y detallada sobre el software para desarrolladores, usuarios finales, administradores de sistemas y otras partes interesadas. 

    + **Markdown:**<br>Es un lenguaje de marcado ligero que permite escribir texto con un formato fácil de leer y escribir, que luego puede ser convertido a HTML u otros formatos de presentación. Es ampliamente utilizado para documentar proyectos de software debido a su simplicidad y versatilidad. Markdown permite agregar formato básico como encabezados, listas, enlaces e imágenes utilizando una sintaxis sencilla y fácil de recordar.<br>https://www.markdownguide.org/getting-started/<br><br>


### 5.1.2. Source Code Management

Para administrar el progreso del código de manera efectiva, hemos decidido adoptar la metodología Git Flow. Esta estrategia se enfoca en el uso de ramas para facilitar la gestión de archivos durante el proceso de programación. En resumen, Git Flow nos permite mantener una rama principal ('main') que contiene una versión estable del proyecto en un punto determinado. Al mismo tiempo, utilizamos otra rama de desarrollo para incorporar nuevas características al código base sin afectar la versión estable actual. Esto nos permite avanzar en el desarrollo de nuestra página de destino mientras realizamos pruebas relacionadas con las nuevas modificaciones introducidas en la rama de desarrollo.

Además, hemos optado por utilizar GitHub debido a su función específica llamada GitHub Pages. Esta función permite la visualización eficiente del proyecto mediante la ejecución de archivos '.html' y la generación de un enlace web.

En cuanto a nuestros archivos feature, creamos una nueva rama “feature/sprint-1” para cada nueva funcionalidad que deseamos agregar. Este enfoque modular y organizado asegura un desarrollo progresivo, ya que cada rama “feature/sprint-1” actúa como un espacio aislado para desarrollar y probar una característica específica antes de fusionarla con la rama de desarrollo.<br><br>

Enlace de la Landing Page en GitHub Pages:https://1asi0730-2610-20177-nex.github.io/LandingPage/<br><br> 

<img src="assets/LandingPageMockUps1.png"></img><br>

Repositorio GitHub de la Landing Page: https://github.com/1ASI0730-2610-20177-Nex/LandingPage/tree/tb01 <br><br> 

<img src="assets/Repos.png"></img><br>


### 5.1.3. Source Code Style Guide & Conventions

En el desarrollo del proyecto se aplican convenciones de estilo para mantener consistencia y legibilidad del código en todos los repositorios.

#### HTML

- Declarar `<!DOCTYPE html>` en la primera línea.
- Mantener estructura base: `<html>`, `<head>`, `<body>`.
- Definir `<title>` descriptivo por página.
- Usar indentación consistente según nivel de anidamiento.
- Cerrar correctamente etiquetas de apertura/cierre.
- Incluir atributo `alt` en imágenes.
- Utilizar etiquetas semánticas como `<header>`, `<main>`, `<section>` y `<footer>`.

Referencia: [W3C/W3Schools HTML Syntax](https://www.w3schools.com/html/html5_syntax.asp)

#### CSS

- Usar nombres de clases claros, cortos y en minúsculas.
- Mantener indentación uniforme y bloques ordenados.
- Definir colores en formato hexadecimal cuando aplique.
- Incorporar comentarios breves en secciones complejas.
- Diseñar interfaces responsivas para distintos dispositivos.
- Evitar duplicación de estilos mediante reutilización.

Referencia: [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)

#### JavaScript

- Nombrar variables y funciones de forma coherente.
- Finalizar instrucciones con punto y coma.
- Priorizar `const` sobre `let` cuando el valor no cambia.
- Usar comparación estricta (`===`, `!==`) cuando sea posible.
- Mantener funciones pequeñas y enfocadas en una responsabilidad.
- Evitar código duplicado y modularizar cuando sea necesario.

Referencia: [JavaScript Conventions](https://www.w3schools.com/js/js_conventions.asp)

#### Vue (Vite)

- Nombrar componentes en `PascalCase`.
- Usar `camelCase` para variables, funciones y propiedades.
- Mantener la estructura de archivos `.vue`: `<template>`, `<script>`, `<style>`.
- Organizar el proyecto en carpetas como `components`, `views`, `services` y `assets`.
- Mantener componentes pequeños, reutilizables y con responsabilidad única.
- Utilizar Composition API para organizar la lógica cuando sea necesario.
- Mantener configuraciones de Vite simples y claras.

Referencia: [Vue Style Guide](https://vuejs.org/style-guide/)  
Referencia: [Vite Documentation](https://vitejs.dev/guide/)

#### C# (Backend)

- Seguir nomenclatura estándar: clases e interfaces en `PascalCase`, variables y métodos en `camelCase`.
- Usar interfaces con prefijo `I` (ejemplo: `IUserService`).
- Mantener una indentación consistente.
- Definir constantes para valores inmutables.
- Aplicar separación de responsabilidades (controladores, servicios, repositorios).
- Usar `async` y `await` en operaciones asíncronas.
- Validar entradas y manejar errores mediante excepciones controladas.
- Priorizar buenas prácticas de seguridad en APIs.

Referencia: [Microsoft C# Coding Conventions](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions)

#### Gherkin

- Estructurar escenarios con `Given`, `When`, `Then`.
- Separar escenarios con líneas en blanco para mejor lectura.
- Usar tablas de ejemplos cuando se requiera parametrización.
- Escribir pasos en lenguaje claro y verificable.

Referencia: [Gherkin conventions](https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/)

### 5.1.4. Software Deployment Configuration

Para la configuración de despliegue del proyecto se emplean las herramientas Git y GitHub:

- **Git** permite el control de versiones del código fuente, facilitando la gestión de cambios, la creación de ramas de trabajo y la integración de avances de manera organizada.
- **GitHub** funciona como repositorio remoto, permitiendo la centralización del código, la revisión mediante *pull requests* y el mantenimiento del historial de versiones.

El flujo de despliegue toma el código alojado en **GitHub**  y realiza la publicación del sitio mediante **GitHub Pages**.

Las integraciones a la rama de despliegue se realizan previa validación, ya sea mediante revisión de *pull requests* o pruebas en entorno local, con el objetivo de asegurar la calidad del producto en cada iteración del proyecto.

La versión pública de la *Landing Page* se encuentra disponible en el siguiente enlace:

Referencia: [Landing Page](https://1asi0730-2610-20177-nex.github.io/LandingPage/)

De este modo, cada versión desplegada corresponde a *commits* rastreables dentro del repositorio, lo que garantiza la trazabilidad, el control de cambios y la mantenibilidad del sistema.

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1 
#### 5.2.1.1. Sprint Planning 1
<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 1</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            20/04/2026         
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            9:00         
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad Remota por Whatsapp
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            ElectroCorp Team    
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Attendees (to planning meeting)</b>
        </td>
        <td>
            - Tavara Correa, Sebastian Oswaldo <br>
            - Tuncar Vila, Ghorghet Saul <br>
            - Cabrejos Chocco, Diego Alexander  <br>
            - Alexander Piero Garfias <br>
            - Ronal Toro Turpo <br>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b> <br>
            <b>Review Summary</b>
        </td>
        <td>
            No existe Spring anterior para realizar una retrospectiva. Sin embargo se debe de desarrollar en la brevedad posible las User Stories y la planificación del Product Backlog  
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b> <br>
            <b>Retrospective Summary</b>
        </td>
        <td>
            No existe un sprint anterior para realizar una retrospectiva. Sin embargo, basándonos en lo avanzado, debemos priorizar la correcta definición y desarrollo de las User Stories y una planificación eficiente del Product Backlog.
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>SPRINT GOAL & USER STORIES</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 1 Goal</b>
        </td>
        <td>
            El objetivo para este Sprint 1, es el desarrollar una landing page para ElectroNex que cumpla con los requisitos dictados en la guía, garantizando una experiencia de usuario (UX) fluida y un diseño visual atractivo (Dark Mode), que comunique eficazmente nuestra propuesta de valor: democratizar la domótica en los hogares peruanos mediante un ecosistema IoT plug-and-play que permite gestionar el consumo eléctrico en tiempo real, reduciendo los altos costos de los recibos de luz y fomentando la eficiencia energética 
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            8
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            8
        </td>
    </tr>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators
Al momento de realizar el sprint 1, el equipo ElectroNex decidió asignar Líderes (B Boss) y Colaboradores (C Collaborator) para los aspectos esenciales como diseño de la interfaz, desarrollo de la landing page, planificacion de los sprints, documentación y las pruebas iniciales. Gracias a esta distribución se permitió un trabajo más colaborador y organizado para el avance del proyecto

<p style="text-align: justify; width: 90%; margin: 20px auto;">
    Al momento de realizar el sprint 1, el equipo ElectroCorp decidió asignar Líderes (B Boss) y Colaboradores (C Collaborator) para los aspectos esenciales como diseño de la interfaz, desarrollo de la landing page, planificación de los sprints, documentación y las pruebas iniciales. Gracias a esta distribución se permitió un trabajo más colaborativo y organizado para el avance del proyecto.
</p>

<table align="center" border="1" width="90%" style="text-align:center; border-collapse: collapse;">
    <tr align="center">
        <td><b>Miembro del Equipo</b></td>
        <td><b>Github Username</b></td>
        <td><b>UI/UX</b></td>
        <td><b>Landing Page</b></td>
        <td><b>Sprint Planning</b></td>
        <td><b>Documentation</b></td>
        <td><b>Testing</b></td>
    </tr>
    <tr align="left">
        <td>- Tavara Correa, Sebastian Oswaldo</td>
        <td align="center">SebastianTavara</td>
        <td align="center">C</td>
        <td align="center">-</td>
        <td align="center">B</td>
        <td align="center">-</td>
        <td align="center">C</td>
    </tr>
    <tr align="left">
        <td>- Tuncar Vila, Ghorghet Saul</td>
        <td align="center">Ghorghet</td>
        <td align="center">C</td>
        <td align="center">-</td>
        <td align="center">-</td>
        <td align="center">-</td>
        <td align="center">C</td>
    </tr>
    <tr align="left">
        <td>- Cabrejos Chocce, Diego Alexander</td>
        <td align="center">MOTOX-357</td>
        <td align="center">B</td>
        <td align="center">C</td>
        <td align="center">C</td>
        <td align="center">C</td>
        <td align="center">B</td>
    </tr>
    <tr align="left">
        <td>- Ronal Toro Turpo</td>
        <td align="center">Ronal</td>
        <td align="center">C</td>
        <td align="center">C</td>
        <td align="center">C</td>
        <td align="center">C</td>
        <td align="center">C</td>
    </tr>
    <tr align="left">
        <td>- Alexander Piero Garfias</td>
        <td align="center">Dostoyevsk1</td>
        <td align="center">C</td>
        <td align="center">B</td>
        <td align="center">C</td>
        <td align="center">B</td>
        <td align="center">C</td>
    </tr>
</table>

#### 5.2.1.3. Sprint Backlog 1. 
<p style="text-align: justify; width: 90%; margin: 20px auto;">
    El primer objetivo del Sprint Backlog fue el establecer los cimientos del proyecto ElectroCorp centrando los esfuerzos en el diseño de la interfaz (UI/UX), la construcción total de la landing page, la definición de los Sprints en la herramienta de gestión y el desarrollo de documentación base. También se incluyeron tareas generales como configuración de repositorios, organización del equipo y avances del trabajo.
</p>

<p style="text-align: left; width: 90%; margin: 20px auto;">
    <b>Enlace de Seguimiento:</b> <a href="https://trello.com/invite/b/69ea69db3f7579b973a8f0d9/ATTIc10bfb6ee54361e0d44f1e36131317e252842AF0/sprint1-electrocorp" target="_blank">Tablero del Sprint 1 en Trello</a>
    <br><br>
    <img src="assets/Tablero-Sprint1.png"></img>
</p>

<table align="center" border="1" width="95%" style="text-align:center">
  <tr>
    <td colspan="1"><b>Sprint #</b></td>
    <td colspan="8"><b>Sprint 1</b></td>
  </tr>
  <tr>
    <td colspan="2"><b>User Story</b></td>
    <td colspan="7"><b>Work-Item / Task</b></td>
  </tr>
  <tr>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td><b>Description</b></td>
    <td><b>Estimation (Hours)</b></td>
    <td><b>Assigned To</b></td>
    <td><b>Student Code</b></td>
    <td><b>Status</b></td>
  </tr>
  <tr>
    <td rowspan="2">US21</td>
    <td rowspan="2">Visualizar página informativa</td>
    <td>T01</td>
    <td>Maquetación HTML inicial</td>
    <td>Diseñar la estructura base en HTML para la landing page.</td>
    <td>2</td>
    <td>Sebastian Tavara</td>
    <td>U20241e179</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T02</td>
    <td>Estilización general</td>
    <td>Aplicar estilos CSS para definir la apariencia general.</td>
    <td>2</td>
     <td>Diego Cabrejos</td>
    <td>U20241e014</td>
    <td>Done</td>
  </tr>
  
  <tr>
    <td rowspan="2">US22</td>
    <td rowspan="2">Landing Page intuitiva</td>
    <td>T03</td>
    <td>Diseño de navegación</td>
    <td>Crear menú de navegación con enlaces funcionales.</td>
    <td>4</td>
     <td>Alexander Piero Garfias</td>
    <td>U20241e014</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T04</td>
    <td>Personalización del Navbar</td>
    <td>Aplicar diseño e identidad visual al menú de navegación.</td>
    <td>4</td>
     <td>Diego Cabrejos</td>
    <td>U20241e014</td>
    <td>Done</td>
  </tr>

  <tr>
    <td rowspan="2">US23</td>
    <td rowspan="2">Landing Page responsiva</td>
    <td>T05</td>
    <td>Adaptar contenido principal</td>
    <td>Aplicar media queries para que el contenido se adapte a distintos dispositivos.</td>
    <td>4</td>
     <td>Alexander Piero Garfias</td>
    <td>U20241e014</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T06</td>
    <td>Navbar adaptable</td>
    <td>Hacer que el menú de navegación funcione correctamente en pantallas móviles.</td>
    <td>2</td>
     <td>Diego Cabrejos</td>
    <td>U20241e014</td>
    <td>Done</td>
  </tr>
</table>

#### 5.2.1.4. Development Evidence for Sprint Review
En el presente sprint se logró desarrollar la primera versión del Landing Page de ElectroNex, la cual presenta de manera clara el propósito de la plataforma y las problemáticas que busca resolver en el ámbito de la domótica y eficiencia energética. La información mostrada fue organizada de forma comprensible y acompañada de elementos visuales (Dark Mode) que refuerzan el mensaje. Asimismo, se consideró un diseño atractivo, responsivo e intuitivo que busca captar la atención de los usuarios y transmitir confianza en la solución propuesta.

<p align="left" style="width: 95%; margin: 20px auto; font-family: Arial, sans-serif;">
    <b>Link de commits del repositorio del landing page:</b> <br>
    <a href="https://github.com/1ASI0730-2610-20177-Nex/LandingPage/commits/tb01/" target="_blank" style="color: #00d2ff;">
       https://github.com/1ASI0730-2610-20177-Nex/LandingPage/commits/tb01/
    </a>
</p>

Principales avances en implementación con relación al Sprint:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
| :--- | :---: | :---: | :--- | :--- | :---: |
| Landing Page | tb01 | `ada1f6e` | feat: add img folder | added img folder and graphical resources | 26/04/2026 |
| Landing Page | tb01 | `51738af` | feat: add testimonials styles | added specific styles for testimonials section | 26/04/2026 |
| Landing Page | tb01 | `4c7f250` | refactor(styles): split global styles into modular CSS files | refactored and modularized global CSS architecture | 26/04/2026 |
| Landing Page | tb01 | `fc1047c` | feat: add sections styles | added core styles for generic sections | 26/04/2026 |
| Landing Page | tb01 | `b03bd31` | feat: add responsive styles | added media queries and responsive rules | 26/04/2026 |
| Landing Page | tb01 | `4185e2b` | feat: add hero styles | added styles for the main hero component | 26/04/2026 |
| Landing Page | tb01 | `3eee37a` | feat: add header styles | added styles for the navigation header | 26/04/2026 |
| Landing Page | tb01 | `40b208e` | feat: add base styles | added base configurations and CSS variables | 26/04/2026 |
| Landing Page | tb01 | `0c9b461` | feat: add auth styles | added styling for authentication pages | 26/04/2026 |
| Landing Page | tb01 | `fc1adee` | feat(css): add about styles | added specific styles for the about section | 26/04/2026 |
| Landing Page | tb01 | `edeeee6` | style: update about section styles | updated and fixed about section styling | 26/04/2026 |
| Landing Page | tb01 | `c65c8cf` | feat(css): add style.css | added main global style.css file | 26/04/2026 |
| Landing Page | tb01 | `4a1a41e` | feat: add audio folder | added audio folder and background music files | 26/04/2026 |
| Landing Page | tb01 | `6df2c23` | feat: add testimonials interaction | implemented JS logic for testimonials | 26/04/2026 |
| Landing Page | tb01 | `009c161` | feat: implement search functionality | added JS logic for search bar and smooth scroll | 26/04/2026 |
| Landing Page | tb01 | `7519a39` | feat: add newsletter subscription logic | added form validation for newsletter | 26/04/2026 |
| Landing Page | tb01 | `0ba2851` | feat: implement internationalization (i18n) | implemented English/Spanish translation logic | 26/04/2026 |
| Landing Page | tb01 | `79294ec` | feat: add audio controls functionality | added JS logic to play/pause background audio | 26/04/2026 |
| Landing Page | tb01 | `1aab006` | feat(ui): add register page | added HTML structure for register page | 26/04/2026 |
| Landing Page | tb01 | `472ce0b` | feat(ui): add dashboard UI layout | added base HTML layout for the dashboard | 26/04/2026 |
| Landing Page | tb01 | `3b49ab0` | feat(ui): add login page | added HTML structure for login page | 26/04/2026 |
| Landing Page | tb01 | `079ce4f` | feat(uix): merge with new team and redesign project with new theme | merged UI components and applied new dark theme | 26/04/2026 |
| Landing Page | tb01 | `01d228a` | style(platafomr): add style to plataform section | added basic styling to platform section | 18/04/2026 |
| Landing Page | tb01 | `7f5a245` | feat(plataform): add plataform section | added HTML structure for platform section | 18/04/2026 |



#### 5.2.1.5. Execution Evidence for Sprint Review
Durante el primer sprint, se lograron varios hitos importantes en el desarrollo del landing page de la StartUp ElectroCorp. Por lo consiguiente, presentamos un resumen de los logros alcanzados hasta la fecha: <br>

- Establecimiento de repositorios: Se crearon y configuraron repositorios en GitHub para gestionar el código y las pruebas, asegurando una correcta organización y control de versiones, ademas de separar en main y developer para evitar posibles errores. <br>

<img src="assets/Repos.png"></img><br>

- Implementación del Landing Page: Se diseño y se estructuro la landing page de ElectroCorp implementando funcionalidades claves y asegurando que cumpla con lo dictado en la rubrica, como el agregarle un boton de traduccion de idioma y que este en ingles por defecto

- Imágenes del Landing Page:
  
  * Home
    
    <img src="assets/LandingPageMockUps1.png"></img><br>
  
  * Description:

    <img src="assets/LandingPageMockUps2.png"></img><br>
    
  * Goals:

    <img src="assets/LandingPageMockUps3.png"></img><br>
    
  * Pricing
    
    <img src="assets/LandingPageMockUps4.png"></img><br>
 
  * Reviews

    <img src="assets/LandingPageMockUps5.png"></img><br>

  * AboutUs

    <img src="assets/LandingPageMockUps6.png"></img><br>
    
  * Smart Plugins
    
    <img src="assets/LandingPageMockUps7.png"></img><br>

  * Contact
    
    <img src="assets/LandingPageMockUps8.png"></img><br>
    

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Durante el primer sprint, se desarrolló el Landing Page del proyecto de ElectroCorp como una primera entrega visual y detallando algunos aspectos. Esta implementación se centró únicamente en la estructura, diseño, la traduccion de ingles a español y viceversa, y uno que otro toque personal como la implementacion de una musica de fondo. Aunque no se han implementado accesos de inicio de sesion por el momento.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Durante este Sprint1 se llevaron a cabo las siguientes actividades relacionadas con el despliegue de la Landing Page.

Creación de Repositorios y Configuración en GitHub
* Gestión de Versiones: Se implementaron repositorios en GitHub para centralizar el control del código fuente, asegurando un historial detallado de los cambios realizados en la Landing Page y demás componentes.
* Preparación del Entorno: Se realizó la configuración técnica de los repositorios para automatizar los flujos de despliegue mediante el uso de GitHub Pages.
* GitHub Pages:: Se utilizó GitHub Pages como infraestructura de hosting estático, permitiendo que la Landing Page sea accesible de forma pública y segura directamente desde la rama principal del repositorio.

  <img src="assets/GitHubPages1.png"></img><br>

Proceso de Despliegue
Despliegue de la Landing Page:
* Se subió el código de la Landing Page al repositorio correspondiente en GitHub.
* Se configuró GitHub Pages para publicar el sitio en línea.

  <img src="assets/GitHubPages2.png"></img><br>

Verificación del Despliegue:
Se hizo una comprobacion sitio publicado en GitHub Pages para asegurar que todos los elementos funcionaran correctamente.
Se ejecutaron pruebas de funcionalidad para verificar la correcta carga del sitio y la ausencia de errores en el contenido desplegado

  <img src="assets/LandingPageMockUps1.png"></img><br>

Durante el Sprint 1, logramos consolidar la infraestructura de publicación del proyecto mediante la implementación de GitHub Pages. Este flujo de trabajo no solo optimizó el despliegue, sino que estableció un ciclo de integración continua eficiente, dejando el camino preparado para escalar la aplicación web de manera ágil en las próximas fases

link de la landing pages: https://1asi0730-2610-20177-nex.github.io/LandingPage/

#### 5.2.1.8. Team Collaboration Insights during Sprint.
Durante este Sprint 1, el equipo llevó a cabo un trabajo colaborativo enfocado en el diseño, desarrollo y despliegue de la Landing Page de ElectroCorp. Asegurando que la página cumpliera con los objetivos de conversión y comunicación de nuestra propuesta de valor (IoT plug-and-play). Asimismo, se registraron los avances en la gestión del repositorio de GitHub, evidenciados en los commits y métricas de colaboración que reflejan la participación del equipo.

| Author | Task completed |
| :--- | :--- |
| **Alexander Piero Garfias** | Integration of landing page sections, UI/UX core development, and interactive features (i18n, navigation). |
| **Tavara Correa, Sebastian** | HTML5 semantic structuring and GitHub Pages deployment configuration. |
| **Cabrejos Chocce, Diego** | Implementation of global CSS, Dark Mode styling, and Responsive Design adjustments. |
| **Cabrejos Chocco, DIego** | Report documentation development and code refactoring. |
| **Tuncar Vila, Ghorghet** | Cross-browser testing, QA, and broken-link verification. |

* **Link de commits del repositorio del reporte:** [https://github.com/1ASI0730-2610-20177-Nex/Report/commits/develop/]
* **Link de commits del repositorio del landing page:** [https://github.com/1ASI0730-2610-20177-Nex/LandingPage/commits/tb01/]

   <img src="assets/ComitsDocs1.png"></img><br>
   <img src="assets/ComitsDocs2.png"></img><br>
   <img src="assets/ComitsDocs3.png"></img><br>
    <br>
   <img src="assets/ContributorsLanding.png"></img><br>
   <img src="assets/Commits1.png"></img><br>
   <img src="assets/Commits2.png"></img><br>
   <img src="assets/Commits3.png"></img><br>

## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas
## 5.4. Video About-the-Product.
# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-Team.
# Bibliografía 
# Anexos
