


<div align="center">

<h1> Cargar-imagenes-en-bbdd <h1>

#

<h3>sql:</h3>
<pre>
CREATE DATABASE if NOT EXISTS fotos DEFAULT CHARACTER SET UTF8 collate UTF8_SPANISH_CI;

USE fotos;


CREATE TABLE IF NOT EXISTS productos (
id INT  PRIMARY KEY AUTO_INCREMENT NOT NULL,
nombre VARCHAR(50) NOT NULL,
foto MEDIUMBLOB NOT NULL  
); 
</pre>

#
<p>Aplicacion creada para mostrar como hay que transformar una imagen traida desde un input para guardarla en la base de datos y traerla de regreso para mostrarla en una ventana</p>

<h2><a href="https://youtu.be/F8bjVnesEO8"> Mira como funciona: <img src="https://github.com/LionelStaricoff/conversor/blob/main/youtube.png?raw=true"  alt="enlace a youtube" width="100" height="100"> </a></h2> 
</div>
