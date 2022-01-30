# School_District_Analysis_Challenge
PyCitySchools with Pandas


## Purpose
A school district asked for a snapshot of several key metrics of each school campus at district level. The main analysis focused on the performance of math and reading scores.  
However, after the school board reviewed the data, it was determined that the data from Thomas High School's 9th grade class was suspect of cheating.  
The school board asked for the data to be removed and analyzed again for a comparison. 


## Results of the School_District_Analysis

### District Summary Affected

Original Analysis:
![Pic 1](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_dist_sum_2_decimals.PNG)

The testing data of 461 9th graders at Thomas High School was turned into null data, which recalculated the percentages of passing math, passing reading, and the overall passing.
![Pic 2](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_dist_sum_2_decimals.PNG)

When comparing the two charts, removing less than 500 test scores had a nominal impact on the almost 40,000 student data set.  The change was less than a 1% difference and the numbers would still round to the same whole number.  

### School Summary Affected

In the original analysis, Thomas High School started with a 91% overall passing rate, which was a concern to the school board as being too high.  After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.  

Original Analysis:
![Pic 3](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_THS_90.PNG)

Adjusted Analysis:
![Pic 4](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_THS_65.PNG)

Removing the 9th grade students from the data set had a huge impact by dropping from 91% to 65% for the overall passing rate. 

### Replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools
In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board. 

Original Analysis:
![Pic 5](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_top_5_schools.PNG)

After adjusting the 9th grade data, Thomas High School ranked 8th from the bottom. 

Adjusted Analysis:
![Pic 6](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_bottom_8_schools.PNG)

## Replacing the ninth-grade scores which affect the following things
### Adjusted Averages using the Math and Reading Scores 

In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. 
Now the scores have been replaced with null values and shows up in Python programming as NaN in the following charts. 

Adjusted Average Math Scores ----------------------------------------------------- Adjusted Average Reading Scores: 

![Pic 7](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_math_by_grade_HS.PNG)
![Pic 8](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_read_by_grade_HS_correct.PNG)

### Scores by school spending

Thomas High School falls in the $630-$644/student spending range.  However, the hundredths place was needed to see the nominal changes. 

Original Analysis:
![Pic 9](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_spend_updated.PNG)

Adjusted Analysis:
![Pic 10](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_spending_updated.PNG)

There was very little spending impact by changing the 9th grade scores. 

### Scores by school size
Thomas High School is defined as a medium sized school.  The hundredths place was needed to see the nominal changes.

Original Analysis:
![Pic 11](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_size_updated.PNG)

Adjusted Analysis:
![Pic 12](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_size_updated.PNG)

There was very little impact by campus size due to changing the 9th grade scores. 

### Scores by school type

Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes.

Original Analysis:
![Pic 13](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/1_type_updated.PNG)

Adjusted Analysis:
![Pic 14](https://github.com/Baylex/School_District_Analysis/blob/main/Resources/2_type_updated.PNG)

There was very little impact by school type by changing the 9th grade scores. 

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

1. The overall passing rate for Thomas High School changed dramatically from 91% to 65%. 

2. Thomas High School's ranking dropped from 2nd to 8th in the district of 15 campuses. 

3. Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School  

4. The campus math and reading averages and passing percentages all were shifted  
