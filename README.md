</div>

<h2 align="center">Informacion sobre mi</h2>

<div align="center">
  
  Soy estudiante de [Ingeniería en Informática](https://cms.fi.uba.ar/uploads/RESCD_2023_526_Informatica_Plan_2023_Aprobacion_15d3cee700_6e3b075bd4.pdf) en la Universidad de Buenos Aires (UBA), tengo 24 años y actualmente me quedan 10 materias para terminar la carrera.
  
</div>

<h2 align="center">Lenguajes de programacion y herramientas</h2>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/git/git-original.svg" alt="git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/github/github-original.svg" alt="git" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/gitlab/gitlab-original.svg" alt="git" width="40" height="40"/>
</p>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/react/react-original.svg" alt="react" width="40" height="40"/>
</p>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/python/python-original.svg" alt="python" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/c/c-original.svg" alt="c" width="40" height="40"/> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/go/go-original-wordmark.svg" alt="go" width="40" height="40"/>
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/java/java-original.svg" alt="java" width="40" height="40"/> 
</p>

<p align="center">
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/nodejs/nodejs-plain-wordmark.svg" alt="nodejs" width="40" height="40"/>
</p>

<p align="center"> 
  <img src="https://github.com/devicons/devicon/blob/v2.15.1/icons/postgresql/postgresql-original.svg" alt="java" width="40" height="40"/> 
</p>

<h2 align="center">Proyectos de FIUBA</h2>


<div align="center">
  <h3 align="center">PlanMe</h3>
  <p align="center">
    Destacó como producto a <a href="https://gestion-fiuba-plan-me.web.app/login">PlanMe</a>, una <b>aplicación web</b> que centraliza la planificación, coordinación y seguimiento del evento en un solo lugar. Es un producto que asiste activamente al usuario en la planificación de su evento, guiándolo con un roadmap inteligente, sugerencias y notificaciones. Le brinda al usuario un soporte completo: Desde la primera idea, hasta el RSVP de los invitados, acompañando al usuario organizador durante todo el proceso.

  Surge como una propuesta del equipo para la materia <b>Gestión del Desarrollo de Sistemas Informáticos</b>, curso <b>Fontela</b>, de la Facultad de Ingeniería de la Universidad de Buenos Aires (<b>FIUBA</b>).

  <details>
  <summary><b>Más detalles acerca del proyecto</b></summary>
  <br>

  ¿Que se hizo antes de empezar con el desarrollo?. En las primeras semanas previo a comenzar con el desarrollo se iteraron distintos artefactos de <b>Lean Inception</b> y <b>Alcance</b>:

  <table style="margin: 0 auto; border-collapse: collapse; text-align: center;">
    <tbody>
      <tr><td>Lean Inception</td><td>Product Vision, Personas, E/NE/H/NH</td></tr>
      <tr><td>Alcance</td><td>Features, User Story Mapping, WBS, Backlog US, Cronograma</td></tr>
    </tbody>
  </table>

  Además de esto, se trabajo con artefactos de soporte: <b>Análisis de riesgos</b>, <b>Plan de comunicación</b>, <b>Plan de costos</b>.

  Tras comenzar con el desarrollo se llevo un seguimiento con graficos para la <b>Velocity</b>, <b>Burn Up</b> y <b>Burn Down</b>.

  ¿Como fue el proceso de desarrollo?.

  La colaboración y el versionado del código se gestionó en <b>GitHub</b>, donde el equipo decidio mantener todo en un mismo repositorio (<b>mono repo</b>) y en un mismo lenguaje porque sabíamos que nos íbamos a apoyar mucho en herramientas de IA durante el desarrollo y la idea del equipo era que la IA pudiera entender mejor el proyecto completo para poder desarrollar features de punta a punta.

 ¿Que tecnologias usamos para desarrollar nuestro producto?:

 <table style="margin: 0 auto; border-collapse: collapse; text-align: center;">
    <tbody>
      <tr><td>Frontend</td><td>Trabajamos con <b>React</b>, <b>Vite</b> y <b>TypeScript</b></td></tr>
      <tr><td>Backend</td><td>Construimos una API REST con <b>Node.js</b>, <b>Express</b>, <b>TypeScript</b> y <b>TypeORM</b>, usando <b>PostgreSQL</b> como base de datos</td></tr>
    </tbody>
  </table>

 El frontend fue desplegado en <b>Firebase Hosting</b>, el backend fue desplegado en <b>Render</b> y la base de datos fue desplegada en <b>Supabase</b>.

 Las iteraciones fueron de miercoles a miercoles, donde en cada iteración tuvimos:

 <table style="margin: 0 auto; border-collapse: collapse; text-align: center;">
    <tbody>
      <tr><td>Planning</td><td>Como equipo tomábamos US de nuestro <b>backlog</b>, definiamos los criterios de aceptación y estimabamos mediante estimación relativa</td></tr>
      <tr><td>Desarrollo</td><td>Trabajamos con un esquema de entrega continua de tal forma que todo este en producción al final de la iteración</td></tr>
      <tr><td>Retro</td><td>Trabajamos con un tablero con las columnas <b>Start Doing</b>, <b>Stop Doing</b>, <b>Keep Doing</b> y <b>Action Items</b></td></tr>
      <tr><td>Demo</td><td>Demo de las US desarrolladas ante nuestro PO</td></tr>
    </tbody>
  </table>

 Los criterios de aceptación los escribimos como <b>Gherkins</b>, con escenarios en formato <b>Given</b>/<b>When</b>/<b>Then</b> y ejemplos concretos para evitar cualquier tipo de ambigüedad. Y en lugar de dejarlos solo como documentación, lo que hicimos fue convertir directamente esos criterios en tests automatizados, usando <b>Cucumber</b>. 

 Trabajamos usando <b>GitHub Projects</b> para poder planificar, organizar y realizar un seguimiento del trabajo y de las US en cada iteración. Dentro de <b>Github Project</b> trabajamos con un tablero Kanban con las columnas <b>To Do</b>, <b>In progress</b>, <b>In review</b> y <b>Done</b>.

 Definimos trabajar con <b>features-branches</b> y la integración a <b>main</b> mediante <b>PRs</b> para tener trazabilidad completa y asegurarnos que siempre al menos la mitad del equipo esté al tanto de los cambios implementados.

 Definimos varios <b>workflows</b> de <b>CI/CD</b> en el repositorio para automatizar la ejecución de formato, linters, build, ejecución de los tests y despliegue.

 Por último, con todas estas decisiones que tomo el equipo, antes de empezar con el desarrollo armamos nuestro <b>Definition of Ready</b> y nuestro <b>Definition of Done</b> que nos guiaron durante todas las iteraciones.

 ¿Cómo trabajamos?. Cada uno de los integrantes del equipo se asignaba el issue en el cual iba a trabajar y se movía a la columna <b>In progress</b> para empezar a trabajar. 
 
 Una vez que la US estaba desarrollada se abría un <b>PR</b>, se movía a la columna <b>In review</b> y, como lo dice nuestro <b>Definition of Done</b>, para poder ser mergeado a <b>main</b> tenían que pasar dos cosas:

 <table style="margin: 0 auto; border-collapse: collapse; text-align: center;">
    <tbody>
      <tr><td>El pipeline de <b>CI</b> tenia que correr sin errores</td></tr>
      <tr><td>Al menos 2 integrantes del equipo revisaron el <b>PR</b> y aprobaron los cambios</td></tr>
    </tbody>
  </table>

 Una vez que pasaba esto, se mergeaba a <b>main</b>, todos los cambios eran deployados en nuestro ambiente de producción y se movía de forma automática la US a la columna <b>Done</b>.

  ¿Qué roles asumimos?. En cada iteración todos los integrantes del equipo escribimos código tanto para el <b>backend</b>, como para el <b>frontend</b>, de tal forma que todos desarrollamos las US de punta a punta con el objetivo de que haya <b>ownership</b> colectivo de todo el código. Esto significa que todos teníamos que poder hacer todo y tener los conocimientos para hacer todo. Además, en cada iteración un integrante tomó el rol de PM, pero sin dejar el rol de desarrollador y también fue el PM de cada iteración quien se encargó de la gestión de los artefactos, particularmente un integrante tuvo que repetir el rol de PM, debido a que eran 7 sprints y eramos 6 integrantes, por lo que yo me ofrecí a cumplir con ese cargo en la ultima semana, cuando tuvimos que pulir el producto y diseñar y practicar la demostración del mismo.

  </details>

  Se puede acceder a su <a href="">repositorio</a> de <b>GitHub</b>, al <a href="">tablero Kanban</a> de <b>Github Project</b>, a los <a href="">artefactos</a> y a una <a href="https://youtu.be/anf5rgWuIKI">demo</a> hecha por mi tras la defensa y aprobación de la materia, con el objetivo de mostrar un poco las funcionalidades principales que el equipo desarrollo.
</div>

---

<div align="center">

---
  <h3 align="center">futbol-5-manager </h3>

  <p align="center">
    Destacó como proyecto Una webapp diseñada para gestionar y organizar partidos amateur de futbol 5,  con funcionalidades que permiten registrar equipos, organizar partidos y actualización en tiempo real de goles, construida con react y Spring Boot.
    Este proyecto fue mi primer practica en el concepto de desarrollo Agil, que luego fue profundizada en PlanMe. Como en PlanMe, tuvimos que diseñar nosotros el enunciado, las funcionalidades y los clientes, por medio de entrevistas e investigación formamos las primeras ideas.
    Luego, en base a estas ideas, desarrollamos usando metodologia Agile en Jira, manteniendo comunicación constante en nuestro equipo de 6 integrantes, resolviendo la distribución de trabajo y la ausencia de nuestro 7mo integrante, con quien nos comunicamos claramente lo que nos permitio resolver la situacion con gracia. Respondiendo a revisiones semanales por parte de nuestro "Cliente", nuestro profesor y puliendo el producto a lo largo de los 2 meses de produccion.
  </p>

  <details>
  <summary><b>Más detalles acerca del proyecto</b></summary>
  <br>

  Utilizamos la técnica de **[User Story Mapping](https://10pines.gitbook.io/desarrollo-de-software-agil-en-10pines/product-discovery#user-story-mapping)** para relevar las funcionalidades. 

  
  El flujo de trabajo fue el siguiente: primero relevamos las funcionalidades y presentamos un release plan a nuestro Product Owner (PO), quien definió cuál sería el MVP. A partir de allí, en cada iteración (con excepción de la primera, que tuvo solo Planning), los lunes  realizábamos **Review, Planning y Retrospective**, y durante la semana trabajábamos en un esquema de entrega continua. Esto significaba que cada funcionalidad (User Story) debía estar validada en producción antes de llegar a la Review, para lo cual definimos un proceso claro: Al comienzo de cada iteracion le comunicabamos a nuestro PO el alcance de la iteracion (es decir, que US entraban en la iteracion donde cada US tenia su estimacion relativa). Antes de comenzar con el desarrollo de cada User Story debíamos enviar al PO los **Gherkin** correspondientes, que él validaba y autorizaba. Una vez que la funcionalidad estaba completa, se desplegaba en el ambiente de test para que el PO pudiera testearla y, tras su aprobación, se realizaba el deploy a producción. De esta manera, siempre llegábamos a la Review con todas las funcionalidades ya disponibles en producción y validadas por el cliente. 

  En cuanto a las metodologías aplicadas, trabajamos con **[BDD y TDD](https://drive.google.com/file/d/1whj-ZLlxVoHNaUnE6a8ckv_XHj9L7wg1/view?usp=sharing)**. La **forma de trabajo** se basó en integración continua, desarrollo en un único branch con trunk-based development, pair y mob programming, y un esquema de entrega continua. La colaboración y el versionado del código se gestionaron en **GitLab**, lo que nos permitió organizar el trabajo de manera centralizada y garantizar la integración continua. 
</div>

---

<div align="center">
  <h3 align="center">Teoría de Algoritmos</h3>
  <p align="center">
    Destacó la realización de trabajos prácticos correspondientes a la materia <a href="https://algoritmos-rw.github.io/tda_bg/">Teoría de Algoritmos</a>, donde se estudiaron los siguientes temas:
  </p>

  <table style="margin: 0 auto; border-collapse: collapse; text-align: center;">
    <tbody>
      <tr><td>1</td><td>División y Conquista avanzada</td></tr>
      <tr><td>2</td><td>Algoritmos Greedy</td></tr>
      <tr><td>3</td><td>Programación Dinámica</td></tr>
      <tr><td>4</td><td>Backtracking</td></tr>
      <tr><td>5</td><td>Programación Lineal</td></tr>
      <tr><td>6</td><td>Redes de Flujo</td></tr>
      <tr><td>7</td><td>Reducción de problemas</td></tr>
      <tr><td>8</td><td>Clases de Complejidad</td></tr>
    </tbody>
  </table>
  
  <p align="center">
    Se realizaron 3 trabajos prácticos grupales que evaluaron el desarrollo y análisis de los distintos algoritmos.
   
   Se puede acceder a su <a href="https://github.com/mmosan/TDA">repositorio</a> de GitHub, donde se encuentra el desarrollo y análisis de cada algoritmo.

  </p>
</div>

---
<h2 align="center">Estadisticas</h2>

<p align="center">
  <img src="./github-metrics.svg" alt="GitHub Metrics" />
</p>

<h2 align="center">Contacto</h2>
<div align="center">
  
  [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/felipe-martin-santellan-998331382/)
  
</div>
