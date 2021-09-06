# DINIC
El algoritmo de Dinic es un algoritmo de Tiempo polinómico para la computación de un Flujo maximal en una red de flujo. El algoritmo es ejecutado en un tiempo de O(V^{2}E) y está basado en el Algoritmo de Edmonds-Karp, el cual a su vez se ejecuta en un tiempo O(VE^{2}), y utiliza trayectorias de aumento más cortas. La introducción de los conceptos nivel de grafo y bloqueo de flujo es lo que define el rendimiento del algoritmo de Dinic.

Opera suando el BFS para poder ver las posible soluciones que tiene el maximo numoer de aristas, despues usa el DFS para poder recorrer cada uno de ellos. 

![](https://i.ytimg.com/vi/8pU6dh0CA6Y/maxresdefault.jpg)
