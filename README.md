# School-District-Analysis

## Project Overview
Maria, the chief data scientist for a city school district, has tasked me with analyzing the standardized test data for all the schools in her district and to help provide insights in relation to a variety of factors. Maria was also notified that Thomas High School may have altered the test results for the 9th grade students, and she wants to see how removing them from the data will affect the analysis. A few analysis that are performed in this script are:

1. Calculate the average of math and reading scores for each school.
2. Analyze how the scores trend in relation to school budget.
3. Analyze relationships between test scores and student body population.
4. Found whether the type of school had an impact on performance.
5. Determined the top and bottom 5 schools of the district.

## Resources
- Data: 
	- resources/schools_complete.csv
	- resources/students_complete.csv
- Software: 
	- Python 3.7.9 
	- Jupyter Notebook
	- Pandas

## Results
After removing the Thomas High School 9th grade students' data, we can compare the new data against the old data set and try to see if there were any significant changes.
#### District Summary
Before change:
![district_summary_old](resources/district_summary_old.png)

After change:
![district_summary_new](resources/district_summary_new.png)

Looking at the overall district data, we can see that the overall impact to the district due to the change is negligible, with percentages decreasing only by a few tenths of a percent at most.

#### School Summary
Top 5 schools before change:
![top_schools_old](resources/top_schools_old.png)

Top 5 schools after change:
![top_schools_new](resources/top_schools_new.png)

Similarly to the results from the district summary, we can see that the changes had an insignificant impact on the school metrics. Again the largest changes are only a few tenths of a percent. Relative to the other top performing schools, Thomas High School still remained second even after the changes.

#### Math and Reading Scores

The only thing effected for the math and reading scores here is in the new data, all of the 9th grade math and reading scores have been removed.

#### School Spending

Before:
![school_spend_old](resources/school_spend_old.png)

After:
![school_spend_new](resources/school_spend_new.png)

Thomas High School is within the $630-644 spending range. The only two metrics effected here are '% Passing Reading' and '% Overall Passing' which only decrease by a negligible 0.1%.

#### School Size

Before:
![school_size_old](resources/school_size_old.png)

After:
![school_size_new](resources/school_size_new.png)

Thomas High School is within the Medium (1000-2000) range. The difference between before and after the change are nearly identical when taking into account school size.

#### School Type

Before:
![school_type_old](resources/school_type_old.png)

After:
![school_type_new](resources/school_type_new.png)

The two data frames are identical here.

## Summary

By removing the 9th grade students' data of Thomas High School from the analysis, we were able to see a drop in performance for certain metrics, albeit a very insignificant one. 

- The changes affected the overall district slightly, causing a small decrease in all the percentage columns. 
- For schools in the spending ranges of $630-644, there was a slight drop in the '% Passing Reading' and '% Overall Passing' columns. 
- Taking into account school sizes, there was a slight drop in '% Passing Reading'.
- As for the school type metric, the data was identical.

As we can clearly see, the new changes to the data resulted in an inconsequential difference in the data, which leads me to believe that perhaps there was little to no alteration to the Thomas High School standard test results.