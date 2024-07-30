# Step 4: Writing a Report on the Neural Network Model
## Alphabet Soup Charity Analysis Report

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

## **Q1 -** **Overview.** `Explain the purpose of this analysis.`

The nonprofit foundation Alphabet Soup wants a tool that can help it select the select the applicants for funding wth the best chance of success in their ventures. Using machine learning and neural networks, we use TensorFlow on the provided dataset to create a binary classifier that can predict whether applicants will be successful if they are funded by Alphabet Soup. This is clearly helpful on determining which applicants to fund or not.


## **Q2 - Results:** `Using bulleted lists and images to support your answers, address the following questions:`

### **Data Preprocessing**

`What variable(s) are the target(s) for your model?`

The target would be the 'y' variable, which is the "IS_SUCCESSFUL" column of the dataset.

`What variable(s) are the features for your model?`

The features are the 'X' variables, which is everything but the "IS_SUCCESSFUL" column: "APPLICATION_TYPE" , "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT"

`What variable(s) should be removed from the input data because they are neither targets nor features?`

"EIN & "NAME" were removed from the variables, since they are neither targets nor features. In other words, specifically in the context of the modeling we're trying to do, they're not needed. 

### **Compiling, Training, and Evaluating the Model**

`How many neurons, layers, and activation functions did you select for your neural network model, and why?`

I had 3 attempts at trying to get the best accuracy:

First try, I used 2 hidden layers & an outer layer. Layer 1 had 10 neurons and tanh activation, layer 2 had 20 neurons and sigmoid activations, and the outer layer had 1 unit, sigmoid activation & adam optimizers for complier.

The second try, I used 3 hidden layers & an outer layer. Layer 1 had 15 neurons and tanh activation, layer 2 had 25 neurons and sigmoid activations, layer 3 had 25 neurons and relu activations, and the outer layer had 1 unit, sigmoid activation, & adam optimizers for complier.

The third try, I used 3 hidden layers & an outer layer. Layer 1 had 30 neurons and tanh activation, layer 2 had 25 neurons and sigmoid activations, layer 3 had 20 neurons and sigmoid activations, and the outer layer had 1 unit, sigmoid acitvation, & adam optimizers for complier.

`Were you able to achieve the target model performance?`

The best accuracy I could achieve was 0.7286, or 72.9% accurate.

`What steps did you take in your attempts to increase model performance?`

textext

## **Q3 - Summary:** `Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.`

textext
