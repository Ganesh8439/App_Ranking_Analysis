# App_Ranking_Analysis
# Summary
The dataset consists of the ranking of different apps with the app id, short description, long description, date, date of Last description change	and the keyword. We have to various factors that affect the app rankings.
# Methods
## Pre-processing
* The short description and long description are text that may contain many errors, hence we clean the texts using a user defined function **clean** which removes all the special characters, numbers, it converts the whole string into lowercase
* For the app id we just remove the special charaters
* The column country and language is same for all and hence removed
* The null values are also less and hence removed from the data
## Data analysis
* Using groupby we try to find any insights
* Group by date and rank, the same app has different rank for different keywords 
* Hence based on **keyword** the apps has variying rank
* After finding a factor based on the **placement of the keyword** in the short and long description, its clear that apps which have the keywords at the start have low ranks which was observed using scatter plot
* Taking data
