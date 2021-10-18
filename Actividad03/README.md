# **ANÁLISIS, LIMPIEZA, ENTRENAMIENTO Y DESPLIEGUE**

## **OBJETIVO**

Desarrollar un ejemplo básico de Machine Learning, realizando el análisis, limpieza,
entrenamiento y despliegue de un modelo de aprendizaje automático supervisado.

**CREACIÓN DE IMAGEN**
* cd Actividad03/docker/
* docker build -t regresion_lineal:v0.1 .
* docker images

**CREACION DE CONTENEDOR**
* cd Actividad03/
* docker run -it -p 8080:8080 -v "$PWD"/code/:/home/code/ --name gitpod_rl1 -h rl1 regresion_lineal:v0.1

