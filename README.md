Taller-Multimedial

#### Exploración creativa de arte, tecnología y medios digitales interactivos.
##### Cultura web y arte digital.

# Indice
Semana 1
Semana 2
Semana 3
Semana 4


## Semana 1:

### Página Principal
```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

<meta charset="UTF-8">
<!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

<title>Multimedial</title>
<!-- Título de la página que aparece en la pestaña del navegador -->

<style>
/* Aquí comienza la sección de estilos CSS que define la apariencia visual */

body{
/* "body" se refiere a todo el contenido visible de la página */

  background-color: white;
  /* Define que el fondo de toda la página sea blanco */

  color: black;
  /* Define que el color del texto sea negro */

  margin: 0;
  /* Elimina los márgenes que los navegadores agregan por defecto */

  height: 100vh;
  /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */

  display: flex;
  /* Activa el sistema Flexbox para organizar y centrar elementos */

  justify-content: center;
  /* Centra el contenido horizontalmente */

  align-items: center;
  /* Centra el contenido verticalmente */

  font-family: Arial, sans-serif;
  /* Define la tipografía del texto */

  font-size: 60px;
  /* Define el tamaño grande del texto */

}
/* Fin de las reglas de estilo del body */

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

MULTIMEDIAL
<!-- Texto que aparece en el centro de la pantalla -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```


## Semana 2:

### Página 1
```
<!DOCTYPE html>
<html lang="es">
<head>
<title>Mi sitio</title>
<meta charset="UTF-8">
</head>
<title>Mi Sitio</title>
<body>

<h1>Página principal</h1>

<a href="pagina2.html">Ir a la segunda página</a>

</body>
</html>
```

### Página 2
```
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Página 2</title>

</head>

<body>

<h1>Esta es la segunda página</h1>

<a href="index.html">Volver a la página principal</a>
<!--<a href="index.html" target="_blank">Volver a la página principal</a>-->

</body>
</html>
```

## Semana 3:

### Página Principal
```
<!DOCTYPE html>
<!-- Indica al navegador que este documento usa HTML5 -->

<html>
<!-- Inicio del documento HTML -->

<head>
<!-- Sección donde van metadatos, título y estilos -->

   <meta charset="UTF-8">
   <!-- Define la codificación de caracteres para que se vean bien tildes y símbolos -->

   <title>Multimedial</title>
   <!-- Título de la página que aparece en la pestaña del navegador -->
  
   <style>
   /* Aquí comienza la sección de estilos CSS que define la apariencia visual */

      body{
     /* "body" se refiere a todo el contenido visible de la página */
       font-family: Arial, sans-serif;
       background-color: #FFB55C;
       color: #752B00;
       /* Define que el color del texto sea negro */
       margin: 0;
       /* Elimina los márgenes que los navegadores agregan por defecto */
       height: 100vh;
       /* Hace que el alto del cuerpo sea igual al 100% de la altura de la pantalla */
       display: flex;
       /* Activa el sistema Flexbox para organizar y centrar elementos */
       justify-content: center;
       /* Centra el contenido horizontalmente */
       align-items: center;
       /* Centra el contenido verticalmente */
       font-family: Arial, sans-serif;
       /* Define la tipografía del texto */
       font-size: 100%;
        /* Define el tamaño grande del texto */
        }
       /* Fin de las reglas de estilo del body */

        /* Contenedor principal */
        .contenedor {
            width: 50%;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: #FFB55C;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 80%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>
<!-- Inicio del contenido visible de la página -->

 <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/imagen1.JPG" alt="Descripción de la imagen">
            <h2>Catalina Olate</h2>
            <p>
                Este es un texto de ejemplo. Aquí puedes escribir contenido descriptivo,
                reflexivo o informativo sobre la imagen.
            </p>
              <a href="obra.html">Obra</a><br> 
  <!-- Enlace a otra página llamada "obra.html" -->
  <!-- <br> agrega un salto de línea -->

  <a href="contacto.html">Contacto</a> 
 <!-- Enlace a otra página llamada "contacto.html" -->

        </div>
  <br><br> <!-- Saltos de línea para generar espacio -->

</body>
<!-- Fin del contenido visible -->

</html>
<!-- Fin del documento HTML -->
```

### Obra
```
<!DOCTYPE html>
<html>
<head>
<title>Obra</title>
</head>

<body>

<h1>Mi obra</h1>

<p>Descripción de mi trabajo artístico</p>

<a href="index.html">Inicio</a><br>
<a href="contacto.html">Contacto</a>


<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Estructura con Divisiones</title>

    <style>
        /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #d1872d;
            margin: 0;
        }

        /* Contenedor principal */
        .contenedor {
            width: %;
            margin: auto;
        }

        /* Sección o bloque */
        .bloque {
            background-color: rgb(77, 56, 41);
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }

        /* Imagen */
        .bloque img {
            width: 20%;
            height: auto;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            line-height: 1.5;
        }
    </style>
</head>

<body>

    <!-- Contenedor principal -->
    <div class="contenedor">

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/imagen1.JPG" alt="Descripción de la imagen">
            <img src="img/imagen2.JPG" alt="Descripción de la imagen">
            <img src="img/imagen3.JPG" alt="Descripción de la imagen">

            <h2>Cuerpos Fantasmas</h2>
            <p>
                Este es un texto de ejemplo. Aquí puedes escribir contenido descriptivo,
                reflexivo o informativo sobre la imagen.
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="imagen2.jpg" alt="Descripción de la imagen">
            <h2>Título 2</h2>
            <p>
                Otro texto que acompaña la imagen. Puedes trabajar narrativa,
                análisis visual o cualquier tipo de contenido.
            </p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="imagen3.jpg" alt="Descripción de la imagen">
            <h2>Título 3</h2>
            <p>
                Este es un tercer bloque. Puedes repetir esta estructura
                tantas veces como quieras.
            </p>
        </div>

    </div>

</body>
</html>

</body>
</html>
```

### Contacto
```
<!DOCTYPE html>
<html>
<head>
<title>Contacto</title>
</head>

<body>

<h1>Contacto</h1>

<img src="contacto.jpg" alt="Imagen de contacto" width="300">

<p>email@email.com</p>

<a href="index.html">Inicio</a><br>
<a href="obra.html">Obra</a>

</body>
</html>
```

## Semana 4

###
```
```

## Semana

###
```
```
