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

<img width="763" alt="Screen Shot 2021-01-14 at 6 03 37 PM" src="https://user-images.githubusercontent.com/69806770/104659721-21ab7c80-5693-11eb-8afb-9fa24120acd9.png">

<img width="543" alt="Screen Shot 2021-01-14 at 6 03 53 PM" src="https://user-images.githubusercontent.com/69806770/104659744-3556e300-5693-11eb-8729-a49c45d1478c.png">

- Second Attempt: Increased the hidden layers to 5 layers with lower neurons at 10, 10, 8, 8 & 5 respectively and achieved a 73% accuracy rate as shown below:

<img width="755" alt="Screen Shot 2021-01-14 at 6 13 02 PM" src="https://user-images.githubusercontent.com/69806770/104660323-4e13c880-5694-11eb-8d91-47e8e905d7e0.png">

<img width="521" alt="Screen Shot 2021-01-14 at 6 13 22 PM" src="https://user-images.githubusercontent.com/69806770/104660339-5835c700-5694-11eb-9254-e985990112ea.png">

- Third Attempt: Kept both the hidden layers and neurons low at 2 hidden layers and 8 and 5 neurons respectively but changed the activation type and achieved a 72.5% accuracy rate as shown below:

<img width="778" alt="Screen Shot 2021-01-14 at 6 15 12 PM" src="https://user-images.githubusercontent.com/69806770/104660417-77ccef80-5694-11eb-9727-b071063e6f60.png">

<img width="517" alt="Screen Shot 2021-01-14 at 6 13 41 PM" src="https://user-images.githubusercontent.com/69806770/104660439-82878480-5694-11eb-8301-2aa1a9645e8f.png">

## Summary

The overall results are ok at 73% but not at the ideal target state of 75%. Since this is a large dataset I would recommend using the Random Forest classification model as this model is quicker to provide the same results so it allows for more attempts to get to the ideal target state of accuracy in a quicker time period.

