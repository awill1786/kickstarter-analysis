#### Kickstarter Analysis

The purpose of this analysis is to show how different Kickstarter campaigns fared in relation to their launch dates and their funding goals. 

## Launch Date Based Outcomes
I started by adding a column, Years by utilizing the Years() function. I then used the data located within the Date Created Conversion to isolate only the year from the date. I then created a pivot table from the data. 

![This is an image]( https://github.com/awill1786/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch_Pivot.png) 

I filtered the Parent category to only show me campaigns that featured theater. The columns show the different outcomes by month.  One challenge I was running into was getting the rows to show the months. I was able to figure it out by only having the Date Created Conversion category in my Rows or Axis area.
From this data I was able to create a line chart with markers. 

![This is an image](https://github.com/awill1786/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png) 
 

## Outcomes Based on Goals
For this analysis we want to find out how many different outcomes there were based on the goal of the campaign. To start I created a table that features the different outcomes separated into columns, and the rows were separated by the goal. I then created a column that added the outcomes based on the goal amount, and then determined the percentage of each outcome based on the goal amount.
 ![This is an image]( https://github.com/awill1786/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals_Table.png) 



I didn’t have any issues obtaining this data, but one challenge I could see is using the proper syntax within the COUNTIF() function. Sometimes its easy to miss a quotation when trying to write the criteria for the formula. From this information I was able to create this chart. 

![This is an image]( https://github.com/awill1786/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)

 

## Results
From the Theater Outcomes by Launch Date chart, we are able to determine that May is the best month to launch a campaign based in theater. Also from the results, October was a month that featured 0 cancelations
From the Outcomes Based on Goals chart, it looks like as the goal gets higher, the percent of success drops, and the percent of failure increases. It is interesting to note that at the $30,000 goal, the trend reverses and the percent of success goes up again, until about $40,000 where it again goes back down.
A limitation of the outcomes based on goals data set is the inclusion of a line graph, I think a bar graph might look better in visually in showing each category.
