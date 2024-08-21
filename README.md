# Student Placement Data Analysis Report
![image_720](https://github.com/user-attachments/assets/fb324a4a-76f0-48d0-9c25-0266a9e0edf1)


## Table of Contents
- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [Methodology](#methodology)
  - [Ask](#ask)
  - [Prepare](#prepare)
  - [Process](#process)
  - [Analyze](#analyze)
  - [Act](#act)
- [Findings](#findings)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

## Introduction
This report analyzes the placement data of students to gain insights into factors affecting their job placement, salary distribution, and academic performance. The visualizations were created using Power BI, focusing on various attributes such as gender, education, work experience, and specialization.

## Dataset Overview
The dataset used for this analysis contains records of students' academic and placement details. Key features include:
- Gender
- Degree Type
- Work Experience
- Specialization
- Academic Percentages (SSC, HSC, MBA)
- Salary
- Placement Status

## Methodology

### Ask
The primary objective of this analysis is to identify trends and factors that influence students' placement outcomes and salaries. Key questions include:
- How does gender impact placement status?
- What is the distribution of salaries among placed students?
- Does work experience significantly affect placement outcomes and salary?
- How do academic percentages correlate with salary?

### Prepare
The dataset was cleaned and prepared by ensuring no missing values for essential features. Salary values were carefully analyzed, and necessary bins were created to segment the data into meaningful categories.

### Process
Data preprocessing involved:
- **Handling Missing Values:** Particularly in the salary column.
- **Data Transformation:** Creating bins for salary to observe distribution patterns.
- **Feature Selection:** Choosing relevant features like gender, status, work experience, and degree type for visual analysis.

### Analyze
The analysis was conducted through a series of visualizations:
- **Placement Status by Gender:** A bar chart comparing the placement status between male and female students.
- **Salary Distribution:** A histogram showing the salary range among students.
- **Salary by Degree Type:** A box plot to compare salaries across different degree types.
- **MBA Percentage vs. Salary:** A scatter plot depicting the relationship between MBA percentage and salary.
- **Work Experience Distribution:** A pie chart illustrating the proportion of students with and without work experience.

### Act
Based on the analysis, actionable insights can be derived for educational institutions to focus on areas like work experience and specialization to improve placement outcomes. Employers can also use these insights to tailor their recruitment strategies.

## Visualizations
![image_360](https://github.com/user-attachments/assets/5efeef4e-6059-475e-92ec-67d387d97449)

Count of Status by Gender: The distribution of placement status is relatively balanced between male and female students. However, a slightly higher number of males are placed compared to females, indicating no significant gender disparity in placement outcomes.

![image_360](https://github.com/user-attachments/assets/78f7bbd5-7043-4a5d-88a7-ffa94c589820)

Sum of Salary by Salary Bin: The salary distributions across different salary bins reveal that a majority of students are concentrated in the lower salary ranges. The highest frequency is observed in the bin for salaries between 300,000 and 400,000, suggesting that most placed students earn within this range.

![image_360](https://github.com/user-attachments/assets/61b4b2db-a27d-4d2f-8958-2361d081b448)

Salary by MBA Percentage: The scatter plot indicates a positive correlation between MBA percentage scores and salaries. As MBA percentages increase, there appears to be a tendency for salaries to increase as well, although the distribution is wide, indicating variability in salary outcomes.

![image_360](https://github.com/user-attachments/assets/6086f0fe-a4e1-438a-8996-73d4d2b466d9)

Sum of Students by Work Experience: The pie chart shows that a significant majority (approximately 63.97%) of students do not have work experience. This could imply that most students are entering the job market without prior professional experience, which may influence placement opportunities.

![image_360](https://github.com/user-attachments/assets/c16c2daa-cb2c-4863-b083-d81e84d2a7d0)

Sum of Students by HSC Board: The bar chart showcases a higher number of students from the Central Board compared to those from Other Boards. This could indicate a preference or trend in the education background of students who pursued further studies.

![image_360](https://github.com/user-attachments/assets/0f6b25a3-7b37-4b01-aa92-dee21652c9fc)

Sum of Students by HSC Specialization: The bar chart indicates that a larger proportion of students specialized in Commerce compared to those in Science and Arts. This may reflect current educational trends or preferences among students.


## Findings
- **Gender Impact on Placement:** Both genders have similar placement opportunities, with slightly more males being placed.
- **Salary Distribution:** Most salaries fall within the 200,000 to 300,000 INR range, with few students earning significantly higher.
- **Degree Type and Salary:** Students from Commerce & Management tend to have higher median salaries compared to those in Science & Technology.
- **MBA Percentage vs. Salary:** There is a weak correlation between MBA percentage and salary, with work experience playing a more critical role in higher earnings.
- **Work Experience:** A significant portion of students has no work experience, yet those with experience tend to have better placement outcomes.

## Limitations
- **Sample Size:** The dataset may not be large enough to generalize findings across all educational institutions.
- **Data Scope:** Limited to students' academic performance and work experience; other factors like interview skills, internships, and extracurricular activities are not considered.
- **Salary Data:** Some salary values are missing, which might affect the accuracy of the salary distribution analysis.

## Conclusion
This report provides a comprehensive analysis of the factors influencing student placements and salaries, offering valuable insights for both educational institutions and employers.
