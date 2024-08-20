# Advance-spreadsheets-Manhattan-borough-AirBnB
## Task
Determine which type of properties of vacation rentals, located in the Manhattan boroughs of New York City, should be target for investment.
## Methodology
In the initial phase, the dataset from NYC Airbnb was thoroughly reviewed. Each sheet within the dataset, including the data dictionary, listings, and calendar, was examined to identify useful columns and potential data cleaning challenges. Tabs were created in the report for documenting data cleaning steps and version updates of the project file. The spreadsheet was organized by freezing rows and columns for easier scrolling, resizing columns, wrapping text, and adding filters. A copy of the raw data was made to maintain a reference, and listings irrelevant to vacation rentals, such as those with a minimum night requirement of more than seven days or no reviews in the past year, were filtered out and documented.

In the subsequent analysis phase, rental activity was estimated using the number of reviews in the last 12 months as a proxy for how often a property was rented. The neighborhood data was cleaned by standardizing capitalization and removing trailing spaces. Then a pivot table was built to determine the top ten neighborhoods with the most reviews. The property sizes were analyzed by creating a new column, `bedrooms_clean`, to address empty cells in the `bedrooms` column, substituting them with zeros. Another pivot table was created to identify the most popular property sizes for rentals and to recommend specific property sizes for the top ten neighborhoods.

In the final phase, occupancy rates were calculated using the calendar sheet. The `available` column was converted into a numeric `occupied` column, and a `day_of_week` column was added. A pivot table was used to calculate the average occupancy rate for each listing, and the average occupancy rates for each day of the week were visualized in a bar chart. For estimating annual revenue, representative properties were filtered, and average prices and occupancy rates were calculated. The annual revenue was estimated using the formula `365 days * Average Price * Occupancy Rate`, with assumptions documented.
## Recomendations
Vacation rentals in Lower East side neighborhood are the best for investment do to this neighborhood being the most popular in the Manhattan boroughs.
Property size 1 bedroom is the most popular for rental.
Vacation Rentals that fulfill criteria in Lower East Side have an average occupancy rate of %82.70, and an average price of $276.35 per night. That produce a estimated revenue of  $83 415.65


[Google Sheets Document](https://docs.google.com/spreadsheets/d/1cRRvA61QYYqoujoY560u43axOa3YWbPGPuF_3Cx-57o/edit?gid=1564314379#gid=1564314379)



