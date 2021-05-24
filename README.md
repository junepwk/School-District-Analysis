# PyCitySchools with Pandas

## Overview of the School District Analysis
The task was to assist in analyzing data on school fundings and student's standardized test scores.  This analysis will provide the district school board with insights regarding school's budget allocation and priorities, as well as, assist the board in budget setting for the next school year. However, there had been evidence of academic dishonesty regarding to Thomas High School's ninth grade reading and math grades with NaNs. The solution was to refactored the code by replacing the Thomas High School's ninth grade standardized test scores and perform the same analysis over the new dataset. The chief data scientist for the city school districts had requested the following data for the analysis:

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

* Original District Summary
![district_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/district_summary.png)

* Updated District Summary
![new_district_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_district_summary.png)

### School Summary for Thomas High School
Similarly to the district summary, the updated results from the refactored code had minor changes from the original data.  The overall percentage of passing both math and reading went down by approximately 0.3%.

* Original School Summary
![labels](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/labels.png)
![ths_school_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/original_data/ths_school_summary.png)
* Updated School Summary
![new_ths_school_summary](https://github.com/junepwk/school-district-analysis/blob/main/Resources/new_data/new_ths_school_summary.png)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
post top 5

### How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
Scores by school spending
Scores by school size
Scores by school type

## Summary
