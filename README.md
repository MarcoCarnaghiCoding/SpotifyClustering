# Spotify Track Clustering Project

![Spotify](https://img.shields.io/badge/Spotify-Data%20Analysis-blue)

Welcome to the Spotify Track Clustering project! In this project, we explore and cluster Spotify tracks based on their metadata using two different methods: K-means and Agglomerative Clustering.

## Clustering Methods

### Agglomerative Clustering
Agglomerative Clustering is a hierarchical clustering algorithm that iteratively merges similar clusters, revealing the hierarchical structure of the data. It can handle various distance metrics and is robust to noise.

### K-Means
K-Means is a centroid-based clustering algorithm that partitions data into K clusters. It's fast and scalable, but assumes spherical clusters and may converge to suboptimal solutions.

## Evaluation Metrics

We evaluate our clustering methods using the following metrics:

- **Silhouette Score:** Measures cluster quality based on data point fit and dissimilarity.
- **Calinski-Harabasz Score:** Measures between-cluster variance relative to within-cluster variance.
- **Davies-Bouldin Score:** Measures average cluster similarity while considering cluster sizes.

## t-Distributed Stochastic Neighbor Embedding (t-SNE)

To achieve a more meaningful lower-dimensional representation, we employ t-SNE. This technique models pairwise similarities and maps high-dimensional data to a lower-dimensional space, revealing patterns not apparent in the original space.

## Interpreting Clusters

We interpret clusters based on popular songs in each group, including:

- Party Time
- Uplifting Rock
- Hits Argentos
- Sad and Moody
- Soundtracks
- Rock del Nuestro
- Hard Rock
- 80s Anthems

## Conclusions

Both clustering methods performed well, distinguishing between genres and musical characteristics. Agglomerative Clustering slightly outperformed K-Means and identified additional clusters, including movie soundtracks.

This project showcases the power of data analysis and clustering in revealing hidden patterns in music metadata.
