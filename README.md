# practica-x-ets
## [Fichas 3.5](https://rol.yosiftware.es/)
Nuestro proyecto se basa en una página web para crear fichas de personaje del juego dungeons & dragons(D&D) 3.5. La web es un intento por facilitar la vida de los jugadores y evitarles la lectura de ingentes cantidades de manuales, por lo que tendrá precargado es una base de datos todo lo necesario para su funcionamiento. Los usuarios aparte de crear sus personajes podrán diseñar elementos homebrew tales como clases, razas, plantillas, etc. En última instancia el fin de este servicio es generar las fichas de personaje como archivos pdf que el jugador pueda usar en sus partidas.

Para la creación de la página hemos elegido un diseño one page (Una sola página sin subpáginas) y para conseguirlo **usaremos el framework** [Angular](https://angular.io/), el cual dispone de todas las herramientas necesarias para la creación de una web con estas características. Además al estar desarrollado por google, nos da las herramientas necesarias para integrarlo con firebase.

**El hosting, la base de datos y el servicio de login nos los proporcionará** [Firebase](https://firebase.google.com/?hl=es-419). Firebase es un sistema de entrada gratuito que nos dará de una forma muy simple las herramientas necesarias para desplegar nuestra web.

- La *base de datos* elegida será la opción realtime, la cual nos proveerá los datos en tiempo real, y cuando un usuario en cualquier parte del mundo cree un personaje u otro elemento, instantáneamente los demás usuarios tendrán acceso a ello.

- El *sistema de login* de Firebase nos proveerá una api de inicio de sesión la cual generará los inicios de sesión automáticamente, o si el usuario lo prefiere, podrá iniciar sesión con google o microsoft.