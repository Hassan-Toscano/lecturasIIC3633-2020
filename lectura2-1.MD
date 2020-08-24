Crítica del Artículo: Collaborative Filtering for Implicit Feedback Datasets [Hu, 2008]

Resumen: Los sistemas de recomendación están basados en dos tipos de entrada. En primer lugar, la retroalimentación 
explicita que incluye información explicita de los usuarios en relación a su interés en los productos. En segundo lugar, 
la retroalimentación implícita que infiere las preferencias de los usuarios mediante la observación del comportamiento. 
El problema consiste en que la información explicita no siempre se encuentra disponible en los sistemas de información 
Por tal motivo, en este trabajo de investigación se propone desarrollar un modelo con base en el enfoque de los factores 
latentes en conjuntos de datos de retroalimentación implícita, que tienen por objetivo descubrir características latentes.

Comentarios: En mi opinión personal, la investigación realizada por Hu et al. 2008 es muy interesante debido a diversos
factores. En primer lugar, propone transformar las observaciones implícitas en dos magnitudes (preferencias, nivel de
confianza), es decir, en cada par usuario-elemento se es asignada una preferencia del elemento y un nivel de confianza.
En segundo lugar, se propone un modelo de factor latente como un enfoque alterno al enfoque del filtrado colaborativo
que tiene como objetivo descubrir características latentes abordando la transformación de las observaciones implícitas.
En tercer lugar, se propone un proceso de optimización que utiliza la estructura algebraica del modelo para abordar el
problema de escalabilidad que representa tomar valores de los pares usuario elemento provocando un excesivo tamaño.

Crítica (Elementos adecuados versus no adecuados): En mi punto de vista, no fue adecuado asignar un mismo nivel de
confianza a todos los pares usuario-elemento con una preferencia cero para provocar un ahorro computacional. En esta
investigación no se contempló integrar una variable tiempo para abordar que ciertos programas tienen más popularidad
en relación a otros programas. A diferencia de la retroalimentación explicita, este modelo considera todos los pares
usuario-elemento generando problemas de escalabilidad. Una característica importante es que permite desarrollar las
explicaciones de las recomendaciones. 

[Hu, 2008] Hu Y., Koren Y. and Volinsky C., “Collaborative filtering for implicit feedback datasets”, Eighth IEEE
International Conference on data mining, pp. 263-272, 2008. DOI: 10.1109/ICDM.2008.22


