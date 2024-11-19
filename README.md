# Predicción de Trastornos del Sueño usando Algoritmos de Machine Learning


## **Descripción del Proyecto**

Este proyecto aborda el problema de los trastornos del sueño, una condición que afecta significativamente a la salud mental y física de las personas. Utilizando el **dataset de Kaggle: [Sleep Health and Lifestyle Dataset](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)**, este proyecto analiza diversos factores asociados al sueño y aplica modelos de aprendizaje automático para predecir la presencia de trastornos como insomnio y apnea del sueño.


## **Objetivos**

- Identificar patrones relevantes en los datos relacionados con la salud del sueño.
- Aplicar y evaluar diferentes algoritmos de clasificación para predecir trastornos del sueño.
- Comparar los resultados obtenidos y determinar el modelo más adecuado para este propósito.


## **Características del Dataset**

El dataset contiene 374 registros y 13 atributos:

- **Categorías Principales**:
  - `Gender`, `Age`, `Occupation`, `BMI Category`, `Sleep Disorder`.

- **Variables Cuantitativas**:
  - `Sleep Duration (hours)`, `Quality of Sleep (scale: 1-10)`, `Physical Activity Level (minutes/day)`, `Stress Level (scale: 1-10)`, `Blood Pressure`, `Heart Rate (bpm)`, `Daily Steps`.


## **Algoritmos Utilizados**

Se implementaron y compararon los siguientes algoritmos de clasificación:

1. **OneR**: Simplicidad y efectividad al usar un único atributo.
2. **PRISM**: Algoritmo basado en reglas.
3. **Árboles de Decisión**: CART e ID3.
4. **Naive Bayes**: Clasificación basada en probabilidad.
5. **K-Nearest Neighbors (KNN)**: Basado en similitudes.
6. **Regresión Logística**: Modelo lineal.
7. **Red Neuronal Perceptrón Multicapa**: Algoritmo avanzado para capturar patrones complejos.


## **Cómo Ejecutar el Proyecto**

- **Ejecuta el Notebook**
Abre el archivo [sleep_desorder_prediction.ipynb](https://colab.research.google.com/drive/1AvpnO6nOaW0Oxoiz6lRBpx2BoY4eKXHK) en Google Colab para explorar y analizar el dataset.

- **Genera Resultados**
Corre las celdas del notebook para realizar el preprocesamiento, entrenar los modelos, y visualizar las métricas de desempeño.

## **Conclusiones**

- **Regresión Logística** es el mejor modelo en términos de balance entre precisión y simplicidad.
- **OneR** ofrece una alternativa altamente interpretable para casos donde se prefiera un modelo menos computacionalmente costoso.
- Los modelos más complejos, como **MLP**, son útiles para capturar la complejidad de los factores asociados a los trastornos del sueño.