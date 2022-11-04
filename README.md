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
Los badges o insignias permiten agregar informacino a cualquier contenido, se usa junt cun una clase contextual como una insignia secundaria. 
Los badges cambian con el tamaño del contexto 

    <h1>Example heading <span class="badge badge-secondary">New</span></h1>
    <h2>Example heading <span class="badge badge-secondary">New</span></h2>
    <h3>Example heading <span class="badge badge-secondary">New</span></h3>
    <h4>Example heading <span class="badge badge-secondary">New</span></h4>
    <h5>Example heading <span class="badge badge-secondary">New</span></h5>
    <h6>Example heading <span class="badge badge-secondary">New</span></h6>

Pueden ser parte de links o botones para llevar contadores


    <button type="button" class="btn btn-primary">
      Notifications <span class="badge badge-light">4</span>
    </button>     

Se pueden aplicar clases contextuales a cada uno
    
    <span class="badge badge-primary">Primary</span>
    <span class="badge badge-secondary">Secondary</span>
    <span class="badge badge-success">Success</span>
    <span class="badge badge-danger">Danger</span>
    <span class="badge badge-warning">Warning</span>
    <span class="badge badge-info">Info</span>
    <span class="badge badge-light">Light</span>
    <span class="badge badge-dark">Dark</span>

Tambien se les puede cambiar el estilo a las insignias

    <h6>Example heading pill<span class="badge badge-pill badge-info">New</span></h6>


Las etiquetas se pueden convertir en links por si mismas al pasar el raton por encima mostrar este comportamiento

    <a href="#" class="badge badge-primary">Primary</a>

Las 8 herramientas contextuales permiten describir el mensaje segun el estado o el tema que se quiere manifestar, en caso que las etiquetaas de danger, warning info o alguna de las otras no manifieste lo que se quiere mostrar, siempre sepuede editar con CSS.

Bootstrap permite agilizar el desarrollo para los que se enfocan en crear contenido. En caso de una necesidad de creacion rapida y robusta de contenido es posible tomar plantillas que sean basicas como templates, y luego agregarles contenido combinando bootstrap con PHP.
Por ejemplo es posible crear una plantilla que permita implementar 10 sitios web por semana. Se creauna plantilla que sea gratuita y estructurada para una pagina basica. Luego obtener el conenido, posteriormente tomar las fotos, agergar un cabecero y luego agregar el contenido cuando ya este completado.
Siempre hay que construir webs pensando en las personas que van a venir despues a usar el codigo que se esta creando.
Lo que se peude hacer es construir equemas de colores personalizados para cada cliente, asi como el contenido, pero lo fundamental en el backend es practicamente lo mismo.



## 34. 13-Progress Bars
Permiten ver un progreso de cuanto se ha avanzado en alguna tarea o cuan lejos se encuentra un proceso de ser creado.
No se usa la etiqueta HTML ```<progress>``` se usa por el contrario una clase de bootstrap que se construye con html y css que permite organizar algunos atributos de la barra de progreso.
Se usa el elemento .progress como un contenedor para indicar el balor maximo de la barra de progreso
Se usa un contenedor interno .progress-bar para indicar el progreso hasta eñ momento
Requiere un estilo inline, clase de utilidad o algun CSS customizado para darle su ancho como porcentaje de anchura.
El elemento *.progress-bar* tambien requiere un atributo **role** y un **aria** para hacerlo accesible.
Si se agrega texto dentro de la variable sirve como label o etiqueta

    <div class="progress" style="height: 20px;">
      <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">25%</div> 
    </div>

Es posible agregar las clases utiles de los colores como **bg-success**

    <div class="progress" style="height: 20px;">
      <div class="progress-bar bg-success" role="progressbar" style="width: 45%;" aria-valuenow="45" aria-valuemin="0" aria-valuemax="100">45%</div> 
    </div>

Tambien es posible animar la barra y darle una apariencia rayada con las clases contextuales**progress-bar-striped progress-bar-animated"**

