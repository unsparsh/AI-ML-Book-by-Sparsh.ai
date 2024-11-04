
# Day 6: Supervised Learning Algorithms - Decision Trees and k-Nearest Neighbors (k-NN)

## Learning Objectives
1. Understand the working principles of Decision Trees and k-Nearest Neighbors.
2. Recognize how each algorithm can be applied in different scenarios.

---

## Content

### 1. Decision Trees
- **Concept**: Decision trees classify data by splitting it into branches based on certain conditions, like a flowchart. Each branch represents a choice, leading to a final prediction.

- **How It Works**:
  - The tree starts with a root node (main question) and splits data based on answers (conditions) at each node.
  - Each split tries to reduce "impurity" (uncertainty), making the groups in each branch more alike.

- **Example**: Imagine a tree that predicts if a person likes a certain fruit. The root node could ask, “Does the person prefer sweet fruits?” Depending on the answer (yes or no), it may then ask about texture or size, continuing until a conclusion is reached.

- **Advantages**:
  - Easy to understand and visualize.
  - Works well with both numerical and categorical data.

### 2. k-Nearest Neighbors (k-NN)
- **Concept**: k-NN is a simple algorithm that classifies data points based on their “neighbors.” It checks the 'k' closest data points and assigns the class that most of these neighbors belong to.

- **How It Works**:
  - Choose a value for 'k' (e.g., 3).
  - Find the 3 nearest points (neighbors) to the new data point.
  - Assign the most common class among these neighbors to the new data point.

- **Example**: If you're trying to predict if a movie is an action movie, k-NN could look at the three movies most similar to it. If two of the three are action movies, the new movie will be classified as action.

- **Limitations**:
  - k-NN can be slow with large datasets, as it calculates the distance to every point.
  - Choosing the right value for 'k' is essential; too small or too large 'k' values can lead to errors.

### Choosing Between Decision Trees and k-NN
- **Decision Trees**: Useful for interpretability, as each path can be explained as a series of rules.
- **k-NN**: Effective when data is clustered or when there's a need for flexibility without assumptions.

---

### Exercise
1. **Decision Tree Practice**: Use a decision tree to classify a dataset (e.g., predicting if a person will enjoy a movie based on age and genre preference).
2. **k-NN Practice**: Use k-NN to classify a dataset (e.g., predicting if a person will buy a product based on similar customer data). Experiment with different values of 'k'.
