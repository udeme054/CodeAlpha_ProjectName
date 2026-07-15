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

# 📈 Dashboard Features
# Key Performance Indicators (KPIs)
# KPI	Value

* Student Count =	100
* Average Math Score = 62.51
* Average Writing Score = 60.53
* Average Reading Score =	60.49
* Maximum Math Score = 97

# Visualizations

The dashboard includes:
* Average Score Percentage by Ethnicity
* Average Score by Test Preparation Status
* Average Score by Parental Education
* Average Score by Gender
* Top 5 Students by Performance
* Ethnicity vs Parental Education (Sankey Diagram)

# Interactive Filters (Slicers)

Users can dynamically filter the report using:
* Ethnicity
* Gender
* Parental Education
* Test Preparation Status
* Student ID

# 📊 Key Insights

# Overall Performance
* The dataset contains 100 students.
* Students achieved an average Mathematics score of 62.51, which is slightly higher than both Reading (60.49) and Writing (60.53).
* The highest Mathematics score recorded is 97, demonstrating excellent performance by the top student.

# Test Preparation
* Students who completed the test preparation course achieved higher average scores than those who did not, suggesting that preparation contributes positively to academic success.

# Gender Performance
* Male and female students performed similarly overall, with only a slight difference in average scores, indicating relatively balanced academic performance between genders.

# Ethnicity Analysis
* Student performance varies slightly across ethnic groups, with Group A recording the highest average score, while differences among the remaining groups are relatively small.

# Parental Education
* Students whose parents attained Some College or a Bachelor’s Degree generally achieved higher average scores, indicating a positive relationship between parental education and academic performance.

# Top Performing Students
* The Top 5 student analysis highlights students with consistently strong scores across Mathematics, Reading, and Writing, providing opportunities to recognize academic excellence and identify best practices.

  
# Business Recommendations
Based on the dashboard insights, the following recommendations are proposed:

* Encourage all students to participate in test preparation programs, as completion is associated with improved academic performance.
* Provide additional academic support for students who are not participating in preparation courses.
* Develop targeted intervention programs for groups with comparatively lower average scores.
* Strengthen parent-school engagement initiatives to support student learning at home.
* Recognize and reward high-performing students to encourage academic excellence.
* Continuously monitor student performance using interactive dashboards to identify learning gaps early and guide instructional strategies.

# Project Workflow
1. Collected the student performance dataset.
2. Imported the data into Power BI.
3. Cleaned and transformed the dataset using Power Query.
4. Built the data model and relationships.
5. Created DAX measures for key performance indicators.
6. Designed interactive dashboard layouts.
7. Added charts, KPIs, slicers, and drill-down functionality.
8. Validated calculations and dashboard visuals.
9. Published the final Power BI report.

# Repository Structure
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
└── LICENSE

# Future Improvements
* Integrate attendance and classroom participation data.
* Build predictive models to identify students at risk of poor performance.
* Add trend analysis across academic terms or school years.
* Include teacher and subject-level performance analysis.
* Develop drill-through pages for individual student profiles.

# 👨‍💻 Author
Udeme Jackson
Aspiring Data Analyst | Power BI Developer | SQL | Excel | DAX | Power Query

# Connect With Me
* LinkedIn: www.linkedin.com/in/udeme-jackson-0a0887144
* GitHub: Add your GitHub profile URL
* Email: udemejackson2016@gmail.com
