# School_District_Analysis
This repository uses Jupyter Notebook and PythonData to produce school district information for a client.

## Overview of School District Analysis ##

This school district wanted summaries of student and school performance in their district. After providing this analysis, the school district suspected some dishonest test scores in a subset of students in one school. Because of this, their scores were replaced with NaN values and the analysis was refactored. After I completed this analysis, this school district can evaluate the impact of total budgets per school, spending per student, school size, on crucial markers like test scores and overall student performance. 

<img width="1085" alt="Screen Shot 2022-01-15 at 5 24 23 PM" src="https://user-images.githubusercontent.com/95657458/149639526-45b2cc99-0842-438a-8606-3e11b3882538.png">

<img width="1081" alt="Screen Shot 2022-01-15 at 5 26 38 PM" src="https://user-images.githubusercontent.com/95657458/149639580-c122ef16-1ee2-490a-a7c7-22d736e7d1f7.png">

## Results ##

The seven school district metrics were:
* School Type
 This metric was not affected because the school district requested that I omit only the alleged cases of academic dishonesty among 9th grade students instead of removing this high school from my analysis entirely.
* Total Students
 This metric was affected because the number of students decreased once the 9th grade students from one high school were removed from analysis. Although these students were removed from that high school's target analysis, they were not removed from the District's Summary. This was an understandable choice, because removing those students from all levels of analysis would have misrepresented the results of other metrics, specifically the Per Student Budget. 
* Total School Budget
 The total school budget remained unchanged. 
* Per Student Budget
 The per student budget remained unchanged.
* Percentage (%) Passing Math
 This metric was affected because the number of students decreased once the 9th grade students from one high school were removed from analysis.
* Percentage (%) Passing Reading
 This metric was affected because the number of students decreased once the 9th grade students from one high school were removed from analysis.
* Percentage (%) Passing Overall
 This metric was affected because the number of students decreased once the 9th grade students from one high school were removed from analysis.


The school district specifically wanted me to analyze the student performance at one school, since this was the school where they uncovered academic dishonesty. In evaluating this school, I found that the students passing math and students passed reading in the 90 percentile range. What remains to be seen is whether these students are simply high performers, or if there could be more instances of academic dishonesty. 
<img width="1081" alt="Screen Shot 2022-01-15 at 5 43 18 PM" src="https://user-images.githubusercontent.com/95657458/149639950-fcf497ea-6fc9-4f25-acc2-1174341a9d05.png">



## Summary
When I re-ran the code, there were some noteworthy changes between my original and new analysis.

The new district summary
<img width="1083" alt="Screen Shot 2022-01-15 at 5 55 28 PM" src="https://user-images.githubusercontent.com/95657458/149640191-ca9750b0-7257-4a3c-9c3c-eba5de121e03.png">


The old district summary
<img width="1074" alt="Screen Shot 2022-01-15 at 5 36 43 PM" src="https://user-images.githubusercontent.com/95657458/149639785-a5ccf085-d2e2-4a11-bace-7162a4be8124.png">

First, the number of students whose performance was considered in the performance analysis decreased, even though the summary counts them as part of the school. Both the average score for students passing math and the percentage of students passing math decreased slightly. And finally, the overall passing percentage decreased. Aside from the budget increasing, these changes were expected because the academic dishonesty bloated these metrics. 
