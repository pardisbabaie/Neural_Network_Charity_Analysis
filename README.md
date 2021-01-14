# Neural_Network_Charity_Analysis
## Overview
The purpose of this project is to use machine learning and nerual networks to predict whether applicants will be successful if funded by Alphabet Soup.To do so we will use a dataset of 34,000 organizations that have been funded by Alphabet soup. 
## Data Preprocessing

What variable(s) are considered the target(s) for your model?
- The target variable is "IS_SUCCESSFUL"

What variable(s) are considered to be the features for your model?
- The variables considered to be the features for the model are: "APPLICATION TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", & "ASK_AMT"

What variable(s) are neither targets nor features, and should be removed from the input data?
- Identification columns including "EIN" & "NAME" are neither targets not features and should be removed from the input data
## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Based on what we did in the module and keeping the number of layers and neurons low to see what the performance would be, I used two hidden layers with 8 and 5 neurons repectively as shown below:

<img width="821" alt="Screen Shot 2021-01-14 at 5 58 30 PM" src="https://user-images.githubusercontent.com/69806770/104659403-8f0add80-5692-11eb-8ee1-bde2c61087b7.png">

Were you able to achieve the target model performance?
No, I was not able to meet the target model performance of 75% with the initial neural network model or with the 3 attempts to increase the model performance.

What steps did you take to try and increase model performance?
I made 3 attempts to increase model performance. The breakdown of each attempt is below:

- First Attempt: Kept the hidden layers low at 3 layers but increased the neurons significantly in each layer to 100, 50, and 50 respectively and achieved a 72% accuracy rate as shown below:

