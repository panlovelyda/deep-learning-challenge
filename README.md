# deep-learning-challenge
# Over View of the Analysis:
# Using Machine Learning and Neural Networks as tools, to help to select appliants and predict whether applicants will be successful to be funded by Alphabet Soup
# Results:
# Data Preprocessing
# What variable(s) are the target(s) for your model?
# Target variable should be IS_SUCCESSFUL and has value of 1 for Yes and 0 for No
# What variable(s) are the features for your model?
# After dropping EIN and NAME, all remaining columns could be considered as features for the model
# What variable(s) should be removed from the input data because they are neither targets nor features?
# EIN and NAME
# Compiling, Training, and Evaluating the Model
# How many neurons, layers, and activation functions did you select for your neural network model, and why?
# 3 layers, 5,981 Nparameters were created by the tranning model.
# Were you able to achieve the target model performance?
# 268/268 - 0s - loss: 0.5676 - accuracy: 0.7248 - 151ms/epoch - 564us/step Loss: 0.5675714015960693, Accuracy: 0.724781334400177
# What steps did you take in your attempts to increase model performance?
# Attempt to keep NAME column in the optimization file to improve the accuracy