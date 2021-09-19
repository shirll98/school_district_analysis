# school_district_analysis
## Overview of the school district analysis (purpose of analysis) 
The purpose of this analysis is to analyze a set of school and student data using python and pandas to approximate the test scores and budget. Python and pandas library was used to analyze the data while data visualization was done via jupyter notebook. 

## Results 
### How is the district summary affected? 
The district summary was not affect by very much. The average math score was still around 
78.9% and average reading score was about 81.9%. 
### How is the school summary affected?
Only the metrics in Thomas High School were affected since the students were from Thomas High School. The overall average scores did not change that much but the % passing of math and reading were affected drastically, since a whole grade of student's grades were unaccounted for. 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The replacement of the ninth grader's scores negatively affected the % passing reading, math and overall. If schools were evaluated and ranked by %overall passing then Thomas High School would've dropped at least from being 3rd place to 8th place in a total of 15 schools. 

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
#### Scores by school spending
#### Scores by school size
#### Scores by school type

Replacing the ninth-grade scores changed Thomas High School's reading and math scores from a 83% to NaN. This change obviously, did not affect the school's spending, school size, or school type. However, this change did affect the % pasing and overall passing. This is expected as a whole grade of students' scores were not accounted for. 


### Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
Removing the data affected the school type summary between charter and district schools. 
The change lowered charter school's passing percentage. Charter schools had a higher passing percentage in all areas (average math score, average reading score, % passing math, % passing reading, and % overall passing) But this replacement, reduced these percentages. However, overall charter school types are still displayed superior passing and average scores than district school types. 