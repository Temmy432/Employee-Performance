# Employee-Performance
This project leverages POWER BI to analyze employee performance metrics, aiming to identify key factors influencing productivity. The interactive dashboard provides actionable insights to enhance workforce efficiency and satisfaction.
# TABLE OF CONTENTS:
- **INTRODUCTION**
- **OBJECTIVES**
- **DATA SOURCE**
- **DATA OVERVIEW**
- **DATA PREPROCESSING**
- **VISUALIZATION AND ANALYSIS**
- **KEY INSIGHTS**
- **RECOMMENDATIONS**
- **CONCLUSION**

---

## INTRODUCTION
- This report provides a data-driven analysis of employee productivity, efficiency, and overall contribution to the organization. It helps HR and management teams track performance trends, identify top performers, and address areas needing improvement.  
- By leveraging **Power BI**, this report offers interactive dashboards that provide real-time insights into workforce performance.  
- It also evaluates employee performance at **OPTA.NG** using key performance indicators (**KPIs**) such as average performance score, total projects, working hours, salaries, and employee satisfaction levels.  

---

## OBJECTIVES  
The objective of this analysis is to:  

- **Optimize Workforce Allocation:** Ensure efficient distribution of working hours and employee count across departments to maintain productivity.  
- **Enhance Compensation Strategies:** Address salary disparities by reviewing compensation structures to ensure fair pay distribution.  
- **Improve Sales Department Performance:** Develop targeted initiatives to increase working hours, productivity, and salary competitiveness in the sales department.  
- **Boost Employee Satisfaction Across Age Groups:** Implement engagement programs tailored to different age demographics to improve overall job satisfaction.  
- **Refine HR Salary Policies:** Assess the impact of high average salaries in Human Resources and align with the organizational compensation framework.  
- **Standardize Salary Distribution:** Reduce pay inconsistencies by establishing transparent and equitable salary policies.  

---

## DATA SOURCE  
- The dataset, **employee_performance.xlsx**, contains employee-related information, including employee IDs, performance scores, department details, attendance records, project contributions, and key performance indicators (**KPIs**).  
- This dataset was provided in Excel format and served as the primary source for the data cleaning and analysis process.  
- It was provided by **Tech Studio Academy** as part of the internship program, serving as a practical case study for applying data analysis, visualization, and performance evaluation techniques.  
- Using the `data.shape` function, it was discovered that the dataset contains **151 rows and 10 columns**, providing a comprehensive set of employee performance data for analysis.  

---

## DATA OVERVIEW  
The dataset consists of **151 rows and 10 columns**. It contains employee information, performance metrics, and salary details. The columns include:  

- **Employee ID:** Unique identifier for each employee (e.g., EMP1000, EMP1001).  
- **Name:** Placeholder for employee names (all listed as "Employee").  
- **Department:** The department where the employee works (e.g., Finance, Marketing, IT, Sales).  
- **Joining Date:** The date when the employee joined the company.  
- **Age:** The age of the employees.  
- **Monthly Salary:** The salary received by the employee per month.  
- **Performance Score:** A rating of the employee’s performance (scale unknown but varies between **1 to 5**).  
- **Projects Completed:** Number of projects successfully completed by the employee.  
- **Hours Per Week:** The number of hours the employee works in a week.  
- **Satisfaction Level:** A numerical value indicating the employee's satisfaction with their job (**ranging from 0 to 1**).  

![](Images/Screenshot%202025-02-27%20141916.png)
---

## DATA PREPROCESSING  
To ensure the data is accurate and reliable for analysis, preprocessing is essential. This involved multiple steps to clean, transform, and organize the data for meaningful insights:  

- **Data Cleaning:** Removing inconsistencies, duplicates, or missing values to improve accuracy.  
- **Aggregation:** Summing up total hours and salaries.  
- **Categorization:** Grouping employees based on department, salary range, and age groups.  

---

## VISUALIZATION AND ANALYSIS  

