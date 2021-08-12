# Weight Loss Visualization

*Note: This project was primarily made in spanish, so the information presented in written is this language. This readme's purpose is to roughly translate the information presented.*

Losing weight is one of the most talked topics on today's world. With obesity on the rise and many people not being able to afford to go to a nutritionist, a lot of us find weight loss frustrating and disencouraging.

The objective of this project was to provide a visualization of the nutritional data that we consume over a period of time of 4 months. By doing this we can hopefully help people be conscious of what we are eating and how it affects our journey into the body of our dreams.

## How it works

Our code attempts to predict our daily caloric intake based on the amount of carbohydrates, lipids and proteins we eat a day. Our nutritional data contains the amount of sodium we consume daily as well, but while developing our project we found out this value had little to no impact on predicting caloric intake.

To make our prediction we use linear regression. This works by feeding the model a series of N dimensional data points to create a trending line. We can test how accurate our prediction is by feeding it a sample of our data and comparing the calories predicted with the actual calories consumed.

## Results

Regrettably our model didn't work in the way we intended, and it did not predict our calorie intake with great accuracy. With some tests we can say that our loosely collected data was the main issue, and by testing our model with more closely supervised data we can expect better results. With the data provided we got an accuracy of 30% and a y intercept of 856 (This number represents the amount of calories we eat without eating proteins, lipids and carbohydrates).

## Graphs

The graphs presented at the bottom represents the amount of lipids, proteins and carbohydrates collected in our data. With this the line plotted represents the trending line our model is following to predict the amount of each data point each graph is presenting.


 