<img src="images/logo-upc.png" alt="Logo de la UPC" />
</p>

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center"><strong>Ingeniería de Software</strong><br>
Aplicaciones para Dispositivos Móviles<br>
<strong>Profesor:</strong> Jorge Luis Mayta  </p>
<h3 align="center">Seccion: 1795  </h3>

<h2 align="center">INFORME</h2>
<h2 align="center">2025 - 20</h2>

<h3 align="center">Startup: PolarNet</h3>
<p align="center"><strong>Producto: CoolGuard </strong></p>

<h3 align="center">Team Members:</h3>

<div align="center">

| **Member**                           | **Code**     |
|--------------------------------------|--------------|
|  Paulo Percy Quincho Gamarra     |   U20191E562 |
|   Geronimo Quispe Pablo Antonio     | u202314304  |
|    Sandro Dinklange Arevalo   |  u202313419 |
|   Marzál Pérez, Jamir Ángel     |  u201824409 |
|       |    |

</div>

<p align="center"><strong>Julio 2025</strong></p>

<div style="page-break-before: always;"></div>

# Registro de Versiones del Informe
| Versión | Fecha       | Autor(es)                                                              | Descripción                                                                                                                                         |
|---------|-------------|------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| TB1     | 13/09/2025  | Paulo Percy Quincho Gamarra       | Desarrollo del capítulo I: Introducción                                                                                                             |
| TB1     | 14/09/2025  | Geronimo Quispe Pablo Antonio       | Desarrollo del capítulo II                                                                                                            |
| TB1     | 15/09/2025  | Sandro Dinklange Arevalo      | Desarrollo del capítulo II                                                                                                               |
| TB1     | 16/09/2025  | Marzál Pérez, Jamir Ángel      | Desarrollo del capítulo II                                                                                                               |
| TB1     | 17/09/2025  |       | Desarrollo del capítulo II                              |

# Project Report Collaboration Insights
Link del repositorio: https://github.com/Paulo02-pixel/Aplicaciones-Para-Dispositivos-Moviles-1795.git

# Tabla de Contenidos

