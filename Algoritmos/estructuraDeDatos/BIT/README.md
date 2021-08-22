# BIT
Un árbol binario indexado, árbol de Fenwick o BIT, es una estructura de datos que proporciona métodos eficientes para el cálculo y la manipulación de las cantidades de prefijos de una array de valores. 
![](https://i.imgur.com/89YKLj4.png)

El Fenwick Tree o BIT principalmente resuelve el problema de equilibrar la eficiencia de la suma del prefijo con la eficiencia de modificar un elemento. La eficacia de estas operaciones se presenta como una solución de compromiso, (dado que una mayor eficiencia en el cálculo de la suma del prefijo se consigue precalculando los valores, pero una vez que los valores son precalculados, debe volverse a calcular cada vez que ocurra una modificación). Esto haría O(1) las consultas pero las modificaciones serían O(n). El Fenwick Tree hace ambas operaciones en O(log n), donde n es el tamaño del array.

