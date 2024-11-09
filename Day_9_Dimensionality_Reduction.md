
# Day 9: Dimensionality Reduction Techniques - PCA and t-SNE

## Learning Objectives
1. Understand the need for dimensionality reduction.
2. Learn about PCA (Principal Component Analysis) and t-SNE for reducing data dimensions.

---

## Content

### 1. Why Dimensionality Reduction?
- **Concept**: Dimensionality reduction simplifies datasets by reducing the number of features while preserving important patterns.
- **Benefits**: Helps speed up training, reduces overfitting, and makes data visualization possible.

### 2. Principal Component Analysis (PCA)
- **Concept**: PCA transforms features into a set of orthogonal (independent) components, prioritizing those with the most variance.
- **How It Works**: PCA projects data onto the axes that capture maximum variance, producing fewer dimensions without much information loss.
- **Example**: Reducing customer features from 10 dimensions to 2, visualizing their distribution in 2D space.

### 3. t-SNE (t-Distributed Stochastic Neighbor Embedding)
- **Concept**: t-SNE focuses on visualizing high-dimensional data by clustering similar points together in a lower dimension.
- **Example**: Visualizing handwritten digits in a 2D plot to observe clusters of similar digits.

---

### Exercise
1. **PCA Practice**: Apply PCA on a high-dimensional dataset, such as Iris, and visualize it in 2D.
2. **t-SNE Practice**: Use t-SNE on the same dataset to compare the clustering result with PCA.
