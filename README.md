# Data Science Foru Week 9
##Dataset: Penguin dataset
##Algorithms: DBSCAN, Birch, Agglomerative Clustering, KMeans
##Evaluation Methods: Rand score, Silhoutte score, Davies-Bouldin index, Calinski and Harabasz score

###DBSCAN: 
DBSCAN is a density-based algorithm that forms clusters based on regions of high data point density, discovering clusters of arbitrary shapes. It categorizes points as core, border, or noise, making it robust to outliers. However, it may struggle with clusters of varying densities.

###Birch: 
Birch is a hierarchical clustering algorithm designed for large datasets. It builds a tree-like structure using a combination of centroids and a feature count at each node. Birch is memory-efficient and suitable for streaming data, but its clustering quality may be affected by the "branching factor" parameter.

###Agglomerative Clustering: 
Agglomerative Clustering is a hierarchical method that starts with individual data points as clusters and iteratively merges them based on proximity until a desired number of clusters is reached. It provides a tree-like structure, allowing for varied cluster shapes and sizes, but can be computationally expensive.

###KMeans: 
KMeans is a partitioning clustering algorithm that divides data into a pre-specified number of clusters by minimizing the sum of squared distances between data points and their assigned cluster centers. It assumes clusters are spherical and equally sized, making it sensitive to initial centroids.
