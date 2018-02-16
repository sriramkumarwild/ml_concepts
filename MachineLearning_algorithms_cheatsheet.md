# Advantages an disadvantages of some ML algorithms

| Algorithm        | Advantages           | Disadvantages  |
| ------------- |-------------| -----|
| K-nearest neighbors | <ul><li>Simple and effective</li><li>No training involved</li><li>Good baseline</li></ul>      |    <ul><li>Computationally slow for large datasets</li><li>Sensitive to distance metric</li></ul>  |
| Linear Regression      | <ul><li>Fast</li><li>Easy to interpret model</li></ul> | <ul><li>Does not exploit non linear relationship in data</li></ul> |
| Decision trees     | <ul><li>Fast</li><li>item2</li></ul>      |   <ul><li>Complex to interpret for large datasets</li><li>item2</li></ul>  |
| Support Vector Machines | <ul><li>Ability to model complex relationships in data</li><li>Robust to outliers</li></ul>      |    <ul><li>Large memory required for big datasets</li><li>Performance depends on kernel functions and its hyperparameters</li></ul>  |
| Neural networks |<ul><li>Ability model complex patterns in data</li><li>No assumption about the data is made</li></ul>      |    <ul><li>Long training time</li><li>Long training time</li><li>Difficult to interpret the learnt model</li></ul>  |

# Induction biases of some ML algorithms

| Algorithm        | Induction bias  |
| ------------- |-------------|
| Linear Regression      | The relationship between input and output is linear.
| Decision Trees | Smaller decision trees have higher generalization accuracy than larger trees .
| Naive Bayes classifier | Assumes the features are independent of each other.
| cross-validation | Minimum cross-validation error: when trying to choose among hypotheses, select the hypothesis with the lowest cross-validation error. Although cross-validation may seem to be free of bias, the "no free lunch" theorems show that cross-validation must be biased.
| Support Vector Machines | Assumes that the classes can be linearly separated.
| Minimum description length | The best hypothesis is one that can best compress the given data.
| Feature selection | Assumes only some features are important than others.
| K-nearest neighbors | Assumes that an unknown samples is similar to a known sample in its neighbourhood.
