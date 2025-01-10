# Sistema de Reconocimiento Facial para Control de Accesos con Raspberry Pi

## Resumen del proyecto

Este proyecto tiene como objetivo crear un sistema que use reconocimiento facial para controlar accesos. La idea es que con una Raspberry Pi puedas detectar rostros en tiempo real, compararlos con una base de datos de usuarios autorizados, y activar algo como una cerradura, un motor o cualquier mecanismo para dar acceso. Vas a trabajar desde la configuración del hardware hasta la implementación del software y las pruebas finales.  

El resultado debe ser algo funcional y básico, pero listo para que después se pueda mejorar o ampliar.

## Objetivos de aprendizaje 
1. Aprender cómo funciona el reconocimiento facial usando herramientas como OpenCV y face_recognition.
2. Entender cómo conectar software y hardware para que trabajen juntos, como usar un relay o un motor desde la Raspberry Pi.
3. Optimizar el sistema para que corra bien en un entorno con recursos limitados, como lo es la Raspberry Pi.
4. Desarrollar un proyecto de principio a fin, con pruebas, ajustes y documentación.

## Consideraciones generales

- Presupuesto: Vamos a usar componentes económicos, pero que funcionen bien para lo que necesitamos.
- Modularidad: Todo lo que hagas debe ser fácil de modificar o mejorar después.
- Seguridad: El sistema tiene que ser confiable y permitir acceso solo a usuarios autorizados.
- Eficiencia: Hay que asegurarse de que la Raspberry Pi no se sature y todo corra de manera fluida.

## Críterios mínimos de aceptación

- El sistema debe poder detectar y reconocer rostros en tiempo real con buena precisión.
- Tiene que haber una forma de gestionar los usuarios autorizados (agregar, editar, eliminar).
- Cuando detecte un rostro autorizado, debe activar el mecanismo de acceso.
- Registrar todo: accesos permitidos y rechazados, con fecha y hora.
- Crear una interfaz básica para gestionar usuarios y revisar registros.

## Consideraciones técnicas

#### Hardware:
- Raspberry Pi 4 con mínimo 2GB de RAM.
- Cámara (puede ser el módulo oficial de Raspberry Pi o una USB).
- Relay de 5V o cualquier controlador que necesites para manejar el mecanismo de acceso.

__Recomendación:__ Comprar los componentes en [AGElectrónica](https://www.agelectronica.com/?sc=general), [UNIT Electrónics](https://uelectronics.com/) ó  [330ohms](https://www.330ohms.com/)

### Software:
- Raspberry Pi OS.
- OpenCV y face_recognition.

#### Optimización:
- Baja la resolución de las imágenes para procesarlas más rápido.
- Asegúrate de que el código esté lo más limpio y eficiente posible.


## Alternativa Económica para el Control de Accesos
Si ves que la cerradura eléctrica no es viable por el presupuesto, podemos usar un servo motor.  
Es más barato y puede hacer lo mismo si se usa con un pestillo.

#### Ventajas del Servo Motor:

- Es económico.
- Se conecta fácil a la Raspberry Pi.
- Consume menos energía.
