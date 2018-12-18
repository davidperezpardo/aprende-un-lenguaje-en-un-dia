# Aprende un lenguaje de programación en un día (ejercicio voluntario para subir nota).

## Introducción

Cuando te sacaste el carnet de conducir, aprendiste las normas de circulación así como los fundamentos básicos para manejar un coche: volante, marchas, freno, acelerador, embrague, retrovisores... Seguramente, el coche que conduces ahora es diferente al que utilizaste para aprender a conducir, no obstante, lo puedes llevar sin problema. Cada coche tiene sus peculiaridades, pero quien sabe manejar un automóvil, puede adaptarse a las medidas, tacto y comportamiento de un vehículo en cuestión de horas.

Aprender a programar es como aprender a conducir. Si tienes una base sólida de programación y sabes manejar con soltura los tipos de datos, bucles, arrays, clases, métodos, etc. podrás pasar de un lenguaje a otro en un período relativamente corto, simplemente tendrás que adaptarte a la sintaxis y a las peculiaridades del nuevo lenguaje.

Con este ejercicio se pretende despertar el interés por otros lenguajes de programación distintos al que el alumno está estudiando como primer lenguaje.

Sigue los pasos que se indican a continuación.

## Creación del equipo

Este ejercicio se debe hacer en grupos de 3 alumnos. Uno de ellos será el representante del grupo.

## Forkea forkea

El representante del grupo debe hacer un *fork* de este repositorio para utilizarlo como base.

## Añadiendo colaboradores

El encargado del grupo deberá añadir como colaboradores del repositorio *forkeado* a los otros dos miembros, para trabajar todos sobre los mismos archivos. Cuando alguien es colaborador en un repositorio, puede hacer *push* a él sin necesidad de pedir permiso o hacer *pull request*.

Para añadir colaboradores hay que hacer click en la pestaña *Settings* y seleccionar luego *Collaborators* en el menú.

## Miembros del grupo

Escribe aquí los miembros del grupo. El primero es el representante o encargado.

* David Pérez
* Lorena Moyano
* Mercedes Perea

## Lenguaje de programación

El profesor llevará una cajita llena de papelitos con los nombres de distintos lenguajes de programación. Los encargados de cada grupo meterán la mano en la caja y sacarán dos papelitos, de los cuales el grupo elegirá uno. No se permite hacer intercambio de papelitos entre grupos.

Escribe el lenguaje de programación elegido por el grupo.

* C

Los papelitos se han recortado de este [documento](lenguajes_de_programacion.pdf).

## Información sobre el lenguaje

<h3>Cuándo y para qué se creó </h3>

El lenguaje de programación C fue creado por <strong>Brian Kernighan y Dennis Ritchie</strong> a mediados de los años 70. Cuando trabajaban en Bell Laboratories de AT&T en el diseño del sistema operativo UNIX. C fue creado para poder escribir dicho sistema operativo en un lenguaje de alto nivel, independiente del hardware donde se ejecutara.

Contar con un lenguaje de alto nivel permitió el avance de los sistemas operativos, ya que el mismo código podía ser utilizado en las distintas plataformas, propiciando la reutilización de código y reduciendo los tiempos de desarrollo. Así es que los sistemas operativos basados en UNIX, el sistema BSD, el sistema GNU/Linux y muchos otros fueron desarrollados en C.

<h3>Ambitos en los que se utiliza</h3>

C es uno de los lenguajes más utilizados como podemos ver en la web de <a href="https://www.tiobe.com/tiobe-index/">TIOBE</a>. Los grandes gigantes de la informática, en sus aplicaciones y en sus sistemas implantados con mayor éxito podemos ver como C y C++ barren a la competencia. En el ámbito de sistemas operativos donde la velocidad es un parámetro crucial los más grandes usan mayoritariamente C junto con algo de C++ en el caso de Windows y Objective-C en el de Mac OS X.


<h3>Principales ventajas</h3>

<ul><li>El lenguaje C ha sido pensado para ser altamente transportable.</li>

<li>Un núcleo del lenguaje simple, con funcionalidades añadidas importantes, como funciones matemáticas y de manejo de archivos, proporcionadas por bibliotecas.</li>

<li>Es un lenguaje muy flexible que permite programar con múltiples estilos. Uno de los más empleados es el estructurado.</li>

<li>Un conjunto reducido de palabras clave.</li>

<li>Proporciona una gran flexibilidad de programación y una muy baja comprobación de incorrecciones</li>

<li>El lenguaje C no es rígido en la comprobación de tipos de datos, permitiendo fácilmente la conversión entre diferentes tipos de datos y la asignación entre tipos de datos diferentes.</li>
</ul>

<h3>Algunos de los principales IDE para C</h3>
<ol><li>Dev-C++</li>
  <li>Code::Blocks</li>
  <li>Visual C++</li>
  <li>C++Builder</li>
  </ol>


<h3>Paginas y enlaces relacionados</h3>

