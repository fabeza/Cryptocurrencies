# Cryptocurrencies

## Overview
Create an analysis for clients who are preparing to get into the cryptocurrency market. One important client is interested in offering a new cryptocurrency investment portfolio for its customers. They’ve requested a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. 

As the results of the dataset are unknown, a unsupervised Machine Learning model was used to create a clustering algorithm to arrange the cryptocurrencies into groups.

The analysis was performed using an elbow curve to identify the best number of clusters needed to group the cryptocurrencies, Principal Component Analysis (PCA), KMeans clustering method, and hvPlot and Plotyly for visualizations.

## Results
After careful preprocessing of the data, applying the elbow curve method and KMeans, the cryptocurrencies were grouped into four clusters based on transaction volume (Total Coin Supply and Total Coins Mined).

![crypto_plot.png]()

## Summary
The client should consider offering its clients the option of investing in the cryptocurrencies that are in the higher transaction and trade volume clusters, for example, BitTorrent.