# Customer Segmentation using K-Means Clustering

This repository contains code for performing customer segmentation using the K-Means clustering algorithm. Customer segmentation is a crucial task for businesses, allowing them to understand their customer base better and tailor marketing strategies accordingly.

## Dataset
The dataset used for this analysis is the Mall Customers dataset, which contains information about customers such as their gender, age, annual income, and spending score. The dataset is stored in a CSV file named `Mall_Customers.csv`.

## Preprocessing
Before applying the K-Means algorithm, the data undergoes preprocessing steps, including:
- **Encoding categorical variables**: The 'Gender' column is encoded using LabelEncoder.
- **Standardization**: The numerical features are standardized using StandardScaler.

## K-Means Clustering
The optimal number of clusters is determined using the Elbow Method, which is visualized to find the "elbow point" indicating the optimal number of clusters. The K-Means algorithm is then applied with the optimal number of clusters to segment the customers.

## Principal Component Analysis (PCA)
PCA is employed to reduce the dimensionality of the data while retaining most of its variance. This step helps in visualizing the clusters in lower-dimensional space.

## Visualization
The clusters obtained from K-Means clustering are visualized using scatter plots. Additionally, the centroids of each cluster are plotted for better understanding. The customer segments are visualized in a two-dimensional space using PCA components.

## Evaluation
The quality of the clusters is evaluated using the Silhouette Score, which measures how well each data point fits into its assigned cluster. A higher Silhouette Score indicates better-defined clusters.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the provided Python script to perform customer segmentation and visualization.

## Author
Amruth Sai Mudivarthi

## License
This project is licensed under the MIT License.
