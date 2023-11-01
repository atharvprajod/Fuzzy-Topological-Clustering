# Fuzzy-Topological-Clustering

Fuzzy Topological Clustering is inspired by and provides an alternative implementation of Songdechakraiwut et. al.'s 2021 Paper 'Fast Topological Clustering with Wasserstein Distance', where the initial paper utilized hard k-Means clustering using topological distance as a novel metric to determine clustering assignments. Alternatively, this approach considers applying soft Fuzzy c-Means instead where it represents the following variations to represent the topological distance as a metric to determine the clusters, 

$$
u_{ij} = \frac{1}{\sum \left( \frac{d(i,k)}{d(i,j)} \right)^{\frac{2}{m-1}}}
$$

