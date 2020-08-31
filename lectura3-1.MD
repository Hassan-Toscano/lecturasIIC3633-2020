Critica Artículo: Performance of recommender algorithms on Top-N recommendation tasks

Resumen: En la práctica, los sistemas comerciales sugieren algunos elementos específicos que probablemente
son más atractivos para el usuario a lo que se denomina Recomendación Top-N, mientras que los valores de
las puntuaciones no son visualizadas. En la actualidad, las métricas tradicionales de error no miden realmente
 el rendimiento de la recomendación Top-N, por lo que se sugiere medir el rendimiento a través de metodologías
basadas en métricas de precisión. Por tal motivo, en este trabajo se evalúa el desempeño de siete algoritmos de
recomendación orientados en la extracción de N elementos más recomendables, mediante el uso de las métricas
de precisión. Los algoritmos son: MovieAvg, TopPop, CorNgbr, NNCosNgbr, AsySVD, 200-D SVD ++ y una
variante que se propone en este trabajo basada en los modelos de factores latentes denomanda PureSVD.

Comentarios: La evaluación de algoritmos se realizó en los conjuntos de datos Netflix y Movielens. En primer
lugar, se realizaron experimentos en Movielens sobre el conjunto de prueba completo y en el conjunto de prueba
de elementos cola larga. Los mejores algoritmos en términos de recuperación y precisión son: PureSVD, NNCos
Ngbr, SVD++. En segundo lugar, se realizaron experimentos en Netflix sobre el conjunto de prueba completo
y en el conjunto de prueba de elementos de la cola larga. Los algoritmos con mejores resultados en términos de
recuperación y precisión son: PureSVD, NNCosNgbr, CorNgbr.

Crítica El algoritmo PureSVD presenta un mejor rendimiento en comparación con los algoritmos tradicionales
basados en modelos de factores latentes. Además, se puede observar una mejor precisión en conjunto de prueba
cola larga debido a que los factores latentes representan características relacionadas a elementos no populares.
El bajo rendimiento de los modelos de factores latentes se atribuye a la limitación de las pruebas de las métricas
de error, que se concentran solamente con las puntaciones, mientras que las métricas de precisión basadas en la
recomendación N elementos se concentra en considerar todos los elementos en la etapa de prueba.

Referencia: Cremonesi P., Koren Y. and Turrin R., “Performance of recommender algorithms on top-n
recommendation tasks”,In: Proceedings of the fourth ACM conference on recommender systems, pp. 39-46,
2010. DOI: 10.1145/1864708.1864721
