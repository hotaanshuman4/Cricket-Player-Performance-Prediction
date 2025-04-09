# Cricket-Player-Performance-Prediction
[CricketPrediction]()

## Introduction
A match prediction on a cricket game adds and creates interest for a fan watching a cricket match. Apart from having fun while watching a game, it helps people to come up with their Dream XI team. By keeping in mind the factors relating to the prediction the model predicts the performance of an individual player.

## Cricket player performance prediction
Cricket player performance prediction is a model which can predict the runs made by a batsman with certain number of balls faced and within a certain over. It consists of a dataset with of players with their past performance records. The model simply analyses the past performance of that certain player along with the other attributes and returns a predicted value.

In order to predict it requries certain input such as player name and the opposition team name, then it will ask for the number of balls that player might face within a span of certain over (i.e 50 or within).

This uses Multiple Regression Method (Supervised Learning) where the data is tested and train, later used for prediction. Unlike Unsupervised here data has a label and it is trained according to that. They are divided into dependent variables and independent variables , where dependent is basically the label that we are trying to predict and independ variables are the other features. We can use different regressors and choose the most accurate regression to predict the accurate output.

## Features
Data Preprocessing: Cleans column names and opposition team data for consistency.
Model: Utilizes a Decision Tree Regressor to predict runs based on player, opposition, balls faced, and overs.
Interactive Prediction: Users can input a player's name, opposition team, and match conditions to get a predicted runs output.
Dataset: Includes historical ODI match data for various players and teams.

## Requirements
To run this project, you'll need the following Python libraries:

numpy
pandas
seaborn
matplotlib
scikit-learn

## Future Improvements
Add more features (e.g., ground, innings, player batting position) to improve prediction accuracy.
Implement data visualization (e.g., using Seaborn/Matplotlib) to analyze player performance trends.
Handle missing data and outliers in the dataset.
Use advanced models like Random Forest or Gradient Boosting for better performance

## Contributing
Feel free to fork this repository, submit pull requests, or open issues for bugs and feature requests!
Happy coding and cricketing! 🏏(@hotaanshuman4@gmail.com)
