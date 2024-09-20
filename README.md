# Capítulo IV: Product Design
En este capítulo, abordamos el diseño integral de la startup, cubriendo aspectos clave como el estilo visual, los diagramas C4 para la arquitectura del sistema, los diagramas de clases, y los modelos de base de datos, proporcionando una visión clara y estructurada de la infraestructura y el funcionamiento del proyecto.

## 4.1. Style Guidelines.
En esta sección se presentan los estándares que definen el formato y el diseño de la solución, asegurando ycalidad en su implementación.

### 4.1.1. General Style Guidelines.
Las decisiones visuales reflejan un diseño moderno y profesional, transmitiendo confianza y frescura a través de una composición limpia, coherente y simbólicamente alineada con la identidad del proyecto.

**Color**  
Seleccionamos esta gama de colores porque armoniza con el diseño del logo y refleja la temática de nuestra aplicación, asegurando la identidad de la marca.  

![Colores generales](/assets/images/chapter-iv/style-guidelines/color-palette.png)

**Tipografia**   
Seleccionamos esta tipografía por su excelente legibilidad en diversos entornos, además de su carácter poco común, lo que nos permite diferenciarnos frente a la competencia y aportar una identidad única a nuestra marca.

![Tipografias generales](/assets/images/chapter-iv/style-guidelines/typography.png)

**Branding**   
El nombre del producto es ArtCollab, el cual cuenta con un logo representado por el icono de un bolígrafo con motivos coloridos a su alrededor haciendo referencia tanto a los escritores como artistas que son parte de los usuarios principales de nuestro aplicativo.

![Branding general](/assets/images/chapter-iv/style-guidelines/logo.png)

### 4.1.2. Web Style Guidelines.
Nuestra página web está diseñada para ofrecer una experiencia de navegación fluida y accesible, sin importar el dispositivo que utilices. Hemos implementado un diseño basado en el patrón Z, que guía de manera intuitiva la mirada de los usuarios hacia los elementos clave, permitiendo que la información más importante sea fácilmente captada.

## 4.2. Information Architecture.  
En esta sección se presenta la estructura del software según cada segmento objetivo, así como los elementos que se utilizarán para la navegación dentro de la plataforma

### 4.2.1. Organization Systems.  
El Sistema de Organización tiene como objetivo la interacción entre los usuarios y la plataforma mediante una jerarquía visual (visual hierarchy) que resalta funciones clave, como la gestión de pedidos y el monitoreo de equipos, facilitando su acceso inmediato.

#### **Sequential** 
Se implementará una organización secuencial (step-by-step) en procesos como el llenado de datos, asegurando que los usuarios sigan pasos claros y estructurados para completar sus tareas de manera eficiente.

#### **Matrix**
Se aplicarán filtros avanzados para la búsqueda de componentes de maquinaria o equipos, así como el estado de los pedidos, brindando opciones específicas que mejoren la navegación.

### 4.2.2. Labeling Systems.
En AquaEngine Components, el sistema de etiquetas está diseñado para que los usuarios encuentren fácilmente la información que necesitan, haciendo que la navegación sea intuitiva y accesible.

* **Inicio:** Botón en el logo que redirige a la página principal, facilitando el acceso a la vista general del sistema.

* **Suscripciones/Plus:** Suscripción en un periodo de tiempo donde te brindan diferentes beneficios según tu tipo de usuario

### 4.2.3. SEO Tags and Meta Tags

**Meta & SEO (Search Engine Optimization) Tags:**  sirven para que la pagina web sea encontrada facilmente es lo que sale al encontrar la pagina en el buscador (se ponen en el <"head">)
* Titulo:   
```<title>AquaEngine - Oficial Landing Page</title> ```

* Descripcion:  
```<meta name = "description" content = "where you will find fishing machinery management, including orders, inventory and equipment monitoring."/> ```
* Palabras Clave:  
```<meta name = "keyword" content = "fishing machinery, production management, equipment monitoring, inventory control, fishing orders, fishing software"/> ```

### 4.2.4. Searching Systems.
**Que se busca?:**   
Los usuarios buscarán componentes de maquinaria pesquera, el estado de los equipos, detalles de pedidos y niveles de inventario. También podrán buscar pedidos específicos, partes o el estado de sus solicitudes en curso.

**Que resultados se mostraran?:**  
Los resultados de búsqueda mostrarán información relevante sobre componentes, incluyendo detalles de maquinaria, estados actuales de pedidos, inventario disponible y datos de monitoreo de equipos. Los resultados estarán organizados para resaltar la información más pertinente según la consulta de búsqueda. 

**Interface de busqueda:**  
La interfaz de búsqueda contará con un diseño intuitivo para ayudar a los usuarios a encontrar la información deseada de manera rápida. Los filtros incluirán categorías como tipo de equipo, estado del pedido y niveles de inventario. La interfaz amigable mejorará la eficiencia en la búsqueda de datos específicos y optimizará la experiencia del usuario.

