# Union Find
La estructura Union-Find, también llamada Disjoint-set Union (abreviado DSU), es una estructura que nos permite manejar conjuntos disjuntos de elementos. Un ejemplo de esto en grafos son las componentes conexas, que son conjuntos disjuntos de nodos.

Cada conjunto va a tener un representante que lo identifica, y las operaciones que debemos poder realizar eficientemente son:

· find(x): Dado un elemento x, nos dice quién es el representante del conjunto al que pertenece.

· union(x,y): Dados dos elementos x e y, unir los conjuntos, es decir, que pasen a ser uno solo, con un solo representantes para los elementos de ambos conjuntos.

![](https://he-s3.s3.amazonaws.com/media/uploads/ff4f029.jpg)
