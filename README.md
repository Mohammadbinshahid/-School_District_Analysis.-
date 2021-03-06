# School District Analysis 

** Challenge code until output line 128 in file, original module code is after line 128 **

## Overview of the school district analysis:
School District Board requested to perform an analysis of several key metrics at school and district level to get a snapshot of their performance. Analysis focused on maths and reading scores presented in several different ways for a board meeting. The School Board reviewed the analysis and assessed that the data from Thomas High School's Ninth Grade Class maybe subject to acadamic dishonesty. The board asked for this data to be removed and a revised analysis to be performed. 

### Process
  1. Used Jupyter notebook by opening notebook through Anaconda Pythondata environment.
  2. Read the CSV file for School District Analysis to create a dataframe.
  3. Formatted and cleaned dataframe.
  4. Retrieved data from specific columns in the dataframe.
  5. Merged, filtered and sorted data.
  6. Used groupby() function on the dataframe.

## Results

How is the district summary affected?

Original
![district_summary_df original](https://user-images.githubusercontent.com/104873181/171781913-035200ca-7fef-4bf3-a845-7f5ef4d6c376.png)

Revised
![district_summary_df revised](https://user-images.githubusercontent.com/104873181/171786912-ca7afa94-f7f5-48e5-8e3f-3bced7918844.png)

The test data of 9th grade students of Thomas High School was changed to null data. Revised percentages of students passing were calculated. Data showed an insignificant change in overall scores. Math grade average came down to 78.9 as compared to 79. In percentage terms, grade average went down by 0.2% to 74.8% from 75% in the original analysis for maths.

For reading, the grade average was same rounded to one decimal point however pass percentage dropped from 86% to 85.7%.

### How is the school summary affected?

Original
![School Summary Original](https://user-images.githubusercontent.com/104873181/171783466-23994cd9-a3dc-496a-b51e-85b2ae5ab0cf.png)

Revised
![School Summary Revised](https://user-images.githubusercontent.com/104873181/171783484-b2132a71-5420-4cb4-8d84-504de97c8735.png)

As shown in the snapshots, the overall passing percentage came down from 90.95% to 90.63%.

### How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?

Using the same snapshots as above, we can see that the passing percentage for Thomas High School came down by 32 basis point where as all other schools remained unchanged.

### How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade - Math average is coming down from 83.42 to 83.35 for Thomas High. Reading average has gone up to 83.90 from 83.85

### Scores by school spending - no change

### Scores by school size 

Original

!![Scores by school sizes original](https://user-images.githubusercontent.com/104873181/171785485-60420544-2e49-4ea4-95f2-dd1b7d6826ea.png)

Revised
![Scores by school sizes revised](https://user-images.githubusercontent.com/104873181/171785469-da75d4e8-59ff-4fdf-a3aa-24755be97e19.png)

As visible in the the snapshots scores have come down for medium sized schools in the revised data due to null values given to students of 9th grade in THS.

### Scores by school type - Average came down for Charter Schools

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed from 90.94% to 90.63%
2. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School
3. Math, reading and overall average for THS saw a shift
4. Overall changes seem insignificant at a broader level but may be significant when drilling down to a more granular level of data.
