# Kickstarting with Excel

## Overview of Project
We are helping an up-and-coming playwright, Louise, who wants to start a crowdfunding campaign, or kickstarter, to help fund her play, *Fever*. Kickstarters allows project creators to add incentives for different pledge amounts. She's estimating a budget of over $10,000.

### Purpose
 Our aim is to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful.

## Analysis and Challenges
We do this by first determining how much money people have pledged to campaigns historically. Then we organized and viewed data in the Theater campaigns category and refined it even further by sub-categories such as sci-fi or drama.
Finally we transposed this data into charts that showed the Theater Outcomes by Launch Date and the Outcomes Based on Goals amount.

### Analysis of Outcomes Based on Launch Date
We used a line chart to show the correlation between outcomes and launch date. To do this, we compared the total number of Successful, Failed, and Canceled Theater campaign outcomes to the months they were launched in.

### Analysis of Outcomes Based on Goals
We used a line chart to show the correlation between outcomes and goal amounts. To do this, we calculated the percentages of Successful, Failed, and Canceled campaign outcomes for "plays" respectively which were then compared to Goal amounts that increased by $5,000 increments (except for goals that were less than $1K and greater than $50K)(we calculated this with a countif ex.'=COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")').

### Challenges and Difficulties Encountered
One challenge someone may encounter is calculating the Date Created/Ended Conversions without prior knowledge of Unix Timestamps.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date? 

The best date to launch is in May and the worst is in December. Furthermore, theater outcomes are more likely to succeed on average.

- What can you conclude about the Outcomes based on Goals?

Based on the data, there is an initial negative correlation between Goal amount and the percentage of Successful campaigns until approx. $25K where the successfulness increases as the Goal amount increases. This trend is true until approx. $45K where it decreases then increases again from $50K. The inverse is also true for the percentage of Canceled campaigns.

- What are some limitations of this dataset?

One drawback is that there isn't an even number of total projects which can skew the data because there is only one project between $45000-$49999 and 533 projects between $1000-$4999. 

- What are some other possible tables and/or graphs that we could create?

We could've created a clustered column chart to represent the Theater Outcomes by Launch Date.