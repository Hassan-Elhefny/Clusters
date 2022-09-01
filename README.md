# Clusters
This Repository will contains the most important types of clusters.

![Clusters!](https://miro.medium.com/max/1400/1*b2sO2f--yfZiJazc5rYSpg.gif)

# What is Clustering?
Clustering is a type of unsupervised learning method of machine learning. In the unsupervised learning method, the inferences are drawn from the data sets which do not contain labelled output variable. It is an exploratory data analysis technique that allows us to analyze the multivariate data sets.

Clustering is a task of dividing the data sets into a certain number of clusters in such a manner that the data points belonging to a cluster have similar characteristics. Clusters are nothing but the grouping of data points such that the distance between the data points within the clusters is minimal. Clustering is done to segregate the groups with similar traits.

# What are the types of Clustering Methods?
Clustering itself can be categorized into two types viz. Hard Clustering and Soft Clustering. In hard clustering, one data point can belong to one cluster only. But in soft clustering, the output provided is a probability likelihood of a data point belonging to each of the pre-defined numbers of clusters.

# Density-Based Clustering
In this method, the clusters are created based upon the density of the data points which are represented in the data space. The regions that become dense due to the huge number of data points residing in that region are considered as clusters.

# DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
DBSCAN groups data points together based on the distance metric. It follows the criterion for a minimum number of data points. It can discover clusters of different shapes and sizes from a large amount of data, which is containing noise and outliers.It takes two parameters – eps and minimum points. Eps indicates how close the data points should be to be considered as neighbors. The criterion for minimum points should be completed to consider that region as a dense region.

# Hierarchical Clustering
Hierarchical Clustering groups (Agglomerative or also called as Bottom-Up Approach) or divides (Divisive or also called as Top-Down Approach) the clusters based on the distance metrics.

In agglomerative clustering, initially, each data point acts as a cluster, and then it groups the clusters one by one. This comes under in one of the most sought-after clustering methods.

Divisive is the opposite of Agglomerative, it starts off with all the points into one cluster and divides them to create more clusters. These algorithms create a distance matrix of all the existing clusters and perform the linkage between the clusters depending on the criteria of the linkage. The clustering of the data points is represented by using a dendrogram. There are different types of linkages: –

o    Single Linkage: – In single linkage the distance between the two clusters is the shortest distance between points in those two clusters.

o   Complete Linkage: – In complete linkage, the distance between the two clusters is the farthest distance between points in those two clusters.

o   Average Linkage: – In average linkage the distance between the two clusters is the average distance of every point in the cluster with every point in another cluster.

# Fuzzy Clustering
In fuzzy clustering, the assignment of the data points in any of the clusters is not decisive. Here, one data point can belong to more than one cluster. It provides the outcome as the probability of the data point belonging to each of the clusters. One of the algorithms used in fuzzy clustering is Fuzzy c-means clustering.

This algorithm is similar in approach to the K-Means clustering. It differs in the parameters involved in the computation,  like fuzzifier and membership values. In this type of clustering method, each data point can belong to more than one cluster.  This clustering technique allocates membership values to each image point correlated to each cluster center based on the distance between the cluster center and the image point.


# Partitioning Clustering
This method is one of the most popular choices for analysts to create clusters. In partitioning clustering, the clusters are partitioned based upon the characteristics of the data points. We need to specify the number of clusters to be created for this clustering method. These clustering algorithms follow an iterative process to reassign the data points between clusters based upon the distance. The algorithms that fall into this category are as follows: –

o   K-Means Clustering: – K-Means clustering is one of the most widely used algorithms. It partitions the data points into k clusters based upon the distance metric used for the clustering. The value of ‘k’ is to be defined by the user. The distance is calculated between the data points and the centroids of the clusters.

K-means clustering is a type of unsupervised learning used when you have unlabeled data (i.e., data without defined categories or groups). This algorithm aims to find groups in the data, with the number of groups represented by the variable K. In this clustering method, the number of clusters found from the data is denoted by the letter ‘K.’
 The data point which is closest to the centroid of the cluster gets assigned to that cluster. After an iteration, it computes the centroids of those clusters again and the process continues until a pre-defined number of iterations are completed or when the centroids of the clusters do not change after an iteration.

It is a very computationally expensive algorithm as it computes the distance of every data point with the centroids of all the clusters at each iteration. This makes it difficult for implementing the same for huge data sets.
