# Cryptocurrencies by Ketaki
## Overview 
This project creates a report to include the cryptocurrencies that are on the trading market and how they could be grouped to create a classification system for new investment.
This is done using Pandas, Plotly Express and Unsupervised machine learning to preprocess and transform the data and create data visualizations.
## Results
The [Cryptocurrency data](https://github.com/ketpradh/Cryptocurrencies/blob/main/Resources/crypto_data.csv) was pre-processed to drop unwanted data columns and null values using Pandas, reduce the data to include fewer dimensions using Principal Component Analysis(PCA), then passed onto Clustering Algorithms such as K-means algorithms to create visualizations.

1. Elbow Curve for K-means 
- ![Elbow Curve](https://github.com/ketpradh/Cryptocurrencies/blob/main/Resources/Elbow%20Curve.PNG)

2. 3-D PLot for Cryptocurrency data grouping
-  ![3-D Plot](https://github.com/ketpradh/Cryptocurrencies/blob/main/Resources/Detailed%203-D%20Curve%20for%20Precitions.PNG)
 
3. Scatter Plot for Cryptocurrency data grouping
- ![Scatter Plot](https://github.com/ketpradh/Cryptocurrencies/blob/main/Resources/Scatter%20Plot.PNG)

## Summary
From the above analysis, we find that -
- There were **four** clusters or groups [0-3] into which the Cryptocurrency data can be divided. 
- Maximum Cyrptocurrencies belonged to Class(group) "0"  with **288** Cryptocurrency records, followed by Class "1" with **238** records. Class "3" has **5** records.
- **BitTorrent** was the only one in it's class(2) and could not be grouped with other cryptocurrencies.
- The Cyrptocurrencies can now be studied and further analyzed based on their groups, making it easier to make investment decisions for them.
  
