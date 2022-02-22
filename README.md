# deep_learning_challenge
 
Step 4: Write a Report on the Neural Network Model
The purpose of this analysis was to analyze the data from a charity, Alphabet Soup, and use an algorithm to predict whether or not applicants for funding would be successful.

Data Preprocessing:
What variable(s) are considered the target(s) for your model?
The ‘is_successful’ column and is represented by a 1 for a successful charity and a 0 for an unsuccessful charity.
What variable(s) are considered to be the features for your model?
The ‘Application_Type’ column as well as the ‘Classification’ column. These columns were significant because they had over 10 unique values
What variable(s) are neither targets nor features, and should be removed from the input data?
The ‘EIN’ and ‘NAME’ were dropped from the model, the rest of the columns were kept in.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Neural networks were applied for each model on three layers each. The number of features dictated the number of hidden nodes
Were you able to achieve the target model performance?
A three-layer model generated 5,981 parameters and 73% accuracy, lower than the requested 75%
What steps did you take to try and increase model performance?
The optimization added ‘NAME’ back into the dataset and the accuracy score was 79%, an increase of 6%
Multiple layers are useful for deep learning models, it increases accuracy for the machine in predicting and classifying information..


 

