# Deep-Learning-for-Customer-Churn-Prediction

""""""""""""""""""""""""DESCRIPTION""""""""""""""""""""""""

Let a bank wants to find out that which of its customers may move out of the bank in the future.
To analyze this, the bank prepares with the customers dataset which include the follwing attributes:-
  Credict Score
  Location
  Gender
  Age
  Time with bank
  Balance in the account
  Number of Products availed
  Credit Card(Yes/No)
  Active(Yes/No)
  Income
  
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""

To predict the future exit of the customer based on the above attributes, lets build a machine(Deep) Learning model.
In this project, we have used dataset of 10,000 customers.


""""""""""""""""""""""""""""""""""""""""HOW TO PREPARE THE DATA"""""""""""""

Follow the below steps:-
  Import the dataset.
  Segregate the input(matrix of features) and output features (a list).
  Process the categorical variables:- Location, Gender using LabelEncoder
  Split the dataset into the training set and test set
  Scale the input and output features
  -> Now the data set is ready.
  
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""


""""""""""""""""""""""""""""""""""""""""HOW TO Prepare and Fit the Deep Learning Model"""""""""""""

Note: Tensorflow must be installed
Follow the below steps
  Import keras library
  from keras.models import Sequential
  from keras.layers import Dense
  Initialize the Artificial Neural Network
  Add the input layer and the first hidden layer
  Add the second hidden layer
  Add the output layer
  Compile the ANN
  Fit the ANN to the Training set
  
  """""""""""""""""""""""""""""""""""""""""""""""""""""""""""
  
Now the model is fitted and make prediction on the test data.
Evaluate the accuaracy of prediction using the confusion matrix.
