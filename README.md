# Proyecto Final Tratamiento de datos

Inicialmente instalaron unas librerias y módulos necesarios para realizar la tarea de aprednizaje utilizando Keras, que es bastante popular en python.

Dentro de las primeras lineas era necesario importar la biblioteca NumPy y la asignar a la abreviatura "np". NumPy es una biblioteca fundamental en Python para realizar cálculos numéricos, especialmente para trabajar con matrices y arreglos multidimensionales. Luego se importa el paquete principal de Keras. Keras es una biblioteca de alto nivel para construir y entrenar redes neuronales, posteriormente se importa el módulo "backend" de Keras y lo asigna a la abreviatura "k". El módulo backend proporciona una interfaz para acceder a las funciones y utilidades específicas de la biblioteca de backend subyacente, como TensorFlow.
La clase Sequential se utiliza para crear modelos secuenciales en Keras, que es una forma sencilla y lineal de construir modelos de redes neuronales. Estas importaciones traen varias capas disponibles en Keras que se utilizan comúnmente en la construcción de modelos de redes neuronales. Algunas de las capas incluidas son: Activation (activación), Dense (totalmente conectada), Flatten (aplanar), BatchNormalization (normalización por lotes) y Convolutional (convolucional). Aquí se importan el optimizador Adam y la métrica categorical_crossentropy desde los respectivos módulos en Keras. El optimizador Adam es un algoritmo de optimización popular utilizado en el entrenamiento de redes neuronales, mientras que categorical_crossentropy es una función de pérdida comúnmente utilizada en problemas de clasificación multiclase.

____________________________________________________


En el código proporcionado, train_path, valid_path y test_path son rutas de directorio que indican la ubicación de los conjuntos de datos utilizados para entrenamiento, validación y pruebas, respectivamente, estas variables representan las rutas de los directorios donde se encuentran los datos de entrenamiento, validación (si está disponible) y prueba para un modelo de aprendizaje automático. Los datos en estos directorios se utilizarán para entrenar, ajustar y evaluar el modelo.
