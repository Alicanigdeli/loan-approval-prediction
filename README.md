# loan-approval-prediction

This project aims to predict whether a loan application will be approved or not based on various features of the applicant. It uses a machine learning approach to build a predictive model using the given dataset.

# Dataset

The dataset contains the following features:

Loan: A unique ID for each loan application.

Gender: Gender of the applicant (Male/Female).

Married: Marital status of the applicant (Yes/No).

Dependents: Number of dependents the applicant has.

Education: Educational background of the applicant (Graduate/Not Graduate).

Self_Employed: Indicates whether the applicant is self-employed (Yes/No).

ApplicantIncome: Income of the applicant.

CoapplicantIncome: Income of the co-applicant (if any).

LoanAmount: Loan amount requested (in thousands).

Loan_Amount_Term: Term of the loan in months.

Credit_History: Credit history of the applicant (repayment of debts).

Property_Area: Area where the property is located (Rural/Urban/Semi-Urban).

Loan_Status: Status of the loan application (Approved/Not Approved).


# Model-Evaluation

The project employs the following machine learning models for loan approval prediction:

K-Nearest Neighbors (KNN)

Random Forest Classifier

Support Vector Classifier (SVC)

Logistic Regression

The models are trained and evaluated using various performance metrics provided by the scikit-learn library.

# Results

The final model's performance on the loan approval prediction task is as follows:

KNN Accuracy: 59.21%

RFC Accuracy: 68.42%

SVC Accuracy: 65.78%

LR Accuracy: 77.63%

# Conclusion

This project demonstrates the application of machine learning techniques to predict loan approval based on applicant information. By utilizing different models and evaluating their performance, we have achieved a satisfactory accuracy rate.

Feel free to explore the code and dataset to gain a better understanding of the loan approval prediction process.
