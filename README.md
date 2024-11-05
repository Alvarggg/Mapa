# Arminton
Bienvenido al repositorio del proyecto Campo de Tiro de la UCJC, una aplicación web donde puedes seleccionar personajes y comprobar que el conocimiento es el mayor arma.

# Descripción
Este proyecto es una aplicación web diseñada para ofrecer a los usuarios una experiencia interactiva en un campo de tiro ficticio, donde los personajes usan "munición de conocimiento". La aplicación permite crear, seleccionar y gestionar personajes, mostrando información detallada sobre sus armas y niveles de energía.

# Características
Gestión de personajes: Creación, selección y personalización de personajes con estadísticas específicas.
Juego en tiempo real: Gracias a Socket.IO, los usuarios pueden interactuar entre sí en un ambiente en vivo.
Interactividad con gráficos: p5.js se utiliza para crear gráficos animados y visualizaciones interactivas que mejoran la experiencia visual en el campo de tiro.

# Frameworks Utilizados
El proyecto se basa en las siguientes tecnologías y frameworks:

1. Bootstrap 5.3
Utilizado para la estructura y el diseño del sitio web, aportando un estilo moderno y receptivo a la interfaz.
Proporciona componentes listos para usar, como botones, formularios, tarjetas, y un sistema de grillas para la disposición del contenido.
Documentación: https://getbootstrap.com/
2. EJS (Embedded JavaScript)
Usado como motor de plantillas para renderizar dinámicamente el contenido en el lado del servidor.
Permite generar HTML con JavaScript, incluyendo la iteración sobre listas de personajes y sus estadísticas.
Documentación: https://ejs.co/
3. JavaScript
Utilizado en la parte interactiva del proyecto para gestionar eventos como la recarga y disparo de personajes mediante el uso de fetch para interactuar con la API del servidor.
4. CSS Personalizado
Se ha empleado un archivo style.css para añadir estilos personalizados que complementan Bootstrap, ajustando los elementos visuales como transparencia, sombras y el diseño general de las imágenes y botones.
5. p5.js
Una biblioteca de JavaScript enfocada en facilitar la creación de gráficos interactivos y visualizaciones artísticas. En este proyecto, p5.js es clave para desarrollar animaciones en el campo de tiro, proporcionando un entorno visual que responde a las acciones de los personajes y mejora la experiencia del usuario.
Documentación: p5.js
6. Socket.IO
Este framework permite la comunicación en tiempo real entre el servidor y los clientes, creando una experiencia de juego interactiva y sincronizada en la que los usuarios pueden competir o colaborar en el campo de tiro. Socket.IO maneja eventos de disparo y recarga de personajes en tiempo real, permitiendo una dinámica de juego fluida.
Documentación: Socket.IO
# Instalacion
```bash
git clone https://github.com/Alvarggg/Mapa.git
cd arminton
```
instalar las dependencias
```bash
npm install
```
iniciar la aplicacion
```bash
node app.js
```




