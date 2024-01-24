# deep-learning-challenge
Module 21 Challenge - Deep Learning

#The report should contain the following:

#Overview of the analysis: Explain the purpose of this analysis.

#Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

1. What variable(s) are the target(s) for your model?
  
  **Answer** The target is the Is_Successful column
2. What variable(s) are the features for your model?

  **Answer** Features list of this model are the following:
   name, application type affiliation classiification use_case 
   organization income special consideration status and ask 
   amount
3. What variable(s) should be removed from the input data because they are neither targets nor features?
  **Answer** EIN (Employee identification)

#Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

**Answer** For this model 3 hidden layers each with many neurons because the compute seems to increase the accuracy above 75%. This is expensive and costly. The first activation is relu and the other layers are sigmoid it might boost accuracy using these functions. Readjusting my data that names as a get dummies can factor in with better scores.


2. Were you able to achieve the target model performance?

**Answer** Yes
3. What steps did you take in your attempts to increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

**Answer** Required to convert the NAME into data points which has the biggest impact on improving efficiency but costly and it requires adding third layer using sigmoid activation function.

#Summary: Summarize the overall results of the deep learning model. 

**Answer** Overall the accuracy above 75% we are able to correctly classify each in the test 75% of the time.
And an applicant has a 80% chance of being successful if they follow this:

Name of applicants appears more than 5 times
type of applications following T3 T4 T5 T6 T7 T8 T10 T19
application of following classification ...


# Include a recommendation for how a different model could solve this classification problem, 
# and then explain your recommendation.

RandomForest model

