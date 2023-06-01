# Resumen

Mini-aplicación para escuchar podcasts musicales, la cual consta de 3 vistas principales:

1. Vista principal
2. Detalles de podcast
3. Detalles de un capítulo de un podcast

Es una _Single Page Application (SPA)_ de manera que la navegación se realizará siempre en el cliente.
La misma contará con dos modos de ejecución _development_ y _production_ .

Ver la aplicación en el siguiente enlace: [mini-podcasts](https://dcarias0388.github.io/mini-podcasts/)

## Creación de la aplicación

El proyecto fue creado haciendo uso del [Create React App](https://github.com/facebook/create-react-app).

## Primeros pasos

Para poder ejecutar la aplicación primeramente se debe clonar el repositorio mini-podcasts: `https://github.com/dcarias0388/mini-podcasts.git` y luego se instalan las dependencias ejecutando en consola _npm install_ o _yarn install_.

### Modo _development_ `npm start`

En el modo development los assets se sirven sin minimizar, para ejecutarlo utilizamos el comando `npm start`.\
Abra [http://localhost:3000](http://localhost:3000) para verlo en su navegador.

### Modo _production_ `npm run build`

Con este comando se crea un `build` directorio con una compilación de producción de la aplicación. Dentro del directorio build/static estarán los archivos JavaScript y CSS.\
Empaqueta correctamente React en modo de producción y optimiza la compilación para obtener el mejor rendimiento.\

La compilación se minimiza (los assets se sirven concatenados y minimizados), y los nombres de archivo incluyen los hashes.\

Para entornos que usan Node, se puede hacer uso de un _Servidor Estático_, como es el caso de [serve](https://www.npmjs.com/package/serve), al cual se le pasa el directorio build que se creó.

`npm install -g serve`
`serve -s build`

El último comando que se muestra arriba servirá nuestro sitio estático en modo _production_ en la url [http://localhost:5000](http://localhost:5000).
