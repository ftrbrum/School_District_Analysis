# School_District_Analysis

## Project Overview:

The school board has noticed evidence of academic dishonesty within the Thomas High School ninth graders.  We have been contacted by Maria to replace the math and reading scores with NaNs for the Thomas School ninth graders.  We have set out to complete:

1. Replace reading and math scores to NaNs for Thomas High School ninth grade.
2. Repeat the district summary with updated data.
3. Repeat the school summary with updated data.
4. Find the new overall passing rate for the top 5 and bottom 5 performing schools.
5. Find the new average reading and math score for each grade level from each school
6. Find the new scores by school for spending per student, by school size, and by school type
7. Compare the new results with the previous results

## Resources:

 Data Source: [students_complete.csv](Resouces/students_complete.csv)
 
 Software: Python 3.7.6, Visual Studio Code, 1.56.0
 
 Code:PyCitySchools_Challenge.py

## School_District_Analysis Results:

1. Showing reading and match scores for Thomas High School have been replaced with NaNs values.
![Thomas_HS_NaNs.png](Resources/Thomas_HS_NaNs.png)

2. The new district summary vs the previous district summary.
![District_Summary.png](Resources/District_Summary.png)
![Prev_District_Summary.png](Resources/Prev_District_Summary.png)

3. The new school summary vs the previous school summary.
![School_Summary.png](Resources/School_Summary.png)
![Prev_School_Summary.png](Resources/Prev_School_Summary.png)

4. The new Top 5 and Bottom 5 schools.
![Top_5_Schools.png](Resources/Top_5_Schools.png)
![Bottom_5_Schools.png](Resources/Bottom_5_Schools.png)

5. The new average reading and math score for each grade level from each school
![Average_Reading.png](Resources/Average_Reading.png)
![Average_Math.png](Resources/Average_Math.png)

6. The new scores by school for spending per student, by school size, and by school type.
![Spending_Per_Student.png](Resources/Spending_Per_Student.png)
![Spending_Per_School_Size.png](Resources/Spending_Per_School_Size.png)
![Spending_Per_School_Type.png](Resources/Spending_Per_School_Type.png)


## School_District_Analysis Summary:
The audit of the election shows that:

With the information at hand using "election_results.csv" we determined that there were 3 candiates in the election over 3 counties.  The candidates in the election were Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane.  While the election took place in Arapahoe, Denver and Jefferson Counties.  The congressional election contained 369,711 votes.  Diana DeGette was declared the winner with 73.8% (272,892 votes) of the popular vote.  Denver County had the largest voter turnout in the election with 82.8% (306,055) of votes cast in the election.  See the above for a list containing all the information we recorded.
    
## School_District_Analysis Proposal:
With the script we have produced you will be able to find the accurate totals of any County election with a few minor tweaks.  It is a matter of lining up the header rows to match the County and Candidates, as well as finding the proper path to the source file.  This script can also be used for any Municipal, Senitorial, or Federal Election.
