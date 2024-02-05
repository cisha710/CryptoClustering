# CryptoClustering

## Overview:
Predicting if cryptocurrencies are affected by 24-hour or 7-day price changes - using  Unsupervised Learning.

In this study, the knowledge of Python coding and  Unsupervised Learning is utilized to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 

## Instructions:
In order to successfully run the code in the Jupyter Notebook file, Crypto_Clustering_MJoshi.ipynb, download that file along with the crypto_market_data.csv data file stored in the Resource folder in this repository, maintaining the current directory structure for correct loading of data using the python code. 


## Procedure: 
In this exercise, the original dataset was first scaled and then the optimal k-value was discovered using the elbow method. The data was then clustered using the ideal k-value and the k-means algorithm. The data was clustered into two neat groups. There appeared to be 2 outlier labels. 
The dataset was then run through the PCA method to reduce the features of the original dataset. The optimal k-value was again determined for the datset with fewer features and it appears that it is the same as with the original dataset. The PCA dataframe was then analysed using the k-means algorithm and similar clusters were obtained. 

## k-value comparison
![Screenshot 2024-02-05 at 4 10 09 PM](https://github.com/cisha710/CryptoClustering/assets/143370584/027dbcb4-d9bd-4801-92cc-54eccf11cd56)


## cluster comparison
![Screenshot 2024-02-05 at 4 10 33 PM](https://github.com/cisha710/CryptoClustering/assets/143370584/70b964a2-b006-466c-8d29-b572e281da9b)



## Conclusion:
After visually comparing both cluster maps, it can be confirmed that the impact of using PCA data resulted in tighter clusters, it also resulted in more entries within cluster 0 and cluster 1 than the original analysis did.