Tambien es posible agrupar barras de progreso para ver por ejemplo el porcentaje de almacenamiento en un disco segun el procentaje del tipo de archivos. A cada una de las barras se les puede dar un estilo personalizado con clases utiles y contextuales, sin embargo al altura va a ser la que se define en la calse contenedor **progess**

    <div class="progress">
      <div class="progress-bar" role="progressbar" style="width: 15%" aria-valuenow="15" aria-valuemin="0" aria-valuemax="100"></div>
      <div class="progress-bar bg-success" role="progressbar" style="width: 30%" aria-valuenow="30" aria-valuemin="0" aria-valuemax="100"></div>
      <div class="progress-bar bg-info" role="progressbar" style="width: 20%" aria-valuenow="20" aria-valuemin="0" aria-valuemax="100"></div>
    </div>

  
## 35. 14-Spinners
Los spinners son como loaders o indicadores de que algo un recurso o una pagina se esta cargando. 
Se aplica usando la clase .spinner-border. Por temas de accesibilidad siempre el loader incluye **role="status"** y un div interno **<span class="sr-only">Loading...</span>**

    <div class="spinner-border text-muted" role="status"><span class="sr-only">Loading...</span></div>

Hay diferentes colores en la clase util de colores. 
Hay otro tipo de spinner que es el growing spinner

    <div class="spinner-border text-light bg-dark" role="status"><span class="sr-only">Loading...</span></div>


Hay otro tipo de spinner que se puede insertar dentro de un boton

    <button class="btn btn-primary" type="button" disabled>
      <span class="spinner-border spinner-border-sm" role="status" aria-hidden="true"></span>
      Loading...
    </button>


## 36. 15-Pagination
La paginacion permite  mostrar paginacion par aindicar una serie de contenido relacionado existente entre multiples paginas.
La paginacion pérmite que un registro con miles de filas, pueda ser cargado por partes, comenzando por sus primeros 50 registros, y permitiendo ir con los proximos 50 y asi sucfesivamente.

    <nav aria-label="Page navigation example">
      <ul class="pagination">
        <li class="page-item"><a class="page-link" href="#">Previous</a></li>
        <li class="page-item"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">Next</a></li>
      </ul>
    </nav>

La paginacion permite tener bloques conectados usando links. Se le agrega un nav aria-label para indicarkle a los navegadores una etiqueta que e una barra de navegacion


## 37. 16-List Groups
Son un flexible componente para mostrar series de un determinado contenido, se permite modificar y extender para soportar casi que cualquier contenido dentro.
La mas basica es una lista sin ordenamiento donde cada item tiene su clase. A un elemento se le puede asignar la etiqueta de clase **active** para mostrar que es el elemento seleccionado en la lista o **disabled** para iondicar que no es un elemento dispónible

    <ul class="list-group">
      <li class="list-group-item active">An item</li>
      <li class="list-group-item disabled">A second item</li>
      <li class="list-group-item">A third item</li>
      <li class="list-group-item">A fourth item</li>
      <li class="list-group-item">And a fifth one</li>
    </ul>

Tambien se pueden listar links y botones para creqar items de listas accionables con hover, tambien aplican active y disabled con las clases **.list-group-item-action** 

    <div class="list-group">
      <a href="#" class="list-group-item list-group-item-action active" aria-current="true">
        The current link item
      </a>
      <a href="#" class="list-group-item list-group-item-action">A second link item</a>
      <a href="#" class="list-group-item list-group-item-action">A third link item</a>
      <a href="#" class="list-group-item list-group-item-action">A fourth link item</a>
      <a class="list-group-item list-group-item-action disabled">A disabled link item</a>
    </div>

  Tambien a los items de la lista es posible aplicar clases contextuales

      <a href="#" class="list-group-item list-group-item-action list-group-item-primary">A fourth link item</a>

