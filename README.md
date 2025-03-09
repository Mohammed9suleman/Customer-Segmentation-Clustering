# Customer Segmentation using K-Means and Hierarchical Clustering

## Overview

Customer segmentation is a powerful marketing strategy that helps businesses categorize their customers into different groups based on their behavior. This project leverages **K-Means** and **Hierarchical Clustering** to segment customers using the [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail), which contains transaction data from a UK-based retailer.

The goal is to provide insights that allow businesses to tailor marketing strategies and improve customer engagement.

## Table of Contents
1. [Introduction](#introduction)
2. [Objectives](#objectives)
3. [Dataset](#dataset)
4. [Clustering Techniques](#clustering-techniques)
5. [Results and Insights](#results-and-insights)
6. [Files in the Repository](#files-in-the-repository)
7. [Installation and Usage](#installation-and-usage)
8. [Contributing](#contributing)
   
## Introduction

This project performs customer segmentation using the **Online Retail Dataset** by applying K-Means and Hierarchical Clustering techniques. The insights from this segmentation can help businesses make data-driven decisions about marketing, customer retention, and sales strategies.

## Objectives

- Explore and clean the dataset for analysis.
- Apply K-Means and Hierarchical Clustering to segment customers.
- Interpret the results to derive actionable business insights.
- Visualize the clusters for better understanding.

## Dataset

The dataset includes transaction data from December 2010 to December 2011 for a UK-based online retailer. The dataset consists of attributes such as:
- Invoice number
- Stock code
- Description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

## Clustering Techniques

1. **K-Means Clustering**: Partitions data into `k` clusters, grouping customers based on their purchasing behavior.
   
2. **Hierarchical Clustering**: Groups customers by building a hierarchy, where similar customers are merged together based on a distance metric.

## Results and Insights

After applying the clustering algorithms, the customers are grouped into segments, providing valuable insights into purchasing patterns:
- **Frequent Buyers**: Customers who purchase often.
- **High-Value Customers**: Customers with significant spending.
- **Infrequent Buyers**: Customers with lower engagement but still valuable to target.

These segments can help businesses optimize marketing strategies and improve customer retention.

## Files in the Repository

- `Customer_Segmentation_K-Means_Clustering.ipynb`: The Jupyter notebook containing the code for data loading, cleaning, clustering, and visualization.
- `Customer_Segmentation_PPT.pptx`: A presentation summarizing the project, methodology, and results.

The dataset used for this analysis is too large to be hosted directly in this repository. You can download the dataset from the following link:

[Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)

## Installation and Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/customer-segmentation-clustering.git
    ```
2. Open the Jupyter notebook to run the analysis:
    ```bash
    jupyter notebook Customer_Segmentation_K-Means_Clustering.ipynb
    ```
3. Review the dataset and presentation as needed.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, feel free to open an issue or a pull request.
