# 🤖 Artificial Intelligence Assignment

## K-Nearest Neighbors (KNN) & K-Means Clustering Implementation From Scratch

### Course Information

**Course:** CSE 3812 – Artificial Intelligence
**Department:** Computer Science & Engineering
**University:** United International University (UIU)
**Assignment Date:** May 24, 2026

---

# 📖 Project Overview

This project consists of implementing two fundamental Machine Learning algorithms from scratch:

1. **K-Nearest Neighbors (KNN)** – A supervised learning algorithm used for classification.
2. **K-Means Clustering** – An unsupervised learning algorithm used for grouping similar data points.

The implementation strictly follows the assignment requirements and avoids using machine learning libraries such as Scikit-Learn. Only basic numerical and visualization libraries are used.

---

# 🎯 Objectives

## Objective 1: K-Nearest Neighbors (KNN)

The objective is to implement the KNN classification algorithm manually and analyze how different values of K affect classification accuracy.

### Tasks

* Load and preprocess a labeled dataset
* Normalize feature values
* Split data into training and testing sets
* Implement Euclidean distance calculation
* Find K nearest neighbors
* Perform majority voting
* Predict class labels
* Calculate classification accuracy
* Compare performance for different K values
* Plot K vs Accuracy

### K Values Tested

```python
K = [1, 3, 5, 7]
```

---

## Objective 2: K-Means Clustering

The objective is to implement the K-Means clustering algorithm from scratch and analyze how the number of clusters affects inertia and cluster formation.

### Tasks

* Load 2D dataset
* Normalize features
* Randomly initialize cluster centers
* Assign data points to nearest centroids
* Update cluster centroids
* Repeat until convergence
* Calculate inertia
* Visualize clusters and centroids
* Compare clustering results for different K values

### K Values Tested

```python
K = [2, 4, 6, 7]
```

---

# 🛠 Technologies Used

* Python 3
* NumPy
* Matplotlib
* Math Module
* Jupyter Notebook

### Libraries Allowed

```python
import numpy as np
import matplotlib.pyplot as plt
import math
```

### Libraries Not Used

❌ Scikit-Learn

❌ Pandas

❌ Built-in Clustering Libraries

---

# 📂 Project Structure

```text
AI-Assignment/
│
├── dataset.txt
├── knn_implementation.ipynb
├── kmeans_implementation.ipynb
├── report.pdf
├── plots/
│   ├── knn_accuracy_plot.png
│   ├── kmeans_k2.png
│   ├── kmeans_k4.png
│   ├── kmeans_k6.png
│   └── kmeans_k7.png
│
└── README.md
```

---

# 🔍 K-Nearest Neighbors (KNN)

## Algorithm Workflow

1. Load Dataset
2. Normalize Features
3. Split Dataset into Train/Test Sets
4. Select K
5. Compute Euclidean Distance
6. Find K Nearest Neighbors
7. Perform Majority Voting
8. Predict Class Labels
9. Calculate Accuracy

### Distance Formula

The Euclidean Distance is calculated using:

```math
d(x,y) = √Σ(xᵢ - yᵢ)²
```

### Evaluation Metric

```math
Accuracy = (Correct Predictions / Total Predictions) × 100
```

---

# 📊 KNN Results

| K Value | Accuracy (%) |
| ------- | ------------ |
| 1       | XX.XX        |
| 3       | XX.XX        |
| 5       | XX.XX        |
| 7       | XX.XX        |

> Replace the values above with your experimental results.

### Visualization

* K vs Accuracy Plot

This graph illustrates how classification performance changes as the value of K increases.

---

# 🎯 K-Means Clustering

## Algorithm Workflow

1. Load Dataset
2. Normalize Features
3. Select Number of Clusters (K)
4. Randomly Initialize Centroids
5. Assign Points to Nearest Centroid
6. Update Centroids
7. Repeat Until Convergence
8. Compute Inertia
9. Visualize Results

---

## Inertia Formula

Inertia measures the compactness of clusters.

```math
Inertia = Σ ||x - c||²
```

Where:

* x = data point
* c = corresponding cluster center

Lower inertia generally indicates better clustering.

---

# 📈 K-Means Results

| Number of Clusters (K) | Inertia |
| ---------------------- | ------- |
| 2                      | XXXX    |
| 4                      | XXXX    |
| 6                      | XXXX    |
| 7                      | XXXX    |

> Replace the values above with your calculated inertia values.

---

# 📊 Cluster Visualizations

The following visualizations are generated:

### K = 2

* Cluster Plot
* Cluster Centers

### K = 4

* Cluster Plot
* Cluster Centers

### K = 6

* Cluster Plot
* Cluster Centers

### K = 7

* Cluster Plot
* Cluster Centers

Each cluster is displayed using a different color, while cluster centers are highlighted separately.

---

# 🔬 Analysis

## KNN Analysis

* Smaller K values are sensitive to noise.
* Larger K values provide smoother decision boundaries.
* Very large K values may lead to underfitting.
* The optimal K achieves the highest test accuracy.

## K-Means Analysis

* Inertia decreases as K increases.
* More clusters create tighter groupings.
* Excessively large K may lead to over-segmentation.
* The relationship between K and inertia can be analyzed using the Elbow Method.

---

# 🎓 Learning Outcomes

Through this assignment, the following concepts were practiced:

* Supervised Learning
* Unsupervised Learning
* Distance-Based Classification
* Clustering Techniques
* Feature Normalization
* Euclidean Distance
* Performance Evaluation
* Data Visualization
* Algorithm Design from Scratch

---

# 🚀 Assignment Requirements Fulfilled

✅ KNN Implemented From Scratch

✅ K-Means Implemented From Scratch

✅ Feature Normalization Applied

✅ Euclidean Distance Used

✅ Accuracy Evaluation Performed

✅ Inertia Calculation Implemented

✅ Multiple K Values Tested

✅ Data Visualization Generated

✅ No Scikit-Learn Used

---

# 👨‍💻 Author

**Name:** MD. Siam Afroz Tanmoy

**Student ID:** 0112230123

**Course:** CSE 3812 – Artificial Intelligence

**Department:** Computer Science & Engineering

**University:** United International University (UIU)

---

> This project demonstrates the implementation of both supervised and unsupervised machine learning algorithms from scratch, providing a deeper understanding of their internal working mechanisms without relying on external machine learning frameworks.
