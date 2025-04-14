# Keyword-Analysis-Project
This project calculates the visit ratio of each website within its keyword group

# Website Popularity Analysis by Keywords

## Project Overview
This project analyzes web visit data by grouping websites based on their associated keywords.  
The main goal is to calculate the **popularity** of each website within its keyword group by comparing its visit count to the total visits of that keyword group.

## Tasks Completed
- Loaded and explored the dataset using Pandas  
- Grouped data by keywords to analyze keyword frequency  
- Filtered keywords with fewer than 1400 total visits  
- Calculated the visit ratio of each website using `groupby` and `transform`  
- Created a new column called `popularity` to show each website’s share (in %) within its keyword group  
