
# Day 4: Model Evaluation Metrics

## Learning Objectives
1. Understand the importance of model evaluation.
2. Learn different metrics for evaluating regression and classification models.

---

## Content

### 1. Why Model Evaluation is Important
- **Concept**: Model evaluation metrics allow us to understand how well a model is performing. Choosing the right metric depends on the problem type (regression vs classification) and the business objective.

- **Train-Test Split**: The data is split into a training set to build the model and a test set to evaluate its performance. A common split is 80% training and 20% testing.

### 2. Regression Metrics
- **Mean Absolute Error (MAE)**: Measures the average magnitude of errors in predictions without considering their direction.
  - **Formula**: \( \text{MAE} = \frac{1}{n} \sum_{i=1}^{n} |y_i - \hat{y}_i| \)
  - **Interpretation**: Lower MAE values indicate a better model.
  
- **Mean Squared Error (MSE)**: Similar to MAE but penalizes larger errors more heavily by squaring them.
  - **Formula**: \( \text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2 \)
  
- **R-squared (R^2)**: Represents the proportion of variance in the dependent variable explained by the independent variables.
  - **Formula**: \( R^2 = 1 - \frac{\text{SS}_{\text{res}}}{\text{SS}_{\text{tot}}} \)
  - **Interpretation**: R^2 values closer to 1 indicate a good model.

### 3. Classification Metrics
- **Accuracy**: Measures the percentage of correct predictions out of total predictions.
  - **Formula**: \( \text{Accuracy} = \frac{\text{True Positives} + \text{True Negatives}}{\text{Total Predictions}} \)
  
- **Precision**: Measures the proportion of positive predictions that were correct.
  - **Formula**: \( \text{Precision} = \frac{\text{True Positives}}{\text{True Positives} + \text{False Positives}} \)
  
- **Recall (Sensitivity)**: Measures the proportion of actual positives that were correctly identified.
  - **Formula**: \( \text{Recall} = \frac{\text{True Positives}}{\text{True Positives} + \text{False Negatives}} \)
  
- **F1 Score**: The harmonic mean of precision and recall, balancing the two metrics.
  - **Formula**: \( \text{F1 Score} = 2 \times \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}} \)

### Choosing the Right Metric
- **Classification**: For balanced datasets, accuracy may be sufficient, but for imbalanced datasets, precision, recall, or F1 score are more informative.
- **Regression**: MSE is useful when penalizing large errors, while MAE is better when all errors should contribute equally.

---

### Exercise
1. **Regression Model Evaluation**: Calculate MAE, MSE, and R^2 for a regression model using a dataset (e.g., predicting house prices).
2. **Classification Model Evaluation**: Calculate accuracy, precision, recall, and F1 score for a classification model, such as predicting spam emails.
