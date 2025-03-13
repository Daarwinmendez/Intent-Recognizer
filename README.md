# Intent-Recognizer | Reconocimiento de Intención en Reseñas de Películas

Este proyecto se basa en la clasificación de reseñas de películas según diferentes emociones o intenciones, utilizando un conjunto de datos de [Kaggle](https://www.kaggle.com/datasets/fahadrehman07/movie-reviews-and-emotion-dataset). Se incluyen análisis exploratorios, limpieza y preprocesamiento de texto con **NLTK**, así como métodos de tokenización, lematización, stemming y eliminación de contracciones. El objetivo final es construir un modelo de reconocimiento de intención (emociones) a partir de las reseñas.

## Características Principales

- **Dataset:** Reseñas de películas con 8 emociones distintas.
- **Procesamiento del Lenguaje Natural (NLP):**
  - Tokenización y lematización con **NLTK**.
  - Eliminación de contracciones con el paquete **contractions**.
  - Utilización de **py3langid** para detectar el idioma.
  - Análisis de frecuencia de palabras y POS tagging.
- **Visualizaciones:** Uso de **matplotlib** para mostrar la distribución de palabras y los resultados del análisis.
- **Entrenamiento de Modelo:** (Incluye detalles del modelo o algoritmos utilizados si aplican).
- **Hallazgos Principales:** (Resumen de la precisión del modelo, patrones de datos observados u otros descubrimientos relevantes).

## Requisitos

Para ejecutar este notebook, se recomienda crear y activar un entorno virtual, después instalar las dependencias:
```bash
pip install numpy==1.26.4 scipy==1.11.2 nltk py3langid contractions pandas matplotlib
```
## Uso

Clonar este repositorio o descargar el archivo intent_recognition_main.ipynb.
1. Instalar los requerimientos mencionados.
2. Abrir el notebook y ejecutar las celdas secuencialmente para:
3. Realizar el preprocesamiento de datos.
4. Entrenar el modelo de clasificación.
5. Analizar y visualizar los resultados.
6. Ajustar los hiperparámetros o cambiar los algoritmos de clasificación según sea necesario.
   
¡Disfruta explorando y aprendiendo sobre el reconocimiento de intenciones en texto con este proyecto!