## 38. 17-Cards
Las tarjetas de bootstrap proveen un flexible y ext4ndible contenedor de contenido con multiples variantes y opciones.
Tiene opciones de agregar headers y footers y una gran variedad de contenido, colores de fondo contextuales, y poderosas opciones de display.
Umn ejemplo de uso seria al agregar el grupo de trabajo para una pagina web. Una tarjeta basica seria.

    <div class="card">
      <div class="card-body">
        This is some text within a card body.
      </div>
    </div>

Un ejemplo de tarjeta mas compuesto que contiene imagen titulo y un link seria

    <div class="card" style="width: 18rem;">
      <img src="..." class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
    </div>


## 39. 18-Dropdowns
permite crear elementos contextuales que desplegan listas de links y mas contenido usando bootstrap. Son modificables y son interactivas usando JS, se disparan al clickearse, no al hacerse hover.
Un simple boton puede volverse un dropdown asi, igualmente que sucede con un link

    <div class="dropdown">
      <button class="btn btn-secondary dropdown-toggle" type="button" data-toggle="dropdown" aria-expanded="false">
        Dropdown button
      </button>
      <div class="dropdown-menu">
        <a class="dropdown-item" href="#">Action</a>
        <a class="dropdown-item" href="#">Another action</a>
        <a class="dropdown-item" href="#">Something else here</a>
      </div>
    </div>

Se puede hacer con cualquier tipo de boton

  
## 40. 19-Collapse
Permite activar o desactivar la visualizacion de un contenido, los botones y anchos son usados como disparadores que son mapeados a especificos elementos que se quieren mostrar. Colaprsar un elemento va a animar su altura hasta 0. En el siguiente caso hay un link y un boton que permiten activar o desactivar la funcinoalidad de un mismo texto collapse

    <p>
      <a class="btn btn-primary" data-toggle="collapse" href="#collapseExample" role="button" aria-expanded="false" aria-controls="collapseExample">
        Link with href
      </a>
      <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
        Button with data-target
      </button>
    </p>
    <div class="collapse" id="collapseExample">
      <div class="card card-body">
        Some placeholder content for the collapse component. This panel is hidden by default but revealed when the user activates the relevant trigger.
      </div>
    </div>

Tiene muchas variantes, en donde se puede desplegar diferente contenido para varios botones en linea.


## 41. 20-Navs
Navs o navigation son la clave para mudchos sitios web. la navegacion es una manera de navegar y explorar en el website. El nav mas basico no incluye estilos, 

    <ul class="nav">
      <li class="nav-item">
        <a class="nav-link active" href="#">Active</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled">Disabled</a>
      </li>
    </ul>

Los estilos disponibles pueden ser: 

Alineacion horizontal centrada, agregando la clase contextuial a la clase nav: **justify-content-center**
Con la variante de que no sea center sino end para llvar hasta el final

un nav de posicion vertical con la clase contextual: **flex-column**

Hay otros estilos como **nav-pills** que modifican el estilo del elemento.

Tambien hay una propiedad que se puede agregar a las anteriores **nav-fill** que permite extender el nav por todo lo disponible de la etiqueta padre, o tambien editar las navvar para que se vuelvan pestalas con nav-tabls.

Son muy usados para crear submenus, mas adelante el navbar va a mostrar como hacer un menu principal


## 42. 21-Navbar
Este es un elemento navigation que se ubica como header en la parte superior de la pagina. Es el elemento mas usado para la navegacion en las paginas y sirve como un indice para la pagina

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-toggle="dropdown" aria-expanded="false">
              Dropdown
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="#">Action</a>
              <a class="dropdown-item" href="#">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="#">Something else here</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled">Disabled</a>
          </li>
        </ul>
        <form class="form-inline my-2 my-lg-0">
          <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
      </div>
    </nav>

