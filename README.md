# School District Analysis
Click here to view my code: [PyCitySchool_Challenge](https://github.com/jzaragoza21/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Overview of Project

The PyCity Schools challenge presented us with two objectives: 1) identify and replace the inaccurate math and reading scores for 9th graders at Thomas High School using the Pandas loc method. Thereafer, we use the Pandas NumPy module to change those reading and math scores to NaN. 2) Repeat the School District Analysis we did in module 4. This process included 15 steps to recreate the following metrics:

    1. The district summary
    2. The school summary
    3. The top 5 and bottom 5 performing schools, based on the overall passing rate
    4. The average math score for each grade level from each school
    5. The average reading score for each grade level from each school
    6. The scores by school spending per student, by school size, and by school type
    
## Results

In reviewing the key performance indicators (KPIs) of both original dataframe and the dataframe without Thomas HS ninth graders, much of it remained the same. Provided this was a large data set of over 39,000 students, removing scores of a few hundred students' scores from one of fifteen schools, the overall impct was substantial. The initial dataframe for all 15 schools is below:


![Original Dataframe](https://github.com/jzaragoza21/School_District_Analysis/blob/main/Resources/School_District_Analysis_Original_Dataframe.png)



Below is the updated dataframe with Thomas High School's ninth graders reading and math scores removed. In comparing the KPI's from both data frames, Thomas High School's average math/reading scores and math/reading passing percentage changed. Addiionally, their overall passing percentage also changed. 


![Updated Challenge Dataframe](https://github.com/jzaragoza21/School_District_Analysis/blob/main/Resources/School_District_Analysis_Challenge_Dataframe.png)


## Summary

The four major changes after removing the Thomas High School's math and reading scores were the following: 

    1. Overall student count
    2. The numbers of students used to calculate Thomas High School's scores
    3. Thomas High School's math/reading scores and math/reading passing percentage
    4. Thomas High School's overall passing percentage

While all these scores changed, what is notable is that all these overall school scores dropped. However, the drop was marginal in all these cases, only dropping by tenth of a percent or close. To me, this demonstrates that the overall scores of the ninth grade were roughly aligned with the rest of the school, thereby not impacting THS' overall KPIs. Having said that, it also shows that the ninth graders math and reading scores were, albeit close, likely slightly better, given the drop in overall scores.


