Cyclistic Bike Share Google Capstone Project

Project Goal

The primary goal of this project is to analyze and understand the behavior of casual and annual riders at Cyclistic Bike-Share to develop strategies that encourage casual riders to become annual members.


Data Collection

The dataset comprises monthly files from the entire year of 2023. Each month's data was stored in a separate file. To consolidate the data for analysis, I used Microsoft SQL Server (MSSQL) and combined the files using the UNION ALL function.


Data Cleaning

To ensure data consistency and quality, the following steps were undertaken:
Consistency Checks: 

•	Ensured consistent data formatting across all files. 
•	Renamed columns for better clarity and uniformity. 
•	Split date columns into separate components (e.g., day, month, year). 
•	Filtered out records with null values in start and end station columns. Duplicate Identified and removed duplicate records.
•	Removed columns that were not relevant to the analysis. 
•	Ensured that all data cleaning steps were performed while keeping the original data intact.


Data Analysis

The analysis focused on understanding the riding patterns and preferences of casual and annual riders. Key aspects analyzed include:

•	Bike Preferences: examined which types of bikes were preferred by casual and annual riders during weekdays and weekends. 
•	Peak Hours: identified hot hours when rides were most frequent. 
•	Temporal Patterns: plotted ride data across weeks and months to discern patterns and behaviors. 
•	Geographical Analysis: analyzed the most popular start and end stations to understand which areas of Chicago are frequented by casual and annual riders for leisure and work.


Recommendations


Based on the analysis, the following strategies are recommended to attract casual riders to become annual members:

•	Special Offers: Create special offers for annual memberships specifically targeted towards casual riders on weekends. 
•	Incentives: Provide attractive incentives, such as exclusive access to certain routes or events, appealing particularly to casual riders. 
•	Group Rides: Organize group rides on weekends, fostering a sense of community and encouraging casual riders to become annual members. 
•	Showcase Benefits: Highlight membership benefits, such as free bike maintenance, discounts on accessories, and exclusive seasonal discounts for annual members.


Conclusion 


By understanding and analyzing the behavior of casual and annual riders, Cyclistic can implement targeted strategies to convert casual riders into annual members, ultimately increasing membership and promoting a more engaged rider community.

