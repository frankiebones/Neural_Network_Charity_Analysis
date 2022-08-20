# Overview
Alphabet Soup has supplied data based on past applpications from organizations as well whether those applicants received funding or not.
We will utilize machine learning and neural networks to create a binary classifier for Alphabet Soup in order to help them predict whether future applicants will be successful.

# Results

- What variable(s) are considered the target(s) for your model? We want our model to predict whether future applicants are likely to be successful, therefore our target columns is <b>IS_SUCCESSFUL</b> <br>
- What variable(s) are considered to be the features for your model? The remaining columns, <b>APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, SPECIAL_CONSIDERATIONS</b> will be utilized by neural network to potentially identify unknown correlations.<br>
![target features](https://user-images.githubusercontent.com/15967377/185755238-408da010-d490-4e74-b20d-65d417ce7d13.PNG)
- What variable(s) are neither targets nor features, and should be removed from the input data? For our purposes we can elimiate both the <b>EIN</b> (Employer Identification Number) and the <b>NAME</b> of each applicant.<br>
- How many neurons, layers, and activation functions did you select for your neural network model, and why? For our original model we used <b>2</b> hidden layers with <b>80</b> and <b>30</b> neurons respectively. <br>
- Were you able to achieve the target model performance? We were unable to acheive the goal of <b>75%</b> accuracy with any of the models we tested.<br>
- What steps did you take to try and increase model performance? Additional layers were added, neurons per layer were adjusted and activation functions such as <b>tanh</b> and <b>sigmoid</b> were also tested.<br>

# Summary
After testing multiple models, the accuracy was raised from <b>72.3%</b> to <b>73.3%</b>. This was done by adding <b>6</b> layers, each with a varying quantity of neurons, though each layer utilized the same activation function of <b>relu</b>. While it was not tested, a Random Forest Classifier may be a good model to fit this data.
