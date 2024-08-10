# Customer Segmentation Analysis

This project performs a customer segmentation analysis on a wholesale distributor dataset. The goal is to identify different groups of customers based on their annual spending on diverse product categories.

## Methodology

The K-Means clustering algorithm is used to group customers into clusters. The number of clusters is determined by running the algorithm with different numbers of clusters and choosing the one that results in the best silhouette score.

## Results

The optimal number of clusters is found to be 3. The clusters can be characterized as follows:

Cluster 0: Customers in this cluster tend to purchase more fresh products and fewer of the other types of products. This could represent customers like restaurants or cafes that need fresh food to prepare meals.

Cluster 1: Customers in this cluster tend to purchase more of 'Milk', 'Grocery', 'Frozen', 'Detergents_Paper', 'Delicassen', and 'Average_GMD'. This could represent customers like supermarkets or large grocery stores.

Cluster 2: Customers in this cluster have a more balanced purchasing behavior, buying a moderate amount of various types of products. This could represent smaller retailers or markets.

## Conclusion

The results of this analysis can provide valuable insights for the distributor. For example, they could tailor their marketing strategies or improve their supply chain management for each type of customer. Future work could involve validating these findings with additional data or using different clustering algorithms.
