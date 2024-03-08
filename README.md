# Road Structure Analysis using Clustering Techniques

## Table of Contents

1. [Overview](#overview)
2. [Data Loading](#data-loading)
3. [Data Scaling](#data-scaling)
4. [Correlation Analysis](#correlation-analysis)
5. [K-Means Clustering](#k-means-clustering)
6. [K-Means Clustering using Population Density feature](#k-means-clustering-using-population-density-feature)
7. [Hierarchical Clustering](#hierarchical-clustering)
8. [Insights and Analysis](#insights-and-analysis)
9. [Overall Insights](#overall-insights)

## Overview <a name="overview"></a>

In this project, I have analyzed the road structure of different cities using clustering techniques. The data was taken from the paper [**"Urban Spatial Order: Street Network Orientation, Configuration, and Entropy"**](https://rdcu.be/dADLR) by Geoff Boeing, which examines street network patterns across 100 global cities. The primary goal was to understand how factors like entropy, street length contribute to road quality. Further, I have also taken another feature, **population density**, and undertook preprocessing steps to ensure its compatibility with the road structure data. This included extraction, merging, handling missing values, and scaling and then analyzed to see if there is any similarity between the city's road structure and population density.

## Data Loading <a name="data-loading"></a>

- Extracted the data from the PDF into Excel using Excel's 'Get Data' feature, then loaded it into Google Colab.

## Data Scaling <a name="data-scaling"></a>

- Discussed the importance of maintaining a uniform scale across variables for K-means and Hierarchical clustering.
- Applied Min-Max Scaler and Standard Scaler to normalize and scale the features.
- In further analysis, I have used data where the data is being scaled using min-max scaler.

## Correlation Analysis <a name="correlation-analysis"></a>

- Checked the correlation matrix to identify redundant variables.
- Created a heatmap to visualize correlations.

## K-Means Clustering <a name="k-means-clustering"></a>

- Used the Elbow Method to find the optimal number of clusters.
- Applied K-Means clustering to group cities into clusters based on different road features.

## K-Means Clustering using Population Density feature <a name="k-means-clustering-using-population-density-feature"></a>

- Extracted population density data and merged it with road structure data.
- Filled missing values and scaled the population density.
- Used the Elbow Method and applied K-Means clustering to group cities into clusters based on entropy and population density.

## Hierarchical Clustering <a name="hierarchical-clustering"></a>

- Used population density data and entropy feature to do clustering using the hierarchical method.
- Explored four linkage methods (single, complete, average, and Ward's) for hierarchical clustering.
- Visualized clustering results using dendrograms and scatter plots.

## Insights and Analysis <a name="insights-and-analysis"></a>

- Analyzed clusters from K-Means and Hierarchical clustering.
- Looked for correlations between different road features and then between entropy and population density.
- Found insights such as the top 5 cities having the best road structure, etc.

## Overall Insights <a name="overall-insights"></a>

This project helped in understanding k-means and hierarchical clustering techniques in understanding and categorizing diverse datasets. Using these two techniques, I clustered various cities based on different features and also performed clustering for the city based on entropy and its correlation with population density.
