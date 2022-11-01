# Bootstrap 4 Ultimate Guide 2022

# Seccion 1, introduccion
## 1. Welcome
Bootstrap es necesario de aprender ya que es software libre y un punto de partida para construir paginas con HTML, CSS y Javascript

# Seccion 2, Firefox Developer Edition
## 2. Overview
El navegador firefox tiene una version para developers, se va a ver en esta seccion


## 3. Download & Install
Es crucial ya que permite abrir muchas oportunidades para un desarrollador web. Lo primero es ir a google y buscar firefox developer edition

https://www.mozilla.org/en-US/firefox/developer/

Dentro de la pagina se busca la opcion de descargar, para linux este tutorial es muy util

https://dev.to/harrsh2124/how-to-setup-firefox-developer-edition-on-ubuntu-4inp


## 4. Features
Lo primero es eliminar restos de instalacino de firefox developer edition.
Tambien se abre y se pinea a la taskbar para poder acceder con mas facilidad.
En la pagina principal de firefox developer edition se puede ver todas las caracerisricas y novedades de esta version de desarrollador

## 5. Developer Tools
Es posible ir a developer tools del navegador dando click derecho e inspeccinoar o apretando F12.
Para ver como funciona esta herramienta se procede a visitar la pagina de Google.
La primer opcion que se encuentra en  es la de **Inspector**, esta funcion permite inspeccionar los elementos html y css de cualquier pagina web usando el elemento inspector ctrl+shift++C, es posible pararse en cualquier elemento de la pagina e inspeccionar mas a fondo sus atributos asi tambien como su estilo css.
Es posible generar cambios a la pagina que se restauran cuando se recarga la pagina.

Posteriormente esta el elemento **Consola** el cual permite depurar el codigo de javascript y se va a tocar a fondo cuando se esten evaluando los elementos de javascript.

Sigue la seccion de **Depurador** o Debugger que permite hacer seguimiento y depuracion de errores dentro del navegador webm, en este caso no se va a usar mucho ya que principalmente se va a debuggear usando el editor de texto y el inspector.

La seccion de **Red** permite encontrar las peticiones que se van realizando al servidor, pero es algo que no se va a tocar en este curso.

Posteriormente sigue el **Editor de estilos** es un elemento interesante ya que permite revisar los estilos a detalle segun su fuente, tambien clickeando en el simbolo de + debado de inspector es posible crear una nueva hoja de estilos que se aplica en tiempo real, la cual puede ser tambien descargada posteriormente.

Las secciones posteriores de Rendimiento, Memoria, Almacenamiento, Accesibilidad y Aplicacion sons eccion que pertenecen mayormente al backend por lo que en este curso no se van a tratar.

El modo de diseño responsive ctrl+shift+M que se puede ver en la parte superior derecha de developer tools como un icono de pantallas, permite ingresar a una vista de smartphone o tablet, en la parte superior se peude escoger el tipo de pantalla, si es de un dispositivo especifico o si se configura un tamaño de pantalla personalizado, puede seleccionarse un laptop y en la opcion de editar lista se puede agregar o quiotar dispositivos.

La resolucion es muy importante ya que en el diseño web responsivo se tienen varios tamaños de imagenes, smartphones, tablets, laptops, todas con diferentes resoluciones.
En una seccion del curso se va a hablar de las media queries que permite agergar puntos de quiebre para cada tamaño de resolucion, y basicamente cubre cada una de las resoluciones y para cubrirlo solo se necesita saber los puntos de quiebre para cada resolucion usando los media query

En la parte suyperior hay un icono con simbolo de llave, de ahi se despliegan otras opciones para los desarrolladores. Eyedropper o Recogecolor es una herraaienta que permite obtener el codigo html del color en donde se posa el mouse. Codigo fuente de la pagina  permite encontrar cual es elcodigo que se esta renderizando. Algunas paginas tienen codigo generado como el de typescript y se vuelve muy poco entendible. Debug remoto, consola de navegador, hay muchas herramientas que puede accederse desde ahi.

Hay otra opcion que es "Extensiones para desarrolladores" permite ir a una nueva pagina donde se encuentran mas herramientas que pueden ser agregadas para obtener mas aspectos del desarrollo web.

