# School_District_Analysis_Challenge

## Overview of Project
A school board has asked for analysis of math and reading test score of students from different schools in the disctrict.
School board believes there was academic dishonesty and that score for 9th graders at Thomas High School are not to be used in the analysis. 
Deliverables requested and provided are listed here:

 1. Replace the 9th grade reading and math scores at Thomas High School with NaN
 2. District Summary (All schools totaled and averaged)
	a.) Total Schools
	b.) Total Students
	c.) Total Budget
	d.) Average Math Score
	e.) Average Reading Score
	f.) Percentage Passing Math
	g.) Percentage Passing Reading
	h.) Percentage Passing Overall
 3. School Summary (Scores for each school individually)
	a.) School Type
	b.) Total Schools
	c.) Total Students
	d.) Total Budget
	e.) Average Math Score
	f.) Average Reading Score
	g.) Percentage Passing Math
	h.) Percentage Passing Reading
	i.) Percentage Passing Overall
	
 4. The total number of votes each candidate won
 5. The winner of the election base on popular vote.
 6. The voter turnout for each county.
 7. The percentage of votes from each county out of the total count.
 8. The county with the highest turnout.		

## Resources
- Data Source: schools_complete.csv, students.csv
- Software: Python 3.7.6, Jupyter Notebook, anaconda 1.9.0
	
## Results
The analysis of the data shows that:
- There were 369,711 votes cast in the election.
- There were 3 candidates and 3 counties.
### Election Results
-------------------------
    Total Votes: 369,711
    -------------------------

    County Votes:
    Jefferson: 10.5% (38,855)
    Denver: 82.8% (306,055)
    Arapahoe: 6.7% (24,801)
    -------------------------
    Largest County Turnout: Denver
    Largest County Votes: 306,055
    Voting Percentage: 82.8%
    -------------------------
    Charles Casper Stockham: 23.0% (85,213)
    Diana DeGette: 73.8% (272,892)
    Raymon Anthony Doane: 3.1% (11,606)
    -------------------------
    Winner: Diana DeGette
    Winning Vote Count: 272,892
    Winning Percentage: 73.8%
    -------------------------

## Summary
A few notes about the python script used for this analysis:
- This script can be used for any election result with at least 1 candidate and 1 county.
- This script must be udpated if the election data is not stored in a folder called "Resources" and/or the script is not
run from a folder containing the "Resources" folder.
- Similarly the script will not print the results to a text file if there is not a folder called "analysis".
- An improvement that could be made is to have the results display the numbers of votes and percentage of votes
 each candidate got from each county.
