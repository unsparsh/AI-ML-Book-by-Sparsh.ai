
# Day 7: Supervised Learning Algorithms - Support Vector Machines (SVM) and Ensemble Methods

## Learning Objectives
1. Understand how Support Vector Machines work and when to use them.
2. Learn about ensemble methods and how they improve model accuracy.

---

## Content

### 1. Support Vector Machines (SVM)
- **Concept**: SVM is a classification algorithm that finds a "hyperplane" that best separates the classes in the data. It tries to maximize the margin (distance) between classes, which helps it make accurate predictions.

- **How It Works**:
  - SVM places a line (or hyperplane) that best divides data points of one class from another.
  - The algorithm tries to find the line that has the maximum distance from the closest points of each class, which are called "support vectors."

- **Example**: Imagine trying to separate dogs from cats based on weight and height. SVM will find the line that best divides dogs from cats with the largest margin possible.

- **Kernel Trick**: SVM can handle complex data using a technique called the "kernel trick," which allows it to create non-linear boundaries for complex datasets.

### 2. Ensemble Methods
- **Concept**: Ensemble methods combine multiple models to improve accuracy. The idea is that a group of models working together will often be better than any single model alone.

- **Types of Ensemble Methods**:
  - **Bagging (Bootstrap Aggregating)**: Creates multiple models from different subsets of data and averages the results.
    - **Example**: Random Forest is a popular bagging method that builds multiple decision trees and combines their results.
  - **Boosting**: Trains models sequentially, where each model focuses on correcting errors from the previous one.
    - **Example**: Gradient Boosting and AdaBoost are popular boosting methods.

- **Why Use Ensemble Methods**:
  - They help reduce overfitting and improve performance, especially on complex datasets.
  - By combining models, they often perform better and are more robust than single models.

### Choosing Between SVM and Ensemble Methods
- **SVM**: Best for clear boundaries and lower-dimensional data. It’s effective in binary classification and works well with complex relationships (using kernels).
- **Ensemble Methods**: Ideal for high-dimensional and complex datasets, providing robust and accurate predictions.

---

### Exercise
1. **SVM Practice**: Use SVM on a classification dataset (e.g., predicting if a person has a certain disease based on symptoms).
2. **Ensemble Method Practice**: Implement a Random Forest model on a dataset (e.g., predicting house prices) and compare its accuracy with a single decision tree.
