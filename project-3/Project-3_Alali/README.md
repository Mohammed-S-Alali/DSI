# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Sharing Dataset on Kaggle

### Problem Statment

<p style="text-align:justify"> News of MBS league has been more excited in the last years. Since the teams spent more than one billion riyals on contracts, deals and training camps. Also, the competition became more intense due to the small point difference between the top 4 teams. The rank of the league will be affected in the long term if the competition is ongoing like the premier league. The aim of a dataset to do sentiment analysis, prediction and clustering in order to know how the competition is described.</p>

---

### Executive Summary

<p style="text-align:justify">This project focuses on providing the dataset of news of MBS league to share it on Kaggle, which provides information about the news, title of news, and writer of news. Currently, the arabic news dataset has been increased in the last year on Kaggle. As a result, the arabic soccer news does not have an attention like arabic character recognition and arabic tweets. So, the objective of this project is to produce the saudi soccer news with including the main features. The project conducts on the data science process (Web-Scraping).</p>
Exploratory data analysis produces the findings:
<ol>
    <li>The 'الرياض' has the highest number of news by 849.</li>
    <li>The 24 January 2021 has the highest number of news by 68.</li>
    <li>The 'الأول', 'الفريق' and 'القدم' are the most common words in news.</li>
</ol>

---

### Data Dictionary

#### Saudi Soccer News dataset

|Feature|Type|Description|
|--|--|--|
|Writer|object|The person or organization who wrote the news.|
|Location|object|The location of news.|
|Date|DateTime|The date of news in format yyyy-mm-dd.|
|Time|DateTime|The time of news in format hh:mm.|
|News|object|The text of news.|
|Title|object|The title of news.|
|Class|Object|The type of news which are 0 for informative about teams, 1 is related to the match and 2 for the general news not specific on teams.|

<br>
