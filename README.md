# Cryptocurrency Clustering Analysis

This repository contains an analysis of cryptocurrency market data, aiming to cluster the cryptocurrencies based on their market performance using K-Means clustering. The analysis includes data preprocessing, normalization, clustering, and visualization. Additionally, the Principal Component Analysis (PCA) technique is used to optimize and compare clustering results.

## Files in this Repository

- `crypto_market_data.csv`: The dataset containing cryptocurrency market data.
- `Crypto_Clustering.ipynb`: The Jupyter Notebook containing the complete analysis.
- `.gitattributes`: Git attributes file to manage end-of-line normalization.

## Assignment Overview

This project involves several key steps to analyze and cluster cryptocurrencies:

1. **Data Loading and Preprocessing**
   - Load the cryptocurrency market data from a CSV file.
   - Drop any rows with missing values and the `coin_id` column.

2. **Data Normalization**
   - Use the `StandardScaler` module from scikit-learn to normalize the data.

3. **Elbow Method for Optimal K**
   - Determine the optimal number of clusters (k) using the Elbow Method.
   - Plot the inertia values for different k values to identify the optimal k.

4. **Principal Component Analysis (PCA)**
   - Apply PCA to reduce the dimensionality of the data.
   - Determine the explained variance to understand the significance of each principal component.

5. **Clustering with K-Means**
   - Perform K-Means clustering using the optimal k value on both the original scaled data and PCA data.
   - Compare the clustering results with and without PCA.

6. **Visualization**
   - Create scatter plots to visualize the clusters for both original and PCA data.
   - Use hvPlot for interactive visualizations.


