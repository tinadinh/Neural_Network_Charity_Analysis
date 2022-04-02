# Neural_Network_Charity_Analysis
## Overview of the loan prediction risk analysis:
Alphabet Soup offers donations to charitable organizations and they want to ensure that their funds donated will be targeted towards a successful project. With the dataset, which contains over 34,000 organizations that have been funded by alphabet soup, a neural network model has been created to predict which future applicants might be successful in their project when funded by Alphabet Soup. The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations which will tell the customer whether or not the applicants will be successful using alphabet soup. 

This project is comprised of 3 steps: 
- Preprocessing the data for the neural network
- Compile, train and evaluate the model 
- Optimizing the model


## Results:
### Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The variable we are targeting in this module is the IS_SUCCESSFUL column.

What variable(s) are considered the feature(s) for your model?
- The features that we are using are every column except the ones that we will drop.

What variable(s) are neither targets nor features were removed?
- First features we drop are the 'EIN' & 'NAME' because we expect both features to have little to do with our outcome.

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".
<img width="1150" alt="1" src="https://user-images.githubusercontent.com/33900637/161364825-f27b182a-717b-4f2c-b1c8-2f669c914831.png">

Were you able to achieve the target model performance?
- Although we the target for the model was to be 75% or above, I was not able to reach the target.

What steps did you take to try and increase model performance?
- Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.
<img width="1118" alt="2" src="https://user-images.githubusercontent.com/33900637/161364845-55802189-b7c8-413f-bb6f-3a872422c67d.png">



## Summary:
The deep learning neural network model did not reach the target of 75% accuracy, this loss in accuracy can be explained from the fact that the model overfitted. We started with a data set and tried to predict whether or not the project would be successful on all of the features that we used after dropping two features that we figured to be irrelevant. Although I did not get to the accuracy of 75% that I wanted it is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. My recommendation is to increase the accuracy of the neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. It also has a faster performance than neural networks and could have avoided the data from being overfitted.
