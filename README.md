
                                                                           SIMPLE LINEAR REGRESSION AND MULTIPLE LINEAR REGRESSION

1. **# Simple Linear Regression - Salary Prediction
**
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





2. **# Multiple Linear Regression - House Price Prediction**

This project demonstrates how to implement a **Multiple Linear Regression** model to predict house prices using features such as total bedrooms, population, and total rooms.

##  Dataset

The dataset used (`housing.csv`) includes features like:

- Total Rooms
- Total Bedrooms
- Population
- Median House Value (target variable)

##  Objective

To predict the **median house value** using multiple input features and evaluate the accuracy of predictions.

##  Steps Performed

1. Load and inspect the dataset
2. Handle missing values in training and test splits
3. Visualize data relationships:
   - Pairplot
   - Correlation heatmap
   - Scatter plots
4. Split dataset into training and testing sets
5. Train a multiple linear regression model
6. Evaluate using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
7. Visualize relationships between input and output variables

##  Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

##  Evaluation Metrics

- **R² Score**: Model performance
- **MAE**: Error magnitude
- **MSE**: Squared error average

##  Visualizations

- Pairplot of numerical features
- Heatmap of correlations
- Scatter plots for feature vs target


