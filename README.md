Project Overview

The Loan Eligibility Predictor is a machine learning–based analytics project designed to predict whether a loan applicant is likely to be approved based on multiple financial and demographic factors.
This project demonstrates skills in data analysis, preprocessing, model building, and evaluation — valuable for finance and data science portfolios.

 Dataset Details

A synthetic dataset (loan_data_synthetic.csv) was generated to closely resemble real-world bank loan data.
It contains 614 records and 12 columns.

Feature	Description
Gender	Male / Female
Married	Applicant’s marital status
Dependents	Number of dependents (0,1,2,3+)
Education	Graduate / Not Graduate
Self_Employed	Whether applicant is self-employed
ApplicantIncome	Applicant’s monthly income
CoapplicantIncome	Co-applicant’s income
LoanAmount	Loan amount (in thousands)
Loan_Amount_Term	Loan duration (in days)
Credit_History	Credit score history (1 = good, 0 = poor)
Property_Area	Urban / Rural / Semiurban
Loan_Status	Target variable (Y = approved, N = not approved)
 Project Workflow:-

Data Preprocessing

Handled missing values with median and mode imputation.

Encoded categorical variables using Label Encoding.

Standardized numerical features for uniform scaling.

Exploratory Data Analysis.

Distribution plots for key numeric features (ApplicantIncome, LoanAmount).

Correlation heatmap to understand feature relationships.

Model Building

Models used:

Logistic Regression

Random Forest Classifier

Evaluation Metrics:

Accuracy is measured through Confusion Matrix.

ROC–AUC Curve is generated.

Results:-

Both models were trained and evaluated.

Random Forest achieved the best accuracy among tested models.

Key Visualizations:-

applicant_income_hist.png – Income distribution

loan_amount_hist.png – Loan amount distribution

correlation_heatmap.png – Correlation matrix of all features

confusion_matrix.png – Model confusion matrix

roc_curve.png – ROC curve showing model performance
