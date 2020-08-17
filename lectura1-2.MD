
Crítica: [Funk, 2006] Netflix Update: Try This at Home

Problema: La empresa de entretenimiento proporcionó a los participantes cien millones de puntuaciones en una tripleta 
de números con un formato (usuario, película, calificación). Estas puntuaciones corresponden a diecisiete mil películas 
por quinientos mil usuarios, por lo que resulta una matriz de 8,500 millones de entradas con 8,400 millones de espacios 
sin información. El problema principal consistió en cómo predecir una puntuación a partir de una tripleta (usuario, 
película, desconocido), es decir, que puntuación se le daría a una película que no se encuentra en el conjunto de datos.

Contexto: En este trabajo se establece que el problema podría ser resuelto al encontrar generalidades, que pueden ser 
más concisas y descripticas que los 8,500 millones de entradas. En este sentido, se establece que el razonamiento puede 
funcionar de manera inversa que es una propiedad del aprendizaje automático, es decir, se pueden encontrar algunas 
generalidades significativas que puedan representar la información en un número menor que 8500 millones de entradas.

Método: En este trabajo se presenta un modelo que se denomina descomposición de valor singular en donde se asume 
que la puntuación de una película se compone de una suma de preferencias en relación a los aspectos de la película, es 
decir, la suma de las multiplicaciones de las preferencias de cada usuario por el aspecto de la correspondiente película.

Este modelo podría generar aproximadamente 20 millones de puntuaciones a partir de la descomposición de la matriz 
original en dos distintas matrices: matriz de aspecto de la película y matriz de preferencias de usuario. Esta estrategia 
de descomposición podría minimizar el error de aproximación. Sin embargo, la utilización de este modelo sobrelleva 
desventajas, como el costo computacional en la multiplicación de matrices y escasa información que limita problema.

Solución: En este trabajo se utilizó la derivada error de aproximación, es decir, se usaron las ecuaciones del error entre 
el modelo de descomposición de valor singular y la información de los cien millones de entradas, para posteriormente 
usar la derivada para inferir el valor de los parámetros. Esto fue evaluado para cada puntuación en un conjunto de datos 
de entramiento. En este trabajo se muestra la rutina para entrenar una muestra, en donde se observa el entrenamiento 
de la característica con la finalidad de encontrar la característica más descriptiva.
