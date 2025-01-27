# CryptoClustering Challenge

# Task
Use background knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes by
completing the following:
  1. Prepare the Data
  2. Find the Best Value for k Using the Scaled DataFrame
  3. Cluster Cryptocurrencies with K-means Using the Scaled DataFrame
  4. Optimize Clusters with Principal Component Analysis
  5. Find the Best Value for k Using the PCA DataFrame
  6. Cluster Cryptocurrencies with K-means Using the PCA DataFrame

# Data Engineering: Libraries and Dependencies
  1. Python
  2. hvplot
  3. sklearn.cluster: KMeans
  4. sklearn.decomposition: PCA
  5. sklearn.preprocessing: StandardScaler
  6. Visual Studio Code

# Data Analysis
1. Elbow Curve 1 yieled cluster 4 to be the best value for k in original data set
2. Elbow Curve 2 yieled cluster 4 to be the best value for k in the PCA data set
2. The total explained variance of the three principal components is: 0.8950316570309841
3. No k value delta exist between PCA and the original data set
