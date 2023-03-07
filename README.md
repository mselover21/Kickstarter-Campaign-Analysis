# Analyze Kickstarter Campaign Data to Determine Trends

## Project Overview
-	The purpose of this project is to analyze data on Kickstarter campaigns to determine when the best time of year is to launch a successful campaign. The second purpose is to determine outcomes of Kickstarter campaigns based on the campaign goals. These two analyses will help the client make decisions about their own campaign to ensure success. 

### Analysis and Challenges

1.	Analysis
-	I broke the data down into specific categories to determine Theater Outcomes Based on Launch Date. I created a pivot table in a new worksheet to focus on only theater campaigns specific to the clients needs. After filtering the data based on Parent Category and Years, I separated the data based on the outcomes; successful, failed, and canceled. After this I created a line chart to better visualize the outcomes of theater Kickstarter campaigns based on launch date.
![Theater_Outcome_vs_Launch](https://github.com/mselover21/ExcelChallenge/blob/main/Theater_Outcomes_vs_Launch.png)
Next, I created a new worksheet to analyze the outcomes of Kickstarter campaigns, specifically plays, based on their goals. I first created columns with the Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Successful, Percentage Failed, and Percentage Canceled. The Goals were organized in increments of 5000 starting with Less Than 1000 and ending with 50000 or More. After creating the table, I utilized the COUNTIFS formula to populate the table with the correct data. Finally, I created a line chart to better visualize the percentages of successful, failed, and canceled theater campaigns.
![Outcomes_vs_Goals.](https://github.com/mselover21/ExcelChallenge/blob/main/Outcomes_vs_Goals.png)
2.	Challenges
-	One thing I did struggle with was using the COUNTIFS formula correctly when creating the outcomes based on goals table. I have never utilized extensive formulas such as the COUNTIFS function and found it difficult. I was able to correctly use the formula by referencing the lessons in module one as well as using classroom exercises to get the correct results.
-	I also found uploading the analysis to GitHub difficult due to it being the first time ever using a program such as GitHub. I found the lessons in module one to be very helpful in making sure that the project was uploaded properly. I also found the basic writing and formatting link on GitHub’s website to be very useful in creating proper headers and formatting of the repository.

#### Results

1.	Theater Outcomes Based on Launch Date
-	At the end of this analysis there are two conclusions that can be made. The first conclusion is that the most successful theater campaigns were launched in the month of May with a steady decrease to September. Based on the data the best time to launch a successful theater Kickstarter campaign would be the month of May. The second conclusion that can be made is that there is a slight spike in failed and successful campaigns during the month of October. The spike in failed campaigns is more significant that the spike in successful leading me to recommend not starting a campaign during October due to a higher chance of failure. 
2.	Outcomes Based on Goal
-	When looking at the data of outcomes based on starting goal it seems that the data that higher starting goals have a higher percentage of failure and lower starting goals have a higher percentage of success. With this it appears that having a lower starting goal for funding increases the chances of having a successful Kickstarter campaign. 
3.	Limitations
-	The data in question is a relatively small sample size of a little over 1000 Kickstarter campaigns. This can prove problematic when it is data collected between 2009 to 2017. If there is more data collected over a longer period, the data could show unforeseen trends when more years are added. Additionally, I would recommend the use of a box and whisker chart to indicate if there are outliers that are skewing the data. Outliers can cause misinterpretation of that data by skewing it in a certain direction. 
