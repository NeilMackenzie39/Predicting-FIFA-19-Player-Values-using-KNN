# Predicting-FIFA-19-Player-Values-using-KNN
Using KNN algorithm to predict value of players in FIFA 19 based on top 10 indicative attributes

## IMPORTANT
The identifiacation of the best attributes and the implementation of the KNN algorithm in this code was my first attempt. Both the identification and implemenation have been greatly improved in [this](https://github.com/NeilMackenzie39/Comparative-Study-of-KNN-vs-Linear-Regression) project on the comparison of KNN and Linear Regression using the same dataset.

## Getting Started
This repository contains a jupyter notebook of the code to execute this project as well as the data.csv file required to run the code

## Project Information
This is the first completely self-created machine learning project I completed. I obtained the majority of the knowledge required to complete this project from the Dataquest.io 'Data Scientist in Python' [course](https://www.dataquest.io/path/data-scientist/). The intention of this project is to practice the implementation of a KNN algorithm before developing another model that can be used at my current company to predict the price of stainless steel components based on their complexity.

In this project, players are categorized as either forwards, midfielders, defenders or goalkeepers. The 10 most successful attributes for predicting the value of players belonging to each category are then identified and a KNN model is developed that uses just the 10 best features to predict a player's value. The predicted value is then compared to the actual value in FIFA 19 to assess the accuracy of the model.
