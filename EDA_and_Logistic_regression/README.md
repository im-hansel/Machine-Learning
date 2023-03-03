# EDA AND LOGISTIC REGRESSION
* This project aims to predict customer churn in a bank using logistic regression.

#### VARIABLES

* The dataset contains the following variables:

* RowNumber: a unique identifier for each record.
* CustomerId: a unique identifier for each customer.
* Surname: surname of the customer.
* CreditScore: credit score of the customer.
* Geography: country of the customer.
* Gender: gender of the customer.
* Age: age of the customer.
* Tenure: number of years for which the customer has been with the bank.
* Balance: balance in the customer's account.
* NumOfProducts: number of bank products the customer is using.
* HasCrCard: indicates whether the customer has a credit card (1) or not (0).
* IsActiveMember: indicates whether the customer is an active member (1) or not (0).
* EstimatedSalary: estimated salary of the customer.
* Exited: indicates whether the customer has exited the bank (1) or not (0).

## Description

* The project performs the following steps:

* Load the customer churn data into a pandas dataframe.
* Perform exploratory data analysis by checking the head of the data, the shape of the data, for missing values, and plotting the distribution of numerical and categorical variables.
* Prepare the data for the model by splitting it into training and test sets, one-hot encoding categorical variables, and fitting a logistic regression model.
* Predict customer churn using the logistic regression model and evaluate its performance using the classification report.

* The code is available in the EDA_and_logistic_efficient.ipynb notebook.

*Results
*The logistic regression model achieved an accuracy of 0.79 and an F1 score of 0.43 on the test data. The confusion matrix and classification report are available in the notebook.

* Usage
*To use this project, follow these steps:

*Clone the repository using git clone https://github.com/im-hansel/repo.git
*Install the required dependencies using pip install -r requirements.txt
*Open the EDA_and_logistic_efficient.ipynb notebook using Jupyter Notebook or JupyterLab
*Run the notebook cells to perform the EDA and logistic regression analysis.
