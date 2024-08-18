# crypto_clustering_challenge
#### Danielle Dejean 
AI Bootcamp - Module Challenge #11,
18 August 2024
## Overview
This code classifies cryptocurrencies according to their price fluctuations across various timeframes. It compares the results of the K-means algorithm and principal component analysis (PCA) methods.

## Functionality Implemented
* Jupyter Notebook
* Installs and library imports: pandas, KMeans from sklearn.cluster, PCA from sklearn.decomposition, and StandardScaler from sklearn.preprocessing
* Functions: pd.read_csv, describe, StandardScaler, fit_transform, pd.DataFrame, index, list, range, KMeans, fit, append, plot.line, predict, copy, plot.scatter, PCA, explained_variance_ratio_, cumsum, rename, components_, T, and columns.
* Other code: scaling (normalizing) data, elbow plot, attributed info to each principal component, PCA component weights

## Set Up
* The files wihtin the CryptoClustering repo were updated using Python version 3.10.14, in Jupyter Notebook. To run it, please download the most recent version of [Python](https://www.python.org/downloads/), as well as a code editor that runs Python ([Visual Studio Code](https://code.visualstudio.com/download), [PyCharm](https://www.jetbrains.com/pycharm/download/?section=mac), etc.). 
## Run Instructions:
In Terminal (Mac) or GitBash (Windows):
* Ensure that you're running the correct version of Python (see Set Up above)
* Ensure that you're in the directory containing the file before running
* In Google Collab, open "Crypto_Clustering.ipynb" and click "Run All"
* The program will analyse the source data and produce several plots 
## References
* The Crypto_Clustering_starter_code.ipynb starter file was downloaded from the AI-PT-WEST-MAY-052824_MTTH Module 11 Challenge files and edited to analyze the data.
