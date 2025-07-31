# 🚢 Titanic Survival Model

Este repositorio contiene el desarrollo de un proyecto de análisis de datos y modelado predictivo utilizando la base de datos histórica del Titanic. Se emplean técnicas de análisis exploratorio y aprendizaje supervisado (regresión logística) para predecir la probabilidad de supervivencia de los pasajeros en base a sus características.

---

## 🎯 Objetivos del Proyecto

- Explorar y comprender los datos disponibles en el conjunto de datos `titanic.csv`.
- Identificar patrones relevantes y relaciones entre variables mediante técnicas de análisis exploratorio.
- Implementar un modelo de clasificación basado en regresión logística.
- Evaluar el desempeño del modelo utilizando métricas estándar.
- Crear una interfaz interactiva que permita hacer predicciones en tiempo real sobre la probabilidad de supervivencia de un pasajero.

---

## 🛠️ Fases del Proyecto

### 1. Análisis Exploratorio de Datos (EDA)

- Carga y visualización de los datos.
- Generación de un reporte detallado usando la librería `ydata-profiling`.
- Identificación de variables categóricas, palabras más comunes en los nombres, y análisis de correlación con la variable objetivo (`Survived`).

### 2. Modelado Predictivo

- Limpieza y preprocesamiento de los datos (manejo de valores nulos y transformación de variables).
- Separación del conjunto de datos en entrenamiento y prueba.
- Entrenamiento de un modelo de regresión logística para predecir la variable `Survived`.
- Evaluación del modelo utilizando métricas: Accuracy, Precision, Recall y F1 Score.

### 3. Interfaz Interactiva

- Desarrollo de una interfaz con `Gradio` para realizar predicciones en tiempo real.
- La interfaz permite ingresar características relevantes (como edad, clase, número de hermanos/esposas a bordo, etc.) y devuelve la probabilidad estimada de supervivencia.

---

## 🧰 Tecnologías y Herramientas Utilizadas

- Python 3
- Pandas
- ydata-profiling
- Scikit-learn
- Gradio
- Google Colab

---

## 📂 Estructura del Proyecto

-  ├── titanic.csv
- ├── Titanic_EDA.ipynb # Análisis exploratorio de datos
- ├── Titanic_LogisticModel.ipynb # Entrenamiento y evaluación del modelo
- ├── gradio_interface.py # Interfaz interactiva para predicciones
- ├── README.md

---

## 👥 Autores

- [Juan Pablo Arias](https://github.com/JuanParias29)
- Sergio Pardo Hurtado

---
## 📚 Curso
Técnicas de Aprendizaje de Máquina (ML)
- **Docente:** Oscar Bustos
- Pontificia Universidad Javeriana
