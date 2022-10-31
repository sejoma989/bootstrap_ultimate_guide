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

Usando liveserver se puede acceder al archivo que se esta editando en atom



# Seccion 5, Components

# Seccion 6, Grid

# Seccion 7, Reference

# Seccion 8, Project

# Seccion 9, Conclusion
