# CryptoClustering Challenge - Cryptocurrency Analysis

Repository for the Monash University Bootcamp Module 19.

## File Structure

- **Crypto_Clustering.ipynb**: The primary Jupyter Notebook that encompasses the entire analysis workflow, from data loading to clustering.
- **Resources folder**: Contains the `crypto_market_data.csv` - a CSV data file providing details on various cryptocurrencies.
- **README.md**: The document you're currently reading, which offers an overview of the project and lists the included files.

## Project Overview

This project delves into the realm of cryptocurrencies, investigating their behavior in the face of short-term price fluctuations. By leveraging Python and unsupervised learning techniques, the project encompasses:

### Data Visualization
An initial exploration of the `crypto_market_data.csv` to grasp the dataset's structure.

### Data Scaling
Utilizing `StandardScaler` from scikit-learn to normalize the dataset, preparing it for subsequent clustering.

### Elbow Method for Optimal Clusters
A strategy employed to ascertain the best number of clusters (`k`) for our K-Means clustering.

### K-Means Clustering
Execution of the K-Means clustering algorithm, grounded on the optimal `k` derived earlier.

### Principal Component Analysis (PCA)
A technique adopted to diminish data dimensions, facilitating an understanding of the variance spanning them.

### Clustering with PCA Data
Conducting K-Means clustering on the PCA-diminished data to ascertain if it yields enhanced insights.

### Result Analysis
A juxtaposition and analysis of the clusters derived from both the original data and the PCA-transformed data.

![1](https://github.com/ashakozak/-CryptoClustering-/assets/134185577/ea9cdc23-6b8f-4006-8704-67eaf91fe290)
![2](https://github.com/ashakozak/-CryptoClustering-/assets/134185577/d9b58cb6-ede6-4d6e-ad28-6752e7f462ae)


### Final Thoughts:

From the initial set of 7 features, we distilled them down to 3 primary components. This reduction not only enhances the efficiency of clustering but also simplifies its visual representation, given the fewer dimensions we now work with.
