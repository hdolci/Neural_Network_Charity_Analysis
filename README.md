## Overview

The purpose of this analysis is to learn Neural networks through the use TensorFlow within Python. Neural network is a form of Machine Learning modeled similar to a human brain that is capable of individual computations. In this specific module, we will deploy this type of machine learning on a provided data set of different charities to see who is likely to spend donation money wisely.


## Results

Our data set contained over 30,000 charities

Data Preprocessing
The following criteria was used during the data processing stage:

* APPLICATION_TYPE with unique values with less than 500 are listed as "Other"

* Name and EIN were removed because it was not relevant in the machine learning model

* IS_SUCCESSFUL was the focal point



Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

* We were unable to achieve our target of 75% accuracy. This was done over 3 optimizations and it was consistent: 

<img src="https://raw.githubusercontent.com/hdolci/Neural_Network_Charity_Analysis/main/Screenshots/Opt1.png" width="25%" height="25%">

<img src="https://raw.githubusercontent.com/hdolci/Neural_Network_Charity_Analysis/main/Screenshots/Opt2.png" width="25%" height="25%">

<img src="https://raw.githubusercontent.com/hdolci/Neural_Network_Charity_Analysis/main/Screenshots/Opt3.png" width="25%" height="25%">

What steps did you take to try and increase model performance?
* Added epoch, attempted to change number or neurons 






## Summary

In summary, our model and various optimizations did not help to achieve the desired result of greater than 75%. Even with adjustments (adding epochs, refining variables, changing neurons) it made little change.
