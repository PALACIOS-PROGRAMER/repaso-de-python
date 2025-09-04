# Temario De App Web

## 1. Introducción al Desarrollo Web
- **Historia y evolución del desarrollo web**  
  El desarrollo web comenzó en los años 90 con páginas estáticas realizadas en HTML. Con el tiempo, surgieron páginas dinámicas, frameworks y tecnologías como JavaScript, CSS y servidores de aplicaciones, permitiendo experiencias más interactivas y funcionales.  
 (https://upload.wikimedia.org/wikipedia/commons/4/40/Internet_Development_Timeline.png)
- **Tipos de aplicaciones web**  
  - **Estáticas:** El contenido no cambia y se muestra igual para todos los usuarios. Ejemplo: portafolios personales sencillos.  
    (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*6NdzV5Y_Md7A9jQzDsK1JQ.png)
  - **Dinámicas:** El contenido se genera o modifica en tiempo real, usualmente con bases de datos. Ejemplo: blogs, tiendas online.  
    (https://www.scnsoft.com/blog-pictures/web-development/web-app-architecture/web-app-architecture.png)
  - **SPA (Single Page Application):** La página no se recarga completamente; solo partes de la interfaz cambian. Ejemplo: Gmail.  
  (https://www.turing.com/blog/wp-content/uploads/2022/07/Single-page-application.png)
  - **PWA (Progressive Web App):** Aplicaciones web que ofrecen experiencia similar a apps móviles, con capacidades offline y notificaciones.  
   (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*Qd0w1M5uK8ZAVf7Vj2b0jw.png)

## 2. Arquitectura de Aplicaciones Web
- **Modelo Cliente-Servidor**  
  El cliente (navegador) solicita recursos y el servidor responde. El servidor puede procesar datos, acceder a bases de datos y enviar resultados al cliente.  
  (https://www.researchgate.net/profile/George-Williams-30/publication/333079033/figure/fig1/AS:753873043865600@1558102500932/Client-server-architecture.png)
- **Arquitectura de tres capas**  
  - **Presentación:** Interfaz de usuario, lo que ve el usuario.
  - **Lógica:** Procesamiento de datos y reglas del negocio.
  - **Datos:** Almacenamiento y gestión en bases de datos.  
  (https://www.tutorialspoint.com/data_communication_computer_network/images/three_tier_architecture.jpg)
- **REST y API-first design**  
  REST es un estilo de arquitectura para APIs que utiliza HTTP y recursos identificados por URLs. API-first significa diseñar la API antes de implementar la lógica o la interfaz.  
   (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*D4wI8hPZz-0QvA2v7N7wXA.png)

## 3. Lenguajes y Tecnologías Fundamentales
- **HTML:** Lenguaje de marcado para estructurar páginas web.  
  (https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.png)
- **CSS:** Permite dar estilo y formato visual a las páginas web.  
  (https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.png)
- **JavaScript:** Lenguaje de programación que añade interactividad y dinamismo.  
(https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png)
- **PHP:** Lenguaje del lado del servidor para crear aplicaciones web dinámicas.  
  (https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg)
- **MySQL:** Sistema de gestión de bases de datos relacional, usado para almacenar y consultar información.  
(https://www.mysql.com/common/logos/logo-mysql-170x115.png)

## 4. Control de Versiones
- **Git y GitHub**  
  Git es un sistema de control de versiones que rastrea cambios en los archivos y facilita el trabajo colaborativo. GitHub es una plataforma basada en Git para alojar proyectos y colaborar en línea.  
(https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)  
  (https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
- **Flujo de trabajo con ramas**  
  - **Branching:** Crear ramas para trabajar en nuevas características sin afectar la principal.  
    (https://wac-cdn.atlassian.com/dam/jcr:5b6e3b4c-5e40-4c26-9f1d-3a3e7d3bce9b/branching-diagram.svg?cdnVersion=492)
  - **Merge:** Unir cambios de ramas distintas.  
    ![Merge](https://docs.gitlab.com/ee/images/merge_request_flow.png)
  - **Pull Requests:** Solicitud para que otros revisen y aprueben los cambios antes de integrarlos al proyecto principal.  
  (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*2FfQH5KqJ7QjHgP-T5rE1g.png)

---

## Propósito de Aprendizaje 2: Desarrollar Componentes y Funcionalidades de una Aplicación Web

### 1. Diseño e Implementación del Frontend
- **Maquetación / Wireframe / Mockup**  
  Son representaciones visuales (bocetos) de la estructura de la interfaz de usuario antes de programar.  
(https://cdn.educba.com/academy/wp-content/uploads/2019/07/Wireframe-Tools.png)
- **Consumo de API**  
  El frontend solicita datos al backend mediante APIs para mostrar información dinámica.  
(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*I1eO5uB0vK2q4W2oT9lZpQ.png)

### 2. Diseño e Implementación del Backend
- **Configuración de servidor**  
  Preparar el entorno donde se ejecuta la aplicación, administrar servicios y recursos.  
  (https://www.hostinger.com/tutorials/wp-content/uploads/sites/2/2021/11/What-is-a-server.png)
- **Manejo de peticiones y respuestas HTTP**  
  El backend recibe solicitudes (GET, POST, PUT, DELETE) y responde con datos o acciones.  
  (https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview/http-structure.svg)
- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)**  
  Interacción entre el servidor y bases de datos para guardar, modificar o recuperar información.  
  (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*LkA3R6YwFecwFfuwjA7s3g.png)

### 3. Bases de Datos
- **Modelado de datos y relaciones**  
  Diseño de tablas y sus conexiones (relaciones) para organizar la información eficientemente.  
  (https://www.vertabelo.com/blog/data-modeling-tutorial-for-beginners/schema.png)
- **ORM (Object Relational Mapping)**  
  Herramientas que permiten manipular bases de datos mediante objetos y código, facilitando la programación.  
  !(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*Edt4v9l0a9wRipE5JYQqGA.png)
- **Operaciones CRUD desde el backend**  
  Crear, Leer, Actualizar y Eliminar datos desde el servidor.  
  (https://www.turing.com/blog/wp-content/uploads/2022/07/CRUD-operations.png)

### 4. Seguridad Básica en Aplicaciones Web
- **Validación de formularios**  
  Comprobar que los datos ingresados por el usuario sean correctos y seguros.  
  (https://cdn.educba.com/academy/wp-content/uploads/2019/07/Form-Validation-in-JavaScript.jpg)
- **Autenticación y autorización**  
  Autenticación verifica la identidad del usuario; autorización determina qué puede hacer el usuario dentro de la aplicación.  
 (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*Q1hU6rK0VQw2WQyJQBylAg.png)

---

## Propósito de Aprendizaje 3: Implementar y Desplegar una Aplicación Web Funcional

### 1. Integración de Frontend y Backend
- **Interfaz de usuario frontend**  
  Es la parte visual con la que interactúa el usuario.  
  (https://cdn.educba.com/academy/wp-content/uploads/2019/07/User-Interface-Web-Development.png)
- **Manejo de API**  
  Comunicación entre frontend y backend para intercambiar datos.  
  !(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*HkZl3Jv5QxN3QX5rL-5mHA.png)
- **Proceso de solicitud y respuesta en el backend**  
  El backend recibe las solicitudes del frontend, las procesa y envía respuestas.  
  (https://dzone.com/media-library/2022/11/18/8f/4f/38e4c3fb-d2c6-4c2e-8d0f-1a4a8a0f1a7d.png)

### 2. Almacenamiento en Servidor
- **Tipos de servidores**  
  Pueden ser físicos, virtuales, dedicados o compartidos, según las necesidades del proyecto.  
  (https://cdn.educba.com/academy/wp-content/uploads/2019/07/Types-of-Servers.png)
- **Servicios de hosting**  
  Empresas que ofrecen alojamiento de aplicaciones web (ej: AWS, Heroku, Vercel).  
  !(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*q9vI0N5x4VhXJk_2WlG4pA.png)
- **Proveedores de servicios de almacenamiento**  
  Plataformas para guardar archivos, bases de datos y copias de seguridad (ej: Google Cloud Storage, Azure).  
  !(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*EYe3YBv9fQfV3uR3O7k1ng.png)

### 3. Optimización y Rendimiento
- **Optimización de recursos (imágenes, scripts)**  
  Mejorar el tiempo de carga y la eficiencia de la aplicación, reduciendo el tamaño de imágenes y archivos.  
  (https://www.optimizesmart.com/wp-content/uploads/2016/03/image-optimization-flow.png)
- **Despliegue de aplicaciones web**  
  Publicar la aplicación en un servidor para que sea accesible a los usuarios.  
  (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*4M3h3O3f1YhW9kU8qP1bVg.png)
- **CI/CD básico**  
  Automatización del proceso de integración, pruebas y despliegue continuo.  
  !(https://miro.medium.com/v2/resize:fit:1400/format:webp/1*8GgGHbsWq2oV5iHnRVH6qA.png)
- **Documentación del proyecto**  
  Escribir guías, manuales y referencias técnicas que expliquen el funcionamiento, uso e instalación de la aplicación. La documentación clara ayuda a nuevos desarrolladores, facilita el mantenimiento y mejora la colaboración.  
  (https://miro.medium.com/v2/resize:fit:1400/format:webp/1*4E6tvkVvIc9FZLkMNxv6aA.png)
