# Kickstarting with Excel
 
## Overview of Project
 
### Purpose
This project came together as a means to deliver information to Louise and her staff about the outcome of other theater/play campaigns in regards to their launch date and fundraising goals. The objective of the project is to look at the campaign outcomes based on their launch date and their fundraising goals. The results, as well as the data collected and visualizations from the project will be sent to Louise and her campaign staff.
 
## Analysis and Challenges
 
### Analysis of Outcomes Based on Launch Date
The analysis of the data began with a comparison between the results of campaigns and the month they started. I started by creating a pivot table to quickly summarize the data and portray an overview of the data. Afterwards, I filtered the data to specifically look at theater campaigns. Subsequently, I added both the campaign outcomes and launch month.
 Based on the pivot table, we can see how many successful, failed, or cancelled theater campaigns were launched in a particular month. Using a line chart, I visualized the data over the ensuing twelve months. By doing so, the trends or peaks of the data within the successful and unsuccessful campaigns could be identified.
![Outcomes_Based_on_Launch_Date](https://github.com/shireenkahlon/Kickstarter-Analysis/blob/main/Screenshots/Theater_Outcomes_vs_Launch.png)
 The chart above illustrates three significant trends that may indicate a correlation. It can be seen in the graph that theater campaigns have a tendency to be successful between April and May. Additionally, between September and October, a substantial trend of unsuccessful campaigns has been observed. Last but not least, successful campaigns decline between October and December. Understanding these trends is vital to gaining a full understanding of the data.
 
### Analysis of Outcomes Based on Goals
 As a way of determining whether fundraising goals were achieved, a table was created that summarized all the projects and their success, failure, and cancellation percentages. There are different fundraising goals by denomination (1,000 to 4,999, 5,000 to 9,999, etc.) up to 49,999, and over 50,000. Every group of fundraising goals was listed along with its percentage result. Finally, I filtered the data to show only play campaigns. In the table, we show how the percentages and numbers of successful, failed, and cancelled campaigns change with an increase in fundraising goals. To visualize the data, I created a line graph, attached below. The graph depicted the trends and peaks in the successful and failed play campaigns as the fundraising goals increased.
![Outcomes_Based_on_Goals](https://github.com/shireenkahlon/Kickstarter-Analysis/blob/main/Screenshots/Outcomes_vs_Goals.png)
 In the data presented, we can see three trends that help solidify our conclusions. In the first instance, the percentage of successful campaigns declines as the fundraising goals grow in monetary value - with two exceptions. Additionally, overall play campaigns decline as fundraising goals increase.The majority of play campaigns are within the budget range of $1000-$4999. Additionally, over half of all failed play campaigns had a budget of $45,000 or higher. As a result of these data trends, we can fully analyze the data and derive conclusions from it.
 
### Challenges and Difficulties Encountered
 I encountered no particular challenges or difficulties while working with this dataset. Handling a dataset this large could pose a variety of challenges. Functions and columns can make filtering data difficult. Re-filtering data or adding a filter where it should not be added is a common mistake; this may alter the data used for analysis. Another challenge with large datasets is that it's possible to enter the wrong column or row into pivot tables or functions. This may change how the data appears in a graph and may not accurately represent the data.
 ## Results
 
#### What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the trends in the data, it is possible to draw two conclusions about the results of the data. First of all, launching a campaign in May may have an impact on its success. It seems that campaigns that begin in September or December suffer from a similar correlation. Besides the launch month, other factors may influence the campaign's success or failure. To examine a true correlation, a correlation matrix or other data science work is required. 
 
#### What can you conclude about the Outcomes based on Goals?
Using the data, we can draw conclusions about outcomes based on three trends. Successful campaigns may be attributed to fundraising goals between $1,000 and $14,999 as well as $35,000 and $44,999. In other words, a campaign's success might be related to a low fundraising goal. A higher fundraising goal - especially above $45,000 - may lead to a lower chance of a successful play campaign.
 
 
#### What are some limitations of this dataset?
The dataset has limitations. First, there are no genre data for the plays. Comedy plays, for example, may be more successful than drama plays. Another limitation may be marketing techniques — for example, the more successful campaigns may have television ads, billboards, and radio ads whereas the failed campaigns solely went off word of mouth. One other limitation is the lack of a venue and a city or state the play will be held in. The play may not be as successful at a small school theater in a rural town as it would be at a large theater hall in New York City, for example. A play's location and city or state can provide insight into whether it affects the outcome of the play.
 
#### What are some other possible tables and/or graphs that we could create?
From the original dataset, additional tables can be made that compare the percentage funded and/or the average donation with the campaign outcome. Some additional graphs that can be created for individual projects are stacked or clustered bar charts for viewing campaigns by launch date. This would help compare the number of successful versus unsuccessful campaigns per month. Pie charts can be generated by summing the number of successful and failed goals, dividing the percentages of each goal by the total number, and creating two pie charts from this data. 