Estas son unas de las razones por la cual firefox version de desarrollador es una muy buena opcion para desarrollar codigo para la web.



## 6. Summary
En estas secciones previas se vio una vision general de lo que es el curso, tambien de como descargar e instalar Firefox Developer Edition, tambien de sus propuiedades en el diseño y posteriormente hablar de las funcionalidades de las herramientas de desarrollador. Se vio como acceder a estas herramientoas, sus respectivas pantallas y usos. Tambien como acceder al modo de diseño responsivo e incluso como recoger colores desde la pagina web, codigo fuente de la pagina y nuevas herrameintas

# Seccion 3, Atom
## 7. Overview
En este curso se va a usar Atom como editor de codigo. La idea es descargar e instalar este editor de texto que es libre y gratis y se va a usar en los siguientes videos.


## 8. Download & Install
La idea de usar Atom es que el curso esta diseñado con este IDE, por lo que puede que algunas funcionalidades sean solo exclusivas en este editr, pero se es libre de escoger cualquier otro editor, igual que con el navegador web.

Se púede conseguir atom buscando en google, la pagina es inteligente para decidir que sistema operativo se esta usando para descargar el adecuado.

## 9. Open a Project
Para abrir un proyecto en atom, basta con abrir una carpeta o un archivo, o arrastrarlo hasta el editor de codigo desde el manejador de archivos

## 10. Version Control with GitHub
Como ya se ha visto antes, para tener el codigo guardado en caso ed cualquier percance en la maquina local y para almacenar versiones ed codigo en la nube se usa git

## 11. Collaborate with Teletype
Teletype es una especie de live server en VSC, permite a otros editar documentos de codigo en linea en compañia de otros estilo google docs


## 12. Install a Package
Atom como cualquier otro ide permite extender funcinoalidades agregando paquetes desarrollados por terceros

## 13. Choose a Theme
Hay varios temas en el theme picker que s epueden escoger, algunos estan en local otros hay que descargarlos


## 14. Hack on the Init Script
Es posible agregar codigo al init script para personalizar la ejecucion de atom


## 15. Add a Snippet
Snippets son plantillas de codigo que pueden ser agregadas y que pueden ser accedidas escribiendo una palabra clave y luego dando tab


## 16. Keyboard Shortcuts
ctr+shift+p permite acceder a todos los comandos de shortcuts


## 17. Summary
En esta seccion se habla sobre atom


# Seccion 4, get started
## 18. Overview
En esta seccion se va a aprender que es bootstrap, como obtenerlo y descargarlo para configurar sus archivos


## 19. What is Bootstrap
Framework front end gratis para mas facil y mas rapido desarrollo web.
Incluye plantillas de codigo diseñadas en HTML y CSS para tipografia, formulaios, botones, tablas, navegacion, modales, carruseles de imagenes y muchos otros plugins adicionales de javascript.
Bootstrap da la habiliadd de crear diseños responsivos de manera sencilla.

Pensar en bootstrap es pensar en comenzar en un punto de partida en donde ya se tiene un sitio responsivo, la plantilla o la estructura  el framework en el que se va a trabajar encima.
Es como trabajar en una casa, se crean unos buenos cimientos y luego se crea la estructura. Bootstrap permite agregar comonentes muy facilmente en diferentes areas, en la siguiente seccion se va a hablar sobre ello.

Bootstrap ademas de ser una buena manera de cimentar el sitio web, si se combina con PHP se puede convertir en un CMS como wordpress para crear contenido rapido.


## 20. Get Bootstrap
Se puede descargar bootstrap yendo a getbootstrap.com y descargandolo. Pero en esta ocasion se va a descargar como CDN o content delivery network. Alguien eta hosteando esos archivos a los cuales yo me conecto usando un link para poder usar esos archivos. Es posible usar bootstrap como CDN, en la documentacion

https://getbootstrap.com/docs/4.0/getting-started/introduction/

indica como crear el starter template, este se puede copiar dentro de un archvo html y permite generar una primer plantilla en bootstrap. Toda la carpeta con los codigos se ha descargado, pero esta solo como referencia.


