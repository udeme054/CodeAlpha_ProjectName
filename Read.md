# Project Overview
The Workforce Analytics Dashboard is an interactive Power BI solution designed to provide HR professionals, business leaders, and decision-makers with a comprehensive view of workforce composition, employee performance, and organizational health.

The dashboard consists of two pages:

* Workforce Profile Dashboard – Provides insights into employee demographics, workforce distribution, employment trends, salary analysis, and workforce cost.
* Performance Dashboard – Evaluates employee productivity, engagement, satisfaction, performance ratings, career growth, and bonus distribution.
Together, these dashboards enable organizations to monitor workforce KPIs, identify performance gaps, optimize human resource planning, and support strategic decision-making.

# Dashboard Preview
1. Workforce Profile Dashboard

2. Performance Dashboard

# Project Objectives
The primary objectives of this dashboard are to:
* Analyze workforce demographics
* Monitor workforce growth over time
* Evaluate employee performance
* Measure employee engagement and satisfaction
* Analyze workforce cost and salary distribution
* Identify career growth opportunities
* Support HR strategic planning
* Improve employee retention

# Business Problem
Organizations often struggle to answer questions such as:
* How many active employees do we have?
* What is our turnover rate?
* Which age groups dominate the workforce?
* How productive are employees?
* Which employees need performance improvement?
* Which departments require additional investment?
* Are employees satisfied and engaged?
* How are bonuses distributed across job levels?
This dashboard provides a centralized solution for answering these questions.

# Dataset
The dataset contains employee information including:
* Employee ID
* Gender
* Age
* Age Group
* Department
* Job Level
* Employment Type
* Salary
* Bonus
* Performance Rating
* Productivity Score
* Satisfaction Score
* Engagement Score
* Manager Evaluation
* Career Growth Category
* Employment Status
* Store
* State
* Hire Date
* Termination Status

# Tools Used
* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* Microsoft Excel (Data Preparation)

# Data Cleaning Process
The following transformations were performed in Power Query:
* Removed duplicate records
* Corrected missing values
* Standardized text formatting
* Changed incorrect data types
* Created Age Groups
* Created Salary Bands
* Standardized department names
* Cleaned employment status values
* Removed unnecessary columns
* Created Date hierarchy

# Data Modeling
The project follows a Star Schema consisting of:

# Fact Table
Employee Fact Table

# Dimension Tables
* Employee
* Department
* Date
* Job Level
* Store
* State
Relationships were created using primary and foreign keys to optimize report performance.

# DAX Measures
Examples of DAX measures used include:
* Total Employees
* Active Employees
* Turnover Rate %
* Average Salary
* Annual Workforce Cost
* Average Productivity Score
* Average Satisfaction Score
* Average Performance Rating
* Average Manager Evaluation
* Average Engagement Index
* Monthly Bonus
* Employee Count

# Workforce Profile Dashboard
Key Performance Indicators (KPIs)
KPI	Value
* Total Employees = 7,500
* Active Employees =	6,009
* Turnover Rate =	19.9%
* Annual Workforce Cost =	204.4M
* Average Salary = 27.25K
* Stores = 150

# Visualizations
* Employment Type Distribution
* Manager Status Distribution
* Salary Band Distribution
* Employee Headcount Trend
* Workforce Distribution by Age Group
* Gender Distribution
* Geographic Employee Distribution (USA Map)

# Interactive Filters
* Employee Status
* State
* Year
* Age Group
* Department
* Education Level
* Job Level

# Performance Dashboard

# Key Performance Indicators (KPIs)
# KPI	Value

* Total Employees =	7,500
* Average Productivity Score = 73.95
* Average Performance Rating = 3.91
* Average Satisfaction Score = 74.50
* Average Manager Evaluation = 3.91
* Average Engagement Index = 74.30

# Visualizations
* Performance Rating Category
* Satisfaction Category
* Evaluation Category
* Career Growth Category
* Performance by Age Group
* Bonus by Job Level
* Gender Distribution
* Department Analysis

# Interactive Filters
* Employee Status
* Gender
* Age Group
* Department
* Education Level
* Job Level

# Key Insights
# Workforce Profile
* Total workforce consists of 7,500 employees.
* 6,009 employees are currently active.
* Turnover rate is 19.9%, indicating opportunities to improve employee retention.
* Most employees are Full-Time.
* Majority of employees fall within the 26–35 age group.
* Male employees account for approximately 72% of the workforce, while females represent 28%.
* Medium salary band contains the highest number of employees.
* Workforce has experienced consistent growth over recent years.

# Performance Dashboard
* Average productivity score is 73.95/100.
* Average employee satisfaction is 74.50/100.
* Performance rating averages is 3.91/5.
* Majority of employees fall within the Good performance category.
* Poor Career Growth category contains the largest employee population, highlighting opportunities for development.
* Entry-level employees receive the highest total bonus allocation.
* Employees aged 26–35 contribute the highest overall performance.

# Business Recommendations
* Develop structured career progression programs to reduce the number of employees experiencing poor career growth.
* Implement targeted retention strategies to lower turnover rates.
* Increase leadership development and mentorship initiatives.
* Introduce performance improvement plans for low-performing employees.
* Enhance employee engagement through regular feedback and recognition programs.
* Review bonus allocation to ensure fairness and alignment with performance outcomes.
* Continue investing in workforce planning using data-driven insights.

# Project Workflow
1. Collected HR employee dataset.
2. Imported data into Power BI.
3. Cleaned and transformed data using Power Query.
4. Built a star schema data model.
5. Created calculated columns and DAX measures.
6. Designed the Workforce Profile dashboard.
7. Designed the Employee Performance dashboard.
8. Added slicers and interactive filtering.
9. Validated KPIs and visualizations.
10. Published the final Power BI report.

# Photo Gallery
Workforce Profile Dashboard
![Alt text](https://github.com/udeme054/CodeAlpha_ProjectName/blob/aa5e6de2e88e583d4a2e938ee6a1a1c904155328/Task%202%20HR%20ANALYTICS%20FOR%20CODEALPHA/Workforce%20Profile%20Dashboard.jpg)

Performance Dashboard
![Alt text](https://github.com/udeme054/CodeAlpha_ProjectName/blob/11d732ade2ef580faea4b5bacbc1dfd917490668/Task%202%20HR%20ANALYTICS%20FOR%20CODEALPHA/Performance%20Dashboard.jpg)

Tooltip
![Alt text](https://github.com/udeme054/CodeAlpha_ProjectName/blob/6c3d99617f627ab7b01496a127d6576557a02628/Task%202%20HR%20ANALYTICS%20FOR%20CODEALPHA/Tooltip.jpg)

# 📁 Repository Structure
Student-Performance-Analysis-Dashboard/
│
├── Dataset/
│   └── Student_Performance_Dataset.xlsx
│
├── Dashboard/
│   └── Student Performance Analysis Dashboard.pbix
│
├── Images/
│   └── Student Performance Analysis Dashboard.jpg
│
├── README.md

# Future Improvements
* Integrate attendance and classroom participation data.
* Build predictive models to identify students at risk of poor performance.
* Add trend analysis across academic terms or school years.
* Include teacher and subject-level performance analysis.
* Develop drill-through pages for individual student profiles.

# 👨‍💻 Author
Udeme Jackson
Aspiring Data Analyst | Power BI Developer | SQL | Excel | DAX | Power Query

# 🤝 Connect With Me
* LinkedIn: www.linkedin.com/in/udeme-jackson-0a0887144
* GitHub: https://github.com/udeme054/CodeAlpha_ProjectName.git
* Email: udemejackson2016@gmail.com
