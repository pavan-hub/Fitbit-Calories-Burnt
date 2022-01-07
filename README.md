# Fitbit-Calories-Burnt
## Problem Statement
To build a regression model to predict the calories burnt based on the given indicators in the training data. 

## Data Description
This dataset predicts the calories burnt based on the different indicators as below:

1.	Id: The customer ID
2.	ActivityDate: The date for which the activity is getting tracked.
3.	TotalSteps:  Total Steps taken on that day.
4.	TotalDistance: Total distance covered.
5.	TrackerDistance: Distance as per the tracker
6.	LoggedActivitiesDistance: Logged 
7.	VeryActiveDistance: The distance for which the user was the most active. 
8.	ModeratelyActiveDistance: The distance for which the user was moderately active.
9.	LightActiveDistance: The distance for which the user was the least active.
10.	SedentaryActiveDistance: The distance for which the user was almost inactive.
11.	VeryActiveMinutes: The number of minutes for the most activity.
12.	FairlyActiveMinutes: The number of minutes for moderately activity.
13.	LightlyActiveMinutes: The number of minutes for the least activity
14.	SedentaryMinutes: The number of minutes for almost no activity
15.	Calories(Target): The calories burnt. 

Apart from training files, we also require a "schema" file from the client, which contains all the relevant information about the training files such as:
Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype.
