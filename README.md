# Regression-Models

Regression is where models predict a number.

In machine learning, the goal of regression is to create a model that can predict a numeric, quantifiable value, such as a price, amount, size, or other scalar number.

Regression is a statistical technique of fundamental importance to science because of its ease of interpretation, robustness, and speed in calculation. Regression models provide an excellent foundation to understanding how more complex machine learning techniques work.

In real world situations, particularly when little data are available, regression models are very useful for making predictions. For example, if a company that rents bicycles wants to predict the expected number of rentals on a given day in the future, a regression model can predict this number. A model could be created using existing data such as the number of bicycles that were rented on days where the season, day of the week, and so on, were also recorded.

Regression works by establishing a relationship between variables in the data that represent characteristics—known as the features—of the thing being observed, and the variable we're trying to predict—known as the label. Recall our company that rents bicycles and wants to predict the expected number of rentals in a given day. In this case, features include things like the day of the week, month, and so on, while the label is the number of bicycle rentals.

To train the model, we start with a data sample containing the features, as well as known values for the label - so in this case we need historical data that includes dates, weather conditions, and the number of bicycle rentals.

We'll then split this data sample into two subsets:

A training dataset to which we'll apply an algorithm that determines a function encapsulating the relationship between the feature values and the known label values.
A validation or test dataset that we can use to evaluate the model by using it to generate predictions for the label and comparing them to the actual known label values.
The use of historic data with known label values to train a model makes regression an example of supervised machine learning.
### The given notebooks will help you to understand the regression.

For practice purpose you can download the libraries as needed in jupyter notebook.
