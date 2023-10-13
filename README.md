## This READ.ME file goes along with the code section by section

### Import Packages
### Import DataSets - These datasets are from a Kaggle project about the Premier League. The datasets range from 2000 to 2020 football seasons. 
### Main Portion of the Project
### Function Creation - Here starts the section where I coded out helper functions to make the data sifting process easier. 

#### List of Features:
Variables with reasons for choosing them:
 - Number of Goals
Whoever scores the most in a season usually wins most of their matches (obviously)
- Number of Corners
Normally, corners are awarded to teams that frequent attacking the goal (having shots on the goal). Having alot of corners in a season produced more opportunities to score
- Number of Shots
Increased number of shots increases the amount of chances to score
- Number of Wins
I'm not explaining this
- Number of Away Wins
A team that has alot of success away tends to do better throughout the season, as playing at home is easier than on the road. With half of the matches being 'away' matches these wins are vital.
 - Number of Away Goals
Going along the same lines as Number of Away Wins, Away goals are also vital in having success across the season
 - Number of Losses
A team wants to limit this category
- Differential
 I chose to look at this statitistic because a high goal differential means your team was elite on both side of the ball, demonstrating true dominance
 - Number of Red Cards
A team would want to limit this because with a red card that means less men on the pitch for your squad
 - Number of Offsides
This statistic is tricky to interpret. On one side having alot of offsides lessens the control you have on the clock, and on the ball. However offsides means your team is attacking ALOT, which is what you want. 
Number of Home Losses
This statistic is simply not good. Losing at home means your club is doing something wrong (of just facing an elite club on the day)

### Data Preprocessing

### Functions to get the average of data across all available Seasons

### Total Average Dataset Compilation

### Data Scraper

### Data Exploration

### Model Prep and Creation

### Conclusion:
This logistic model can do a pretty good job predicting who can win the Prem based on the average of all the other seasons taken into account. As this is just the beta version we will revisit this project once my plate clears up a little bit. For now, Enjoy!


### To Be Continued...
