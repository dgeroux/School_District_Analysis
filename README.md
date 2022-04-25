# School_District_Analysis
Click here to view the jupyter file: [School District Project](https://github.com/dgeroux/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Overview of Analysis
A board of directors for a school district has provided raw data to be cleaned, organized, and analyzed. They originally tasked me with the following deliverables: 

1. A high-level snapshot of the district's key metrics, presented in a table format
2. An overview of the key metrics for each school, presented in a table format
3. Tables presenting each of the following metrics:
4. Top 5 and bottom 5 performing schools, based on the overall passing rate
5. The average math score received by students in each grade level at each school
6. The average reading score received by students in each grade level at each school
7. School performance based on the budget per student
8. School performance based on the school size 
9. School performance based on the type of school

After providing the above deliverables, the school board notified me that these results show evidence of academic dishonesty; specifically, reading and math grades for Thomas High School 9th graders appear to have been altered. They asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. The board would like me to repeat the school district analysis that I did and write up a report to describe how these changes affected the overall analysis.

## Results
After making the changes requested by the board, much of the data from the original analysis remained the same. The original data set is so large that removing such a small portion of the data (math and reading scores for 9th graders at Thomas High School) did not drastically skew the data. 

### Deliverable One
![deliverable_one](https://github.com/dgeroux/School_District_Analysis/blob/main/deliverable_one.png)

### Deliverable Two

![deliverable_one](https://github.com/dgeroux/School_District_Analysis/blob/main/deliverable_one.png)


## Summary
The four major changes that occurred is the number of total students, the number of students counted at Thomas High School, the average math and reading scores, and the overall percentages for math and reading at Thomas High School. The removal of data implies a decrease in the count of total students overall, and total students at Thomas High School, specifically for this analysis. And since the population amount was decreased, this leads to a change in average scores and score percentages. Due to the fact that these score and percentage changes were minimal, we can assume that the removal of math and reading scores of 9th graders at Thomas High School not as significant as we would imagine it to be.
