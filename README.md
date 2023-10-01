1  Project Description
You work for the online store "Streamlet," which sells computer games worldwide. Historical data on game sales, user and expert ratings, genres, and platforms (e.g., Xbox or PlayStation) are available from open sources. Your task is to identify the patterns that determine the success of a game. This will allow you to place a bet on a potentially popular product and plan advertising campaigns.

You have data up to 2016. Let's assume it's December 2016, and you're planning a campaign for 2017. You need to practice working with data, whether you're forecasting 2017 sales based on 2016 data or 2027 sales based on 2026 data.

The dataset includes the abbreviation ESRB (Entertainment Software Rating Board), an association that determines the age rating of computer games. ESRB evaluates game content and assigns an appropriate age category, such as "Mature," "Early Childhood," or "Teen."

1.1  Data Description
Name — game name
Platform — platform
Year_of_Release — year of release
Genre — game genre
NA_sales — sales in North America (in million dollars)
EU_sales — sales in Europe (in million dollars)
JP_sales — sales in Japan (in million dollars)
Other_sales — sales in other countries (in million dollars)
Critic_Score — critic score (maximum 100)
User_Score — user score (maximum 10)
Rating — rating from the ESRB (Entertainment Software Rating Board) organization, which assigns age categories to computer games.
1.2  Work Plan
Step 1: Open the data file and study the general information.

File path: /datasets/games.csv.
Step 2: Prepare the data.

Rename columns (convert to lowercase).
Convert data to the appropriate types. Describe which columns had data type changes and why.
Handle missing values if necessary.
Explain why missing values were filled in a certain way.
Describe the possible reasons for missing values.
Pay attention to the abbreviation 'tbd' in the user score column. Address this separately and describe how to handle it.
Calculate total sales in all regions and record them in a separate column.
Step 3: Conduct exploratory data analysis.

Examine the number of games released in different years. Are data for all periods important?
Examine how sales have changed by platform. Select platforms with the highest total sales and plot their distribution by year. What is the typical lifespan of platforms?
Choose data for the relevant current period. Determine this period based on the analysis of previous questions. The main factor is that this data will help make a forecast for 2017. Do not consider data from previous years in your work.
Identify leading platforms by sales, whether they are growing or declining. Select several potentially profitable platforms.
Create a box plot for global game sales by platform. Describe the results.
Examine how user and critic reviews affect sales within a popular platform. Create a scatter plot and calculate the correlation between reviews and sales. Formulate conclusions.
Compare the findings with game sales on other platforms.
Analyze the overall distribution of games by genre. What can be said about the most profitable genres? Are there genres with high and low sales?
Step 4: Create a user profile for each region.

Determine the most popular platforms (top 5) for each region and describe the differences in sales shares.
Identify the most popular genres (top 5) for each region and explain the differences.
Does the ESRB rating affect sales in a particular region?
Step 5: Test hypotheses.

Are the average user ratings for Xbox One and PC the same?
Are the average user ratings for Action and Sports genres different?
Set the alpha threshold yourself and explain:
How the null and alternative hypotheses are formulated.
Which criterion is used to test hypotheses and why.
Step 6: Write a general conclusion.

Formatting: Complete the task in a Jupyter Notebook. Fill in program code in code cells and explanations in markdown cells. Apply formatting and headings.
