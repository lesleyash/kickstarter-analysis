# kickstarter-analysis
Performing analysis on Kickstarter data

## Overview of Project
### Purpose
The purpose of the analysis is to help Louise to understand how the outcomes of campaigns are related to launch dates and funding goals.

## Analysis and Challenges
I created Pivot tables to summarize the number of events based on outcome. Line Charts have been created to provide the visualization of the results.

The challenge is the original data are not structured to be easily analyzed. I have created additional columns to extract key information from original data.

### Analysis of Outcomes Based on Launch Date

I have created a Pivot table to summarize the number of the success, failed, canceled, and live and a line chart to show visualized results.
Based on the chart (***Theater Outcomes based on Launch Date***) below, month May has the highest successful outcome, while December has the lowest successful outcome. In terms of number of failed campaigns, there is no significant difference among months.

#### Theater Outcomes based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92648619/139609847-49bbc6d0-b10e-495d-adc1-f55e2a3c7b80.png)

### Analysis of Outcomes Based on Goals

I have utilized *COUNTIFS* formula to summarize the success rate based on different level of campaign goal amounts. The chart (***Outcome_vs_Goals***) below visualized the success rate and failed rate among different goal groups. 

#### Outcomes vs Goals
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92648619/139611726-a3cbadc7-31a1-4574-82f4-3521a1c812c8.png)

### Challenges and Difficulties Encountered

The number of campaigns which has a goal amount higher than $25k is very small compared to other groups.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. If Louise would like a higher success rate for the campaign, she should launch the campaign during May or June.

  2. I suggest Louise avoid campaign launching in December as it has the lowest success rate.

- What can you conclude about the Outcomes based on Goals?

  When the goal amount of campaign is below $24,999, there is a negative correlation between goal amount and success rate. 

- What are some limitations of this dataset?

  During the analysis of outcome based on goals, the sample size of campaigns which has a goal mount higher than $25k is not sufficient to make any trend analysis. 

- What are some other possible tables and/or graphs that we could create?



