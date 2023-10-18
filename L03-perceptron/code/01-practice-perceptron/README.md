## Práctica 1.1. Aprendizaje del Percetrón dataset Iris

### Instrucciones

1. Utilizar los archivos [`Perceptron.py`](Perceptron.py) y [`Perceptron.ipynb`](Perceptron.ipynb) como base para la construcción de un perceptrón funcional. 
2. Consideraciones:
    Los datos de entrenamiento se adecuen a el número de características de cada ejemplo de entrenamiento y la dimensión de la etiqueta de salida.
    Agregar los siguientes atributos de comportamiento a la clase `Perceptron`:

    - `eta`: `float`, taza de aprendizaje.
    - `n_iter` : `int`, indica el número de iteraciones de entrenamiento, en el caso que sea 0 o menor entonces el entrenamiento termina hasta que sean aprendidos todos los ejemplos de la muestra de entrenamiento.
    - `random_state` : `int` semilla generadora de los números aleatorios.
    - `init_weigt`: `boolean`, indica la forma de iniciarlizar los pesos. `true` se inicializan de forma aleatoria y `false` se inicializan todos los pesos en cero. 
    - `weights`: lista de `int`, indica los pesos iniciales, y solo se utiliza si `init_weigt` es `true`.
    - `shuffle`: `boolean`, indica el orden los ejemplos de entreanaiento, `true` el orden es aleatorio para cada epoca y `false` el orden es el mismo
    - `f_activate`: `string` indica la función de activación: `step` o `sign`.
3. Probar los resultados con el conjunto de datos `Iris`.
4. Entregar el proyecto en Classroom de Google y Clasroom de GitHub (en la asingación de classroom de Google encontraras la liga). 