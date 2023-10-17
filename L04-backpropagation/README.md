[`Computación Flexible`](../README.md) > `Unidad 4. Backpropagation`

## Unidad 4. Backpropagation

### Objetivo

En esta clase el alumno conocerá:

* La estructura básica del MLP.
* Las funciones de activación que pueden ser utilizadas en una neurona.
* El algoritmo Feedforward
* EL algoritmo de Backpropagtion (online y batch)
  
### Introducción

Después de Madaline I, en 1971 se presentó la primera mejora significativa de las RNs feedforward. Werbos desarrollo el algoritmo de entrenamiento backpropagation, el cual fue publicada por primera vez en su tesis doctoral en 1974. La idea de la retropagación del error a través de sistemas no lineales existió siglos antes de que Werbos lo aplicara a las RNAs. Lamentablemente, el trabajo de Werbos paso desapercibido en la comunidad científica. Hasta que en 1982, Parker redescubrió la técnica y en 1985, publicó un reporte para el MIT.

Las RNs están compuestas de varias capas, y han tenido un papel principal en los algoritmos de aprendizaje profundo y sus arquitecturas. Ejemplos comunes son los productos desarrollados por Facebook, Microsoft, Amazon, Uber y Google que han invertido demasiado en investigaciones sobre NNs y Deep Learning.

### 1. Funciones de error

Función de costo: Error Cuadrático Medio (MSE, Mean Square Error).

$MSE_{NN} = \frac{1}{2} \Sigma_{i=0}^m (target_i - a_i^{(out))})^2$

**Redes Neuronales Múlticapa (M-L NNs).**
Estas redes tienen un tipo especial de conexión entre capas llamado MLP.

### Implementación de Feedforwar y Backpropagation paso a paso

* [`Ejemplo Online`](./code/brackpropagation_online.ipynb)

### Implementación backprogation batch

* [`Ejemplo Batch`](./code/MLP_batch_own.ipynb)

### Implementación RN en keras

* [`Ejemplo Keras`](./code/MLP_Keras.ipynb)

[`Anterior`](../L03-perceptron/README.md) | [`Siguiente`](../L05-som/README.md)