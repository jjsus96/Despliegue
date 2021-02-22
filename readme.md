# Proyecto Gimnasio 360

<!--Para crear encabezados utilizamos tantos # como queremos que sea nuestro encabezado, por ejemplo para h1 utilizamos #, para h2 ## y así con los demás.-->

## Información General

<!--Para añadir una cita solo tenemos que añadir mayor qué, y para crear una cita con saltos de líneas, solo cambiamos de línea y añadimos el mísmo símbolo al inicio.-->

> El proyecto trata sobre una página web de un gimnasio en el cual los socios obtienen información sobre las clases impartidas y sobre el propio gimnasio una vez que acceden a esta, actualmente está en consturucción y los elementos que está creados son:

<!--Para crear listas desordenadas, ponemos antes del inicio de cada elemento un guión, algunas aplicaciones también aceptan el símbolo más y un asterisco para esto.-->

- Index
+ Formulario de registro
* Página de contacto

<!--Para crear listas numeradas es tan sencillo como decidir el número del elemento en la lista y aádirlo antes del elemento seguido de un punto, para anidar elementos podemos introducir una tabulación y repetir el proceso que hemos realizado con aterioridad.-->

> En la siguiente lista veremos más detenidamente el contenido de cada uno de los elementos del menú

1. Index
    - Cambio de tema de la página
    - Información general del gimnasio
2. Formulario de la página
    - Correo electronico
    - Contraseña
    - Confirmar contraseña
    - Código de socio
4. Página de contacto
    - Mapa de cada uno de los gimnasios
    - Información del gerente de cada una de las sucursales

<!--Para hacer una separación, introducimos 3 guiones bajos seguidos-->
___

## Imágenes del proceso

<!--Si rodeamos nuestra frase se aplicará cursiva a nuestro texto, si en lugar de uno usamos 2 se pondra en negrita y si usamos 3 asteriscos se aplicaran los 2 estilos como en el ejemplo.-->

***En este apartado veremos cómo va por el momento el proceso de la página, a medida que se actualice, modificaremos este apartado para que se vean los diferentes cambios realizados mediante imágenes***

<!--Para esto lo realizamos como en el paso anterior, pero en lugar de escribir un enlace, escribimos la ruta de en la que se encuentra nuestra imagen y justo al inicio le añadimos un signo de exclamación-->

**Index.html**

