# Clustering-Varshini-102217252

## Overview
This project aims to implement various clustering algorithms such as Kmeans, Agglomerative Clustering and DBSCAN clustering using different pre-processing techniques and evaluate them on different parameters. The dataset used for this project is the Heart Disease Dataset from UCI Repository.

## Dataset
https://archive.ics.uci.edu/dataset/45/heart+disease

## Output
![image](https://github.com/user-attachments/assets/b5f706f1-e57a-4c58-a6b0-5a503d1e2c9c)
![image](https://github.com/user-attachments/assets/4ff5f8d0-c688-47b1-802c-5692de7dd5a0)
![image](https://github.com/user-attachments/assets/a70603a6-a93b-4a86-9f58-6d9eb01f52b7)

## Line Graphs
Line graphs were used to plot the variation of evaluation metrics (Silhouette Score, Calinski-Harabasz Score, Davies-Bouldin Score) across different subcluster sizes for each processing method. In this type of graph, each line represents a different processing method, and each subplot represents a different evaluation metric.

**Subplots per Evaluation Metric:** The visualization consists of three subplots, each dedicated to one of the standard clustering evaluation metrics:
  1. Silhouette Score: Measures how similar an object is to its own cluster compared to other clusters. Higher values indicate well-separated and dense clusters.
  2. Calinski-Harabasz Score: Also known as the Variance Ratio Criterion, it evaluates cluster dispersion. A higher score suggests better defined clusters.
  3. Davies-Bouldin Score: Quantifies the average similarity between clusters. Unlike the other two, lower values are better.

**X-axis:** Represents the Subcluster Size, i.e., the number of clusters or subgroups formed by the clustering algorithm.
**Y-axis:** Represents the value of the respective evaluation metric.

![image](https://github.com/user-attachments/assets/9d68d739-f69a-42cd-a9a3-e5e2d15b859b)
![image](https://github.com/user-attachments/assets/527c1028-8411-4865-8f81-7d68d11c9543)
![image](https://github.com/user-attachments/assets/a1af27ea-6c1b-4fa7-b685-29d4d741d920)

## Bar Graphs
Bar graphs were used to plot the average scores of each evaluation metric across different processing methods for each subcluster size. In this type of graph, each bar represents the average score of a particular metric for a specific processing method, and each subplot represents a different evaluation metric.

![image](https://github.com/user-attachments/assets/0fe8af3a-e842-4f15-8894-b3236e422cee)
![image](https://github.com/user-attachments/assets/c11af93c-b30a-4627-ac87-9de5a13d932b)
![image](https://github.com/user-attachments/assets/bb14d297-9ecd-4e01-b8e8-06603ba32608)
