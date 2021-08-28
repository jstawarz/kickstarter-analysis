# Kickstarting with Excel

## Overview of Project

In this analysis, we are working to provide our client, Louise, with information regarding how different Kickstarter campaigns performed,
based on their launch date and funding goals. Using the data provided for various Kickstarter campaigns, we will use Excel to compile, 
analyze, and provide Louise with deliverables to demonstrate how the results of the campaigns compared to their launch dates and fundraising goals.

### Purpose

To provide Louise with insight as to how different Kickstarter campaigns performed in relatation to their launch date and fundraising goals. 

## Analysis and Challenges

This analysis was primarily carried out in Excel, utilizing Excel formulas, Pivot tables and Pivot charts to compile, analyze and display the
data in question. We converted the timestamp data provided using the DATE, ROUND, YEAR, COUNTIF and SUM functions to format, summarized and 
calculate the data needed to perform the analysis. We also utilized Text to Column, Filters, Pivot Tables and Pivot Charts to create, sort and
visualize the data needed to delivery insights from the data. 

![This is an image](/resouces/Excel.png)

##Results

### Analysis of Outcomes Based on Launch Date

Based on the analysis, the months of May, June and July show the highest numbers of succuessful Kickstarter campaigns. Conversely some of the highest number of 
failures also occured during these months, May being the highest, July and October tying for second, and June in third. However, percentage wise, December
seems to be the worst month for theater related Kickstarters, with only 37 succusses, 35 failures and 3 cancellations. 

![This is an image] (/resources/Theater_Outcomes_vs_Launch)

### Analysis of Outcomes Based on Goals

Looking at the outcomes versus goals data, as the chart suggests, the rate of a successful campaign deceases the higher the fundraising goals, while the
failure rate increases the higher the fundraising goal. The data would suggest that a lower fundraising goal would increase the chances of success. 

![This is an image] (/resources/Outcomes_vs_Goals)

### Challenges and Difficulties Encountered

Challenges in this analysis were that the original Kickstarter data was not provided with all data points needed and in a readibly useable format. For
example, in order to provide analysis based on start date, the time stamp data needed to be converted into a decipherable format. Additionally, 
to provide analysis regarding the outcomes of the Kickstarter based on goals, additional calculations were needed to obtain the percentage of the goal
that was ultimately funded. This is to all to say, the data provided was not immediately complete for the purposes of out analysis. It was a
challenge to work with the data to obtain the data points needed to complete the analysis.

The dataset was also limited to Kickstarter campaigns. To provide a more comprehensize analysis, sources of data from other fundraising campaigns could
also have been helpful. Additionally, it could be that the campaigns received donations or other support from outside of the Kickstarter website. If so,
the data itself could be inaccurate. 

###Other Possibile Charts and Tables

Another possibility for a helpful chart could be average donation. In a similar fashion to the Outcomes Based on Goals, we could create a table of successful,
failed and canceled outcomes for plays compared to the average donatation given. Using this information, we could render a suggestion to Louise to ask for
a specific dollar ammount when soliciting donations. 
