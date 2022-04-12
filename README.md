# Cryptocurrencies

## Project Overview
A prominent investment bank would like to see what cryptocurrencies are on the trading market and how they could be grouped to create a classification system. In order to do this, we need to use unsupervided learning, specfically in this case, a clustering algorithm.

## Resources
- Data Source: crypto_data.csv
- Software: Jupyter Notebook 6.4.5

## The Process

 ### Orginal Crypto DataFrame
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/og_crypto_df.png?raw=true)

 ### Cleaned Crypto DataFrame
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/new_crypto_df.png?raw=true)

 ### Create Dummy Variables for Categorical Data
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/dummy_variables.png?raw=true)

 ### Standardize the Data
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/standarization.png?raw=true)
 
 ### Reducing Data Dimensions Using PCA
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/pca.png?raw=true)

 ### Elbow Curve to Find the Best Value for K
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/elbow_curve.png?raw=true)

 ### Clustered DataFrame with Predicted Clusters and Cryptocurrencies Features
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/clustered_df.png?raw=true)

 ### A Table with Tradable Cryptocurrencies
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/hvplot_table.png?raw=true)
 
 ### A New DataFrame that has the Scaled Data with the Clustered DataFrame Index
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/new_clustered_df.png?raw=true)

 ### A hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply"
 ![alt text](https://github.com/thehatch4815162342/Cryptocurrencies/blob/main/Images/scatter_plot.png?raw=true)


