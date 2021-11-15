# Neural_Network_Charity_Analysis

## Overview of the analysis
The purpose of this analysis is to use a neural network to decide which companies should recieve loans from Alphabet Soup. This analysis uses python's TensorFlow library to create, train, and evaluate data gathered from previous loans.

## Results

### Data Preprocessing
* Variable that was considered as the target for the model: IS_SUCCESSFUL Column
* Variables that were considered features for the model: Every Column except for IS_SUCCESSFUL which is the target and the ones dropped
* Variable that were neither targets or features for the dataset: Columns dropped are EIN, NAME because they will have little to no impact om the outcome

## Compiling, Training, and Evaluating the Model

* This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".
![pic1](https://github.com/Klubbers0/Neural_Network_Charity_Analysis/blob/a289384d1575bd1f975729fb5859b1aa476f403c/image1.PNG)

**Was this model able to achieve the target model performance?**

* Although we the target for the model was to be 75% or above, I was not able to reach the target.


**What steps did you take to try and increase model performance?**

* Some of the steps I took to try and make the model more accurate were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.
![pic1](https://github.com/Klubbers0/Neural_Network_Charity_Analysis/blob/5de6987d9bbbe8fe4583053b9a915e576f21da1b/hidden%20layers.PNG)


## Summary
The model ended up with the accuracy score of 72% after optimization. The initial neural network had a accuracy score of 52%. This loss in accuracy can be explained from the fact that the model overfitted. Furthermore, we could further also optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. Also the random forest models have a faster performance than neural networks and could have avoided the data from being overfitted.


