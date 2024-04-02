# Report on Customer Data Analysis

## Introduction

This report presents an analysis of customer data with the aim of segmenting customers into homogeneous groups based on their characteristics. The data analysis comprises several steps including data cleaning, normalization, implementation of the K-Means algorithm, and interpretation of results.

## Data Cleaning

The following steps were carried out to clean the data:

1. **Handling missing values:** Rows with missing values were removed using the `dropna()` method.

2. **Removing duplicates:** Any potential duplicates were eliminated using the `drop_duplicates()` method.

3. **Handling outliers:** Outliers were examined and dealt with, for example by removing age values greater than 100.

## Data Normalization

Data was normalized to bring all features to the same scale. Normalization was performed using scikit-learn's MinMaxScaler to scale the 'Age', 'Annual Income', and 'Spending Score' features between 0 and 1.

## Implementation of K-Means Algorithm

The K-Means algorithm was used to segment customers into homogeneous clusters. Prior to this, the optimal number of clusters was determined using the elbow method. Then, K-Means was applied to the normalized data with the optimal number of clusters.

## Interpretation of Clusters

The characteristics of the clusters were analyzed to understand the profiles of different customer groups. This includes examining the means of features per cluster to identify trends and differences between groups.

## Visualization of Results

The analysis results were visualized using appropriate graphs, such as scatter plots to visualize clusters and bar charts to compare feature means between clusters.

## Conclusion

The analysis of customer data successfully segmented customers into homogeneous groups, which can be useful for decision-making and service personalization. However, further analysis may be needed for a deeper understanding of customer behaviors and potential business opportunities.
