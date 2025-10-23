# Práctica 4 — Calidad de Datos, Minería y Despliegue (Churn Modelling)

Este repositorio contiene el desarrollo completo de una solución analítica aplicada al caso de **Churn Modelling**, abordando las etapas de calidad de datos, minería de datos, entrenamiento de modelos, hiperparametrización y despliegue de un modelo predictivo utilizando **Streamlit**.

---

## Contenido del repositorio

El proyecto se encuentra organizado en los siguientes notebooks:

---

### 1. `1.Calidad_Datos.ipynb`
Notebook correspondiente al proceso de **calidad de datos** y **preparación inicial**, donde se realizan tareas como:

- Limpieza de nulos
- Detección y tratamiento de outliers
- Detección de redundancias
- Preparación del dataset para modelado

---

### 2. `2.Mineria_Datos.ipynb`
Notebook enfocado en la **minería de datos**, que incluye:

- Preprocesamiento de datos para modelado
- Entrenamiento y evaluación de modelos:
  - Árbol de decisión
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Redes Neuronales
  - Support Vector Machine (SVM)
- Métricas de clasificación
- Comparación de desempeño mediante **AUC**

---

### 3. `3.Hiperparametrizacion_Prediccion_Churn_Modelling.ipynb`
Notebook en el cual se realiza la **optimización de hiperparámetros** sobre el modelo seleccionado (*árbol de decisión*), empleando:

- GridSearchCV 
- Evaluación de mejoras en desempeño
- Selección del modelo final para despliegue

---

### 4. `4.Despliegue_Grafico_Churn_Modelling.ipynb`
Notebook que contiene el código necesario para realizar el:

- Cargue del modelo final
- Preparación de datos futuros
- Generación de predicciones
- Construcción de interfaz de usuario con **Streamlit**
- Exportación del script `app.py` para despliegue en la nube

---

## Despliegue en Streamlit

El despliegue de la aplicación predictiva se realiza utilizando **Streamlit Community Cloud**, permitiendo:

- Ingreso de características del cliente
- Predicción del riesgo de churn
- Visualización del resultado final

Puedes acceder al despliegue en el siguiente enlace:

**https://practica4desplieguechurnw.streamlit.app/**

En repositorio donde se aloja todo el código sobre el despliegue esta alojado en el siguiente enlace: https://github.com/JesusDiaz5678/Analitica-Despliegue-Churn_Modelling-Streamlit-.git
---

##  Objetivo del proyecto

El propósito principal de esta práctica es aplicar técnicas de:

- Calidad de datos
- Minería de datos
- Entrenamiento y evaluación de modelos
- Optimización via hiperparámetros
- Despliegue de modelos en la nube

Para generar una solución analítica funcional capaz de predecir la **probabilidad de fuga de clientes** (churn).

