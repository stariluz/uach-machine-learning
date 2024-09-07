La estandarización se relaiza cuando
tenemos datos de tipo normal.

### Estandarización
En caso de no tenerlos, debemos realizar una
normalización de los datos.
La estandarízación tendrá una media de 0 y una desciación estándar de 1.
Es util cuando los datos siguen una distribución normal o aproximadamente normal.
EL SVM o regresión lógica la utilizan.

### Normalizacion
Los datos se comportarán dentro de un rango específico, entre 0 y 1.
Permite que las caracteristicas de mayor magnitud influyan en el modelo.
Se utiliza cuando no se puede asumir una distribución normal de los datos o contienen características en distintas escalas.
Es común en redes neuronales ya que ayuda a la
convergencia durante el entrenamiento.

### Reescalamiento
Importante en algoritmos con técnicas de distancia


# Detección y manejo de valores extremos

¿Cómo podemos hacer para no considerar los datos anómalos?
### Métodos estadísticos
#### Rango intercuartilico
Para identificar los Outliers se considera un Rango.

---

Vamos a trabajar con una base de datos llamada iris en python.

Para la estandarízación utilizaremos la librería sklearn.


En python lka estandarización y normalización se hace sobre las columnas, no sobre todo el conjunto de datos. Esto es debido a que cada columna representa distintas características, no nos interesa mezclar todas las características.


La normalización nos deja todos los datos entre 0 y 1


La obtención de los datos es lo complicado en estos proyectos.

$$
\begin{cases}
2x + 3y = 5 \\
4x + 5y = 6
\end{cases}
$$
