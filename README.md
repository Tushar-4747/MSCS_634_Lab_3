# Lab 3 – Clustering Analysis Using K-Means and K-Medoids

##  Course Information
- **Name**: Tushar Jitendrakumar Limbachiya 
- **Course**: MSCS 634 – Machine Learning  
- **Lab Title**: Lab 3 – Clustering Analysis Using K-Means and K-Medoids Algorithms  

##  Purpose
This lab focuses on applying unsupervised learning techniques to the Wine dataset using two popular clustering algorithms: **K-Means** and **K-Medoids**. The goal is to compare the performance of these algorithms using metrics such as the **Silhouette Score** and **Adjusted Rand Index (ARI)** and to visualize how well the data points are grouped into clusters.

##  Files Included
- `Lab3_Clustering_Wine.ipynb`: Jupyter Notebook with all steps from loading the dataset to final analysis and plots.
- `README.md`: This file with lab purpose, insights, and challenges.

##  Methods Used
- **Data Preprocessing**: Standardized using z-score normalization
- **Clustering Algorithms**:
  - K-Means (`sklearn.cluster.KMeans`)
  - K-Medoids (`sklearn_extra.cluster.KMedoids`)
- **Evaluation Metrics**:
  - **Silhouette Score**: Measures cluster cohesion and separation.
  - **Adjusted Rand Index (ARI)**: Measures clustering accuracy against true labels.
- **Visualization**: Used PCA for dimensionality reduction and side-by-side scatter plots to visualize clusters.

##  Key Insights
- K-Means generally performed slightly better in terms of Silhouette Score.
- K-Medoids was more stable when considering cluster shape and potential outliers.
- The visualizations helped highlight differences in cluster centroids vs medoids and how they affect group boundaries.

