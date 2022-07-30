# Neural Network Charity Analysis

## Overview of the Analysis:
To implement a neural network and optimized neural network in order to develope a binary classifier to that is capable of predicitn whether applicants will be successful if funded by Alphabet Soup. 

## Analysis: 

### Data Preprocessing
    1) What variable(s) are considered the target(s) for your model?
      IS_SUCCESSFUL column
    2) What variable(s) are considered to be the features for your model?
      ASK_AMT, INCOME_AMT, CLASSIFICATION, APPLICATION_TYPE, USE_CASE, & ORGANIZATION
    3) What variable(s) are neither targets nor features, and should be removed from the input data?
      SPECIAL_CONSIDERATION, EIN, NAME, & STATUS
      
  Before Optimization: 
      
 ![image](https://github.com/cmmoreno9/Neural_Network_Charity_Analysis/blob/330e20a3096be9e16e4a5fad9891c48b36be0c9d/picture/Screen%20Shot%202022-07-30%20at%204.15.35%20PM.png)
 
 ![image](https://github.com/cmmoreno9/Neural_Network_Charity_Analysis/blob/330e20a3096be9e16e4a5fad9891c48b36be0c9d/picture/Screen%20Shot%202022-07-30%20at%204.13.38%20PM.png)
 
### Compiling, Training, and Evaluating the Model
    1) How many neurons, layers, and activation functions did you select for your neural network model, and why?
    Chose 80 neurons, with two hidden layers. The hope was the the increase of nuerons and hidden layers would result in better accuracy. The activation funtions chosen were relu and sigmoid. Used relu due to its celerity and simplicity. Sigmoid was also chosen as it exists between 0-1 and is common in predicitive models. 
    2) Were you able to achieve the target model performance?
    Unfortunaley, I was not able to get a higher accuracy. However, I was able to achieve a slighly lower loss of 69%. The model still needs to optimized to reach at least an accuracy of 75%, however, 95% accuracy is the goal. Maintaining a loss of .05 is also optimal
    3) What steps did you take to try and increase model performance?
      - dropped columns STATUS" & SPECIAL_CONSIDERATIONS in addition to EIN & NAME columns
      - Added a third hidden layer and changed my nuerons. 
      - changed output activation functions in my hidden layers to sigmoid and my output layer to relu to see any differences. 
      
  After Optimization: 
  
 ![image](https://github.com/cmmoreno9/Neural_Network_Charity_Analysis/blob/330e20a3096be9e16e4a5fad9891c48b36be0c9d/picture/Screen%20Shot%202022-07-30%20at%204.15.20%20PM.png)
 
 ![image](https://github.com/cmmoreno9/Neural_Network_Charity_Analysis/blob/330e20a3096be9e16e4a5fad9891c48b36be0c9d/picture/Screen%20Shot%202022-07-30%20at%204.15.05%20PM.png)
 
## Summary: 

Through the removal of additional features and utlizing diferent amounts of neurons and their functions, the loss of the optimized model was reduced by ~ 10%. However, the accuracy fell ~ 5%. This may be due to the extra features dropped and the additional third layer. 

In the future, a random forest model as it will alleviate the issues with overfitting the data. 
    
    
