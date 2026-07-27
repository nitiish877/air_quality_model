# Air Quality Prediction — From Scratch to Linear Regression

- This project was built to understand **how Linear Regression works internally** by implementing it from scratch and comparing its performance with Scikit-learn and Random Forest.

## What This Project Covers

- Implemented **Linear Regression from scratch**
- Trained the model using the **Normal Equation**
- Cleaned and preprocessed the Air Quality dataset
- Performed correlation analysis
- Split the dataset into training and testing sets
- Compared the custom implementation with Scikit-learn's Linear Regression
- Trained a Random Forest Regressor for performance comparison
- Evaluated both models using cross-validation
- Analysed prediction errors using residual plots


## Dataset

The project uses the **UCI Air Quality Dataset**.

**Target Variable**

- C6H6(GT)


- All remaining columns are used as input features.


## Project Workflow


- Dataset
-     │

- Data Cleaning
-     │

- Correlation Analysis
-     │

- Train-Test Split
-     │
-     ├───────────────┐

- Custom LR      Scikit-learn LR
-     │               │
-     └──────Compare──┘
-             │

-      Random Forest
-             │

- Cross Validation
-             │

- Residual Analysis


## Custom Linear Regression

- The core part of this project is the custom implementation of Linear Regression.

- The implementation includes:

- Adding the bias term
- Applying the Normal Equation
- Computing model parameters (θ)
- Building a prediction function
- Calculating the R² score

- This implementation was developed without using Scikit-learn's `LinearRegression` class.


## Model Evaluation

The models are evaluated using:

- R² Score
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Cross-validation score
- Residual plots

The comparison focuses not only on prediction performance but also on understanding model behaviour, generalisation, and how closely the custom implementation matches Scikit-learn's results.

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
