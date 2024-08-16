<style>
  body {
  font-family: 'Times New Roman', Times, serif;
  }
</style>

<h1 style="text-align: center;"><b>Universidad Peruana de Ciencias Aplicadas</b></h1>

<h2 style="text-align: center;">
    <p>Ingenieria de Software - Ciclo 5</p>
    <p>Desarrollo de Aplicaciones Open Source SV54</p>
</h2>

<div style="text-align: center;">
    <img src="img/UPC.png" alt="UPC Logo">
</div>

<h2 style="text-align: center;">
    <p>Informe de Trabajo Final</p>
    <p>NAXUS</p>
    <p>NutriSend</p>
    <p>Hugo Allan Mori Paiva</p>
</h2>

<h2 style="text-align: center;">Integrantes</h2>

<table style="margin-left: auto; margin-right: auto;">
  <tr>
    <th>Nombre y Apellidos</th>
    <th>Código</th>
  </tr>
  <tr>
    <td>Camila Leonor Espinoza Vivas</td>
    <td>U202214572</td>
  </tr>
  <tr>
    <td>Renzo José Araujo Ingunza</td>
    <td>u202113612</td>
  </tr>
  <tr>
    <td>Fatima Asmad Padilla</td>
    <td>u202113612</td>
  </tr>
   <tr>
    <td>Jhordi Luis Carranza Pérez</td>
    <td>u20191e835</td>
  </tr>
</table>

<h4 style="text-align: center;">Agosto 2024</h4>

# Registro de Versiones del Informe

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th>Version</th>
    <th>Fecha</th>
    <th>Autor</th>
    <th>Descripción de modificación</th>
  </tr>
  <tr>
    <td>TB1</td>
    <td>15/08</td>
    <td>Camila Leonor Espinoza Vivas</td>
    <td>Caratula</td>
  </tr>
  <tr>
    <td>TB1</td>
    <td>16/08</td>
    <td>Renzo José Araujo Ingunza</td>
    <td>Índice</td>
  </tr> 
  <tr>
    <td>TB1</td>
    <td>---</td>
    <td>Fatima Asmad Padilla</td>
    <td>---</td>
  </tr>
  <tr>
    <td>TB1</td>
    <td>---</td>
    <td>Jhordi Luis Carranza Pérez</td>
    <td>---</td>
  </tr>
</table>


# Project Report Collaboration Insights

# Contenido 

