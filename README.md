# HR_Project_GCD

The Employee attrition is the gradual reduction in employee numbers. Employee attrition happens when the size of  workforce diminishes over time. 
This means that employees are leaving faster than they are hired. Employee attrition happens when employees retire, resign, or simply aren't replaced.
Companies are struggling to address today and this situation shall continue to be there for one simple reason: 
the companies don’t really understand why their employees are leaving in the first place.

Current Practice
Once an employee leaves, he or she is taken an interview with the name “exit interview” and shares reasons for leaving.
The HR Department then tries and learns insights from the interview and makes changes accordingly.

This suffers from the following problems:

This approach is that it's too haphazard. The quality of insight gained from an interview depends heavily on the skill of the interviewer.
The second problem is these insights can't be aggregated and interlaced across all employees who have left.
The third is that it is too late by the time the proposed policy changes take effect.

# Problem Statement

Our client for this project is the HR Department at a software company.

- HR want to try a new initiative to retain employees.
- The idea is to use data to predict whether an employee is likely to leave.
- Once these employees are identified, HR can be more proactive in reaching out to them before it's too late.
- They only want to deal with the data that is related to permanent employees.

Hr Department have given three datasets that contain information about past employees and their status (still employed or already left).
Our task is to build a classification model using the datasets.Because there is no machine learning model for this problem in the company.

The Business Intelligence Analysts of the Company provided you three datasets that contain information about past employees and their status (still employed or already left).

department_data
This dataset contains information about each department. The schema of the dataset is as follows:

dept_id – Unique Department Code
dept_name – Name of the Department
dept_head – Name of the Head of the Department

employee_details_data
This dataset consists of Employee ID, their Age, Gender and Marital Status. The schema of this dataset is as follows:

employee_id – Unique ID Number for each employee
age – Age of the employee
gender – Gender of the employee
marital_status – Marital Status of the employee

employee_data
This dataset consists of each employee’s Administrative Information, Workload Information, Mutual Evaluation Information and Status.

Target variable

status – Current employment status (Employed / Left)
Administrative information

department – Department to which the employees belong(ed) to
salary – Salary level with respect to rest of their department
tenure – Number of years at the company
recently_promoted – Was the employee promoted in the last 3 years?
employee_id – Unique ID Number for each employee
Workload information

n_projects – Number of projects employee has worked on
avg_monthly_hrs – Average number of hours worked per month
Mutual evaluation information

satisfaction – Score for employee’s satisfaction with the company (higher is better)
last_evaluation – Score for most recent evaluation of employee (higher is better)
filed_complaint – Has the employee filed a formal complaint in the last 3 years?
