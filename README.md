# Avocado Price Analysis (2018-2024)

Final project of school course Statistical Pattern Recognition.  
This project aims to analyze avocado prices over the years (2018-2024) in various cities, identifying seasonal patterns, dependencies between cities, and anomalies in the prices. The analysis uses different data visualization techniques, dimensionality reduction, and clustering algorithms to understand price fluctuations and provide useful tools for future decision-making.

## Tools and Techniques Used

### 1. **Data Visualization**
For graphical representation of the data and identifying patterns, the following tools were used:
- **Matplotlib**: A library for creating basic static plots and charts.
- **Seaborn**: Built on top of Matplotlib, Seaborn makes it easier to create more complex statistical plots.
- **Plotly** (optional): Used for interactive and dynamic visualizations.

### 2. **Dimensionality Reduction**
Dimensionality reduction was crucial to simplify the data and allow for clearer visualization of patterns:
- **PCA (Principal Component Analysis)**: A technique used to reduce the dimensionality of the data and visualize the main trends.
- **t-SNE**: Used to preserve the local structure of the data and visualize clusters within the dataset.

### 3. **Clustering Algorithms**
Clustering algorithms were used to identify patterns and dependencies between prices in different cities and time periods:
- **K-Means**: Used to group data into clusters based on similar prices.
- **DBSCAN**: Used for anomaly detection and finding groups of unusual or outlier prices.
- **Agglomerative Clustering**: Used to observe how the data groups hierarchically.

### 4. **Time Series Analysis**
The analysis of price fluctuations over time was facilitated by:
- **Pandas**: A key tool for handling and analyzing time series data.
- **Statsmodels** or **Prophet**: Time series models used to identify trends and seasonalities in avocado prices.

### 5. **Anomaly Detection**
Anomaly detection was important to understand unusual price behaviors:
- **Isolation Forest**: An anomaly detection algorithm used to identify prices that deviate significantly from the norm.
- **One-Class SVM**: Used to detect anomalies based on the density of prices in the dataset.

## Project Objectives

- Identify seasonal patterns and trends in avocado prices.
- Detect anomalies in prices and understand the causes of unexpected fluctuations.
- Analyze dependencies between avocado prices in different cities.
- Use dimensionality reduction and clustering tools to simplify data analysis and visualization.

## Conclusions

By using various data analysis techniques, it was possible to identify specific behaviors in avocado prices between 2018 and 2024. Visualizations helped in detecting dependencies between cities and seasonal patterns, while clustering and dimensionality reduction algorithms confirmed previous observations and simplified data interpretation. These tools provide a solid foundation for strategic decision-making and future avocado price analysis.

