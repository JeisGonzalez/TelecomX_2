# 📊 Telecom X 2 — Modelo de Predicción de Cancelación de Clientes (Churn)

## 📋 Descripción general

En este proyecto se realiza un análisis de churn para la empresa Telecom X, enfocado en comprender 
los factores que influyen en la cancelación del servicio y en el desarrollo de modelos predictivos 
que permitan detectar de forma temprana a los clientes con mayor probabilidad de abandono, apoyando 
la toma de decisiones estratégicas.

El análisis se apoya en un dataset previamente tratado (`datos_tratados.csv`) y desarrolla:
- Preparación de datos
- Análisis de correlaciones y variables relevantes
- Visualizaciones descriptivas
- Modelado predictivo (Regresión Logística y Random Forest)
- Interpretación de resultados y recomendaciones

---

## 🧰 Librerías utilizadas

| Librería | Función |
|----------|---------|
| **pandas** | Manipulación y análisis de datos |
| **scikit-learn** | Preprocesamiento, modelos y métricas |
| **plotly** | Visualizaciones interactivas |
| **IPython.display** | Renderizado dinámico de Markdown |

---

## 📂 Estructura del proyecto

**3)TelecomX_2.ipynb**

Incluye:

### 🗂️ 1. Preparación de datos

- Carga del archivo `datos_tratados.csv`.
- Eliminación de columnas no informativas.
- Definición de la variable objetivo (**Churn**).
- Codificación one-hot de variables categóricas.
- Separación en conjunto de entrenamiento y prueba.

### 📈 2. Correlación y selección de variables

- Cálculo de correlaciones con la variable objetivo.
- Filtro de variables más relevantes.
- Visualización de tasas de churn por variables categóricas.
- Análisis de variables numéricas con boxplots y scatter plots.

### 🤖 3. Modelado predictivo

- Entrenamiento de modelos de clasificación:
  - Regresión Logística
  - Random Forest
- Evaluación con métricas (accuracy, precision, recall, F1).
- Matriz de confusión y ajuste de umbral.
- Interpretación de importancia de variables en el modelo final.

### 📝 4. Interpretación y conclusiones

- Informe automático en Markdown con:
  - Introducción y contexto
  - Análisis numérico y categórico
  - Evaluación comparativa de modelos
  - Selección del modelo final
  - Recomendaciones estratégicas

---

## 📊 Dataset utilizado

- **Archivo:** `datos_tratados.csv`
- Contiene variables demográficas, contractuales y de uso del servicio.

---

## 🧑‍💻 Autor

Proyecto desarrollado como parte del desafío:
**_Challenge Telecom X2: análisis de evasión de clientes_**
