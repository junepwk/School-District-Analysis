# PyCitySchools with Pandas

## Overview of the School District Analysis
The task was to assist in analyzing data on school fundings and student's standardized test scores.  This analysis will provide the district school board with insight regarding school's budget allocation and priorities, as well as, assist the board in budget setting for the next school year. However, there has been evidence of academic dishonesty in regards to Thomas High School's ninth grade reading and math grades with NaNs. The solution was to refactor the code by replacing the Thomas High School's ninth grade standardized test scores and perform the same analysis over the new dataset. The chief data scientist for the city school districts had requested the following data for the analysis:

	1. Total number of schools, students, and budget
	2. Average math & reading scores
	3. Total percentage of students passing math
	4. Total percentage of students passing reading
	5. Total percentage of students passing both math and reading
	6. Budget per student
	7. A district summary
	8. A data summary for each school

## Resources
- Data Source: students_complete.csv, schools_complete.csv
- Software: Jupyter Notebook 6.3.0, Python 3.7.10

## Results
### District Summary
The affect of replacing Thomas High School's ninth grade test scores with NaNs values had minimal influence on the overall district summary with scores decreasing by 0.1%-0.3%
The total student count decreased by 461 students.  This shows that there were 461 Thomas High School ninth graders' scores that were nulled.

* Original District Summary
![district_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/district_summary.png)

* Updated District Summary
![new_district_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_district_summary.png)

### School Summary for Thomas High School
Since only Thomas High was the only school that required adjustments, other schools' summaries were not effected.  Similarly to the district summary, the updated results from the refactored code had minor changes from the original data.  The overall percentage of passing both math and reading went down by approximately 0.3%.

* Original School Summary
![labels](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/labels.png)
![ths_school_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/ths_school_summary.png)
* Updated School Summary
![new_ths_school_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_ths_school_summary.png)

### Thomas High School’s performance VS. Other Schools
The updated results showed that Thomas High School retained their 2nd place position out of 15 schools in the district.  Therefore, there are no effect to Thomas High School's performance relative to the other schools.

*Original Top 5 Schools
![top_five](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/top_five.png)
*Updated Top 5 Schools
![new_top_five](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_top_five.png)

### Math and Reading Scores by Grade
The only changes in the results when sorting scores based on grades were the replacement of the ninth grade's average score value with NaN.  This also applies for the reading category so to avoid clustering the README, only the math results will be shown. The reading scores by grades can be viewed [here](https://github.com/junepwk/school-district-analysis/tree/main/Resources).

* Original vs. Updated Math Scores by Grades  

![math_by_grade](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/math_by_grade.png) ![new_math_by_grade](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_math_by_grade.png)

## Additional Analysis

### Scores by school spending
Thomas High School's budget per student is $638 which falls into the $630-644 range that's highlighted below.  There were no changes in the data after refactoring the code.

![new_score_spending](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_score_spending.png)

### Scores by school size
Thomas High School's total student count is 1,635 which falls into the medium range highlighted below. There were no changes in the data after refactoring the code.

![new_score_size](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_score_size.png)

### Scores by school type
Thomas High School is a charter school and similarly to the results above, there were no changes in the data after nulling their ninth grade's scores.

![new_score_type](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_score_type.png)

## Summary
