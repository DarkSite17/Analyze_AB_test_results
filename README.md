# Analyze AB test results
 
Las pruebas A / B las realizan con mucha frecuencia analistas de datos y científicos de datos. Es importante que aprenda a trabajar con las dificultades de estos.

Para este proyecto, trabajaremos para comprender los resultados de una prueba A / B realizada por un sitio web de comercio electrónico. La empresa ha desarrollado una nueva página web con el fin de intentar aumentar el número de usuarios que "convierten", es decir, el número de usuarios que deciden pagar por el producto de la empresa. Su objetivo es trabajar con este cuaderno para ayudar a la empresa a comprender si deben implementar esta página nueva, mantener la página anterior o quizás ejecutar el experimento por más tiempo para tomar una decisión.

Los datos y el Jupyter Notebook, que son todos los archivos que necesita para completar el proyecto, se le proporcionan en un archivo zip descargable en la pestaña de recursos (así como en "Materiales de apoyo" a continuación). Tenga en cuenta que partes del cuaderno hacen referencia a las pruebas que están vinculadas en esta lección para asegurarse de que está en el camino correcto.

Este proyecto le asegurará que domina los temas cubiertos en las lecciones de estadística. La esperanza es que este proyecto sea lo más completo posible de estos temas. 

## Tabla de contenido
- Introducción
- Parte I - Probabilidad
- Parte II - Prueba A / B
- Parte III - Regresión

## Librerias
- pandas
- Numpy
- random
- matplotlib
- scipy.stats
- statsmodels.api

## Etapas a reforzar:
 - Comprension del conjunto de Datos
 - Datos desordenados
 - Marco de datos
 - Probabilidad
 - Prueba de Hipotesis
 - Regresion
________

## Introducción
Las pruebas A / B las realizan con mucha frecuencia analistas de datos y científicos de datos. Es importante que aprenda a trabajar con las dificultades de estos

Para este proyecto, trabajará para comprender los resultados de una prueba A / B realizada por un sitio web de comercio electrónico. Su objetivo es trabajar con este cuaderno para ayudar a la empresa a comprender si deben implementar la página nueva, mantener la página anterior o quizás ejecutar el experimento por más tiempo para tomar una decisión.

## Parte II - Prueba A / B
Tenga en cuenta que debido a la marca de tiempo asociada con cada evento, técnicamente podría ejecutar una prueba de hipótesis de forma continua a medida que se observaba cada observación.

Sin embargo, entonces la pregunta difícil es: ¿se detiene tan pronto como una página se considera significativamente mejor que otra o debe suceder de manera consistente durante un cierto período de tiempo? ¿Cuánto tiempo se tarda en tomar la decisión de que ninguna página es mejor que otra?

### Parte III - Un enfoque de regresión
1. En esta parte final, verá que el resultado que logró en la prueba A / B en la Parte II anterior también se puede lograr realizando una regresión.
