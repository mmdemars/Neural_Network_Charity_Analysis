# Neural_Network_Charity_Analysis
## Overview of the analysis: 
A dataset 34,000 past charity funds recipients is being explored to create a binary classifier to predict the success of future applicants. 

## Results:
### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  Targets for the dataset included  "STATUS", "ASK_AMT", "APPLICATION_TYPE", "INCOME_AMT", AND "SPECIAL_CONSIDERATIONS".
- What variable(s) are considered to be the features for your model?
  The features of the data set was the "IS_SUCCESSFUL" column of data.
- What variable(s) are neither targets nor features, and should be removed from the input data?
  "EIN", "NAME", and "USE_CASE" were removed from the dataset after being identified as noisey.
  
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  For the optimized neural network, I selected 2 hidden layers, with 80 and 50 neurons, after each run with incresed layers and neurons performed worse than the previous iteration. Up to 4 layers was tested with neuron numbers ranging from 120 to 20 - increasing the second layer to 50 seemed to yeild the least bad results. 
- Were you able to achieve the target model performance?
  I was not able to achieve the target performance. I was barely able to keep the model performace from failing spectacularly.
- What steps did you take to try and increase model performance? 
  Attempts to improve the model included (but were not limited to:
  - Removing and editing various variables to increase performance
  - Increasing the number of hidden layers (up to four)
  - Increasing the number of neurons in each layer (between 20 and 120)
  - Changing the activation model of different layers adn the output (all changes made the model worse)

## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
My unoptimized model performed at 69% accuracy, while the highest level of accuracy I was able to achieve with "optimization" was 63%. Most attempts ranged between 43 and 56% accuracy. More layers and neurons did not create a more accurate model. Changes in the features I was able to come up with had a negative impact on performace. Future models might try different targets for the model, or a more through job cleaning up particular aspects of the features.