Por defecto el navbar se comporta de forma responsiva para pantallas desde rtamaño pequeño, asiq ue para las pantallas lg y xl se comprimer el contenido del navbar. E sposible cambiar el color y el estilo de la barra con clases contextuales

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">

    <nav class="navbar navbar-light" style="background-color: #e3f2fd;">


## 43. 22-Forms
Los formularios en bootstrap como casi todos los elementos son expandidos usando clases. Sin embargo la etiqueta form principal no se aplica ninguna clase, se aplican las clases al grupo que pertenece a cada elemento del input. Es necesario usar la clase **form-group** para indicar que se quiere usar el estilo bootstrap para los formularios.
Es necesario verificar que los campos tengan el **type** adecuado. Los grupos de campos pueden contener label, input y tambien un small que permite agregar una leyenda bajo un campo

    <div class="container">
      <form>
        <div class="form-group">
          <label for="exampleInputEmail1">Email address</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
        </div>
        <div class="form-group">
          <label for="exampleInputPassword1">Password</label>
          <input type="password" class="form-control" id="exampleInputPassword1">
        </div>
        <div class="form-group form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label" for="exampleCheck1">Check me out</label>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </div>

Los forms son elementos muy personalizables y se puede ver en la documentacion de bootstrap.

## 44. 23-Inputs
bootstrap permite extender los estilos de los elementos de HTML, para este caso los inputs, usando la clase **form-group**, que por lo general va dentro de un form, o a veces no. Esta tiene una seccion de label y un textarea para comentarios

    <div class="form-group">
      <label for="comment">Comment</label>
      <textarea class="form-control" name="name" id="comment" cols="30" rows="10"></textarea>
    </div>

Tambien es posible agregar listas de opciones

    <div class="form-group">
      <label for="sell">Select list</label>
      <select class="form-control" id="sell">
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
      </select>
    </div>


## 45. 24-Input Groups
Es posible combinar etiquetas input para extender las fuucniones de un campo, agregando texto, botones, grupos puntuales de inputs de texto por defecto, selectores personalizados y entrada personalizada de archivo.
La mayoria de gente se guia mas facil cuando los inputs tienen iconos. El siguiente input group permite mostrar un arroba para indicar un username

    <div class="input-group mb-3">
      <div class="input-group-prepend">
        <span class="input-group-text" id="basic-addon1">@</span>
      </div>
      <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="basic-addon1">
    </div>


## 46. 25-Custom Forms
Los input-grups permiten tambien crear selectores personalizados y tambien entradas de archivo pesonalizadas

    <div class="input-group mb-3">
      <div class="input-group-prepend">
        <label class="input-group-text" for="inputGroupSelect01">Options</label>
      </div>
      <select class="custom-select" id="inputGroupSelect01">
        <option selected>Choose...</option>
        <option value="1">One</option>
        <option value="2">Two</option>
        <option value="3">Three</option>
      </select>
    </div>

## 47. 26-Carousel
EL componente carrusel permite mostar de manera ciclica imagenes o presentaiones de texro, como un carrusel. Es un elemento muy usado en muchas paginas. Los data targets permiten agregar indicadores. La clase carousel-item active permite agregr uno de los slides o imagenes que se van a mostrar. Finalmente la clase carousel-control-prev y -next crea las flechas a los lados

    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <    <div class="carousel-item active">
          <img src="https://www.hospitalveterinariglories.com/wp-content/uploads/2022/09/14-09-22-Todo-sobre-el-gato-calico%CC%81.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="https://image.shutterstock.com/shutterstock/photos/1765073558/display_1500/stock-photo-curious-calico-cat-walking-outside-predator-in-the-autumn-garden-1765073558.jpg" class="d-block w-100" alt="...">
        </div>
        <div class="carousel-item">
          <img src="https://cf.ltkcdn.net/cats/images/std/242113-800x533r1-black-orange-white-calico-cat.jpg" class="d-block w-100" alt="...">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-target="#carouselExampleIndicators" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-target="#carouselExampleIndicators" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </button>
    </div>

