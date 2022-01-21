# CPSC392_Final
## Problem Statement
The goal of this project is to answer three questions
1. Which variables have the strongest impact on a players value
2. What is the relationship between a players overall rating and value 
3. What is the probability of players that are left footed and above 6 feet being older than 27 compared to players that are right footed and shorter than 6 feet

## Motivation
The reason behind creating such an algorithm is to help soccer clubs and managers in a number of areas:
1. Helps scouts identify possible star players.
2. Supports financial planning.
3. Aids in finding new players for a teams roster.

## Data Source
The data used comes from [kaggle](https://www.kaggle.com/karangadiya/fifa19).

## Approach
The dataset included a lot of variables which were not related to some of my questions, because of this I cleaned the data in excel.

## Results
1. For the first question I used linear regression and dimensionality reduction and concluded that the variables the had the strongest impact on a player's value was the players overall rating. 
2. Using clustering algorthms such as DBSCAN, hierarchial, Gaussian Mixture Models, and K means I've concluded that there are two distinct groups for the relationship between overall rating and value. The first group represents the majority population of players and the second group is what we could consider star players.
3. Using propability statistics I found that 41% of left footed players taller than 6 feet are older than 27 and 46% of players that are right foot and shorter than 6 feet are older than 27. 

## Implementation
The models can be implemented for internal club analytics. All three of the models accurately aid a team in planning. 
