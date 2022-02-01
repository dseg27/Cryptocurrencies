# Cryptocurrencies

## Overview 

The purpose of this project was to employ unsupervised machine learning algorithms such as K Means, and managing data using Principal Component Analylsis (PCA) to identify groups within our unlabeled cryptocurrency data. 

The data was first processed and scaled, and then fed to a PCA model to reduce data dimensions to three components. A new dataframe was constructed using these three principle components. An elbow curve was generated to determine the ideal number of clusters to feed into the KMeans algorithm, which ended up being 4 clusters. The results were then visualized via scatter plots by both the three principal components:


![image](https://user-images.githubusercontent.com/90593897/151893873-6bdbcd93-a476-4be1-aa75-514d5c102b8b.png)


and by class:


![image](https://user-images.githubusercontent.com/90593897/151893900-b715cb2b-77b4-4beb-b811-b388a9b36db4.png)
