# Advance-spreadsheets-Manhattan-borough-AirBnB

In the initial phase, the dataset from NYC Airbnb was thoroughly reviewed. Each sheet within the dataset, including the data dictionary, listings, and calendar, was examined to identify useful columns and potential data cleaning challenges. Tabs were created in the report for documenting data cleaning steps and version updates of the project file. The spreadsheet was organized by freezing rows and columns for easier scrolling, resizing columns, wrapping text, and adding filters. A copy of the raw data was made to maintain a reference, and listings irrelevant to vacation rentals, such as those with a minimum night requirement of more than seven days or no reviews in the past year, were filtered out and documented.

In the subsequent analysis phase, rental activity was estimated using the number of reviews in the last 12 months as a proxy for how often a property was rented. The neighborhood data was cleaned by standardizing capitalization and removing trailing spaces. Then a pivot table was built to determine the top ten neighborhoods with the most reviews. The property sizes were analyzed by creating a new column, `bedrooms_clean`, to address empty cells in the `bedrooms` column, substituting them with zeros. Another pivot table was created to identify the most popular property sizes for rentals and to recommend specific property sizes for the top ten neighborhoods.

In the final phase, occupancy rates were calculated using the calendar sheet. The `available` column was converted into a numeric `occupied` column, and a `day_of_week` column was added. A pivot table was used to calculate the average occupancy rate for each listing, and the average occupancy rates for each day of the week were visualized in a bar chart. For estimating annual revenue, representative properties were filtered, and average prices and occupancy rates were calculated. The annual revenue was estimated using the formula `365 days * Average Price * Occupancy Rate`, with assumptions documented.

[Google Sheets Document](https://docs.google.com/spreadsheets/d/1cRRvA61QYYqoujoY560u43axOa3YWbPGPuF_3Cx-57o/edit?gid=1564314379#gid=1564314379)



![Screenshot 2024-07-17 114949](https://github.com/user-attachments/assets/83d85780-a8c8-42c1-ad9f-bf58bd98a5d5)
