<div align="center">

# 🤖 Machine Learning Portfolio

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

*Colección de proyectos y ejercicios de Machine Learning desarrollados durante la Maestría en Ingeniería de Sistemas y Computación — Universidad de los Andes*

</div>

---

## 📁 Estructura del repositorio

```
machine-learning/
├── 01-exploratory-data-analysis/    # EDA y manipulación de datos
├── 02-linear-regression/            # Regresión lineal
├── 03-polynomial-lasso-ridge/       # Regularización y regresión polinomial
├── 04-logistic-regression/          # Regresión logística y clasificación
├── 05-knn-decision-trees/           # KNN, árboles de decisión
├── 06-ml-pipelines/                 # Pipelines de ML
└── 07-clustering-kmeans/            # Clustering no supervisado
```

---

## 🗂️ Proyectos

### 📊 01 · Exploratory Data Analysis
> Análisis exploratorio de un dataset de canciones de Spotify con más de 18,000 registros.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`spotify-songs-eda.ipynb`](./01-exploratory-data-analysis/spotify-songs-eda.ipynb) | Análisis de popularidad, bailabilidad y características de canciones | Spotify Songs (~18K registros) |

**Conceptos:** Pandas · Matplotlib · Seaborn · Estadística descriptiva · Visualización de datos

---

### 📈 02 · Linear Regression
> Predicción de popularidad musical usando regresión lineal simple y múltiple.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`linear-regression-music-popularity.ipynb`](./02-linear-regression/linear-regression-music-popularity.ipynb) | Modelo de regresión lineal para predecir popularidad de canciones | Spotify Songs |

**Conceptos:** Regresión lineal · MSE · R² · Train/Test split · scikit-learn

---

### 🔧 03 · Polynomial Regression & Regularization
> Comparación de técnicas de regularización para prevenir overfitting.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`polynomial-regression-song-features.ipynb`](./03-polynomial-lasso-ridge/polynomial-regression-song-features.ipynb) | Regresión polinomial sobre características de canciones | Spotify Songs |
| [`lasso-regularization.ipynb`](./03-polynomial-lasso-ridge/lasso-regularization.ipynb) | Regularización L1 — selección automática de features | Spotify Songs |
| [`ridge-regularization.ipynb`](./03-polynomial-lasso-ridge/ridge-regularization.ipynb) | Regularización L2 — control de complejidad del modelo | Spotify Songs |

**Conceptos:** Regularización L1/L2 · Overfitting · Bias-Variance tradeoff · Cross-validation

---

### 🎯 04 · Logistic Regression & Classification
> Clasificación binaria y proyecto integrador de ML.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`logistic-regression-classification.ipynb`](./04-logistic-regression/logistic-regression-classification.ipynb) | Regresión logística para clasificación binaria | Custom dataset |
| [`project-logistic-regression.ipynb`](./04-logistic-regression/project-logistic-regression.ipynb) ⭐ | **Proyecto completo:** pipeline de clasificación end-to-end | Datos_Etapa_1 |

**Conceptos:** Regresión logística · Matriz de confusión · Precision · Recall · F1-Score · ROC-AUC

---

### 🌳 05 · KNN & Decision Trees
> Algoritmos de clasificación basados en vecinos y árboles.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`knn-employee-attrition.ipynb`](./05-knn-decision-trees/knn-employee-attrition.ipynb) | Predicción de rotación de empleados con KNN | Employee Attrition |
| [`decision-trees-employee-attrition.ipynb`](./05-knn-decision-trees/decision-trees-employee-attrition.ipynb) | Árboles de decisión para clasificación de empleados | Employee Attrition |
| [`heart-disease-prediction.ipynb`](./05-knn-decision-trees/heart-disease-prediction.ipynb) ⭐ | **Predicción de enfermedades cardíacas** con regresión logística | Heart Disease (~250K registros) |

**Conceptos:** KNN · Árboles de decisión · Hiperparámetros · GridSearchCV · Imbalanced datasets

---

### ⚙️ 06 · ML Pipelines
> Automatización y estandarización de flujos de trabajo en ML.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`ml-pipelines-insurance.ipynb`](./06-ml-pipelines/ml-pipelines-insurance.ipynb) | Pipeline completo con preprocesamiento, transformación y modelado | Employee Attrition |

**Conceptos:** sklearn Pipeline · ColumnTransformer · StandardScaler · OneHotEncoder · Automatización

---

### 🔵 07 · Clustering & Unsupervised Learning
> Aprendizaje no supervisado y proyecto final de agrupamiento.

| Notebook | Descripción | Dataset |
|----------|-------------|---------|
| [`kmeans-clustering-music.ipynb`](./07-clustering-kmeans/kmeans-clustering-music.ipynb) | Segmentación de canciones con K-Means | Spotify Songs |
| [`project-clustering-kmeans.ipynb`](./07-clustering-kmeans/project-clustering-kmeans.ipynb) ⭐ | **Proyecto completo:** clustering y análisis de segmentos | Datos_Etapa_2 |

**Conceptos:** K-Means · Elbow Method · Silhouette Score · PCA · Visualización de clusters

---

## 🛠️ Tecnologías utilizadas

| Categoría | Herramientas |
|-----------|-------------|
| Lenguaje | Python 3.x |
| Manipulación de datos | Pandas, NumPy |
| Machine Learning | scikit-learn |
| Visualización | Matplotlib, Seaborn |
| Entorno | Jupyter Notebook, Google Colab |

---

## 🚀 Cómo ejecutar los notebooks

```bash
# Clonar el repositorio
git clone https://github.com/mjgarcia-bonilla/machine-learning.git
cd machine-learning

# Instalar dependencias
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Abrir Jupyter
jupyter notebook
```

---

## 👩‍💻 Autora

**María J. García-Bonilla** — AI Engineer | MSc Universidad de los Andes

[![GitHub](https://img.shields.io/badge/GitHub-mjgarcia--bonilla-7B00CC?style=flat-square&logo=github&logoColor=white)](https://github.com/mjgarcia-bonilla)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-María_García--Bonilla-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mar%C3%ADa-jos%C3%A9-garc%C3%ADa-bonilla-ab5688267/)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-García--Bonilla-00CCBB?style=flat-square&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Maria-Garcia-Bonilla-3)