<a href="https://www.abrirllave.com/c/guia-de-uso-de-dev-c-plus-plus.php"> Abrir llave</a><br>
<a href="https://es.wikihow.com/aprender-a-programar-en-C"> Wikihow</a><br>
<a href="https://informatica.uv.es/estguia/ATD/apuntes/laboratorio/Lenguaje-C.pdf"> Universidad de Valencia </a><br>
<a href="https://es.wikibooks.org/wiki/Programaci%C3%B3n_en_C"> Wikibooks </a><br>
<a href="https://es.scribd.com/doc/141304397/Curso-de-C-para-dummies-pdf"> Scribd </a><br>
<a href="https://sites.google.com/site/lenguajecprogramacion/ventajas-y-desventajas"> Sites google </a><br>
<a href="https://www.headsem.com/mejores-ide-para-programar-en-c/"> Headsem </a><br>


## Herramientas de desarrollo

Hemos usado el programa <strong><em>Dev-C++</em></strong>, el cuál sirve también para C.
En primer lugar, <a href="http://sourceforge.net/projects/orwelldevcpp/"> descargamos el programa </a>. Una vez instalado, para crear un nuevo proyecto, nos dirigimos a <em>"File -> New -> Source file"</em><br>
<img src = "https://github.com/lorenamoyano/aprende-un-lenguaje-en-un-dia/blob/master/Captura1.PNG" alt = "crear proyecto nuevo" width="50%">
<br>
Seguidamente guardamos el proyecto para que nos "colorée" las palabras de forma automática. Debemos tener en cuanta que a la hora de guardar, debemos escoger el tipo de fichero en <strong>.c</strong>.<br>
<img src = "https://github.com/lorenamoyano/aprende-un-lenguaje-en-un-dia/blob/master/Captura2.PNG" alt="guardar un proyecto" width="50%">
<br>
A continuación, escribimos nuestro programa.<br>
<img src="https://github.com/lorenamoyano/aprende-un-lenguaje-en-un-dia/blob/master/Captura3.PNG" alt = "escribir el programa en el IDE" width = "50%"><br>
Compilamos el programa para poder ejecutarlo.<br>
<img src="https://github.com/lorenamoyano/aprende-un-lenguaje-en-un-dia/blob/master/Captura4.PNG" alt = "compilar" width="50%"><br>
Finalmente ejecutamos el código que hemos compilado y debería salirnos bien si no tenemos ningún error.<br>
<img src="https://github.com/lorenamoyano/aprende-un-lenguaje-en-un-dia/blob/master/Captura5.PNG" alt = "ejecución" width="50%"><br>


## Poniendo en práctica el lenguaje

Pon en práctica el lenguaje de programación realizando los siguientes ejercicios. Para cada uno de los ejercicios, pega el código fuente de la solución y una captura de pantalla.

### 1. ¡Hola mundo!

Realiza un programa que muestre por pantalla la frase **¡Hola mundo!**.
``` c
#include <stdio.h> //archivo de cabecera que contiene las funciones...
#include <conio.h> //para usar getch

int main() { //función principal
    printf("Hola Mundo"); //impresión del programa
    getch(); //pausa
    return 0; //le dice al sistema operativo que el programa ha finalizado correctamente
}
```

### 2. Pirámide

Dada una altura introducida por el usuario, realiza un programa que pinte una pirámide a base de asteriscos con la altura indicada.
``` c
#include <stdio.h>
int main()
{
    int i, o, altura, k=0;

    printf("Dime la altura que quiere para su piramide: ");
    scanf("%d",&altura);

    for(i=1; i<=altura; ++i, k=0)
    {
        for(o=1; o<=altura-i; ++o)
        {
            printf("  ");
        }

        while(k != 2*i-1)
        {
            printf("* ");
            ++k;
        }

        printf("\n");
    }
    
    return 0;
}

```

### 3. Arrays y números aleatorios

Realiza un programa que rellene un array (o una estructura similar) con 20 números enteros aleatorios entre 1 y 100 y que seguidamente los muestre por pantalla. A continuación, se deben pasar los números primos a las primeras posiciones del array y los no primos a las posiciones restantes. Muestra finalmente el array resultado.
``` c
#include <stdio.h>
#include <stdlib.h>

int main() {
    int numeroAleatorio[19]; //se crea un array con 20 huecos
    int i;
    
    for (i=0; i<=19; i++) {
        numeroAleatorio[i] = rand()%101; // se llena de numeros aleatorios entre el 0 y el 100
    }

    for (i=0; i<=19; i++) {
        printf("Aleatorio %d vale: %d\n", i, numeroAleatorio[i]);
    }
    return 0;
}
```

## Presentación de resultados

Cada equipo explicará al resto de la clase lo aprendido durante la realización del ejercicio. Todos los miembros de cada equipo deben participar en la explicación. Se puede utilizar como material de base para la presentación el repositorio de GitHub.

## Recompensa

* Todos los alumnos que realicen correctamente la actividad tendrán 0'25 puntos extra en la nota del trimestre.

* Los miembros del equipo más votado ganarán un premio.

:star: Si te ha gustado este ejercicio, dale una estrellita al [repositorio original](https://github.com/LuisJoseSanchez/aprende-un-lenguaje-en-un-dia).

