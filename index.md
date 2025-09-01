# REGRESIÓN NO LINEAL - Distintos modelos para poder un conjunto de datos
En este proyecto se trabajó con una base de datos generada en el semestre de Otoño 2022 en la materia de Sistemas Digitales en la Universidad de Monterrey. La información corresponde a 432 actividades entregadas por estudiantes, donde se registró el tiempo restante para el cierre de la bandeja de entrega y la calificación obtenida. El objetivo principal fue analizar si existe una relación entre el tiempo de entrega de las tareas y el desempeño académico de los estudiantes, partiendo de la hipótesis de que, mientras más tarde se entrega la actividad, menor es la calificación obtenida.

En cuanto a la modelación, se entrenarán tres enfoques distintos de regresión:

 Regresión polinomial, que permitirá ajustar una curva de mayor orden y observar la forma de la relación entre las variables.

 Regresión segmentada, que consistirá en dividir el dominio en intervalos y entrenar funciones cuadráticas en cada segmento, para capturar patrones locales.

 Regresión KNN, que estimará los valores de calificación a partir de la cercanía entre observaciones en el espacio de características.

La evaluación de los modelos se realizará mediante el cálculo del RSE (Raíz del Error Cuadrático) sobre los datos de prueba, lo que permitirá medir la precisión de cada aproximación. No obstante, la comparación no se basará exclusivamente en el error, sino que también se tomarán en cuenta factores como la interpretabilidad, la complejidad y la robustez de cada modelo.

Este proyecto no solo permitió evaluar cuál modelo se adapta mejor a los datos, sino también reflexionar sobre la importancia de equilibrar precisión y claridad al momento de seleccionar un modelo predictivo.

Se incluyen los siguientes documentos:

 [Proyecto en formato ipynb](Regresion_no_lineal.ipynb)

 [Proyecto en formato HTML](Regresion_no_lineal.html)

 [Base de datos](Tiempo%20de%20Entrega.csv)
