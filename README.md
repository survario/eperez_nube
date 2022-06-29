Emmanuel Perez - Desafío: Desplegar proyecto en la nube (Heroku)
-------------------------------------------------------------

Acceder a trvés del siguiente link:

https://emperez.herokuapp.com/login

El archivo INFORME.pdf contiene los resultados del Desafío Loggers, Gzip y Análisis de Performance.

El archivo comandos.txt contiene los comandos requeridos para el desafío Servidor con Balance de Carga, Nginx.

En el directorio de NGINX, se debe reemplazar el archivo nginx.conf, por el archivo del mismo nombre, incluído en este proyecto, en la carpeta raíz.

En el mismo archivo nginx.conf, en la línea 54, se debe actualizar root, por la ruta correspondiente que dirija desde el directorio de NGINX hasta la carpeta public del proyecto, según corresponda.

- Levantar servidor NGINX

Antes de ejecutar la aplicación, 

* Ingrese en la terminal, ubicado en el directorio del proyecto, el comando:

- npm start

A través del navegador, acceder a las rutas:

- https://emperez.herokuapp.com/info

- https://emperez.herokuapp.com/login

- https://emperez.herokuapp.com/registrar

- https://emperez.herokuapp.com/api/productos-test (productos generados con faker)

------------------------------------------------------------------------


La aplicación se conecta a una base de datos de nombre "ecommerce" en un servidor Mongo DB Atlas.

Las colecciones son users, mensajes, productos.



--------------------------------------------------------------

Dependencias utilizadas: 

    autocannon,

    bcrypt,

    compression,

    connect-mongo,

    dotenv, 

    ejs,

    express,

    express-session,

    faker,

    log4js,

    mongoose,

    nodemon,

    normalizr,
    
    passport,

    passport-local,

    socket.io

*----------------------- Junio - 2022 --------------------------*