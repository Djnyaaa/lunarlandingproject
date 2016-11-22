# Proyecto Lunar Landing

**Proyecto creado por Kevin Blanco, Oscar Adrian Mudarra, Vili Mihaylov y Jordi Genovart.**

## Partes del proyecto

### Modelo Horizontal

El diseño esta dividido en 6 partes que ire explicando acontinuación: 

* Fondo: Ocupará el 100% de la pantalla, la imágen que se utilizará se llama "Fondo.jpg" y esta ubicada en la carpeta IMG.

* Superficie: Ocupará el 100% de ancho. Tiene una posición Absolute  y el fondo sera la imágen "Superficie.png" que estará situada en la parte inferior de la pantalla y se usará el Background-size cover para hacer que la imagen ocupe el fondo.

* Opciones: Ocupara el 100% de alto y 20% de ancho de la pantalla. El fondo será de color Blanco y tendrá una posición Fixed. Además estara situado en la parte superior izquierda de la pantalla. Dentro de este DIV, habrán otras 4 que serán para cada opción.

* Panel de Control: Dentro de la parte de Opciones, habrán 4 DIV's que tendrán el 100% de ancho y el 25% de alto del DIV de Opciones. Además tendrá un borde que será de 10 pixeles solido de color negro y el texto centrado. Ademas habrá un DIV IMG para controlar el tamaño de la imagen que ira dentro.

* Estado: Ocupará el 20% de ancho y 20% de alto de la pantalla. Tendrá una posición Fixed, un fondo Blanco y estará situado en la parte superior derecha. Tendrá una lista que no tendrá estilo, tendra un padding de 15 pixeles.

* Nave: La imágen tendra un tamaño fijo de 200 pixeles  de ancho y 190 pixeles de alto. Una posición Absolute además de estar situada en la parte central y un margen negativo hacia la derecha para dejar centrara la imagen. La imágen utilizada sera la que esta ubidaca en la carpeta IMG.

* Sonido: Al iniciar el juego tendrá una musica que se reproducira automaticamente y luego con javascript se tratará para que pueda ser silenciada.

### Modelo Vertical

El diseño tambien está dividido en 6 partes que ire explicando acontinuación: 

* Fondo: Ocupará el 100% de la pantalla, la imágen que se utilizará se llama "Fondo.jpg" y esta ubicada en la carpeta IMG.

* Superficie: Ocupará el 100% de ancho. Tiene una posición Absolute  y el fondo sera la imágen "Superficie.png" que estará situada en la parte inferior de la pantalla y se usará el Background-size cover para hacer que la imagen ocupe el fondo. Estará a un 12% del fondo dado que habra un DIV situado debajo y esa su la medida de alto.

* Opciones: Ocupara el 12% de alto y 100% de ancho de la pantalla. El fondo será de color Blanco y tendrá una posición Absolute. Además estará situado en la parte inferior de la pantalla. Dentro de este DIV, habrán otras 4 que serán para cada opción.

* Panel de Control: Dentro de la parte de Opciones, habrán 4 DIV's que tendrán el 23% de ancho y el 100% de alto del DIV de Opciones. Además tendrá un borde que será de 10 pixeles solido de color negro y el texto centrado. Ademas habrá un DIV IMG para controlar el tamaño de la imagen que ira dentro.

* Estado: Ocupará el 100% de ancho y 10% de alto de la pantalla. Tendrá una posición Fixed, un fondo Blanco y estará situado en la parte superior. Tendrá una lista que no tendrá estilo, tendra un padding de 15 pixeles y el tamaño de la fuente será 9 puntos.

* Nave: La imágen tendra un tamaño fijo de 100 pixeles  de ancho y 90 pixeles de alto. Una posición Absolute además de estar situada en la parte central y un margen negativo hacia la derecha para dejar centrara la imagen, tendrá un espacio de 20% de alto de la nave hasta la parte superior para que no interfiera con el Estado. La imágen utilizada sera "Nave.jpg" que esta ubicada en la carpeta IMG.

* Sonido: Al iniciar el juego tendrá una musica que se reproducira automaticamente y luego con javascript se tratará para que pueda ser silenciada.
