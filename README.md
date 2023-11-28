# DataScience WEEK 9!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

# Unsupervised Machine Learning Algorithms and Evaluation
# Clustering Method: K-Means, Gaussian MM, DBSCAN, Hierarchical
# Dataset used: Toyota Corolla!

### K-Means:

K-Means is a type of unsupervised machine learning algorithm that consists of a partitioning method. This partitioning method works by dividing the dataset into "K clusters", wherein every data point belongs to an assigned cluster with the nearest mean. This will result in minimal numbers of squared distances in between data points and their respective cluster centroids. An advantage of this algorithm is that it is very efficient for larger datasets and works very well when clusters are equally sized. However, the disadvantage of this algorithm is that they always assume that the clusters are equally sized, making it an inefficient choicec for datasets which goes against that assumption.



### Gaussian Mixture Model

Gaussian Mixture Model (or what i label as Gaussian MM) is a type of unsupervised machine learning algorithm that represents combinations of Gaussian distributions. It works by using an algorithm called Expectation-Maximization (EM) to estimate parameters, and assumes before-hand that all datapoints are just derived from combinations of Gaussian distributions. The advantage of using Gaussian MM is that it can work with clusters which have different sorts of shapes and sizes along with working out probability-related tasks. However, the disadvantage of this algorithm is that it is very power-intensive.



### Hierarchical Clustering

Hierarchical Clustering is a type of unsupervised machine learning algorithm that builds up a tree of clusters by repetitively splitting or splitting clusters. As a result of that recursion, it will give out a hierarchy of clusters, hence the name. These clusters will be represented as a dendrogram, and the number of clusters can be chosen by cutting the dendrogram at a specified height. The advantage to this algorithm is that you dont need to specify the amount of clusters before hand, unlike most other algorithms. However, the disadvantage to this algorithm is that it can be very power intensive.



### DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

DBSCAN is a type of unsupervised machine learning algorithm that groups together data points that are close to each other with numbers of neighours, marking the outliners as noise. The advantage to this algorithm is that you won't need to specify the amount of clusters before hand, unlike other algorithms. However, the disadvantage to this algorithm is that it is poor in performance when working with higher dimensions.






# Results of Score and Eval

![image](https://github.com/ToyotaPrius9/DataScience-UML/assets/114371673/a46d45c2-ddaf-4d05-908a-aaf1b256ca16)



With this result, we can see that Hierarchical Clustering comes best in the Silhouette Score wherein DBSCAN gets the worst score with a negative value, indicating faults with clusters. The Calinski-Harabasz Index shows K-means as the most excelling with DBSCAN again the worst. As for Davies-Bouldin Index, Gaussian MM gets the highest score with Hierarchical Clustering being the lowest this time. 

