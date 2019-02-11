# Stay Vigilant,Stay Safe NYC
Our version of crime predictor and classifier to alert people of areas prone to crime.

## Why is our project Unique?
Our project is a system which predicts the number of crime reports which might occur in an area in future so that police department can be alerted beforehand. Also it classifies and determines which area of New York is more prone to what kind of crime targeted towards which gender/age/race

## Inspiration behind this project?
- According to the data report from New York Police Department,there are around 1800 criminal reports filed every 28 days
- Every part of New York confronts a different high in terms of various criminal activities.So area based analysis to identify risk factors in any particular area has become very important
- Often various crimes are targeted towards gender or race of individual,so to mitigate the effects of such type of injustice,we need to identify the areas and the target population ,to help take the right steps in the direction of Social betterment of the society as a whole
- A small model built with good accuracy,can serve as blueprint for various other cities which face similar problems

## What does our project do?
- Analyzes NYC’s historic complaint data.
- Makes use of ML algorithms to predict no. of crimes occurring in a district
- Predicts the offence type based on the feature of the observations
- Making use of BOSE API to give advice about crime situation with reliable degree of accuracy
- Spatial analysis to identify hot spots and cold spots of various criminal activities.

## How did we build it?
- Collected data from NYC Open data about historic Crime reports
- Cleaned and preprocessed data to fit it to Machine Learning Models
- Applied Deep Learning Model(LSTM) for time series prediction 
- Comparative analysis of ANN, Random Forest, Decision Tree, Voting classifier, Logistic regression, Multinomial Naive Bayes,Multi layer Perceptron(MLP) models applied for classification
- Wrote a script for text to speech conversion using Google text to speech API which takes the output text of the model and gives it as an input to BOSE API. 
- Wrote a script to convert the text input to audio output and play it on BOSE Speaker.

## Future Scope
- Automating location detection and then giving appropriate alerts 
- Automating the collection of data in a periodic manner 
- Looking for secondary datasets which might augment and increase the accuracy of our analysis
- Personal safety assistant or recommender
