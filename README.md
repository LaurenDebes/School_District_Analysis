# School_District_Analysis
Using Python with Anaconda Pandas/Jupyter Notebook
## Overview of School District Analysis
We are helping Maria, the chief data scientist for a city school district, analyze data on student funding and students' standardized test scores, aggregate the data, and showcase trends in school performance. We will deliver the following materials:
   - Each district's key metrics
   - Key metrics for each school
   - The top 5 and bottom 5 performing schools (by overall reading and math passing rate)
   - The average math and reading score by grade level per school
   - School performance based on budget per student, school size, and type of school

Then, Maria was notified that the test scores for 9th grade students at Thomas High School were invalid, so we needed to help her remove those scores and reanalyze the data and deliver the same materials.

## School District Analysis Results
**District Summary:**
The district summary was verly slightly altered by the removal of 9th grade test scores from Thomas High School. 
![DistrictSummaries.png](https://raw.githubusercontent.com/LaurenDebes/School_District_Analysis/main/DistrictSummaries.png) 
The following metrics decreased with the removal of 9th grade test scores at Thomas High School:
  - Average math score went down .1 points
  - % Passing math decreased by 0.2%
  - % Passing reading decreased 0.1%
  - % Overall passing decreased 0.3%
 
**School Summary:** The school summary, by looking at the top 5 high performing schools, also changed very little. The change in metrics mirrored the district summary, except for average reading score, which increased by .05 points. This may have also been presentn though in the district summary if we had not formatted the results to round to the nearest tenth or whole number.
![schoolsummary.png](https://raw.githubusercontent.com/LaurenDebes/School_District_Analysis/main/schoolsummary.png) 

**Replacement of 9th grade scores and overall performance:** Overall, the replacement of the 9th grade scores did very little to the district's performance relative to the other schools. There were only differences in the tenth and hundredths. It still ranked second for highest performing school. It is still important to have these numbers corrected for accuracy, though. 

**Other effects of 9th grade score replacements:** Heres how the replacement of 9th grade scores affected the other metrics:
  - Math and reading scores by grade: This only changed the 9th grade reading score for Thomas High School, reading "nan" instead of "83.7" as previously calculated.
  - Scores by school spending: Thomas High School spent $638 per student. The changes to this range are very small. When formatted to round up to the nearest tenth or whole number, there was no change between the older data set and the fixed.
  - Scores by school size: Thomas High School is a medium-sized school. Similarly to scores by school spending, the change was very small and was not shown when the data set was formatted to round up to the nearest tenth or whole number.
  - Scores by school type: Thomas High School is a Charter school. It also had no change when rounded to the nearest tenth or whole number.

## School District Analysis Summary
Four changes to the analysis after the reading and math scores were replaced:
  - % Overall passing decreased 0.3% both by school and by district.
  - There is no longer a 9th grade reading score for Thomas High School. We are not able to compare Thomas High School with other high schools. If we were to compare all grade levels across the district to one another (i.e if we wanted to see which grade level has the highest overall passing) the ninth grade total score may be affected.
  - The passing math grade decreased by 0.2% both by school and by district.
  - For Thomas High School specifically, the % passing math shot up from 66.91% to 93.19%, the % passing reading went from 69.66% to 97.02%, and the overall passing rose from 65.08% to 90.63%
