#Información del Dataset

##Wine recognition data

###Descripción
Este dataset contiene información de los resultados de un análisis 
químico de vinos cultivados en la misma región de Italia pero de tres distintos cultivos.
El análisis determino la cantidad de 13 consituyentes encontrados en cada uno de los 3 tipos de vino.

###Características
Son 13 características:

1. Alcohol
2. Malic acid
3. Ash
4. Alcalinity of ash  
5. Magnesium
6. Total phenols
7. Flavanoids
8. Nonflavanoid phenols
9. Proanthocyanins
10. Color intensity
11. Hue
12. OD280/OD315 of diluted wines
13. Proline

###Clases
El dataset está compuesto por 3 clases con las siguientes instancias:

-Clase 1 59
-Clase 2 71
-Clase 3 48 

###Descarga del dataset
Link de descarga del dataset: https://archive.ics.uci.edu/ml/machine-learning-databases/wine/
Dataset: wine.data

Alternativamente sklearn posee ya el dataset al cual es accese importando:
*from sklearn import datasets*
*wine = datasets.load_wine()*
*X=wine.data*
*y=wine.target*