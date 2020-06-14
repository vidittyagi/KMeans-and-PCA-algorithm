# KMeans-and-PCA-algorithm

K-MEANS

k-means is  one of  the simplest unsupervised  learning  algorithms  that  solve  the well  known clustering problem. The procedure follows a simple and  easy  way  to classify a given data set  through a certain number of  clusters (assume k clusters) fixed apriori. The  main  idea  is to define k centers, one for each cluster. These centers  should  be placed in a cunning  way  because of  different  location  causes different  result. So, the better  choice  is  to place them  as  much as possible  far away from each other. The  next  step is to take each point belonging  to a  given data set and associate it to the nearest center. When no point  is  pending,  the first step is completed and an early group age  is done. At this point we need to re-calculate k new centroids as barycenter of  the clusters resulting from the previous step. After we have these k new centroids, a new binding has to be done  between  the same data set points  and  the nearest new center. A loop has been generated. As a result of  this loop we  may  notice that the k centers change their location step by step until no more changes  are done or  in  other words centers do not move any more. Finally, this  algorithm  aims at  minimizing  an objective function know as squared error function given by

![kmeans formula](https://user-images.githubusercontent.com/47559181/84587825-1adc3300-ae40-11ea-865e-64de169dac7a.JPG)

where,
                          
                          ‘||xi - vj||’ is the Euclidean distance between xi and vj.
                         ‘ci’ is the number of data points in ith cluster.
                           ‘c’ is the number of cluster centers.
                           
KMeans visualising the dataset 

![kmeans visualising dataset](https://user-images.githubusercontent.com/47559181/84587897-b8376700-ae40-11ea-9135-04db1dc2f1c0.png)


KMeans cluster centroids 

![kmeans cluster centroids](https://user-images.githubusercontent.com/47559181/84587924-f03eaa00-ae40-11ea-89c7-2fe2ce18479f.png)

PRINCIPAL COMPONENT ANALYSIS(PCA)

Principal Component Analysis (PCA) is a statistical procedure that uses an orthogonal transformation which converts a set of correlated variables to a set of uncorrelated variables. PCA is a most widely used tool in exploratory data analysis and in machine learning for predictive models. Moreover, PCA is an unsupervised statistical technique used to examine the interrelations among a set of variables. It is also known as a general factor analysis where regression determines a line of best fit.

PCA visualising the dataset 

![PCA visualising iris dataset](https://user-images.githubusercontent.com/47559181/84588042-bfab4000-ae41-11ea-97c0-4ea9cf441c83.png)

PCA K-Means Clustering Elbow Method

![PCA K-Means Clustering Elbow Method](https://user-images.githubusercontent.com/47559181/84588063-e4071c80-ae41-11ea-9e1e-46e2ea7c2cc4.png)

K-Means Clustering on PCA-Reduced Iris Data Set

![K-Means Clustering on PCA-Reduced Iris Data Set](https://user-images.githubusercontent.com/47559181/84588088-0731cc00-ae42-11ea-98c7-e31f7b3a9d70.png)