### **Total Hours Per Week by Department**
- Marketing has the highest total working hours per week.  
- Other departments, including Information Technology, Human Resources, and Finance, have nearly equal working hours.  
- Sales has the least working hours per week.  

![](Images/Screenshot%202025-02-15%20171606.png)

### **Count of Employee ID by Department**
- Marketing has the highest number of employees (**40 employees, 26.67%**).  
- Finance and Information Technology follow with **31 (20.67%)** and **27 (18%)** employees, respectively.  
- Sales has the least number of employees (**23 employees, 15.33%**).

    ![](Images/Screenshot%202025-02-15%20171633.png)

### **Count of Monthly Salary by Salary Range**
- The majority of employees earn between **5K and 15K** per month.  
- There is a significant variation in salary distribution, indicating different compensation structures across departments.  

![](Images/Screenshot%202025-02-15%20171651.png)

### **Average Monthly Salary by Department**
- **Human Resources** has the highest average salary (**$10,332.05**).  
- **Finance** and **Marketing** have comparable average salaries (**$9,966.40** and **$9,655.42**, respectively).  
- **Sales** has the lowest average salary (**$8,793.27**).  

![](Images/Screenshot%202025-02-15%20171702.png)

### **Average Satisfaction Level by Age**
- Employee satisfaction fluctuates across different age groups.  
- Satisfaction tends to increase and decrease irregularly, indicating that **age alone may not determine job satisfaction**.

![](Images/Screenshot%202025-02-15%20171751.png)

### **Total IT Projects by Department**
- IT projects are distributed across multiple departments, with **Finance, Human Resources, and Marketing** having a significant share.  

![](Images/Screenshot%202025-02-15%20171727.png)

---

## KEY INSIGHTS  
- **Marketing employees** contribute the most working hours and have the highest employee count.  
- Despite having fewer employees, **Human Resources** has the highest average salary.  
- **Sales** has the lowest working hours and salaries, suggesting a possible need for improvement in that department.  
- Satisfaction levels fluctuate across different age groups, highlighting the need for **targeted engagement strategies**.  
- **Salary distribution varies significantly**, which may indicate disparities in compensation policies.  

---

## RECOMMENDATIONS  

### **Optimize Workload Distribution in Marketing:**  
- Assess workload efficiency and consider redistributing tasks to prevent burnout.  
- Implement automation tools to improve productivity and reduce manual effort.  

### **Enhance Compensation Strategies:**  
- Conduct a salary benchmarking analysis to ensure fair and competitive pay across all departments.  
- Develop structured salary scales to minimize disparities and enhance employee retention.  

### **Improve Sales Department Performance:**  
- Increase training and development programs to enhance employee skills and boost productivity.  
- Evaluate workload and incentives to attract and retain top talent.  

### **Implement Targeted Employee Engagement Programs:**  
- Conduct regular employee satisfaction surveys to identify pain points.  
- Develop age-specific engagement strategies to improve morale and job satisfaction.  

### **Standardize Compensation Policies:**  
- Establish clear guidelines for salary increments and promotions based on performance and experience.  
- Implement data-driven compensation decisions to reduce wage disparities and increase employee motivation.  

---
![](Images/Screenshot%202025-02-15%20171818.png)
## CONCLUSION  
- The **Employee Performance Analysis** for **OPTA.NG** highlights key areas that impact workforce productivity, compensation, and satisfaction levels.  
- **Marketing** contributes the highest working hours, while **Human Resources** leads in salary averages despite having fewer employees.  
- The **Sales department** shows the lowest working hours and salaries, signaling a need for improvement.  
- Additionally, **fluctuations in satisfaction levels across age groups** and **significant salary disparities** indicate the necessity for strategic engagement and compensation adjustments.  
- To address these findings, **implementing workforce optimization, salary standardization, and targeted engagement strategies** will enhance overall productivity and employee satisfaction.  
- A **data-driven approach** to decision-making will ensure **fair compensation policies, better resource allocation, and improved performance across all departments**.  
