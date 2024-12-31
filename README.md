# SCT_ML_01
House price prediction using linear regression 
# K-Means Clustering for Customer Segmentation

This project implements a K-Means clustering algorithm to group customers of a retail store based on their purchase history. The clustering is performed using features like annual income and spending score.

## Features

1. **Data Preparation**:
   - A sample dataset with `CustomerID`, `AnnualIncome`, and `SpendingScore` is used for clustering.
   - Clustering features include:
     - Annual Income (in $1000s)
     - Spending Score (1-100 scale)

2. **K-Means Clustering**:
   - Utilizes scikit-learn's `KMeans` to cluster customers into 3 groups.
   - Cluster centroids are computed for visualization.

3. **Visualization**:
   - Scatter plot displays clusters with distinct colors.
   - Centroids are highlighted in red.

4. **Output**:
   - Cluster assignments are added as a new column to the dataset.
   - Final DataFrame is printed with cluster labels.

## Prerequisites

- Python 3.x
- Required libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`

Install dependencies using:
```bash
pip install numpy pandas scikit-learn matplotlib
```

## Running the Script

1. Clone or download the script.
2. Ensure the dependencies are installed.
3. Execute the script in a Python environment:
   ```bash
   python kmeans_customer_clustering.py
   ```
4. The scatter plot will display the clusters, and the terminal will print the dataset with cluster labels.

## Results

- Visualizes customer groups based on purchase behavior.
- Highlights cluster centroids for better understanding of grouping.

## Use Cases

- Customer segmentation for personalized marketing.
- Identifying spending patterns in different income groups.
- Enhancing customer relationship management (CRM).

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.