## 21. Download and Setup Files
Para descargar bootstrap cmo CDN basta con ir a la documentacion oficial de bootstrap, crear el starter template y comenzar a crear los componentes que se van a ver en la proxima seccion

    <!doctype html>
    <html lang="en">
      <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">

        <title>Hello, world!</title>
      </head>
      <body>
        <h1>Hello, world!</h1>

        <!-- Optional JavaScript -->
        <!-- jQuery first, then Popper.js, then Bootstrap JS -->
        <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
      </body>
    </html>

Usando http-server se puede acceder al archivo que se esta editando en atom

    $ http-server -o


# Seccion 5, Components
## 22. 1-Overview
En esta seccion se va a ver una vista previa de los componentes que se van a ver de javascript, son 35 en total.


## 23. 2-Containers
En esta seccion se va a hablar de los **Containers** o contenedores. Dentro de la carpeta de la seccion, se crea una nuevo archivo **components.html**.

Un contenedor es usado para rellenar el contenido que esta dentro de los contenedores, hay varios tipos de contenedores. Por lo general estas clases van dentro de una etiqueta ```<div>```

Fixed-width container, Fluid container, Container with different colors, Responsive containers

Para usar los componentes de bootstrap siempre va a haber un nombre de clase para aplicar cierta funcionalidad. De esta manera al aplicar una o varias clases se trae el estilo del framework de bootstrap.

### Fixed-width container
Clase de bootstrap: 

```class="container">```

Cuando se ajusta el tamaño de la pantalla, el contenedor se ajusta con ella

    <div class="container">
      <h1>My first container</h1>
      <p>This is text</p>
    </div>


### Fluid container
Clase de bootstrap:  

```class="container-fluid">```

Cuando se ajusta el tamaño de la pantalla, el contenedor siempre va a tomar el 100% de la pantalla y se va a quedar fijo

    <div class="container-fluid">
      <h1>Fluid Container</h1>
      <p>This is text</p>
    </div>

### Container with different colors
Clases de bootstrap: 


```class="container p-3 my-5 border">```

```class="container p-4 my-4 bg-dark text-white">```

```class="container p-5 my-3 bg-primary text-white">```

Por lo general otras utilidades como border y color vienen con otros contenedores, entonces estas clases permiten agregar colores a los contenedores. 
Los contenedores son usados para poner contenido dentro y son usados bastante.

Se puede apreciar que border permite bordear el contenedor, diferentes colores de background y de texto. Esto es una adicion en Bootstrap 4.

Tambien hay containers responsivos, pueden usar clases en las container small, medium, large, y extralarge que ermiten ajustar diferentes contenidos segun el viewport

### Responsive containers
Para los contenedores responsivos se usan unas clases que permiten cambiar el tamaño del contenido segun el tamaño del viewport

```<div class="container-sm bg-primary">.container-sm</div>```

```<div class="container-md bg-dark">.container-md</div>```

```<div class="container-lg bg-alert">.container-lg</div>```

```<div class="container-xl border">.container-xl</div>```

En este momento estos contenedores no tienen contenido, pero mas adelante se va a poder ver mas informacion sobre ellos.

## 24. 3-Grid Basic
En bootstrap el sistema de grid esya construido con flexbox y permite tener hasta 12 columnas en toda la pagina. Si no se quiere usar todas las 12 columnas individualmente, se pueden agrupar pára crear columnas compuestas.

El sistema grid es responsive y se ajusta automaticamente dependiendo del tamaño de la pantalla. Estar seguro de que la suma llegue a 12 o a mas pocas no implica que se deban usar las 12 columnas

En bootstrap el sistema grid tiene 5 tipos de columnas:

Pantallas extrapequeñas, ancho de pantallas menor a  576 pixeles.

      <div class="col-3">.col-3</div>

Pantallas pequelñas, ancho de pantallas igual o mayor a  576px 

      <div class="col-sm-3">.col-sm-3</div>

Panrallas medianas, iancho de pantallas igual o mayor a 768px

      <div class="col-md-3">.col-md-3</div>

Pantallas grandes, ancho de pantallas igual o mayor a  992px

      <div class="col-lg-3">.col-lg-3</div>

Panatallas extragrandes, ancho de pantallas igual o mayor a 1200px 

      <div class="col-xl-3">.col-xl-3</div>

