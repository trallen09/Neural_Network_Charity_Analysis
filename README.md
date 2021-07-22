# Neural_Network_Charity_Analysis

# Overview 

The overview consists of using the features in the charity dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Results

## Data Preprocessing

  1 What variable(s) are considered the target(s) for your model?
  - The Y is the column IS_SUCCESSFUL
  
  2 What variable(s) are considered to be the features for your model? 
  - The X is all other columns not IS_SUCCESSFUL
  
  3 What variable(s) are neither targets nor features, and should be removed from the input data? 
  - We dropped the EIN and NAME column

## Compiling, Training, and Evaluating the Model

  4 How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - I ended up trying up to 6 hidden layers, with between 30 and 80 neurons and combination of relu and sigmoid.
  5 Were you able to achieve the target model performance?
  - only 74
  6 What steps did you take to try and increase model performance?
  - I played with adjusting more layers and different activiation functions with no real change.


# Summary
I'm having a hard time really understanding what is actually happening behind the scenes as I add more neurons or layers. The activiation functions seem to be very unique as well. We could try more epochs as well as other activiation functions that better suite this type of model. We can also narrow down the data to get better results. I think I would narrow the data down to see if that made a big impact.  
