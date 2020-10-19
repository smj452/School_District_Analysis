# School District Analysis
## Overview of the project

Maria, a chief data scientist for city school districts has asked for help in analyzing the student’s math and reading test scores from 15 different schools. The data includes breakdowns by grade, school type, funding level and size. The goal of this project is to gain insights from the data on key metrics for each school, which will help the county education board make budget decisions for the next academic year. Before the results of the analysis were published, the school board was notified about academic dishonesty relating to reading and math grades for Thomas High School ninth graders in the ```students_complete.csv``` file. Although the school board does not know the full extent of the academic dishonesty and is still looking into the matter, they want to continue the analysis while upholding state-testing standards. Therefore, the math and reading scores for Thomas High School have been replaced with NaNs while keeping the rest of the data intact.

## Results

After removing the reading and math scores, the following are the conclusions made:

### 1.How is the district summary affected?

Overall scores went down with the removal of the scores belonging to Thomas High School 9th grade students.  Below is a before and after snapshot

**District Summary without Thomas Highschool 9th graders**


![DistrictSummarywithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/District_Summary_withoutTHS.png)


**District Summary with Thomas Highschool 9th graders**


![DistrictSummarywithTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/District_Summary_withTHS.png)

### Findings

-	"Average Math Score" is reduced by 0.1
-	No change in "Average Reading score"
-	"% Passing Math" is reduced by 0.2%
-	"% Passing Reading" is reduced by 0.3%
-	% Overall Passing" is reduced by 0.1%

### 2.How is the school summary affected? 

As the school summary has no bins based on performance, the only school affected was THS.  Where the affect can really be illustrated is in the is in the percentage of students passing math reading and overall.  Before the students were removed the % for math reading and over all were in the mid 90%’s and after they were in the mid to high 60%’s.  THS’s performance relative to other schools was also greatly affected.  

**School Summary without THS 9th graders**

![SchoolSummarywithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/School_Summary_withoutTHS.png)



**School Summary with THS 9th graders**

![SchoolSummarywithTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/School_Summary_withTHS.png)



### 3.How does removing the ninth graders’ math and reading scores affect Thomas High   School’s performance, relative to the other schools?

With making 9th grader math and reading scores to NaN, the "% Passing Math", "%   Passing    Reading" and "% Overall Passing numbers dropped drastically by ~18-26%

### 4.How does removing the ninth-grade scores affect the Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, and Scores by School Type? 


**Math Scores**

![Math_scorewithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/math_score_withoutTHS.png)


![Math_scorewithTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/math_score_withTHS.png)



**Reading Score**

![Reading_scorewithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Reading_score_withoutTHS.png)


![Reading_scorewithTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/math_score_withTHS.png)


**Scores by school spending**

![scores_by_schoolspendingwithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Scoresbyschoolspending_withoutTHS.png)


![scores_by_schoolspendingwithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Scoresbyschoolspending_withTHS.png)

From the above image we can clearly see that is no change in "Average Math Score", "Average Reading Score ", "% Passing Math", "% Passing Reading" and "% Overall Passing" for any of the spending bin ranges per student.


**Scores by school size**

![scores_by_schoolsizewithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Scoresbyschoolsize_withoutTHS.png)


![scores_by_schoolsizewithTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Scoresbyschoolsize_withTHS.png)

From these images we can depict that "Average Math Score", "Average Reading Score", "% Passing Math", "% Passing Reading" and "% Overall Passing" for any of the school size ranges aren't affected by removal of the ninth-grade scores.

**Scores by school type**

![scores_by_schooltypewithoutTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Scoresbyschooltype_withoutTHS.png)


![scores_by_schooltypewithTHS](https://github.com/smj452/School_District_Analysis/blob/main/Resources/Scoresbyschooltype_withTHS.png)

From the above images we can say that the "Average Math Score", "Average Reading Score", "% Passing Math", "% Passing Reading" and "% Overall Passing" for either Charter or District school aren't affected by the removal of the ninth-grade scores.

## Summary

Impact from replacing 9th grade Math and Reading scores:

### School summary 

-	Thomas High school Average Math & Reading scores is lower compared to the one including 9th graders.
-	Thomas High School has seen 66.911315% passing math compared to 93.272171%. i.e. around 26.3% change.
-	Thomas High School has seen 69.663609% passing reading compared to 97.308869%. i.e. a decline of 27.6%
-	Overall passing percentage for Thomas High School has changed from 90.948012 to 65.076453 i.e. a difference of 25.8%

### District Summary 

District has seen lower scores for Average Math and Average Reading. Also, seen a slight variance in Passing Math, Passing Reading and Overall Passing percentage


