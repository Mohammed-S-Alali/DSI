# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 4: Applying Unsupervised Learning Algorithms

## Project 4: Applying Unsupervised Learning Algorithms
_Team Members: Mohammad Al Ali - Noha Zaman - Mariah Alshiekh_


### Problem Statment

<p style="text-align:justify">In recent times, interest in video games has been increased. A video game is an electronic game that involves interaction with a user interface or input device – for example a joystick, controller, keyboard, or motion sensing device – to generate visual feedback for a player. The most famous device of video games is PlayStation 4 . More than one million players are active on PlayStation 4. Players of PlayStation 4 games are of different ages, different cultures and interests as well as developers from different countries. Therefore, suggesting a specific game to any player is very hard. Thus, our main aim in this project is to create a recommendation system that provides each player on PlayStation Network a suitable game based on the features of games.</p>

---

### Executive Summary

This project focuses on building recommender model on video games of PlayStation 4. The recommendation depends on Content Based method with different algorithms:
<ol>
<li> Nearst neighbors algorithm : select the nearst game that contain similar features to user selection.</li>
<li> Random forest algorithm : calculate the recommend score based on features importance to rate.</li>
</ol>
Currently, the development video games accelerate sharply. As a result, the number of players have been increased.
Therefore, it became more difficult to suggest games to a specific player. The objective of our project is solving this issue by using machine learning algorithems.
The project conducts on the data science process (`Recommender system`).
<br>
<br>
Exploratory data analysis produces the findings:

- The quarter of games required one hour for completion the game.
- The Drowning (HK/TW) game is the highest rated games.
- The DRIVECLUB game has the highest score.
- The players prefer to games that have high challenge.

Based on findings, our recommender system focused on these features (`rate` , `score` , `comp_perc` ,`gamers`).
These features make recommender system more reliable.

---

### Dataset

For this project, you'll have datasets:

- [PS4 Games](https://www.kaggle.com/ww1234/ps4-games)

---

### Data Dictionary

#### PS4 Games dataset

|Feature|Type|Description|
|--|--|--|
|game|object|Contains the games name|
|score|int64|Contains maximum TrueTraphy score|
|leaderbord|float64|Contains Game Leaderboard ratio|
|gamers|int64|Contains the number of gamers plying this game in truetrophies website|
|comp_perc|float64|Contains percentage of how many gamer complete this game|
|rating|float64|Contains a rating from people who play this game by out of 5|
|url|object|Contains URL that have more information about each game|
|min_comp_time|int64|Contains minimnum estimated time per hour to unlock all trophies|
|max_comp_time|int64|Contains maximum estimated time per hour to unlock all trophies|

<br>

---

### Deliverables

This File will include:
- A Jupyter notebook that describes data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of the project.
- Dataset.

---

### Conclusions and Recommendations
<p style="text-align:justify">In the video games, there are many factors contribute in recommendation like rating and number of gamers. The diversity of gamers appear in video games such as minimum time for completion. The DRIVECLUB has the highest score among video games. So, the recommender system will consider those factors to produce a reliable result. The recommendations are building the recommender system based on the content of games by Nearest Neighbors for a similar game and Feature Importances for the best game. Also, we should consider the impact of each factor and know the behavior of gamers is important while building a recommendation system.</p>
