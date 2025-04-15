# 📊 Predicción de Ventas de Videojuegos con Machine Learning

Este proyecto analiza el conjunto de datos **Video Game Sales** y aplica modelos de regresión para predecir las ventas de videojuegos. A través de distintas técnicas de análisis de datos y modelos de machine learning, se busca estimar las ventas globales de un videojuego a partir de características como plataforma, año, género, etc.

---

## 📁 Estructura del Notebook

### 1. **Importación de Librerías**
Se importan librerías de:
- Manipulación de datos: `pandas`, `numpy`
- Visualización: `matplotlib`, `seaborn`
- Machine Learning: `scikit-learn`, `xgboost`

---

### 2. **Carga y Exploración del Dataset**
- Se carga el archivo `vgsales.csv`.
- Se revisan las primeras filas, tipos de datos y estadísticas descriptivas.
- Se identifican valores faltantes y columnas con valores únicos.
- Se analiza la distribución de publishers (editoras).

---

### 3. **Análisis Exploratorio de Datos (EDA)**
- Se generan gráficos para entender relaciones entre variables:
  - Ventas por género
  - Distribución de ventas por plataforma y año
  - Correlaciones entre ventas regionales y globales
- Se limpian datos irrelevantes o con valores nulos.

---

### 4. **Preprocesamiento**
- Se seleccionan columnas relevantes.
- Se convierten variables categóricas a variables numéricas con *One-Hot Encoding*.
- Se dividen los datos en conjuntos de entrenamiento y prueba (80/20).

---

### 5. **Entrenamiento de Modelos de Regresión**
Se entrenan y comparan los siguientes modelos:
- **Regresión Lineal**
- **Soporte Vectorial para Regresión (SVR)**
- **XGBoost Regressor**

Cada modelo es evaluado con las siguientes métricas:
- MSE (Error cuadrático medio)
- MAE (Error absoluto medio)
- R² Score (Coeficiente de determinación)

---

### 6. **Comparación de Resultados**
Se grafican y comparan los resultados de los modelos, analizando cuál tuvo mejor desempeño en predicción de ventas globales.

---

## 🧠 Tecnologías Usadas

- Python 3.x
- Jupyter Notebook
- scikit-learn
- XGBoost
- Pandas, Numpy
- Matplotlib, Seaborn

---

## 📌 Conclusiones
El análisis permite:
- Comprender qué variables influyen más en las ventas globales.
- Comparar la eficiencia de distintos modelos de regresión.
- Demostrar cómo el preprocesamiento y visualización ayudan a construir mejores modelos predictivos.

---

## 🚀 Cómo Usar

1. Asegúrate de tener instalado Python y Jupyter Notebook.
2. Coloca el archivo `vgsales.csv` en el mismo directorio que el notebook.
3. Abre el archivo `VideoGame_Sales.ipynb` y ejecuta cada celda secuencialmente.
