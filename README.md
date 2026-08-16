# 🌸 Iris K-Means Clustering

An unsupervised machine learning project that applies **K-Means Clustering** to the famous Iris dataset.

The goal is to group iris flowers based only on their numerical measurements, without using the species labels during training. The true species labels are used later only for evaluation and comparison.

---

## 📌 Project Overview

The Iris dataset contains measurements of iris flowers from three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

Each sample contains four numerical features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

In this project, I treated the problem as an **unsupervised learning task** and used K-Means to discover natural groups within the data.

---

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Kaggle

---

## 🔍 Project Workflow

### 1. Data Loading

Loaded the Iris dataset using Pandas and inspected its:

- Shape
- Data types
- Statistical summary
- Columns

### 2. Data Cleaning

Checked the dataset for:

- Missing values
- Duplicate rows

Duplicate rows were removed before training.

### 3. Exploratory Data Analysis

Used several visualizations to understand the dataset:

- Histograms
- Correlation Heatmap
- Pairplot

These visualizations helped identify relationships between the numerical features and understand how the species are distributed.

### 4. Feature Scaling

Since K-Means is a distance-based algorithm, the numerical features were standardized using:

```python
StandardScaler()
