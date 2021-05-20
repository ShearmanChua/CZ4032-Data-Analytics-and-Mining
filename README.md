# CZ4032 Data Analytics and Mining

This repository contains the Python notebooks as well as the project report for the NTU CZ4032 Data Analytics and Mining Assignment.

##CZ4032 Data Analytics and Mining Team Project - Formula 1 Data Set

![Image of f1](https://github.com/ShearmanChua/CZ4032-Data-Analytics-and-Mining/blob/master/images/formula1.jpg)

Formula One (F1) is one of the most well-known international motorsports. An F1 season consists of a series of races, known as Grand Prix (GP), which take place worldwide on purpose-built circuits and public roads. The results of each race are evaluated using a points system to determine two annual World Championships: Driver Championship (DC) and Constructor Championship (CC). Every season, F1 teams, also known as Constructors, compete using cars with chassis built by themselves. Some examples are major car companies like Ferrari. Every Constructor in F1 must run two cars in every session in a GP weekend, and every Constructor may use up to four drivers in a season.

### Abstract

Formula One (F1) is a motorsport with an extensive global viewership. Multiple Constructors (teams) and their drivers compete annually for the Constructor’s Championship and the Driver’s Championship respectively. By winning the Constructor’s Championship, the Constructor will be allocated a larger budget to be used in the next season of F1. As such, Constructors should come up with a race strategy that would provide them the best advantage to win the championship.

Therefore, our project aims to make use of publicly available F1 data and perform real world Data Analytics and Mining tasks to help derive new insights that can help Constructors devise better race strategies. The project will utilize data from Formula 1 seasons from the year 1950 to 2017, available on Kaggle.

In the first part of the project, we will be studying various classification models for binary classification to predict if a Driver is able to be in a Point Winning Position (PWP) for a particular race. By predicting if a driver will be in PWP, we could determine the race pace and strategy the Constructor could execute for that race.
In the second part of the project, we will be utilizing a neural network to perform regression to predict what will be the fastest lap time for a particular race. This is to allow teams to try to hit that timing early on in the race and focus on getting into a PWP afterwards. An additional point is gained by achieving the fastest lap time in a race, which is an added advantage towards winning the championships.

In the third part of the project, we will be utilizing a neural network to perform regression to predict the final Driver’s Standing of a Driver-Constructor pair. After each season, Constructors could bid for their driver of choice. By predicting which driver performs better with the Constructor, Constructors could bid for that driver which could improve the chance of winning the championships.

In the fourth part of the project, we will be utilizing a neural network to perform a multiclass classification on which race classification a Driver will achieve for a particular race, the classes namely, Did Not Finish (DNF), podium, Point Winning Position and Finish. This classification model will serve to be an extension of the first part of the project to help improve race strategy for Constructors.

### EDA

![Image of EDA](https://github.com/ShearmanChua/CZ4032-Data-Analytics-and-Mining/blob/master/images/EDA.jpg)

### References

Kaggle Dataset 1: https://www.kaggle.com/cjgdev/formula-1-race-data-19502017

Kaggle Dataset 2: https://www.kaggle.com/coolcat/f1-binary-classification-of-race-finish-status/notebook?select=Pirelli_Tyre_Categories.csv

