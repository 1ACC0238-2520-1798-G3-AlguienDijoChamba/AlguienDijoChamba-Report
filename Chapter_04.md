## **Capítulo IV: Product Implementation & Validation**
  - **4.1. Software Configuration Management**<br>
  En esta sección se definen las convenciones que garantizan la coherencia del proyecto a lo largo de su ciclo de vida.
    - **4.1.1. Software Development Environment Configuration**
    Para el desarrollo del AlguienDijoChamba usamos las siguientes herramientas: 
      #### Requirements Management:
        - **UxPressia**<br>
        Plataforma especializada en el desarrollo y gestión de componentes de experiencia de usuario. Mediante esta herramienta se elaboraron los artefactos de Needfinding, incluyendo User Personas, Journey Maps, Empathy Maps e Impact Maps.
        <br><br>
        <div align="center">
        <img src="https://uxpressia.com/blog/wp-content/uploads/2022/08/2.png" width="150">
        </div>

        - **Miro**<br>
        Herramienta de colaboración visual que facilitó la creación de diagramas, flujos de trabajo y especialmente el desarrollo de sesiones de EventStorming.
        <br><br>
        <div align="center">
        <img src="https://logos-world.net/wp-content/uploads/2023/09/Miro-Logo.jpg" width="250">
        </div>

      #### Product UX/UI Design:

        - **Figma**<br>
        Plataforma de diseño colaborativa empleada para el desarrollo de la capa de presentación de la aplicación móvil, landing page y prototipos interactivos. Permite simular y validar la navegación e interacciones planteadas para la experiencia de usuario.
        <br><br>
        <div align="center">
        <img src="https://cdn.sanity.io/images/599r6htc/regionalized/5094051dac77593d0f0978bdcbabaf79e5bb855c-1080x1080.png?w=540&h=540&q=75&fit=max&auto=format" width="150">
        </div>

      #### Software Development

        - **Visual Studio Code**<br>
        Editor de código fuente desarrollado por Microsoft, utilizado para la implementación del frontend mediante HTML, CSS y JavaScript en la landing page del proyecto.
        <br><br>
        <div align="center">
        <img src="https://live.mrf.io/statics/i/ps/www.muylinux.com/wp-content/uploads/2019/07/vscode.jpg" width="300">
        </div>
        <br>

        - **Android Studio**<br>
        Entorno de desarrollo oficial para Android, basado en IntelliJ IDEA. Empleado para el desarrollo nativo de la aplicación móvil propuesta en el proyecto.
        <br><br>
        <div align="center">
        <img src="https://uxwing.com/wp-content/themes/uxwing/download/brands-and-social-media/android-studio-icon.png" width="150">
        </div>
        <br>


      #### Software Deployment

        - **Git**
        Sistema de control de versiones distribuido que permite mantener un historial detallado de modificaciones y facilitar la colaboración entre los miembros del equipo.
        <br><br>
        <div align="center">
        <img src="https://git-scm.com/images/logos/downloads/Git-Logo-1788C.svg" width="180">
        </div>
        <br>

        - **GitHub**
        Plataforma de alojamiento que optimiza la colaboración mediante gestión de ramas e integración continua. Adicionalmente, se utiliza GitHub Pages para el despliegue automatizado de la landing page.
        <br><br>
        <div align="center">
        <img src="https://logos-world.net/wp-content/uploads/2020/11/GitHub-Logo.png" width="180">
        </div>
    - **4.1.2. Source Code Management**
    La gestión del proyecto de la aplicación móvil, landing page y aplicación Backend, siguen los principios del modelo "Git Branch Model" en la cual se define como una estrategia para administrar y organizar un trabajo en un repositorio de Github mediante la creación de ramas con distintas funcionalidades. Uno de los modelos que usaremos es el "Git Flow", la cual define como crear ramas para mantener el control del ciclo de vida del desarrollo del software.
     ---   
    **Repositorio de Landing Page:** [https://github.com/1ACC0238-2520-1798-G3-AlguienDijoChamba/AlguienDijoChamba---Landing_Page](https://github.com/1ACC0238-2520-1798-G3-AlguienDijoChamba/AlguienDijoChamba---Landing_Page)

    **Repositorio de Aplicación Móvil:** [https://github.com/1ACC0238-2520-1798-G3-AlguienDijoChamba/AlguienDijoChamba---Fronted](https://github.com/1ACC0238-2520-1798-G3-AlguienDijoChamba/AlguienDijoChamba---Fronted)

    **Repositorio de Backend:** [https://github.com/1ACC0238-2520-1798-G3-AlguienDijoChamba/AlguienDijoChamba---Backend](https://github.com/1ACC0238-2520-1798-G3-AlguienDijoChamba/AlguienDijoChamba---Backend)
    
     ---

      **Estructura de ramas**

      1. Rama main(Rama Principal): Esta rama mantiene las versiones definitivas del código. Toda modificación debe ser previamente validada y probada en otras ramas antes de su incorporación.<br><br>

      1. Rama develop(Rama de Desarrollo): En esta rama se centraliza el desarrollo colaborativo, integrando progresivamente cada funcionalidad hasta estabilizarlas para su posterior merge a main.<br><br>

      1. Rama feature(Rama de Caracteristicas): Estas ramas, derivadas de `develop`, tienen como propósito exclusivo el desarrollo de nuevas características. Una vez implementadas y validadas, se fusionan nuevamente con la rama de desarrollo. Aunque por naturaleza son temporales, en el caso específico de la Landing Page se conservarán con fines documentales.<br><br>

      4. Convenciones de Commits: Para los mensajes de commit, seguimos la especificación Conventional Commits con la siguiente estructura:

                "(tipo):(titulo)" y "(descripcion)"

    - **4.1.3. Source Code Style Guide & Conventions**

    Para el desarrollo de AlguienDijoChamba, hemos empleado los siguientes lenguajes y tecnologías:

    **Next.js**<br>
    Como framework full-stack hemos implementado Next.js con las siguientes prácticas:

    - **Estructura de proyecto:**
      Organización estándar con directorios app/ para routing, components/ para componentes reutilizables y lib/ para utilidades y configuraciones.

    - **Renderizado híbrido:**
      Combinación de Server-Side Rendering (SSR) para contenido dinámico y Static Site Generation (SSG) para páginas estáticas optimizando el SEO y performance.

      **React**<br>
      Para el desarrollo de la interfaz de usuario hemos utilizado React con las siguientes convenciones:

      - **Componentes funcionales:**
        Implementación de componentes basados en funciones con Hooks para el manejo de estado y efectos secundarios.

      - **Estructura de componentes:**
        Organización modular con componentes reutilizables, separación de lógica de presentación y custom hooks para funcionalidades compartidas.

      **CSS**<br>
      Hemos adoptado la metodología BEM y guías de estilo establecidas:

      - **Nomenclatura descriptiva:**
        Las clases siguen el formato "kebab-case" en inglés, facilitando la identificación de su propósito.

      - **Mejoras de experiencia de usuario:**
        Implementación de transiciones suaves en interacciones y efectos de botones.

      - **Recursos tipográficos:**
        Carga optimizada de fuentes personalizadas mediante `@font-face`, siguiendo mejores prácticas de rendimiento.

      **.NET**<br>
      Para el desarrollo del API Restful hemos seguido las convenciones estándar de Microsoft:

      - **Convenciones de nomenclatura:**
        Uso de PascalCase para clases y métodos, y lowerCamelCase para parámetros y variables.

      - **Arquitectura limpia:**
        Implementación de Clean Architecture y principios Domain Driven Design, organizando el proyecto en capas diferenciadas (Aplicación, Infraestructura, Dominio y Presentación).

      **Kotlin (Android Studio)**
      Desarrollo móvil bajo las guías de estilo de Kotlin:

      - **Arquitectura escalable:**
        Implementación de Clean Architecture con separación por capas (Repositorios, UI, Casos de Uso y Dominios) siguiendo principios DDD.
    - **4.1.4. Software Deployment Configuration**

      **Landing Page:**<br>
      Para el despliegue de la Landing Page, utilizaremos **Netlify**, usando el servico integrado de enlace con GitHub.

      1. Ingresamos a netlify, y seleccionamos import git
      <br><br><img src="./feature/chapter04/deploy_step1.jpeg">     
      1. Elegimos importar de github un proyecto
      <br><br><img src="./feature/chapter04/deploy_step2.jpeg">
      1. Configuramos o enlazamos netlify con github
      <br><br><img src="./feature/chapter04/deploy_step3.jpeg">
      1. Seleccionamos nuestro repositorio
      <br><br><img src="./feature/chapter04/deploy_step4.jpeg">
      1. Seleccionamos el repositorio del landing page
      <br><br><img src="./feature/chapter04/deploy_step5.jpeg">
      1. Definimos el nombre de nuestro link
      <br><br><img src="./feature/chapter04/deploy_step6.jpeg">
      1. Definimos variables y le damos a deploy
      <br><br><img src="./feature/chapter04/deploy_step7.jpeg">
      1. Esperamos que termine el proceso
      <br><br><img src="./feature/chapter04/deploy_step8.jpeg">
      1. Ingresamos a nuestro link
      <br><br><img src="./feature/chapter04/deploy_step9.jpeg">
      1. Ingresamos a nuestra pag
      <br><br><img src="./feature/chapter04/deploy_step10.jpeg">

      **Enlace del Landing Page:** [https://alguiendijochamba-landingpage.netlify.app/](https://alguiendijochamba-landingpage.netlify.app/)
  - **4.2. Landing Page & Mobile Application Implementation**
    - **4.2.1. Sprint 1**<br>
    La siguiente sección detalla los resultados del Sprint #1, correspondiente a la entrega inicial del proyecto. Se presentan los avances organizativos, la distribución de trabajo y los productos desarrollados: la landing page operativa, el progreso del Web Service y la versión preliminar de la Mobile Application.
      - **4.2.1.1. Sprint Planning 1**<br>
        <table>
          <tr>
            <th> Sprint # </th>
            <th> Sprint 1 </th>
          </tr>
          <tr>
            <td style="font-weight: bold;" colspan="2"> Sprint Planning Background </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Date </td>
            <td> 29/09/2025 </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Time </td>
            <td> 00:38 horas (GMT-5) </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Location </td>
            <td> Virtual (Google Meet) </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Prepared By </td>
            <td> Bastidas Bastidas, Diego Martin </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Attendees (to planning meeting) </td>
            <td>
              Bastidas Bastidas, Diego Martin<br>
              Belahonia Miranda, Fabrisio<br>
              Dominguez Vargas, Rafael Alexander<br>
              Escobar Palomino, Sebastian Matias<br>
              Muñiz Huayanca, Percy Alonso	
            </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Sprint 1 Review Summary </td>
            <td> Dado que este es el primer sprint de desarrollo, no contamos con un review summary previo. </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Sprint 1 Retrospective Summary </td>
            <td> Al ser el primer sprint, aún no hemos identificado áreas específicas de mejora para el proceso. </td>
          </tr>
          <tr>
            <td style="font-weight: bold;" colspan="2"> Sprint Goal & User Stories </td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Sprint 1 Goal </td>
            <td></td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Sprint 1 Velocity </td>
            <td></td>
          </tr>
          <tr>
            <td style="font-weight: bold;"> Sum of Story Points </td>
            <td>  </td>
          </tr>
        </table>
      - **4.2.1.2. Sprint Backlog 1**
      - **4.2.1.3. Development Evidence for Sprint Review**
      - **4.2.1.4. Testing Suite Evidence for Sprint Review**
      - **4.2.1.5. Execution Evidence for Sprint Review**
      - **4.2.1.6. Services Documentation Evidence for Sprint Review**
      - **4.2.1.7. Software Deployment Evidence for Sprint Review**
      - **4.2.1.8. Team Collaboration Insights during Sprint**
  - **4.3. Validation Interviews**
    - **4.3.1. Diseño de Entrevistas**
    - **4.3.1. Registro de Entrevistas**
    - **4.3.1. Evaluaciones según heurísticas**
## **Conclusiones**
## **Conclusiones y recomendaciones**
## **Video App Validation**
## **Video About the product**
## **Video About the team**
## **Glosario**
## **Bibliografía**
## **Anexos**