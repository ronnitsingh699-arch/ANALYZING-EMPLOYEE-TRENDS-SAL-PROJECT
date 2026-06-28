# 📊 Analyzing Employee Trends Using SQL

## 📌 Project Overview

Employee trend analysis is essential for understanding workforce behavior, improving employee satisfaction, and reducing attrition. This end-to-end SQL project analyzes Human Resource (HR) data to uncover meaningful insights related to employee demographics, departmental distribution, job satisfaction, business travel, and employee attrition.

Using SQL, this project transforms raw HR data into actionable business insights that can support Human Resource managers in making data-driven decisions for workforce planning and employee retention.

---

# 🎯 Project Objective

The primary objective of this project is to analyze HR employee data using SQL and identify workforce trends that help organizations:

* Understand employee distribution across departments.
* Analyze employee demographics.
* Measure job satisfaction levels.
* Identify high attrition employee segments.
* Evaluate the impact of education, marital status, and business travel on employee engagement.
* Support strategic HR decision-making through data analysis.

---

# ❓ Problem Statement

Organizations often struggle to understand the factors affecting employee satisfaction and attrition. High employee turnover increases recruitment costs and impacts productivity.

The objective of this project is to use SQL to analyze employee data and answer important business questions such as:

* Which department has the highest number of employees?
* Which age groups have higher attrition?
* Does education influence job satisfaction?
* Which departments have the highest and lowest employee satisfaction?
* How does business travel affect employee engagement?

---

# 📂 Dataset Description

**Dataset Name:** HR Employee Analytics Dataset

**Database:** `hr_data`

**Table:** `hrdata`

### Dataset Information

* Total Employees: **1,470**
* Total Columns: **15**
* Domain: **Human Resource Analytics**

### Important Columns

* Employee Number
* Age
* Age Band
* Gender
* Department
* Job Role
* Education
* Education Field
* Marital Status
* Business Travel
* Job Satisfaction
* Attrition
* Active Employee Indicator

---

# 🗄 Database Schema

Since this project uses a **single HR table**, an ER Diagram is not applicable.

### Table Structure

```
hrdata
│
├── emp_no
├── age
├── age_band
├── gender
├── department
├── job_role
├── education
├── education_field
├── marital_status
├── business_travel
├── job_satisfaction
├── attrition
├── attrition_label
├── employee_count
└── active_employee
```

---

# 🛠 SQL Concepts Used

This project demonstrates the use of multiple SQL concepts, including:

* SELECT Statements
* WHERE Clause
* GROUP BY
* ORDER BY
* Aggregate Functions

  * COUNT()
  * AVG()
  * SUM()
* CASE Statements
* Conditional Aggregation
* UNION ALL
* LIMIT
* Business-Oriented Analytical Queries

> **Note:** This project uses a single table, so concepts like JOINs, CTEs, Window Functions, and Subqueries were not required.

---

# 📈 Key Queries & Business Insights

### 1. Employee Distribution by Department

* Counted employees in each department.
* Identified workforce distribution across business units.

---

### 2. Average Employee Age by Department

* Compared average employee age across departments.
* Helped identify demographic patterns.

---

### 3. Most Common Job Roles

* Identified the most frequent job role within each department.

---

### 4. Job Satisfaction by Education Level

* Measured average satisfaction for employees with different education levels.

---

### 5. Average Age by Job Satisfaction

* Examined the relationship between employee age and satisfaction.

---

### 6. Attrition Rate by Age Band

* Calculated attrition percentage for each age group.
* Identified age segments with higher employee turnover.

---

### 7. Department with Highest & Lowest Satisfaction

* Compared average job satisfaction across departments.
* Highlighted best and worst performing departments.

---

### 8. Highest Attrition Segment

* Identified employee categories experiencing the highest attrition.

---

### 9. Satisfaction Among Frequent Travelers

* Analyzed job satisfaction for employees who travel frequently.

---

### 10. Satisfaction Among Married Employees

* Evaluated satisfaction trends among married employees.

---

# 📊 Business Insights

The analysis revealed several valuable workforce trends:

* Workforce distribution varies significantly across departments.
* Employee satisfaction differs by education level.
* Certain age groups experience higher attrition than others.
* Business travel appears to influence employee engagement.
* Department-wise satisfaction analysis highlights opportunities for HR improvement.
* Identifying high-risk employee groups enables targeted retention strategies.

---

# ✅ Conclusion

This project demonstrates how SQL can be used to solve real-world HR analytics problems by transforming raw employee data into actionable business insights.

Through descriptive analysis and business-focused SQL queries, the project identifies trends in employee demographics, satisfaction, and attrition that can support strategic Human Resource decisions.

This project also strengthened my SQL skills in data aggregation, conditional analysis, and business reporting, making it a strong addition to my Data Analytics portfolio.

---

## 🚀 Tools Used

* MySQL
* MySQL Workbench
* SQL

---

## 👨‍💻 Author

**Ronnit Singh**

Aspiring Data Analyst.




