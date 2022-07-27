# School District Analysis

## Overview of the school district analysis: Explain the purpose of this analysis
#
Using Jupyter Notebook and Python to conduct an in-depth school data analysis for reading and math assessment scores to help identify patterns and trends in students'achievements based on school size, budget, and type. Before sharing the final results to the school board members, math and Reading scores for Thomas High School's 9th graders must be replacesd with NaNs (Not a Number) and all deliverables must be recalculated.

### List of requested deliverables:
- A high-level snapshot of the district's key metrics, presented in a table format
- An overview of the key metrics for each school, presented in a table format
- Tables presenting each of the following metrics:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school

### Tools:
- GitBash
- Anaconda
- Jupyter-Notebook
- Python
- Pandas
- Numpy
- Virtual Studio Code

## Results: 

### How is the district summary affected?

Original District Summary:
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/District%20Summary%20-%20Original.png> 

Updated District Summary:
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/District%20Summary%20-%20Updated.png>

The change on the overall, math, and reading passing scores, after removing the data from all 461 Thomas High School's 9th grade students, was less than 1%. 


### How is the school summary affected?

As shown in the comparison below, the school saw significant drops in math and reading passing percentage, and overall passing percentage. Average scores for math and reading remained almost the same.

Fig.3 - Thomas High School (School Summary)
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/THS%20-%20Comparison.png>

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Before removing the scores for 9th grade, Thomas High School was in the top 5 performing schools:





### How does replacing the ninth-grade scores affect the following:
- Math scores by grade:

The previous ninth-grade score of 83.59 for math has been replaced with nan (not a number). Grades for tenth to twelveth grades remain unchanged.

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Math%20Scores%20by%20Grade%20-%20Updated.png>


- Reading scores by grade: 
 
 The previous ninth-grade score of 83.72 for reading has been replaced with nan (not a number). Grades for tenth to twelveth grades remain unchanged.

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Reading%20Scores%20by%20Grade%20-%20Updated.png>

- Scores by school spending:

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Spending%20Summary%20-%20Comparison.png>


- Scores by school size:
  
With 1635 students, Thomas High school is considered a medium school. Replacing ninth-grade scores had relatively low impact in the average scores of medium-sized schools, as shown:
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Size%20Summary%20-%20Comparison.png>
  
- Scores by school type:    

Thomas High School is a charter school. Like the scores by school size, replacing ninth-grade scores had relatively low impact in the average scores of charter schools in general.
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/School%20Type%20Summary%20-%20Comparison.png>



## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
