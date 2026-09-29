#**Cocktail Shaker Sort**

**Complejidad en el mejor caso**  
El mejor caso posible es O(n)  
**Complejidad en el peor caso**  
El mejor caso posible es O(n2)  
**Complejidad en el caso promedio**  
En este caso este algoritmo comparte la complejidad del caso promedio con la del peor caso es decir O(n2)   
**¿Es adecuado para Big Data? ¿Por qué?**  
No, este algoritmo no es adecuado para Big Data ya que el tiempo de procesamiento crece de forma cuadrática colapsando los recursos.

[Video](https://www.youtube.com/watch?v=njClLBoEbfI)

**Idea:** El algoritmo recorre el array en ambas direcciones, comparando elementos adyacentes e intercambiándolos si están desordenados. Primero de izquierda a derecha y después de derecha a izquierda, repitiendo hasta que no haya intercambios.

**Complejidad:** O(n²) en promedio y peor caso

**Espacio:** O(1) \- in-place
