# Detector de Bagre

![Imagen de un pez](bagre.jpg)

## Descripción

Este es un proyecto de detección de bagres utilizando aprendizaje automático y visión por computadora. 

## Requisitos

Para poder correr este proyecto, necesitarás tener instalado lo siguiente:

- Python 3
- pip

## Pasos para correr el proyecto

1. Descarga el repositorio y accede al directorio principal.

2. En la terminal, ejecuta el siguiente comando para descargar AWS CLI:

`curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip`
  
3. agregar la access key y secret key

`aws configure`


4. Crea un entorno virtual con el siguiente comando:

`python3 -m venv venv`


5. Activa el entorno virtual:

`source /venv/bin/activate`

6. Instala las dependencias necesarias:

`pip install -r requirements.txt`


7. Ejecuta el siguiente comando para iniciar el programa:

`python app.py`

