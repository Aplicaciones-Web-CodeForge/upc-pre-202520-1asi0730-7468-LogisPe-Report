<div align="center">

![Logo UPC](https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png)

**Universidad Peruana de Ciencias Aplicadas**

**Carrera**: Ingeniería de Software  
**Ciclo**: 2025-02  
**Curso**: 1ASI0730 - Aplicaciones Web  
**NRC**: 7468  
**Profesor**: Angel Augusto Velasquez Nuñez  

<br>

# **Informe de Trabajo Final**

**Startup**: CodeForce  
**Producto**: LogisPE  

<br>

## **Integrantes**

Aguilar Untiveros, Rodrigo Fabrizio – u202318309  
Condori Lozano, Alessandro Ramiro – u20211a118  
Murillo, Mathias Javier – u202022211  
Mejia Aliaga, Katherine Maryory – u20221a118  
Montes Maza, Augusto Sebastian – u202218645  

<br><br>

**Agosto del 2025**

</div>

---


# Registro de Versiones del Informe

<table>
<colgroup>
<col style="width: 10%" />
<col style="width: 15%" />
<col style="width: 16%" />
<col style="width: 57%" />
</colgroup>
<thead>
<tr class="header">
<th>Versión</th>
<th>Fecha</th>
<th>Autor</th>
<th>Descripción de modificación</th>
</tr>
<tr class="odd">
<th>TB1</th>
<th>21/09/2025</th>
<th><p>Aguilar Untiveros, Rodrigo Fabrizio</p>
<p>Condori Lozano, Alessandro Ramiro</p>
<p>Murillo, Mathias Javier</p>
<p>Mejia Aliaga, Katherine Maryory</p>
<p>Montes Maza, Augusto Sebastian</p></th>
<th><p>Se realizaron los Capítulos I: Introducción, Capítulo II:
Requirements Elicitation &amp; Analysis, Capítulo</p>
<p>III: Requirements Specification y Capítulo IV: Product
Design</p></th>
</tr>
<tr class="header">
<th>TP</th>
<th>10/10/2025</th>
<th><p>Aguilar Untiveros, Rodrigo Fabrizio</p>
<p>Condori Lozano, Alessandro Ramiro</p>
<p>Murillo, Mathias Javier</p>
<p>Mejia Aliaga, Katherine Maryory</p>
<p>Montes Maza, Augusto Sebastian</p></th>
<th><p>Se realizaron los puntos del Capítulo V: Sprint 2, Sprint
Planning 2, Sprint Backlog 2, Development</p>
<p>Evidence for Sprint Review, Testing Suite Evidence for Sprint Review,
Execution Evidence for Sprint</p>
<p>Review, Services Documentation Evidence for Sprint Review, Software
Deployment Evidence for</p>
<p>Sprint Review y Team Collaboration Insights during Sprint</p></th>
</tr>
<tr class="odd">
<th>TB2</th>
<th>16/11/2025</th>
<th><p>Aguilar Untiveros, Rodrigo Fabrizio</p>
<p>Condori Lozano, Alessandro Ramiro</p>
<p>Murillo, Mathias Javier</p>
<p>Mejia Aliaga, Katherine Maryory</p>
<p>Montes Maza, Augusto Sebastian</p></th>
<th>Se realizaron los puntos del Capítulo V: Sprint 3, Sprint Planning
3, Sprint Backlog 3, Development Evidence for Sprint Review, Testing
Suite Evidence for Sprint Review, Execution Evidence for Sprint Review,
Services Documentation Evidence for Sprint Review, Software Deployment
Evidence for Sprint Review, Team Collaboration Insights during Sprint,
Diseño de Entrevistas, Registro de Entrevistas, Evaluaciones según
heurísticas, Video About-the-Product, Video About-the-Team</th>
</tr>
</thead>
<tbody>
</tbody>
</table>
---

# Project Report Collaboration Insights

A continuación, se detalla el proceso de colaboración y gestión de versiones que el equipo ha seguido para la elaboración de este informe y los productos asociados. Todas las contribuciones están centralizadas y son rastreables a través de nuestro repositorio en GitHub.

- **URL del Repositorio del Informe:** https://github.com/Aplicaciones-Web-CodeForge/Report
- **URL del Frontend desplegado:** https://upc-pre-202520-1asi0729-7468-logis.vercel.app/home
- **URL del Backend desplegado:** https://upc-pre-202520-1asi0729-7468-logispe.onrender.com/docs/#/

---

### **Entrega N°1: TB1**

Para la primera entrega, el equipo se centró en establecer las bases del proyecto, desde la investigación inicial hasta el diseño conceptual y el despliegue de la primera versión de la Landing Page.

**Proceso de Colaboración:**

La elaboración del informe y los artefactos se gestionó siguiendo un flujo de trabajo estructurado para garantizar la calidad y la coherencia:

1.  **Planificación y Asignación:** Las tareas, como la redacción de capítulos específicos del informe o la creación de artefactos de UX, se definieron y asignaron a través de nuestro tablero de Trello. Cada miembro del equipo fue responsable de liderar y/o colaborar en diferentes secciones.

2.  **Desarrollo en Ramas (`feature branches`):** Siguiendo el flujo de trabajo **GitFlow**, cada contribución significativa se desarrolló en su propia rama. Por ejemplo, `feature/chapter-2-interviews` o `feature/landing-page-ui`. Esto permitió trabajar en paralelo sin afectar la rama principal de desarrollo.

3.  **Revisión y Fusión (`Pull Requests`):** Una vez completada una tarea, el responsable abría un *Pull Request* (PR) en GitHub. Al menos un miembro del equipo era asignado como revisor para proporcionar feedback, sugerir mejoras y asegurar que los cambios cumplieran con las convenciones del proyecto antes de ser fusionados a la rama `develop`.

4.  **Commits Convencionales:** Todos los commits siguieron la especificación de **Conventional Commits** (ej. `docs(report): add user personas section`). Esto nos permitió mantener un historial de cambios limpio, legible y fácil de auditar.


---

### **Entrega N°2: TP1**

Para la segunda entrega, el foco principal fue la materialización de los diseños en la aplicación web, la definición de la arquitectura de software y la incorporación de las mejoras identificadas a partir del feedback recibido.

**Proceso de Colaboración:**

El proceso colaborativo evolucionó para abordar la mayor complejidad técnica de esta fase:

1.  **Gestión del Feedback:** Las observaciones y el feedback del docente sobre la entrega TB1 se registraron como *Issues* en nuestro repositorio de GitHub. Cada *Issue* fue asignado a un responsable, discutido por el equipo y vinculado a los *Pull Requests* que implementaban la solución, asegurando una trazabilidad completa de las mejoras.

2.  **Desarrollo de la Aplicación Web:** La implementación de las pantallas de la aplicación web se dividió por módulos (ej. `feature/stock-management-ui`, `feature/recipes-module`). Los desarrolladores de frontend trabajaron en estas ramas, consumiendo datos simulados mientras se definía la arquitectura del backend.

3.  **Diseño de Arquitectura:** La creación de los diagramas de arquitectura (C4 Model) y el diseño de la base de datos se realizaron de forma colaborativa utilizando herramientas en la nube. Las propuestas se compartieron y discutieron en reuniones de equipo, y los diagramas finales se versionaron y documentaron en el informe.

4.  **Revisión de Código y Coherencia Visual:** Los *Pull Requests* para la aplicación web fueron revisados no solo por su funcionalidad, sino también para garantizar que se adhirieran a los **Style Guidelines** definidos en el Capítulo IV. Esto aseguró una experiencia de usuario consistente en toda la aplicación.


---
### **Entrega N°3: TB2**

Para la tercera entrega, el foco principal fue el desarrollo del backend avanzado, la implementación de la arquitectura basada en Domain-Driven Design (DDD) y la integración técnica con la aplicación web desarrollada en el TP1.

**Proceso de Colaboración:**

El proceso colaborativo evolucionó nuevamente para enfrentar la mayor complejidad técnica de esta etapa, que implicó decisiones de arquitectura, definición de bounded contexts y construcción de una API escalable y mantenible.

1. **Definición de los Bounded Contexts (DDD):**  
   El equipo definió de manera colaborativa la separación del dominio en siete *bounded contexts*, acordando los límites funcionales y las reglas de negocio de cada módulo. Este análisis se realizó mediante reuniones técnicas, pizarras colaborativas y revisión grupal de los modelos conceptuales.

2. **Arquitectura del Backend y Estructura del Proyecto:**  
   Se construyó la estructura base del backend siguiendo principios de arquitectura limpia: capas de *controllers*, *services*, *repositories* y *domain models*.  
   El equipo discutió y acordó el uso de patrones como **DTOs**, **Value Objects**, **Aggregates**, así como las convenciones de nombrado y organización para garantizar consistencia en los siete bounded contexts.

3. **Implementación de Endpoints y Casos de Uso:**  
   Cada integrante asumió módulos específicos del backend, desarrollando controladores y casos de uso independientes, pero bajo las reglas globales del dominio.  
   Las funciones principales (creación, consulta, actualización y validación) se implementaron siguiendo lineamientos comunes y asegurando que cada servicio respetara su bounded context.

4. **Diseño e Integración de la Base de Datos:**  
   El equipo trabajó en conjunto para finalizar el modelo relacional, asegurando que las entidades reflejaran fielmente el dominio definido en DDD. Se documentaron relaciones, claves primarias, restricciones y normalización.  
   Además, se integró la base de datos con el backend mediante repositorios con consultas optimizadas y manejo adecuado de transacciones.

5. **Revisión de Código y Estándares Técnicos:**  
   Los *Pull Requests* se revisaron no solo por su funcionalidad, sino también para verificar el cumplimiento de estándares definidos en TB2: manejo de excepciones, validaciones, nomenclatura, estructura del proyecto y documentación técnica.  
   Cada revisión quedó registrada en GitHub con comentarios detallados que permitieron mantener la calidad y la cohesión arquitectónica.

6. **Integración con el Frontend:**  
   A medida que los módulos del backend estaban listos, se realizaron pruebas de consumo desde el frontend del TP1 utilizando herramientas como Postman y fetch/axios.  
   Se validó la coherencia entre contratos API, tipos de datos, rutas y respuestas, asegurando que el frontend pudiera integrarse sin fricciones con la API.

7. **Documentación Técnica del Backend:**  
   Finalmente, el equipo elaboró documentación detallada de la arquitectura, los endpoints, la estructura interna de módulos, casos de uso, reglas de negocio y modelos de datos. Esta documentación se añadió al informe y al repositorio, garantizando trazabilidad y claridad para futuras iteraciones.

---

# Contenido

## Tabla de contenidos

### [Capítulo I: Introducción](#capítulo-i-introducción)

- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2 Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#211-análisis-competitivo)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
- [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
- [2.5. Ubiquitous Language](#25-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

- [3.1. User Stories](#31-user-stories)
- [3.2. Impact Mapping](#32-impact-mapping)
- [3.3. Product Backlog](#33-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design)

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

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Sprint Backlog 1](#5212-aspect-leaders-and-collaborators)
    - [5.2.1.3. Development Evidence for Sprint Review](#5213-sprint-backlog-1)
    - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
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
- [5.3. Validation Interviews](#53-validation-interviews)
  - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
  - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)

### [Conclusiones](#conclusiones)

#### [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

#### [Video About-the-Team](#video-about-the-team)

### [Biblioteca](#biblioteca)

### [Anexos](#anexos)

---

# Student Outcome

Objetivo general, ABET – EAC - Student Outcome 5: Capacidad de comunicarse efectivamente con un rango de audiencias.

# Outcomes TB1 & TP1 – Pilares del Producto y Landing Page  

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
|---|---|---|
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **Rodrigo Fabrizio Aguilar Untiveros**<br>**TB1**: Argumenté y defendí propuestas sobre la estructura de la landing page durante las reuniones de equipo (audiencia técnica). Moderé discusiones para sintetizar las ideas de todos en pilares de producto claros, facilitando un consenso sobre el mensaje a comunicar a nuestros futuros usuarios (audiencia externa).<br>**TP1**: Lideré la presentación del Product Backlog al equipo, explicando oralmente la priorización de User Stories y justificando su valor de negocio. Comuniqué las decisiones de diseño de la arquitectura de software (C4 Model) en términos claros, asegurando que todos los miembros, independientemente de su rol, comprendieran la estructura y el flujo de datos de la solución.<br>**TB2**: Guié las reuniones técnicas de arquitectura del backend, explicando la estructura DDD, los bounded contexts y cómo se integrarían los módulos entre sí. Presenté oralmente la propuesta del backend avanzado, facilitando que todos los integrantes entendieran la interacción entre controladores, servicios, repositorios y la base de datos.<br><br>**Alessandro Ramiro Condori Lozano**<br>**TB1**: Traduje los objetivos técnicos del proyecto a un lenguaje centrado en beneficios para el usuario durante nuestras sesiones de brainstorming. Esta explicación ayudó a que el equipo, como audiencia interna, pudiera visualizar y acordar el discurso comercial que se implementaría en la landing page.<br>**TP1**: Expuse los User Journey Maps al equipo, narrando la experiencia del usuario paso a paso para ilustrar los puntos de dolor y las oportunidades. Esta presentación oral fue clave para que el equipo empatizara con el usuario final y validara los flujos de la aplicación web.<br>**TB2**: Expliqué verbalmente los flujos de comunicación de los endpoints del backend, detallando cómo las peticiones viajan desde el controlador hasta el repositorio. Presenté al equipo las validaciones y reglas de negocio para garantizar una comprensión clara de la lógica implementada.<br><br>**Mathias Javier Murillo**<br>**TB1**: Propuse y justifiqué verbalmente la adaptación del tono de comunicación para dos segmentos de audiencia distintos en la landing page. Expliqué al equipo cómo un mismo pilar del producto debía presentarse de forma diferente para un usuario técnico versus un usuario de negocio, logrando alinear la estrategia de contenido.<br>**TP1**: Presenté los Mockups y prototipos de la aplicación web, guiando al equipo a través de la interfaz y explicando las decisiones de diseño UX/UI. Adapté mi discurso para una audiencia de desarrolladores, enfocándome en la funcionalidad y componentes, y luego para una audiencia de "negocio", resaltando la facilidad de uso y los beneficios.<br>**TB2**: Expliqué oralmente los modelos de dominio del backend, detallando entidades, agregados, value objects y su transformación en tablas. Clarifiqué al equipo cómo se estructurarían los módulos internos y cómo se validarían los datos en cada fase del backend.<br><br>**Katherine Maryory Mejia Aliaga**<br>**TB1**: Expuse verbalmente propuestas para la arquitectura de la información y la jerarquía visual de la landing page. Mi rol fue transformar los conceptos abstractos del equipo en una narrativa oral clara que describía el "viaje" del usuario, permitiendo que todos entendieran cómo se comunicarían visualmente las ideas.<br>**TP1**: Expliqué al equipo los Style Guidelines definidos para el proyecto, comunicando de forma oral las reglas sobre tipografía, colores y espaciado. Mi presentación aseguró que todos tuvieran una comprensión compartida de la identidad visual que se implementaría en la aplicación web.<br>**TB2**: Expliqué de forma oral la estructura de validaciones del backend, el manejo de excepciones y cómo se garantizaría la integridad de los datos. Facilitó la alineación entre frontend y backend comunicando cómo se consumirían los servicios API.<br><br>**Augusto Sebastian Montes Maza**<br>**TB1**: Participé activamente en los debates de planificación, enfocándome en asegurar la coherencia verbal entre los objetivos de negocio y las funcionalidades propuestas. Cuestioné y validé oralmente que nuestro discurso interno fuera lo suficientemente robusto como para sostener el mensaje público en la landing page.<br>**TP1**: Argumenté las decisiones sobre el diseño de la base de datos durante las sesiones técnicas. Simplifiqué conceptos complejos de modelado de datos para que todo el equipo pudiera participar en la validación, asegurando que el diseño fuera escalable y respondiera a las necesidades funcionales.<br>**TB2**: Expliqué oralmente la estructura completa de la base de datos del backend, detallando relaciones, normalización y reglas de integridad. Presenté al equipo cómo se integraría la base de datos con los bounded contexts y cómo cada módulo consumiría los datos. | **Rodrigo Fabrizio Aguilar Untiveros**<br>**TB1**: La habilidad para mediar y sintetizar diferentes puntos de vista oralmente fue crucial para unificar la visión del equipo y asegurar que el mensaje final del producto fuera coherente y potente para nuestra audiencia objetivo.<br>**TP1**: Comunicar oralmente la arquitectura y el backlog demostró que traducir decisiones técnicas complejas a un lenguaje accesible para todo el equipo es fundamental para mantener la alineación y el enfoque durante el desarrollo.<br>**TB2**: Explicar el diseño del backend reforzó la importancia de comunicar arquitecturas complejas de manera simple para evitar malinterpretaciones y asegurar cohesión técnica en el equipo.<br><br>**Alessandro Ramiro Condori Lozano**<br>**TB1**: La traducción de conceptos técnicos a un discurso oral centrado en el usuario demostró ser fundamental para alinear al equipo, permitiendo que la comunicación del producto fuera más empática y efectiva en la landing page.<br>**TP1**: Narrar la experiencia del usuario a través de los Journey Maps consolidó mi entendimiento de que la comunicación oral efectiva es una herramienta poderosa para generar empatía y guiar el diseño de productos centrado en las personas.<br>**TB2**: Explicar los flujos del backend me permitió entender que la claridad técnica en la comunicación oral es clave para asegurar integraciones correctas y evitar retrasos en el desarrollo.<br><br>**Mathias Javier Murillo**<br>**TB1**: La comunicación oral adaptativa fue clave para definir una estrategia de contenido inclusiva, reconociendo que un mensaje efectivo no es universal, sino que debe ajustarse a las necesidades y perspectivas de cada audiencia.<br>**TP1**: Presentar los mismos prototipos a diferentes audiencias me enseñó a modular mi comunicación oral, concluyendo que la efectividad radica en resaltar los aspectos más relevantes para cada grupo, ya sea técnico o estratégico.<br>**TB2**: Explicar verbalmente los modelos y estructuras del backend me enseñó que comunicar conceptos técnicos con claridad evita errores en la implementación y mejora la colaboración entre áreas.<br><br>**Katherine Maryory Mejia Aliaga**<br>**TB1**: La comunicación oral de una estrategia visual fue un puente esencial entre la idea y la ejecución, demostrando que la capacidad de "narrar" una interfaz es vital para que un equipo técnico y creativo trabaje hacia un mismo objetivo comunicacional.<br>**TP1**: La exposición oral de guías de estilo confirmó que establecer y comunicar reglas de diseño de manera clara previene inconsistencias y agiliza el trabajo de desarrollo, asegurando la cohesión visual del producto final.<br>**TB2**: La comunicación oral sobre validaciones, excepciones y reglas de negocio del backend confirmó que explicar estos elementos en detalle permite una implementación más sólida y consistente.<br><br>**Augusto Sebastian Montes Maza**<br>**TB1**: Mantener la coherencia en la comunicación oral interna previno desviaciones conceptuales, concluyendo que un discurso de equipo sólido y bien alineado es la base para una comunicación externa clara y confiable.<br>**TP1**: La capacidad de simplificar y argumentar decisiones técnicas oralmente no solo valida el diseño, sino que también empodera a todo el equipo, permitiendo una toma de decisiones más informada y colaborativa.<br>**TB2**: Comunicar oralmente la estructura de la base de datos y la interacción entre los módulos del backend demostró que la claridad técnica es esencial para garantizar un desarrollo sin ambigüedades. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Rodrigo Fabrizio Aguilar Untiveros**<br>**TB1**: Redacté la versión inicial de la propuesta de valor y los textos para la sección principal (Hero) de la landing page, utilizando un lenguaje persuasivo y claro dirigido a una audiencia no técnica.<br>**TP1**: Desarrollé y documenté las User Stories principales del proyecto, redactando los Criterios de Aceptación con la estructura Gherkin (Given-When-Then). Este formato técnico y preciso fue diseñado para que el equipo de desarrollo tuviera una guía sin ambigüedades.<br>**TB2**: Documenté por escrito la arquitectura completa del backend, la estructura DDD, los bounded contexts, la definición de entidades y la descripción de endpoints, asegurando una comunicación técnica precisa para desarrollo y QA.<br><br>**Alessandro Ramiro Condori Lozano**<br>**TB1**: Contribuí en la redacción de la sección "Introducción" del informe del proyecto y adapté estos conceptos a mensajes más directos y concisos para la landing page.<br>**TP1**: Redacté el análisis competitivo en el informe del proyecto, utilizando un lenguaje formal y analítico para una audiencia académica. Además, plasmé las conclusiones de este análisis en comentarios escritos dentro de Figma para guiar las decisiones de diseño del UI.<br>**TB2**: Documenté la estructura de carpetas, el estándar de nombrado del backend y los lineamientos técnicos para mantener consistencia. Elaboré documentación escrita sobre el consumo de servicios y expectativas del contrato API.<br><br>**Mathias Javier Murillo**<br>**TB1**: Elaboré y ajusté los textos descriptivos de las características del producto, creando variantes del mensaje escrito para dos perfiles de usuario identificados.<br>**TP1**: Documenté por escrito las especificaciones de varios componentes de la aplicación web en el informe, describiendo su comportamiento y relación con otros elementos. Esta comunicación escrita fue esencial para guiar la implementación técnica posterior.<br>**TB2**: Documenté los modelos del backend, sus relaciones, reglas de negocio y transformaciones de datos, produciendo descripciones claras para asegurar correcta implementación del dominio.<br><br>**Katherine Maryory Mejia Aliaga**<br>**TB1**: Estructuré el contenido del informe en la sección de "Requisitos" para asegurar una lectura lógica y organicé la disposición de los bloques de texto en el wireframe de la landing page.<br>**TP1**: Contribuí a la redacción del capítulo de Arquitectura de la Información del informe. Documenté por escrito las decisiones sobre los sistemas de organización y etiquetado, creando una referencia formal para que el equipo consultara al construir la navegación de la aplicación.<br>**TB2**: Redacté la documentación del manejo de validaciones, excepciones y reglas de negocio aplicadas en los bounded contexts del backend. Escribí guías técnicas sobre la estructura del API y las interacciones frontend-backend.<br><br>**Augusto Sebastian Montes Maza**<br>**TB1**: Realicé la revisión y edición de los textos finales tanto de la landing page como del informe TB1, unificando el tono de voz y asegurando la correcta aplicación de la terminología del proyecto.<br>**TP1**: Fui responsable de documentar el Ubiquitous Language del proyecto en el informe, creando un glosario de términos de negocio. Esta comunicación escrita fue vital para evitar malentendidos y asegurar que todos los miembros del equipo, tanto técnicos como no técnicos, hablaran el mismo "idioma".<br>**TB2**: Documenté la estructura de la base de datos, normalización, entidades del modelo y estándares de desarrollo del backend, asegurando referencias claras para todos los integrantes del equipo. | **Rodrigo Fabrizio Aguilar Untiveros**<br>**TB1**: La redacción orientada a la audiencia me permitió comprender que la comunicación escrita efectiva no se trata solo de informar, sino de conectar y persuadir, adaptando el mensaje al contexto del lector.<br>**TP1**: Redactar Criterios de Aceptación me enseñó que la precisión en la comunicación escrita técnica es fundamental para reducir errores y retrabajo, demostrando que un lenguaje claro y estructurado es una herramienta de productividad.<br>**TB2**: Documentar el backend me enseñó que una arquitectura sólida depende de una comunicación escrita técnica clara, precisa y consistente.<br><br>**Alessandro Ramiro Condori Lozano**<br>**TB1**: La tarea de adaptar un mismo mensaje para un informe técnico y una web comercial me enseñó que la efectividad de la comunicación escrita reside en la capacidad de síntesis y en la selección precisa del lenguaje.<br>**TP1**: Documentar el análisis de competidores por escrito me demostró que la comunicación formal es clave para presentar hallazgos de manera objetiva y profesional, mientras que los comentarios escritos en herramientas de diseño son un canal ágil para la comunicación contextual.<br>**TB2**: Documentar estándares técnicos y estructura del backend me confirmó que la claridad escrita es esencial para mantener escalabilidad y coherencia en el desarrollo.<br><br>**Mathias Javier Murillo**<br>**TB1**: La redacción de contenidos para distintos perfiles de usuario reforzó mi entendimiento de que la comunicación escrita empática es clave; es necesario escribir para que cada audiencia sienta que le hablas directamente.<br>**TP1**: La documentación escrita de especificaciones funcionales me hizo concluir que un registro claro y detallado es indispensable para la escalabilidad del proyecto, sirviendo como una fuente de verdad para el equipo a lo largo del tiempo.<br>**TB2**: Documentar el modelo de dominio del backend me enseñó que escribir con precisión evita errores de interpretación y facilita una implementación más sólida.<br><br>**Katherine Maryory Mejia Aliaga**<br>**TB1**: La organización del contenido demostró que la estructura es un componente silencioso pero poderoso de la comunicación escrita. Un texto bien ordenado guía al lector y refuerza la claridad del mensaje.<br>**TP1**: Documentar por escrito la Arquitectura de la Información me permitió valorar la importancia de formalizar las decisiones de diseño, concluyendo que un documento bien estructurado sirve como pilar para construir experiencias de usuario coherentes.<br>**TB2**: Documentar reglas de negocio y validaciones del backend reforzó que la documentación técnica clara es esencial para evitar inconsistencias entre módulos.<br><br>**Augusto Sebastian Montes Maza**<br>**TB1**: El proceso de edición y unificación de textos me permitió concluir que la consistencia en la comunicación escrita es fundamental para construir una identidad de producto sólida y profesional.<br>**TP1**: Establecer un lenguaje ubicuo por escrito fue una lección clave sobre la importancia de crear una base terminológica común, concluyendo que esta práctica elimina la ambigüedad y fomenta una comunicación más eficiente y precisa en equipos multidisciplinarios.<br>**TB2**: Documentar la estructura técnica del backend me permitió comprender que una documentación clara es vital para asegurar que todo el equipo trabaje con las mismas reglas y estándares. |
---


# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1 Descripción de la Startup

En un entorno económico cada vez más competitivo, donde la eficiencia operativa se ha convertido en un factor determinante para la supervivencia y el crecimiento de las empresas, surge la necesidad de soluciones tecnológicas que optimicen procesos y reduzcan costos. Nuestra startup se presenta como respuesta a esta demanda, ofreciendo una aplicación web de gestión de inventarios específicamente diseñada para pequeñas y medianas empresas del sector gastronómico, con un enfoque inicial en restobares y restaurantes, sectores caracterizados por un alto dinamismo y un consumo intensivo de insumos perecibles.

La solución tecnológica propuesta tiene como objetivo principal facilitar el control en tiempo real del stock de productos e insumos. El sistema permitirá a los administradores y propietarios gestionar con mayor precisión las compras, identificar tendencias de consumo, minimizar pérdidas por caducidad o deterioro, y recibir alertas automáticas cuando los niveles de inventario estén próximos a agotarse. Esta capacidad de supervisión inmediata resulta crucial en un negocio donde las decisiones deben tomarse con rapidez para evitar sobrecostos o interrupciones en el servicio.

A diferencia de sistemas tradicionales o de registros manuales, nuestra plataforma ofrece accesibilidad desde cualquier dispositivo con conexión a internet, lo cual garantiza disponibilidad en todo momento y lugar. Asimismo, se integra con mecanismos de seguridad y gestión de roles que aseguran el uso confiable de la herramienta y la protección de los datos. Estas características no solo fortalecen la transparencia y la trazabilidad de la información, sino que también promueven la confianza en la toma de decisiones.

La propuesta de valor radica en la simplicidad y personalización del sistema. Mientras que soluciones corporativas suelen ser costosas y complejas de implementar, nuestra startup busca ofrecer una herramienta intuitiva, adaptable a las particularidades de cada negocio y asequible para el mercado objetivo. Con ello, no solo se pretende optimizar los procesos internos, sino también contribuir a la sostenibilidad y crecimiento de los negocios gastronómicos, donde los márgenes de rentabilidad suelen ser reducidos.

**Misión**: Brindar a pequeñas y medianas empresas un sistema de gestión de inventario eficiente, accesible y seguro que optimice el control de productos, insumos y proveedores, facilitando la toma de decisiones en tiempo real.

**Visión**: Convertirse en la aplicación de referencia para la gestión de inventarios en el sector gastronómico y de servicios, reconocida por su confiabilidad, usabilidad y capacidad de adaptación a las necesidades del cliente.

### 1.1.2 Perfiles de integrantes del equipo

| Integrantes | Descripción | Conocimientos |
| :---------- | :---------- | :------------ |
| <div style="display: flex; align-items: center;">![Integrante1](https://github.com/AplicacionesOpenSource-Grupo1/upc-pre-202520--1asi0729-7369-MatchPoint-report/blob/3e152bc721b8f4af5ed4a09ce9a896e9f78f8340/images/MathiasJM.jpg)&nbsp;&nbsp;<br>**Mathias Javier Murillo**</div> | Estudiante de Ingeniería de Software. Apasionado por las nuevas tecnologías y realizar nuevos proyectos | Conocimientos en SQL, HTML, JS, CSS y Python |
| <div style="display: flex; align-items: center;">![Integrante2](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/42133cd9906da8423954d70d98db4aaa98811d5c/img/AlessandroCondori.jpg)&nbsp;&nbsp;<br>**Alessandro Condori**</div> | Soy estudiante de la carrera de Ingeniería de Software, puedo aportar mucho al equipo, aplicando mis conocimientos en diversos lenguajes de programación | Java, C++, Python, html, css, javascrip, C# y SQL |
| <div style="display: flex; align-items: center;">![Integrante3](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/42133cd9906da8423954d70d98db4aaa98811d5c/img/AugustoMontes.png)&nbsp;&nbsp;<br>**Augusto Montes**</div> | Estudiante de la carrera de Ingeniería de Software. Programador amateur, interesado en la creación de aplicaciones, ciberseguridad y videojuegos| C++, C#, SQL, Html, css, javascript, python y java |
| <div style="display: flex; align-items: center;">![Integrante4](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/42133cd9906da8423954d70d98db4aaa98811d5c/img/KatherineAguilar.jpg)&nbsp;&nbsp;<br>**Katherine Mejia**</div> | Estudiante de 5to ciclo de la carrera de ingeniería de software. Tengo experiencia creando aplicaciones front end que consuman una API y hagan peticiones. | C++, C#, SQL, Html, css, javascript, python y java |
| <div style="display: flex; align-items: center;">![Integrante5](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/42133cd9906da8423954d70d98db4aaa98811d5c/img/RodrigoAguilar.jpg)&nbsp;&nbsp;<br>**Rodrigo Aguilar**</div> | Estudiante de Ingeniería de Software cursando el 6 ciclo de la carrera de ingeniería de software.  | Tengo experiencia con Javascript, Java, C++. |


## 1.2 Solution Profile

La presente sección, Solution Profile, tiene como finalidad exponer un marco integral que permita comprender la naturaleza del problema identificado, sus impactos en el sector gastronómico y la propuesta de solución que nuestra startup ofrece. A través de un análisis estructurado, basado en la técnica de los 5W’s & 2H’s, se abordarán los antecedentes y la problemática central que enfrentan restaurantes y restobares en la gestión de inventarios.

El análisis se fundamenta en evidencias empíricas y académicas que confirman que la carencia de herramientas de control adecuadas puede representar pérdidas significativas, no solo en términos financieros, sino también en la experiencia del cliente, en la sostenibilidad del negocio y en la capacidad de crecimiento.

Al situar el problema en un contexto más amplio, se busca justificar la pertinencia de la solución propuesta y establecer las bases para la implementación de un sistema que no solo atienda a necesidades inmediatas, sino que también se proyecte como una herramienta estratégica de largo plazo.

### 1.2.1 Antecedentes y problemática

Para comprender en profundidad los desafíos que enfrenta el sector gastronómico en relación con el control de inventarios, se aplicó la técnica 5W’s & 2H’s, la cual permite organizar el análisis de manera sistemática:

**What**:

Restaurantes y restobares experimentan pérdidas económicas recurrentes debido a la ausencia de un control eficiente en el uso de insumos y gestión de inventarios. Estas pérdidas suelen manifestarse en forma de desperdicios, caducidad de productos, compras excesivas o faltantes que interrumpen la operación.

**When**:

Esta problemática se observa actualmente con mayor frecuencia, dado que el mercado gastronómico exige altos niveles de eficiencia para responder a un entorno competitivo en el cual los consumidores demandan calidad, precios justos y continuidad en el servicio.

**Where**:

El problema es común en múltiples geografías, pero cobra especial relevancia en el Perú, país reconocido por su diversidad gastronómica y la proliferación de negocios dedicados a la restauración. Dentro de este marco, se enfatiza el caso del restobar Bolivarcito, ubicado en Lima, como ejemplo representativo.

**Who**:

Los principales afectados son los propietarios, administradores y trabajadores de restaurantes, quienes dependen de información precisa para tomar decisiones relacionadas con compras, ventas, producción y control de stock.

**Why**:

El uso de métodos manuales o herramientas no especializadas genera errores frecuentes, tales como duplicación de registros, pérdida de datos o retrasos en la disponibilidad de información, lo que repercute negativamente en la productividad.

**How**:

La solución radica en implementar un sistema web centralizado que permita gestionar inventarios en tiempo real, integrar a proveedores y recetas, y emitir alertas automáticas para anticiparse a faltantes o excesos.

**How much**:

Los costos de un sistema ineficiente son altos. Estudios en el sector señalan que las pérdidas por mala gestión de inventario pueden alcanzar entre el 10 % y 15 % de los ingresos, lo que impacta directamente en la rentabilidad (Universidad Le Cordon Bleu, 2022).

_Estadística de la problemática_

. En Perú, según la Universidad Le Cordon Bleu, los llamados “costos ocultos” como mermas no contabilizadas, obsolescencia, errores en almacenamiento o traslado pueden equivaler al 10 % o 15 % de pérdida en restaurantes, afectando significativamente la productividad y rentabilidad (Diario la Republica, 2022).

. Un estudio en empresas restauranteras públicas en EE.UU. entre 1999 y 2015 concluye que una alta rotación de inventario se asocia positivamente con la rentabilidad. Esto muestra la relevancia de un control eficiente, sobre todo cuando los costos de insumos representan más de un tercio de los ingresos totales (Sage Journals, 2020).

### 1.2.2 Lean UX Process

El proceso Lean UX constituye un enfoque esencial para startups tecnológicas, ya que busca validar hipótesis de negocio de manera ágil, reduciendo riesgos y maximizando el aprendizaje temprano con clientes reales. A diferencia de los modelos tradicionales de desarrollo, que suelen invertir grandes cantidades de tiempo y recursos antes de probar la utilidad del producto, Lean UX prioriza la experimentación, la retroalimentación continua y la iteración rápida. En el contexto de nuestra propuesta de valor, este proceso permitirá comprender mejor las necesidades de los negocios gastronómicos y diseñar una solución ajustada a sus expectativas reales, garantizando un producto con mayor aceptación en el mercado.

#### 1.2.2.1. Lean UX Problem Statements

Los Problem Statements se formulan para definir con claridad los principales retos que enfrentan nuestros usuarios. Estos no son simples enunciados, sino representaciones estratégicas de las brechas actuales en la gestión de inventarios. La ausencia de visibilidad en tiempo real del stock genera escenarios críticos: desde pérdidas económicas por insumos caducados hasta sobrecompras que inmovilizan capital. Esto limita la capacidad de reacción de los negocios frente a la demanda y debilita su competitividad.

Del mismo modo, la gestión manual de insumos y recetas se traduce en procesos lentos, repetitivos y propensos a errores humanos. Estos fallos repercuten directamente en la experiencia del cliente final, ya que los restobares o cafés pueden ofrecer un servicio inconsistente o incluso enfrentar quiebres de stock en momentos de alta demanda. En este contexto, resulta evidente que el problema no solo afecta a la rentabilidad, sino también a la reputación del negocio.

**Problem Statement 1:**

Los propietarios y administradores de restaurantes, cafés y restobares enfrentan serias dificultades para tener visibilidad en tiempo real del inventario. En la mayoría de los casos, dependen de registros manuales, hojas de cálculo desactualizadas o simples estimaciones, lo que impide contar con información precisa y confiable. Esta carencia conlleva consecuencias críticas: por un lado, se producen quiebres de inventario en momentos de alta demanda, generando pérdida de ventas, insatisfacción en los clientes y daño en la reputación del negocio. Por otro lado, también se generan excesos de compras y acumulación innecesaria de productos, que muchas veces terminan en desperdicio o caducidad, incrementando los costos operativos. En un sector altamente competitivo como el gastronómico, la falta de control oportuno del stock no solo afecta la eficiencia de las operaciones, sino que compromete la sostenibilidad financiera del negocio a mediano y largo plazo.

**Problem Statement 2:**

La gestión manual de insumos, recetas y procesos relacionados al control de inventario consume grandes cantidades de tiempo y se convierte en una fuente recurrente de errores humanos. El uso de métodos tradicionales, como anotaciones en cuadernos o la dependencia exclusiva de la memoria del personal, genera inconsistencias en las cantidades registradas, omisiones en los cálculos de costos y dificultades para rastrear el uso de cada insumo en las preparaciones. Estas fallas impactan directamente en la rentabilidad del negocio, ya que dificultan la correcta proyección de compras y provocan mermas innecesarias. Además, la ausencia de un sistema estandarizado limita la capacidad de replicar procesos de manera consistente, afectando la calidad del servicio ofrecido al cliente final. En consecuencia, la gestión manual no solo compromete la eficiencia interna, sino también la experiencia del consumidor, reduciendo la competitividad del negocio frente a aquellos que han adoptado soluciones digitales.

#### 1.2.2.2. Lean UX Assumptions

En esta sección se establecen las suposiciones de negocio y de usuario que guiarán el desarrollo de la solución propuesta. Dichas suposiciones constituyen hipótesis que deberán ser validadas en el proceso de diseño y puesta en marcha del sistema, a fin de reducir riesgos y garantizar que la aplicación responda efectivamente a las necesidades del mercado. Siguiendo el marco de Lean UX, estas hipótesis se convierten en una guía para orientar decisiones de diseño, priorización de funcionalidades y estrategias de adquisición de clientes. Las siguientes suposiciones se formulan considerando las particularidades del sector gastronómico, las tendencias de digitalización y los principales desafíos en la gestión de inventarios.

**Business Outcomes:**

- **Creemos que mis usuarios necesitan**

Un sistema ágil, intuitivo y confiable que les permita controlar de manera integral los inventarios, gestionar proveedores de forma más eficiente y anticipar posibles quiebres de stock.

- **Estas necesidades se pueden resolver**

Mediante un software web multiplataforma, accesible desde cualquier dispositivo con conexión a internet, que brinde visibilidad en tiempo real, alarmas preventivas y herramientas de análisis para la toma de decisiones estratégicas.

- **Nuestros clientes iniciales son**

Negocios gastronómicos de pequeña y mediana escala, como restobares, cafeterías y restaurantes, que requieren optimizar la administración de sus insumos sin necesidad de contar con un gran equipo administrativo o con elevados presupuestos tecnológicos.

- **El valor #1 que un cliente requiere de nuestro servicio es**

La precisión y confiabilidad en la gestión del inventario, garantizando el abastecimiento oportuno de insumos y reduciendo las pérdidas ocasionadas por desperdicios, caducidad o compras excesivas.

- **El cliente también puede obtener estos beneficios adicionales**

Generación de reportes detallados y personalizables, reducción de pérdidas económicas, incremento en la eficiencia operativa, mejor control de costos, mayor trazabilidad de los insumos y, en consecuencia, un aumento en la rentabilidad del negocio.

- **Adquiriremos a nuestros clientes a través del**

Estrategias de marketing digital, colaboraciones con asociaciones gastronómicas, recomendaciones entre colegas del sector, y la implementación de planes de prueba gratuita que permitan experimentar los beneficios antes de la adquisición.

- **Haremos dinero a través de**

Un modelo de suscripción mensual o anual, complementado con la venta de licencias y el cobro por servicios de soporte técnico, mantenimiento y actualizaciones continuas del sistema.

- **Nuestra competencia de mercado serán**

Sistemas de inventario genéricos o de uso general, que no se encuentran especializados en el sector gastronómico y, por lo tanto, no logran resolver de manera completa las necesidades particulares de este mercado.

- **Los venceremos debido a que**

Ofrecemos una solución diseñada específicamente para la industria gastronómica, con funcionalidades adaptadas a sus procesos únicos, interfaces fáciles de usar y un enfoque en la reducción de pérdidas y mejora de la rentabilidad.

- **Nuestros mayores riesgos son**

La resistencia de algunos negocios a adoptar nuevas tecnologías, la percepción de que los sistemas digitales son costosos, así como la falta de conocimiento técnico para utilizarlos de manera efectiva.

- **Resolveremos esto mediante**

Programas de capacitación prácticos, soporte técnico cercano y proactivo, y el diseño de un sistema intuitivo que reduzca la curva de aprendizaje y genere confianza en su implementación.

- **Sabremos que hemos tenido éxito cuando uno de estos cambios en el comportamiento de nuestro cliente**

El uso constante y disciplinado del sistema en las operaciones diarias, la reducción medible de pérdidas en insumos, la mejora en el control financiero y un mayor grado de satisfacción en la gestión del negocio.

- **Qué otras suposiciones tenemos que, de probarse falsas pueden causar que nuestro proyecto fracase**

Que los negocios gastronómicos no consideren prioritario invertir en tecnología de gestión, que prefieran continuar con métodos tradicionales manuales, o que la percepción del costo-beneficio no sea suficiente para justificar la adopción del sistema.

**User Outcomes**

**¿Quiénes serán nuestros usuarios?**

Nuestros usuarios principales serán propietarios, administradores y personal operativo de restaurantes, cafeterías, restobares y bares. Estos perfiles desempeñan un papel clave en la gestión de compras, control de insumos y organización del servicio diario.

**¿Dónde encaja nuestro producto en su vida o trabajo?**

El producto se integra de manera directa en la gestión diaria del negocio gastronómico, apoyando actividades como:

- Control de inventarios.
- Registro de compras y ventas.
- Organización de recetas e insumos.
- Coordinación con proveedores y gestión de pedidos.

**¿Qué problemas tiene nuestro producto y cómo se pueden resolver?**

**Problemas:**

- Sobrecostos ocasionados por desorganización y compras innecesarias.
- Falta de control en el stock de insumos.
- Retrasos en pedidos y reposiciones críticas.
- Pérdidas económicas por caducidad, desperdicio o errores de registro.

**Soluciones:**

- Automatización de inventarios con reportes y alertas inteligentes.
- Acceso a un sistema web centralizado y disponible desde cualquier dispositivo.
- Notificaciones automáticas sobre niveles bajos de stock.
- Módulo de gestión de recetas y proveedores que optimiza la planificación de compras.

**¿Cómo y cuándo es usado nuestro producto?**

El sistema será utilizado todos los días, en las diferentes fases de operación de un negocio gastronómico:

- Apertura: revisión de stock, planificación de compras y pedidos.
- Operación diaria: registro de insumos utilizados, actualización de recetas y control de ventas.
- Cierre: consolidación de reportes, cálculo de costos y análisis de pérdidas o desperdicios.

**¿Qué características son importantes?**

- Gestión integral de stock e insumos.
- Automatización de alertas para evitar quiebres de inventario.
- Reportes detallados de costos, consumo y eficiencia.
- Gestión de proveedores y recetas vinculadas a inventario.
- Roles y permisos de usuarios que garanticen control y trazabilidad.
- Exportación de reportes en formatos PDF/Excel para facilitar la toma de decisiones.

**¿Cómo debe verse y comportarse nuestro producto?**

Debe ser un sistema intuitivo, moderno y fácil de usar, con una interfaz limpia que priorice la claridad visual. Además, debe ser rápido, seguro y confiable, con un diseño adaptable a cualquier dispositivo (desktop, tablet, smartphone) para acompañar a los usuarios en todo momento de su operación diaria.

**Features**

- Gestión de stock en tiempo real.
- Alertas automáticas de inventario bajo.
- Creación y administración de recetas.
- Gestión de proveedores y pedidos.
- Roles y permisos de usuarios.
- Generación de reportes personalizables (PDF/Excel).

**_Desde la cuenta de la empresa cliente:_**

- Las empresas deben tener acceso a un panel donde visualicen todos los equipos arrendados, organizados por área o departamento. Esto les permitirá un control ordenado y evitar pérdidas o duplicidades.

- Además, se debería incluir un sistema de búsqueda avanzada y filtros dinámicos (por tipo de dispositivo, fecha de adquisición, estado de garantía, proveedor asignado), lo que mejorará la eficiencia en la gestión.

- Un historial de mantenimiento y soporte estará disponible para cada equipo, lo que garantiza transparencia en las intervenciones técnicas y ayuda a tomar decisiones futuras. Dicho historial podría exportarse en formatos PDF/Excel y compartirse con auditores o gerentes para cumplir con normativas internas o legales.

- Contarán con un sistema de alertas automáticas para notificar cuándo un equipo está próximo a su renovación o si requiere atención especial, evitando interrupciones en su productividad. Estas alertas podrían configurarse con niveles de criticidad (baja, media, alta), y enviarse no solo dentro de la plataforma, sino también mediante correo electrónico o aplicaciones de mensajería (ej. WhatsApp Business o Microsoft Teams).

- El cliente podrá solicitar upgrades de hardware de forma ágil desde su cuenta, ajustando los recursos a sus necesidades reales en tiempo casi inmediato. Esto debería estar integrado con un catálogo dinámico de opciones disponibles, donde el cliente pueda comparar costos, beneficios y tiempos de entrega.

- Un dashboard de costos consolidado permitirá analizar el gasto mensual en TI y medir el ahorro frente a un modelo tradicional de compra. Este dashboard debería incluir gráficas comparativas, simuladores de costos futuros y métricas de ROI (Retorno de Inversión) para respaldar la toma de decisiones estratégicas.

- Adicionalmente, la cuenta cliente podría integrar un módulo de tickets de soporte, donde se pueda dar seguimiento en tiempo real al estado de cada solicitud, con tiempos de respuesta garantizados (SLA).

- Finalmente, un módulo de capacitación digital permitiría que los usuarios accedan a tutoriales, manuales y webinars dentro del mismo sistema, facilitando la adopción tecnológica.

**_Desde la cuenta de administración de PcPedia:_**

- Los administradores tendrán un sistema centralizado para monitorear en tiempo real todos los equipos en uso por los clientes, junto con su estado de garantía y mantenimientos programados. Esto debe incluir un mapa interactivo de clientes (geolocalización) para optimizar la distribución de técnicos y recursos.

- Contarán con herramientas de análisis predictivo para recomendar a cada cliente los equipos más rentables según su patrón de uso. Este análisis podría alimentarse con modelos de machine learning, que identifiquen patrones de fallas, ciclos de vida óptimos y predicciones de sustitución.

- Se dispondrá de un módulo para gestionar contratos y facturación de manera automatizada, evitando errores manuales. Además, debería soportar múltiples métodos de pago (tarjeta, transferencia, pasarelas digitales como Stripe o PayPal) y la posibilidad de facturación electrónica integrada según normativas locales.

- La plataforma permitirá registrar casos de soporte y asignar técnicos rápidamente, reduciendo los tiempos de respuesta. Se puede integrar un sistema de priorización automática que clasifique los tickets por urgencia y complejidad, asignando el recurso más calificado de forma inmediata.

- Un repositorio de métricas de clientes servirá para identificar patrones, generar reportes y mejorar continuamente el servicio de Smart Leasing. Dicho repositorio debería estar acompañado de un sistema de benchmarking, que compare el desempeño de diferentes clientes y ofrezca insights personalizados para la optimización.

- PcPedia también podría contar con un módulo de administración de inventario interno, que permita verificar la disponibilidad de equipos, repuestos y accesorios antes de aprobar solicitudes de clientes.

- Finalmente, un sistema de auditoría y trazabilidad registrará todas las acciones realizadas por administradores y clientes, garantizando seguridad, transparencia y cumplimiento normativo (por ejemplo, GDPR o regulaciones locales de protección de datos).

#### 1.2.2.3. Lean UX Hypothesis Statements

- **Creemos que** los administradores podrán optimizar el inventario con el sistema, ya que este proporcionará información precisa, centralizada y actualizada en tiempo real sobre los niveles de stock y el consumo de insumos. Esto permitirá reducir drásticamente la dependencia de registros manuales y hojas de cálculo, lo cual suele generar errores y pérdidas económicas.

- **Sabremos que** esta hipótesis es cierta cuando se reduzcan en al menos un 15 % los quiebres de stock y se observe una mejora sustancial en la capacidad de anticipar compras necesarias, evitando tanto la escasez de productos críticos como la sobrecompra de insumos perecibles.

- **Creemos que** los reportes ayudarán a tomar mejores decisiones de compra, porque ofrecerán un análisis histórico de consumos, tendencias de demanda y rotación de productos. De esta manera, los responsables podrán comparar periodos, identificar patrones y negociar con proveedores en condiciones más favorables. Además, los reportes servirán como base para implementar estrategias de reducción de costos sin comprometer la calidad del servicio.

- **Sabremos que** la hipótesis es válida cuando se logre una disminución comprobable en los costos operativos mensuales y se identifique una mayor eficiencia en la planificación de compras, optimizando tanto el presupuesto como la rentabilidad general del negocio.

- **Creemos que** el sistema será adoptado por el personal de forma natural, siempre que la interfaz sea intuitiva, rápida y se adapte a los procesos cotidianos de trabajo. La adopción orgánica será clave para garantizar que no solo los administradores, sino también el personal de cocina y bar, puedan registrar fácilmente cada movimiento en el inventario.

- **Sabremos que** esta hipótesis se confirma cuando los trabajadores registren transacciones diarias de manera constante, sin depender de supervisión directa, reflejando un nivel de confianza y facilidad de uso que garantice la sostenibilidad de la herramienta en el largo plazo.

#### 1.2.2.4. Lean UX Canvas

![Logo UPC](https://i.imgur.com/SZVlLz9.png)

## 1.3. Segmentos objetivo

En nuestro proyecto, los segmentos han sido definidos a partir de criterios como el tipo de establecimiento, el nivel de digitalización alcanzado y los principales desafíos operativos que enfrentan. A continuación, se presentan los tres grupos prioritarios de usuarios que servirán como base para la implementación y validación de la propuesta:

1. **Restobares y Restaurantes (pequeños y medianos)**

   Estos negocios se caracterizan por manejar una gran variedad de insumos y proveedores, lo que incrementa la complejidad de su control operativo. La falta de digitalización suele llevar a pérdidas por duplicidad de pedidos, sobrecompra de productos perecibles y dificultad para medir la rentabilidad real de cada plato ofrecido. La implementación de un sistema de control digital permite a estos negocios integrar compras, recetas y stock en un solo entorno, reduciendo costos y mejorando la consistencia del servicio. Un estudio académico peruano, centrado en mejoras concretas para la gestión de inventario en el sector gastronómico, destaca cómo una estrategia planificada y digitalizada contribuye a un abastecimiento más oportuno y eficiente en tiempos adecuados (Elvira, A. Mari, F. (2018)).

2. **Cafeterías y Bares**

   Son establecimientos que trabajan con productos de alta rotación (como café, cerveza, snacks) y con insumos perecibles (como lácteos, frutas y licores). La gestión manual del inventario puede ocasionar desajustes críticos, impactando directamente en las ventas del día. Con un sistema automatizado, se garantiza un flujo constante de información en tiempo real, permitiendo evitar quiebres de stock en horarios de alta demanda. Además, la digitalización de recetas estandariza procesos y mejora la calidad del servicio. Una investigación sobre la influencia de la digitalización en la calidad del servicio en PYMEs del rubro restaurante en Perú demuestra que la adopción tecnológica incide positivamente en la eficiencia operativa y en la percepción de calidad por parte del cliente (Jenny, J. Sara, L. (2024)).

3. **Emprendimientos Gastronómicos**

   Los nuevos negocios enfrentan grandes desafíos en sus primeros años, y uno de los más frecuentes es la mala gestión de inventarios y finanzas, que puede llevar al cierre prematuro del emprendimiento. Un sistema accesible y escalable les brinda a los emprendedores la posibilidad de iniciar con procesos claros, medibles y organizados desde el primer día. Esto no solo ayuda a evitar errores comunes, como sobrecompras o falta de insumos críticos, sino que también genera información clave para proyectar el crecimiento del negocio. Además, un estudio reciente en el contexto peruano muestra cómo una gestión eficaz de costos, basada en sistemas organizados, contribuye a mantener márgenes de rentabilidad saludables incluso en situaciones adversas (Martin, C. Selena, V. Miguel A. (2024)). Asimismo, el notable auge del sector gastronómico en Perú, con un crecimiento del 63.59 % en emprendimientos, subraya el potencial y la necesidad de contar con bases tecnológicas sólidas desde el inicio (Infobae 2024).

## Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

Dentro del mercado peruano existen múltiples opciones digitales para solucionar el problema de la gestión de inventarios, que compiten directa o indirectamente con nuestra propuesta. Entre los principales competidores identificados se encuentran:

**Nubefact:** Plataforma peruana conocida por su servicio de facturación electrónica, que incluye herramientas para la administración de inventarios y ventas. Aunque cumple con las normativas de SUNAT y ofrece integración con sistemas POS, su principal beneficio no es la gestión de inventarios, lo que limita el nivel de personalización para las empresas que lo adquieren.

**Siigo Perú:** Antes conocido como Contasis, es un sistema contable y administrativo que incorpora funciones como control de inventarios, compras y ventas. Tiene una amplia trayectoria en el mercado peruano y brinda soporte técnico local. Sin embargo, está más orientado a la contabilidad que a la gestión gastronómica, con interfaces menos intuitivas para usuarios sin experiencia tecnológica.

**Factura Perú:** Solución peruana orientada a la facturación electrónica e inventarios para negocios pequeños. Sus principales beneficios son los costos accesibles, el cumplimiento legal con SUNAT y la facilidad de uso para empresas en crecimiento. No obstante, presenta limitaciones en funciones avanzadas enfocadas en gastronomía, como gestión de recetas, control de insumos perecibles o reportes especializados.

Finalmente, es importante mencionar que algunos negocios en Perú aún recurren a herramientas indirectas como Excel o Google Sheets para llevar el control de sus inventarios de manera manual.

## 2.1.1. Análisis competitivo

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 15%" />
<col style="width: 18%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>

<thead>
<tr class="header">
    <th colspan="6"><strong>Competitive Analysis Landscape</strong></th>
</tr>

<tr class="odd">
    <th rowspan="2">
        <p>¿Por qué llevar a cabo este análisis?</p>
    </th>
    <th colspan="5">
        Analizar la competencia directa en soluciones de facturación e inventarios en Perú, identificando fortalezas, debilidades, oportunidades y amenazas para posicionar nuestra startup gastronómica.
    </th>
</tr>

<tr class="header">
    <th colspan="2">
        <p>(En la cabecera colocar por</p>
        <p>cada competidor nombre y</p>
        <p>logo)</p>
    </th>
    <th>Su Startup</th>
    <th>Nubefact</th>
    <th>Siigo Perú</th>
    <th>Factura Perú</th>
</tr>

<!-- PERFIL -->
<tr class="header">
    <th rowspan="2">Perfil</th>
    <th>Overview</th>
    <th>Aplicación web especializada en gestión de inventarios para el sector gastronómico.</th>
    <th>Plataforma peruana centrada en facturación electrónica, con módulo básico de inventarios.</th>
    <th>Sistema contable y administrativo con funciones de inventario, compras y ventas.</th>
    <th>Solución peruana de facturación electrónica con módulo de inventarios para negocios pequeños.</th>
</tr>

<tr class="odd">
    <th>
        <p>Ventaja competitiva</p>
        <p>¿Qué valor</p>
        <p>ofrece a los</p>
        <p>clientes?</p>
    </th>
    <th>Especialización gastronómica: recetas, control de insumos perecibles, alertas automáticas.</th>
    <th>Cumplimiento con SUNAT y alta adopción en negocios peruanos.</th>
    <th>Amplia trayectoria, soporte contable y administrativo.</th>
    <th>Costos accesibles y facilidad de uso para microempresas.</th>
</tr>

<!-- PERFIL DE MARKETING -->
<tr class="header">
    <th rowspan="2">Perfil de Marketing</th>
    <th>Mercado objetivo</th>
    <th>Restaurantes, cevicherías, cafeterías y emprendimientos gastronómicos.</th>
    <th>Empresas de todos los rubros que requieren facturación electrónica.</th>
    <th>PYMEs que buscan un sistema administrativo y contable.</th>
    <th>Negocios pequeños: bodegas, tiendas, etc.</th>
</tr>

<tr class="odd">
    <th>
        <p>Estrategias de</p>
        <p>marketing</p>
    </th>
    <th>Marketing digital, alianzas con gremios gastronómicos, referidos.</th>
    <th>Posicionamiento como líder en facturación electrónica en Perú.</th>
    <th>Presencia corporativa y convenios contables.</th>
    <th>Promoción de precios bajos y cumplimiento legal.</th>
</tr>

<!-- PERFIL DE PRODUCTO -->
<tr class="header">
    <th rowspan="3">Perfil de Producto</th>
    <th>
        <p>Productos &amp;</p>
        <p>Servicios</p>
    </th>
    <th>Inventario en tiempo real, recetas, proveedores, reportes y alertas automáticas.</th>
    <th>Facturación electrónica + inventarios básicos.</th>
    <th>Contabilidad, inventarios, compras y ventas.</th>
    <th>Facturación e inventarios simples.</th>
</tr>

<tr class="odd">
    <th>Precios &amp; Costos</th>
    <th>Planes escalables y accesibles para pymes gastronómicas.</th>
    <th>Suscripciones orientadas a facturación.</th>
    <th>Costos más altos, orientados a contabilidad integral.</th>
    <th>Costos bajos para pequeños negocios.</th>
</tr>

<tr class="header">
    <th>
        <p>Canales de</p>
        <p>distribución</p>
        <p>(Web y/o Móvil)</p>
    </th>
    <th>100% web responsive. Disponible en móviles.</th>
    <th>Web.</th>
    <th>Web y aplicaciones conectadas.</th>
    <th>Web (principalmente escritorio).</th>
</tr>

<!-- SWOT -->
<tr class="odd">
    <th rowspan="5">Análisis SWOT</th>
    <th colspan="5"></th>
</tr>

<tr class="header">
    <th>Fortalezas</th>
    <th>Especialización en gastronomía, interfaz intuitiva, reportes claros.</th>
    <th>Cumplimiento legal con SUNAT y gran base de clientes.</th>
    <th>Trayectoria, soporte técnico local.</th>
    <th>Precio accesible y fácil implementación.</th>
</tr>

<tr class="odd">
    <th>Debilidades</th>
    <th>Nueva en el mercado, menos reconocimiento.</th>
    <th>Módulo de inventarios poco desarrollado.</th>
    <th>Complejidad de uso y enfoque contable.</th>
    <th>Funciones limitadas en gastronomía.</th>
</tr>

<tr class="header">
    <th>Oportunidades</th>
    <th>Crecimiento del sector gastronómico y digitalización de pymes.</th>
    <th>Ampliar funciones hacia sectores especializados.</th>
    <th>Integrar más módulos sectoriales.</th>
    <th>Expandirse en microempresas.</th>
</tr>

<tr class="odd">
    <th>Amenazas</th>
    <th>Resistencia al cambio tecnológico y competencia consolidada.</th>
    <th>Aparición de softwares especializados en gastronomía.</th>
    <th>Competidores más simples y accesibles.</th>
    <th>Migración a plataformas más completas.</th>
</tr>

</thead>
<tbody>
</tbody>
</table>


## 2.1.2. Estrategias y tácticas frente a competidores

Estrategias: 

*   Resaltar la especialización gastronómica frente a competidores generales de facturación e inventarios.
    
*   Ofrecer precios accesibles y escalables, que se adapten al tamaño y crecimiento del negocio gastronómico.
    
*   Garantizar seguridad y confiabilidad, con roles de usuario, respaldos automáticos y protección de datos.
    
*   Aprovechar la digitalización acelerada del sector gastronómico en Perú, impulsada por la necesidad de eficiencia y control.
    
*   Mantener la innovación constante, incorporando funcionalidades específicas como gestión de recetas, alertas de insumos perecibles y reportes de rentabilidad.
    
*   Promover una experiencia de usuario intuitiva y accesible, diseñada específicamente para negocios gastronómicos, lo que facilita la adopción rápida del sistema sin necesidad de conocimientos técnicos avanzados.
    

Tácticas:

*   Campañas de marketing digital enfocadas en redes sociales y asociaciones con gremios gastronómicos, destacando la facilidad de uso y el ahorro en pérdidas de insumos.
    
*   Demostración gratuitas (free trials) para mostrar beneficios inmediatos del sistema frente a la competencia.
    
*   Capacitación y soporte cercano, ayudando a superar la resistencia al cambio tecnológico que afecta a muchos negocios pequeños.
    
*   Desarrollo de tutoriales y guías interactivas, para que cualquier usuario (sin conocimientos contables) pueda manejar el sistema sin dificultad.
    
*   Reportes personalizables en PDF/Excel, resaltando cómo ayudan a la toma de decisiones y la reducción de costos.
    
*   Monitoreo constante de competidores para adaptar mejoras rápidamente y aprovechar sus debilidades.
    

Estrategia freemium o plan básico económico, que atraiga a microempresas que de otro modo optaron por soluciones limitadas como Excel.

## 2.2. Entrevistas

El objetivo de las entrevistas es recolectar información cualitativa de propietarios, administradores y personal de negocios gastronómicos para conocer sus características demográficas y de contexto, identificar hábitos de gestión de inventarios y tecnología, explorar necesidades, frustraciones y expectativas con respecto a un sistema digital de gestión y construir arquetipos de usuario que guíen el diseño del producto.

### 2.2.1. Diseño de entrevistas

**Para restobares y restaurantes:**

Preguntas principales:

1.  ¿Cuál es el nombre de su negocio, en qué distrito se ubica y cuántos años lleva operando?
    
2.  ¿Qué métodos utilizan actualmente para controlar el inventario (manual, Excel, sistema)?
    
3.  ¿Qué problemas han enfrentado en el control de insumos y productos (quiebres, exceso, desperdicio)?
    
4.  ¿Cómo realizan actualmente la reposición de insumos perecibles?
    
5.  ¿Cómo gestionan la relación con proveedores y recetas?
    
6.  ¿Qué tipo de reportes o información necesitan para tomar decisiones de compra?
    
7.  ¿Qué factores los motivarían a implementar un sistema digital de inventarios?
    

      Preguntas complementarias:

1.  ¿Podría contarme un poco sobre usted?
    
2.  ¿Qué dispositivos usan más en la gestión del negocio (computadora, tablet, celular)?.
    
3.  ¿Qué canales digitales utilizan con más frecuencia (WhatsApp, correo, redes sociales)?
    
4.  Cuando toma decisiones importantes, ¿las consulta con alguien más (familia, socios, colegas)?
    
5.  ¿Qué objetivos tienen a corto plazo (por ejemplo: reducir pérdidas, abrir nuevas sedes)?
    
6.  En su día a día, ¿qué es lo que más le frustra en la gestión del negocio?
    
7.  ¿Cómo empezó en el rubro gastronómico?
    

**Para cafeterías y bares:**

1.  ¿Cuál es el nombre de su negocio, en qué distrito está y cuántos años lleva operando?
    
2.  ¿Cuáles son los productos de mayor rotación en su cafetería o bar?
    
3.  ¿Cómo controlan actualmente la reposición de insumos perecibles?
    
4.  ¿Han tenido pérdidas económicas por caducidad o falta de control de inventario?
    
5.  ¿Qué tan relevantes serían para ustedes las alertas automáticas de stock bajo?
    
6.  ¿Qué beneficios esperan de un sistema especializado en gastronomía?
    
7.  ¿Qué limitaciones han encontrado con los métodos que usan actualmente (Excel, manual)?
    

Preguntas complementarias: 

1.  ¿Podría contarme un poco sobre usted? (edad, ocupación, lugar de residencia).
    
2.  ¿Qué dispositivos suelen usar durante la operación (celular en turno, PC en oficina)?
    
3.  ¿Qué tan familiarizado está con herramientas digitales (Excel, apps, POS)?
    
4.  ¿Qué personas, marcas o colegas suelen influir cuando deciden implementar nuevas herramientas en el negocio?
    
5.  ¿Qué objetivos buscan alcanzar (optimizar compras, reducir desperdicios, mejorar márgenes)?
    
6.  ¿Qué experiencias previas han tenido con software de inventarios u otros sistemas? ¿Qué les gustó o no?
    

**Para emprendimientos gastronómicos:**

Preguntas principales:

1.  ¿Cuál es el nombre de su negocio, en qué distrito se ubica y cuánto tiempo lleva operando?
    
2.  ¿Qué los motivó a iniciar este emprendimiento gastronómico?
    
3.  ¿Cómo gestionan actualmente sus inventarios y proveedores?
    
4.  ¿Qué funciones consideran esenciales en un sistema que los acompañe desde el inicio?
    
5.  ¿Qué factores los harían confiar en un software (precio, facilidad de uso, soporte, recomendación)?
    
6.  ¿Qué tan importante es para ustedes recibir reportes sobre costos y rentabilidad?
    
7.  ¿Qué objetivos tienen a corto y mediano plazo con el negocio (ej. crecer, formalizarse, digitalizar procesos)?
    

Preguntas complementarias: 

1.  Para conocerte un poco más, ¿cuál es tu edad, ocupación y dónde resides?
    
2.  ¿Qué experiencia previa has tenido en gastronomía o en otros rubros?
    
3.  ¿Qué dispositivos prefieres para trabajar (celular, tablet, PC)?
    
4.  ¿Qué personas, marcas o referentes suelen considerar antes de decidir sobre nuevas herramientas digitales?
    
5.  Si pudieras diseñar la herramienta ideal para tu negocio, ¿cómo sería?

### 2.2.2. Registro de entrevistas


Segmento objetivo: Restaurantes y Restobares

Entrevista 1

![Entrevista](assets/restaurante1.png)

**Entrevistado:** Luciano De La Torre  
**Edad:** 25 años  
**Distrito:** Pueblo Libre  
**Negocio:** Sazón Familiar  
**Minuto de inicio:**  00:00
**URL del video en Microsoft Stream:** [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)   

**Resumen**  
El entrevistado es un joven de 25 años que administra *Sazón Familiar* en Pueblo Libre, un restaurante familiar con 12 años en el rubro. Actualmente gestiona inventarios manualmente y en Excel, lo que ocasiona quiebres de stock, sobrecompras y desperdicio. La reposición de perecibles se hace diariamente y los proveedores se contactan por WhatsApp o teléfono.  

Menciona que las recetas no están completamente estandarizadas, lo que genera variaciones en costos. Su mayor frustración es la falta de control real del inventario. Considera que un sistema digital debería ser sencillo, dar alertas automáticas, organizar proveedores y calcular costos por plato. Su objetivo es modernizar el negocio familiar, optimizar la cocina y abrir un segundo local a mediano plazo.  

---

Entrevista 2

![Entrevista](assets/restaurante2.png)

**Entrevistado:** Juan José López  
**Edad:** 28 años   
**Negocio:** La Esquina Limeña  
**Distrito:** Barranco – Lima  
**Minuto de inicio:**  03:18
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
El entrevistado administra un restobar en Barranco con 3 años de operación. Controla inventarios en Excel, pero depende de encargados y se generan errores. Los problemas principales son el desperdicio por sobrecompra y quiebres de insumos en alta demanda.  

La reposición se hace dos veces por semana vía WhatsApp o llamadas, y en emergencias en el mercado. Las recetas están dispersas en cuadernos y correos, sin conexión al inventario. Señala que necesita reportes con consumo promedio, stock mínimo y costos.  

Un sistema lo motivaría si es accesible desde celular, fácil de usar, con alertas y costo razonable. Su frustración es la falta de información en tiempo real y su objetivo es reducir pérdidas antes de expandirse.  

---

Entrevista 3

![Entrevista](assets/restaurante3.png)

**Entrevistado:** Patricio Rodríguez Amador  
**Edad:** 27 años  
**Distrito:** Comas  
**Negocio:** Apolo Restobar  
**Tiempo de operación:** 3 años  
**Minuto de inicio:**  05:46
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
Patricio Rodríguez, dueño de *Apolo Restobar* en Comas, lleva 3 años operando. Usa un sistema recomendado por un amigo, pero limitado y sin soporte. Su principal problema es el desperdicio de insumos por falta de reportes claros.  

La reposición de perecibles se maneja con proveedores sin agenda fija. No tiene gestión formal de recetas. Le interesa contar con reportes comparativos de insumos usados vs. desperdiciados y valora el soporte técnico.  

Usa computadora y celular, se comunica principalmente por WhatsApp. Su objetivo es reducir pérdidas y mejorar la organización interna.  

---

**Segmento objetivo: Cafeterías y Bares**


Entrevista 1

![Entrevista](assets/cafeteria1.png)

**Entrevistada:** Alejandra Martínez  
**Edad:** 25 años  
**Distrito:** Surco  
**Negocio:** Dulce Aroma  
**Tiempo de operación:** 2 años  
**Minuto de inicio:** 07:50
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
La dueña de *Dulce Aroma*, en Surco, lleva 2 años de operación. Sus productos más vendidos son cafés (capuccino, latte), sándwiches y postres caseros. Maneja el inventario manualmente, con compras casi diarias de perecibles, lo que causa pérdidas por caducidad.  
Un sistema con alertas de stock bajo le sería útil para anticiparse. Espera que un software especializado organice inventarios, calcule costos por receta y genere reportes. Usa celular y computadora, maneja Excel, apps y POS. Se guía por colegas y redes sociales. Sus objetivos son reducir desperdicios, mejorar márgenes y abrir una segunda sede.  

Entrevista 2

![Entrevista](assets/cafeteria2.png)


**Entrevistado:** Leonardo Solís  
**Edad:** 34 años  
**Distrito:** Miraflores  
**Negocio:** Café Aroma  
**Tiempo de operación:** 5 años  
**Minuto de inicio:**  13:07
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
El dueño de *Café Aroma*, en Miraflores, lleva 5 años de operación. Los productos de mayor rotación son cafés, postres artesanales y cervezas artesanales. Maneja inventarios manualmente, lo que genera pérdidas por caducidad.  

Considera esencial un sistema con alertas automáticas, control en tiempo real y reportes de costos. Critica Excel por tedioso y poco confiable. Se dedica de lleno al negocio tras dejar marketing. Usa celular y PC, y suele guiarse por colegas y asociaciones. Sus objetivos son optimizar compras, reducir desperdicios y abrir un segundo local.  

Entrevista 3

![Entrevista](assets/cafeteria3.png)


**Entrevistado:** Gonzalo Flores Rojas  
**Distrito:** Barrios Altos  
**Negocio:** Tinco  
**Tiempo de operación:** 10 meses  
**Minuto de inicio:**  17:56
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
Gonzalo Flores es dueño de *Tinco*, con 10 meses en Barrios Altos. Sus productos más rotados son insumos para kekes y tortas. No tiene proveedores fijos y compra según necesidad, lo que le genera pérdidas por caducidad.  
Considera muy valiosas las alertas de inventario, sobre todo que avisen vencimientos próximos. Usa Excel, pero lo ve limitado porque no anticipa problemas ni genera reportes. Ve en un sistema digital la oportunidad de mejorar el orden y control para crecer de manera sostenible.  

---

**Segmento objetivo: Emprendimientos Gastronómicos**

Entrevista 1

![Entrevista](assets/emprendedor1.png)


**Entrevistada:** Luciana Aguilar  
**Edad:** 17 años  
**Distrito:** Ate (distribución en La Molina y Surco)  
**Negocio:** Laguntis Verigen (repostería)  
**Tiempo de operación:** 3 años  
**Minuto de inicio:**  19:57
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
Luciana Aguilar, de 17 años, creó *Laguntis Verigen*, un emprendimiento de repostería con 3 años de operación. Empezó como un hobby, con apoyo de su madre, quien maneja inventarios. Ella se encarga de la preparación y promoción en Instagram.  
Considera clave contar con reportes de costos y pérdidas para decidir qué productos priorizar. Busca un software sencillo, accesible y que automatice procesos. Usa el celular para promocionar y gestionar pedidos. Se inspira en referentes como Alessandra Penny.  
Aunque valora el negocio, no busca expandirse, ya que lo considera complementario a su interés en las finanzas. Su herramienta ideal sería una página web para organizar mejor pedidos y comunicación.  

Entrevista 2

![Entrevista](assets/emprendedor2.png)


**Entrevistado:** Juan Alberto Rosales  
**Edad:** 28 años  
**Distrito:** San Isidro 
**Negocio:** Sabor Criollo  
**Tiempo de operación:** 8 meses  
**Minuto de inicio:**  31:15
**URL del video en Microsoft Stream:**   [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)   

**Resumen**  
Juan Rosales abrió *Sabor Criollo* hace 8 meses en San Isidro tras iniciar ventas durante la pandemia. Hoy controla inventarios con cuadernos y Excel, contactando proveedores por WhatsApp o llamadas.  

Busca un sistema que ofrezca control en tiempo real, alertas, cálculo de costos y organización de proveedores. Destaca que debe ser accesible, fácil y con soporte. Reportes de costos serían claves para crecer. Sus metas son reducir pérdidas, digitalizar procesos y abrir un segundo local.  

Tiene 28 años, vive en SJL y antes trabajaba en ventas. Usa celular en el día a día y PC para cuentas. Suele guiarse por colegas y reseñas online. Su app ideal sería sencilla, intuitiva y móvil, con alertas y reportes claros.  

Entrevista 3

![Entrevista](assets/emprendedor3.png)


**Entrevistado:** Andrés Cieza de León  
**Edad:** 31 años  
**Distrito:** San Juan de Lurigancho  
**Negocio:** Hamburguesería (nombre no especificado)  
**Tiempo de operación:** 2 años  
**Minuto de inicio:**  34:57
**URL del video en Microsoft Stream:**  [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221a118_upc_edu_pe/ESg13gM5GtlNmoyLYxTu9AEB2dEAnd_uByYu-Nh3B4dRuQ?e=zcQfTL&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)  

**Resumen**  
Andrés Cieza de León es dueño de una hamburguesería en SJL con 2 años de operación. Emprendió porque en su zona había pocas opciones y de baja calidad.  

Actualmente maneja inventarios en Excel, pero considera vital tener reportes y gráficos accesibles. Para él, la facilidad de uso es lo más importante en un software, ya que no quiere perder tiempo en procesos complicados.  

Señaló que la información clara y visual es fundamental para tomar decisiones y que busca expandirse en el mundo digital para hacer crecer su negocio.  


### 2.2.3. Análisis de entrevistas

Segmento: Restaurantes y Restobares (3 entrevistas)

- **Método de gestión de inventario:**  
  El 100% maneja inventarios manualmente o en Excel. Solo 1 de 3 (33%) ha probado un sistema digital, pero lo considera limitado y sin soporte.

- **Problemas frecuentes:**  
  100% mencionó quiebres de stock y sobrecompras.  
  67% indicó pérdidas por desperdicio de insumos y falta de información en tiempo real.

- **Reposición de insumos:**  
  100% se abastece vía WhatsApp o llamadas.  
  67% realiza compras frecuentes (diarias o dos veces por semana).

- **Necesidades en un sistema digital:**  
  100% pidió alertas automáticas y reportes de costos/consumo.  
  67% quiere organización de proveedores.  
  33% valoró contar con soporte técnico confiable.

- **Objetivos:**  
  100% busca reducir pérdidas y organizar mejor la gestión.  
  67% tiene como meta abrir un segundo local a mediano plazo.

 Segmento: Cafeterías y Bares (3 entrevistas)

- **Método de gestión de inventario:**  
  El 100% controla insumos manualmente (cuaderno o Excel). Ninguno usa un sistema especializado.

- **Problemas frecuentes:**  
  100% reportó pérdidas por caducidad de perecibles (lácteos y frutas).  
  67% considera Excel tedioso y poco confiable.  
  33% no trabaja con proveedores fijos.

- **Necesidades en un sistema digital:**  
  100% priorizó alertas automáticas de stock bajo.  
  100% quiere reportes en tiempo real.  
  67% pidió cálculo de costos por receta.

- **Perfil tecnológico:**  
  100% usa celular y computadora.  
  Todos manejan Excel, apps y POS, aunque reconocen limitaciones.  
  67% se guía por colegas o redes sociales antes de probar nuevas herramientas.

- **Objetivos:**  
  100% busca reducir desperdicios y mejorar márgenes.  
  67% expresó interés en abrir una segunda sede.

Segmento: Emprendimientos Gastronómicos (3 entrevistas)

- **Método de gestión de inventario:**  
  El 100% usa Excel o control manual. Ninguno cuenta con sistemas especializados.

- **Motivación para emprender:**  
  67% inició por pasión por la gastronomía.  
  33% lo hizo al identificar una oportunidad de mercado en su zona.

- **Problemas frecuentes:**  
  100% reconoció que Excel es limitado (sin reportes ni alertas).  
  67% mencionó pérdidas o ineficiencia en insumos.  
  33% pidió mayor visualización gráfica de datos.

- **Necesidades en un sistema digital:**  
  100% resaltó que sea sencillo y fácil de usar.  
  67% pidió reportes claros de costos y rentabilidad.  
  33% enfatizó la importancia de gráficos accesibles.

- **Perfil personal y tecnológico:**  
  100% usa el celular como dispositivo principal.  
  67% combina con PC para cuentas y reportes.  
  67% se apoya en recomendaciones de colegas o referentes.

- **Objetivos:**  
  100% busca digitalizar procesos.  
  67% quiere crecer o expandirse (nuevo local o canales digitales).  
  33% prefiere mantenerlo como hobby.

### 2.3. Needfinding

### 2.3.1. User Personas

Estas representaciones semi-ficticias de clientes ideales ayudan a comprender las necesidades, deseos, comportamientos de nuestros segmentos de usuario. A través de las fichas de User Persona, podremos comprender mejor a estos usuarios y orientar el diseño de nuestra plataforma para satisfacer sus necesidades.

Segmento objetivo: Restaurantes y Restobares


![User Diego](assets/user3.png)

Segmento objetivo: Cafeterías y Bares


![User Maria Alejandra](assets/user2.png)

Segmento objetivo: Emprendimientos gastronómicos


![User Javier](assets/user1.png)

### 2.3.2. User Task Matrix
## User Task Matrix  

En esta sección se presentan las tareas que realizan los **User Personas** de los tres segmentos objetivo:  
- **Diego Fernández Valdivia** (Restobares y Restaurantes).  
- **María Alejandra Pérez Alvarado** (Cafeterías y Bares).  
- **Javier Ramírez Soto** (Emprendimientos Gastronómicos).  

Las tareas corresponden a actividades necesarias para el funcionamiento de sus negocios, independientemente de la existencia de soluciones digitales.  

### Cuadro de User Task Matrix  

| **Tareas** | **Diego Fernández**<br>(Restobares y Restaurantes)<br>Frecuencia | **Diego Fernández**<br>Importancia | **María Alejandra**<br>(Cafeterías y Bares)<br>Frecuencia | **María Alejandra**<br>Importancia | **Javier Ramírez**<br>(Emprendimientos Gastronómicos)<br>Frecuencia | **Javier Ramírez**<br>Importancia |
|------------|-------------------------------------------------|-------------------------------|-------------------------------------------------|-------------------------------|---------------------------------------------------|-----------------------------------|
| Gestionar inventario de insumos | Alta | Alta | Alta | Alta | Alta | Alta |
| Coordinar pedidos con proveedores | Alta | Alta | Media | Alta | Alta | Alta |
| Controlar costos y rentabilidad de productos | Alta | Alta | Media | Alta | Alta | Alta |
| Estandarizar recetas y procesos | Media | Alta | Alta | Alta | Media | Alta |
| Evitar quiebres de stock | Alta | Alta | Alta | Alta | Alta | Alta |
| Gestionar la rotación de productos perecibles | Alta | Alta | Alta | Alta | Media | Alta |
| Proyectar compras según demanda | Media | Alta | Media | Alta | Media | Alta |
| Monitorear ventas diarias y márgenes | Alta | Alta | Media | Media | Alta | Alta |
| Organizar la apertura y operación diaria | Alta | Alta | Alta | Alta | Alta | Alta |
| Planificar crecimiento del negocio | Media | Alta | Baja | Media | Alta | Alta |

### Explicación de las tareas principales  

- **Gestionar inventario de insumos:** Evitar sobrecompras, pérdidas y garantizar disponibilidad de productos críticos.  
- **Coordinar pedidos con proveedores:** Mantener abastecimiento constante y evitar retrasos.  
- **Controlar costos y rentabilidad:** Detectar platos o productos más rentables y ajustar la oferta.  
- **Estandarizar recetas y procesos:** Asegurar consistencia y calidad en el servicio.  
- **Evitar quiebres de stock:** Prevenir quiebres en horarios pico que afectan ventas y experiencia del cliente.  
- **Gestionar rotación de perecibles:** Reducir pérdidas por caducidad y asegurar frescura.  
- **Proyectar compras según demanda:** Anticiparse a temporadas y eventos especiales.  
- **Monitorear ventas diarias y márgenes:** Dar visibilidad sobre ingresos y costos en tiempo real.  
- **Organizar operación diaria:** Garantizar orden, eficiencia y consistencia en cada jornada.  
- **Planificar crecimiento del negocio:** Especialmente crítico en emprendimientos que buscan sostenibilidad y escalabilidad.  


### 2.3.3. User Journey Mapping

En esta parte se muestran los User Journey Maps As-Is de cada User Persona. El objetivo es representar cómo viven actualmente sus procesos, desde la planificación hasta la evaluación, señalando sus acciones, emociones, puntos de contacto y principales problemas. Estos mapas reflejan la situación real sin una solución implementada y ayudan a entender mejor las necesidades de los usuarios, sirviendo como base para proponer mejoras en el futuro.

**Segmento objetivo: Restobares y Restaurantes**


![User Diego](assets/journey1.png)

**Segmento objetivo: Cafeterías y Bares**


![User Maria Alejandra](assets/journey2.png)

**Segmento objetivo: Emprendimientos Gastronómicos**


![User Javier](assets/journey3.png)

### 2.3.4. Empathy Mapping

**Segmento objetivo: Restaurantes y Restobares**


![User Diego](assets/empathy1.png)

**Segmento objetivo: Cafeterías y Bares**


![User Maria Alejandra](assets/empathy2.png)

**Segmento objetivo: Emprendimientos gastronómicos**


![User Javier](assets/empathy3.png)

### 2.4. Big Picture Event Storming

En esta sección se presenta el Big Picture Event Storming realizado por el equipo. Esta dinámica colaborativa permitió mapear de manera visual el dominio del negocio gastronómico, identificando los eventos clave, los comandos que los disparan, los actores involucrados, las políticas vigentes, así como los hostpots y las oportunidades de mejora.

![Event Storming](assets/storming.png)

### 2.5. Ubiquitous Language

**Inventory (Inventario):** Son todos los insumos y productos que el negocio tiene guardados y listos para usarse en la operación diaria.

**Stock Out (Quiebre de Stock):** Cuando un insumo se acaba y ya no se puede preparar una receta o atender un pedido.

**Overstock (Sobrestock):** Tener más insumos de los necesarios, lo que termina generando caducidad, desperdicios o dinero inmovilizado.

**Waste (Desperdicio):** Pérdida de productos por mala gestión, porque se vencieron o se usaron de manera ineficiente.

**Supplier (Proveedor):** Persona o empresa que entrega los insumos o materias primas al negocio.

**Order (Pedido):** Solicitud que hace el negocio a un proveedor para asegurarse de que no falten productos.

**Recipe (Receta):** Lista detallada de ingredientes y cantidades necesarias para preparar un plato o bebida de manera estándar.

**Menu Item (Plato del Menú):** El producto final que aparece en la carta y que llega al cliente.

**Consumption (Consumo):** El uso real de los insumos durante la preparación de platos en la jornada.

**Expiration (Caducidad):** Fecha límite en la que un insumo puede usarse con seguridad antes de que se eche a perder.

**Cost of Goods Sold – COGS (Costo de Ventas):** Es el valor de todos los insumos utilizados para preparar los productos vendidos.

**Profit Margin (Margen de Ganancia):** Lo que queda de diferencia entre el precio de venta de un plato y lo que costó prepararlo.

**Sales Report (Reporte de Ventas):** Resumen de todas las ventas realizadas en un periodo de tiempo.

**User Role (Rol de Usuario):** El tipo de acceso o funciones que tiene cada persona dentro del sistema (administrador, cajero, mozo, cocinero, etc.).

**Purchase Forecast (Proyección de Compras):** Una estimación de los insumos que se van a necesitar en el futuro, calculada a partir del historial de consumo.

**Reorder Point (Punto de Reorden):** El nivel mínimo de inventario a partir del cual se genera automáticamente un nuevo pedido.

**Service Continuity (Continuidad del Servicio):** La capacidad del negocio de operar sin interrupciones y sin quedarse sin insumos.

**Customer Satisfaction (Satisfacción del Cliente):** La percepción positiva de los clientes sobre la calidad del servicio, la atención y la disponibilidad de productos.

**Digital Report (Reporte Digital):** Documento que genera automáticamente el sistema con datos de consumo, costos y ventas.

**Alert Notification (Notificación de Alerta):** Aviso automático que manda el sistema cuando un insumo está a punto de agotarse.

# Capítulo III: Especificación de Requisitos

## 3.1. Historias de Usuario

A continuación, se presentan las Épicas e Historias de Usuario que definen los requisitos funcionales de la solución "LogisPe". Estos artefactos se han derivado del análisis de las entrevistas y de las necesidades identificadas en los segmentos objetivo, como la necesidad de un control preciso del stock y la optimización de costos. Las historias se agrupan en Épicas para organizar las funcionalidades de alto nivel y se detallan en Historias de Usuario específicas que guiarán el desarrollo de manera incremental.

Cada historia de usuario incluye Criterios de Aceptación redactados en formato Gherkin (Given-When-Then), como lo exige el enunciado, para asegurar que los requisitos sean comprobables y no dejen lugar a ambigüedades. Se han incluido historias para la aplicación principal, la Landing Page (con el rol de "Visitante") y Technical Stories para el desarrollo del backend (con el rol de "Developer").

### Epic Stories

| Epic ID | Título | Descripción | Criterios de Aceptación Generales |
| :--- | :--- | :--- | :--- |
| EP-01 | Gestión de Autenticación y Cuentas | Proporcionar un sistema seguro para el registro, inicio de sesión y gestión de perfiles de usuario y roles dentro de la empresa. | - El sistema debe permitir el registro de nuevas empresas validando su información fiscal.<br>- Se deben poder crear y asignar roles con diferentes niveles de permiso (ej. Administrador, Cocinero).<br>- Un usuario debe poder iniciar y cerrar sesión de forma segura y gestionar su perfil. |
| EP-02 | Administración del Inventario | Permitir a los usuarios registrar, visualizar, auditar y gestionar todos los insumos y productos del inventario en tiempo real. | - Se deben poder crear, editar, buscar y eliminar productos e insumos.<br>- El stock debe actualizarse automáticamente con las ventas, compras y mermas.<br>- El sistema debe mostrar el estado del inventario (disponible, bajo, agotado) y un historial de movimientos. |
| EP-03 | Gestión de Recetas y Costos | Facilitar la creación y administración de recetas, vinculando los insumos del inventario para calcular costos, estandarizar la producción y gestionar la rentabilidad. | - Se deben poder crear recetas asociando insumos y cantidades exactas.<br>- El costo de cada plato debe calcularse automáticamente basado en el costo de los insumos.<br>- Al registrar una venta de un plato, el stock de los insumos de la receta debe descontarse automáticamente. |
| EP-04 | Gestión de Proveedores y Compras | Centralizar la información de los proveedores y agilizar el proceso de creación, seguimiento y registro de órdenes de compra para reabastecer el inventario. | - Se debe poder registrar, editar y gestionar una lista de proveedores con sus datos de contacto y productos.<br>- El sistema debe permitir generar y enviar órdenes de compra a los proveedores.<br>- El estado de las órdenes de compra debe ser rastreable (pendiente, recibido, cancelado). |
| EP-05 | Generación de Alertas y Reportes | Proveer notificaciones automáticas y reportes analíticos para optimizar la toma de decisiones, prevenir problemas operativos y analizar el rendimiento del negocio. | - El sistema debe generar alertas personalizables de stock bajo y fechas de caducidad próximas.<br>- Se deben poder generar reportes detallados de consumo, ventas, costos y mermas.<br>- Los reportes deben ser visuales (gráficos) y exportables a formatos comunes (CSV/PDF). |
| EP-06 | Presentación y Captación (Landing Page) | Ofrecer un sitio web informativo y persuasivo que presente la propuesta de valor de LogisPe, sus características y planes, y guíe a los potenciales clientes al registro. | - La página debe describir claramente los beneficios y características de la solución.<br>- Debe contener llamados a la acción (CTA) claros y visibles para registrarse o solicitar una demo.<br>- Debe ser visualmente atractiva, profesional y completamente adaptable a dispositivos móviles. |

### User Stories

| User Story ID | Título | Descripción | Criterios de Aceptación (Gherkin) | Relacionado con (Epic ID) |
| :--- | :--- | :--- | :--- | :--- |
| **_User Stories para la Aplicación Web_** |
| US-01.01 | Registro de Nueva Empresa | Como **administrador de un restaurante**, quiero registrar mi negocio en la plataforma para empezar a gestionar mi inventario de forma digital. | **Dado** que soy un nuevo usuario y no tengo una cuenta,<br>**Cuando** completo el formulario de registro con datos válidos (RUC, nombre del negocio, email, contraseña),<br>**Entonces** el sistema crea mi cuenta, me asigna el rol de administrador y me envía un correo de bienvenida. | EP-01 |
| US-01.02 | Inicio de Sesión Seguro | Como **usuario registrado**, quiero iniciar sesión con mi correo y contraseña para acceder al dashboard de mi negocio de forma segura. | **Dado** que tengo una cuenta activa y estoy en la página de login,<br>**Cuando** ingreso mis credenciales correctas,<br>**Entonces** soy redirigido al panel principal de la aplicación. | EP-01 |
| US-01.03 | Gestión de Roles de Usuario | Como **administrador**, quiero asignar roles (ej. Cocinero, Almacenero) a los miembros de mi equipo para controlar su acceso a diferentes módulos y proteger la información sensible. | **Dado** que estoy en la sección de "Administración de Usuarios",<br>**Cuando** selecciono un usuario existente y le asigno el rol "Cocinero",<br>**Entonces** ese usuario solo podrá ver y utilizar los módulos de "Recetas" e "Inventario", pero no "Reportes Financieros". | EP-01 |
| US-02.01 | Añadir Nuevo Insumo | Como **administrador**, quiero añadir un nuevo insumo a mi inventario con su nombre, unidad de medida, proveedor y stock inicial para tener un control preciso. | **Dado** que estoy en la vista de "Inventario",<br>**Cuando** hago clic en "Añadir Insumo" y lleno el formulario (ej. "Harina Preparada", "Kg", "Proveedor A", 50),<br>**Entonces** el insumo aparece en mi lista de inventario con el stock y proveedor indicados. | EP-02 |
| US-02.02 | Actualizar Stock Manualmente | Como **almacenero**, quiero poder ajustar manualmente la cantidad de un insumo para corregir discrepancias después de un conteo físico. | **Dado** que el sistema muestra 20 Kg de "Azúcar" pero el conteo físico es de 18 Kg,<br>**Cuando** selecciono "Ajustar Stock", ingreso la nueva cantidad (18) y un motivo (ej. "Merma"),<br>**Entonces** el stock del insumo se actualiza a 18 Kg y se registra un movimiento en el historial. | EP-02 |
| US-02.03 | Búsqueda y Filtro de Insumos | Como **cocinero**, quiero buscar y filtrar insumos por nombre o categoría para encontrar rápidamente lo que necesito para mis preparaciones. | **Dado** que estoy en la pantalla de "Inventario" con más de 100 insumos,<br>**Cuando** escribo "Leche" en la barra de búsqueda y selecciono el filtro "Lácteos",<br>**Entonces** la lista se reduce para mostrar solo las leches de la categoría "Lácteos". | EP-02 |
| US-03.01 | Crear una Receta | Como **administrador**, quiero crear una receta para un plato del menú, especificando los insumos y las cantidades necesarias para estandarizar la producción y controlar costos. | **Dado** que tengo insumos registrados en el inventario,<br>**Cuando** creo una nueva receta (ej. "Lomo Saltado") y asocio los insumos (ej. 200g de Lomo, 100g de Cebolla),<br>**Entonces** la receta queda guardada y el costo del plato se calcula automáticamente. | EP-03 |
| US-04.01 | Registrar un Proveedor | Como **administrador**, quiero registrar los datos de mis proveedores (nombre, contacto, RUC) para tener un directorio centralizado y agilizar las compras. | **Dado** que estoy en el módulo de "Proveedores",<br>**Cuando** completo el formulario con la información de un nuevo proveedor,<br>**Entonces** el proveedor se añade a mi lista de contactos y puedo asociarle insumos. | EP-04 |
| US-04.02 | Generar Orden de Compra | Como **administrador**, quiero generar una orden de compra para un proveedor específico, seleccionando los insumos y cantidades que necesito reponer. | **Dado** que he recibido una alerta de stock bajo para "Aceite",<br>**Cuando** voy a "Órdenes de Compra", selecciono "Proveedor B" y añado 10 litros de "Aceite",<br>**Entonces** se genera una orden de compra en estado "Pendiente" y puedo enviarla al proveedor. | EP-04 |
| US-05.01 | Alerta de Stock Bajo | Como **administrador**, quiero recibir una notificación cuando el stock de un insumo llegue a un nivel mínimo predefinido para poder reabastecer a tiempo y evitar quiebres de stock. | **Dado** que el punto de reorden para "Tomates" es de 5 Kg,<br>**Cuando** el stock actual baja a 4.5 Kg debido a una venta,<br>**Entonces** recibo una alerta visual en el dashboard y un correo electrónico notificándome. | EP-05 |
| US-05.02 | Generar Reporte de Consumo | Como **dueño del negocio**, quiero generar un reporte de consumo de insumos por rango de fechas para analizar cuáles son los más utilizados y planificar mejor mis compras. | **Dado** que he registrado ventas durante la última semana,<br>**Cuando** voy a "Reportes", selecciono "Consumo de Insumos" y el rango de fechas,<br>**Entonces** el sistema me muestra un gráfico y una tabla con los insumos más consumidos, y me permite exportarlo a CSV. | EP-05 |
| **_Technical Stories_** |
| TS-02.01 | Obtener Insumos de Inventario | Como **developer**, quiero un endpoint `GET /api/inventory/supplies` para obtener la lista completa de insumos de un negocio, con opción de paginación. | **Dado** que realizo una petición GET autenticada a `/api/inventory/supplies?page=1&limit=20`,<br>**Cuando** la petición es válida,<br>**Entonces** la API debe devolver un objeto JSON con un array de 20 insumos, información de paginación y un código de estado 200 (OK). | EP-02 |
| TS-03.01 | Crear Nueva Receta (API) | Como **developer**, quiero un endpoint `POST /api/recipes` para que la aplicación web pueda crear una nueva receta enviando sus datos en formato JSON. | **Dado** que envío una petición POST a `/api/recipes` con un cuerpo JSON válido (nombre, array de insumos con cantidades),<br>**Cuando** los datos son procesados correctamente,<br>**Entonces** la API debe devolver el objeto de la nueva receta creada con su ID y un código de estado 201 (Created). | EP-03 |
| TS-05.01 | Endpoint de Reporte de Ventas | Como **developer**, quiero un endpoint `GET /api/reports/sales` que acepte parámetros de fecha para generar datos de ventas. | **Dado** que realizo una petición GET autenticada a `/api/reports/sales?startDate=2025-09-01&endDate=2025-09-30`,<br>**Cuando** la petición es válida,<br>**Entonces** la API debe devolver un JSON con el resumen de ventas de ese período y un código de estado 200 (OK). | EP-05 |
| **_User Stories para Landing Page_** |
| LS-06.01 | Ver Propuesta de Valor | Como **visitante y dueño de un restaurante**, quiero entender rápidamente los beneficios principales de LogisPe en la página de inicio para decidir si es la solución que necesito. | **Dado** que ingreso a la página de inicio de LogisPe,<br>**Cuando** observo la sección principal (Hero),<br>**Entonces** puedo leer un titular claro y un subtítulo que resumen la propuesta de valor en menos de 15 segundos. | EP-06 |
| LS-06.02 | Explorar Características | Como **visitante interesado**, quiero navegar a una sección de "Características" para conocer en detalle qué funcionalidades ofrece el sistema. | **Dado** que estoy en la página de inicio,<br>**Cuando** hago clic en el enlace "Características" del menú de navegación,<br>**Entonces** la página se desplaza suavemente hasta la sección que detalla las funcionalidades con texto e imágenes. | EP-06 |
| LS-06.03 | Iniciar Proceso de Registro | Como **visitante convencido**, quiero encontrar fácilmente un botón de "Registrarse" o "Empezar ahora" para crear mi cuenta sin demoras. | **Dado** que estoy en cualquier sección de la landing page,<br>**Cuando** decido que quiero registrarme,<br>**Entonces** puedo ver un botón de llamado a la acción (CTA) claramente visible en la barra de navegación y en el pie de página que me lleva al formulario de registro. | EP-06 |
## 3.2. Impact Mapping

![ImpactMapping](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3546d09e0ce3821addfa7613d37cd1e07d57eaa3/img/Impact%20map%201.png)

## 3.3. Product Backlog

El **Product Backlog** es una lista ordenada y priorizada de todo el trabajo pendiente para el proyecto "LogisPe". Las Historias de Usuario se han estimado utilizando **Story Points** (siguiendo la secuencia 1, 2, 3, 5, 8) y se han organizado en función del **valor que aportan al negocio** y al usuario final. La priorización busca entregar las funcionalidades más críticas y de mayor impacto en las primeras iteraciones. Se han incluido las historias de la **Landing Page** al inicio, ya que son cruciales para la captación de clientes, seguidas por las funcionalidades centrales de la aplicación que resuelven los problemas más urgentes identificados en la fase de investigación.

***

| #Orden | User Story ID | Título | Descripción (resumen) | Story Points |
| :--- | :--- | :--- | :--- | :--- |
| 1 | LS-06.01 | Ver Propuesta de Valor | Como visitante, quiero entender los beneficios de LogisPe en la página de inicio. | 2 |
| 2 | US-02.02 | Visualizar Stock en Tiempo Real | Como cocinero, quiero ver la lista de insumos con su cantidad disponible. | 5 |
| 3 | US-02.01 | Añadir Nuevo Insumo | Como administrador, quiero añadir un nuevo insumo a mi inventario con su stock inicial. | 3 |
| 4 | US-03.01 | Crear una Receta | Como administrador, quiero crear una receta especificando insumos y cantidades. | 5 |
| 5 | US-05.01 | Alerta de Stock Bajo | Como administrador, quiero recibir una notificación cuando el stock de un insumo esté bajo. | 3 |
| 6 | US-05.02 | Generar Reporte de Consumo | Como dueño, quiero generar un reporte de consumo de insumos por rango de fechas. | 5 |
| 7 | US-02.03 | Búsqueda y Filtro de Insumos | Como cocinero, quiero buscar y filtrar insumos por nombre o categoría. | 3 |
| 8 | LS-06.02 | Explorar Características | Como visitante, quiero navegar a una sección de "Características" en la Landing Page. | 1 |
| 9 | US-01.01 | Registro de Nueva Empresa | Como administrador, quiero registrar mi negocio en la plataforma. | 3 |
| 10 | LS-06.03 | Iniciar Proceso de Registro | Como visitante, quiero encontrar fácilmente un botón para registrarme. | 1 |
| 11 | US-04.01 | Registrar un Proveedor | Como administrador, quiero registrar los datos de mis proveedores. | 2 |
| 12 | US-01.02 | Inicio de Sesión Seguro | Como usuario registrado, quiero iniciar sesión con mi correo y contraseña. | 2 |
| 13 | US-04.02 | Generar Orden de Compra | Como administrador, quiero generar una orden de compra para un proveedor. | 3 |
| 14 | US-02.04 | Registrar Merma o Desperdicio | Como almacenero, quiero registrar la pérdida de un insumo para mantener el stock exacto. | 3 |
| 15 | US-03.02 | Calcular Costo de Receta | Como administrador, quiero que el sistema calcule el costo de una receta automáticamente. | 3 |
| 16 | US-02.05 | Ver Historial de Movimientos | Como administrador, quiero ver el historial de movimientos de un insumo (compras, ventas, mermas). | 5 |
| 17 | US-05.03 | Reporte de Rentabilidad por Plato | Como dueño, quiero un reporte que muestre la rentabilidad de cada plato del menú. | 8 |
| 18 | US-04.03 | Registrar Recepción de Compra | Como almacenero, quiero marcar una orden de compra como "Recibida" para que el stock se actualice. | 3 |
| 19 | US-02.06 | Asignar Categorías a Insumos | Como administrador, quiero poder crear y asignar categorías a mis insumos (ej. Lácteos, Carnes). | 2 |
| 20 | US-01.03 | Gestión de Roles de Usuario | Como administrador, quiero asignar roles (Cocinero, Almacenero) a los miembros de mi equipo. | 3 |
| 21 | US-05.04 | Exportar Reportes a PDF/CSV | Como administrador, quiero exportar cualquier reporte en formato PDF o CSV. | 3 |
| 22 | US-03.03 | Editar una Receta Existente | Como administrador, quiero poder editar los ingredientes o cantidades de una receta ya creada. | 2 |
| 23 | US-04.04 | Directorio de Proveedores | Como administrador, quiero tener una vista de todos mis proveedores con sus datos de contacto. | 2 |
| 24 | US-01.04 | Editar Perfil de Usuario | Como usuario, quiero poder cambiar mi nombre y contraseña en mi perfil. | 2 |
| 25 | US-05.05 | Dashboard Principal con KPIs | Como administrador, quiero ver un dashboard con indicadores clave al iniciar sesión. | 8 |
| 26 | US-02.07 | Alerta de Caducidad Próxima | Como almacenero, quiero recibir alertas sobre insumos que están por vencer. | 5 |
| 27 | US-04.05 | Ver Historial de Compras | Como administrador, quiero ver un historial de todas las órdenes de compra realizadas a un proveedor. | 3 |
| 28 | US-05.06 | Reporte de Mermas | Como dueño, quiero un reporte que me muestre las mermas por insumo en un período. | 5 |


# Capítulo IV: Product Design

## 4.1. Style Guidelines

Las guías de estilo son fundamentales para asegurar una comunicación clara, coherente y profesional en todos los aspectos del proyecto. En esta sección, definiremos las pautas que el equipo utilizará para diseñar la aplicación FinTeka. Estas directrices abarcarán aspectos como la selección de colores, tipografía y la estructura general del diseño.

Para el desarrollo de LogisPE, utilizaremos plataformas como Figma para crear la interfaz web y la página de inicio.  La paleta de colores estará compuesta por tonos blancos y rojos, que transmiten modernidad, confianza y accesibilidad, reflejando el objetivo de la aplicación de conectar a los usuarios con asesores profesionales de manera eficiente y amigable. 

A continuación, se detallan los aspectos clave de este enfoque de diseño.

### 4.1.1. General Style Guidelines

#### Brading

#### Branding Overview:

LogisPE es una plataforma innovadora dedicada a la gestión de inventarios en empresas pequeñas y medianas del sector gastronómico, con un enfoque inicial en restobares y restaurantes. La solución permite controlar en tiempo real el stock de productos e insumos, generar alertas automáticas cuando los niveles bajan, gestionar proveedores y recetas y crear reportes detallados que facilitan la toma decisiones.

#### Misión:

La misión de LogisPE es brindar a pequeñas y medianas empresas un sistema de gestión de inventario eficiente, accesible y seguro que optimice el control de productos, insumos y proveedores, facilitando la toma de decisiones en tiempo real.

#### Visión:

Nuestra visión es la de convertirse en la aplicación de referencia para la gestión de inventarios en el sector gastronómico y de servicios, reconocida por su confiabilidad, usabilidad y capacidad de adaptación a las necesidades del cliente.

#### Brand name:

El nombre de nuestro producto es LogisPe, que da a entender el apoyo en la logistica a nivel nacional que brindamos en forma de un aplicativo web.

#### Logo:

![Logo](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/8019c2c2143e92d4dc2cf3df187b961bc4f659e6/img/Logo.png) 

#### Colores:

![Colores](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/d2ce0581baefc71e19b27c35feb30d953e33fe81/img/Colores.png)

#### Tipografía:

La tipografía organiza el lenguaje visual de las plataformas, garantizando legibilidad y mejorando la experiencia del usuario. Por eso, se eligieron estos tipos de letra:

![Tipografia](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/085181a7ae5a87ce9ac8350bb00f2a32fa7df4d5/img/Tipografia.png)

#### Espaciado:

![Espaciado](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/b8a51503dcb87c07f8857bd821b06027d8758718/img/Espaciado.png)

### 4.1.2. Web Style Guidelines

#### Elementos Visuales (Imágenes)

La aplicación web incorporará una variedad de imágenes con diferentes propósitos. Estas pueden ir desde íconos funcionales dentro de un menú hasta fotografías como la imagen de perfil del usuario. Cada imagen se seleccionará o diseñará en función de su contexto y objetivo específico dentro de la interfaz.

#### Botones

Los botones serán un elemento clave para facilitar la interacción del usuario con la aplicación. Su diseño seguirá las pautas definidas en el apartado de General Style Guidelines y deberán ser claramente distinguibles del resto de los elementos gráficos. Estarán presentes a lo largo de toda la aplicación, ya sea al final de formularios o como parte de opciones dentro de menús.

#### Formularios

Se integrarán formularios en diversas secciones de la aplicación, como las páginas de inicio de sesión, registro de usuarios, carga de documentos, entre otras. La implementación de estos formularios se adaptará al perfil del usuario, considerando tanto a desarrolladores principiantes como a desarrolladores con mayor experiencia.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

Dominios y entidades: Usuarios (Login, Register, Perfil), Inventario (Productos, Stock disponible, Recetas, Insumos), Proveedores, Órdenes, Analítica (Dashboard/Home).

Estructura jerárquica (top-level → subniveles):

Público: Home (landing), Login, Register.

Privado (app): Home/Dashboard, Stock (/app/stock), Orders (/app/orders), Recipes & Supplies (/app/recipes, /app/supplies), Suppliers (/app/suppliers), Products (/app/products, …/new, …/:id), Profile (/app/profile).

Flujos por tarea: Alta de producto → asignar receta/insumos → actualizar stock; Reabastecimiento (low stock) → orden a proveedor → recepción → stock ↑; Gestión de pedidos → filtrar → detalle → actualizar estado.

Acceso y permisos: rutas públicas vs. privadas; roles (Administrador / Operador / Lectura) para crear/editar/eliminar y ver reportes.

### 4.2.2. Labeling Systems

Principios: lenguaje claro y consistente; singular para detalle y plural para listados; verbos en botones; evitar jerga.

Menú/navegación: Home, Stock, Orders, Recipes, Supplies, Suppliers, Products, Add Product, Profile, Logout.

Columnas comunes: SKU, Name, Category, Qty/Unit, Cost, Status, Updated, Supplier, Actions.

CTAs: Add Product, New Order, Save, Cancel, Edit, Delete, Export CSV, Restock.

Mensajes del sistema: vacíos (“No results”), validaciones (“SKU is required”), confirmaciones (“Order created”), errores (“Network error, try again”).

### 4.2.3. SEO Tags and Meta Tags

<.title>LogisPe — Inventory & Orders</title> <br>
<.meta name="description" content="Controla stock, órdenes, recetas e insumos en un solo lugar."> <br>
<.link rel="canonical" href="https://example.com/"> <br>
<.meta property="og:title" content="LogisPe — Inventory & Orders"> <br>
<.meta property="og:description" content="Dashboard para inventario, órdenes y proveedores."> <br>
<.meta property="og:image" content="https://example.com/og-cover.jpg"> <br>
<.meta name="twitter:card" content="summary_large_image">

### 4.2.4. Searching Systems

Búsqueda en tablas: input con debounce por Nombre/SKU/Proveedor; coincidencia parcial; normalización de mayúsculas/acentos.

Filtros avanzados: chips por Estado (Active/Low stock/Pending/Shipped), Categoría, Rango de fechas (Orders), Proveedor (Stock/Suppliers).

Orden y paginación: orden por columna con indicador; paginación server-side para grandes volúmenes.

Vistas guardadas: Low stock, Pending orders, Recently updated.

Acciones del resultado: exportación (CSV/Excel) y selección múltiple (acciones en lote).

Búsqueda global (opcional): atajo Ctrl/⌘+K para abrir Productos/Órdenes/Proveedores y saltar al detalle.

### 4.2.5. Navigation Systems

Navegación global: sidebar persistente con módulos; topbar con búsqueda, notificaciones y menú de usuario (Perfil/Logout).

Navegación local: subpestañas o filtros contextuales (Orders: All, Pending, Shipped; Stock: All, Low stock).

Breadcrumbs: p. ej., Suppliers / Acme Co. / Edit para contexto y retorno.

Navegación contextual: enlaces cruzados (desde Low stock → Create purchase order; desde Supplier → View related products).

Detalle/formularios: “Back to list”, confirmación al salir si hay cambios no guardados; autosave opcional.

Paginación y densidad: controles al pie; selector de filas por página y densidad (compacta/normal).

Responsive y accesibilidad: sidebar colapsable en móvil; foco visible; navegación con teclado; roles/ARIA; contraste adecuado.

Estados vacíos/errores: empty states con CTA (“Add Product”) y páginas 404/403 coherentes con el layout.

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

#### Home Wireframe
![HomeWire](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/1df5990c649a1b943b4887bb3cc0602ef80233a2/img/Home.png)

#### About Us Wireframe
![AboutWire](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/1df5990c649a1b943b4887bb3cc0602ef80233a2/img/About%20Us.png)

#### Learn More Wireframe
![LearnWire](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3318f6cc03d43b461e49812ba0d4a35e36f54dd0/img/Learn%20More%20(1).png)

#### Suscribe Wireframe
![SuscribeWire](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/1df5990c649a1b943b4887bb3cc0602ef80233a2/img/Suscribe.png)

### 4.3.2. Landing Page Mock-up.

#### Home Mockup
![HomeMock](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/81b84572f012bedd2317112c906194b44749f84d/img/Home-Mock.png)

#### About Us Mockup
![AboutMock](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/81b84572f012bedd2317112c906194b44749f84d/img/About%20Us-Mock.png)

#### Learn More Mockup
![LearnMock](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/1af882d5cda949db5c95359f0f13c7526159dfcf/img/Learn%20More-Mock%20(1).png)

#### Suscribe Mockup
![SuscribeMock](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/fc4a24d36073a8a6abfd9bf86a2dce9bd6500d08/img/Suscribe-Mock.png)

#### Login Mockup
![LoginMock](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/1af882d5cda949db5c95359f0f13c7526159dfcf/img/Login.png)

#### Register Mockup
![RegisterMock](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/fc4a24d36073a8a6abfd9bf86a2dce9bd6500d08/img/Register.png)

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

#### Login & Register
![Login & Register](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/83517cef8527291ea7835754ae2cbfac76b5c835/img/Login%26Register-Wireframe.png)

#### Home
![Home](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/eb97c396e85fb5bc03f3d514a19c6784de33502f/img/Home-Wireframe.png)

#### Stock Available and Additional
![Stock Available](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/7713b639bbb5707dc606739e29b82dd32f45e4d0/img/Stock%20Avaible%20-%20Wireframe.png)  
![Add Product](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/7713b639bbb5707dc606739e29b82dd32f45e4d0/img/Add%20Product%20-%20Wireframe.png)  
![Product Info](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/7713b639bbb5707dc606739e29b82dd32f45e4d0/img/Product%20Info%20-%20Wireframe.png)

#### Orders
![Orders 1](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/10e40a8cf6508dad9eaf616e4e90e8d653fe5eb7/img/Orders1.png)  
![Orders 2](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/10e40a8cf6508dad9eaf616e4e90e8d653fe5eb7/img/Orders2.png)

#### Recipes and Supplies
![Recipes and Supplies](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/7108cc69e8ccd3f12486043224314ae266343e77/img/Recipes-wireframes.png)

#### Suppliers
![Suppliers 1](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/1a0ff24fd74cc29b94c591844a1b3312b1dc5eee/img/Suppliers1-wireframes.png)  
![Suppliers 2](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/1a0ff24fd74cc29b94c591844a1b3312b1dc5eee/img/Suppliers2-wireframes.png)

### 4.4.2. Web Applications Wireflow Diagrams

![Wireflow](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/dcf6a4c117bbe51a62871c5b6c1d06d8414791ca/img/Wireframe-Wireflow.png)

### 4.4.3. Web Applications Mock-ups

#### Login & Register
![Login Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/49bccf341ee220f79120b36ffbda5ce15cb5b3d0/img/Login-Mockup.png)  
![Register Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/49bccf341ee220f79120b36ffbda5ce15cb5b3d0/img/Register-Mockup.png)

#### Home
![Home Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/b7a531a6aaedea58c4a8871e3679a80e23fcad5d/img/Home-Mockup.png)

#### Stock Available and Additional
![Stock 1 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/f81bbbf90d270efb4f09661050d01fb835f1ad16/img/Stock1-Mockup.png)  
![Stock 2 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/f81bbbf90d270efb4f09661050d01fb835f1ad16/img/Stock2-Mockup.png)  
![Stock 3 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/f81bbbf90d270efb4f09661050d01fb835f1ad16/img/Stock3-Mockup.png)

#### Orders
![Orders 1 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/ca5909c57ab5c2457b49bae1ee27b43aa136ebb3/img/Orders1-Mockup.png)  
![Orders 2 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/ca5909c57ab5c2457b49bae1ee27b43aa136ebb3/img/Orders2-Mockup.png)

#### Recipes and Supplies
![Recipes Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/70dda5bbf48e565740a972c5d1ff249680e0d4ba/img/Recipes-mockup.png)

#### Suppliers
![Suppliers 1 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/70dda5bbf48e565740a972c5d1ff249680e0d4ba/img/Suppliers1-mockup.png)  
![Suppliers 2 Mockup](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/70dda5bbf48e565740a972c5d1ff249680e0d4ba/img/Suppliers2-mockup.png)


### 4.4.4. Web Applications User Flow Diagrams

![UserFlow](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/dcf6a4c117bbe51a62871c5b6c1d06d8414791ca/img/Mockup-Wireflow.png)

## 4.5. Web Applications Prototyping

![WebAppProto](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/b7a531a6aaedea58c4a8871e3679a80e23fcad5d/img/Home-Mockup.png)

Link del Figma: https://www.figma.com/design/IOMF0hdIHOy89ULFA7dwIh/Untitled?node-id=0-1&t=zsc02RRSwG2QXSx6-1

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming
![Design-Level Event Storming](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/ee224d79ad2f1f124403868efac908f8073fad6b/img/Design-Level%20Event%20Storming.png)

### 4.6.2. Software Architecture Context Diagram
![Software Architecture Context Diagram](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/b089bb5d189b011a15d1cf1fd5d447d9c308a36e/img/Software%20Architecture%20Context%20Diagram.png)

### 4.6.3. Software Architecture Container Diagrams
![Software Architecture Container Diagrams](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/b089bb5d189b011a15d1cf1fd5d447d9c308a36e/img/Software%20Architecture%20Container%20Diagrams.png)

### 4.6.4. Software Architecture Components Diagrams
![Software Architecture Components Diagrams](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/b089bb5d189b011a15d1cf1fd5d447d9c308a36e/img/Software%20Architecture%20Components%20Diagrams.png)

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams
![Class Diagrams](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/6ef347df67480f72d3638405cbda9034cdcc5039/img/Diagrama%20de%20Clases.png)

## 4.8. Database Design

### 4.8.1. Database Diagram
![Database Diagram](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/6ef347df67480f72d3638405cbda9034cdcc5039/img/Diagrama%20de%20Base%20de%20Datos.png)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

#### Requirements Management

1. Canva: Es una herramienta de diseño utilizada para realizar los user persona, empathy mapping, Lean UX Canvas, As-is Scenario Mapping y otros elementos importantes más. Esta aplicación está basada en un sistema de diseño simple en el cual puedes mover y editar objetos para lograr el objetivo de diseñar nuestras piezas escenciales de análisis de mercado para nuestra aplicación. Ruta de referencia: https://www.canva.com/es_es/.

2. Figma: Plataforma de elaboración de prototipos y edición gráfica, que usamos principalmente para nuestra Landing Page y Web Application, tanto para los Wireframes y los MockUps, al igual que para nuestros Wireflows Diagrams. Ruta de referencia: https://www.figma.com/.

3. Vertabelo: Plataforma basada en creación, gestión y realización de gráficos para organizar las herencias y dependencias de nuestros programas y/o bases de datos. Como en nuestro caso fue implementada para realizar nuestros Class Diagrams y nuestra Database Diagrams. Ruta de referencia https://vertabelo.com/.

#### Software Devlopment

1. JetBrains WebStorm: Es un entorno de desarrollo integrado (IDE) enfocado en el desarrollo web. Ofrece herramientas que facilitan la prueba del proyecto en diversos navegadores como Chrome, Microsoft Edge, Safari y Mozilla Firefox. El uso de WebStorm aporta un valor agregado al desarrollo, ya que permite visualizar cómo funciona la aplicación en múltiples plataformas y proporciona soporte avanzado para la edición de código en varios lenguajes compatibles. Ruta de Referencia: https://www.jetbrains.com/es-es/webstorm/.

2. HTML5: Lenguaje de marcado utilizado para estructurar y presentar contenido en la web. Es una herramienta fundamental en nuestro proyecto, ya que se emplea para construir la base del contenido de la aplicación. Ruta de Referencia: https://www.w3schools.com/html/.

3. CSS: Conocido como Hojas de Estilo en Cascada (Cascading Style Sheets), este lenguaje trabaja en conjunto con HTML5 para definir el diseño y la presentación visual de la aplicación. Permite personalizar estilos como colores, tipografías y distribución de los elementos. Ruta de Referencia: https://developer.mozilla.org/es/docs/Web/CSS.

4. JavaScript: Lenguaje de programación orientado a objetos e interpretado en el navegador. Se utilizará principalmente para desarrollar la interfaz dinámica de usuario en nuestro proyecto, facilitando la interactividad dentro de la aplicación. Ruta de Referencia: https://developer.mozilla.org/es/docs/Web/JavaScript.

#### Software Deployment

1. Git: Es una herramienta de control de versiones diseñada para mejorar la eficiencia, confiabilidad y compatibilidad en la gestión de versiones de software. Su uso permite a los integrantes del equipo acceder y trabajar con el proyecto desde la línea de comandos, facilitando la colaboración y el seguimiento de cambios en el desarrollo. Ruta de Referencia: https://git-scm.com/.

#### Software Documentation and Project Management

1. GitHub: Es una plataforma que permite alojar proyectos y gestionarlos mediante el control de versiones de Git, utilizando repositorios. Facilita la colaboración en tiempo real entre los miembros del equipo, así como la revisión y seguimiento de los aportes individuales en el desarrollo del proyecto. Ruta de Referencia: https://github.com/.

### 5.1.2. Source Code Management

El proyecto sigue las convenciones del modelo GitFlow como flujo de trabajo para el control de versiones, utilizando GitHub como plataforma central. Se compartirán los enlaces a los repositorios en GitHub correspondientes a la Landing Page, y este mismo enfoque será aplicado de manera consistente en los demás productos del proyecto.

#### Repositorio de GitHub:

- URL para acceder a nuestro reporte en GitHub: https://github.com/Aplicaciones-Web-CodeForge/Report

- URL para acceder nuestro repositorio de Landing Page: https://github.com/Aplicaciones-Web-CodeForge/upc-pre-202520--1asi0729-7468-LogisPe-Landing-Page

### 5.1.3. Source Code Style Guide & Conventions

#### **HTML5**
El Lenguaje de Marcado de Hipertexto (HTML) constituye la base para estructurar el contenido en páginas web. Por convención, el archivo principal de un sitio suele llamarse `index.html`. Algunas buenas prácticas al trabajar con HTML son:

- Usar etiquetas en minúsculas para mantener uniformidad y facilitar la lectura.
- Cerrar correctamente todas las etiquetas, aunque no sea obligatorio en todos los casos, para evitar errores y mejorar la compatibilidad.
- Incluir comentarios breves y claros para documentar el código.
- Evitar líneas de código demasiado extensas y solo usar espacios en blanco cuando sea necesario para una mejor organización visual.
- No omitir elementos esenciales como `<title>`, `<html>`, `<body>`, y `<head>`, ya que son fundamentales para la estructura del documento.
- Agregar el atributo `lang` en la etiqueta `<html>` para definir el idioma del contenido.
- Especificar atributos como `alt`, `width` y `height` en imágenes, para mejorar la accesibilidad y evitar cargas irregulares.
- Evitar dejar espacios innecesarios alrededor de símbolos y signos para mejorar la claridad.
- Incluir siempre la metaetiqueta `<meta name="viewport">` para asegurar una correcta visualización en dispositivos móviles.

#### **CSS (Cascading Style Sheets)**
CSS permite dar estilo y personalizar el diseño visual de los sitios web. Algunas convenciones importantes a seguir al escribir CSS son:

- Usar una nomenclatura coherente para nombres de clases, identificadores y selectores, facilitando la colaboración y el mantenimiento.
- Mantener una indentación uniforme y aplicar espacios en blanco adecuados para mejorar la claridad del código.
- Comentar el código para explicar la lógica detrás de bloques o secciones de estilo.
- Agrupar propiedades relacionadas por bloques para una mejor estructura.
- Evitar selectores excesivamente específicos que puedan generar conflictos en el futuro.
- Utilizar prefijos de proveedores (vendor prefixes) cuando sea necesario para asegurar compatibilidad con todos los navegadores.
- Optimizar el código evitando duplicidades y combinando reglas similares.
- Probar estilos en distintos navegadores y dispositivos para verificar su consistencia visual.
- Validar el código CSS usando herramientas como el validador de W3C para identificar errores.

#### **JavaScript**
JavaScript se usa para incorporar interactividad y comportamiento dinámico en las páginas web. Para mantener un código eficiente y comprensible, se recomienda lo siguiente:

- Mantener una nomenclatura consistente en variables, funciones y objetos.
- Aplicar una indentación clara y utilizar espacios en blanco adecuados, por ejemplo, después de palabras clave como `if`, `for` o `function`.
- Incluir comentarios explicativos que ayuden a entender la lógica de determinadas partes del código.
- Reducir al mínimo el uso de variables globales, favoreciendo los contextos locales.
- Implementar mecanismos de manejo de errores como `try-catch` para evitar fallos inesperados en la ejecución.
- Usar técnicas de optimización como el almacenamiento en caché, minimización y combinación de scripts para mejorar el rendimiento.
- Realizar pruebas cruzadas en varios navegadores y dispositivos para asegurar la correcta funcionalidad del código.

#### **Gherkin**
Gherkin es un lenguaje de texto estructurado utilizado para definir pruebas de comportamiento de forma legible por cualquier miembro del equipo. Algunas pautas clave incluyen:

- Redactar los escenarios de forma clara y sencilla, pensando en la comprensión de todos los roles del equipo.
- Usar una estructura estandarizada en los archivos `.feature` con palabras clave como `Feature`, `Scenario`, `Given`, `When`, `Then` y `And`.
- Ser detallado al describir escenarios, especificando claramente el estado inicial, las acciones realizadas y los resultados esperados.
- Reutilizar pasos comunes con la palabra `And` para evitar repeticiones innecesarias.
- Mantener los escenarios enfocados y sin pasos redundantes o irrelevantes.
- Utilizar comentarios para agregar contexto o aclaraciones adicionales cuando sea necesario.
- Fomentar la colaboración revisando y afinando los escenarios con el equipo para asegurar que estén alineados con los requerimientos funcionales.

### 5.1.4. Software Deployment Configuration

### **Configuraciones de despliegue del proyecto**

Para la puesta en línea de nuestro proyecto, utilizamos GitHub Pages, una plataforma especializada en el alojamiento web y despliegue continuo de aplicaciones y sitios estáticos. Esta herramienta simplifica enormemente el proceso de publicación y actualización de nuestros desarrollos. Su funcionamiento se basa en los siguientes puntos:

- **Integración con repositorios Git**: GitHub Pages se enlaza fácilmente con plataformas como GitHub, GitLab o Bitbucket. Cada vez que actualizamos el código y lo subimos a nuestro repositorio, Netlify detecta los cambios y comienza automáticamente el proceso de construcción del sitio.
- **Compilación automatizada del sitio**: Durante el proceso de build, GitHub Pages transforma el código fuente (HTML, CSS, JavaScript) en una versión optimizada del sitio estático. Además, realiza tareas como la compilación de archivos, minificación y optimización de imágenes.
- **Despliegue en red CDN**: Una vez que la construcción se completa con éxito, el sitio es desplegado a través de una red global de entrega de contenido (CDN), lo que garantiza tiempos de carga rápidos y disponibilidad en cualquier parte del mundo.
- **Vistas previas automáticas por rama**: Por cada rama de trabajo activa o pull request, Netlify genera automáticamente una versión previa del sitio. Esto permite revisar los cambios antes de integrarlos al proyecto principal, favoreciendo el trabajo colaborativo y la detección temprana de errores.
- **Despliegues automáticos continuos**: Cada vez que se fusiona una rama o se realiza un nuevo commit en la rama principal, Netlify actualiza el sitio automáticamente, asegurando que siempre esté reflejando la versión más reciente del código.

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
            15/09/25         
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            20:30         
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad Online - Vía Discord
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Equipo de LogisPe    
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Attendees (to planning meeting)</b>
        </td>
        <td>
            - Javier Murillo, Mathias<br>
            - Aguilar Untiveros, Rodrigo Fabrizio<br>
            - Condori Lozano, Alessandro Ramiro<br>
            - Mejia Aliaga, Katherine Maryory<br>
            - Montes Maza Augusto Sebastian<br>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b> <br>
            <b>Review Summary</b>
        </td>
        <td>
            No existe un sprint anterior para realizar el review, siendo este el primer sprint a desarrollar para PlayMatch.  
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b> <br>
            <b>Retrospective Summary</b>
        </td>
        <td>
            No existe un sprint anterior para realizar una retrospectiva. Sin embargo, en base a lo avanzado debemos considerar como prioridad el correcto desarrollo de las User Stories y una planificación eficiente del Product Backlog.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 1 Goal</b>
        </td>
        <td>
            El objetivo del sprint es construir la landing page de LogisPe con una interfaz moderna, clara e intuitiva, que presente de forma efectiva la propuesta de valor de la aplicación, que es conectar usuarios con profesionales de manera rápida y segura.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            6
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            6
        </td>
    </tr>
</table>

#### 5.2.1.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | Github Username | Diseño, wireframes landing Leader (L), Collaborator (C) | Desarrollo estatico HTML, CSS, JS Leader (L), Collaborator (C) | Desplegar el servicio Leader (L), Collaborator (C) |
| ----------------------------------- | --------------- | ------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------- |
| Mathias Javier Murillo              | K1ngHulk        | (L)                                                     | (L)                                                            | (L)                                                |
| Rodrigo Fabrizio Aguilar Untiveros  | Rodri2712       | (C)                                                     | (C)                                                            | (C)                                                |
| Alessandro Ramiro Condori Lozano    | AlessandroRCL   | (C)                                                     | (C)                                                            | (C)                                                |
| Katherine Maryory Mejia Aliaga      | KathMJ          | (C)                                                     | (C)                                                            | (C)                                                |
| Augusto Sebastian Montes Maza       | asmmaza         | (C)                                                     | (C)                                                            | (C)                                                |

#### 5.2.1.3. Sprint Backlog 1

El objetivo principal del Sprint 1 fue establecer la base del proyecto LogisPe, centrando los esfuerzos en el diseño de la interfaz (UI/UX), la construcción inicial de la landing page, la definición de los Sprints en la herramienta de gestión y el desarrollo de documentación base. También se incluyeron tareas generales como configuración de repositorios y organización del equipo.

A continuación se presenta un screenshot del Board de Sprint 1 en Trello, junto con el enlace público correspondiente:

https://trello.com/invite/b/68cf9b5efdc693c0847bd189/ATTI824e909b5beee840ebf67f032d02795825FBB2F7/sprint-1-logispe

![Sprint Backlog](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/d253bd1316053141e81cd714db15425f7dded346/img/SprintBacklog1-LogisPe.png)

#### 5.2.1.4. Development Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body |  Commited on (Date) |
| ---------- | ------ | --------- | --------- | ------------------- | ------------------- |
|Landing Page|main| 23b653a | Initial commit  | create the README.md  | 16/09/2025 |
|            |main| ac6322f | Create index.html  | create the index.html  | 17/09/2025 |
|            |main| e557e41 | feat: added Section Home | added content in the section Home  | 17/09/2025 |
|            |main| 3dab5df | feat: added assets carpet | create the assets carpet  | 17/09/2025 |
|            |main| 80d023b | feat: added css carpet | create the css carpet  | 17/09/2025 |
|            |main| 5b06e21 | feat: added javascript carpet | create the javascript carpet  | 17/09/2025 |
|            |main| 0a8a575 | feat: added i18n.js file | create the i18n.js file | 17/09/2025 |
|            |main| 6b71c13 | feat: added scripts | added content in the scripts section | 17/09/2025 |

#### 5.2.1.5. Execution Evidence for Sprint Review

Durante el primer sprint, se lograron varios hitos importantes en el desarrollo de la landing page para LogisPe. A continuación, se presenta un resumen de los logros alcanzados:

* Establecimiento de Repositorios: Se crearon y configuraron repositorios en GitHub para gestionar el código y las pruebas.

![Evidence1](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3147c381e69b44457571b18d11fd9eb420501e0d/img/Evidencia1-LogisPe.png)

* Implementación del Landing Page: Se diseñó y desarrolló la página de inicio de LogisPe, implementando funcionalidades clave y asegurando que cumpla con los requisitos del proyecto.
  
  ![Evidence2](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3147c381e69b44457571b18d11fd9eb420501e0d/img/Evidencia2-LogisPe.png)    
  
* Imágenes del Landing Page:
   
  * Inicio:
  
    ![Evidence3](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3147c381e69b44457571b18d11fd9eb420501e0d/img/Evidencia2-LogisPe.png)
    
Estos logros reflejan el avance significativo en la creación de una experiencia de usuario atractiva y funcional para LogisPe.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el primer sprint, se desarrolló el Landing Page del proyecto como una primera entrega visual. Esta implementación se centró únicamente en la estructura y diseño, sin integrar aún servicios web ni funcionalidades conectadas a sistemas externos.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante este Sprint, se realizaron las siguientes actividades en relación con el despliegue de los productos del proyecto, incluyendo la Landing Page.

##### Introducción

Durante este Sprint, se llevaron a cabo las siguientes actividades clave relacionadas con el despliegue:

1. Creación de Repositorios y Configuración en GitHub:  
   * Se crearon repositorios en GitHub para gestionar el código fuente y el seguimiento de cambios. Estos repositorios incluyeron la Landing Page y otros componentes del proyecto.  
   * Se configuraron los repositorios para permitir el despliegue de la Landing Page.
     
2. Configuración del Proceso de Despliegue:  
   * GitHub Pages: Se configuró GitHub Pages para el despliegue de la Landing Page. Este servicio proporciona una manera sencilla de alojar el sitio web directamente desde un repositorio de GitHub.

##### Proceso de Despliegue

A continuación se detallan los pasos realizados durante el Sprint para el despliegue:

1. Despliegue en GitHub Pages:  
   * Se subió el código de la Landing Page al repositorio en GitHub.  
   * Se configuró GitHub Pages en el repositorio para publicar el contenido en la web. El proceso incluyó la configuración del dominio y la personalización de la página de inicio.

2. ![Evidence4](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3147c381e69b44457571b18d11fd9eb420501e0d/img/Evidencia1-LogisPe.png)

3. Verificación del Despliegue:  
   * Se realizó una revisión exhaustiva del sitio web publicado en GitHub Pages para asegurar que todos los elementos de la Landing Page funcionaran correctamente.  
   * Se realizaron pruebas de funcionalidad para verificar que el sitio se cargara correctamente y que no hubiera errores en el contenido desplegado.

4. ![Evidence5](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/3147c381e69b44457571b18d11fd9eb420501e0d/img/Evidencia2-LogisPe.png)

Link del Landing Page: https://aplicaciones-web-codeforge.github.io/upc-pre-202520--1asi0729-7468-LogisPe-Landing-Page/

El proceso de despliegue durante este Sprint ha permitido establecer una base sólida para la gestión y publicación del proyecto. La configuración de GitHub Pages ha optimizado el proceso de despliegue y garantizado una integración continua efectiva, facilitando el despliegue y la actualización del sitio web.

#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante este Sprint, el equipo ha trabajado de manera colaborativa por 2 alumnos en el diseño y programación en la implementación de la Landing Page de LogisPe. A continuación, se presenta un resumen de cómo se han desarrollado las actividades de implementación, junto con capturas de pantalla de los analíticos de colaboración y commits en GitHub realizados por los miembros del equipo.  

| Author           | Task completed                                     |
|------------------|----------------------------------------------------|
| Mathias Javier    | create landing page design with HTML, CSS and JS  |
| Rodrigo Aguilar   | desing landing page wireframes                    |
| Alessandro Condori| desing landing page mockups                       |
| Katherine Mejia   | deploy landing page with Github Pages             |
| Augusto Montes    | support to deploy and fix errors with landing page|

### 5.2.2. Sprint 2

#### 5.2.2.1. Sprint Planning 2

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 2</b>
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
            29/09/2025
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            20:30
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad Online - Vía Discord
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Equipo de LogisPe
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Attendees (to planning meeting)</b>
        </td>
        <td>
            - Javier Murillo, Mathias<br>
            - Aguilar Untiveros, Rodrigo Fabrizio<br>
            - Condori Lozano, Alessandro Ramiro<br>
            - Mejia Aliaga, Katherine Maryory<br>
            - Montes Maza Augusto Sebastian<br>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b> <br>
            <b>Review Summary</b>
        </td>
        <td>
            En el Sprint 1 se completó exitosamente la implementación y el despliegue de la primera versión de la Landing Page. Se validó la propuesta de valor y el diseño visual inicial. El equipo demostró una buena colaboración y dominio de las herramientas de control de versiones.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b> <br>
            <b>Retrospective Summary</b>
        </td>
        <td>
            La retrospectiva del Sprint 1 destacó la fluida comunicación del equipo. Como punto de mejora, se identificó la necesidad de definir los "contratos" de datos (la estructura de la información) antes de iniciar el desarrollo del frontend. Esta decisión fue clave para adoptar el uso de una Fake API en el Sprint 2 y así desacoplar el desarrollo del frontend y backend.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 2 Goal</b>
        </td>
        <td>
            Nuestro objetivo es construir un prototipo funcional de la aplicación web, desarrollando las vistas de autenticación (Login, Register), el Home y las pantallas principales de gestión (Stock, Orders, Recipes, Suppliers), conectándolas a una Fake API. Creemos que esto nos permitirá validar el flujo de navegación principal y la usabilidad de las funcionalidades core. Esto se confirmará cuando un usuario pueda registrarse, iniciar sesión, navegar por todas las vistas implementadas y ver datos de prueba cargados desde la Fake API.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 2 Velocity</b>
        </td>
        <td>
            23
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            23
        </td>
    </tr>
</table>

#### 5.2.2.2. Aspect Leaders and Collaborators

| Team Member (Last Name, First Name) | Github Username | Desarrollo Frontend de Vistas (Vue.js) Leader (L), Collaborator (C) | Configuración de Fake API (JSON Server) Leader (L), Collaborator (C) | Documentación y Corrección de Feedback Leader (L), Collaborator (C) |
|---|---|---|---|---|
| Mathias Javier Murillo | K1ngHulk | (L) | (L) | (C) |
| Rodrigo Fabrizio Aguilar Untiveros | Rodri2712 | (C) | (C) | (C) |
| Alessandro Ramiro Condori Lozano | AlessandroRCL | (C) | (L) | (C) |
| Katherine Maryory Mejia Aliaga | KathMJ | (C) | (C) | (C) |
| Augusto Sebastian Montes Maza | asmmaza | (C) | (C) | (L) |

#### 5.2.2.3. Sprint Backlog 2

El objetivo del Sprint 2 fue materializar los diseños de la aplicación web en componentes funcionales. El equipo se enfocó en desarrollar las pantallas principales (Login, Register, Home, Stock, Orders, Recipes, Suppliers), asegurando una correcta gestión del estado y la interacción con una API simulada (Fake API) que proveyó los datos de prueba.

| Sprint # | Sprint 2 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **User Story** | | | **Work-Item/Task** | | | | |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| US-01.01 | Registro de Nueva Empresa | TSK-01 | Maquetar la vista de Registro (Register) | Crear el componente con los campos de formulario requeridos (RUC, email, etc.). | 6 | Aguilar R. | Done |
| US-01.02 | Inicio de Sesión Seguro | TSK-02 | Maquetar la vista de Inicio de Sesión (Login) | Crear el componente con los campos de email y contraseña. | 5 | Aguilar R. | Done |
| N/A | Configuración de Fake API | TSK-03 | Definir y configurar los endpoints en JSON Server | Crear los archivos JSON con datos de prueba para usuarios, insumos, órdenes, etc. | 8 | Condori A. | Done |
| | | TSK-04 | Implementar la lógica de autenticación simulada | Crear la lógica en el frontend para simular el login/register contra la Fake API. | 6 | Murillo M. | Done |
| US-02.02 | Visualizar Stock en Tiempo Real | TSK-05 | Maquetar la vista "Stock Available" | Desarrollar la tabla principal que listará los insumos del inventario. | 8 | Murillo M. | Done |
| | | TSK-06 | Conectar la vista "Stock Available" a la Fake API | Consumir el endpoint de insumos y renderizar los datos en la tabla. | 5 | Mejia K. | Done |
| N/A | Maquetación Vistas Adicionales | TSK-07 | Desarrollar la vista "Orders" | Crear la interfaz para visualizar el listado de órdenes de compra. | 7 | Aguilar R. | Done |
| | | TSK-08 | Desarrollar la vista "Recipes and Supplies" | Implementar la UI para listar y crear nuevas recetas. | 8 | Mejia K. | Done |
| | | TSK-09 | Desarrollar la vista "Suppliers" | Crear la interfaz para visualizar el directorio de proveedores. | 6 | Condori A. | Done |
| N/A | Documentación y Bugs | TSK-10 | Documentar el uso de los nuevos componentes | Actualizar el informe y el `README` con la descripción de las vistas creadas. | 5 | Montes A. | Done |
| | | TSK-11 | Corregir errores de feedback de TB1 | Aplicar las correcciones observadas en el diseño y la estructura del informe. | 6 | Montes A. | Done |

#### 5.2.2.4. Development Evidence for Sprint Review

![EvidenciaDeploy](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/f23be2e4a69e13a2260b3d9ad4ff7082294b0b21/img/Evidencia-Tp.png)

![EvidenciaDeploy](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/34a172656f49a48ccbf00f602e193f796c5eaf8b/img/Evidencia-Tp1.png)

![EvidenciaDeploy](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/34a172656f49a48ccbf00f602e193f796c5eaf8b/img/Evidencia-Tp2.png)

#### 5.2.2.5. Execution Evidence for Sprint Review

![EvidenciaDeploy](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/f23be2e4a69e13a2260b3d9ad4ff7082294b0b21/img/Evidencia-Tp.png)

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

Durante este sprint, el desarrollo del frontend se basó en una **Fake API** utilizando **JSON Server**. La estructura de los datos y los endpoints simulados (para usuarios, insumos, órdenes, etc.) se documentaron internamente en el repositorio del frontend para guiar el desarrollo. La documentación formal con OpenAPI/Swagger se realizará en sprints posteriores, cuando se construya la API real.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review

![EvidenciaDeploy](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/f23be2e4a69e13a2260b3d9ad4ff7082294b0b21/img/Evidencia-Tp.png)

#### 5.2.2.8. Team Collaboration Insights during Sprint

Durante el Sprint 2, la colaboración se centró en la construcción de las pantallas principales de la aplicación web. El equipo trabajó de manera coordinada para transformar los diseños en componentes de software funcionales, utilizando una API simulada para desacoplar el trabajo.

| Author | Task completed |
|---|---|
| Mathias Javier Murillo | Lideró el desarrollo frontend, implementó la vista "Stock Available" y la lógica de autenticación simulada. |
| Rodrigo Aguilar | Desarrolló las vistas de "Login", "Register" y "Orders", asegurando su correcta funcionalidad. |
| Alessandro Condori | Lideró la configuración de la Fake API con JSON Server, definiendo los datos de prueba. También desarrolló la vista "Suppliers". |
| Katherine Mejia | Implementó la vista de "Recipes and Supplies" y conectó la vista de "Stock" a la Fake API. |
| Augusto Sebastian Montes Maza | Se encargó de la documentación técnica de los nuevos componentes y de la corrección de errores y mejoras basadas en el feedback recibido del TB1. |

![EvidenciaCommits](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/afd1f9ddc5cee4672d4fb7a648a4bcb5bdaf4d8c/img/CommitsTP.png)

Captura de Analíticos de Colaboración en GitHub en el repositorio de la Landing Page:

![Commits](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/fa894917805872b29efd6ce1c30ff914ea3c9679/img/Commits.png)

## 5.2.3. Sprint 3

### 5.2.3.1. Sprint Planning 3

<table align="center" border="1" width="90%" style="text-align:center;">

<tr align="left">
    <td colspan="2"><b>Sprint Planning Background</b></td>
</tr>

<tr align="left">
    <td><b>Date</b></td>
    <td>15/11/2025</td>
</tr>

<tr align="left">
    <td><b>Time</b></td>
    <td>20:30</td>
</tr>

<tr align="left">
    <td><b>Location</b></td>
    <td>Modalidad Online - Vía Discord</td>
</tr>

<tr align="left">
    <td><b>Prepared By</b></td>
    <td>Equipo de LogisPe</td>
</tr>

<tr align="left">
    <td><b>Attendees (to planning meeting)</b></td>
    <td>
        - Javier Murillo, Mathias<br>
        - Aguilar Untiveros, Rodrigo Fabrizio<br>
        - Condori Lozano, Alessandro Ramiro<br>
        - Mejia Aliaga, Katherine Maryory<br>
        - Montes Maza, Augusto Sebastián<br>
    </td>
</tr>

<tr align="left">
    <td><b>Sprint n - 1<br>Review Summary</b></td>
    <td>
        Durante el Sprint 2 se completó la construcción del prototipo funcional del frontend de LogisPe utilizando Vue.js, 
        incluyendo vistas esenciales como Login, Register, Home, Stock, Orders, Recipes y Suppliers, todas conectadas a una Fake API. 
        Este avance permitió validar los flujos principales de navegación y confirmar que la arquitectura del frontend 
        es escalable y coherente con las necesidades del proyecto. El equipo mantuvo un ritmo estable y cumplió el total 
        de puntos planificados.
    </td>
</tr>

<tr align="left">
    <td><b>Sprint n - 1<br>Retrospective Summary</b></td>
    <td>
        En la retrospectiva del Sprint 2 se resaltó la eficiencia del equipo trabajando en paralelo gracias a la Fake API. 
        Sin embargo, se identificó como área de mejora la necesidad de estandarizar la estructura del backend real 
        para evitar bloqueos futuros y asegurar una integración fluida. Se acordó que el Sprint 3 estaría dedicado a 
        formalizar el backend, documentarlo y preparar la base para la conexión real con el frontend.
    </td>
</tr>

<tr align="left">
    <td><b>Sprint 3 Goal</b></td>
    <td>
        El objetivo del Sprint 3 es implementar la arquitectura completa del backend de LogisPe, incluyendo los módulos 
        Inventory, Suppliers y Stores, siguiendo un enfoque por bounded contexts. Se desarrollarán los controladores, 
        servicios, repositorios, entidades, documentación Swagger y la base para integrar este backend con el frontend 
        en sprints posteriores. Este objetivo se considerará cumplido cuando el backend funcione correctamente, exponga 
        endpoints estables, tenga documentación clara y esté desplegado en un entorno de pruebas.
    </td>
</tr>

<tr align="left">
    <td><b>Sprint 3 Velocity</b></td>
    <td>24</td>
</tr>

<tr align="left">
    <td><b>Sum of Story Points</b></td>
    <td>24</td>
</tr>

</table>

### 5.2.3.2. Aspect Leaders and Collaborators

<!-- Igual, un cuadro igual al anterior, con las diferentes tareas realizadas, los miembros del equipo asignados y si son Leader (L) o Collaborator (C) -->
| Team Member (Last Name, First Name) | Github Username | Desarrollo Backend Avanzado (DDD) Leader (L), Collaborator (C) | Integración Frontend–Backend Sprint 3 Leader (L), Collaborator (C) | Entrevistas de Validación y Análisis Leader (L), Collaborator (C) |
| ----------------------------------- | --------------- | ------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------- |
| Mathias Javier Murillo              | K1ngHulk        | (L)                                                     | (L)                                                            | (L)                                                |
| Rodrigo Fabrizio Aguilar Untiveros  | Rodri2712       | (C)                                                     | (C)                                                            | (C)                                                |
| Alessandro Ramiro Condori Lozano    | AlessandroRCL   | (C)                                                     | (C)                                                            | (C)                                                |
| Katherine Maryory Mejia Aliaga      | KathMJ          | (C)                                                     | (C)                                                            | (C)                                                |
| Augusto Sebastian Montes Maza       | asmmaza         | (C)                                                     | (C)                                                            | (C)                                                |
### 5.2.3.3. Sprint Backlog 3

El objetivo del Sprint 3 fue implementar la arquitectura completa del backend de LogisPe, incluyendo los módulos Inventory, Suppliers y Stores, siguiendo un enfoque de bounded contexts. Además, se documentaron los endpoints con Swagger y se preparó el entorno de despliegue para dejar listo el backend para su integración con el frontend en siguientes iteraciones.

| Sprint # | Sprint 3 | | | | | | |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **User Story** | | | **Work-Item/Task** | | | | |
| **Id** | **Title** | **Id** | **Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| US-03.01 | Implementar Módulo Inventory (DDD) | TSK-01 | Crear entidades y Value Objects del módulo Inventory | Implementar entidades Item, Category y StockMovement siguiendo DDD. | 8 | Murillo M. | Done |
| | | TSK-02 | Implementar servicios del módulo Inventory | Crear lógica de dominio para registrar insumos, actualizar stock y registrar movimientos. | 6 | Aguilar R. | Done |
| | | TSK-03 | Crear controladores REST del módulo Inventory | Implementar endpoints CRUD para Items, Categories y Stock Movements. | 5 | Mejia K. | Done |
| US-03.02 | Implementar Módulo Suppliers (DDD) | TSK-04 | Implementar entidades y repositorios de Suppliers | Crear entidades Supplier, ContactInfo y repositorios asociados. | 7 | Condori A. | Done |
| | | TSK-05 | Implementar servicios del módulo Suppliers | Lógica de registro, actualización y búsqueda de proveedores. | 5 | Montes A. | Done |
| | | TSK-06 | Crear controladores REST para Suppliers | Definir endpoints CRUD con validaciones. | 5 | Mejia K. | Done |
| US-03.03 | Implementar Módulo Stores (DDD) | TSK-07 | Crear entidades Store y Warehouse | Implementar estructura de datos para gestionar múltiples almacenes. | 6 | Murillo M. | Done |
| | | TSK-08 | Implementar servicios del módulo Stores | Lógica para creación de tiendas, asignación de inventario y rutas. | 6 | Aguilar R. | Done |
| | | TSK-09 | Controladores REST de Stores | Definir endpoints y validaciones específicas del módulo. | 5 | Condori A. | Done |
| US-03.04 | Documentación Técnica del Backend | TSK-10 | Documentar arquitectura DDD | Redacción de estructura del backend, bounded contexts y flujos. | 4 | Montes A. | Done |
| | | TSK-11 | Implementar Swagger para API | Generar documentación interactiva de todos los endpoints. | 3 | Mejia K. | Done |
| US-03.05 | Preparar Despliegue del Backend | TSK-12 | Configurar entorno Docker para backend | Crear Dockerfile y docker-compose para entorno de pruebas. | 5 | Aguilar R. | Done |
| | | TSK-13 | Deploy en servidor de pruebas | Desplegar backend en Render/Fly.io y validar funcionamiento. | 4 | Murillo M. | Done |
| US-03.06 | Validaciones y Entrevistas Técnicas | TSK-14 | Ajustar backend según feedback del equipo | Resolver bugs, mejorar estructura y normalización. | 4 | Montes A. | Done |
| | | TSK-15 | Realizar entrevistas de validación técnica | Validar arquitectura, endpoints y casos de uso con el equipo. | 3 | Aguilar R. | Done |

### 5.2.3.4. Development Evidence for Sprint Review

![commits](assets/captura1.png)
![commits](assets/captura2.png)
![commits](assets/captura3.png)

### 5.2.3.5. Execution Evidence for Sprint Review

![EvidenciaSwagger](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/327dc3bb1466da1e80ddc1c34e9d5007d6cc114b/img/Swagger.png)

### 5.2.3.6. Services Documentation Evidence for Sprint Review

Durante este sprint, el desarrollo del backend se centró en la implementación de la arquitectura basada en **Domain-Driven Design (DDD)** y la creación de la **API real** de LogisPe. Toda la estructura de endpoints para los módulos Inventory, Suppliers y Stores fue documentada mediante **Swagger/OpenAPI**, permitiendo visualizar, probar y validar cada recurso del sistema.  
La documentación incluye esquemas de datos, ejemplos de request y response, códigos de estado y reglas de validación. Además, se generó documentación interna en el repositorio describiendo los bounded contexts, casos de uso, repositorios y flujo de manejo de errores. Esta documentación sienta las bases para la integración real con el frontend en sprints posteriores.

### 5.2.3.7. Software Deployment Evidence for Sprint Review

- Link de la Landing Page desplegada: https://aplicaciones-web-codeforge.github.io/upc-pre-202520--1asi0729-7468-LogisPe-Landing-Page/
- Link del Frontend desplegado: https://upc-pre-202520-1asi0729-7468-logis.vercel.app/home
- Link del Backend desplegado: https://upc-pre-202520-1asi0729-7468-logispe.onrender.com/docs/#/

### 5.2.3.8. Team Collaboration Insights during Sprint

Durante el Sprint 3, la colaboración se centró en la construcción completa del backend, siguiendo una estructura por bounded contexts. El equipo trabajó de manera coordinada para desarrollar los módulos Inventory, Suppliers y Stores, documentar todos los endpoints con Swagger y preparar el despliegue del backend en un entorno de pruebas. La comunicación continua permitió revisar pull requests, resolver inconsistencias y asegurar estándares comunes entre todos los módulos.

| Author | Task completed |
|---|---|
| Mathias Javier Murillo | Implementó entidades, controladores y despliegue de prueba del módulo Inventory. |
| Rodrigo Aguilar | Implementó servicios clave en los módulos Inventory y Stores, y configuró Docker y despliegue. |
| Alessandro Condori | Implementó entidades, repositorios y endpoints del módulo Suppliers. |
| Katherine Mejia | Implementó controladores, validaciones y documentación Swagger para múltiples módulos. |
| Augusto Sebastian Montes Maza | Documentó la arquitectura DDD, refinó casos de uso y realizó validaciones técnicas internas. |

![EvidenciaCommits](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/afd1f9ddc5cee4672d4fb7a648a4bcb5bdaf4d8c/img/CommitsTP.png)

Captura de Analíticos de Colaboración en GitHub en el repositorio de la Landing Page:

![Commits](https://github.com/Aplicaciones-Web-CodeForge/Report/blob/fa894917805872b29efd6ce1c30ff914ea3c9679/img/Commits.png)


Captura de Analíticos de Colaboración en GitHub en el repositorio del Backend:

![Commits Backend](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/d239a8d7ee916ddff9846d69481a2597d386e644/img/commits/commits%20Backend.PNG)


Captura de Analíticos de Colaboración en GitHub en el repositorio del Frontend:

![Commits Frontend](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/d239a8d7ee916ddff9846d69481a2597d386e644/img/commits/commits%20Frontend.PNG)

### 5.3. Validation Interviews
En esta etapa se validaron las hipótesis del producto mediante entrevistas semiestructuradas aplicadas a usuarios reales del sector gastronómico. El objetivo fue contrastar las necesidades detectadas durante la investigación inicial con percepciones, comportamientos y problemas reales experimentados por administradores, chefs y encargados de compras. Este proceso permitió identificar brechas, validar supuestos críticos y orientar la siguiente fase del diseño e implementación.

Las entrevistas se realizaron siguiendo los lineamientos del marco Lean UX: validar suposiciones temprano, iterar rápido y obtener evidencia directa del usuario. Se emplearon técnicas de análisis cualitativo para identificar patrones asociados a necesidades, frustraciones y oportunidades de mejora dentro del flujo actual de gestión de inventarios.

### 5.3.1. Diseño de entrevistas

## Preguntas Generales
1. ¿Cuál es tu nombre?
2. ¿Qué edad tienes?
3. ¿Dónde te encuentras actualmente?
4. ¿A qué te dedicas dentro del negocio?
5. ¿Cuántos años de experiencia tienes en el rubro gastronómico?
6. ¿Cuántas personas trabajan en tu negocio?
7. ¿Cómo describirías un día típico de operación en tu negocio?

---

# Segmento: Dueños de Restobares y Restaurantes

## Sobre soluciones actuales
1. ¿Qué herramientas utilizas hoy? (Excel, cuadernos, software, notas, WhatsApp, etc.)
2. ¿Qué es lo que más te molesta de tu método actual?
3. Si ya usas un software, ¿qué limitaciones encuentras y por qué?

## Sobre LogisPe y sus funcionalidades
4. ¿Qué tan útil sería para ti un sistema que te avise cuando un insumo está por agotarse?
5. ¿Qué opinas de tener reportes diarios/semanales de costos e inventario?
6. ¿Te interesa vincular recetas directamente al inventario para controlar el consumo real?
7. ¿Cuánta importancia le das a un historial de compras y proveedores con seguimiento automático?

## Sobre expectativas
8. ¿Qué característica sería imprescindible para que realmente uses un sistema como este?
9. ¿Qué información te gustaría ver en un dashboard diario?
10. ¿Qué no debería tener un sistema de inventario para no volverse complejo o estorboso?
11. ¿Cómo medirías si la herramienta está funcionando para tu negocio?

---

# Segmento: Dueños de Cafeterías y Bares

## Sobre posibles soluciones
11. ¿Qué opinas de tener alertas automáticas por niveles bajos de stock?
12. ¿Te ayudaría un sistema que calcule automáticamente el costo por bebida/receta?
13. ¿Te interesaría almacenar el historial de mantenimientos o equipos de preparación? (máquinas de café, molinos, etc.)

## Expectativas y valor
14. ¿Qué esperas ver en un reporte semanal para tomar decisiones?
15. ¿Qué haría que un sistema como LogisPe realmente valga la pena para ti?
16. ¿Qué función crees que no usarías nunca?
17. ¿Qué características agregarías pensando en tu operación específica?

---

# Segmento: Dueños de Emprendimientos Gastronómicos (food trucks, dark kitchens, pequeños negocios)

## Sobre necesidades
1. ¿Qué necesitas para sentir que tienes control sobre tu inventario?
2. ¿Qué información te gustaría tener siempre disponible desde tu celular?
3. ¿Qué tan importante es para ti ver reportes automáticos sin tener que hacer cálculos manuales?

## Sobre soluciones
4. ¿Qué opinas de un sistema que calcule consumo automático en base a recetas?
5. ¿Qué tan útil sería recibir alertas por WhatsApp o correo sobre insumos críticos?
6. ¿Te interesaría llevar un registro de compras para ver cuánto gastas por semana/mes?

## Sobre expectativas
7. ¿Qué funcionalidad crees que no debería faltar en un sistema para tu tipo de negocio?
8. ¿Hay algo que un sistema de inventario sencillo siempre hace mal o te complica?
9. ¿Si tuvieras que pagar por un sistema así, ¿qué valor esperarías recibir a cambio?


### 5.3.2. Registro de entrevistas
# Segmento: Dueños de Cafeterías y Bares
Entrevista 1

![Entrevista](https://raw.githubusercontent.com/Aplicaciones-Web-CodeForge/Report/master/img/tb2%20entrevistas/cafeteria%20-%20Laguntis%20Verigen.PNG)


**Entrevistada:** Luciana Aguilar  
**Edad:** 17 años  
**Distrito:** Ate (distribución en La Molina y Surco)  
**Negocio:** Laguntis Verigen (repostería)  
**Tiempo de operación:** 3 años  
**Minuto de inicio:**  00:00
**URL del video en Microsoft Stream:**  [Ver entrevista](https://1drv.ms/v/c/131b5cdffd607f3f/EebVci5kyhRLj3gP5PDd3SkBS1h7_zMlej_f6vxU-zZkAw?e=TACIwX)  

# Segmento: Dueños de Emprendimientos Gastronómicos (food trucks, dark kitchens, pequeños negocios)

Entrevista 2

**Entrevistado:** Juan Viera  
**Edad:** 24 años  
**Distrito:** Miraflores  
**Negocio:** Propietario de un restaurante  
**Tiempo de operación:** 4 años  
**Minuto de inicio:** 00:00
**URL del video en Microsoft Stream:** [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218645_upc_edu_pe/IQB0kbaaDdYhTLwmwDIoQRMNARAlSDScit2i1az_Dy1iULQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=pp9uip)

# Segmento: Dueños de Restobares y Restaurantes

Entrevista 3

**Entrevistado:** Sergio Aguirre  
**Edad:** 24 años  
**Distrito:** Miraflores  
**Negocio:** Dueño y Gerente de cadena de bares  
**Tiempo de operación:** 2 años  
**Minuto de inicio:** 0:00
**URL del video en Microsoft Stream:** [Ver entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218645_upc_edu_pe/IQBEi8vIWPkoSq8HNxp466ACAVxJNhv-FLJx2-fo08H8Quw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=FXSlvr)

**Resumen**  
Luciana Aguilar, de 17 años, creó *Laguntis Verigen*, un emprendimiento de repostería con 3 años de operación. Empezó como un hobby, con apoyo de su madre, quien maneja inventarios. Ella se encarga de la preparación y promoción en Instagram.  
Considera clave contar con reportes de costos y pérdidas para decidir qué productos priorizar. Busca un software sencillo, accesible y que automatice procesos. Usa el celular para promocionar y gestionar pedidos. Se inspira en referentes como Alessandra Penny.  
Aunque valora el negocio, no busca expandirse, ya que lo considera complementario a su interés en las finanzas. Su herramienta ideal sería una página web para organizar mejor pedidos y comunicación.

### 5.3.3. Evaluaciones según heurísticas
Esta sección contiene el proceso de evaluación de las sesiones de validación basado en heurísticas, considerando usabilidad, arquitectura de información e inclusive design.  
Se utiliza el formato del Anexo D: “Evaluación de User Experience según Heurísticas”.

## UX Heuristics & Principles Evaluation  
**Usability – Inclusive Design – Information Architecture**

**CARRERA:** Ingeniería de Software  
**CURSO:** Aplicaciones Web  
**SECCIÓN:** 7468  
**PROFESORES:** Todos  
**AUDITOR:** Equipo LogisPE  
**CLIENTES:** Participantes de los segmentos gastronómicos entrevistados  

**SITE o APP A EVALUAR:**  
Landing Page + Aplicaciones Web LogisPE

### TAREAS A EVALUAR
1. Registro de usuario  
2. Ingreso al sistema  
3. Registro de insumos  
4. Registro de proveedores  
5. Visualización de stock  
6. Actualización de inventario  
7. Visualización de recetas y costos  
8. Alertas de inventario bajo  
9. Generación de reportes  

---

### Resultados de la Evaluación por Heurísticas

**1. Visibilidad del estado del sistema**  
Los usuarios destacaron que la aplicación muestra datos esenciales como stock actual y alertas, pero solicitaron mayor contraste en los indicadores, barras de progreso más evidentes y estados de carga más claros al registrar insumos o proveedores.  
**Recomendación:** incorporar notificaciones visuales persistentes y animaciones breves de confirmación de acciones.

**2. Relación del sistema con el mundo real**  
El uso de términos como “insumos”, “perecibles”, “proveedores”, “recetas” y “stock” facilita la comprensión del sistema.  
**Recomendación:** agregar iconografía estándar gastronómica (ingredientes, refrigerados, costos) para mejorar la asociación visual.

**3. Libertad y control del usuario**  
Los usuarios pidieron opciones para revertir acciones, especialmente en registro de cantidades o eliminación de insumos.  
**Recomendación:** incorporar botones “Deshacer”, “Revertir cambio” y “Restaurar stock previo”.

**4. Consistencia y estándares**  
Los formularios siguen un estilo coherente y los botones mantienen el mismo color y función en toda la plataforma.  
**Recomendación:** unificar 100% la estructura de títulos, descripciones y acciones principales en todas las pantallas.

**5. Prevención de errores**  
Se detectaron casos donde el sistema permitía ingresar valores negativos, campos vacíos o cantidades irreales.  
**Recomendación:** aplicar validaciones estrictas numéricas, fechas de caducidad obligatorias y restricciones de unidades.

**6. Reconocimiento sobre recuerdo**  
Las listas de insumos y proveedores ayudan a evitar que el usuario memorice datos.  
**Recomendación:** añadir plantillas visuales para recetas, atajos para repetir compras frecuentes y categorías predefinidas.

**7. Flexibilidad y eficiencia**  
Usuarios con experiencia pidieron automatizar tareas como reposición sugerida o estimación automática de consumo semanal.  
**Recomendación:** agregar funciones avanzadas opcionales para usuarios expertos (modos rápidos, autocompletado inteligente).

**8. Estética y diseño minimalista**  
La interfaz es limpia, sin elementos innecesarios. No obstante, algunos formularios se percibieron extensos.  
**Recomendación:** agrupar campos, usar acordeones y simplificar pasos cuando sea posible.

**9. Diagnóstico y recuperación de errores**  
Los mensajes de error son entendibles, pero falta más contexto sobre cómo resolver el problema.  
**Recomendación:** incluir mensajes como: “Falta completar el campo X. Ejemplo: …” o “Este proveedor ya existe. ¿Desea editarlo?”

**10. Ayuda y documentación**  
Los usuarios solicitaron tutoriales breves y accesibles desde la interfaz.  
**Recomendación:** integrar guías paso a paso, videos cortos y un glosario de términos gastronómicos.

### 5.4. Video About-the-Product

[Video About-the-Product (OneDrive)](https://1drv.ms/v/c/131b5cdffd607f3f/EbqGzFdPKfpGqhDEeP7Pr9kBBhsPyNmuRxbg_ncvzXJChA?e=gysMM4)

[Video About-the-Product (YouTube)](https://youtu.be/BdOGV9lqrGM)


## Conclusiones y recomendaciones

El Sprint 1 permitió establecer las bases del proyecto mediante el diseño, desarrollo y despliegue de la landing page. Durante este proceso, el equipo consolidó los pilares del producto, alineando los objetivos visuales y funcionales con la propuesta de valor. Asimismo, se logró implementar una estructura clara y adaptable, aplicando buenas prácticas de HTML, CSS y JavaScript para garantizar una experiencia de usuario eficiente.

El despliegue exitoso de la landing page representa un primer paso fundamental para la validación del producto y la captación de usuarios iniciales. Además, este avance evidenció una comunicación efectiva y un trabajo colaborativo dentro del equipo, lo que sienta un precedente positivo para los siguientes sprints. En general, el Sprint 1 cumplió sus metas, aportando un entregable tangible y de calidad que sirve como base para futuras mejoras y nuevas funcionalidades.

# Bibliografía

- Crockford, D. (2008). *JavaScript: The good parts*. O’Reilly Media. [https://www.oreilly.com/library/view/javascript-the-good/9780596517748/](https://www.oreilly.com/library/view/javascript-the-good/9780596517748/)

- Duckett, J. (2011). *HTML and CSS: Design and build websites*. Wiley. [https://www.wiley.com/en-us/HTML+and+CSS%3A+Design+and+Build+Websites-p-9781118008188](https://www.wiley.com/en-us/HTML+and+CSS%3A+Design+and+Build+Websites-p-9781118008188)

- Flanagan, D. (2020). *JavaScript: The definitive guide* (7th ed.). O’Reilly Media. [https://www.oreilly.com/library/view/javascript-the-definitive/9781491952016/](https://www.oreilly.com/library/view/javascript-the-definitive/9781491952016/)

- Freeman, E., & Robson, E. (2014). *Head first JavaScript programming*. O’Reilly Media. [https://www.oreilly.com/library/view/head-first-javascript/9781449343989/](https://www.oreilly.com/library/view/head-first-javascript/9781449343989/)

- Keith, J. (2010). *HTML5 for web designers*. A Book Apart. [https://abookapart.com/products/html5-for-web-designers](https://abookapart.com/products/html5-for-web-designers)

- Meyer, E. A. (2006). *CSS: The definitive guide* (3rd ed.). O’Reilly Media. [https://www.oreilly.com/library/view/css-the-definitive/0596527330/](https://www.oreilly.com/library/view/css-the-definitive/0596527330/)

- Mozilla Developer Network. (2025). *MDN Web Docs: HTML, CSS, and JavaScript*. Mozilla Foundation. [https://developer.mozilla.org/](https://developer.mozilla.org/)

- Pilgrim, M. (2010). *HTML5: Up and running*. O’Reilly Media. [https://www.oreilly.com/library/view/html5-up-and/9781449393908/](https://www.oreilly.com/library/view/html5-up-and/9781449393908/)

- Resig, J., & Bibeault, B. (2013). *Secrets of the JavaScript Ninja* (2nd ed.). Manning Publications. [https://www.manning.com/books/secrets-of-the-javascript-ninja-second-edition](https://www.manning.com/books/secrets-of-the-javascript-ninja-second-edition)

- Robbins, J. N. (2018). *Learning web design: A beginner’s guide to HTML, CSS, JavaScript, and web graphics* (5th ed.). O’Reilly Media. [https://www.oreilly.com/library/view/learning-web-design/9781491960196/](https://www.oreilly.com/library/view/learning-web-design/9781491960196/)

# Anexos

- Link del repositorio del Informe: https://github.com/Aplicaciones-Web-CodeForge/Report <br>
- Link del repositorio de la Landing Page: https://github.com/Aplicaciones-Web-CodeForge/upc-pre-202520--1asi0729-7468-LogisPe-Landing-Page <br>
- Link de la Landing Page desplegada por GitHub Pages: https://aplicaciones-web-codeforge.github.io/upc-pre-202520--1asi0729-7468-LogisPe-Landing-Page/
- Link del Frontend desplegado: https://upc-pre-202520-1asi0729-7468-logis.vercel.app/home
- Link del Backend desplegado: https://upc-pre-202520-1asi0729-7468-logispe.onrender.com/docs/#/
