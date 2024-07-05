# Cryptocurrency Clustering using K-Means and PCA

#### Overview:
This code demonstrates how to cluster cryptocurrencies based on their market data using two approaches: K-Means clustering on original features and K-Means clustering on PCA-transformed features.

#### Steps:

1. **Data Preparation:**
   - Load cryptocurrency market data from a CSV file.
   - Standardize the data using `StandardScaler()`.

2. **Original Data Clustering:**
   - Perform K-Means clustering on the standardized data to identify clusters.
   - Plot an Elbow curve to determine the optimal number of clusters (`k`).
   - Visualize the clusters using scatter plots colored by cluster labels.

3. **PCA Transformation:**
   - Apply Principal Component Analysis (PCA) to reduce the dimensionality of the data.
   - Plot another Elbow curve to determine the optimal number of clusters (`k`) for PCA-transformed data.

4. **PCA Data Clustering:**
   - Perform K-Means clustering on the PCA-transformed data to identify clusters.
   - Visualize the clusters using scatter plots colored by cluster labels.

#### Code Files:
- **`cryptocurrency_clustering.py`**: Contains the main code for clustering cryptocurrencies.
  - Loads data, preprocesses using `StandardScaler`, and performs K-Means clustering.
  - Utilizes PCA for dimensionality reduction and compares clustering results.
  - Generates visualizations using `hvplot` for interactive plots.

#### Requirements:
- Python 3.x
- Required Python packages: `pandas`, `scikit-learn`, `hvplot`

#### Usage:
1. Ensure Python and required packages are installed.
2. Run `cryptocurrency_clustering.py`.
3. View interactive visualizations of clustering results.

#### Notes:
- Adjust `k` values and visualization parameters as needed.
- Experiment with different clustering algorithms or additional features for improved clustering accuracy.

---

This README provides a concise overview of the code functionality, its purpose, and how to use it. It also highlights key steps and considerations for clustering cryptocurrencies using K-Means and PCA. Adjustments can be made based on specific requirements or further exploration of the data.