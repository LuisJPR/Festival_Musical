# Festival Musical
Link del proyecto: https://festivalmusical-luisjpr.netlify.app/
## SASS
Se le considera un estándar de la industria, compatible con muchos frameworks CSS.
No es soportado nativamente por el navegador, por lo tanto deberá ser compilado a un archivo .css. Para compilarlo existen diferentes opciones siendo webpack y Gulp las más populares.
## GULP
Te permite automatizar tareas que son repetitivas en Desarrollo Web tales como: compilar SASS y JavaScrip, crear imagenes más ligeras o la versión webp, minificar y mejorar tu código para producción. Para utilizar Gulp se requiere Node.js y NPM.
Gulp utiliza JavaScript y Pipes (un pipe en gulp es una acción que se ejecuta, una ves finalizada se ejecuta otra y otra; el orden en que se ejecutan es definido por ese pipe)
### GUIA
##### Descargar e instalar Node.js
- Para trabajar con SASS y Gulp tenemos que crear el package.json (sirve para ejecutar comandos de npm y para instalar dependencia de npm), escribir en la terminal:
##### npm init
- Para instalar la dependencia de SASS con NPM, escribir en la terminal:
##### npm install sass --save-dev
- Para correr un scripts (SASS), escribir en la terminal:
##### npm run sass

- Para instalar la dependencia de Gulp con NPM, escribir en la terminal:
##### npm i -D gulp
- Para llamar una funcion de Gulp con NPX (ejecuta paquetes sin ejecutarlos globalmente), escribir en la terminal:
##### npx gulp tarea (tarea -> nombre de la función ubicado en gulpfile.js)
- Para llamar una funcion de Gulp con NPM, escribir en la terminal:
##### npm run tarea (tarea -> nombre del scripts ubicado en package.json)

- Para conectar Gulp con SASS, escribir en la terminal:
##### npm i --save-dev gulp-sass
- Para compilar Gulp con NPX, escribir en la terminal:
##### npx gulp css (css -> nombre de la función ubicado en gulpfile.js)
- Para compilar Gulp con NPM, escribir en la terminal:
##### npm run css (css -> nombre del scripts ubicado en package.json)

- Para instalar la dependencia Plumber con NPM, escribir en la terminal:
##### npm -i --save-dev gulp-plumber

- Para instalar la dependica Webp (permite convertir imagenes jpg, png, etc a webp) con NPM, escribir en la terminal:
##### npm install --save-dev gulp-webp
###### OBS: En caso de error, usar la version 4 de gulp-webp porque la version 5 se actualizo a ESM, escribir en la terminal:
##### npm i -D gulp-webp@4

- Para instalar la dependencia de Image (imagenes mas ligeras) con NPM, escribir en la terminal:
##### npm i --save-dev gulp-imagemin@7.1.0

- Para instalar la dependencia de Cache con NPM, escribir en la terminal:
##### npm i --save-dev gulp-cache

- Para instalar la dependencia de Avif con NPM, escribir en la terminal:
##### npm install --save-dev gulp-avif

- Para instalar la dependencia de CSSNano y mas con NPM, escribir en la terminal:
##### npm i --save-dev cssnano autoprefixer postcss gulp-postcss

- Para instalar la dependencia de SourceMaps con NPM, escribir en la terminal:
##### npm i --save-dev gulp-sourcemaps

- Para instalar la dependencia de Terser con NPM, escribir en la terminal:
##### npm i gulp-terser-js
