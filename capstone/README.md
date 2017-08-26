# Machine Learning for Employee Retention   

## Project Overview 

This project outlines a supervised machine learning approach to help implement an effective employee retention program. Different classification algorithms including Logistic Regression, Linear Discriminant Analysis, Decision Trees, K-nearest Neighbors, Support Vector Machines, and Random Forest are built and compared. F2 score is selected as the performance metric in order to put more weights on recall. K-fold cross validation procedure is implemented to evaluate the models. Random Forest classifier is chosen as it gives the best cross validation F2 score. After further fine-tuning the hyperparameters, the final model shows excellent F2 score (0.97) and generalizes well to unseen data. Feature importance analysis reveals the top 5 features, including satisfaction level, employment time, number of projects, average working hours and last evaluation scores, which consist about 95% of the total importance.


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

