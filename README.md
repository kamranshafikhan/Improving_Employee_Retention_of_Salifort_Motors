# Improving Employee Retention of Salifort Motors

## Introduction
Salifort motors is a French based fictional company. It is alternative energy vehicle manufacturer. Its global workforce of over 100,000 employees research, design, construct, validate, and distribute electric, solar, algae, and hydrogen-based vehicles.

## Project Overview
The goal of this project is to analyze the data of Salifort employees and create binary logistic regression, decision tree and random forest models to predict whether or not an employee will leave the company. The project utilized the HR's survey data of a sample of 15000 employees. The champion model came out to be random forest with an accuracy of 96.16%, f1 score of 88.67%, and an AUC score of 93.84. Based on the model, the following factors (in order) were most influential in determining the employee's turnover:
- Recent feedback given to employee
- Number of projects
- Tenure
- Overworked

## Tools and Skills Used
- Python - programming language
- Exploratory Data Analysis
- Machine Learning Models - Logistic Regression, Decision Tree, Random Forest
- Feature Engineering

## Business Understanding
High turn over rate is a big challenge for Salifort company. It makes a big investment in recruiting, training, and upskilling its employees. If the key factors that drive the employees turnover are analyzed and predicted this can significantly help the company increase retention and job satisfaction for current employees, and save money and time training new employees.

## Data Understanding
The data for the employee's survery came from "https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction". The dataset consisted of aprroximately 15000 rows and 10 features. The features included information on department, number of projects, average monthly hours, tenure etc of employees (both who are working and those who have left).

## Modeling and Evaluation
A random forest model comprising of 300 decision trees was used to determine feature importance in predicting whether an employee will leave the company or not. The plot below shows that recent evaluation score of employee, number of projects, tenure and overworked were the top 4 most important factors in determining the turn over.
The model performed with an accuracy of 96.16%, f1 score of 88.67%, and an AUC score of 93.84.

![__results___166_0](https://github.com/kamranshafikhan/Improving_Employee_Retention_of_Salifort_Motors/assets/61063685/57797418-d485-4e04-aee4-cd645474bdf4)

## Conclusion
This model can benefit the Salifort motors in improving the employee retention of the company. Efforts and changes should be made in the workload managment and employee recognition.
  
