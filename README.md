# Neural_Network_Charity_Analysis

## Overview

- Preprocessing Data for a Neural Network Model
- Compile, Train, and Evaluate the Model
- Optimize the Model

## Purpose
Using machine learning and neural networks features create binary classifier that is capable of predicting whether
applicants will be successfull if funded by Alphaber Soup.The initial file has 34,000 organizations and a number of 
columns that capture metadata about each organization that have received funding from Alphabet Soup.

## Results

#### Preprocessing Data for a Neural Network Model:

- Remove variables that are non beneficial for the the model and can be improve the model efficiency.


![image](https://user-images.githubusercontent.com/105381777/193980771-a570b5c6-cea1-4abf-a411-d7941c8fdacf.png)


- The varible donsidered to be the feature for the model is the "IS_SUCCESSFUL" column, split the processed data,
Scale the data.

![image](https://user-images.githubusercontent.com/105381777/193981466-333859e0-7c4c-4540-b213-eb921434c898.png)

#### Compile, Train, and Evaluate the Model

- There was an accruracy result of 72.35$ with a 57.60% of model loss using 3 layers of hidden notes fitting the model with in 5 epochs.

![image](https://user-images.githubusercontent.com/105381777/194194134-f34c9d84-b4fb-4d03-8d59-dffc24914cd0.png)

![image](https://user-images.githubusercontent.com/105381777/194194501-4b2f6fb8-e4b4-4e8e-8398-8ed9451b027f.png)

#### Optimize the Model

 - More non-Beneficial coulums were dropped, added more hidden nodes of layers ina  deep neral net, i was able increase my model
 but the not to the 75%. With the changes made, it was able to get an accrucy result of 72.86% with a model loss of 55.79%
 fitting the model with in 10 epochs.
 
 ![image](https://user-images.githubusercontent.com/105381777/194195326-140566cd-f12f-40ff-820e-5d3222bb6b92.png)
 
 ![image](https://user-images.githubusercontent.com/105381777/194195279-35753255-e823-4cc7-9704-782a9e02581e.png)
 
 ![image](https://user-images.githubusercontent.com/105381777/194195797-77b68226-133b-4827-9bc0-81106f9c8952.png)
 
 
 ## Summary
 
 The relu and sigmoid activations yielded a 72%, I beliave that there could be better rewults by using the random forest clasifier since this is 
 less influenced by the outliers.








