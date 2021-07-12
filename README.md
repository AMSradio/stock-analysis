# stock-analysis
Module 2 Exercises and Challenge

##Overview of Project
The purpose of this week's project is to refactor existing VBA code to conduct an analysis of performance given an array of ticker symbols of interest to the customer.

##Results
Refactoring the code streamlined the process time by approximately 20%. The average process time in the refactored code (between the two years) was 0.14 seconds compared to the original code that consisted of a lead time of 0.73 (on average between the two data sets). This will allow for the code to go through more information faster.

https://github.com/AMSradio/stock-analysis/blob/266672973665fc192262d0c9daeecd7959a89b7a/Resources/original_time_of_unfactored_code.PNG "Original Code Process Time"

https://github.com/AMSradio/stock-analysis/blob/266672973665fc192262d0c9daeecd7959a89b7a/Resources/VBS_Challenge_2017.PNG "Refactored Code Process Time for 2017"

https://github.com/AMSradio/stock-analysis/blob/266672973665fc192262d0c9daeecd7959a89b7a/Resources/VBS_Challenge_2018.PNG "Refactored Code Process Time for 2018"


##Sumary
The code has been refactored now to allow for faster analysis of the dataset. In short, this means that the dataset can be a living, breathing and expanding set and the code will be adaptable to process those changes on an ad-hoc basis by clicking the "Stock Analysis" button in the spreadsheet. A sort function has been added to the code to ensure that the ticker symbols are sorted in the right manner every time the code runs and identifies beginning and end prices.
