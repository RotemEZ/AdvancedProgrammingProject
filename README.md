# Team-15-Project

For running the the code with the dataset, you'll need to download the sav 
file from the drive to your computer. Then, go to the code repository.
Go to where we firstly declare the variable "data", place the path of the
file in the function "read_sav()" and run the code(there is instructions in
the code).

This dataset includes a range of variables that were carefully selected to capture important
psychological characteristics of the individuals being studied. The psychological variables include 
measures of life satisfaction, depression, ability to deal with problems, and future expectations. 
These variables were chosen because they are important determinants of well-being and are commonly 
used in studies investigating the factors that contribute to individuals' life satisfaction and 
mental health. By examining the associations between these variables, this dataset can provide 
valuable insights into the complex interplay between numerous factors that contribute to individual 
well-being.

ID - The ID of the individual, numeric

T3gender- the gender of the individual, numeric(1-female, 2- male, 3-transgender, 4-other)

T3martial_status- the martial status of the individual, numeric(1-married, 2-living separatdely, 
3-divorced, 4-widower, 5- single)

T3_children_no- Does the individual have children?, numeric(1-yes, 2-no)

T3education_level- What is the highest diploma or degree you have received?, numeric(1- I graduated 
from elementary school or middle school, including those who attended high school and did not 
graduate, 2- High school graduation certificate (not a matriculation certificate), 3- Matriculation 
certificate, 4 - High school graduation certificate that is not an academic certificate (for 
example, 13, 14), 5-First academic degree B.A, or an equivalent degree, 6- A second M.A. academic 
degree, or an equivalent degree including a Doctor of Medicine, 7 - Do not read -----, 
8 -Other certificate, 9 - You didn't get any certificate )

T3education_courses- Did you attend courses for professional training, after graduating from high 
school, such as: computers, electricity and electronics, bookkeeping, carpentry?, numeric 
(1-yes, 2- no)

T3army - Did you serve or are you currently serving in the IDF?, numeric(1-yes, 2- no)

T3army_fullservice - Have you served full military service?, numeric(1-yes, 2- no)

T3civil_service - Did you do national service?, numeric(1-yes, 2- no)

T3civilserv_full - Did you serve full national service? Women - two years, men - two years, 
numeric(1-yes, 2- no)


### All the columns below, with the prefix of T3, relates to the third assessment:

T3_15.230_2 - Now I will ask questions relating to different emotional states in the last year - 
have you felt depressed?, numeric(1-always or frequently, 2- sometimes, 3- seldom)

T3_15.230_3 - In the past year - did the individual feel that he could deal with his problems?, 
numeric(1-always or frequently, 2- sometimes, 3- seldom)

T3_15.340 - In general, is the individual satisfied with his life?, numeric(from 0 to 10, 
where 0= not satisfied at all; 10 = completely satisfied)

For all the columns below, the individual were asked how much he agreed with the statement:

T3_life_satisfaction_1- I am doing well in life?, numeric(1- never, 2- sometimes, 3- usually, 
4- almost always)

T3_life_satisfaction_2- My life is just as it should be, numeric(1- never, 2- sometimes, 
3- usually, 4- almost always)

T3_life_satisfaction_3- I would like to change many things in my life, numeric(1- never, 
2- sometimes, 3- usually, 4- almost always)

T3_life_satisfaction_4-I wish I had a different kind of life, numeric(1- never, 2- sometimes, 
3- usually, 4- almost always)

T3_life_satisfaction_6 - I have everything I want in life, numeric(1- never, 2- sometimes, 
3- usually, 4- almost always) 



For all the columns below, the individual were asked the next question: when you think about 
your future, how certain are you that each of the following will happen?

T3_future_expect_1- You will have good friends, numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

T3_future_expect_2 - You will have a stable, good and long relationship,  numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes)

T3_future_expect_3 -Be a good parent, numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes) 

T3_future_expect_6- You will have a good profession, numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes) 

T3_future_expect_8- . You will have problems of unemployment, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes) 

T3_future_expect_9 - You will have an academic education, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes) 

T3_future_expect_10 - You will have problems with the police, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes) 

T3_future_expect_11 - You will have emotional difficulties, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes)



For all the columns below, the individual were asked the next question: what you think 
you can do today independently?

T3_skills_4 - Succeed in a job interview? numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

T3_skills_12- Avoid getting involved in bad company?, numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

T3_skills_13- Avoid getting drunk? numeric(1- definitely not, 2- I don't think so, 3- I think so, 
4- definitely yes)

T3_skills_14- Avoid using drugs? numeric(1- definitely not, 2- I don't think so, 3- I think so, 
4- definitely yes)

T3_skills_15 - Avoid getting into trouble with the law?, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes)



### All the columns below, with the prefix of B, relates to the second assessment:

For all the columns below, the individual were asked the next question: what you think 
you can do today independently?

B.LIFE.SKILLS.ALL_4- Succeed in a job interview? numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

B.LIFE.SKILLS.ALL_12 - Avoid getting involved in bad company?, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes)

B.LIFE.SKILLS.ALL_13 - Avoid getting drunk? numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

B.LIFE.SKILLS.ALL_14 - Avoid using drugs? numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

B.LIFE.SKILLS.ALL_15 - Avoid getting into trouble with the law?, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes)

B.OPTIMI - When you think about your ambitions and goals for the future, how optimistic 
(positive) you are about your future? numeric(1-to a very small extent, 2- Slightly, 3- Moderately, 
4- to a high extent, 5- to a very high extent )


For all the columns below, the individual were asked the next question: when you think 
about your future, how certain are you that each of the following will happen?

B.FUTURE.EXPECT.ALL_1- You will have good friends, numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes)

B.FUTURE.EXPECT.ALL_2 - You will have a stable, good and long relationship,  
numeric(1- definitely not, 2- I don't think so, 3- I think so, 4- definitely yes)

B.FUTURE.EXPECT.ALL_3 -Be a good parent, numeric(1- definitely not, 2- I don't think so, 
3- I think so, 4- definitely yes) 

B.FUTURE.EXPECT.ALL_6- You will have a good profession, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes) 

B.FUTURE.EXPECT.ALL_8- . You will have problems of unemployment, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes) 

B.FUTURE.EXPECT.ALL_9 - You will have an academic education, numeric(1- definitely not, 
2- I don't think so, 
3- I think so, 4- definitely yes) 

B.FUTURE.EXPECT.ALL_10 - You will have problems with the police, numeric(1- definitely not, 
- I don't think so, 3- I think so, 4- definitely yes) 

B.FUTURE.EXPECT.ALL_11 - You will have emotional difficulties, numeric(1- definitely not, 
2- I don't think so, 3- I think so, 4- definitely yes)


For all the columns below, the individual were asked how much he agreed with the statement:

B.LIFE.SATISFACTION_1- I am doing well in life?, numeric(1- never, 2- sometimes, 3- usually, 
4- almost always)

B.LIFE.SATISFACTION_2- My life is just as it should be, numeric(1- never, 2- sometimes, 3- usually, 
4- almost always)

B.LIFE.SATISFACTION_3- I would like to change many things in my life, numeric(1- never, 2- sometimes, 
3- usually, 4- almost always)

B.LIFE.SATISFACTION_4-I wish I had a different kind of life, numeric(1- never, 2- sometimes, 
3- usually, 4- almost always)

B.LIFE.SATISFACTION_6 - I have everything I want in life, numeric(1- never, 2- sometimes, 3- usually, 
4- almost always)




