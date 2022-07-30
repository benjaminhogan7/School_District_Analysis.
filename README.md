# School_District_Analysis
School District Analysis Project

## Overview
This week's challenge tasked us with analyzing school standardized testing data across various high schools in a school district. The two types of tests were reading and math. There were several variables between schools that I analyzed, including grade level, type of school (district vs charter), size of the school, and per student spending. The output looked at all of these variables on test scores.

During the course of the analysis, I got my first foray into cleaning data using Python and Pandas. The main point here was to clean up erroneous prefixes and suffixes, such as MR., MRS., DR., etc., while leaving in valid suffixes such as Jr. or III. This was a good prep for one of the challenges of the challenge, which was to edit out 9th grade scores for Thomas High School, who it was determined had academic integrity issues.

## Differences Between Initial Analysis and Excluding Thomas High School 9th Graders


* How is the district summary affected?
** The district summary seems to have been relatively unaffected by removing Thomas High School 9th graders. The top 5 ranking did not change and the passing percentages for math, reading, and both were only affected by tenths of a percentage point. Below are the top 5 ranking schools in the first analysis.
<img width="991" alt="Top 5 Schools 1st Analysis" src="https://user-images.githubusercontent.com/108236450/182003422-bf03b4eb-f560-47c6-9aec-22b5afad5e95.png">
** When compared to that of the second analysis (below), you can see that the test scores for Thomas High School must have been very consistent between at least the 9th graders and the rest of the population, though the 9th graders performed slightly better than the rest, resulting in slightly lower averages.
<img width="982" alt="Top 5 Schools 2nd Analysis" src="https://user-images.githubusercontent.com/108236450/182003466-e7eebc1c-de82-4a4c-8f65-37d35865b9c5.png">

*How is the school summary affected?
** As mentioned above it does not affect the school summary very much

*How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
** As displayed in the top 5 performing schools summary pictures above, omitting the grades does not affect the placement of Thomas High School relative to other schools.
*How does replacing the ninth-grade scores affect the following:
** Math and reading scores by grade
*** You can see below that overall average scores in math and reading were largely unaffected by omitting 9th graders from Thomas High School. In both cases average scores dropped slightly, but only by tenths or hundreths of percentages
<img width="927" alt="Screen Shot 2022-07-30 at 7 43 34 PM" src="https://user-images.githubusercontent.com/108236450/182003699-1271dfd0-b1b8-4d75-b072-c6c38f3de8ae.png">

<img width="926" alt="Screen Shot 2022-07-30 at 7 43 41 PM" src="https://user-images.githubusercontent.com/108236450/182003701-b77d3de3-eea8-4962-97c1-803b466f0fc1.png">

**Scores by school spending
*** Negligibly 
**Scores by school size
*** Negligibly
**Scores by school type
*** Negligibly


