# IBM Employee Attrition Prediction Using XGBoost

This project predicts employee attrition in IBM using the company's employee data. The dataset includes various attributes related to employees, such as age, job satisfaction, years with the company, and more. The project applies machine learning techniques, specifically XGBoost, to predict whether an employee is likely to leave the company (attrition) based on these features.

## Project Overview

The goal of this project is to build a predictive model to forecast employee attrition using XGBoost. The model is trained on a dataset containing features like age, job role, education, marital status, and performance ratings, among others.

## Dataset

The dataset used for this project is IBM Employee Attrition data, which contains information on employee demographics, job satisfaction, performance, and other relevant metrics.
Link - https://www.kaggle.com/datasets/uniabhi/ibm-hr-analytics-employee-attrition-performance?resource=download

### Data Columns:
- **Age**: The age of the employee.
- **Attrition**: Whether the employee left the company (target variable).
- **BusinessTravel**: Frequency of business travel.
- **DailyRate**: The employee's daily rate.
- **Department**: The department where the employee works.
- **DistanceFromHome**: The distance from the employee's home to work.
- **Education**: Level of education.
- **EducationField**: The field of education.
- **Gender**: The gender of the employee.
- **JobInvolvement**: Employee job involvement level.
- **JobLevel**: The employee’s job level.
- **JobRole**: The employee’s job role.
- **JobSatisfaction**: The employee’s job satisfaction.
- **MaritalStatus**: The marital status of the employee.
- **MonthlyIncome**: Monthly income of the employee.
- **YearsAtCompany**: Number of years the employee has been with the company.
- **YearsInCurrentRole**: Number of years the employee has been in the current role.
- **Other Features**: Includes performance ratings, work-life balance, etc.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- xgboost
- scikit-learn

You can install the necessary dependencies using the following command:

```bash
pip install -r requirements.txt
