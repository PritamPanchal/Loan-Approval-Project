# Loan-Approval-Project
A banking firm wants to build an algorithm which can predict if the customer can get a loan or not.
We have to build a ML model to predict the loan eligibility/approval of the customer based on previous historical data provided.


## Dataset Attributes

#### Loan_ID           : A unique identification number/ID assigned to each loan application.
#### Gender            : Gender of the applicant.
#### Married           : Whether the applicant is married or not.
#### Dependents        : The number of dependents on the applicant.
#### Education         : Educational qualification of applicant.
#### Self_Employed     : Whether applicant is self-employed or not.
#### ApplicantIncome   : The income of the applicant.
#### CoapplicantIncome : The income of the co-applicant.
#### LoanAmount        : Amount of the loan.
#### Loan_Amount_Term  : Duration of the loan in months.
#### Credit_History    : A binary variable indicating whether the applicant has a credit history (i.e., 1/0 for Yes/No).
#### Property_Area     : The area where the property associated with the loan is located (i.e., Urban/Rural).
#### Loan_Status       : The final status of the loan application (i.e., Yes/No).

## Steps performed

### Load and Examine the Dataset

    Importing libraries
    Reading the dataset
    Examining the basic structure of the dataset

### Data Preprocessing

    Normalising the skewed data columns
    Handling missing values in the dataset
    Converting categorical variables into numerical format.
    
### Feature Scaling

    Standardizing the feature values using StandardScaler.

### Model Training and Evaluation using Random Forest Classifier

    Initializing and training the Random Forest Classifier.
    Generating classification report on the training set.
    Analyzing accuracy

### Model Training and Evaluation using Naive Bayes Classifier

    Based on accuracy using Naive Bayes Classifier to predict values on test dataset

