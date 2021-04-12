# School_District_Analysis
---

## Project Overview
---
The school board has become suspicious that the reading and math scores reported for 9th graders at Thomas High School may have been altered. Maria and her supervisor have asked that the math and reading scores for Thomas High School 9th graders be replaced with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, Maria would like the school district analysis repeated to illustrate how these changes affected the overall analysis.

## Resources
---
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, conda 4.9.2, jupyter lab version 2.2.6

## Results
---
### Replace Ninth-Grade Reading and Math Scores

The *loc* method with conditional statements and comparison and logical operators can be used to determine how many 9th grade students from Thomas High Schools were part of the population of the school district. 461 of the 39,170 were in fact first-years at Thomas which represents only about 1.18% of the population. Removing their scores from consideration for determining average reading and math scores for the entire district might not significantly impact the averages, but for the sake of data intergrity, it would certainly be good practice to remove them. Let's check...Without scores from Thomas 9th graders, the average reading score looks to have increased from 81.9 to 86.2 while average math scores drop from 78.9 to 75.3. 


### Repeat the School District Analysis

Unfortunately, due to poor time budgeting on my part, I was unable to complete the analysis for Scores by Grade, School Spending, School Size amd School Type. 

## Summary
---


