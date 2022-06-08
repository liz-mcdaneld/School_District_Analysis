# School_District_Analysis
## Overview of the school district analysis
The purpose of this analysis is to review and analyze the school districts’ data to showcase trends in different schools’ performance. This will allow the school board to make informed decisions regarding schools’ budget allotments. Due to possible academic dishonesty with Thomas High School’s 9th grade reading and math scores, these will be nulled to keep the rest of the data acurate. This will be done through the following.
1. Using Jupyter Notebook to open files from local directories.
2. Creating a development environment to use with Python and Pandas coding.
3. Read CSV files and import the data into a data frame.
4. Merge school and student data frames into one frame.
5. Filter, group and preform calculations on the merged data frame.
6. Create a summary of the school district and independent school data frames.
7. Show the top 5, and bottom 5, preforming schools based on overall passing rates.
8. Show the average math and reading scores for each grade level from the schools.
9. Score schools by spending per student, size, and type.


## Analysis Results 

### District Summary

With the possibility of Thomas High School’s 9th grade reading and math scores being altered and academic dishonesty they are turned to null data. Doing this requires the recalculation of overall passing scores, as well as, reading and math passing percentages.
-The percentage passing math originally is 74.98%, the new percentage passing math 75.87%.
-The percentage passing reading originally is 85.80%, the new percentage passing reading is 86.83%.
-The percentage overall passing originally is 65.17%, the new percentage overall passing is 65.95%.
-Original Analysis:
![](Resources%5CDistrict_summary_original.png)
-Amended Analysis:
![](Resources%5Cdistrict_summary_df.png.png)

### School Summary
The data was changed to isolate the student’s data for 10th through 12th grade, causing a large change to the summary for Thomas High School’s data results. By removing the 9th grade scores from the data set, Thomas High School’s the following is found.
- Overall passing rate went from 91% to 65%.  
-Percentage Passing math went from 93% to 67%.
-Percentage Passing reading went from 97% to 70%. 
-Original Analysis:
[image]
-Amended Analysis:
![](Resources%5Cths_summary.png)


### Thomas High School Performance
By changing the suspected altered scores Thomas High School went from being the top second preforming high school to being the 15th in performance.
-Original Analysis:![](Resources%5Coriginal_top_5_schools.png)
-Amended Analysis: ![](Resources%5Cbottom_schools.png)

## Amened Analysis vs Original Analysis Results

By replacing the Thomas High School 9th grade scores there are changes that can be observed.
How does replacing the ninth-grade scores affect the following:
### Math and Reading Scores by grade
The math and reading scores by grade are affected by being replaced with a null value, and now show up as a NaN value in the average math and reading scores.
![](Resources%5Creadinng_scores_by_grade.png)
![](Resources%5Cmath_scores_by_grade.png)

### Scores by school spending
The scores on school spending for changed for the range in which Thomas High School is categorized, the $630-$645 per student range. The average math and reading scores remained the same. The following changes can be seen.
-Percentage passing math originally is 73%, the new percentage is 67% rounded.
-Percentage passing reading originally 84%, the new percentage is 80% rounded.
-Percentage overall passing originally 63%, the new percentage is 53% rounded.
-Original Analysis:
![](Resources%5Coriginal_spending_range_per_student.png)
-Amended Analysis:
![](Resources%5Cspending_range_per_student.png)

### Scores by school size
By changing the Thomas High School 9th grader data there was only a slight change to the scores by school size. The small and large sized school scores are unaffected due to Thomas High school being in the medium sized category. To see the change in values for the medium school size the percentages must be shown to the hundredths decimal point. 
-Percentage passing math originally is 93.60%, the new percentage is 93.68%.
-Percentage passing reading originally is 96.79%, the new percentage is 96.66%.
-Percentage overall passing originally is 90.62%, the new percentage is 90.54%
-Original Analysis:
![](Resources%5Coriginal_school_size.png)
-Amended Analysis:
![](Resources%5Cscores_by_school_size.png.png)

### Scores by school type
Thomas High School is listed as a charter type school. Amending the analysis with changing the 9th grade scores has a small impact on the data for scores by school type for charters. The district scores by school type remain unaffected.
-Percentage passing math originally 93.62%, the new percentage is 93.67%.
-Percentage passing reading originally is 96.59%, the new percentage is 96.48%.
-Percentage overall passing originally is 90.43%, the new percentage is 90.36%.
-Original Analysis:
![](Resources%5Coriginal_school_type.png)
-Amended Analysis:
![](Resources%5Cscores_by_school_type.png)

## Summary of updated school district analysis
 Four changes we can see in the school district analysis after changing the Thomas High School reading and math scores to null, replacing it with NANs are as follows. 
1. 9th grade student data for Thomas High School will now read as “NaN” in place of the math and reading scores.
2.Thomas High School dropped from 2nd to ranking 13th in school rankings.
3.Thomas High School’s overall passing rate had a drastic change from 91% to 65%.
4.While it was a small shift average scores for math and reading percentages changes as well.
