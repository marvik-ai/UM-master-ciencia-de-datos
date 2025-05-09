URL Planilla Grupos: https://docs.google.com/spreadsheets/d/1ft_r4iGLiGFE3WFzFYoxKQzetdtWpCkg/edit?usp=sharing&ouid=110569650319601117642&rtpof=true&sd=true

# UM - Master - Ciencia de Datos - Modelos de Lenguajes - Clase 1: Despliegue de un modelo de Sentiment Analysis Model utilizando FastAPI, Streamlit y Docker

## Descripción del Proyecto
Este proyecto consiste en desarrollar y desplegar una API con FastAPI que utiliza un modelo de machine learning basado en BERT para realizar análisis de sentimiento de reseñas de películas. La API proporcionará una interfaz para calificar reseñas en una escala de 1 a 5 estrellas basada en la inferencia del modelo que recibe la review en formato de texto plano. Además, se contará con una interfaz de usuario sencilla desarrollada con Streamlit, que permitirá a los usuarios ingresar texto y recibir una calificación automática.

## Objetivos
- Desarrollar una API que disponibilice un modelo de análisis de sentimiento.
- Implementar una interfaz de usuario utilizando Streamlit para interactuar con el modelo.
- Desplegar la solución localmente utilizando Docker para asegurar la portabilidad y escalabilidad del servicio.

## Componentes del Proyecto
- **Dockerfile**: Define el entorno de ejecución contenerizado para la API y la interfaz de usuario.
- **app.py**: Script de Flask para implementar la API.
- **front_streamlit.py**: Script de Streamlit para la interfaz de usuario.
- **requirements.txt**: Lista de dependencias necesarias para el proyecto.
- **build_api.sh, run_api.sh, setup_api.sh, run_docker.sh**: Scripts para facilitar la construcción, ejecución y configuración de la API y el entorno de Docker.

## Uso de Entornos Virtuales
El proyecto utiliza entornos virtuales para gestionar las dependencias y asegurar que el entorno de desarrollo y producción sean consistentes y libres de conflictos entre bibliotecas.

## Instrucciones de Despliegue
Para desplegar la aplicación de forma local:
1. Clonar el repositorio en la instancia.
2. Ejecutar `setup_api.sh` para configurar el entorno virtual y instalar dependencias.
3. Construir la imagen Docker utilizando `build_api.sh`.
4. Desplegar la aplicación ejecutando `run_docker.sh`.

