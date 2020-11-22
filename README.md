# EmployeeAttrition
Data Analytics Competition by CNA club of IITG

## Overview
Built a linear regression model after applying necessary Feature Engineering to predict Employee Attrition and used Data Pipeline to keep the code clean, the Kaggle notebook for the same can be accessed from [here](https://www.kaggle.com/vineet140502/employeeattrition). CNA club IITG organized this competition as part of its Summer Analytics Course 2020 in July 2020. 

## Aim
The competition aimed to predict the probability that an employee will resign from the company based on his previous data at work.

## Requirements
The following packages must be installed with Python3 already installed:

* Numpy
* Pandas

Other python libraries used:

* Scikit-Learn
* Matplotlib
* Seaborn
* XGBoost

## Evalutaion
The evaluation metric for this competition was the AUC score under ROC. ROC is a probability curve, and AUC represents the degree or measure of separability. Higher the AUC, the better the model is at predicting 0s as 0s and 1s as 1s.

## Data 
The data was provided by IBM in the CSV format(the same has been included in the repo) and consisted of basic details about the employee, his role in the company, and work records.

Data fields:

Id - an anonymous id given to an Employee

Age - Age of an Employee

Attrition - Did the Employee leave the company, 0-No, 1-Yes

BusinessTravel - Traveling frequency of an Employee

Department - Work Department

DistanceFromHome - Distance of office from home

EducationField - Field of Education

EmployeeNumber - Number of Employees in the division of a given Employee

EnvironmentSatisfaction - Work Environment Satisfaction

Gender - Gender of Employee

MartialStatus - Martial Status of an employee

MonthlyIncome - Monthly Income of Employee in USD

NumCompaniesWorked - Number of Companies in which Employee has worked before joining this Company

OverTime - Does The person work overtime

PercentSalaryHike - Average annual salary hike in percentages

StockOptionLevel - Company stocks given to an Employee

TotalWorkingYears - Total working experience of an employee

TrainingTimesLastYear - No. of trainings an employee went through last year

YearsAtCompany - Number of years worked at this company

YearsInCurrentRole - Number of years in current role

YearsSinceLastPromotion - Number of years since last promotion

YearsWithCurrManager - Number of years with the current manager

Education

1 'Below College' 
2 'College' 
3 'Bachelor' 
4 'Master' 
5 'Doctor'

EnvironmentSatisfaction

1 'Low' 
2 'Medium' 
3 'High' 
4 'Very High'

JobInvolvement

1 'Low' 
2 'Medium'
3 'High'
4 'Very High'

JobSatisfaction

1 'Low' 
2 'Medium' 
3 'High'
4 'Very High'

PerformanceRating

1 'Low' 
2 'Good'
3 'Excellent' 
4 'Outstanding'

Behaviour

1 'Good'
2 'Bad'
3 'Not Rated'

CommunicationSkill

1 'Bad'
2 'Average' 
3 'Good'
4 'Better'
5 'Best'

StockOptionLevel

0 'No stocks'
1 'Less Stocks' 
2 'Moderate Stocks'
3 'A lot of Stocks'
