# El Juego de la Vida


En 1970, el matemático británico John Conway creó su **"Juego de la vida"**, un conjunto de reglas que imita el crecimiento caótico pero modelado de una colonia de organismos biológicos. 

El "juego" tiene lugar en una cuadrícula bidimensional que consiste en células "vivas" y "muertas", y las reglas para pasar de generación en generación son simples:

    * Sobrepoblación: si una célula viva está rodeada por más de tres células vivas, muere.
    * Estasis: si una célula viva está rodeada por dos o tres células vivas, sobrevive.
    * Subpoblación: si una célula viva está rodeada por menos de dos células vivas, muere.
    * Reproducción: si una célula muerta está rodeada por exactamente tres células, se convierte en una célula viva.

Al hacer cumplir estas reglas en pasos secuenciales, pueden aparecer patrones hermosos e inesperados.




![Game](https://www.oreilly.com/library/view/python-game-programming/9781785281532/graphics/B04505_02_03.jpg)
