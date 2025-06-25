# Sistema de Recomendación con SVD

Este repositorio contiene un sistema de recomendación utilizando la descomposición en valores singulares (SVD) y técnicas de reducción de dimensionalidad. El sistema predice las calificaciones de los usuarios para películas basándose en las interacciones previas de usuarios y películas, utilizando el algoritmo de **SVD** para descomponer y reconstruir la matriz de interacciones. Además, se utiliza **PCA** para determinar el número de componentes latentes adecuados para optimizar la eficiencia y precisión del modelo.

## Instrucciones

1. Clona este repositorio a tu máquina local.
2. Asegúrate de tener instaladas las librerías necesarias (como pandas, numpy, scikit-learn, etc.).
3. Descarga el dataset '
4. Ejecuta los scripts de Python para ver los resultados y las predicciones de calificación.

## Resultados
La matriz reconstruida obtenida de la descomposición muestra una aproximación de las calificaciones que los usuarios podrían asignar a las películas que no calificaron originalmente. Por ejemplo, el valor predicho para la calificación del usuario 4 para la película 1 es 20490.475165297998, lo que sugiere que el modelo ha estimado una calificación muy alta para esa película, basándose en las relaciones latentes que se descubren mediante SVD

En resumen, al aplicar SVD con 300 componentes, hemos logrado reducir la dimensionalidad de los datos y al mismo tiempo realizar predicciones útiles sobre las calificaciones faltantes, lo que es fundamental para los sistemas de recomendación.
