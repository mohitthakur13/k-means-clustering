## k-means clustering algorithm
A Simple implementation of k-means clustering algorithm.

An instance is defined by an array of vectors (or points), representative points of clusters and the number of clusters of the clusters (also called centroids).

The algorithm essentially consists of the iteration of the following two steps:
1. Assign each vector to a cluster by choosing the closest representative
2. Compute the set of new representatives from the vector assignment for each cluster

Note that the algorithm is not guaranteed to be optimal, but is optimal if either vector assignment is fixed or cluster representative.
