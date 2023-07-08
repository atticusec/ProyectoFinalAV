# Proyecto Final Tratamiento de datos

Inicialmente instalaron unas librerias y módulos necesarios para realizar la tarea de aprednizaje utilizando Keras, que es bastante popular en python.

import numpy as np

Esta línea importa la biblioteca NumPy y la asigna a la abreviatura "np". NumPy es una biblioteca fundamental en Python para realizar cálculos numéricos, especialmente para trabajar con matrices y arreglos multidimensionales.

import keras
Aquí se importa el paquete principal de Keras. Keras es una biblioteca de alto nivel para construir y entrenar redes neuronales.

from keras import backend as k
Esta línea importa el módulo "backend" de Keras y lo asigna a la abreviatura "k". El módulo backend proporciona una interfaz para acceder a las funciones y utilidades específicas de la biblioteca de backend subyacente, como TensorFlow.

from keras.models import Sequential
Aquí se importa la clase Sequential de Keras. La clase Sequential se utiliza para crear modelos secuenciales en Keras, que es una forma sencilla y lineal de construir modelos de redes neuronales.

from keras.layers import Activation
from keras.layers.core import Dense, Flatten
from keras.layers.normalization import *
from keras.layers.convolutional import *
Estas importaciones traen varias capas disponibles en Keras que se utilizan comúnmente en la construcción de modelos de redes neuronales. Algunas de las capas incluidas son: Activation (activación), Dense (totalmente conectada), Flatten (aplanar), BatchNormalization (normalización por lotes) y Convolutional (convolucional).

from keras.optimizers import Adam
from keras.metrics import categorical_crossentropy
Aquí se importan el optimizador Adam y la métrica categorical_crossentropy desde los respectivos módulos en Keras. El optimizador Adam es un algoritmo de optimización popular utilizado en el entrenamiento de redes neuronales, mientras que categorical_crossentropy es una función de pérdida comúnmente utilizada en problemas de clasificación multiclase.

from sklearn.metrics import confusion_matrix
import itertools
Estas importaciones provienen de la biblioteca scikit-learn (sklearn) y se utilizan para calcular y visualizar matrices de confusión, que son útiles para evaluar el rendimiento de modelos de clasificación.

get_ipython().run_line_magic('matplotlib', 'inline')
Esta línea es específica de los entornos de Jupyter Notebook y se utiliza para mostrar gráficos y visualizaciones de Matplotlib directamente en el cuaderno. En otros entornos, como la terminal interactiva de Python, esta línea no es necesaria.
