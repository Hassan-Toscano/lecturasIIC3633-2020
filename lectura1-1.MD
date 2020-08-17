Crítica: [Sarwar, 2001] Item-Based Collaborative Filtering Recommendation Algorithms --- Nombre: Jasiel Hassan Toscano Martínez

Artículo: En este trabajo se realizó la evaluación de tres diferentes algoritmos enfocados en la similitud de elementos, 
como la similitud basada en el coseno, la similitud basada en la correlación y la similitud basada en el coseno ajustado. 
Además, en cada uno de estos algoritmos de similitud de elementos se realizó la implementación de un algoritmo para 
calcular la vecindad y la integración de los algoritmos suma ponderada y regresión para la generación de predicciones.

Problema: En esta investigación se propone abordar el tema de los sistemas de recomendación mediante algoritmos 
de filtrado colaborativo basados en elementos, también denominados algoritmos de filtrado colaborativo basados en el
modelo, para abordar los desafíos a los que se enfrenten los algoritmos de filtrado colaborativo basados en los usuarios,
como el desafío de mejorar la escalabilidad de los algoritmos y el desafío de mejorar la calidad de las recomendaciones.

Método: Los algoritmos de filtrado colaborativo basados en elementos analizan la matriz de representación usuario-
elemento para identificar relaciones similares entre el conjunto de elementos, que son utilizadas para la generación de
recomendaciones para los usuarios a través del cálculo del promediado ponderado de las puntaciones, es decir, calculan
las similitudes de los elementos para poder realizar la predicción mediante un promedio ponderado de las puntuaciones.

Los algoritmos de recomendación basado en elementos se dividen en dos etapas: a) Similitud entre elementos. En esta
etapa se realiza el cálculo de la similitud entre dos elementos mediante la implementación de técnicas para determinar
similitudes, como similitud basada en coseno, similitud basada en correlación y similitud basada en el coseno ajustado.
b) Generación de predicciones. Una vez que se efectúa la identificación de los elementos similares, se realiza el análisis
de las puntuaciones a través de técnicas para la generación de predicciones, como la suma ponderada y la regresión.

Evaluación: La evaluación se basó en la utilización de datos experimentales del sistema de recomendación Movielenz.
La calidad del sistema fue avaluada con base en el uso de la métrica del error absoluto medio. Los resultados se dividen
en resultados de calidad y resultados de rendimiento. En los resultados experimentales se observa que el algoritmo de
similitud basada coseno ajustado de coseno tiene un error absoluto medio menor en relación a los algoritmos anteriores.
El algoritmo de regresión muestra mejores resultados en la prueba para determinar la sensibilidad del conjunto de datos
en comparación al algoritmo de la suma ponderas. De igual forma el algoritmo de regreso muestra mejores resultados
en la calidad de las predicciones al cambiar el tamaño del vecindario. Sin embargo, se observa una disminución en la
calidad de las predicciones al aumentar el número de vecinos. Por último, se realizó una comparación de los enfoques
 en donde se establece que el algoritmo basado en elementos proporciona una mejor calidad que los algoritmos basados
en usuario. Además, el algoritmo basado en regresión se desempeña de mejor manera con un conjunto de datos escaso.

Conclusión (Personal): En este trabajo se realizó la evaluación de tres técnicas para calcular la similitud de elementos.
La técnica con mayor rendimiento fue el algoritmo de similitud basada en el coseno ajustado. El algoritmo de regresión
muestra un mejor comportamiento en la generación de predicciones en comparación con el algoritmo de suma pondera.
Las predicciones del algoritmo de filtrado colaborativo basado en los elementos son de una significativa mejor calidad
con respecto a las predicciones generadas por los algoritmos de filtrado colaborativo basados en el usuario. Este trabajo
permite observar avances que se obtuvieron en relación a los algoritmos de filtrado colaboradito basados en elementos,
también permite establecer nuevas líneas de investigación con la finalidad de mejorar la calidad de las predicciones.

Referencia: [Sarwar, 2001] Sarwar, B., Karypis, G., Konstan, J., & Riedl, J. (2001). Item-based collaborative filtering
recommendation algorithms. In Proceedings of the 10th international conference on World Wide Web (pp. 285-295).




