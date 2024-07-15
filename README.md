# Loan prediction Analysis: Classification and Prediction
## Introduction
Financial Institutions play a key role in economy building through providing loand to businesses and individuals based on several factors one of them being income. A major risk for businesses is loan default where teh borrowers often fail to pay back tehir loans. To handle this problem, it is important for financial institutions to apply machine learning techniques, moreso, logistic regression, aiding in decision-making for the long-term.
## Project Goals
1. Identify borrowers that pose a high risk based on the factors provided.
2. Train a model (Logistic regression) that informs future decions.
3. Apply the new prediction meausres to new data to view its efficiency.
4. Save and load the trained models.
## Steps: training a logistic regression model
- we take linear combination (or weighted sum of the input features)
- we apply the sigmoid function to the result to obtain a number between 0 and 1
- this number represents the probability of the input being classified as "Yes"
- instead of RMSE, the cross entropy loss function is used to evaluate the results
## Data Acquisition
The data is from Kaggle: https://www.kaggle.com/datasets/nikhil1e9/loan-default. This dataset provides an equivalent number of points to build a model on.
## Model
The model is aimed at predicting whether a person will default on their loan(1) or not(0). A Logistic model aims to promote accuracy and interpretability. 
