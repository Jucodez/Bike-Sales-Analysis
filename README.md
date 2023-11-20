# Bike Sales Dashboard


## Problem Statement

This survey collects data on various individuals in different demographic classes and reveals if they purchased a bike or not.

This dashboard helps the motorbike manufacturing company understand its potential customers better. It helps them to know who best to market to accross different demographics.


## Steps followed 

- Step 1 : Load data into Microsoft Excel, dataset is an excel file.
- Step 2 : Copy orginal data into another sheet where it would be edited.
- Step 3 : Turned on filter for column headers.
- Step 4 : Identified misssing data in columns using filter to identify blanks (No misssing data identified).
- Step 5 : Remove duplicates.
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Examine unique values in categorical columns for error. 
- Step 8 : Find and replace (M and S) to (married and single) in marital status column.
- Step 9 : Find and replace (f and m) to (female and male) in marital status column.
- Step 10 : Change income column to actual currency data type. 
- Step 11 : Change decimal precision of income column to whole number.
- Step 12 : Create Age brackets from age col using:

    =IFS(L2 > 54, "Old", L2 >= 31, "Middle-age", L2 < 31, "Adolescent", TRUE, "Invalid")

- Step 13 : Extract average income for both genders for those who. bought a bike and those who didnt using pivot tables.
- Step 14 :  Use clustered Column Chart to Visualize gender data
- Step 15 :  For each commute distance category, extracted percentage that purchased bikes and those that didnt using pivot tables.
- Step 16 :  Use line Chart to Visualize commute distance data.
- Step 17 :  For each Age group, extracted percentage that purchased bikes and those that didnt using pivot tables.
- Step 18 :  Use line Chart to Visualize age group data.
- Step 19 :  Create a dashboard by arranging the graphs in a new sheet
- Step 20 :  Add marital status, region and education as filters and connect to all charts.

## Insights

A single page report was created on Microsoft Excel.

The following inferences can be drawn from the dashboard;

### [1] Bike Purchase Rate Per Age Bracket 

   Overall, Among various age groups, analysis reveals that middle-aged individuals had the highest percentage of bike purchases (54.64%)

   This trend noticably changed in the Pacific as Adolescents were the ones with the highest bike purchases (86.72%)
           
### [2] Bikes Purchased Rate Per Comute Distance

   Across various commute distances, disctances of 0-1 Miles and 2-5 Miles had the highest percentage of bike purchases (54.64% and 58.64% respectively)

   10+ miles had the lowest percentage of bike purchases (29.73%)
 
  
### [3] Average Income Per Purchase By Gender

   Across both genders examined those that purchased bikes had a higher average income
   
   This trend was sustained across both marital statuses examined (married and single)
