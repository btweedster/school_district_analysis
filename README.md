# School District Analysis
An analysis of school district data, comparing and contrasting public and charter schools for budget, number of students and grades.

## Overview
Data Source: 
- [new_full_student_data.csv](resources/new_full_student_data.csv)

Analysis:
- [Student_Data_Challenge.ipynb](Student_Data_Challenge.ipynb)

Software / Tools:
 - Python 3.7.13
 - Pandas 1.3.5
 - Jupyter Notebook 6.4.12

## Findings
### Math Scores
Charter schools seemed to generally perform better regarding the average math scores for each grade. However the public school grade 12 average math score is greater than in charter schools.

### Budgets
The average public school budget is greater than the average public school budget. The public school budget is approximately 4.4% above the charter school budget.

## Further Analysis
### Cost per Student
Further analysis should involve comparing the above budgets with student body size, that is, what is the average ratio of school budget to number of students per school. This should be looked at for each school and by school type. Additionally this should be compared with student performance, to see if there is a correlation between school budget and student performance.

### Missing Data
There is a significant amount of missing math and reading scores. Some data points are missing both, while some are only missing one or the other. It would be worthwhile to *consider* including rows in the analysis where data is available instead of removing the whole row. Ideally, we would investigate the cause of the missing data first.