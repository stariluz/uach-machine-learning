
Acuraccy-> Exactitud
Queremos que el acuraccy sea cercano a 1

La perdida la queremos cercana a 0

Para regression siempre se utiliza MSE(Mean Sqare Error).

El mse lo queremos cercano a 0 ya que indica que hay poco error.

Esto es un analisis de regresion con redes neuronales convencionales.


Clasificacion
Si mi objetivo es obtener rangos de edad
3 rangos es igual a una capa final softmax con 3 neuronas

Regresion
Basados en los datos de caracteristicas de los datos de una persona
No queremos una funcion de activacion en la capa final ya que lo que queremos es una edad posible de la persona.

Hay analisis de reduccion de dimensionalidad
PCA(Principal Components Analysis) y SVD(Singular value composition)




Al comenzar, la eleccion de las capas la realizaremos basandonos en ejemplos similares, que hayan utilizado datos similares, o análisis similares

Recomendación: mover un parámetro a la vez para saber que parametro representa una mejora en nuestra caso.


El 95% de las ocasiones, la candidad de neuronas de la ultima capa son la cantidad de categorias que se pueden obtener.

Habitualmente en clasificacion, se coloca una neurona por caracteristica.


Deep learning hace alucion a las capas intermedias que tengamos.
Muchas capas intermedias implica un aprendizaje mas profundo de los patrones.
Tiene una mayor relacion con las redes neuronales convolusionales por que es mas común tener muchas capas intermedias en estas redes


### Redes neuronales convolucionales

Ideales para estructuras de datos cuadriculadas, por esto son ideales para analizar imagenes.

Fueron utilizadas en una competencia de 2012 ImageNet. Consistia en clasificar imagenes a color.

Los mejores algoritmos para el 2011 daban precision de 58%.

A partir del 2012, en esta competencia de ImageNet, que desarrollaron las CNN, se alcanzo una precision de 90%.

Geoffrey Hinton desarrollo en los 90 el algoritmo de backpropagation.

La primer sera una capa de convolución.
La convolución se da con un filtro o kernel. El kernel tiene cierto tamaño.
El problema de estas redes es que son altamente parametrizadas.

Este filtro/kernel, nos entrega un valor del analisis de la imagen, que es como una mezcla de si mismo con la imagen.

El filtro activara la convolusión en las zonas de más semejansa a si mismo, por lo cual, no se activará y no pasará los valores a la siguiente capa.
Matematicamente una convolusión no es eso, pero para un entendimiento sencillo lo podemos ver asi.

En la capa de convolusión debemos decir cuantos filtros tendremos y de que tamaño serán.

Luego le añadimos una capa de pooling. Esta realiza una operacion de downsampling (reduccion de dimenscionalidad).

Existen 2 tipos, el max pooling y el average pooling. El mas comun es max pooling, toma el mayor valor analizado por el kernel.

Las capas completamente conectadas son neuronas normales, no son convolucionales

Tarea: Dar un chequeo a la pagina con la informacion de las redes neuronales convolucionales.