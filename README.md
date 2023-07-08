# Proyecto Final Tratamiento de datos

Inicialmente instalaron unas librerias y módulos necesarios para realizar la tarea de aprendizaje utilizando Keras, que es bastante popular en python.

Dentro de las primeras lineas era necesario importar la biblioteca NumPy y la asignar a la abreviatura "np". NumPy es una biblioteca fundamental en Python para realizar cálculos numéricos, especialmente para trabajar con matrices y arreglos multidimensionales. Luego se importa el paquete principal de Keras. Keras es una biblioteca de alto nivel para construir y entrenar redes neuronales, posteriormente se importa el módulo "backend" de Keras y lo asigna a la abreviatura "k". 

El módulo backend proporciona una interfaz para acceder a las funciones y utilidades específicas de la biblioteca de backend subyacente, como TensorFlow.
La clase Sequential se utiliza para crear modelos secuenciales en Keras, que es una forma sencilla y lineal de construir modelos de redes neuronales. Estas importaciones traen varias capas disponibles en Keras que se utilizan comúnmente en la construcción de modelos de redes neuronales. Algunas de las capas incluidas son: Activation (activación), Dense (totalmente conectada), Flatten (aplanar), BatchNormalization (normalización por lotes) y Convolutional (convolucional). Aquí se importan el optimizador Adam y la métrica categorical_crossentropy desde los respectivos módulos en Keras. 

El optimizador Adam es un algoritmo de optimización popular utilizado en el entrenamiento de redes neuronales, mientras que categorical_crossentropy es una función de pérdida comúnmente utilizada en problemas de clasificación multiclase.

____________________________________________________

Con train_path, valid_path y test_path son rutas de directorio que indican la ubicación de los conjuntos de datos utilizados para entrenamiento, validación y pruebas, respectivamente, estas variables representan las rutas de los directorios donde se encuentran los datos de entrenamiento, validación (si está disponible) y prueba para un modelo de aprendizaje automático. Los datos en estos directorios se utilizarán para entrenar, ajustar y evaluar el modelo.

El generador de datos de imágenes train_batches se puede utilizar en un bucle para iterar a través de los lotes de datos de entrenamiento. Cada iteración proporcionará un lote de imágenes y sus correspondientes etiquetas de clase. Esto permite alimentar los datos de entrenamiento al modelo en lotes durante el entrenamiento.

La función primero realiza algunas comprobaciones y transformaciones en los datos de las imágenes para asegurarse de que se puedan mostrar correctamente. Luego, crea una figura con el tamaño especificado por figsize y organiza las imágenes en una cuadrícula con el número de filas y columnas determinadas por rows y cols. Cada imagen se agrega a la figura en su posición correspondiente en la cuadrícula.



La función plot_confusion_matrix que proporcionaste es una función personalizada para trazar una matriz de confusión. Aquí está la explicación de cómo funciona:

cm: La matriz de confusión que se desea trazar. Debe ser una matriz NumPy que representa la matriz de confusión.

classes: Una lista de etiquetas de clase que corresponden a las clases en la matriz de confusión.

normalize: Un parámetro booleano que indica si se debe aplicar normalización a la matriz de confusión. Si se establece en True, la matriz de confusión se normalizará dividiendo cada valor por el total de la fila correspondiente. Esto puede ser útil para visualizar la distribución proporcional de las predicciones correctas e incorrectas. Por defecto, se establece en False.

title: El título de la figura que muestra la matriz de confusión.

cmap: El mapa de colores que se utilizará para visualizar la matriz de confusión. Por defecto, se utiliza plt.cm.Blues.

La función plot_confusion_matrix es una función personalizada para imprimir y trazar una matriz de confusión. 

![image](https://github.com/atticusec/ProyectoFinalAV/assets/138344385/7fb5cb33-e04c-4ef8-b245-d7cdf95e1c3c)