![Search interface preview web](/assets/images/chapter-iv/style-guidelines/searching-system.png)

### 4.2.5. Navigation Systems.
La navegación en la aplicación web será sencilla y minimalista, permitiendo a los usuarios acceder fácilmente a las diversas opciones disponibles.

**Hierarchical Navigation System:**  
La navegación se organiza de manera jerárquica desde la página principal hacia las páginas de destino.

**Global Navigation Systems**  
Permite el movimiento vertical dentro de la página. Incluye una barra de navegación que facilita el retorno a la página principal y la navegación entre secciones importantes sin necesidad de retroceder.

**Local Navigation System**  
Complementa al sistema global permitiendo el acceso a otras páginas dentro del sub-sitio.

![Navigation interface preview web](/assets/images/chapter-iv/style-guidelines/nav.png)

## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
Link a los Wireframes de la Landing Page (Figma):  
**https://shorturl.at/0RTW9**

## 1. Hero and Features
Sección principal captando la atención del usuario con una introducción a la aplicación brindando información  
respecto a las características de uso.

![Landing page Wireframe](/assets/images/chapter-iv/landing%20page%20wireframe/wireframe1.png)

## 2. Preview and Subscriptions
Sección donde el usuario visualizará una vista previa respecto a cómo hacemos uso de la aplicación. Además de  
ver los distintos planes que ofrecemos.

![Landing page Wireframe](/assets/images/chapter-iv/landing%20page%20wireframe/wireframe2.png)

## 3. Testimonials and Contac Us
Sección donde el usuario visualizará comentarios de clientes que ya usaron la aplicación y su satisfacción. También  
con un formulario el cuál puede contactarnos para cualquier duda de interés.

![Landing page Wireframe](/assets/images/chapter-iv/landing%20page%20wireframe/wireframe3.png)

### 4.3.2. Landing Page Mock-up.
Link a los Mock-up de la Landing Page (Figma):  
**https://shorturl.at/0RTW9**

## 1. Hero and Features
Sección principal captando la atención del usuario con una introducción a la aplicación brindando información  
respecto a las características de uso.  

![Landing page mockup](/assets/images/chapter-iv/landing%20page%20mock-up/mock-up1.png)

## 2. Preview and Subscriptions
Sección donde el usuario visualizará una vista previa respecto a cómo hacemos uso de la aplicación. Además de  
ver los distintos planes que ofrecemos.  

![Landing page mockup](/assets/images/chapter-iv/landing%20page%20mock-up/mock-up2.png)

## 3. Testimonials and Contac Us
Sección donde el usuario visualizará comentarios de clientes que ya usaron la aplicación y su satisfacción. También  
con un formulario el cuál puede contactarnos para cualquier duda de interés.

![Landing page mockup](/assets/images/chapter-iv/landing%20page%20mock-up/mock-up3.png)

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

Presentamos los wireframes de la aplicación web, proporcionando una visión clara de la estructura y disposición de las diferentes páginas y funcionalidades. Los wireframes son representaciones visuales que muestran la organización de los elementos en la interfaz de usuario.

Link a los Wireframes de la Web Application (Figma):
**https://shorturl.at/cEaJM**

## Home
Esta es la página principal de la aplicación web, donde los usuarios pueden acceder a las funcionalidades principales y obtener una visión general del sistema.

![Web Application Wireframe Home](/assets/images/chapter-iv/ux-ui%20design%20wireframe/home.png)

## Inventory
La página de inventario muestra una lista de productos disponibles, permitiendo a los usuarios ver detalles específicos de cada producto.

![Web Application Wireframe Invetory](/assets/images/chapter-iv/ux-ui%20design%20wireframe/inventory.png)

## Inventory Detail
La página de detalles del inventario muestra información específica de un producto seleccionado, incluyendo características, disponibilidad y precio.

![Web Application Wireframe Invetory Detail](/assets/images/chapter-iv/ux-ui%20design%20wireframe/inventory-product-detail.png)

## Order Machinery
La página de orden de maquinaria permite a los usuarios solicitar equipos y ver el estado de sus pedidos.

![Web Application Wireframe Order Machinery](/assets/images/chapter-iv/ux-ui%20design%20wireframe/order.png)

## Order Machinery Detail
La página de detalles de la orden de maquinaria muestra información específica de un pedido, incluyendo el estado actual y detalles del producto.  

![Web Application Wireframe Order Machinery Detail](/assets/images/chapter-iv/ux-ui%20design%20wireframe/order-detail.png)

## Order Machinery Detail Requested
La página de detalles de la orden de maquinaria muestra información específica de un pedido solicitado, incluyendo el estado actual y detalles del producto.  