Las clases descritas anteriormente pueden ser combinadas para crear diseños mas dinamicos y flexibles basados en la estructura basica de bootstrap para grid. Anteriormente se muestra la construccion de 4 columnas organizadas de a 3 elementos para un total de 12 en una sola fila, en los diferentes tamaños de la patnalla.

La filosofia de bootstrap es crear elementos y trabajar con filas y columnas, por lo que se hace mas facil crear la responsividad. Para las pantallas pequeñas

    <div class="row">
      <div class="col-sm-3">.col-sm-3</div>
      <div class="col-sm-3">.col-sm-3</div>
      <div class="col-sm-3">.col-sm-3</div>
      <div class="col-sm-3">.col-sm-3</div>
    </div>

Este es el codigo que se va a mostrar en linea en la fila para dispositivos con pantallas iguales o mas grandes que  576px de ancho, cuando el tamaño de la pantalla se hace menor a este tamaño, los elementos se apilan en linea.

Este seria el codigo para los dispositivos con pantalla extra pequeña

    <div class="row">
      <div class="col-3">.col-3</div>
      <div class="col-3">.col-3</div>
      <div class="col-3">.col-3</div>
      <div class="col-3">.col-3</div>
    </div>

Para los dispositivos medianos

    <div class="row">
      <div class="col-md-3">.col-md-3</div>
      <div class="col-md-3">.col-md-3</div>
      <div class="col-md-3">.col-md-3</div>
      <div class="col-md-3">.col-md-3</div>
    </div>

Finalmente para los dispositivos grandes

    <div class="row">
      <div class="col-lg-3">.col-lg-3</div>
      <div class="col-lg-3">.col-lg-3</div>
      <div class="col-lg-3">.col-lg-3</div>
      <div class="col-lg-3">.col-lg-3</div>
    </div>

Y los dispositivos mas grandes 

      <div class="row">
      <div class="col-xl-3">.col-xl-3</div>
      <div class="col-xl-3">.col-xl-3</div>
      <div class="col-xl-3">.col-xl-3</div>
      <div class="col-xl-3">.col-xl-3</div>
    </div>

Finalmente se puede apreciar el funcionamiento del sistema de grid desde la configuracion para el dispositivo mas pequeño hasta el dispositivo xl o extra grande.

Al disminuir el tamaño de la pantalla gradualmente, el bloque de codigo con las clases xl cuando llega a cierto punto, los elementos se encolan o se enlistan de manera vertical. Los elementos estan alineados horizontalmente segun lo deseado hasta los 1200px exactamente, pero cuando la pantalla llega a un minimo de 1119px los elementos se encolan.

Cuando se sigue haciendo mas pequeña la pantalla, la siguiente fila con los elementos lg o grandes se mantiene horizontal hasta los 992px exactamente, cuando baja a 991px inmediantamente los elementos se apilan verticalmente.

Cuando se llega a un minimo de 767 pixeles se va a apilar al dispositivo mediano o md. Ya que el minimo es 768px Cuando se sigue haciendo mas pequeño el tamaño de pantalla y se simula un dispositivo pequeño, sm, el limite hasta donde llegan los elementos alineados horizontalmente es 576px, cuando llega a menos de esto se va a apilar para los dispositivos pequeños. En teoria para los elementos extra pequeños se deberian apilar los elementos en menos de 576px, pero esto no sucedio, parece que estos elementos no se apilan.

Para el resto de los elementos han sido apiladas las columnas, se convirtieron en filas, aunque siguen siendo columnas tienen un comportamiento responsivo a los tamaños de la pantalla. La razon para esto es que muchas veces es necesario apilar el contenido cuando se sta usando un dispositivo movil para que las personas puedan hacer scroll arriba y abajo y la experiencia de usuario sea buena. Ya que esta es la manera de acceder a contenido en dispositivos moviles.

Esta es la mejor parte de bootstrap, su grid responsive y estos fueron los basicos del grid.


## 25. 4-Typography
Bootstrap para la tipografia usa por defecto una fuente de 16px y lel tamaño de la linea es 1.5, el tipo de letra por defecto es **Helvetica, new Helvetica, aerial y sans serif** 

Los elementos de parrafo tienen ```margin-top=0``` y ```margin-bottom=1m (16px)```  por defecto.

Los elementos de titulo tienen todos diferentes pesos y tamaños segun su importancia

