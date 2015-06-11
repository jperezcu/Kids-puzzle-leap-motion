# Kids-puzzle-leap-motion
Juego de rompecabezas para niños, requiere de un dispositivo Leap Motion

Dado que la aplicación es un archivo .html, simplemente se debe acceder a él a través de cualquier navegador web. Su contenido se adapta al tamaño de la ventana, permitiendo su uso en pantallas de distinto tipo.

El juego consiste en ordenar un rompecabezas básico, pensado para niños. Del lado derecho de la pantalla se muestran las piezas desordenadas, y el objetivo es ordenarlas llevándolas del lado izquierdo de la pantalla hasta lograr la imagen completa.

El usuario debe señalar la ficha que quiera posicionar en el tablero y llevarla con el movimiento del dedo hasta el lugar en la izquierda que le corresponde a esa ficha. Esto se debe hacer con todas las fichas.
Una vez ordenado el rompecabezas, aparece un mensaje que felicita al usuario y se pasa al nivel siguiente. También se puede cambiar de nivel en cualquier momento con el gesto que se conoce como “swipe”: hacia la izquierda pasa al siguiente nivel y hacia la derecha vuelve al nivel anterior. El "swipe" requiere del uso de varios dedos de la mano.

En su estado actual, la aplicación cuenta con cuatro niveles. Cada nivel cuenta con una ilustración distinta dividida en 4 piezas de igual tamaño y forma.

Se pueden agregar niveles extra agregando un archivo .jpg a la carpeta /images/puzzles/N.jpg, donde N es el número de nivel próximo a los que ya existen. Este archivo debe ser una imagen de cualquier tamaño, sin importar su proporción. Para que la aplicación reconozca este nivel, hay que actualizar el valor de la variable "levelQty" en las primeras líneas del código javascript.