# Movie Rating Prediction using Linear Regression
# Overview
In this project, I developed a machine learning model to predict the ratings of Indian movies based on various attributes such as genre, director, and lead actors. The dataset used in this project is the IMDb Movies in India dataset from Kaggle.

# Project Objectives
The main objectives of this project were:

Load and preprocess the IMDb Movies in India dataset, handling missing values and encoding categorical features.
Split the dataset into training and testing sets.
Train a Linear Regression model on the training data.
Evaluate the model's performance using the mean squared error (MSE) metric.
Visualize the relationship between the actual and predicted movie ratings.

# Implementation
The project is implemented in Python using the following libraries:

* `pandas`: for data manipulation and analysis
* `sklearn`: for machine learning algorithms, evaluation metrics, and preprocessing
* `matplotlib` and `seaborn`: for data visualization
The code is organized in a Jupyter Notebook and can be found in the Movie_Rating_Prediction.ipynb file.

# Results
After loading and preprocessing the IMDb Movies in India dataset, I split it into training and testing sets. I then trained a Linear Regression model on the training data and evaluated its performance on the test set.

The model achieved an MSE of 0.44 on the test set, which indicates a reasonably good fit to the data. The low MSE suggests that the model can accurately predict movie ratings based on the given attributes.

To visualize the relationship between the actual and predicted movie ratings, I created a scatter plot. The plot shows a strong correlation between the actual and predicted ratings, further confirming the model's effectiveness.

# Conclusion
This project demonstrates the use of Linear Regression, a fundamental machine learning algorithm, to predict movie ratings based on various attributes. The low MSE achieved by the model suggests that it can be a useful tool for movie producers, distributors, and fans to estimate the potential success of a movie.

The code and detailed explanations are available in the Jupyter Notebook. Feel free to explore the project and provide feedback or suggestions for improvement.