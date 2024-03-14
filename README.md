# Loan-Approval-Project
A banking firm wants to build an algorithm which can predict if the customer can get a loan or not.
We have to build a ML model to predict the loan eligibility/approval of the customer based on previous historical data provided.


## Dataset Attributes
Loan_ID           : A unique identification number assigned to each loan application.
Gender            : The gender of the applicant (e.g., Male).
Married           : Indicates whether the applicant is married (e.g., Yes or No).
Dependents        : The number of dependents the applicant has (e.g., 0, 1).
Education         : The educational qualification of the applicant (e.g., Graduate or Not Graduate).
Self_Employed     : Indicates whether the applicant is self-employed (e.g., Yes or No).
ApplicantIncome   : The income of the applicant.
CoapplicantIncome : The income of the co-applicant, if any.
LoanAmount        : The amount of the loan applied for.
Loan_Amount_Term  : The term or duration of the loan in months.
Credit_History    : A binary variable indicating whether the applicant has a credit history (e.g., 1 for Yes, 0 for No).
Property_Area     : The area where the property associated with the loan is located (e.g., Urban, Rural).
Loan_Status       : The final status of the loan application (e.g., Y for Yes, N for No).

## Steps performed
Load and Examine the Dataset
    Importing libraries
    Reading the dataset
    Examining the basic structure of the dataset

Data Preprocessing
    Normalising the skewed data columns
    Handling missing values in the dataset
    Converting categorical variables into numerical format.
    
Feature Scaling
    Standardizing the feature values using StandardScaler.

Model Training and Evaluation using Random Forest Classifier
    Initializing and training the Random Forest Classifier.
    Generating classification report on the training set.
    Analyzing accuracy

Model Training and Evaluation using Naive Bayes Classifier

