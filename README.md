Road Structure Analysis using Clustering Techniques
Overview
In this project, I delved into the analysis of road structures across different cities employing clustering techniques. The dataset was sourced from Geoff Boeing's paper titled "Urban Spatial Order: Street Network Orientation, Configuration, and Entropy", which investigates street network patterns in 100 global cities. The primary objective was to comprehend how factors like entropy and street length contribute to road quality. Additionally, I explored the relationship between road structure and population density.

Steps Taken
1. Data Loading
Extracted data from the PDF into Excel using Excel's 'Get Data' feature.
Loaded the data into Google Colab for further analysis.
2. Data Scaling
Emphasized the importance of maintaining a uniform scale for K-means and Hierarchical clustering.
Applied Min-Max Scaler and Standard Scaler to normalize and scale the features.
Further analysis focused on data scaled using Min-Max Scaler.
3. Correlation Analysis
Checked the correlation matrix to identify redundant variables.
Visualized correlations using a heatmap.
4. K-Means Clustering
Utilized the Elbow Method to determine the optimal number of clusters.
Applied K-Means clustering to categorize cities based on different road features.
5. K-Means Clustering using Population Density
Extracted population density data and merged it with road structure data.
Imputed missing values and scaled the population density.
Applied the Elbow Method and K-Means clustering based on entropy and population density.
6. Hierarchical Clustering
Leveraged population density and entropy for hierarchical clustering.
Explored four linkage methods (single, complete, average, and Ward's) for clustering.
Visualized clustering results using dendrograms and scatter plots.
7. Insights and Analysis
Analyzed clusters from both K-Means and Hierarchical clustering.
Explored correlations between different road features and entropy and population density.
Extracted insights, including identifying the top 5 cities with the best road structure.
Overall Insights
This project provided insights into the application of k-means and hierarchical clustering techniques for understanding and categorizing diverse datasets. Through these methods, I clustered cities based on various features and conducted a  analysis focusing on entropy and its correlation with population density.
