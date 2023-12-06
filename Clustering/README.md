## Unveiling Clusters: Exploring K-Means and Hierarchical Clustering

This repository delves into the realm of unsupervised learning, specifically focusing on two prominent clustering algorithms: **K-Means** and **Hierarchical Clustering**. Both techniques aim to uncover hidden groups (clusters) within data based on their similarities.

### K-Means Clustering:

* **Simple and efficient:** K-Means iteratively assigns data points to K pre-defined clusters based on their distances to the cluster centroids.
* **Fast and scalable:** Efficient for handling large datasets due to its iterative nature.
* **Sensitive to initialization:** The initial placement of centroids significantly impacts the final clusters.

### Hierarchical Clustering:

* **Exploratory and flexible:** Supports two main approaches: Divisive (top-down) and Agglomerative (bottom-up), allowing for different clustering granularity.
* **Captures hierarchical relationships:** Identifies nested clusters, revealing insights into data structure at various levels.
* **Computationally expensive:** Can be slower than K-Means for large datasets due to the exhaustive pairwise comparisons.

**This repository provides:**

* Implementations of both K-Means and Hierarchical Clustering in Python.
* Visualizations of the clustering results using various techniques like scatter plots and dendrograms.
* Exploration of different metrics for evaluating cluster quality, such as silhouette score and Calinski-Harabasz index.
* Application examples on real-world datasets, showcasing the strengths and weaknesses of each algorithm.

### Getting Started:

1. Clone this repository.
2. Install the required dependencies.
3. Run the provided Jupyter notebook or Python scripts to explore the examples.

### Further Resources:

* K-Means: [https://en.wikipedia.org/wiki/K-means_clustering](https://en.wikipedia.org/wiki/K-means_clustering)
* Hierarchical Clustering: [https://en.wikipedia.org/wiki/Hierarchical_clustering](https://en.wikipedia.org/wiki/Hierarchical_clustering)
* Scikit-learn KMeans: [http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
* Scikit-learn AgglomerativeClustering: [http://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html](http://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html)
* Comparing K-Means and Hierarchical Clustering: [https://buggyprogrammer.com/k-means-vs-hierarchical-clustering/](https://buggyprogrammer.com/k-means-vs-hierarchical-clustering/)

