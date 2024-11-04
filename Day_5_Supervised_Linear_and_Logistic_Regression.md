
# Day 5: Supervised Learning Algorithms - Linear Regression and Logistic Regression

## Learning Objectives
1. Understand how Linear Regression and Logistic Regression work.
2. Know when to use each algorithm based on the type of data and prediction goals.

---

## Content

### 1. Linear Regression
- **Concept**: Linear regression is a method to predict a continuous (numeric) output. It finds the best-fitting line through the data points to predict future values.

- **Mathematical Explanation**: Linear regression tries to find a line represented by the equation \( y = mx + b \), where \( m \) is the slope and \( b \) is the y-intercept.
  - The model tries to minimize the distance between each data point and the line, which is called minimizing the "error."

- **Example**: Suppose you want to predict a person’s weight based on their height. If you have a dataset with heights and weights, linear regression finds a line that can be used to predict the weight for any given height.

- **Cost Function (Mean Squared Error)**: Measures how well the line fits the data by calculating the average squared distance between the predicted and actual values.

### 2. Logistic Regression
- **Concept**: Logistic regression is used for binary classification (predicting categories like “yes” or “no,” “spam” or “not spam”). Instead of predicting a value, it predicts the probability of belonging to a particular class.

- **Mathematical Explanation**:
  - The logistic regression model applies a transformation (sigmoid function) to make predictions that fall between 0 and 1, representing probabilities.
  - The sigmoid function is defined as \( \sigma(x) = \frac{1}{1 + e^{-x}} \). Values close to 0 represent one class, and values close to 1 represent the other.

- **Example**: Logistic regression could help predict if a person will click on an ad based on their browsing history. Here, it would output probabilities, like a 70% chance of clicking or a 30% chance of not clicking.

### Choosing Between Linear and Logistic Regression
- Use **Linear Regression** for predicting continuous values (e.g., temperature, stock price).
- Use **Logistic Regression** for predicting categories (e.g., spam or not spam, disease or no disease).

---

### Exercise
1. **Linear Regression Practice**: Create a linear regression model using a simple dataset (e.g., height and weight data) to predict weight based on height.
2. **Logistic Regression Practice**: Create a logistic regression model on a dataset (e.g., predicting if a student will pass or fail based on study hours) and interpret the probabilities it provides.
