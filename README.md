# kickstarter_analysis
Kickstarter analysis to uncover data trends for theater project


### Overview of Analysis
* The purpose of this analysis is to review and analyze data regarding the success of fundraising campaigns to hold plays and theater productions at various times of year and countries.


### Analysis and Challenges
####Analysis
* First, by using the YEAR() function, I added a column in the Kickstarter sheet to track what year each theater campaign was started,
* In a new sheet, a PivotTable was created showing the category, time frame in months, and the success, failure, or canceled rate of each play broken down by month.
* Using this data, I created a line chart to help visualize what these numbers actually look like over the course of a year.
![Theater_Outcomes_vs_Launch](path/to/Theater_Outcomes_vs_Launch.png)

* In a separate sheet, I made a data table showing the rate of success, failure, and cancellation (using the COUNTIFS() function), and the total amount of projects (using SUM()), as well as their percentages based on the goal dollar amount of fundraising for each project (for this I did need to Google how to do this, using variable1/variable2 to complete it)
* A line chart was created to help visualize the percentage of these categories.
![Outcomes_vs_Goals](path/to/Outcomes_vs_Goals.png)

####Challenges
* I did not struggle much with the first deliverable, though I can see issues with being able to accurately determione the YEAR() values if the Date Created Conversion column was not completed correctly or there was an error in one row.
* I did, however, have several issues with the second deliverable. 
** It took me some time to work the formula for COUNTIFS into the sheet, primarily because I missed a step in the instructions and didn't include that part of the formula when calculating the total successes, failures, and cancellations.
** When doing the line chart, I mistakenly chose a stacked line chart instead and could not get the selected data (the percentages of success, failure, and cancellations) to properly appear in the chart. I tried changing the type from bar (where all data appeared as it should) to (stacked) line, where it then disappeared, before realizing I was using the wrong type of line chart.


### Results
1) the most successful theater productions all occurred over the summer months, as opposed to the winter months.
2) while there was some increase during the summer for the failed productions, the line graph shows far less change, indicating there might be some other reason for these failures than time of year.
3) This other reason can be postulated from the data shown in the Outcomes Based on Goal chart, where it can be seen that the higher the goal of the fundraising campaign, the more likely productions are to fail or fewer are to be successful.
4) Limitations could include a lack of defining what the subject matter in relation to popular culture at the time of the production may have had to do with impacting the success of the production, as well as the geographical location and population density that the production took place in.
5) Another table/chart that could be helpful would be one that tracks the success, failure, and cancellation rate in relation to how long each fundraising campaign went on for.
