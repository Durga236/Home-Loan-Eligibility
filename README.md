# Home-Loan-Eligibility

PROJECT OVERVIEW

Banks and financial institutions receive thousands of loan applications daily. Not all applicants are eligible for loans due to various factors such as income, employment status, credit history, and existing liabilities. Manually evaluating these applications is time-consuming, prone to errors, and can lead to biased decisions.

This project applies data analytics and machine learning to build a predictive system that determines whether a customer is eligible for a home loan. By analyzing applicant details, the system improves decision-making, reduces processing time, and ensures transparency.

OBJECTIVES

1. To predict home loan eligibility based on applicant details.
2. To automate and assist loan officers in the decision-making process.
3. To identify key factors influencing loan approval.
4. To improve accuracy compared to manual assessment.

DATASET

We use a synthetic dataset containing applicant details and their final loan approval status (Approved / Not Approved).
Features include:
1. Applicant Information: Gender, Marital Status, Education, Dependents.
2. Financial Status: Applicant Income, Co-applicant Income, Loan Amount, Loan Amount Term.
3. Credit History: Past repayment record (0 = bad, 1 = good).
4. Property Area: Rural, Semi-urban, Urban.
5. Target Variable: Loan Status (Approved / Not Approved).

METHODS

1. Data Preprocessing
•	Handled missing values.
•	Encoded categorical variables (e.g., Gender, Property Area).
•	Normalized numerical values (Income, Loan Amount).
2. Exploratory Data Analysis (EDA)
•	Studied distribution of income, loan amount, approval rate.
•	Checked correlation between features and loan approval.
•	Visualized patterns using bar charts, histograms, and heatmaps.
3. Feature Selection
•	Identified important predictors (Credit History, Income, Loan Amount).
4. Model Building
•	Algorithms used: Logistic Regression, Decision Trees, Random Forest, XGBoost.
•	Split dataset into training (70%) and testing (30%) sets.
5. Model Evaluation 
•	Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
•	Compared performance of different models.

TOOLS & TECHNOLOGIES

•	Programming Languages: Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn).
•	Visualization: Power BI.
•	Deployment: Flask / Streamlit (optional).
•	Version Control: GitHub.

RESULTS & INSIGHTS

•	Credit History and Applicant Income emerged as the most significant predictors of loan approval.
•	Models like Random Forest and XGBoost achieved higher accuracy (~80–85%) compared to Logistic Regression.
•	Visualization dashboards helped identify trends, e.g., urban applicants had higher approval rates.

CONCLUSION

This project demonstrates how data analytics and machine learning can assist banks in making faster and more reliable loan approval decisions. By automating the eligibility process, financial institutions can reduce human bias, improve customer satisfaction, and minimize loan default risks.

PROJECT WORKFLOW

1.	Data Collection / Synthetic Data Generation.
2.	Data Cleaning & Preprocessing.
3.	Exploratory Data Analysis (EDA).
4.	Feature Engineering.
5.	Model Training & Evaluation.
6.	Explainability & Fraud Rules.
7.	Dashboard Development.
8.	Report & Presentation

DURGA DM
18th Sep, 2025
