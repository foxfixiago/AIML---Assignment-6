# Practical Assignment 6: Clustering Algorithms

AIML Lab, MIT Academy of Engineering, Pune

Clustering of the UCI Wine dataset (178 samples, 13 features) using
K-Means, Agglomerative (Hierarchical), DBSCAN and Gaussian Mixture Model.
Evaluated with Silhouette score, Davies-Bouldin index, Calinski-Harabasz
and Adjusted Rand Index.

## Results
| Algorithm | Silhouette | Davies-Bouldin | ARI |
|---|---|---|---|
| K-Means (k=3) | 0.285 | 1.389 | 0.897 |
| Agglomerative (Ward) | 0.277 | 1.419 | 0.790 |
| GMM (k=3) | 0.284 | 1.394 | 0.880 |
| DBSCAN | 0.342 | 1.126 | 0.322 |

K-Means performed best overall. DBSCAN's scores exclude 52 noise points.

## Run
pip install -r requirements.txt
jupyter notebook Practical_Assignment_6_Clustering.ipynb

## Author
Your Name, PRN
