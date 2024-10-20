# Project Overview
This project aims to perform clustering analysis based on health, economic, and social indicators of various countries. The dataset includes important indicators such as child mortality, health expenditures, income levels, and life expectancy of different countries. The project utilizes these data to group countries based on their similarities using various clustering algorithms.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
   - 2.1 [Data Descriptions](#data-descriptions)
3. [Clustering Models](#clustering-models)
   - 3.1 [KMeans Clustering](#kmeans-clustering)
   - 3.2 [Agglomerative Clustering](#agglomerative-clustering)
   - 3.3 [MiniBatch KMeans](#minibatch-kmeans)
4. [Data Analyses](#data-analyses)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

## Dataset
The dataset includes health, economic, and social indicators for various countries. Below are the main variables in the dataset:

### Data Descriptions
- **country**: Country name
- **child_mort**: Child mortality rate (per 1000 live births)
- **exports**: Exports ratio (percentage of GDP)
- **health**: Health expenditure (percentage of GDP)
- **imports**: Imports ratio (percentage of GDP)
- **income**: Income level (in USD)
- **inflation**: Inflation rate (%)
- **life_expec**: Life expectancy (years)
- **total_fer**: Total fertility rate
- **gdpp**: Gross Domestic Product (GDP) in USD

## Clustering Models
Three different clustering models have been used in this project:

### KMeans Clustering
The KMeans algorithm represents data points with K clusters and calculates the center of each cluster. Data points are grouped based on their nearest cluster center.

### Agglomerative Clustering
Agglomerative clustering starts with each data point as a cluster and combines the two closest clusters to create a hierarchical structure. This process continues until only one cluster remains.

### MiniBatch KMeans
MiniBatch KMeans is a variation of the KMeans algorithm. It works on a randomly selected subset of data to reduce computation time, providing faster results.

## Data Analyses
The following analyses have been conducted in the project:
- **Application of Clustering Models**: Clustering operations have been performed on the dataset using KMeans, Agglomerative, and MiniBatch KMeans algorithms.
- **Boxplots**: Boxplots have been created to visualize the distribution among different variables.
- **Calculation of Interquartile Ranges**: Interquartile ranges have been calculated for each variable in the dataset to provide insights into data distribution.
- **Visualization of the Correlation Matrix**: A correlation matrix has been created to analyze the relationships between variables.

## Results
As a result of the clustering analysis and data visualizations performed, distinct groups of countries have been identified based on their health and economic indicators. These groups help in identifying countries with similar health and economic profiles.

## Contributing
If you would like to contribute to this project, please share your suggestions or repo
