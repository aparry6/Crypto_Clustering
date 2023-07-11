# Crypto_Clustering
This readme provides an overview of the steps involved in clustering cryptocurrencies using K-means algorithm and Principal Component Analysis (PCA). 
Created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
Found the best value for k (number of clusters) using the elbow method on the original scaled data.
Clustered the cryptocurrencies using K-means algorithm on the original scaled data with the best value of k.
Performed Principal Component Analysis (PCA) on the original scaled DataFrame and reduced the features to three principal components.
Created a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
Found the best value for k using the elbow method on the PCA data.
Clustered the cryptocurrencies using K-means algorithm on the PCA data with the best value of k.
Answered the question regarding the impact of using fewer features with K-means clustering.
Refer to the code and the outputs in your notebook for more details and specific visualizations.

