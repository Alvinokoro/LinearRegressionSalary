Salary Prediction Model
Overview
This project implements a univariate linear regression model to predict salary based on years of experience. The model is built from scratch using gradient descent optimization with regularization.
Dataset

The dataset contains two main features:
YearsExperience: Number of years of professional experience
Salary: Annual salary in dollars

Implementation Details:-
Data Preprocessing:
Loaded and examined the dataset for missing values
Split the data into training (80%) and testing (20%) sets using scikit-learn
Visualized the data to confirm the linear relationship between experience and salary

Model Development:
The linear regression model includes the following components:

Model function: f(x) = wx + b
Cost function with L2 regularization
Gradient descent optimization algorithm
Learning rate adjustment
Parameter initialization and regularization control

Key Functions:

model(): Computes predictions based on input features
compute_cost(): Calculates the cost with L2 regularization
compute_gradient(): Computes gradients for weight and bias updates
gradient_descent(): Implements the optimization algorithm
predict_salary(): Makes salary predictions for given years of experience

Visualization

Scatter plot of the original dataset
Model prediction plot showing the fitted line
Learning curve to monitor convergence during training

Evaluation Metrics

Mean Squared Error (MSE)
R-squared score

Results
The model achieves good predictive performance as indicated by:

Strong correlation between years of experience and salary
High R-squared value on test data
Low MSE on test predictions

Before running, ensure to have necessary libraries.
pip install pandas numpy matplotlib scikit-learn
