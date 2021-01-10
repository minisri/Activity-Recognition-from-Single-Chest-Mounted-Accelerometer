# Activity Recognition from Single Chest-Mounted Accelerometer
 I have used two approaches
 1- Using machine learning algorithms
 2- Using deep learing algorithms
 
 Approach 1- Here I have used multiclass classification algorithms like decision tree classifier and XGboost classifier. In data preprocessing each csv file is a user data. So I have added a column as user which has number 1-15 eg- csv1 user-1 . I have mapped the columns names and lables according to the readme file given. I have done Data visualisation to check the distribution of data. I have used decision tree classifier and XGB classifier which is giving us the accuracy about 75% . I have also calculated the precession and recall and the confusion matrix.
  
 Approch 2- As this data is a time series data I have used LSTM (Long Short term memory) approch. As LSTM uses the data which depends on the previous sequence it means next step was a function of a past observatioin. I have scaled the training  data using scaler and reduced the converted the shape of the data into 3Dim data and Testing data into categorical values using one hot encoding.Then used Bidirectional LSTM model with softmax activation function and loss function as categorical cross entropy to train the data and predict the results. This approach will give around 65% of accuracy.
