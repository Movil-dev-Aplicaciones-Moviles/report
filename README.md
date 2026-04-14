<div align="center">
<img src="assets/UPC-Logo.png" width="120"><br><br>

<h3>Universidad Peruana de Ciencias Aplicadas</h3>

<strong>Facultad de Ingeniería</strong><br>
<strong>Carrera de Ingeniería de Software</strong><br>

<strong>Período 202610 </strong><br>
<strong>1ACC0238</strong><br>
<strong>Aplicaciones para Dispositivos Móviles</strong><br>
<strong>NRC: 3821<br>

<strong>Nombre del profesor: Jorge Luis Mayta Guillermo</strong><br>

<br><strong>_Informe de Trabajo Final_</strong><br><br>

<strong>Nombre del startup: Movildev</strong><br>
<strong>Nombre del producto: SmartStay</strong><br>

### Relación de Integrantes

| Código | Apellidos y Nombres |
| :---: | :--- |
| U202518934 | Herrera Albites, Marcoandres |
| U20231D343 | Montes Ramos, Henry Jaredt |
| U20211D760 | Paico, July |
| U202210787 | Ramirez Escalante, Carlo Patricio |
| U20221E617 | Verona Flores, Ítalo Sebastián |

<strong> Abril, 2026</strong><br>

</div>

</div>

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto.  
Esta sección inicia en una página nueva e incluye un cuadro con la siguiente estructura:

| Versión |   Fecha    | Autor                                 | Descripción de los Cambios                                    |
| :-----: | :--------: | :------------------------------------ | :------------------------------------------------------------ |
|   1.0   | 14/04/2026 | Italo Sebastian Verona Flores (Líder) | Estructuración inicial del proyecto y coordinación del equipo |
|   1.1   | 14/04/2026 | Italo Sebastian Verona Flores         | Creación del documento inicial del Informe de Trabajo Final   |


<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

- **URL del repositorio para el Project Report:** https://github.com/Movil-dev-Aplicaciones-Moviles


El desarrollo del presente informe de trabajo final se realizó de manera colaborativa utilizando las herramientas de control de versiones de GitHub. A continuación se presenta la evidencia de la participación y contribuciones de cada miembro del equipo:

El trabajo en el repositorio del informe demuestra la participación activa de todos los miembros del equipo por cada entrega.

*Primer Avance*

En el Primer Avance el objetivo principal fue la construcción completa del informe base del proyecto. El equipo trabajó en:

- Estructura del documento (portada, índice, organización de capítulos).

- Desarrollo de contenido general y conceptual:

- Contexto del proyecto

- Problemática y objetivos

- Alcance del sistema

- Arquitectura conceptual

- Identificación inicial de usuarios, funcionalidades y módulos

- Definición de lineamientos de estilo y formato del documento.

- Revisión colaborativa del contenido, ajustando redacción, coherencia y estilo.

![commits_team1](assets/commits_team1.png) aqui van las evidencias de los commits del primer avance

![commits_team2](assets/commits_team2.png) !aqui van las evidencias de los commits del segundo avance

Los gráficos muestran la distribución del trabajo del equipo durante esta fase, donde todos los miembros aportaron contenido significativo al informe base.

### Metodología de Trabajo Colaborativo

