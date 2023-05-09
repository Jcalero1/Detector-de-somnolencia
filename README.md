#Alerta de somnolencia y bostezo
Este proyecto consiste en una aplicación que utiliza una cámara web para detectar si el usuario está somnoliento o bostezando mientras trabaja en su ordenador. Si detecta alguno de estos síntomas, la aplicación alerta al usuario para que tome un descanso y se despeje antes de continuar trabajando.

#Requisitos previos
Para ejecutar la aplicación, necesitas tener instalados los siguientes paquetes en tu entorno de Python:

- scipy

- imutils

- numpy

- argparse

- dlib

- opencv-python

Puedes instalar estos paquetes ejecutando el siguiente comando:

```sh
pip install scipy imutils numpy argparse dlib opencv-python
```

# Uso
Para iniciar la detección de somnolencia y bostezo, ejecuta el archivo detect_drowsiness.py con el siguiente comando:

``` sh
python detect_drowsiness.py
```

Por defecto, la aplicación utiliza la cámara web de tu ordenador. 
Si quieres utilizar otra cámara, puedes indicar el índice de la cámara como argumento al ejecutar el archivo. 
Por ejemplo, si quieres utilizar la segunda cámara de tu ordenador, ejecuta el siguiente comando:

``` sh
python detect_drowsiness.py --webcam 1
```

# Créditos
Este proyecto utiliza la biblioteca dlib para detectar los rasgos faciales, así como la biblioteca OpenCV para procesar las imágenes capturadas por la cámara web.

El código para reproducir una alerta de voz fue obtenido de: 
https://www.geeksforgeeks.org/convert-text-speech-python/

# Contribución
Si deseas contribuir a este proyecto, por favor crea un fork y realiza un pull request para incluir tus cambios.