h1 - 2.5em o 40px <br>
h2 - 32px <br>
h3 - 28px <br>
h4 - 24px <br>
h5 - 20px <br>
h6 - 16px

Tambien es posible agregar el estilo de un titulo a un elemento parrafo, cuando no sea posible modificar la estructura html, por ejemplo:

    <p class="h1">Parrafo como titulo</p>

Por defecto estos son los tamaños de los titulos, sin embargo a las tipografias se les pueden agregar clases para modificar su visualizacion. 

Por ejemplo se puede agregar un titulo que tiene un texto secundario atenuado 

    <h3>
      Fancy display heading
      <small class="text-muted">With faded secondary text</small>
    </h3>


Si se agrega la clase display, es posible darle mas peso al texto. En el caso de los titulos se puede incrementar su tamaño para cuando sea necesario llamar la atencion

      <h1 class="display-1">Titulo 1</h1>
      <h2 class="display-2">Titulo 2</h2>
      <h3 class="display-3">Titulo 3</h3>
      <h4 class="display-4">Titulo 4</h4>
      <h5>Titulo 5</h5>
      <h6>Titulo 6</h6>

Hay muchas otras opciones para estilizar no solo los titulos sino tambien los parrafos y cualquier otra tipografia, esta en el siguiente link de la documentacion

https://getbootstrap.com/docs/4.0/content/typography/
  


## 26. 5-Colors
Bootstrap tiene ciertas clases que se pueden agregar como contexto a otras y aplicar color. Hay varias clases en bootstrap para la aplicacion del color.

Texto normal      ```<p>Este es un texto normal</p>```

text muted      ```<p class="text-muted">Este texto esta muteado</p>```

primary text      ```<p class="text-primary">Este es un texto primario</p>```

success text      ```<p class="text-success">Este es un texto exitoso</p>```

info text      ```<p class="text-info">Esto es informacion</p>```

text warning      ```<p class="text-warning">Esto es una advertencia</p>```

danger text      ```<p class="text-danger">Esto es peligro!</p>```

secondary text      ```<p class="text-secondary">Este es secundario</p>```

white text      ```<p class="text-white bg-dark">Esto es blanco</p>```

dark text      ```<p class="text-dark">Esto esta en negro</p>```

text body      ```<p class="text-body">Esto es cuerpo</p>```

text light      ```<p class="text-light bg-dark">Esto es light</p>```

Estos estilos para los colores tambien incluyen soporte para el hover y los links.
Las clases contextuales permiten agregar estilos en conjunto con otras y tambien funcionan bien para anchos completos y hover sobre links.

Tambien se pueden usar para botones, fondos, etc. Las clases contextuales se usan para crear colores representativos e importantes.

## 27. 6-Tables
Las tablas en bootstrap tienen varios estilos y atributos, el mas basico es cuando a la tabla se le da la clase **.table**. Luego se crea una tabla normal, es opcional darle el scope a las columnas, pero es lo recomendado

    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First</th>
          <th scope="col">Last</th>
          <th scope="col">Handle</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
        </tr>
        <tr>
          <th scope="row">3</th>
          <td>Larry</td>
          <td>the Bird</td>
          <td>@twitter</td>
        </tr>
      </tbody>
    </table>

Se puede aplicar la clase table-dark junto con .table con el fin de darle el tema oscuro

    <table class="table table-dark">

Tambien es posible aplicar un estilo slo al cabecero thad

      <thead class="thead-light">

Asi como aplicar un estilo de cebras a los elementos de fila tr

    <table class="table table-striped">

Se puede aplicar un estilo que permita ver el comportamiento del hover del mouse

    <table class="table table-hover table-dark">

Se pueden ver mas usos de las tablas y sus estilos en la documentacion

https://getbootstrap.com/docs/4.0/content/tables/

## 28. 7-Images
Hay varias cosas que se le pueden hacer a las imagenes en bootstrap. Se puede agregar un redndeo a las esqionmnas, se puede usar una clase que moldee la imagen dentro de un circulo o tambien se puede usar una clase thumbnail que permite volver la imagen mimiatura con un borde miniatura.

Se trae una imagen de google y se copia su link

https://images.squarespace-cdn.com/content/v1/5bba5251a9ab9576241f7fc1/1558468503069-X8TOFD0EWZIVSZM4MZ9F/cat-4110342_1920.jpg?format=1500w

