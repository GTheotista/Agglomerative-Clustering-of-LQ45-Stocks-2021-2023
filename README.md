# Agglomerative Clustering in Stock Analysis
## Overview
This repository presents the implementation of Agglomerative Clustering for stock analysis. The main objective is to explore the application of Agglomerative Clustering in understanding stock behavior within the LQ45 index. The analysis considers key financial metrics like historical stock returns, trading volume, stock prices, Price-to-Earnings (P/E) ratio, Earnings per Share (EPS), and Dividends. The Agglomerative Clustering algorithm is applied to group stocks with similar characteristics into distinct clusters.

## Background
The stock market, represented by the LQ45 index, is a dynamic financial arena that attracts investors and researchers alike. This project focuses on investigating LQ45 stocks from 2020 to 2023 to uncover fundamental patterns based on financial metrics. The goal is to provide significant implications for investors, aiding in understanding market dynamics and potentially building diversified portfolios.

## Data Collection
Data was sourced from Yahoo Finance on January 5, 2024, covering various financial metrics such as sector, historical stock prices, trading volume, dividends, and EPS for a diverse set of LQ45 stocks.

## Data Preprocessing
Preprocessing involved calculating average trading volume, total dividend percentage, daily return statistics, and the Price-to-Earnings (P/E) ratio. Binary encoding was applied to categorical variables, such as industry sector, and scaling was performed using Absolute Maximum Scaling for normalization.

## Agglomerative Clustering
The Agglomerative Clustering algorithm was employed to group stocks into clusters based on selected features. The optimal number of clusters was determined using the dendrogram, revealing insights into the behavior of different sectors.

## Conclusion
The clustering analysis categorizes stocks into distinct groups, offering valuable insights into their behavior. This aids investors in making informed decisions and navigating the dynamic financial landscape.

## Recommendations
Based on clustering results, investors can strategically align their portfolios with specific sectors. Recommendations can be tailored considering the risk and potential gains associated with each cluster.

Feel free to explore the Jupyter Notebook and Python scripts for a detailed understanding of the methodology and results. Your feedback and contributions are welcome!
