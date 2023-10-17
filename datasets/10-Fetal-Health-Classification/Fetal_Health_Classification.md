# Fetal Health Classification

La reducción de la mortalidad infantil se refleja en varios de los Objetivos de Desarrollo Sostenible de las Naciones Unidas y es un indicador clave del progreso humano.
La ONU espera que para 2030, los países pongan fin a las muertes prevenibles de recién nacidos y niños menores de 5 años, con el objetivo de reducir la mortalidad de menores de 5 años al menos a 25 por cada 1000 nacidos vivos.

Paralelamente a la noción de mortalidad infantil está, por supuesto, la mortalidad materna, que representa 295 000 muertes durante y después del embarazo y el parto (a partir de 2017). La gran mayoría de estas muertes (94%) ocurrieron en entornos de bajos recursos y la mayoría podría haberse evitado.

La cardiotocografía (CTG) se usa durante el embarazo para controlar la frecuencia cardíaca fetal y las contracciones uterinas. Es monitorear el bienestar fetal y permite la detección temprana de sufrimiento fetal.
La interpretación de CTG ayuda a determinar si el embarazo es de alto o bajo riesgo. Una CTG anormal puede indicar la necesidad de más investigaciones y una posible intervención.

A la luz de lo mencionado anteriormente, los cardiotocogramas (CTGs) son una opción simple y económicamente accesible para evaluar la salud fetal, lo que permite a los profesionales de la salud tomar medidas para prevenir la mortalidad infantil y materna. El equipo en sí funciona enviando pulsos de ultrasonido y leyendo su respuesta, arrojando luz sobre la frecuencia cardíaca fetal (FCF), los movimientos fetales, las contracciones uterinas y más.

Se pretende desarrollar un modelo para clasificar el resultado de la prueba de cardiotocograma para garantizar el bienestar del feto.

## Datos

Este conjunto de datos contiene 2126 registros de características extraídas de exámenes de cardiotocograma, que luego fueron clasificados por tres obstetras expertos en 3 clases:

* Normal - 1
* Sospechar - 2
* Patológico - 3

## Características

* **baseline value** : Latidos por minuto
* **accelerations** : Número de aceleraciones por segundo
* **fetal_movement** : Número de movimientos fetales por segundo
* **uterine_contractions** : Número de contracciones uterinas por segundo
* **light_decelerations** : Número de desaceleraciones de luz por segundo
* **severe_decelerations** : Número de desaceleraciones severas por segundo
* **prolongued_decelerations** : Número de desaceleraciones prolongadas por segundo
* **abnormal_short_term_variability** : Porcentaje de tiempo con variabilidad anormal a corto plazo
* **mean_value_of_short_term_variability** : Valor medio de la variabilidad a corto plazo
* **percentage_of_time_with_abnormal_long_term_variability** : Porcentaje de tiempo con variabilidad anormal a largo plazo
* **mean_value_of_long_term_variability** : Valor medio de la variabilidad a largo plazo
* **histogram_width** : Ancho del histograma de frecuencia cardíaca fetal
* **histogram_min** : Mínimo (baja frecuencia) del histograma de frecuencia cardíaca fetal
* **histogram_max** : Máximo (alta frecuencia) del histograma de frecuencia cardíaca fetal
* **histogram_number_of_peaks** : Número de picos de histograma
* **histogram_number_of_zeroes** : Número de ceros del histograma
* **histogram_mode** : Modo histograma
* **histogram_mean** : Media del histograma
* **histogram_median** : Mediana del histograma
* **histogram_variance** : Variación del histograma
* **histogram_tendency** : Tendencia del histograma

---

## Referencia

Ayres de Campos et al. (2000) SisPorto 2.0 A Program for Automated Analysis of Cardiotocograms. J Matern Fetal Med 5:311-318

## Licencia

La licencia no se especificó en la fuente, pero el acceso a los datos es público y se solicitó una cita.