[![2.png](https://i.postimg.cc/sDwppWGh/2.png)](https://postimg.cc/fJStsJKz)

**Formulario de registro**

[![3.png](https://i.postimg.cc/fb0mng2c/3.png)](https://postimg.cc/QBhHcSrC)

**Página de contacto**

[![1.png](https://i.postimg.cc/yWq2jGbL/1.png)](https://postimg.cc/XB827s35)

## Código

<!--Si queremos añadir código en nuestra página la mejor forma es usar 3 virgulillas por arriba y 3 por abajo, así reconocerá que es código-->

***Aquí podemos ver la estructura de la página index.html a partir de la cual está creada el resto de la página***

~~~
<!DOCTYPE html>
    <meta charset="utf-8">
    <meta http-equiv="refresh" content="">
    <link rel="stylesheet" type="text/css" href="../css/estilosindex.css">
    <html lang="es">
<html>
<head>
    <title>Inicio</title>
</head>
<body>
    <header> <!--Aquí empieza el menú de navegación-->
        <nav class="topnav" id="myTopnav">
            <a id="celdalogo" href="index.html"><img src="../imagenes/Logo.jpg" alt="logo"></a><!--Icono del logo que redirige al inicio-->
            <a href="#">EVENTOS</a>
            <a href="#">FORO</a>
            <a href="contacto.html">CONTACTO</a>
            <a id="menuderecha" href="#">ACCESO</a>
            <a id="menuderecha" href="registro.html">REGISTRO</a>
             <!--Llamada a la función de js para el menú responsive-->
            <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                <i class="fa fa-bars"></i>
            </a>
        </nav>    
    </header> 
    <div class="boton-oscuro"><button class="boton-oscurobtn" id="boton-oscurobtn">CAMBIO MODO</button> </div> <!--Este es el botón con el que cambiamos al modo oscuro/claro-->
    <div class="container">
        <div class="item rojo"><!--Esta es una de las tres columnas que tenemos hechas en esta página con responsive-->
            <br>
            <br>
            <img id="grande" src="../imagenes/index1.jpg" alt="Tio fuerte"><!--Foto del gimnasio con información bajo ella-->
            <br>
            <br>
            <p id="textotripl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis no
                n diam faucibus, tristique ante vitae, 
                lobortis lorem. Integer eu eros commodo, rhoncus leo nec, moll
                is enim. Phasellus eget augue nulla. 
                Pellentesque sodales dictum ultrices. Fusce efficitur felis sed orci</p><!--Esto es el texto informativo bajo la foto al que le añadiremos la información a futuro-->
            <img id="pequeña" src="../imagenes/index11.jpg" alt="Foto cara"><!--Foto deun cliente con testimonio debajo-->
            <br>
            <p id="textotripl">Lorem ipsum dolor sit amet, consectetur adipiscing eliti.</p><!--testimonio del cliente-->
        </div>
        <div class="item verde"><!--Esta es una de las tres columnas que tenemos hechas en esta página con responsive-->
            <br>
            <br>
            <img id="grande" src="../imagenes/index2.jpg" alt="Un gimnasio"><!--Foto del gimnasio con información bajo ella-->
            <br>
            <br>
            <p id="textotripl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis no
                n diam faucibus, tristique ante vitae, 
                lobortis lorem. Integer eu eros commodo, rhoncus leo nec, moll
                is enim. Phasellus eget augue nulla. 
                Pellentesque sodales dictum ultrices. Fusce efficitur felis sed orci</p><!--Esto es el texto informativo bajo la foto al que le añadiremos la información a futuro-->
            <img id="pequeña" src="../imagenes/index22.jpg" alt="Foto cara"><!--Foto deun cliente con testimonio debajo-->
            <br>
            <p id="textotripl">Lorem ipsum dolor sit amet, consectetur adipiscing eliti.</p><!--testimonio del cliente-->
        </div>
        <div class="item azul"><!--Esta es una de las tres columnas que tenemos hechas en esta página con responsive-->
            <br>
            <br>
            <img id="grande" src="../imagenes/index3.jpg" alt="Tia fitness"><!--Foto del gimnasio con información bajo ella-->
            <br>
            <br>
            <p id="textotripl">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis no
                n diam faucibus, tristique ante vitae, 
                lobortis lorem. Integer eu eros commodo, rhoncus leo nec, moll
                is enim. Phasellus eget augue nulla. 
                Pellentesque sodales dictum ultrices. Fusce efficitur felis sed orci</p><!--Esto es el texto informativo bajo la foto al que le añadiremos la información a futuro-->
            <img id="pequeña" src="../imagenes/index33.jpg" alt="Foto cara"><!--Foto deun cliente con testimonio debajo-->
            <br>
            <p id="textotripl">Lorem ipsum dolor sit amet, consectetur adipiscing eliti.</p><!--testimonio del cliente-->
        </div>
    </div>
    <footer> <!--Pié con la marca del gimnasio y los iconos para enlazar a las redes sociales-->
        <p id="ppie">GIMNASIO 360 ©</p>
        <div id="iconos">
        <a href="#"><i class="fab fa-twitter-square" style="font-size: 40;"></i></a><!--Icono de twitter-->
        <a href="#"><i class="fab fa-facebook-square" style="font-size: 40;"></i></a><!--Icono de facebook-->
        <a href="#"><i class="fab fa-instagram-square" style="font-size: 40;"></i></a><!--Icono de instagram-->
        </div>
    </footer>
</body>
<!--Script para cambiar de modo noche/dia-->
<script>
    const boscuro = document.querySelector('.boton-oscurobtn');
    const cuerpo = document.querySelector('body');

    boscuro.addEventListener('click', e => {
        cuerpo.classList.toggle('modoOscuro')
    })
</script>
<script defer src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/js/all.min.js"></script> <!--Script para los iconos-->
<!--Script para que el menú sea responsive-->
<script>
    function myFunction() {
      var x = document.getElementById("myTopnav");
      if (x.className === "topnav") {
        x.className += " responsive";
      } else {
        x.className = "topnav";
      }
    }
    </script>
</html>
~~~
