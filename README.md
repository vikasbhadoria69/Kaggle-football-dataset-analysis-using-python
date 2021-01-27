# Data Analysis report on Kaggle football dataset
* Spot weaknesses and strengths in the teams/players in order to help them.
* Look at the performance of teams & players.
* Explore which kind of game piece the best team is using to win.
* Statistical Data Analysis on the kaggle football dataset.
* Detailed Analysis of Cards

## What is this project?
Football Dataset Analysis is a project to analyse and extract information from the [kaggle football dataset](https://www.kaggle.com/secareanualin/football-events/home).
I have mainly focused on Spanish La Liga in my analyses. Kindly see all the outputs of analysis in the pdf report above. 

## Tools and libraries used for development;
* **ditor: Jupyter Notebook**
* **Programming language: Python 3**
- **Libraries:** 
	1. numpy
	2. warning
	3. matplotlib
	4. pandas
	5. seaborn
	
## Dataset Description:
* Game_info.csv 
	* ID: game id
	* General: league, season, date and host country.
	* Teams: home and away teams.
	* Results: home and away goals.
	* Odds: odds on (home win, away win and draw)
* Events.csv:
	* ID: game id and event id.
	* Teams: playing team and opponent.
	* Player: players involved in the event, bodypart, assist method and
	* situation.
	* Shot: location (in the pitch), outcome, place, and is_goal or not.
	
## Detailed Analysis of Goals:

* Most offensive teams in La Liga

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Most_offensive_team_LaLiga.png)
	
* Most offensive Players in La Liga

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Most_offensive_players_in_laliga.png)
	
* The teams with best shooting accuracy in La Liga

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Teams_with_best_shooting_acc.png)
	
* Goals scored by teams in the first 15 minutes and the last 15 minutes

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Goals_scored_in_last15%26first15_minutes.png)
	
* Goal Situation & Shot Outcome: Barcelona vs Real Madrid

	- **Real Madrid**
	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Real_Madrid_goalsituation_shotOutcome.png)
	
	- **Barcelona**
	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Barca_goalsituation_shotOutcome.png)

* Team analysis for red cards in La Liga

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Red_card-laliga.png)
	
* Red card occurance v/s Time

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Red_card_occurance.png)
	
* When are goals most likely to be scored in La Liga

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/When_are_goals_most_likely_to_occur.png)
	
* Placement of penalties on the goal

	![alt text](https://github.com/vikasbhadoria69/Kaggle-football-dataset-analysis-using-python/blob/master/Images/Percentage%20of%20each%20placement%20of%20penalties.png)
	
## Codes
All the codes can be found in the two python notebooks uploaded above.
