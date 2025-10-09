## **Capítulo III: Solution UI/UX Design**
  - **3.1. Product design**
    - **3.1.1. Style Guidelines**
      
        Esta sección establece las bases visuales y comunicacionales de Fix Now, garantizando coherencia en toda la experiencia digital. Se crea un repositorio común para el equipo con assets gráficos, fuentes y reglas visuales que mantienen una presentación profesional, accesible y funcional.

      - **3.1.1.1. General Style Guidelines**
        
        <br >**Nombre y logotipo** <br> <br>
        El nombre de la aplicación, es AlguienDijoChamba, transmite innovación, profesionalismo y un enfoque claro en la gestión de servicios de reparación y mantenimiento del hogar. El logotipo de AlguienDijoChamba está compuesto por una casa y una llaves inglesas incrustada que representa el trabajo de los tecnicos pedidos a domicilio. Este símbolo representa de forma clara y directa la especialización en servicios técnicos. El diseño limpio y geométrico asegura una fácil identificación y recordatorio de la marca.
        <br>
        ![Logo](feature/chapter3/Illustrations_and_Imagery.png)
        <br><br>**Tono de comunicación** <br> <br>
        El tono de comunicación será profesional y accesible, transmitiendo confianza sin perder la cercanía ni la calidez. Se evitará el uso de tecnicismos innecesarios y se privilegiará un lenguaje claro y sencillo que facilite la comprensión. La aplicación se expresará como un asistente confiable y siempre dispuesto a colaborar, ofreciendo ayuda de manera oportuna pero sin resultar invasiva.
        <br><br>**Colors** <br> <br>
        La paleta de colores se basa principalmente en tonos de azul, que transmiten confianza, profesionalismo y seguridad. Estos se complementan con acentos en naranja y amarillos cálidos, que aportan energía, dinamismo y cercanía, generando un contraste vibrante y atractivo. Como colores secundarios se utilizan blanco, negro y gris, que equilibran la composición, mejoran la legibilidad y refuerzan una estética limpia y moderna. Esta combinación proyecta una imagen clara, ordenada y a la vez amigable y dinámica, logrando un balance entre seriedad profesional y calidez accesible para los usuarios.
        <br>
        ![Color](feature/chapter3/Colors.png)
        <br><br>**Typography** <br> <br>
        La tipografía principal utilizada es Arimo, elegida por su legibilidad, estilo moderno y versatilidad en entornos digitales. Se aplican diferentes tamaños para jerarquizar la información: los títulos emplean un tamaño grande y peso seminegrita para destacar, los subtítulos utilizan un tamaño medio con peso regular o medio, y el texto normal mantiene un tamaño cómodo para la lectura continua, con un peso regular.      
        <br>
        ![Typography](feature/chapter3/Typography.png)
        <br><br>**Spacing** <br> <br>
        En nuestra app móvil aplicamos un sistema de spacing consistente para mantener una estructura visual ordenada y accesible. Se utilizan márgenes de 19.5px entre secciones principales, un padding interno de 18px en botones y componentes, y un interlineado de 1.5x en los textos largos para optimizar la lectura. El layout se organiza en una rejilla de 4 columnas, con alineación centrada, un ancho de columna de 78px y un gutter de 16px entre ellas. Esta configuración asegura equilibrio, claridad y consistencia en toda la interfaz.
        <br>
        ![Spacing](feature/chapter3/Spacing.png)
        <br><br>**Iconos de aplicación** <br> <br>
        La aplicación emplea un conjunto de íconos minimalistas y uniformes, seleccionados para potenciar la experiencia del usuario y mantener una coherencia visual en toda la interfaz. Cada ícono tiene un propósito definido y se integra de manera consistente con la identidad de la marca, reforzando claridad y armonía en el diseño.
        <br>
        ![Spacing](feature/chapter3/Iconography.png)
        <br><br>**Lenguaje Aplicado** <br> <br>
        En el desarrollo de la aplicación móvil “FIX IT” y de su landing page se ha definido un lenguaje formal, claro y cercano, alineado con el propósito y los objetivos del producto. Tanto en el diseño como en la construcción de la app y la página de aterrizaje, se han aplicado los principios fundamentales del diseño visual, asegurando coherencia, consistencia y una comunicación efectiva.

    - **3.1.2. Information Architecture**
      - **3.1.2.1. Organization Systems**
      Vamos a implementar diversos sistemas de organización según el tipo de contenido que se presente, con el objetivo de facilitar la comprensión, la navegación y la forma que interactue el usuario con nuestro app mobil.
      <br><br> **Organización visual del contenido**<br>
        - **Jerárquica(Visual Hierarchy):**<br>
          Usamos la jerarquía visual para destacar el mensaje más importante, que aparece en este encabezado. La información se organiza de manera que primero llame la atención lo principal y luego los detalles secundarios, como textos explicativos o botones, para guiar al usuario de forma clara.
          <br><br>
        - **List Vertical(List View):**<br>
          Aplicaremos una organización en lista vertical cuando queramos mostrar elementos en orden secuencial, como mensajes, tareas o historial de acciones. Esto permite al usuario recorrer la información de manera lineal y enfocarse en cada Tecnico uno a la vez, facilitando la lectura y la navegación dentro de la app.
          <br>
      <br> **Esquemas de categorización de contenido**<br>
        -  **Por topicos:** Se utilizará cuando el contenido pueda organizarse en categorías o temas específicos, facilitando que el usuario encuentre información relacionada o explore áreas de interés de manera lógica.
        - **Secuencial:** Se aplicará cuando el contenido deba presentarse en un orden cronológico o lógico, guiando al usuario a través de procesos, instrucciones o tutoriales de manera estructurada.
        - **Relevancia:** Se usará para destacar el contenido que ha recibido mayor interacción, vistas o valoración, permitiendo al usuario acceder primero a lo más relevante o buscado.
        - **Tags:** Se empleará cuando el contenido pueda asociarse con palabras clave o etiquetas, facilitando la búsqueda y el filtrado según intereses específicos del usuario.
        - **Cronológico:** Se aplicará cuando sea importante mostrar el contenido en función de fechas o eventos, permitiendo que el usuario siga la evolución o historia de manera temporal.
      - **3.1.2.2. Labelling Systems**
        <br>La interfaz de nuestra aplicación está diseñada para ser intuitiva y fácil de usar, utilizando palabras clave que resulten familiares para nuestros usuarios. Por esta razón, las etiquetas de navegación explican de manera concisa la función de cada sección. A continuación, presentamos las etiquetas principales para los dos roles de la aplicación: Cliente y Técnico.
        <br>**Client**<br>
        - **Home:** Página principal con vistas rápidas, notificaciones y accesos directos a todas las funciones importantes de la app.
        - **Search:** Buscar técnicos disponibles según tipo de trabajo , con filtros por ubicación, calificación y disponibilidad.
        - **Process:** Seguimiento de las solicitudes de servicios enviadas, con detalles del técnico asignado, estado del trabajo y fecha programada.
        - **Rewards:** Beneficios y recompensas por contratar servicios a través de la app.
        - **Profile:** Gestión de información personal y datos de contacto.
    
        <br>**Tecnico**<br>
        - **Home:** Página principal con vistas rápidas, notificaciones de nuevos trabajos y accesos directos a todas las funciones importantes de la app.
        - **Request:** Visualizar, aceptar o rechazar solicitudes de trabajo de clientes, con información del tipo de servicio y ubicación.
        - **Calendar:** Calendario de trabajos programados, mostrando fecha, hora y dirección de cada servicio asignado.
        - **Payments:** Registrar pagos recibidos por los trabajos realizados y consultar historial de ingresos.
        - **Profile:** Gestionar informacion personal.
      - **3.1.2.3. SEO Tags and Meta Tags**
        <br> Tenemos lo que es Optimización SEO para Mayor Visibilidad en Plataformas Móviles,  donde se han implementado estrategias de posicionamiento en tiendas de aplicaciones (ASO – App Store Optimization), utilizando títulos, descripciones y palabras clave relevantes para que AlguienDijoChamba sea fácilmente encontrada por clientes que buscan contratar técnicos de diferentes especialidades, así como por técnicos que deseen ofrecer sus servicios.<br>
        - **Titulo:** “AlguienDijoChamba – Encuentra técnicos confiables cerca de ti”
        - **Descripción de la App:** “Conecta con técnicos especializados en plomería, carpintería, electricidad y más. Solicita servicios desde tu móvil, agenda citas y gestiona pagos de manera rápida y segura.”
        - **Palabras Clave:**: “contratar técnicos, servicios a domicilio, plomero, carpintero, electricista, app de servicios, AlguienDijoChamba”
      - **3.1.2.4. Searching Systems**
        En nuestra app movil tendremos diversidad de tecnicos registrados, por lo cual nos ha resultado crucial brindar herramientas de busqueda para que ayuden a los Clientes en encontrar al tecnico mas adecuado para su caso.
        <br><br>
        **Búsqueda por palabra clave:**
        El usuario puede ingresar directamente lo que necesita, como “electricista”, “plomero” o “arreglar fuga de agua”. El sistema mostrará técnicos y servicios relacionados de inmediato.
        <br><br>
        **Filtros por especialidad y ubicación:**<br>
        Además del buscador, se incluyen filtros desplegables para seleccionar el tipo de oficio. Esto ayuda a acotar resultados de manera eficiente.
        <br><br>
        **Filtros por calificación y experiencia:**<br>
        Los usuarios pueden ordenar a los técnicos según su valoración promedio, años de experiencia o número de servicios completados, facilitando la elección del más confiable.
        <br><br>
      **Busqueda por problema en el hogar:**<br>
        Si el usuario no sabe exactamente qué tipo de técnico necesita, podrá escribir el problema directamente y el sistema sugerirá automáticamente al especialista adecuado.
      - **3.1.2.5. Navigation Systems**
        <br> En AlguienDijoChamba buscamos ofrecer la mejor experiencia a nuestros usuarios, garantizando que la interfaz sea clara, simple y funcional. Por ello, hemos definido las siguientes decisiones de diseño de interfaz (UI):
        <br> **Landing Page (promoción de la app):**<br>
        - La navegación de la Landing Page hará uso del scroll vertical, ya que es la forma más intuitiva y natural para los usuarios en páginas informativas.
        - La página contará con una barra de menú superior fija, que se mantiene visible mientras el usuario navega hacia abajo. Esta barra tendrá enlaces a las secciones: Inicio, Producto, Servicio, Testimonio y Contactos.
          <br> <br>**Aplicación Móvil:**<br>
        - La aplicación contará con un menú de navegación inferior (bottom navbar) con accesos rápidos a las secciones principales: Home, Search, Process, Rewards, ProfileClients y Home, Requests, Calendar, Payments, ProfileTechnique.
        - En la navegación entre pantallas, se incluirá siempre una opción para volver atrás, asegurando que el usuario tenga control total de su recorrido dentro de la app.
        <br><br>**Accesibilidad y Usabilidad:** La aplicación está diseñada con Responsive Design, lo que asegura que se adapte correctamente a distintos tamaños de pantalla dentro del ecosistema móvil.
    - **3.1.3. Landing Page UI Design**
      - **3.1.3.1. Landing Page Wireframe**
        <br>
        **Enlace al Figma de la Landing Page:** https://www.figma.com/design/ZcdFsusLeG4RP5GM0TwIpB/Landing-Page?node-id=0-1&t=e2lefX3uya8tLLM5-1
        <br>A continuación, se muestra la landing page tal como se visualiza desde un navegador web.<br><br>
        ![imagesWireframe1](./feature/chapter3/Landing_Wireframe.png)

      - **3.1.3.2. Landing Page Mock-up**
        <br>
        **Enlace al Figma de la Landing Page:** https://www.figma.com/design/ZcdFsusLeG4RP5GM0TwIpB/Landing-Page?node-id=0-1&t=e2lefX3uya8tLLM5-1
        <br>El wireframe para desktop guió la disposición de los elementos, y el mock-up finalizo con las secciones propuestas.<br><br>
        ![imagesWireframe1](./feature/chapter3/Landing_Mock_Ups.png)
        <br><br>
    - **3.1.4. Mobile Applications UX/UI Design**
      - **3.1.4.1. Mobile Applications Wireframes**
        <br>
        **Enlace al Figma del Mobil Application Wireframes:** https://www.figma.com/design/PeLAC5bn6HtSfybmA78rXe/Wireframes?t=e2lefX3uya8tLLM5-1
      
        ### **Users**
        **Inicio de Sesion Cliente**<br>
        ![imagesWireframeMobileApplication1](./feature/chapter3/Mobile_Applications_Wireframes/Users/Inicio_Client.png)
        <br>
        <br>**Registro Cliente**<br>
        ![imagesWireframeMobileApplication2](./feature/chapter3/Mobile_Applications_Wireframes/Users/Registro_Client.png)
        <br>
        ![imagesWireframeMobileApplication3](./feature/chapter3/Mobile_Applications_Wireframes/Users/Registros_Client_2.png)
        <br>
        <br>**Main**<br>
        ![imagesWireframeMobileApplication4](./feature/chapter3/Mobile_Applications_Wireframes/Users/Main_Client.png)
        <br>
        <br>**Rewards Section**<br>
        ![imagesWireframeMobileApplication5](./feature/chapter3/Mobile_Applications_Wireframes/Users/Rewards_Clients.png)
        <br>
        <br>**Search Section**<br>
        ![imagesWireframeMobileApplication6](./feature/chapter3/Mobile_Applications_Wireframes/Users/Search_CLient.png)
        <br>
        ### **Technician**
        **Inicio de Sesion**<br>
        ![imagesWireframeMobileApplication7](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Inicio_Tecnician.png)
        <br>
        ![imagesWireframeMobileApplication8](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Inicio_Tecnician_2.png)
        <br>
        <br>**Registro**<br>
        ![imagesWireframeMobileApplication8](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Register_Tecnician_1.png)
        <br>
        ![imagesWireframeMobileApplication9](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Register_Tecnician_2.png)
        <br>
        <br>**Main**<br>
        ![imagesWireframeMobileApplication10](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Main_Tecnician.png)
        <br>
        ![imagesWireframeMobileApplication11](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Main_Tecnician_2.png)
        <br>
        ![imagesWireframeMobileApplication12](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Main_Tecnician_3.png)
        <br>
        <br>**Payments Section**<br>
        ![imagesWireframeMobileApplication13](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Paymenter_Tecnician_1.png)
        <br>
        ![imagesWireframeMobileApplication14](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Payments_Tecnician_2.png)
        <br>
        ![imagesWireframeMobileApplication15](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Payments_Tecnician_3.png)
        <br>
        <br>**Gamification Section**<br>
        ![imagesWireframeMobileApplication16](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Gamification_Tecnician_1.png)
        <br>
        ![imagesWireframeMobileApplication17](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Gamification_Tecnician_2.png)
        <br>
        ![imagesWireframeMobileApplication18](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Gamification_Tecnician_3.png)
        <br>
        <br>**Availability Section**<br>
        ![imagesWireframeMobileApplication19](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Avalibility_Tecnician.png)
        <br>
        ![imagesWireframeMobileApplication20](./feature/chapter3/Mobile_Applications_Wireframes/Technician/Avalibility_Tecnician_2.png)
        <br> <br>
      - **3.1.4.2. Mobile Applications Wireflow Diagrams**
        <br>
        **Enlace al LucidShart del Mobile Applications User Flow Diagrams:** https://lucid.app/lucidchart/d428fcd4-907b-46e0-b414-33d3837168e1/edit?viewport_loc=-6752%2C-1346%2C11674%2C8944%2C0_0&invitationId=inv_0fbb098a-87f0-470f-a144-5961d011abb1
        <br>
        ### **User**
        **Register**<br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/User/1.png)
        <br>
        <br>**Search Configuration**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/User/2.png)
        <br>
        <br>**Rewards Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/User/3.png)
        <br>
        ### **Technician**
        **Register**<br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/Technician/1.png)
        <br>
        <br>**Home Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/Technician/2.png)
        <br>
        <br>**Payments Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/Technician/3.png)
        <br>
        <br>**Calendar Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/Technician/4.png)
        <br>
        <br>**Gamification Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_Wireflow_Diagrams/Technician/5.png)
        <br> <br>
      
      - **3.1.4.3. Mobile Applications Mock-ups**
        <br>
        **Enlace al Figma del Mobile Applications Mock-ups:** https://www.figma.com/design/gixtO1KKFxurOMzcb4xiw6/Mock-UP?node-id=9-2217&t=e2lefX3uya8tLLM5-1
        <br>
        <br>**Inicio al abrir la app**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/presentacion_1.png)
        <br>
        ![imagesMockUpsMobileApplication2](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/Tipo_usuario.png)
        <br>
        ### **Users**
        **Inicio User**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/2_Inicio_USER_2.png)
        <br>
        <br>**Register**<br>
        <br>
        ![imagesMockUpsMobileApplication3](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/1_register/registro1.png)
        <br>
        ![imagesMockUpsMobileApplication4](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/1_register/registro2.png)
        <br>
        <br>**Home**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/2_Home/home.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/2_Home/home_profile.png)
        <br>
        <br>**Search Section**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/3_search/buscar_tecnicos.png)
        <br>
        <br>**Process Section**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/4_process/process_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/4_process/process_2.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/4_process/process_3.png)
        <br>
        <br>**Rewards Section**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/5_rewards/gamificion.png)
        <br>
        <br>**Profile Section**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/6_profile/profile_user_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/6_profile/profile_user_2.png)
        <br>
        <br>**Chat Section**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/7_chat/chat_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Users/7_chat/chat_2.png)
        <br>
      
        ### **Technician**
        **Register**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/1_register/register_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/1_register/register_2.png)
        <br>
        <br>**Main**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/2_main/main_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/2_main/main_2.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/2_main/main_3.png)
        <br>
        <br>**Calendar**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/3_calendar/Calendar_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/3_calendar/Calendar_2.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/3_calendar/Calendar_3.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/3_calendar/Calendar_4.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/3_calendar/Availability_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/3_calendar/Availability_2.png)
        <br>
        <br>**Payments**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/4_payments/pages_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/4_payments/pages_2.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/4_payments/pages_3.png)
        <br>
        <br>**Profile**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/5_profile/profile_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/5_profile/profile_2.png)
        <br>
        <br>**Gamification**<br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/6_gamification/gamification_1.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/6_gamification/gamification_2.png)
        <br>
        ![imagesMockUpsMobileApplication1](./feature/chapter3/Mobile_Applications_Mock_Ups/Technician/6_gamification/gamification_3.png)
        <br> <br>
      - **3.1.4.4. Mobile Applications User Flow Diagrams**
        <br>
        **Enlace al LucidShart del Mobile Applications User Flow Diagrams:** https://lucid.app/lucidchart/d428fcd4-907b-46e0-b414-33d3837168e1/edit?viewport_loc=-6752%2C-1346%2C11674%2C8944%2C0_0&invitationId=inv_0fbb098a-87f0-470f-a144-5961d011abb1
        <br>
        ### **User**
        **Register**<br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/1.png)
        <br>
        <br>**Profile Configuration**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/2.png)
        <br>
        <br>**Search Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/3.png)
        <br>
        <br>**Process Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/4.png)
        <br>
        <br>**Rewards Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/5.png)
        <br>
        <br>**Chat Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/6.png)
        <br>
        <br>**Edit Profile Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/1_user/7.png)
        <br>
        ### **Technician**
        **Register**<br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/2_technician/1.png)
        <br>
        <br>**Home Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/2_technician/2.png)
        <br>
        <br>**Payments Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/2_technician/3.png)
        <br>
        <br>**Calendar Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/2_technician/4.png)
        <br>
        <br>**Profile Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/2_technician/6.png)
        <br>
        <br>**Gamification Section**<br>
        ![imagesUserFlowDiagramsApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/2_technician/7.png)
        <br> 
        ### **User Stories**
        <br>**US01**<br>
        Como nuevo cliente, quiero registrarme en la plataforma para poder buscar y contratar profesionales.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US01.png)
        <br>
        <br>**US02**<br>
        Como nuevo profesional técnico, quiero registrarme detallando mis especialidades, experiencia y contacto para ofrecer mis servicios.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US02.png)
        <br>
        <br>**US03**<br>
        Como usuario, quiero recuperar mi cuenta o iniciar sesión mediante diferentes métodos.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US03.png)
        <br>
        <br>**US04**<br>
        Como usuario registrado, quiero poder editar la información de mi perfil para mantenerla actualizada.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US04.png)
        <br>
        <br>**US05**<br>
        Como cliente, quiero ver el perfil completo de un profesional con toda su información relevante.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US05.png)
        <br>
        <br>**US06**<br>
        Como cliente, quiero contactar directamente a un profesional para coordinar un servicio.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US06.png)
        <br>
        <br>**US07**<br>
        Como cliente, quiero buscar profesionales filtrando por tipo de servicio y ubicación.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US07.png)
        <br>
        <br>**US08**<br>
        Como cliente, quiero contactar a un profesional y solicitar un servicio.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US08.png)
        <br>
        <br>**US09**<br>
        Como técnico, quiero gestionar mi lista de servicios ofrecidos.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US09.png)
        <br>
        <br>**US10**<br>
        Como técnico, quiero gestionar mi disponibilidad para solicitudes.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US10.png)
        <br>
        <br>**US11**<br>
        Como técnico, quiero recibir notificaciones instantáneas sobre nuevas solicitudes.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US11.png)
        <br>
        <br>**US12**<br>
        Como técnico, quiero aceptar o rechazar solicitudes de trabajo.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US12.png)
        <br>
        <br>**US13**<br>
        Como técnico, quiero marcar un servicio como completado y registrar trabajo final, y recibir el pago instantáneo.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US13.png)
        <br>
        <br>**US14**<br>
        Como cliente, quiero recibir notificaciones cuando un profesional acepta o rechaza mi solicitud.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US14.png)
        <br>
        <br>**US15**<br>
        Como usuario, quiero ver mi progreso y puntos acumulados en el sistema de gamificación.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US15.png)
        <br>
        <br>**US16**<br>
        Como usuario, quiero recibir recompensas al completar logros específicos en la plataforma.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US16.png)
        <br>
        <br>**US17**<br>
        Como cliente, quiero crear solicitud de servicio detallada.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US17.png)
        <br>
        <br>**US18**<br>
        Como cliente, quiero ver el estado de mis solicitudes en tiempo real.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US18.png)
        <br>
        <br>**US19**<br>
        Como cliente, quiero pagar los servicios de forma segura.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US19.png)
        <br>
        <br>**US20**<br>
        Como cliente, quiero solicitar reembolso o iniciar disputa en caso de servicio no satisfactorio.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US20.png)
        <br>
        <br>**US21**<br>
        Como técnico, quiero aceptar o rechazar solicitudes, y recibir pagos instantáneos.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US21.png)
        <br>
        <br>**US22**<br>
        Como cliente, quiero cancelar una solicitud si no la necesito.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US22.png)
        <br>
        <br>**US23**<br>
        Como técnico, quiero recibir notificaciones de nuevas solicitudes.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US23.png)
        <br>
        <br>**US24**<br>
        Como cliente, quiero abrir un reclamo si el servicio no fue satisfactorio, para que la plataforma lo gestione.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US24.png)
        <br>
        <br>**US25**<br>
        Como cliente, quiero calificar a un profesional tras el servicio.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US25.png)
        <br>
        <br>**US26**<br>
        Como cliente, quiero ver calificaciones y reseñas de otros usuarios.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US26.png)
        <br>
        <br>**US27**<br>
        Como cliente, quiero ver la calificación promedio del profesional.
        <br>
        ![imagesUserFlowDiagramsMobileApplication1](./feature/chapter3/Mobile_Applications_User_Flow_Diagrams/3_User_Stories/US27.png)
        <br>
      - **3.1.4.5. Mobile Applications Prototyping**

      **Link del video:** [https://acortar.link/rnHeKG](https://acortar.link/rnHeKG)


