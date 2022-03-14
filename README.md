# Kickstarter-Analysis
Looking at trends using the Kickstarter data
## Analyzing Kickstarter Campaigns
Using the Kickstarter data provided, we can analyze and interpret patterns and create a better campaign plan. 
### Overview
The data provided conveys the fundraising campaigns that Louise helped plan. To better get a visualization of the timeline Louise needs for a campaign plan, an analysis is created. 
### Analysis
Using the first screenshot below as a visualization, a campaign ID is provided, a blurb to briefly describe the campaign, how much the goal and pledge is, and whether the campaign was successful or not, along with it being cancelled or being run live. The second screenshot visualizes the average donation made with each category of campaigns. The whole data is analyzed and extracted into pivot tables and charts. Columns with goals and pledge have been used to extract the outcome values used mostly in the charts. Filters were used to find specific quantity, for example, the Country column (G) was filtered to only see campaign outcomes only in the US.

Screenshot 1

  ![Screenshot of Kickstarter](https://user-images.githubusercontent.com/100643648/158088290-751f1c3c-a4da-4f37-99be-7711dfd83899.png)
  
Screenshot 2

  ![Screenshot of Kickstarter 2](https://user-images.githubusercontent.com/100643648/158088569-7107b73f-90b3-426f-a1c6-6174a4a253c3.png)
  
#### Challenges
Creating an analysis is not smooth sailing. Formulas have result in error, in which have tested my patience, but with the help of a step by step guide provided, I had the chance to try it on my own debugg errors. As someone who is not too familiar with the power of excel, it was a challenege as a whole as well, to curate a chart and making sure that the results make sense. Charts came out that looks different than the example provided and maybe there was a small step I had missed while curating the pivot table, but when reading the graphs, it made sense to me. There was a challenege in aggregating the X values or the Y values. A lot is still a challenege after this analysis but going back and forth with the Kickstarter workbook, and playing around with different settings, I am more knowledgable now than before the program started.
### Results
Looking at Graph 1, _Theater Outcomes by Launch Date_--- the subcategory was extracted from the Parent Category, which then was filtered out to **Theater** only, is used as the value in the line graph. Whether theater campaigns were successful, live or cancelled, over the years from the launch date, was visualize. (Due to a large range of years, the launch date was filtered by months). Comparing the trends between the three outcomes, the line graph makes it easier to see if the success rate decreased or increased over the months, same as live and canceled. 
The sum of all theater campaigns along with each of its outcome is shown here. The sum of all success, all lives and all canceled campaigns is shown as Grand Total in the X axis. A slow increase for each outcomes is visible, of course, showing more values in the success outcome for each month in the Theatre campaign only. 

Graph 1

[Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/100643648/158090917-0a0ffd84-943f-4a27-a636-a032af7aacc5.png)

Looking at Graph 2, _Outcomes Based on Goals_---this is based on the Parent Category in which only the Goal column (D) is extracted to see if the outcome is succesful or not. Grouping the goals such as having goals less than 1000 (dollar) to goals between 50000 (dollar) or more, is helpful in organizing the values. To calculate the number of successful outcome, failed and canceled, the excel formula **COUNTIFS** was used. This generated the specific amount found under each group of goals. The percentage was then calculated by dividing the amount of goal outcome by the total number of projects or campaigns. All throughout, both the number of canceled and percentage canceled  showed a consistent amount of 0, which can be seen in the graph as a horizontal line.

Graph 2

[Outcomes_vs_ Goals](https://user-images.githubusercontent.com/100643648/158091542-c8ff9f3d-7beb-4869-8660-879149ef1899.png)
### Conclusion
To conclude, the analysis itself is the best example of how to work with the basic functions in Excel. Having a step by step guide is needed and the most helpful. Creating pivot tables and curating charts practices the skills and tools taught by having them be put into action. Each graph does not align with the example graph provided in the module but having to follow the steps and still seeing different results in the graph was really challenging to overcome. To find more graphs and tables based on the Kickstarter data, please refer to the excel file uploaded. [Kickstarter_Challenge.xlsx](https://github.com/Mae-Linda-Vidal/kickstarter-analysis/files/8241211/Kickstarter_Challenge.xlsx). Louise can better visualize the next campaign plan based on similar goals with past campaigns and similar outcomes. 
