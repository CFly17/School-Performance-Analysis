# School_Analysis

## Project Overview
In conjunction with Maria, a Chief City Scientist of a school district, we analyzed school data from a variety of sources and formats to prepare standardized test data for analysis and reporting. The goal is to provide insights into performance trends and patterns which, in turn, inform discussions and strategic decisions at the school and district level. 
For this case, we were particularly interested in re-analyzing the data and comparing once we account for potential alterations that occurred to the Thomas High School ninth graders' math and reading scores.

1. Analyze student funding.
2. Analyze student test scores. 
3. Aggregate the data and showcase performance trends.
4. Repeat and compare the analysis with Thomas High School 9th grade scores set to null values.

#### Resources used
* Data Source: students_complete.csv, schools_compelte.csv
* Software: Visual Studio Code (version 1.63.2)

## Results
* How is the district summary affected?
It appears the district summary only changed slightly: The average math score 
* How is the school summary affected?
The school summary changed dramatically, seeing increases to student test taking by approximately 28% across both reading and math. Here we can see a 'before' data row for Thomas High:

![school_summary_before](https://user-images.githubusercontent.com/87148145/150451592-3ebf5350-a9bc-40cb-8871-a49a5c7bbcf9.PNG)

...and the new data after the 9th grade scores were changed:

![school_summary_after](https://user-images.githubusercontent.com/87148145/150453090-a5a1daca-5d6e-4af4-94c1-baa51865bc96.png)

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
If the scores for 9th graders were accounted for, Thomas High would have ranked 8th, behind Holden High School and above Bailey High School; however, after adjusting for the 9th grade errors, Thomas High placed #2 among the best performing schools.
* How does replacing the ninth-grade scores affect the following:
The majority of all of the other data remained largely unaffected, or only slightly so. With about 1,600 students, Thomas High is a medium-sized school. Their data contributed to the highest overall passing percentage among this group, at 91%:

![schools_by_size](https://user-images.githubusercontent.com/87148145/150454812-b683c6e2-d32b-4098-9fac-e60374812065.PNG)

Since math and reading scores for 9th grades were erased, the other grades remain at about 83% passing rate for math and reading. As Thomas High is in the second-highest bucket for spending, the school-by-school overall passing percentage remained mostly unchanged. But it is also noteworthy that charter schools (like Thomas High) outperformed the district schools. 

## Summary
To summarize, several changes occurred once the 'bad' 9th grader test results data was cleaned. Noteably, the percentage of students passing math and passing reading shot up dramatically -- nearly 30% each! Furthermore, the overall passing percentage increased by about 25%. As a result of these increases, Thomas High went from 8th place overall passing amongh the other schools, to the #2 spot. 