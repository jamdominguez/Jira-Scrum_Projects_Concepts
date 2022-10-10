# Jira-Scrum_Projects_Concepts
Concepts of Scrum projects management with Jira agile

It is based in a [Udemy](https://www.udemy.com/) course.

**Status: Completed**

<div align="center">

![Jira-Scrum_Projects_Concepts](courseIcon.png)<br>
[Gestiona tu Proyecto Scrum con Jira Agile](https://www.udemy.com/course/scrum-jira/) by Hector Bravo

</div>

### Personal Set Up
- CUP: i5-7600K@3.80GHz 
- RAM: 16GB
- Environment: Windows 10
- Browser: Google Chrome (80)
- IDE: Visual Studio Code (1.43)
- IDE Extensions: Markdown all in one

<br><br>

# 1. Introducción
## 1.1. Jira
Jira fue desarrollado por la empresa australiana [Atlassian](https://www.atlassian.com/es).
Inicialmente se utilizó para el desarrollo de software, sirviendo de apoyo para la gestión de requisitos, seguimiento del estado de desarrollo y más tarde para la gestión de errores. Jira puede ser utilizado para la gestión y mejora de los procesos, gracias a sus funciones para la organización de flujos de trabajo
Es la herramienta numero uno para la gestión de proyectos: planificación, seguimeinto y reportes

## 1.2. Casos de uso para Jira
  - Los Product Owner (PO): Pueden crear el backlog del producto, programar sprint, lineas de tiempo
  - Los Porject Manager (PM) y Scrum Master (SM): Pueden gestionar el proyecto, el alacance, el backlog, los impedimentos, recursos
  - Los developers: Llevar el control de las actividades, seguimiento de bugs

## 1.3. Utilidades de Jira
  - Planificación ágil
  - Monitoreo y seguimiento
  - Deployments (liberaciones / releases)
  - Reportes
  - Integración

## 1.4. Jerarquia de Jira dentro de Atlassian:
  - Sitio/Empresa (Atlassian)
  - Productos (Jira)
  - Proyectos
  - Incidencias
	
## 1.5. Tipos de issues (incidencias)
  - Epic: Se puede descomponer en una o más user stories
  - User story: Se puede descomponer en una o multiples tareas
  - Bug
  - Task
  - Sub-Task
	
## 1.6. Productos Atalssian integrables con Jira
## 1.6.1. Confluence
Es una herramienta eficaz para crear, compartir, organizar y discutir el trabajo con tu equipo. Permite crear documentos en línea de manera colaborativa (algunas plantillas que provee: linea de tiempo, programar un proyecto, diseño de producto, minutas de reuniones).
Confluence tiene los siguientes casos de uso:
  - Crear y compartir contenido
  - Versionado
  - Persona a persona
  - Inegración con Jira
  - Extendible con addons
  - Creado para equipos

### 1.6.2. Bamboo
Es un sistema de integración continua y automatización (como [Jenkins](https://www.jenkins.io/) o [Team City](https://www.jetbrains.com/teamcity/))
	
### 1.6.3. Bitbucket
Repositorio de código basado en [Git](https://git-scm.com/) (como [GitHub](https://github.com/))

### 1.6.4. Probar productos Atlassian
Los productos de [Atlassian](https://www.atlassian.com/es) tienen periodos de prueba que puede ser extendidos solicitándolo a sales@atlassian.com.

<br><br>

# 2. Conceptos de Scrum
Scrum es un marco de trabajo (framework) para la gestión agil de proyectos. Se puede utilizar en cualquier tipo de proyecto, pero sobre todo en los software. El concepto es dividir proyectos grandes en etapas más pequeñas, revisar y adaptar a lo largo del camino

## 2.1. ¿Por qué utilizar Scrum?
- Adraptable
  - Proyectos adaptables
  - Incorporación al cambio
- Transparencia
  - Información compartida
  - Ambiente de trabajo abierto 	
- Retroalimentación continua
  - Daily standup
  - Revisar y demo de sprints
- Mejora continua
  - Refinar backlog
  - Retrospectiva
- Entrega continua de valor
  - Proceso iterativo
  - Entregables de forma progresiva
- Ritmo sostenible
  - Duración definida de un sprint
  - Diseñado para ritmo sostenible
- Entrega anticipada de alto valor
  - Backlog priorizado
  - Entrega de requisitos de mayor valor
- Proceso de desarollo eficiente
  - Time-boxing (tiempo fijo definido)
  - Reducción de desperdicio
- Motivación
  - Daily standup
  - Retrospectiva
- Resolución de problemas más rápidos
  - Colaboración
  - Resolver impedimentos (scrum master)
- Entregables efectivos
  - Backlog priorizado
  - Revisiones periódicas de entregables
- Centrado en el cliente
  - Enfasis en el valor de negocio
  - Entorno de colaboración con stakeholders
- Ambiente de alta confianza
  - Transparencia y colaboración
  - Baja fricción entre colaboradores
- Responsabilidad colectiva
  - Comprometer historias de usuario
  - Hacer suyo el proyecto
- Alta velocidad
  - Entregas progresivas y priorizadas
  - Cliente percibe velocidad en los entregables
- Ambiente innovador
  - Retrospectiva de sprint y proyecto
  - Aprendizaje, adaptación que conlleva a un ambiente de trabajo innovador y creativo

## 2.2. Artefactos:
- **Backlog del producto**: Conjunto de todas las epics y user stories que se han definido
- **Backlog del sprint**: Es un subconjunto del backlog del producto que se van a desarrollar en cada sprint. Al inicio de cada sprint se seleccionan las user stories en las que se va a trabajar, se crea el backlog del sprint y luego se ejecuta el sprint.
- **Incremento**: Despues de cada sprint hay un incremento del producto potencialmente entregable, debido a la entrega gradual y progresiva del producto
- **Definición de terminado**: Hay que clarificar cuándo y cómo una user story está terminada. Es decir, desarrollada, testeada en UAT, y **con el OK del PO**.

## 2.3. Divison temporal y conceptos clave en proyectos
- **Sprint**: Iteración o periodo de trabajo donde se debe finalizar las user stories (En una metodología de cascada: analisis, diseño, desarrollo, testing e implementación). Suele durar de 2 a 4 semanas. Entrega progresiva y gradual de valor al cliente. En cada sprint se hará planificación / análisis, desarrollo, test, revisión y entrega.
- **Epic** (epopeya): Funionalidad o user story grande que debe ser dividida en user storiess
- **User story**: Funcionalidad / requisito que puede ser completado en un tiempo definido. Formato para redactar epics o user stories:
  - Como (rol de usuario) : Como usuario Web.
  - Quiero (objetivo): Quiero consultar las tablas de pedidos. 
  - Para poder (beneficio): Para conocer todos los pedidos
- **Task**: Pequeño incremento de trabajo. La user story está dividida en tareas
- **Medición de esfuerzo**: Con story points se indican los puntos de esfuerzo que miden la complejidad / esfuerzo que conlleva una user story / issue (código, tiempo, etc)
- **Roles**:
  - **Cliente**: Proporciona los requisitos al PO.
  - **Product Owner (PO)**: Dueño del producto. Persona principal de crear y mantener el backlog. Definir prioridades y criterios de aceptación. Intermediario con las otras areas de la empresa
  - **Scrum Master (SM)**: Líder, que verifica y valida que los principios y conceptos de Scrum se implementen de la manera correcta a lo largo del proyecto. Es como un coach. Resolver impedimentos
  - **Equipo Scrum:** Analista, diseñador, programadores, etc.

## 2.4. Eventos / Reuniones por Sprint
- Planificación de sprint: Planificar las historias de usuario y asignarlas
- Daily standup: Que hiciste ayer, qué haras hoy, posbiles impedimentos. Aquí el Scrum master debe ayyudar a resolver los problemas
- Revisión del sprint: Se hace una demo de las funcionalidades añadidas al producto en el sprint
- Retrospectiva del sprint: Que se hizo mal, que se hizo bien, que inconvenientes se encontraron
- Retrospectiva del proyecto: Que se hizo mal / bien a nivel de proyecto

## 2.5. Flujo de Scrum
- Guía SBOK: Define cuales son las mejores prácticas para implementar Scrum
- Fases genéricas de un proyecto:
  1. Inicio
  2. Planificación
  3. Ejecución / Monitoreo y control
  4. Cierre
- Ciclo de vida de un proyecto software:
  1. Evaluación y priorización
  2. Requerimientos detallados
  3. Diseño y análisis
  4. Codificación y pruebas del desarrollador
  5. QA / Pruebas de Aceptación
  6. Despliegue
- Fluoj de Scrum: Todo empieza con un caso de negocio del proyecto (business case).
  1. Caso de negocio del proyecto: Necesidad del cliente, oportunidad en el mercado
  2. Declaración de la visión del proyecto: Donde se describen los objetivos y metas del proyecto
  3. Backlog priorizado del producto / Cronograma de planificación del lanzamiento: Lista de requisitos
  4. Sprint backlog

## 2.6. Principios de Scrum
Son fundamentos básicos para implementar el framework. Pueden aplicarse a cualquier tipo de proyecto u organización y deben respetarse a fin de garantizar la aplicación adecuada de Scrum. Los aspectos y procesos de Scrum pueden modificarse para cumplir con los requisitos del proyecto o la organización que los usa. Los principios de Scrum se pueden listar de la siguente manera:
1. **Control del proceso empírico**. En Scrum, las decisiones se basan en la observación y la experimentación en vez de la planificación inicial detallada (hacemos planificación en cada Sprint). Se basa en las ideas principales de:
   - Transparencia: Proyecto visible a todo el mundo del equipo
   - Inspección: Revisar y obtener retroalimentación (uso de scrumboard)
   - Adaptación: Mejora continua. Mejoras en el trabajo
2. **Auto-organización**. Scrum cuenta con que los empleados tienen motivación propia y buscan aceptar mayores responsabilidades. Por tanto ofrecen más valor cuando se organizan por cuenta propia. El estilo de liderazgo preferido en Scrum, es el liderazgo servicial, el cual enfatiza los resultados, centrándose en las necesiades del equipo Scrum. En la vida real es complicado, por lo que hay que hacer inspección y empuje constante (PO y SM)
3. **Colaboración**. El equipo principal de Scrum trabaja e interactua con los stakeholders para crear y validar los resultados del proyecto. Se produce cuando se integra el aporte indiviual de cada miembro con fin de producir algo más grande. Se prefiere la co-ubicación
4. **Priorización basada en valor**. El framework Scrum se guia en ofrecer el máximo valor empresarial en un mínimo periodo de tiempo. La herramienta base para esto es la priorización, estas descisiones las debe tomar el PO.
5. **Time-boxing**(asignación de un bloque de tiempo). Scrum trata al tiempo como una de las limitantes más importantes en la gestión de proyectos. El fin de este principio es proponer la fijación de una cierta cantidad de tiempo para cada proceso y actividad en un proyecto Scrum.
6. **Desarrollo Iterativo**. Entregables progresivos. Permite modificaciones solicitadas por el cliente ya que es más flexible. El mismo cliente va tomando mayor conciencia de las funcionalidades de su producto y del alcance del mismo según se avanza y esto permite afinar mucho más en lo que se quiere y cómo se quiere.

## 2.7. Aspectos de Scrum
1. **Organización**
   - **Roles centrales**
     * <u>Prodcut Owner (PO)</u>: Es la voz del cliente. Crea y administra el backlog. Maximiza el valor. Define criterios de aceptación
     * <u>Scrum Master</u>: Facilitador que debe garantizar que el equipo pueda trabajar correctamente, resolviendo problemas e impedimentos y asegurar que se cumplan los los requisitos del framework de Scrum. Interactua con la organización, con el PO y con el equipo Scrum
     * <u>Equipo Scrum</u>: Los miembros deben tener diferentes habilidades. Deben entender los requisitos. Son los que crean los entregables del producto
   - **Roles no centrales**
     * <u>Stakeholders</u> (interesados en el proyecto)
     * <u>Scrum Guidance Body (SGB)</u>: Documentos / grupo de expertos
     * <u>Vendors (vendedores)</u>: Individuos u organizaciones externas que participan en el proyecto
   - **Organización real de un equipo Scrum**
     * <u>Project Manager</u>: Lidera el equipo. Responsable del proyecto. Debe preocuparse por alcanzar los objetivos
        - Desarrolla el plan de proyecto
    	- Gestiona las comunicaciones
    	- Gestiona el cronograma
    	- Gestiona el presupuesto
    	- Gestiona los interesados
    	- Gestiona el equipo de proyecto
    	- Gestiona conflictos
    	- Gestiona los riesgos
    	- Gestiona los entregables
    	- Interactua con: Organización, cliente, equipo de proyecto, otros departamentos, proveedores, gerentes funcionales.
     * <u>Scrum Master</u>
     * <u>Equipo Scrum</u>
     * <u>Product Owner</u>
     * <u>Cliente</u>
     * <u>Stakeholders</u>
   - Lo ideal es la coubicación por la facilidad de interacción y daily standup, aunque Scrum tb puede funcionar con equipos distribuidos
2. **Justificación del negocio**
   - Entrega impulsada por el valor
   - Incertidumbre sobre los resultados
   - Adaptabilidad de objetivos y procesos si se justifican ante negocio
3. **Calidad**
   - Capacidad de que los entregables cumplan los criterios de aceptación
   - Mejora continua
   - Asegurar criterio de aceptación continuo
4. **Cambio**
   - Aceptar cambios
   - Requisitos volátiles, que se van afinando conforme el proyecto avanza
   - Maximizar beneficios a partir de los cambios y minimizar impactos negativos
5. **Riesgo**
   - Riesgos positivos, son oportunidades
   - Riesgos negativos, son amenazas
   - La gestión de riesgos debe hacerse de manera preventiva y proactiva. Debe comenzar al inicio del proyecto y debe ser iterativo a lo largo del ciclo de vida del mismo
   - Plan de respuesta / mitigación de riesgos
		

## 2.8. Fases y procesos de Scrum
- Fases genéricas de un proyecto
  - Inicio
  - Planificación
  - Ejecución / Monitorización y control
  - Cierre
- Fases en Scrum (SBOK): 5 fases y 12 procesos
  - Inicio
    - Crear visión del proyecto
    - Identificar al Scrum master y stakeholders
    - Formar equipos
    - Desarrollar épicas
    - Crear Backlog priorizado del producto
    - Realizra la planificación de lanzamiento
  - Planificación y estimación
    - User stories (historias de usuario)
    - Estimar user stories
    - Comprometer user stories por Sprint
    - Identificar tasks
    - Estimar tasks
    - Crear el Sprint backlog
  - Implementación(**1**) / Revisión y retrospectiva(**2**). Son procesos paralelos
    - (**1**) Crear entregables
    - (**1**) Realizar daily
    - (**1**) Refinar el backlog priorizado del producto
    - (**2**) Demostrar y validar el sprint
    - (**2**) Retrospectiva del sprint			
- Lanzamiento
  - Enviar entregables
  - Retrospectiva del proyecto