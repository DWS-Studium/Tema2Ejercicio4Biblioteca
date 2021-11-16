<h1>Biblioteca</h1>
<p>Crear una base de datos sencilla con PHPMyAdmin. La base de datos se llamará biblioteca y tendrá dos únicas tablas. La tabla usuarios servirá para almacenar los datos de los usuarios y tendrá la siguiente estructura:</p>
<h2>Tabla usuarios</h2>
<table border="1" style="width:100%;"><thead><tr><td>NOMBRE</td><td>TIPO</td><td>TAMAÑO</td></tr>
<tbody>
<tr><td>idUsuario</td><td>INT</td><td>8</td></tr>
<tr><td>nombreUsuario</td><td>VARCHAR</td><td>32</td></tr>
<tr><td>clave</td><td>VARCHAR</td><td>64</td></tr>
<tr><td>tipo</td><td>INT</td><td>2</td></tr>
</tbody>
</table>
<h2>Tabla libros</h2>
<table border="1" style="width:100%;"><thead><tr><td>NOMBRE</td><td>TIPO</td><td>TAMAÑO</td></tr>
<tbody>
<tr><td>idLibro</td><td>INT</td><td>8</td></tr>
<tr><td>nombreLibro</td><td>VARCHAR</td><td>128</td></tr>
<tr><td>autor</td><td>VARCHAR</td><td>64</td></tr>
<tr><td>isbn</td><td>VARCHAR</td><td>13</td></tr>
<tr><td>puntuacion</td><td>INT</td><td>8</td></tr>
<tr><td>genero</td><td>VARCHAR</td><td>64</td></tr>
</tbody>
</table>
<p>A continuación:</p>
<ol>
<li>Hacer un sistema de autentificación de usuarios a partir de esta base de datos.</li>
<li>Crear un programa en PHP (en diferentes ficheros) que añadirá libros en la base de datos. Antes de insertar un libro tenemos que comprobar que no exista ningún libro con el mismo ISBN.</li>
<li>Crear un programa en PHP (en diferentes ficheros) que mostrará los libros de la base de datos. Además, la página principal mostrará un formulario en el que se podrá escoger la puntuación de los libros que queremos buscar en la base de datos.</li>
</ol>