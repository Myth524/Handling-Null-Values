# Handling-Null-Values

## Description
This project aims to explore and address missing values in the NHANES (National Health and Nutrition Examination Survey) database. NHANES provides health and nutrition data for the U.S. population, but like many real-world datasets, it contains missing values that need to be properly handled for robust analysis.

## The project focuses on:

- **Identification of Missing Values:** Locating and analyzing the amount and distribution of missing values across the various variables in the dataset.

- **Classification of Missing Value Types:** Distinguishing between different types of missing values (completely random, conditionally random, or non-random) to understand their possible causes.

- **Correlation Analysis:** Evaluating correlations between variables to determine if missing values in one variable are related to others, which can help in selecting the best imputation strategies.

- **Methods for Handling Missing Values:** Exploring various imputation techniques to address missing values, comparing their effectiveness using machine learning models such as:
  - Decision Tree
  - Simple Perceptron Neural Network
  - K-means
  - Random Forest
- **Imputation Evaluation:** Using evaluation metrics like model accuracy, mean squared error (MSE), and cross-validation to determine which imputation method provides the best performance on the NHANES dataset.

## **Technologies Used:**
- **Python:** Main programming language for data analysis and model development.
- **Pandas and NumPy:** Libraries for data manipulation and analysis.
- **Scikit-learn:** Implementation of imputation models and machine learning techniques.
- **Matplotlib & Seaborn:** Visualization tools to analyze data patterns and correlations.
