# Customer Segmentation using K-Means Clustering (Unsupervised ML)

## Project Overview
This project implements an **Unsupervised Machine Learning** model to categorize customers into distinct groups based on their Annual Income and Spending Score. By using clustering, businesses can identify target segments and optimize their marketing strategies.

## Key Features
* **Data Normalization:** Utilized `StandardScaler` to ensure that all features are on the same scale, preventing bias during the clustering process.
* **K-Means Algorithm:** Applied the K-Means++ initialization method to identify 3 unique customer clusters.
* **Centroid Analysis:** Calculated and visualized the cluster centroids (center points) to represent the average behavior of each segment.

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn (ML), Pandas (Data), Matplotlib (Visualization), NumPy (Logic)
* **Environment:** Pydroid 3

## Insights from Clusters
* **Cluster 1:** Budget-Conscious Customers.
* **Cluster 2:** High-Value Target Customers.
* **Cluster 3:** High-Income Low-Spenders.

## Project Output
![Customer Clusters](./customer_clusters.png)
*(Note: The 'X' markers represent the centroids of each customer segment)*
