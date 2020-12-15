# Neural Network Charity Analysis

## Analysis Overview
The purpose of this project is to use the knowledge of machine learning and neural networks to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Three main parts in the analysis:
- Data Processing
- Compiling, Training, and Evaluating the Model
- optimize the model.

## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
 The column `IS_SUCCESSFUL` is considered the target(s) for the model

- What variable(s) are considered to be the features for your model?
 `ASK_AMT, APPLYCATION_TYPE, AFFILIATION, ORGANIZATION, INCOME_AMT` are the features for our model.\

- What variable(s) are neither targets nor features, and should be removed from the input data?
The columns `EIN` and `NAME` are identification information and have been removed from the input data. In deliverable 3 I also removed `STATUS` 

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively.

- Were you able to achieve the target model performance?
The model accuracy keeps staying around 72% and didn't achienve the target model performance

- What steps did you take to try and increase model performance?
In order to increase the model performance the `STATUS`column was removed; also, the nodes was inresed and a third layer was used. the epochs was increased

## Summary
The deep learning neural network model did not reach the target of 75% accuracy. However the accuracy stays stable between optimizations around 72%.

 For a different model, we should see if we can get more unnacessary columns eliminated. We could also use Random Forest Classifier to evaluate its performance.