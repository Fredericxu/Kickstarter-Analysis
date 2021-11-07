# Module 1: Kickstarter

Analyze a dataset consisting of 4,000 crowdfunding projects to discover hidden trends.
## Overview of Project:
### Purpose:
Analyze a dataset consisting of 4,000 crowdfunding projects to discover:
1. Worldwide Theater Successful Number Based on Launch Months during year 2009 to 2017
2. US Theater Successful Rate Based on Goals during year 2009 to 2017
## Analysis and Challenges:
1. https://github.com/Fredericxu/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png
  - Followed the instructions from the challenge 1 assignment
  - Difficulty occurs when descending the outcomes but after playing with the data a little, the problem solved.
  - There are discontinued date for canceled in Oct. Maybe it is just didnt included in the original data set.
2. https://github.com/Fredericxu/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png
  - Followed the instructions from the challenge 1 assignment
  - It takes a lot of time for debuging the "countifs" functions with different sections like 0 to 1000, 1000 to 1500 to be very accurate.
  - The lines from the chart intersects three times near 17500/35000/45000 which means they dominate in different sections and adding up to 100%
  - There is "0" case for canceled data, which is a doubt to me at first.

## Results:
### Analysis of Outcomes Based on Launch Date
1. December has the lowest successful rate for Theater launching
2. May has the highest succesful rate for theater lauching
### Analysis of Outcomes Based on Goals
1. Below 15000 goal, the lower the goal was, the more chance it would be successful.
### What are some limitations of this dataset?
1. Average Disposable income on each year/each country should be considered as another factor or even with the specific city
2. Date column "staff picked" is not used or considered into the analysis
### What are some other possible tables and/or graphs that we could create?
1. Add a filter with "Staff_picked" to show the difference that affected by this input change.

## Details of the project
### Deliverable 1
1. Date Created Conversion in Sheet “Kickstater” Column S
2. Pivot Table created in Sheet "Theater Outcomes by Launch Date"
3. Please see cells A1:B2 for Pivot Table filters on "Parent Category" and "years". 
4. Please see cells A4:E18 for the columns, rows, and values in the pivot table fields are correctly populated.
5. Please see cell B2 for the "Parent Category" is filtered on "theater" . 
6. Please see cells A5:D5 for the row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order.
7. Please see the diagram in sheet "Theater Outcomes by Launch Date" for the line chart.

### Deliverable 2
1. Please see sheet "Outcomes based on goals" for "A new sheet is created with eight columns and twelve rows, according to the instructions".
2. Please check countifs functions in cells B2:D13
3. Please check Sum functions in cells E2:E13
4. Please check the percentage in cells F2:H13
5. Please see the diagram for the line chart.