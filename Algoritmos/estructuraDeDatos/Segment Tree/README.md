# Segment Tree
El Segment Tree es una estructura de datos muy versátil que sirve para responder varias consultas de agregación tipo máximo, mínimo, sumas, promedio, multiplicaciones y otras menos estándar, en tiempo log N para un universo de N elementos. Típicamente el Segment Tree se construye para responder consultas sobre un arreglo (como "entrégame el mínimo valor entre los índices i y j del arreglo"). 
También se pueden hacer actualizaciones de elementos de ese arreglo que tardan tiempo log N. Si tenemos entonces un problema donde hay Q consultas (preguntas por rango y actualizaciones de elementos) sobre un arreglo de largo N, el tiempo total de la solución con Segment Tree será Ο(Q log N) más el tiempo de construcción inicial del Segment Tree (que se puede lograr en Ο(N log N)).

![](https://miro.medium.com/max/1400/1*9V1l8_weUfmT4jHg21EE5w.png)
