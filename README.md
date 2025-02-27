# Ruta Melódica  

| **Camargo Ambicho Joussepe Josué** | **Ing. de Sistemas e Informática** |  

### Music Player Application  
Es una pequeña aplicación web de reproductor de música desarrollada con el stack MERN (MongoDB, Express, React, Node.js). La app permite a los usuarios registrarse, iniciar sesión, seleccionar canciones de una biblioteca, crear playlists, reproducir canciones y reanudar la reproducción desde donde la dejaron.

**A continuación, se presenta un desglose de las tecnologías utilizadas, funcionalidades y cómo configurarla localmente:**

### Tecnologías utilizadas:  

1. **Frontend**:  
   - **React.js**: Para construir la interfaz de usuario.  
   - **Redux**: Para la gestión del estado, especialmente del reproductor de música y la autenticación de usuarios.  
   - **Tailwind-CSS**: Para estilizar los componentes y crear un diseño responsive.  
   - **Axios**: Para realizar solicitudes HTTP al backend.  

2. **Backend**:  
   - **Node.js**: Como entorno de ejecución para el código del lado del servidor.  
   - **Express.js**: Para construir la API RESTful que interactúa con el frontend.  
   - **MongoDB**: Como base de datos para almacenar información de usuarios, playlists e información de la música.  
   - **Mongoose**: Para modelar datos (ODM) y trabajar con MongoDB.  

3. **Autenticación**:  
   - **JWT (JSON Web Tokens)**: Para la autenticación de usuarios, permitiendo un inicio de sesión y gestión de sesiones seguros.  

### Funcionalidades:  
- **Autenticación de usuarios**: Los usuarios pueden registrarse e iniciar sesión utilizando autenticación basada en JWT.   
- **Gestión de playlists**: Los usuarios pueden crear, ver y gestionar sus playlists.  
- **Reproductor de música**: Incluye funciones como reproducir, pausar, avanzar y controlar el volumen.  

## Guía paso a paso para usar la aplicación de música una vez abierto el servidor en vivo:  

### Paso 1: Abrir el servidor en vivo  
- Navega a la URL donde está alojada la aplicación.  

### Paso 2: Registrarse o iniciar sesión  
- **Registrarse**: Si eres un nuevo usuario, haz clic en el botón "Registrarse" y completa los datos requeridos para crear una cuenta.  
- **Iniciar sesión**: Si ya tienes una cuenta, haz clic en "Iniciar sesión" e ingresa tus credenciales.  

### Paso 3: Redirección a la página principal  
- Después de registrarte o iniciar sesión correctamente, serás redirigido a la página principal.  

### Paso 4: Navegar por la página principal  
- En la página principal, verás dos botones principales: **Subir canciones** y **Reproducir canciones**.  

### Paso 5: Subir canciones  
- Haz clic en el botón **Subir canciones**.  
- Aparecerá un cuadro de diálogo para seleccionar archivos. Puedes subir cualquier número de canciones desde tu dispositivo.  
- Después de subirlas, las canciones se añadirán a tu biblioteca.  

### Paso 6: Reproducir canciones  
- Haz clic en el botón **Reproducir canciones**.  
- Podrás ver la lista de canciones disponibles en tu biblioteca.  
- Haz clic en cualquier canción para reproducirla.  

### Paso 7: Añadir a playlist  
- Mientras reproduces una canción, tienes la opción de añadirla a una playlist.  
- Puedes crear una nueva playlist o añadir la canción a una existente.  

### Paso 8: Cerrar sesión  
- Cuando termines, puedes cerrar sesión haciendo clic en el botón **Cerrar sesión**, disponible en la barra de navegación o en un menú desplegable.  

**Estas instrucciones te guiarán a través de las funcionalidades básicas de la aplicación de música.**




