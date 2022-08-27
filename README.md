# Module_13_Challenge_DeepLearning_NeuralNetworks

This Project is to create a model that predicts whether applicants will be successful if they are funded by Alphabet Soup, a venture capital firm.

The assignment is broken into the following sections:


1. Prepare the data for use on a neural network model.


2. Compile and evaluate a binary classification model using a neural network.


3. Optimise the neural network model.


# Prepare the data for use on a neural network

The data was encoded for the categorical variable and then divided into testing and training data. 


# Compile and evaluate a binary classification model using a neural network

The first model was a two-layer deep neural network model that uses the relu activation function for both layers.

The model was compiled and fit  using the binary_crossentropy loss function, the adam optimiser, and the accuracy evaluation metric.

Finally using the test data the model's loss and accuracy was determined.


# Optimise the neural network model

TensorFlow and Keras were used to optimise the model to improve the model's accuracy.


There were three different alternatives applied to improve the model:

Alternative Model 1 : Adding another layer to the existing model

Alternative Model 2 : Using less nodes for hidden layer, linear activation for output layer and decreasing the no. of epochs to 20

Alternative Model 3 : Using more nodes for hidden layer and increasing the no. of epochs to 100


# Results:

All the alternative models had more or less same accuracy but the linear activation model showed more loss compared to the other two models.

This indicates that there was a non-linear realtionship between the dataset. It also signifies the dataset was complex and hence sigmoid activation function was a better choice.



Below are the final results using the original and 3 alternatives:



Original Model Results
268/268 - 0s - loss: 0.5556 - accuracy: 0.7310 - 333ms/epoch - 1ms/step
Loss: 0.5555784702301025, Accuracy: 0.7309620976448059

Alternative Model 1 Results
268/268 - 0s - loss: 0.5580 - accuracy: 0.7319 - 339ms/epoch - 1ms/step
Loss: 0.5579661130905151, Accuracy: 0.7318950295448303

Alternative Model 2 Results
268/268 - 0s - loss: 0.8650 - accuracy: 0.7224 - 458ms/epoch - 2ms/step
Loss: 0.8650399446487427, Accuracy: 0.722449004650116

Alternative Model 3 Results
268/268 - 0s - loss: 0.5750 - accuracy: 0.7327 - 454ms/epoch - 2ms/step
Loss: 0.5750026702880859, Accuracy: 0.7327113747596741

