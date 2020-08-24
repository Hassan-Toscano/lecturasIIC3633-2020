Crítica del Artículo: BPR: Bayesian personalized ranking from implicit feedback [Redle, 2009]

Resumen: La recomendación de elementos tiene por objetivo predecir una puntuación personalizada para un conjunto
de elementos. En la literatura se observan algunas investigaciones relacionadas que centran su interés en escenarios en
donde se utiliza la retroalimentación explicita. Sin embargo, en escenarios reales por lo regular la retroalimentación es
implícita. En esta investigación se establece que en esos tiempos existían métodos diseñados para realizar la predicción
de elementos a través de la retroalimentación implícita, pero ninguno de estos métodos estaba directamente optimizado
para recomendación de elementos. En esta investigación se propone un criterio de optimación denominado BPR-Opt
y un algoritmo de aprendizaje genérico designado LearnBPR que se utilizan para realizar la puntuación personalizada.

Comentario: La puntuación personalizada esta basada en el criterio de optimación genérico BPR-Opt que consiste en
un estimador posterior máximo derivado de un análisis bayesiano del problema a través de la utilización de una función
 una verosimilitud y la probabilidad previa para el parámetro del modelo. El algoritmo aprendizaje genérico LearnBPR
se basa en el descenso de gradiente estocástico con un muestreo de arranque. El correspondiente algoritmo fue utilizado
para optimizar dos modelos de aprendizaje, tales como la factorización matricial y K vecinos más cercanos adaptativo.

Crítica (Elementos adecuados vs no adecuados): La optimización de modelos de recomendación con base en el criterio
de optimación superan resultados de los mismos modelos que se encuentran optimizados con base en otros criterios.
La calidad de predicción depende del criterio de optimización, es decir, el criterio de la optimación es muy importante
en la puntuación personalizada. No me parece una buena estrategia reconstruir pares de elementos asumiendo que los
usuarios prefieren elementos en relación a otros elementos. Esta estrategia se utilizó para evitar remplazar los valores
perdidos por valores negativos. Los valores perdidos entre dos elementos no observados son los elementos a clasificar. 

[Rendle, 2009] Rendle S., Freudenthaler C., Gantner Z. and Schmidt-Thieme L., “BPR: Bayesian personalized ranking
from implicit feedback”, Proceedings of the twenty-fifth conference on uncertainty in artificial intelligence, pp. 452-
461, 2009.