### Capítulo I: Introducción
- 1.1. [Startup Profile](#Startup-Profile)
  - 1.1.1. [Descripción de la Startup](#Descripción-de-la-Startup)
  - 1.1.2. [Perfiles de integrantes del equipo](#Perfiles-de-integrantes-del-grupo)
- 1.2. [Solution Profile](#Solution-profile)
  - 1.2.1. [Antecedentes y problemática](#Antecedentes-y-problemática)
  - 1.2.2. [Lean UX Process](#Lean-UX-Proccess)
    - 1.2.2.1. [Lean UX Problem Statements](#Lean-UX-problem-statements)
    - 1.2.2.2. [Lean UX Assumptions](#Lean-UX-assumptions)
    - 1.2.2.3. [Lean UX Hypothesis Statements](#Lean-UX-Hypothesis-Statements)
    - 1.2.2.4. [Lean UX Canvas](#Lean-UX-Canvas)
- 1.3. [Segmentos objetivo](#Segmentos-objetivos)


### Capítulo II: Requirements Elicitation & Analysis
- 2.1. [Competidores](#Competidores)
  - 2.1.1. [Análisis competitivo](#Análisis-competitivo)
  - 2.1.2. [Estrategias y tácticas frente a competidores](#Estrategias-y-tácticas)
- 2.2. [Entrevistas](#Entrevistas)
  - 2.2.1. [Diseño de entrevistas](#Diseño-de-entrevistas)
  - 2.2.2. [Registro de entrevistas](#Registro-de-entrevistas)
  - 2.2.3. [Análisis de entrevistas](#Análisis-de-entrevistas)
- 2.3. [Needfinding](#Needfinding)
  - 2.3.1. [User Personas](#User-personas)
  - 2.3.2. [User Task Matrix](#User-Task-Matrix)
  - 2.3.3. [User Journey Mapping](#User-journey-mapping)
  - 2.3.4. [Empathy Mapping](#Empathy-mapping)
  - 2.3.5. [As-is Scenario Mapping](#As-is-scenario)
- 2.4. [Ubiquitous Language](#Ubiquitoues-language)

### Capítulo III: Requirements Specification
- 3.1. [To-Be Scenario Mapping](#To-Be-scenario-mapping)
- 3.2. [User Stories](#User-stories)
- 3.3. [Impact Mapping](#Impact-mapping)
- 3.4. [Product Backlog](#product-backlog)

### Capítulo IV: Product Design
- 4.1. [Style Guidelines](#Style-Guidelines)
  - 4.1.1. [General Style Guidelines](#General-style-guidelines)
  - 4.1.2. [Web Style Guidelines](#Web-style-guidelines)
- 4.2. [Information Architecture](#Information-architecture)
  - 4.2.1. [Organization Systems](#Organization-systems)
  - 4.2.2. [Labeling Systems](#Labeling-systems)
  - 4.2.3. [SEO Tags and Meta Tags](#SEO-tags-and_meta-tags)
  - 4.2.4. [Searching Systems](#-Searching-systems)
  - 4.2.5. [Navigation Systems](#Navigation-systems)
- 4.3. [Landing Page UI Design](#Landing-page-UI-design)
  - 4.3.1. [Landing Page Wireframe](#Landing-page-wireframe)
  - 4.3.2. [Landing Page Mock-up](#Landing-page-mock-up)
- 4.4. [Web Applications UX/UI Design](#Web-applications-UX/UI-design)
  - 4.4.1. [Web Applications Wireframes](#Web-applications-wireframes)
  - 4.4.2. [Web Applications Wireflow Diagrams](#web-applications-wireflow-diagrams)
  - 4.4.3. [Web Applications Mock-ups](#Web-applications-mock-ups)
  - 4.4.4. [Web Applications User Flow Diagrams](#Web-applications-user-flow)
- 4.5. [Web Applications Prototyping](#Web-applications-prototyping)
- 4.6. [Domain-Driven Software Architecture](#Domain-driven-software-architecture)
  - 4.6.1. [Software Architecture Context Diagram](#Software-architecture-context-diagram)
  - 4.6.2. [Software Architecture Container Diagrams](#Software-architecture-container-diagrams)
  - 4.6.3. [Software Architecture Components Diagrams](#Software-architecture-components-diagrams)
- 4.7. [Software Object-Oriented Design](#Software-object-oriented-design)
  - 4.7.1. [Class Diagrams](#Class-diagrams)
  - 4.7.2. [Class Dictionary](#Class-dictionary)
- 4.8. [Database Design](#Database-Design)
  - 4.8.1. [Database Diagram](#Database-diagram)

### Capítulo V: Product Implementation, Validation & Deployment
  - 5.1. [Software Configuration Management](#Software-configuration-management)
  - 5.1.1. [Software Development Environment Configuration](#Software-development-enviroment)
  - 5.1.2. [Source Code Management](#Source-code-management)
  - 5.1.3. [Source Code Style Guide & Conventions](#Source-code-style-guide-&-convetions)
  - 5.1.4. [Software Deployment Configuration](#Software-deployment-configuration)
- 5.2. [Landing Page, Services & Applications Implementation](#Landing-page,-services-&-Applications-Implementation)
  - 5.2.X. [Sprint 1](#Sprint-1)
    - 5.2.X.1. [Sprint Planning 1](#Sprint-Planning-1)
    - 5.2.X.2. [Sprint Backlog 1](#Sprint-Backlog-1)
    - 5.2.X.3. [Development Evidence for Sprint Review](#Development-evidence-for-Sprint-Review)
    - 5.2.X.4. [Testing Suite Evidence for Sprint Review](#Testing-Suite-evidence-for-Sprint-Review)
    - 5.2.X.5. [Execution Evidence for Sprint Review](#Execution-Evidence-for-Sprint-Review)
    - 5.2.X.6. [Services Documentation Evidence for Sprint Review](#Services-Documentation-Evidence-for-Sprint)
    - 5.2.X.7. [Software Deployment Evidence for Sprint Review](#Software-Deployment-Evidence-for-Sprint)
    - 5.2.X.8. [Team Collaboration Insights during Sprint](#Team-Collaboration-Insights-during-Sprint)
- 5.3. [Validation Interviews](#Validation)
  - 5.3.1. [Diseño de Entrevistas](#Diseño-de-Entrevistas)
  - 5.3.2. [Registro de Entrevistas](#Registro-de-Entrevistas)
  - 5.3.3. [Evaluaciones según heurísticas](#Evaluaciones-según-heurísticas)
- 5.4. [Video About-the-Product](#Video-About-the-Product)
---
# Student Outcome

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Desarrollo de experimentos</td>
    <td>TB1</td>
    <td>TB1</td>
  </tr>
  <tr>
    <td>Análisis e interpretación de datos/ resultados</td>
    <td>TB1</td>
    <td>TB1</td>
  </tr>
</table>

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1   Descripción de la Startup
NAXUS es una startup dirigida por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), parte de la Facultad de Ingeniería. Nuestra Startup  ofrece una innovadora plataforma web llamada NutriSend, diseñada para simplificar la planificación de comidas y apoyar un estilo de vida saludable. En un mundo donde el tiempo es un recurso escaso y los regímenes alimenticios se vuelven cada vez más específicos, NutriSend se posiciona como la solución ideal para quienes buscan mantener un equilibrio entre su vida personal y sus objetivos de salud.

Nuestra plataforma ofrece un servicio integral de envío de alimentos semanalmente, que incluye información detallada sobre el contenido nutricional de cada comida, incluyendo calorías, proteínas, grasas y otros nutrientes esenciales. Ya sea que estés ocupado con tu agenda diaria o que sigas un plan de alimentación y ejercicio estricto, NutriSend se adapta a tus necesidades.
### 1.1.2   Perfiles de integrantes del equipo

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th>Miembros del equipo</th>
    <th>Código del Estudiante</th>
    <th>Carrera</th>
    <th>Principales conocimientos / habilidades</th>
  </tr>
  <tr>
    <td>Camila Leonor Espinoza Vivas</td>
    <td>u202214572</td>
    <td>Ingeniería de Software</td>
    <td>----</td>
  </tr>
  <tr>
    <td>Renzo José Araujo Ingunza</td>
    <td>u202113612</td>
    <td>Ingeniería de Software</td>
    <td>Soy una persona responsable y aplicada. para este proyecto cuento con conocimientos en lenguajes de programación como C + +, Python y java.</td>
  </tr>
  <tr>
    <td>Fatima Asmad Padilla</td>
    <td>u202113612</td>
    <td>----</td>
    <td>----</td>
  </tr>
  <tr>
    <td>Jhordi Luis Carranza Pérez</td>
    <td>u20191e835</td>
    <td>Ingeniería de Software</td>
    <td>Soy una persona dispuesta a seguir aprendiendo y mejorando constantemente. Mis conocimientos de programación en C++, Python, HTML y sobre todo la lógica de programación serán de vital ayuda para la realización de este proyecto.</td>
  </tr>
  <td>Renzo José Araujo Ingunza</td>
    <td>u202113612</td>
    <td>----</td>
    <td>----</td>
  </tr>    
</table>


## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
- **Antecedentes:** En la actualidad, muchas personas por temas de trabajo o estudios, no tienen el tiempo suficiente para cocinar. Otras, necesitan saber y controlar el valor nutricional de los platillos que comen debido al régimen alimenticio que llevan y tener una rutina acorde a lo que ellos necesiten. Para todas esas personas está pensado este proyecto el cual ayudará tanto al que no puede cocinar como al que quiere tener un control sobre su alimentación y ejercicios.
- **Problemática:** Para definir la problemática, nuestro equipo ha dispuesto la estrategia de las 5'W's y 2'H's
  
  ***5’W’s:***

  **1.What(Qué):**

  Creación de un sistema para ofrecer comida procesada y fría lista para calentar y comer, dirigido a personas que no pueden cocinar regularmente o personas que necesitan de un control alimenticio.

  **2. Who(Quién):**

  Personas con tiempo limitado para cocinar y personas con un régimen alimenticio estructurado que hagan ejecicios.

  **3. Where(Dónde):**

  Las operaciones del servicio estarán disponibles en Lima metropolitana, haciendo énfasis en puntos estratégicos donde se encuentren
  la mayor cantidad de pedidos de comidas procesadas.

  **4. When(Cuándo):**

  El servicio se ofrecerá a lo largo de todo el año, ajustándose a los requerimientos y horarios de los usuarios.

  **5. Why(Por qué):**

  Se pretende brindar una opción práctica y segura para quienes carecen de tiempo para cocinar o siguen un plan alimenticio específico
  seguido de determinados ejercicios.

  ***2’H’s:***

  **1. How(Cómo):**

  La comida seleccionada es preparada por chefs calificados, luego se procesa y congela para garantizar su frescura y seguridad alimentaria. Los usuarios
  pueden hacer sus pedidos mediante una plataforma en línea.

  **2. How Much(Cuánto):**

  El sistema asegura la frescura y seguridad alimentaria de los platos por un periodo de hasta 8 días en el refrigerador. Se implementarán precios
  accesibles y competitivos, considerando tanto el proceso de preparación como la conveniencia del servicio brindado.
  
### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
Para los usuarios con agendas ocupadas que no disponen de tiempo para cocinar con frecuencia, Nutri Send aborda el reto de ofrecer una solución rápida y conveniente que cubra sus necesidades alimentarias sin sacrificar la calidad.

**¿Cómo podemos ofrecer una solución conveniente y rápida que satisfaga las necesidades alimentarias de los usuarios ocupados sin comprometer la calidad de  los alimentos preparados?**

Para los usuarios con un plan alimenticio estructurado que desean tener un control sobre sus alimentos y llevar una rutina de ejercicios y llevar un estilo de vida más saludable. Nutri Send aborda el reto de ofrecer una solución rápida y conveniente que cumpla con los requisitos alimenticios sin sacrificar la calidad ni el valor nutricional de los alimentos preparados y tener una estructura de ejercicios establecidos.

**¿Cómo podemos ofrecer una solución rápida y conveniente que cumpla con los requisitos alimenticios de los usuarios con un plan estructurado, permitiéndoles controlar sus alimentos, mantener una rutina de ejercicios y llevar un estilo de vida más saludable sin sacrificar la calidad ni el valor nutricional de los alimentos preparados?**

#### 1.2.2.2. Lean UX Assumptions.
- Los usuarios valoran la conveniencia y rapidez: Asumimos que los usuarios de NutriSend priorizan la conveniencia y la rapidez en la entrega de sus alimentos, debido a sus agendas ocupadas.
- Los usuarios quieren alimentos saludables y de calidad: Creemos que nuestros usuarios no solo buscan conveniencia, sino también opciones de alimentos que sean saludables y que mantengan su valor nutricional, especialmente aquellos que siguien planes alimenticios estructurados.
- El diseño y la usabilidad de la plataforma son cruciales: Asumimos que una plataforma web fácil y visualmente atractiva es fundamental para que los usuarios realicen sus pedidos de manera rápida y sin complicaciones.
- Existe una demanda significativa en Lima metropolitana: Suponemos que en la capital Lima hay una demanda bastante alta de servicios de entrega de alimentos preparados, especialmente entre profesionales jóvenes y estudiantes universitarios.
- Los usuarios están dispuestos a pagar un precio justo por conveniencia y calidad: Creemos que nuestros usuarios estarán dispuestos a pagar un precio justo que refleja la conveniencia del servicio y la calidad de alimentos.

#### 1.2.2.3. Lean UX Hypothesis Statements.

**Users:**
*  Personas con escaso tiempo para cocinar
*  Personas que necesiten una dieta estructurada con ejercicios de acuerdo a sus objetivos.
   

#### 1.2.2.4. Lean UX Canvas.
## 1.3. Segmentos objetivo.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.
### 2.1.1. Análisis competitivo.

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="4">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="4">Texto</td>
  </tr>
  <tr>
   <td colspan="2">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td>Starup</td>
    <td>Competidor 1</td>
    <td>Competidor 2</td>
    <td>Competidor 3</td> 
  </tr>
  <tr>
    <td rowspan="2">Perfil</td>
    <td>Overview</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Ventaja competitiva ¿Que valor ofrece a los clientes</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td rowspan="2">Perfil de Marketing</td>
    <td>Mercado objetivo</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Estrategias de marketing</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td rowspan="3">Perfil de Producto</td>
    <td>Productos & Servicios</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Canales de distribucion (Web y/o Movil)</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td rowspan="5">Analisis SWOT</td>
    <td colspan="5">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus
    oportunidades y contribuir a lo que ustedes definen como su posible ventaja
    competitiva. </td>
  </tr>
  <tr>
    <td>Fortalezas</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.
## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
### 2.2.2. Registro de entrevistas.
### 2.2.3. Análisis de entrevistas.
## 2.3. Needfinding.
### 2.3.1. User Personas.
### 2.3.2. User Task Matrix.
### 2.3.3. User Journey Mapping.
### 2.3.4. Empathy Mapping.
### 2.3.5. As-is Scenario Mapping.
## 2.4. Ubiquitous Language.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
<tr>
    <td>Epic / Story ID</td>
    <td>Titulo</td>
    <td>Descripción</td>
    <td>Criterios de Aceptacion</td>
    <td>Relacionado con (Epic ID)</td>
</tr>
<tr>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
    <td>texto</td>
  </tr>
</table>

## 3.3. Impact Mapping.
## 3.4. Product Backlog.

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
### 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.
## 4.8. Database Design.
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.X. Sprint n
#### 5.2.X.1. Sprint Planning n.
#### 5.2.X.2. Sprint Backlog n.
#### 5.2.X.3. Development Evidence for Sprint Review.
#### 5.2.X.4. Testing Suite Evidence for Sprint Review.
#### 5.2.X.5. Execution Evidence for Sprint Review.
#### 5.2.X.6. Services Documentation Evidence for Sprint Review.
#### 5.2.X.7. Software Deployment Evidence for Sprint Review.
#### 5.2.X.8. Team Collaboration Insights during Sprint.
## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
### 5.3.2. Registro de Entrevistas.
### 5.3.3. Evaluaciones según heurísticas.

# Conclusiones
## Conclusiones y recomendaciones.
## Video About-the-Team.
# Bibliografía
# Anexos
<<<<<<< HEAD

Repositorio GitHub: 
=======
>>>>>>> 70f0313112ccd091315ae071927a516f03a9108a
