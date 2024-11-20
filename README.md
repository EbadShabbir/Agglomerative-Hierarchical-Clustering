# Mall Customer Segmentation using Hierarchical Clustering

This project demonstrates customer segmentation using hierarchical clustering. By analyzing the annual income and spending scores of mall customers, the project identifies distinct customer groups for targeted marketing strategies.

---

## Project Overview

The goal of this project is to segment mall customers into clusters based on their spending behavior and income levels. Hierarchical clustering, specifically using Ward's linkage method, is applied to discover meaningful patterns in the data.

---

## Dataset Description

The analysis uses the **Mall Customers Dataset**, which contains information about 200 mall customers. Key attributes include:
- `Annual Income (k$)` - The yearly income of the customer.
- `Spending Score (1-100)` - A score assigned based on customer purchasing behavior.

---

## Approach

### 1. Exploratory Data Analysis
Initial exploration of the dataset ensures data quality and identifies key trends.

### 2. Optimal Number of Clusters
A **dendrogram** is used to determine the optimal number of clusters based on the dataset's hierarchical structure.

### 3. Clustering with Agglomerative Clustering
The customers are grouped into 5 clusters using the **Agglomerative Clustering** algorithm, leveraging Euclidean distance as a metric.

### 4. Visualization
Scatter plots illustrate the clusters, showing clear segmentation based on the features.

---

## Key Results

- **Cluster Insights**: The clustering model identified groups of customers with varying income levels and spending patterns, helping to distinguish high-spending customers from others.
- **Dendrogram Analysis**: The dendrogram helped confirm that 5 clusters provided an optimal representation of the data.

---

## Libraries and Tools Used

- **Python Libraries**:
  - `numpy`
  - `matplotlib`
  - `pandas`
  - `scipy`
  - `sklearn`
- **Tools**: Jupyter Notebook or Kaggle Notebook for implementation and visualization.

---

## How to Run the Project

1. Clone this repository to your local machine.
2. Download the **Mall Customers Dataset** from [Kaggle](https://www.kaggle.com/shwetabh123/mall-customers).
3. Ensure all required libraries are installed (`numpy`, `pandas`, etc.).
4. Follow the steps outlined in the notebook to replicate the analysis.

---

## Future Improvements

- Integrate additional customer features such as demographics or transaction history.
- Experiment with other clustering techniques like K-Means or DBSCAN.
- Automate the optimal cluster determination process.

---

## References

- [Kaggle: Mall Customers Dataset](https://www.kaggle.com/shwetabh123/mall-customers)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

---

## Acknowledgments

Special thanks to the creators of the Mall Customers Dataset and the developers of Scikit-learn and Matplotlib for their tools and resources.
