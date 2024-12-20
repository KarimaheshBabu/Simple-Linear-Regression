# Simple-Linear-Regression
#### Explanation of the Code

1. Libraries:We import necessary libraries like numpy, pandas, sklearn, and matplotlib.
3. Data Preparation:We create a DataFrame containing the size and price of houses.
5. Feature and Target: We separate the feature (Size) and the target (Price).
8. Train-Test Split: We split the data into training and testing sets.
9. Model Training: We create a LinearRegression model and train it using the training data.
10. Predictions: We use the trained model to predict house prices for the test set.
11. Evaluation: We evaluate the model using Mean Squared Error (MSE) and R-squared (R²) metrics.
12. Visualization: We plot the original data points and the regression line to visualize the model's performance.

#### Evaluation Metrics

- Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted values. Lower values indicate better performance.
- R-squared (R²): Represents the proportion of the variance in the dependent variable that is predictable from the independent variable(s). Values closer to 1 indicate a better fit.