- **Control de versiones:** Uso de Git para el seguimiento de cambios y colaboración
- **Revisiones de contenido:** Implementación de pull requests para la validación del contenido
- **Documentación continua:** Actualización incremental del informe durante todo el ciclo del proyecto
- **Coordinación de equipo:** Reuniones regulares para alinear el progreso y resolver conflictos

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
        - [2.3.5. Ubiquitous Language](#235-ubiquitous-language)
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
        - [2.6.1. Bounded Context: [Nombre del Bounded Context]](#261-bounded-context-nombre-del-bounded-context)
            - [2.6.1.1. Domain Layer](#2611-domain-layer)
            - [2.6.1.2. Interface Layer](#2612-interface-layer)
            - [2.6.1.3. Application Layer](#2613-application-layer)
            - [2.6.1.4. Infrastructure Layer](#2614-infrastructure-layer)
- [Capítulo III: Solution UI/UX Design](#capítulo-iii-solution-uiux-design)
    - [3.1. Product design](#31-product-design)
        - [3.1.1. Style Guidelines](#311-style-guidelines)
            - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
        - [3.1.2. Information Architecture](#312-information-architecture)
            - [3.1.2.1. Organization Systems](#3121-organization-systems)
            - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
            - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
        - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
        - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
        - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
        - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
        - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
- [Capítulo IV: Product Implementation & Validation](#capítulo-iv-product-implementation--validation)
    - [4.1. Software Configuration Management](#41-software-configuration-management)
        - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
        - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.2. Landing Page & Mobile Application Implementation](#42-landing-page--mobile-application-implementation)
        - [4.2.1. Sprint 1](#421-sprint-1)
            - [4.2.1.1. Sprint Planning 1](#4211-sprint-planning-1)
            - [4.2.1.2. Sprint Backlog 1](#4212-sprint-backlog-1)
- [Conclusiones](#conclusiones)
- [Glosario](#glosario)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

<div style="page-break-after: always;"></div>

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

### ABET – EAC - Student Outcome 7

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 7.

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.** | **Verona Flores, Ítalo Sebastián AV1:** <ul><li>Investigué y apliqué conceptos avanzados de Domain-Driven Design (DDD) tanto estratégico como táctico para la estructuración del proyecto</li></ul> <br> **Carlo Patricio Ramirez Escalante (U202210787):** <br><br> **Henry Jaredt Montes Ramos (U20231D343):** <br><br> **Marcoandres Herrera Albites (U202518934):** <br><br> **July Paico (U20211D760):** | **Verona Flores, Ítalo Sebastián AV1::** <ul></ul> <br> **Carlo Patricio Ramirez Escalante (U202210787):** <br><br> **Henry Jaredt Montes Ramos (U20231D343):** <br><br> **Marcoandres Herrera Albites (U202518934):** <br><br> **July Paico (U20211D760):** |
| **Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.** | **Verona Flores, Ítalo Sebastián AV1::** <ul><li>Participé activamente en la búsqueda de soluciones a errores de compatibilidad durante la integración de capas, utilizando documentación técnica oficial y foros especializados como estrategia de aprendizaje continuo.</li></ul> <br> **Carlo Patricio Ramirez Escalante (U202210787):** <br><br> **Henry Jaredt Montes Ramos (U20231D343):** <br><br> **Marcoandres Herrera Albites (U202518934):** <br><br> **July Paico (U20211D760):** | **Verona Flores, Ítalo Sebastián AV1::** <ul><li>El proceso de desarrollo del proyecto confirmó que el aprendizaje en ingeniería de software no es estático; la capacidad de reaccionar y aprender nuevas tecnologías sobre la marcha es lo que permite entregar una solución de valor profesional.</li></ul> <br> **Carlo Patricio Ramirez Escalante (U202210787):** <br><br> **Henry Jaredt Montes Ramos (U20231D343):** <br><br> **Marcoandres Herrera Albites (U202518934):** <br><br> **July Paico (U20211D760):** |

<div style="page-break-after: always;"></div>

## Objetivos SMART

En esta sección, cada miembro del equipo formula un plan que incluye al menos dos objetivos SMART centrados en su desarrollo profesional tras finalizar la carrera.

### 1. Italo Sebastian Verona Flores
* **Objetivo 1:** Obtener la certificación **AWS Certified Solutions Architect – Associate** en un plazo de **18 meses** tras la graduación, y escalar hacia la certificación **Professional** en un máximo de **3 años**, con el fin de consolidar mi perfil como **Senior Software Architect**. Esto me permitirá liderar el diseño de infraestructuras escalables para mi propia startup o consultora, asegurando una retribución mensual superior a los **15,000 soles** mediante la validación técnica de mis competencias en el mercado internacional.
* **Objetivo 2:** Fundar y consolidar una Startup tecnológica o establecer una Consultoría de Infraestructura Independiente que sea operativamente remota en un plazo de **5 a 6 años**. El propósito es alcanzar la libertad financiera y técnica necesaria para trasladar mi residencia a un país con altos estándares de seguridad y clima cálido manteniendo un flujo de proyectos que sustente mi desarrollo profesional continuo y mi posicionamiento como referente en arquitectura de software.

### 2. Carlo Patricio Ramirez Escalante
* **Objetivo 1:** [Redactar aquí]
* **Objetivo 2:** [Redactar aquí]

### 3. Henry Jaredt Montes Ramos
* **Objetivo 1:** [Redactar aquí]
* **Objetivo 2:** [Redactar aquí]

### 4. Marcoandres Herrera Albites
* **Objetivo 1:** [Redactar aquí]
* **Objetivo 2:** [Redactar aquí]

### 5. July Paico
* **Objetivo 1:** [Redactar aquí]
* **Objetivo 2:** [Redactar aquí]

<div style="page-break-after: always;"></div>

## Capítulo I: Presentación