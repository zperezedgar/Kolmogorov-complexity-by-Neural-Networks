# Kolmogorov-complexity-by-Neural-Networks
An implementation which uses neural networks for a low-cost and fast implementation of Kolmogorov complexity.
Based in the results of https://github.com/algorithmic-dynamics-lab/pybdm

Diseño de una red neuronal para medir la complejidad algorítmica de una secuencia de bits.

Medir la complejidad de una secuencia de bits mediante la definición de complejidad algorítmica o 
complejidad de Kolmogorov es imposible, sin embargo, recientemente se ha desarrollado un método y 
una librería para poder aproximarla. Esta librería requiere mucho tiempo de computo para secuencias 
de longitudes grandes. Mi propuesta es diseñar una red neuronal que reciba como datos de entrenamiento, 
mediciones aproximadas de la complejidad de Kolmogorov de algunas secuencias. Después entrenaré la red
para que aprenda a predecir esta complejidad. Como la red ya se encontrará entrenada, la evaluación de 
la complejidad de nuevas secuencias será inmediata y ya no requerirá mayor tiempo de computo, por lo 
que de esta forma aumentaré la utilidad de esta medición para aplicaciones diversas.
