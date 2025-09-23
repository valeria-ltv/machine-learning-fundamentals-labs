## Clustering with k-Means and Hierarchical Methods

### Task:

1. Open and read the provided data file.

2. Determine and display the number of records.

3. Remove the quality attribute.

4. Display the remaining attributes.

5. Using the KMeans function of the scikit-learn library, partition the data set into clusters with random initial initialization and display the coordinates of the cluster centers. The optimal number of clusters can be determined based on the initial data set in three different ways:
- elbow method
- average silhouette method
- prediction strength method

6. For the previously selected number of clusters, perform clustering multiple times using the k-means method, using the k-means++ method for initial initialization. Select the best clustering option. What quantitative criterion did you choose to select the best clustering?

7. Using the AgglomerativeClustering function of the scikit-learn library, divide the data set into clusters. Choose the same number of clusters as in the previous method. Output the coordinates of the cluster centers.
