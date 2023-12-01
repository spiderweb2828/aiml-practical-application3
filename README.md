# aiml-practical-application3

Link to Jupyter Notebook can be found at https://github.com/spiderweb2828/aiml-practical-application3/blob/main/prompt_III.ipynb 

## Data Clean up: In order to find the required data clean up, lets find the unique values of each column by executing the command data.apply(lambda col: col.unique()) on the dataframe "data"

### Understanding the Data: 
    The data contains information about the customers of a bank. The data has 45211 rows and 17 columns. The data has 7 categorical columns and 10 numeric columns. The data has 1 target variable. The data has 0 missing values. The data has 0 nan values.   
### Understanding the features:
    'age', 'job', 'marital', 'education', 'default', 'housing', 'loan' and 'y' are the features in the dataset. 'y' is the target variable. 'age' is the age of the customer. 'job' is the type of job of the customer. 'marital' is the marital status of the customer. 'education' is the education level of the customer. 'default' is whether the customer has credit in default. 'housing' is whether the customer has housing loan. 'loan' is whether the customer has personal loan. 'y' is whether the customer has subscribed to a term deposit.
### Understanding the Task: 
    Business Objective is to predict whether the customer will subscribe to a term deposit or not. This is a classification problem.
### Baseline Model: 
    DummyClassifier makes predictions that ignore the input features.This classifier serves as a simple baseline to compare against other more complex classifiers. The baseline model has an accuracy of 0.8873458288821987
### Model Comparisons:
    Using the following models, we will try to predict whether the customer will subscribe to a term deposit or not.
    1. Logistic Regression
    2. Decision Tree Classifier
    3. K Neighbors Classifier
    4. Support Vector Classifier

### Observations:
[results.txt](results.txt)