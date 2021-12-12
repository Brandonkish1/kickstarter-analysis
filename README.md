# An analysis of kickstarter campaigns

## Overview
Lousie needs to raise $10,000 to produce her play Fever. This is an analysis of kickstarter campaigns to guide Louise on what characteristics a successful campaign has. Included is an analysis of campaigns based on goal size and an analysis of campaigns by launch date.

## Analysis and Challenges

### Analysis

I performed the analysis by creating pivot tables and charts on the kickstarter data set. I utilized the vlookup and countifs functions to get required data into the right locations in order to make the pivot tables.

### Challenges

I had some trouble with the countifs function. I had forgot the "" around the text in the formula. This took me a little while to trouble shoot and before correcting it.

![]()

## Results

### Theater Outcomes by Launch Date

![]()

The summer is the best time to launch a kickstarter campaign with May, June and July having the most successful campaigns. May was the best month overall.

December is the worst month to start a campaign, there were almost as many failed campaigns as there were successful.

### Outcomes by Goals

![Outcomes_vs_Goals](https://github.com/Brandonkish1/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

In general the smaller the goal the more likely the kickstarter campaign is to be successful, with the highest success rate being for goals under $1,000. Once the the goal exceeds $15,000 it is more likely to fail than succeed. The exception to this is the $35,000 to $45,000 range of goals. Louise's goal of 10,000 is more likely to succeed than fail.

### Limitations of Data

#### Limitations
Some limitations to the data are its not a huge data set. Having more data could have possibly given different results. Another limitation is that there is data from 21 different coutries. Different countries may have different donation habits. Having all data from country that Louise wants to launch the play in may be better.

#### Other Potential Analysis
Another useful analysis would be to look at successful campaigns to determine the starting month of the campaigns that meet their goal the fastest. 
