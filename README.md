# :hammer_and_wrench:Harmonious
## Tabla de Contenidos
1. [Información General](#Informacion-General)
2. [Tecnologías](#tecnologías)
3. [Desarrolladores](#desarrolladores)
4. [Información Personal](#información-personal)

### Informacion General
* Este sitio web se encuentra en desarrollo y fue iniciado por fines educativos.
Fue creado para posibles barberías o peluquerías con la opción de suscribirse al sitio y realizar reservación de turnos de forma on-line, mostrar los servicios ofrecidos
y presentar a los usuarios una lista de precios.

* En próximas versiones se incluirá backend para que sea posible darle una completa funcionalidad al sitio. También se agregará una página de productos, junto con un carrito de compras y otras tecnologías para que la compra on-line sea posible.

### Logo
![Image text](https://harmonious.000webhostapp.com/img/logo.png)

## Tecnologías
Lista de tecnologías utilizadas en este proyecto:
* [Boostrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/): Versión 5.0.2 
* [NodeJs](https://nodejs.org/en/download/): Versión 16.17
* [npm](https://www.npmjs.com/package/npm): Versión 8.19.1

## :keyboard:Desarrolladores:
Todos aquellos que quieran continuar con el proyecto se utiliza HTML, SASS y Boostrap.
A continuación les dejo los pasos para poder compilar con node-js:
* Descargar e instalar NodeJs y npm
* Ir a la carpeta del proyecto y ejecutar
npm init
* ejecutar npm install node-sass nodemon
* Crear carpeta y archivo SCSS
* Copiar contenido de style.css del proyecto en style.scss
* Configurar el archivo package.json agregando las siguientes lineas en la sección scripts:
    "build-css": "node-sass --include-path scss scss/style.scss css/style.css",
    "watch-css": "nodemon -e scss -x \"npm run build-css\""
* Dar formato SASS al archivo style.scss
* Ejecutar: npm run watch-css

## Información Personal
### ¡Hola! Soy Sofía Caucota

Soy aprendiz de desarrollo web, específicamente front-end. Tengo interés en seguir aprendiendo y amplear mi conocimiento.

:star2:**Sobre mi:**
   - Soy alguien con una personalidad creativa.
   - Además de apasionarme la maquetación de páginas web, estoy muy interesada en el diseño de las mismas.
   - Disfruto mucho aprender constantemente cosas nuevas.
   - Suelo tener la iniciativa en el trabajo en equipo.
   
:books: **Estoy aprendiendo:**
   - Desarrollo Web NodeJs
   - JavaScript
   - Inglés nivel B1
   
:computer: **Busco:**
   - Trabajar en diferentes proyectos para así enfrentarme a varios desafíos, buscando superarme a mí misma y aprender nuevas cosas.
