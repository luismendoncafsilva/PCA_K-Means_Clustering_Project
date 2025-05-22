# Unsupervised Machine Learning: PCA & K-Means Clustering on Microvan Dataset

## 🚀 Project Overview

This project applies **Principal Component Analysis (PCA)** and **K-Means Clustering** to a microvan dataset to explore how unsupervised learning techniques can be used for dimensionality reduction and market segmentation. The goal is to simplify the dataset while uncovering meaningful patterns and groups of vehicles with similar characteristics.

## 🔍 Objectives

- Reduce dimensionality using PCA to improve data interpretability.
- Apply K-Means Clustering to segment vehicles based on technical and performance specifications.
- Visualize and interpret the clusters to extract actionable insights.

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## 📊 Project Steps

1. **Data Exploration and Preprocessing**  
   - Overview of the microvan dataset.  
   - Data normalization for PCA and clustering.

2. **Principal Component Analysis (PCA)**  
   - Dimensionality reduction.  
   - Visualization of the explained variance.  
   - Projection of data into principal components.

3. **K-Means Clustering**  
   - Determination of the optimal number of clusters using the Elbow Method.  
   - Cluster assignment based on principal components.  
   - Visualization of clusters.

4. **Cluster Analysis & Findings**  
   - **Cluster 0:** Higher engine power, heavier vehicles, and higher maximum speed — likely performance-focused models.  
   - **Cluster 1:** Lighter vehicles with smaller engines and lower maximum speeds — economy or entry-level models.  
   - **Cluster 2:** Balanced specs between Clusters 0 and 1 — offering a middle-ground option.

## 💡 Key Insights

- PCA effectively reduced the dataset complexity while retaining most of the variance.
- K-Means successfully segmented the microvans into clear groups with distinct characteristics.
- These insights can support marketing strategies, product positioning, and targeted development.
