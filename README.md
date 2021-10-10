# Kickstarter-analysis

## Overview of Project
Louise wants to start a fundraising campaign for a play "Fever". She wants to know how different campaigns fared in relation to their launch dates and their funding goals based on the Kickstarter dataset she has. She would like to visualize the outcomes based on launch date, as well as based on Goals. Then she would like to see a written analysis of the results on the findings, including limitations of the dataset, and what other possible tables and/or graphs we can produce that would be helpful.

## Analysis and Challenges
1. From looking at the 'Theater Outcomes Based on Launch Date' chart , it is noticeable that 
    - There are more successful fundraisings than failed ones, in fact, it is more than doubled. 
    - There are more events happening from May to July period than any other months.
    - The successful fundraising has a normal distribution where it peaks in May.
    The dataset is collected from all over the world in years 2009 to 2017, but we are not able to see the impact as the chart is based on months only.  Activities in countries from southern hemisphere are different to those in northern hemisphere. We are not able to see the season different impact on the outcomes.

2. 'Outcomes based on Goal' chart shows a different story:
    - The success rate is 3 times higher than failed rate if you ask for less than $5,000;
    - the successful and failed lines are following a linear trend, yet opposite directions. The breakeven point is within $15,000 to $19,000 range. After the breakeven point, the more money you ask for, the more likely you fail. After $25,000 to $29,999 range, it's just random because of not enough data points to present the accurate story.

## Results
The conclusions we can make from 'Theater Outcomes by Launch Date' are:
- The period to launch a fundraising event is between April to Sept.
- The ideal month is May.
The take-away from 'Outcomes based on Goals' is you have a 50% success/fail rate if you ask for maximum $19,999. The success rate decreases as the goal goes towards $19,999.
We would need further filtering such as country, year etc to be able to have a more accurate picture.
