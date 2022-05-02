# School District Analysis

## Overview
This analysis of the local school district was done to gain a better understanding of which schools were most successful and why. The data was re-analyzed for the district after excluding the Thomas High School 9th grade scores due to suspicion of tampering. In this analysis we used Jupyter Notebook version 6.4.5 with Python version 3.9.7 in conjunction with the data analysis software library pandas.

## Results
After re-evaluating the school districts performance and excluding the 9th graders from Thomas High School we discovered some changes in the results and findings. 

### District Summary Results
Our results prior to the exclusion of the 9th graders at Thomas High School had overall higher percentages of passing in math, reading, and overall. 

![District Summary with Thomas High School 9th Graders](https://github.com/Trevor-Jackson94/School_District_Analysis/blob/main/Resources/district_summary_before.PNG)

After exluding the 9th graders we saw the percentage of students passing math at 74.8, passing reading at 85.7 and overall dropped to 64.9.

![District Summary without Thomas High School 9th Graders](https://github.com/Trevor-Jackson94/School_District_Analysis/blob/main/Resources/district_summary_after.PNG)

### School Summary Results
The 'per_school_summary_df' DataFrame displays the schools and their statistics including Total Students, Total School Budget, Per Student Budget, Average Scores, and Percentage of Students Passing. The before and after the removal of the 9th Graders test scores from Thomas High School did not have a dramatic effect on the table. When looking at the top schools before the removal Thomas High School as in 3rd, based on overall percentage of students passing. They stayed in the same spot afterwards. The Thomas High School 'Overall Passing Percentage' dropped only slightly down from 90.948012 to 90.630324. This was not enough of a change to alter the overall results or rankings of the school.

![Per School Summary Table](https://github.com/Trevor-Jackson94/School_District_Analysis/blob/main/Resources/per_school_summary.PNG)

![Top 5 Schools Based on Percent of Passing Overall](https://github.com/Trevor-Jackson94/School_District_Analysis/blob/main/Resources/top_schools.PNG)

### Effects of Replacing the 9th Grader Scores
The score changes did not change Thomas High School's overall performance too much. Their performance statistics dropped slightly but not significantly. The scores by grade table now reads 'nan' for the Thomas High School average score in math and reading. Since Thomas High School is in the $631-$645 spending range per student, the '% Overall Passing' in that range, along with the reading and math percentages of passing, decreased ever so slightly, from 62.857656 to 62.778233. The reason the data changed in such a way is because there are less "passing grades" with an unchanged Total Student Count for Thomas High School.

![Average Scores and Percentage of Passing by Spending Ranges per Student] (https://github.com/Trevor-Jackson94/School_District_Analysis/blob/main/Resources/spending_summary.PNG)

The school type results, seen in the 'type_summary_df' DataFrame, exhibit very small changes after removing the 9th graders results from the data. The only changes visable to 1 decimal place in the 'Charter' type of school are seen in the 'Average Reading Score' and 'Average Math Score'. Both these categories increased ever so slightly.

## Summary
After the reading and math scores of the 9th graders at Thomas High School were removed due to suspicion of tampering, the following changes occurred to the data:
    - Math and Reading scores by grade table shows 'nan' for Thomas High School 9th Graders.
    - The $631-$645 range of spending per student decreased slightly in '% Overall Passing'.
    - 'Average Math Score' and 'Average Reading Score' increased for the 'Charter' type.
