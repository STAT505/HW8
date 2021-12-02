# HW8

### 1. (6 points)

```
candy <- read_csv("https://math.montana.edu/ahoegh/teaching/stat446/candy-data.csv")
```

We are going to compare different models fit the the candy dataset. Select at least three models to compare, but ideally look for the best possible model. Note large values of likelihoods or ELPD values are preferred and, similarly, lower values of AIC or LOOIC indicate better models. For reference, here is a nice article about predictive evaluation: [http://www.stat.columbia.edu/~gelman/research/published/waic_understand3.pdf](http://www.stat.columbia.edu/~gelman/research/published/waic_understand3.pdf)

Some of the function below will require using either `stan_glm()` or `lm`.

#### a. (2 points)
First use the `loo` function and ELPD. Discuss the results for the different models and what this implies for model choice. 

#### b. (2 points)
Then use the `kfold` function and ELPD. Discuss the results for the different models and what this implies for model choice. 

#### c. (2 points)
Finally use `AIC` function. Discuss the results for the different models and what this implies for model choice.


### 2. Optional

Use the candy dataset to:

a. Analyze the relationship between predictors in the dataset and whether the candy contains chocolate.

b. Fit several different versions of your model. Try including different predictors, interactions, and transformations of the predictors. Justify you selection of a model.

c. Based on the model you selected describe how each input affects Pr[chocolate = 1] and then use the model to make predictions for some test cases.
  
