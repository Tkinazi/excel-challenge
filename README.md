
For the dataset consisting of 1000 projects carried between the years of 2010 and 2020. I did the following.

*Used conditional formatting to fill each cell in the "outcome" column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

*Created a new column called "Percent Funded" that uses a formula to find how much money a campaign made relative to its initial funding goal.

*Used conditional formatting to fill each cell in the "Percent Funded" column according to a three-color scale. The scale starts at 0 with a dark shade of red, and it transitions to green at 100 and blue at 200.

*Created a new column called "Average Donation" that uses a formula to find how much each project backer paid on average.

*Created two new columns, one called "Parent Category" and another called "Sub-Category", that use formulas to split the "Category and Sub-Category" column into the two new, separate columns.

*Created a new sheet with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

*Create a stacked-column pivot chart on the sheet named "Category Stat" that can be filtered by country based on the table that I created.

*Created a new sheet named "Sub-Category Stat" with a pivot table that analyzes the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

*Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that I created.

*The dates in the "deadline" and "launched_at" columns use Unix timestamps. I used the formulaLinks to an external site that can be used to convert these timestamps to a normal date.

*Created a new column named "Date Created Conversion" that will use this formula Links to an external site to convert the data contained in "launched_at" into Excel's date format.

*Created a new column named "Date Ended Conversion" that will use this formula Links to an external site to convert the data contained in "deadline" into Excel's date format.

*Created a new sheet with a pivot table that has a column of "outcome", rows of "Date Created Conversion", values based on the count of "outcome", and filters based on "parent category" and "Years".

*Then, created a pivot-chart line graph that visualizes this new table.

*Wrote a report in Microsoft Word summarizing my findings regarding the data I had read.

*To conduct a crowdfunding goal analysis, I created a new sheet with 8 columns
* 	Goal
*	Number Successful
*	Number Failed
*	Number Canceled
*	Total projects
*	Percentage Successful
*	Percentage Failed
*	Percentage Canceled

*In the "Goal" column, i created 12 rows with the following headers
*	Less than 1000
*	1000 to 4999
*	5000 to 9999
*	10000 to 14999
*	15000 to 19999
*	20000 to 24999
*	25000 to 29999
*	30000 to 34999
*	35000 tp 39999
*	40000 to 44999
*	45000 to 49999
*	Greater than or equal to 50000

*Using the "COUNTIFS()" formula, I counted how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populated the "Number Successful", "Number Failed", and "Number Canceled" columns with these data points.

*Added up each of the values in the "Number Successful", "Number Failed", and "Number Canceled" columns to populate the "Total Projects" column. Then, using a mathematical formula, found the percentage of projects that were successful, failed, or canceled per goal range.

*Created a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

As most people use the number of campaign backers to assess the success of a crowdfunding campaign. I created a summary statistics table based on the number of campaign backers.

*Created a new worksheet in your workbook, and created one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

*Used Excel to evaluate the following values for successful campaigns, and then did the same for unsuccessful campaigns:

-The mean number of backers

-The median number of backers

-The minimum number of backers

-The maximum number of backers

-The variance of the number of backers

-The standard deviation of the number of backers

-I used the data to determine whether the mean or the median better summarizes the data. As a supporting statistic, I calculated the skewness and used as a supporting argument to determine which statistic to use whether mean or median.

 
