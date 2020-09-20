# Coursera_Capstone
  This is the first notebook of Applied Data Science Capstone Course for Peer-graded Assignment: Capstone Project Notebook of Week 1

# Introduction/Business Problem 

  To reduce the frequency of car collisions at a location, current weather, road, and visibility conditions should be taken into account and an algorithm should be developed to estimate the material and spiritual seriousness of the accident. The main purpose of this study is to prevent accidents when conditions are bad, so this model helps protect drivers from the risks they will encounter. Another possible target audience for this study is as follows. Local police, health institutes, insurance companies, etc. They can use this model well and take action to know when they will be ready to receive bad news about a particular road. In many cases, carelessness while driving, using drugs and alcohol, or driving too fast are some of the main causes of accidents that can be prevented by applying stronger regulations. Besides the above reasons, weather, visibility, or road conditions are the main uncontrollable factors that can be avoided by revealing hidden patterns in the data and reporting a warning to the local government, police, and road drivers.

# Data Understanding

  The data was collected by the Seattle Police Department and Accident Traffic Records Department from 2004 to present. The data consists of 37 independent variables and 194,673 rows. The dependent variable, “SEVERITYCODE”, contains numbers that correspond to different levels of severity caused by an accident from 0 to 4.
Severity codes are as follows:

0: Little to no Probability (Clear Conditions)
1: Very Low Probability - Chance or Property Damage
2: Low Probability - Chance of Injury
3: Mild Probability - Chance of Serious Injury
4: High Probability - Chance of Fatality

  Furthermore, because of the existence of a huge unbalance in some attributes occurrences and the existence of null values in some records, the data needs to be preprocessed, cleaned and balanced before any further processing.

  How the data will be used to solve the problem:

  We have to select the most important features to weigh the severity of accidents in Seattle. Among all the features, the following features have the most influence in the accuracy of the predictions:
The ‘WEATHER’, ‘ROADCOND’ and ‘LIGHTCOND’ attributes.
