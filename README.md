# CryptoClustering

In this challenge, Python and unsupervised learning are used to predict if cryptocurriences are affected by 24-hour or 7-day price changes.

The data is normalized using StandardScaler(). 
The best value for K is found using the scaled data. 
The cryptocurriences are clustered for the best K value from the scaled data.
PCA is performed to reduce the features to 3 components.
The best value for K is then found using the PCA data. 
The cryptocurrencies are clustered using the PCA data. 