# Practicum_project_5
 My fifth project from Practicum course

What was used in the project: Python, Jupyter notebook. Libraries: pandas, numpy, scipy, matplotlib, seaborn.

Project Description

I work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. I need to identify patterns that determine whether a game succeeds or not. This will allow me to spot potential big winners and plan advertising campaigns.
The data going back to 2016. Let’s imagine that it’s December 2016 and I'm planning a campaign for 2017.
The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

# Steps
1) Data preprocessing.
   - Convert the data to the necessary types
   - Decide how to deal with missing values
   - Calculate the total sales (the sum of sales in all regions) for each game and put these values in a separate column
2) Analyze the data.
   - Look at how many games were released in different years
   - Look at how sales varied from platform to platform
   - Which platforms are leading in sales? Which ones are growing or shrinking?
   - Build a box plot for the global sales of all games, broken down by platform
   - Take a look at the general distribution of games by genre
3) Create a user profile for each region. For each region (NA, EU, JP), determine:
   - The top five platforms
   - The top five genres
   - Do ESRB ratings affect sales in individual regions?
4) Test the following hypotheses:
   - Average user ratings of the Xbox One and PC platforms are the same
   - Average user ratings for the Action and Sports genres are different
   - Do ESRB ratings affect sales in individual regions?
5) Overall conclusion.

# Description of the data
The data is stored in the file moved_games.csv

## Description of columns:
'Name'<br/>
'Platform'<br/>
'Year_of_Release'<br/>
'Genre'<br/>
'NA_sales' (North American sales in USD million)<br/>
'EU_sales' (sales in Europe in USD million)<br/>
'JP_sales' (sales in Japan in USD million)<br/>
'Other_sales' (sales in other countries in USD million)<br/>
'Critic_Score' (maximum of 100)<br/>
'User_Score' (maximum of 10)<br/>
'Rating' (ESRB)<br/>

Data for 2016 may be incomplete.