## 48. 27-Modal
Los modales agregan cajas de dialogo al sitio para lightboxes, notificaciones de dusuario o contenido completamente custom.
Los modales s econstruyen con HTML, CSS y JavaScript. Se posicionan sobre el resto de la pagina y remueve el scroll del body encima se pone el modal.

Solo se admite una alerta a la vez, no es posible concatenarlas, por temas de experiencia de usuario. Se despliega al dar click a un boton

    <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#staticBackdrop">
      Launch static backdrop modal
    </button>

    <!-- Modal -->
    <div class="modal fade" id="staticBackdrop" data-backdrop="static" data-keyboard="false" tabindex="-1" aria-labelledby="staticBackdropLabel" aria-hidden="true">
      <div class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 class="modal-title" id="staticBackdropLabel">Modal title</h5>
            <button type="button" class="close" data-dismiss="modal" aria-label="Close">
              <span aria-hidden="true">&times;</span>
            </button>
          </div>
            <div class="modal-body">
              <p>Modal body text goes here.</p>
          </div>    
          <div class="modal-footer">
            <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
            <button type="button" class="btn btn-primary">Understood</button>
          </div>
        </div>
      </div>
    </div>


## 49. 28-Tooltip
Los tooltips son pequeñas cajas informativas de texto que aparecen como pop-ups cuando se pone el mouse por encima.
Es una manera de dar informacion a las personas de tipo experiencia de usuario.

    <button type="button" class="btn btn-secondary" data-toggle="tooltip" data-placement="left" title="Tooltip on left">
      Tooltip on left
    </button>

Tambien se puede agregar a un link

    <!-- HTML to write -->
    <a href="#" data-toggle="tooltip" title="Some tooltip text!">Hover over me</a>
      
    <!-- Generated markup by the plugin -->
    <div class="tooltip bs-tooltip-top" role="tooltip">
      <div class="arrow"></div>
      <div class="tooltip-inner">
        Some tooltip text!
      </div>
    </div>



## 50. 29-Popover
Un popover es similar al tooltip, en teoria permite añadir mas informacion, sin embargo en la practica parece que es similar al tootltip

    <a href="#" data-toggle="popovver" title="Popover Header" data-content="Some text inside the popover">Hover over popover</a>



## 51. 30-Toast
SOn notificaciones push que llegan a los usuarios, sin embargo no parece que est funcionando, solo se mantienen por cierto momento


## 52. 31-Scrollspy
Los scrollspy permiten actualizar automaticamente barras de navegacion o componentes list-group basados en la posicion del scroll en la pantalla a la cual corresponda el link activo en el viewport.

    <nav id="navbar-example2" class="navbar navbar-light bg-light">
      <a class="navbar-brand" href="#">Navbar</a>
      <ul class="nav nav-pills">
        <li class="nav-item">
          <a class="nav-link" href="#fat">@fat</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#mdo">@mdo</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#" role="button" aria-expanded="false">Dropdown</a>
          <div class="dropdown-menu">
            <a class="dropdown-item" href="#one">one</a>
            <a class="dropdown-item" href="#two">two</a>
            <div role="separator" class="dropdown-divider"></div>
            <a class="dropdown-item" href="#three">three</a>
          </div>
        </li>
      </ul>
    </nav>
    <div data-spy="scroll" data-target="#navbar-example2" data-offset="0">
      <h4 id="fat">@fat</h4>
      <p>...</p>
      <h4 id="mdo">@mdo</h4>
      <p>...</p>
      <h4 id="one">one</h4>
      <p>...</p>
      <h4 id="two">two</h4>
      <p>...</p>
      <h4 id="three">three</h4>
      <p>...</p>
    </div>


## 53. 32-Utilities
Las clases utilities son bastantes, permiten agregar o quitar elementos como bordes ```class="border"``` es un ejemplo de una clase utility. 
Se vieron ejemplos previos con los colores ```class="text-primary"``` que permitian cambiar el color a elementos.

    <div class="bg-info clearfix">
      <button type="button" class="btn btn-secondary float-left">Example Button floated left</button>
      <button type="button" class="btn btn-secondary float-right">Example Button floated right</button>
    </div>

