## Clasificación de números escritos a mano (MNIST)

## Resumen del proyecto

Este proyecto tiene como objetivo entrenar un modelo de inteligencia artificial para reconocer y clasificar dígitos escritos a mano utilizando el conjunto de datos MNIST (Modified National Institute of Standards and Technology).  

El conjunto de datos MNIST es una colección de 60,000 imágenes de entrenamiento y 10,000 imágenes de prueba de dígitos escritos a mano (del 0 al 9). Cada imagen es en escala de grises y tiene un tamaño de 28x28 píxeles.

## Objetivo

Construir un modelo de aprendizaje profundo (Deep Learning) que pueda identificar automáticamente los números escritos a mano con alta precisión.

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
- Entender sintaxis básica de Python: variables, tipos de datos, operadores, estructuras de control (if, for, while).

__Recursos:__
- [Libro de Python](https://ellibrodepython.com/)
- [Clase Python Google](https://developers.google.com/edu/python?hl=es-419)
- [Tutorial Python W3S](https://www.w3schools.com/python/)

__Ejercicios simples:__
- Escribir un script que pida al usuario su nombre y edad, y luego imprima un mensaje personalizado con la edad que tendrá en 10 años. 
- Experimentar con operaciones matemáticas y estructuras de control (if, for, while)

### 2. Funciones, Listas y Diccionarios en Python

__Objetivo:__ Entender estructuras de datos y funciones en Python. Implementar una agenda de contactos utilizando listas, diccionarios y funciones en Python.


__Actividades:__
- Crear una agenda de contactos con una lista de diccionarios.
- Implementar funciones para agregar, buscar y mostrar contactos.

__Ejecicio:__

- Crear una función  ```agregar_contacto() ``` que reciba un nombre, teléfono y correo, y lo almacene en un diccionario dentro de una lista.
- Crear una función  ```mostrar_contactos() ``` que imprima todos los contactos almacenados.
- Crear una función  ```buscar_contacto() ``` que permita encontrar un contacto por nombre.
- Usar un bucle para que el usuario pueda agregar, buscar y mostrar contactos mediante un menú interactivo.

### 3. Intruducción a NumPy y Matplotlib

__Objetivo:__ Conocer librerías esenciales para IA.

__Ejercicio:__
- Generar una lista de 100 números aleatorios y graficarlos usando Matplotlib.
- Comparar la media y la mediana usando NumPy.

### 4. Pandas y Manejo de Datos

__Objetivo:__  Manipular datos con pandas.

__Ejecicio:__
- Descargar un archivo CSV de datos abiertos (ej. sobre clima o precios).
- Cargarlo con pandas, mostrar las primeras filas y hacer un análisis básico (.describe()).
- Graficar una columna usando Matplotlib.

### 5.  Introducción a Machine Learning con Scikit-learn

__Objetivo:__ Comprender el concepto de aprendizaje automático.
__Ejecicio:__ 
- Cargar el dataset de iris (```from sklearn.datasets import load_iris```).
- Dividirlo en conjunto de entrenamiento y prueba.
- Implementar una [Regresión Logística](https://cienciadedatos.net/documentos/py17-regresion-logistica-python) para predecir la especie de flor usando [Scikit-learn](https://scikit-learn.org/1.5/modules/generated/sklearn.linear_model.LogisticRegression.html#). 