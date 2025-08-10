# **Clustering ALS Data**

**Project Overview**

This notebook applies clustering techniques to ALS patient data to uncover distinct groupings based on clinical and condition-related variables. After removing irrelevant features, the dataset was standardized to prepare it for clustering. The main objective was to determine the optimal number of clusters using silhouette scores, fit a K-means model, and visualize the results through a PCA transformation to better understand the structure of the data.

**Methods & Results**

The process began by filtering the dataset to retain only information relevant to ALS conditions and applying a standard scaler for normalization. Silhouette scores were calculated for various cluster counts, with two clusters emerging as the optimal choice (highest score at ~0.08). A K-means model was then fit using this cluster count, and the data was transformed with PCA into two components for visualization. The scatterplot revealed clear separation between the two clusters, suggesting that the model effectively grouped patients with similar characteristics. The distribution also indicated meaningful relationships captured by the principal components.

**Key Outputs**

- Cleaned ALS dataset containing only condition-relevant variables
- Standardized features for improved clustering performance
- Silhouette score analysis confirming two optimal clusters
- K-means clustering results with PCA visualization
- Insights into separation and structure of patient groups

**Conclusion**

The combination of K-means clustering and PCA revealed two distinct patient groups within the ALS dataset, highlighting meaningful differences in their clinical characteristics. These findings demonstrate the potential for clustering to aid in understanding patient subgroups, which could inform further research or tailored treatment strategies.
