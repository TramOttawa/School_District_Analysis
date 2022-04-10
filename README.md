# School_District_Analysis
## Overview:
The main analysis is to focus on the performance of math and reading scores which are disaggregated some points in the reports for a board meeting of the school district. After the school board reviewed the data, there was a suspection about the results of the report that are the data from Thomas High School's 9th grade class was dishonest. The school board asked for the data to be removed and analyzed again for a comparison.

* ### How is the district summary affected?
The testing data of 461 students of 9th graders at Thomas High School was turned into null data, which was recalculated the percentages of passing math, passing reading, and the overall passing. The total count of students did not change because that was run on the count of the student IDs, which was not turned into null data.

When comparing the two charts, removing less than 500 test scores had a nominal impact on 39170 students in data set. The difference is lesser than 1%
#### Current results vs. Original result:
![Current_result](https://user-images.githubusercontent.com/100484606/162560870-8a11c189-a341-4a2f-8a98-8856d7f6aecc.JPG)

![District_Summary_Original](https://user-images.githubusercontent.com/100484606/162596587-9398c82c-4144-4ed5-9d67-b44655bc4c16.JPG)

* ### How is the school summary affected?
The original result of Thomas High School has the overall passing rate with 91%. After calculating the total number of grades 10th - 12th by removing grade 9th out of the dataset, the result of the overal passing rate of the school dropped from 91% to 65%.

![THSpassingrate_65_Current](https://user-images.githubusercontent.com/100484606/162600406-ec25d458-bb29-4362-b8f6-7806b92cabee.JPG)

![THSpassingrate_91_Original](https://user-images.githubusercontent.com/100484606/162600414-daae1629-d059-4d3d-ac8d-cd9aa6017199.JPG)

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
* In the original report, Thomas High school ranked the 2nd place with 91% based on the overall passing score; however, with the current passing score of 65%, Thomas High school lost their position and drop to the middle of the rank.

### How does replacing the ninth-grade scores affect the following:
* #### Math and reading scores by grade: Ogirinal vs current:
Math and reading scores have been replaced with null value.

![Math_reading_original](https://user-images.githubusercontent.com/100484606/162601957-0a044222-bf1d-4328-a2f1-ac2c5cd5bdfc.JPG)

![New_mathscore](https://user-images.githubusercontent.com/100484606/162601964-cd588811-49f2-441e-bef4-c99444f8bf20.JPG)

![New_readingscore](https://user-images.githubusercontent.com/100484606/162601967-c8105f0d-de94-4951-91d6-941da98b55a0.JPG)

* #### Scores by school spending

Thomas High school falls in the spending range of $630-$644 per student. There is almost not much impact by replacing the grade 9th.

![Current_score_spending](https://user-images.githubusercontent.com/100484606/162601337-8f9d67e0-0ef9-497a-bfa9-745292287c45.JPG)

![Original_score_spending](https://user-images.githubusercontent.com/100484606/162601350-bab1cf2a-ae89-46f9-9f3c-9c04a761f044.JPG)

* #### Scores by school size
Thomas High school belongs to the medium size and there is almost the same before or after changing the dataset by dropping grade 9th.

![Current_schoolsize](https://user-images.githubusercontent.com/100484606/162601732-e4bae3c5-1146-4458-9fb0-333039965b00.JPG)


* #### Scores by school type
There is a very little impact by school type.

![Current_schooltype](https://user-images.githubusercontent.com/100484606/162601519-b71a6f75-2d2e-4c69-b29e-48b489c38d77.JPG)

![Original_schooltype](https://user-images.githubusercontent.com/100484606/162601529-0014aa55-f65c-41d9-bf58-22ddfddc1487.JPG)


## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

### The overall passing rate for Thomas High School changed dramatically from 91% to 65%.

### Thomas High School's ranking dropped from 2nd to almost the middle of 15 campuses.

### Data at the grade level will now show as "NaN" in reports for the 9th grade students at Thomas High School

### Beside the changes mentioned above, there was a little bit affects in others such as school spending scores, school size scores and school typle scores.
