# boba--tea-shop-analysis
Working on data optimization
## Project Overview
As a data analyst at a marketing agency in San Francisco, I was tasked with preparing a dataset for a potential collaboration with local boba tea shops. The goal was to target top-rated shops within a 10-mile radius of our focus area. My team sourced data on shop ratings and locations from an online source, but the dataset was messy and inconsistent. It was my responsibility to identify the problematic elements, clean the data, and ensure it was accurate and ready for analysis to support our campaign planning efforts.
### Data Source:
The primary dataset used for the analysis is "Bobatea_shop.csv" file, Containing detailed inforation of sales.
### Tools:
- SpreadSheets (Data cleaning)
### Eliminating Duplicate Entries:
The first step in cleaning a dataset is removing any duplicate entries to ensure data accuracy and integrity. Duplicates can skew analysis results, even if they are not immediately obvious.
###  Cleaning Inaccurate Data:
Identify Invalid Yelp Ratings: Yelp ratings should fall between 0 and 5. Any ratings outside this range need to be corrected.
Use the COUNTIF Function: To find the inaccurate ratings, you can use the COUNTIF function in Google Sheets. The function will allow you to count the number of entries that do not meet the valid range of 0-5.
### Cleaning Latitude and Longitude Data:
Use the SPLIT Function:
To separate the latitude and longitude values from a single column into two distinct columns, the SPLIT function in Google Sheets is useful. This function divides the text around a specified character or string and places each part into a separate cell in the row.
  
