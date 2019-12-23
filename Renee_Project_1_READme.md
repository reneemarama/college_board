### DSI - College Board ###

The College Board is investigating where to best invest funds to increase SAT participation. Based on analysis of participation rates and scores, I recommend focusing funding strategies in West Virginia, Ohio, and New Mexico.

**Data Set:**

The data sets include SAT and ACT participation rates, total and composite scores, and subtest scores for 2017 and 2018 (excluding ACT subtest score for 2018).  In order to perform analysis on the data set, given as .csv files, the data was cleaned with appropriate corrections for typos and formatting. There are many factors important in making a recommendation to the College Board and below outlines my findings and recommendations. 

**Analysis:**
To begin, analysis shows that  ACT and SAT participation rates are inversely correlated (-0.65). Where ACT participation is high, SAT participation is low, and vice versa. So let’s assume that it would cost more to convert an ACT dominate state then it would to focus on states already with a strong foothold in SAT participation.

Interestingly, analysis reveals a negative correlation between participation and high tests scores. College Vine says that this is because if a test is preferred by a state, students will only take the unpopular test if they think they’ll do well [1]. 

Notably, several states had 100% participation in 2018: Colorado, Connecticut, Delaware, Michigan, and Idaho. Four states were close behind with above 95% participation: Illinois, Maine, Rhode Island and New Hampshire.

After looking at participation rates for the SAT between 2017 and 2018, we can see that for the most part, participation rates were similar between 2018 and 2017 with a few exceptions. For example, Colorado and Illinois had phenomenal increases, from 11% participation to 100% and from 9% to 99% respectively.

!["SAT Participation 2017 and 2018"](project_1/plots/2017_2018.png)


A handful of additional states had significant growth in participation rates from 2017 to 2018, as shown in the graph below. This is important because it’s easier to capitalize on growth where there is momentum than to start fresh in markets with cold or stagnant trends. In order to ensure a productive return on investment, I excluded states where 2018 participation remained below 10%, and states with 99% or greater participation.  In conclusion, the states with the most traction and opportunity to grow are West Virginia, Ohio, and New Mexico. I recommend the College Board further investigates these states for the best return on investment of SAT participation.

!['SAT percent change of participation'](project_1/plots/null_less_plot.png)

**References:**

https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/