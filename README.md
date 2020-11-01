# HW8

### 1. (Based on ROS 10.2) 
Here is the output from a fitted linear regression of y on pre-treatment predictor x, treatment indicator z and their interaction:

|   |  Median | MAD_SD  |
|---|---|---|
| (Intercept)   | 1.2  | 0.2  |
| x  | 1.6  | 0.4  |
| z  | 2.7  | 0.3  |
| x:z  | 0.7  | 0.5  |

Auxilarly parameters:

|   |  Median | MAD_SD  |
|---|---|---|
| sigma   | 0.5  | 0.0  |

#### a. (2 points)
Write the equation of the estimated regression lines of y on x for the treatment group and the control group.

#### b. (2 points)
Graph the two regression lines (assuming x is in the range of 0 to 10). Simulate data that is consistent with this model.

### 2. (Based on ROS 11.6) 

Suppose you have 100 data points that arose from the following model: y = 3 + 0.1 x1 + 0.5 x2 + error, with independent errors drawn from a t distribution with df =1 `rt(100, df = 1)`

#### a. (2 points)
Assume values of x1 are integers from 1 to 100 and x2 are random assigned to one or zero with probability .5. Simulate one instance of this model and create a scatterplot of the data.

#### b. (2 points)
Fit a regression model that assumes the error term is standard normal. Report your findings, do they match your expectations?

#### c. (2 points)
Carry out residual diagnostics for the model you have fit. Summarize you findings.

#### d. (2 points)
Construct a series of posterior predictive checks from the model fit, summarize your observations.

### 3. (Based on ROS 11.9 / 11.10)

Use LOO to compare different models fit the the candy dataset. You can select at least three models to compare, but ideally look for the best possible model.

#### a. (2 points)
Discuss the LOO results for the different models and what this implies for model choice.

#### b. (2 points)
Then use 5 - fold cross validation. Partition the dataset into 5 parts (using the sample function).

#### c. (2 points)
For each part, refit the model on the other four folds of data, and predict the 5th fold. Compute the mean squared error for each fold.

#### d. (2 points)
For each model, add up the sum of squared errors for the five folds of data and use this information to compare the models.