- [Capítulo I: Presentación](#capítulo-i-presentación)  
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

- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)  
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
    - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)  
  - [2.4. Requirements specification](#24-requirements-specification)  
    - [2.4.1. User Stories](#241-user-stories)  
    - [2.4.2. Impact Mapping](#242-impact-mapping)  
    - [2.4.3. Product Backlog](#243-product-backlog)  
  - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)  
    - [2.5.1. EventStorming](#251-eventstorming)  
      - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)  
      - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)  
      - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)  
    - [2.5.2. Context Mapping](#252-context-mapping)  
    - [2.5.3. Software Architecture](#253-software-architecture)  
      - [2.5.3.1. Context Level Diagrams](#2531-software-architecture-context-level-diagrams)  
      - [2.5.3.2. Container Level Diagrams](#2532-software-architecture-container-level-diagrams)  
      - [2.5.3.3. Deployment Diagrams](#2533-software-architecture-deployment-diagrams)  
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)  
    - [2.6.x. Bounded Context](#26x-bounded-context)  
      - [2.6.x.1. Domain Layer](#26x1-domain-layer)  
      - [2.6.x.2. Interface Layer](#26x2-interface-layer)  
      - [2.6.x.3. Application Layer](#26x3-application-layer)  
      - [2.6.x.4. Infrastructure Layer](#26x4-infrastructure-layer)  
      - [2.6.x.5. Component Level Diagrams](#26x5-bounded-context-software-architecture-component-level-diagrams)  
      - [2.6.x.6. Code Level Diagrams](#26x6-bounded-context-software-architecture-code-level-diagrams)  
        - [2.6.x.6.1. Domain Layer Class Diagrams](#26x61-bounded-context-domain-layer-class-diagrams)  
        - [2.6.x.6.2. Database Design Diagram](#26x62-bounded-context-database-design-diagram)  

- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)  
  - [3.1. Product design](#31-product-design)  
    - [3.1.1. Style Guidelines](#311-style-guidelines)  
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)  
    - [3.1.2. Information Architecture](#312-information-architecture)  
      - [3.1.2.1. Organization Systems](#3121-organization-systems)  
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)  
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)  
      - [3.1.2.4. Searching Systems](#3124-searching-systems)  
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)  
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)  
      - [3.1.3.1. Wireframe](#3131-landing-page-wireframe)  
      - [3.1.3.2. Mock-up](#3132-landing-page-mock-up)  
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)  
      - [3.1.4.1. Wireframes](#3141-mobile-applications-wireframes)  
      - [3.1.4.2. Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)  
      - [3.1.4.3. Mock-ups](#3143-mobile-applications-mock-ups)  
      - [3.1.4.4. User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)  
      - [3.1.4.5. Prototyping](#3145-mobile-applications-prototyping)  

- [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)  
  - [4.1. Software Configuration Management](#41-software-configuration-management)  
    - [4.1.1. Development Environment Configuration](#411-software-development-environment-configuration)  
    - [4.1.2. Source Code Management](#412-source-code-management)  
    - [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)  
    - [4.1.4. Deployment Configuration](#414-software-deployment-configuration)  
  - [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)  
    - [4.2.1. Sprint n](#421-sprint-n)  
      - [4.2.1.1. Sprint Planning n](#4211-sprint-planning-n)  
      - [4.2.1.2. Sprint Backlog n](#4212-sprint-backlog-n)  
      - [4.2.1.3. Development Evidence](#4213-development-evidence-for-sprint-review)  
      - [4.2.1.4. Testing Suite Evidence](#4214-testing-suite-evidence-for-sprint-review)  
      - [4.2.1.5. Execution Evidence](#4215-execution-evidence-for-sprint-review)  
      - [4.2.1.6. Services Documentation](#4216-services-documentation-evidence-for-sprint-review)  
      - [4.2.1.7. Software Deployment Evidence](#4217-software-deployment-evidence-for-sprint-review)  
      - [4.2.1.8. Team Collaboration Insights](#4218-team-collaboration-insights-during-sprint)  
  - [4.3. Validation Interviews](#43-validation-interviews)  
    - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)  
    - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)  
    - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)  

## Anexos

# Student Outcome

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|-------------------------|--------------------------|------------------|
| Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de ingeniería de software. | **TB1: Paulo Percy Quincho Gamarra (U20191E562)** <br> Investigó y aplicó conceptos de programación backend con Python y Node.js, reforzando conocimientos en bases de datos SQL y NoSQL. <br><br> **TB1: Geronimo Quispe Pablo Antonio (U202314304)** <br> Estudió metodologías ágiles y las aplicó en la organización del proyecto, mejorando la planificación de tareas y la coordinación del equipo. <br><br> **TB1: Sandro Dinklange Arevalo (U202313419)** <br> Actualizó sus conocimientos en arquitectura de software y modelado de base de datos, contribuyendo al diseño estructurado de la solución. <br><br> **TB1: Jamir Ángel Marzál Pérez (U201824409)** <br> Reforzó conocimientos en programación orientada a objetos y patrones de diseño, aplicándolos en la implementación de módulos del sistema. | Cada integrante actualizó y aplicó conceptos clave de software en el proyecto, asegurando un mejor entendimiento técnico y fortaleciendo sus competencias profesionales para proyectos reales. |
| Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de tecnologías de ingeniería de software. | **TB1: Paulo Percy Quincho Gamarra (U20191E562)** <br> Participó en la revisión de nuevas herramientas y frameworks, demostrando apertura al aprendizaje continuo para fortalecer el backend del proyecto. <br><br> **TB1: Geronimo Quispe Pablo Antonio (U202314304)** <br> Investigó sobre herramientas de gestión colaborativa como Trello y GitHub, mostrando interés en ampliar su experiencia en entornos profesionales. <br><br> **TB1: Sandro Dinklange Arevalo (U202313419)** <br> Estudió sobre servicios en la nube y su impacto en aplicaciones móviles, comprendiendo la importancia de actualizarse en nuevas tecnologías. <br><br> **TB1: Jamir Ángel Marzál Pérez (U201824409)** <br> Reconoció la necesidad de mejorar constantemente en lenguajes modernos como TypeScript y frameworks frontend, buscando aplicarlos en futuros proyectos. | Los integrantes demostraron compromiso con el aprendizaje permanente, entendiendo que la actualización constante es clave para desenvolverse en proyectos de software y adaptarse a los cambios tecnológicos. |




# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup
**PolarNet** es una aplicación móvil desarrollada para optimizar la gestión y el mantenimiento de sistemas de refrigeración en negocios que dependen del frío de manera crítica, como supermercados, minimarkets, laboratorios, restaurantes y empresas de los sectores alimentario o farmacéutico.  

La app permite a los usuarios mantenerse conectados en todo momento con sus equipos y con técnicos o proveedores especializados, ofreciendo una administración integral, preventiva y automatizada desde la comodidad del celular.  

De igual manera, **PolarNet** incluye un módulo especializado para técnicos y proveedores, donde pueden visualizar todos los equipos que atienden, organizar visitas de servicio, consultar historiales técnicos y generar reportes de manera ágil y eficiente, directamente desde la app.  

**Misión:** En PolarNet, nuestra misión es proporcionar una solución móvil inteligente que proteja el inventario de los negocios y potencie la gestión de sus sistemas de refrigeración, al mismo tiempo que brinda herramientas prácticas para mejorar la productividad de técnicos y proveedores.  

**Visión:** Convertirnos en la aplicación líder en gestión y mantenimiento de equipos de refrigeración, iniciando en Lima y expandiéndonos a nivel nacional, facilitando el acceso móvil a la tecnología en todo el Perú.  

---

### 1.1.2 Perfiles de integrantes del equipo

<table border="1" cellspacing="0" cellpadding="8">
  <tr>
    <td style="text-align: center" align="center">
      <p align="center">
        Paulo Percy Quincho Gamarra - U20191E562  
        <br>
        <img src="images/paulo-foto.PNG" alt="Foto Paulo" width="45%">
      </p>
    </td>
    <td style="text-align: center" align="center">
      Soy una persona responsable, comprometida con mis objetivos y soy puntual, lo que me permite realizar todos los trabajos a tiempo. Me gusta tener buena comunicación con el equipo. 
    </td>
    <td style="text-align: center" align="center">
      Conocimientos en Python, JavaScript, TypeScript, SQL y NoSQL. Disfruto entregar los mejores resultados posibles y fomentar la buena comunicación en grupo.
    </td>
  </tr>
  
  <tr>
    <td style="text-align: center" align="center">
      <p align="center">
        Geronimo Quispe Pablo Antonio - U202314304  
        <br>
        <img src="images/pablo-foto.PNG" alt="Foto Geronimo" width="45%">
      </p>
    </td>
    <td style="text-align: center" align="center">
      Mi nombre es Pablo,tengo 20 años y soy estudiante de Ingeniería de Software en la UPC, sede San Miguel. Soy una persona decidida, confiable, responsable y honesta con mi grupo de trabajo ,siendo lo más útil posible.
    </td>
    <td style="text-align: center" align="center">
      Tengo conocimientos en C++,C# y php. Cada día trato de dar una mejor versión de mi y aprender de mis errores.
    </td>
  </tr>
  
  <tr>
    <td style="text-align: center" align="center">
      <p align="center">
        Sandro Dinklange Arevalo - U202313419  
        <br>
        <img src="images/sandro-foto.PNG" alt="Foto Sandro" width="45%">
      </p>
    </td>
    <td style="text-align: center" align="center">
      Soy un estudiante de 18 años que cursa la carrera de Ingeniería de Software, en sexto ciclo, en la Universidad Peruana de Ciencias Aplicadas (UPC).
    </td>
    <td style="text-align: center" align="center">
      Cuento con conocimientos en C++.
    </td>
  </tr>
  
  <tr>
    <td style="text-align: center" align="center">
      <p align="center">
        Jamir Ángel Marzál Pérez - U201824409  
        <br>
        <img src="images/jamir-foto.PNG" alt="Foto Jamir" width="45%">
      </p>
    </td>
    <td style="text-align: center" align="center">
      Me gusta colaborar con mis compañeros, aportar ideas y trabajar de forma organizada para lograr objetivos comunes.
    </td>
    <td style="text-align: center" align="center">
      Conocimientos en Python, C#, Java y SQL. Enfocado en mejorar continuamente mis habilidades técnicas.
    </td>
  </tr>
  
  <tr>
    <td style="text-align: center" align="center">
      <p align="center">
        [Nombre del 5° Integrante] - [Código]  
        <br>
        <img src="images/integrante5.png" alt="Foto Integrante 5" width="45%">
      </p>
    </td>
    <td style="text-align: center" align="center">
      [Descripción breve del integrante].
    </td>
    <td style="text-align: center" align="center">
      [Conocimientos técnicos y habilidades].
    </td>
  </tr>
</table>

## 1.2 Solution Profile

**Nombre del producto:** PolarNet  

**Descripción:**  
PolarNet es una aplicación móvil innovadora y eficiente, creada para optimizar la gestión y el mantenimiento de equipos de congelación en negocios que dependen críticamente del frío, como supermercados, laboratorios, restaurantes y compañías de los sectores alimentario y farmacéutico.  

Desde el celular, los usuarios pueden acceder a un monitoreo constante en tiempo real, recibir alertas automáticas ante fallos, programar mantenimientos inteligentes y consultar reportes detallados del rendimiento de los equipos, todo desde una sola app.  

La solución centraliza la gestión en el dispositivo móvil y facilita la conexión directa entre negocios, técnicos y proveedores especializados, permitiendo una operación más segura, económica y sostenible en cualquier momento y lugar.  

**Monetización:**  
PolarNet monetiza su aplicación móvil a través de un modelo de suscripciones y tarifas por servicio. Los negocios podrán elegir entre diferentes planes mensuales.  

Por otro lado, los proveedores de servicios y técnicos podrán pagar una suscripción mensual para usar un módulo centralizado dentro de la aplicación, donde gestionan solicitudes de mantenimiento, organizan su flujo de trabajo y mejoran la calidad de la atención desde su dispositivo móvil.  

Además, la app permitirá habilitar tarifas por transacción para intervenciones técnicas no incluidas en el plan de suscripción, garantizando flexibilidad y nuevas oportunidades de ingresos.  

---

### 1.2.1 Antecedentes y problemática
PolarNet busca dar solución a los principales desafíos que enfrentan los negocios en la gestión de equipos de congelación, como supermercados, restaurantes y empresas del sector farmacéutico, que deben mantener la cadena de frío de manera constante.  

Estos negocios suelen lidiar con la falta de soluciones móviles accesibles, la dificultad de realizar mantenimientos preventivos efectivos y la ausencia de herramientas que permitan monitorear y gestionar el rendimiento de los equipos en tiempo real.  

Con su aplicación móvil, PolarNet pone todo este control en la palma de la mano del usuario, ofreciendo monitoreo constante, alertas inmediatas y una gestión automatizada que facilita la prevención de fallos y mejora la eficiencia operativa desde cualquier lugar.

## 5Ws y 2Hs

| Pregunta   | Descripción |
|------------|-------------|
| **What?** <br> ¿Cuál es el problema? | Los negocios que dependen de sistemas de congelación enfrentan grandes retos operativos por fallas imprevistas y la falta de un mantenimiento adecuado. La ausencia de monitoreo constante, el consumo energético elevado no detectado a tiempo y los problemas de temperatura pueden ocasionar pérdidas de productos, afectar la calidad del servicio y generar importantes costos económicos. |
| **When?** <br> ¿Cuándo ocurre este problema? | Estas situaciones suelen presentarse durante la operación continua de los equipos, en especial cuando no hay técnicos disponibles de inmediato o no se realiza un seguimiento periódico del estado de los sistemas. |
| **Where?** <br> ¿Dónde sucede este problema? | Este tipo de inconvenientes se da en negocios a nivel nacional, con mayor incidencia en Lima, donde mantener la cadena de frío es crítico en sectores como el alimentario, farmacéutico y logístico. Asimismo, impacta a las empresas proveedoras de refrigeración que atienden a múltiples clientes sin una herramienta centralizada para la gestión. |
| **Who?** <br> ¿Quiénes están implicados? | El problema afecta tanto a los dueños y administradores de negocios que utilizan congeladoras como a los técnicos y proveedores responsables del mantenimiento de estos equipos. |
| **Why?** <br> ¿Qué origina este problema? | La causa principal es la falta de soluciones tecnológicas integrales y accesibles que combinen funciones como monitoreo, alertas, historial de uso y planificación de mantenimientos. Muchas empresas aún dependen de procesos manuales o carecen de controles preventivos, quedando vulnerables a fallas críticas. |
| **How?** <br> ¿Cómo se llegó a esta situación? | Esta situación se ha generado por la acumulación de incidentes inesperados y la poca digitalización del mantenimiento preventivo. Como resultado, los negocios dependen en gran medida de acciones reactivas en lugar de planes anticipados, lo que incrementa los costos, retrasa las atenciones y aumenta la carga operativa. |
| **How much?** <br> ¿Cuál es el impacto económico? | Las pérdidas económicas varían según el tipo de negocio, pero una falla en un sistema de congelación puede representar desde cientos hasta miles de soles en productos dañados. A esto se suman los tiempos de inactividad, la insatisfacción de clientes y los gastos derivados de reparaciones o sustituciones de equipos. |

---

## 1.2.2 Lean UX Process

### 1.2.2.1 Lean UX Problem Statement
El sector de la refrigeración comercial y técnica enfrenta grandes retos en la administración, el mantenimiento y la trazabilidad de los equipos de congelación. Negocios que dependen críticamente del frío como supermercados, minimarkets, restaurantes, laboratorios y empresas del rubro alimentario o farmacéutico aún operan sin un monitoreo en tiempo real y con mantenimientos mayormente reactivos, lo que genera pérdidas económicas, consumo energético ineficiente y riesgo constante sobre el inventario.  

Las soluciones disponibles no cubren la necesidad de una aplicación confiable y automatizada que centralice la gestión y ofrezca un enfoque predictivo y transparente tanto para negocios como para técnicos y proveedores. La falta de historial técnico digital, reportes accesibles y alertas preventivas limita la capacidad de reacción frente a fallas y afecta la calidad del servicio.  

**PolarNet** responde a este escenario con una aplicación móvil integral que conecta a negocios y técnicos especializados, brindando funciones como monitoreo en tiempo real de temperatura y consumo, programación inteligente de mantenimientos, notificaciones instantáneas por fallos, reportes automáticos y trazabilidad completa de cada equipo.  

Además, ofrece a los proveedores de servicios un módulo dentro de la app para gestionar equipos atendidos, planificar visitas y consultar historiales técnicos de manera ágil. La primera etapa de implementación se enfocará en Lima, apoyando a negocios que requieren garantizar el rendimiento de sus sistemas de congelación y a proveedores que buscan modernizar sus operaciones con herramientas digitales avanzadas.  

El éxito se medirá en la reducción de fallas inesperadas, la optimización del consumo energético, la mejora en la eficiencia de los técnicos y el aumento de la satisfacción de los clientes, asegurando continuidad operativa y fidelización de los usuarios de la app.

---

### 1.2.2.2 Lean UX Assumptions

**Business Outcomes**

- Incrementar en un 15% los usuarios activos de la aplicación móvil PolarNet, consolidando su presencia en el mercado.  
- Potenciar la visibilidad en redes sociales, especialmente en sectores como alimentos y técnicos en refrigeración, destacando la app como herramienta innovadora.  
- Generar confianza en la efectividad del monitoreo y mantenimiento automatizado, mostrando la app como un aliado confiable para proteger inventario y optimizar operaciones.  
- Mantener informados a los usuarios mediante notificaciones móviles en tiempo real, sobre fallas térmicas, cortes de energía o anomalías en los equipos.  
- Consolidar una base de usuarios dispuestos a adquirir membresías premium desde la app, con beneficios como mantenimiento predictivo, reportes personalizados y soporte técnico prioritario.  
- Establecer alianzas con plataformas de geolocalización como Google Maps, para mejorar el alcance y la programación de visitas técnicas desde dispositivos móviles.  
- Fomentar la participación activa de los usuarios en la app, a través de encuestas, valoraciones de técnicos y comentarios sobre el desempeño de los equipos.  
- Diseñar una interfaz sencilla, intuitiva y pensada para móvil, que ofrezca una experiencia atractiva sin sobrecargar de información.  
- Implementar inteligencia artificial en la aplicación, para optimizar mantenimientos inteligentes, rutas de técnicos y recomendaciones preventivas frente a posibles fallos.  

## User Outcomes

### ¿Quién será nuestro usuario?
- Negocios que dependen de manera crítica de sistemas de refrigeración, como supermercados, minimarkets, restaurantes, laboratorios y empresas en los sectores alimentario y farmacéutico.  
- Técnicos especializados en refrigeración encargados del mantenimiento de estos equipos.  
- Proveedores de equipos de refrigeración que desean ofrecer un servicio postventa más eficiente.  

---

### ¿Dónde encaja nuestro producto en su vida?
- En situaciones donde los negocios deben garantizar el funcionamiento continuo de sus sistemas de frío para evitar pérdidas económicas por fallas imprevistas.  
- En la rutina diaria de los técnicos, quienes gestionan múltiples clientes, visitas y tareas de mantenimiento.  
- En las operaciones diarias de los negocios que requieren registros detallados y reportes precisos sobre el rendimiento de sus sistemas de refrigeración.  

---

### ¿Qué problemas tiene nuestro producto y cómo se pueden resolver?
- **Problema:** Garantizar que los datos de monitoreo (temperatura, consumo energético, fallas, etc.) sean precisos y confiables.  
  **Solución:** Integrar sensores calibrados y sistemas automáticos de verificación de datos antes de almacenarlos.  

- **Problema:** La adopción inicial por parte de usuarios no familiarizados con la tecnología.  
  **Solución:** Ofrecer una interfaz sencilla, guías paso a paso y soporte técnico accesible para facilitar el uso.  

---

### ¿Cómo y cuándo se utiliza nuestro producto?
- Se accede a través de la aplicación web, disponible tanto para computadoras como dispositivos móviles.  
- Se usa a diario para monitorear los equipos de refrigeración, recibir alertas, programar mantenimientos y revisar historiales técnicos.  
- También se activa automáticamente en segundo plano al integrar sensores de monitoreo con la plataforma.  

---

### ¿Qué problemas tiene nuestro producto?
- En sus fases iniciales, podría carecer de integraciones con algunos dispositivos de terceros.  
- Algunos usuarios necesitarán formación para aprovechar al máximo las funcionalidades avanzadas.  
- Los técnicos tradicionales pueden resistirse al cambio hacia un sistema digital.  

---

### ¿Qué características son esenciales para la app?
- Monitoreo en tiempo real de temperatura, consumo energético y tiempo de uso.  
- Alertas automáticas ante fallos en los equipos.  
- Historial técnico completo con reportes exportables en PDF.  
- Calendario de mantenimiento preventivo con notificaciones programadas.  
- Módulo exclusivo para técnicos con gestión de visitas y clientes.  
- Soporte técnico inteligente y recomendaciones predictivas mediante IA.  
- Registro de múltiples ubicaciones y usuarios con distintos roles.  
- Interfaz minimalista e intuitiva para facilitar la adopción.  

---

### ¿Cómo debe verse y comportarse nuestro producto?
- **Interfaz amigable y confiable:** clara, ordenada y fácil de navegar, con gráficos e indicadores intuitivos.  
- **Diseño centrado en tareas críticas:** acceso rápido a fallos, próximas visitas y reportes de equipos.  
- **Accesibilidad multiplataforma:** disponible en web y móvil, adaptada para oficina y campo, con notificaciones inmediatas.  
- **Simplicidad:** panel centralizado para ver clientes, equipos en riesgo y visitas programadas, con generación de reportes rápida y fácil.  

---

### ¿Qué valor busca el cliente?
- **Gestión técnica simplificada:** mantenimiento predictivo, historiales claros y clientes organizados.  
- **Seguridad operativa y sin sorpresas:** monitoreo constante, alertas automáticas y control total.  
- **Eficiencia energética y trazabilidad:** detección anticipada de problemas, identificación de equipos en riesgo.  

---

### ¿Qué beneficios adicionales obtendrá el cliente?
- Visibilidad total del estado de sus equipos desde cualquier lugar y en cualquier momento.  
- Soporte técnico ágil gracias al historial detallado y alertas automáticas.  
- Reducción de costos operativos mediante mantenimientos preventivos y mayor eficiencia energética.  
- Reportes personalizados y exportables.  
- Automatización de visitas técnicas al detectar patrones de fallas.  

---

### ¿Cómo atraeremos usuarios?
- Marketing dirigido a nichos clave: supermercados, restaurantes y empresas del sector frío mediante LinkedIn, correos y llamadas estratégicas.  
- Alianzas con proveedores de equipos para incluir PolarNet en sus paquetes postventa.  
- Prueba gratuita de 14 días de versiones premium, con monitoreo limitado, para mostrar el valor en tiempo real.  

---

### ¿Cómo generaremos ingresos?
- **Suscripción mensual para negocios:** según número de equipos, tipos de reportes y funcionalidades.  
- **Modelo freemium:** versión gratuita con funciones limitadas y anuncios.  
- **Publicidad dirigida (opcional):** visibilidad para marcas de refrigeración dentro de la plataforma.  

---

### ¿Cuál es nuestra competencia y cómo la superamos?
- **Competencia:** Otras aplicaciones centradas en gestión de datos y mantenimiento de equipos de refrigeración.  
- **Nuestra ventaja:** PolarNet está diseñado exclusivamente para negocios que dependen del frío, detecta anomalías en tiempo real, genera alertas y automatiza acciones.  

---

### ¿Cuál es el mayor riesgo para el producto?
- **Adopción lenta:** proveedores que aún usan agendas físicas o Excel.  
- **Falta de adopción inicial:** convencer a los primeros usuarios de la utilidad y confiabilidad de la app.  
- **Desconfianza en la precisión de los sensores:** riesgo de perder valor si los datos no son precisos.  

---

### ¿Cómo lo resolveremos?
- **Algoritmos de validación:** IA para verificar precisión y filtrar información incorrecta.  
- **Capacitación y soporte:** tutoriales, videos y soporte técnico accesible.  
- **Estrategia progresiva de integraciones:** empezar con los equipos más utilizados y luego ampliar compatibilidad con APIs.  
- **Sensores certificados:** integrar solo dispositivos validados para garantizar precisión.  

---

## 1.2.2.3 Lean UX Hypothesis

1. **Hipótesis 1: Mejora en la eficiencia operativa y reducción de fallas inesperadas**  
   Al centralizar en una sola app todas las funciones de monitoreo, mantenimiento y gestión de equipos de refrigeración, los negocios y proveedores podrán operar con mayor eficiencia, simplificando procesos y reduciendo el riesgo de fallas inesperadas.  
   Validación: reducción en reportes de fallas térmicas y mejor organización de mantenimientos preventivos.  

2. **Hipótesis 2: Control de pérdidas operativas y consumo energético**  
   Si ofrecemos herramientas de análisis en tiempo real y alertas automáticas, los usuarios podrán anticiparse a fallas, reducir pérdidas y optimizar su consumo energético.  
   Validación: incremento en el uso de estas funciones y reducción de costos por interrupciones.  

3. **Hipótesis 3: Mejora en el servicio técnico predictivo y personalizado**  
   Con reportes automáticos e históricos de cada equipo, los técnicos podrán brindar un servicio más predictivo y personalizado.  
   Validación: técnicos valoran la utilidad de los reportes y clientes expresan mayor satisfacción.  

4. **Hipótesis 4: Trazabilidad y seguridad de la información técnica**  
   Si garantizamos trazabilidad en cada acción y protegemos la información técnica, generaremos confianza en negocios y proveedores.  
   Validación: mayor fidelidad de usuarios y reducción en incidencias por pérdida de datos.  

5. **Hipótesis 5: Transición a una gestión moderna y digitalizada de refrigeración**  
   Al ofrecer una solución digital sencilla y especializada, ayudaremos a negocios y técnicos a migrar hacia una gestión moderna.  
   Validación: rápida adopción, baja tasa de abandono y uso frecuente de funciones clave.  

## 1.2.2.4 Lean UX Canvas

<p align="center">
  <img src="images/canva.PNG" alt="Canvas" />
</p>

## 1.3 Segmentos objetivo

### Segmento Objetivo #1: Negocios que utilizan sistemas de refrigeración

**Aspectos demográficos:**
- Tipo de negocio: Empresas de diferentes tamaños, desde pequeñas hasta grandes.  
- Sectores: Alimentación, farmacéutico, restauración y comercio minorista.  
- Nivel de necesidad: Alta dependencia de equipos de refrigeración.  

**Aspectos geográficos:**
- Nacionalidad: Peruana.  
- Ubicación: Áreas urbanas.  
- Región: Lima, con planes de expansión a nivel nacional.  

**Aspectos psicográficos:**
- Empresas que buscan evitar pérdidas económicas debido a fallas en los sistemas de refrigeración.  
- Negocios que necesitan un control eficiente del consumo energético.  
- Administradores interesados en implementar soluciones tecnológicas para optimizar operaciones y preservar la calidad del inventario.  

---

### Segmento Objetivo #2: Proveedores de servicios y equipos de refrigeración

**Aspectos demográficos:**
- Tipo de empresa: Técnicos independientes, pequeñas y medianas empresas (PYMES), y proveedores especializados en refrigeración.  
- Rol: Técnicos de mantenimiento, instaladores y empresas de soporte técnico.  

**Aspectos geográficos:**
- Nacionalidad: Peruana.  
- Ubicación: Áreas urbanas.  
- Región: Lima, con planes de expansión a nivel nacional.  

**Aspectos psicográficos:**
- Técnicos que desean organizar y gestionar sus visitas de manera más eficiente y centralizada.  
- Empresas que buscan mejorar la trazabilidad de sus servicios, con la capacidad de generar reportes automáticos.  
- Profesionales que desean ofrecer un servicio más personalizado y predictivo a sus clientes.  
=======
## Capítulo II: Requirements Elicitation & Analysis <a id="cap2"></a>

### 2.1. Competidores

**Competidor 1: Infraspeak**
Infraspeak: Es uno de los softwares de mantenimiento y gestión de órdenes de trabajo, con buen reconocimiento puesto que cuenta con módulos robustos, tareas preventivas y un buen soporte


---

**Competidor 2: Persat**
Con sedes en Latinoamérica, sus funciones más relevantes cuentan con asignación de tareas de servicio, una buena localización regional así como un gran enfoque al servicio técnico


---

**Competidor 3: Kiconex**
 Este software basado en el control remoto en la nube para equipos de refrigeración cuenta con fuertes monitorios, sensores, iot y un buen soporte de hardware profesional, dedicados mayormente en Europa.
#### 2.1.1. Análisis competitivo

<table> 
  <tr>
    <th colspan="7"> Competitive Analysis Landscape </th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar acabo este análisis? </td>
    <td colspan="5"> Pregunta </td>
  </tr>
  <tr>
    <td colspan="5"> Para poder evaluar el posicionamiento competitivo de nuestra app frente a competidores perfecto para identificar fortalezas, debilidades, oportunidades y amenazas en el mercado peruano de gestión y monitoreo de refrigeración. </td>
  </tr>
  <tr>
    <td colspan="2"> Productos </td>
    <td> PolarNet  </td>
    <td> Infraspeak </td>
    <td> Persat </td>
    <td> Kiconex </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>App móvil enfocada en monitoreo y mantenimiento preventivo de refrigeración comercial. </td>
    <td> Plataforma internacional para mantenimiento y monitoreo.. </td>
    <td> App de gestión de equipos de campo y mantenimiento. </td>
    <td> App de refrigeración industrial con sistema. </td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
    <td> Interfaz simple, costos accesibles, soporte local, alertas predictivas en tiempo real. </td>
    <td> Solución integral con muchos módulos y certificaciones internacionales. </td>
    <td> Amplia red de técnicos y logística integrada.. </td>
    <td> Experiencia técnica en refrigeración industrial y hardware especializado.. </td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td> Mercado Objetivo </td>
    <td> Supermercados, restaurantes y cadenas minoristas. </td>
    <td> Grandes empresas y facilities. </td>
    <td> Empresas de servicios técnicos, distribuidores. </td>
    <td> Plantas industriales, exportadoras. </td>
  </tr>
  <tr>
    <td> Estrategias de Marketing </td>
    <td> Marketing digital, alianzas con proveedores, asociaciones locales,etc. </td>
    <td> Ventas consultivas a grandes cuentas, partners globales. </td>
    <td> Marketing basado en casos de éxito y distribuidores. </td>
    <td> Promoción a través de fabricantes e instaladores, ferias industriales. </td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td> Productos & Servicios </td>
    <td> App móvil, IoT para monitoreo, reportes automáticos. </td>
    <td> Plataforma modular, integraciones con IoT. </td>
    <td> App móvil y web para gestión de técnicos y mantenimiento. </td>
    <td> Sistemas de refrigeración y hardware para control remoto. </td>
  </tr>
  <tr>
    <td> Precios & Costos </td>
    <td> Modelo mensual accesible, pago por equipo monitoreado. </td>
    <td> Modelo empresarial con precios premium. </td>
    <td> Suscripción mensual media, pago por usuario técnico. </td>
    <td> Precios altos ligados al hardware e instalación. </td>
  </tr>
  <tr> 
    <td>Canales de distribución (Web y/o Móvil)</td>
    <td> App móvil y dashboard web con soporte local. </td>
    <td> Web, app móvil, integraciones API. </td>
    <td> App móvil y web, CRM integrado. </td>
    <td> Hardware y software propio, canal de distribuidores. </td>
  </tr>
  <tr>
    <td rowspan="4"> Análisis SWOT </td>
    <td> Fortalezas </td>
    <td> Soporte local, precios competitivos, adaptación rápida a normativas, UI amigable. </td>
    <td> Amplia trayectoria, reputación internacional, plataforma completa. </td>
    <td> Experiencia en gestión de técnicos y logística integrada. </td>
    <td> Hardware especializado en refrigeración industrial. </td>
  </tr>
  <tr>
    <td> Debilidades </td>
    <td> Marca nueva, menos funcionalidades avanzadas que otras empresas internacionales. </td>
    <td> Costos elevados, menor flexibilidad. </td>
    <td> Poca especialización en refrigeración crítica. </td>
    <td> Requiere inversión inicial alta y poca presencia local en Perú. </td>
  </tr>
  <tr>
    <td> Oportunidades </td>
    <td> Creciente necesidad de monitoreo y cumplimiento normativo en Perú, alianzas con proveedores de equipos. </td>
    <td> Expansión a mercados emergentes con soluciones más accesibles. </td>
    <td> Especializarse en nichos críticos </td>
    <td> Ampliar servicios en Latam con soporte remoto. </td>
  </tr>
  <tr>
    <td> Amenazas </td>
    <td> Entrada de competidores internacionales con precios agresivos o alianzas locales.</td>
    <td> Startups locales más baratas y ágiles. </td>
    <td> Competidores globales con más capital. </td>
    <td> Sustitución tecnológica por soluciones puras sin hardware. </td>
  </tr>
</table>
#### 2.1.2. Estrategias y tácticas frente a competidores

Hemos identificado diversas estrategias y tácticas para diferenciarse y competir efectivamente con otros actores del mercado de la gestión y monitoreo de sistemas de refrigeración. A continuación se detallan las principales:

---

**1. Estrategias de Diferenciación:**

- **Automatización y Mantenimiento Preventivo**: A diferencia de los competidores identificados, PolarNet se enfoca en ofrecer una solución integral y especializada para refrigeración, con monitoreo en tiempo real, alertas automáticas y programación inteligente de mantenimientos. Esto permite a los negocios reducir incidencias y gestionar sus equipos de manera proactiva.

- **Experiencia del usuario como ventaja competitiva**: Se invertirá en una interfaz y procesos extremadamente simples y agradables para el usuario. El objetivo es que cada interacción genere confianza y sensación de control, reduciendo la fricción en comparación con los competidores.

- **Construcción de comunidad y fidelización**: Crear foros, newsletters, o espacios exclusivos donde proveedores y clientes intercambien experiencias y recomendaciones. Esto genera una comunidad difícil de replicar por la competencia.

---

**2. Tácticas de Marketing:**

- **Aumento de usuarios fieles**: Mostrar funcionalidades clave del sistema en fepublicar historias reales de reducción de costos y tiempos gracias al uso de la plataforma para reforzar la credibilidad.ias industriales y eventos del sector alimentario y farmacéutico.

---

**3. Estrategias de Precios:**

- **Modelo Freemium**: Versión gratuita para registro de equipos y mantenimientos básicos, con servicios avanzados (diagnóstico predictivo, analítica, reportes) en planes de pago.

- **Planes escalonados para técnicos y proveedores**: Desde un plan básico para pequeños talleres hasta uno premium para grandes distribuidores.

---

**4. Expansión y Adaptabilidad:**

- **Foco inicial en Lima y principales ciudades del Perú**: Implementar pilotos locales para adaptar procesos a necesidades reales del mercado antes de escalar.

- **Colaboraciones con Proveedores Locales**: Estableceremos alianzas estratégicas con proveedores de equipos de refrigeración y servicios técnicos en Perú, lo que nos distinguirá de la competencia al tener un sistema sólido y diseñado especialmente para el mercado peruano
---

### 2.2. Entrevistas.

#### 2.2.1. Diseño de entrevistas

**Segmento Objetivo #1: Negocios que utilizan sistemas de refrigeración**

1. ¿Qué marcas o empresas relacionadas con refrigeración/servicios técnicos te inspiran confianza? 
2. ¿Qué factores te hacen elegir una marca sobre otra (precio, calidad, soporte, reputación)? 
3. ¿Qué dispositivos usas con mayor frecuencia para tu trabajo (smartphone, laptop, tablet)? 
4. ¿Qué características consideras más importantes al seleccionar una aplicación de este tipo? 
5. ¿Cuáles son tus principales preocupaciones a la hora de gestionar/obtener el servicio o producto? 
6. Si pudieras mejorar una sola cosa del servicio actual, ¿qué sería?


**Segmento Objetivo #2: Proveedores de servicios y equipos de refrigeración**

1. ¿Podrías contarnos brevemente sobre tu empresa o rol en el negocio de refrigeración?
2. ¿Cuáles son tus principales preocupaciones al ofrecer servicios de refrigeración a tus clientes?
3. ¿Qué características consideras importantes en una aplicación o sistema para gestionar servicios/equipos de refrigeración?
4. ¿Podrías contarme una situación en la que un problema con equipos o mantenimiento haya afectado a tus clientes?


---
#### 2.2.2. Registro de entrevistas

##### Segmento objetivo #1: Negocios que utilizan sistemas de refrigeración


---
#### Entrevista 1:

- **Nombres y apellidos:** Javier Martínez
- **Edad:** 50
- **Distrito:** San Martín de Porres


- ![Entrevista 1](images/entrevista%201.PNG)


- **Inicio:** 0:02
- **Duración:** 3:00 min
- **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202313419_upc_edu_pe/EbAKUznIOb1Hj52G0gDEO4cB5aB_zzFbWqKma_ojJr-KDw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=0bIob4
- **Resumen:** Nuestro primer entrevistador nos explica que es nuevo con respecto a las máquinas de refrigeración y que su mayor preocupación es la dificultad del hardware, explica que quiere UI más intuitivas..

---
#### Entrevista 2:
- **Nombres y apellidos:** Jesús Cortez Soria
- **Edad:** 25
- **Distrito:** San Martín de Porres

![Entrevista 2](images/entrevista%202.PNG)
- **Inicio:** 0:02
- **Duración:** 1:50 min
- **URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202313419_upc_edu_pe/EQl3y6bGWi9ArBB2C0V_6-ABZiouXaloDBWMnfE-n-0CRA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SQ7nw4
- **Resumen:** Nuestro segundo entrevistador menciona que lo más importante es el soporte y la atención que brindan las empresas, menciona también el uso de tablets para un mejor monitoreo y la confianza con los trabajadores.


##### Segmento objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración

---
#### Entrevista 1:

- **Nombres y apellidos:** Adrian Barzola
- **Edad:** 25
- **Distrito:** Los Olivos


![Entrevista 3](images/entrevista%203.PNG)


- **Inicio:** 0:02
- **Duración:** 2:24 min
- **URL:** https://upcedupe-my.sharepoint.com/personal/u202313419_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202313419%5Fupc%5Fedu%5Fpe%2FDocuments%2Fentrevista%203%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E684695f3%2Da04a%2D4389%2D98b5%2Dd95b0223728e
- **Resumen:** Nuestro tercer entrevistador menciona que es importante una relación de calidad-precio y una empresa destacaría más aprovechando las redes sociales
---


#### 2.2.3. Análisis de entrevistas
Basándonos en las entrevistas, hemos llevado a cabo un análisis en el que destacamos los puntos compartidos y tendencias comunes entre los usuarios.

**Hallazgos:**
- La mayoría de los entrevistados percibe que los sistemas de refrigeración actuales son complejos, sobre todo para nuevos usuarios.
- Se valora altamente la facilidad de uso y las interfaces intuitivas, que reduzcan la curva de aprendizaje y aumenten la eficiencia.
- El soporte técnico y la atención al cliente son factores decisivos para elegir proveedor; la confianza en la empresa es clave para la adopción de la tecnología.
- Preferencia por dispositivos móviles y tablets para monitorear y controlar los equipos; buscan experiencias ágiles, modernas y accesibles desde cualquier lugar.
- Algunos entrevistados señalaron que los costos iniciales pueden ser un obstáculo, pero estarían dispuestos a pagar más por una solución que ahorre tiempo y reduzca fallos.
- Se identificó que los negocios pequeños tienen mayores dificultades para capacitar a su personal y valoran capacitación rápida y soporte remoto.
- La gran mayoría manifestó interés en que las plataformas ofrezcan tutoriales o guías interactivas para facilitar el aprendizaje.

### 2.3. Needfinding.
#### 2.3.1. User personas

Para la construcción de las User Personas se analizaron los segmentos definidos previamente (negocios que dependen de la cadena de frío y proveedores/técnicos de refrigeración). Estos arquetipos representan de manera ficticia, pero fundamentada en los hallazgos, a usuarios clave de PolarNet.

**Segmento Objetivo #1: Negocios que utilizan equipos de refrigeración**

![User Persona – Administrador de Restaurant](./images/Carlos%20Ramírez.png)

**Segmento Objetivo #2: Empresas proveedoras de servicios y equipos de refrigeración**

![User Persona – Técnico de Refrigeración](./images/Jorge%20Martínez.png)

#### 2.3.2. User Task Matrix

Se identificaron las principales tareas que los segmentos objetivo realizan actualmente para cumplir con sus responsabilidades. A continuación, se presenta el User Task Matrix que relaciona a cada User Persona con las tareas detectadas, considerando frecuencia e importancia.

**Segmento 1: Negocios que utilizan equipos de refrigeración (representado por Carlos Ramírez).**

**Segmento 2: Empresas proveedoras de servicios y equipos de refrigeración (representado por Jorge Martínez).**

  

<table class="utm-table" role="table" aria-label="User Task Matrix for PolarNet">
    <thead>
      <tr>
        <th>Tarea / Task</th>
        <th colspan="2">Carlos Ramírez</th>
        <th colspan="2">Jorge Martínez</th>
      </tr>
      <tr>
        <th></th>
        <th>Frecuencia</th>
        <th>Importancia</th>
        <th>Frecuencia</th>
        <th>Importancia</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align:left;">Monitorear temperatura equipos</td>
        <td class="level-high">Alta</td>
        <td class="level-high">Alta</td>
        <td class="level-medium">Media</td>
        <td class="level-high">Alta</td>
      </tr>
      <tr>
        <td style="text-align:left;">Recibir alertas de fallos</td>
        <td class="level-high">Alta</td>
        <td class="level-very-high">Muy Alta</td>
        <td class="level-high">Alta</td>
        <td class="level-high">Alta</td>
      </tr>
      <tr>
        <td style="text-align:left;">Programar mantenimientos</td>
        <td class="level-medium">Media</td>
        <td class="level-high">Alta</td>
        <td class="level-high">Alta</td>
        <td class="level-very-high">Muy Alta</td>
      </tr>
      <tr>
        <td style="text-align:left;">Generar reportes de rendimiento</td>
        <td class="level-medium">Media</td>
        <td class="level-high">Alta</td>
        <td class="level-low">Baja</td>
        <td class="level-medium">Media</td>
      </tr>
      <tr>
        <td style="text-align:left;">Contactar técnicos/proveedores</td>
        <td class="level-high">Alta</td>
        <td class="level-very-high">Muy Alta</td>
        <td class="level-medium">Media</td>
        <td class="level-medium">Media</td>
      </tr>
      <tr>
        <td style="text-align:left;">Acceder a historial de fallos</td>
        <td class="level-medium">Media</td>
        <td class="level-high">Alta</td>
        <td class="level-high">Alta</td>
        <td class="level-very-high">Muy Alta</td>
      </tr>
    </tbody>
</table>

### 2.3.3. User Journey Mapping

**Segmento objetivo #1: Negocios que utilizan equipos de refrigeración**

Este User Journey Map representa el recorrido actual de Carlos Ramírez. El mapa ilustra su experiencia completa desde que maneja continuamente los datos registrados de su restaurante hasta el seguimiento posterior a la ejecución de los mantenimientos o reparaciones. Esta sección refleja la situación actual sin intervención de soluciones tecnológicas, mostrando los puntos de contacto, tareas clave, emociones y posibles fricciones que enfrenta en su día a día. Este recorrido permite entender los desafíos que enfrenta Carlos, incluyendo la falta de historial confiable, la dependencia de técnicos disponibles a última hora y la dificultad de consolidar información para tomar decisiones rápidas.

![User Journey Mapping – Administrador de restaurant](./images/Customer%20journey%20map%201.png)

**Segmento objetivo #2: Técnicos y empresas proveedoras de servicios de refrigeración**

Este User Journey Map representa el recorrido actual de Jorge Martínez. El mapa ilustra su experiencia completa desde que gestiona continuamente las solicitudes y mantenimientos de sus clientes hasta el seguimiento posterior a la realización de los servicios. Esta sección refleja la situación actual sin intervención de soluciones tecnológicas, mostrando los puntos de contacto, tareas clave, emociones y posibles fricciones que enfrenta en su día a día. Este recorrido permite entender los desafíos que enfrenta Jorge, incluyendo la sobrecarga de trabajo por urgencias imprevistas, la falta de historial técnico centralizado y la dificultad para planificar rutas y visitas de manera eficiente.

![User Journey Mapping – Técnico](./images/Customer%20journey%20map%202.png)

### 2.3.4. Empathy Mapping

Se elaboraron mapas de empatía para cada User Persona utilizando la herramienta indicada. A continuación, se resumen los principales hallazgos:

**Segmento 1: Negocios que utilizan equipos de refrigeración (representado por Carlos Ramírez).**

![Empathy Mapping – Administrador de restaurant](./images/Empathy%20map%20Carlos%20Ramírez.png)

**Segmento 2:Empresas proveedoras de servicios y equipos de refrigeración (representado por Jorge Martínez).**

![Empathy Mapping – Administrador de restaurant](./images/Empathy%20map%20Jorge%20Martínez.png)



  




















##2.6.1. Bounded Context:Authentification Bounded Context
###2.6.1.1.Domain Layer
###2.6.1.2. Interface Layer
###2.6.1.3. Application Layer
###2.6.1.4  Infrastructure Layer
###2.6.1.5. Bounded Context Software Architecture Component Level Diagrams 
###2.6.1.6. Bounded Context Software Architecture Code Level Diagrams   
####2.6.1.6.1. Bounded Context Domain Layer Class Diagrams 
####2.6.1.6.2. Bounded Context Database Design Diagram 

##2.6.2. Bounded Context:Service request Bounded Context
###2.6.2.1.Domain Layer
###2.6.2.2. Interface Layer
###2.6.2.3. Application Layer
###2.6.2.4  Infrastructure Layer
###2.6.2.5. Bounded Context Software Architecture Component Level Diagrams 
###2.6.2.6. Bounded Context Software Architecture Code Level Diagrams   
####2.6.2.6.1. Bounded Context Domain Layer Class Diagrams 
####2.6.2.6.2. Bounded Context Database Design Diagram 

##2.6.3. Bounded Context:Equipment monitoringBounded Context
###2.6.3.1.Domain Layer
###2.6.3.2. Interface Layer
###2.6.3.3. Application Layer
###2.6.3.4  Infrastructure Layer
###2.6.3.5. Bounded Context Software Architecture Component Level Diagrams 
###2.6.3.6. Bounded Context Software Architecture Code Level Diagrams   
####2.6.3.6.1. Bounded Context Domain Layer Class Diagrams 
####2.6.3.6.2. Bounded Context Database Design Diagram 

##2.6.4. Bounded Context:Notification Bounded Context
###2.6.4.1.Domain Layer
###2.6.4.2. Interface Layer
###2.6.4.3. Application Layer
###2.6.4.4  Infrastructure Layer
###2.6.4.5. Bounded Context Software Architecture Component Level Diagrams 
###2.6.4.6. Bounded Context Software Architecture Code Level Diagrams   
####2.6.4.6.1. Bounded Context Domain Layer Class Diagrams 
####2.6.4.6.2. Bounded Context Database Design Diagram 
