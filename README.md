# Simple Linear Regression - Salary Prediction

This project demonstrates how to implement and evaluate a **Simple Linear Regression** model using Python and scikit-learn. It predicts salary based on years of experience.

##  Dataset

The dataset used (`Salary_dataset.csv`) contains:

- **YearsExperience**: Number of years of experience
- **Salary**: Salary in currency units

##  Objective

To model the linear relationship between experience and salary using a simple regression algorithm.

## Steps Performed

1. Load and inspect the dataset
2. Visualize data relationships using pairplot and heatmap
3. Plot scatter graph of input vs output
4. Split dataset into training and testing sets
5. Train a simple linear regression model
6. Evaluate performance using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
7. Visualize test predictions

##  Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

##  Evaluation Metrics

- **R² Score**: Measures how well the regression predictions approximate the real data.
- **MAE**: Measures the average magnitude of the errors.
- **MSE**: Squares the errors, giving more weight to large ones.

##  Visualization

- Scatter plot of `YearsExperience` vs `Salary`
- Regression line overlay on test data
