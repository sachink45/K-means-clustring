# K-means-clustring

- K-means clustering is a type of unsupervised machine learning algorithm used to partition a given dataset into K distinct clusters. The "K" in k-means refers to the number of clusters that will be formed from the dataset.

- The k-means algorithm works by assigning each data point in the dataset to the nearest centroid, which is a point at the center of a cluster. After all the data points have been assigned to centroids, the mean of the points in each cluster is computed and used to update the location of the centroid. This process is repeated until the centroids no longer move significantly, and the clusters become stable.

- The k-means algorithm is widely used in various applications, including image segmentation, customer segmentation, anomaly detection, and data compression. One of the main advantages of k-means clustering is its simplicity and scalability, as it can be easily applied to large datasets with a high number of dimensions. However, one of the main disadvantages of k-means clustering is that it requires specifying the number of clusters in advance, which can be challenging in some cases.

- In the notebook I have implemented K-means clustring from scratch and compared with the sklearn k-means clustring. This notebook will help you to understand how k-means clustring algorithms works.

Dataset - ! kaggle datasets download -d stefanoleone992/fifa-22-complete-player-dataset
