# E-Commerce-prediction
## Overview
This linear regression project predicts the yearly amount spent on an ecommerce marketplace by considering 4 factors:
  1. Average session length
  2. Time on App
  3. Time on Website
  4. Length of Membership

I trained the model on finding the weights of these parameters and implemented that model on some test data.
The real-values vs predictions graph is given with the residuals.

## Implementation
The e-commerce dataset is from kaggle. Consists of 500 entries corresponding to the 4 parameters mentioned above.
I plotted each of the parameters against the yearly amount spent in a jointplot graph and the data shows that length
of membership is in highest correlation with the yearly amount spent.

I split the dataset into a 7:3 ratio for training and testing. 
On testing, the model retrieved the weights for each parameter after which i plugged in the testing part of the dataset.
To test the accuracy of the predictions, i plot the values from dataset against the prediction, which is at the end.
The residuals are also given in a plot against the yearly amount spent, along with the probability distribution about the normal
of the distribution.
