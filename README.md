# Taller-Multimedial

#### Exploración creativa de arte, tecnología y medios digitales interactivos.
##### Cultura web y arte digital.

# Indice
1. [Página web](#página-web) <br>
2. [Guión](#guión) <br>
3. [Storyboard](#storyboard) <br>
4. [Reflexión Donna Harraway](#reflexión-donna-harraway) <br>
5. [TouchDesigner](#touchdesigner) <br>
6. [ComfyDesktop](#comfy-desktop) <br>

## Página web
### Semana 1:

#### Página Principal
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


### Semana 2:

#### Página 1
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

#### Página 2
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

### Semana 3:

#### Página Principal
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

#### Obra
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

#### Contacto
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

### Semana 4

#### Index
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
       background-color: #222222;
       color: #787878;
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
            background-color: #222222;
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

.navbar {
  background-color: #333;
  overflow: hidden;
}

.navbar a {
  float: left;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: red;
}

.navbar {
  background-color: #333;
  overflow: hidden;
}

.navbar a {
  float: left;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: red;
}

</style>
<!-- Fin de la sección de estilos -->

</head>
<!-- Fin de la sección head -->

<body>


<!-- Inicio del contenido visible de la página -->

 <!-- Contenedor principal -->
    <div class="contenedor">
            <div class="navbar">

  <a href="index.html">Inicio</a>
  <a href="#">Proyectos</a>
     </div>

        <!-- BLOQUE 1 -->
        <div class="bloque">
            <img src="img/portada.jpg" alt="Descripción de la imagen">
            <h2>Catalina Olate</h2>
            <p>
                Hablo desde la corporalidad en un contexto en el que el cuerpo y su percepción deja de ser algo rigido y limitado.
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

#### Obra
```
<!DOCTYPE html>
<html>
<head>
<title>Obra</title>
<style>


            /* Estilo general del cuerpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #474747;
            color: #787878;
            margin: 20;
            display: flex; /* Activa flexbox */
            justify-content: center; /* Centra horizontalmente */
            align-items: center; /* Centra verticalmente */
            height: 100vh; /* Altura total de la pantalla (viewport height) */
        }

  .caja { /* Elemento que será centrado */
  background-color: black; /* Fondo negro */
  color: white; /* Texto blanco */
  padding: 10px; /* Espacio interno */
   }


        /* Contenedor principal */
        .contenedor {
            width: 60%;
            margin: auto;
            display: flex; /* Activa flexbox: organiza los hijos en fila */
             justify-content: center; /* Centra horizontalmente */
             align-items: center; /* Centra verticalmente */
             height: 100vh; /* Altura total de la pantalla (viewport height) */
        }

        .caja { /* Clase para cada bloque */
            background-color: lightgreen; /* Color de fondo */
         padding: 20px; /* Espacio interno */
        }

         

        /* Sección o bloque */
        .bloque {
            justify-content: center; /* Centra horizontalmente */
            background-color: rgb(40, 40, 40);
            margin: 40px 40px;
            padding: 80px;
            border-radius: 20px;
        }

        /* Imagen */
        .bloque img {
            width: 100%;
            height: 40%;
        }

        /* Encabezado */
        .bloque h2 {
            margin-top: 10px;
        }

        /* Texto */
        .bloque p {
            
            line-height: 1.5;
        }
    

.navbar {
  background-color: #333;
  overflow: hidden;
}

.navbar a {
  float: left;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: red;
}

.navbar {
  background-color: #333;
  overflow: hidden;
}

.navbar a {
  float: left;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

.navbar a:hover {
  background-color: red;
}
</style>
</head>
<body>

<div class="navbar">

  <a href="index.html">Inicio</a>
  <a href="#">Proyectos</a>
     </div>


    <!-- Contenedor principal -->
    <div class="contenedor">



        <!-- BLOQUE 1 -->
        <div class="bloque">
        
            <img src="img/imagen1.JPG" alt="Descripción de la imagen">
            <img src="img/imagen2.JPG" alt="Descripción de la imagen">
            <img src="img/imagen3.JPG" alt="Descripción de la imagen">

            <h2>Cuerpos Fantasmas</h2>
            <p>
                2024
 
                 Fotografía.
                 Coautor junto con Alex Correa y Mocka Águila.
            </p>
        </div>

        <!-- BLOQUE 2 -->
        <div class="bloque">
            <img src="img/imagen4.jpg" alt="Descripción de la imagen">
            <h2>Psique y Soma</h2>
            <p>
               2026

               Acrílico sobre lienzo
            </p>
            <p>Descripción de mi trabajo artístico</p>
        </div>

        <!-- BLOQUE 3 -->
        <div class="bloque">
            <img src="img/imagen5.JPG" alt="Descripción de la imagen">
            <img src="img/imagen6.JPG" alt="Descripción de la imagen">
            <img src="img/imagen7.JPG" alt="Descripción de la imagen">
            <h2>Cuerpo-Objeto</h2>
            <p>
               2025
               
               Fotografía.
            </p>
        </div>

    </div>
</body>
</html>
```
## Guión
```
Un ser descansaba desnudo sobre el colchón, presentaba incisiones y marcas ardientes
sobre su cuerpo, algunas de ellas todavía sangraban, en otras había intentado juntar los
pellejos con las costuras de las sábanas que tenía a su disposición, en las más añejas se
había formado una coraza que se fusionaba con su piel, una huella persistente en la
memoria. Las manos avanzaban lentamente sobre la superficie, recorriendo cada pliegue
de la tela. No buscaban ocultar ni reparar por completo, sino cubrir aquello que todavía
permanecía expuesto, aquello más profundo y doloroso que se va más allá de la superficie.
Permanecía resguardado entre capas de tela, habitando una zona intermedia entre lo visible
y lo oculto. Cada hilo del tejido parecía sostener una historia, reuniendo fragmentos
dispersos de experiencia, pérdida y resistencia.
El tejido se convertía entonces en un espacio vulnerable, entre lo que se rompe y lo que
permanece. Un espacio contenido, no desde la ausencia del dolor, sino desde la posibilidad
de habitarlo acompañado por las manos, la tela y nudos que, sin cerrar completamente la
herida, ofrecían un lugar donde descansar.
En la quietud de una habitación, el cuerpo se recogía sobre sí mismo, guardando aquello
que no podía ser dicho.
En ese contacto silencioso, el cuerpo encontraba refugio.
```
## Storyboard
```
```
## Reflexión Donna Harraway
```
Lo que más me llamó la atención del documental es como se cuenta.
Donna Harraway es una persona muy expresiva, y se da a entender perfectamente tanto por su rostro, sus manos y sus palabras. También percibí que era genuina y transparente, en el sentido de que en ocasiones hubo interrupciones que en una producción se tendrían que repetir o cortar de la producción final, además de relatar situaciones y experiencias personales que no cualquiera contaría tan libremente, y eso hace sentir una cercanía hacia ellx.
Otro elemento llamativo es la edición del documental en sí. usa recursos visuales explicitos y sutíles, como la aparición de medusas gigantes, movimientos de cámara, desplazamiento y cambio de fondos, e incluso pantalla verde o la aparición de la artista en el fondo. También el documental cuenta con diferentes secciones (Entrevista, retrospectivas, videos, narrativas, etc) que enriquece aquello que la artista quiere contar.

Minutajes
8:50 Cambio de fondo
19:10 Koko el gorila
23:15 El fondo gira horizontalmente hacia la derecha
39:40 El fondo gira horizontalmente hacia la izquierda
43:45 Cambio de fondo
44:50 medusa
49:30 “trabajamos con lo que tenemos”
49:40 El fondo se desplaza hacia abajo
53:00 Cambio de fondo
53:48  / 54:33 Medusa
58:05 El fondo se aleja
1:05:05 pantalla verde
```

## TouchDesigner
### Mappin

### Lsystem


## Comfy Desktop
### Prompts e imágenes
```
Prompt 1 
Una imagen sobre piel, que representa procesos internos en el cuerpo humano.
Visualmente abstracta. La composición es cerrada, en plano a detalle, con una atmósfera neutra.
Sin elementos extra.
```
<img src=""/>

```
Prompt 2
Una imagen sobre un acercamiento a la piel, que representa procesos internos en el cuerpo humano.
Visualmente realista. La composición es cerrada, en plano a detalle, con una atmósfera neutra.
Sin elementos extra.
```
<img src=""/>

```
Prompt 3
Una imagen sobre un acercamiento a la piel, que representa procesos internos en el cuerpo humano.
Visualmente realista pero abstracta. La composición es cerrada, en plano a detalle, con una atmósfera neutra.
Sin elementos distinguibles.
```
```
Prompt 4
Una imagen sobre un acercamiento a la piel a una muy corta distancia, que representa procesos internos en el cuerpo humano.
Visualmente realista pero abstracta, donde no se distingue la parte del cuerpo. La composición es cerrada, en plano a detalle, con una atmósfera neutra.
Sin elementos distinguibles.
```
```
Prompt 5
Una imagen sobre un acercamiento a la piel a una muy corta distancia, que representa procesos internos en el cuerpo humano.
Visualmente realista pero abstracta, donde no se distingue la parte del cuerpo pero si los poros, bello y otros elementos de la piel.
La composición es cerrada, en plano a detalle, con una atmósfera neutra. Sin otros elementos.
```
```
Prompt 6
Una imagen sobre un acercamiento a la piel a una muy corta distancia, que representa procesos internos en el cuerpo humano.
Visualmente realista pero abstracta, donde no se distingue la parte del cuerpo pero si los poros, bello, lunares, venas, cicatrices o marcas.
La composición es cerrada, en plano a detalle, con una atmósfera neutra y poca iluminación. Sin otros elementos.
```
```
Prompt 7
Una imagen sobre un acercamiento a la piel a una muy corta distancia, que representa procesos internos en el cuerpo humano.
Visualmente abstracta, donde no se distingue la parte del cuerpo pero si los poros, bello, lunares, venas, cicatrices o marcas.
La composición es cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos.
```
```
Prompt 8
Una imagen sobre un acercamiento a la piel a una muy corta distancia, que representa procesos internos en el cuerpo humano.
Visualmente abstracta, donde no se distingue la parte del cuerpo pero si los poros, bellos, lunares, venas, cicatrices y marcas de la piel de forma detallada.
La composición es cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos.
```
```
Prompt 9
Una imagen de acercamiento a la piel desde una muy corta distancia, que representa procesos y conflictos internos en el cuerpo humano.
Visualmente abstracta, donde no se distingue la parte del cuerpo pero si los poros, venas, cicatrices, enrojecimiento, heridas e imperfecciones de la piel de forma detallada.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles.
```
```
Prompt 10
Una imagen de acercamiento a la piel desde una muy corta distancia, que representa procesos y conflictos internos en el cuerpo humano.
Visualmente abstracta, donde no se distingue la parte del cuerpo pero si los poros, venas, cicatrices, enrojecimiento, heridas e imperfecciones de la piel de forma detallada, en el que intervienen elementos textiles como hilos y telas.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles.
```
```
Prompt 11
Una imagen de acercamiento a la piel desde una muy corta distancia, que representa procesos y conflictos internos en el cuerpo humano.
Visualmente abstracta, donde no se distingue el cuerpo pero si los poros, venas, cicatrices, heridas e imperfecciones de la piel, en el que intervienen elementos textiles como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles.
```
```
Prompt 12
Una imagen de acercamiento a la piel desde una muy corta distancia, que representa procesos y conflictos internos en el cuerpo humano.
Visualmente abstracta, donde no se distingue el cuerpo pero si los poros, venas, cicatrices, heridas e imperfecciones de la piel, fusionando texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación.
Sin otros elementos distinguibles ni realistas.
```
```
Prompt 13
Una imagen de acercamiento a la piel desde una muy corta distancia, que representa procesos y conflictos internos en el cuerpo humano por medio de tecnicas textiles.
Visualmente abstracta, donde se reemplaza la piel los poros, venas, cicatrices, heridas e imperfecciones de la piel, por texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 14
Una imagen que representa procesos y conflictos internos en el cuerpo humano por medio de tecnicas textiles y la abstracción.
Visualmente abstracta y deformada, donde se reemplaza la piel, los poros, venas, cicatrices, heridas e imperfecciones de la piel, por texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 15
Una imagen que representa procesos y conflictos internos en el cuerpo humano por medio de tecnicas textiles y la abstracción.
Visualmente abstracta y deformada, donde se elimina la figura humana y elementos como la piel, los poros, venas, cicatrices, heridas e imperfecciones de la piel se reemplazan por texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 16
Una imagen que representa procesos y conflictos internos en el cuerpo humano por medio de tecnicas textiles y la abstracción.
Visualmente abstracta y deformada, donde se elimina la figura humana y elementos como la piel, los poros, venas, cicatrices, heridas e imperfecciones de la piel se reemplazan por texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 17
Una imagen que representa procesos y conflictos internos desde la piel por medio de tecnicas textiles y la abstracción.
Visualmente abstracta y deformada, donde las cicatrices, heridas e imperfecciones de la piel se reemplazan por texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 18
Una imagen que representa tecnicas textiles y la abstracción haciendo una analogía desde la piel.
Visualmente abstracta y deformada, donde las cicatrices, heridas e imperfecciones de la piel se reemplazan por texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 19
Una imagen que representa tecnicas textiles y la abstracción 
Visualmente abstracta y deformada, aparecen texturas como hilos, telas y costuras.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 20
Una imagen que representa tecnicas textiles y la abstracción 
Visualmente abstracta y deformada, aparecen texturas como hilos, telas desgarradas y costuras. de apariencia desordenada y caotica.
La composición es muy cerrada, en plano a detalle, con una atmósfera neutra y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 21
Una imagen que representa tecnicas textiles y la abstracción 
Visualmente abstracta y deformada, aparecen texturas como hilos, telas desgarradas y costuras mal hechas. de apariencia desordenada y caotica.
La composición es muy cerrada, en plano a detalle, con una atmósfera cálida y baja iluminación. Sin otros elementos distinguibles ni realistas.
```
```
Prompt 22
Una imagen que representa tecnicas textiles y la abstracción 
Visualmente abstracta y deformada, aparecen texturas como hilos, telas desgarradas y costuras mal hechas, de apariencia desordenada, caotica y visceral.
La composición es muy cerrada, en plano a detalle, con una atmósfera cálida y baja iluminación. 
```
```
Prompt 23
An image representing textile techniques and abstraction.
Visually abstract and distorted, it features textures such as threads, torn fabrics, and crude stitching, creating a chaotic, visceral, and disheveled appearance.
The composition is tightly framed—a close-up shot—set in a warm atmosphere with low lighting.
```
```
Prompt 24
An image representing textile techniques and abstraction.
Visually abstract and distorted, it features textures such as threads, torn and frayed fabrics, and crude stitching, creating a chaotic, visceral, and disheveled appearance.
The composition is tightly framed—a close-up shot—set in a warm backlit atmosphere.
```
```
Prompt 25
An image representing textile techniques and abstraction.
Visually abstract and distorted, it features textures such as threads, torn and frayed fabrics, and crude stitching, creating a chaotic, visceral, and disheveled appearance.
The composition is tightly framed—a close-up shot—set in a warm backlit atmosphere that gives it the appearance of a painting
```
```
Prompt 26
A visually abstract and distorted image featuring textures such as threads, torn and frayed fabrics, and seams with a disordered, chaotic, and visceral appearance.
```
```
Prompt 27
destroyed fabric
```
```
Prompt 28
destroyed and shredded fabric
```
```
