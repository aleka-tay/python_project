# Machine Learning Project Based on the Computer Game League of Legends

## Introduction
This machine learning model predicts champion selection by providing the following categories: 
- champLevel
- championId
- goldEarned
- goldSpent
- longestTimeSpentLiving
- individualPosition
- teamPosition
- kills
- deaths
- assists
- doubleKills
- largestKillingSpree
- largestMultiKill
- totalDamageDealtToChampions
- totalDamageDealt
- totalDamageTaken
- damageDealtToObjectives
- damageDealtToBuildings
- damageDealtToTurrets
- magicDamageDealt
- magicDamageDealtToChampions
- magicDamageTaken
- physicalDamageDealt
- physicalDamageDealtToChampions
- physicalDamageTaken
- trueDamageDealt
- trueDamageDealtToChampions
- trueDamageTaken
- inhibitorKills
- inhibitorTakedowns
- inhibitorsLost
- nexusTakedowns
- nexusLost
- turretKills
- turretTakedowns
- turretsLost
- AP

## Data Assembly
Before starting the project, I collected data from the RIOT API to create a dataset. I used PostgreSQL to help me quickly access the data I had collected.

## Exploratory Analysis
After the data was collected, I cleaned the dataset and performed an exploratory analysis. This work helped me collect features for my model.

## Feature Engineering
Feature engineering is a crucial part of building an ML model. It involves selecting, modifying, or creating new features from raw data to improve the performance of the model.

## Training
I trained my model using 70% of the data for training and 30% for testing, with a Random Forest algorithm.

## Conclusion
Overall, this project was a great challenge. It taught me a lot, from accessing an API and managing request limits to building a predictor with an ML model.
