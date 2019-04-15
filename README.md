# Practica02-Mi-Sitio-Web-CSS-
Adaptación de sitio web existente con reglas css

 	FORMATO DE INFORME DE PRÁCTICA DE LABORATORIO / TALLERES / CENTROS DE SIMULACIÓN – PARA ESTUDIANTES

CARRERA: Computación
DESARROLLADO POR: Adrian Viscaino	ASIGNATURA: Programación Hypermedial
NRO. PRÁCTICA:	2	TÍTULO PRÁCTICA: Resolución de problemas sobre HTML5
OBJETIVO ALCANZADO:
Lograr crear un diseño en páginas ya existentes para entender cómo funcionan las reglas en css

ACTIVIDADES DESARROLLADAS
Creación y conexión con un repositorio remoto en GitHub
Uso del repositorio GitHub
Implementación de reglas css para crear estructuras de paginas

Pruebas de las paginas en W3C
 
Actividades Desarrolladas












1.Creacion del Repositorio GitHub con el nombre Practica02 – Mi Sitio Web (CSS) 
https://raw.githubusercontent.com/aviscainoc/Practica02-Mi-Sitio-Web-CSS-/master/Capturas/c1.png


 

Una vez que creamos el repositorio procedemos a clonarlo en nuestra maquina con el comando Git: Clone, importamos los documentos HTML de las paginas ya creadas para implementar el diseño en estas.
2. Creación de un archivo que permita manejar dos columnas en una pagina
Para este paso se trabajó con el archivo index.html, en donde se dio a algunas de las secciones id y clases para poder trabajar de manera más ordenada y poder usarlas en las reglas.
 ’
El uso del ID= “menú” nos va a permitir trabajar con esa sección refiriéndonos como un solo bloque, esto lo utilizaremos para trabajar con cajas, además esta sección será la primera columna de nuestra página.
 

Al poseer distintas secciones en esta parte del documento lo que hacemos es agrupar todo con una etiqueta div, a esta etiqueta le añadimos un id “c1” la cual utilizaremos para referirnos a la columna 2 en nuestra estructura, además de trabajar las columnas también se añaden identificadores a los apartados de los encabezados y el pie de documento.
 
 

Una vez que tenemos identificadas nuestras cajas de trabajo procedemos a darle una estructura a estas en un archivo .css, el cual contendrá las reglas que nos darán formato a la página. El archivo para la práctica tendrá el nombre de “dos_columnas.css”

  







Como se puede observar, las partes principales y que se repiten en cada identificador son las propiedades de los border, estas propiedades son las que nos permitirían observar las líneas de las cajas con las que estamos trabajando, además se utiliza propiedades como la altura(height) y anchura(width) para ajustarlas a las páginas y a lo que necesitamos. Otra propiedad importante es especificar la posición, utilizamos una posición relativa y en la propiedad de float, establecemos que será left, esto para que las cajas se organicen de una manera consecutiva así conseguimos el formato deseado.
Para realizar la estructura de 3 formatos trabajos en el archivo “p_caracteristicas.html” esta página contiene secciones que dividí en 3: 1. El menú de navegación; 2. Una tabla informativa con un video multimedia; 3. Conceptos necesarios para esta sección. A cada una de estas secciones se le dio un identificador siendo estos: “menú”, “c1”, “c2”.
 
 
 

Con la información separada con identificadores en nuestro archivo CSS “tres_columnas.css” procedemos a crear las reglas con sus respectivas propiedades, el proceso es el mismo seguido para las dos columnas.

  

Una vez que realizamos estos procedimientos nuestras paginas tienen el formato solicitado.
 
 


3. Creacion del archivo para las reglas CSS.
Para el resto de paginas, se creo un nuevo archivo que contendria reglas generales para todo el sitio web, entre estas reglas se encuentran especificaciones para los tamanos de imagen, posicion de los menus, de los textos tamano de fuente, color tipo, etc. 

Primero empezamos en una regla general para establecer un fondo de pantalla para todo el sitio web.
 

A demas en la practica anterior exisitio problemas con la creacion de estructuras como las tablas o la insercion de video, por ello con la creacion de archivos .css establecemos aquí las propiedades eliminando asi esos errores de pagina.
 



4. Creacion de una pagina de contacto
En esta parte vamos a crear un nuevo documento .html que contenga informacion y cajaas de texto para introducri nuestros datos y que nos permita enviar un mensaje o sugerencia, utilizando un boton. La estructura de esta pagina es la siguiente:
 

Html ya permite etiquetas con la finalidad de hacer formularios de contacto, se hizo uso de llas y  y se fue editando las secciones que necesitabamos, como el form, en el que especifica el titulo, el uso de lable para etiquetar las secciones y el uso de input, que complementando con el type nos ayuda a crear las seeciones de recepcion de mensaje.

5. Uso de Pseudo-clases
El uso de Pseudo clases en esta practica se ve reflejado en la pagina de “p_historia_budismo” Aquí tenemos 6 articulos, cada uno con su respectivo titulo y enlaces entre ellos con un menu de navegacion, con el uso de pseudo clases especificamos que cuando un enlace sea abierto este cambie de color, el tamano de fuente y obtenga una linea debajo de texto de color violeta
 
6. Uso de selectores
Para cumplir este punto se utilizo 3 tipos de selectores, selector por clase, selector por id y selector descendente.
•	Selector por clase
Este selector se utilizo en el archivo de reglasformulario.css, para poder modificar secciones de nuestro formulario, ya que era necesario editar secciones especificas por ello se trabajo como el siguiente ejemplo:
 
 


•	Selector por id
Fue uno de los mas utilizados al ser este sitio web un sitio con secciones en lso que se necesitaba especificar elementos en cada pagina se prefirio el uso de estos para evitar confusiones. Un ejemplo claro es el del menu de navegacion.
 
 
•	Selector descendente
El uso de selectores descendente es necesario para especificar secciones dentro de clases id o etiquetas, en el trabajo se ve reflejado en la parte de Contacto
 
 














Link del Repositorio
https://github.com/aviscainoc/Practica02-Mi-Sitio-Web-CSS-.git
Usuario
aviscainoc



•	El trabajo desarrollado nos ayuda a conocer mejor el comportamiento de la creación de paginas web en los aspectos de diseño, se puede conocer que es mejor trabajr con estructuras para poder generalizar y asi trabajar de una manera mas rápida y eficiente sin desperdiciar tanto código, tiempo y esfuerzo.





Viscaino Conce Adrian Fernando

 
                       .               

