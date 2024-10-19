# Project Description

- This project focuses on predicting bank loan approvals using machine learning techniques.

- By analyzing historical loan data, we built and evaluated several models to identify key factors influencing loan approval decisions. 

- The Random Forest Classifier emerged as the best-performing model, significantly improving prediction accuracy.

# Steps Followed

1.	Data Loading and Initial Exploration

○	Imported necessary libraries, including pandas and google.colab.drive.

○	Loaded the dataset from Google Drive.

○	Displayed the first and last 5 rows of the dataset.

○	Checked the shape of the dataset.

○	Obtained information about the dataset, including the number of rows, columns, and data types of each column.

○	Identified columns with missing values and calculated the percentage of missing values.

2.	Data Cleaning

○	Dropped the Loan_ID column, as it was not required.

○	Dropped columns with missing values less than 5%.

○	Filled remaining missing values with appropriate strategies (mean, median, or mode).

3.	Data Preprocessing

○	Converted categorical variables into numerical values using label encoding.

○	Checked for and addressed multicollinearity using correlation matrix and VIF (Variance Inflation Factor).

4.	Model Building

○	Split the data into training and testing sets.

○	Trained and evaluated several models, including Logistic Regression, Decision Tree Classifier, Random 
Forest Classifier, K-Nearest Neighbors, and Support Vector Classifier.

○	Used GridSearchCV for hyperparameter tuning of the best performing models.

5.	Model Evaluation

○	Evaluated models using accuracy scores before and after hyperparameter tuning.

○	Chose the Random Forest Classifier based on performance metrics.

6.	Model Deployment

○	Saved the trained model using joblib.

○	Loaded the saved model and made predictions on new data.

○	Displayed the loan approval status for each prediction.
