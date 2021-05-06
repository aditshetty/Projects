**Logistic Regression**

In this project, I analyzed a dataset containing information on posts from a major social media platform. The goal was to better understand the factors influencing views via clicks on promoted posts. 
The analysis was done through multiple logistic regression models, as the target variable (**viewed**) was binary. 

**Primary Steps**

Data wrangling - Untidy data was inspected, missing values were dealt with through imputation or elimination. Variables were converted to appropriate data types to facilitate model building. 

Data visualization - I built charts to provide a high level understanding of important variables and their relationship with the target variable.

Model - I ran the logistic regression model (generalized linear model) and tuned it using the StepAIC method. Confusion matrices for each model helped me understand the frequency of false positives and false negatives which resulted in constructing a payoff matrix to find the minimum threshold at which I can cross validate my model. I compared the different models based on accuracy scores and the AIC value. 

**Takeaway**

My philosophy with this project was to understand what the workings of a log regression model in R. Building the confusion matrices and payoff matrix involved understanding the equations behind the real world cost of predicting a false positive and false negative. 
I also had the opportunity to cross validate the model which meant that I had to split the dataset into training and test sets. This helped me understand the importance of fitting a model and the risk of overfitting. 
 One of the key lessons learned through this project was applying context to this problem as opposed to looking at it through the lens of a clinical data problem. This helped me articulate the results of the model and crucially, helped me understand the payoff matrix.

