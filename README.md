# Analysis-on-Bike-sales-purchase
## Introduction: 
The objective of the analysis is to answer specific questions about bike buyers of different age bracket, region, educational background etc. Its also to show the relationship between regions, marital status, gender, average income and their respective purchase bike history

We answered key business problems through the data including finding the average income of each gender and their bike purchase history.  We also discovered the commute distance, age bracket of each individual in respect to their bike purchase

The data was gotten from an email sent by Joseph Elijah.

## Description of Data: 
The raw data has 1027 rows and 13 columns. It includes columns containing elements like Employer ID, Gender, Income, Children, etc.
The given data further helped us answer questions and analyze the data

## Data Methodology: 
Before proceeding with exploration and visualization, the data was properly cleaned. Below are the steps that was used.

The duplicate was removed by first highlighting and conditionally formatting the whole sheet to easily identify duplicated rows and blanks.

- I used the Remove Duplicates in the Data tab to remove duplicates and get unique data. We noted that the ID is the primary key in the table while removing duplicates
- I replaced M and S as well as M and F with Married and Single with Male and Female in the Marital status and Gender column respectively using the Find and Replace button in the HOME tab
- The income column was formatted to 0 decimal place and the dollar currency ($) using the Number Format button in the Home tab
- I then grouped the ages into three main age brackets using the IF function as the range was wide. Formula used is given as: =_IF(L2<=30,"Adolescent",IF(L2<=54,"Middle Age",IF(L2>=55,"Old")))
_
## Data Exploration
I made use of Pivot tables to explore the formatted data set and answer the given questions earlier outlined. 
From the analysis of Age bracket and bike purchase, we suggest that Middle age bracket should be given less attention by the Bike Manufacturers because it is discovered they usually buy more. More marketing focus should instead be on the adolescent and old age bracket because their count of bike purchase is relatively low.


![image](https://github.com/user-attachments/assets/d6811411-e8ef-4779-a4ee-1ae61f35e7af)



![image](https://github.com/user-attachments/assets/0158e0db-c935-45d0-814b-dad284da1a3e)

For this datasheet, we made use of mainly bar charts and line charts in Microsoft excel to visualize the data and create the dashboards.
- With the slicer in the dashboard above, we can deduce the behavior of European Middle age singles on Bike purchase
- Using the slicer, it is deducted that the Graduate degree earns more with an average income of $70,000, as shown in the image below
 
## CONCLUSION
From the above analysis using age bracket purchase, it was deduced that the **middle age** purchased more bike than old age and the adolescence and we also have it that the male have more income than the female using the bike average income purchase.

However, I recommend more attention should be given to the old age people because the purchase rate of bike is lower than the rest. I will suggest if age will be considered when producing the bike.






























  






