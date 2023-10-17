## Detector de Humo

## _Contexto_
Un detector de humo es un dispositivo capaz de detectar cuerpos de fuego, generalmente como indicador de incendio. Los detectores de humo generalmente se alojan en recintos de plástico, generalmente con forma de disco de aproximadamente 150 milímetros (6 pulgadas) de diámetro y 25 milímetros (1 pulgada) de grosor, pero la forma y el tamaño varían. Son demasiado útiles, pues su instalación puede garantizar una protección en caso de un accidente que involucre fuego.

## _Sobre el dataset_

La recopilación de datos de entrenamiento se realizó con la ayuda de un dispositivos IOT. El objetivo es desarrollar un dispositivo detector de humo apoyado con una IA (un modelo de aprendizaje automático).

Se deben muestrear muchos entornos y fuentes de fuego diferentes para garantizar un buen conjunto de datos para el entrenamiento. Una breve lista de diferentes características que se capturaron:

-    UTC
-    Temperatura[C]
-    Humedad[%]
-    TVOC[ppb]
-    eCO2[ppm]
-    Raw H2
-    Raw Ethanol
-    Pressure [hPa]
-    PM1.0
-    PM2.5
-    NC0.5
-    NC1.5
-    CNT

El dataset está conformado por más de 62629 muestras con 13 distintas características con las que se puede determinar si un detector de humo debe activarse o no, lo cual lo hace una clasificación binaria.

Puede ser descargado desde: https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset creándose una cuenta en Kaggle (también fue proporcionado el dataset descargado).
