# Markdown

<!--Para crear encabezados utilizamos tantos # como queremos que sea nuestro encabezado, por ejemplo para h1 utilizamos #, para h2 ## y así con los demás.-->

# Encabezado1
## Encabezado2
### Encabezado3
#### Encabezado4
##### Encabezado5
###### Encabezado6

## Citas

<!--Para añadir una cita solo tenemos que añadir mayor qué, y para crear una cita con saltos de líneas, solo cambiamos de línea y añadimos el mísmo símbolo al inicio.-->

> Esto es una cita
> continuación de la cita

## Listas
### Desordenadas

<!--Para crear listas, ponemos antes del inicio de cada elemento un guión, algunas aplicaciones también aceptan el símbolo más y un asterisco para esto.-->

- Elemento1
+ Elemento2
* Elemento3

### Numeradas

<!--Para crear listas numeradas es tan sencillo como decidir el número del elemento en la lista y aádirlo antes del elemento seguido de un punto, para anidar elementos podemos introducir una tabulación y repetir el proceso que hemos realizado con aterioridad.-->

1. Elemento1
2. Elemento2
3. Elemento3
    - Elemento4

## Separaciones

<!--Para hacer una separación, introducimos 3 guiones bajos seguidos-->

Esto es una separación
___

## Negrita y Cursiva

<!--Si rodeamos nuestra frase se aplicará cursiva a nuestro texto, si en lugar de uno usamos 2 se pondra en negrita y si usamos 3 asteriscos se aplicaran los 2 estilos como en el ejemplo.-->

***Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum***

### Enlaces

<!--En primer lugar, introducimos entre corchetes nuestro texto ancla y después entre paréntesis el enlace que queremos añadir, si añadimos entre comillas dentro de los paréntesis texto después del enlace, este será el tittle del enlace. -->

[Esto es un enlace a google](https://www.google.es"Enlace a google")

<!--Si queremos que el propio enlace sea el enlace, lo añadiremos entre mayor qué y menor qué.-->

<https://www.google.es>

## Imágenes

<!--Para esto lo realizamos como en el paso anterior, pero en lugar de escribir un enlace, escribimos la ruta de en la que se encuentra nuestra imagen y justo al inicio le añadimos un signo de exclamación-->

![Imagen](https://www.google.com/url?sa=i&url=https%3A%2F%2Fempresas.blogthinkbig.com%2Fcomo-obtener-imagenes-para-textos%2F&psig=AOvVaw33MR95gNonLVwq1RffR2gS&ust=1614030203053000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKjFoZr5--4CFQAAAAAdAAAAABAJ)

## Código

<!--Si queremos añadir código en nuestra página la mejor forma es usar 3 virgulillas por arriba y 3 por abajo, así reconocerá que es código-->

~~~
Esto es código
~~~

## Anular Markdown

<!--Si queremos usar cualquiera de los carácteres reservados por markdown, le añadiremos un slatch invertido justo antes del caracter reservado y así podremos utilizarlo inutilizando markdown.-->

Así anulamos \*Markdown*.
