

# KMeans from Scratch

**Repository:** [xgagandeep/KMeans-from-scratch](https://github.com/xgagandeep/KMeans-from-scratch)  
**Date:** 2020  
**Language:** Python  
**Libraries:** NumPy, Matplotlib, Scikit-learn

## Description

This project implements the KMeans clustering algorithm from scratch using Python. The notebook demonstrates how to perform clustering on synthetic data generated using the `make_blobs` function from Scikit-learn. The implementation includes initializing clusters, assigning points to clusters, updating cluster centers, and visualizing the results.

## Features

- **Synthetic Data Generation:** Uses Scikit-learn's `make_blobs` to generate synthetic datasets with specified number of clusters.
- **Cluster Initialization:** Randomly initializes cluster centers.
- **Distance Calculation:** Computes Euclidean distance between points and cluster centers.
- **Cluster Assignment:** Assigns each point to the nearest cluster center.
- **Cluster Update:** Updates cluster centers based on the mean of assigned points.
- **Visualization:** Plots clusters and their centers to visualize the clustering process.

## Files

- **`Kmeans.ipynb`:** Jupyter Notebook containing the implementation of the KMeans clustering algorithm from scratch.

## Installation

To run this project, you need Python and the required libraries installed. Follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/xgagandeep/KMeans-from-scratch.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd KMeans-from-scratch
   ```

3. **Install the required libraries:**

   ```bash
   pip install numpy matplotlib scikit-learn
   ```

4. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook Kmeans.ipynb
   ```

## Usage

1. **Data Generation:** Generates synthetic data with `make_blobs`.
2. **Cluster Initialization:** Initializes clusters with random centers.
3. **Clustering Process:**
   - Assign points to clusters based on the nearest center.
   - Update cluster centers to the mean of the assigned points.
   - Repeat the assignment and update steps until convergence.
4. **Visualization:** Plots clusters and their centers to show the clustering process.

## Functions

- `distance(v1, v2)`: Computes the Euclidean distance between two points.
- `assignPointsToClusters(clusters)`: Assigns each point to the nearest cluster.
- `updateClusters(clusters)`: Updates the center of each cluster based on the mean of assigned points.
- `plotClusters(clusters)`: Visualizes the clusters and their centers.

## Performance

- **Initialization:** Randomly initializes cluster centers.
- **Iteration:** Repeats the assignment and update steps until convergence.
- **Visualization:** Provides visual feedback of the clustering process and final cluster centers.

## Contribution

Feel free to contribute to this project by submitting issues or pull requests. For any questions or feedback, please open an issue on the GitHub repository.
