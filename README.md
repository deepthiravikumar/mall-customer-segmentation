# mall-customer-segmentation
# Customer Segmentation using K-Means Clustering

This model demonstrates how to perform customer segmentation using K-Means clustering. In this model, we use a dataset of mall customers' annual income and spending scores to group them into distinct clusters based on their purchasing behavior.

## Introduction

Customer segmentation is a vital task for businesses to better understand their customers and marketing strategies. K-Means clustering is a popular unsupervised machine learning technique used for this purpose. It groups similar customers together based on their features, in this case, annual income and spending score.

## Data Source

we start by loading the customer data from a CSV file Mall_Customers.csv in kaggle. The dataset typically contains columns like "Annual Income" and "Spending Score," which are important for segmentation.

## Finding the Optimal Number of Clusters

Before performing K-Means clustering, we need to determine the optimal number of clusters (K). We use the "elbow method" to find the appropriate K value by calculating the within-cluster sum of squares (WCSS) for different K values and plotting them. The "elbow point" in the plot is where the WCSS starts to level off, indicating the optimal K value.

## K-Means Clustering

Once we have determined the optimal K value (in this case 5 cluster), we apply K-Means clustering to group customers into five clusters. The K-Means algorithm assigns each customer to one of the clusters based on their similarity to the cluster centroids.

## Visualizing the Clusters

To visualize the clusters, we create a scatter plot of the customers' data points, where each point is colored according to its assigned cluster. Additionally, we plot the cluster centroids as yellow points.

## Usage

To run this code, you'll need to provide the path to your own customer data CSV file or adjust the path accordingly. Make sure you have the necessary libraries like pandas, numpy, matplotlib, and scikit-learn installed.

Feel free to modify the code to suit your specific dataset or business requirements.

## Author

This code was written by [deepthi_ravikumar].

For any questions or inquiries, please contact [deepthisrikr01@gmail.com].
