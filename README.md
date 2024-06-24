# Exploring the Impact of School Funding, Class Sizes, and Student Success: A Data-Driven Analysis with Django and Python
This project explores how school funding, class sizes, and student success are interconnected by analyzing multiple datasets. The analysis utilizes Django for implementation, with Python and Pandas managing data manipulation and statistical analysis tasks.

## Research Question
- Is school size correlated to school performance?
- Is socioeconomic status correlated with school performance?
- What is the relationship between school size, student socioeconomic status, and school performance?

## Datasets Used
- School Fast Facts: Used to determine schools and regions of interest.
- District Fast Facts: Used to determine districts and regions of interest.
- Low Income Data for Public Schools: Percentage of economically disadvantaged students per school and the number of students per school.
- PSSA Exam: Percentage proficient in English, math, and science.
- Keystone Exam: Percentage proficient in algebra, literature, and biology.

## Database Schema
- School: Contains attributes such as school name, school number, AUN (Administrative Unit Number), and school type (high school, middle school, elementary school).
- District: Contains attributes such as district name, county ID, and AUN.
- County: Contains the county ID.
- Enrollment: Contains attributes like year, number of students, number of low-income students, and percentage of low-income students.
- Keystone Exam: Contains attributes related to student proficiency percentages in literature, algebra, and biology.
- PSSA Exam: Contains attributes related to student proficiency percentages in English, science, and math.

## Analysis
This project includes the following analyses
- Hypothesis Testing: To determine if there is a statistically significant relationship between school performance and factors like enrollment size and socioeconomic status.
- Regression Analysis: To quantify the relationship between the dependent variable (school performance) and independent variables (enrollment size and socioeconomic status).
- Data Visualization: Using Chart.js and jQuery for interactive graphs and charts.
