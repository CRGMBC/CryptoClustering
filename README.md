# CryptoClustering
Challenge 19

This challenge is to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Provided csv data consisted of a list of cryptocurrencies and their market data during different time periods

##Process##
The data was normalised to be able to find the best k value for the K-Means modelusing all the features of data provided.  
I determined the best value for k was 4 based ont he Elbow curve plot

Based on this k value 4 cluster of crypto currentcies were generated as can be seen in the scatter plot.


Then I reduced the amount of features used by applying Principle component analysis (PCA).

Using the PCA data, I then calculated the optimal k value for the K-Means model.
Finally, new clusters were generated based on the PCA data.


Side by side plots to compare before & after PCA has been applied are available for ease of comparison.
