# HR_ATTRITION_DASHBOARD-Major-Project-
This project analyzes employee attrition using HR data and presents insights through an interactive Power BI dashboard to help improve employee retention.

HR Attrition Analysis Dashboard (Power BI):

Project Overview:

Employee attrition is a critical challenge for organizations as it directly impacts productivity, hiring costs, and employee morale.
This project analyzes employee attrition patterns using Power BI, focusing on demographics, compensation, growth, and engagement factors to identify the key drivers behind employee turnover.

The dashboard is designed to help HR teams and management make data-driven retention decisions.

Objectives:

* Analyze overall employee attrition trends.
* Identify high-risk departments and job roles.
* Understand demographic patterns affecting attrition.
* Evaluate compensation and growth-related factors.
* Assess employee engagement and satisfaction impact.

Dataset:

Source: IBM HR Analytics Employee Attrition Dataset.

Records: 1,470 employees

Attributes: Demographics, job roles, salary, performance, satisfaction, experience.

Data Modeling:

Schema: Star Schema.

Fact Table: Fact_Attrition.

Dimension Tables:
* Dim_Employee
* Dim_Department
* Dim_Compensation
* Dim_Experience
* Dim_Satisfaction
* Dim_Education

Key Measures Table: Centralized KPI measures.

<img width="1015" height="628" alt="Screenshot 2025-12-27 145339" src="https://github.com/user-attachments/assets/85e2bd9f-9be7-48ae-9200-dbc600fb680d" />


Tools & Technologies:

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Power Query
* Star Schema Data Modeling

Dashboard Pages:

-> Page 1: HR Attrition Overview
* Total Employees
* Attrition Count & Rate
* Attrition by Department
* Attrition by Job Role
* Attrition by Gender
* Attrition by Age Band

Purpose: High-level executive summary for quick insights.

<img width="1308" height="731" alt="Screenshot 2025-12-27 150222" src="https://github.com/user-attachments/assets/b9f09ffc-46c4-47ec-8e92-62c74eeb3d2e" />


-> Page 2: Employee Demographics Analysis
* Attrition by Age Group
* Attrition by Marital Status
* Attrition by Education Field
* Attrition by Income Band

Purpose: Identify demographic segments with higher attrition risk.

<img width="1305" height="733" alt="Screenshot 2025-12-27 150303" src="https://github.com/user-attachments/assets/62c2060a-8b7c-43f1-9034-6d594213df5e" />


-> Page 3: Compensation & Growth Analysis
* Attrition by Income Band
* Attrition vs Salary Hike
* Attrition by Years Since Last Promotion
* Attrition by Total Working Years

Purpose: Understand salary and growth-related attrition drivers.

<img width="1303" height="731" alt="Screenshot 2025-12-27 150325" src="https://github.com/user-attachments/assets/cb2c652e-1ff9-4be8-920c-d49cb839fc49" />


-> Page 4: Engagement & Satisfaction Analysis
* Attrition by Job Satisfaction
* Attrition by Work-Life Balance
* Attrition by Overtime
* Attrition by Performance Rating

Purpose: Analyze engagement and workload impact on attrition.

<img width="1306" height="722" alt="Screenshot 2025-12-27 150350" src="https://github.com/user-attachments/assets/0f963cd0-52b9-45ce-9655-7b5b69a25c79" />


Key KPIs:
* Total Employees
* Attrition Count
* Attrition Rate (%)
* Average Monthly Income
* Average Years at Company
* Overtime Percentage
* Average Job Satisfaction
* Average Performance Rating

Key Insights:
* Higher attrition observed among younger employees and lower income bands.
* Employees with longer promotion gaps show increased attrition.
* Overtime and poor work-life balance significantly contribute to employee exits.
* Attrition exists even among high-performing employees, indicating external opportunity influence.

Learnings:
* Importance of proper data modeling (Star Schema).
* Avoiding incorrect aggregations (SUM vs AVERAGE).
* Using bins for continuous variables.
* Designing dashboards for storytelling, not just visuals.

Future Enhancements:
* Predictive attrition modeling using Machine Learning.
* Department-level retention strategy recommendations.
* Integration with real-time HR systems.


---

Author:

Divyanshu Chandra

B.Tech (IT) – Data Analytics Enthusiast

LinkedIn: https://www.linkedin.com/in/divyanshu-chandra-47269329a

If you like this project :
Give it a ⭐ on GitHub and feel free to fork or suggest improvements!
