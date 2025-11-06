🧑‍💼 Employee Performance and Retention Analysis – SQL Project

📘 Project Overview
This project analyzes employee performance, attendance, and attrition trends to identify workforce efficiency and retention patterns.
It aims to help HR and management teams improve employee satisfaction, reduce attrition, and optimize departmental budgets using data-driven insights.
________________________________________
🎯 Project Objectives
1.	Evaluate employee performance across departments and roles.
2.	Identify top-performing and low-performing employees.
3.	Analyze attrition reasons and predict high-risk departments.
4.	Assess the relationship between attendance, performance, and attrition.
5.	Monitor department-level budget utilization vs. performance outcomes.
________________________________________
🧾 Dataset Details
The project uses the file: employee_performance_dataset.xlsx

1. Employees
Column Name	   Description
Employee_ID	   Unique employee identifier
Employee_Name	 Name of employee
Department	   Department name
Role	         Job role/title
Salary	       Monthly salary (in ₹)
Gender	       Male/Female
Join_Date    	 Date of joining

2. Performance
Column Name	         Description
Performance_ID	     Unique performance record
Employee_ID	         Foreign key (Employees table)
Performance_Rating   Rating (Excellent, Good, Average, Poor)
Score	               Numeric performance score
Month	               Month of review
Year	               Year of review

3. Attendance
Column Name	    Description
Attendance_ID	  Unique attendance record
Employee_ID	    Foreign key (Employees table)
Date	          Attendance date
Status	        Present, Absent, On Leave

4. Attrition
Column Name	     Description
Attrition_ID	   Unique record
Employee_ID	     Foreign key (Employees table)
Exit_Date	       Date of exit
Exit_Type	       Resigned / Terminated
Reason	         Reason for leaving

5. Department_Budget
Column Name	      Description
Department	      Department name
Budget_Allocated	Annual budget (₹)
Budget_Used	      Actual expenditure (₹)
________________________________________
📊 Insights & Recommendations
•	Top-performing departments: Sales & IT show consistently high scores.
•	High attrition: HR and Operations face more employee exits due to personal or performance-related reasons.
•	Budget utilization: Finance and Operations exceeded 90% utilization, indicating tight resource allocation.
•	Performance correlation: Employees with “Poor” performance had a 3× higher attrition probability.
•	Recommendation: Introduce skill-based training for low-performing employees and review HR policies for retention.
________________________________________
🧠 Tools Used
•	Database: MySQL 
•	Visualization: Power BI /  Excel
•	Data Source: employee_performance_dataset.xlsx (Synthetic data)
________________________________________
🏁 Outcome
This project demonstrates your ability to:
•	Design normalized datasets
•	Write SQL queries from basic to advanced level
•	Perform HR analytics and retention analysis
•	Provide actionable insights through data storytelling
________________________________________
⭐ Author
Your Name – Preeti Lata Biswal