## 54. 33-Flex
Flex es una utilidad de bootstrap que permite manejar el layout el alineamiento, el tamaño de la plantilla, columnas, navegacion, componentes y mas utilidades responsivas de flexbox. Puede ser necesario agregar codigo CSS para acomodaciones muy complejas.
Permite acomodar los elementos de manera rapida, es una gran diferencia comparado a bootstrap3, que ahora se usa display-flex y antes se usaban box.

Usando la propiedad display que es una utilidad para cerar un contenedor flexbox para transformar elementos hijos directos en items flex. Para aplicarla en el contenedor padre se pone **.d-flex** y **.d-inline-flex**

    <div class="d-flex p-2 bd-highlight">I'm a flexbox container!</div>
    <div class="d-inline-flex p-2 bd-highlight">I'm an inline flexbox container!</div>


Tambien estan las variantes responsivas: 

- .d-sm-flex
- .d-sm-inline-flex
- .d-md-flex
- .d-md-inline-flex
- .d-lg-flex
- .d-lg-inline-flex
- .d-xl-flex
- .d-xl-inline-flex

Se puede dar una direccion a los items y tambien ponerlos en columna
```.flex-row``` para la organizacino horizontal de izquierda a derecha, por defecto o ```.flex-row-reverse``` para que los elementos comiencen de derecha a izquierda. Lo mismo sucede para las columnas ```.flex-column```  y ```.flex-column-reverse```

Tambien es posible justificar el contenido 

    <div class="d-flex justify-content-start">Flex justificado</div>

## 55. 34-Icons
Para el manejo de iconos bootstrap tiene una libreria propia, sin embargo se aconseja a usar librerias externas. Font awesome es recomendada, sin embargo la mas utilizada es material icons.

https://fonts.google.com/icons

Las instrucciones son sencillas, se importa en el head
  
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />

Y luego se usan donde se necesiten 

    <span class="material-symbols-outlined">
      bolt
    </span>


## 56. 35-Media Objects
Los media objects permiten una manera facil de alinear elementos multimedia como imagenes o videos en conjunto con el contenido. Es una manera de construir componentes que representan elementos como comentarios de blog, tweets y el like.

    <div class="media">
      <img src="http://www.i2clipart.com/cliparts/e/7/0/3/clipart-sleepy-calico-cat-256x256-e703.png" width="64px" class="mr-3" alt="...">
      <div class="media-body">
        <h5 class="mt-0">Media heading</h5>
        <p>Will you do the same for me? It's time to face the music I'm no longer your muse. Heard it's beautiful, be the judge and my girls gonna take a vote. I can feel a phoenix inside of me. Heaven is jealous of our love, angels are crying from up above. Yeah, you take me to utopia.</p>
      </div>
    </div>



## 57. 36-Filters
En bootstrap no hay un componente para filtrar, por lo que hay que construir el elemento, Por ejemplo en una tabla se quiere filtrar que es algo muy comun. Para esto sw 


# Seccion 6, Grid
## 58. Overview

- Grid System
- Stacked/Horizontal
- Grid XSmall
- Grid Small
- Grid Medium
- Grid Large
- Grid XLarge
- Grid Examples

## 59. Grid System
El sistema grid de bootstrap permite usar un poderoso diseño mobile-first con diversos formas y tamaños gracias a un sistema de 12 columnas, 5 clases responsivas entre otras clases predefinidas.

En bootstrap el sistema grid tiene 5 tipos de columnas:


                        Max container width   Class prefix
    Extra small   <576px	None (auto)           col-	
    Small         ≥576px 		540px	              .col-sm-	
    Medium        ≥768px	  720px             	.col-md-
    Large         ≥992px	  960px	              .col-lg-
    Extra large   ≥1200px   1140px              .col-xl-

