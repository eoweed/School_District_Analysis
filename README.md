# School_District_Analysis
# 

## Overview of school district analysis:

#### The purpose of this analysis is to analyze standardized test scores within the school district, and to make smart decisions on plans for the next school year or future school years. 

#### An initial analysis was performed using all the data provided, however the scores from 9th graders at Thomas High School may have been altered, so a second analysis shows results excluding those scores. 

#

## Results:

#### These results show how the analysis was affected after removing Thomas High School 9th grade scores.

### District Summary: 
##### - Average Math Score decreased by 0.1
##### - % Passing Math decreased by 0.2%
##### - % Passing Reading decreased by 0.3%
##### - % Overall Passing decreased by 0.1%
#####
### School Summary:
##### - Average Math Score decreased for Thomas High School
##### - Average Reading Score decreased for Thomas High School
##### - % Passing Math decreased for Thomas High School
##### - % Passing Reading decreased for Thomas High School
##### - % Overall Passing decreased for Thomas High School
#####
### Top 5 and Bottom 5 Performance:
##### - Thomas High School is still the 2nd Top School after removing 9th grade scores.
#####
### Scores by grade:
##### - 9th grade scores for reading and math are shown as NaN.
#####
### Scores by School Spending:
##### - Removing Thomas High School 9th grade scores does not significantly affect scores by school spending.
#####
### Scores by School Size:
##### - Removing Thomas High School 9th grade scores does not significantly affect scores by school size.
#####
### Scores by School Type:
##### - Removing Thomas High School 9th grade scores does not significantly affect scores by school type.

#

## Summary: 

#### The updated analysis results in a few changes to the district summary and school summary. 

#### In the District Summary, the average math score decreased as shown in the data frame below, and the percent of students who passed math and reading decreased, which means the percent of students who passed both math and reading overall decreased as well. 

#### Original Analysis:
<img src="https://github.com/eoweed/School_District_Analysis/blob/main/Resources/imagesOriginalAnalysis/Screenshot%20(74).png">

#### Updated Analysis:
<img src="https://github.com/eoweed/School_District_Analysis/blob/main/Resources/imagesAfterRemovingAlteredScores/Screenshot%20(83).png">

#### In the School Summary, the average scores for both reading and math at Thomas High School decreased once the 9th grade scores were excluded. The percent of students who passed reading, math, or both overall also decreased as well. 
[Link: Original School Summary](https://github.com/eoweed/School_District_Analysis/blob/main/Resources/imagesOriginalAnalysis/Screenshot%20(75).png)
####
[Link: Updated School Summary](https://github.com/eoweed/School_District_Analysis/blob/main/Resources/imagesAfterRemovingAlteredScores/Screenshot%20(84).png)
#### Removing the Thomas High School 9th grade scores had no effect on the number of total schools, total students, or total budget.

#

## Software: 
#### Python 3.9.12
#### Pandas 1.4.3
#### Numpy 1.23.0
#### Matplotlib 3.5.1
#### Jupyter Notebook 6.4.8
