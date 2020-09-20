# Kickstarting with Excel

## Overview of Project

Louise created a Kickstarter campaign to raise money for her play creation "Fever", her campaign came close to its fundraising goal in a short amount of time and she would like to review the data to compare the relationship of other campaigns specifically focusing on using their Launch Date and Fundraising Goals as variables. 

### Purpose

The purpose of this analysis is to provide an in-depth look at other campaigns (a variety and categorically specific).

## Analysis and Challenges

The analysis was conducted by organizing the data and correcting and fields to be readable. The Unix Timestamp converter was used to create date/time format; Parent/Subcatagory was split with 'Text to Columns', =years() was used to pull out the data based on annual launch dates, colors were assigned to the different outcomes with the 'Highlight Cells Rules' using 'Equals to', and percentage funded was determined and color shaded. Challenges could be encountered with incorrect formulas and data. 

![Outcomes VS Goals](/Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Launch Date

The Outcomes Based on Launch Date allow Louise to see sorted outcomes on "plays" as it relates to the year, month, day, time, and any combination of these variables. This can assist with not only what years (paired with financial information of the economy for specific years) produced more successful outcomes but also what launch month have a higher success rate. For example, the 1st and 4th quarter produces a much lower rate of success assuringly paired with holiday spending and time spent away from investing research and social media advertisements related to subjects outside of the holidays. 
	

### Analysis of Outcomes Based on Goals

The Outcomes Based on Goal allow Louise to see a variety of comparisons in the specific category of "plays" as it relates to the goals set by other campaigns. This allows an analysis of goal ranges that end successfully versus failed or canceled - this information can be used to set her goals in a predictive range for ending successfully. 	

### Challenges and Difficulties Encountered

## Results 	

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Campaigns that launch in quarter 2 and quarter 3 have a higher success rate
2. With the exception of December, Successful Campaigns for plays comes within 20% of doubling the amount of Failed Campaigns showing that plays carry an overall success rate with Kickstarter Campaigns.

- What can you conclude about the Outcomes based on Goals?

Goals over $45,000 have a considerable increase in being Failed Campaigns and campaigns with goals less than $5,000 and $$35,000-$44,999 carry the highest success rate.

- What are some limitations of this dataset?

Some limitations of this data include the omission of what advertising efforts were used for each campaign and more specific geographic location of each campaign.

- What are some other possible tables and/or graphs that we could create? 

1. The outcomes based on the amount of backers and average donation - this would assist her in knowing the spread across population she would need to reach 

2. The outcomes based on the "live" span of the campaign to see if more 'sprint' or 'marathon' campaigns are more successful. 

3. The amount of percentage funded for "plays" to see if it is an overall successful campaign category.  

