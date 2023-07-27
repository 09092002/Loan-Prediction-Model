# Loan-Prediction-Model
#Description
The Loan Prediction Model using Decision Tree is a machine learning project designed to automate the loan approval process for banks and financial institutions. The goal of the project is to develop a predictive model using the Decision Tree algorithm that can determine whether a loan applicant is likely to be approved or rejected based on their application details. The project involves collecting historical loan application data, including features such as applicant's gender, age, income, education, employment status, loan amount, loan term, credit history, marital status, and number of dependents. Each of these features provides valuable information about the applicant's financial situation and creditworthiness. The Decision Tree algorithm is chosen for this project due to its ability to handle both categorical and numerical data and its interpretability. By recursively splitting the data based on the most significant features, the Decision Tree creates a tree-like structure of decision rules, allowing for easy interpretation and understanding of the loan approval process. The project follows several essential steps, including data preprocessing to clean and handle missing values, exploratory data analysis to gain insights into the data distribution, data splitting to create training and testing datasets, and model training using the Decision Tree algorithm to learn the decision rules. The model's performance is evaluated on the testing data using various metrics such as accuracy, precision, recall, F1-score, and confusion matrix. Hyperparameter tuning is performed to optimize the Decision Tree model's performance. Interpreting the decision rules learned by the Decision Tree provides valuable insights into the factors influencing loan approval decisions. The trained model is then deployed in a real-world setting to predict loan approvals and assist in making objective and data-driven lending decisions. Overall, the Loan Prediction Model using Decision Tree aims to improve the efficiency of the loan approval process, reduce bias, and ensure fair lending practices by relying on data-driven predictions and objective criteria for loan decisions.

Features
Applicant's Gender: The gender of the loan applicant, represented as a binary variable (Male/Female).

Applicant's Age: The age of the loan applicant, providing insights into their financial maturity and capacity to repay the loan.

Applicant's Income: The income of the applicant, which helps assess their ability to meet loan repayment obligations.

Applicant's Education: The educational qualification of the loan applicant, indicating their level of financial awareness and potential earning prospects.

Applicant's Employment Status: The current employment status of the applicant, including employed, self-employed, unemployed, or retired.

Loan Amount: The amount of money the applicant is applying for as a loan.

Loan Term: The duration for which the applicant is seeking the loan, typically represented in months.

Credit History: A binary variable representing the applicant's credit history (1 for good credit history, 0 for bad credit history).

Marital Status: The marital status of the loan applicant, providing additional demographic information.

Dependents: The number of dependents the applicant has, indicating their financial responsibilities.

Tech Used
Python NumPy Pandas Plotly scikit-learn SciPy
