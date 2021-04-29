# Kickstarting with Excel


## Overview of Project

### Purpose

The purpose of this project is to uncover hidden trends that may contribute towards the success of crowdfunding campaigns accross different countries.\
Particularly, here we are looking at the outcomes of fundraising for theatre projects, and trying to find if any correlation exists with their launch dates.\
We are also trying to reveal if any relationshsip exists between the crowdfunding outcomes for plays, and the goals set for their fund collections


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

A pivot table was created that showed the numbers of successful, failed and canceled crowdfunding campaigns that were launched in each month of the year.

![Outcomes Based on Launch Dates_Analysis](https://user-images.githubusercontent.com/71800628/116613660-93d06600-a8fe-11eb-9ea1-8bd1887c40c4.png)

The data was distilled for the category of theatre only. A line-chart showing the number of successful, failed, and canceled theatre projects for each month was created.


### Analysis of Outcomes Based on Goals

A table was created to show the number of successful, failed, and canceled campaigns of fundraising for plays within different goal ranges.\
The goal amounts were bracketed as less than 1000, greater than 50000, and in between, range brackets of 5000.\
Percentages of successful, failed and canceled campaigns were then calculated for each range.  

![Outcomes Based on Goals_Analysis](https://user-images.githubusercontent.com/71800628/116613334-29b7c100-a8fe-11eb-8144-6a7b9e07ab5c.png)

A line chart was plotted of the percentages of successful, failed, and canceled against the different range brackets. 


### Challenges and Difficulties Encountered
No challenges were ecountered during this analysis.
In the analysis of outcomes based on goals, the total number of projects with goals of 25000 and above decrease substantially. This decreases the trustworthiness of the outcomes for the goal ranges above this amount.
The data is collected across different countries, and the fund amounts are in different currencies. Therefore the outcomes based on goals should be approched with caution keeping in mind that the goal brackets are for absolute amounts for each currencies. 



## Results

#### Two conclusions that may be drawn about the Outcomes based on Launch Date.

![Outcomes Based on Launch Dates](https://github.com/Subhangi-G/kickstarter-analysis/blob/main/resources/Theatre_Outcomes_vs_Launch.png)

1) Out of the 1369 total campaigns for raising funds for theatre, the 111 launched in May were most successful.\
The best time to launch a campaign for theatre is between Apr. and July. 

2) The number of canceled campaigns were very low and remained almost steady over the months which might imply that their cancellation may not be dependent upon when they were launched.\
Similarly the number of failed campaigns also did not vary as much as the successful ones, but showed a similar trend to them being slightly elevated from Apr. through August, and in Oct. This could be bacause most campaigns for plays are launched during these months. Or maybe the faliure of theatre campaigns may not be completely dependent on the month of launch.

However, keep in mind that this is across different countries. A summer campaign launched in one country may not have the exact same in another country. The trend may be biased because of more number of data points representing one country.


#### Conclusions from the Outcomes based on Goals.

![Outcomes Based on Goals](https://github.com/Subhangi-G/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

1) Crowdfunding campaigns for plays were most successful when their goal amounts were less than 5000.\
For a comparable number of total projects, those with goal amounts between 5000 to 9999, had may be a slightly higher likelyhood of being successful.

2) Campaigns for goals between 10,000 to 25,000 also showed similar likelyhood of success and faliure. 

3) The trend seems to that asking above 20,000, to fund plays, will likely result in a failed project, except for the range beween 35000-40000. However this conclusion may not be relaible because the there aren't many projects in the ranges above 20000.



#### Some limitations of this dataset.
The number of campaigns for plays that have a very high goal amount (above 25,000) is very limited.
The dataset is spread over many years, and may not be evenly divided across the years. This affects the analysis of outcomes based on dates.
The above analysis shows that May is the best month to launch a theatre fundraising campaign, but that's an average over all the years. The results may be different for an individiual year.
The data may be incomplete. For example, only a count of a certain outcome may have been taken for some columns, say counting only successful campaigns in a certain year, or counting only cancelled plays from a country, or a goal bracket may have been left out for a region or a category or a year.



#### Some other possible tables and/or graphs that we could create.

1) An analysis of outcomes based on goals could be performed for different countries. 

2) Line charts showing the outcomes of plays by launch dates from different years could be created.

3) Line charts showing outcomes from separate countries could be created.
