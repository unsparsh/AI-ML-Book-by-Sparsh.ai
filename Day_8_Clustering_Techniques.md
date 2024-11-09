
# Day 8: Introduction to Unsupervised Learning - Clustering Techniques (K-Means and Hierarchical Clustering)

## Learning Objectives
1. Understand the difference between supervised and unsupervised learning.
2. Learn about clustering and how it’s used to find patterns in unlabeled data.

---

## Content

### 1. What is Unsupervised Learning?
- **Concept**: Unsupervised learning finds patterns in data without predefined labels or outputs. It’s often used for exploring data and identifying natural groupings or clusters.

- **Common Use Cases**: Clustering, dimensionality reduction, and anomaly detection.

### 2. K-Means Clustering
- **Concept**: K-Means is a simple and popular clustering method. It groups data points into a specified number of clusters, where each cluster has a "centroid" (center point) that represents it.

- **How It Works**:
  1. Choose the number of clusters, 'k'.
  2. Randomly assign initial centroids for each cluster.
  3. Assign each data point to the nearest centroid.
  4. Update the centroids based on the current points in each cluster.
  5. Repeat steps 3-4 until centroids no longer move significantly.

- **Example**: Suppose you have data about customer spending. K-Means can help group customers into clusters, such as "low spenders," "average spenders," and "high spenders."

### 3. Hierarchical Clustering
- **Concept**: Hierarchical clustering builds a "tree" of clusters, where similar data points are merged step-by-step.

- **How It Works**:
  1. Start with each data point as its own cluster.
  2. Merge the closest clusters together.
  3. Repeat until only one cluster remains or the desired number of clusters is reached.

- **Types of Hierarchical Clustering**:
  - **Agglomerative**: Bottom-up approach where each point starts as its own cluster and merges upwards.
  - **Divisive**: Top-down approach where all data points start in one cluster and are split.

### Choosing Between K-Means and Hierarchical Clustering
- **K-Means**: Best for a known number of clusters, fast and scalable for large datasets.
- **Hierarchical Clustering**: Useful for exploring the hierarchy of clusters, works better with smaller datasets.

---

### Exercise
1. **K-Means Practice**: Use K-Means on a dataset (e.g., customer spending data) to form clusters and interpret them.
2. **Hierarchical Clustering Practice**: Perform hierarchical clustering on a small dataset and create a dendrogram (tree diagram) to visualize the clustering hierarchy.
