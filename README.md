# Neural_Network_Charity_Analysis
## Overview of the loan prediction risk analysis:
## The purpose of this analysis is well defined (4 pt)
Using my knowledge from machine learning and neural networks for this project I use the features in this dataset I create a binary classifier that will tell the customer whether or not the applicants will be successful using alphabet soup. The dataset contains over 34,000 organizations that have been funded by alphabet soup. There are a number of columns that capture the metadata of each organization such as organization type, the use of funding amongst others. This project is comprised of 3 steps: Preprocessing the data for the neural network, Compile,train and evaluate the model & finally optimizing the model.

Alphabet Soup offers donations to charitable organizations. They want to ensure that their funds donated will be targeted towards a successful project.
In order to select which applicants receive a donation, an analysis has been done using charity_data.csv, which consists of over 34,000 organizations that have been funded by Alphabet Soup in the past. With this data a neural network model has been created to predict which future applicants might be successful in their project when funded by Alphabet Soup.

## Results:
## There is a bulleted list that answers all six questions (15 pt)
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
## There is a summary of the results (2 pt)
## here is a recommendation on using a different model to solve the classification problem, and justification (3 pt)
