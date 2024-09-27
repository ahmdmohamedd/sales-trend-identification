# Sales Trend Identification

## Overview

The **Sales Trend Identification** project aims to analyze and identify trends in sales data using clustering algorithms. Two different clustering techniques, **K-Means** and **DBSCAN**, are implemented to explore customer behavior based on their annual income and spending score.

## Purpose

Understanding customer segments is crucial for businesses to tailor their marketing strategies, enhance customer satisfaction, and drive sales. This project applies two popular clustering algorithms to uncover these segments within the dataset.

## Dataset

The dataset used for this project is the **Mall Customers** dataset, which contains information about customers in a shopping mall, including:
- Customer ID
- Gender
- Age
- Annual Income (in thousands of dollars)
- Spending Score (1-100)

The dataset can be accessed directly in the notebooks.

## Algorithms

1. **K-Means Clustering**
   - A simple yet powerful clustering technique that partitions the dataset into `k` clusters based on the mean distance of points to the cluster centroids.
   - **Notebook**: `kmeans_cluster.ipynb`

2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
   - A more advanced clustering method that identifies clusters based on the density of points and can effectively handle noise in the data.
   - **Notebook**: `DBSCAN_cluster.ipynb`

## Requirements

To run the Jupyter notebooks, you'll need the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How to Use

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/ahmdmohamedd/sales-trend-identification.git
   cd sales-trend-identification
   ```

2. Open the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

3. Run the notebooks to explore the clustering results and visualizations.

## Acknowledgments

- The dataset used in this project is from [Mall Customers dataset](https://raw.githubusercontent.com/mallcustomers/Mall_Customers/main/Mall_Customers.csv).
- Special thanks to the creators of the libraries used for clustering and data visualization.
