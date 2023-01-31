# KMeans Clustering with sklearn
## Introduction
This code performs KMeans clustering on a sample data set with two variables (x and y). The data is read from a CSV file, 'data1.csv'.

## KMeans Clustering
1. Import libraries numpy, pandas, matplotlib, sqrt, KMeans and MinMaxScaler.
2. Read the data from 'data1.csv' using pandas and store it in a DataFrame 'df'.
3. Initialize KMeans with number of clusters as 4 and fit it to the data.
4. Predict the clusters for each data point and add the cluster column to the DataFrame 'df'.
5. Plot the clusters using matplotlib.
6. Calculate distances between each data point and centroids of each cluster.
7. Find the closest centroid for each data point and assign it to the corresponding cluster.
8. Find the mean of each cluster and use it as the new centroid for each cluster.
## Results
The code returns the final centroids for each cluster and the data points assigned to each cluster.
