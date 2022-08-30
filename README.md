# Kickstarting with Excel

## Overview of Project

### Purpose
Up-and-coming playwright, Louise, has launched her first fundraising campaign for her play *Fever*. In a very short amount of time, *Fever* came close to its fundraising goal. The purpose of this project is to discover how launch dates and funding goals impact different campaigns. 
The analysis was performed on the Kickstarting dataset which contains fundraising goals, launch dates, outcomes, etc.  Utilizing pivot tables,  functions, formulas and charts, we are able to visualize campaign outcomes and their relationship with launch dates and funding goals. 

## Analysis and Challenges

![Link to Kickstarter Analysis file](Kickstarter_Challenge.xlsx)

### Analysis of Outcomes Based on Launch Date

For the analysis of outcomes based on launch date, we utilized pivot tables to summarize the data and filter it to only only show "Theater" campaigns.
A line chart was created from the pivot table to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date.

### Analysis of Outcomes Based on Goals

For the analysis of Outcomes Based on Goals, we used Excel formulas and functions to calculate the percentage of "successful", "failed" and "canceled" plays based on the funding goal amount. Again, we used a line chart to visualize the relationship between outcomes and campaign goals.

### Challenges and Difficulties Encountered

One the challenges was using the COUNTIFS function to populate the "Number Successful," "Number Failed," and "Number Canceled" since criteria changed based on the goal range for each of the cells to be populated. Changing the criteria manually could have led to errors.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Based on the analysis of theater outcomes based on launch date, we can conclude that there is a larger number of successful campaigns lauched in the  months of May, June and July (Summer). The most successful month was May; 66.9% of the 166 total campaigns launched were successful.
On the other hand, we can conclude that the least successful campaigns took place the winter months (Nov, Dec, Jan). December was the month with most failed campaigns, 46.67% of 75 campaigns failed.
![Outcomes based on launch](/Resources/Theater_Outcomes_vs_Launch.png)

- What can you conclude about the Outcomes based on Goals?

We can conclude that the most successful campaigns are the ones with the lowest goals while campaigns with larger goals tend to fail. 
The most successful goal range was "less than $1000" with 76% sucess rate, followed by the  "$1000 to $4999" range with 73% sucess rate. 
Campaign goals of "$45000 to $49999" and "$50,000 or more" are the most unsucessful with 100% and 88% failure rate respectively. 
![Outcomes based on goal](/Resources/Outcomes_vs_Goals.png)

- What are some limitations of this dataset?

One of the limitations of this dataset is that the sample size of the categories of our interest is not large enough and the results might not tell a true story. 
In the analysis of outcomes based on goal, we are only focusing on Plays and the total number of projects with goals over 15000 is only 86 while the total number of projects with goals less than 14999 is 961. For instance, campaign goals of "$45000 to $49999" show a 100% failure rate but there is only one campaign in this range and that one campaign failed. This does not necessarily mean that all campaigns in the "$45000 to $49999" goal range will a 100% fail but because our sample size is 1, the story might be misleading. 

- What are some other possible tables and/or graphs that we could create?

We can create also create a stacked column chart for both analyses. For the Outcomes based on Launch Date, we can compare the successful, failed and canceled outcomes as whole and show how it changes over time. 
A clustered column chart can be created for the Outcomes based on Goals to compare the values across the different categories: % successful, % failed and % canceled. 
