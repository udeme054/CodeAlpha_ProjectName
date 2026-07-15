# Project Overview
The Student Performance Analysis Dashboard is an interactive Power BI dashboard developed to analyze students' academic performance across Mathematics, Reading, and Writing. The dashboard provides educators, school administrators, and stakeholders with valuable insights into student achievement by examining demographic and educational factors such as gender, ethnicity, parental education level, and test preparation course completion.

This project transforms raw educational data into meaningful visual insights that support data-driven decisions aimed at improving student learning outcomes.

# Project Objectives

The dashboard was designed to:
* Monitor overall student academic performance.
* Compare scores across Mathematics, Reading, and Writing.
* Analyze performance by gender and ethnicity.
* Evaluate the impact of parental education on student achievement.
* Measure the effect of test preparation courses on academic performance.
* Identify high-performing students.
* Support educators with actionable insights for improving student outcomes.

# Business Problem
Educational institutions often face challenges in answering important questions such as:
* What is the overall academic performance of students?
* Does completing a test preparation course improve student performance?
* How does parental education influence student achievement?
* Are there significant differences in performance across ethnic groups?
* Which students consistently perform at the highest level?
* Is there a performance gap between male and female students?

This dashboard provides a centralized solution for answering these questions through interactive visualizations.

# Dataset
The dataset contains academic records of 100 students, including:

* Student ID
* Gender
* Ethnicity
* Parental Level of Education
* Test Preparation Status
* Math Score
* Reading Score
* Writing Score

# Tools Used
* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel (Data Preparation)

# Data Cleaning Process

The following data preparation steps were completed using Power Query:
* Removed duplicate records.
* Checked and handled missing values.
* Corrected inconsistent text formatting.
* Standardized categorical values.
* Verified data types.
* Renamed columns for consistency.
* Removed unnecessary fields.
* Validated score ranges.

# Data Modeling
A simple relational model was implemented with:

# Fact Table
* Student Performance
* Dimension Tables
* Student
* Gender
* Ethnicity
* Test Preparation
* Parental Education

This structure improves report performance and simplifies analysis.

# DAX Measures

The dashboard includes several calculated measures, including:
* Student Count
* Average Math Score
* Average Reading Score
* Average Writing Score
* Maximum Math Score
* Average Score %
* Top Student Score
* Performance Ranking
