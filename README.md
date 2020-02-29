# Machine Learning

*****Machine Learning***** es una disciplina científica del ámbito de la Inteligencia Artificial que crea sistemas que aprenden automáticamente. Aprender en este contexto quiere decir identificar patrones complejos en millones de datos. La máquina que realmente aprende es un algoritmo que revisa los datos y es capaz de predecir comportamientos futuros. Automáticamente, también en este contexto, implica que estos sistemas se mejoran de forma autónoma con el tiempo, sin intervención humana. Veamos cómo funciona.

### Tabla de prueba

Prueba|Número
---|---
IA|1
Automatización|2
IA Orientativa|3
Text Speech|4
Voice Recognition|5

### Índice
* Historia
* ¿Aplicaciones?
* ¿Cómo funciona?

#### Código python
~~~
import random
import math
import pandas as pd
import matplotlib.pyplot as plt

DATASET = "./dataSet/RL_Calorias_Tiempo.csv"
ALPHA = 0.0005
MAX_ITERATIONS = 100
CONVERGENCE_TOLERANCE = 0.01


def print_results(a, b, error):
    print '\n----------------------------'
    print '\nFINAL RESULTS'
    print '\t Calorias(Tiempo) = %f * Tiempo + %f' % (a, b)
    print '\t\tTotal Error = %f' % error
~~~
#### Cita

>*"El machine learning es la vía de transformación principal que nos está llevando a repensar todo lo que hacemos"*

##### Imagen

![Texto alternativo](https://www.ionos.es/digitalguide/fileadmin/DigitalGuide/Teaser/machine-learning-t.jpg)
