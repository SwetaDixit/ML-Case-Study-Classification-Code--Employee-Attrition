Description
Attrition Prediction
Welcome to the Employee Attrition Classification Challenge! In this competition, you are tasked with developing a machine learning model to predict employee attrition in a company. Employee attrition is a significant concern for businesses, as it can lead to decreased productivity, increased costs, and loss of valuable knowledge. By identifying the factors that contribute to attrition and accurately predicting which employees are at risk of leaving, companies can take proactive steps to retain their top talent and minimize the negative impact on their organization.

The dataset provided contains historical employee data, including demographics, job-related information, and employee satisfaction metrics. Your goal is to create a classification model that can accurately predict whether an employee will leave the company or not, based on these features.

Submission File
For each EmployeeNumber in the test set, you must predict the probability for the target variable Attrition. The file should contain a header and have the following format:

EmployeeNumber,Attrition
1677,0.78
1678,0.34
1679,0.55
etc.

Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on a Employee Attrition. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

Files
train.csv - the training dataset; Attrition is the binary target
test.csv - the test dataset; your objective is to predict the probability of positive Attrition
sample_submission.csv - a sample submission file in the correct format
