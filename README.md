# DECISION-TREE-IMPLEMENTATION

COMPANY: CODTECH IT SOLUTIONS

NAME: ARYA DILIP BHONGALE

INTERN ID:CTIS4921

DOMAIN:MACHINE LEARNING

DURATION:4 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

DESCRIPTION-

Overview-

This project focuses on predicting crop yield (Q/acre) using machine learning techniques. Agricultural productivity is influenced by multiple factors such as rainfall, temperature, fertilizer usage, and soil nutrients. By applying a Decision Tree Regression model, this project aims to analyze these factors and estimate crop yield accurately.

Objective-

The main objective of this project is to:

-Build a machine learning model that predicts crop yield based on environmental and soil parameters

-Analyze which factors have the greatest impact on crop yield

-Visualize model decisions and performance for better understanding and interpretability

-Dataset Description

The dataset used in this project contains the following features:

Input Features:

Rain Fall (mm)
Fertilizer
Temperature
Nitrogen (N)
Phosphorus (P)
Potassium (K)
Target Variable:
Yield (Q/acre)
All features are numerical, making the dataset suitable for regression analysis.

Tools and Technologies Used-

Python – programming language

Scikit-learn – for building and evaluating the machine learning model

Pandas & NumPy – for data handling and preprocessing

Matplotlib – for data and model visualization

Jupyter Notebook – for implementation and analysis

Methodology-

Data Loading and Exploration
The dataset was loaded using Pandas and analyzed to understand its structure, data types, and distribution.

-Data Preprocessing
Converted all columns to numeric values
Handled missing values using mean imputation
Selected relevant features for prediction

-Train–Test Split
The dataset was divided into training and testing sets (80% training, 20% testing) to evaluate model performance on unseen data.

-Model Development
A DecisionTreeRegressor from Scikit-learn was used to model the relationship between agricultural parameters and crop yield.
Model complexity was controlled using parameters like:
max_depth,min_samples_split to prevent overfitting.

-Model Training
The model was trained on the training dataset using the fit() method, where it learned decision rules from the data.

-Prediction and Evaluation
Crop yield was predicted for the test dataset
Model performance was evaluated using error metrics such as:
-Mean Absolute Error (MAE)
-Mean Squared Error (MSE)
-R² score

-Visualization and Analysis

-Visualized the decision tree to understand how predictions are made

-Plotted feature importance to identify influential parameters

-Used graphs such as actual vs predicted yield and yield distribution for performance analysis

What This Project Does??
Predicts crop yield based on rainfall, fertilizer usage, temperature, and soil nutrients
Helps identify key factors affecting agricultural productivity
Provides an interpretable machine learning model that can assist in decision-making for agriculture
Demonstrates practical implementation of decision tree regression using Scikit-learn

Conclusion

The project successfully demonstrates how machine learning can be applied in agriculture for yield prediction. The Decision Tree model provides clear insights into the relationship between environmental factors and crop yield. While the model performs well, future improvements could include using ensemble methods like Random Forest or integrating real-time data such as satellite-based rainfall measurements.

