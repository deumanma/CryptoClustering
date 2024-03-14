# Crypto Clustering Project

This project involves clustering cryptocurrencies based on their market data. Using Python libraries such as Pandas, scikit-learn, and Matplotlib, I performed data preprocessing, normalization, and clustering. The goal is to identify patterns and groups within the cryptocurrency market, aiding in the analysis and decision-making process for investments or research.

## Getting Started

### Prerequisites for install:
Pandas
scikit-learn
Matplotlib
hvPlot 


## Usage

1. Load and Display Data: The script starts by loading the cryptocurrency market data from a CSV file into a Pandas DataFrame. It displays sample data and generates summary statistics to understand the dataset better.

2. Data Preparation: The data is then normalized using the StandardScaler to ensure that all features contribute equally to the analysis.

3. Optimal Number of Clusters: Using the Elbow Method, the script determines the optimal number of clusters for K-means clustering. This is done twice: once using the original scaled data and then using data transformed through Principal Component Analysis (PCA).

4. Clustering: Cryptocurrencies are clustered using the K-Means algorithm, first with the scaled data and then with the PCA-transformed data. The clusters are visualized using scatter plots.

5. Principal Component Analysis: PCA is used to reduce the dimensionality of the dataset while retaining most of the variance. This step helps in optimizing clustering by focusing on the components that carry the most information.

6. Feature Influence: The script concludes by analyzing the weights of each feature on the principal components to identify which features have the strongest positive or negative influence on each component.
