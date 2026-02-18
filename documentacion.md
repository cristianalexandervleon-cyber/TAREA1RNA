# ARN TAREA1 - Red Neuronal

## ¿Qué hice?
Clone el repositorio de MichalDanielDobrzanski (DeepLearningPython) y entrene 
una red neuronal usando el archivo network.py con el dataset MNIST.

## ¿Qué hace el código?

### network.py
Es la red neuronal principal. Tiene estas partes:

- **__init__**: Crea la red y define cuántas capas y neuronas tiene
- **feedforward**: Recibe una imagen y predice qué número es
- **SGD**: Entrena la red repasando los datos varias veces (épocas)
- **backprop**: Corrige los errores que comete la red durante el entrenamiento
- **evaluate**: Cuenta cuántas imágenes clasificó bien

### mnist_loader.py
Carga las imágenes de números escritos a mano para entrenar la red.

### mnist.pkl.gz
Base de datos con 70,000 imágenes de números del 0 al 9.

## Resultados
Entrené la red con 30 épocas y logré clasificar correctamente 
alrededor de 9500 de 10000 imágenes (95% de precisión).
La captura de los resultados está en TAREA1.jpg.

## Repositorio original
https://github.com/MichalDanielDobrzanski/DeepLearningPython

## Fecha
Febrero 2026
