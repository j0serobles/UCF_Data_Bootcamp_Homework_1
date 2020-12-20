# Excel Homework: Kickstart My Chart
Files for Homework #1 (Excel Homework) for the UCF Data Analytics &amp; Visualization Bootcamp Dec. 19 2020

## Introduction

In this homework, we organize and analyze a database of 4,000 Kickstarter projects in order to find any hidden market trends. 

## Starter Table

![Kickstarter Table](Images/Sheet1_Conditinal_Formatting.PNG)

This figure shows the provided table wih the 4,000 past Kickstarter projects.  

  * The "state" column has been color coded depending on the results of the campaign, green=successful, red=failed, gray=canceled, blue=live.  The "percent funded" column uses a three-color scale, showing a dark shade of red for 0, transitioning to green at 100% and blue at 200% funding.

  * The `Average Donation` column uses a formula to uncover how much each backer for the project paid on average.

  * The `Category and Sub-Category` column has been split into two additional columns, one for `Category` and one for `Sub-Category`.
  
  ## Category Stats

  ![Category Stats](Images/CategoryStats.PNG)

  This worksheet has a pivot table that analyzes the starter table, counting how many campaigns were successful, failed, canceled, or are currently live per **category**.  It also includes ate a stacked column pivot chart that can be filtered by country.
  
  ## Subcategory Stats

  ![Subcategory Stats](Images/SubcategoryStats.PNG)

  This worksheet has a pivot table that analyzes the starter table, counting how many campaigns were successful, failed, canceled, or are currently live per **sub-category**.  It also includes ate a stacked column pivot chart that can be filtered by country.  It also includes a stacked column pivot chart that can be filtered by country and parent-category.
  
  ## Outcomes Based on Launch Dates

  ![Outcomes Based on Launch Date](Images/LaunchDateOutcomes.PNG)

  This worksheet contains a pivot table with a column of `state`, rows of `Date Created`, values based on the count of `state`, and filters based on `parent category` and `Years`.  It also includes a pivot chart line graph that visualizes this new table.
  
  ## Report
  Access the report in Microsoft Word format [here](report.docx)

## Bonus


# Goal Outcomes

  ![Goal Outcomes](Images/GoalOutcomes.png)

This worksheet contains a pivot table and a line chart graphs the relationship between a campaign goal's amount and its chances at success, failure, or cancellation.

## Bonus Statistical Analysis

If one were to describe a successful crowdfunding campaign, most people would use the number of campaign backers as a metric of success. One of the most efficient ways that data scientists characterize a quantitative metric, such as the number of campaign backers, is by creating a summary statistics table.

For those looking for an additional challenge, you will evaluate the number of backers of successful and unsuccessful campaigns by creating **your own** summary statistics table.

* Create a new worksheet in your workbook, and create a column each for the number of backers of successful campaigns and unsuccessful campaigns.

  ![Images/backers01.png](Images/backers01.png)

* Use Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:

  * The mean number of backers.

  * The median number of backers.

  * The minimum number of backers.

  * The maximum number of backers.

  * The variance of the number of backers.

  * The standard deviation of the number of backers.

* Use your data to determine whether the mean or the median summarizes the data more meaningfully.

* Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?


© 2019 Trilogy Education Services