### Borde redondeado

Le da a la imagen un leve borde redondeado

    class="rounded"

### Imagen moldeada en un circulo

Encierra a la imagen en un circulo haciendo la imagen de forma ovalada

    class="rounded-circle"

### Version miniatura de la imagen

Encierra a la imagen en un borde miniatura, ademas de que la vuelve  su version miniatura. Funciona de manera responsiva y permite que se adapte al tamaño de la pantalla

    class="img-thumbnail"

La clase .img-fluid permite un comportamiento responsivo pero sin el borde miniatura

    class="img-fluid" 

## 29. 8-Jumbotron
Es un tipo de componente que permite mostrar contenido en estilo de unidad de heroe. Es util y flexible que permite extenderse por todo el viewport para mostrar mensajes de informacion de marketing clave para el sitio. Hay dos estilos principales, ocupando el mismo tamaño de los otros elementos

    <div class="container">
      <div class="jumbotron">
        <h1 class="display-4">Hello, world!</h1>
        <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
        <hr class="my-4">
        <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
        <p class="lead">
          <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
        </p>
      </div>
    </div>

O haciendo que ocupe todo el tamaño de viewport disponible

    <div class="jumbotron jumbotron-fluid">
      <div class="container">
        <h1 class="display-4">Fluid jumbotron</h1>
        <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
      </div>
    </div>



## 30. 9-Alerts
Son elementos que proveen de mensajes de retroalimentacion contextual para las acciones tipicas de los usuarios. Estan disponibles para cualquier dimension de texto

    <div class="alert alert-success" role="alert">
      This is a success alert—check it out!
    </div>    
    
Tambien es posible agregar un link al mensaje de alerta

    <div class="alert alert-primary" role="alert">
      This is a primary alert with <a href="#" class="alert-link">an example link</a>. Give it a click if you like.
    </div>

Las alertas aceptan alguno de los 8 estilos cotextuales vistos anteriormente


## 31. 10-Buttons
Los botones pueden aplicar los diferentes estlos y usarse para acciones en formularios, dialogos y mas, soportando diferetnes tamaños estados y mas. Tienen a disposicion las 8 clases contextuales

    <button type="button" class="btn btn-secondary">Secondary</button>

Tambien estan los mismos botones con estilos outline

    <button type="button" class="btn btn-outline-secondary">Secondary</button>

Tambien es posible darle a un elemento link o input el estilo de los botones, dandole las clases de los botones.

      <a class="btn btn-primary" href="#" role="button">Link</a>




## 32. 11-Button Groups
Bootstrap permite agrupar botones en una sola linea y darles poderes con JS. Se crea una clase btn-group en un div donde agrupa varios botones

    <div class="btn-group" role="group" aria-label="Basic example">
      <button type="button" class="btn btn-secondary">Left</button>
      <button type="button" class="btn btn-secondary">Middle</button>
      <button type="button" class="btn btn-secondary">Right</button>
    </div>

Hay varios usos con los grupos de botones. es posible agrupar botones y otros tipos de buttons dentro del grupo. Tambien es posible agregar grupos de botones dentro de otros grupos para formar secciones separadas.

Es posible tambien cambiar el tamaño de los grupos con la clase contextual ```btn-group-lg``` para crear un grupo grande, y la notacion sm para los pequeños.


## 33. 12-Badges

## 34. 13-Progress Bars

## 35. 14-Spinners

## 36. 15-Pagination

## 37. 16-List Groups

## 38. 17-Cards

## 39. 18-Dropdowns

## 40. 19-Collapse

## 41. 20-Navs

## 42. 21-Navbar

## 43. 22-Forms

## 44. 23-Inputs

## 45. 24-Input Groups

## 46. 25-Custom Forms

## 47. 26-Carousel

## 48. 27-Modal

## 49. 28-Tooltip

## 50. 29-Popover

## 51. 30-Toast

## 52. 31-Scrollspy

## 53. 32-Utilities

## 54. 33-Flex

## 55. 34-Icons

## 56. 35-Media Objects

## 57. 36-Filters




# Seccion 6, Grid

# Seccion 7, Reference

# Seccion 8, Project

# Seccion 9, Conclusion
