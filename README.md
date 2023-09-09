# **Predicción de Noticias Falsas utilizando Machine Learning**
Este notebook es una implementación de un modelo de Machine Learning para predecir noticias falsas (fake news) utilizando el conjunto de datos proporcionado.

## **Descripción del Conjunto de Datos**
El conjunto de datos consta de un archivo llamado train.csv que contiene los siguientes atributos:

- **id**: Identificación única para un artículo de noticias.
- **title**: El título de un artículo de noticias.
- **author**: El autor del artículo de noticias.
- **text**: El texto completo del artículo; puede estar incompleto.
- **label**: Una etiqueta que marca el artículo como potencialmente poco confiable:
  * 1: No confiable (fake news).
  * 0: Confiable (noticias legítimas).
## Objetivo
El objetivo de este proyecto es desarrollar un modelo de Machine Learning capaz de predecir si un artículo de noticias es falso o confiable basándose en sus atributos, como el título, el autor y el texto. Este modelo puede ser útil para detectar automáticamente noticias falsas en línea y ayudar a los usuarios a identificar información no confiable.

## **Cómo Utilizar el Notebook**
Descarga el conjunto de datos train.csv proporcionado.
Ejecuta el notebook Fake_News_Prediction.ipynb en un entorno de Jupyter Notebook o Jupyter Lab.
Sigue las instrucciones proporcionadas en el notebook para cargar el conjunto de datos, realizar la limpieza de datos, y entrenar y evaluar el modelo de Machine Learning.

## ***Dependencias***
Asegúrate de tener instaladas las siguientes bibliotecas de Python antes de ejecutar el notebook:

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

Puedes instalar estas bibliotecas utilizando pip:
