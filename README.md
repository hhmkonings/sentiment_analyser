# Sentiment Analyser
This repository provides a foundational notebook designed to introduce students to categorise messages by means of TF-IDF. The example focuses on a [regression](https://en.wikipedia.org/wiki/Regression_analysis) problem, using [labelled Twitter messages](https://www.kaggle.com/datasets/tariqsays/sentiment-dataset-with-1-million-tweets). The primary goal of this assignment is to recognise whether a message's intent is considered positive, neutral or negative.

![sentiment-analyser](https://github.com/Fontys/sentiment_analyser/blob/main/BANNER.jpeg)
*Image by Stable Diffusion: a robot analysing social media messages*

This notebook is intentionally designed as a foundational starting point and does not strictly adhere to established best practices as it is meant as a learning opportunity. This repo belongs to a five part course: 🚗 [Car price predictor](https://github.com/Fontys/car_price_predictor/)   🛳️ [Titanic Survival Rater](https://github.com/Fontys/titanic_survival_rater/)   📧 [Sentiment Analyser](https://github.com/Fontys/sentiment_analyser/)   🚲 [Bike Rental Forecaster](https://github.com/Fontys/bike_rental_forecaster/) 

Feel free to learn from the other parts too!

## 📚 Preparation
Please ensure that you are familiar with the following aspects in order to successfully work with this repo and notebook.
 - You know the basics of [scikit-learn](https://scikit-learn.org/stable/getting_started.html)
 - You understand the concept of [TF-IDF](https://www.geeksforgeeks.org/machine-learning/understanding-tf-idf-term-frequency-inverse-document-frequency/)
 - You understand  [Support Vector Classification (SVC)](https://www.geeksforgeeks.org/machine-learning/support-vector-machine-algorithm/) and their [kernel functions](https://www.geeksforgeeks.org/machine-learning/major-kernel-functions-in-support-vector-machine-svm/)
 - You understand the purpose and value of regression evaluation metrics [Coefficient of determination (R²)](https://en.wikipedia.org/wiki/Coefficient_of_determination) and [Root Mean Square Error](https://en.wikipedia.org/wiki/Root_mean_square_deviation)

## 🎯 Learning opportunities
The following aspects of machine learning are part of this example:
- Encode texts to characters
- Select a number of words for the modelling phase
- Using a validation dataset to gauge the model's training gains
- Adding inference cases to test the model .

## 🤔 Considerations for improvement
This notebook is an example on how to get started, it is open for improvements and enhancements. Feel free to clone my work and use it to study and learn. Things to consider if you want to improve this work:
- The texts can be cleaned in several ways for possible improvement of the data. Investigate packages like [NLTK](https://www.nltk.org/) and [Spacy](https://spacy.io/) and apply cleaning methods.
- The constructor of the SVM has an optional hyperparameter named C, which by default is 1.0. Try providing a value of 0.5 or 2.0 for this parameter and see if this makes any difference. Which of those values would you say gives the best results and why?
- The constructor of the SVM has an optional hyperparameter named kernel, which by default is rbf. In this case the chosen value is sigmoid. Look up in the sklearn documentation which other values this hyperparameter accepts, and compare the results from the different kernels. 

## ⭐ Citation & Star
If you use my work please cite and star ⭐ this repo. Thanks!
> Konings, Hans H.H.M. (2026) "Sentiment Analyser" GitHub: https://github.com/Fontys/sentiment-analyser/
