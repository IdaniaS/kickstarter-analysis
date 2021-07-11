# **kickstarter-analysis**
Performing analysis on Kickstarter data to uncover trends
## Overview
### Background
Louise's created a play _Fever_ that came close to its fundraising goal in a short amount of time. There is a variety of launch dates for each campaign and the funding results ranged from successful, failed or canceled.
### Purpose
The purpose of this analysis was to determine how different play campaigns fared in relation to their launch dates and their funding goals. Comparing the Play outcomes to the launch date and goals to determine the best goal and time to launch a campaign.
## Analysis and Challenges
### Anaylsis
The analysis of the dataset started with an initial look and collection of the data. Once the data was formatted and filtered to resemble the play outcomes the next step was to determine how many campaigns were successful, failed or were canceled based on their launch date. This data was collected to create a graph to represent the [Theater Outcomes by Launch Date](https://github.com/IdaniaS/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png). This graph will provide insight to the time of the year when a campaign will be the most likely to succeed, as the month is shown on the x-axis with the comparison to outcomes along the y-axis. Along with this graph it is important to take a look at the campaign outcomes vs the goal amount of money to raise for each event. This graph presents the goal amount along the x-axis while the outcome percentage is on the y-axis. The [Outcomes vs Goals](https://github.com/IdaniaS/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png) is important to view as it factors in the possible negative impact of increased 
### Challenges
The challenges when working with the dataset came with removing unwanted data points and outliers. This was determined in the cleaning stage of anaylsis. Outliers and irrelevant observations have impacts on the overall dataset. Outliers are extreme points of data that can be much larger or smaller than the rest of the data presenting skewed results. This challenge of outliers can be overcame by using the Median and IQR method. The IQR refers to the Interquartile Range. This is a guideline used to determine outliers that have a value greater than the upper quartile plus 1.5*IQR or any value less than the lower quartile minus 1.5*IQR. It is important to eliminate outliers because it draws away from the important data.

## Results

Through structuing and labeling the data it became clear in identifying patterns and connections between how theater campaigns fared in relation to their launch dates and their funding goals. 

The [Theater Outcomes by Launch Date](https://github.com/IdaniaS/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png) presents the data in a graph. The graph provided insight to which months had the most successful outcomes. The Theater campaigns that were the most likely to succeed were launched in the month of May with about a 61% chance of overall success. 


https://github.com/IdaniaS/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png (Outcomes vs Goals)
https://github.com/IdaniaS/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png (Theater Outcomes)
https://github.com/IdaniaS/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx (Excel file)
