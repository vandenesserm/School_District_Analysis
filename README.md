# School District Analysis

## Overview:
#
Conduct an in-depth school data analysis for reading and math assessment scores to help identify patterns and trends in students' achievements based on school size, budget, and type. Before sharing the final results with the school board members, math and reading scores for Thomas High School's ninth graders must be replaced with NaNs (Not a Number) and all deliverables must be recalculated.

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
- Jupyter Notebook
- Python
- Pandas
- Numpy
- Virtual Studio Code
#
## Results: 
#
### How is the district summary affected by the data removal?
The school district has 39,170 in grades nine through twelve, across 15 high schools. Thomas High School has 1635 students, of which 461 are in ninth grade. After removing the scores for Thomas High School's ninth grade, the change to the math, reading, and overall passing scores, was less than 0.5%.

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/District%20Summary%20-%20Original.png> 
 <figcaption> Fig. 1 - Original District Summary </figcaption>
</br>

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/District%20Summary%20-%20Updated.png>  
<figcaption>Fig. 2 - Updated District Summary</figcaption>
</br>

### How is the school summary affected?
As shown in the comparison below, the school did not experience a significant drop in math and reading, and overall passing percentages. Average scores for math and reading remained almost the same.
<br />

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/THS%20-%20Comparison.png>
<figcaption> Fig. 3 - Thomas High School (School Summary)</figcaption>
</br>

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Before removing the scores for 9th grade, Thomas High School was the second best performing high school in the district.
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Top%20Five%20-%20Original.png>
<figcaption> Fig. 4 - Top Five Schools (including ninth-grade scores)</figcaption>
</br>

After removing the ninth-grade scores, the overall passing rate was slightly lowered, but Thomas High School remained the second to the best school. 
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Top%20Five%20-%20Updated.png>
 <figcaption> Fig. 5 - Top Five Schools (excluding ninth-grade grade scores)</figcaption>
</br>

### How does replacing the ninth-grade scores affect the following:
#### <u> Math scores by grade:</u>
The previous ninth-grade score of 83.59 for math has been replaced with nan (not a number). Grades for tenth to  twelfth grades remain unchanged.

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Math%20Scores%20by%20Grade%20-%20Updated.png>
 <figcaption> Fig. 6 - Math Scores (excluding 9-th grade scores)</figcaption>
</br>

#### <u>Reading scores by grade: </u>
 The previous ninth-grade score of 83.72 for reading has been replaced with nan (not a number). Grades for tenth to  twelfth grades remain unchanged.

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Reading%20Scores%20by%20Grade%20-%20Updated.png>
 <figcaption> Fig. 7 - Reading Scores (excluding ninth-grade scores) </figcaption>
</br>


#### <u>Scores by school spending:</u>
Thomas High School spends an average of $638 per student, putting it in the spending range of $631-645. Changes to average score and passing rates were also minimal.

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Spending%20Summary%20-%20Comparison.png>
<figcaption> Fig. 8 - Scores by School Spending </figcaption>
</br>
</br>

#### <u>Scores by school size:</u>
  
With 1635 students, Thomas High school is considered a medium school. Thomas High school is considered a medium school. Replacing ninth-grade scores had a relatively low impact on the average scores of medium-sized schools, as shown:

<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/Size%20Summary%20-%20Comparison.png>
<figcaption> Fig. 9 - Scores by School Size </figcaption>
</br>

#### <u>Scores by school type: </u>   

Thomas High School is a charter school. Like the scores by school size, replacing ninth-grade scores had a relatively low impact on the average scores of charter schools in general. 
<img src=https://raw.githubusercontent.com/vandenesserm/School_District_Analysis/main/PNGs/School%20Type%20Summary%20-%20Comparison.png>
<figcaption> Fig. 10 - Scores by School Type </figcaption>
</br>

#
## Summary: 
#
To summarize, the removal of scores for Thomas High School's ninth grade had very little to no impact in the following areas:

1) District overall performance
2) School overall performance, including its placement within the top five schools in the district.
3) The performance and or data for Thomas High School's tenth through  twelfth grade.
4) The performance of schools when based on school size, type, and spending.


