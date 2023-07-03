# Poverty Analysis
The goal of this project was to predict whether the wealth in the area is greater or less than the mean wealth value.  The distribution is bimodal due to large disparities in wealth between urban and rural areas. Thus, the mean wealth differs depending on whether a satellite image is classified as urban or rural. 

The performance of the model for this project was based on two different scores.  The first score was on a random test set, in which predictions were made with data that was from the same countries that were in the training data.  This model had to predict either -1 for an area below the mean or a 1 for an area above the mean. The second score was on a test set with satellite images from countries that were not part of the training data.  The score 
