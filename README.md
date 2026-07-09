# -Hierarchical-Clustering-on-Iris-Dataset
## Project Overview

This project demonstrates the implementation of **Hierarchical Clustering (Agglomerative Clustering)** using the famous **Iris Dataset**. The objective is to group similar flowers into clusters based on their features without using the target labels.

The project also explains how a **Dendrogram** helps determine the optimal number of clusters before building the clustering model.

---

## Objective

- Understand the working of Hierarchical Clustering.
- Visualize how clusters are formed using a Dendrogram.
- Identify the optimal number of clusters.
- Apply Agglomerative Clustering to group similar data points.
- Visualize the final clusters.

---

## Dataset

**Dataset:** Iris Dataset

The dataset contains **150 flower samples** with the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

---

## Project Workflow

```
Load Dataset
      ↓
Data Preprocessing
      ↓
Feature Scaling
      ↓
Generate Dendrogram
      ↓
Determine Number of Clusters
      ↓
Apply Agglomerative Clustering
      ↓
Assign Cluster Labels
      ↓
Visualize Final Clusters
```

---

## Steps Performed

### 1. Data Loading

- Loaded the Iris dataset from Scikit-learn.

### 2. Data Preprocessing

- Checked dataset structure.
- Prepared feature matrix.

### 3. Feature Scaling

- Applied StandardScaler.
- Standardized all features before clustering.

### 4. Dendrogram Analysis

- Created a dendrogram using Ward linkage.
- Observed the largest vertical gap.
- Selected the optimal number of clusters.

### 5. Hierarchical Clustering

- Applied Agglomerative Clustering.
- Generated cluster labels for each observation.

### 6. Cluster Visualization

- Plotted clusters using Sepal Length and Petal Length.

---

## Results

- Successfully identified natural groups in the Iris dataset.
- Dendrogram helped determine the appropriate number of clusters.
- Agglomerative Clustering grouped similar flowers into three distinct clusters.

---

## Key Concepts Covered

- Unsupervised Learning
- Hierarchical Clustering
- Agglomerative Clustering
- Dendrogram
- Ward Linkage
- Euclidean Distance
- Feature Scaling
- Cluster Visualization

---

## Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt

from sklearn.datasets import load_iris
from sklearn.preprocessing import StandardScaler
from sklearn.cluster import AgglomerativeClustering

from scipy.cluster.hierarchy import linkage, dendrogram
```

---

## Project Output

- Dendrogram Visualization
- Cluster Assignment
- Scatter Plot of Clusters

---

## Learning Outcomes

After completing this project, I learned:

- Difference between K-Means and Hierarchical Clustering.
- Importance of feature scaling in distance-based algorithms.
- How Agglomerative Clustering builds clusters from the bottom up.
- How to interpret a dendrogram.
- How to determine the optimal number of clusters using the largest vertical gap.
- How to implement Hierarchical Clustering using Scikit-learn.

---

## Future Improvements

- Apply Hierarchical Clustering to real-world datasets.
- Compare different linkage methods:
  - Single Linkage
  - Complete Linkage
  - Average Linkage
  - Ward Linkage
- Compare Hierarchical Clustering with K-Means and DBSCAN.
- Evaluate cluster quality using Silhouette Score.

---

## Author

**Bhavya P**

Data Analyst | Machine Learning Enthusiast
