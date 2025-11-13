# Employee_Attrition_Analysis_Dashboard
1]Project Name :- Employee Attrition Dashboard
2]Objectives :- The objective of this project is to analyze employee attrition data to identify key factors contributing to workforce turnover. The insights derived from the dashboard help HR departments make data-driven decisions to improve employee retention, job satisfaction, and workforce planning.
3] Tools & Technologies Used :-
•	Data Source : Excel/CSV file
•	Data Visualization Tool : Power BI
•	Data Cleaning & Transformation : Power Query
•	Data Analysis : DAX (Data Analysis Expressions)
•	Visualization Elements : Bar charts, Donut charts, Cards, Line chart, and Slicers
4] Project Workflow :-
	Step 1: Data Import
•  Imported the employee dataset (CSV file) into Power BI Desktop.
•  Verified column names, data types, and structure.
	Step 2: Data Cleaning (Power Query Editor)
   Performed cleaning and transformation tasks such as:
•	Removed duplicate and blank values.
•	Standardized column headers (e.g., Attrition, JobRole, Education, etc.).
•	Converted data types (e.g., salary, age, years) to numeric formats.
•	Created new calculated columns where needed (e.g., Age Groups, Salary Bands).


	Step 3 : DAX Calculations (KPI Metrics)
Created several DAX measures to calculate key performance indicators:
•	Total Employees:
Count of Employee = COUNT(Employee[EmployeeID])
•	Total Attrition:
Attrition = CALCULATE(COUNT(Employee[EmployeeID]), Employee[Attrition] = "Yes")
•	Attrition Rate (%):
Attrition Rate = DIVIDE([Attrition], [Count of Employee])
•	Average Age:
Avg Age = AVERAGE(Employee[Age])
•	Average Salary:
Avg Salary = AVERAGE(Employee[MonthlyIncome])
•	Average Years of Service:
Avg Years = AVERAGE(Employee[YearsAtCompany])
	Step 4 : Dashboard Design & Visualization
1]KPI :
•  Count of Employees: 1,470
•  Attrition: 237
•  Attrition Rate: 16.1%
•  Average Age: 37 years
•  Average Salary: ₹6.5K
•  Average Years: 7 years


2] Visuals Used :
	Donut Chart (Attrition by Education):
Shows how attrition varies across education fields (Life Sciences, Medical, Marketing, Technical Degree, etc.).
	Bar Chart (Attrition by Age):
Highlights that employees aged 26–35 have the highest attrition count (116).
	Stacked Bar (Attrition by Salary):
Indicates lower-salary employees (≤ ₹5K) have the highest attrition (163).
	Line Chart (Attrition by Years of Service):
Shows high attrition during the initial year of employment.
	Horizontal Bars (Attrition by Job Role):
Identifies top job roles with attrition — Laboratory Technician, Sales Executive, Research Scientist, etc.
	Matrix (Job Satisfaction by Job Role):
Displays satisfaction scores (1–4) across various job roles.
	Gender-wise Card Chart:
Shows that attrition among males (140) is higher than females (79).
	Slicers : 
Added for Department to allow dynamic filtering.


5] Conclusion :
	This Power BI dashboard effectively visualizes employee attrition patterns, helping HR managers make informed decisions. By identifying high-risk groups and underlying causes, organizations can reduce turnover, improve employee satisfaction, and enhance overall productivity.

6]Dashboard :

