# School_District_Analysis

## Overview
The school board found discrepancies in the *student_complete.csv* file for the 9th-graders’ reading and math scores from Thomas High School. Lacking confidence in the data filed received, Maria was asked to review, clean and analyze the data and provide an explanation on the impact her changes had to the schools’ performances and school district’s overall analysis.


## Results:

- The district summary is including presumed corrupt data for **461** 9th-graders from Thomas High School (‘THS’), thus affecting the math, reading and overall passing percentages. 

- In the school summary, only THS’s math, reading and overall passing percentages are affected. The values of the other 14 schools are accurately reported.

    -    **School Summary** ![School Summary]( https://github.com/AQUINT01/School_District_Analysis/blob/main/images/per_school_summary_original.png)


 - Replacing the THS 9th-graders’ math and reading scores only impact THS performance and has no bearing on the individual performance of the remaining 14 schools.

    -    **School Summary Comparison ** ![School Summary Comparison]( https://github.com/AQUINT01/School_District_Analysis/blob/main/images/per_school_summary_comparison.png)



### However, it should be noted that replacing the ninth-grade scores will affect the following items;

- **Math and reading scores by grades**: With the removal of the 9th-graders, only the average grades in THS were affected.

- **Scores by school spending**: No impact to spending because the scores have no bearing on the calculation and the total student population at THS was unchanged (**1,635**).  

- **Scores by school size**: The average math- and reading- scores were not impacted because the school size at THS remained within the meduim range -- a population of **1,174** students, excluding the **461** 9th-graders. Conversely, the math- and reading- percentages spiked up due to removal of the 9th-graders' scores.

    -    **Scores by School Size** ![Scores by school size]( https://github.com/AQUINT01/School_District_Analysis/blob/main/images/scores_by_school_size.png)


- **Scores by school type**: THS is a *Charter* school, therefore the cumulative performance result of the charter school is impacted. 

    -    **Scores by School Type** ![Scores by school type]( https://github.com/AQUINT01/School_District_Analysis/blob/main/images/scores_by_school_type.png)


## Summary:

In sum, the 9th grade scores of Thomas High School don't definitively support the suspicion that math and reading scores were manipulated because this data analysis performed demonstrates otherwise.  By removing the presumed hampered data, the performance of many score indicators remained the same or increased, suggesting that the reading and math scores were probably honest values and not manipulated.

-    Average Math Scores, no change, **83.35** 
-    Average Reading Scores,  no change, **83.89**
-    % Passing Math increased from **66%** to **93%** 
-    % Passing Reading increased from **69%** to **97%** 
-    **% Overall Passing increased from** **65%** to **91%**, moving Thomas High School's performance to the top 5 schools list.

     -    **Top 5 schools** ![Top 5 schools]( https://github.com/AQUINT01/School_District_Analysis/blob/main/images/top_schools.png)


