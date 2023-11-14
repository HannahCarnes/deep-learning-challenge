#CODE LOCATED IN DEEP-LEARNING FILE IN "deep-learning-code"
# deep-learning-challenge
For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis was to use machine learning to predict the success of donations from various organizations.

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS were the variables.
IS SUCCESSFUL was the target.
What variable(s) are the features for your model?
AFFILIATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS
What variable(s) should be removed from the input data because they are neither targets nor features?
APPLICATION_TYPE, CLASSIFICATION
Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I used two layers, two activation functions, and 5 units.
Were you able to achieve the target model performance?
No.
What steps did you take in your attempts to increase model performance?
I attempted to produce a more accurate model by increasing the number of epochs.
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
In summary, the accuracy was about 72%. I believe more layers could have produced an increased accuracy.
