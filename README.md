# Car Price Predictor
This repository provides a foundational notebook designed to introduce students to machine learning using sklearn. The example focuses on a [regression](https://en.wikipedia.org/wiki/Regression_analysis) problem, utilizing the [car insurance dataset](https://www.openml.org/search?type=data&sort=runs&status=active&qualities.NumberOfClasses=lte_1&id=195) to predict the selling price of a car, which is a [continuous variable](https://en.wikipedia.org/wiki/Continuous_or_discrete_variable). The primary goal of this assignment is to familiarize students with regression modelling and evaluate model training outcomes by means of sklearn.

![house-price-predictor](https://raw.githubusercontent.com/bshtmichielsen/house_price_predictor/refs/heads/main/BANNER.jpg)
*Image by Stable Diffusion: a robot selling houses in Boston*

This notebook is intentionally designed as a foundational starting point and does not strictly adhere to established best practices as it is meant as a learning opportunity. This repo belongs to a five part course: <続く> Feel free to learn from the other parts too!

## 📚 Preparation
Please ensure that you are familiar with the following aspects in order to successfully work with this repo and notebook.
 - You know how to load data from and [work with ARFF files](https://www.geeksforgeeks.org/pandas/reading-an-arff-file-to-pandas-dataframe/)
 - You know the basic structure of a [linear regression](https://scikit-learn.org/stable/modules/linear_model.html) project
 - You understand the reasons for making [train, validate and test](https://en.wikipedia.org/wiki/Training%2C_validation%2C_and_test_data_sets) datasets
 - You understand the purpose and value of regression evaluation metrics [Coefficient of determination (R²)](https://en.wikipedia.org/wiki/Coefficient_of_determination) and [Root Mean Square Error](https://en.wikipedia.org/wiki/Root_mean_square_deviation)

## 🎯 Learning opportunities
The following aspects of machine learning are part of this example:
- Loading tabular data into a Tensor Dataset and making different loaders for different steps of the process
- Defining a simple neural network and training it using deep-learning with epochs
- Using a validation dataset to gauge the model's training gains
- Evaluating a regression model's performance using standardized evaluation metrics for regression problems.

## 🤔 Considerations for improvement
This notebook is an example on how to get started, it is open for improvements and enhancements. Feel free to clone my work and use it to study and learn. Things to consider if you want to improve this work:
- A visualization of the errors at the end would be interesting
- Calculating the R² and the RMSE of this model would help judging the model's performance. What do their values mean in relation to the case? 
- Regression models can be sensitive to the data being distributed normally. Is it in this project? If not, what can we do?

## ♻️ A different context
Make a copy or clone of this repo, and change the code that loads the ARFF file so that loads one of your own CSV files with completely different data in it. Preferably not about predicting the price of something. Make sure the target variable, that which needs to be predicted by the model, is in the last column of the CSV file, and is a continuous variable. Then, fix the notebook so that it works again. You do not need to make the model predict outcomes well (you can do that later if you want), just make the notebook run on your data first, so you can evaluate the outcomes.

## ⭐ Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!
> Konings, Hans H.M. (2025) "House Price Predictor" GitHub: <続く>
