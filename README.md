# Temario De App Web

## 1. Introducción al Desarrollo Web
- **Historia y evolución del desarrollo web**  
  El desarrollo web comenzó en los años 90 con páginas estáticas realizadas en HTML. Con el tiempo, surgieron páginas dinámicas, frameworks y tecnologías como JavaScript, CSS y servidores de aplicaciones, permitiendo experiencias más interactivas y funcionales.

- **Tipos de aplicaciones web**  
  - **Estáticas:** El contenido no cambia y se muestra igual para todos los usuarios. Ejemplo: portafolios personales sencillos.
  - **Dinámicas:** El contenido se genera o modifica en tiempo real, usualmente con bases de datos. Ejemplo: blogs, tiendas online.
  - **SPA (Single Page Application):** La página no se recarga completamente; solo partes de la interfaz cambian. Ejemplo: Gmail.
  - **PWA (Progressive Web App):** Aplicaciones web que ofrecen experiencia similar a apps móviles, con capacidades offline y notificaciones.

## 2. Arquitectura de Aplicaciones Web
- **Modelo Cliente-Servidor**  
  El cliente (navegador) solicita recursos y el servidor responde. El servidor puede procesar datos, acceder a bases de datos y enviar resultados al cliente.

- **Arquitectura de tres capas**  
  - **Presentación:** Interfaz de usuario, lo que ve el usuario.
  - **Lógica:** Procesamiento de datos y reglas del negocio.
  - **Datos:** Almacenamiento y gestión en bases de datos.

- **REST y API-first design**  
  REST es un estilo de arquitectura para APIs que utiliza HTTP y recursos identificados por URLs. API-first significa diseñar la API antes de implementar la lógica o la interfaz.

## 3. Lenguajes y Tecnologías Fundamentales
- **HTML:** Lenguaje de marcado para estructurar páginas web.
- **CSS:** Permite dar estilo y formato visual a las páginas web.
- **JavaScript:** Lenguaje de programación que añade interactividad y dinamismo.
- **PHP:** Lenguaje del lado del servidor para crear aplicaciones web dinámicas.
- **MySQL:** Sistema de gestión de bases de datos relacional, usado para almacenar y consultar información.

## 4. Control de Versiones
- **Git y GitHub**  
  Git es un sistema de control de versiones que rastrea cambios en los archivos y facilita el trabajo colaborativo. GitHub es una plataforma basada en Git para alojar proyectos y colaborar en línea.
- **Flujo de trabajo con ramas**  
  - **Branching:** Crear ramas para trabajar en nuevas características sin afectar la principal.
  - **Merge:** Unir cambios de ramas distintas.
  - **Pull Requests:** Solicitud para que otros revisen y aprueben los cambios antes de integrarlos al proyecto principal.
<img width="366" height="202" alt="image" src="https://github.com/user-attachments/assets/dd772dc5-4262-4db7-8d24-b7e0d456dbfd" />

---

## Propósito de Aprendizaje 2: Desarrollar Componentes y Funcionalidades de una Aplicación Web

### 1. Diseño e Implementación del Frontend
- **Maquetación / Wireframe / Mockup**  
  Son representaciones visuales (bocetos) de la estructura de la interfaz de usuario antes de programar.
- **Consumo de API**  
  El frontend solicita datos al backend mediante APIs para mostrar información dinámica.

### 2. Diseño e Implementación del Backend
- **Configuración de servidor**  
  Preparar el entorno donde se ejecuta la aplicación, administrar servicios y recursos.
- **Manejo de peticiones y respuestas HTTP**  
  El backend recibe solicitudes (GET, POST, PUT, DELETE) y responde con datos o acciones.
- **Conexión a bases de datos (MySQL, PostgreSQL, MongoDB)**  
  Interacción entre el servidor y bases de datos para guardar, modificar o recuperar información.

### 3. Bases de Datos
- **Modelado de datos y relaciones**  
  Diseño de tablas y sus conexiones (relaciones) para organizar la información eficientemente.
- **ORM (Object Relational Mapping)**  
  Herramientas que permiten manipular bases de datos mediante objetos y código, facilitando la programación.
- **Operaciones CRUD desde el backend**  
  Crear, Leer, Actualizar y Eliminar datos desde el servidor.

### 4. Seguridad Básica en Aplicaciones Web
- **Validación de formularios**  
  Comprobar que los datos ingresados por el usuario sean correctos y seguros.
- **Autenticación y autorización**  
  Autenticación verifica la identidad del usuario; autorización determina qué puede hacer el usuario dentro de la aplicación.
<img width="377" height="214" alt="image" src="https://github.com/user-attachments/assets/5a7be564-e058-40f6-b8f6-dacde12abb37" />

---

## Propósito de Aprendizaje 3: Implementar y Desplegar una Aplicación Web Funcional

### 1. Integración de Frontend y Backend
- **Interfaz de usuario frontend**  
  Es la parte visual con la que interactúa el usuario.
- **Manejo de API**  
  Comunicación entre frontend y backend para intercambiar datos.
- **Proceso de solicitud y respuesta en el backend**  
  El backend recibe las solicitudes del frontend, las procesa y envía respuestas.

### 2. Almacenamiento en Servidor
- **Tipos de servidores**  
  Pueden ser físicos, virtuales, dedicados o compartidos, según las necesidades del proyecto.
- **Servicios de hosting**  
  Empresas que ofrecen alojamiento de aplicaciones web (ej: AWS, Heroku, Vercel).
- **Proveedores de servicios de almacenamiento**  
  Plataformas para guardar archivos, bases de datos y copias de seguridad (ej: Google Cloud Storage, Azure).

### 3. Optimización y Rendimiento
- **Optimización de recursos (imágenes, scripts)**  
  Mejorar el tiempo de carga y la eficiencia de la aplicación, reduciendo el tamaño de imágenes y archivos.
- **Despliegue de aplicaciones web**  
  Publicar la aplicación en un servidor para que sea accesible a los usuarios.
- **CI/CD básico**  
  Automatización del proceso de integración, pruebas y despliegue continuo.
- **Documentación del proyecto**  
  Escribir guías, manuales y referencias técnicas que expliquen el funcionamiento, uso e instalación de la aplicación. La documentación clara ayuda a nuevos desarrolladores, facilita el mantenimiento y mejora la colaboración.
  <img width="152" height="194" alt="image" src="https://github.com/user-attachments/assets/b15e6382-fc0f-4a9d-885a-d662398bfb00" />
