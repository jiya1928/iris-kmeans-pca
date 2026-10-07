# Iris Dataset Clustering using K-Means and PCA

## Project Overview

This project applies **K-Means clustering** and **Principal Component Analysis (PCA)** to the Iris dataset.

The main objective is to group Iris flowers into three clusters using K-Means and then reduce the four-dimensional dataset to two dimensions using PCA for visualization and analysis.

## Objectives

- Load and explore the Iris dataset.
- Apply K-Means clustering with `k = 3`.
- Visualize the resulting clusters.
- Standardize the dataset before applying PCA.
- Reduce the four original features to two principal components.
- Visualize the clusters in the reduced two-dimensional space.
- Analyze the variance explained by PCA.

## Dataset

The project uses the built-in **Iris dataset** provided by Scikit-learn.

The dataset contains:

- **150 observations**
- **4 numerical features**
- **3 Iris species**

The four features are:

1. Sepal length
2. Sepal width
3. Petal length
4. Petal width

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

## Methodology

### 1. Load the Dataset

The Iris dataset is loaded using Scikit-learn.

```python
from sklearn.datasets import load_iris

iris = load_iris()

X = iris.data
y = iris.target
