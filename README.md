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
### Compiling, Training, and Evaluating the Model
    1) How many neurons, layers, and activation functions did you select for your neural network model, and why?
    Chose 80 neurons, with two hidden layers. The hope was the the increase of nuerons and hidden layers would result in better accuracy. The activation funtions chosen were relu and sigmoid. Used relu due to its celerity and simplicity. Sigmoid was also chosen as it exists between 0-1 and is common in predicitive models. 
    2) Were you able to achieve the target model performance?
    Unfortunaley, I was not able to get a lower loss. However, I was able to achieve a slighly higher accuracy of 58%. The model still needs to optimized to reach at least 75%, however, 95% accuracy is the goal. 
    3) What steps did you take to try and increase model performance?
      - dropped columns STATUS" & SPECIAL_CONSIDERATIONS in addition to EIN & NAME columns
      - Added a third hidden layer
      - changed output activation function to relu to see any differences 
 
## Summary: 

    
    
