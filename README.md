# Hierarchical_Clustering_for_Customer_Data
Customer segmentation using hierarchical clustering on the Mall Customers dataset. Analysis includes preprocessing, EDA, dendrogram, and 2D/3D visualizations. The results identify distinct customer groups to support targeted marketing strategies.
📌 Project Overview
This project applies Hierarchical Clustering (Ward’s method) on the Mall Customers Dataset to segment customers based on Annual Income, Spending Score, and Age. The aim is to identify meaningful customer groups to support targeted marketing strategies.

⚙️ Steps in the Project
Import Libraries – NumPy, Pandas, Matplotlib, Seaborn, SciPy, Scikit-learn, Plotly
Load Dataset – Mall_Customers.csv
Data Preprocessing – Encoding categorical data, checking missing values, summary statistics
Exploratory Data Analysis (EDA) – Distribution plots & correlation heatmap
Feature Selection – Income & Spending Score used for clustering
Dendrogram – To determine optimal number of clusters
Hierarchical Clustering – Agglomerative clustering with 5 clusters
Visualization
2D Scatter plot of Income vs Spending
3D Plotly visualization with Age, Income, Spending
Clustered Data – Cluster label added to dataset
📊 Results
The dendrogram suggested 5 clusters.
Clusters represent distinct customer groups:
Cluster 0: High spenders with mid-level income
Cluster 1: Budget-conscious shoppers
Cluster 2: High-income but low-spending group
Cluster 3: Young customers with high spending
Cluster 4: Older/low-income low spenders
🛠️ Technologies Used
Python 3
Pandas, NumPy
Matplotlib, Seaborn, Plotly
SciPy, scikit-learn
