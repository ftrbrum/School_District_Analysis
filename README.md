# School_District_Analysis

## Project Overview:

The school board has noticed evidence of academic dishonesty within the Thomas High School ninth graders.  To uphold state-testing standards we have been contacted by Maria to replace the math and reading scores with NaNs (not a number) for the Thomas School ninth graders.  We have set out to complete the following:

1. Replace reading and math scores to NaNs for Thomas High School ninth grade.
2. Repeat the district summary with updated data.
3. Repeat the school summary with updated data.
4. Find the new overall passing rate for the top 5 and bottom 5 performing schools.
5. Find the new average reading and math score for each grade level from each school
6. Find the new scores by school for spending per student, by school size, and by school type
7. Compare the new results with the previous results

## Resources:

 Data Source: [students_complete.csv](Resouces/students_complete.csv)
 
 Software: Jupyter Notebook, Anaconda 4.10.1, Python 3.7.6, Visual Studio Code, 1.56.0
 
 Code: [PyCitySchools_Challenge.ipynb](PyCitySchools_Challenge.ipynb)

## School_District_Analysis Results:

### Showing reading and match scores for Thomas High School have been replaced with NaNs values.
![Thomas_HS_NaNs.png](Resources/Thomas_HS_NaNs.png)

### The new district summary vs the previous district summary.
![District_Summary.png](Resources/District_Summary.png)

![Prev_District_Summary.png](Resources/Prev_District_Summary.png)

### The new school summary vs the previous school summary.
![School_Summary.png](Resources/School_Summary.png)

![Prev_School_Summary.png](Resources/Prev_School_Summary.png)

### The new Top 5 and Bottom 5 schools.
![Top_5_Schools.png](Resources/Top_5_Schools.png)

![Bottom_5_Schools.png](Resources/Bottom_5_Schools.png)

### The new average reading and math score for each grade level from each school
![Average_Reading.png](Resources/Average_Reading.png)

![Average_Math.png](Resources/Average_Math.png)

### The new scores by school for spending per student, by school size, and by school type.
![Spending_Per_Student.png](Resources/Spending_Per_Student.png)

![Spending_Per_School_Size.png](Resources/Spending_Per_School_Size.png)
+
![Spending_Per_School_Type.png](Resources/Spending_Per_School_Type.png)


## School_District_Analysis Summary:

There were 461 grade nine students at Thomas High School that had their marks in reading and math changed to NaNs.  This affected the scores very little in every category we tracked with the largest decline at 0.03%.

Average Math = 0.01% decline <br />
Average Reading = stayed the same <br />
% Passing Math = 0.02% decline <br />
% Passing Reading = 0.03% decline <br />
% Overall Passing = 0.01% decline <br />

The overall funding levels per student, per school, and per school type were not changed.  I believe the school board will be happy with their choice of using NaNs for the grade nine students.  The state-testing standards have been upheld.  




