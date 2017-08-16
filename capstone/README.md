# Machine Learning for Employee Retention   

## Overview 
Build and optimize binary classification model to predict whether an employee with given features is leaving or not. Identify the most important features that lead to employee turnover. This project can provide actional insights to the management and human resource team to implement an effective employee retention program.    

## Libraries  
This project was done in **Python 3.5** environment with the following Python libraries:  

- Numpy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

## Data   
The dataset was obtained from [**Kaggle**](https://www.kaggle.com/ludobenistant/hr-analytics). It is a simulated dataset containing 14,999 rows and 10 columns.   

### Features  
- `'satisfaction_level'`: employee satisfaction level (numerical, float 0-1)   
- `'last_evaluation'`: the score from the employee's last evaluation (numerical, float 0-1)   
- `'number_project'`: the number of projects the employee worked on (numeric, integer)    
-  `'average_monthly_hours'`: the average monthly hours the employee spent on work (numeric, integer)   
- `'time_spend_company'`: number of year the employee spent at the company (numeric, integer)    
- `'work_accident'`: whether the employee had a work accident (categorical, '0' - no, '1' - yes)    
- `'promotion_last_5year'`: whether the employee had a promotion in the last 5 years (categorical, '0' - no, '1' - yes)   
- `'sales'`: the Department the employee works (categorical, 'sales', 'accounting', 'hr', 'technical', 'support', 'management', 'IT', 'product_mng', 'marketing', 'RandD')     
- `'salary'`: the salary of the employee (categorical, 'low', 'medium', 'high')     

### Target Variable      
- `'left'`: whether the employee has left or not (categorical, '0' - no, '1' - yes)     

