# CryptoClustering
Module 19 Challenge for Laura Jordan

## Description
In this challenge, I used my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

There were several steps that I followed to complete this challenge:
 1. Prepare the Data - I used the StandardScaler module from scikit-learn to normalize the data then created a dataframe with that data.
 2. Identify Best Value for 'k' Using Scaled Data - Used the elbow method to find the best value for k.
 3. Cluster Cryptocurrencies with K-Means Using Scaled Data 
 4. Optimized the Clusters with Principal Component Analysis - Used the original scaled dataframe to perform a PCA and reduce the features to three principal components then created a dataframe with that data.
 5. Identify Best Value for 'k' Using PCA Data - Used the elbow method to find the best value for k.
 6. Cluster Cryptocurrencies with K-Means Using PCA Data 

## Support
I attended class and reviewed my notes from class/class activities to complete this challenge assignment.

## Submission Includes 
* Crypto_Clustering_LauraJordan.ipynb file with my code
* Resources folder with the crypto_market_data.csv, which is the csv of data used for the analysis
