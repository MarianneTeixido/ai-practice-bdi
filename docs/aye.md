## Clasificación de números escritos a mano (MNIST)

## Resumen del proyecto

Este proyecto tiene como objetivo entrenar un modelo de inteligencia artificial para reconocer y clasificar dígitos escritos a mano utilizando el conjunto de datos MNIST (Modified National Institute of Standards and Technology).  

El conjunto de datos MNIST es una colección de 60,000 imágenes de entrenamiento y 10,000 imágenes de prueba de dígitos escritos a mano (del 0 al 9). Cada imagen es en escala de grises y tiene un tamaño de 28x28 píxeles.

## Objetivo

Construir un modelo de aprendizaje profundo (Deep Learning) que pueda identificar automáticamente los números escritos a mano con alta precisión.

## Forma de trabajo

Antes de comenzar ten en consideración la importancia de documentar tu trabajo paso a paso almacenando tu código en un repositorio de Github. Para ello:
- Instala git
- Crea una cuenta de Github
- Configura tu clave SSH
- Documenta en un archivo tipo markdown o dentro de un Jupyter NoteBook los links  que consideres relevantes asi como la investigación realizada.
- Al terminar cada módulo sube tus cambios al repositorio remoto.  

## Procedimiento

### 1. Instalación y Fundamentos de Python 

__Objetivo:__ Configurar el entorno de desarrollo y aprender lo esencial de Python.

__Actividades:__  
- Terminar la instalación de Debian en WSL.
- Instalar Python:
    ```bash
    sudo apt install python3 python3-pip
    ```
- Instalar VSCode o usar un editor como nano o vim en Debian.
- Crea un entorno virtual usando 
- Activar el entorno virtual
- Instalar Jupyter Notebook: 
    ```bash
    pip install jupyter
     ```
- Abrir Jupyter Notebook y crea un nuevo cuaderno.
- Escribe y ejecuta un programa simple en Python que imprima "Hola, mundo".
- Entender sintaxis básica de Python: variables, tipos de datos, operadores, estructuras de control (if, for, while).
- Investigar cómo funcionan las variables, tipos de datos y estructuras básicas (listas, diccionarios).

__Recursos:__
- [Libro de Python](https://ellibrodepython.com/)
- [Clase Python Google](https://developers.google.com/edu/python?hl=es-419)
- [Tutorial Python W3S](https://www.w3schools.com/python/)

__Ejercicios:__  
- Escribe un programa que sume dos números ingresados por el usuario.  
- Escribir un script que pida al usuario su nombre y edad, y luego imprima un mensaje personalizado con la edad que tendrá en 10 años.


### 2. Introducción a Librerías y Manipulación de Datos

__Objetivo:__ Aprender a usar librerías básicas de Python y manipular datos.

__Ejecicio:__

- Instala las librerías `numpy` y `matplotlib` usando `pip install numpy matplotlib`.
- Investiga cómo funcionan los arreglos en numpy.
- Crea un arreglo de números del 1 al 10 y realiza operaciones básicas (suma, resta, multiplicación).
- Usa matplotlib para graficar una línea simple con los valores del arreglo.
- Investiga cómo cargar datos desde un archivo CSV usando pandas (instálalo con `pip install pandas`).
- Carga un archivo CSV de alguna base de datos abiertos (clima, precios, etc), muestra las primeras 5 filas y haz un análisis básico (`.describe()`).

### 3. Introducción al Procesamiento de Imágenes

__Objetivo:__ Familiarizarse con el procesamiento de imágenes usando Python.

__Ejercicio:__
- Instala la librería `opencv-python` con `pip install opencv-python`.
- Investiga cómo cargar y mostrar una imagen usando OpenCV.
- Carga una imagen y conviértela a escala de grises.
- Aplica un filtro de suavizado (blur) a la imagen.
- Guarda la imagen procesada en un archivo nuevo.
- Investiga cómo redimensionar una imagen y aplícalo a la imagen cargada.

### 4. Introducción a Redes Neuronales y TensorFlow

__Objetivo:__  Entender los conceptos básicos de redes neuronales y cómo usar TensorFlow.

__Ejecicio:__
- Instala TensorFlow con pip.
- Investiga qué es una red neuronal y cómo funciona.
- Crea un modelo simple de red neuronal usando TensorFlow para predecir si un número es par o impar.
- Entrena el modelo con un conjunto de datos pequeño (por ejemplo, números del 1 al 100).
- Evalúa el modelo y verifica su precisión.
- Investiga cómo guardar y cargar un modelo entrenado.

### 5. Conjunto de Datos MNIST y Preprocesamiento

__Objetivo:__ Aprender a trabajar con el conjunto de datos MNIST.

__Ejecicio:__ 
- Descarga el conjunto de datos MNIST (puedes usar `tensorflow.keras.datasets.mnist`).
- Explora el conjunto de datos: visualiza algunas imágenes y sus etiquetas.
- Normaliza los datos (escala los valores de píxeles entre 0 y 1).
- Divide el conjunto de datos en entrenamiento y prueba.
- Investiga cómo se preparan los datos para entrenar una red neuronal.
- Prepara los datos para que estén listos para el entrenamiento.


### 6. Creación y Entrenamiento de un Modelo de Reconocimiento de Dígitos

__Objetivo:__ Crear y entrenar un modelo de red neuronal para reconocer dígitos escritos a mano.

__Ejecicio:__ 
- Define un modelo de red neuronal usando TensorFlow/Keras.
- Añade capas densas (Dense) y una capa de salida con activación softmax.
- Compila el modelo con un optimizador (por ejemplo, Adam) y una función de pérdida (por ejemplo, `sparse_categorical_crossentropy`).
- Entrena el modelo con los datos de entrenamiento de MNIST.
- Evalúa el modelo con los datos de prueba y verifica su precisión.
- Guarda el modelo entrenado para usarlo más tarde.



### 7. Prueba y Mejora del Modelo

__Objetivo:__ Probar el modelo y explorar formas de mejorarlo.

__Ejecicio:__ 
- Carga el modelo entrenado del día anterior.
- Prueba el modelo con algunas imágenes de dígitos escritos a mano (puedes dibujarlas o descargarlas).
- Investiga cómo mejorar el modelo: añade más capas, cambia la función de activación o ajusta los hiperparámetros.
- Entrena el modelo nuevamente con las mejoras y evalúa su rendimiento.
- Visualiza algunas predicciones incorrectas y analiza por qué el modelo falló.
- Escribe un breve informe con los resultados y las conclusiones del proyecto.