COn estos tamaños prederminados y admeas los limites de los tamañños de los contenedores  debe estar limitado tambien.

El sistema grid determina algo de bootstrap para las reglas del sisteema de grid. las filas deben estar ubicados dentro de un .container que sea fixed o fluid con su alineacion, y las filas basicas ayudan a crear grupos horizontales de columnas.

En contenido se debe ubicar dentrro de columnas y solo las colmunas qpueden ser inmediatamente hijas de las filas
Las columnas a las que no se les ha especificado el ancho determinado se acomodan automaticamente en columna del mismo tamaño. Por ejmeplo cuatro instancias de .col-sm va a crear un ancho de 25% para cuatro columnas iguales en el breakpoint y superior.

Las clases de la columna indican el numero de colu,mas que se quieren usar de las 12 posibles por fila. 
Por ejemplo si se quieren 3 columnas iguales en toda la pantalla se puede usar .col-4

El ancho de las columnas sempre esta organizado en porcentajes, asi que siempre estan en acomodacion relativa a su elemento padre de manera fluida y relativa

Las columnas tienen padding gorizontal por edfecto, se puede quierta usando .no-glutters en .row

En un div .container debe ir dentro una clase .row, y dentro van las columnas de esa fila en ese contenedor.

La manera mas basica, aunque es responsiva, no hace que se apilen los elementos

    <div class="container">
        <h1 class="text-center">01. Grid System</h1>
        <div class="row">
            <div class="col-sm bg-info">
                Una de tres columnas
            </div>
            <div class="col-sm bg-danger">
                Dos de tres columnas
            </div>
            <div class="col-sm bg-info">
                Tres de tres columnas
            </div>
        </div>
    </div>

## 60. Stacked/Horizontal
Esta priopiedad del grid permite acomodar todos los bloques de manera vertical para dispositivos pequeños para luego volverse horizontal en dispositivos mas grandes.
Para el siguiente ejemplo, es ta clase para los devices pequeños, por lo que para que aparezcan encolados de manera horizontal, el dispositivo debe ser menor a 576px de ancho

    <div class="container">
        <div class="row">
          <div class="col-sm-8">col-sm-8</div>
          <div class="col-sm-4">col-sm-4</div>
        </div>
        <div class="row">
          <div class="col-sm">col-sm</div>
          <div class="col-sm">col-sm</div>
          <div class="col-sm">col-sm</div>
        </div>
      </div>


## 61. Grid XSmall
Un ejemplo para la clase Xsmall, muestra que esta clase apila los elementos solo cuando el viewport esta por debajo de 120px

      <h1 class="text-center">03. Grid Xsmall</h1>
      <div class="container-fluid">
        <div class="row">
            <div class="col-3 bg-success">
                <p>Este es algo de texto para Xsmall</p>
            </div>
            <div class="col-9 bg-warning">
                <p>Esto es mas texto par Xsmall</p>
            </div>
        </div>
      </div>


## 62. Grid Small
Un ejemplo para la clase smal o sm que es la primera en donde se apilan los elementos por debajo de 576px en el viewport seria

    <div class="container-fluid">
        <div class="row">
            <div class="col-sm-3 bg-success">
                <p>Este es algo de texto para Xsmall</p>
            </div>
            <div class="col-sm-9 bg-warning">
                <p>Esto es mas texto par Xsmall</p>
            </div>
        </div>
    </div>


## 63. Grid Medium
Para la clase medium a la que pertenecen los dispositivos que estan por debajo de viewports de 768-px, un ejemplo 

    <div class="container-fluid">
        <div class="row">
            <div class="col-md-3 bg-success">
                <p>Este es algo de texto para medium</p>
            </div>
            <div class="col-md-9 bg-warning">
                <p>Esto es mas texto par medium</p>
            </div>
        </div>
    </div>

