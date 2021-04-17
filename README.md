# Kickstarting with Excel

## Overview of Project

Louise, an up and coming playwrite, wants to know how different theatre campaigns fared in relation to their launch dates and their funding goals.

### Purpose

*The purpose of this analysis is to provide Louise the insights that she needs to set up her fundraising campaign.  With these inisights, Louise can make decisions that give her  a better chance of succeeding*. 

## Analysis and Challenges

The analysis was performed by looking at past Kickstarter theatrical fundraising campaigns. The results were further narrowed down to campaigns that were either successful or unsuccesful based off of their launch date and fundraising goal. 

The Kickstarter Crowdfunding data comes from: https://github.com/DSupps/Kickstarter_Challenge/blob/main/Kickstarter_Challenge.xlsx

### Analysis of Outcomes Based on Launch Date
By the time July and August start to come around there appears to be a decline in the amount of campaigns meeting their fundraising goal.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/36451701/115090093-ec0c6e80-9ee1-11eb-928b-78d1f4bade10.png)

### Analysis of Outcomes Based on Goals
To determine the outcome a campaign, the ones reaching their goal were labeled "successful", while ones that did not were "unsucessful". There were no canceled campaigns.

- Campaigns with goals up to $5,000 have about a 75% of being successful.
- Campaigns between $5,000 to $25,000 have roughly a 50% chance of being successful 


-  The lower the campaign goal the better.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/36451701/115091086-91c0dd00-9ee4-11eb-8faf-7b3290011327.png)


### Challenges and Difficulties Encountered

- The dataset did not come with a description about the data.  
- Columns labeled "staff_pick" and "spotlight" were included with not context. There might be some important data in there but I don't know what they are referring to. 
- The "blurb" column contained some characters that were hard to interpret. 

## Results

**What are two conclusions you can draw about the Outcomes based on Launch Date?**
- The time of year to start a campaign makes a big difference to the outcome. 
- Most successful theatrical campaigns are started in May or June.


**What can you conclude about the Outcomes based on Goals?**
- Choosing a campaing with a goal of lower than $15,000 gives Louise a much higher chance of succeeding. If she could keep her goal below $5,000, she would really boost here chances.


**What are some limitations of this dataset?**
- There just aren't as many campagins with goals above $15,000 in the data.  It is not as easy to say with confidence, that just because the goals are higher, they are more likely to fail. 
- There isn't a lot of context in the data. There is a blurb section but nothing that gives you enough to determine any correlations. 
- There aren't details about the individual backers. 
- What do "staff_pick" and "spotlight" mean?


**What are some other possible tables and/or graphs that we could create?**

1) A pivot table with spotlight in the rows, outcomes for columns and outcomes for values. Filtered by Parent category "theatre" and subcategory "plays". If you look further in the data, you see that all successful plays have TRUE in the "spotlight" column and all failed plays have FALSE.

2) A line graph with average donation to plays over time. Average donations to Plays has decreased significantly since 2015.






