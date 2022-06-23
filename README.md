Emmanuel Perez - Desafío Leggers, Gzip y Análisis de Performance
-------------------------------------------------------------

El archivo INFORME.pdf contiene los resultados del Desafío Loggers, Gzip y Análisis de Performance.

El archivo comandos.txt contiene los comandos requeridos para el desafío Servidor con Balance de Carga, Nginx.

En el directorio de NGINX, se debe reemplazar el archivo nginx.conf, por el archivo del mismo nombre, incluído en este proyecto, en la carpeta raíz.

En el mismo archivo nginx.conf, en la línea 54, se debe actualizar root, por la ruta correspondiente que dirija desde el directorio de NGINX hasta la carpeta public del proyecto, según corresponda.

- Levantar servidor NGINX

Antes de ejecutar la aplicación, 

1. Levantar un servidor local mongoDB en una carpeta a elección (o utilizar una base online).

2. Crear base de datos de nombre ecommerce en el servidor mongodb (use ecommerce)

3. Ingrese en la terminal, ubicado en el directorio del proyecto, el comando:

- npm start

A través del navegador, acceder a las rutas (reemplace <PORT> por el número de Puerto utilizado (por defecto 8080)):

- localhost:<PORT>/info

- localhost:<PORT>/api/randoms

- localhost:<PORT>/login

- localhost:<PORT>/registrar

- localhost:<PORT>/api/productos-test (productos generados con faker)

------------------------------------------------------------------------


La aplicación se conecta a una base de datos de nombre "ecommerce" en un servidor local de Mongo DB.

URL: 'mongodb://localhost:27017/ecommerce'

Para conectar a otra base de datos Mongo:

En el archivo /index.js, reemplazar la URL de Mongo localhost por la URL correspondiente en las líneas 17 y 37.

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

    minimist,

    mongoose,

    nodemon,

    normalizr,
    
    passport,

    passport-local,

    socket.io

*----------------------- Junio - 2022 --------------------------*