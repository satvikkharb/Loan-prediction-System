# Loan Prediction Model

## Introduction
In finance, a loan is the lending of money by one or more individuals, organizations, or other entities to other individuals, organizations, etc. The recipient (i.e., the borrower) incurs a debt and is usually liable to pay interest on that debt until it is repaid as well as to repay the principal amount borrowed. The major aim of this notebook is to predict which of the customers will have their loan approved.

## Data Overview
This dataset is named Loan Prediction Dataset and contains a set of 613 records under 13 attributes:

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (target variable)

## Libraries Used
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Exploratory Data Analysis (EDA)
The notebook begins with loading the dataset and performing exploratory data analysis (EDA) to understand the data's characteristics, including its structure, summary statistics, and missing values.

## Data Preprocessing
Data preprocessing steps include handling missing values, outliers detection and handling, converting categorical variables into numerical ones, and preparing the data for modeling.

## Model Building
The machine learning model, Logistic Regression, is built to predict loan approvals based on the provided features. The model's performance is evaluated using accuracy score and classification report metrics.

## Instructions for Running the Code
1. Ensure all required libraries are installed (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`).
2. Download the dataset `LoanData.csv`.
3. Open the Jupyter notebook `Loan_Prediction_Model.ipynb`.
4. Run each cell in the notebook sequentially to execute the code.
5. Input any new data for prediction into the `model_pred` array and run the corresponding cell to get the loan approval prediction.

## Conclusion
This notebook demonstrates the process of building a machine learning model to predict loan approvals using the Loan Prediction Dataset. The logistic regression model achieved a satisfactory accuracy score in predicting loan approvals based on the provided features.
