🚀 Credit Risk Analysis & Default Prediction
This project focuses on predicting the probability of a customer defaulting on a loan using machine learning techniques. By analyzing historical loan data, I developed a model that identifies high-risk applicants with high accuracy.

📊 Project Overview
Objective: To build a robust classification model to predict loan_status (0: Non-default, 1: Default).

Dataset: 32,581 loan applications with 12 financial and demographic features.

Model Performance: Achieved an Accuracy Score of 92.52% using the Random Forest algorithm.

🛠️ Tech Stack
Language: Python

Libraries: * Pandas & NumPy (Data Manipulation)

Scikit-Learn (Machine Learning & Preprocessing)

Seaborn & Matplotlib (Data Visualization)

🔍 Key Stages of the Project
1. Data Cleaning & Preprocessing
Handled missing values (NaN) in loan_int_rate and person_emp_length using Mean Imputation.

Detected and removed outliers/anomalies (e.g., individuals with an age of 144 years or employment length of 123 years).

Converted categorical variables (Loan Grade, Home Ownership, etc.) into numerical format using Label Encoding.

2. Exploratory Data Analysis (EDA)
Analyzed the relationship between Income and Loan Amount.

Visualized the correlation between Loan Grade and Default Rate, confirming that lower grades (E, F, G) significantly increase the risk.

Used Correlation Heatmaps to identify key drivers of loan defaults.

3. Machine Learning Modeling
Split the data into Training (80%) and Testing (20%) sets.

Trained a Random Forest Classifier with 100 decision trees.

Evaluated the model using a classification report, focusing on Precision and Recall for high-risk customers.

💡 Business Insights
The model revealed that the most influential factors in predicting default are:

Loan Interest Rate: Higher rates are strongly correlated with default.

Loan Percent Income: Applicants spending a high percentage of their income on loan repayments pose a greater risk.

Person Income: Annual income remains a primary indicator of repayment capacity.