## 64. Grid Large
Para el ejemplo del viewport largo lg, se va a hacer un caso diferente, se tienen 25 de porcentaje para dispositivos extrapequeños y pequeños, 50% para los medium devices y 33.66 para los largos

    <div class="container-fluid">
        <div class="row">
            <div class="col-sm-3 col-md-6 col-lg-4 bg-primary">
                <p>Este es algo de texto para .col-sm-3 .col-md-6 .col-lg-4</p>
            </div>
            <div class="col-sm-9 col-md-6 col-lg-8 bg-warning">
                <p>Esto es mas texto para col-sm-9 col-md-6 col-lg-8</p>
            </div>
        </div>
    </div>

## 65. Grid XLarge
Para los dispositivos extralargos se va a aver un ejemplo similar al anterior, sin embargo para los dispositivos extralrgos un 20% y 80%, un ejemplo para el contenido desplegado en xbox series one.

    <div class="container-fluid">
        <div class="row">
            <div class="col-sm-3 col-md-6 col-lg-4 col-xl-2 bg-primary">
                <p>Este es algo de texto para .col-sm-3 .col-md-6 .col-lg-4</p>
            </div>
            <div class="col-sm-9 col-md-6 col-lg-8 col-xl-10 bg-warning">
                <p>Esto es mas texto para col-sm-9 col-md-6 col-lg-8</p>
            </div>
        </div>
    </div>


## 66. Grid Examples
Otra propiedad importante de ver es el offset, permite mover columnsa a la izquierda usando .offset-md-* mueve a col-md-4 por sobre 4 columnas

    <div class="container">
        <div class="row">
          <div class="col-sm-5 col-md-6 bg-info">.col-sm-5 .col-md-6</div>
          <div class="col-sm-5 offset-sm-2 col-md-6 offset-md-0 bg-danger">.col-sm-5 .offset-sm-2 .col-md-6 .offset-md-0</div>
        </div>
        <div class="row">
          <div class="col-sm-6 col-md-5 col-lg-6 bg-primary">.col-sm-6 .col-md-5 .col-lg-6</div>
          <div class="col-sm-6 col-md-5 offset-md-2 col-lg-6 offset-lg-0 bg-secondary">.col-sm-6 .col-md-5 .offset-md-2 .col-lg-6 .offset-lg-0</div>
        </div>
      </div>

    


# Seccion 7, Reference
Esta seccion es un repaso a la seccion 02.Componentes, todo se encuentra ahi 

# Seccion 8, Project
## 79. Overview
La idea es crear un template que sirva para un 

- Build Home Page
- Build About Page
- Build Services Page
- Build Contact Page

## 80. Build Home Page
Teniendo en cuenta que Lo primero que se quiere construir es de arriba hacia abajo el **navigation** usando la clase **navbar**

Posteriormente se crera el ```<header>``` que contiene dentro un slide de imagenes como carrusel.

Luego se pone una seccion de marketing que va a permitir en unas tarjetas mostrar una seccion de marketing, puede mostear productos o ese tipo de elementos

Posteriormente va una seccino de portafolio que usa tarjetas portafolio para agregar 6 cajas que permiten listar proyectos.

Sigue la seccion de features que permite ver atributos y finalmente una seccion de llamado a la accion


## 81. Build About Page
La pagina about es tambien informativa, luego de la navbar tiene un heading donde se tienen breadcrumbs, donde se tiene una imagen con texto y tambien la presentacion del equipo, los clientes, y eso estodo, muy simplista


## 82. Build Services Page
La pagina de servicios tiene un breadcrumb para mostrar en donde esta y como regresa, un banner de toda la pantalla y tarjetas para cada servicio ofrecido

## 83. Build Contact Page
Esta apgina contiene un breadcrumb, una llamada a la api de maps para ver la direccion del negocio, al lado derecho la informacion del negocio, en la parte de abajo se desplega un formulario para permitir la subida de datos


# Seccion 9, Conclusion
