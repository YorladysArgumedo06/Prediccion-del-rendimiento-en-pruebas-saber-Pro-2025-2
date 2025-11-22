# Proyecto: Predicción del Rendimiento en Pruebas Saber Pro 📊

Este repositorio contiene el desarrollo de un modelo de Machine Learning para predecir el rendimiento de los estudiantes en las pruebas Saber Pro, basándose en datos socioeconómicos y académicos.

## 👥 Autores

Este proyecto fue desarrollado por:

| Nombre Completo | Número de Identificación | Carrera Universitaria |
| :--- | :--- | :--- |
| **Yorladys Argumedo Lozano** | `1038824209` | Ingeniería Industrial Virtual |
| **Sebastian Gabriel Castro** | `1029720632` | Ingeniería Industrial Virtual |

## 🎥 Entregas y Videos

A continuación se presentan los enlaces a las sustentaciones de las entregas del curso:

*   **Entrega 2 (Preprocesado):** [Ver en YouTube](https://youtu.be/771uPZHF0mw)
*   **Entrega 3 (Final - Solución Kaggle):** [PEGAR AQUÍ EL ENLACE A TU VIDEO FINAL DE YOUTUBE]

---

## 📝 Descripción del Proyecto

El objetivo principal es construir un modelo de clasificación capaz de asignar a cada estudiante una de las cuatro categorías de rendimiento definidas (**Bajo, Medio-Bajo, Medio-Alto, Alto**). Para lograrlo, se realiza un proceso completo que abarca desde la exploración y limpieza de los datos hasta el entrenamiento y la evaluación de diferentes algoritmos de Machine Learning.

Este proyecto se desarrolla en el marco de la competencia de Kaggle para el curso de **Introducción a la Inteligencia Artificial**.

## 🚀 Aproximación a la Solución Final (Notebook 99)

Para la solución definitiva enviada a Kaggle, implementamos un pipeline robusto que incluye:

1.  **Preprocesamiento:**
    *   Imputación de valores numéricos usando la mediana.
    *   Imputación de valores categóricos faltantes con una constante.
    *   Codificación de variables categóricas mediante **One-Hot Encoding**.
    *   Escalado de variables numéricas con **StandardScaler**.
2.  **Modelo Seleccionado:**
    *   Se utilizó un **Random Forest Classifier**. Este modelo fue seleccionado por su capacidad para manejar relaciones no lineales y su robustez frente al sobreajuste (overfitting) en comparación con otros modelos probados.
3.  **Resultados:**
    *   Esta estrategia nos permitió generar el archivo `submission.csv` respetando los IDs del conjunto de test de la competencia.

## 📂 Estructura del Repositorio

El proyecto está organizado siguiendo estrictamente los requisitos de la entrega:

*   **`README.md`**: Información general, autores y enlaces a videos.
*   **`01 - exploración.ipynb`**: (Entrega 1) Carga de datos (`train.csv`, `test.csv`) y Análisis Exploratorio de Datos (EDA).
*   **`02 - preprocesado.ipynb`**: (Entrega 2) Limpieza, manejo de nulos e ingeniería de características inicial.
*   **`03 - modelo con SVM.ipynb`**: Notebook experimental donde se prueba una aproximación usando *Support Vector Machines*.
*   **`04 - modelo con KNN.ipynb`**: Notebook experimental utilizando el algoritmo de *K-Nearest Neighbors*.
*   **`99 - modelo solución.ipynb`**: **(Entrega Final)** Notebook autocontenido que ejecuta el pipeline completo: carga datos, preprocesa, entrena el modelo Random Forest y genera el archivo `submission.csv` para Kaggle.

## 💻 Tecnologías Utilizadas

Para el desarrollo de este proyecto se utilizaron las siguientes herramientas y librerías de Python:

*   **Python 3.x**
*   **Pandas:** Manipulación y análisis de datos tabulares.
*   **NumPy:** Operaciones numéricas eficientes.
*   **Scikit-learn:** Entrenamiento de modelos, pipelines y preprocesamiento.
*   **Matplotlib y Seaborn:** Visualización de datos.
*   **Kaggle API:** Para la descarga automatizada del dataset.
*   **Google Colab:** Entorno de desarrollo.

---
