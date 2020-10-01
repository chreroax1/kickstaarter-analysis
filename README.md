# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview of Project

The project we are examining in this report is for the client "Louise." Louise wants to know how different campaigns fared in relation to the launch dates and the funding goals.  

### Purpose

The purpose is to identify the trends in historical data from other fundraising campaigns with similar monetary goals.  We examine what factors affect achieving the monetary goal, by looking at the outcomes based on launch dates and outcomes based on stated goals.

## Analysis and Challenges

Looking at the data presented, the data is not user friendly and needs to be reformatted so that it is not overwhelming. 

We created a new sheet, "Outcomes Based on Launch Date," and created a pivot table to filter "Parent Category" and "Years." We filtered the column labels to show only "successful," "failed," and "canceled." Using the pivot table, we could use the "Parent Category" filter to show only the data for “theater.” From that we were able to use the data to create a line chart so we can easily visualize the relationship between the outcomes and the launch month.
 ![Theater_Outcomes_vs_Launch](https://github.com/chreroax1/kickstaarter-analysis/blob/master/Resources/Theater_Outcomes_vs_Launch.png)

Lastly, we created a new sheet, named “Outcomes Based on Goals” and new pivot table so we could group the dollar-amount ranges based on their goal amount. Using “COUNTIFS()” function to populate the “Number Successful,” “Number Failed,” and “Number Canceled” based on the “outcome” and the “goal” ranges created. Using the pivot table filter for “Subcategory” we could use “plays” as our criteria. We then used the “SUM()” function to populate the “Total Projects” column with the number of successful, failed and canceled projects for each goal range. We could then generate our line chart so we can better visualize the relationship between our “Outcomes” and the “Goal” set. 
 ![Outcomes_vs_Goals](https://github.com/chreroax1/kickstaarter-analysis/blob/master/Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Launch Date

Summer months (May-July) appear to be the most successful time period to launch a "theater" Kickstarter campaign. Although there is a slight uptick in failures during this period, the failure rate is insignificant compared to the overall success rate. Specifically, the month May has the highest success rate of 67% and the lowest failure rate of 31%. If at all possible, launch a Kickstarter campaign in May.

The worst months to launch a “theater” campaign is during winter (Sep.-Mar). The worst month being December. It saw the same amount of failures as it did successes. 


### Analysis of Outcomes Based on Goals

As seen in the chart titled "Outcomes Based on Goal," we can see although there are some fluctuations, the higher the goal set, the higher the failure rate. A goal of less than 5000 has the highest success rate. Our data in the less than 5000 range is more reliable because we have more data sets to work from.  


### Challenges and Difficulties Encountered
The most challenging issue I encountered was writing this report. Interpreting the data, to me, can be done in many different ways depending on how you look at it. I just needed to figure out how to look at the given data and interpolate it the best way I saw fit. 


## Results

  The two conclusions drawn from the "Outcomes Based on Launch Date" data is that May and June are the two best months to launch a compaign and December is the worst month.
  
  The easiest conclusion to come to using the "Outcomes Based on Goals" is you have a higher chance to succeed the lower the goal set.
  
  Some of the limitations of the dataset is there is not enough data points for the higher number goal sets. Majority of the projects had low goals which made them more appear more successful.
  
  Other tables and graphs we could use is to filter country to determine what types of campaigns are successful around the world.
