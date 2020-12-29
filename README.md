# Pandas (Case Assignment)
Generated a report that breaks down a fictional game's purchasing data into meaningful insights.

- Player Count
    - Total Number of Players
- Purchasing Analysis (Total)
    - Number of Unique Items
    - Average Purchase Price
    - Total Number of Purchases
    - Total Revenue
- Gender Demographics
    - Percentage and Count of Male Players
    - Percentage and Count of Female Players
    - Percentage and Count of Other / Non-Disclosed
- Purchasing Analysis (Gender)
    - The below each broken by gender
      - Purchase Count
      - Average Purchase Price
      - Total Purchase Value
      - Average Purchase Total per Person by Gender
- Age Demographics
    - The below each broken into bins of 4 years (i.e. <10, 10-14, 15-19, etc.)
      - Purchase Count
      - Average Purchase Price
      - Total Purchase Value
      - Average Purchase Total per Person by Age Group
- Top Spenders
    - Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
      - SN
      - Purchase Count
      - Average Purchase Price
      - Total Purchase Value
- Most Popular Items
    - Identify the 5 most popular items by purchase count, then list (in a table):
      - Item ID
      - Item Name
      - Purchase Count
      - Item Price
      - Total Purchase Value
- Most Profitable Items
    - Identify the 5 most profitable items by total purchase value, then list (in a table):
      - Item ID
      - Item Name
      - Purchase Count
      - Item Price
      - Total Purchase Value

# Pandas (Project)
Cleaning a data set containing over 15,000 records.

Part 1:
- Using Pandas, load the CSV provided in Resources
- Create a new table using the following columns: [0, 1, 2, 3, 4, 7, 8, 9, 10, 11, 29, 30, 32, 36, 37, 45, 48, 56, 110, 111]
- The data set currently uses 0.0 to represent "No" or "False", and "1.0" to represent "Yes" or "True"
- Calculated the total number of respondents in the subtable you built
- Created a table out of the rows corresponding only to people who did attend a bootcamp
- Calculated the number of people who attended a bootcamp
- Calculated the average age of bootcamp attendees
- Calculated the number of bootcamp attendees who self-identify as male; female; or neither
- Calculated the number of bootcamp attendees who hold college degrees
- Calculated the percentage of respondents who attended a bootcamp
- Calculated the percentage of people who attended a bootcamp and hold a college degree
- Calculated the average post-bootcamp salary
- Created a new, two-row table collecting the above data
- Finally, exported the final table into an Excel file

Part 2:
- The data set currently uses 0.0 to represent "No" or "False", and "1.0" to represent "Yes" or "True"
- Extracted rows corresponding only to respondents who attended a bootcamp
- Created a DataFrame with two columns: One with the bootcamp name, and one with the number of respondents who went to each bootcamp
- Created another DataFrame with two columns: One for the bootcamp name, and one for the number of respondents who recommend it
- Created a new DataFrame by merging the previous two DataFrames on the appropriate column
- In the new DataFrame, I created a new column containing the percentage of respondents for each bootcamp who would recommend that bootcamp
- Then, sorted the new DataFrame in descending order of the percentage of recommenders just calculated
- Used map and format to make the "% Recommended" column look more presentable
- Finally, exported the DataFrame to an Excel file
