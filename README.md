
 Calculadora
Este proyecto consiste en una calculadora web simple, construida utilizando HTML, CSS y JavaScript. A continuación, se detallan los componentes principales del código y su funcionalidad.

[![imagen-2024-08-15-112737645.png](https://i.postimg.cc/HWPkzt3z/imagen-2024-08-15-112737645.png)](https://postimg.cc/JtZ84ZfH)

Estructura del Proyecto
Archivos Principales
index.html: Este archivo contiene la estructura básica de la calculadora.
index.css: Archivo de estilos que define la apariencia de la calculadora.
Display.js: Script que maneja la visualización de los valores en la calculadora.
Calculadora.js: Script que contiene la lógica de operaciones matemáticas.
index.js: Script que inicializa la calculadora y maneja interacciones del usuario.}

HTML:
La estructura HTML define el diseño de la página web.

La sección contiene metadatos y recursos necesarios para la página. Incluye:

meta nombre="viewport" content="ancho=ancho del dispositivo, escala inicial=1.0"
título de la página web
enlaces a la hoja de estilo y fuentes externas
Incluye un contenedor para agrupar y esta compuesto por
 Contenedor Principal: Utiliza una <div> con la clase container que alberga toda la calculadora.
Display: Dos <div>s dentro de la clase display muestran el valor anterior y el valor actual.
Botones: Cada botón tiene una clase que lo categoriza como numero u operador, permitiendo la interacción del usuario. Los botones de los números permiten ingresar valores, mientras que los botones de operadores ejecutan operaciones matemáticas.

CSS
el estilo CSS define la apariencia de los elementos de la página web.
 proporciona un  estilo  para  el fondo de la calculadora y su estilo en forma rectangular 
proporciona un estilo para los botones y el fondo 
el fondo de la pantalla

JAVASCRIPT
el primero titulodo calculadora proporciona métodos para realizar operaciones matemáticas básicas: suma, resta, división y multiplicación. Esta implementación es sencilla y permite a los usuarios realizar cálculos de manera rápida y eficiente.

el segundo tiutlado Display gestiona la lógica de interacción de una calculadora, permitiendo al usuario ingresar números, realizar operaciones y ver los resultados en la interfaz de usuario. Utiliza métodos para manejar la entrada del usuario y actualizar la pantalla de la calculadora utilizando 

displayValorAnterior y displayValorActual: Elementos del DOM donde se mostrarán los valores.
calculador: Instancia de otra clase llamada Calculadora, que probablemente maneja las operaciones matemáticas.
tipoOperacion: Almacena el tipo de operación actual (suma, resta, etc.).
valorActual y valorAnterior: Cadenas que almacenan los números actuales y anteriores.
signos: Un objeto que mapea los tipos de operaciones a sus símbolos correspondiente