![Web Application Wireframe Order Machinery Detail](/assets/images/chapter-iv/ux-ui%20design%20wireframe/order-requested.png)

## Invoicing
La página de facturación muestra un historial de facturas y permite a los usuarios ver detalles específicos de cada factura.  

![Web Application Wireframe Invoicing](/assets/images/chapter-iv/ux-ui%20design%20wireframe/invoice.png)

## Equipment Monitoring
La página de monitoreo de equipos muestra información en tiempo real sobre el estado de los equipos, permitiendo a los usuarios ver detalles específicos de cada equipo.  

![Web Application Wireframe Equipment Monitoring](/assets/images/chapter-iv/ux-ui%20design%20wireframe/equipment-monitoring.png)

### 4.4.2. Web Applications Wireflow Diagrams.

Presentamos los diagramas de flujo de la aplicación web, proporcionando una visión clara de la navegación y las interacciones entre las diferentes páginas y funcionalidades. Los diagramas de flujo son representaciones visuales que muestran la secuencia de acciones y decisiones que los usuarios pueden tomar.

Link a los Wireframes de la Web Application (Figma):
**https://shorturl.at/w2yHe**

Acceso al inventario y tiene interés de ver los detalles de algún producto inventariado.  

![Web Aplication Wireflow Inventory](/assets/images/chapter-iv/wireflow-diagrams-wireframe/inventory.png)

Acceso a ordenar alguna maquinaria, solicitarlos y ver detalle de solicitud.  

![Web Aplication Wireflow Order Machinery](/assets/images/chapter-iv/wireflow-diagrams-wireframe/order-machinery.png)

Acceso a las facturas.  

![Web Aplication Wireflow Invoicing](/assets/images/chapter-iv/wireflow-diagrams-wireframe/invoice.png)

Acceso al monitoreo de equipos.  

![Web Aplication Wireflow Equipment Monitoring](/assets/images/chapter-iv/wireflow-diagrams-wireframe/equipment-monitoring.png)

### 4.4.2. Web Applications Mock-ups.
En esta sección, presentamos los mock-ups de la aplicación web, proporcionando una visión detallada de la apariencia final de las diferentes páginas y funcionalidades. Son representaciones visuales de alta fidelidad que muestran el diseño y la interfaz de usuario, permitiendo una comprensión clara de cómo funcionará la aplicación.  

Link al Web Application Mock-up (Figma):  
**https://shorturl.at/VhlUS**

## Home
La página principal de la aplicación web, donde los usuarios pueden acceder a las funcionalidades principales y obtener una visión general del sistema.  

![Web Application Wireframe Home](/assets/images/chapter-iv/ux-ui%20design%20mock-up/home.png)

## Inventory
La página de inventario muestra una lista de productos disponibles, permitiendo a los usuarios ver detalles específicos de cada producto.  

![Web Application Wireframe Invetory](/assets/images/chapter-iv/ux-ui%20design%20mock-up/inventory.png)

## Inventory Detail
La página de detalles del inventario muestra información específica de un producto seleccionado, incluyendo características, disponibilidad y precio.  

![Web Application Wireframe Invetory Detail](/assets/images/chapter-iv/ux-ui%20design%20mock-up/inventory-product-detail.png)

## Order Machinery
La página de orden de maquinaria permite a los usuarios solicitar equipos y ver el estado de sus pedidos.  

![Web Application Wireframe Order Machinery](/assets/images/chapter-iv/ux-ui%20design%20mock-up/order-machine.png)

## Order Machinery Detail
La página de detalles de la orden de maquinaria muestra información específica de un pedido, incluyendo el estado actual y detalles del producto.  

![Web Application Wireframe Order Machinery Detail](/assets/images/chapter-iv/ux-ui%20design%20mock-up/order-machine-detail.png)

## Order Machinery Detail Requested
La página de detalles de la orden de maquinaria muestra información específica de un pedido solicitado, incluyendo el estado actual y detalles del producto.  

![Web Application Wireframe Order Machinery Detail](/assets/images/chapter-iv/ux-ui%20design%20mock-up/order-machine-requested.png)

## Invoicing
La página de facturación muestra un historial de facturas y permite a los usuarios ver detalles específicos de cada factura.  

![Web Application Wireframe Invoicing](/assets/images/chapter-iv/ux-ui%20design%20mock-up/invoice.png)

## Equipment Monitoring
La página de monitoreo de equipos muestra información en tiempo real sobre el estado de los equipos, permitiendo a los usuarios ver detalles específicos de cada equipo.  

![Web Application Wireframe Equipment Monitoring](/assets/images/chapter-iv/ux-ui%20design%20mock-up/monitoring.png)

