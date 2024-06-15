# House-Price-Prediction
House price prediction in california using Random Forest Classifier

# Dataset
The data set that i used is available at "https://raw.githubusercontent.com/ageron/handson-ml2/master/". 

#Scatter Plot
The graph shows that there are certain neighbour hoods with a higher house price mostly located near the ocean. But furthur analysis showed that ocean proximity is not the strongest indicator of house price.

#Insights
Using correlation matrix and most important features of grid search , it was concluded that the biggest indicator of house price was the median house income of that neighbourhood coupled with latitude, longitude and population per household

#Model Selection
After playing around with linear regression model, decision trees and SVR, I settled with Random Forest as it provided the lowest error rate ~ $47000
