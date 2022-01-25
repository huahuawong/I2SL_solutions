## 1. For each of parts (a) through (d), indicate whether we would generally expect the performance of a flexible statistical learning method to be better or worse than an inflexible method. Justify your answer.

(a) The sample size n is extremely large, and the number of predictors p is small.
- Flexible method will fit the data closer and with the large sample size

(b) The number of predictors p is extremely large, and the number of observations n is small.
- A flexible method would overfit due to small number of observations

(c) The relationship between the predictors and response is highly non-linear.
- Flexible method will work better. The reverse case (highly linear) will work better with inflexible one (specifically linear regression)

(d) The variance of the error terms, i.e. σ2 = Var(), is extremely high.
- Worse. A flexible method would fit to the noise in the error terms and increase variance. This is considered overfitting


## 3. Refer to https://rpubs.com/ppaquay/65557

## 5. Flexible approaches are generally prefeered if there is non-linearity, it can reduce the bias. Large smaple size with small numm of predictors. However, it can overfit due to noise and it involves greater number of parameters
