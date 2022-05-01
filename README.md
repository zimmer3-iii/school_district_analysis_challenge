# School_District_Analysis_Challenge

## Overview of Project
A school board has asked for analysis of math and reading test score of students from different schools in the disctrict.
School board believes there was academic dishonesty and that score for 9th graders at Thomas High School are not to be used in the analysis. 
Deliverables requested and provided are listed here:

 1. Replace the 9th grade reading and math scores at Thomas High School with NaN
 2. District Summary (All schools totaled and averaged)
-	a.) Total Schools
-	b.) Total Students
-	c.) Total Budget
-	d.) Average Math Score
-	e.) Average Reading Score
-	f.) Percentage Passing Math
-	g.) Percentage Passing Reading
-	h.) Percentage Passing Overall
 3. School Summary (Scores for each school individually)
-	a.) School Type
-	b.) Total Schools
-	c.) Total Students
-	d.) Total Budget
-	e.) Average Math Score
-	f.) Average Reading Score
-	g.) Percentage Passing Math
-	h.) Percentage Passing Reading
-	i.) Percentage Passing Overall
 4. Top and bottom 5 performing schools
 5. Average Math scores by grade per school.
 6. Average Reading scores by grade per school.
 7. Scores based on spending per student.
 8. Scores based on school size.		

## Resources
- Data Source: schools_complete.csv, students.csv
- Software: Python 3.7.6, Jupyter Notebook, anaconda 1.9.0
	
## Results

Removing the 9th graders' scores from Thomas High Shcool had the following affects: 
- District summary affects:
	- Total Students decreased from 39,710 to 38,709.
	- Average Math Score decreased from 79.0 to 78.9.
	- Percentage Passing Math decreased from 75.0% to 74.8%.
	- Percentage Passing Overall decreased from 65.2% to 64.9%
- School summary affects (Only Thomas High School was affected):
	- Percentage Passing Math decreased from 93.27% to 93.18%.
	- Percentage Passing Reading decreased from 97.30% to 97.01%
	- Percentage Passing Overall decreased from 90.94 to 90.63%
- Math and Reading Scores by grade affects:
	- The only affect is that 9th graders at Thomas High School display a NaN for both reading and math scores.
- Scores by school spending affects:
	- None, the small percentage change wasn't enought to affect the results.
- Scores by school size affects:
	- None, the small percentage change wasn't enought to affect the results.
- Scores by school type
	- None, the small percentage change wasn't enought to affect the results.

## Summary
Removing the 9th graders' scores from Thomas High School had little affect on the summaries the school board
requested. Only when looking at the Thomas High School results can we see a small percentage change. While I
would have thought to see a more noticable change in the results, we only removed 461 students from a dataset of 39,170 students (~1.17%).
