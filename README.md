# CryptoClustering

## Description

This project demonstrates how Python and Google Colab can be used to implement unsupervised machine learning techniques to analyze whether cryptocurrency behaviors correlate with price fluctuations over 24-hour and 7-day periods.

## Technologies and Libraries

- Python (in Google Colab)
- pandas – data manipulation
- hvplot and holoviews – interactive data visualization
- scikit-learn – machine learning (KMeans, PCA, StandardScaler)

## Requirements

1. Upload the provided `crypto_market_data.csv` file to your Google Drive.
2. Open the notebook file: `Crypto_Clustering_SunilWilliams.ipynb` in Google Colab.
3. Ensure all required libraries are installed (Colab includes most by default).
4. Run each cell in sequential order, allowing each to finish processing before moving to the next.

## Analysis Overview

This project uses two main unsupervised learning techniques:

### 1. KMeans Clustering
- Identifies natural groupings within the cryptocurrency market data.
- Helps uncover trends based on short-term and weekly price fluctuations.

### 2. Principal Component Analysis (PCA)
- Reduces dimensionality of the dataset for easier visualization and pattern recognition.
- Maintains core insights while simplifying the feature set.

## Outcomes

- KMeans clustering successfully grouped cryptocurrencies based on behavioral similarities.
- PCA retained the structure and effectiveness of the clustering model, even after reducing the number of features.
- The distribution of data points across clusters remained consistent before and after PCA, confirming that important patterns were preserved.

## Visual Results

Scatter plots produced during the analysis highlight the impact of dimensionality reduction and the consistency of clustering results. This supports the conclusion that PCA can simplify data without compromising the accuracy or insight of the analysis.
