# School_District_Analysis
## Overview of the school district analysis
The purpose of this analysis is to review and analyze the school districts’ data to showcase trends in different schools’ performance. This will allow the school board to make informed decisions regarding schools’ budget allotments. Due to possible academic dishonesty with Thomas High School’s 9th grade reading and math scores, these will be nulled, and turned into the value of "NaN" to keep the rest of the data acurate. This will be done through the following.
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

With the possibility of Thomas High School’s 9th grade reading and math scores being altered and academic dishonesty they are turned to null data. This gives the Thomas High School grades a new nulled value of "NaN". Doing this requires the recalculation of overall passing scores, as well as, reading and math passing percentages.
* The percentage passing math originally is 74.98%, the new percentage passing math 74.76%.
* The percentage passing reading originally is 85.80%, the new percentage passing reading is 85.66%.
* The percentage overall passing originally is 65.17%, the new percentage overall passing is 64.86%.

* #### Original Analysis:
![District_summary_original](https://user-images.githubusercontent.com/103263248/172680111-ed10a129-1732-4695-82e5-2d12f00cbaf2.png)

* #### Amended Analysis:
![district_summary_df png](https://user-images.githubusercontent.com/103263248/172680061-23f45250-fe64-462a-abe2-e88aa58172b7.png)


### School Summary
The data was then isolated to only show the students in 10th through 12th grade. This caused a large change to the summary for Thomas High School’s data results. By removing the 9th grade scores from the Thomas High School’s data the following is found.
* Overall passing rate went from 91% to 65%.  
* Percentage Passing math went from 93% to 67%.
* Percentage Passing reading went from 97% to 70%. 

* #### Original Analysis:
![ths_summary_origiinal](https://user-images.githubusercontent.com/103263248/172680995-c222c5e2-cb72-4675-b441-5d0f4adec088.png)

* #### Amended Analysis:
![ths_summary](https://user-images.githubusercontent.com/103263248/172680187-325b0c42-d3d1-4208-8d5e-c526653e22b3.png)


### Thomas High School Performance
By changing the suspected altered scores Thomas High School went from being the top second preforming high school to being the in the bottom 8th in performance.

* #### Original Analysis:
![original_top_5_schools](https://user-images.githubusercontent.com/103263248/172680272-1090d975-289e-4d05-8524-e5a24994a873.png)

* #### Amended Analysis:  
<img width="743" alt="bottom_8_schools" src="https://user-images.githubusercontent.com/103263248/172709065-f6bcc83b-547c-4f17-8a91-b938703c4b44.png">



## Amened Analysis vs Original Analysis Results
#### By replacing the Thomas High School 9th grade scores there are some changes that can be observed.

### Math and Reading Scores by grade
The math and reading scores by grade are affected by being replaced with a null value, and now show up as "NaN" in the average math and reading scores.
* Reading

![readinng_scores_by_grade](https://user-images.githubusercontent.com/103263248/172680303-07661c42-68cb-46a6-afe4-2ea08ab948aa.png)

* Math

![math_scores_by_grade](https://user-images.githubusercontent.com/103263248/172680311-4e4e27f8-5ed1-427e-b13f-50d26bb09111.png)


### Scores by school spending
The scores on school spending changed for the range in which Thomas High School is categorized, the $630-$645 per student range. The average math and reading scores remained the same. The following changes can be seen.
* Percentage passing math originally is 73%, the new percentage is 67% rounded.
* Percentage passing reading originally 84%, the new percentage is 80% rounded.
* Percentage overall passing originally 63%, the new percentage is 53% rounded.

* #### Original Analysis:
![original_spending_range_per_student](https://user-images.githubusercontent.com/103263248/172680416-8d53663f-46b3-4226-bd78-db3175b8b00e.png)

* #### Amended Analysis:
![spending_range_per_student](https://user-images.githubusercontent.com/103263248/172680343-b20cc8ae-8375-4f5b-be60-4620dccc58a4.png)



### Scores by school size
By changing the Thomas High School 9th grader data to the "NaN" value, there was only a slight change to the scores by school size. The small and large sized school scores are unaffected due to Thomas High school being in the medium sized category. To see the change in values for the medium school size the percentages must be shown to the hundredths decimal point. 
* Percentage passing math originally is 93.60%, the new percentage is 93.68%.
* Percentage passing reading originally is 96.79%, the new percentage is 96.66%.
* Percentage overall passing originally is 90.62%, the new percentage is 90.54%
* #### Original Analysis:
![original_school_size](https://user-images.githubusercontent.com/103263248/172680461-c26eccea-f633-4e0d-a192-34c0fb37c0ef.png)

* #### Amended Analysis:
![scores_by_school_size png](https://user-images.githubusercontent.com/103263248/172680488-b5a721e3-a9a2-4297-a867-2b87a2a00576.png)

### Scores by school type
Thomas High School is listed as a charter type school. Amending the analysis with changing the 9th grade scores has a small impact on the data for scores by school type for charters. The district scores by school type remain unaffected.
* Percentage passing math originally 93.62%, the new percentage is 93.67%.
* Percentage passing reading originally is 96.59%, the new percentage is 96.48%.
* Percentage overall passing originally is 90.43%, the new percentage is 90.36%.

* #### Original Analysis:
![original_school_type](https://user-images.githubusercontent.com/103263248/172680572-1c979f14-5c95-495b-822d-436a06b042df.png)

* #### Amended Analysis:
![scores_by_school_type](https://user-images.githubusercontent.com/103263248/172680538-9897a65b-f2b6-41d9-a769-c09eac51d561.png)


## Summary of updated school district analysis
 Four changes we can see in the amended school district analysis after changing the Thomas High School's 9th grade reading and math scores to null, and replacing it with "NaNs" are as follows. 
1. 9th grade student data for Thomas High School will now read as “NaN” in place of the math and reading scores.
2. Thomas High School dropped from 2nd to ranking the bottom 8th in school rankings.
3. Thomas High School’s overall passing rate had a drastic change from 91% to 65%.
4. While it was a small shift average scores for math and reading percentages changes as well.
