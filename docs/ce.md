# Ejercicio 

#### Objetivo
Crear un MVP relacionado con asistentes virtuales, análisis de voz. Aprovechar herramientas de análisis de datos como Pytohon y sin dependencia de una GPU dedicada.

### Día 1.  Introducción y Setup
__Objetivo__ Configurar el entorno y familiarizarse con los conceptos clave.

__Ejercicio:__ Crear un script básico para convertir audio a texto usando speechrecognition.  
__Explicación__ Investigar qué es un MVP, intruducción a STT y TTS.  
__Opcional:__ Instalar WSL para trabajar con Debian 12.


### Día 2.  Speech-to-Text
__Objetivo:__ Implementar STT básico y almacenar resultados para análisis.

__Ejercicio:__  
- Crear un script que grabe audio desde el micrófono y lo convierta a texto.  
- Almacenar el texto resultante en un archivo CSV para análisis posterior.  
- Introducir visualizaciones simples con matplotlib para análisis (ejemplo: palabras más comunes en el texto transcrito).

### Día 3. Análisis de Datos de Texto
__Objetivo:__ Aprender análisis de datos enfocado en texto.

__Ejercicio:__     
- Usar pandas para procesar el archivo CSV generado.  

Analizar datos como:  
- Longitud promedio de palabras/frases.  
- Frecuencia de palabras clave.  
- Crear gráficos sencillos que muestren tendencias o insights.  

### Día 4. Text-to-Speech

__Objetivo:__  Text-to-Speech  

__Ejercicio:__  
- Utilizar pyttsx3 o gTTS para convertir texto a voz.  
- Configurar parámetros como velocidad y tono.  
- Crear una función que tome el texto procesado y lo convierta en audio.

### Día 5. Integración STT y TTS
__Objetivo:__ Crear un flujo básico que combine ambas tecnologías.

__Ejercicio:__  
- Crear un flujo donde el usuario hable, el sistema transcriba el audio a texto, y luego reproduzca el texto como voz.  
- Agregar logs para guardar las interacciones (audio, texto, y audio generado).

### Día 6: Asistente Virtual Básico
__Objetivo:__ Añadir capacidades simples de chatbot.  

__Ejercicio:__  

#### Opción 1. Google
- Configurar Google Cloud Platform (GCP) y habilitar las APIs de Speech-to-Text y Text-to-Speech.
- Implementar Google Speech-to-Text para transcribir audio en tiempo real.
- Usar Google Text-to-Speech para generar respuestas habladas a partir del texto.
- Integrar ambas herramientas en un flujo básico que permita interacción por voz.

#### Opción 2. OpenAI
- Usar la API de OpenAI o una librería como ChatterBot para generar respuestas a preguntas básicas.  
- Integrar el modelo de chatbot con el flujo STT-TTS.  
- Permitir preguntas de prueba y respuestas habladas.  


### Día 7: Interfaz de Usuario
__Objetivo:__  Crear una interfaz web básica para el MVP.

__Ejercicio:__   
- Usar Flask para servir una página web simple. (Opcional, pueden usar la herramienta que mas les acomode) 
- Agregar botones para grabar audio, mostrar transcripciones, y reproducir audio generado.   
- Crear un frontend básico con HTML/CSS.  

### Día 8: Iteración y Mejora
__Objetivo:__  Pulir el MVP y añadir más análisis.

__Ejercicio:__   
- Mejorar la transcripción y análisis con bibliotecas como spaCy o NLTK.  
- Agregar métricas adicionales en la interfaz (número de palabras, palabras clave, etc.).  
- Opcional: Probar con audio pregrabado.  

### Día 9: Demo y Documentación
__Objetivo:__ Preparar y mostrar el MVP.

__Ejercicio:__  
- Crear una breve presentación o demo del MVP.  
- Documentar el flujo, las herramientas usadas y los pasos para replicar el proyecto.  
- Discusión sobre aprendizajes y mejoras posibles.

### Entregable
Un MVP funcional que permita:

- Escuchar audio desde el micrófono.
- Convertirlo a texto.
- Analizar el texto y mostrar insights.
- Generar una respuesta hablada usando TTS.
- Mostrar el flujo en una interfaz web simple.