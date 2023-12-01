[`Computación Flexible`](../README.md) > `Unidad 5. Red de Kohonen`

## Unidad 5. Red de Kohonen

### Objetivo

En esta clase el alumno conocerá:

* Introducción al aprendizaje no supervisado
* La estructura básica SOM.
* El algoritmo entrenamiento de una red unidimensional de Khonen
* Visualización de clústers
  
### 1. Introducción 

#### Aprendizaje no supervizado

El aprendizaje supervisado elimina al maestro y requiere que el alumno forme y evalué los conceptos por su cuenta. Los científicos son quizá el mejor ejemplo de aprendizaje no supervisado en humanos. Los científicos no tienen el beneficio de un maestro. En su lugar, ellos proponen hipótesis para explicar sus observaciones, evalúan sus hipótesis utilizando criterios como la simplicidad, la generalización y la elegancia; y prueban sus hipótesis a través de experimentos de su propio diseño.

El agrupamiento  (o análisis de grupos)  es una técnica que nos permite encontrar grupos de objetos similares que esta más relacionados uno con otros que con otros del grupo. Ejemplos de aplicaciones de agrupamiento orientadas al negocio incluyen el agrupamiento de documentos, música y películas de diferentes temas, o encontrar clientes que tienen intereses similares basados en comportamiento de compras comunes com una base de un motor de recomendaciones.

#### k-means

Un ejemplo de aprendizaje no supervisado es el algoritmo k-means

K-medias o *K-Means* es un algoritmo de agrupación basada en prototipos lo que significa que utiliza prototipos (***centroides***) para representan a un grupo de objetos. 

__Algoritmo de k-means__

1Elegir de manera aleatoria $k$ centroides de los ejemplos como centros de clusters iniciales.
2. Asignar a cada ejemplo al centroide más cercano, $\mu^{(j)}, j \in \{1, \ldots k\}$.
3. Mover el centroide al centro de los ejemplos que fueron asignados a él.
4. Repetir pasos 2 y 3 hasta que la asignación del clúster no cambie o el usuario defina una tolerancia o un número mínimo de iteraciones es alcazado.

* [`Ejemplo K-means Iris`](./code/k_means_sklrn_iris.ipynb)

### 2. Mapas Auto-Organizativos

* Las Redes de Kohonen o knet (SOM, por las siglas en inglés de Self-Organization Map) es un tipo de red no supervisada.

* Están basadas en un aprendizaje competitivo, es decir, que las neuronas compiten entre ellas para ser activadas o encendidas. La neurona que gana la salida es llamada _winner-taker-all-neurons_ o _winning neuron_ (neurona ganadora).

#### Estructura básica de SOM

Los SOM al igual que el cerebro humano tienen la tarea de mapear información de alta dimensión (n dimensiones) en áreas de una cuadrícula de baja dimensión (g dimensiones) para dibujar un mapa del espacio de alta dimensión.

La estructura de SOM solo contiene una capa de entrada de neuronas y una capa de neuronas de salida. No hay capaz ocultas. 

### 3. Entrenamiento de la Red Unidimensional de Kohonen

[`SOM unidimensional paso a paso`](./code/som_unidimensional.ipynb)

### 4. Visualización de clústers


[`Anterior`](../L04-backpropagation/README.md) | [`Siguiente`](../L06-fuzzy-logic/README.md)