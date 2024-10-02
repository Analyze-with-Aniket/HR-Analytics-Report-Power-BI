# HR-Analytics-Report-Power-BI

# About
This HR Analytics Dashboard project provides a detailed analysis of employee attrition using Power BI. The dashboard explores key factors influencing employee turnover, including education, age, gender, job role, salary, years at the company, and job satisfaction ratings. By leveraging interactive visuals, the dashboard offers valuable insights to help HR teams understand attrition trends and develop strategies for employee retention.

# Purpose of the project
The purpose of this project is to analyze employee attrition patterns and identify the factors contributing to turnover within an organization. By examining various dimensions such as age, education, gender, job role, salary range, and years of service, this dashboard aims to provide HR departments with actionable insights. These insights can be used to:
- Develop effective employee retention strategies
- Improve workplace satisfaction and engagement
- Address areas of concern, such as high attrition in specific job roles or demographics
- Support data-driven decision-making for talent management and workforce planning
The ultimate goal is to help organizations reduce employee turnover and foster a more stable, satisfied workforce.

# About Data
The dataset used for this HR analytics project contains comprehensive employee information gathered from internal HR records and surveys. Key features include:
-Demographic Information: Age, gender, and education level.
-Job-Related Data: Job role, department, salary slab, business travel, and years of service.
-Employee Satisfaction: Job satisfaction ratings, work-life balance scores, and relationship satisfaction.
-Attrition Status: Indicates whether an employee has left the company.
This data is crucial for identifying trends in employee attrition, helping HR teams understand which factors—such as age group, education, or job role—have the greatest impact on employee turnover. The dataset supports a wide range of analyses to drive retention strategies and workforce improvements.

# KPI Requirements
1. Attrition Rate: Percentage of employees leaving the company.
2. Attrition by Age Group: Analysis of turnover across different age brackets.
3. Attrition by Gender: Distribution of attrition rates between male and female employees.
4. Attrition by Education: Insights into how education levels influence attrition.
5. Attrition by Job Role: Examination of turnover rates across various job roles.
6. Attrition by Salary Slab: Analysis of attrition based on different salary ranges.
7. Attrition by Years at Company: Understanding turnover in relation to employee tenure.
8. Average Employee Metrics: Average age, average salary, and average years of service of employees.
These KPIs will enable the HR team to identify trends and formulate effective retention strategies.

# Approach Used
1.	Requirement gathering/ business requirement
2.	Data walkthrough
3.	Data connection
4.	Data cleaning/ quality check (Replacing some values like (LF to Low fat, reg to regular), Check for errors (if any))
5.	Data modelling
6.	Data processing
7.	Dax calculation
8.	Dashboard layouting
9.	Charts development and formatting 
10.	Dashboard / report development
11.	Insights generation

## DAX function used:
1. For Attrition Rate: sum function for calculating attrition count and employee count and then divide them
   Formula used: sum(HR_Analytics[AttritionCount])/sum(HR_Analytics[EmployeeCount])

In KPI's I just used the options in power bi to get the results.

# Key Insights
1. Attrition Concentrated in Younger Workforce: The highest attrition is among employees aged 26-35, suggesting a need for retention initiatives targeting younger professionals.
2. Job Roles with Critical Turnover: Laboratory Technicians and Sales Executives exhibit the highest turnover, signaling potential job dissatisfaction or mismatches in role expectations.
3. Low Salary Driving Attrition: Employees earning below 5K show the highest attrition, implying that compensation is a significant factor influencing employee departure.
4. Medical and Life Sciences Graduates at Risk: Employees with Medical and Life Sciences backgrounds have distinct attrition trends, indicating these groups may need more tailored engagement or development programs.
5. Gender Disparity in Attrition: Males have a higher attrition rate compared to females, suggesting potential issues that affect male employee retention more severely.
6. Early Tenure Employees Leaving: Attrition is highest for employees with less than one year of tenure, indicating onboarding or initial engagement issues.
These focused insights can help HR prioritize interventions and strategies in specific areas to reduce turnover and improve workforce stability.

# Overview of the dashboard
Here is the overview of the dashboard, for the actual interacting dashboard, check the [HR Analytics Dashboard](https://github.com/Analyze-with-Aniket/HR-Analytics-Report-Power-BI/blob/main/HR%20Analytics%20Dashboard.pbix).
![Screenshot 2024-10-02 122524](https://github.com/user-attachments/assets/14ea2f57-20ac-4b09-a600-fffd69cc3bf7)
