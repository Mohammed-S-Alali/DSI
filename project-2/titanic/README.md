


![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 
**Titanic Project**
By: Rawan  MohammedEid , Mohammed Alali , Ibrahim Alzahrani
## Overview
The Project covers:
- Many Python programming concepts
- Programmatically interacting with files and directories
- visualizations
- EDA
- Machine Learning Models
- Prediction Scores.

## Problem Statement
So Kaggle recently hosted an open online competition where the competitors had to design a model based on given training data set which predicted the survival of passengers during the famous Titanic shipwreck. And we will attempt this problem using Machine Learning basic concepts of algorithms and data processing.

---

## Executive Summary
When There was some element of luck involved in surviving such as the cabin and gender and so on, it seems some groups of people were more likely to survive than others. And  by using five features we were able to predict the number of survived passengers.

Exploratory data analysis produces the findings:
<ol>
    <li>The mean of age in pclass 3 is the smallest among the pclasses by 25.14.</li>
    <li>The percentage of male death is more than %90.</li>
    <li>The Southampton embarkation port has the highest number of survived among the ports.</li>
</ol>

---

## Datasets

For this project, you'll have datasets:

- [Titanic](https://www.kaggle.com/c/titanic)

---

## Deliverables

This File will include:
- A Jupyter notebook that describes  data with visualizations & statistical analysis.
- A README markdown file the provides an introduction to and overview of the project.
- Datasets and Prediction file. 
- Screenshot of Kaggle compition score.

---

## Data Dictionary 
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**Pclass**|*int*|train/test|The passenger Class.| 
|**Age**|   *int*|train/test|The passenger Age.|
|**SibSp**| *int*|train/test| Number of sibling and spouses.|
|**Parch**|   *int*|train/test|of parents / children aboard.|
|**Fare**|   *float*|train/test| Passenger fare.|
|**Cabin**| *Object*|train/test|Cabin number.|
|**Sex**| *Object*|train/test|Gender of passenger.|
|**Embarked**|  *Object*|train/test|Port of Embarkation.|

---

## Conclusions
After applying  basic concepts of Machine Learning algorithms and data processing to predict the survival passengers,  We used 6 different ML models and the **Best** machine learning model among others that gave highest score on Kaggle competition was Gradiant Boosting Classifier with  **0.77033 of accuracy score** . The recommendations are the safety equipments should be around the ship and available, and the emergency plan is required for each ticket class.