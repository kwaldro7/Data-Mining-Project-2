# Loan Default Classification (First Draft)

This project is a first draft of a machine learning pipeline for predicting **loan default risk** based on applicant and loan data.  
The dataset includes features such as applicant demographics, loan characteristics, and financial history.

---

## Dataset

The dataset contains the following columns:

- **Applicant_ID**: Unique identifier for each applicant  
- **Age**: Applicant’s age  
- **Income**: Applicant’s income  
- **Credit_Score**: Applicant’s credit score  
- **Loan_Amount**: Requested loan amount  
- **Loan_Term**: Duration of the loan (in months)  
- **Interest_Rate**: Loan interest rate (%)  
- **Employment_Status**: Employment status (e.g., employed, unemployed, self-employed)  
- **Debt_to_Income_Ratio**: Ratio of debt payments to income  
- **Marital_Status**: Marital status of the applicant  
- **Number_of_Dependents**: Number of dependents supported by the applicant  
- **Property_Ownership**: Whether the applicant owns or rents a property  
- **Loan_Purpose**: Purpose of the loan (e.g., personal, education, mortgage)  
- **Previous_Defaults**: Indicator if the applicant has previously defaulted (target variable)

---

## Approach (First Draft)

This first draft keeps things simple:

1. **Preprocessing**
   - Selected a subset of features (`Age`, `Income`, `Credit_Score`, `Loan_Amount`, `Employment_Status`)  
   - Encoded categorical variables (e.g., `Employment_Status`)  
   - Split the data into training and test sets  

2. **Model**
   - Trained a **Decision Tree Classifier** for interpretability and simplicity  
   - Evaluated with accuracy score on test set  