### 4.4.3. Web Applications User Flow Diagrams.
Link a los Wireframes de la Web Application (Figma):  
**https://shorturl.at/LLkEt**

Acceso al inventario y tiene interés de ver los detalles de algún producto inventariado.  
![Web Aplication Wireflow Inventory](/assets/images/chapter-iv/wireflow-diagrams-mockup/inventory.png)

Acceso a ordenar alguna maquinaria, solicitarlos y ver detalle de solicitud.  
![Web Aplication Wireflow Order Machinery](/assets/images/chapter-iv/wireflow-diagrams-mockup/order-machinery.png)

Acceso a las facturas.  
![Web Aplication Wireflow Invoicing](/assets/images/chapter-iv/wireflow-diagrams-mockup/invoice.png)

Acceso al monitoreo de equipos.  
![Web Aplication Wireflow Equipment Monitoring](/assets/images/chapter-iv/wireflow-diagrams-mockup/equipment-monitoring.png)

 
## 4.5. Web Applications Prototyping.
En esta sección, se presentan los prototipos de la aplicación web, los cuales son fundamentales para validar y refinar las decisiones de diseño de interacción. Los principales criterios para estas decisiones incluyen la usabilidad, accesibilidad, consistencia y eficiencia. Estos prototipos permiten a los diseñadores y desarrolladores evaluar cómo los usuarios interactúan con la aplicación, asegurando que la experiencia de usuario sea intuitiva y satisfactoria.  

Link Application Prototype (Figma): 
https://shorturl.at/w2yHe  

![Web Aplication Prototype](/assets/images/chapter-iv/application-prototype/prototype.png)

## 4.6. Domain-Driven Software Architecture.
En esta sección, se presenta la arquitectura de software basada en el dominio, un enfoque que centra el diseño y desarrollo del software en el conocimiento del dominio específico del negocio. Este enfoque permite crear sistemas más alineados con las necesidades y procesos del negocio, facilitando la comunicación entre desarrolladores y expertos del dominio. A continuación, se detallan los diferentes diagramas y contextos delimitados que conforman la arquitectura de software de nuestro proyecto.

### 4.6.1. Software Architecture Context Diagram.
El diagrama de contexto del sistema muestra la relación entre el sistema y los actores externos, proporcionando una visión general de la arquitectura del sistema y sus interacciones con el entorno externo.  

<img src="./assets/images/chapter-iv/c4model/SystemContext.png" alt="c4-system-context"/>

### 4.6.2. Software Architecture Container Diagrams.
Los diagramas de contenedores muestran los diferentes contenedores que componen el sistema, como aplicaciones web, bases de datos, microservicios y cómo se comunican entre sí. Estos diagramas proporcionan una visión de alto nivel de la arquitectura del sistema, destacando las responsabilidades de cada contenedor y sus interacciones.  

<img src="./assets/images/chapter-iv/c4model/Containers.png" alt="c4-container"/> 

### 4.6.3. Software Architecture Components Diagrams.
En esta sección, se presentan los diagramas de componentes de la arquitectura de software. Estos diagramas detallan los diferentes componentes que conforman el sistema, sus responsabilidades y cómo interactúan entre sí. 

**Login and SignIn Bounded Context**

<img src="./assets/images/chapter-iv/c4model/AuthenticationContext.png" alt="bound-context-authentication"/>

**Generate Invoice Bounded Context**

<img src="./assets/images/chapter-iv/c4model/InvoiceContext.png" alt="bound-context-invoice"/>

**Manage Inventory Bounded Context**

<img src="./assets/images/chapter-iv/c4model/InventoryContext.png" alt="bound-context-inventory"/>

**Monitoring Bounded Context**

<img src="./assets/images/chapter-iv/c4model/MonitoringContext.png" alt="bound-context-monitoring"/>

**Request Orders Bounded Context**

<img src="./assets/images/chapter-iv/c4model/RequestContext.png" alt="bound-context-request"/>

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
Esta yaselasaben (diagrama de clases)
Clases(name), objetos(nombre-objeto [como objeto]), metodos("Accion") y atributos(Correo, edad,nombre como valor, ID)
### 4.7.2. Class Dictionary.
Inherit (ave(superclase) -> (subclase)canario )
Polymorphism (Ej. funcion de persona hablar() -> Peruano hablar() , Gringo hablar() todos tienen una funcion que contiene persona y van cambiando sus formas)
Abstraction (Ej. Solo muestra el usuario, pero esta su edad, correo y veces usada que uso app en la base de datos (fuera de vista))
Encapsulation (cuando tienes tus variables y metodos en la misma clase las estas encapsulando, aun mas se encapsulan en Private y Public )
## 4.8. Database Design.
### 4.8.1. Database Diagram.
Diagrama de base de datos (la relacion entre clases PK FK el Normalizar tmbn, isiyisi 🕸)
