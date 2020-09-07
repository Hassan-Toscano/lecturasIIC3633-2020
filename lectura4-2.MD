Artículo: Document clustering based on non-negative matrix factorization - Nombre: Jasiel Hassan Toscano Martinez

Resumen: Anteriormente, la agrupación de documentos se convirtió en un tema de interés para la comunidad científica
debido a que permite a las computadoras organizar un conjunto de documentos de la manera jerárquica grupal para su
navegación y exploración. Este tema sigue siendo abierto para investigación debido a que aún no existen métodos que
realicen con precisión el agrupamiento de documentos. En esta investigación se propone un método de agrupamiento
de documentos basado en la factorización matricial no negativa, que es utilizada para encontrar la estructura semántica
latente del corpus del documento e identificar grupos de documentos en el correspondiente espacio semántico latente.

Comentario: El método de agrupamiento está compuesto por cuatro etapas. En primer lugar, se realiza la construcción
de la matriz término-documento dado un corpus de documento, en donde cada columna representa el vector ponderado
término-frecuencia. En segundo lugar, se efectúa la factorización matricial no negativa para dos matrices no negativas.
En tercer lugar, se realiza la normalización de las matrices no negativas. Por último, se usa la segunda matriz negativa
para determinar la etiqueta grupo de cada punto de dados. El desempeño del método se evaluó comparando resultados
con una variación ponderada y dos métodos representativos de agrupamiento espectral, como la asociación promedio
y el corte normalizado. Los resultados señalan que la variación ponderada del método puede generar mejores resultados
en los corpus de documentos TDT2 Y Reuters.

Crítica: En el trabajo se indica que el éxito del método propuesto se basa en que el espacio semántico latente no necesita
ser ortogonal, garantizando que cada documento tome valores no negativos en todas las direcciones semánticas latentes
permitiendo que los resultados de agrupación de documentos se deriven sin la necesidad de las operaciones adicionales
 Esta estrategia puede conllevar algunos inconvenientes debido a que están forzando que documentos adquieran valores
no negativos en todas las direcciones semántica latentes. Los corpus de documentos están compuestos por agrupaciones
compactas y bien enfocadas, es decir, los corpus fueron construidos de forma manual. Por tal motivo, sería interesante
probar el método propuesto en corpus de documentos sin agrupaciones no tan compactas y que no estén bien enfocadas.

Referencia: Xu W., Liu X. and Gong Y., “Document clustering based on non-negative matrix factorization”, The 
adaptive web, In Proceedings of the 26th annual international ACM SIGIR conference on Research and development 
in informaion retrieval, pp. 267-273, 2003. DOI: 10.1145/860435.860485
