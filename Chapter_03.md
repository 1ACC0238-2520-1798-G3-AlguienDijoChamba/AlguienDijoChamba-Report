## **Capítulo III: Solution UI/UX Design**
  - **3.1. Product design**
    - **3.1.1. Style Guidelines**
      
        Esta sección establece las bases visuales y comunicacionales de Fix Now, garantizando coherencia en toda la experiencia digital. Se crea un repositorio común para el equipo con assets gráficos, fuentes y reglas visuales que mantienen una presentación profesional, accesible y funcional.

      - **3.1.1.1. General Style Guidelines**
        
        <br >**Nombre y logotipo** <br> <br>
        El nombre de la aplicación, es FIX IT, transmite innovación, profesionalismo y un enfoque claro en la gestión de servicios de reparación y mantenimiento del hogar. El logotipo de FIX IT está compuesto por 3 llaves inglesas que se alinean mostrando el funcionamiento de esta misma. Este símbolo representa de forma clara y directa la especialización en servicios técnicos. El diseño limpio y geométrico asegura una fácil identificación y recordatorio de la marca.
        ![Logo](feature/chapter3/Logo_FIX_IT.png)
        <br><br>**Tono de comunicación** <br> <br>
        El tono de comunicación será profesional y accesible, transmitiendo confianza sin perder la cercanía ni la calidez. Se evitará el uso de tecnicismos innecesarios y se privilegiará un lenguaje claro y sencillo que facilite la comprensión. La aplicación se expresará como un asistente confiable y siempre dispuesto a colaborar, ofreciendo ayuda de manera oportuna pero sin resultar invasiva.
        <br><br>**Colors** <br> <br>
        La paleta de colores se basa principalmente en tonos de azul, que transmiten confianza, profesionalismo y seguridad. Estos se complementan con acentos en naranja y amarillos cálidos, que aportan energía, dinamismo y cercanía, generando un contraste vibrante y atractivo. Como colores secundarios se utilizan blanco, negro y gris, que equilibran la composición, mejoran la legibilidad y refuerzan una estética limpia y moderna. Esta combinación proyecta una imagen clara, ordenada y a la vez amigable y dinámica, logrando un balance entre seriedad profesional y calidez accesible para los usuarios.
        ![Color](feature/chapter3/Colors.png)
        <br><br>**Typography** <br> <br>
        La tipografía principal utilizada es Arimo, elegida por su legibilidad, estilo moderno y versatilidad en entornos digitales. Se aplican diferentes tamaños para jerarquizar la información: los títulos emplean un tamaño grande y peso seminegrita para destacar, los subtítulos utilizan un tamaño medio con peso regular o medio, y el texto normal mantiene un tamaño cómodo para la lectura continua, con un peso regular.        
        ![Typography](feature/chapter3/Typography.png)
        <br><br>**Spacing** <br> <br>
        En nuestra app móvil aplicamos un sistema de spacing consistente para mantener una estructura visual ordenada y accesible. Se utilizan márgenes de 19.5px entre secciones principales, un padding interno de 18px en botones y componentes, y un interlineado de 1.5x en los textos largos para optimizar la lectura. El layout se organiza en una rejilla de 4 columnas, con alineación centrada, un ancho de columna de 78px y un gutter de 16px entre ellas. Esta configuración asegura equilibrio, claridad y consistencia en toda la interfaz.
        ![Spacing](feature/chapter3/Spacing.png)
        <br><br>**Iconos de aplicación** <br> <br>
        La aplicación emplea un conjunto de íconos minimalistas y uniformes, seleccionados para potenciar la experiencia del usuario y mantener una coherencia visual en toda la interfaz. Cada ícono tiene un propósito definido y se integra de manera consistente con la identidad de la marca, reforzando claridad y armonía en el diseño.
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
      - **3.1.3.2. Landing Page Mock-up**
    - **3.1.4. Mobile Applications UX/UI Design**
      - **3.1.4.1. Mobile Applications Wireframes**
      - **3.1.4.2. Mobile Applications Wireflow Diagrams**
      - **3.1.4.3. Mobile Applications Mock-ups**
      - **3.1.4.4. Mobile Applications User Flow Diagrams**
      - **3.1.4.5. Mobile Applications Prototyping**

