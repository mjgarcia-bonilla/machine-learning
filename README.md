<div align="center">

# 🤖 Machine Learning Portfolio

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

*Collection of Machine Learning projects and exercises developed during the MSc in Systems and Computing Engineering — Universidad de los Andes, Colombia*

</div>

---

## 📁 Repository Structure

```
machine-learning/
├── 01-exploratory-data-analysis/    # EDA & data manipulation
├── 02-linear-regression/            # Linear regression
├── 03-polynomial-lasso-ridge/       # Regularization & polynomial regression
├── 04-logistic-regression/          # Logistic regression & classification
├── 05-knn-decision-trees/           # KNN & decision trees
├── 06-ml-pipelines/                 # ML pipelines
└── 07-clustering-kmeans/            # Unsupervised learning
```

---

## 🗂️ Projects

### 📊 01 · Exploratory Data Analysis
> Exploratory analysis of a Spotify songs dataset with over 18,000 records.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`spotify-songs-eda.ipynb`](./01-exploratory-data-analysis/spotify-songs-eda.ipynb) | Analysis of song popularity, danceability and audio features | Spotify Songs (~18K records) |

**Concepts:** Pandas · Matplotlib · Seaborn · Descriptive statistics · Data visualization

---

### 📈 02 · Linear Regression
> Predicting music popularity using simple and multiple linear regression.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`linear-regression-music-popularity.ipynb`](./02-linear-regression/linear-regression-music-popularity.ipynb) | Linear regression model to predict song popularity | Spotify Songs |

**Concepts:** Linear regression · MSE · R² · Train/Test split · scikit-learn

---

### 🔧 03 · Polynomial Regression & Regularization
> Comparison of regularization techniques to prevent overfitting.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`polynomial-regression-song-features.ipynb`](./03-polynomial-lasso-ridge/polynomial-regression-song-features.ipynb) | Polynomial regression on song audio features | Spotify Songs |
| [`lasso-regularization.ipynb`](./03-polynomial-lasso-ridge/lasso-regularization.ipynb) | L1 regularization — automatic feature selection | Spotify Songs |
| [`ridge-regularization.ipynb`](./03-polynomial-lasso-ridge/ridge-regularization.ipynb) | L2 regularization — model complexity control | Spotify Songs |

**Concepts:** L1/L2 regularization · Overfitting · Bias-Variance tradeoff · Cross-validation

---

### 🎯 04 · Logistic Regression & Classification
> Binary classification and end-to-end ML project.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`logistic-regression-classification.ipynb`](./04-logistic-regression/logistic-regression-classification.ipynb) | Logistic regression for binary classification | Custom dataset |
| [`project-logistic-regression.ipynb`](./04-logistic-regression/project-logistic-regression.ipynb) ⭐ | **Full project:** end-to-end classification pipeline | Datos_Etapa_1 |

**Concepts:** Logistic regression · Confusion matrix · Precision · Recall · F1-Score · ROC-AUC

---

### 🌳 05 · KNN & Decision Trees
> Classification algorithms based on neighbors and trees.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`knn-employee-attrition.ipynb`](./05-knn-decision-trees/knn-employee-attrition.ipynb) | Employee turnover prediction using KNN | Employee Attrition |
| [`decision-trees-employee-attrition.ipynb`](./05-knn-decision-trees/decision-trees-employee-attrition.ipynb) | Decision tree classifier for employee attrition | Employee Attrition |
| [`heart-disease-prediction.ipynb`](./05-knn-decision-trees/heart-disease-prediction.ipynb) ⭐ | **Heart disease prediction** with logistic regression | Heart Disease (~250K records) |

**Concepts:** KNN · Decision trees · Hyperparameters · GridSearchCV · Imbalanced datasets

---

### ⚙️ 06 · ML Pipelines
> Automation and standardization of ML workflows.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`ml-pipelines-insurance.ipynb`](./06-ml-pipelines/ml-pipelines-insurance.ipynb) | Full pipeline with preprocessing, transformation and modeling | Employee Attrition |

**Concepts:** sklearn Pipeline · ColumnTransformer · StandardScaler · OneHotEncoder · Automation

---

### 🔵 07 · Clustering & Unsupervised Learning
> Unsupervised learning and final clustering project.

| Notebook | Description | Dataset |
|----------|-------------|---------|
| [`kmeans-clustering-music.ipynb`](./07-clustering-kmeans/kmeans-clustering-music.ipynb) | Song segmentation using K-Means | Spotify Songs |
| [`project-clustering-kmeans.ipynb`](./07-clustering-kmeans/project-clustering-kmeans.ipynb) ⭐ | **Full project:** clustering analysis and segment profiling | Datos_Etapa_2 |

**Concepts:** K-Means · Elbow Method · Silhouette Score · PCA · Cluster visualization

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python 3.x |
| Data manipulation | Pandas, NumPy |
| Machine Learning | scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook, Google Colab |

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/mjgarcia-bonilla/machine-learning.git
cd machine-learning

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Launch Jupyter
jupyter notebook
```

---

## 👩‍💻 Author

**María J. García-Bonilla** — AI Engineer | MSc Universidad de los Andes

[![GitHub](https://img.shields.io/badge/GitHub-mjgarcia--bonilla-7B00CC?style=flat-square&logo=github&logoColor=white)](https://github.com/mjgarcia-bonilla)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-María_García--Bonilla-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mar%C3%ADa-jos%C3%A9-garc%C3%ADa-bonilla-ab5688267/)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-García--Bonilla-00CCBB?style=flat-square&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Maria-Garcia-Bonilla-3)
