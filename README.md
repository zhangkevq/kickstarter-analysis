# Kickstarter Analysis Project
  An analysis project of Kickstarter trends requested by Louise, who wishes to know how other Theater campaigns fared in relation to their launch dates and funding goals. This report will seek to find the results of such Kickstarters and a trend in the data that would find the most success and failure based on these elements.

#### difficulties in the project
  Sorting of rows and columns in the creation of the pivot charts and graphs are not as clearcut as simply applying them to the fields. When adding launch dates to the rows, Excel will automatically try to add a new "Years" and "Quarters" element, which are not necessary. These needed to be removed from the rows field before creating the graph. In the goals chart, it was a challenge to use COUNTIFS in a way that takes multiple arguments to stratify the data.

## overview of project
* Outcomes Based on Launch Date Chart
* Outcomes Based on Goals Chart
* Zip file with all data: [Kickstarter Zip](https://github.com/zhangkevq/kickstarter-analysis/blob/main/Resources.zip)

### outcomes vs launch date
  First deliverable: a chart based on Outcomes of Kickstarter projects (success, fail, cancelation) vs. their Launch dates. This deliverable seeks to find the correlation between success rate and start month of the year for the Kickstarter project. Link to excel sheet: [Kickstarter Data](https://github.com/zhangkevq/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)
  
#### chart of outcomes vs launch date
![Outcomes vs Launch Dates](https://github.com/zhangkevq/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

  From the chart presented, there is peak success in theater projects that are started in May and drops off over the year while failure/cancellation remain much more consistent throughout the year.

### outcomes vs goals
  Second deliverable: a chart based on outcomes of kickstarter projects vs. their donation goals (how much they wanted to raise). This deliverable seeks to find the correlation between success rate and how much money the kickstarter project wanted to earn to meet their goals. Link to excel sheet: [Kickstarter Data](https://github.com/zhangkevq/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)
  
#### chart of outcomes vs goals
![Outcomes vs Goals](https://github.com/zhangkevq/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

  In this chart, there appears to be a downward trend for success. The higher the project's goal, the less likely it will be successful. This is also reflected in the upward trend for failure *and* cancelation.
  
