# Kickstarting with Excel
##Overview of the project:
A playwriter named Louise wants to start a crowdfunding campaign to fund her play “FEVER” with an estimated budget of $10,000. Louise also wants to analyze how different 
campaigns fared in relation to their launch dates and funding goals.
### Purpose
The purpose of this project is to use Excel sheet as a tool to understand the parameters required to make her campaign successful.
## Analysis
Analysis was based on two parameters viz: outcomes based on goals and outcomes based on launch date. This is done with theater as a category, because it was proved earlier that theater outcome was successful compared to Food, Games, Technology etc. 
### Analysis based on Launch date:
To analyze the outcome based on launch date, a formula was used to create a column named “Date Ended Conversion” to convert the timestamp into a day-month-year format for interpretation in the Kickstarter data workbook. Then year was extracted from the “Date Created Conversion “column using a function called Year () to create a new column for Year. Based on these data, a pivot table was created into a new sheet named as “Theater Outcomes by Launch Date” from Kickstarter worksheet. By creating filters for “Parent Category” and “Years”, then filter the column labels for “successful”, “failed “and “canceled “and sorted in descending order so successful is first, and a pivot chart and a line graph was created was created as below. And saved as Theater_Outcomes_vs_Launch.png

