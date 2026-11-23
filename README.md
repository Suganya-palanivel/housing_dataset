California Housing Price Prediction using Linear Regression

1. Overview

This project implements a Machine Learning model to predict median house values in California using the California Housing dataset. The project follows an end-to-end Machine Learning workflow, including data loading, data preprocessing, exploratory data analysis (EDA), data visualization, model training, evaluation, and interpretation.

The objective is to understand how different housing and demographic features influence median house values and to build a predictive model using Linear Regression.

This project is developed as a beginner-friendly introduction to regression-based Machine Learning.

2. Objectives

Understand and explore the California Housing dataset.

Perform data cleaning and preprocessing.

Conduct Exploratory Data Analysis (EDA).

Visualize feature distributions and relationships.

Identify correlations between features and the target variable.

Split the dataset into training and testing sets.

Implement a Linear Regression model.

Evaluate model performance using regression metrics.

Visualize actual versus predicted values.

Analyse residuals and model errors.

Interpret model coefficients and feature importance.

Save the trained Machine Learning model.

3. Technologies Used
Programming Language: Python

Development Environment: Jupyter Notebook

Data Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn

4. Project Workflow
Import required libraries.

Load the California Housing dataset.

Understand dataset structure and features.

Perform data quality checks.

Clean and prepare the dataset.

Conduct Exploratory Data Analysis (EDA).

Visualize feature distributions and relationships.

Analyse correlations.

Separate input features and target variable.

Split data into training and testing sets.

Perform feature scaling.

Build and train the Linear Regression model.

Generate predictions.

Evaluate model performance.

Visualize predictions and residuals.

Interpret model coefficients.

Perform cross-validation.

Save the trained model.

5. Algorithm Used
Linear Regression
Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values.

In this project, Multiple Linear Regression is used because the model considers multiple independent variables to predict the target variable.

The model estimates the relationship between input features and the target value by minimizing the sum of squared differences between actual and predicted values.

6. Dataset Description
The California Housing dataset contains information about housing districts in California based on the 1990 U.S. Census.

Dataset Details
Number of records: 20,640

Number of features: 8 input features

Target variable: MedHouseVal

Problem type: Regression

Input Features
Feature	Description
MedInc	Median income of households in a district
HouseAge	Median house age
AveRooms	Average number of rooms
AveBedrms	Average number of bedrooms
Population	District population
AveOccup	Average household occupancy
Latitude	Geographic latitude
Longitude	Geographic longitude
7. Target Variable
MedHouseVal
The target variable is MedHouseVal, which represents the median house value for a California housing district.

The values are expressed in units of $100,000.

For example:

1.0 represents $100,000

2.0 represents $200,000

3.5 represents $350,000

The model uses the eight input features to predict this continuous numerical value.

8. Data Preparation
The following preprocessing steps are performed:

Checking missing values.

Checking duplicate records.

Checking data types.

Checking infinite values.

Removing duplicate records if present.

Separating input features and target variable.

Splitting data into training and testing sets.

Standardizing numerical features using StandardScaler.

The dataset is divided into:

80% Training Data: Used to train the model.

20% Testing Data: Used to evaluate the model on unseen data.

Feature scaling is implemented using a Scikit-learn Pipeline to prevent data leakage.

9. Exploratory Data Analysis and Visualization
The project includes the following analyses:

Dataset structure and summary statistics.

Target variable distribution.

Feature distributions.

Correlation heatmap.

Feature versus target scatter plots.

Boxplots for outlier analysis.

Actual versus predicted visualization.

Residual distribution.

Residuals versus predicted values.

Q-Q plot of residuals.

These visualizations help understand the data, identify patterns, and evaluate the model's performance.

10. Model Evaluation
The Linear Regression model is evaluated using the following metrics:

Mean Absolute Error (MAE)
Measures the average absolute difference between actual and predicted values.

Mean Squared Error (MSE)
Measures the average squared prediction error and penalizes larger errors more heavily.

Root Mean Squared Error (RMSE)
The square root of MSE. It represents prediction error in the same unit as the target variable.

R-squared (R²)
Measures the proportion of variation in the target variable explained by the model.

Cross-Validation
Five-fold cross-validation is used to evaluate model stability and consistency across different training and validation subsets.

11. Model Interpretation
The project analyses:

Linear Regression coefficients.

Positive and negative feature relationships.

Feature importance using permutation importance.

Actual versus predicted values.

Residual patterns.

Model performance on training and testing datasets.

The results help identify which features contribute most to the model's predictive performance.

Feature relationships are interpreted as associations and not as proof of causation.

12. Expected Outcome
The expected outcome of this project is a trained Linear Regression model capable of predicting median house values based on housing and demographic features.

The project demonstrates:

A complete Machine Learning workflow.

Data preprocessing and feature scaling.

Exploratory Data Analysis.

Regression model implementation.

Model evaluation and interpretation.

Prediction on unseen data.

Model saving and reuse.

15. Conclusion
This project demonstrates the implementation of Linear Regression for predicting California housing values. It covers the complete Machine Learning lifecycle, from data preparation and exploratory analysis to model training, evaluation, visualization, and interpretation.

The trained Linear Regression model serves as a baseline for understanding regression problems and for comparing the performance of more advanced Machine Learning algorithms in future experiments.
