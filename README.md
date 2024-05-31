# house-price-prediction-using-linear-regression

In this project, I have implemented multivariate linear regression (from scratch using NumPy as well as regularized linear regression techniques such as Lasso, Ridge, and Elastic Net using SciKit) to predict the median price of homes in a Boston suburb.

## About The Dataset 

Each record in the dataset describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. There are 404 examples in the train set and 102 examples in test set. Each example has 13 input variables (features) and one output variable (price in $10,000s). Below is the description of input variables:

- Per capita crime rate.
- The proportion of residential land zoned for lots over 25,000 square feet.
- The proportion of non-retail business acres per town.
- Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
- Nitric oxides concentration (parts per 10 million).
- The average number of rooms per dwelling.
- The proportion of owner-occupied units built before 1940.
- Weighted distances to five Boston employment centers.
- Index of accessibility to radial highways.
- Full-value property-tax rate per $10,000.
- Pupil-teacher ratio by town.
- 1000 * (Bk - 0.63) ** 2 where Bk is the proportion of Black people by town.
- Percentage lower status of the population.

Each one of these input features is stored using a different scale. Some features are represented by a proportion between 0 and 1, other features are ranges between 1 and 12, some are ranges between 0 and 100, and so on. 

Link to the dataset: https://www.kaggle.com/datasets/vikrishnan/boston-house-prices

For any queries, feel free to reach out to me at 25100325@lums.edu.pk
