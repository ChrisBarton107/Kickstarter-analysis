# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview of Project  
Kickstarter is a platform on the internet that enables creative projects to come to life through crowdfunding. The kickstarter data set included information involving various project campaigns around the world. Notable categories of data include the name of the kickstarter campaign, a “blurb”, or description of the campaign, their goals in fundraising, outcomes, campaign category/genre, country of origin, and launch dates. Data provided in the analysis was collected between May 2009 and March 2017 and includes 4114 total campaigns.

### Purpose  
The objective of the analysis is to help our friend Louise extract useful information regarding campaign launch dates and financial fundraising goals to compare to her own project. Louise raised money in a short amount of time in effort to fund *Fever*, the play that will be her new campaign. Information relevant to Louise' interests includes campaign outcomes of plays in Great Britian. Using the data set as a comparison, we set out to extract information based on the outcomes of other campaigns based on their launch date (time of year) and the financial fundraising goals established prior to beginning the campaign. 

## Analysis and Challenges  
Louise is interested in the campaign outcomes of plays in Great Britian. For reasons of comparison, it was necessary to filter the main data set with three main filters, including country, outcome, and category. The initial data used a "category & subcategory" column which was later used to create two new columns, including "Parent Category" and "Subcategory". 

### Analysis of Outcomes Based on Launch Date
Analysis of campaign outcomes based on their launch date used a total of 1,369 campaigns of the original 4,114 in the dataset. A pivot table was created that uses outcomes as columns and all 12 months of the year as rows. A line chart was created from the table, using months of the year (launch date) as the x-axis and total sum (successful, failed, canceled) from each month as the y-axis.

### Analysis of Outcomes Based on Goals
Analysis of campaign outcomes based on financial fundraising goals used data from the plays subcategory. Plays, a subcategory of the theater parent category, contained 1,066 campaign items of the 1,369 theater campaigns and 4,114 total campaigns. Data was divided into 12 categories and calculated the total number of successful, failed, and canceled campaigns in addition to the percentage of successful, failed, and canceled campaigns. The 12 categories used in this analysis occupy our charts x-axis and range from financial goal quantities of "Less than 1000" to "Greater than 50,000" with increments of approximately 5,000. The y-axis displays percentage values pertaining to successful, failed, and canceled theater campaigns. 

### Challenges and Difficulties Encountered  
Desired analysis was completed without any noteworthy challenges.

## Results  
**What are two conclusions you can draw about the Outcomes based on Launch Date?** 
Campaigns launched during late spring/early summer were most successful in achieving their goals. The rate of canceled campaigns remained relatively consistent throughout the year. 

**What can you conclude about the Outcomes based on Goals?** 
Campaigns with greater financial fundraising goals were more likely to fail while campaigns with less financial fundraising goals were more likely to succeed. 

**What are some limitations of this dataset? - What are some other possible tables and/or graphs that we could create?**
The analysis which captured information regarding outcomes related to launch date does not factor in the duration of the fundraising campaign. This information is provided in the data but is not factored into the analysis. The addition of a fundraising time duration variable would likely have a major influence on results. The data captured reveals the benefits of launching campaigns during late spring/early summer but could be misleading by not disclosing time duration of the fundraising campaign. 
