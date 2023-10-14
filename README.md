# CryptoClustering Challenge - Cryptocurrency Analysis

Repository for Monash University Bootcamp Module 19 

## File Structure

- **Crypto_Clustering.ipynb**: The main Jupyter Notebook that contains the entire analysis workflow, starting from data loading to clustering.
- **Resources folder with crypto_market_data.csv**: CSV data file containing information about various cryptocurrencies.
- **README.md**: The file you are currently reading, providing an overview of the project and listing included files.

## Project Overview

This project dives into the world of cryptocurrencies, exploring how they're influenced by short-term price changes. We employ Python and unsupervised learning techniques, and the project covers:

### Data Visualization
Initial glance into the `crypto_market_data.csv` to understand the dataset's structure.

### Data Scaling
Using `StandardScaler` from scikit-learn to normalize the dataset and prepare it for clustering.

### Elbow Method for Optimal Clusters
A method to determine the best number of clusters (`k`) for our K-Means clustering.

### K-Means Clustering
Implementing the K-Means clustering algorithm based on the optimal `k` found.

### Principal Component Analysis (PCA)
A technique used to reduce the data dimensions and understand the variance across them.

### Clustering with PCA Data
Performing K-Means clustering on the PCA-reduced data to see if it offers better insights.

### Result Analysis
Comparing and analyzing the clusters obtained from the original and PCA-reduced data.
![2023_10_14_08_39_25_Crypto_Clustering_Jupyter_Notebook](https://github.com/ashakozak/-CryptoClustering-/assets/134185577/38306d09-1bd2-4359-82a9-f706c621fce4)
![2](https://github.com/ashakozak/-CryptoClustering-/assets/134185577/128c78e5-5066-434c-8eca-f5e8aead72ce)

