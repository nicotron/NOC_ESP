## I.1 Paseos Aleatorios

Imagina que estás de pie en medio de una barra de equilibrio. Cada diez segundos lanzas una moneda al aire. Cara, das un paso hacia adelante. Sello, das un paso hacia atrás. Esto define un pase aleatorio —un camino definido por una serie de pasos aleatorios. Llevando la barra de equilibrio hacia el suelo, podrías realizar un paseo aleatorio en dos dimensiones, lanzando la moneda dos veces con los siguients resultados:

| Lanzamiento 1 | Lanzamiento 2 |        Resultado        |
| :-----------: | :-----------: | :---------------------: |
|     Cara      |     Cara      |   Paso hacia adelante   |
|     Cara      |     Sello     |  Paso hacia la derecha  |
|     Sello     |     Cara      | Paso hacia la izquierda |
|     Sello     |     Sello     |    Paso hacia atrás     |



Pareciera que es particularmente un algoritmo poco sofisticado. Sin embargo, los paseos aleatorios pueden ser usados para modelar fenómenos que ocurren en el mundo real, desde el movimiento de moléculas en un gas, hasta el comportamiento de un apostador a lo largo de un día en el casino. En cuanto a nosotros, empezaremos este libro estudiando un paseo aleatorio con tres metas en mente.

1. Necesitamos repasar un concepto de programación central —Programación Orientada a Objetos. El caminante aleatorio nos servirá como modelo para que el diseño orientado a objetos que usemos haga que cosas se muevan dentro de la ventana de Processing.
2. El caminante aleatorio induce las dos preguntas que nos haremos a través de todo este libro: "¿Cómo definimos las reglas que gobiernan el comportamiento de nuestros objetos?" y luego "¿Cómo implementamos estas reglas en Processing?"
3. A travéz del libro, periódicamente necesitaremos un entendimiendo básico de aleatoriedad, probabilidad y Perlin Noise. El paseo aleatorio nos permitirá demostrar algunos puntos imporntantes que nos serán útiles más adelante.