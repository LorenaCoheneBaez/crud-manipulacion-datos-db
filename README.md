# Digital Movies CRUD con base de datos

## Objetivo:

Realizar un CRUD (create, read, update, delete) en el sitio Digital movies.

Se utiliza una base de datos relacional (MYSQL), para traer los datos.

Además se hacen validaciones en formularios de agregar y editar películas con Express-validator.

## Tecnologías usadas


<p align="left">
 <!–– JAVASCRIPT ––>
<a href=https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" data-bs-toggle="tooltip" title="JavaScript"> <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javaScript"/> </a>
<!-- EXPRESS -->
<a href="https://developer.mozilla.org/es/docs/Learn/Server-side/Express_Nodejs/Introduction" alt="Express Js" ><img src= "https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" /></a>
<!-- MYSQL -->
<a href="https://www.mysql.com/" alt="Express Js" ><img src= "https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" /></a>
<!–– CSS ––>
<a href="https://www.w3schools.com/css/" target="_blank" data-bs-toggle="tooltip" title="CSS3"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css3"/> </a>
<!–– BOOTSTRAP ––>
<a href="https://getbootstrap.com" target="_blank" data-bs-toggle="tooltip" title="Bootstrap"> <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" alt="bootstrap"/></a>
  </p>

### Instalación de la base de datos relacional movies-db.sql:

- Debe tener instalado un gestor de base de datos, por ejemplo: MYSQL Workbench (https://www.mysql.com/products/workbench/) o Heidi db (https://www.heidisql.com/).

- Desde su gestor de base de datos, correr el script que se encuentra en:

   crud-manipulacion-datos-db/src/database/script/movies-db.sql

- Levantar el servidor para la base de datos desde su gestor de base de datos.

### ¿Cómo instalar el proyecto?

#### Desde la terminal:

<h4> Clonar el proyecto:</h4>
<p>- <strong> git clone https://github.com/LorenaCoheneBaez/crud-manipulacion-datos-db.git </strong> </p>
<p>- Ingresar a la carpeta del proyecto: <strong>cd crud-manipulacion-datos-db</strong> </p>
<p>- Para instalar las dependencias correr: <strong>npm install</strong> </p>

### Levantar el servidor del proyecto: npm start

### Rutas:

- Home "http://localhost:3001/"
- Listado de todas las películas "http://localhost:3001/movies"
- Detalle de película "http://localhost:3000/products/detail/:id"
- Agregar película "http://localhost:3001/movies/add"
- Editar película "http://localhost:3000/products/edit/:id"
- Eliminar película "http://localhost:3000/products/delete/:id"
