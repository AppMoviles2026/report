<div align="center">

<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="100" alt="Logo UPC">
<br><br>
Universidad Peruana de Ciencias Aplicadas<br>
Carrera de Ingeniería de Software<br><br>

<strong>1ACC0238</strong> <br>
<strong>Aplicaciones para Dispositivos Móviles</strong>

NRC <br>
<strong>4950</strong>

<strong>Informe del Trabajo Final</strong>

Docente <br>
<strong>Mayta Guillermo, Jorge Luis</strong><br><br>

Equipo <br>
<strong>CollabTech</strong>

Proyecto <br>
<strong>CollabPro</strong><br><br>

<strong>Integrantes</strong><br>

<table border="0" style="border-collapse: collapse; border: none; margin: 0 auto; background-color: transparent;">
  <tr style="border: none;">
    <th style="border: none; text-align: center; padding: 5px 15px;">Código</th>
    <th style="border: none; text-align: left; padding: 5px 15px;">Apellidos y Nombres</th>
  </tr>
  <tr style="border: none;">
    <td style="border: none; text-align: center; padding: 5px 15px;">U201717085</td>
    <td style="border: none; text-align: left; padding: 5px 15px;">Revilla Quispe, Renzo Zamir</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none; text-align: center; padding: 5px 15px;">U20241D922</td>
    <td style="border: none; text-align: left; padding: 5px 15px;">Quispe Serrano, Julio Frank</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none; text-align: center; padding: 5px 15px;">U20221C803</td>
    <td style="border: none; text-align: left; padding: 5px 15px;">Rocca Leon, Anhelo Rodrigo</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none; text-align: center; padding: 5px 15px;">U20231H059</td>
    <td style="border: none; text-align: left; padding: 5px 15px;">Garcia Villanueva, Leonardo Rafael</td>
  </tr>
  <tr style="border: none;">
    <td style="border: none; text-align: center; padding: 5px 15px;">U20211D989</td>
    <td style="border: none; text-align: left; padding: 5px 15px;">Vallejo Trujillo, Fabio Cesar</td>
  </tr>
</table>

<br><br>
<strong>Período 202620</strong><br>
<strong>Octubre 2026</strong><br><br>

</div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto.

| Versión | Fecha      | Autor             | Descripción de modificación                                                                                                                                                                                           |
| ------- | ---------- | ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| V1.0    | 10/09/2026 | Equipo CollabTech | Creación de la primera versión del informe para la entrega AV1. Se incluyen las secciones preliminares, el Capítulo I (Startup Profile, Solution Profile, Segmentos) y el Capítulo II (Requirements y Strategic DDD). |
| V1.1    | 28/09/2026 | Equipo CollabTech | Se incorpora la sección 4.1 de Software Configuration Management para CollabPro: entorno, gestión del código fuente, convenciones y configuración propuesta de despliegue.                                            |
| V1.2    | 09/10/2026 | Equipo CollabTech | Se documenta la evidencia de servicios REST y despliegue del backend en Azure; se completa Student Outcome para TB1, se actualizan conclusiones y recomendaciones del sprint y se agregan enlaces de artefactos y entrevistas en Anexos. |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

El repositorio para el Project Report se encuentra alojado en la organización de GitHub del equipo: `https://github.com/AppMoviles2026/report`.

**- AV1**

Durante la entrega AV1, las actividades de elaboración del informe se gestionaron utilizando un enfoque de trabajo en paralelo. Cada integrante clonó el repositorio y trabajó en su rama correspondiente según la división de los capítulos I y II.

![Collab Github](./assets/C02/Collab/AV1.png)

Repositorio del reporte: https://github.com/AppMoviles2026/report

<div style="page-break-after: always;"></div>

## Contenido

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Objetivos SMART](#objetivos-smart)
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
    - [2.3.5. Big Picture EventStorming](#235-big-picture-eventstorming)
    - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
  - [2.4. Requirements Specification](#24-requirements-specification)
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
      - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
      - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
      - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
  - [2.6. Tactical-Level Domain-Driven Design](#26-tactical-level-domain-driven-design)
    - [2.6.1. Bounded Context: Identity & Profile Management](#261-bounded-context-identity--profile-management)
      - [2.6.1.1. Domain Layer](#2611-domain-layer)
      - [2.6.1.2. Interface Layer](#2612-interface-layer)
      - [2.6.1.3. Application Layer](#2613-application-layer)
      - [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
      - [2.6.1.5. Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.1.6. Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.1.6.1. Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)
        - [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
    - [2.6.2. Bounded Context: Campaign Management](#262-bounded-context-campaign-management)
      - [2.6.2.1. Domain Layer](#2621-domain-layer)
      - [2.6.2.2. Interface Layer](#2622-interface-layer)
      - [2.6.2.3. Application Layer](#2623-application-layer)
      - [2.6.2.4. Infrastructure Layer](#2624-infrastructure-layer)
      - [2.6.2.5. Bounded Context Software Architecture Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.2.6. Bounded Context Software Architecture Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.2.6.1. Bounded Context Domain Layer Class Diagrams](#26261-bounded-context-domain-layer-class-diagrams)
        - [2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)
    - [2.6.3. Bounded Context: Collaboration Management](#263-bounded-context-collaboration-management)
      - [2.6.3.1. Domain Layer](#2631-domain-layer)
      - [2.6.3.2. Interface Layer](#2632-interface-layer)
      - [2.6.3.3. Application Layer](#2633-application-layer)
      - [2.6.3.4. Infrastructure Layer](#2634-infrastructure-layer)
      - [2.6.3.5. Bounded Context Software Architecture Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.3.6. Bounded Context Software Architecture Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.3.6.1. Bounded Context Domain Layer Class Diagrams](#26361-bounded-context-domain-layer-class-diagrams)
        - [2.6.3.6.2. Bounded Context Database Design Diagram](#26362-bounded-context-database-design-diagram)
    - [2.6.4. Bounded Context: Billing & Compensation Management](#264-bounded-context-billing--compensation-management)
      - [2.6.4.1. Domain Layer](#2641-domain-layer)
      - [2.6.4.2. Interface Layer](#2642-interface-layer)
      - [2.6.4.3. Application Layer](#2643-application-layer)
      - [2.6.4.4. Infrastructure Layer](#2644-infrastructure-layer)
      - [2.6.4.5. Bounded Context Software Architecture Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.4.6. Bounded Context Software Architecture Code Level Diagrams](#2646-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.4.6.1. Bounded Context Domain Layer Class Diagrams](#26461-bounded-context-domain-layer-class-diagrams)
        - [2.6.4.6.2. Bounded Context Database Design Diagram](#26462-bounded-context-database-design-diagram)
    - [2.6.5. Bounded Context: Performance & Attribution Management](#265-bounded-context-performance--attribution-management)
      - [2.6.5.1. Domain Layer](#2651-domain-layer)
      - [2.6.5.2. Interface Layer](#2652-interface-layer)
      - [2.6.5.3. Application Layer](#2653-application-layer)
      - [2.6.5.4. Infrastructure Layer](#2654-infrastructure-layer)
      - [2.6.5.5. Bounded Context Software Architecture Component Level Diagrams](#2655-bounded-context-software-architecture-component-level-diagrams)
      - [2.6.5.6. Bounded Context Software Architecture Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
        - [2.6.5.6.1. Bounded Context Domain Layer Class Diagrams](#26561-bounded-context-domain-layer-class-diagrams)
        - [2.6.5.6.2. Bounded Context Database Design Diagram](#26562-bounded-context-database-design-diagram)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
  - [3.1. Product Design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labeling Systems](#3122-labeling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
      - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
      - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
      - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
      - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
      - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
  - [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)
  - [4. Product Implementation & Validation](#4-product-implementation--validation)
    - [4.1. Software Configuration Management](#41-software-configuration-management)
      - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
      - [4.1.2. Source Code Management](#412-source-code-management)
      - [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
      - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
    - [4.2.1. Sprint 1](#421-sprint-1)
      - [4.2.1.1. Sprint Planning 1](#4211-sprint-planning-1)
      - [4.2.1.2. Aspect Leaders and Collaborators](#4212-aspect-leaders-and-collaborators)
      - [4.2.1.3. Sprint Backlog 1](#4213-sprint-backlog-1)
      - [4.2.1.4. Development Evidence for Sprint Review](#4214-development-evidence-for-sprint-review)
      - [4.2.1.5. Testing Suite Evidence for Sprint Review](#4215-testing-suite-evidence-for-sprint-review)
      - [4.2.1.6. Execution Evidence for Sprint Review](#4216-execution-evidence-for-sprint-review)
      - [4.2.1.7. Services Documentation Evidence for Sprint Review](#4217-services-documentation-evidence-for-sprint-review)
      - [4.2.1.8. Software Deployment Evidence for Sprint Review](#4218-software-deployment-evidence-for-sprint-review)
      - [4.2.1.9. Team Collaboration Insights during Sprint](#4219-team-collaboration-insights-during-sprint)
  - [4.3. Validation Interviews](#43-validation-interviews)
    - [4.3.1. Diseño de Entrevistas](#431-diseño-de-entrevistas)
    - [4.3.2. Registro de Entrevistas](#432-registro-de-entrevistas)
    - [4.3.3. Evaluaciones según heurísticas](#433-evaluaciones-según-heurísticas)

- [Conclusiones](#conclusiones)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

**ABET EAC - Student Outcome 7:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

| Criterio específico                                                                                                                         | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Conclusiones                                                                                                                                                                                                                                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Quispe Serrano, Julio Frank:** AV1: Actualicé mis conocimientos investigando de forma autónoma la metodología ágil Lean UX y la técnica de las 5W's y 2H's para redactar correctamente el Solution Profile, los Assumptions y el Canvas del proyecto.<br><br>**TB1:** Apliqué criterios de validación y pruebas a los flujos de registro, diseño adaptable y postulación; profundicé en casos límite y criterios de aceptación para comprobar las historias asignadas.<br><br>**Vallejo Trujillo, Fabio Cesar:** AV1: Aprendí a utilizar la herramienta UXPressia de manera autodidacta para estructurar el Needfinding (User Personas y Journey Maps) y actualicé mis nociones sobre métricas para el análisis competitivo de plataformas de marketing.<br><br>**TB1:** Profundicé en diseño adaptable y localización al llevar los requisitos de la Landing Page y del perfil creador a interfaces y flujos móviles consistentes.<br><br>**Garcia Villanueva, Leonardo Rafael:** AV1: En este avance tuve que realizar la especificación de los requisitos del proyecto, y para ello actualicé mis conocimientos técnicos sobre Behavior-Driven Development (BDD), estudiando a fondo la sintaxis del estándar Gherkin para redactar historias de usuario sin ambigüedades.<br><br>**TB1:** Amplié mis conocimientos sobre autenticación, recuperación de acceso y autorización OAuth al trabajar con los flujos de registro, recuperación de cuenta y vinculación social.<br><br>**Revilla Quispe, Renzo Zamir:** AV1: Tuve que investigar y actualizar mis conocimientos teóricos sobre Domain-Driven Design (DDD) y modelado EventStorming para poder definir correctamente el lenguaje ubicuo y los Bounded Contexts a nivel estratégico.<br><br>**TB1:** Apliqué DDD a los flujos de campañas y postulaciones, profundizando en estados, condiciones, disponibilidad, filtros y reglas de negocio.<br><br>**Rocca León, Anhelo:** AV1: Para el desarrollo de la arquitectura, investigué de manera autónoma los fundamentos del modelo C4 (Context, Container, Component, Code) y cómo aplicarlo para diagramar la infraestructura técnica del sistema.<br><br>**TB1:** Amplié mis conocimientos de diseño de interacción al trabajar en formularios de identidad, consulta de perfil y autorización de redes sociales. | **AV1:** Durante esta entrega, todo el equipo demostró la capacidad de investigar y aplicar metodologías y estándares de la industria (como Lean UX, Gherkin, DDD y C4 Model) que no se dominaban del todo al inicio del ciclo, integrándolos exitosamente en la documentación formal de requerimientos y arquitectura del sistema.<br><br>**TB1:** El equipo convirtió ese aprendizaje en entregables verificables: flujos de usuario y pantallas, endpoints REST organizados por contexto, autenticación JWT, pruebas automatizadas y documentación OpenAPI publicada en el entorno Azure. |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.**  | **Quispe Serrano, Julio Frank:** AV1: Comprendí que estructurar un modelo de negocio B2B requiere investigar constantemente el mercado y validar las hipótesis (Hypothesis Statements) iterativamente para asegurar que el software brinde valor real.<br><br>**TB1:** Reconocí que debo seguir profundizando en pruebas de integración y escenarios negativos para validar los flujos ante datos inválidos, conflictos y cambios de estado.<br><br>**Vallejo Trujillo, Fabio Cesar:** AV1: Reconocí la importancia de adaptar las herramientas de investigación a los usuarios reales; entender las frustraciones de los creadores de contenido me exigió buscar continuamente nuevos enfoques de empatía (Empathy Mapping).<br><br>**TB1:** Identifiqué la necesidad de seguir aprendiendo sobre accesibilidad, adaptación a distintos dispositivos e integración de las pantallas con los contratos reales del backend.<br><br>**Garcia Villanueva, Leonardo Rafael:** AV1: Identifiqué que mis conocimientos sobre Gherkin para la elaboración de las User Stories necesitaban ser reforzados, y también reconocí la necesidad de continuar investigando y aprendiendo sobre la correcta gestión del Product Backlog y la elaboración del Impact Mapping para aplicarlos correctamente durante el desarrollo de este proyecto y así mejorar tanto como mi desempeño como la calidad del proyecto.<br><br>**TB1:** Reconocí que los flujos de recuperación y OAuth dependen de políticas y proveedores externos, por lo que debo mantenerme actualizado y probar sus estados de error y seguridad.<br><br>**Revilla Quispe, Renzo Zamir:** AV1: Asimilé que el diseño a nivel estratégico nunca es estático; dominar los flujos de dominio y la delimitación de contextos (Context Mapping) me exigió mantener una postura de estudio constante de la literatura técnica.<br><br>**TB1:** Identifiqué la importancia de continuar estudiando consistencia transaccional, concurrencia e idempotencia para evolucionar los servicios de campañas y postulaciones con seguridad.<br><br>**Rocca León, Anhelo:** AV1: Evidencié la necesidad de consultar fuentes académicas y documentación oficial constantemente para justificar decisiones de arquitectura de bases de datos y garantizar la viabilidad del despliegue tecnológico.<br><br>**TB1:** Reconocí que los flujos deben seguir validándose con usuarios y que debo profundizar en accesibilidad y estados de carga, error y ausencia de conexión. | **AV1:** Como equipo, comprendemos que el ecosistema de startups y las tecnologías de desarrollo evolucionan rápidamente. Reconocemos que adoptar una postura proactiva hacia la lectura de documentación oficial y literatura especializada es fundamental para el éxito y la escalabilidad del proyecto.<br><br>**TB1:** El equipo identificó nuevas necesidades de aprendizaje en seguridad, integración móvil-backend, pruebas con datos persistentes y experiencia de uso. La evolución del producto requerirá revisar la documentación técnica y validar cada incremento con usuarios y evidencia de ejecución. |

<div style="page-break-after: always;"></div>

## Objetivos SMART

**Quispe Serrano, Julio Frank:**

Plan: Al finalizar mi carrera, continuaré fortaleciendo mis competencias en desarrollo de software y arquitectura de soluciones, complementando los conocimientos adquiridos durante mi formación universitaria con nuevas tecnologías y buenas prácticas utilizadas en proyectos profesionales. Buscaré mejorar progresivamente mis habilidades técnicas mediante proyectos propios, certificaciones y experiencias prácticas que me permitan asumir mayores responsabilidades dentro de equipos de desarrollo.

Objetivo SMART 1: Durante los primeros 9 meses después de finalizar la carrera, desarrollaré y desplegaré al menos 2 proyectos de software de complejidad media utilizando tecnologías de backend, frontend, bases de datos y servicios cloud. En cada proyecto aplicaré buenas prácticas de arquitectura de software y documentaré las decisiones técnicas tomadas, con el objetivo de fortalecer mi portafolio profesional y demostrar mi capacidad para desarrollar soluciones completas.

Objetivo SMART 2: Durante los primeros 12 meses después de finalizar la carrera, obtendré al menos 2 certificaciones o completaré 2 programas de especialización relacionados con arquitectura de software, computación en la nube o DevOps. Aplicaré los conocimientos adquiridos en al menos uno de mis proyectos personales, incorporando aspectos como despliegue en la nube, integración continua o contenerización para fortalecer mis competencias profesionales.

<br>

**Vallejo Trujillo, Fabio Cesar:**

Plan: Al terminar mi carrera, continuaré desarrollando mis conocimientos en arquitectura de software, infraestructura cloud y desarrollo de aplicaciones, buscando fortalecer especialmente mi capacidad para diseñar soluciones mantenibles y escalables. Complementaré la experiencia obtenida en proyectos universitarios con formación especializada y proyectos que me permitan aplicar diferentes patrones, arquitecturas y servicios tecnológicos.

Objetivo SMART 1: En los primeros 12 meses después de finalizar la carrera, diseñaré e implementaré al menos 2 aplicaciones utilizando principios de arquitectura limpia y buenas prácticas de desarrollo, documentando su arquitectura mediante diagramas y explicando las principales decisiones técnicas. Al menos uno de estos proyectos será desplegado utilizando servicios cloud para demostrar conocimientos tanto de desarrollo como de infraestructura.

Objetivo SMART 2: Durante los primeros 6 meses posteriores a mi graduación, completaré al menos 2 cursos o certificaciones relacionados con arquitectura cloud, DevOps o diseño de sistemas escalables. Como evidencia de aprendizaje, implementaré al menos 3 mejoras técnicas en mis proyectos personales, tales como pipelines de integración y despliegue continuo, contenerización, monitoreo o servicios administrados en la nube.

<br>

**Garcia Villanueva, Leonardo Rafael:**

Plan: Al concluir con mi carrera, continuaré desarrollando mis competencias profesionales mediante un proceso de aprendizaje continuo donde practicaré el desarrollo de software con las nuevas tecnologías relevantes que salgan en el mercado, incluyendo las emergentes como la inteligencia artificial, agentes de IA y automatización de procesos de programación. De este modo reforzaré mis conocimientos adquiridos durante la carrera e incorporaré nuevos conocimientos que me permitan tener un perfil profesional actualizado.

Objetivo SMART 1: En los 6 primeros meses después de haber finalizado la carrera ampliaré mis conocimientos y habilidades para el desarrollo Full Stack, enfocándome principalmente en Java con Spring Boot para el backend, Vue.js para el frontend y MongoDB para la base de datos. Para ello, crearé 2 proyectos personales de complejidad media y alta, con el propósito de consolidar mi aprendizaje y tener un portafolio que demuestre mi crecimiento profesional.

Objetivo SMART 2: Durante los primeros 9 meses después de haber finalizado la carrera tomaré 2 o más cursos relacionados con las tecnologías emergentes, priorizando especialmente áreas como el uso profesional y ético de inteligencia artificial, agentes de IA y automatización aplicada al desarrollo de software. Luego, aplicaré lo aprendido elaborando un proyecto personal pequeño o mediano por cada curso finalizado, para mantener actualizados mis conocimientos y reforzar mi perfil como Ingeniero de Software.

<br>

**Revilla Quispe, Renzo Zamir:**

Plan: Al finalizar mi carrera, continuaré fortaleciendo mis conocimientos en desarrollo web y móvil, enfocándome también en mejorar mis competencias en diseño y organización de sistemas de software. Buscaré complementar mis conocimientos técnicos con habilidades de gestión y trabajo colaborativo que me permitan participar progresivamente en proyectos de mayor complejidad y asumir responsabilidades dentro de equipos de desarrollo.

Objetivo SMART 1: Durante los primeros 12 meses después de finalizar la carrera, desarrollaré al menos 2 aplicaciones, una orientada al entorno web y otra al entorno móvil, aplicando principios de Domain-Driven Design y buenas prácticas de arquitectura. Cada proyecto contará con documentación técnica y repositorio público que evidencie el proceso de desarrollo y las decisiones tomadas.

Objetivo SMART 2: En los primeros 12 meses posteriores a mi graduación, completaré al menos 2 cursos especializados relacionados con Domain-Driven Design, arquitectura de software o gestión de proyectos de desarrollo. Aplicaré los conocimientos adquiridos participando en al menos un proyecto colaborativo en el que pueda asumir responsabilidades relacionadas con planificación, organización técnica o coordinación del equipo.

<br>

**Rocca Leon, Anhelo Rodrigo:**

Plan: Después de finalizar mi carrera, continuaré desarrollando mis competencias en diseño de soluciones de software, experiencia de usuario y arquitectura, buscando complementar mis conocimientos de programación y bases de datos con herramientas que me permitan participar en todo el proceso de construcción de un producto digital. Mantendré un aprendizaje continuo mediante cursos especializados y proyectos prácticos que integren tanto aspectos técnicos como de diseño.

Objetivo SMART 1: Durante los primeros 9 meses después de finalizar la carrera, desarrollaré al menos 2 proyectos de software en los que participe tanto en la definición de la experiencia de usuario como en su implementación técnica. Para cada proyecto elaboraré prototipos, flujos de interacción y una aplicación funcional, con el objetivo de fortalecer mi capacidad para transformar necesidades de usuarios en soluciones digitales.

Objetivo SMART 2: En un periodo máximo de 9 meses después de finalizar la carrera, completaré al menos 2 cursos o certificaciones relacionados con UX/UI, arquitectura de software o diseño de soluciones digitales. Aplicaré los conocimientos obtenidos mejorando al menos 2 proyectos de mi portafolio mediante prototipos, diagramas de arquitectura o evaluaciones de usabilidad que permitan evidenciar mi crecimiento profesional.

## Capítulo I: Presentación

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

CollabTech es una startup de tecnología conformada por estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC), orientada al desarrollo de soluciones digitales para pequeñas y medianas empresas.

Nuestra propuesta de valor se materializa en CollabPro, un marketplace B2B que conecta empresas con creadores de contenido para gestionar colaboraciones de marketing de forma estructurada, segura y medible. La plataforma permite publicar campañas, definir entregables y compensaciones, gestionar postulaciones y verificar el cumplimiento de las colaboraciones.

CollabPro busca reemplazar la gestión informal mediante mensajes directos y otros canales dispersos por un proceso centralizado que genere mayor confianza entre empresas y creadores y permita medir el rendimiento de las campañas realizadas.

#### 1.1.2. Perfiles de integrantes del equipo

|                        Foto                         | Apellidos y Nombres                |   Código   | Carrera                | Resumen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| :-------------------------------------------------: | :--------------------------------- | :--------: | :--------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|       ![foto](./assets/C01/Team/frankFT.png)        | Quispe Serrano, Julio Frank        | U20241D922 | Ingeniería de Software | Soy Julio Frank Quispe Serrano, alumno de 6to ciclo de Ingeniería de Software en la UPC. Cuento con una marcada inclinación hacia la programación y la gestión eficiente del tiempo. Mi aporte principal a este grupo de trabajo será la resolución de conflictos técnicos y operativos, aportando una visión pragmática que permita superar eventuales estancamientos en las fases de elaboración del proyecto.                                                                                                       |
| ![foto](./assets/C01/Team/perfil-fabio-vallejo.png) | Vallejo Trujillo, Fabio Cesar      | U20211D989 | Ingeniería de Software | Soy estudiante de séptimo ciclo de Ingeniería de Software. Me caracterizo por tener conocimientos técnicos en múltiples áreas de software y mantener en orden mis equipos de trabajo para mantener entregables de alta calidad. Puedo aportar al proyecto con mis conocimientos de arquitectura limpia, infraestructura cloud, programación y manteniendo al equipo organizado.                                                                                                                                        |
|       ![foto](./assets/C01/Team/leonardo.png)       | Garcia Villanueva, Leonardo Rafael | U20231H059 | Ingeniería de Software | Actualmente soy estudiante de sexto ciclo de la carrera de Ingeniería de Software. Tengo conocimientos sobre el manejo de bases de datos, varios lenguajes de programación, y de metodologías ágiles. Además, puedo dar solución a problemas que requieran de un enfoque lógico y creativo mediante el desarrollo de software. Dentro del equipo puedo aportar con la resolución de dificultades técnicas o de documentación que se presenten de forma eficiente.                                                      |
|        ![foto](./assets/C01/Team/renzo.png)         | Revilla Quispe, Renzo Zamir        | U201717085 | Ingenieria de Software | Soy Renzo Revilla, estudiante de Ingenieria de Software en la Universidad Peruana de Ciencias Aplicadas, con experiencia en desarrollo web y movil. Me destaco por mis habilidades en comunicacion efectiva y trabajo en equipo, lo que facilita la coordinación y el cumplimiento de objetivos dentro del grupo. Disfruto de la natacion y del aprendizaje continuo. Mi aporte al equipo se centra en el desarrollo tecnico y en la gestion del proyecto, contribuyendo a mantener un trabajo organizado y eficiente. |
|     ![foto](./assets/C01/Team/anhelo-photo.png)     | Rocca Leon, Anhelo Rodrigo         | U20221C803 | Ingeniería de Software | Soy estudiante de Ingeniería de Software. Cuento con conocimientos en programación, bases de datos y desarrollo de soluciones digitales, utilizando tecnologías como C++, Python y SQL. Asimismo, me desenvuelvo con facilidad en Bash. En el equipo, aporto en actividades relacionadas con experiencia de usuario, flujos de interacción, mock-ups y documentación visual del producto. Mi contribución se enfoca en que el productor tenga una experiencia clara, ordenada y útil para sus usuarios.                |

### 1.2. Solution Profile

CollabPro es una plataforma B2B que profesionaliza las colaboraciones entre pequeñas y medianas empresas y creadores de contenido. La solución permite a las empresas publicar campañas estructuradas con objetivos, requisitos, entregables, plazos y compensaciones, mientras que los creadores pueden postular y gestionar sus colaboraciones desde un mismo espacio.

La plataforma también incorpora un proceso de validación que permite verificar el cumplimiento de los entregables antes de liberar la compensación y un panel de métricas para que las empresas puedan evaluar el rendimiento de sus campañas y tomar mejores decisiones de marketing.

#### 1.2.1. Antecedentes y problemática

**Who (¿Quiénes son los afectados?)**

Los principales afectados son dos grupos claramente identificables. En primer lugar, las pequeñas y medianas empresas que necesitan utilizar las redes sociales y el marketing de creadores para promocionar sus productos o servicios, pero que no cuentan con procesos estructurados para encontrar, contratar y supervisar creadores de contenido.

En segundo lugar, los creadores de contenido, especialmente aquellos que trabajan con pequeñas marcas o negocios locales, quienes reciben propuestas mediante mensajes directos y otros canales informales, sin contar necesariamente con acuerdos claros sobre los entregables, plazos, condiciones de publicación y compensación.

**What (¿Cuál es el problema?)**

Las colaboraciones entre pequeñas y medianas empresas y creadores de contenido suelen gestionarse mediante mensajes directos de Instagram, WhatsApp, correo electrónico u otros canales no especializados. Esta informalidad dificulta establecer acuerdos claros sobre los objetivos de una campaña, los entregables esperados, los plazos y la compensación.

Como consecuencia, las empresas pueden recibir contenido que no cumple con sus requisitos, enfrentar retrasos o tener dificultades para verificar si una publicación realmente cumplió las condiciones acordadas. Además, al no existir un proceso centralizado para registrar y medir las campañas, las empresas tienen dificultades para determinar el alcance obtenido y evaluar el retorno de su inversión.

Por otro lado, los creadores también pueden enfrentar problemas relacionados con cambios en los acuerdos, falta de claridad sobre los requisitos de la campaña o incertidumbre respecto al cumplimiento de la compensación.

**Where (¿Dónde ocurre?)**

El problema se presenta principalmente en los canales digitales utilizados actualmente para coordinar colaboraciones entre empresas y creadores, especialmente redes sociales como Instagram, además de WhatsApp, correo electrónico y otros medios de comunicación.

La problemática resulta especialmente relevante en mercados urbanos como Lima Metropolitana, donde existe una alta presencia de pequeñas y medianas empresas que utilizan las redes sociales como canal de promoción y adquisición de clientes.

**When (¿Cuándo ocurre?)**

El problema se manifiesta durante todo el ciclo de una colaboración entre una empresa y un creador. Comienza cuando la empresa busca un creador adecuado, continúa durante la negociación de las condiciones y se hace más evidente durante la ejecución de la campaña, cuando deben verificarse los entregables y el cumplimiento de los acuerdos.

También se presenta después de la publicación del contenido, cuando la empresa necesita determinar si la colaboración generó resultados suficientes para justificar la inversión realizada.

**Why (¿Por qué es un problema?)**

La informalidad de las colaboraciones genera incertidumbre tanto para las empresas como para los creadores.

Las empresas pueden invertir recursos económicos o productos sin tener mecanismos adecuados para garantizar que el contenido entregado cumpla con los requisitos definidos. Además, la ausencia de métricas centralizadas dificulta comparar campañas y determinar cuáles colaboraciones generan mejores resultados.

Los creadores, por su parte, pueden recibir instrucciones ambiguas, modificaciones de última hora o enfrentar incertidumbre respecto a cuándo y bajo qué condiciones recibirán su compensación.

Esta situación reduce la confianza entre ambas partes y limita la posibilidad de establecer relaciones comerciales recurrentes.

**How (¿Cómo se manifiesta?)**

La problemática se manifiesta mediante conversaciones dispersas por mensajes directos, acuerdos informales o verbales, ausencia de contratos formales, entregables poco definidos, retrasos en las publicaciones y dificultades para auditar el cumplimiento comercial. De acuerdo con el Instituto Nacional de Defensa de la Competencia y de la Protección de la Propiedad Intelectual (INDECOPI, 2024), una parte significativa de las colaboraciones comerciales locales se realiza bajo modalidades como canjes, envíos de productos o acuerdos verbales sin contratos integrales que precisen los deberes de las partes, tales como el control editorial, la acreditación de testimonios auténticos o el cumplimiento de las normas de autenticidad publicitaria.

Asimismo, las empresas suelen tener que recopilar manualmente información de las publicaciones para analizar métricas como alcance, visualizaciones e interacciones, dificultando la evaluación objetiva del rendimiento de cada campaña.

**How much (¿Cuál es la magnitud?)**

La relevancia de esta problemática se sustenta en el acelerado crecimiento del ecosistema publicitario digital en el Perú. De acuerdo con el Informe de Inversión Publicitaria Digital 2024 elaborado por IAB Perú y PwC (2024), el gasto publicitario digital en el país alcanzó los 296 millones de dólares en 2024, consolidando una trayectoria de expansión continua desde los 140 millones reportados en 2020.

Sin embargo, a pesar de este importante flujo de capital, las micro, pequeñas y medianas empresas enfrentan serias limitaciones para profesionalizar su participación dentro del ecosistema digital. Si bien las redes sociales representan el canal de entrada más accesible frente a los altos costos de los medios tradicionales, la gestión de colaboraciones con creadores de contenido se mantiene atomizada. La falta de herramientas estructuradas para pactar compensaciones, supervisar entregables bajo estándares regulatorios vigentes y auditar el retorno sobre la inversión frena la capacidad de las pymes para escalar estas estrategias de micro-marketing de manera predecible y formal.

En este contexto, existe una oportunidad para desarrollar una plataforma especializada que permita estructurar las colaboraciones entre empresas y creadores, reduciendo la informalidad y facilitando la medición de los resultados obtenidos.

**Figura 1** Evolución de la inversión en publicidad digital en el Perú (2014-2024)

![EcosistemaMarketing](./assets/C01/fuente1.png)

_Nota._ Adaptado de Informe de Inversión Publicitaria Digital 2024 (p. 2), por PwC e Interactive Advertising Bureau Perú (IAB Perú), 2024.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

Las pequeñas y medianas empresas necesitan utilizar las redes sociales para promocionar sus productos y servicios, pero muchas colaboraciones con creadores de contenido se gestionan mediante mensajes directos de Instagram, WhatsApp y otros canales informales. En este contexto, las empresas enfrentan dificultades para definir acuerdos claros, verificar los entregables, controlar los plazos y medir el retorno de inversión de sus campañas.

Al mismo tiempo, los creadores de contenido reciben propuestas poco estructuradas y pueden enfrentar incertidumbre respecto a los requisitos de la colaboración y la compensación correspondiente.

Hemos observado un factor crítico que afecta a este ecosistema: las empresas necesitan mayor control y trazabilidad sobre sus campañas, mientras que los creadores necesitan condiciones claras para aceptar y ejecutar las colaboraciones.

Estas necesidades son interdependientes, ya que una empresa requiere confianza en el cumplimiento de los entregables y el creador requiere confianza en que las condiciones acordadas serán respetadas.

**¿Cómo podemos desarrollar una plataforma que permita a las pymes gestionar campañas con creadores de forma estructurada, mientras proporciona a los creadores condiciones claras de colaboración y un mecanismo confiable para recibir su compensación?**

##### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

- Creemos que existe una necesidad de profesionalizar las colaboraciones entre pymes y creadores de contenido, debido a que actualmente gran parte del proceso se realiza mediante canales informales.

- Creemos que las pymes estarán dispuestas a utilizar CollabPro si pueden publicar campañas estructuradas, definir requisitos específicos y acceder posteriormente a métricas que les permitan evaluar el rendimiento de sus colaboraciones.

- Creemos que los creadores de contenido utilizarán CollabPro si pueden encontrar campañas relevantes, conocer claramente los requisitos antes de postular y contar con mayor seguridad respecto a las condiciones de compensación.

- Creemos que un sistema de validación de entregables y liberación de la compensación después del cumplimiento de las condiciones acordadas aumentará la confianza entre empresas y creadores.

- Creemos que el modelo SaaS mediante suscripción mensual será atractivo para las empresas si el costo de la plataforma es compensado por el ahorro de tiempo, la reducción de errores y la posibilidad de medir el rendimiento de sus campañas.

- Creemos que CollabPro puede diferenciarse de los canales tradicionales de colaboración al centralizar en una sola plataforma la publicación de campañas, postulación de creadores, gestión de entregables y seguimiento de métricas.

- Sabremos que estamos equivocados si las empresas abandonan la plataforma durante los primeros 60 días porque consideran que gestionar sus campañas mediante CollabPro no aporta suficiente valor frente a continuar utilizando Instagram, WhatsApp u otros canales tradicionales.

**User Assumptions**

- **¿Quién es el usuario?**

  Los principales usuarios son las pequeñas y medianas empresas que buscan promocionar sus productos o servicios mediante creadores de contenido y los creadores de contenido que buscan oportunidades de colaboración con marcas y negocios.

- **¿Dónde encaja nuestro producto en su vida?**

  Para las empresas, CollabPro encaja dentro de sus actividades de marketing y promoción digital, especialmente cuando necesitan planificar y ejecutar campañas con creadores.

  Para los creadores, la plataforma forma parte de su proceso para encontrar oportunidades comerciales, postular a campañas y gestionar los compromisos adquiridos con las empresas.

- **¿Qué problemas resuelve?**

  Reduce la informalidad en las colaboraciones, centraliza la comunicación y las condiciones de las campañas, estructura los entregables, facilita la validación del contenido y permite a las empresas consultar métricas para evaluar el rendimiento de sus colaboraciones.

- **¿Cuándo y cómo es usado?**

  Las empresas utilizan CollabPro cuando necesitan crear y administrar campañas con creadores, revisar postulaciones, establecer condiciones y analizar los resultados obtenidos.

  Los creadores utilizan la plataforma para descubrir campañas, revisar sus requisitos, postular, entregar el contenido solicitado y verificar el estado de sus colaboraciones.

- **¿Qué características son importantes?**

  Publicación de campañas estructuradas, definición de objetivos y entregables, postulación de creadores, gestión de compensaciones, validación de publicaciones, seguimiento de campañas y visualización de métricas de rendimiento.

- **¿Cómo debe verse y comportarse?**

  La plataforma debe presentar una interfaz limpia, profesional, responsiva, rápida y accesible (a11y), con una navegación intuitiva para usuarios con diferentes niveles de familiaridad tecnológica. Asimismo, debe proporcionar información clara sobre el estado de cada campaña, sus entregables y las acciones pendientes.

##### 1.2.2.3. Lean UX Hypothesis Statements

- **Hipótesis 1:** "Creemos que las empresas podrán reducir el tiempo y la incertidumbre asociados a la gestión de colaboraciones mediante el uso de campañas estructuradas que permitan definir objetivos, entregables, plazos y compensaciones.

  Sabremos que esto es verdad cuando al menos el 70% de las empresas que utilicen CollabPro completen la configuración de una campaña sin requerir asistencia externa durante las primeras 4 semanas de uso."

- **Hipótesis 2:** "Creemos que los creadores de contenido tendrán mayor claridad sobre las colaboraciones al disponer de campañas con requisitos y condiciones previamente definidos.

  Sabremos que esto es verdad cuando al menos el 75% de los creadores que postulen a una campaña revisen y acepten sus condiciones antes de iniciar la colaboración durante las primeras 4 semanas."

- **Hipótesis 3:** "Creemos que las empresas tendrán mayor confianza en las colaboraciones al contar con un mecanismo de validación de entregables antes de liberar la compensación acordada.

  Sabremos que esto es verdad cuando al menos el 80% de las colaboraciones finalizadas utilicen correctamente el proceso de validación antes de liberar la compensación durante los primeros 3 meses de operación."

- **Hipótesis 4:** "Creemos que las empresas percibirán mayor valor en CollabPro al poder consultar métricas centralizadas del rendimiento de las publicaciones realizadas por sus creadores contratados.

  Sabremos que esto es verdad cuando al menos el 70% de las empresas activas consulten el panel de métricas después de finalizar una campaña durante los primeros 3 meses de uso."

##### 1.2.2.4. Lean UX Canvas

![./assets/C01/LeanUX.png](./assets/C01/LeanUX.png)

### 1.3. Segmentos objetivo

CollabPro está dirigido a dos segmentos principales que forman parte del ecosistema del marketing de creadores de contenido.

- **Segmento 1: Pequeñas y Medianas Empresas (Pymes)**

  El primer segmento está conformado por pequeñas y medianas empresas que utilizan o desean utilizar las redes sociales como canal de promoción y adquisición de clientes. Dentro de este segmento pueden encontrarse restaurantes, tiendas, emprendimientos, marcas de productos, servicios profesionales y otros negocios que buscan aumentar su visibilidad mediante colaboraciones con creadores de contenido.

  Estas empresas pueden contar con recursos limitados para desarrollar campañas de marketing y, en muchos casos, gestionan directamente las colaboraciones con creadores mediante Instagram, WhatsApp u otros canales informales. Esta situación dificulta comparar propuestas, establecer condiciones claras, controlar los entregables y determinar si una colaboración generó resultados suficientes para justificar la inversión.

- **Segmento 2: Creadores de Contenido**

  El segundo segmento está conformado por creadores de contenido que utilizan plataformas digitales como Instagram, TikTok, YouTube u otras redes sociales para desarrollar y compartir contenido con sus comunidades.

  Dentro de este segmento pueden coexistir creadores pequeños y medianos, microcreadores especializados en determinados nichos y creadores que buscan establecer relaciones comerciales con marcas y negocios. A pesar de sus diferencias en tamaño y alcance, todos comparten la necesidad de encontrar oportunidades de colaboración y conocer claramente las condiciones antes de aceptar una campaña.

---

## Capítulo II: Requirements Development and Software Solution Design

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

El análisis considera competidores directos que conectan marcas con creadores o gestionan ese ciclo de campaña. La comparación se construyó a partir de las funcionalidades y condiciones publicadas en los sitios oficiales de cada empresa (consultados el 12 de septiembre de 2026); por ello, las debilidades y oportunidades son inferencias competitivas para el segmento de pymes de Lima y deben validarse con entrevistas y pruebas de mercado.

| Competitive analysis landscape              | CollabPro                                                                                                                                                                                                                                     | BrandMe                                                                                                                                                                           | SocialPubli                                                                                                                                                        | Influencity                                                                                                                                                                   |
| :------------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Overview**                                | Marketplace B2B para que pymes publiquen campañas y los creadores postulen. Centraliza objetivos, entregables, plazos, compensación, validación y métricas.                                                                                   | Hub de influencer marketing: buscador, análisis de perfiles, gestión y medición de campañas; combina software, marketplace y servicio gestionado.                                 | Plataforma de influencer marketing para crear campañas, analizar perfiles, seleccionar creadores y aprobar publicaciones antes de su difusión.                     | Plataforma SaaS de gestión de influencers: descubrimiento, CRM, campañas, briefs, entregables, pagos, reportes y social listening. Declara no ser un marketplace.             |
| **Ventaja competitiva / valor ofrecido**    | Flujo simple y trazable diseñado desde el problema de la pyme: campaña estructurada, aceptación explícita de condiciones, evidencia de entrega y liberación de compensación tras validación. Enfoque inicial en creadores y negocios de Lima. | Escala, datos y experiencia: su sitio declara más de 750 000 influencers y empresas; ofrece filtros, análisis de autenticidad/audiencia, automatización y servicios expertos.     | Facilita campañas con creadores de distinto tamaño —incluidos nano y microinfluencers— y permite controlar/aprobar el avance antes de publicar.                    | Suite internacional con una base declarada de más de 300 millones de perfiles, filtros de audiencia, automatización y analítica de desempeño en tiempo real.                  |
| **Mercado objetivo**                        | Pymes urbanas de Lima que realizan o desean realizar marketing con creadores y microcreadores que buscan acuerdos claros.                                                                                                                     | Marcas y agencias de habla hispana e internacionales que requieren software o ejecución experta de campañas.                                                                      | Marcas, empresas y anunciantes que buscan ejecutar campañas con creadores de redes sociales; atiende desde nano hasta megainfluencers.                             | Marcas, agencias y equipos de marketing que gestionan campañas a escala y necesitan un repositorio global de creadores.                                                       |
| **Estrategias de marketing**                | Captación bilateral local: pilotos con pymes, referidos de creadores y contenido educativo sobre campañas, brief y cumplimiento. Prueba social basada en casos locales.                                                                       | Marketing de contenidos, comunidad de creadores, prueba/demo del software, planes de membresía y venta consultiva de servicios completos.                                         | Promoción de la plataforma como medio para crear, gestionar y medir campañas; enfatiza beneficios del influencer marketing y oportunidades de pago para creadores. | Prueba o demo del SaaS, contenido especializado y posicionamiento como plataforma integral para marcas y agencias; presencia internacional.                                   |
| **Productos y servicios**                   | Publicación y postulación a campañas; definición de requisitos, entregables, plazo y compensación; seguimiento de estado; validación antes de liberar la compensación; panel de métricas e historial.                                         | BrandMe Finder, análisis de cuentas, suite de campañas y métricas, marketplace de propuestas y servicios personalizados.                                                          | Creación de campañas, selección/análisis de influencers, seguimiento y aprobación de publicaciones; campañas en redes sociales.                                    | Descubrimiento y análisis de creadores, IRM/CRM, outreach, campañas, seguimiento de contenido, pagos, reportes, social media management y social listening.                   |
| **Precios y costos**                        | Modelo SaaS de suscripción mensual para empresas, pendiente de validación de precio. La modalidad de cobro por tipo de usuario y la compensación de cada campaña se definirán y validarán con los pilotos.                                    | Plan gratuito limitado y plan Marca Premium publicado a US$150 mensuales (US$1 560 anuales); los servicios gestionados se cotizan por propuesta.                                  | No publica una tarifa única en la página de campañas; el presupuesto depende de la campaña y de los creadores seleccionados.                                       | No publica una tarifa estándar en su página de plataforma; invita a solicitar prueba o demo.                                                                                  |
| **Canales de distribución (web y/o móvil)** | Plataforma web responsiva; captación mediante redes sociales, alianzas con comunidades de emprendimiento y creadores, y referidos.                                                                                                            | Plataforma web, demostraciones, servicio consultivo y comunidad digital de creadores.                                                                                             | Plataforma web para marcas y creadores; captación por contenido y presencia en redes sociales.                                                                     | Plataforma web/SaaS, prueba o demo, contenidos y ventas dirigidas a equipos de marketing y agencias.                                                                          |
| **FODA: fortalezas**                        | Propuesta enfocada en reducir la informalidad: condiciones visibles, entregables verificables y compensación condicionada. Especialización inicial en la realidad operativa de las pymes de Lima.                                             | Ecosistema amplio de creadores y marcas, capacidades de búsqueda, medición y acompañamiento experto.                                                                              | Modelo de conexión marca-creador y mecanismo de aprobación previa a la publicación.                                                                                | Cobertura funcional muy amplia, datos globales y automatización para operaciones complejas.                                                                                   |
| **FODA: debilidades**                       | Startup en etapa temprana: red de usuarios, reputación, integración de pagos y datos históricos aún deben construirse y validarse.                                                                                                            | Para una pyme local, el plan Premium y la amplitud de funciones pueden representar una barrera de presupuesto o aprendizaje; su propuesta no se especializa públicamente en Lima. | La información pública se centra en la campaña y no detalla una propuesta localizada para pymes peruanas ni un flujo de liberación condicionada de pagos.          | No es un marketplace: la marca debe identificar y gestionar la relación con creadores; su amplitud funcional puede exceder las necesidades y capacidades de una pyme inicial. |
| **FODA: oportunidades**                     | Convertir la coordinación informal de Instagram/WhatsApp en un flujo confiable para microcampañas; construir una red local de microcreadores por rubro y generar datos de desempeño relevantes para pymes.                                    | Profundizar su presencia y alianzas locales en Perú, aprovechando la demanda de marketing de creadores en Latinoamérica.                                                          | Aumentar la oferta de campañas de micro y nanocreadores y facilitar presupuestos de entrada para pequeños negocios.                                                | Traducir su capacidad global en ofertas accesibles para pymes y ampliar el soporte/localización para mercados latinoamericanos.                                               |
| **FODA: amenazas**                          | Efectos de red y recursos de plataformas consolidadas; dependencia de APIs y reglas de redes sociales; desintermediación por acuerdos directos fuera de la plataforma; riesgos de fraude o incumplimiento.                                    | Competencia de suites globales y marketplaces especializados; cambios en datos disponibles por las redes sociales y presión de precios en autoservicio.                           | Competencia de marketplaces con mayor analítica, CRM o localización; cambios en políticas de plataformas sociales y confianza en la calidad de creadores.          | Marketplaces que ofrecen una red cerrada de creadores y servicio gestionado; cambios en acceso a datos de redes sociales y presión por herramientas más simples y económicas. |

**Lectura del landscape.** BrandMe es el competidor directo de mayor alcance porque combina marketplace, gestión de campañas y servicios; SocialPubli compite por el flujo de campañas y su acceso a microcreadores; Influencity representa la referencia funcional de una suite de gestión. CollabPro no debe intentar igualar su escala inicial. Su ventaja defendible a corto plazo es resolver con menor fricción la colaboración de bajo y mediano presupuesto entre pymes y microcreadores locales, haciendo visibles las condiciones y el estado de cumplimiento.

#### 2.1.2. Estrategias y tácticas frente a competidores

La estrategia competitiva inicial será **especialización local + confianza operativa + simplicidad**. En lugar de competir por una base global de millones de perfiles o por una suite empresarial completa, CollabPro buscará ser la alternativa más clara y asequible para una pyme de Lima que ejecuta sus primeras campañas con creadores.

| Estrategia                                                   | Tácticas preliminares                                                                                                                                                                                                                                                                                                 | Fortaleza/debilidad competitiva que aborda                                                                                                                 | Indicador de validación                                                                                                           |
| :----------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| **1. Diferenciación por confianza y cumplimiento**           | Implementar una ficha de campaña obligatoria con objetivo, entregables, fecha, compensación y criterios de aceptación; registrar evidencias de entrega/publicación; usar una secuencia visible de “pendiente–en revisión–aprobado–compensación liberada”; habilitar calificación bilateral y un canal de incidencias. | Responde a la informalidad que CollabPro busca resolver y evita competir solo por volumen de creadores frente a BrandMe o Influencity.                     | Al menos 80% de colaboraciones finalizadas pasan por validación antes de liberar la compensación durante los primeros tres meses. |
| **2. Entrada asequible para pymes**                          | Ofrecer plan piloto o freemium con una campaña; diseñar planes mensuales por número de campañas activas, no por funcionalidades complejas; transparentar desde el brief el presupuesto y la compensación; medir disposición a pagar antes de fijar el precio definitivo.                                              | Contrarresta la posible barrera de costo y complejidad de suites premium; reconoce que SocialPubli y BrandMe ya poseen alternativas gratuitas o variables. | 75% de pymes piloto completa su primera campaña y al menos 30% declara intención de continuar con un plan pagado.                 |
| **3. Densidad de oferta local y microcreadores verificados** | Lanzar por verticales con alta presencia local (gastronomía, belleza, retail y servicios); captar 20–30 creadores por vertical mediante referidos; verificar identidad, ciudad, red social y portafolio; mostrar etiquetas de nicho, distrito y tipo de compensación.                                                 | Reduce la desventaja inicial de red frente a los catálogos globales de BrandMe e Influencity y mejora la relevancia para una pyme limeña.                  | Por cada campaña piloto, obtener al menos cinco postulaciones pertinentes y concretar una colaboración en un máximo de 14 días.   |
| **4. Onboarding guiado y educación práctica**                | Usar plantillas de brief, entregables y criterios de aceptación; asistente de creación de campaña en pocos pasos; guías cortas sobre publicidad con influencers y buenas prácticas de disclosure; soporte por chat durante las primeras campañas.                                                                     | Aprovecha la oportunidad de atender negocios sin especialista de marketing y reduce la curva de aprendizaje de herramientas empresariales amplias.         | 70% de las empresas crea una campaña sin asistencia externa en sus primeras cuatro semanas.                                       |
| **5. Métricas accionables, no solo reportes**                | Mostrar un tablero por campaña con publicaciones verificadas, alcance, interacción, costo por resultado y comparación con campañas previas; pedir a la pyme definir una métrica principal antes de publicar; usar enlaces o códigos rastreables cuando corresponda.                                                   | Equipara el valor analítico que ofrecen los competidores, pero lo presenta en un nivel comprensible para pymes.                                            | 70% de empresas activas consulta el tablero después de finalizar una campaña y puede identificar su métrica principal.            |
| **6. Retención y defensa frente a la desintermediación**     | Mantener dentro de la plataforma el historial de campañas, plantillas, evidencia, evaluación y métricas; ofrecer beneficios por colaboración recurrente, no penalizaciones; realizar recordatorios de plazos y renovaciones de campaña.                                                                               | Mitiga la amenaza de que marca y creador vuelvan a negociar por mensajes directos después de conocerse.                                                    | Alcanzar que 40% de las empresas piloto cree una segunda campaña y que 25% repita con un creador evaluado positivamente.          |

Estas tácticas deben priorizarse como un MVP: primero campaña estructurada, postulación, validación y tablero básico; después, reputación, pagos integrados, automatización y expansión geográfica. Así se evita replicar prematuramente las suites completas de los competidores y se valida la propuesta de valor central de CollabPro.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

- **Segmento 1: Pequeñas y Medianas Empresas**

1. ¿Actualmente utilizan redes sociales para promocionar su negocio? ¿Cuáles utilizan principalmente?
2. ¿Han realizado alguna colaboración con un creador de contenido o influencer? Cuéntame cómo fue esa experiencia.
3. ¿Cómo encuentran actualmente a los creadores con los que trabajan?
4. ¿Cómo suelen negociar las condiciones de una colaboración, como precio, productos, publicaciones, fechas y entregables?
5. ¿Alguna vez han tenido problemas porque un creador no entregó el contenido acordado, lo publicó tarde o no cumplió con los requisitos? ¿Qué ocurrió?
6. ¿Cómo verifican actualmente que una colaboración cumplió con lo que habían acordado?
7. Después de realizar una colaboración, ¿cómo determinan si realmente valió la pena la inversión? ¿Qué métricas revisan?
8. ¿Qué es lo que más tiempo o esfuerzo les toma cuando trabajan con creadores?
9. Si pudieran mejorar una sola cosa del proceso actual de trabajar con creadores, ¿qué cambiarían?
10. ¿Estarían dispuestos a pagar una suscripción mensual por una plataforma que les permita encontrar creadores, estructurar campañas, controlar entregables y medir resultados? ¿Qué tendría que ofrecer para que consideren que vale la pena pagar?

- **Segmento 2: Creadores de Contenido**

1. ¿Actualmente creas contenido en redes sociales? ¿En cuáles y qué tipo de contenido produces?
2. ¿Has realizado colaboraciones pagadas o mediante intercambio de productos con alguna marca o negocio? Cuéntame sobre la última.
3. ¿Cómo suelen llegar actualmente las propuestas de colaboración?
4. ¿Qué información te proporciona normalmente una empresa cuando te propone una colaboración?
5. ¿Alguna vez has aceptado una colaboración y posteriormente descubriste que los requisitos eran diferentes a lo que esperabas? ¿Qué ocurrió?
6. ¿Has tenido problemas con empresas respecto al pago, productos ofrecidos, cambios en los requisitos o fechas de entrega?
7. Antes de aceptar una colaboración, ¿qué información consideras indispensable conocer?
8. ¿Qué dificultades tienes actualmente para encontrar marcas o negocios que realmente encajen con tu contenido y audiencia?
9. ¿Qué opinas de un sistema donde puedas ver campañas disponibles, revisar sus requisitos antes de postular y conocer claramente la compensación? ¿Qué ventajas o problemas tendría para ti?
10. ¿Qué tendría que ofrecer una plataforma de este tipo para que prefieras utilizarla en lugar de negociar directamente por Instagram o WhatsApp?

#### 2.2.2. Registro de entrevistas

###### **Segmento 1: Pequeñas y Medianas Empresas (Pymes)**

**Entrevista 1: Frank Loayza**

| Campo                             | Detalle                                                        |
| --------------------------------- | -------------------------------------------------------------- |
| **Nombre y Apellidos**            | Frank Loayza                                                   |
| **Edad**                          | 24                                                             |
| **Distrito / Zona de residencia** | Santiago de Surco                                              |
| **Segmento**                      | Pequeñas y Medianas Empresas (Pymes)                           |
| **Inicio en video**               | 0:00                                                           |
| **Fin de video**                  | 14:30                                                          |
| **Duración**                      | 14:30                                                          |
| **URL del video**                 | [https://youtu.be/dvb_GWTTWyg](https://youtu.be/dvb_GWTTWyg)   |
| **Screenshot**                    | ![Entrevista Frank](./assets//C02/Entrevistas/FrankLoayza.png) |

##### Resumen Descriptivo de la Entrevista

###### Características Objetivas y Entorno

Frank es un joven emprendedor que, junto con un socio, dirige desde hace más de un año un negocio de makis y sushi operado exclusivamente bajo el formato de dark kitchen o full delivery (sin atención en mesa). El negocio cuenta con un catálogo de más de 20 variedades y tiene a dos empleados adicionales.

El 80% de su público objetivo está compuesto por clientes jóvenes, por lo que su estrategia de exposición digital se centra en plataformas como TikTok e Instagram, descartando Facebook por considerarlo para un segmento de mayor edad.

###### Herramientas y Proceso Actual

Actualmente, el manejo del marketing y la creación de contenido se realizan de manera empírica. El negocio no emplea plataformas formales para contactar influencers ni agencias de publicidad.

El proceso actual se basa en:

- Creación de contenido orgánico y casero con los propios trabajadores.
- Contacto informal con conocidos o "amigos de amigos" de la etapa universitaria que poseen cierta audiencia (ej. 8,000 seguidores en Instagram).
- Negociación directa vía mensajes (DM) para realizar "canjes": a cambio de productos (ej. 72 cortes de makis), el creador publica historias promocionales.
- El seguimiento de resultados se hace observando empíricamente el aumento de visualizaciones, likes, comentarios y percibiendo si hay un ligero pico de demanda temporal en los días posteriores a la publicación.

###### Problemas Detectados (Pain Points)

El entrevistado expone limitaciones claras en su proceso de marketing de influencers:

- **Red de contactos limitada:** Al depender de amigos, es difícil escalar la exposición o encontrar creadores nuevos de forma constante.
- **Dificultad de segmentación (Match):** Considera "una gestión tremenda" encontrar perfiles de creadores cuya audiencia haga match exacto con su público objetivo juvenil.
- **Falta de tiempo:** Al ser dos socios liderando la empresa en fase de arranque, están enfocados en la operación y desarrollo del producto, relegando la búsqueda de influencers.
- **Presupuesto restringido:** No cuentan con capital para inversiones grandes o contrataciones formales recurrentes.

###### Necesidades y Oportunidades

Frank muestra interés en profesionalizar su búsqueda de creadores, pero requiere herramientas que se adapten a la realidad de un negocio emergente.

Valora positivamente una plataforma que le ofrezca:

- Un espacio (Marketplace) para recibir postulaciones de creadores alineados a su nicho, sin tener que buscarlos manualmente.
- Herramientas integradas para medir con precisión las métricas de rendimiento (vistas, interacción) y controlar los entregables.
- Opciones de pago justas, mostrando preferencia inicial por modelos de pago basados en resultados (pago por interacción, vistas o rendimiento) en lugar de cargos fijos.

###### Aspectos Subjetivos y Comportamiento

Frank es un emprendedor cauteloso con los gastos y fuertemente enfocado en el núcleo de su negocio operativo. Su toma de decisiones es pragmática y consensuada (siempre consulta con su socio).

Es receptivo a probar nuevas tecnologías o plataformas, pero exige que la herramienta demuestre su valor agregado, especialmente en el área analítica (métricas exactas que le eviten hacer estimaciones manuales).

No busca fama inmediata, sino exposición rentable y dirigida exclusivamente al nicho universitario/juvenil.

###### Tecnología y Riesgos Percibidos

El riesgo principal que percibe Frank frente a la propuesta de valor es el modelo de negocio por suscripción mensual.

Para un emprendimiento en fase de crecimiento y con poco capital sobrante, asumir un costo fijo mensual solo para acceder a una plataforma de contacto representa una barrera de entrada alta.

Estaría dispuesto a evaluar la herramienta y pagar si se le demuestra que la automatización, las métricas y la calidad de los creadores compensan el gasto de la suscripción mensual.

###### Validación del Arquetipo

Los hallazgos validan el arquetipo del **Emprendedor de Pequeña Empresa con Recursos Limitados**.

Se confirma que este segmento reconoce el valor del marketing de influencers, pero necesita soluciones que reduzcan la fricción de gestión (tiempo) y ofrezcan modelos de entrada de bajo riesgo financiero.

Esto respalda la necesidad de desarrollar funciones dentro de la plataforma enfocadas en:

- **Algoritmos de Matchmaking preciso por nicho de mercado:** filtros por audiencia joven/delivery.
- **Panel de control automatizado para medir ROI (Retorno de Inversión):** mediante vistas e interacciones.
- **Flexibilidad en los modelos de contratación:** canjes estandarizados, pagos por resultados o suscripciones escalables adaptadas a pymes.

##### Entrevista 2: Andy Pillaca

| Campo                             | Detalle                                                                                                                                          |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Nombre y Apellidos**            | Andy Pillaca                                                                                                                                     |
| **Edad**                          | 29                                                                                                                                               |
| **Distrito / Zona de residencia** | Santiago de Surco                                                                                                                                |
| **Segmento**                      | Pequeñas y Medianas Empresas (Pymes)                                                                                                             |
| **Inicio en video**               | 0:00                                                                                                                                             |
| **Fin de video**                  | 4:23                                                                                                                                             |
| **Duración**                      | 4:23                                                                                                                                             |
| **URL del video**                 | [https://drive.google.com/file/d/1z8S2-whw5Wi0ZabnAjMTSdbTEb_XWkOh/view](https://drive.google.com/file/d/1z8S2-whw5Wi0ZabnAjMTSdbTEb_XWkOh/view) |
| **Screenshot**                    | ![Entrevista Andy](./assets/C02/Entrevistas/Andy.png)                                                                                            |

###### Resumen Descriptivo de la Entrevista

###### Características Objetivas y Entorno

Andy forma parte del personal encargado del marketing de una pequeña empresa que utiliza activamente las redes sociales para promocionar sus productos. La empresa mantiene presencia principalmente en Instagram, Facebook y TikTok, canales mediante los cuales busca incrementar su alcance y llegar a nuevos clientes.

La empresa cuenta con experiencia previa realizando colaboraciones con diferentes creadores de contenido, incluyendo streamers. Por ello, el entrevistado conoce directamente las dificultades asociadas con la búsqueda, coordinación, seguimiento y evaluación de este tipo de campañas.

###### Herramientas y Proceso Actual

Actualmente, la empresa encuentra potenciales colaboradores principalmente mediante redes sociales y recomendaciones de otras personas. Antes de trabajar con un creador, intentan conocer referencias sobre su responsabilidad, puntualidad y cumplimiento de compromisos anteriores.

La negociación de las colaboraciones se realiza principalmente mediante mensajes y llamadas. Durante estas conversaciones se establecen aspectos como:

- Precio o compensación de la colaboración.
- Tipo de contenido que deberá producirse.
- Fechas de publicación.
- Condiciones generales de la colaboración.

Una vez iniciada la campaña, el seguimiento se realiza de manera manual. El personal revisa las publicaciones realizadas por el creador para comprobar si se respetaron los contenidos y fechas acordadas.

Después de finalizar una colaboración, la empresa analiza principalmente las visualizaciones, interacciones y seguidores obtenidos. Cuando existe la posibilidad de relacionar directamente una campaña con ventas, también utilizan las ventas generadas como indicador de rendimiento.

###### Problemas Detectados (Pain Points)

Durante la entrevista se identificaron los siguientes problemas principales:

- **Coordinación dispersa:** La comunicación con los creadores se realiza mediante diferentes mensajes y llamadas, dificultando mantener toda la información organizada.
- **Dificultad para encontrar creadores adecuados:** La empresa dedica tiempo a buscar perfiles que, además de ser relevantes para la marca, sean responsables y cumplan con los plazos establecidos.
- **Incumplimiento de fechas:** El entrevistado recordó una situación en la que un creador publicó el contenido después de la fecha acordada, obligando a la empresa a insistir para conseguir el cumplimiento.
- **Seguimiento manual:** La verificación de publicaciones, contenido y fechas se realiza manualmente.
- **Información distribuida:** Los acuerdos y el seguimiento de una campaña pueden encontrarse repartidos entre diferentes conversaciones y medios de comunicación.
- **Esfuerzo operativo elevado:** Buscar al creador adecuado y supervisar sus entregables son las actividades que consumen mayor tiempo.

###### Necesidades y Oportunidades

Andy identifica como principal oportunidad la posibilidad de **centralizar todo el proceso de colaboración en un único lugar**.

De acuerdo con sus respuestas, una solución de este tipo debería facilitar:

- La búsqueda de creadores de contenido.
- La estructuración de campañas.
- El registro de las condiciones acordadas.
- El seguimiento de entregables y fechas.
- La verificación del cumplimiento.
- La visualización de métricas de rendimiento.
- La medición de resultados obtenidos después de cada campaña.

Esta necesidad coincide directamente con la propuesta de CollabPro de reemplazar la coordinación distribuida en redes sociales, mensajes y llamadas por un proceso estructurado y trazable.

###### Aspectos Subjetivos y Comportamiento

El entrevistado demuestra especial preocupación por la responsabilidad y puntualidad de los creadores. Al momento de seleccionar un colaborador, no considera únicamente su alcance en redes sociales, sino también referencias sobre su comportamiento en colaboraciones anteriores.

Asimismo, la empresa parece mantener un proceso de marketing orientado a resultados, ya que después de una campaña revisa diferentes indicadores como visualizaciones, interacciones, crecimiento de seguidores y, cuando es posible, ventas generadas.

Andy considera que una herramienta especializada podría aportar valor si efectivamente reduce el esfuerzo requerido para administrar las campañas.

###### Disposición de Pago y Riesgos Percibidos

El entrevistado manifestó que la empresa estaría dispuesta a pagar una suscripción mensual por una plataforma especializada siempre que esta permita ahorrar tiempo, controlar las campañas y medir sus resultados.

Sin embargo, también señaló como condición importante que los precios sean accesibles para el contexto de una pequeña empresa.

Esto demuestra que existe interés por un modelo de suscripción, pero que la disposición de pago dependerá de dos factores:

1. Que la plataforma demuestre un ahorro real de tiempo y esfuerzo.
2. Que el precio se encuentre dentro de las posibilidades económicas de una pyme.

###### Validación del Arquetipo

La entrevista con Andy refuerza el arquetipo de la **Pyme que necesita profesionalizar la gestión de sus colaboraciones con creadores**.

A diferencia de un negocio que recién comienza a experimentar con influencer marketing, la empresa entrevistada ya ha realizado varias colaboraciones. Sin embargo, continúa gestionando actividades importantes mediante mensajes, llamadas y verificaciones manuales.

Los hallazgos respaldan especialmente el desarrollo de funcionalidades relacionadas con:

- **Marketplace y búsqueda de creadores**, incluyendo información que ayude a determinar su confiabilidad.
- **Campañas estructuradas** con requisitos, entregables, fechas y compensaciones claramente establecidas.
- **Seguimiento de entregables** y estados de cumplimiento.
- **Historial o reputación del creador**, que permita conocer su desempeño previo.
- **Panel de métricas**, incluyendo visualizaciones, interacciones, seguidores y resultados comerciales cuando puedan ser medidos.
- **Centralización de la comunicación y coordinación** de cada colaboración.
- **Planes de precios accesibles para pequeñas empresas.**

**Entrevista 3: Jorge Altamirano**

| Campo                             | Detalle                                                        |
| --------------------------------- | -------------------------------------------------------------- |
| **Nombre y Apellidos**            | Jorge Luis Altamirano                                          |
| **Edad**                          | 28                                                             |
| **Distrito / Zona de residencia** | San Borja                                                      |
| **Segmento**                      | Pequeñas y Medianas Empresas (Pymes)                           |
| **Inicio en video**               | 0:00                                                           |
| **Fin de video**                  | 11:12                                                          |
| **Duración**                      | 11:12                                                          |
| **URL del video**                 | [https://youtu.be/EhL1vlqkHbM](https://youtu.be/EhL1vlqkHbM)   |
| **Screenshot**                    | ![Entrevista Jorge](./assets/C02/Entrevistas/JorgeLuis.png)   |

###### Resumen Descriptivo de la Entrevista

###### Características Objetivas y Entorno

Jorge Marmolejo Altamirano es técnico en cocina y actualmente se desempeña como chef en restaurantes de hoteles. Su experiencia con colaboraciones se desarrolla principalmente dentro del sector gastronómico, mediante actividades conjuntas con otros chefs.

El entorno en el que trabaja está vinculado al turismo y presenta temporadas de alta y baja demanda. Durante las temporadas bajas, busca generar ideas y estrategias que permitan atraer al público local, al que considera más difícil de captar.

Utiliza principalmente Instagram para compartir preparaciones, procesos, productos y proveedores. También menciona el uso de esta red social para difundir eventos gastronómicos mediante publicaciones y piezas promocionales.

###### Herramientas y Proceso Actual

Las colaboraciones se establecen principalmente a través de contactos y grupos sociales del entorno gastronómico de la capital. Estos espacios permiten conocer a otros profesionales, intercambiar ideas y organizar actividades conjuntas.

Jorge menciona experiencias con chefs como Jorge Muñoz y Renzo Miñán. Estas colaboraciones incluyen la creación o adaptación de platos, combinando estilos culinarios y conocimientos sobre productos y cocina regional.

El proceso actual comprende las siguientes actividades:

- **Selección mediante contactos profesionales:** Encuentran colaboradores dentro de los círculos gastronómicos en los que participan.
- **Planificación conjunta:** Coordinan con anticipación e intercambian propuestas para definir los platos y la dinámica del evento.
- **Compensación mediante canjes:** Ofrecen beneficios del hotel, como desayunos, promociones de alojamiento o descuentos, a cambio de la colaboración.
- **Promoción del evento:** Difunden la actividad principalmente mediante Instagram.
- **Seguimiento previo:** Mantienen comunicación frecuente durante la última semana, con aproximadamente tres reuniones y una hora de llegada acordada para el día del evento.
- **Evaluación posterior:** Revisan las ventas del turno y las reservas recibidas mediante la página del restaurante e Instagram.

Los resultados comerciales también les permiten decidir si conviene volver a trabajar con un determinado chef.

###### Problemas Detectados (Pain Points)

Durante la entrevista se identificaron las siguientes dificultades:

- **Cancelaciones después de iniciar la promoción:** Jorge relata que un chef canceló su participación aproximadamente entre una semana y diez días antes de un evento, cuando la publicidad ya estaba difundida. Fue necesario conseguir un reemplazo para cumplir con lo anunciado a los clientes.
- **Dificultad para adaptar las formas de trabajo:** Cada chef tiene métodos y necesidades diferentes. Ajustar la operación del restaurante a un colaborador por un solo día exige esfuerzo adicional.
- **Duración limitada de las colaboraciones:** Considera que una jornada resulta insuficiente para integrarse con el chef invitado y desarrollar todas las ideas que podrían surgir del trabajo conjunto.
- **Carga de gestión:** Señala que concentrar la captación de clientes, las redes sociales y otros aspectos de la operación en una sola persona puede generar estrés.
- **Captación del público local en temporada baja:** El restaurante necesita desarrollar propuestas que mantengan el interés y la demanda cuando disminuye la actividad turística.

El seguimiento del cumplimiento se apoya principalmente en reuniones, comunicación y confirmación de la participación. El entrevistado no describe un sistema específico para controlar publicaciones o entregables digitales.

###### Necesidades y Oportunidades

Jorge propone ampliar las colaboraciones a una semana para lograr una mayor integración con el profesional invitado. Durante ese periodo, le gustaría compartir ideas, recorrer mercados y visitar lugares que contribuyan al desarrollo de nuevas propuestas gastronómicas.

También valora una plataforma que apoye la gestión del marketing, las redes sociales y las reservas, reduciendo la carga que estas actividades representan para una sola persona.

A partir de estas necesidades, se identifican oportunidades para CollabPro:

- **Registro de acuerdos y compensaciones:** Documentar los beneficios ofrecidos mediante canje y los compromisos de cada participante.
- **Organización de fechas y actividades:** Facilitar la planificación de reuniones, jornadas de trabajo y eventos.
- **Seguimiento de compromisos:** Mantener visibles las confirmaciones y tareas pendientes antes de la colaboración.
- **Historial de colaboraciones:** Consultar los resultados de experiencias anteriores para orientar futuras decisiones.
- **Medición de resultados comerciales:** Registrar ventas y reservas asociadas al evento, indicando las limitaciones para atribuirlas directamente a la colaboración.

Estas funcionalidades podrían apoyar la coordinación descrita por Jorge. Sin embargo, sus expectativas también incluyen asistencia en redes sociales y reservas, aspectos que deben contrastarse con el alcance previsto de CollabPro.

###### Aspectos Subjetivos y Comportamiento

Jorge muestra una orientación hacia el trabajo colaborativo y el intercambio de conocimientos. Valora que los chefs puedan combinar sus estilos, compartir experiencias y crear propuestas que ayuden al restaurante a mantenerse al tanto de las tendencias gastronómicas.

También demuestra preocupación por cumplir con lo anunciado al cliente. Frente a la cancelación de un colaborador, priorizó encontrar una solución que permitiera realizar el evento.

Su evaluación de las colaboraciones se centra en resultados comerciales, especialmente ventas y reservas. Estos indicadores influyen en la decisión de repetir una experiencia con el mismo chef.

Asimismo, considera importante disponer de más tiempo para conocer la forma de trabajo del colaborador e integrarlo a la operación del restaurante.

###### Disposición de Pago y Riesgos Percibidos

Jorge expresa una valoración positiva de una plataforma que facilite el marketing y apoye la gestión de redes sociales y reservas. Considera que este tipo de herramienta podría agilizar el trabajo y reducir el estrés operativo.

No obstante, su respuesta no confirma explícitamente que pagaría una suscripción mensual ni establece un presupuesto. Por ello, la entrevista evidencia interés en la solución, pero no permite dar por validada su disposición de pago.

La principal condición de valor identificada es que la plataforma brinde apoyo práctico en la gestión diaria. Será necesario comprobar si las funciones de CollabPro responden a esa expectativa y qué precio estaría dispuesto a asumir.

###### Validación del Arquetipo

La entrevista aporta evidencia sobre el perfil de un **responsable gastronómico con experiencia en colaboraciones que busca mejorar su coordinación y evaluar sus resultados comerciales**.

Su experiencia coincide parcialmente con el segmento empresarial de CollabPro, porque participa en la promoción de un restaurante y en la gestión de colaboraciones. Sin embargo, la entrevista no precisa el tamaño de la empresa, por lo que no permite confirmar su clasificación como pyme.

Además, las colaboraciones descritas se concentran en eventos y creación conjunta de platos con chefs. Aunque incluyen promoción en Instagram, no corresponden necesariamente a campañas centradas en la producción de contenido digital.

Los hallazgos respaldan especialmente la exploración de funcionalidades relacionadas con:

- **Acuerdos estructurados**, incluyendo compensaciones mediante canjes.
- **Calendarios y seguimiento de compromisos**, para organizar la participación de los colaboradores.
- **Registro de confirmaciones y cambios**, para responder oportunamente ante cancelaciones.
- **Historial de colaboraciones y resultados**, para apoyar la selección de futuros participantes.
- **Indicadores comerciales**, especialmente ventas y reservas de los eventos.

La entrevista ofrece una validación parcial de la propuesta de CollabPro y muestra la necesidad de distinguir entre colaboraciones gastronómicas presenciales y campañas con entregables de contenido.

###### **Segmento 2: Creadores de Contenido**

**Entrevista 1: Luis Ángel**

| Campo                             | Detalle                                                           |
| --------------------------------- | ----------------------------------------------------------------- |
| **Nombre y Apellidos**            | Luis Ángel                                                        |
| **Edad**                          | 20                                                   |
| **Distrito / Zona de residencia** | Santiago de Surco                                                   |
| **Segmento**                      | Creadores de Contenido                                            |
| **Inicio en video**               | 0:00                                                              |
| **Fin de video**                  | 8:45                                                              |
| **Duración**                      | 8:45                                                              |
| **URL del video**                 | [https://www.youtube.com/watch?v=vipJiRQga7c](https://www.youtube.com/watch?v=vipJiRQga7c)                    |
| **Screenshot**                    | ![Entrevista Luis Ángel](./assets/C02/Entrevistas/LuisAngel.png)  |

##### Resumen Descriptivo de la Entrevista

###### Características Objetivas y Entorno

Luis Ángel es estudiante y barbero, y crea contenido relacionado principalmente con su actividad profesional. En sus redes sociales publica trabajos de barbería, cortes, diseños y recomendaciones relacionadas con el cuidado del cabello.

Su contenido se encuentra vinculado principalmente al sector de belleza y cuidado personal, por lo que las colaboraciones que considera relevantes deben guardar relación con este nicho y ser coherentes con los intereses de su audiencia.

Cuenta con experiencia previa realizando colaboraciones mediante intercambio de productos. En una de ellas recibió una línea de ceras para el cabello con el objetivo de probar los productos y posteriormente compartir una opinión sincera sobre ellos.

###### Herramientas y Proceso Actual

Actualmente, las propuestas de colaboración suelen llegar principalmente mediante mensajes directos en redes sociales, especialmente Instagram y TikTok.

Cuando una empresa se comunica con él, normalmente primero se presenta como marca, explica brevemente quién es y posteriormente comunica la propuesta de colaboración.

El proceso actual se basa en:

- Recepción de propuestas mediante mensajes directos en Instagram o TikTok.
- Revisión de la información proporcionada por la empresa sobre la colaboración.
- Identificación del tipo de compensación ofrecida, ya sea mediante dinero, productos u otra modalidad.
- Búsqueda de referencias de otros creadores que hayan colaborado previamente con la marca.
- Verificación de que la empresa sea legítima antes de aceptar una propuesta.
- Revisión de las condiciones y detalles específicos de la colaboración.

###### Problemas Detectados (Pain Points)

El entrevistado expone limitaciones relacionadas principalmente con la transparencia y confiabilidad de las propuestas:

- **Información incompleta:** Algunas empresas no comunican desde el inicio toda la información necesaria sobre la colaboración.
- **Falta de transparencia:** Considera que una de las principales dificultades consiste en determinar si una empresa comunica claramente todas sus condiciones.
- **Necesidad de investigación adicional:** Debe buscar referencias por su cuenta para comprobar si una marca es legítima y confiable.
- **Problemas con fechas:** Aunque no ha tenido inconvenientes graves con pagos o productos, sí ha experimentado algunas dificultades relacionadas con las fechas de entrega.
- **Riesgo reputacional:** Recomendar productos que no sean de buena calidad podría perjudicar la confianza de su audiencia.
- **Tiempo invertido en búsqueda:** Encontrar marcas realmente interesadas y compatibles con su contenido requiere tiempo y esfuerzo.

###### Necesidades y Oportunidades

Luis Ángel muestra interés en utilizar una plataforma que centralice las oportunidades de colaboración y permita conocer previamente las condiciones de cada campaña.

Valora positivamente una plataforma que le ofrezca:

- Un espacio donde pueda encontrar campañas disponibles sin tener que buscarlas manualmente.
- Información clara sobre requisitos, entregables y fechas.
- Conocimiento previo de la compensación ofrecida.
- Información suficiente para determinar si una empresa es confiable.
- Campañas relacionadas con su nicho de contenido.
- Reducción del tiempo empleado buscando oportunidades.
- Condiciones claras antes de aceptar una colaboración.

El entrevistado considera que una plataforma de este tipo podría reducir considerablemente el tiempo dedicado a buscar empresas y negociar inicialmente una colaboración.

###### Aspectos Subjetivos y Comportamiento

Luis Ángel mantiene una postura cuidadosa frente a las colaboraciones y considera importante mantener la honestidad con su audiencia.

Aunque exista una compensación de por medio, considera que su opinión sobre un producto debe continuar siendo sincera. Si el producto cumple con sus expectativas puede realizar una reseña positiva, pero si considera que no es adecuado, prefiere no continuar con la colaboración.

También demuestra interés por conocer previamente la reputación de las empresas con las que trabaja y busca referencias antes de aceptar una propuesta.

###### Tecnología y Riesgos Percibidos

Luis Ángel no identifica problemas importantes en el concepto de una plataforma especializada para gestionar colaboraciones.

Sin embargo, considera indispensable que la herramienta cumpla realmente con aquello que ofrece y que la experiencia de navegación sea sencilla.

Para él, la plataforma debería ser:

- Confiable.
- Rápida.
- Práctica.
- Intuitiva.
- Fácil de navegar.
- Visualmente organizada.
- No saturada de información.

Una plataforma demasiado compleja podría generar fricción y provocar que los usuarios abandonen el proceso.

###### Validación del Arquetipo

Los hallazgos validan el arquetipo del **Creador de Contenido Especializado que busca colaboraciones confiables y relevantes**.

Se confirma que este segmento necesita conocer las condiciones de una colaboración antes de aceptarla, reducir el tiempo empleado buscando oportunidades y contar con mayor información sobre las empresas con las que trabajará.

Esto respalda la necesidad de desarrollar funciones dentro de la plataforma enfocadas en:

- **Marketplace de campañas:** centralización de oportunidades disponibles para creadores.
- **Campañas con condiciones claras:** requisitos, fechas, entregables y compensaciones visibles desde el inicio.
- **Verificación de empresas:** información que permita conocer la confiabilidad de las marcas.
- **Filtros por nicho:** campañas relacionadas con los intereses y tipo de contenido del creador.
- **Interfaz intuitiva:** navegación rápida, sencilla y con información organizada.


**Entrevista 2: Britner De La Cruz**

| Campo                             | Detalle                                                         |
| --------------------------------- | --------------------------------------------------------------- |
| **Nombre y Apellidos**            | Britner De La Cruz                                                         |
| **Edad**                          | 22                                                 |
| **Distrito / Zona de residencia** | Santiago de Surco                                                 |
| **Segmento**                      | Creadores de Contenido                                          |
| **Inicio en video**               | 0:00                                                            |
| **Fin de video**                  | 3:24                                                            |
| **Duración**                      | 3:24                                                            |
| **URL del video**                 | [https://www.youtube.com/watch?v=_zyG4bD_Zr4](https://www.youtube.com/watch?v=_zyG4bD_Zr4)                  |
| **Screenshot**                    | ![Entrevista Britner](./assets/C02/Entrevistas/Britner.png)     |

##### Resumen Descriptivo de la Entrevista

###### Características Objetivas y Entorno

Britner es creador de contenido enfocado principalmente en videojuegos. Produce gameplays y contenido relacionado con gaming, utilizando principalmente TikTok como uno de sus canales de publicación.

Cuenta con experiencia previa realizando colaboraciones, principalmente mediante intercambio de productos relacionados con su contenido.

Su perfil corresponde a un creador especializado en un nicho específico, por lo que necesita encontrar empresas y campañas relacionadas principalmente con videojuegos, tecnología y productos compatibles con su audiencia.

###### Herramientas y Proceso Actual

Actualmente, las propuestas de colaboración suelen llegar mediante mensajes directos de Instagram o correo electrónico.

Cuando una empresa se comunica con él, normalmente proporciona información relacionada con el producto o videojuego que desea promocionar, el tipo de contenido requerido y la fecha en la que debería publicarse.

El proceso actual se basa en:

- Recepción de propuestas mediante Instagram o correo electrónico.
- Revisión del producto o videojuego que la empresa desea promocionar.
- Revisión del tipo de contenido solicitado.
- Consulta de la cantidad de videos o publicaciones requeridas.
- Verificación de las fechas de entrega y publicación.
- Evaluación de la compensación y demás condiciones antes de aceptar.

###### Problemas Detectados (Pain Points)

El entrevistado expone diferentes dificultades relacionadas con la claridad y cumplimiento de las condiciones:

- **Cambios posteriores al acuerdo:** En algunas colaboraciones se le han solicitado elementos adicionales que no fueron mencionados inicialmente.
- **Cambios de última hora:** Los requisitos pueden modificarse cuando el contenido ya se encuentra en proceso de elaboración.
- **Demoras en productos:** Ha experimentado retrasos en la entrega de productos necesarios para realizar colaboraciones.
- **Demoras en pagos:** También ha presentado inconvenientes relacionados con retrasos en las compensaciones.
- **Dificultad para encontrar marcas compatibles:** No siempre resulta fácil encontrar marcas de videojuegos o tecnología interesadas en trabajar con creadores de su tamaño.
- **Canales dispersos:** Las oportunidades pueden llegar mediante Instagram o correo electrónico, por lo que no existe un único espacio donde consultar todas las propuestas.

###### Necesidades y Oportunidades

Britner muestra interés en una plataforma que centralice las campañas disponibles y facilite encontrar oportunidades relacionadas con su contenido.

Valora positivamente una plataforma que le ofrezca:

- Un único espacio donde encontrar campañas disponibles.
- Campañas relacionadas con videojuegos y tecnología.
- Requisitos claramente definidos antes de postular.
- Información sobre la cantidad y tipo de contenido requerido.
- Fechas de entrega establecidas desde el inicio.
- Compensaciones claramente indicadas.
- Mayor seguridad respecto al cumplimiento de los pagos.

El entrevistado considera que disponer de todas las campañas en un solo lugar facilitaría considerablemente la búsqueda de oportunidades y reduciría la dependencia de diferentes canales de comunicación.

###### Aspectos Subjetivos y Comportamiento

Britner demuestra una orientación práctica al momento de evaluar una colaboración.

Antes de aceptar una propuesta, considera indispensable conocer exactamente qué contenido deberá realizar, cuántos videos serán necesarios y cuáles serán las fechas de entrega.

Los cambios posteriores al acuerdo representan una dificultad debido a que pueden modificar el trabajo inicialmente planificado.

También muestra interés en recibir principalmente oportunidades relacionadas con su nicho, evitando campañas que no tengan relación con videojuegos, tecnología o su audiencia.

###### Tecnología y Riesgos Percibidos

Britner no identifica problemas importantes en la propuesta de utilizar una plataforma especializada para gestionar colaboraciones.

Para preferirla frente a Instagram, WhatsApp o correo electrónico, considera necesario que la plataforma disponga de:

- Buenas marcas.
- Campañas relacionadas con su contenido.
- Información clara sobre pagos.
- Fechas de entrega establecidas.
- Condiciones visibles antes de aceptar una colaboración.

El principal riesgo percibido sería que la plataforma no cuente con suficientes campañas relevantes para su nicho.

###### Validación del Arquetipo

Los hallazgos validan el arquetipo del **Creador de Contenido de Nicho que busca campañas claras y compatibles con su audiencia**.

Se confirma que este segmento necesita acceder a oportunidades relacionadas con su contenido y conocer claramente las condiciones antes de iniciar una colaboración.

Esto respalda la necesidad de desarrollar funciones dentro de la plataforma enfocadas en:

- **Marketplace centralizado:** campañas disponibles reunidas en un único espacio.
- **Filtros por nicho:** búsqueda de campañas relacionadas con videojuegos, tecnología u otras categorías.
- **Requisitos previamente definidos:** claridad sobre el contenido solicitado antes de postular.
- **Control de fechas:** visualización de fechas de entrega y publicación.
- **Compensaciones transparentes:** información clara sobre pagos o productos ofrecidos.
- **Registro de condiciones:** conservación de los requisitos acordados para evitar cambios posteriores no previstos.

##### Entrevista 3: Katrina Villarreal

| Campo                             | Detalle                                                                                                                                    |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Nombre y Apellidos**            | Katrina Villarreal                                                                                                                         |
| **Edad**                          | 19                                                                                                                                         |
| **Distrito / Zona de residencia** | Cercado de Lima                                                                                                                                |
| **Segmento**                      | Creadores de Contenido                                                                                                                     |
| **Inicio en video**               | 0:00                                                                                                                                       |
| **Fin de video**                  | 8:14                                                                                                                                       |
| **Duración**                      | 8:14                                                                                                                                       |
| **URL del video**                 | [https://youtu.be/hwh1Y0CnKpk](https://youtu.be/hwh1Y0CnKpk) |
| **Screenshot**                    | ![Entrevista Katrina Villarreal](./assets/C02/Entrevistas/katrinaVillarreaL.png)                                                           |

##### Resumen Descriptivo de la Entrevista

###### Características Objetivas y Entorno

Katrina Villarreal tiene 19 años y se desempeña como creadora de contenido en redes sociales. Utiliza principalmente TikTok e Instagram y, dependiendo de la empresa con la que colabora, también Facebook. Su contenido se encuentra orientado principalmente al maquillaje, productos de cuidado personal, recomendaciones, rutinas personales y experiencias relacionadas con lugares o productos en tendencia.

Se describe como una persona responsable al momento de desarrollar contenido para una empresa. Antes de realizar una colaboración procura escuchar y comprender lo que la marca espera para poder cumplir adecuadamente con los requerimientos planteados.

###### Herramientas y Proceso Actual

Las propuestas de colaboración llegan principalmente mediante mensajes directos de Instagram. Algunas empresas también la contactan por correo electrónico, el cual se encuentra asociado a su perfil de TikTok, y en menor medida mediante mensajes dentro de TikTok.

Katrina cuenta con experiencia realizando colaboraciones tanto mediante intercambio de productos como mediante compensaciones económicas. En una de sus colaboraciones más recientes recibió productos para el cuidado del cabello, los probó y posteriormente elaboró un video para TikTok y publicaciones en las historias de Instagram.

La información recibida antes de iniciar una colaboración varía dependiendo de la empresa. Algunas marcas especifican desde el inicio el producto, el contenido requerido, una fecha estimada de publicación y la compensación. Sin embargo, otras proporcionan inicialmente poca información, por lo que la creadora debe solicitar detalles adicionales antes de comprender completamente lo que la empresa espera.

###### Problemas Detectados (Pain Points)

Uno de los principales problemas identificados es la modificación de los requisitos después de haber aceptado una colaboración. Katrina relató una experiencia en la que inicialmente debía realizar únicamente un video de un producto, pero posteriormente la empresa solicitó historias adicionales, el uso obligatorio de determinadas palabras y modificaciones al contenido previamente realizado. Esto generó incomodidad debido a que dichas condiciones no habían sido establecidas desde el comienzo.

También ha experimentado retrasos en los pagos, situación que la obligó a contactar repetidamente a la empresa para conocer cuándo recibiría la compensación. Asimismo, señaló casos en los que los productos llegan después de la fecha acordada, pero la empresa mantiene la fecha original de publicación, reduciendo el tiempo disponible para producir contenido de calidad.

Otra dificultad es encontrar empresas que realmente sean compatibles con su contenido y audiencia. Actualmente debe esperar a que las marcas la contacten o buscarlas por cuenta propia, sin tener certeza de cuáles se encuentran buscando creadores ni cuáles están dispuestas a trabajar con un perfil y audiencia como la suya. Además, recibe propuestas que no siempre se relacionan con el contenido que produce.

###### Necesidades y Oportunidades

Antes de aceptar una colaboración, Katrina considera indispensable conocer el producto o servicio que deberá promocionar, el tipo y cantidad de contenido requerido, las fechas de entrega y publicación, los elementos obligatorios que debe mencionar, el monto de la compensación y la fecha en la que se realizará el pago.

La entrevistada considera útil una plataforma que le permita visualizar campañas disponibles y buscar oportunidades directamente, en lugar de depender únicamente de que una empresa la contacte. Asimismo, valora la posibilidad de revisar los requisitos, fechas y compensaciones antes de postular, debido a que esto le permitiría determinar previamente si una campaña es compatible con sus intereses y disponibilidad.

También manifestó interés en contar con filtros según el tipo de contenido que produce, de manera que pueda encontrar campañas relacionadas con su perfil y evitar propuestas poco relevantes.

###### Aspectos Subjetivos y Comportamiento

Katrina demuestra una actitud responsable y orientada al cumplimiento de los acuerdos establecidos con las empresas. Busca entender previamente las necesidades de la marca y considera importante disponer de información clara antes de comenzar una colaboración.

También evidencia preocupación por mantener la calidad de su contenido. Los retrasos en la entrega de productos o los cambios de último momento representan un problema debido a que reducen el tiempo disponible para preparar adecuadamente las publicaciones.

###### Tecnología y Riesgos Percibidos

La creadora utiliza principalmente TikTok e Instagram como plataformas para publicar contenido y recibir oportunidades de colaboración. También utiliza el correo electrónico como medio de contacto con algunas empresas y ocasionalmente trabaja con Facebook dependiendo de las necesidades de la marca.

Entre los riesgos percibidos se encuentran la falta de claridad en las condiciones de una colaboración, los cambios posteriores a la aceptación, los retrasos en los pagos y la incertidumbre respecto al cumplimiento de los acuerdos por parte de las empresas. Por ello, considera importante que una plataforma especializada incluya marcas confiables y brinde seguridad respecto a las condiciones y pagos de cada campaña.

###### Validación del Arquetipo

La entrevista valida la necesidad de una solución que centralice las oportunidades de colaboración entre creadores de contenido y empresas. Katrina manifestó que una plataforma de este tipo resultaría útil si permite visualizar campañas disponibles, revisar previamente requisitos, fechas y compensaciones, filtrar campañas según el tipo de contenido y trabajar con marcas confiables.

Los principales hallazgos que respaldan el arquetipo del creador de contenido son la dependencia actual de mensajes directos para recibir propuestas, la falta de claridad en algunos acuerdos, los cambios posteriores en los requisitos, los retrasos en las compensaciones y la dificultad para descubrir marcas compatibles con el contenido y la audiencia del creador. Estos hallazgos respaldan la propuesta de CollabPro de centralizar las campañas y establecer sus condiciones desde el inicio.

#### 2.2.3. Análisis de entrevistas

Para esta primera etapa de investigación se analizaron cuatro entrevistas correspondientes a los dos segmentos principales de CollabPro.

Dentro del segmento de pequeñas y medianas empresas se entrevistó a Frank Loayza, propietario de un emprendimiento de comida mediante delivery, y a Andy Pillaca, integrante del personal de marketing de una pequeña empresa.

Para el segmento de creadores de contenido se entrevistó a Luis Ángel, estudiante y barbero que crea contenido relacionado con barbería y cuidado personal, y a Britner, creador de contenido enfocado principalmente en videojuegos y gameplays.

Aunque los entrevistados presentan contextos, niveles de experiencia y necesidades diferentes, se identificaron patrones comunes que permiten comprender cómo se gestionan actualmente las colaboraciones entre empresas y creadores de contenido.

##### Búsqueda y selección de colaboradores

Uno de los principales hallazgos es que la búsqueda de colaboradores continúa realizándose de manera poco estructurada desde ambos lados de la relación.

Frank depende principalmente de conocidos, recomendaciones y contactos indirectos para encontrar personas que puedan promocionar su negocio. Esta situación limita la cantidad de perfiles disponibles y dificulta encontrar creadores cuya audiencia coincida con el público objetivo de su emprendimiento.

Andy también indicó que la búsqueda se realiza principalmente mediante redes sociales y recomendaciones. Sin embargo, además de encontrar un perfil adecuado, su empresa intenta conocer si el creador es responsable, puntual y cumple los acuerdos establecidos.

Desde la perspectiva de los creadores también existen dificultades para encontrar oportunidades adecuadas.

Luis Ángel indicó que las propuestas suelen llegar principalmente mediante Instagram o TikTok, pero considera necesario investigar por su cuenta si la empresa es legítima y si otros creadores han trabajado anteriormente con ella.

Britner señaló que no siempre resulta sencillo encontrar marcas de videojuegos o tecnología interesadas en trabajar con creadores de su tamaño, por lo que disponer de campañas relacionadas con su nicho representa una necesidad importante.

Por lo tanto, la selección de una colaboración no depende únicamente de encontrar una contraparte disponible. También existe la necesidad de evaluar aspectos como:

- Nicho y audiencia.
- Compatibilidad entre la marca y el creador.
- Responsabilidad.
- Puntualidad.
- Experiencia previa.
- Reputación.
- Cumplimiento de colaboraciones anteriores.
- Confiabilidad de la empresa.
- Tipo de contenido solicitado.

Este hallazgo respalda la necesidad de incorporar mecanismos de búsqueda, filtrado, perfiles e historial de colaboraciones dentro de CollabPro.

##### Coordinación y definición de acuerdos

Otro patrón encontrado en los cuatro entrevistados es el uso de canales informales para coordinar las colaboraciones.

En el caso de las empresas, las condiciones suelen negociarse mediante conversaciones directas, mensajes o llamadas. Aspectos importantes como la compensación, el contenido esperado y las fechas pueden quedar distribuidos entre diferentes conversaciones.

Desde la perspectiva de los creadores ocurre una situación similar.

Luis Ángel explicó que las propuestas normalmente llegan mediante mensajes en Instagram o TikTok. Aunque las empresas suelen presentarse y comunicar la propuesta general, en algunas ocasiones no proporcionan toda la información necesaria desde el inicio.

Britner recibe propuestas principalmente mediante Instagram o correo electrónico. Además, indicó que en algunas colaboraciones se le solicitaron posteriormente elementos que no habían sido comunicados originalmente.

Esta situación aumenta la posibilidad de generar confusiones y dificulta consultar posteriormente qué condiciones fueron establecidas originalmente.

Los resultados respaldan la propuesta de utilizar campañas estructuradas donde se registren previamente:

- Objetivo de la campaña.
- Tipo de contenido solicitado.
- Entregables.
- Cantidad de publicaciones o videos.
- Fechas de entrega y publicación.
- Compensación.
- Requisitos específicos.
- Criterios de aceptación.

De esta manera, tanto la empresa como el creador podrían consultar las condiciones de la colaboración desde un único punto durante todo el proceso.

##### Claridad y cambios en los requisitos

Las entrevistas del segmento de creadores permitieron identificar un problema que anteriormente se encontraba planteado principalmente como una hipótesis: la necesidad de conocer claramente las condiciones antes de iniciar una colaboración.

Luis Ángel considera importante conocer toda la información necesaria antes de aceptar una propuesta y presta especial atención a los detalles que podrían no haber sido comunicados inicialmente.

Britner presentó evidencia más directa de este problema, señalando que en algunas ocasiones una empresa le solicitó agregar elementos al contenido que no habían sido mencionados al inicio.

Estos cambios pueden afectar la planificación y producción del creador, especialmente cuando el contenido ya se encuentra en desarrollo.

Por lo tanto, resulta importante que CollabPro permita registrar las condiciones originales de una colaboración y que cualquier modificación posterior pueda quedar claramente identificada.

Esto permitiría reducir problemas relacionados con:

- Requisitos ambiguos.
- Información incompleta.
- Cambios de última hora.
- Nuevos entregables no contemplados inicialmente.
- Confusión sobre las responsabilidades de cada parte.

##### Seguimiento y cumplimiento de entregables

La supervisión del cumplimiento representa otro problema relevante para ambos segmentos.

Andy indicó que su empresa ha experimentado retrasos en la publicación del contenido y que fue necesario insistir al creador para que cumpliera con el acuerdo establecido. Asimismo, explicó que actualmente verifican de forma manual si las publicaciones cumplen con los contenidos y fechas acordadas.

En el caso de Frank, aunque su experiencia se encuentra principalmente relacionada con colaboraciones mediante canje, también existe la necesidad de controlar que el creador realice correctamente aquello que fue acordado.

Desde el lado de los creadores también se identificaron problemas relacionados con los plazos.

Luis Ángel manifestó haber experimentado algunas dificultades relacionadas con fechas de entrega, aunque estas pudieron resolverse mediante coordinación con la empresa.

Britner indicó que ha experimentado cambios de última hora y retrasos relacionados con la entrega de productos necesarios para realizar algunas colaboraciones.

Las cuatro entrevistas muestran una oportunidad para implementar un flujo de seguimiento en el que una colaboración pueda pasar por estados claramente identificables, por ejemplo:

**Pendiente → En proceso → Entregado → En revisión → Aprobado → Finalizado.**

También resulta relevante permitir que:

- El creador adjunte evidencias de cumplimiento.
- La empresa pueda revisar los entregables.
- Se registren las fechas originalmente acordadas.
- Se identifiquen entregas fuera de plazo.
- Se puedan solicitar correcciones cuando sea necesario.
- Ambas partes conozcan el estado actual de la colaboración.

##### Compensaciones y cumplimiento de pagos

La compensación representa otro elemento importante identificado durante las entrevistas.

Frank trabaja principalmente mediante canjes y considera importante que cualquier modelo comercial se adapte a las posibilidades económicas de pequeños negocios.

Andy manifestó una mayor apertura hacia pagos y modelos de suscripción siempre que la plataforma permita ahorrar tiempo y controlar adecuadamente las campañas.

Desde la perspectiva de los creadores, conocer la compensación previamente también resulta fundamental.

Luis Ángel ha participado principalmente en colaboraciones mediante intercambio de productos y considera necesario conocer claramente qué ofrece la empresa antes de aceptar una colaboración.

Britner indicó que ha experimentado demoras relacionadas con pagos y considera indispensable que una plataforma muestre claramente la compensación y el estado de cumplimiento.

Los resultados muestran que CollabPro debería permitir diferenciar claramente modalidades como:

- Pago monetario.
- Intercambio de productos.
- Servicios.
- Canjes.
- Otras formas de compensación acordadas.

Asimismo, resulta importante mostrar el estado de la compensación y relacionarlo con el cumplimiento de los entregables.

##### Confianza y reputación

Las nuevas entrevistas también permitieron identificar la confianza como un elemento importante dentro del segmento de creadores.

Luis Ángel considera indispensable verificar que una empresa sea seria antes de realizar una colaboración. Para ello, actualmente busca otras personas que hayan trabajado con la marca y comprueba por su cuenta si esta parece legítima.

También manifestó que una de sus principales dificultades consiste en encontrar empresas transparentes que proporcionen toda la información necesaria.

Este problema también se encuentra presente desde la perspectiva empresarial.

Andy intenta obtener referencias sobre los creadores antes de trabajar con ellos para conocer si son responsables, puntuales y cumplen sus compromisos.

Por lo tanto, existe una necesidad bilateral de conocer el comportamiento previo de la contraparte.

Esto respalda la incorporación futura de mecanismos como:

- Historial de colaboraciones.
- Verificación de perfiles.
- Reputación de empresas y creadores.
- Registro de cumplimiento.
- Incidencias anteriores.
- Valoraciones posteriores a una colaboración.

##### Medición de resultados

Las entrevistas del segmento de empresas demostraron un interés claro en conocer los resultados obtenidos después de trabajar con un creador.

Frank actualmente analiza de manera empírica indicadores como visualizaciones, likes, comentarios y posibles incrementos temporales en los pedidos.

Andy utiliza métricas similares, considerando principalmente:

- Visualizaciones.
- Interacciones.
- Seguidores obtenidos.
- Ventas generadas cuando pueden ser identificadas.

Por lo tanto, las entrevistas respaldan la necesidad de un panel que concentre las principales métricas de cada colaboración y permita que las empresas comparen los resultados obtenidos entre campañas.

La información debería presentarse de manera sencilla, ya que el objetivo de este segmento no necesariamente es realizar análisis avanzados de marketing, sino determinar rápidamente si la inversión realizada generó resultados suficientes.

Para los creadores, las métricas no fueron identificadas como una preocupación principal durante las entrevistas. Su prioridad se encuentra más relacionada con encontrar campañas adecuadas, conocer sus condiciones, cumplir los entregables y recibir la compensación acordada.

##### Tiempo y esfuerzo requerido

Otro patrón claramente identificado es el tiempo invertido en administrar y encontrar colaboraciones.

Frank señaló que, debido a que debe concentrarse en las operaciones principales de su negocio, dispone de poco tiempo para buscar nuevos creadores.

De manera similar, Andy indicó que las actividades que demandan mayor esfuerzo son encontrar creadores adecuados y realizar seguimiento a todo lo que deben entregar.

Luis Ángel considera que una plataforma con campañas disponibles podría ahorrarle una cantidad importante de tiempo durante la búsqueda de oportunidades.

Asimismo, considera poco eficiente tener que investigar individualmente empresas y averiguar si realmente están interesadas en realizar una colaboración.

Britner también valora la posibilidad de encontrar diferentes campañas en un único lugar en lugar de depender de propuestas recibidas mediante diferentes canales.

Esto permite identificar dos actividades especialmente problemáticas para cada segmento:

**Empresa: Encontrar al creador adecuado → Gestionar y supervisar la colaboración.**

**Creador: Encontrar una campaña relevante → Verificar y gestionar sus condiciones.**

Reducir el tiempo requerido para estas actividades representa una de las principales oportunidades de valor para CollabPro.

##### Experiencia de usuario y facilidad de uso

La entrevista con Luis Ángel permitió identificar adicionalmente la importancia de la experiencia de usuario de la plataforma.

El entrevistado considera que una solución de este tipo debería tener una navegación rápida, fluida e intuitiva.

Indicó que algunas aplicaciones generan fricción debido a su complejidad, exceso de opciones o gran cantidad de información, lo que puede provocar que los usuarios abandonen el proceso.

Por lo tanto, además de ofrecer las funcionalidades necesarias, CollabPro deberá procurar que la información se encuentre correctamente organizada y que las acciones principales puedan realizarse sin una curva de aprendizaje elevada.

Este hallazgo respalda especialmente:

- Navegación sencilla.
- Información jerarquizada.
- Interfaces no saturadas.
- Acceso rápido a campañas.
- Visualización clara de requisitos y compensaciones.
- Procesos de postulación simples.

##### Disposición de pago

La disposición a pagar por una plataforma especializada fue evaluada principalmente desde el segmento empresarial.

Frank se muestra cauteloso frente a una suscripción mensual debido a las restricciones presupuestarias de un negocio pequeño. Su preferencia se orienta hacia alternativas de menor riesgo económico y modelos relacionados con los resultados obtenidos.

Andy manifestó una mayor apertura hacia una suscripción mensual, siempre que la plataforma permita ahorrar tiempo, controlar las campañas y medir sus resultados. Sin embargo, también destacó que el precio deberá ser accesible para una pequeña empresa.

Por tanto, la hipótesis de que las pymes pagarían una suscripción mensual se encuentra **parcialmente respaldada**, pero todavía no puede considerarse completamente validada.

Los resultados indican que el precio y el modelo comercial deberán probarse posteriormente mediante pilotos. Algunas alternativas que podrían evaluarse son:

- Plan de entrada económico.
- Suscripción escalonada según cantidad de campañas.
- Periodo de prueba.
- Una campaña inicial gratuita.
- Modelos mixtos de suscripción y comisión.

##### Hallazgos comunes

A partir de las cuatro entrevistas se identifican necesidades compartidas y complementarias entre ambos segmentos.

Para las pequeñas y medianas empresas destacan:

1. **Encontrar creadores adecuados con mayor facilidad.**
2. **Centralizar las condiciones y comunicaciones relacionadas con cada colaboración.**
3. **Controlar los entregables y fechas acordadas.**
4. **Reducir el tiempo requerido para realizar seguimiento.**
5. **Medir de manera objetiva los resultados obtenidos.**
6. **Conocer la responsabilidad y confiabilidad del creador.**

Para los creadores de contenido destacan:

1. **Encontrar campañas compatibles con su contenido y audiencia.**
2. **Conocer todos los requisitos antes de aceptar una colaboración.**
3. **Conocer claramente las fechas y entregables requeridos.**
4. **Evitar cambios inesperados en las condiciones.**
5. **Conocer previamente la compensación ofrecida.**
6. **Tener mayor seguridad respecto al cumplimiento del pago o intercambio.**
7. **Trabajar con empresas confiables y transparentes.**
8. **Reducir el tiempo requerido para encontrar oportunidades.**

Ambos segmentos coinciden especialmente en la necesidad de contar con condiciones claras, fechas conocidas, información centralizada y mayor confianza durante todo el proceso.

Estos hallazgos respaldan la problemática planteada inicialmente por CollabPro respecto a la fragmentación del proceso actual y la ausencia de una herramienta centralizada para administrar las colaboraciones.

##### Diferencias entre los entrevistados

Aunque existen necesidades comunes, también se identificaron diferencias relevantes entre los cuatro entrevistados.

Frank representa un emprendimiento pequeño en una fase relativamente temprana, con recursos económicos y humanos limitados. Sus colaboraciones se encuentran fuertemente vinculadas a canjes y contactos personales, y su principal preocupación es conseguir exposición rentable sin asumir elevados costos.

Andy representa un contexto donde las colaboraciones con creadores ya se realizan con mayor frecuencia. Por este motivo, sus problemas están más relacionados con la coordinación, el cumplimiento de fechas, el seguimiento y la medición.

Luis Ángel representa a un creador especializado en belleza y cuidado personal que prioriza la confiabilidad de las empresas, la transparencia de las propuestas y la coherencia entre los productos promocionados y el contenido que presenta a su audiencia.

Britner representa a un creador especializado en videojuegos que necesita principalmente encontrar campañas relacionadas con su nicho y contar con requisitos, fechas y compensaciones claramente establecidos desde el inicio.

Estas diferencias sugieren que CollabPro deberá atender usuarios con distintos niveles de experiencia y necesidades.

Para las empresas con poca experiencia deberá facilitar principalmente el descubrimiento y estructuración de campañas, mientras que para aquellas con mayor experiencia deberá aportar control, seguimiento y métricas.

Para los creadores deberá facilitar el descubrimiento de campañas según su nicho y proporcionar suficiente información para evaluar una oportunidad antes de postular.

##### Validación de las hipótesis de CollabPro

Las cuatro entrevistas permiten realizar una evaluación más completa de las principales hipótesis planteadas para la solución.

| Hipótesis                                                                                  | Resultado preliminar           | Evidencia encontrada                                                                                                                                                                                                 |
| ------------------------------------------------------------------------------------------ | ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Las pymes tienen dificultades para administrar colaboraciones mediante canales informales. | **Respaldada**                 | Frank y Andy muestran procesos basados principalmente en mensajes, redes sociales, recomendaciones y coordinación manual.                                                                                            |
| Las empresas necesitan encontrar creadores adecuados con mayor facilidad.                  | **Respaldada**                 | Frank presenta una red limitada de contactos y Andy identifica la búsqueda de creadores responsables como una de las actividades que más tiempo consume.                                                             |
| Las campañas estructuradas pueden reducir problemas de coordinación.                       | **Respaldada**                 | Las cuatro entrevistas muestran que actualmente las condiciones se gestionan mediante canales dispersos y tanto empresas como creadores valoran contar con requisitos, fechas y compensaciones previamente definidos. |
| Las empresas necesitan controlar los entregables.                                          | **Respaldada**                 | Andy reportó retrasos en publicaciones y actualmente realiza verificaciones manuales, mientras que Frank también necesita comprobar que el creador cumpla lo acordado.                                                |
| Las métricas centralizadas aportarían valor a las pymes.                                   | **Respaldada**                 | Frank y Andy utilizan métricas para intentar evaluar los resultados y muestran interés por obtener información más clara.                                                                                            |
| Las pymes pagarían una suscripción mensual.                                                | **Parcialmente respaldada**    | Andy estaría dispuesto si existe ahorro de tiempo y un precio accesible; Frank presenta mayor sensibilidad frente a un costo mensual fijo.                                                                           |
| Los creadores necesitan mayor claridad sobre los requisitos de una colaboración.           | **Respaldada**                 | Luis Ángel considera indispensable conocer toda la información antes de aceptar y Britner reportó requisitos adicionales comunicados después de iniciado el acuerdo.                                                  |
| Los creadores necesitan conocer previamente la compensación.                               | **Respaldada**                 | Ambos creadores consideran importante conocer qué recibirán antes de aceptar una colaboración.                                                                                                                       |
| Los creadores necesitan encontrar campañas relacionadas con su nicho.                      | **Respaldada**                 | Luis Ángel busca propuestas relacionadas con belleza y cuidado personal, mientras que Britner identifica dificultades para encontrar oportunidades relacionadas con videojuegos y tecnología.                         |
| Los creadores necesitan mayor seguridad respecto al cumplimiento de la compensación.       | **Respaldada preliminarmente** | Britner reportó demoras en pagos y Luis Ángel considera indispensable trabajar con empresas confiables y transparentes.                                                                                              |
| Una plataforma centralizada reduciría el tiempo invertido en encontrar colaboraciones.     | **Respaldada**                 | Tanto Luis Ángel como Britner consideran ventajoso poder encontrar campañas disponibles en un único lugar, mientras que Frank y Andy también buscan reducir el tiempo destinado a localizar creadores.                 |
| La confiabilidad de empresas y creadores influye en la decisión de colaborar.               | **Respaldada**                 | Luis Ángel investiga previamente a las marcas y Andy busca referencias sobre la responsabilidad y cumplimiento de los creadores.                                                                                      |

##### Implicaciones para el MVP

Los resultados permiten priorizar un primer conjunto de funcionalidades para CollabPro considerando las necesidades de ambos segmentos.

El MVP debería concentrarse inicialmente en:

- Registro y perfil de empresas y creadores.
- Información sobre nicho, contenido y características relevantes de cada creador.
- Búsqueda y filtrado de creadores por nicho y características relevantes.
- Marketplace de campañas disponibles para creadores.
- Filtros de campañas por nicho o categoría.
- Creación de campañas con condiciones estructuradas.
- Registro explícito de requisitos, entregables, fechas y compensaciones.
- Consulta detallada de condiciones antes de postular.
- Postulación de creadores.
- Seguimiento del estado de cada colaboración.
- Entrega de evidencias.
- Validación de entregables.
- Registro de incidencias.
- Consulta del estado de la compensación.
- Historial de colaboraciones y cumplimiento.
- Información básica que permita evaluar la confiabilidad de empresas y creadores.
- Panel básico de métricas para empresas.
- Interfaz sencilla e intuitiva que permita acceder rápidamente a la información relevante.

Funciones más avanzadas, como sistemas complejos de recomendación automática, automatización integral de pagos, reputación avanzada o analítica avanzada, pueden evaluarse posteriormente después de validar el comportamiento de los usuarios durante el uso del MVP.

##### Limitaciones de la investigación

Hasta el momento se dispone de cuatro entrevistas: dos pertenecientes al segmento de pequeñas y medianas empresas y dos pertenecientes al segmento de creadores de contenido.

Esto permite identificar patrones iniciales en ambos lados de la plataforma y proporciona evidencia directa para validar varias de las hipótesis planteadas anteriormente.

Sin embargo, la cantidad de entrevistas continúa siendo reducida y no garantiza que los resultados representen a todas las pymes ni a todos los tipos de creadores de contenido.

Además, los creadores entrevistados pertenecen a nichos específicos de barbería, cuidado personal y videojuegos, por lo que posteriormente será conveniente ampliar la investigación incluyendo creadores de otros sectores y con diferentes tamaños de audiencia.

En consecuencia, los hallazgos actuales deben considerarse una validación preliminar de la propuesta bilateral de CollabPro. El siguiente paso de investigación debería ampliar la muestra de ambos segmentos y contrastar especialmente aspectos relacionados con disposición de pago, reputación, cambios de requisitos, mecanismos de compensación y comportamiento durante una colaboración completa.

### 2.3. Needfinding

#### 2.3.1. User Personas

**Persona 1: Emprendedor de pequeña empresa con recursos limitados**

![User Persona Frank Loayza](./assets/C02/Needfinding/User%20Persona%20Frank%20Loayza.png)

Frank representa al propietario de una pyme que busca promocionar su negocio mediante creadores de contenido, pero dispone de poco tiempo, una red de contactos limitada y un presupuesto restringido. Sus principales necesidades son encontrar creadores alineados con su público, definir condiciones claras, controlar los entregables y medir objetivamente los resultados de una colaboración.

**Persona 2: Creadora de contenido y microinfluencer**

![User Persona Camila Rojas](./assets/C02/Needfinding/User%20Persona%20Camila%20Rojas.png)

Camila representa a una creadora de contenido que busca campañas relacionadas con su audiencia y necesita conocer los requisitos, fechas y compensación antes de aceptar una colaboración. Sus principales necesidades son recibir propuestas completas, evitar cambios de última hora, enviar evidencias de sus entregables y contar con mayor seguridad respecto al cumplimiento de la compensación. Esta persona es una proto-persona y sus características deben validarse con investigación adicional.

#### 2.3.2. User Task Matrix

En esta sección se presentan las tareas que realizan los dos segmentos de CollabPro para cumplir sus objetivos durante una colaboración de marketing. Las tareas describen actividades que las personas realizan independientemente de la existencia de una solución de software; por ello, no se consideran funcionalidades como publicar una campaña, consultar un dashboard o recibir notificaciones. Se consideran las personas **Frank Loayza**, representante del segmento de pequeñas y medianas empresas, y **Camila Rojas**, representante del segmento de creadores de contenido.

La frecuencia se interpreta de la siguiente manera: **Alta** significa que la tarea ocurre habitualmente en el ciclo de una colaboración o se repite con frecuencia; **Media** significa que ocurre en algunas colaboraciones o en momentos puntuales; y **Baja** significa que ocurre ocasionalmente. La importancia indica cuánto afecta la tarea al logro del objetivo del segmento.

<table>
  <thead>
    <tr>
      <th rowspan="2">User task</th>
      <th colspan="2">Frank Loayza<br><em>Pyme</em></th>
      <th colspan="2">Camila Rojas<br><em>Creadora de contenido</em></th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Definir el objetivo de la colaboración</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Identificar el público objetivo y el nicho adecuado</td>
      <td>Alta</td>
      <td>Media</td>
      <td>Media</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Buscar posibles colaboradores o campañas</td>
      <td>Media</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Evaluar si existe compatibilidad entre la marca, el creador y la audiencia</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Contactar al posible colaborador e intercambiar una propuesta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Negociar la compensación y las condiciones de la colaboración</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Acordar entregables, fechas y criterios de aceptación</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Preparar los productos, recursos o contenido necesarios</td>
      <td>Media</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Publicar o entregar el contenido acordado</td>
      <td>Media</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Verificar el cumplimiento y entregar evidencias</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Gestionar y confirmar la compensación</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Alta</td>
    </tr>
    <tr>
      <td>Medir y evaluar el desempeño de la colaboración</td>
      <td>Alta</td>
      <td>Alta</td>
      <td>Baja</td>
      <td>Media</td>
    </tr>
    <tr>
      <td>Decidir si se mantiene o repite la relación comercial</td>
      <td>Media</td>
      <td>Media</td>
      <td>Media</td>
      <td>Media</td>
    </tr>
  </tbody>
</table>

Las tareas de mayor frecuencia e importancia para ambos segmentos son evaluar la compatibilidad, contactar al posible colaborador, negociar las condiciones, acordar los entregables, cumplir con la publicación y gestionar la compensación. Estas actividades son críticas porque determinan si la colaboración será clara, confiable y beneficiosa para ambas partes.

La principal diferencia entre los segmentos se observa en la etapa posterior a la publicación. Para la pyme, medir el desempeño y determinar si la inversión generó resultados es una tarea de alta importancia y frecuencia. Para el creador, esta actividad es menos frecuente porque su prioridad es producir, publicar y demostrar que cumplió con los entregables. Asimismo, la búsqueda de campañas es más frecuente para el creador, mientras que la pyme suele buscar colaboradores únicamente cuando necesita ejecutar una campaña.

La principal coincidencia es que ambos segmentos necesitan claridad sobre el acuerdo, los entregables, las fechas y la compensación. Actualmente estas tareas se realizan mediante conversaciones dispersas en Instagram, WhatsApp u otros canales, lo que genera pérdida de información, cambios de última hora, dificultades para verificar el cumplimiento e incertidumbre sobre los resultados.

#### 2.3.3. User Journey Mapping

**Journey 1: Pyme**

![As-Is User Journey - Pyme](./assets/C02/Needfinding/Journey%201_%20Pyme.png)

El journey de la pyme muestra que el proceso comienza con la necesidad de aumentar la exposición del negocio y continúa con la búsqueda informal de creadores, la negociación mediante mensajes directos, el envío de productos, la verificación manual de publicaciones y la evaluación empírica de los resultados. Los principales puntos de dolor son la dificultad para encontrar perfiles adecuados, la falta de trazabilidad de los acuerdos, el riesgo de incumplimiento y la ausencia de métricas centralizadas.

**Journey 2: Creador de contenido**

![As-Is User Journey - Creador de contenido](./assets/C02/Needfinding/Journey%202_%20Creador%20de%20contenido.png)

El journey del creador de contenido muestra un proceso basado principalmente en propuestas recibidas mediante redes sociales y otros canales digitales. El creador debe revisar la información proporcionada por la empresa, solicitar detalles adicionales cuando sea necesario, negociar las condiciones, producir y publicar el contenido acordado y realizar seguimiento de la compensación. Los principales puntos de dolor identificados en las entrevistas son la información incompleta al inicio de algunas colaboraciones, los cambios posteriores en los requisitos, los retrasos en los pagos y la dificultad para encontrar marcas compatibles con el contenido y la audiencia del creador.

#### 2.3.4. Empathy Mapping

Los mapas de empatía permiten sintetizar lo que cada segmento necesita realizar, observa, escucha, dice, hace, piensa y siente durante el proceso de colaboración entre una pyme y un creador de contenido. También permiten organizar sus principales problemas y beneficios esperados.

**Empathy Map 1: Pyme**

![Empathy Map - Pyme](./assets/C02/Needfinding/Empathy%20map%20Pyme.png)

El mapa de empatía de la pyme se construyó a partir de la entrevista realizada a Frank Loayza. El segmento busca promocionar su negocio y llegar a una audiencia joven, pero enfrenta dificultades para encontrar creadores adecuados, coordinar las condiciones, verificar los entregables y medir el retorno de inversión. Sus principales beneficios esperados son ahorrar tiempo, encontrar colaboradores relevantes, reducir el riesgo de las campañas y obtener métricas objetivas.

**Empathy Map 2: Creador de contenido**

![Empathy Map - Creador de contenido](./assets/C02/Needfinding/Empathy%20map%20Creador.png)

El mapa de empatía del creador de contenido se construyó a partir de los hallazgos obtenidos en las entrevistas realizadas a creadores del segmento. El creador busca encontrar campañas compatibles con su contenido y audiencia, conocer claramente los requisitos antes de aceptar una colaboración, cumplir con los entregables acordados y recibir una compensación clara y oportuna. Entre sus principales problemas se encuentran la información incompleta en algunas propuestas, los cambios posteriores en los requisitos, los retrasos en los pagos y la dificultad para identificar marcas que estén buscando creadores con características compatibles con su perfil.

#### 2.3.5. Big Picture EventStorming

El equipo aplicó **Big Picture EventStorming** para representar visualmente el ciclo general de una colaboración entre una pyme y un creador de contenido. La sesión parte de los hallazgos de las entrevistas, User Personas, User Journey Maps y Empathy Maps de CollabPro. Los eventos se ordenan cronológicamente y se complementan con actores, acciones, reglas y puntos problemáticos del dominio.

El flujo central que debe observarse en los post-its es: **Promotion need identified → Campaign objective defined → Creator discovered → Proposal exchanged → Agreement reached → Content published → Evidence submitted → Deliverable approved → Compensation released → Campaign evaluated**. También deben representarse los caminos alternativos: propuesta rechazada, colaboración cancelada, entregable rechazado, solicitud de revisión, disputa y compensación retrasada.

![Big Picture Domain Events](./assets/C02/Needfinding/BigPicture/big-picture-collabpro-1.png)

![Big Picture Domain Events](./assets/C02/Needfinding/BigPicture/big-picture-collabpro-2.png)

![Big Picture Business Clusters](./assets/C02/Needfinding/BigPicture/big-picture-collabpro-3.png)

![Big Picture Bounded Context Candidates](./assets/C02/Needfinding/BigPicture/big-picture-collabpro-4.png)

Enlace del Miro: https://miro.com/app/board/uXjVHl9jh_M=/?share_link_id=159650084488

#### 2.3.6. Ubiquitous Language

El siguiente glosario define los términos del dominio de marketing de creadores utilizados por el equipo de CollabPro. Los conceptos se mantienen en inglés para establecer un lenguaje común con los stakeholders y las referencias de la industria. Las definiciones buscan evitar ambigüedades entre la perspectiva de la pyme y la del creador de contenido. No se incluyen términos técnicos de ingeniería de software.

| Term (equivalente en español)                         | Definition                                                                                                                                                                 |
| ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Brand (Marca)**                                     | Business or organization that promotes a product or service and initiates or finances a collaboration with a creator.                                                      |
| **Creator (Creador de contenido)**                    | Person who produces and publishes original content for an audience through one or more social media channels.                                                              |
| **Influencer (Influencer)**                           | Creator whose opinions, recommendations or presence can influence the behavior or purchasing decisions of an audience. Not every creator must be considered an influencer. |
| **Micro-creator (Microcreador)**                      | Creator with a relatively small and specific audience who may offer strong relevance and interaction within a particular niche.                                            |
| **Audience (Audiencia)**                              | Group of people who follow, view or interact with a creator's content.                                                                                                     |
| **Niche (Nicho)**                                     | Specific category, interest or market segment around which a creator produces content or a brand offers products.                                                          |
| **Campaign (Campaña)**                                | Time-bound marketing initiative with an objective, target audience, deliverables, deadline and compensation.                                                               |
| **Collaboration (Colaboración)**                      | Commercial relationship in which a brand and a creator agree to exchange content and value under defined conditions.                                                       |
| **Brief (Brief de campaña)**                          | Concise description of the campaign objective, message, audience, requirements, deliverables, dates and acceptance criteria.                                               |
| **Proposal (Propuesta)**                              | Offer made by a brand or creator that describes the intended collaboration and its initial conditions.                                                                     |
| **Agreement (Acuerdo)**                               | Set of conditions accepted by both the brand and the creator before the collaboration begins.                                                                              |
| **Deliverable (Entregable)**                          | Specific piece of content or activity that the creator must produce or complete as part of the agreement.                                                                  |
| **Deadline (Fecha límite)**                           | Date or time by which a deliverable, publication or other agreed activity must be completed.                                                                               |
| **Content (Contenido)**                               | Material created for an audience, such as a story, post, video, reel, review or live stream.                                                                               |
| **Sponsored content (Contenido patrocinado)**         | Content created in exchange for compensation or another commercial benefit from a brand.                                                                                   |
| **Compensation (Compensación)**                       | Value received by the creator for fulfilling the agreement. It may be cash, products, services, credits or a combination of these.                                         |
| **Barter (Canje)**                                    | Collaboration arrangement in which products or services are exchanged for content instead of, or in addition to, cash.                                                     |
| **Evidence (Evidencia de cumplimiento)**              | Proof that a creator completed or published an agreed deliverable, such as a link, screenshot or publication record.                                                       |
| **Approval (Aprobación)**                             | Confirmation by the brand that a submitted deliverable satisfies the agreed requirements.                                                                                  |
| **Disclosure (Declaración publicitaria)**             | Clear indication that a piece of content is part of a commercial collaboration or has received compensation from a brand.                                                  |
| **Brand fit (Compatibilidad con la marca)**           | Degree to which the creator's content, values, style and audience are aligned with the brand and its campaign objective.                                                   |
| **Match (Coincidencia)**                              | Degree to which the characteristics of a brand, campaign, creator and audience correspond to one another.                                                                  |
| **Reach (Alcance)**                                   | Number of unique people who have seen or may have seen a piece of content.                                                                                                 |
| **Impressions (Impresiones)**                         | Total number of times a piece of content has been displayed, including repeated views by the same person.                                                                  |
| **Engagement (Interacción)**                          | Actions generated by content, such as likes, comments, shares, saves, clicks or replies.                                                                                   |
| **Conversion (Conversión)**                           | Desired action attributed to a campaign, such as a purchase, inquiry, registration or visit.                                                                               |
| **Performance (Desempeño)**                           | Results achieved by a campaign or piece of content in relation to its objective and expected outcomes.                                                                     |
| **Return on investment — ROI (Retorno de inversión)** | Relationship between the value generated by a collaboration and the money, products or resources invested in it.                                                           |
| **Repeat collaboration (Colaboración recurrente)**    | New collaboration between the same brand and creator after a previous collaboration has been completed.                                                                    |

Para mantener la consistencia del lenguaje, el equipo utilizará **Brand** para referirse a la pyme que contrata o propone una colaboración y **Creator** para referirse a la persona que produce el contenido. **Compensation** es el término general e incluye dinero, productos, servicios o créditos; **Barter** se utilizará únicamente cuando la compensación consista en un intercambio de productos o servicios. Finalmente, **Reach**, **Impressions**, **Engagement** y **Conversion** representan métricas diferentes y no deben utilizarse como sinónimos.

### 2.4. Requirements specification

#### 2.4.1. User Stories

<table>
<thead>
<tr>
<th>Epic ID</th>
<th>Título</th>
<th>Descripción</th>
</tr>
</thead>
<tbody>

<tr>
<td><strong>EP-01</strong></td>
<td>Presentación inicial de CollabPro</td>
<td>Presentar la propuesta de valor de CollabPro, explicar su funcionamiento y facilitar el contacto y acceso inicial con los usuarios potenciales.</td>
</tr>

<tr>
<td><strong>EP-02</strong></td>
<td>Cuentas y perfiles</td>
<td>Permitir que empresas y creadores de contenido se registren, accedan a la plataforma y administren la información necesaria para participar en colaboraciones.</td>
</tr>

<tr>
<td><strong>EP-03</strong></td>
<td>Campañas y colaboraciones</td>
<td>Permitir que las empresas publiquen campañas de búsqueda y que los creadores encuentren estas oportunidades, se postulen y participen en colaboraciones bajo condiciones previamente establecidas.</td>
</tr>

<tr>
<td><strong>EP-04</strong></td>
<td>Facturaciones y pagos</td>
<td>Gestionar los medios de pago, las suscripciones, las compensaciones, la validación del cumplimiento y la consulta de resultados verificables de las colaboraciones.</td>
</tr>

<tr>
<td><strong>EP-05</strong></td>
<td>Servicios e integraciones técnicas de CollabPro</td>
<td>Proporcionar los servicios y las funcionalidades técnicas necesarias relacionadas con RESTful API para el soporte de CollabPro.</td>
</tr>

<tr>
<td><strong>EP-06</strong></td>
<td>Investigación técnica sobre servicios de terceros y extracción de métricas </td>
<td>Investigar, analizar y validar la viabilidad técnica y funcional de los servicios de terceros y mecanismos de extracción de métricas necesarias.</td>
</tr>

<br>

</tbody>
</table>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-01</strong></td>
<td>Visitante del segmento de pymes</td>
<td>Alta</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Presentación de CollabPro para empresas</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de pymes, quiero conocer la propuesta de valor de CollabPro,
para determinar si la plataforma puede ayudarme a gestionar colaboraciones con creadores de contenido.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Comprensión de la propuesta</strong><br><br>
<strong>Dado que</strong> el visitante ingresa a la Landing Page<br><br>
<strong>Cuando</strong> consulta la información principal de CollabPro<br><br>
<strong>Entonces</strong> comprende que la plataforma permite gestionar campañas con creadores de contenido de forma profesional y justa.<br><br>
<strong>Escenario 2: Identificación de beneficios</strong><br><br>
<strong>Dado que</strong> el visitante consulta la propuesta de valor<br><br>
<strong>Cuando</strong> revisa los beneficios de CollabPro<br><br>
<strong>Entonces</strong> identifica que puede centralizar campañas, requisitos, entregables, compensaciones y seguimiento.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-02</strong></td>
<td>Visitante del segmento de creadores</td>
<td>Alta</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Presentación de CollabPro para creadores</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de creadores, quiero conocer la propuesta de
valor de CollabPro, para determinar si la plataforma puede ayudarme a
encontrar y gestionar colaboraciones con empresas.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Comprensión de la propuesta</strong><br><br>
<strong>Dado que</strong> el visitante ingresa a la Landing Page<br><br>
<strong>Cuando</strong> consulta la información principal de CollabPro<br><br>
<strong>Entonces</strong> comprende que la plataforma permite encontrar y gestionar campañas con empresas.<br><br>
<strong>Escenario 2: Identificación de beneficios</strong><br><br>
<strong>Dado que</strong> el visitante consulta los beneficios de la plataforma<br><br>
<strong>Cuando</strong> revisa las características principales<br><br>
<strong>Entonces</strong> identifica que puede conocer los requisitos, entregables, fechas y compensaciones de una empresa antes de aceptar una colaboración.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-03</strong></td>
<td>Visitante del segmento de pymes</td>
<td>Media</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Información sobre el funcionamiento de CollabPro para empresas</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de pymes, quiero conocer cómo se desarrolla una
colaboración en CollabPro, para saber cómo manejar correctamente la herramienta antes de registrarme.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Proceso de colaboración</strong><br><br>
<strong>Dado que</strong> el visitante revisa el funcionamiento de CollabPro<br><br>
<strong>Cuando</strong> revisa el proceso de colaboración<br><br>
<strong>Entonces</strong> identifica las etapas de creación de campaña, recepción de postulaciones, selección, ejecución y validación.<br><br>
<strong>Escenario 2: Cumplimiento de colaboración</strong><br><br>
<strong>Dado que</strong> el visitante revisa el proceso de una colaboración<br><br>
<strong>Cuando</strong> consulta cómo se verifica su cumplimiento<br><br>
<strong>Entonces</strong> comprende que los entregables son validados antes de completar el proceso del pago de la colaboración.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-04</strong></td>
<td>Visitante del segmento de creadores</td>
<td>Media</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Información sobre el funcionamiento de CollabPro para creadores</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de creadores, quiero conocer cómo participar en
una colaboración dentro de CollabPro, para conocer mis responsabilidades y 
condiciones de la colaboración antes de registrarme.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Participación en campañas</strong><br><br>
<strong>Dado que</strong> el visitante consulta el funcionamiento de CollabPro<br><br>
<strong>Cuando</strong> revisa el proceso detallado de colaboración para creadores<br><br>
<strong>Entonces</strong> identifica las etapas de búsqueda, postulación, aceptación, entrega y validación.<br><br>
<strong>Escenario 2: Revisión de las condiciones de colaboración</strong><br><br>
<strong>Dado que</strong> el visitante consulta el proceso de una colaboración<br><br>
<strong>Cuando</strong> revisa cómo se dan las condiciones de participación y de cumplimiento<br><br>
<strong>Entonces</strong> comprende que las condiciones se conocen antes de confirmar una colaboración.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-05</strong></td>
<td>Visitante del segmento de pymes o de creadores</td>
<td>Media</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Contacto con CollabPro</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de pymes o de creadores, quiero comunicarme con
CollabPro, para solicitar información adicional o realizar una consulta sobre
el servicio.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Envío de consulta</strong><br><br>
<strong>Dado que</strong> el visitante proporciona la información requerida de contacto<br><br>
<strong>Cuando</strong> envía una consulta<br><br>
<strong>Entonces</strong> se registra la solicitud y se le confirma su recepción.<br><br>
<strong>Escenario 2: Información incompleta</strong><br><br>
<strong>Dado que</strong> el visitante omite información requerida de contacto<br><br>
<strong>Cuando</strong> intenta enviar una consulta<br><br>
<strong>Entonces</strong> se le impide registrar la solicitud hasta completar la información requerida.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-06</strong></td>
<td>Visitante del segmento de pymes o de creadores</td>
<td>Media</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Cambio de idioma</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de pymes o de creadores, quiero consultar la
información de CollabPro en español o inglés, para comprender la propuesta
de acuerdo al idioma seleccionado.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Idioma inglés</strong><br><br>
<strong>Dado que</strong> el visitante ingresa a la Landing Page<br><br>
<strong>Cuando</strong> selecciona la opción de visualización en inglés<br><br>
<strong>Entonces</strong> el contenido disponible se muestra en este idioma.<br><br>
<strong>Escenario 2: Idioma español</strong><br><br>
<strong>Dado que</strong> el visitante ingresa a la Landing Page<br><br>
<strong>Cuando</strong> selecciona la opción de visualización en español<br><br>
<strong>Entonces</strong> el contenido disponible se muestra en este idioma.<br><br>
<strong>Escenario 3: Conservación del idioma</strong><br><br>
<strong>Dado que</strong> el visitante ha seleccionado un idioma<br><br>
<strong>Cuando</strong> continúa navegando por la Landing Page<br><br>
<strong>Entonces</strong> el contenido mantiene el idioma seleccionado.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-07</strong></td>
<td>Visitante del segmento de pymes o de creadores</td>
<td>Media</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Compatibilidad visual de la Landing Page con varios dispositivos</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de pymes o de creadores, quiero consultar la
landing desde diferentes dispositivos, para acceder a la información sin
importar el tamaño de pantalla.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Acceso desde dispositivo móvil</strong><br><br>
<strong>Dado que</strong> el visitante accede desde un dispositivo móvil<br><br>
<strong>Cuando</strong> consulta la Landing Page<br><br>
<strong>Entonces</strong> puede acceder al contenido y a las funcionalidades disponibles en formato móvil sin pérdida de información esencial.<br><br>
<strong>Escenario 2: Acceso desde computadora de escritorio</strong><br><br>
<strong>Dado que</strong> el visitante accede desde una computadora<br><br>
<strong>Cuando</strong> consulta la Landing Page<br><br>
<strong>Entonces</strong> puede acceder al contenido y a las funcionalidades disponibles en formato de escritorio.<br><br>
<strong>Escenario 3: Cambio de orientación</strong><br><br>
<strong>Dado que</strong> el visitante utiliza un dispositivo que permite cambiar de orientación<br><br>
<strong>Cuando</strong> cambia la orientación del dispositivo<br><br>
<strong>Entonces</strong> el contenido continúa siendo visible y comprensible.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-08</strong></td>
<td>Visitante del segmento de pymes o de creadores</td>
<td>Alta</td>
<td>EP-01</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Registro desde la Landing Page</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como visitante del segmento de pymes o de creadores, quiero acceder al
registro correspondiente a mi segmento, para comenzar a utilizar CollabPro.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro empresarial</strong><br><br>
<strong>Dado que</strong> el visitante pertenece al segmento de pymes<br><br>
<strong>Cuando</strong> selecciona el registro de cuenta empresarial<br><br>
<strong>Entonces</strong> es dirigido al proceso de registro correspondiente.<br><br>
<strong>Escenario 2: Registro de creador de contenido</strong><br><br>
<strong>Dado que</strong> el visitante pertenece al segmento de creadores<br><br>
<strong>Cuando</strong> selecciona el registro de cuenta de creador de contenido<br><br>
<strong>Entonces</strong> es dirigido al proceso de registro correspondiente.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-09</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-02</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Registro de empresa</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero crear una cuenta en CollabPro,
para gestionar campañas con creadores.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro válido</strong><br><br>
<strong>Dado que</strong> la empresa proporciona la información obligatoria y un correo no registrado<br><br>
<strong>Cuando</strong> completa el registro<br><br>
<strong>Entonces</strong> se le crea una cuenta empresarial.<br><br>
<strong>Escenario 2: Cuenta existente</strong><br><br>
<strong>Dado que</strong> el correo ya está asociado a una cuenta<br><br>
<strong>Cuando</strong> la empresa intenta registrarse nuevamente<br><br>
<strong>Entonces</strong> se le impide crear una cuenta duplicada.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-10</strong></td>
<td>Creador de contenido</td>
<td>Alta</td>
<td>EP-02</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Registro de creador</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero crear una cuenta en CollabPro,
para encontrar oportunidades de colaboración con empresas.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro válido</strong><br><br>
<strong>Dado que</strong> el creador proporciona la información obligatoria y un correo no registrado<br><br>
<strong>Cuando</strong> completa el registro<br><br>
<strong>Entonces</strong> se le crea la cuenta de creador.<br><br>
<strong>Escenario 2: Cuenta existente</strong><br><br>
<strong>Dado que</strong> el correo ya está asociado a una cuenta<br><br>
<strong>Cuando</strong> el creador intenta registrarse nuevamente<br><br>
<strong>Entonces</strong> se le impide crear una cuenta duplicada.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-11</strong></td>
<td>Usuario de CollabPro</td>
<td>Alta</td>
<td>EP-02</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Inicio de sesión y recuperación de cuenta</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como usuario de CollabPro, quiero iniciar sesión y recuperar el acceso a mi
cuenta, para utilizar la plataforma cuando lo necesite.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Inicio de sesión válido</strong><br><br>
<strong>Dado que</strong> existe una cuenta activa<br><br>
<strong>Cuando</strong> el usuario proporciona credenciales de acceso válidas<br><br>
<strong>Entonces</strong> se le concede acceso a las funcionalidades correspondientes a su tipo de cuenta.<br><br>
<strong>Escenario 2: Credenciales inválidas</strong><br><br>
<strong>Dado que</strong> las credenciales proporcionadas no son válidas<br><br>
<strong>Cuando</strong> el usuario intenta iniciar sesión<br><br>
<strong>Entonces</strong> se le rechaza el acceso.<br><br>
<strong>Escenario 3: Recuperación de cuenta</strong><br><br>
<strong>Dado que</strong> existe una cuenta asociada al correo proporcionado<br><br>
<strong>Cuando</strong> el usuario solicita recuperar el acceso<br><br>
<strong>Entonces</strong> se inicia el proceso de recuperación correspondiente.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-12</strong></td>
<td>Representante de una pyme</td>
<td>Media</td>
<td>EP-02</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Gestión del perfil empresarial</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero administrar la información de mi empresa,
para proporcionar a los creadores de contenido información relevante antes de una colaboración.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro de información</strong><br><br>
<strong>Dado que</strong> la empresa tiene una cuenta activa<br><br>
<strong>Cuando</strong> registra información válida del negocio<br><br>
<strong>Entonces</strong> el sistema guarda la información del perfil.<br><br>
<strong>Escenario 2: Actualización de información</strong><br><br>
<strong>Dado que</strong> existe información empresarial registrada<br><br>
<strong>Cuando</strong> la empresa cambia datos modificables<br><br>
<strong>Entonces</strong> se actualiza la información correspondiente.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-13</strong></td>
<td>Creador de contenido</td>
<td>Media</td>
<td>EP-02</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Gestión del perfil de creadores</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero administrar la información de mi perfil,
para mostrar información relevante para las empresas.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro de perfil</strong><br><br>
<strong>Dado que</strong> el creador tiene una cuenta activa<br><br>
<strong>Cuando</strong> proporciona información válida sobre su contenido y audiencia<br><br>
<strong>Entonces</strong> se guarda la información de su perfil.<br><br>
<strong>Escenario 2: Actualización del perfil</strong><br><br>
<strong>Dado que</strong> existe un perfil guardado<br><br>
<strong>Cuando</strong> el creador modifica información permitida<br><br>
<strong>Entonces</strong> se le actualiza el perfil.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-14</strong></td>
<td>Creador de contenido</td>
<td>Media</td>
<td>EP-02</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Vinculación de redes sociales</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero vincular mis redes sociales a CollabPro,
para acreditar mi presencia digital y permitir obtener información autorizada
de mis publicaciones.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Vinculación autorizada</strong><br><br>
<strong>Dado que</strong> el creador dispone de una cuenta compatible<br><br>
<strong>Cuando</strong> autoriza la vinculación solicitada desde esa cuenta<br><br>
<strong>Entonces</strong> el sistema registra la red social como vinculada.<br><br>
<strong>Escenario 2: Autorización rechazada</strong><br><br>
<strong>Dado que</strong> el creador no concede los permisos solicitados<br><br>
<strong>Cuando</strong> finaliza el proceso de autorización<br><br>
<strong>Entonces</strong> no se registra la cuenta como vinculada.<br><br>
<strong>Escenario 3: Cuenta ya vinculada</strong><br><br>
<strong>Dado que</strong> una cuenta social ya está asociada a su perfil<br><br>
<strong>Cuando</strong> un creador intenta vincularla nuevamente<br><br>
<strong>Entonces</strong> se le impide duplicar la vinculación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-15</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Creación de campaña</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero publicar una campaña,
para encontrar creadores de contenido que puedan cumplir mis objetivos de marketing.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Creación válida</strong><br><br>
<strong>Dado que</strong> la empresa tiene una cuenta habilitada<br><br>
<strong>Cuando</strong> registra la información obligatoria de la campaña<br><br>
<strong>Entonces</strong> se crea la campaña y se vuelve visible para todos los creadores registrados.<br><br>
<strong>Escenario 2: Información incompleta</strong><br><br>
<strong>Dado que</strong> falta información obligatoria sobre la campaña<br><br>
<strong>Cuando</strong> la empresa intenta publicar la campaña<br><br>
<strong>Entonces</strong> se impide la publicación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-16</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Definición de condiciones de campaña</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero definir requisitos, entregables,
plazos y compensación, para establecer las condiciones de la colaboración
antes de recibir postulaciones.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Condiciones válidas</strong><br><br>
<strong>Dado que</strong> existe una campaña en preparación<br><br>
<strong>Cuando</strong> la empresa registra las condiciones obligatorias<br><br>
<strong>Entonces</strong> se asocian estas condiciones a la campaña.<br><br>
<strong>Escenario 2: Condiciones incompatibles</strong><br><br>
<strong>Dado que</strong> existe una condición incompatible con las fechas o reglas de la campaña<br><br>
<strong>Cuando</strong> la empresa intenta guardar las condiciones<br><br>
<strong>Entonces</strong> se impide guardar la campaña con estas condiciones.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-17</strong></td>
<td>Creador de contenido</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Búsqueda de campañas</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero buscar campañas según mis intereses y
características, para encontrar oportunidades de colaboración relevantes.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Búsqueda con coincidencias</strong><br><br>
<strong>Dado que</strong> existen campañas publicadas<br><br>
<strong>Cuando</strong> el creador utiliza criterios de búsqueda<br><br>
<strong>Entonces</strong> se muestran las campañas que cumplen con los criterios.<br><br>
<strong>Escenario 2: Búsqueda sin coincidencias</strong><br><br>
<strong>Dado que</strong> ninguna campaña cumple los criterios definidos<br><br>
<strong>Cuando</strong> el creador realiza la búsqueda<br><br>
<strong>Entonces</strong> se le informa que no existen coincidencias.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-18</strong></td>
<td>Creador de contenido</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Consulta de condiciones de una campaña</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero consultar las condiciones a detalle de una
campaña, para determinar si puedo cumplirlas antes de postular.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Campaña disponible</strong><br><br>
<strong>Dado que</strong> existe una campaña abierta<br><br>
<strong>Cuando</strong> el creador consulta la campaña<br><br>
<strong>Entonces</strong> se le muestra el objetivo, requisitos, entregables, fechas y pago.<br><br>
<strong>Escenario 2: Campaña cerrada</strong><br><br>
<strong>Dado que</strong> la campaña ya no acepta postulaciones<br><br>
<strong>Cuando</strong> el creador consulta la campaña<br><br>
<strong>Entonces</strong> se informa que la campaña no admite nuevas postulaciones.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-19</strong></td>
<td>Creador de contenido</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Postulación a campaña</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero postular a una campaña,
para participar en oportunidades comerciales relevantes.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Postulación válida</strong><br><br>
<strong>Dado que</strong> la campaña acepta nuevas postulaciones<br><br>
<strong>Cuando</strong> el creador cumple las condiciones requeridas y presenta su postulación<br><br>
<strong>Entonces</strong> se registra la postulación como pendiente.<br><br>
<strong>Escenario 2: Postulación duplicada</strong><br><br>
<strong>Dado que</strong> el creador ya se ha postulado<br><br>
<strong>Cuando</strong> intenta postular nuevamente<br><br>
<strong>Entonces</strong> se le impide duplicar la postulación.<br><br>
<strong>Escenario 3: Incumplimiento de requisito</strong><br><br>
<strong>Dado que</strong> el creador no cumple una condición obligatoria<br><br>
<strong>Cuando</strong> intenta presentar la postulación<br><br>
<strong>Entonces</strong> se le impide registrar la postulación y se le muestra la condición incumplida.<br><br>
<strong>Escenario 4: Edición de postulación</strong><br><br>
<strong>Dado que</strong> el creador ya se ha postulado<br><br>
<strong>Cuando</strong> la postulación se encuentra pendiente<br><br>
<strong>Entonces</strong> se le permite editar la postulación.<br><br>
<strong>Escenario 4: Cancelación de postulación</strong><br><br>
<strong>Dado que</strong> el creador ya se ha postulado<br><br>
<strong>Cuando</strong> la postulación se encuentra pendiente<br><br>
<strong>Entonces</strong> se le permite cancelar su postulación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-20</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Evaluación de postulaciones</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero revisar las postulaciones recibidas,
para seleccionar al creador que cumpla las condiciones de mi campaña.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Consulta de postulaciones</strong><br><br>
<strong>Dado que</strong> existen postulaciones para una campaña<br><br>
<strong>Cuando</strong> la empresa las consulta<br><br>
<strong>Entonces</strong> se proporciona la información de cada postulante.<br><br>
<strong>Escenario 2: Selección de postulantes</strong><br><br>
<strong>Dado que</strong> existen postulaciones para una campaña<br><br>
<strong>Cuando</strong> la empresa elige a los creadores y los acepta<br><br>
<strong>Entonces</strong> se registra la elección.<br><br>
<strong>Escenario 3: Rechazo de postulante</strong><br><br>
<strong>Dado que</strong> se revisó una postulación<br><br>
<strong>Cuando</strong> la empresa la rechaza<br><br>
<strong>Entonces</strong> se le informa el resultado de su postulacion al creador de contenido.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-21</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Aceptación de una colaboración</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero formalizar la colaboración con un creador
seleccionado, para dejar establecidas las condiciones que ambas partes deben cumplir.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Aceptación de ambas partes</strong><br><br>
<strong>Dado que</strong> existe una postulación seleccionada<br><br>
<strong>Cuando</strong> ambas partes se comunican y aceptan las condiciones<br><br>
<strong>Entonces</strong> se crea la colaboración con las condiciones acordadas.<br><br>
<strong>Escenario 2: Rechazo de las condiciones</strong><br><br>
<strong>Dado que</strong> una de las partes no acepta las condiciones<br><br>
<strong>Cuando</strong> finaliza el proceso de aceptación<br><br>
<strong>Entonces</strong> no se inicia la colaboración.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-22</strong></td>
<td>Empresa o creador de contenido</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Consulta del estado de una colaboración</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como empresa o creador de contenido, quiero consultar el estado de una
colaboración, para conocer las acciones pendientes y las etapas completadas.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Colaboración activa</strong><br><br>
<strong>Dado que</strong> existe una colaboración vigente<br><br>
<strong>Cuando</strong> el usuario consulta su estado<br><br>
<strong>Entonces</strong> se le muestra la etapa actual y las acciones pendientes.<br><br>
<strong>Escenario 2: Colaboración vencida</strong><br><br>
<strong>Dado que</strong> se ha superado una fecha límite sin completar los requisitos correspondientes<br><br>
<strong>Cuando</strong> se actualiza el estado de la colaboración<br><br>
<strong>Entonces</strong> se marca como vencida según las reglas establecidas.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-23</strong></td>
<td>Creador de contenido</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Entrega de contenido y evidencias</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero registrar mis entregables y evidencias,
para demostrar el cumplimiento de la colaboración.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Entrega válida</strong><br><br>
<strong>Dado que</strong> la colaboración permite registrar entregables<br><br>
<strong>Cuando</strong> el creador presenta el contenido y la evidencia requerida<br><br>
<strong>Entonces</strong> se registra la entrega como pendiente de validación.<br><br>
<strong>Escenario 2: Entrega fuera de plazo</strong><br><br>
<strong>Dado que</strong> se ha superado la fecha límite<br><br>
<strong>Cuando</strong> el creador presenta la entrega<br><br>
<strong>Entonces</strong> se registra la entrega como fuera del plazo establecido.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-24</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Validación de entregables</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero validar los entregables recibidos,
para determinar si cumplen las condiciones acordadas.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Entregable aprobado</strong><br><br>
<strong>Dado que</strong> existe un entregable pendiente de validación<br><br>
<strong>Cuando</strong> la empresa determina que cumple las condiciones<br><br>
<strong>Entonces</strong> se registra el entregable como aprobado.<br><br>
<strong>Escenario 2: Entregable rechazado</strong><br><br>
<strong>Dado que</strong> el entregable incumple una condición<br><br>
<strong>Cuando</strong> la empresa lo rechaza<br><br>
<strong>Entonces</strong> se registra el rechazo y las observaciones.<br><br>
<strong>Escenario 3: Corrección del entregable</strong><br><br>
<strong>Dado que</strong> la colaboración permite corregir un entregable<br><br>
<strong>Cuando</strong> el creador presenta una nueva versión<br><br>
<strong>Entonces</strong> se registra la nueva entrega para validación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-25</strong></td>
<td>Empresa o creador de contenido</td>
<td>Media</td>
<td>EP-03</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Gestión de incidencias</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como empresa o creador de contenido, quiero registrar una incidencia sobre una
colaboración, para resolver desacuerdos relacionados con las condiciones,
los entregables o el cumplimiento.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro de incidencia</strong><br><br>
<strong>Dado que</strong> existe una colaboración activa o recientemente finalizada<br><br>
<strong>Cuando</strong> una de las partes registra una incidencia válida<br><br>
<strong>Entonces</strong> se registra la incidencia asociada a la colaboración y se guarda en un historial.<br><br>
<strong>Escenario 2: Resolución de incidencia</strong><br><br>
<strong>Dado que</strong> existe una incidencia pendiente<br><br>
<strong>Cuando</strong> se registra una resolución válida<br><br>
<strong>Entonces</strong> se actualiza el estado de la incidencia y se guarda en un historial.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-26</strong></td>
<td>Empresa o creador de contenido</td>
<td>Alta</td>
<td>EP-04</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Vinculación de medio de pago</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como empresa o creador de contenido, quiero vincular un medio de pago,
para cumplir las condiciones necesarias para participar en operaciones
económicas dentro de CollabPro.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Vinculación correcta</strong><br><br>
<strong>Dado que</strong> el usuario dispone de un medio de pago válido<br><br>
<strong>Cuando</strong> completa el proceso de vinculación<br><br>
<strong>Entonces</strong> se registra este medio de pago.<br><br>
<strong>Escenario 2: Vinculación fallida</strong><br><br>
<strong>Dado que</strong> el medio de pago no puede ser validado<br><br>
<strong>Cuando</strong> el usuario intenta asociarlo<br><br>
<strong>Entonces</strong> se informa que el medio de pago no fue vinculado.<br><br>
<strong>Escenario 3: Operación sin medio de pago</strong><br><br>
<strong>Dado que</strong> una operación económica requiere un medio de pago asociado<br><br>
<strong>Cuando</strong> el usuario intenta iniciar una operación sin tener ninguno asociado<br><br>
<strong>Entonces</strong> se le impide continuar con esa operación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-27</strong></td>
<td>Representante de una pyme</td>
<td>Alta</td>
<td>EP-04</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Suscripción de la empresa</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero tener una suscripción de pago de CollabPro,
para utilizar las funcionalidades incluidas en el plan seleccionado.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Suscripción válida</strong><br><br>
<strong>Dado que</strong> la empresa tiene un medio de pago válido<br><br>
<strong>Cuando</strong> elige una suscripción disponible y la confirma<br><br>
<strong>Entonces</strong> se registra la suscripción como activa.<br><br>
<strong>Escenario 2: Cobro fallido</strong><br><br>
<strong>Dado que</strong> el medio de pago no permite completar el cobro<br><br>
<strong>Cuando</strong> se procesa el pago de la suscripción<br><br>
<strong>Entonces</strong> se registra el fallo y no se activa la suscripción.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-28</strong></td>
<td>Creador de contenido</td>
<td>Alta</td>
<td>EP-04</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Consulta del estado de la compensación</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como creador de contenido, quiero consultar el estado de mi paga,
para conocer si se encuentra pendiente, pagada o afectada
por una incidencia.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Compensación pendiente</strong><br><br>
<strong>Dado que</strong> existen entregables pendientes de validación<br><br>
<strong>Cuando</strong> el creador consulta la compensación<br><br>
<strong>Entonces</strong> se le informa que el pago no se realiza hasta que todos los entregables hayan sido validados.<br><br>
<strong>Escenario 2: Compensación pagada</strong><br><br>
<strong>Dado que</strong> se han validado todos los entregables<br><br>
<strong>Cuando</strong> la empresa se confirma el pago<br><br>
<strong>Entonces</strong> se registra la compensación como pagada.<br><br>
<strong>Escenario 3: Compensación afectada por una incidencia</strong><br><br>
<strong>Dado que</strong> existe una incidencia que afecta el proceso de compensación<br><br>
<strong>Cuando</strong> el creador consulta el estado<br><br>
<strong>Entonces</strong> se le informa que la compensación se encuentra afectada por la incidencia.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-29</strong></td>
<td>Representante de una pyme</td>
<td>Media</td>
<td>EP-04</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Consulta y atribución de resultados de campaña</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como representante de una pyme, quiero consultar los resultados verificables
de una colaboración, para evaluar el desempeño obtenido con la información disponible.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Métricas disponibles</strong><br><br>
<strong>Dado que</strong> una colaboración tiene contenido publicado y existen métricas autorizadas disponibles<br><br>
<strong>Cuando</strong> la empresa consulta los resultados<br><br>
<strong>Entonces</strong> se presentan las métricas disponibles junto con su fuente y periodo de referencia.<br><br>
<strong>Escenario 2: Métricas no disponibles</strong><br><br>
<strong>Dado que</strong> la red social donde se publicó el contenido no proporciona las métricas requeridas<br><br>
<strong>Cuando</strong> la empresa consulta los resultados<br><br>
<strong>Entonces</strong> se informa que no existen métricas disponibles.<br><br>
<strong>Escenario 3: Evidencia proporcionada por el creador</strong><br><br>
<strong>Dado que</strong> no existen datos automatizados pero la colaboración permite presentar evidencias<br><br>
<strong>Cuando</strong> el creador proporciona una evidencia válida<br><br>
<strong>Entonces</strong> se registra la evidencia como información de referencia de la colaboración.<br><br>
<strong>Escenario 4: Atribución de resultados</strong><br><br>
<strong>Dado que</strong> la campaña utiliza un enlace o código asociado a una colaboración<br><br>
<strong>Cuando</strong> se registra una interacción atribuible<br><br>
<strong>Entonces</strong> se asocian estos datos a la colaboración correspondiente.<br><br>
<strong>Escenario 5: Interpretación de resultados</strong><br><br>
<strong>Dado que</strong> existen resultados atribuibles registrados<br><br>
<strong>Cuando</strong> la empresa consulta la información de la campaña<br><br>
<strong>Entonces</strong> se presentan los resultados atribuibles con la advertencia de que solo son estimaciones y se debe considerarlos con cautela.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>US-30</strong></td>
<td>Empresa o creador de contenido</td>
<td>Media</td>
<td>EP-04</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Historial de colaboraciones</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como empresa o creador de contenido, quiero consultar el historial de mis
colaboraciones, para revisar acuerdos, entregables y resultados anteriores.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Historial existente</strong><br><br>
<strong>Dado que</strong> el usuario ha participado en colaboraciones anteriores<br><br>
<strong>Cuando</strong> consulta su historial<br><br>
<strong>Entonces</strong> se le proporciona la lista de colaboraciones asociadas y detalles relevantes.<br><br>
<strong>Escenario 2: Historial vacío</strong><br><br>
<strong>Dado que</strong> el usuario no tiene colaboraciones anteriores<br><br>
<strong>Cuando</strong> consulta su historial<br><br>
<strong>Entonces</strong> se le informa que no existen colaboraciones registradas.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-01</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de autenticación de cuentas</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST para registrar usuarios,
autenticar cuentas y gestionar el acceso, para que las aplicaciones móviles
puedan utilizar las funciones correspondientes a cada tipo de usuario.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Registro</strong><br><br>
<strong>Dado que</strong> no existe una cuenta con el correo proporcionado<br><br>
<strong>Cuando</strong> la aplicación realiza una petición <strong>POST /api/v1/auth/register</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma la creación de la cuenta.<br><br>
<strong>Escenario 2: Inicio de sesión</strong><br><br>
<strong>Dado que</strong> existen credenciales válidas<br><br>
<strong>Cuando</strong> la aplicación realiza una petición <strong>POST /api/v1/auth/login</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona las credenciales necesarias para utilizar los servicios protegidos.<br><br>
<strong>Escenario 3: Acceso inválido</strong><br><br>
<strong>Dado que</strong> las credenciales no son válidas<br><br>
<strong>Cuando</strong> la aplicación intenta iniciar sesión<br><br>
<strong>Entonces</strong> la API responde con código <strong>401 Unauthorized</strong> y rechaza el acceso.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-02</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de perfiles y redes sociales</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST para consultar y actualizar
perfiles y gestionar vinculaciones con redes sociales, para que las aplicaciones
puedan administrar la información de empresas y creadores.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Consulta de perfil</strong><br><br>
<strong>Dado que</strong> existe una sesión autenticada<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/user/{id}</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona la información del perfil correspondiente al usuario autenticado.<br><br>
<strong>Escenario 2: Actualización de perfil</strong><br><br>
<strong>Dado que</strong> existe un perfil válido<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>PATCH /api/v1/user/{id}</strong> con información permitida<br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y confirma la actualización del perfil.<br><br>
<strong>Escenario 3: Vinculación de red social</strong><br><br>
<strong>Dado que</strong> el proceso de autorización de una red social fue completado correctamente<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/user/{id}/social-media</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y registra la asociación con la cuenta de la red social.<br><br>
<strong>Escenario 4: Consulta de redes vinculadas</strong><br><br>
<strong>Dado que</strong> el usuario posee redes sociales vinculadas<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/user/{id}/social-media</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona las asociaciones registradas.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-03</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de campañas y postulaciones</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST para gestionar campañas
y postulaciones, para que empresas y creadores puedan utilizar el marketplace
desde las aplicaciones móviles.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Crear campaña</strong><br><br>
<strong>Dado que</strong> existe una empresa autenticada y autorizada<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/campaigns</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma la creación de la campaña.<br><br>
<strong>Escenario 2: Actualizar campaña</strong><br><br>
<strong>Dado que</strong> existe una campaña y se le quiere realizar modificaciones<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>PATCH /api/v1/campaigns/{id}</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y confirma la actualización de la campaña.<br><br>
<strong>Escenario 3: Consultar campañas</strong><br><br>
<strong>Dado que</strong> existen campañas disponibles<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/campaigns</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona las campañas disponibles.<br><br>
<strong>Escenario 4: Consultar una campaña</strong><br><br>
<strong>Dado que</strong> se elige una campaña disponible<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/campaigns/{id}</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona los datos de la campaña.<br><br>
<strong>Escenario 5: Registrar postulación</strong><br><br>
<strong>Dado que</strong> la campaña acepta postulaciones<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/campaigns/{id}/applications</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma la postulación.<br><br>
<strong>Escenario 6: Consultar postulaciones</strong><br><br>
<strong>Dado que</strong> existen postulaciones para una campaña<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/campaigns/{id}/applications</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona las postulaciones disponibles para esa empresa.<br><br>
<strong>Escenario 7: Actualizar postulación</strong><br><br>
<strong>Dado que</strong> existe una postulación válida y se quiere editarla<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>PATCH /api/v1/applications/{id}</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y confirma la actualización de la postulación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-04</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de colaboraciones y entregables</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST de colaboraciones y
entregables, para permitir que las aplicaciones gestionen la ejecución de los acuerdos.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Crear colaboración</strong><br><br>
<strong>Dado que</strong> una postulación ha sido seleccionada y las partes aceptaron las condiciones<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/collaborations</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma la creación de la colaboración.<br><br>
<strong>Escenario 2: Consultar colaboración</strong><br><br>
<strong>Dado que</strong> existe una colaboración<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/collaborations/{id}</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona el estado, las fechas, las condiciones y los entregables asociados.<br><br>
<strong>Escenario 3: Registrar entrega</strong><br><br>
<strong>Dado que</strong> la colaboración permite realizar una entrega<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/collaborations/{id}/deliverables</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma el registro de la entrega.<br><br>
<strong>Escenario 4: Consultar entregas</strong><br><br>
<strong>Dado que</strong> existen entregables registrados<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/collaborations/{id}/deliverables</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona las entregas y su estado de validación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-05</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de validación, incidencias y compensaciones</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST para validar entregables,
gestionar incidencias y consultar compensaciones, para mantener la trazabilidad
del cumplimiento de las colaboraciones.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Aprobar entrega</strong><br><br>
<strong>Dado que</strong> existe un entregable pendiente de revisión<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/deliverables/{id}/validation</strong> con una aprobación<br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y confirma la validación.<br><br>
<strong>Escenario 2: Rechazar entrega</strong><br><br>
<strong>Dado que</strong> existe un entregable que incumple las condiciones<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/deliverables/{id}/rejection</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y conserva el motivo registrado.<br><br>
<strong>Escenario 3: Registrar incidencia</strong><br><br>
<strong>Dado que</strong> existe una colaboración válida<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/collaborations/{id}/incidents</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y registra la incidencia.<br><br>
<strong>Escenario 4: Consultar incidencia</strong><br><br>
<strong>Dado que</strong> existe una incidencia registrada<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/collaborations/{id}/incidents</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona el estado actual de la incidencia.<br><br>
<strong>Escenario 5: Consultar compensación</strong><br><br>
<strong>Dado que</strong> existe una colaboración con compensación asociada<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/collaborations/{id}/compensation</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona el estado actual de la compensación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-06</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de suscripciones y pagos</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST para gestionar medios de
pago, suscripciones y pagos de colaboraciones, para que las aplicaciones puedan
utilizar los servicios financieros de CollabPro.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Preparación del medio de pago</strong><br><br>
<strong>Dado que</strong> un usuario necesita asociar un medio de pago<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/user/{id}/billing</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y proporciona la información necesaria para completar el proceso mediante el proveedor de pagos.<br><br>
<strong>Escenario 2: Creación de suscripción</strong><br><br>
<strong>Dado que</strong> existe un medio de pago de prueba válido<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/user/{id}/subscription</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma la creación de la suscripción.<br><br>
<strong>Escenario 3: Consulta de suscripción</strong><br><br>
<strong>Dado que</strong> existe una suscripción registrada<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/user/{id}/subscription</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona el estado actual de la suscripción.<br><br>
<strong>Escenario 4: Inicio de pago de colaboración</strong><br><br>
<strong>Dado que</strong> una colaboración cumple las condiciones necesarias para iniciar su compensación<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/collaborations/{id}/payment</strong><br><br>
<strong>Entonces</strong> la API responde confirmando el inicio del proceso de pago.<br><br>
<strong>Escenario 5: Recepción de evento de pago</strong><br><br>
<strong>Dado que</strong> el proveedor de pagos genera un evento relacionado con una transacción<br><br>
<strong>Cuando</strong> el backend recibe <strong>POST /api/v1/webhooks/payments</strong><br><br>
<strong>Entonces</strong> valida el evento y actualiza el estado correspondiente sin duplicar la operación.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>TS-07</strong></td>
<td>Developer</td>
<td>Media</td>
<td>EP-05</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Servicios de métricas, evidencias y atribución</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero implementar los servicios REST para consultar métricas
disponibles, registrar evidencias y gestionar mecanismos de atribución, para que
las aplicaciones puedan presentar resultados verificables de las colaboraciones.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Consulta de métricas</strong><br><br>
<strong>Dado que</strong> una colaboración dispone de métricas autorizadas<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/collaborations/{id}/metrics</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona las métricas disponibles, su origen y el periodo correspondiente.<br><br>
<strong>Escenario 2: Métricas no disponibles</strong><br><br>
<strong>Dado que</strong> no existen métricas automatizadas disponibles<br><br>
<strong>Cuando</strong> la aplicación consulta el recurso<br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> indicando que no existen métricas disponibles.<br><br>
<strong>Escenario 3: Registro de evidencia</strong><br><br>
<strong>Dado que</strong> una colaboración permite registrar evidencias adicionales<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/collaborations/{id}/evidence</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y registra la evidencia asociada a la colaboración.<br><br>
<strong>Escenario 4: Creación de mecanismo de atribución</strong><br><br>
<strong>Dado que</strong> la colaboración permite utilizar un mecanismo de atribución por un enlace personalizado en la publicación del creador de contenido<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>POST /api/v1/collaborations/{id}/attribution</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>201 Created</strong> y confirma la creación del mecanismo correspondiente.<br><br>
<strong>Escenario 5: Consulta de resultados atribuibles</strong><br><br>
<strong>Dado que</strong> existen resultados asociados a un mecanismo de atribución<br><br>
<strong>Cuando</strong> la aplicación realiza <strong>GET /api/v1/collaborations/{id}/attribution</strong><br><br>
<strong>Entonces</strong> la API responde con código <strong>200 OK</strong> y proporciona los resultados atribuibles disponibles.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>SS-01</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-06</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Viabilidad de Stripe en Sandbox</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero investigar y probar la integración de Stripe en Sandbox
para las suscripciones y las compensaciones de las colaboraciones, para definir
un flujo técnicamente viable antes de implementar los servicios de pago.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Suscripción</strong><br><br>
<strong>Dado que</strong> CollabPro requiere cobrar una suscripción a las empresas<br><br>
<strong>Cuando</strong> el equipo prueba el flujo de suscripción utilizando Stripe Sandbox<br><br>
<strong>Entonces</strong> documenta el proceso necesario desde la asociación del medio de pago hasta la confirmación del cobro de prueba.<br><br>
<strong>Escenario 2: Compensación</strong><br><br>
<strong>Dado que</strong> una colaboración puede requerir una compensación económica<br><br>
<strong>Cuando</strong> el equipo prueba el flujo de pago correspondiente en Sandbox<br><br>
<strong>Entonces</strong> documenta cómo se representa, confirma y actualiza el estado del pago de prueba.<br><br>
<strong>Escenario 3: Incumplimiento</strong><br><br>
<strong>Dado que</strong> una colaboración puede presentar un incumplimiento<br><br>
<strong>Cuando</strong> el equipo prueba las operaciones disponibles para revertir, reembolsar o ajustar un pago de prueba<br><br>
<strong>Entonces</strong> documenta qué alternativas permiten representar el flujo requerido por CollabPro.<br><br>
<strong>Escenario 4: Resultado</strong><br><br>
<strong>Dado que</strong> finaliza la investigación<br><br>
<strong>Cuando</strong> el equipo consolida los resultados<br><br>
<strong>Entonces</strong> se hace un informe con el flujo probado, dependencias, restricciones y conclusiones técnicas.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>SS-02</strong></td>
<td>Developer</td>
<td>Alta</td>
<td>EP-06</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Viabilidad de OAuth para redes sociales</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero investigar y probar OAuth para la vinculación de redes
sociales, para determinar qué información de los creadores puede obtener
CollabPro de forma autorizada.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Autorización</strong><br><br>
<strong>Dado que</strong> un creador necesita vincular una red social<br><br>
<strong>Cuando</strong> el equipo ejecuta el flujo de autorización correspondiente<br><br>
<strong>Entonces</strong> documenta los permisos necesarios y el resultado de la autorización.<br><br>
<strong>Escenario 2: Información del perfil</strong><br><br>
<strong>Dado que</strong> el creador concede los permisos correspondientes<br><br>
<strong>Cuando</strong> el sistema consulta la información autorizada<br><br>
<strong>Entonces</strong> documenta qué información puede obtenerse de la cuenta.<br><br>
<strong>Escenario 3: Métricas</strong><br><br>
<strong>Dado que</strong> una cuenta dispone de datos accesibles mediante la autorización del usuario<br><br>
<strong>Cuando</strong> el equipo realiza la consulta de prueba<br><br>
<strong>Entonces</strong> documenta las métricas disponibles encontradas.<br><br>
<strong>Escenario 4: Resultado</strong><br><br>
<strong>Dado que</strong> finaliza la investigación<br><br>
<strong>Cuando</strong> el equipo consolida los resultados<br><br>
<strong>Entonces</strong> se realiza una matriz con las redes sociales analizadas, permisos requeridos, información disponible y limitaciones.
</td>
</tr>
</tbody>
</table>

<hr>

<table border="1" width="100%" cellspacing="0" cellpadding="8">
<thead>
<tr>
<th>Story ID</th>
<th>User</th>
<th>Priority</th>
<th>Epic</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>SS-03</strong></td>
<td>Developer</td>
<td>Media</td>
<td>EP-06</td>
</tr>
<tr>
<th>Title:</th>
<td colspan="3">Viabilidad de medición de resultados de campañas</td>
</tr>
<tr>
<th colspan="4">Description:</th>
</tr>
<tr>
<td colspan="4">
Como Developer, quiero investigar las alternativas para obtener y registrar
resultados de las colaboraciones, para determinar qué métricas puede ofrecer
CollabPro sin depender de información privada de las empresas.
</td>
</tr>
<tr>
<th colspan="4">Acceptance Criteria:</th>
</tr>
<tr>
<td colspan="4">
<strong>Escenario 1: Métricas de redes sociales</strong><br><br>
<strong>Dado que</strong> un creador ha proporcionado el enlace de una publicación de una colaboración en una red social compatible<br><br>
<strong>Cuando</strong> el equipo prueba la consulta de datos disponibles<br><br>
<strong>Entonces</strong> documenta qué métricas pueden obtenerse y bajo qué condiciones.<br><br>
<strong>Escenario 2: Evidencia manual</strong><br><br>
<strong>Dado que</strong> una red social no proporciona una métrica requerida<br><br>
<strong>Cuando</strong> el equipo analiza el registro de evidencias proporcionadas por el creador<br><br>
<strong>Entonces</strong> documenta qué información puede utilizarse como evidencia y cómo debe distinguirse de una métrica obtenida automáticamente.<br><br>
<strong>Escenario 3: Atribución</strong><br><br>
<strong>Dado que</strong> una campaña requiere relacionar resultados con una colaboración concreta<br><br>
<strong>Cuando</strong> el equipo prueba enlaces de atribución<br><br>
<strong>Entonces</strong> documenta qué resultados pueden asociarse de forma verificable a la colaboración.<br><br>
<strong>Escenario 4: Resultado</strong><br><br>
<strong>Dado que</strong> finaliza la investigación<br><br>
<strong>Cuando</strong> el equipo consolida los hallazgos<br><br>
<strong>Entonces</strong> existe una propuesta para medir de forma aproximada el impacto de la colaboración con sus fuentes, restricciones y supuestos.
</td>
</tr>
</tbody>
</table>

#### 2.4.2. Impact Mapping

![Impact Map](./assets/C02/Requisitos/Impact_Map.png)

#### 2.4.3. Product Backlog

|   # | User Story Id | Título                                                           | Story Points | Sprint |
| --: | ------------- | ---------------------------------------------------------------- | -----------: | :----: |
|   1 | US-01         | Presentación de CollabPro para empresas                          |            1 |   1    |
|   2 | US-02         | Presentación de CollabPro para creadores                         |            1 |   1    |
|   3 | US-03         | Información sobre el funcionamiento de CollabPro para empresas   |            2 |   1    |
|   4 | US-04         | Información sobre el funcionamiento de CollabPro para creadores  |            2 |   1    |
|   5 | US-05         | Contacto con CollabPro                                           |            2 |   1    |
|   6 | US-06         | Cambio de idioma                                                 |            1 |   1    |
|   7 | US-07         | Compatibilidad visual de la Landing Page con varios dispositivos |            2 |   1    |
|   8 | US-08         | Registro desde la Landing Page                                   |            2 |   1    |
|   9 | US-17         | Búsqueda de campañas                                             |            3 |   1    |
|  10 | US-18         | Consulta de condiciones de una campaña                           |            2 |   1    |
|  11 | US-19         | Postulación a campaña                                            |            5 |   1    |
|  12 | US-10         | Registro de creador                                              |            3 |   1    |
|  13 | US-11         | Inicio de sesión y recuperación de cuenta                        |            2 |   1    |
|  14 | US-13         | Gestión del perfil de creadores                                  |            3 |   1    |
|  15 | US-14         | Vinculación de redes sociales                                    |            5 |   1    |
|  16 | US-15         | Creación de campaña                                              |            3 |   1    |
|  17 | US-16         | Definición de condiciones de campaña                             |            2 |   1    |
|  18 | US-09         | Registro de empresa                                              |            3 |   2    |
|  19 | US-12         | Gestión del perfil empresarial                                   |            3 |   2    |
|  20 | US-20         | Evaluación de postulaciones                                      |            5 |   2    |
|  21 | US-21         | Aceptación de una colaboración                                   |            5 |   2    |
|  22 | US-22         | Consulta del estado de una colaboración                          |            3 |   2    |
|  23 | US-23         | Entrega de contenido y evidencias                                |            3 |   2    |
|  24 | US-24         | Validación de entregables                                        |            5 |   3    |
|  25 | US-25         | Gestión de incidencias                                           |            5 |   3    |
|  26 | US-26         | Vinculación de medio de pago                                     |            3 |   3    |
|  27 | US-27         | Suscripción de la empresa                                        |            5 |   3    |
|  28 | US-28         | Consulta del estado de la compensación                           |            3 |   3    |
|  29 | US-29         | Consulta y atribución de resultados de campaña                   |            3 |   3    |
|  30 | US-30         | Historial de colaboraciones                                      |            3 |   3    |
|  31 | SS-02         | Viabilidad de OAuth para redes sociales                          |            3 |   1    |
|  32 | TS-01         | Servicios de autenticación de cuentas                            |            3 |   1    |
|  33 | TS-03         | Servicios de campañas y postulaciones                            |            5 |   1    |
|  34 | TS-02         | Servicios de perfiles y redes sociales                           |            3 |   2    |
|  35 | TS-04         | Servicios de colaboraciones y entregables                        |            5 |   2    |
|  36 | TS-05         | Servicios de validación, incidencias y compensaciones            |            5 |   2    |
|  37 | SS-01         | Viabilidad de Stripe en Sandbox                                  |            3 |   3    |
|  38 | TS-06         | Servicios de suscripciones y pagos                               |            5 |   3    |
|  39 | SS-03         | Viabilidad de medición de resultados de campañas                 |            3 |   3    |
|  40 | TS-07         | Servicios de métricas, evidencias y atribución                   |            5 |   3    |

<br>
Trello: https://trello.com/b/X1Cgxi0s/collabpro
<br>

### 2.5. Strategic-Level Domain-Driven Design

En esta sección se presenta el proceso de diseño estratégico aplicado al dominio de CollabPro mediante Domain-Driven Design. El objetivo es identificar límites claros entre las principales capacidades del negocio y establecer las relaciones necesarias entre ellas antes de desarrollar su diseño interno a nivel táctico.

Como punto de partida se utilizaron los hallazgos obtenidos durante el proceso de Needfinding, el Ubiquitous Language, las User Stories, las Technical Stories y el Big Picture EventStorming previamente elaborado. A partir de estos artefactos se profundizó en los eventos, comandos, actores y reglas que intervienen durante el ciclo completo de una colaboración entre una empresa y un creador de contenido.

El análisis permitió identificar cinco Bounded Contexts: **Identity & Profile Management**, **Campaign Management**, **Collaboration Management**, **Billing & Compensation Management** y **Performance & Attribution Management**. Cada contexto agrupa capacidades que comparten un mismo modelo y lenguaje, pero que evolucionan por motivos diferentes respecto de los demás contextos.

La delimitación busca evitar que conceptos con ciclos de vida diferentes, como Campaign, Collaboration, Compensation o Performance, formen parte de un único modelo altamente acoplado. Asimismo, permite aislar las integraciones con servicios externos de pagos y redes sociales de las principales reglas de negocio de CollabPro.

#### 2.5.1. EventStorming

El equipo utilizó EventStorming para profundizar en el comportamiento del dominio de CollabPro. Mientras que el Big Picture EventStorming presentado anteriormente permitió representar de manera general el recorrido completo de una colaboración, en esta etapa se analizaron con mayor detalle los eventos de negocio, comandos, actores, reglas y puntos de decisión que permiten identificar límites naturales dentro del dominio.

La sesión tomó como flujo principal el proceso que comienza cuando una empresa prepara una campaña, continúa con la postulación y selección de un creador, deriva en la ejecución de una colaboración y finaliza con la compensación y evaluación de sus resultados.

También se consideraron flujos alternativos como el rechazo o cancelación de una postulación, cierre de una campaña, entrega fuera de plazo, rechazo de un entregable, presentación de una nueva versión, apertura de una incidencia, fallo de una operación de pago y ausencia de métricas disponibles desde una red social.

Durante el EventStorming se identificaron los siguientes elementos principales:

| Command / Action           | Actor            | Domain Event                                | Regla o consideración principal                                                                              |
| -------------------------- | ---------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Register account           | Brand / Creator  | Account Registered                          | El correo utilizado no debe estar asociado previamente a otra cuenta.                                        |
| Complete profile           | Brand / Creator  | Profile Completed                           | El perfil debe corresponder al tipo de cuenta registrado.                                                    |
| Link social account        | Creator          | Social Media Account Linked                 | La asociación requiere autorización del propietario de la cuenta externa.                                    |
| Create campaign            | Brand            | Campaign Created                            | Solo una cuenta empresarial habilitada puede crear campañas.                                                 |
| Define campaign conditions | Brand            | Campaign Conditions Defined                 | La campaña debe especificar requisitos, entregables, fechas y compensación.                                  |
| Publish campaign           | Brand            | Campaign Published                          | Una campaña incompleta no puede abrirse a postulaciones.                                                     |
| Submit application         | Creator          | Application Submitted                       | El creador debe cumplir las condiciones obligatorias y no debe existir una postulación duplicada.            |
| Select application         | Brand            | Application Selected                        | La postulación debe encontrarse pendiente y pertenecer a la campaña correspondiente.                         |
| Accept collaboration terms | Brand / Creator  | Collaboration Terms Accepted                | Ambas partes deben aceptar las condiciones antes de iniciar la colaboración.                                 |
| Start collaboration        | System           | Collaboration Created                       | Las condiciones aceptadas deben conservarse durante la colaboración.                                         |
| Submit deliverable         | Creator          | Deliverable Submitted                       | La entrega debe estar asociada a una colaboración vigente.                                                   |
| Review deliverable         | Brand            | Deliverable Approved / Deliverable Rejected | La revisión debe considerar las condiciones aceptadas para el entregable.                                    |
| Open incident              | Brand / Creator  | Incident Opened                             | La incidencia debe estar vinculada a una colaboración identificable.                                         |
| Complete collaboration     | System           | Collaboration Completed                     | Los entregables obligatorios deben encontrarse en un estado compatible con el cierre.                        |
| Authorize compensation     | System           | Compensation Authorized                     | La compensación monetaria no debe liberarse antes de satisfacer las condiciones correspondientes.            |
| Process payment            | Payment Provider | Compensation Paid / Payment Failed          | Los eventos externos deben procesarse sin duplicar operaciones.                                              |
| Collect metrics            | System           | Metrics Collected                           | Solo se consideran métricas obtenidas mediante fuentes autorizadas o evidencias identificadas como manuales. |
| Update performance         | System           | Performance Report Updated                  | Cada resultado debe conservar información sobre su fuente y periodo.                                         |

Durante la sesión se identificaron además diversos hotspots que requieren especial atención durante el diseño y la implementación:

- Modificación de las condiciones de una campaña después de recibir postulaciones.
- Postulaciones duplicadas.
- Campañas que alcanzan su fecha límite mientras existen postulaciones pendientes.
- Entregables presentados fuera de plazo.
- Corrección de entregables rechazados.
- Incidencias que afectan el cierre de una colaboración.
- Compensaciones bloqueadas debido a una incidencia.
- Fallos o eventos duplicados enviados por el proveedor de pagos.
- Limitaciones de las APIs de redes sociales para obtener determinadas métricas.
- Diferencias entre métricas obtenidas automáticamente y evidencias proporcionadas manualmente.

**Strategic EventStorming - Domain Events**

![Strategic EventStorming - Domain Events](./assets/C02/DDD/EventStorming/strategic-eventstorm-1-domain-events.jpg)

_Nota. Elaboración propia._

**Strategic EventStorming - Commands, Actors, Rules and Hotspots**

![Strategic EventStorming - Commands, Actors, Rules and Hotspots](./assets/C02/DDD/EventStorming/strategic-eventstorm-2-enriched.jpg)

_Nota. Elaboración propia._

##### 2.5.1.1. Candidate Context Discovery

A partir del EventStorming se realizó Candidate Context Discovery con el objetivo de identificar grupos de comportamientos y conceptos que presentan alta cohesión interna y que cambian por razones diferentes respecto de otras partes del dominio.

Para la sesión de Candidate Context Discovery se utilizó principalmente la técnica start-with-simple, descomponiendo el timeline del EventStorm en grupos secuenciales de actividades relacionadas y analizando la cohesión existente entre sus eventos, reglas y responsabilidades de negocio.

A partir de esta agrupación se identificaron cambios claros de responsabilidad dentro del proceso. Las actividades relacionadas con identidad y perfiles presentan un ciclo de vida independiente de las campañas; las campañas y postulaciones corresponden a la etapa previa a la formalización de una colaboración; la colaboración concentra el cumplimiento del acuerdo, los entregables y las incidencias; las operaciones de compensación poseen reglas financieras propias; y la medición de resultados depende de procesos y fuentes diferentes a los utilizados durante la ejecución de la colaboración.

Como resultado se identificaron los siguientes Bounded Contexts candidatos:

| Bounded Context                          | Clasificación propuesta | Responsabilidad                                                                      | Principales capabilities                                                                                                        |
| ---------------------------------------- | ----------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------- |
| **Identity & Profile Management**        | Generic Domain          | Administrar las identidades y perfiles que participan en CollabPro.                  | Registro, autenticación, recuperación de acceso, perfiles empresariales, perfiles de creadores y vinculación de redes sociales. |
| **Campaign Management**                  | Core Domain             | Administrar las oportunidades de colaboración antes de que exista un acuerdo formal. | Creación de campañas, condiciones, publicación, búsqueda, postulaciones y evaluación de postulantes.                            |
| **Collaboration Management**             | Core Domain             | Administrar el cumplimiento de un acuerdo entre una empresa y un creador.            | Formalización de colaboración, estado, entregables, evidencias, revisiones, incidencias e historial.                            |
| **Billing & Compensation Management**    | Supporting Domain       | Administrar las operaciones económicas relacionadas con CollabPro.                   | Medios de pago, suscripciones, compensaciones, transacciones y eventos de proveedores financieros.                              |
| **Performance & Attribution Management** | Supporting Domain       | Administrar la medición de resultados generados por una colaboración.                | Métricas, evidencias, enlaces de atribución, interacciones y reportes de desempeño.                                             |

**Candidate Context Discovery de CollabPro**

![Candidate Context Discovery](./assets/C02/DDD/EventStorming/strategic-eventstorm-3-context-discovery.jpg)

_Nota. Elaboración propia._

##### 2.5.1.2. Domain Message Flows Modeling

Para analizar la comunicación entre los Bounded Contexts de CollabPro se utilizó Domain Message Flow Modeling. Los diagramas representan los mensajes que permiten coordinar las capacidades distribuidas entre los distintos contextos del dominio.

Cada interacción se expresa mediante uno de los tipos de mensaje utilizados en el modelado: **Command**, cuando se solicita ejecutar una acción; **Event**, cuando se comunica un hecho que ya ocurrió dentro del dominio; y **Query**, cuando un contexto necesita consultar información sin modificar el estado del sistema.

Se consideraron tres flujos principales debido a que representan las interacciones que atraviesan la mayor cantidad de capacidades y Bounded Contexts de CollabPro.

**Message Flow 1: Creación de campaña y formación de una colaboración**

Una empresa autenticada completa su perfil y crea una campaña. La empresa define los requisitos, entregables, plazos y condiciones de compensación y posteriormente publica la campaña.

Un creador consulta las oportunidades disponibles, revisa una campaña y registra su postulación. La empresa revisa las postulaciones y selecciona a un creador. Después de que ambas partes aceptan las condiciones, se crea una colaboración manteniendo una copia de las condiciones aceptadas.

Este flujo representa la colaboración principal entre **Identity & Profile Management**, **Campaign Management** y **Collaboration Management**.

![storytelling diagram 1](assets/C02/DDD/storytelling-diagram-1.jpg)

**Message Flow 2: Cumplimiento de colaboración y compensación**

El creador consulta una colaboración activa, desarrolla el contenido solicitado y registra el entregable junto con la evidencia correspondiente.

La empresa revisa el entregable. Si existe un incumplimiento, registra las observaciones y el creador puede presentar una nueva versión cuando las condiciones de la colaboración lo permitan.

Cuando todos los entregables obligatorios son aprobados y no existe una condición que impida continuar, la colaboración alcanza el estado correspondiente para su finalización. Collaboration Management informa a Billing & Compensation Management que la compensación puede ser autorizada.

Cuando la compensación es monetaria, el proveedor financiero procesa la operación y posteriormente comunica el resultado al backend de CollabPro.

Este flujo representa la colaboración entre **Collaboration Management** y **Billing & Compensation Management**.

![storytelling diagram 2](assets/C02/DDD/storytelling-diagram-2.jpg)

**Message Flow 3: Obtención y análisis de resultados**

Cuando una colaboración produce contenido publicado, Performance & Attribution Management puede consultar las métricas disponibles mediante una cuenta social previamente autorizada.

Las métricas obtenidas se almacenan junto con su fuente y periodo correspondiente. Cuando una métrica no puede obtenerse automáticamente, puede registrarse una evidencia adicional manteniendo explícita la diferencia entre un dato automatizado y una evidencia proporcionada por el creador.

Cuando se utiliza un mecanismo de atribución, CollabPro puede registrar interacciones relacionadas con un enlace o identificador asociado a la colaboración.

Finalmente, la empresa consulta el reporte de desempeño con la información disponible.

Este flujo representa la colaboración entre **Identity & Profile Management**, **Collaboration Management** y **Performance & Attribution Management**, además de los proveedores externos de redes sociales.

![storytelling diagram 3](assets/C02/DDD/storytelling-diagram-3.jpg)

##### 2.5.1.3. Bounded Context Canvases

A partir de los contextos candidatos se elaboraron Bounded Context Canvases con el objetivo de precisar el propósito, reglas, lenguaje, capabilities y dependencias de cada contexto.

La elaboración se realizó de forma iterativa considerando Context Overview Definition, Business Rules Distillation & Ubiquitous Language Capture, Capability Analysis, Dependencies Capture y Design Critique.

**Identity & Profile Management**

| Aspecto                   | Definición                                                                                                                                                                                      |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Proporcionar una identidad verificable dentro de CollabPro y mantener la información necesaria de empresas y creadores.                                                                         |
| **Domain Role**           | Generic Domain.                                                                                                                                                                                 |
| **Ubiquitous Language**   | Account, Brand Profile, Creator Profile, Social Media Account.                                                                                                                                  |
| **Capabilities**          | Registrar cuenta, autenticar cuenta, recuperar acceso, actualizar perfiles, vincular y desvincular redes sociales.                                                                              |
| **Business Rules**        | El correo de una cuenta debe ser único. Una cuenta mantiene un tipo definido. Una cuenta social no debe duplicarse dentro de un mismo perfil. Las asociaciones externas requieren autorización. |
| **Inbound Dependencies**  | Proveedores externos utilizados en los procesos de autorización social.                                                                                                                         |
| **Outbound Dependencies** | Proporciona identificadores y datos de referencia de empresas y creadores a otros contextos.                                                                                                    |
| **Design Critique**       | Los detalles particulares de OAuth o de proveedores externos no forman parte del modelo de dominio.                                                                                             |

**Campaign Management**

| Aspecto                   | Definición                                                                                                                                                                                                                 |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Administrar las oportunidades comerciales disponibles antes de que exista una colaboración.                                                                                                                                |
| **Domain Role**           | Core Domain.                                                                                                                                                                                                               |
| **Ubiquitous Language**   | Campaign, Requirement, Deliverable Specification, Compensation Terms, Application.                                                                                                                                         |
| **Capabilities**          | Crear campaña, definir condiciones, publicar campaña, buscar campañas, postular, modificar o cancelar una postulación y evaluar postulantes.                                                                               |
| **Business Rules**        | Una campaña incompleta no puede publicarse. Solo se puede postular a campañas abiertas. Un creador no debe registrar una postulación duplicada. Las postulaciones solo pueden modificarse mientras permanezcan pendientes. |
| **Inbound Dependencies**  | Identity & Profile Management proporciona referencias de Brand y Creator.                                                                                                                                                  |
| **Outbound Dependencies** | Una postulación seleccionada y las condiciones aceptadas permiten iniciar el proceso correspondiente en Collaboration Management.                                                                                          |
| **Design Critique**       | Campaign no debe controlar entregables reales ni estados de ejecución de una colaboración.                                                                                                                                 |

**Collaboration Management**

| Aspecto                   | Definición                                                                                                                                                                                                                                  |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Gestionar el acuerdo y cumplimiento de una relación comercial entre una empresa y un creador.                                                                                                                                               |
| **Domain Role**           | Core Domain.                                                                                                                                                                                                                                |
| **Ubiquitous Language**   | Collaboration, Agreement, Deliverable, Evidence, Approval, Incident.                                                                                                                                                                        |
| **Capabilities**          | Crear colaboración, consultar estado, registrar entregables, registrar evidencias, revisar entregables, administrar correcciones, abrir incidencias y completar una colaboración.                                                           |
| **Business Rules**        | Una colaboración requiere condiciones aceptadas por ambas partes. Las condiciones acordadas no deben modificarse como consecuencia de cambios posteriores en la campaña. Un entregable debe validarse utilizando las condiciones aceptadas. |
| **Inbound Dependencies**  | Campaign Management proporciona la postulación seleccionada y las condiciones aceptadas.                                                                                                                                                    |
| **Outbound Dependencies** | Informa a Billing & Compensation Management cuando la compensación puede continuar y proporciona información a Performance & Attribution Management sobre contenido y colaboraciones.                                                       |
| **Design Critique**       | El procesamiento financiero y la consulta de APIs sociales permanecen fuera de este contexto.                                                                                                                                               |

**Billing & Compensation Management**

| Aspecto                   | Definición                                                                                                                                                                                                                     |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Purpose**               | Administrar las operaciones económicas relacionadas con el uso de CollabPro y las compensaciones de las colaboraciones.                                                                                                        |
| **Domain Role**           | Supporting Domain.                                                                                                                                                                                                             |
| **Ubiquitous Language**   | Subscription, Payment Method, Compensation, Transaction.                                                                                                                                                                       |
| **Capabilities**          | Asociar medio de pago, crear suscripción, consultar suscripción, registrar compensación, autorizar compensación, procesar pago y gestionar eventos financieros.                                                                |
| **Business Rules**        | Subscription y Compensation representan obligaciones económicas diferentes. Una compensación monetaria no debe procesarse antes de ser autorizada. Los eventos provenientes del proveedor deben tratarse de forma idempotente. |
| **Inbound Dependencies**  | Identity & Profile Management proporciona referencias de usuario. Collaboration Management informa cuándo una compensación puede ser autorizada.                                                                               |
| **Outbound Dependencies** | Proporciona el estado de las operaciones económicas relacionadas con la colaboración.                                                                                                                                          |
| **Design Critique**       | El modelo de dominio no debe depender directamente de Stripe u otro proveedor concreto.                                                                                                                                        |

**Performance & Attribution Management**

| Aspecto                   | Definición                                                                                                                                                                                                     |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Mantener información verificable sobre el desempeño generado por las colaboraciones.                                                                                                                           |
| **Domain Role**           | Supporting Domain.                                                                                                                                                                                             |
| **Ubiquitous Language**   | Performance, Reach, Impressions, Engagement, Conversion, Attribution, Metric Source.                                                                                                                           |
| **Capabilities**          | Consultar métricas, registrar snapshots, registrar evidencias, crear mecanismos de atribución y generar reportes de desempeño.                                                                                 |
| **Business Rules**        | Toda métrica debe mantener su fuente y periodo. Los datos automáticos deben diferenciarse de las evidencias manuales. Los resultados atribuibles no deben presentarse como equivalentes a causalidad absoluta. |
| **Inbound Dependencies**  | Collaboration Management proporciona la referencia de la colaboración y el contenido relacionado. Identity & Profile Management proporciona la asociación social autorizada.                                   |
| **Outbound Dependencies** | Proporciona resultados y reportes para consulta de las empresas.                                                                                                                                               |
| **Design Critique**       | Las particularidades de Instagram, TikTok, YouTube u otros servicios externos deben permanecer fuera del modelo de dominio.                                                                                    |

![Bounded Context Canvas de Identity & Profile Management](assets/C02/DDD/bcc-identity-profile-management.jpg)

![Bounded Context Canvas de Campaign Management](assets/C02/DDD/bcc-campaign-management.jpg)

![Bounded Context Canvas de Collaboration Management](assets/C02/DDD/bcc-collaboration-management.jpg)

![Bounded Context Canvas de Billing & Compensation Management](assets/C02/DDD/bcc-billing-compensation-management.jpg)

![Bounded Context Canvas de Performance & Attribution Management](assets/C02/DDD/bcc-performance-attribution-management.jpg)

#### 2.5.2. Context Mapping

Una vez identificados y detallados los Bounded Contexts, el equipo analizó sus dependencias para establecer un Context Map que reduzca el acoplamiento entre modelos y permita mantener responsabilidades claramente delimitadas.

Durante el análisis se consideró inicialmente agrupar Campaign Management y Collaboration Management dentro de un único contexto de marketplace. Esta alternativa fue descartada debido a que una campaña representa una oportunidad disponible para múltiples creadores, mientras que una colaboración representa una relación concreta con condiciones previamente aceptadas y un ciclo de cumplimiento independiente.

También se evaluó mantener Billing & Compensation Management dentro de Collaboration Management. La alternativa fue descartada debido a que los procesos financieros poseen reglas y estados diferentes, además de depender de un proveedor externo que puede cambiar sin modificar las reglas de cumplimiento de la colaboración.

De forma similar, se consideró incorporar Performance & Attribution Management dentro de Collaboration Management. La alternativa fue descartada porque la disponibilidad y actualización de métricas depende de APIs externas y mecanismos de atribución que evolucionan independientemente del ciclo de ejecución de una colaboración.

Finalmente se descartó utilizar Shared Kernel para compartir los modelos internos entre Bounded Contexts. Cada contexto mantiene su propio modelo y únicamente comparte identificadores y contratos de integración cuando resulta necesario.

Las relaciones resultantes y la justificación de los patrones seleccionados se resumen a continuación:

| Upstream | Downstream | Relación | Información intercambiada | Justificación |
| --- | --- | --- | --- | --- |
| Identity & Profile Management | Campaign Management | Customer / Supplier | Identidad y referencia de Brand y Creator. | Identity & Profile Management actúa como upstream al proporcionar las referencias de identidad requeridas por Campaign Management. Se selecciona Customer / Supplier porque Campaign Management depende de este contrato para asociar campañas y postulaciones con usuarios válidos, por lo que sus necesidades deben ser consideradas al definir la información suministrada. |
| Identity & Profile Management | Billing & Compensation Management | Customer / Supplier | Referencia de la cuenta asociada a medios de pago o suscripción. | Billing & Compensation Management necesita identificar al usuario asociado a una suscripción, medio de pago o compensación. Identity & Profile Management proporciona esta referencia sin compartir su modelo interno, manteniendo una relación clara entre proveedor y consumidor. |
| Identity & Profile Management | Performance & Attribution Management | Customer / Supplier | Referencia de las cuentas sociales autorizadas. | Performance & Attribution Management requiere conocer qué cuentas sociales han sido autorizadas para asociar o consultar métricas. Identity & Profile Management mantiene dichas asociaciones y proporciona únicamente la información necesaria mediante un contrato explícito. |
| Campaign Management | Collaboration Management | Customer / Supplier | Postulación seleccionada y snapshot de las condiciones aceptadas. | Campaign Management administra la campaña y las postulaciones hasta seleccionar un creador. Collaboration Management utiliza esa información para iniciar una colaboración y conservar las condiciones aceptadas, por lo que depende del contrato proporcionado por Campaign Management. |
| Collaboration Management | Billing & Compensation Management | Customer / Supplier | Autorización o elegibilidad de la compensación. | Collaboration Management determina cuándo se cumplen las condiciones necesarias para continuar con una compensación. Billing & Compensation Management utiliza esa decisión para ejecutar el proceso económico sin incorporar dentro de su modelo las reglas propias del cumplimiento de una colaboración. |
| Collaboration Management | Performance & Attribution Management | Customer / Supplier | Referencia de la colaboración y contenido utilizado para medir resultados. | Performance & Attribution Management necesita identificar qué colaboración y contenido deben analizarse. Collaboration Management proporciona esas referencias mediante un contrato explícito, permitiendo que los procesos de medición evolucionen independientemente del ciclo de cumplimiento de la colaboración. |

Las relaciones internas fueron modeladas mediante el patrón **Customer / Supplier** debido a que presentan una dirección clara de dependencia entre un Bounded Context upstream, responsable de proporcionar información o capacidades, y un Bounded Context downstream, que utiliza dicho contrato para cumplir sus propias responsabilidades. El downstream puede establecer necesidades sobre la información requerida, pero no accede directamente al modelo interno del upstream.

Para evitar un acoplamiento innecesario, la comunicación entre Bounded Contexts se realiza mediante contratos explícitos que contienen únicamente los datos requeridos para cada interacción. De esta manera, cada contexto puede evolucionar internamente sin obligar a los demás contextos a adoptar sus entidades, reglas o estructuras internas.

En las integraciones con proveedores externos de pagos y redes sociales se utiliza el patrón **Anti-Corruption Layer (ACL)**. Este patrón permite proteger el modelo de dominio de CollabPro frente a conceptos, estructuras y cambios definidos por sistemas externos. Los adapters traducen la información proveniente de estos proveedores hacia los conceptos pertenecientes al Ubiquitous Language de cada Bounded Context.

El Context Map final mantiene a Campaign Management y Collaboration Management como los principales contextos del dominio. Identity & Profile Management proporciona las referencias de identidad necesarias para las operaciones de los demás contextos; Billing & Compensation Management mantiene aisladas las reglas económicas; y Performance & Attribution Management concentra las responsabilidades relacionadas con la medición y atribución de resultados.

**DDD Context Map**

![CollabPro – DDD Context Map](./assets/C02/DDD/ContextMapping/context-map.jpg)

_Nota. Elaboración propia._

#### 2.5.3. Software Architecture

La arquitectura de software de CollabPro se representa utilizando C4 Model con el objetivo de visualizar la solución desde diferentes niveles de abstracción. El Context Level Diagram presenta a CollabPro como un único sistema y sus relaciones con usuarios y sistemas externos. El Container Level Diagram muestra los principales productos y unidades ejecutables de la solución. Finalmente, el Deployment Diagram representa la distribución de dichos elementos entre dispositivos, servicios de infraestructura y sistemas externos.

##### 2.5.3.1. Software Architecture Context Level Diagrams

El System Context Diagram presenta a CollabPro como el sistema central dentro del ecosistema.

Los principales usuarios son el **Brand Representative**, quien utiliza CollabPro para crear y administrar campañas, seleccionar creadores, validar entregables y consultar resultados; y el **Content Creator**, quien utiliza la solución para descubrir oportunidades, postular a campañas, administrar colaboraciones, presentar entregables y consultar compensaciones.

CollabPro interactúa con un **Payment Service Provider** para las operaciones relacionadas con suscripciones y compensaciones monetarias. Asimismo, interactúa con **Social Media Platforms** para autorizar cuentas y obtener información disponible de perfiles, publicaciones o métricas cuando los permisos concedidos lo permitan.

Estas integraciones se realizan mediante el backend de CollabPro, evitando que los clientes móviles dependan directamente de las reglas o credenciales privadas utilizadas por dichos servicios.

**Software Architecture System Context Diagram**

![Software Architecture System Context Diagram](./assets/C02/DDD/C4/system-context.png)

_Nota. Elaboración propia._

##### 2.5.3.2. Software Architecture Container Level Diagrams

El Container Diagram representa los productos principales que conforman CollabPro.

La solución incluye un Landing Page, una aplicación móvil nativa para Android, una aplicación móvil multiplataforma, los RESTful Web Services, el sistema de persistencia y las integraciones externas.

| Container                             | Tecnología               | Responsabilidad                                                                                                              |
| ------------------------------------- | ------------------------ | ---------------------------------------------------------------------------------------------------------------------------- |
| **Landing Page**                      | HTML5, CSS3 y JavaScript | Presentar la propuesta de valor, información del producto, idiomas disponibles y mecanismos iniciales de acceso a CollabPro. |
| **Native Android Application**        | Kotlin                   | Proporcionar la experiencia móvil nativa para empresas y creadores.                                                          |
| **Cross-Platform Mobile Application** | Flutter                  | Proporcionar la experiencia móvil multiplataforma requerida por la solución.                                                 |
| **RESTful Web Services**              | Spring Boot Java         | Exponer los casos de uso de CollabPro y coordinar los cinco Bounded Contexts.                                                |
| **Relational Database**               | MySQL                    | Persistir los datos administrados por los Bounded Contexts.                                                                  |
| **Evidence/Object Storage**           | Firebase Cloud Storage   | Almacenar archivos o evidencias que no deban persistirse directamente dentro de la base de datos relacional.                 |

Se propone implementar inicialmente los RESTful Web Services mediante una arquitectura modular, manteniendo cada Bounded Context como un módulo independiente dentro del backend. Esta decisión permite conservar los límites definidos por Domain-Driven Design sin introducir prematuramente la complejidad operacional de una arquitectura distribuida.

La aplicación nativa y la aplicación multiplataforma consumen los RESTful Web Services mediante HTTPS. La persistencia es accedida exclusivamente por el backend. Las integraciones con el proveedor de pagos y las plataformas sociales también se realizan desde los componentes correspondientes de Infrastructure Layer.

Las aplicaciones móviles incorporarán además almacenamiento local para aquellos datos que requieran disponibilidad dentro del dispositivo, en cumplimiento de los requisitos tecnológicos establecidos para la solución.

**Software Architecture Container Diagram**

![Software Architecture Container Diagram](./assets/C02/DDD/C4/container-diagram.png)

_Nota. Elaboración propia._

##### 2.5.3.3. Software Architecture Deployment Diagrams

El Deployment Diagram representa la distribución física de CollabPro entre los dispositivos de los usuarios y la infraestructura utilizada para publicar sus productos digitales.

El Landing Page se despliega mediante un servicio de hosting web estático. Los RESTful Web Services se ejecutan en una infraestructura cloud accesible públicamente mediante HTTPS y se conectan con una base de datos administrada y, cuando corresponda, con un servicio de almacenamiento de objetos para las evidencias.

La aplicación nativa Android se instala sobre dispositivos Android, mientras que la aplicación multiplataforma se distribuye en los dispositivos compatibles con la estrategia seleccionada por el equipo. Cada aplicación puede utilizar almacenamiento local dentro del dispositivo y se comunica con el backend publicado mediante conexiones HTTPS.

El backend mantiene las conexiones necesarias con los servicios externos utilizados por CollabPro, incluyendo el proveedor de pagos y las APIs autorizadas de redes sociales.

Durante AV1 este diagrama representa la arquitectura de despliegue propuesta. Los nombres concretos de los proveedores cloud, recursos y configuraciones deberán actualizarse posteriormente cuando la infraestructura definitiva sea aprovisionada y desplegada.

**Software Architecture Deployment Diagram**

![Software Architecture Deployment Diagram](./assets/C02/DDD/C4/deployment-diagram.png)

_Nota. Elaboración propia._

### 2.6. Tactical-Level Domain-Driven Design

En esta sección se presenta la perspectiva táctica de Domain-Driven Design aplicada a CollabPro. A partir de los requisitos funcionales, Technical Stories, Spike Stories, Ubiquitous Language y eventos de negocio identificados previamente, la solución se organiza internamente en cinco Bounded Contexts: Identity & Profile Management, Campaign Management, Collaboration Management, Billing & Compensation Management y Performance & Attribution Management.

Cada Bounded Context mantiene su propio modelo de dominio, reglas de negocio y responsabilidades, reduciendo el acoplamiento entre capacidades que evolucionan por razones diferentes. Para su diseño interno se consideran las capas Domain, Application, Interface e Infrastructure. La Domain Layer concentra las reglas y conceptos propios del negocio; la Application Layer coordina los casos de uso; la Interface Layer expone las capacidades del contexto a las aplicaciones cliente y otros sistemas; y la Infrastructure Layer implementa la persistencia e integración con servicios externos.

Esta separación permite que conceptos como Campaign, Collaboration, Compensation y Performance mantengan significados y ciclos de vida independientes dentro de sus respectivos límites, siguiendo los principios de Domain-Driven Design (Evans, 2003).

#### 2.6.1. Bounded Context: Identity & Profile Management

El Bounded Context Identity & Profile Management concentra las capacidades relacionadas con la creación y acceso a las cuentas de CollabPro, así como la administración de los perfiles que representan a empresas y creadores de contenido. También controla la asociación autorizada entre un perfil de creador y sus cuentas de redes sociales.

Este contexto permite mantener separadas las responsabilidades de identidad y perfil de las reglas relacionadas con campañas, colaboraciones, compensaciones y medición de resultados.

##### 2.6.1.1. Domain Layer

La Domain Layer contiene los conceptos necesarios para representar una cuenta y su información asociada. `Account` funciona como Aggregate Root y mantiene la identidad y estado de la cuenta. Dependiendo del tipo de usuario, la cuenta mantiene un `BrandProfile` o un `CreatorProfile`. En el caso de los creadores, el perfil puede contener una o más asociaciones `SocialMediaAccount`.

| Clase                | Tipo                    | Propósito                                                                       | Principales atributos                                                          | Principales métodos                                                             |
| -------------------- | ----------------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------- |
| `Account`            | Aggregate Root / Entity | Representar la cuenta registrada en CollabPro y controlar su estado y tipo.     | `accountId`, `email`, `passwordHash`, `accountType`, `status`, `createdAt`     | `activate()`, `changePassword()`, `deactivate()`                                |
| `BrandProfile`       | Entity                  | Mantener la información comercial de una pyme que participa en CollabPro.       | `brandProfileId`, `businessName`, `description`, `category`, `location`        | `updateInformation()`                                                           |
| `CreatorProfile`     | Entity                  | Mantener la información profesional de un creador de contenido.                 | `creatorProfileId`, `displayName`, `biography`, `niche`, `audienceDescription` | `updateInformation()`, `linkSocialMediaAccount()`, `unlinkSocialMediaAccount()` |
| `SocialMediaAccount` | Entity                  | Representar una red social vinculada y autorizada por el creador.               | `socialMediaAccountId`, `platform`, `externalAccountId`, `username`, `status`  | `activate()`, `revoke()`                                                        |
| `EmailAddress`       | Value Object            | Representar y validar una dirección de correo utilizada por una cuenta.         | `value`                                                                        | `isValid()`                                                                     |
| `AccountType`        | Enumeration             | Identificar el tipo de cuenta dentro de CollabPro.                              | `BRAND`, `CREATOR`                                                             | N/A                                                                             |
| `AccountStatus`      | Enumeration             | Representar el estado operativo de la cuenta.                                   | `PENDING`, `ACTIVE`, `SUSPENDED`, `DISABLED`                                   | N/A                                                                             |
| `AccountRepository`  | Repository Interface    | Definir las operaciones de persistencia necesarias para el Aggregate `Account`. | N/A                                                                            | `save()`, `findById()`, `findByEmail()`, `existsByEmail()`                      |

La relación principal del Aggregate establece que una `Account` pertenece a un único tipo de usuario. Una cuenta empresarial mantiene un `BrandProfile`, mientras que una cuenta de creador mantiene un `CreatorProfile`. Un `CreatorProfile` puede asociar cero o varias instancias de `SocialMediaAccount`.

##### 2.6.1.2. Interface Layer

La Interface Layer expone las capacidades relacionadas con autenticación, perfiles y asociación de redes sociales mediante servicios REST.

| Clase                   | Propósito                                                                    | Principales operaciones                                                         |
| ----------------------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| `AuthController`        | Recibir las solicitudes de registro, autenticación y recuperación de cuenta. | `registerBrand()`, `registerCreator()`, `login()`, `recoverAccount()`           |
| `UserProfileController` | Exponer las operaciones de consulta y actualización de perfiles.             | `getProfile()`, `updateBrandProfile()`, `updateCreatorProfile()`                |
| `SocialMediaController` | Gestionar las solicitudes relacionadas con cuentas sociales asociadas.       | `linkSocialMediaAccount()`, `getLinkedAccounts()`, `unlinkSocialMediaAccount()` |

Los Controllers no implementan reglas de negocio directamente. Su responsabilidad consiste en recibir la solicitud, validar su estructura básica, invocar el caso de uso correspondiente en Application Layer y devolver la respuesta adecuada.

##### 2.6.1.3. Application Layer

La Application Layer coordina los casos de uso relacionados con cuentas y perfiles.

| Clase                                  | Tipo            | Responsabilidad                                             |
| -------------------------------------- | --------------- | ----------------------------------------------------------- |
| `RegisterBrandCommandHandler`          | Command Handler | Crear una cuenta empresarial y su perfil inicial.           |
| `RegisterCreatorCommandHandler`        | Command Handler | Crear una cuenta de creador y su perfil inicial.            |
| `AuthenticateAccountCommandHandler`    | Command Handler | Validar las credenciales y gestionar el acceso a CollabPro. |
| `RecoverAccountCommandHandler`         | Command Handler | Coordinar el proceso de recuperación de acceso.             |
| `UpdateBrandProfileCommandHandler`     | Command Handler | Actualizar los datos permitidos de una empresa.             |
| `UpdateCreatorProfileCommandHandler`   | Command Handler | Actualizar los datos permitidos de un creador.              |
| `LinkSocialMediaAccountCommandHandler` | Command Handler | Coordinar la asociación autorizada de una cuenta social.    |
| `GetUserProfileQueryHandler`           | Query Handler   | Recuperar la información del perfil correspondiente.        |
| `GetLinkedSocialMediaQueryHandler`     | Query Handler   | Consultar las redes sociales vinculadas por el creador.     |

Los handlers utilizan las abstracciones definidas por el dominio y coordinan servicios externos cuando el caso de uso lo requiere. De esta forma, la lógica de autenticación externa o autorización mediante OAuth no se incorpora directamente al modelo de dominio.

##### 2.6.1.4. Infrastructure Layer

La Infrastructure Layer implementa los mecanismos técnicos necesarios para persistir cuentas, gestionar credenciales e interactuar con proveedores externos.

| Clase                       | Propósito                                                                                                    |
| --------------------------- | ------------------------------------------------------------------------------------------------------------ |
| `AccountPersistenceAdapter` | Implementar `AccountRepository` utilizando el mecanismo de persistencia seleccionado para el backend.        |
| `PasswordHashingService`    | Generar y verificar representaciones seguras de las contraseñas.                                             |
| `AccessTokenProvider`       | Generar y validar las credenciales utilizadas por los servicios protegidos.                                  |
| `SocialOAuthClient`         | Encapsular la comunicación con los proveedores externos utilizados para autorizar cuentas de redes sociales. |
| `AccountRecoveryService`    | Gestionar el envío del mecanismo necesario para recuperar el acceso a una cuenta.                            |

La integración concreta con proveedores de redes sociales permanece encapsulada en `SocialOAuthClient`. Esto permite sustituir o incorporar nuevos proveedores sin modificar el modelo de dominio.

##### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

El Component Diagram de Identity & Profile Management representa la descomposición interna del contexto dentro del backend de CollabPro. El componente de Interface expone los servicios de autenticación, perfiles y redes sociales. Los componentes de Application coordinan los casos de uso, mientras que el Domain Model mantiene las reglas relacionadas con cuentas y perfiles. Finalmente, los adapters de Infrastructure proporcionan persistencia, manejo seguro de credenciales e integración con proveedores de identidad social.

##### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams

En esta sección se representa el diseño a nivel de código del Bounded Context Identity & Profile Management mediante el Domain Layer Class Diagram y el Database Design Diagram.

###### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams

El Class Diagram muestra `Account` como Aggregate Root. Una instancia de `Account` mantiene, según su tipo, un `BrandProfile` o un `CreatorProfile`. El `CreatorProfile` puede mantener múltiples `SocialMediaAccount`. Asimismo, se representan los Value Objects, enumeraciones y la abstracción `AccountRepository`.

###### 2.6.1.6.2. Bounded Context Database Design Diagram

El Database Design Diagram representa la persistencia correspondiente a cuentas, perfiles empresariales, perfiles de creadores y cuentas sociales vinculadas. Debe conservarse la relación uno a uno entre una cuenta y su perfil, mientras que un creador puede poseer múltiples cuentas sociales asociadas.

![Database Design Diagram de Identity & Profile Management](assets/C02/DDD/DatabaseDiagram/database-diagram-identity-profile.png)

#### 2.6.2. Bounded Context: Campaign Management

El Bounded Context Campaign Management administra el ciclo de vida de las oportunidades comerciales publicadas por las empresas antes de que exista una colaboración formal. Incluye la creación de campañas, definición de requisitos y entregables esperados, publicación, búsqueda por parte de los creadores y administración de postulaciones.

La separación entre Campaign y Collaboration permite distinguir la fase de búsqueda y selección de creadores de la fase posterior de ejecución de un acuerdo ya aceptado por ambas partes.

##### 2.6.2.1. Domain Layer

`Campaign` representa el Aggregate principal del contexto y contiene las condiciones necesarias para participar. Las postulaciones son representadas mediante el Aggregate `Application`, cuyo ciclo de vida es independiente una vez que el creador presenta su candidatura.

| Clase                           | Tipo                    | Propósito                                                                                                                    | Principales atributos                                                                                            | Principales métodos                                                          |
| ------------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `Campaign`                      | Aggregate Root / Entity | Representar una oportunidad de colaboración creada por una empresa.                                                          | `campaignId`, `brandId`, `title`, `objective`, `description`, `status`, `publicationDate`, `applicationDeadline` | `defineConditions()`, `publish()`, `update()`, `close()`                     |
| `CampaignRequirement`           | Entity / Value Object   | Representar una condición que debe cumplir un creador para participar.                                                       | `requirementId`, `description`, `mandatory`                                                                      | `changeDescription()`                                                        |
| `DeliverableSpecification`      | Entity                  | Definir el contenido o actividad que se espera del creador.                                                                  | `specificationId`, `contentType`, `description`, `quantity`, `deadline`                                          | `updateDeadline()`, `updateDescription()`                                    |
| `CompensationTerms`             | Value Object            | Expresar la compensación ofrecida como parte de las condiciones de campaña sin realizar todavía su procesamiento financiero. | `type`, `amount`, `currency`, `description`                                                                      | `isMonetary()`                                                               |
| `Application`                   | Aggregate Root / Entity | Representar la postulación de un creador a una campaña.                                                                      | `applicationId`, `campaignId`, `creatorId`, `message`, `status`, `submittedAt`                                   | `submit()`, `update()`, `cancel()`, `select()`, `reject()`                   |
| `CampaignStatus`                | Enumeration             | Representar el estado de una campaña.                                                                                        | `DRAFT`, `OPEN`, `CLOSED`, `CANCELLED`                                                                           | N/A                                                                          |
| `ApplicationStatus`             | Enumeration             | Representar el estado de una postulación.                                                                                    | `PENDING`, `SELECTED`, `REJECTED`, `CANCELLED`                                                                   | N/A                                                                          |
| `CampaignRepository`            | Repository Interface    | Definir la persistencia del Aggregate `Campaign`.                                                                            | N/A                                                                                                              | `save()`, `findById()`, `search()`                                           |
| `ApplicationRepository`         | Repository Interface    | Definir la persistencia de las postulaciones.                                                                                | N/A                                                                                                              | `save()`, `findById()`, `findByCampaignId()`, `existsByCampaignAndCreator()` |
| `ApplicationEligibilityService` | Domain Service          | Evaluar si un creador cumple los requisitos obligatorios definidos por una campaña.                                          | N/A                                                                                                              | `evaluate()`                                                                 |

Una `Campaign` contiene uno o más `CampaignRequirement` y `DeliverableSpecification`, además de las condiciones de compensación. Una campaña puede recibir múltiples `Application`, pero un creador no debe mantener postulaciones duplicadas activas sobre la misma campaña.

##### 2.6.2.2. Interface Layer

| Clase                   | Propósito                                                                                           | Principales operaciones                                                                                                                |
| ----------------------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| `CampaignController`    | Exponer las operaciones de creación, actualización, publicación y consulta de campañas.             | `createCampaign()`, `updateCampaign()`, `getCampaign()`, `searchCampaigns()`                                                           |
| `ApplicationController` | Gestionar las postulaciones realizadas por los creadores y su evaluación por parte de las empresas. | `submitApplication()`, `updateApplication()`, `cancelApplication()`, `getApplications()`, `selectApplication()`, `rejectApplication()` |

##### 2.6.2.3. Application Layer

| Clase                                    | Tipo            | Responsabilidad                                                          |
| ---------------------------------------- | --------------- | ------------------------------------------------------------------------ |
| `CreateCampaignCommandHandler`           | Command Handler | Crear una campaña en estado inicial.                                     |
| `DefineCampaignConditionsCommandHandler` | Command Handler | Registrar requisitos, entregables, fechas y condiciones de compensación. |
| `PublishCampaignCommandHandler`          | Command Handler | Verificar que la campaña pueda abrirse a postulaciones.                  |
| `UpdateCampaignCommandHandler`           | Command Handler | Coordinar las modificaciones permitidas sobre una campaña.               |
| `SearchCampaignsQueryHandler`            | Query Handler   | Recuperar campañas utilizando los criterios indicados por el creador.    |
| `GetCampaignDetailsQueryHandler`         | Query Handler   | Recuperar las condiciones completas de una campaña.                      |
| `SubmitApplicationCommandHandler`        | Command Handler | Validar requisitos y registrar una postulación.                          |
| `UpdateApplicationCommandHandler`        | Command Handler | Modificar una postulación mientras continúe pendiente.                   |
| `CancelApplicationCommandHandler`        | Command Handler | Cancelar una postulación pendiente.                                      |
| `EvaluateApplicationCommandHandler`      | Command Handler | Registrar la selección o rechazo realizado por la empresa.               |

Cuando una postulación es seleccionada, el contexto registra dicho resultado. La creación de la colaboración correspondiente pertenece al Bounded Context Collaboration Management.

##### 2.6.2.4. Infrastructure Layer

| Clase                           | Propósito                                                                          |
| ------------------------------- | ---------------------------------------------------------------------------------- |
| `CampaignPersistenceAdapter`    | Implementar las operaciones definidas por `CampaignRepository`.                    |
| `ApplicationPersistenceAdapter` | Implementar las operaciones definidas por `ApplicationRepository`.                 |
| `CampaignSearchAdapter`         | Ejecutar la búsqueda de campañas según criterios como nicho, condiciones y estado. |

Las decisiones de persistencia se mantienen separadas del modelo de dominio, permitiendo que las reglas asociadas a campañas y postulaciones no dependan de la tecnología de almacenamiento utilizada.

##### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

El Component Diagram de Campaign Management muestra los componentes responsables de la administración de campañas y postulaciones. Los Controllers reciben las solicitudes provenientes de las aplicaciones móviles, los Application Handlers coordinan los casos de uso, el Domain Model implementa las reglas sobre campañas y postulaciones, y los Persistence Adapters almacenan sus estados.

##### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

###### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams

El Class Diagram representa los Aggregates `Campaign` y `Application`. Una campaña contiene requisitos, especificaciones de entregables y condiciones de compensación. Las postulaciones referencian la campaña y al creador correspondiente, manteniendo su propio ciclo de vida.

###### 2.6.2.6.2. Bounded Context Database Design Diagram

La persistencia del contexto contempla la campaña, sus requisitos, especificaciones de entregables, condiciones de compensación y postulaciones. La relación entre campañas y postulaciones es de uno a muchos.

![Database Design Diagram de Campaign Management](assets/C02/DDD/DatabaseDiagram/database-diagram-campaign.png)

#### 2.6.3. Bounded Context: Collaboration Management

Collaboration Management controla la ejecución de una relación comercial después de que una empresa selecciona a un creador y ambas partes aceptan sus condiciones. El contexto mantiene el acuerdo aceptado, el estado de la colaboración, los entregables presentados, las evidencias de cumplimiento, las revisiones realizadas por la empresa y las incidencias que puedan surgir.

Este contexto representa uno de los núcleos principales de CollabPro debido a que concentra la trazabilidad que permite sustituir los acuerdos informales realizados mediante mensajes dispersos.

##### 2.6.3.1. Domain Layer

`Collaboration` funciona como Aggregate Root y representa la relación activa entre una empresa y un creador. Las condiciones aceptadas se conservan mediante un `AgreementSnapshot`, evitando que modificaciones posteriores de la campaña cambien las obligaciones previamente acordadas.

| Clase                     | Tipo                    | Propósito                                                                            | Principales atributos                                                                         | Principales métodos                                            |
| ------------------------- | ----------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| `Collaboration`           | Aggregate Root / Entity | Representar el acuerdo activo entre una empresa y un creador.                        | `collaborationId`, `campaignId`, `brandId`, `creatorId`, `status`, `startedAt`, `completedAt` | `activate()`, `markExpired()`, `complete()`, `cancel()`        |
| `AgreementSnapshot`       | Value Object            | Conservar las condiciones aceptadas por ambas partes al iniciar la colaboración.     | `requirements`, `deliverableTerms`, `compensationTerms`, `acceptedAt`                         | `matches()`                                                    |
| `Deliverable`             | Entity                  | Representar un entregable requerido durante la colaboración.                         | `deliverableId`, `type`, `description`, `deadline`, `status`, `submittedAt`                   | `submit()`, `resubmit()`, `approve()`, `reject()`              |
| `Evidence`                | Entity / Value Object   | Representar la evidencia presentada para demostrar el cumplimiento de un entregable. | `evidenceId`, `type`, `reference`, `submittedAt`                                              | `validateReference()`                                          |
| `DeliverableReview`       | Entity                  | Mantener el historial de decisiones realizadas sobre un entregable.                  | `reviewId`, `deliverableId`, `decision`, `observation`, `reviewedAt`                          | N/A                                                            |
| `Incident`                | Entity                  | Representar un desacuerdo o problema relacionado con la colaboración.                | `incidentId`, `type`, `description`, `status`, `openedAt`, `resolvedAt`, `resolution`         | `open()`, `resolve()`                                          |
| `CollaborationStatus`     | Enumeration             | Representar el estado de la colaboración.                                            | `PENDING`, `ACTIVE`, `UNDER_REVIEW`, `COMPLETED`, `EXPIRED`, `CANCELLED`, `DISPUTED`          | N/A                                                            |
| `DeliverableStatus`       | Enumeration             | Representar el estado de un entregable.                                              | `PENDING`, `SUBMITTED`, `LATE`, `APPROVED`, `REJECTED`, `RESUBMITTED`                         | N/A                                                            |
| `IncidentStatus`          | Enumeration             | Representar el estado de una incidencia.                                             | `OPEN`, `UNDER_REVIEW`, `RESOLVED`                                                            | N/A                                                            |
| `CollaborationRepository` | Repository Interface    | Definir las operaciones de persistencia del Aggregate.                               | N/A                                                                                           | `save()`, `findById()`, `findByBrandId()`, `findByCreatorId()` |

Una colaboración contiene uno o varios `Deliverable`. Cada entregable puede tener múltiples evidencias y revisiones a lo largo de su ciclo de vida. Una colaboración también puede registrar cero o múltiples incidencias.

La colaboración solo debe considerarse completada cuando los entregables obligatorios hayan alcanzado un estado válido para su cierre y no exista una condición que impida completarla.

##### 2.6.3.2. Interface Layer

| Clase                     | Propósito                                                               | Principales operaciones                                                                                            |
| ------------------------- | ----------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| `CollaborationController` | Gestionar creación, consulta, estado e historial de las colaboraciones. | `createCollaboration()`, `getCollaboration()`, `getCollaborationHistory()`                                         |
| `DeliverableController`   | Gestionar la presentación, revisión y corrección de entregables.        | `submitDeliverable()`, `getDeliverables()`, `approveDeliverable()`, `rejectDeliverable()`, `resubmitDeliverable()` |
| `IncidentController`      | Gestionar las incidencias registradas sobre una colaboración.           | `createIncident()`, `getIncidents()`, `resolveIncident()`                                                          |

##### 2.6.3.3. Application Layer

| Clase                                 | Tipo            | Responsabilidad                                                                         |
| ------------------------------------- | --------------- | --------------------------------------------------------------------------------------- |
| `CreateCollaborationCommandHandler`   | Command Handler | Crear la colaboración a partir de una postulación seleccionada y condiciones aceptadas. |
| `GetCollaborationQueryHandler`        | Query Handler   | Recuperar el estado y condiciones vigentes de una colaboración.                         |
| `SubmitDeliverableCommandHandler`     | Command Handler | Registrar un entregable y su evidencia.                                                 |
| `ReviewDeliverableCommandHandler`     | Command Handler | Registrar la aprobación o rechazo de un entregable.                                     |
| `ResubmitDeliverableCommandHandler`   | Command Handler | Registrar una nueva versión de un entregable rechazado cuando corresponda.              |
| `OpenIncidentCommandHandler`          | Command Handler | Abrir una incidencia relacionada con una colaboración.                                  |
| `ResolveIncidentCommandHandler`       | Command Handler | Registrar la resolución y cerrar una incidencia.                                        |
| `GetCollaborationHistoryQueryHandler` | Query Handler   | Recuperar las colaboraciones anteriores relacionadas con una empresa o creador.         |
| `CompleteCollaborationCommandHandler` | Command Handler | Verificar las condiciones de cierre y completar una colaboración.                       |

Cuando una colaboración satisface sus condiciones de cumplimiento, el contexto puede producir un evento de dominio que indique que la compensación puede continuar su ciclo en Billing & Compensation Management.

##### 2.6.3.4. Infrastructure Layer

| Clase                             | Propósito                                                                                                                               |
| --------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| `CollaborationPersistenceAdapter` | Implementar `CollaborationRepository`.                                                                                                  |
| `EvidenceStorageAdapter`          | Almacenar o recuperar las evidencias asociadas a entregables cuando estas requieren un recurso externo de almacenamiento.               |
| `CollaborationEventPublisher`     | Propagar los eventos relevantes generados por el contexto hacia otras capacidades de la solución, sin trasladar las reglas del dominio. |

##### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

El Component Diagram de Collaboration Management debe mostrar los Controllers de colaboración, entregables e incidencias; los handlers encargados de los casos de uso; el Domain Model compuesto por Collaboration, Deliverable e Incident; y los adapters responsables de persistencia y almacenamiento de evidencias.

##### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams

###### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

El Class Diagram representa `Collaboration` como Aggregate Root y detalla las relaciones con `AgreementSnapshot`, `Deliverable`, `Evidence`, `DeliverableReview` e `Incident`, además de sus enumeraciones y `CollaborationRepository`.

###### 2.6.3.6.2. Bounded Context Database Design Diagram

La persistencia de este contexto debe conservar la colaboración y el snapshot de sus condiciones, sus entregables, evidencias, revisiones e incidencias. El modelo debe permitir mantener trazabilidad histórica de las revisiones y correcciones.

![Database Design Diagram de Collaboration Management](assets/C02/DDD/DatabaseDiagram/database-diagram-collaboration.png)

#### 2.6.4. Bounded Context: Billing & Compensation Management

Billing & Compensation Management concentra los procesos económicos de CollabPro. Separa el modelo comercial de suscripción de la plataforma del modelo de compensación asociado a las colaboraciones entre empresas y creadores.

El contexto debe distinguir entre una suscripción pagada por una empresa para utilizar las funcionalidades de CollabPro y una compensación acordada con un creador por el cumplimiento de una colaboración. Asimismo, la compensación puede ser monetaria o no monetaria, según las condiciones establecidas entre las partes.

##### 2.6.4.1. Domain Layer

| Clase                      | Tipo                    | Propósito                                                                            | Principales atributos                                                                                   | Principales métodos                                                               |
| -------------------------- | ----------------------- | ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| `PaymentAccount`           | Aggregate Root / Entity | Representar la configuración financiera asociada a un usuario.                       | `paymentAccountId`, `accountId`, `status`                                                               | `addPaymentMethod()`, `removePaymentMethod()`                                     |
| `PaymentMethod`            | Entity                  | Representar un medio habilitado para realizar o recibir operaciones económicas.      | `paymentMethodId`, `providerReference`, `type`, `status`                                                | `activate()`, `disable()`                                                         |
| `Subscription`             | Aggregate Root / Entity | Representar la suscripción contratada por una empresa.                               | `subscriptionId`, `brandId`, `planCode`, `status`, `startedAt`, `renewalDate`                           | `activate()`, `renew()`, `suspend()`, `cancel()`                                  |
| `Compensation`             | Aggregate Root / Entity | Representar el valor acordado para un creador dentro de una colaboración.            | `compensationId`, `collaborationId`, `creatorId`, `type`, `amount`, `currency`, `description`, `status` | `markPending()`, `authorizeRelease()`, `markPaid()`, `markAffectedByIncident()`   |
| `PaymentTransaction`       | Entity                  | Mantener la referencia y estado de una operación procesada por un proveedor externo. | `transactionId`, `providerReference`, `amount`, `currency`, `status`, `processedAt`                     | `confirm()`, `fail()`, `refund()`                                                 |
| `Money`                    | Value Object            | Representar un monto monetario y su moneda.                                          | `amount`, `currency`                                                                                    | `isPositive()`                                                                    |
| `CompensationType`         | Enumeration             | Identificar la forma de compensación.                                                | `CASH`, `PRODUCT`, `SERVICE`, `CREDIT`, `BARTER`                                                        | N/A                                                                               |
| `CompensationStatus`       | Enumeration             | Representar el estado de la compensación.                                            | `PENDING`, `READY`, `PROCESSING`, `PAID`, `AFFECTED`, `CANCELLED`                                       | N/A                                                                               |
| `SubscriptionStatus`       | Enumeration             | Representar el estado de una suscripción.                                            | `PENDING`, `ACTIVE`, `SUSPENDED`, `CANCELLED`                                                           | N/A                                                                               |
| `PaymentAccountRepository` | Repository Interface    | Definir persistencia de cuentas y medios de pago.                                    | N/A                                                                                                     | `save()`, `findByAccountId()`                                                     |
| `SubscriptionRepository`   | Repository Interface    | Definir persistencia de suscripciones.                                               | N/A                                                                                                     | `save()`, `findByBrandId()`                                                       |
| `CompensationRepository`   | Repository Interface    | Definir persistencia de compensaciones.                                              | N/A                                                                                                     | `save()`, `findByCollaborationId()`                                               |
| `PaymentGateway`           | Domain Port             | Abstraer las operaciones necesarias sobre un proveedor externo de pagos.             | N/A                                                                                                     | `preparePaymentMethod()`, `createSubscription()`, `initiatePayment()`, `refund()` |

La existencia de `PaymentGateway` evita que el modelo dependa directamente de un proveedor específico. La tecnología concreta deberá establecerse de acuerdo con los resultados obtenidos en la Spike Story relacionada con la viabilidad del proveedor de pagos.

##### 2.6.4.2. Interface Layer

| Clase                      | Propósito                                                            | Principales operaciones                      |
| -------------------------- | -------------------------------------------------------------------- | -------------------------------------------- |
| `BillingController`        | Gestionar la asociación de medios de pago.                           | `linkPaymentMethod()`, `getPaymentMethods()` |
| `SubscriptionController`   | Gestionar la creación y consulta de suscripciones.                   | `createSubscription()`, `getSubscription()`  |
| `CompensationController`   | Consultar e iniciar las operaciones relacionadas con compensaciones. | `getCompensation()`, `initiatePayment()`     |
| `PaymentWebhookController` | Recibir y validar eventos enviados por el proveedor externo.         | `receivePaymentEvent()`                      |

##### 2.6.4.3. Application Layer

| Clase                                       | Tipo            | Responsabilidad                                                                                                    |
| ------------------------------------------- | --------------- | ------------------------------------------------------------------------------------------------------------------ |
| `LinkPaymentMethodCommandHandler`           | Command Handler | Coordinar la asociación de un medio de pago.                                                                       |
| `CreateSubscriptionCommandHandler`          | Command Handler | Crear y activar una suscripción mediante el proveedor correspondiente.                                             |
| `GetSubscriptionQueryHandler`               | Query Handler   | Consultar el estado vigente de la suscripción.                                                                     |
| `CreateCompensationCommandHandler`          | Command Handler | Registrar la compensación asociada a una nueva colaboración.                                                       |
| `AuthorizeCompensationCommandHandler`       | Command Handler | Permitir la liberación de la compensación una vez satisfechas las condiciones externas necesarias.                 |
| `InitiateCompensationPaymentCommandHandler` | Command Handler | Iniciar una operación monetaria cuando la compensación corresponda a efectivo.                                     |
| `GetCompensationQueryHandler`               | Query Handler   | Consultar el estado de la compensación.                                                                            |
| `HandlePaymentProviderEventHandler`         | Event Handler   | Interpretar un evento validado del proveedor y actualizar la transacción correspondiente sin duplicar operaciones. |

##### 2.6.4.4. Infrastructure Layer

| Clase                              | Propósito                                                                                |
| ---------------------------------- | ---------------------------------------------------------------------------------------- |
| `PaymentAccountPersistenceAdapter` | Implementar `PaymentAccountRepository`.                                                  |
| `SubscriptionPersistenceAdapter`   | Implementar `SubscriptionRepository`.                                                    |
| `CompensationPersistenceAdapter`   | Implementar `CompensationRepository`.                                                    |
| `ExternalPaymentGatewayAdapter`    | Implementar `PaymentGateway` utilizando el proveedor seleccionado.                       |
| `PaymentWebhookVerifier`           | Verificar autenticidad e integridad de los eventos recibidos desde el proveedor externo. |

El Spike relacionado con Stripe se utiliza como investigación de viabilidad. Por ello, el dominio no depende de Stripe de manera directa y conserva la abstracción `PaymentGateway`.

##### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

El Component Diagram debe mostrar los componentes de medios de pago, suscripciones y compensaciones, así como la integración del backend con el proveedor de pagos externo. La comunicación con dicho proveedor se realiza exclusivamente mediante el adapter definido en Infrastructure Layer.

##### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams

###### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams

El Class Diagram presenta los Aggregates `PaymentAccount`, `Subscription` y `Compensation`, junto con `PaymentMethod`, `PaymentTransaction`, el Value Object `Money`, sus enumeraciones y las abstracciones de persistencia y comunicación con proveedores financieros.

###### 2.6.4.6.2. Bounded Context Database Design Diagram

El Database Design Diagram representa las cuentas financieras, medios de pago tokenizados o referenciados mediante el proveedor, suscripciones, compensaciones y transacciones. No se almacenan directamente datos sensibles completos del medio de pago; se conserva únicamente la referencia necesaria proporcionada por el proveedor seleccionado.

![Database Design Diagram de Billing & Compensation Management](assets/C02/DDD/DatabaseDiagram/database-diagram-billing.png)

#### 2.6.5. Bounded Context: Performance & Attribution Management

Performance & Attribution Management concentra las capacidades utilizadas para registrar, consultar e interpretar los resultados obtenidos por una colaboración. El contexto administra las métricas provenientes de fuentes autorizadas, evidencias adicionales y mecanismos de atribución como enlaces asociados a una colaboración.

La separación de este contexto permite mantener las reglas de medición desacopladas del ciclo operacional de una colaboración y de las particularidades de cada proveedor de red social.

##### 2.6.5.1. Domain Layer

| Clase                   | Tipo                    | Propósito                                                                                           | Principales atributos                                                                         | Principales métodos                                          |
| ----------------------- | ----------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| `PerformanceReport`     | Aggregate Root / Entity | Consolidar los resultados disponibles para una colaboración.                                        | `performanceReportId`, `collaborationId`, `periodStart`, `periodEnd`, `updatedAt`             | `addMetricSnapshot()`, `addEvidence()`, `calculateSummary()` |
| `MetricSnapshot`        | Entity                  | Registrar una métrica obtenida en un momento y periodo determinados.                                | `metricSnapshotId`, `metricType`, `value`, `source`, `capturedAt`, `periodStart`, `periodEnd` | `updateValue()`                                              |
| `PerformanceEvidence`   | Entity                  | Registrar evidencia suministrada cuando una métrica no puede obtenerse automáticamente.             | `evidenceId`, `type`, `reference`, `submittedAt`, `verificationStatus`                        | `verify()`, `reject()`                                       |
| `AttributionLink`       | Entity                  | Representar un enlace o identificador utilizado para relacionar interacciones con una colaboración. | `attributionLinkId`, `collaborationId`, `token`, `destination`, `status`                      | `activate()`, `deactivate()`                                 |
| `AttributedInteraction` | Entity                  | Registrar una interacción asociada al mecanismo de atribución.                                      | `interactionId`, `attributionLinkId`, `interactionType`, `occurredAt`                         | N/A                                                          |
| `MetricType`            | Enumeration             | Identificar las métricas utilizadas por CollabPro.                                                  | `REACH`, `IMPRESSIONS`, `ENGAGEMENT`, `CLICKS`, `CONVERSIONS`                                 | N/A                                                          |
| `MetricSource`          | Value Object            | Identificar el origen y nivel de confiabilidad del dato registrado.                                 | `provider`, `sourceType`                                                                      | `isAutomated()`                                              |
| `PerformanceRepository` | Repository Interface    | Definir la persistencia del Aggregate de desempeño.                                                 | N/A                                                                                           | `save()`, `findByCollaborationId()`                          |
| `SocialMetricsProvider` | Domain Port             | Abstraer la consulta autorizada de métricas disponibles en servicios externos.                      | N/A                                                                                           | `getAvailableMetrics()`                                      |

Los datos proporcionados automáticamente y las evidencias suministradas manualmente deben mantenerse diferenciados mediante su `MetricSource`, permitiendo que la empresa conozca el origen de la información presentada.

##### 2.6.5.2. Interface Layer

| Clase                           | Propósito                                                                | Principales operaciones                                        |
| ------------------------------- | ------------------------------------------------------------------------ | -------------------------------------------------------------- |
| `PerformanceController`         | Exponer los resultados y evidencias correspondientes a una colaboración. | `getMetrics()`, `registerEvidence()`, `getPerformanceReport()` |
| `AttributionController`         | Crear y consultar los mecanismos de atribución.                          | `createAttributionLink()`, `getAttributionResults()`           |
| `AttributionTrackingController` | Registrar las interacciones generadas por enlaces de atribución.         | `trackInteraction()`                                           |

##### 2.6.5.3. Application Layer

| Clase                                       | Tipo            | Responsabilidad                                                                     |
| ------------------------------------------- | --------------- | ----------------------------------------------------------------------------------- |
| `RefreshMetricsCommandHandler`              | Command Handler | Solicitar al proveedor autorizado las métricas disponibles y actualizar el reporte. |
| `RegisterPerformanceEvidenceCommandHandler` | Command Handler | Registrar evidencia proporcionada por un creador.                                   |
| `CreateAttributionLinkCommandHandler`       | Command Handler | Crear un identificador de atribución para una colaboración.                         |
| `RecordAttributedInteractionCommandHandler` | Command Handler | Registrar una interacción asociada a un mecanismo de atribución.                    |
| `GetPerformanceReportQueryHandler`          | Query Handler   | Consolidar la información disponible para su consulta por la empresa.               |
| `GetAttributionResultsQueryHandler`         | Query Handler   | Recuperar los resultados asociados a los mecanismos de atribución.                  |

##### 2.6.5.4. Infrastructure Layer

| Clase                               | Propósito                                                                                 |
| ----------------------------------- | ----------------------------------------------------------------------------------------- |
| `PerformancePersistenceAdapter`     | Implementar `PerformanceRepository`.                                                      |
| `SocialMetricsProviderAdapter`      | Implementar `SocialMetricsProvider` utilizando las APIs autorizadas que resulten viables. |
| `AttributionPersistenceAdapter`     | Gestionar la persistencia de enlaces e interacciones atribuidas.                          |
| `PerformanceEvidenceStorageAdapter` | Gestionar evidencias externas asociadas a métricas cuando corresponda.                    |

Las APIs concretas utilizadas para obtener datos de redes sociales se determinarán en función de los resultados de las Spike Stories de OAuth y medición de campañas. Por ello, el Domain Layer permanece independiente de Instagram, TikTok, YouTube u otro proveedor específico.

##### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams

El Component Diagram representa la coordinación entre los componentes de resultados, métricas, evidencias y atribución. También representa la comunicación con los servicios externos utilizados para obtener información autorizada de las redes sociales.

##### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams

###### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams

El Class Diagram representa `PerformanceReport` como Aggregate Root y sus relaciones con `MetricSnapshot`, `PerformanceEvidence`, `AttributionLink` y `AttributedInteraction`, junto con los Value Objects, enumeraciones y la abstracción `SocialMetricsProvider`.

###### 2.6.5.6.2. Bounded Context Database Design Diagram

El Database Design Diagram debe distinguir las métricas obtenidas automáticamente de las evidencias ingresadas manualmente y mantener la relación de cada dato con la colaboración correspondiente. También debe representar los enlaces de atribución y las interacciones asociadas.

![Database Design Diagram de Performance & Attribution Management](assets/C02/DDD/DatabaseDiagram/database-diagram-performance.png)

---

## Capítulo III: Solution UI/UX Design

### 3.1. Product Design

El diseño de producto de CollabPro busca trasladar la propuesta de valor del negocio a una experiencia móvil clara, consistente y orientada a tareas. La solución está dirigida principalmente a dos tipos de usuario, representantes de pequeñas y medianas empresas y creadores de contenido. Debido a que ambos participan en un mismo proceso de colaboración, pero persiguen objetivos diferentes, la experiencia visual y la arquitectura de información se diseñan para mantener una base común y, al mismo tiempo, presentar funcionalidades específicas según el tipo de cuenta.

Para las empresas, la experiencia se orienta principalmente a la creación y gestión de campañas, revisión de postulaciones, selección de creadores, validación de entregables, administración de compensaciones y consulta de resultados. Para los creadores, la experiencia prioriza el descubrimiento de campañas, revisión de condiciones, postulación, seguimiento de colaboraciones, presentación de evidencias y consulta del estado de sus compensaciones.

El producto mantiene una estructura visual uniforme en todas sus funcionalidades mediante componentes reutilizables, una paleta cromática común, jerarquías tipográficas consistentes y patrones de interacción similares. Estas decisiones buscan reducir la curva de aprendizaje y permitir que el usuario reconozca rápidamente las acciones principales, los estados de los procesos y la información relevante dentro de cada pantalla.

#### 3.1.1. Style Guidelines

Los Style Guidelines de CollabPro establecen los lineamientos visuales y de comunicación utilizados para mantener una experiencia coherente entre las diferentes funcionalidades de la aplicación móvil.

El sistema visual busca transmitir principalmente **confianza, profesionalismo, claridad y cercanía**, atributos necesarios debido a que CollabPro intermedia relaciones comerciales entre empresas y creadores de contenido. A diferencia de una plataforma social orientada principalmente al entretenimiento, la interfaz debe comunicar que cada campaña, postulación, colaboración, entregable y compensación forma parte de un proceso estructurado y verificable.

Las decisiones de diseño se implementan mediante un conjunto de componentes reutilizables que permiten mantener consistencia entre pantallas, incluyendo contenedores de información, botones de acción, etiquetas de estado, campos de entrada, selectores y tarjetas navegables.

![Colors](./assets/C03/StyleGuidelines/StyleGui.png)


##### 3.1.1.1. General Style Guidelines

###### Branding

La identidad visual de CollabPro parte del nombre de la plataforma, compuesto por las palabras **Collab** y **Pro**.

El término _Collab_ representa la colaboración entre empresas y creadores de contenido, mientras que _Pro_ comunica el objetivo de profesionalizar estas relaciones mediante campañas estructuradas, condiciones explícitas, seguimiento de entregables y medición de resultados.

Dentro de la aplicación, la marca se representa mediante el wordmark:

**collabpro**

Visualmente se diferencian ambas partes del nombre:

- **collab:** utiliza el color principal de texto oscuro.
- **pro:** utiliza el color principal de marca, Teal.

Esta combinación permite reforzar el reconocimiento del producto sin depender de elementos gráficos complejos y mantiene una identidad compatible con una interfaz orientada a negocios.

La aplicación utiliza el nombre **CollabPro** como nombre oficial del producto en títulos, configuración y distribución de la aplicación.

![CollabPro](./assets/C03/StyleGuidelines/branding.png)

###### Color Palette

La paleta cromática utilizada en CollabPro se basa en colores sobrios para las superficies principales y colores de acento para representar acciones y estados.

| Nombre         | Hexadecimal | Uso principal                                                                           |
| -------------- | ----------- | --------------------------------------------------------------------------------------- |
| **Ink**        | `#172B39`   | Texto principal, títulos y elementos de alta jerarquía.                                 |
| **Muted**      | `#5E7280`   | Texto secundario, descripciones y datos complementarios.                                |
| **Teal**       | `#087E80`   | Color principal de la marca, acciones principales, etiquetas y elementos seleccionados. |
| **Light Teal** | `#E1F4F1`   | Fondos informativos, estados y elementos resaltados de baja intensidad.                 |
| **Coral**      | `#FF765C`   | Color secundario y de acento.                                                           |
| **Canvas**     | `#F6F8F7`   | Fondo general de la aplicación.                                                         |
| **Border**     | `#DCE6E4`   | Bordes, divisores y delimitación entre componentes.                                     |
| **Warning**    | `#B75C21`   | Mensajes de error, advertencia o situaciones que requieren atención.                    |
| **White**      | `#FFFFFF`   | Superficies de tarjetas, campos y componentes elevados.                                 |

El **Teal (`#087E80`)** se utiliza como color principal debido a que permite transmitir estabilidad y confianza sin adoptar una apariencia excesivamente corporativa. Se utiliza principalmente en botones de acción, elementos seleccionados, elementos de marca y estados positivos o informativos.

El **Ink (`#172B39`)** proporciona el contraste necesario para títulos y contenido principal y evita utilizar negro absoluto, conservando una apariencia visual más suave.

El color **Muted (`#5E7280`)** permite reducir visualmente la importancia de información secundaria sin eliminar su legibilidad.

El fondo **Canvas (`#F6F8F7`)** genera una separación perceptible entre la superficie de la aplicación y las tarjetas blancas utilizadas para agrupar información.

El color **Warning (`#B75C21`)** se reserva para comunicar errores o situaciones que requieren atención, evitando utilizar el color de marca para mensajes negativos.

![Colors](./assets/C03/StyleGuidelines/Color.png)

###### Typography

CollabPro utiliza la tipografía proporcionada por el sistema de diseño de Material 3 mediante `FontFamily.Default`, buscando mantener buena legibilidad y compatibilidad con diferentes dispositivos Android.

![Colors](./assets/C03/StyleGuidelines/typography.png)
![Colors](./assets/C03/StyleGuidelines/typography1.png)


La aplicación utiliza variaciones de tamaño y peso para establecer jerarquía entre los elementos.

| Elemento                     | Tamaño aproximado | Peso              | Uso                                                         |
| ---------------------------- | ----------------: | ----------------- | ----------------------------------------------------------- |
| Título principal de pantalla |           `30 sp` | Bold              | Identificar la función o contexto principal de la pantalla. |
| Logotipo textual             |           `22 sp` | Bold              | Representación de la identidad CollabPro.                   |
| Título de panel o tarjeta    |           `17 sp` | Bold              | Identificar agrupaciones de información.                    |
| Texto principal              |        `14-16 sp` | Normal            | Descripciones y contenido general.                          |
| Información secundaria       |           `13 sp` | Normal / SemiBold | Detalles, valores y datos complementarios.                  |
| Eyebrow / contexto           |           `11 sp` | Bold              | Identificar contexto, categoría o etapa del proceso.        |

Los títulos se mantienen breves y descriptivos, por ejemplo:

- `Mis campañas`
- `Explorar campañas`
- `Mis postulaciones`
- `Colaboraciones`
- `Resultados`
- `Compensación`

La jerarquía tipográfica evita mostrar bloques extensos de texto cuando la misma información puede representarse mediante títulos, etiquetas, estados y agrupaciones.

###### Spacing

El sistema de espaciado utiliza valores consistentes para reducir diferencias arbitrarias entre pantallas.

Entre los principales valores utilizados se encuentran:

- **8 dp:** separación reducida entre componentes relacionados.
- **10 dp:** separación interna de elementos dentro de determinados grupos.
- **14 dp:** separación vertical habitual entre componentes.
- **18 dp:** padding interno de tarjetas.
- **20 dp:** padding horizontal principal de las pantallas.
- **22 dp:** separación superior inicial del contenido.
- **36 dp:** espacio inferior para evitar que el último elemento quede demasiado próximo al límite de la pantalla.

Los componentes mantienen márgenes suficientes para favorecer la lectura y permitir una interacción táctil adecuada.

Las tarjetas utilizan esquinas redondeadas de aproximadamente **20 dp**, mientras que botones y campos utilizan esquinas de aproximadamente **14 dp**. Esto permite diferenciar visualmente contenedores de contenido y elementos interactivos manteniendo un mismo lenguaje visual.

###### Dimensiones para el tono de comunicación y lenguaje aplicado

El tono de CollabPro se define considerando las siguientes dimensiones:

| Dimensión                | Orientación de CollabPro                            |
| ------------------------ | --------------------------------------------------- |
| Divertido / Serio        | Principalmente serio, con una comunicación cercana. |
| Casual / Formal          | Semiformal.                                         |
| Irreverente / Respetuoso | Respetuoso.                                         |
| Entusiasta / Sereno      | Sereno y orientado a la acción.                     |

**Serio y cercano**

CollabPro administra relaciones comerciales, compensaciones, entregables y resultados, por lo que evita un tono excesivamente informal. Sin embargo, también evita lenguaje corporativo complejo que pueda dificultar la comprensión para emprendimientos pequeños o creadores independientes.

**Semiformal**

La plataforma utiliza expresiones directas como:

- `Crear campaña`
- `Explorar campañas`
- `Postular a esta campaña`
- `Validar entregable`
- `Registrar incidencia`
- `Ver resultados`

Estas etiquetas indican claramente qué ocurrirá después de la interacción.

**Respetuoso**

Los estados negativos evitan culpabilizar al usuario. Por ejemplo, en lugar de utilizar mensajes agresivos, la interfaz comunica situaciones concretas como:

- `No se pudo validar el medio de pago.`
- `No existen coincidencias.`
- `Describe el problema antes de continuar.`
- `Agrega un medio de pago para continuar.`

**Sereno**

La interfaz evita utilizar mensajes alarmistas para procesos comerciales normales. Los cambios de estado se comunican mediante etiquetas y mensajes contextuales que describen la situación actual.

###### Elementos de diseño

Los principales elementos de diseño reutilizados por CollabPro son los siguientes:

**Page**

Representa la estructura principal de una pantalla. Incluye:

- encabezado;
- identidad de CollabPro;
- opción de retorno cuando corresponde;
- eyebrow opcional;
- título principal;
- subtítulo;
- contenido vertical desplazable.

Esto permite que las diferentes funcionalidades mantengan una estructura visual uniforme.

**Panel**

Agrupa información relacionada dentro de una tarjeta blanca con borde y esquinas redondeadas.

Se utiliza, por ejemplo, para representar:

- información de campañas;
- condiciones;
- perfiles;
- resultados;
- compensaciones;
- medios de pago;
- información de colaboraciones.

**Action**

Representa botones de acción principales y secundarios.

La acción primaria se utiliza para continuar o confirmar una operación, mientras que la variante secundaria se utiliza para acciones alternativas o de menor jerarquía.

Ejemplos:

- `Crear campaña`
- `Publicar campaña`
- `Postular a esta campaña`
- `Seleccionar creadora`
- `Acepto las condiciones`

Las acciones secundarias se utilizan para opciones como editar, cancelar, volver o consultar estados alternativos.

**Status**

Representa visualmente el estado actual de una entidad o proceso mediante una etiqueta compacta.

Ejemplos de estados utilizados dentro de la aplicación:

- `Pendiente`
- `Seleccionada`
- `Rechazada`
- `Finalizada`
- `Vinculado`
- `Activa`
- `Pagada`

La representación explícita de estados resulta especialmente importante debido a que una campaña o colaboración atraviesa diferentes etapas antes de completarse.

**Entry**

Representa campos de ingreso de información.

Los campos utilizan etiquetas persistentes para indicar claramente el dato requerido y pueden mostrar un estado de error cuando el contenido ingresado no cumple las condiciones esperadas.

**Choice Row**

Permite seleccionar una opción dentro de conjuntos pequeños mediante chips.

Actualmente se utiliza para elementos como:

- idioma;
- tipo de usuario;
- categoría de campaña;
- plataforma social;
- filtros de resultados.

**Link Card**

Representa entidades o acciones navegables mediante tarjetas que combinan:

- título;
- descripción;
- estado opcional;
- enlace visual `Ver detalle →`.

Este patrón permite que campañas, postulaciones, colaboraciones e historiales puedan explorarse manteniendo una representación consistente.

![Colors](./assets/C03/StyleGuidelines/components-design-system.png)



###### Principios de diseño

**Consistencia**

Las mismas acciones, estados y entidades mantienen representaciones similares a lo largo de toda la aplicación. Una tarjeta seleccionable conserva el mismo patrón independientemente de si representa una campaña, una postulación o una colaboración.

**Jerarquía visual**

Los elementos más importantes de cada pantalla se presentan siguiendo el orden:

1. Contexto.
2. Título.
3. Descripción.
4. Información principal.
5. Acción principal.
6. Acciones secundarias.

De esta manera el usuario puede identificar rápidamente qué pantalla está utilizando y cuál es la acción esperada.

**Visibilidad del estado del sistema**

Los procesos que evolucionan en el tiempo muestran su estado de manera explícita.

Esto resulta especialmente importante para:

- campañas;
- postulaciones;
- colaboraciones;
- entregables;
- incidencias;
- suscripciones;
- compensaciones.

**Reducción de carga cognitiva**

La interfaz evita presentar simultáneamente opciones que pertenecen a etapas futuras del proceso.

Por ejemplo, la creación de una campaña se divide en pasos:

1. Información general de la campaña.
2. Condiciones, entregables, fecha y compensación.

Esto reduce la cantidad de información solicitada simultáneamente.

**Prevención de errores**

Los formularios validan que la información necesaria esté disponible antes de permitir continuar.

Entre los casos considerados se encuentran:

- correo electrónico inválido;
- contraseña demasiado corta;
- datos obligatorios de campaña vacíos;
- condiciones incompletas;
- medios de pago inválidos.

**Reconocimiento antes que recuerdo**

La aplicación prioriza mostrar opciones, estados y acciones disponibles en lugar de exigir que el usuario recuerde comandos o rutas.

**Feedback inmediato**

Después de una acción relevante se presenta un estado o mensaje que permite conocer el resultado de la interacción.

**Diseño orientado a tareas**

Cada pantalla responde principalmente a un objetivo específico. Por ejemplo:

- buscar una campaña;
- consultar sus condiciones;
- postular;
- revisar postulantes;
- aceptar un acuerdo;
- entregar evidencia;
- revisar un entregable;
- consultar una compensación.

Esto evita mezclar operaciones de diferentes etapas dentro de una misma vista.

#### 3.1.2. Information Architecture

La arquitectura de información de CollabPro organiza las funcionalidades del producto de acuerdo con el rol del usuario, el momento dentro del ciclo de una colaboración y la entidad de negocio con la que se encuentra interactuando.

La estructura se diseñó considerando que una empresa y un creador utilizan la misma plataforma, pero realizan tareas diferentes.

El representante de una empresa necesita principalmente:

1. Administrar su perfil.
2. Crear campañas.
3. Definir condiciones.
4. Revisar postulaciones.
5. Seleccionar creadores.
6. Confirmar colaboraciones.
7. Revisar entregables.
8. Gestionar incidencias.
9. Consultar compensaciones.
10. Consultar resultados e historial.

El creador de contenido necesita principalmente:

1. Administrar su perfil y redes sociales.
2. Explorar campañas.
3. Consultar requisitos y compensaciones.
4. Postular.
5. Revisar el estado de sus postulaciones.
6. Aceptar condiciones.
7. Gestionar colaboraciones activas.
8. Presentar entregables y evidencias.
9. Consultar incidencias.
10. Consultar compensaciones e historial.

Esta separación permite adaptar la información visible sin crear dos aplicaciones diferentes y mantiene un mismo lenguaje de interacción para los procesos compartidos.

![Colors](./assets/C03/StyleGuidelines/information-architecture.png)


##### 3.1.2.1. Organization Systems

CollabPro utiliza diferentes sistemas de organización dependiendo de la naturaleza de la información.

###### Organización según audiencia

La primera clasificación ocurre de acuerdo con el tipo de usuario.

**Empresa**

El espacio de empresa prioriza:

- campañas;
- postulaciones;
- validación de entregables;
- resultados;
- planes y suscripción.

**Creador**

El espacio de creador prioriza:

- exploración de campañas;
- postulaciones;
- acuerdos;
- entrega de contenido;
- compensaciones.

Las funcionalidades compartidas, como perfil, colaboraciones, historial, incidencias y medios de pago, mantienen patrones consistentes para ambos tipos de usuario.

###### Organización jerárquica

Se utiliza jerarquía visual para mostrar primero la información más importante.

Por ejemplo, en el detalle de una campaña se presenta:

1. Nombre de la campaña.
2. Empresa responsable.
3. Descripción.
4. Estado.
5. Objetivo.
6. Requisitos.
7. Entregables.
8. Condiciones de aceptación.
9. Acción disponible.

De forma similar, en las colaboraciones se presenta primero el estado y la información del acuerdo antes que las acciones complementarias.

###### Organización secuencial

Los procesos que requieren completar varias etapas siguen una organización secuencial.

**Creación de campaña**

`Nueva campaña → Condiciones de campaña → Publicación`

El primer paso solicita información general como título, objetivo, categoría y público objetivo.

El segundo solicita requisitos, entregables, fecha límite y compensación.

**Proceso del creador**

`Explorar campañas → Consultar campaña → Postular → Confirmar acuerdo → Colaboración → Entregar evidencia → Finalización`

**Proceso de empresa**

`Crear campaña → Recibir postulaciones → Revisar postulante → Seleccionar → Confirmar acuerdo → Revisar entregable → Consultar resultados`

Esta organización permite que el usuario comprenda el progreso del proceso y disminuye el riesgo de ejecutar operaciones fuera de orden.

###### Organización por tópicos

Las funcionalidades principales se agrupan de acuerdo con el objetivo que cumplen.

| Tópico                 | Información agrupada                                      |
| ---------------------- | --------------------------------------------------------- |
| Identidad              | Registro, acceso, recuperación y perfil.                  |
| Campañas               | Creación, condiciones, búsqueda, detalle y postulaciones. |
| Colaboraciones         | Acuerdos, colaboración activa, entregables e incidencias. |
| Operaciones económicas | Medios de pago, planes, suscripción y compensaciones.     |
| Resultados             | Métricas, evidencias, atribución e historial.             |

Esta organización coincide con las principales capacidades identificadas dentro del dominio de CollabPro.

###### Organización cronológica

Se utiliza organización cronológica cuando el tiempo forma parte de la interpretación de la información.

Se aplica principalmente en:

- fechas límite de campañas;
- fechas de entrega;
- colaboraciones vencidas;
- historial de colaboraciones;
- periodos de métricas;
- fechas asociadas a evidencias.

Esto permite al usuario identificar elementos próximos, vencidos o finalizados.

###### Organización por estado

Las entidades que poseen ciclo de vida muestran su condición actual.

Ejemplos:

**Postulación**

`Pendiente → Seleccionada / Rechazada / Cancelada`

**Colaboración**

`Activa → Entregada → En revisión → Finalizada`

**Compensación**

`Pendiente → Pagada`

También puede presentarse como afectada cuando existe una incidencia.

La organización por estado permite al usuario priorizar elementos que requieren una acción.

##### 3.1.2.2. Labeling Systems

El sistema de etiquetas de CollabPro utiliza términos cortos, consistentes y relacionados directamente con el dominio de negocio.

El objetivo es que las personas puedan identificar una funcionalidad sin tener que interpretar terminología técnica.

###### Etiquetas principales de navegación

| Etiqueta      | Asociación                                            |
| ------------- | ----------------------------------------------------- |
| **Inicio**    | Resumen de actividades y accesos principales.         |
| **Campañas**  | Campañas creadas y administradas por una empresa.     |
| **Explorar**  | Búsqueda de oportunidades disponibles para creadores. |
| **Colaborar** | Colaboraciones activas y sus estados.                 |
| **Perfil**    | Información del usuario o negocio.                    |

Las etiquetas se mantienen deliberadamente cortas debido al espacio disponible en dispositivos móviles.

###### Etiquetas de Campaign Management

| Etiqueta                   | Significado                                    |
| -------------------------- | ---------------------------------------------- |
| **Mis campañas**           | Campañas administradas por una empresa.        |
| **Crear campaña**          | Inicio de registro de una nueva campaña.       |
| **Nueva campaña**          | Formulario inicial de creación.                |
| **Condiciones de campaña** | Requisitos, entregables, fecha y compensación. |
| **Explorar campañas**      | Consulta de campañas disponibles.              |
| **Postular**               | Presentar interés formal en una campaña.       |
| **Mis postulaciones**      | Solicitudes realizadas por un creador.         |
| **Postulaciones**          | Candidatos recibidos por una empresa.          |
| **Revisar postulaciones**  | Evaluación de candidatos.                      |

###### Etiquetas de Collaboration Management

| Etiqueta                   | Significado                                   |
| -------------------------- | --------------------------------------------- |
| **Confirmar colaboración** | Aceptación de las condiciones acordadas.      |
| **Colaboraciones**         | Relaciones comerciales activas o registradas. |
| **Entregar contenido**     | Registro del entregable y su evidencia.       |
| **Validar entregable**     | Revisión realizada por la empresa.            |
| **Incidencias**            | Problemas o desacuerdos registrados.          |
| **Historial**              | Colaboraciones completadas anteriormente.     |

###### Etiquetas económicas

| Etiqueta           | Significado                                         |
| ------------------ | --------------------------------------------------- |
| **Medios de pago** | Métodos asociados a operaciones económicas.         |
| **Planes**         | Alternativas comerciales disponibles para empresas. |
| **Suscripción**    | Estado del plan contratado por la empresa.          |
| **Compensación**   | Valor acordado entre empresa y creador.             |
| **Pendiente**      | La operación todavía no ha sido completada.         |
| **Pagada**         | La compensación ya fue procesada.                   |

###### Etiquetas relacionadas con resultados

| Etiqueta       | Significado                                                  |
| -------------- | ------------------------------------------------------------ |
| **Resultados** | Información obtenida después de una colaboración.            |
| **Métricas**   | Datos cuantificables asociados al contenido.                 |
| **Evidencia**  | Información aportada para demostrar un resultado o entrega.  |
| **Atribución** | Relación entre una interacción y la campaña correspondiente. |
| **Periodo**    | Intervalo temporal al que pertenecen los resultados.         |
| **Origen**     | Fuente desde la que se obtuvo el dato.                       |

###### Etiquetas de acciones

Las acciones utilizan verbos que describen el resultado esperado:

- `Crear`
- `Continuar`
- `Publicar`
- `Explorar`
- `Postular`
- `Editar`
- `Cancelar`
- `Seleccionar`
- `Rechazar`
- `Aceptar`
- `Entregar`
- `Revisar`
- `Registrar`
- `Guardar`
- `Vincular`
- `Consultar`

Se evita utilizar etiquetas genéricas como `Aceptar` o `Enviar` cuando puede proporcionarse una acción más específica.

Por ejemplo:

- `Publicar campaña` en lugar de `Aceptar`.
- `Postular a esta campaña` en lugar de `Continuar`.
- `Registrar incidencia` en lugar de `Enviar`.
- `Guardar perfil` en lugar de `Guardar cambios` cuando el contexto puede especificarse.

##### 3.1.2.3. SEO Tags and Meta Tags

Debido a que la experiencia documentada en esta sección corresponde a una aplicación móvil, la estrategia de descubrimiento se concentra en elementos de **App Store Optimization (ASO)**.

###### App Title

`CollabPro`

El título mantiene exactamente el nombre de la plataforma para facilitar el reconocimiento de marca y mantener consistencia con el producto.

###### App Subtitle

`Colaboraciones claras entre marcas y creadores`

El subtítulo resume la propuesta central de la plataforma indicando los dos actores principales y destacando la estructuración de las colaboraciones.

###### App Keywords

`creadores de contenido, marcas, campañas, influencers, colaboraciones, marketing, pymes, contenido, campañas digitales, influencer marketing`

Estas palabras representan los conceptos principales utilizados por los usuarios al buscar soluciones relacionadas con campañas y colaboraciones entre empresas y creadores.

###### Short Description

`Encuentra creadores, publica campañas y gestiona colaboraciones desde un solo lugar.`

La descripción corta resume las principales capacidades del producto desde la perspectiva de los dos segmentos.

###### App Description

`CollabPro es una plataforma que conecta pequeñas y medianas empresas con creadores de contenido para gestionar colaboraciones de marketing de forma estructurada y trazable.

Las empresas pueden crear campañas, definir objetivos, requisitos, entregables, fechas y compensaciones, revisar postulaciones, seleccionar creadores y validar el cumplimiento de cada colaboración.

Los creadores pueden explorar oportunidades, consultar claramente las condiciones antes de postular, gestionar sus colaboraciones, presentar entregables y consultar el estado de sus compensaciones.

CollabPro también permite mantener un historial de colaboraciones y consultar resultados disponibles, evidencias y mecanismos de atribución asociados a las campañas.`

###### App Category

Categoría propuesta:

`Business`

Como categoría secundaria podría considerarse:

`Productivity`

La categoría Business se relaciona directamente con el modelo B2B de CollabPro y con las actividades comerciales que empresas y creadores gestionan mediante la aplicación.

###### App Author / Developer

`CollabTech`

CollabTech se presenta como la startup responsable del desarrollo de CollabPro.

###### Package Name

`com.example.collabpro`

El prototipo Android utiliza actualmente este identificador de aplicación. Para una publicación productiva deberá sustituirse por un identificador definitivo asociado al dominio o identidad oficial de CollabTech.

##### 3.1.2.4. Searching Systems

El sistema de búsqueda de CollabPro se concentra principalmente en facilitar que los creadores encuentren campañas relevantes sin recorrer manualmente todas las oportunidades disponibles.

###### Búsqueda de campañas

La pantalla **Explorar campañas** proporciona un campo de búsqueda identificado mediante la etiqueta:

`Buscar marca o campaña`

El campo permite utilizar texto relacionado con una campaña o con la empresa que la publica.

La búsqueda reduce dinámicamente el conjunto de resultados y presenta únicamente las campañas relacionadas con los criterios introducidos.

###### Filtros por categoría

Además de la búsqueda textual, se utilizan filtros mediante chips.

Las categorías consideradas actualmente son:

- Todas
- Gastronomía
- Belleza
- Moda

La opción **Todas** elimina la restricción de categoría.

Este sistema permite combinar una búsqueda textual con una clasificación temática.

Por ejemplo:

`"Maki" + Gastronomía`

puede utilizarse para reducir las oportunidades mostradas a campañas relacionadas con gastronomía y cuyo nombre o empresa coincidan con el término introducido.

###### Presentación de resultados

Cada coincidencia se muestra utilizando una tarjeta que contiene:

- nombre de la campaña;
- nombre de la empresa;
- ubicación;
- compensación;
- estado;
- acceso al detalle.

El usuario puede seleccionar una tarjeta para consultar información adicional antes de postular.

###### Búsqueda sin coincidencias

Cuando ningún elemento satisface los criterios, el sistema presenta un estado vacío:

**Sin coincidencias**

acompañado del mensaje:

`Prueba otra palabra o categoría.`

También se proporciona la acción:

`Limpiar filtros`

Esta decisión evita mostrar una vista vacía sin explicación y ofrece una forma inmediata de recuperar el listado original.

###### Criterios futuros compatibles con el dominio

La arquitectura del sistema permite ampliar los criterios de búsqueda de campañas a información ya perteneciente al dominio, como:

- nicho;
- ubicación;
- tipo de compensación;
- estado;
- requisitos del creador;
- fecha límite.

Estos criterios deberán incorporarse progresivamente cuando las historias de usuario correspondientes sean implementadas sobre servicios reales.

![Colors](./assets/C03/StyleGuidelines/searching-system.png)


##### 3.1.2.5. Navigation Systems

CollabPro utiliza un sistema de navegación híbrido compuesto por navegación global mediante una barra inferior y navegación contextual dentro de los diferentes procesos.

###### Navegación global

Una vez que el usuario ingresa al espacio principal de la aplicación, dispone de una barra inferior persistente con cuatro destinos.

Para una **empresa**:

`Inicio | Campañas | Colaborar | Perfil`

Para un **creador**:

`Inicio | Explorar | Colaborar | Perfil`

La estructura mantiene tres posiciones conceptualmente equivalentes:

- Inicio.
- Área principal correspondiente al rol.
- Colaboraciones.
- Perfil.

La segunda opción cambia según la audiencia porque representa la principal tarea asociada a cada segmento.

La empresa necesita administrar campañas, mientras que el creador necesita descubrir oportunidades.

###### Inicio como dashboard

La pantalla Inicio funciona como punto de acceso a las actividades relevantes de cada usuario.

Para una empresa, muestra accesos como:

- Crear campaña.
- Revisar postulaciones.
- Validar entregable.
- Resultados.
- Plan y suscripción.
- Historial.
- Centro de incidencias.
- Medios de pago.

Para un creador, presenta accesos como:

- Explorar campañas.
- Mis postulaciones.
- Acuerdo por confirmar.
- Entregar contenido.
- Compensación.
- Historial.
- Centro de incidencias.
- Medios de pago.

Esta organización evita obligar al usuario a navegar por múltiples niveles para encontrar actividades pendientes.

###### Navegación contextual

Las pantallas secundarias muestran una acción de retorno mediante:

`‹ Volver`

Esta acción permite regresar al contexto anterior sin alterar la navegación principal.

Se utiliza en pantallas como:

- detalle de campaña;
- formulario de postulación;
- postulaciones;
- detalle del postulante;
- colaboración;
- entregables;
- resultados;
- medios de pago.

###### Navegación secuencial

Los procesos dependientes se recorren siguiendo una secuencia lógica.

**Empresa**

`Inicio`
→ `Mis campañas`
→ `Nueva campaña`
→ `Condiciones de campaña`
→ `Campaña publicada`

Posteriormente:

`Campaña`
→ `Postulaciones`
→ `Detalle del postulante`
→ `Confirmar colaboración`
→ `Colaboración`

**Creador**

`Inicio`
→ `Explorar campañas`
→ `Detalle de campaña`
→ `Postular`
→ `Mis postulaciones`

Cuando es seleccionado:

`Postulación seleccionada`
→ `Confirmar colaboración`
→ `Colaboración`
→ `Entregar contenido`

###### Navegación por relaciones entre entidades

CollabPro también permite navegar según las relaciones del dominio.

Por ejemplo:

`Campaña → Postulación → Creador → Colaboración`

y posteriormente:

`Colaboración → Entregable → Revisión → Compensación → Resultados`

Este patrón facilita comprender cómo se relacionan las entidades del negocio y mantiene la trazabilidad de cada colaboración.

###### Historial de navegación

La aplicación mantiene internamente el historial de las rutas recorridas durante la sesión para que la acción `Volver` regrese a la pantalla anterior.

Esto resulta especialmente importante en flujos como:

`Explorar campañas → Campaña → Postular`

porque permite regresar progresivamente sin reiniciar completamente el proceso.

###### Navegación según el rol

Las rutas disponibles también dependen del rol activo.

Una empresa puede acceder directamente a funcionalidades como:

- crear campañas;
- revisar postulantes;
- seleccionar creadores;
- validar entregables;
- consultar resultados.

Un creador puede acceder a:

- buscar campañas;
- postular;
- administrar sus postulaciones;
- entregar evidencias;
- consultar compensaciones.

Esta adaptación permite reutilizar la misma estructura de navegación manteniendo visibles únicamente las acciones relevantes para cada tipo de usuario.

![Colors](./assets/C03/StyleGuidelines/navigation-system.png)


### 3.1.3. Landing Page UI Design

La página de presentación de CollabPro organiza la información según las decisiones que necesita tomar una persona antes de utilizar la plataforma. Primero comunica la propuesta de colaboración entre empresas y creadores, luego explica las funcionalidades y los planes, y finalmente ofrece un espacio de contacto y una presentación del equipo. Esta secuencia permite comprender el servicio antes de evaluar sus condiciones o realizar una consulta.

La navegación global se concentra en una barra superior siempre visible, desde la cual se puede acceder directamente a cada sección. A su vez, la disposición del contenido propone un recorrido secuencial mediante el desplazamiento vertical, sin obligar al visitante a seguirlo. En escritorio se aprovecha el espacio para comparar información y relacionar textos con imágenes. En móvil se conserva el mismo orden de contenidos mediante una distribución en una sola columna.

#### 3.1.3.1. Landing Page Wireframe

Los esquemas representan la estructura de la página antes de aplicar colores, fotografías y detalles del sistema de diseño. Los bloques grises permiten distinguir la jerarquía, la agrupación de contenidos y la ubicación de las acciones. Las imágenes y los videos se representan mediante cuadros con una X.

##### Organización visual y heurísticas aplicadas

**Patrón Z**

En escritorio, la composición de inicio toma como referencia el patrón Z para conectar la marca y la navegación superior con el mensaje principal, las acciones y la imagen de apoyo. La distribución facilita un recorrido desde la zona superior hacia la propuesta de valor y sus botones. En el pie de página, la marca y la descarga ocupan la franja superior, mientras que la información complementaria se distribuye debajo.

**Patrón F**

En los bloques con mayor cantidad de texto, especialmente en funcionalidades y planes, se considera el patrón F como referencia para priorizar los encabezados y el comienzo de cada línea. Los beneficios se presentan mediante títulos breves, listas y grupos separados para que la información principal pueda identificarse sin leer todos los párrafos. Esta organización ayuda a reducir las omisiones que pueden producirse durante una lectura rápida.

| Sección | Decisión de diseño y propósito | Heurísticas aplicadas |
| --- | --- | --- |
| Inicio | El mensaje principal tiene mayor jerarquía que el texto de apoyo y los botones indican la acción disponible. La navegación identifica la sección activa para mantener al visitante orientado. | Visibilidad del estado del sistema y Reconocimiento en lugar de recuerdo |
| Funcionalidades | Los beneficios se agrupan en tarjetas y el proceso se presenta mediante pasos numerados. Esta estructura relaciona la plataforma con acciones conocidas, como crear una campaña, encontrar colaboradores y coordinar el trabajo. | Correspondencia entre el sistema y el mundo real y Reconocimiento en lugar de recuerdo |
| Planes | Las tarjetas mantienen el mismo orden de nombre, descripción, precio, condiciones, beneficios y acción. En escritorio se muestran juntas para facilitar la comparación y en móvil conservan esa secuencia. | Consistencia y estándares y Reconocimiento en lugar de recuerdo |
| Contacto | Los campos tienen etiquetas visibles y permiten distinguir los datos obligatorios de los opcionales. La acción de envío permanece deshabilitada mientras falten datos válidos, lo que evita intentar completar una operación incompleta. | Prevención de errores y Reconocimiento en lugar de recuerdo |
| Sobre nosotros | La descripción del equipo se relaciona con un espacio de video y se limita a la información necesaria para presentar a sus integrantes y su propósito. | Diseño estético y minimalista |
| Pie de página | Los enlaces complementarios y la acción para volver al inicio permiten continuar la navegación sin recorrer nuevamente toda la página. | Control y libertad del usuario y Flexibilidad y eficiencia de uso |

##### Navegador de escritorio

La distribución en columnas permite relacionar textos e imágenes sin extender demasiado la lectura vertical. Las tarjetas de funcionalidades se agrupan en una fila y los planes se presentan en paralelo. La proximidad, los bordes y el espacio entre bloques permiten reconocer qué elementos pertenecen a un mismo grupo.

**Inicio**

![Esquema de inicio para escritorio](./assets/C03/LandingPageUI/wireframes/desktop/01-Inicio-desktop.png)

**Funcionalidades**

La propuesta incluye el espacio “about the product” para complementar la explicación del servicio mediante un video.

![Esquema de funcionalidades para escritorio](./assets/C03/LandingPageUI/wireframes/desktop/02-Funcionalidades-desktop.png)

**Planes**

![Esquema de planes para escritorio](./assets/C03/LandingPageUI/wireframes/desktop/03-Planes-desktop.png)

**Contacto**

![Esquema de contacto para escritorio](./assets/C03/LandingPageUI/wireframes/desktop/04-Contacto-desktop.png)

**Sobre nosotros**

La composición prevista relaciona la presentación del equipo con el espacio “about the team”.

![Esquema de sobre nosotros para escritorio](./assets/C03/LandingPageUI/wireframes/desktop/05-Sobre-nosotros-desktop.png)

**Pie de página**

![Esquema de pie de página para escritorio](./assets/C03/LandingPageUI/wireframes/desktop/06-Pie-de-pagina-desktop.png)

##### Navegador móvil

En móvil, los contenidos se reorganizan en una sola columna. En inicio se presenta primero el mensaje, luego las acciones y finalmente la imagen. Las tarjetas, los pasos del proceso y los planes se apilan conservando su orden, mientras que las etiquetas del formulario permanecen sobre sus campos.

La composición Z de escritorio se adapta a un recorrido vertical. En los bloques de texto se mantiene la prioridad de los encabezados y del comienzo de las líneas. El menú conserva los mismos destinos de navegación y los botones cuentan con espacio suficiente para facilitar la interacción táctil. Estas decisiones mantienen la Consistencia y estándares entre ambas versiones.

**Inicio**

![Esquema de inicio para móvil](./assets/C03/LandingPageUI/wireframes/mobile/01-Inicio-mobile.png)

**Funcionalidades**

![Esquema de funcionalidades para móvil](./assets/C03/LandingPageUI/wireframes/mobile/02-Funcionalidades-mobile.png)

**Planes**

![Esquema de planes para móvil](./assets/C03/LandingPageUI/wireframes/mobile/03-Planes-mobile.png)

**Contacto**

![Esquema de contacto para móvil](./assets/C03/LandingPageUI/wireframes/mobile/04-Contacto-mobile.png)

**Sobre nosotros**

![Esquema de sobre nosotros para móvil](./assets/C03/LandingPageUI/wireframes/mobile/05-Sobre-nosotros-mobile.png)

**Pie de página**

![Esquema de pie de página para móvil](./assets/C03/LandingPageUI/wireframes/mobile/06-Pie-de-pagina-mobile.png)

#### 3.1.3.2. Landing Page Mock-up

Los prototipos visuales aplican el sistema de diseño de CollabPro sobre la estructura definida en los esquemas. El turquesa identifica las acciones principales y los estados activos, los fondos claros separan grupos de contenido y los textos oscuros favorecen la lectura. La tipografía Inter establece una jerarquía común entre títulos, descripciones y controles, con Roboto como alternativa.

Los botones, las tarjetas de esquinas redondeadas y los iconos mantienen un lenguaje visual compartido con la aplicación móvil. Las fotografías muestran situaciones de colaboración y creación de contenido para relacionar la propuesta del servicio con actividades reconocibles.

##### Aplicación del sistema de diseño y las heurísticas

| Sección | Aplicación visual e interacción | Heurísticas aplicadas |
| --- | --- | --- |
| Inicio | El botón principal utiliza un fondo turquesa y la acción secundaria un contorno, lo que permite distinguir su prioridad. La sección activa se identifica mediante color y subrayado, mientras que el selector de idioma muestra la opción elegida. | Visibilidad del estado del sistema y Consistencia y estándares |
| Funcionalidades | Las tarjetas repiten la relación entre icono, título y descripción. La fotografía de creadores y los pasos del proceso conectan los beneficios con actividades familiares para el público objetivo. | Correspondencia entre el sistema y el mundo real y Consistencia y estándares |
| Planes | Los contornos definidos separan las tarjetas y el fondo turquesa destaca el plan de crecimiento. Los precios, la periodicidad y las condiciones se ubican en posiciones equivalentes para facilitar la comparación. El cambio de fondo al pasar el cursor permite reconocer la tarjeta sobre la que se está interactuando. | Consistencia y estándares y Reconocimiento en lugar de recuerdo |
| Contacto | El botón permanece deshabilitado mientras el formulario esté incompleto o contenga datos inválidos. Al completarlo correctamente, se habilita. Durante la simulación se muestra el estado de envío y después una confirmación o un mensaje de error que permite identificar el problema. | Prevención de errores, Visibilidad del estado del sistema y Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de los errores |
| Sobre nosotros | El texto y la portada del video forman un grupo claramente delimitado. El símbolo de reproducción permite reconocer la función del recurso sin añadir instrucciones extensas. | Diseño estético y minimalista y Reconocimiento en lugar de recuerdo |
| Pie de página | El fondo oscuro diferencia el cierre de la página y agrupa los enlaces complementarios. Las acciones de descarga y regreso al inicio conservan símbolos y etiquetas reconocibles. | Consistencia y estándares y Control y libertad del usuario |

##### Navegador de escritorio

**Inicio**

![Prototipo visual de inicio para escritorio](./assets/C03/LandingPageUI/mockups/desktop/01-Inicio-desktop.png)

**Funcionalidades**

![Prototipo visual de funcionalidades para escritorio](./assets/C03/LandingPageUI/mockups/desktop/02-Funcionalidades-desktop.png)

**Planes**

![Prototipo visual de planes para escritorio](./assets/C03/LandingPageUI/mockups/desktop/03-Planes-desktop.png)

**Contacto**

![Prototipo visual de contacto para escritorio](./assets/C03/LandingPageUI/mockups/desktop/04-Contacto-desktop.png)

**Sobre nosotros**

![Prototipo visual de sobre nosotros para escritorio](./assets/C03/LandingPageUI/mockups/desktop/05-Sobre-nosotros-desktop.png)

**Pie de página**

![Prototipo visual de pie de página para escritorio](./assets/C03/LandingPageUI/mockups/desktop/06-Pie-de-pagina-desktop.png)

##### Navegador móvil

La versión móvil mantiene los colores, los iconos y las etiquetas de escritorio para que las acciones sigan siendo reconocibles. Los precios y beneficios conservan su posición dentro de cada tarjeta, lo que facilita compararlos durante el desplazamiento. Los controles se distribuyen con suficiente separación y los botones aprovechan el ancho disponible para facilitar su selección.

**Inicio**

![Prototipo visual de inicio para móvil](./assets/C03/LandingPageUI/mockups/mobile/01-Inicio-mobile.png)

**Funcionalidades**

![Prototipo visual de funcionalidades para móvil](./assets/C03/LandingPageUI/mockups/mobile/02-Funcionalidades-mobile.png)

**Planes**

![Prototipo visual de planes para móvil](./assets/C03/LandingPageUI/mockups/mobile/03-Planes-mobile.png)

**Contacto**

![Prototipo visual de contacto para móvil](./assets/C03/LandingPageUI/mockups/mobile/04-Contacto-mobile.png)

**Sobre nosotros**

![Prototipo visual de sobre nosotros para móvil](./assets/C03/LandingPageUI/mockups/mobile/05-Sobre-nosotros-mobile.png)

**Pie de página**

![Prototipo visual de pie de página para móvil](./assets/C03/LandingPageUI/mockups/mobile/06-Pie-de-pagina-mobile.png)

##### Diseño inclusivo e interacciones

La identificación de la sección activa combina color y subrayado para evitar que la orientación dependa únicamente del color. Los iconos se acompañan de etiquetas cuando es necesario explicar una acción y los campos del formulario mantienen sus nombres visibles. La selección persistente entre español e inglés, las descripciones alternativas de las imágenes y el foco visible durante la navegación por teclado amplían las posibilidades de uso.

Las animaciones de entrada presentan la barra superior y los contenidos de forma progresiva. Cada bloque se anima únicamente la primera vez que aparece y se respeta la preferencia de movimiento reducido para mantener una experiencia cómoda.

Los espacios “about the product” y “about the team” forman parte del diseño previsto y aparecen en los esquemas y prototipos visuales. Las portadas son ilustrativas y su incorporación al sitio queda pendiente de los enlaces definitivos.

### 3.1.4. Mobile Applications UX/UI Design

#### 3.1.4.1. Mobile Applications Wireframes

Se muestran la distribución del contenido y los controles de cada pantalla mediante textos negros y componentes en escala de grises. 
La información relacionada se reúne en tarjetas, mientras que los títulos y el espacio entre bloques permiten distinguir los grupos y reconocer su importancia.
Cada Wireflow esta organizado por User Goal.
Dentro de esta organización, los campos indican qué datos se solicitan y los botones permiten identificar la acción principal.

[Enlace de figma](https://www.figma.com/design/dWJkpGdFOOHLbDqiLJ9oj1/CollabPro?node-id=0-1&t=p3jf9OlwKmfJjX7y-1)

##### Organización visual y heurísticas aplicadas

**Patrón F**

En los listados y las pantallas de detalle, el patrón F se considera como referencia para ubicar los títulos y los datos relevantes al comienzo de cada bloque. Esta disposición facilita localizar nombres, estados y fechas durante una lectura rápida, mientras que las tarjetas y los subtítulos permiten reconocer dónde continúa la información.

**Recorrido vertical**

El contenido se distribuye en una sola columna, desde el contexto de la pantalla hasta la acción principal. Este recorrido se complementa con la organización descrita para los listados y detalles, mientras que los formularios y las explicaciones del servicio utilizan grupos de campos y pasos numerados para orientar al usuario.

| **Pantallas** | **Decisión de diseño y propósito** | **Heurísticas aplicadas** |
| --- | --- | --- |
| Presentación y explicación del servicio | Las tarjetas separan los públicos y los pasos numerados explican las tareas de cada rol antes del registro. | Correspondencia entre el sistema y el mundo real y ayuda y documentación. |
| Registro, acceso y recuperación | Los campos se agrupan antes de la acción principal. Volver, Ya tengo cuenta y Olvidé mi contraseña ofrecen alternativas visibles según el contexto. | Reconocimiento en lugar de recuerdo y control y libertad del usuario. |
| Inicio de empresa y creador | El resumen precede a las actividades pendientes. Las tarjetas reúnen accesos frecuentes para reducir la búsqueda entre niveles. | Visibilidad del estado del sistema y flexibilidad y eficiencia de uso. |
| Campañas y colaboraciones | Las tarjetas repiten nombre, estado, fecha y acceso al detalle. Esta organización por entidad y estado facilita identificar actividades relevantes. | Consistencia y estándares y visibilidad del estado del sistema. |
| Creación de campaña | Los dos pasos separan información general y condiciones. El formato de fecha y los campos de requisitos, entregables y compensación explicitan los datos necesarios. | Prevención de errores y reconocimiento en lugar de recuerdo. |
| Exploración y detalle de campaña | La búsqueda y las categorías preceden al listado. Las condiciones se muestran antes de postular para que la decisión tenga un contexto claro. | Flexibilidad y eficiencia de uso y prevención de errores. |
| Detalle de colaboración | Seguimiento reúne los estados del acuerdo y la entrega. Próxima acción explica la tarea pendiente junto a su botón. | Visibilidad del estado del sistema y ayuda y documentación. |
| Perfiles y redes sociales | Los datos se agrupan según el rol. Las redes muestran su estado y explican la autorización necesaria antes de vincular una cuenta. | Reconocimiento en lugar de recuerdo y visibilidad del estado del sistema. |

##### Diseño inclusivo

La interfaz combina iconos con etiquetas y presenta los estados mediante palabras para que las personas puedan comprender las opciones sin depender únicamente de símbolos o colores. Este criterio también se aplica a los formularios, donde las indicaciones relacionan cada campo con el dato solicitado. A su vez, los botones describen la acción disponible y mantienen una separación que facilita distinguirlos, favoreciendo la comprensión de usuarios con diferentes niveles de experiencia digital.

##### Presentación y acceso

**Presentación**

![Wireframe de presentación de CollabPro](./assets/C03/MobileApplicationsUI/wireframes/1_Presentacion.png)

**Descubrimiento para empresas**

![Wireframe de descubrimiento para empresas](./assets/C03/MobileApplicationsUI/wireframes/2_Descubrir_Empresa.png)

**Cómo funciona para empresas**

![Wireframe de cómo funciona para empresas](./assets/C03/MobileApplicationsUI/wireframes/3_Como_Funciona_Empresa.png)

**Descubrimiento para creadores**

![Wireframe de descubrimiento para creadores](./assets/C03/MobileApplicationsUI/wireframes/4_Descubrir_Creador.png)

**Cómo funciona para creadores**

![Wireframe de cómo funciona para creadores](./assets/C03/MobileApplicationsUI/wireframes/5_Como_Funciona_Creador.png)

**Selección del tipo de cuenta**

![Wireframe de selección del tipo de cuenta](./assets/C03/MobileApplicationsUI/wireframes/6_Seleccion_Tipo_de_Cuenta.png)

**Creación de cuenta de empresa**

![Wireframe de creación de cuenta de empresa](./assets/C03/MobileApplicationsUI/wireframes/7_Crear_Cuenta_Empresa.png)

**Creación de cuenta de creador**

![Wireframe de creación de cuenta de creador](./assets/C03/MobileApplicationsUI/wireframes/8_Crear_Cuenta_Creador.png)

**Inicio de sesión**

![Wireframe de inicio de sesión](./assets/C03/MobileApplicationsUI/wireframes/9_Iniciar_Sesion.png)

**Recuperación del acceso**

![Wireframe de recuperación del acceso](./assets/C03/MobileApplicationsUI/wireframes/10_Recuperar_Acceso.png)

##### Espacio de empresa

**Inicio de empresa**

![Wireframe del inicio de empresa](./assets/C03/MobileApplicationsUI/wireframes/11_Inicio_Empresa.png)

**Opciones complementarias del inicio de empresa**

Esta captura corresponde a la continuación del contenido de Inicio.

![Wireframe de opciones complementarias del inicio de empresa](./assets/C03/MobileApplicationsUI/wireframes/12_Inicio_Empresa_Opciones.png)

**Mis campañas**

![Wireframe de mis campañas de empresa](./assets/C03/MobileApplicationsUI/wireframes/13_Mis_Campanas_Empresa.png)

**Colaboraciones de empresa**

![Wireframe de colaboraciones de empresa](./assets/C03/MobileApplicationsUI/wireframes/14_Colaboraciones_Empresa.png)

**Perfil de empresa**

![Wireframe del perfil de empresa](./assets/C03/MobileApplicationsUI/wireframes/15_Perfil_Empresa.png)

**Nueva campaña**

![Wireframe del primer paso de creación de campaña](./assets/C03/MobileApplicationsUI/wireframes/16_Nueva_Campana.png)

**Condiciones de campaña**

![Wireframe de condiciones de campaña](./assets/C03/MobileApplicationsUI/wireframes/17_Condiciones_de_Campana.png)

##### Espacio de creador

**Inicio de creador**

![Wireframe del inicio de creador](./assets/C03/MobileApplicationsUI/wireframes/18_Inicio_Creador.png)

**Opciones complementarias del inicio de creador**

Esta captura corresponde a la continuación del contenido de Inicio.

![Wireframe de opciones complementarias del inicio de creador](./assets/C03/MobileApplicationsUI/wireframes/19_Inicio_Creador_Opciones.png)

**Exploración de campañas**

![Wireframe de exploración de campañas para creadores](./assets/C03/MobileApplicationsUI/wireframes/20_Explorar_Campanas_Creador.png)

**Detalle de campaña**

![Wireframe del detalle de campaña](./assets/C03/MobileApplicationsUI/wireframes/21_Detalle_de_Campana.png)

**Colaboraciones de creador**

![Wireframe de colaboraciones de creador](./assets/C03/MobileApplicationsUI/wireframes/22_Colaboraciones_Creador.png)

**Detalle de colaboración**

![Wireframe del detalle de colaboración](./assets/C03/MobileApplicationsUI/wireframes/23_Detalle_de_Colaboracion.png)

**Perfil de creador**

![Wireframe del perfil de creador](./assets/C03/MobileApplicationsUI/wireframes/24_Perfil_Creador.png)

**Redes sociales del creador**

![Wireframe de redes sociales del creador](./assets/C03/MobileApplicationsUI/wireframes/25_Redes_Sociales_Creador.png)

#### 3.1.4.2. Mobile Applications Wireflow Diagrams

##### User Goal 1 - Configurar identidad comercial
![UG01](assets/C03/MobileApplicationsUI/Wireflow/Wireflow1-UG01.png)

##### User Goal 2 - Crear y validar perfil profesional
![UG02](assets/C03/MobileApplicationsUI/Wireflow/Wireflow2-UG02.png)

##### User Goal 3 - Acceder a la plataforma de forma segura
![UG03](assets/C03/MobileApplicationsUI/Wireflow/Wireflow3-UG03.png)

##### User Goal 4 - Publicar oportunidad de colaboración
![UG04](assets/C03/MobileApplicationsUI/Wireflow/Wireflow4-UG04.png)

##### User Goal 5 - Encontrar y asegurar colaboraciones
![UG05](assets/C03/MobileApplicationsUI/Wireflow/Wireflow5-UG05.png)

##### User Goal 6 - Contratar al creador ideal
![UG06](assets/C03/MobileApplicationsUI/Wireflow/Wireflow6-UG06.png)

##### User Goal 7 - Demostrar trabajo y gestión financiera
![UG07](assets/C03/MobileApplicationsUI/Wireflow/Wireflow7-UG07.png)

##### User Goal 8 - Controlar calidad del contenido
![UG08](assets/C03/MobileApplicationsUI/Wireflow/Wireflow8-UG08.png)

##### User Goal 9 - Resolver conflictos comerciales
![UG09](assets/C03/MobileApplicationsUI/Wireflow/Wireflow9-UG09.png)

##### User Goal 10 - Configurar operaciones financieras
![UG10](assets/C03/MobileApplicationsUI/Wireflow/Wireflow10-UG10.png)

##### User Goal 11 - Desbloquear herramientas premium
![UG11](assets/C03/MobileApplicationsUI/Wireflow/Wireflow11-UG11.png)

##### User Goal 12 - Evaluar el ROI y mantener historial
![UG12](assets/C03/MobileApplicationsUI/Wireflow/Wireflow12-UG12.png)

#### 3.1.4.3. Mobile Applications Mock-ups

Los mockups presentan la apariencia visual de la aplicación al aplicar el sistema de diseño de CollabPro sobre la distribución definida en los wireframes. Los botones con relleno destacan las acciones principales y los botones con contorno identifican las alternativas. Este tratamiento se combina con tarjetas que agrupan la información de campañas, colaboraciones y perfiles, manteniendo una organización visual consistente entre pantallas.

[Enlace del figma](https://www.figma.com/design/dWJkpGdFOOHLbDqiLJ9oj1/CollabPro?node-id=0-1&t=p3jf9OlwKmfJjX7y-1)

##### Aplicación del sistema de diseño y las heurísticas

| **Pantallas** | **Aplicación visual y propósito** | **Heurísticas aplicadas** |
| --- | --- | --- |
| Presentación y explicación del servicio | La marca mantiene su representación habitual. Las tarjetas distinguen los roles y los botones principales destacan las acciones para conocer el servicio o comenzar. | Consistencia y estándares y correspondencia entre el sistema y el mundo real. |
| Registro, acceso y recuperación | Los campos conservan forma y separación. El botón con relleno distingue la acción principal de los enlaces y botones con contorno. | Consistencia y estándares y reconocimiento en lugar de recuerdo. |
| Inicio de ambos roles | Las cifras y los títulos destacan el resumen. Las etiquetas sobre fondos claros contextualizan las actividades pendientes y la barra inferior identifica la sección activa. | Visibilidad del estado del sistema y flexibilidad y eficiencia de uso. |
| Campañas y colaboraciones | Las tarjetas repiten la jerarquía de título, estado, datos y enlace. Los estados escritos conservan su significado sin depender del color. | Consistencia y estándares y visibilidad del estado del sistema. |
| Creación de campaña | El indicador de paso utiliza el color de marca. Los chips distinguen la categoría elegida y los campos mantienen visibles las indicaciones necesarias antes de publicar. | Reconocimiento en lugar de recuerdo y prevención de errores. |
| Exploración y detalle de campaña | Los filtros distinguen la selección y las tarjetas separan información y condiciones. Postular a esta campaña se destaca después de los compromisos. | Reconocimiento en lugar de recuerdo y prevención de errores. |
| Detalle de colaboración | Los valores del seguimiento destacan frente a sus etiquetas. Entregar contenido y evidencia tiene mayor jerarquía que las consultas de compensación e incidencias. | Visibilidad del estado del sistema y diseño estético y minimalista. |
| Perfiles y redes sociales | Las etiquetas contextualizan los valores. Guardar perfil y Vincular Instagram destacan como acciones principales, y Sin vincular comunica el estado de la red. | Consistencia y estándares y visibilidad del estado del sistema. |

##### Diseño inclusivo

Los textos oscuros sobre superficies claras y las diferencias de tamaño y peso favorecen la lectura. La navegación mantiene iconos con etiquetas y las condiciones se expresan mediante textos, fechas y valores. El color refuerza la información escrita. Las explicaciones breves y los controles separados conservan los criterios inclusivos de los esquemas.

##### Presentación y acceso

**Presentación**

![Mockup de presentación de CollabPro](./assets/C03/MobileApplicationsUI/mockups/1_Presentacion.png)

**Descubrimiento para empresas**

![Mockup de descubrimiento para empresas](./assets/C03/MobileApplicationsUI/mockups/2_Descubrir_Empresa.png)

**Cómo funciona para empresas**

![Mockup de cómo funciona para empresas](./assets/C03/MobileApplicationsUI/mockups/3_Como_Funciona_Empresa.png)

**Descubrimiento para creadores**

![Mockup de descubrimiento para creadores](./assets/C03/MobileApplicationsUI/mockups/4_Descubrir_Creador.png)

**Cómo funciona para creadores**

![Mockup de cómo funciona para creadores](./assets/C03/MobileApplicationsUI/mockups/5_Como_Funciona_Creador.png)

**Selección del tipo de cuenta**

![Mockup de selección del tipo de cuenta](./assets/C03/MobileApplicationsUI/mockups/6_Seleccion_Tipo_de_Cuenta.png)

**Creación de cuenta de empresa**

![Mockup de creación de cuenta de empresa](./assets/C03/MobileApplicationsUI/mockups/7_Crear_Cuenta_Empresa.png)

**Creación de cuenta de creador**

![Mockup de creación de cuenta de creador](./assets/C03/MobileApplicationsUI/mockups/8_Crear_Cuenta_Creador.png)

**Inicio de sesión**

![Mockup de inicio de sesión](./assets/C03/MobileApplicationsUI/mockups/9_Iniciar_Sesion.png)

**Recuperación del acceso**

![Mockup de recuperación del acceso](./assets/C03/MobileApplicationsUI/mockups/10_Recuperar_Acceso.png)

##### Espacio de empresa

**Inicio de empresa**

![Mockup del inicio de empresa](./assets/C03/MobileApplicationsUI/mockups/11_Inicio_Empresa.png)

**Opciones complementarias del inicio de empresa**

Esta captura corresponde a la continuación del contenido de Inicio.

![Mockup de opciones complementarias del inicio de empresa](./assets/C03/MobileApplicationsUI/mockups/12_Inicio_Empresa_Opciones.png)

**Mis campañas**

![Mockup de mis campañas de empresa](./assets/C03/MobileApplicationsUI/mockups/13_Mis_Campanas_Empresa.png)

**Colaboraciones de empresa**

![Mockup de colaboraciones de empresa](./assets/C03/MobileApplicationsUI/mockups/14_Colaboraciones_Empresa.png)

**Perfil de empresa**

![Mockup del perfil de empresa](./assets/C03/MobileApplicationsUI/mockups/15_Perfil_Empresa.png)

**Nueva campaña**

![Mockup del primer paso de creación de campaña](./assets/C03/MobileApplicationsUI/mockups/16_Nueva_Campana.png)

**Condiciones de campaña**

![Mockup de condiciones de campaña](./assets/C03/MobileApplicationsUI/mockups/17_Condiciones_de_Campana.png)

##### Espacio de creador

**Inicio de creador**

![Mockup del inicio de creador](./assets/C03/MobileApplicationsUI/mockups/18_Inicio_Creador.png)

**Opciones complementarias del inicio de creador**

Esta captura corresponde a la continuación del contenido de Inicio.

![Mockup de opciones complementarias del inicio de creador](./assets/C03/MobileApplicationsUI/mockups/19_Inicio_Creador_Opciones.png)

**Exploración de campañas**

![Mockup de exploración de campañas para creadores](./assets/C03/MobileApplicationsUI/mockups/20_Explorar_Campanas_Creador.png)

**Detalle de campaña**

![Mockup del detalle de campaña](./assets/C03/MobileApplicationsUI/mockups/21_Detalle_de_Campana.png)

**Colaboraciones de creador**

![Mockup de colaboraciones de creador](./assets/C03/MobileApplicationsUI/mockups/22_Colaboraciones_Creador.png)

**Detalle de colaboración**

![Mockup del detalle de colaboración](./assets/C03/MobileApplicationsUI/mockups/23_Detalle_de_Colaboracion.png)

**Perfil de creador**

![Mockup del perfil de creador](./assets/C03/MobileApplicationsUI/mockups/24_Perfil_Creador.png)

**Redes sociales del creador**

![Mockup de redes sociales del creador](./assets/C03/MobileApplicationsUI/mockups/25_Redes_Sociales_Creador.png)

#### 3.1.4.4. Mobile Applications User Flow Diagrams

##### User Goal 01 - Registrar la empresa y configurar el perfil para atraer creadores

![UG01](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow01-UG01.png)

##### User Goal 02 - Crear una cuenta, definir el nicho profesional y vincular redes sociales

![UG02](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow02-UG02.png)

##### User Goal 03 - Iniciar sesión o recuperar el acceso a la cuenta.

![UG03](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow03-UG03.png)

##### User Goal 04 - Crear y publicar una campaña con condiciones y compensación definidas

![UG04](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow04-UG04.png)

##### User Goal 05 - Buscar campañas, revisar sus condiciones y postularse

![UG05](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow05-UG05.png)

##### User Goal 06 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG06](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow06-UG06.png)

##### User Goal 07 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG07](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow07-UG07.png)

##### User Goal 08 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG08](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow08-UG08.png)

##### User Goal 09 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG09](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow09-UG09.png)

##### User Goal 010 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG10](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow10-UG10.png)

##### User Goal 11 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG011](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow11-UG11.png)

##### User Goal 12 - Revisar postulantes, elegir un creador y formalizar la colaboración

![UG12](./assets/C03/MobileApplicationsUI/UserFlow/UserFlow12-UG12.png)

#### 3.1.4.5. Mobile Applications Prototyping  

##### Pymes  

El prototipado de la App Pyme busca simular la experiencia de los representantes de pequeñas y medianas empresas al utilizar CollabPro. 
Mediante prototipos interactivos en Figma, se representan las principales pantallas, la navegación y las interacciones definidas en los User Flows, considerando tanto los recorridos esperados como los estados alternativos.
![Screenshot Prototyping](./assets/C03/MobileApplicationsUI/Prototyping/pymes.png)
[Video del prototyping para pymes en CollabPro Figma](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c803_upc_edu_pe/IQBQXGjIXGrmQ75axqsoKAByAQMhLumSaWrarDadO4NNQAw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=48mNJk)  

##### Creador  

El prototipado de la App Creador tiene como objetivo simular la experiencia de los creadores de contenido dentro de CollabPro. 
A través de prototipos interactivos en Figma, se representan las pantallas, la navegación y las interacciones correspondientes a los User Flows, incluyendo los recorridos principales y sus alternativas.
![Screenshot Prototyping](./assets/C03/MobileApplicationsUI/Prototyping/creador.png)
[Vidoe del prototyping para creador en CollabPro Figma](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221c803_upc_edu_pe/IQCb-mwYqjFPR5tUyzRrSetFAaDYayt0aYLJoRZPxJf2BIc?e=3cdeb3&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

## Capítulo IV: Product Implementation & Validation

La solución definida para CollabPro comprende una landing page web, servicios REST desarrollados con Spring Boot y Java, persistencia relacional MySQL y almacenamiento de evidencias en Firebase Cloud Storage. El diseño también considera una aplicación nativa Android en Kotlin y una aplicación móvil multiplataforma en Flutter. Esta sección documenta cómo preparar el entorno, organizar los cambios, aplicar convenciones comunes y reproducir el despliegue.

### 4.1. Software Configuration Management

La configuración de gestión de software busca que todos los integrantes puedan preparar un entorno equivalente, revisar los cambios antes de integrarlos y reconstruir los productos desde código versionado. Se propone mantener configuraciones y documentación no confidenciales en GitHub, automatizar validaciones en cada pull request y almacenar claves, contraseñas y tokens únicamente como secretos del entorno de ejecución. No se deben subir credenciales, archivos locales de configuración ni datos reales de usuarios al repositorio.

#### 4.1.1. Software Development Environment Configuration

| Actividad / producto                    | Herramienta propuesta                                                                   | Propósito y configuración del proyecto                                                                                                                                                                                                                  |
| :-------------------------------------- | :-------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Gestión de trabajo y código             | Git y GitHub                                                                            | Control de versiones, incidencias, pull requests, revisión de código, tablero de trabajo y documentación compartida. El repositorio actualmente identificado es el del informe; los repositorios de los productos se detallan en 4.1.2.                 |
| Diseño de producto y colaboración UX/UI | Figma                                                                                   | Prototipos, componentes visuales y entrega de especificaciones para landing y aplicaciones móviles; enlazar los archivos desde las tareas o documentación del repositorio.                                                                              |
| Landing page (HTML5, CSS3, JavaScript)  | Visual Studio Code y navegador Chromium                                                 | Edición, vista previa local y revisión adaptable en tamaños de escritorio y móvil. Mantener instrucciones de ejecución en el README del producto.                                                                                                       |
| Servicios REST (Java, Spring Boot)      | JDK, IntelliJ IDEA o VS Code, Maven y Spring Boot                                       | Desarrollo y ejecución local de la API; configurar dependencias y tareas de compilación en `pom.xml` y fijar la versión de Java compatible en el proyecto. La base local MySQL debe iniciarse con una configuración documentada sin contraseñas reales. |
| Aplicación nativa Android (Kotlin)      | Android Studio, Android SDK y Gradle                                                    | Edición, compilación y prueba en emulador/dispositivo. Versiones de SDK, plugin y Gradle se fijan en los archivos Gradle del repositorio.                                                                                                               |
| Aplicación multiplataforma (Flutter)    | Flutter SDK, Dart y Android Studio o VS Code                                            | Desarrollo y ejecución de la app multiplataforma; fijar dependencias y restricciones en `pubspec.yaml` y el canal/versión del SDK en la documentación del proyecto.                                                                                     |
| Base de datos relacional                | MySQL Server y MySQL Workbench (opcional)                                               | Desarrollo local, inspección de datos y ejecución controlada de migraciones. Los cambios del esquema se guardan como scripts versionados o migraciones del backend; nunca se distribuyen copias de datos personales reales.                             |
| Evidencias y objetos                    | Firebase Console / Firebase Cloud Storage                                               | Configuración del bucket de almacenamiento de evidencias. Las credenciales de servicio se guardan en secretos del entorno, con acceso mínimo necesario; no se incluyen en el cliente móvil ni en el repositorio.                                        |
| Pruebas y calidad                       | JUnit (backend), pruebas de Flutter/Android y Postman para pruebas exploratorias de API | Mantener pruebas unitarias junto al código y colecciones/scripts de pruebas de integración versionados. Los casos de aceptación pueden documentarse en Gherkin cuando correspondan a historias de usuario.                                              |
| Integración continua y documentación    | GitHub Actions, Markdown y OpenAPI                                                      | Ejecutar compilación y pruebas al abrir/actualizar pull requests; publicar artefactos solo desde ramas o etiquetas autorizadas. Documentar endpoints con OpenAPI/Swagger en el servicio REST.                                                           |

Cada producto debe incluir un `README.md` con prerrequisitos, versiones requeridas, configuración local, comandos de ejecución y pruebas, variables de entorno de ejemplo sin valores secretos y procedimiento de compilación. Se recomienda agregar `.editorconfig` y archivos de formato/lint apropiados por lenguaje para reducir diferencias entre IDEs.

#### 4.1.2. Source Code Management

| Producto                   | Repositorio en la organización `AppMoviles2026` | Contenido mínimo                                                                                                   |
| :------------------------- | :---------------------------------------------- | :----------------------------------------------------------------------------------------------------------------- |
| Landing page               | `collabpro-landing` (URL pendiente de creación) | Código HTML/CSS/JavaScript, assets optimizados e instrucciones de publicación.                                     |
| RESTful Web Services       | `collabpro-api` (URL pendiente de creación)     | Proyecto Spring Boot, migraciones/configuración no secreta, pruebas unitarias y pruebas de integración/aceptación. |
| Aplicación nativa Android  | `collabpro-android` (URL pendiente de creación) | Proyecto Kotlin/Android, pruebas y configuración de compilación.                                                   |
| Aplicación multiplataforma | `collabpro-mobile` (URL pendiente de creación)  | Proyecto Flutter/Dart y pruebas para las plataformas acordadas.                                                    |

Se aplicará GitFlow de manera ligera en cada repositorio:

| Rama                                          | Uso y regla                                                                                                                                                                                                          |
| :-------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `main`                                        | Código estable y versiones publicadas. Protegerla para impedir pushes directos y exigir pull request con revisión y checks aprobados.                                                                                |
| `develop`                                     | Integración del trabajo aceptado para la siguiente versión. Las features y fixes normales parten de aquí y vuelven mediante pull request.                                                                            |
| `feature/<id>-<short-name>`                   | Una rama por funcionalidad, por ejemplo `feature/CP-24-campaign-brief`; usar identificador de backlog cuando exista y nombre breve en inglés con kebab-case.                                                         |
| `release/<major>.<minor>.<patch>`             | Preparación de una versión candidata desde `develop`; solo se permiten correcciones de estabilización, documentación y metadatos. Tras aprobar pruebas, se integra a `main`, se etiqueta y se reintegra a `develop`. |
| `hotfix/<major>.<minor>.<patch>-<short-name>` | Corrección urgente que parte de `main`; una vez verificada, se integra a `main` y `develop` (o a la release activa) para evitar regresiones.                                                                         |

Los cambios se proponen mediante pull requests pequeños, con descripción del problema, alcance, pruebas ejecutadas y capturas cuando afecten la interfaz. La revisión debe comprobar criterios de aceptación, pruebas, convenciones y ausencia de secretos. Los conflictos se resuelven en la rama de trabajo y no mediante edición directa de `main`.

Los mensajes seguirán Conventional Commits en inglés: `feat(campaign): add campaign brief`, `fix(payment): validate compensation status`, `test(api): cover creator application`, `docs(readme): explain local setup`. Se utilizarán tipos como `feat`, `fix`, `docs`, `test`, `refactor`, `build` y `chore`; un cambio incompatible se indica con `!` o con un pie `BREAKING CHANGE:`. Los tags usarán Semantic Versioning (`MAJOR.MINOR.PATCH`): `MAJOR` para incompatibilidad, `MINOR` para capacidades compatibles nuevas y `PATCH` para correcciones compatibles. Mientras el producto esté en desarrollo inicial puede publicarse como `0.x.y`; no se deben reutilizar ni modificar tags publicados.

#### 4.1.3. Source Code Style Guide & Conventions

La nomenclatura del código, nombres de ramas, mensajes de commit, contratos API, comentarios técnicos y documentación de desarrollo será en inglés. El contenido dirigido a usuarios puede mostrarse en español, de acuerdo con el público objetivo. Se mantendrán nombres descriptivos, funciones acotadas, validación en los límites del sistema y separación de responsabilidades coherente con los Bounded Contexts ya definidos.

| Tecnología / artefacto | Convenciones acordadas                                                                                                                                                                                                                                                           |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| HTML5                  | Elementos semánticos, atributos entre comillas, minúsculas en nombres de elementos/atributos, estructura accesible con etiquetas asociadas a controles y jerarquía de encabezados. Evitar estilos y scripts inline salvo justificación.                                          |
| CSS3                   | Selectores y clases en kebab-case, tokens reutilizables para color/espaciado/tipografía, diseño adaptable y estados visibles de foco. Agrupar reglas por componente y evitar selectores excesivamente específicos.                                                               |
| JavaScript             | `camelCase` para variables/funciones, `PascalCase` para clases, `UPPER_SNAKE_CASE` solo para constantes globales, módulos pequeños, `const` por defecto y errores tratados explícitamente.                                                                                       |
| Java / Spring Boot     | Seguir Google Java Style Guide; paquetes en minúsculas, clases `UpperCamelCase`, métodos y variables `lowerCamelCase`, constantes `UPPER_SNAKE_CASE`; separar controladores, aplicación, dominio e infraestructura y no exponer entidades de persistencia directamente como API. |
| Kotlin / Android       | Seguir Kotlin Coding Conventions y formato oficial del IDE; paquetes en minúsculas, tipos `UpperCamelCase`, funciones/propiedades `lowerCamelCase`, preferir `val` e inmutabilidad y documentar APIs públicas.                                                                   |
| Dart / Flutter         | Seguir Effective Dart; archivos `lowercase_with_underscores.dart`, tipos `UpperCamelCase` y miembros y constantes `lowerCamelCase`; widgets pequeños y estado separado de presentación cuando sea apropiado.                                                                     |
| Gherkin (`.feature`)   | Escenarios en lenguaje de negocio, con `Given/When/Then` en inglés; cada escenario prueba un comportamiento, pasos concretos y sin lógica de implementación. Evitar escenarios largos o duplicados.                                                                              |
| JSON, SQL y API        | Contratos y propiedades públicas en inglés; JSON en `camelCase`, tablas/columnas en `snake_case` de forma consistente; documentar endpoint, payload, errores y autenticación en OpenAPI. No guardar secretos ni datos productivos en ejemplos.                                   |

Se recomienda aplicar formato automático antes de integrar cambios y ejecutar validadores/lint en CI: formatter/linter del frontend, formatter de Java, Kotlin formatter/inspections, `dart format`/`flutter analyze` y comprobación de los casos Gherkin. Los criterios de formato deberán quedar configurados en el repositorio, en vez de depender solo de preferencias personales del IDE.

#### 4.1.4. Software Deployment Configuration

| Componente             | Destino de despliegue                                                                                                                | Configuración                                                                                                                                                                                                  |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Landing page           | Hosting estático con HTTPS (GitHub Pages)                                                                                            | Compilar/minificar assets si corresponde, publicar solo desde `main` o una etiqueta de release, verificar rutas, formulario/enlaces y renderizado móvil. La decisión del proveedor queda pendiente.            |
| RESTful Web Services   | Azure Virtual Machine (despliegue verificado para Sprint 1); Azure App Service permanece como alternativa propuesta                    | API disponible en `http://40.75.23.68:8081`. La ruta pública utiliza HTTP; para un entorno productivo se debe publicar detrás de HTTPS. La evidencia de Sprint Review registra el estado observado en la VM.  |
| MySQL                  | Azure Database for MySQL (destino propuesto; ubicación del entorno desplegado pendiente de confirmar)                                   | Crear esquema mediante migraciones versionadas, restringir red/usuarios, habilitar respaldos y separar credenciales por ambiente. Nunca exponer el puerto de base de datos a Internet público.                 |
| Apps Android y Flutter | Distribución de prueba mediante Firebase App Distribution o canal interno equivalente; publicación final según plataformas acordadas | Generar builds firmados desde pipeline/entorno controlado. Llaves de firma y credenciales de publicación se guardan fuera del repositorio. Probar instalación, permisos y URL del backend antes de distribuir. |

### 4.2. Landing Page & Mobile Application Implementation

#### 4.2.1. Sprint 1

##### 4.2.1.1. Sprint Planning 1

El Sprint Planning 1 tiene como objetivo definir el alcance de la primera iteración de desarrollo de CollabPro, considerando las primeras 18 User Stories priorizadas en el Product Backlog. El Sprint comprende tanto la implementación de la Landing Page como el avance de las principales capacidades del backend relacionadas con identidad, perfiles, campañas y postulaciones.

Durante la planificación se revisaron los User Stories asignados al Sprint 1 y su contribución a una primera versión funcional de CollabPro. El alcance busca permitir que empresas y creadores conozcan la propuesta de valor de la plataforma y, al mismo tiempo, establecer los servicios necesarios para soportar registro, autenticación, gestión de perfiles, campañas y postulaciones.

| Sprint # | Sprint 1 |
| --- | --- |
| **Sprint Planning Background** | El Sprint 1 corresponde a la primera iteración de desarrollo de CollabPro. El equipo priorizó las primeras 18 User Stories del Product Backlog, incluyendo funcionalidades de la Landing Page y capacidades iniciales del backend correspondientes a identidad, perfiles, campañas y postulaciones. |
| **Date** | 2026-10-09 |
| **Time** | 09:00 AM |
| **Location** | Microsoft Teams |
| **Prepared By** | Renzo Zamir Revilla Quispe |
| **Attendees (to planning meeting)** | Todo el equipo |
| **Sprint 1 Goal** | Nuestro enfoque es desarrollar una primera versión funcional de CollabPro que permita presentar claramente la propuesta de valor a empresas y creadores y establecer las principales capacidades de backend requeridas para iniciar su interacción con la plataforma. Esto será validado cuando los usuarios puedan conocer el funcionamiento de CollabPro y se encuentren disponibles las capacidades correspondientes a registro, autenticación, perfil, búsqueda y consulta de campañas, creación y definición de campañas y postulación a oportunidades de colaboración. |
| **Sprint 1 Velocity** | 44 Story Points |
| **Sum of Story Points** | 44 Story Points |

##### 4.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1 el trabajo se distribuyó considerando los principales aspectos necesarios para construir la primera versión funcional de la experiencia móvil de CollabPro. Para cada aspecto se identifica un **Leader (L)** como responsable principal de conducir y consolidar el trabajo, mientras que los demás miembros que participaron como apoyo se identifican como **Collaborators (C)**.

La distribución no implica exclusividad sobre la implementación, ya que todos los miembros del equipo participan en el desarrollo y revisión del producto. El objetivo de esta clasificación es evidenciar la responsabilidad principal asumida por cada integrante durante el Sprint.

| Team Member (Last Name, First Name) | Mobile Architecture & Domain Integration Leader (L) / Collaborator (C) | Campaign & Collaboration Implementation Leader (L) / Collaborator (C) | Mobile UX/UI & Design System Leader (L) / Collaborator (C) | Navigation & Interaction Flows Leader (L) / Collaborator (C) | Testing & Quality Assurance Leader (L) / Collaborator (C) |
| ----------------------------------- | :--------------------------------------------------------------------: | :-------------------------------------------------------------------: | :--------------------------------------------------------: | :----------------------------------------------------------: | :-------------------------------------------------------: |
| Quispe Serrano, Julio Frank         |                                 C                                  |                                   C                                   |                             C                              |                              C                               |                             **L**                             |
| Revilla Quispe, Renzo Zamir         |                                   C                                    |                                 **L**                                 |                             C                              |                              C                               |                             C                             |
| Vallejo Trujillo, Fabio Cesar       |                                   C                                    |                                   C                                   |                           **L**                            |                              C                               |                             C                             |
| Garcia Villanueva, Leonardo Rafael  |                                   C                                    |                                   C                                   |                             C                              |                            **L**                             |                             C                             |
| Rocca Leon, Anhelo Rodrigo          |                                   **L**                                    |                                   C                                   |                             C                              |                              C                               |                           C                           |

**Mobile Architecture & Domain Integration**

Este aspecto comprende la organización estructural de la aplicación móvil, la separación entre las capas `domain`, `application`, `infrastructure` y `presentation`, así como la correspondencia entre los módulos implementados y los Bounded Contexts definidos previamente para CollabPro.

**Campaign & Collaboration Implementation**

Comprende la implementación y revisión de funcionalidades relacionadas con campañas, postulaciones, acuerdos, colaboraciones, entregables e incidencias, manteniendo coherencia con las User Stories y reglas de negocio definidas para el producto.

**Mobile UX/UI & Design System**

Comprende la definición y aplicación de colores, tipografía, espaciado, componentes reutilizables, tarjetas, botones, campos, estados y demás elementos visuales que permiten mantener consistencia entre las pantallas.

**Navigation & Interaction Flows**

Comprende la organización de rutas, navegación según el tipo de usuario, acceso a las funcionalidades principales, navegación hacia detalles y retorno entre pantallas, manteniendo coherencia con los flujos definidos para empresas y creadores.

**Testing & Quality Assurance**

Comprende la revisión del comportamiento esperado de los principales escenarios del Sprint, validaciones de formularios, estados alternativos, errores, pruebas de interacción y comprobación general de consistencia de la experiencia móvil.

##### 4.2.1.3. Sprint Backlog 1

El Sprint Backlog 1 reúne los User Stories y Work-items seleccionados para alcanzar el objetivo definido durante el Sprint Planning. El alcance de esta primera iteración comprende las primeras 18 User Stories priorizadas en el Product Backlog, incluyendo la implementación de la Landing Page y el desarrollo de capacidades iniciales del backend relacionadas con identidad, perfiles, campañas y postulaciones.

Para el seguimiento del trabajo del Sprint se utilizó Trello, donde las actividades se organizaron de acuerdo con su estado de avance y los Work-items necesarios para implementar las funcionalidades correspondientes.

###### Sprint 1 Board

![Sprint 1 Board](./assets/C04/Sprint1/sprint-backlog-board.png)

_Nota. Elaboración propia._

Trello: [https://trello.com/b/2D9IrqkO/collabpro-sprint-1](https://trello.com/b/2D9IrqkO/collabpro-sprint-1)

| Sprint 1 | User Story Id | User Story Title | Work-Item / Task Id | Task Title | Description | Estimation (Hours) | Assigned To | Status |
| --- | --- | --- | --- | --- | --- | ---: | --- | --- |
| 1 | US-01 | Presentación de CollabPro para empresas | T-01 | Implementar propuesta de valor para empresas | Implementar en la Landing Page la propuesta de valor y los principales beneficios de CollabPro dirigidos a pequeñas y medianas empresas. | 1 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-02 | Presentación de CollabPro para creadores | T-02 | Implementar propuesta de valor para creadores | Implementar en la Landing Page la propuesta de valor y los principales beneficios dirigidos a creadores de contenido. | 1 | Fabio Cesar Vallejo Trujillo | Done |
| 1 | US-03 | Información sobre el funcionamiento de CollabPro para empresas | T-03 | Implementar sección de funcionamiento para empresas | Implementar una sección que explique a las empresas las principales etapas del proceso de colaboración dentro de CollabPro. | 2 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-04 | Información sobre el funcionamiento de CollabPro para creadores | T-04 | Implementar sección de funcionamiento para creadores | Implementar una sección que explique a los creadores las etapas de búsqueda, postulación, aceptación, entrega y validación. | 2 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-05 | Contacto con CollabPro | T-05 | Implementar formulario de contacto | Implementar el formulario de contacto con los campos requeridos y sus respectivas validaciones. | 2 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-05 | Contacto con CollabPro | T-06 | Implementar confirmación de contacto | Implementar una confirmación visual cuando una consulta sea enviada correctamente. | 1 | Julio Frank Quispe Serrano | Done |
| 1 | US-06 | Cambio de idioma | T-07 | Implementar selector de idioma | Implementar el selector que permita visualizar la Landing Page en español o inglés. | 2 | Fabio Cesar Vallejo Trujillo | Done |
| 1 | US-06 | Cambio de idioma | T-08 | Mantener idioma seleccionado | Mantener el idioma seleccionado durante la navegación dentro de la Landing Page. | 1 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-07 | Compatibilidad visual de la Landing Page con varios dispositivos | T-09 | Implementar diseño responsive | Adaptar la Landing Page para su correcta visualización en dispositivos móviles y computadoras. | 3 | Fabio Cesar Vallejo Trujillo | Done |
| 1 | US-07 | Compatibilidad visual de la Landing Page con varios dispositivos | T-10 | Validar comportamiento responsive | Validar la visualización en distintos tamaños y orientaciones de pantalla. | 2 | Julio Frank Quispe Serrano | Done |
| 1 | US-08 | Registro desde la Landing Page | T-11 | Implementar acceso al registro de empresa | Implementar desde la Landing Page el acceso al proceso de registro correspondiente a una empresa. | 1 | Leonardo Rafael Garcia Villanueva | Done |
| 1 | US-08 | Registro desde la Landing Page | T-12 | Implementar acceso al registro de creador | Implementar desde la Landing Page el acceso al proceso de registro correspondiente a un creador de contenido. | 1 | Leonardo Rafael Garcia Villanueva | Done |
| 1 | US-17 | Búsqueda de campañas | T-13 | Implementar búsqueda de campañas | Implementar la consulta de campañas publicadas utilizando los criterios de búsqueda disponibles. | 3 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-17 | Búsqueda de campañas | T-14 | Implementar filtros de campañas | Implementar los filtros por categoría, ubicación, tipo de compensación y demás criterios establecidos. | 2 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-18 | Consulta de condiciones de una campaña | T-15 | Implementar consulta de detalle de campaña | Permitir consultar objetivo, requisitos, entregables, fechas, compensación y estado de una campaña. | 2 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-19 | Postulación a campaña | T-16 | Implementar registro de postulación | Implementar el proceso mediante el cual un creador puede registrar una postulación a una campaña. | 3 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-19 | Postulación a campaña | T-17 | Implementar validaciones de postulación | Validar duplicidad, requisitos obligatorios y disponibilidad de la campaña antes de registrar la postulación. | 2 | Julio Frank Quispe Serrano | Done |
| 1 | US-19 | Postulación a campaña | T-18 | Implementar actualización de postulación | Permitir actualizar una postulación mientras esta permanezca en estado pendiente. | 2 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-10 | Registro de creador | T-19 | Implementar registro de creador | Implementar el servicio para crear una cuenta correspondiente a un creador de contenido. | 3 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-10 | Registro de creador | T-20 | Validar registro de creador | Validar información obligatoria, formato de correo y existencia previa de la cuenta. | 2 | Julio Frank Quispe Serrano | Done |
| 1 | US-11 | Inicio de sesión y recuperación de cuenta | T-21 | Implementar inicio de sesión | Implementar la autenticación de usuarios mediante sus credenciales de acceso. | 3 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-11 | Inicio de sesión y recuperación de cuenta | T-22 | Implementar recuperación de cuenta | Implementar la solicitud de recuperación y restablecimiento de contraseña. | 3 | Leonardo Rafael Garcia Villanueva | Done |
| 1 | US-13 | Gestión del perfil de creadores | T-23 | Implementar consulta de perfil de creador | Permitir obtener la información correspondiente al perfil del creador autenticado. | 2 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-13 | Gestión del perfil de creadores | T-24 | Implementar actualización de perfil de creador | Permitir modificar la información disponible del perfil del creador. | 2 | Fabio Cesar Vallejo Trujillo | Done |
| 1 | US-14 | Vinculación de redes sociales | T-25 | Implementar autorización de red social | Implementar el inicio del proceso de autorización para vincular una cuenta social. | 3 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-14 | Vinculación de redes sociales | T-26 | Procesar vinculación de red social | Procesar la respuesta de autorización y registrar las redes sociales vinculadas al perfil. | 3 | Leonardo Rafael Garcia Villanueva | Done |
| 1 | US-15 | Creación de campaña | T-27 | Implementar creación de campaña | Implementar el registro de los datos generales requeridos para crear una campaña. | 3 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-15 | Creación de campaña | T-28 | Implementar publicación de campaña | Implementar la operación para publicar una campaña cuando cuente con la información requerida. | 2 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-16 | Definición de condiciones de campaña | T-29 | Implementar condiciones de campaña | Implementar el registro de requisitos, entregables, plazos y compensación de una campaña. | 3 | Renzo Zamir Revilla Quispe | Done |
| 1 | US-09 | Registro de empresa | T-30 | Implementar registro de empresa | Implementar el servicio para crear una cuenta correspondiente a una empresa. | 3 | Anhelo Rodrigo Rocca León | Done |
| 1 | US-09 | Registro de empresa | T-31 | Validar registro de empresa | Validar la información obligatoria y evitar la creación de cuentas empresariales duplicadas. | 2 | Julio Frank Quispe Serrano | Done |


##### 4.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1 se realizaron avances relacionados con la documentación y desarrollo de los artefactos que conforman CollabPro. Los cambios fueron gestionados mediante Git y GitHub, siguiendo las convenciones de control de versiones definidas por el equipo.

A continuación, se presentan algunos de los commits realizados durante el desarrollo del proyecto como evidencia del trabajo efectuado durante el Sprint.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| --- | --- | --- | --- | --- | --- |
| AppMoviles2026/report | main | 7f7bf6d | docs: added requirements specification | Requirements specification added | 2026-09-18 |
| AppMoviles2026/report | main | 9a370c6 | docs: add strategic and tactical DDD documentation | Strategic and tactical DDD documentation added | 2026-09-18 |
| AppMoviles2026/report | main | e5ccaa5 | docs: update README with storytelling diagrams | Storytelling diagrams added to README | 2026-09-18 |
| AppMoviles2026/report | main | 35d6813 | docs: update README to include Bounded Context Canvases for various management domains | Bounded Context Canvases documentation added | 2026-09-18 |
| AppMoviles2026/report | main | 1a45ab3 | doc: add conclutions and interview | Conclusions and interview documentation added | 2026-09-18 |
| AppMoviles2026/report | main | 294c3e3 | docs: update README to include database design diagrams for various bounded contexts | Database design diagrams added for bounded contexts | 2026-09-18 |
| AppMoviles2026/report | main | d821931 | docs: fixed minor gramatic details | Minor grammatical corrections applied | 2026-09-18 |
| AppMoviles2026/report | main | 198b9e2 | docs: fixed minor gramatic detail | Minor documentation correction applied | 2026-09-18 |
| AppMoviles2026/report | main | 0a273ec | doc: update | General project documentation updated | 2026-09-18 |

##### 4.2.1.5. Testing Suite Evidence for Sprint Review

Durante el Sprint 1 se implementó un conjunto de pruebas automatizadas para validar las principales capacidades desarrolladas en los Bounded Contexts Identity & Profile Management y Campaign Management. Las pruebas se encuentran en el repositorio `AppMoviles2026/platform`, dentro de la ruta `src/test/java/com/collabtech/platform`, y fueron desarrolladas utilizando JUnit 5, Spring Boot Test y Mockito.

La estrategia de testing comprende Unit Tests orientados a verificar reglas de dominio y servicios de aplicación, Integration Tests para comprobar la interacción entre las capas de aplicación, persistencia, seguridad y base de datos, y pruebas de aceptación automatizadas a nivel API que ejecutan escenarios completos mediante solicitudes HTTP reales sobre la aplicación.

Durante este Sprint no se implementaron pruebas bajo el enfoque BDD con archivos `.feature` en lenguaje Gherkin. Las pruebas de aceptación fueron implementadas directamente mediante JUnit y Spring Boot Test, por lo que no se presentan Feature Files ni Step Definitions.

###### Unit Tests

Los Unit Tests validan de manera aislada reglas de negocio, agregados, Value Objects, servicios de dominio, handlers y componentes de seguridad.

| Test Id | Test Class | Related User Story | Component / Behavior |
| --- | --- | --- | --- |
| UT-01 | `RegistrationDomainTests` | US-09, US-10 | Valida la creación de cuentas de empresa y creador, la asignación correcta del tipo de cuenta, perfiles iniciales y validaciones de contraseña. |
| UT-02 | `RegistrationHandlersTests` | US-09, US-10 | Valida el procesamiento de los comandos de registro, hash de contraseña, persistencia y rechazo de correos previamente registrados. |
| UT-03 | `PasswordHasherTests` | US-09, US-10, US-11 | Comprueba que las contraseñas sean almacenadas mediante hash, empleando valores de salt diferentes y evitando almacenar el texto original. |
| UT-04 | `JwtSessionSecurityTests` | US-11 | Valida la emisión y verificación de tokens JWT, expiración, firma, revocación y rechazo de tokens inválidos. |
| UT-05 | `SecretCipherTests` | US-14 | Comprueba el cifrado de credenciales asociadas a proveedores externos y el rechazo de información alterada. |
| UT-06 | `CampaignDomainTests` | US-15, US-16 | Valida las reglas del agregado Campaign para definición de condiciones, fechas, compensación, publicación, cierre y estados permitidos. |
| UT-07 | `ApplicationDomainTests` | US-19 | Valida elegibilidad, requisitos obligatorios, creación de postulaciones, actualización, cancelación y restricciones según el estado de la postulación. |

###### Integration Tests

Las pruebas de integración validan el funcionamiento conjunto de controladores REST, servicios de aplicación, seguridad, persistencia y base de datos utilizando el perfil de testing del backend.

| Test Id | Test Class | Related User Story | Component / Behavior |
| --- | --- | --- | --- |
| IT-01 | `RegistrationApiTests` | US-09, US-10 | Verifica registro de empresas y creadores, validaciones de entrada, prevención de cuentas duplicadas, persistencia y rollback ante errores. |
| IT-02 | `IdentityLifecycleApiTests` | US-11, US-13, US-14 | Verifica inicio de sesión, recuperación de cuenta, actualización de perfil, sesiones protegidas y vinculación de redes sociales. |
| IT-03 | `RecoveryMailpitTests` | US-11 | Comprueba la generación y entrega del correo correspondiente al proceso de recuperación de cuenta. |
| IT-04 | `SocialOAuthAdapterTests` | US-14 | Valida la integración del adaptador OAuth para TikTok e Instagram mediante respuestas HTTP controladas y almacenamiento seguro de credenciales. |
| IT-05 | `CampaignPreparationApiTests` | US-15, US-16 | Verifica creación de campañas, definición y actualización de condiciones, publicación, autorización por rol, persistencia e idempotencia. |
| IT-06 | `CampaignDiscoveryApplicationApiTests` | US-17, US-18, US-19 | Verifica búsqueda y filtrado de campañas, consulta de detalle, validación de elegibilidad y creación, consulta, actualización y cancelación de postulaciones. |
| IT-07 | `BackendMigrationUpgradeTests` | Soporte técnico del Sprint | Valida que las migraciones Flyway puedan actualizar una base de datos existente sin eliminar cuentas, sesiones o estados pendientes. |
| IT-08 | `CollabproPlatformApplicationTests` | Soporte técnico del Sprint | Comprueba que el contexto completo de Spring Boot pueda inicializarse correctamente con el perfil de testing. |

###### Acceptance Tests

Las pruebas de aceptación automatizadas se ejecutan sobre la API utilizando un servidor Spring Boot real iniciado en un puerto de testing. Estos escenarios atraviesan las capas REST, Application, Domain e Infrastructure, permitiendo validar el comportamiento esperado desde la perspectiva de los User Stories.

| Test Id | Automated Scenario | Related User Story | Expected Result |
| --- | --- | --- | --- |
| AT-01 | Registro de empresa y creador mediante HTTP real | US-09, US-10 | La API registra correctamente la cuenta y su perfil correspondiente y retorna HTTP 201 sin exponer la contraseña. |
| AT-02 | Inicio de sesión y acceso al perfil mediante HTTP real | US-11, US-13 | El usuario obtiene una sesión válida y puede acceder a los recursos protegidos correspondientes a su perfil. |
| AT-03 | Creación y persistencia de campaña mediante HTTP real | US-15 | Una empresa autenticada puede crear una campaña y la información permanece almacenada correctamente. |
| AT-04 | Búsqueda y detalle de campañas | US-17, US-18 | El creador puede consultar campañas publicadas mediante criterios de búsqueda y acceder al detalle y condiciones de una campaña. |
| AT-05 | Flujo completo de postulación | US-19 | El creador puede postular, consultar, actualizar y cancelar una postulación respetando las validaciones y estados definidos. |

###### Testing Source Code Repository

Repository: `https://github.com/AppMoviles2026/platform`

Testing source code path:

`src/test/java/com/collabtech/platform`

Durante el Sprint, los tests fueron incorporados junto con las funcionalidades correspondientes en los commits de implementación. Los principales commits relacionados con la suite de testing se presentan a continuación.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| --- | --- | --- | --- | --- | --- |
| AppMoviles2026/platform | develop | `1966dba` | feat: added auth endpoints for brands and creators (US09 and US10) | — | 2026-10-05 |
| AppMoviles2026/platform | develop | `9325b94` | feat: added login endpoints (US11, US13, US14) for identity context | — | 2026-10-05 |
| AppMoviles2026/platform | develop | `31ba1b9` | feat: added campaign creation and conditions (US15 and US16) for campaign context | — | 2026-10-05 |
| AppMoviles2026/platform | develop | `f2b1faa` | feat: added campaign filters and postulations (US17 and US19) for campaigh context | — | 2026-10-05 |
| AppMoviles2026/platform | develop | `aac2f6f` | feat: implemented JWT for login | — | 2026-10-07 |

##### 4.2.1.6. Execution Evidence for Sprint Review

##### 4.2.1.7. Services Documentation Evidence for Sprint Review

Durante el Sprint 1 se documentaron los servicios REST del backend de CollabPro mediante OpenAPI 3.1. La especificación se genera desde los controladores Spring Boot y permite consultar rutas, parámetros y modelos de solicitud/respuesta. En la revisión del 9 de octubre de 2026, la interfaz Swagger y el documento OpenAPI respondieron correctamente desde la máquina virtual de Azure.

**Swagger UI:** [http://40.75.23.68:8081/swagger-ui/index.html](http://40.75.23.68:8081/swagger-ui/index.html)<br>
**OpenAPI JSON:** [http://40.75.23.68:8081/v3/api-docs](http://40.75.23.68:8081/v3/api-docs)

La versión documentada expone 22 rutas relacionadas con los casos de uso implementados en Identity & Profile Management y Campaign Management:

| Servicio / área | Capacidades documentadas | Rutas representativas |
|---|---|---|
| Identity y autenticación | Registro de empresas y creadores, inicio de sesión, recuperación/restablecimiento de contraseña y consulta de la cuenta actual. | `POST /api/v1/auth/brands`, `/creators`, `/sessions`, `/recovery-requests`, `/password-resets`; `GET /api/v1/accounts/me` |
| Perfil y redes sociales | Consulta/actualización del perfil de creador; inicio de autorización OAuth, callback, consulta de resultado y listado de redes vinculadas. | `GET/PUT /api/v1/profiles/me/creator`; `/api/v1/social-accounts/{platform}/authorizations`, `/callback`, `/authorizations/{authorizationId}`, `/me` |
| Campañas | Exploración paginada, consulta de detalle, campañas propias, creación, definición de condiciones, publicación, cierre y descarte de borradores. | `GET/POST /api/v1/campaigns`; `/campaigns/published`, `/campaigns/mine`, `/campaigns/{id}`, `/campaigns/{id}/conditions`, `/publication`, `/closure` |
| Postulaciones | Envío, listado propio, detalle, edición y cancelación; las solicitudes de creación aceptan `Idempotency-Key` para proteger reintentos. | `POST /api/v1/campaigns/{id}/applications`; `GET /api/v1/applications/mine`, `/applications/{id}`; `PUT /api/v1/applications/{id}`; `POST /api/v1/applications/{id}/cancellation` |

Las rutas protegidas usan JWT Bearer. Para probarlas desde Swagger, se ejecuta `POST /api/v1/auth/sessions`, se copia `accessToken` y se ingresa en **Authorize**; el control añade el esquema Bearer al realizar solicitudes. Las rutas de registro, autenticación, recuperación y callback OAuth son públicas según su propósito. Los errores de autenticación y autorización se devuelven como HTTP 401 y 403, respectivamente. La vinculación de Instagram/TikTok necesita credenciales OAuth y callbacks registrados en los proveedores; la documentación no representa una autorización social simulada. Los bounded contexts Collaboration, Billing y Performance no exponen todavía rutas en la API desplegada.


![Vista general de Swagger UI con los grupos de rutas de CollabPro](./assets/C04/Sprint1/services/swagger-ui-overview.png)

_Figura. Interfaz Swagger UI de la API desplegada, mostrando los grupos de endpoints disponibles._

##### 4.2.1.8. Software Deployment Evidence for Sprint Review

El backend REST de CollabPro se desplegó para la revisión del Sprint 1 en una máquina virtual de Microsoft Azure. La API queda expuesta en el puerto 8081 y la dirección pública informada es `http://40.75.23.68:8081`. Durante la verificación del 9 de octubre de 2026, Swagger UI (`/swagger-ui/index.html`) y el contrato OpenAPI (`/v3/api-docs`) respondieron con HTTP 200; el documento identifica el servicio como **CollabPro API**, versión **v1**, y publica 22 rutas.

| Elemento | Estado observado |
|---|---|
| Plataforma de cómputo | Máquina virtual de Azure |
| URL base informada | [http://40.75.23.68:8081](http://40.75.23.68:8081) |
| Documentación interactiva | [Swagger UI](http://40.75.23.68:8081/swagger-ui/index.html) |
| Especificación de servicios | [OpenAPI JSON](http://40.75.23.68:8081/v3/api-docs), OpenAPI 3.1 |
| Verificación registrada | Swagger UI y OpenAPI disponibles con HTTP 200 el 9 de octubre de 2026 |
| Transporte publicado | HTTP en el endpoint proporcionado |

El repositorio del backend contiene un `Dockerfile` para construir la imagen de Spring Boot y `compose.yaml` para levantar localmente la API, MySQL y Mailpit. La URL pública confirma la disponibilidad de la API; por sí sola no identifica dónde se aloja MySQL ni confirma que la VM utilice exactamente el mismo archivo Compose. Por ello, las capturas de Azure deben mostrar la VM y su configuración efectiva, sin incluir secretos.

La dirección de despliegue usa HTTP, según la URL proporcionada. Para un entorno productivo se recomienda publicar la API mediante HTTPS y un nombre de dominio. La arquitectura C4 de la sección 2.5.3.3 corresponde a la propuesta de despliegue elaborada durante AV1; esta evidencia documenta el estado operativo observado durante Sprint 1.

![Máquina virtual de CollabPro en Azure](./assets/C04/Sprint1/deployment/azure-vm-overview.jpeg)

_Figura. Portal de Azure mostrando la máquina virtual utilizada para el despliegue y su estado de ejecución._

![Reglas de red para acceder al backend de CollabPro](./assets/C04/Sprint1/deployment/azure-network-port-8081.jpeg)

_Figura. Configuración de red de Azure que permite el acceso al servicio en el puerto 8081._

##### 4.2.1.9. Team Collaboration Insights during Sprint

### 4.3. Validation Interviews

#### 4.3.1. Diseño de Entrevistas

#### 4.3.2. Registro de Entrevistas

#### 4.3.3. Evaluaciones según heurísticas

## Conclusiones

**Conclusiones generales**

1. Las entrevistas y el Needfinding evidenciaron que marcas y creadores necesitan coordinar campañas con mayor claridad, especialmente al descubrir oportunidades, acordar condiciones, validar entregables y dar seguimiento a resultados.
2. La síntesis de personas, tareas, journeys y necesidades de ambos segmentos permitió convertir problemas del dominio en un alcance inicial priorizado para CollabPro, manteniendo como foco el valor para empresas y creadores.

**Conclusiones técnicas del sprint 1**

1. La organización del backend por bounded contexts y la aplicación de DDD dieron estructura a las capacidades iniciales de identidad, perfiles, campañas y postulaciones, con contratos REST documentados mediante OpenAPI.
2. La autenticación JWT, la persistencia relacional y la publicación del servicio en una máquina virtual de Azure conforman una primera base desplegable; la documentación OpenAPI permite inspeccionar los endpoints disponibles.

## Conclusiones y recomendaciones

**Recomendaciones generales**

1. Ampliar la validación con empresas y creadores de distintos tamaños y especialidades, contrastando las necesidades identificadas y las condiciones de colaboración con evidencia de entrevistas y pruebas de prototipos.
2. Validar con usuarios los flujos prioritarios de ambos segmentos y llevar los hallazgos de usabilidad al Product Backlog antes de ampliar funcionalidades.

**Recomendaciones técnicas del sprint 1**

1. Publicar el servicio de Azure detrás de HTTPS y un dominio estable; mantener MySQL sin exposición pública y gestionar credenciales y secretos mediante configuración segura del entorno.
2. Automatizar despliegues y pruebas de humo, y ejecutar recorridos de extremo a extremo contra datos persistentes para comprobar autenticación, permisos, errores, paginación y retorno OAuth antes de cada entrega.

## Glosario

## Bibliografía

- Evans, Eric. (2003). _Domain-Driven Design: Tackling Complexity in the Heart of Software_. Addison-Wesley.
- BrandMe. (s.f.). _Membresías para marcas_. Consultado el 12 de septiembre de 2026. https://brandme.la/membresias-marcas/
- Influencity. (s.f.). _Influencer marketing platform for brands & agencies_. Consultado el 12 de septiembre de 2026. https://influencity.com/platform/
- Instituto Nacional de Defensa de la Competencia y de la Protección de la Propiedad Intelectual. (2024). _Guía de publicidad para influencers 2024_. INDECOPI. https://www.gob.pe/institucion/indecopi/informes-publicaciones/5870366-guia-de-publicidad-para-influencers-2024
- Interactive Advertising Bureau Perú, & PricewaterhouseCoopers. (2024). _Informe de inversión publicitaria digital 2024_. IAB Perú. https://iabperu.com/wp-content/uploads/2025/03/PwC-e-IAB-Informe-de-Inversion-en-Publicidad-Digital-2024-version-reducida.pdf
- SocialPubli. (s.f.). _Influencer marketing campaigns_. Consultado el 12 de septiembre de 2026. https://socialpubli.com/brands
- GitHub. (s.f.). _GitHub Docs: Branches, pull requests and GitHub Actions_. https://docs.github.com/
- Google. (s.f.). _Google Java Style Guide_. https://google.github.io/styleguide/javaguide.html
- Google. (s.f.). _Google HTML/CSS Style Guide_. https://google.github.io/styleguide/htmlcssguide.html
- W3Schools. (s.f.). _HTML Style Guide and Coding Conventions_. https://www.w3schools.com/html/html5_syntax.asp
- Kotlin. (s.f.). _Coding conventions_. https://kotlinlang.org/docs/coding-conventions.html
- Dart. (s.f.). _Effective Dart: Style_. https://dart.dev/effective-dart/style
- SpecFlow. (s.f.). _Gherkin conventions for readable specifications_. https://specflow.org/gherkin/gherkin-conventions-for-readablespecifications/
- Semantic Versioning. (s.f.). _Semantic Versioning 2.0.0_. https://semver.org/
- Conventional Commits. (s.f.). _Conventional Commits 1.0.0_. https://www.conventionalcommits.org/en/v1.0.0/
- Driessen, V. (2010). _A successful Git branching model_. https://nvie.com/posts/a-successful-git-branching-model/
- Spring. (s.f.). _Spring Boot Reference Documentation_. https://docs.spring.io/spring-boot/index.html
- Android Developers. (s.f.). _Android Studio_. https://developer.android.com/studio
- Flutter. (s.f.). _Flutter documentation_. https://docs.flutter.dev/
- Google. (s.f.). _Firebase Cloud Storage documentation_. https://firebase.google.com/docs/storage

## Anexos

### ANEXO A. Repositorios del proyecto

- **Repositorio del reporte:** <https://github.com/AppMoviles2026/report>
- **Repositorio del backend:** <https://github.com/AppMoviles2026/platform>
- **Repositorio del sitio web:** <https://github.com/AppMoviles2026/website>
- **Repositorio de la aplicación móvil:** <https://github.com/AppMoviles2026/mobile-app>

### ANEXO B. Gestión, diseño y modelado

- **Tablero general del proyecto en Trello:** <https://trello.com/b/X1Cgxi0s/collabpro>
- **Tablero del Sprint 1 en Trello:** <https://trello.com/b/2D9IrqkO/collabpro-sprint-1>
- **Diseño y prototipos en Figma:** <https://www.figma.com/design/dWJkpGdFOOHLbDqiLJ9oj1/CollabPro?node-id=0-1&t=p3jf9OlwKmfJjX7y-1>
- **Big Picture EventStorming en Miro:** <https://miro.com/app/board/uXjVHl9jh_M=/?share_link_id=159650084488>

### ANEXO C. Enlaces a entrevistas

- **Entrevista a Frank Loayza:** <https://youtu.be/dvb_GWTTWyg>
- **Entrevista a Andy Pillaca:** <https://drive.google.com/file/d/1z8S2-whw5Wi0ZabnAjMTSdbTEb_XWkOh/view>
- **Entrevista a Jorge Altamirano:** <https://youtu.be/EhL1vlqkHbM>
- **Entrevista a Luis Ángel:** <https://www.youtube.com/watch?v=vipJiRQga7c>
- **Entrevista a Britner:** <https://www.youtube.com/watch?v=_zyG4bD_Zr4>
- **Entrevista a Katrina Villarreal:** <https://youtu.be/hwh1Y0CnKpk>

### ANEXO D. Despliegues y documentación de servicios

- **Landing page desplegada:** <https://appmoviles2026.github.io/website/>
- **URL base de la API:** <http://40.75.23.68:8081>
- **Swagger UI:** <http://40.75.23.68:8081/swagger-ui/index.html>
- **Especificación OpenAPI en formato JSON:** <http://40.75.23.68:8081/v3/api-docs>
