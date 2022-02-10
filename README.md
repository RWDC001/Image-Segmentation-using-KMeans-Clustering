# Image-Segmentation-using-KMeans-Clustering

 Image Segmentation: In computer vision, image segmentation is the process of partitioning an image into multiple segments. The goal of segmenting an image is to change the representation of an image into something that is more meaningful and easier to analyze. It is usually used for locating objects and creating boundaries. 

It is not a great idea to process an entire image because many parts in an image may not contain any useful information. Therefore, by segmenting the image, we can make use of only the important segments for processing. 

An image is basically a set of given pixels. In image segmentation, pixels which have similar attributes are grouped together. Image segmentation creates a pixel-wise mask for objects in an image which gives us a more comprehensive and granular understanding of the object.

Uses: 

    Used in self-driving cars. Autonomous driving is not possible without object detection which involves segmentation.
    Used in the healthcare industry. Helpful in segmenting cancer cells and tumours using which their severity can be gauged.

There are many more uses of image segmentation.

In this article, we will perform segmentation on an image of the monarch butterfly using a clustering method called K Means Clustering.

K Means Clustering Algorithm:

K Means is a clustering algorithm. Clustering algorithms are unsupervised algorithms which means that there is no labelled data available. It is used to identify different classes or clusters in the given data based on how similar the data is. Data points in the same group are more similar to other data points in that same group than those in other groups. 

K-means clustering is one of the most commonly used clustering algorithms. Here, k represents the number of clusters.

Let’s see how does K-means clustering work –

    Choose the number of clusters you want to find which is k.
    Randomly assign the data points to any of the k clusters.
    Then calculate the center of the clusters.
    Calculate the distance of the data points from the centers of each of the clusters.
    Depending on the distance of each data point from the cluster, reassign the data points to the nearest clusters.
    Again calculate the new cluster center.
    Repeat steps 4,5 and 6 till data points don’t change the clusters, or till we reach the assigned number of iterations.

Requirements:

    Make sure you have Python, Numpy, Matplotlib and OpenCV installed.
