# Números escritos a mano

Este código fuente sirve como apoyo para el video de exportación de modelos de Tensorflow a Tensorflow.js, del canal de YouTube [Ringa Tech](https://youtube.com/RingaTech)

### Inicia un servidor en la carpeta

Este proyecto utiliza un modelo de Tensorflow.js, el cual para cargarse requiere que el acceso sea por medio de http/https.
Para eso puedes usar cualquier servidor, pero aquí hay una forma de hacerlo:

- Descarga Python en tu computadora
- Abre una línea de comandos o terminal
- Navega hasta la carpeta donde descargaste el repositorio
- Ejecuta el comando `python -m http.server 8000`
- Abre un explorador y ve a http://localhost:8000

### Uso

Dibuja con el mouse o tu dedo en el canvas cuadrado un número del 0 al 9, y da clic en "Predecir". Para limpiar el canvas da clic en "Limpiar".
