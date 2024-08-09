Flight Booking Price Prediction

Welcome to the Flight Booking Price Prediction project! This project uses machine learning to predict flight prices based on various features such as airline, class, and source city.

Project Overview

The goal of this project is to build a model that can accurately predict flight prices. This can be incredibly useful for individuals planning trips, travel agencies, or even airlines themselves. The model is trained on a dataset that includes features like airline, class, and source city.

Key Features

- Airline: The airline with which the ticket is booked.
- Class: The class of the ticket (Economy, Business, etc.).
- Source City: The city from which the flight departs.

Model

The model used in this project is a RandomForestRegressor. It was chosen for its ability to handle a large number of features and its effectiveness with regression tasks. The model was trained with 10 features, and it expects the same for making predictions.

Model Performance

The RandomForestRegressor model achieved an accuracy of 97% on the test set.

Implementation

The project is implemented in Python, with the use of libraries such as Streamlit for creating the web app, and Pickle for model serialization and deserialization. The model is loaded from a pickle file, which contains the trained RandomForestRegressor model along with LabelEncoders for the categorical features.

Usage

The web app provides an interface where users can select the airline, class, and source city. Upon clicking the "Predict Price" button, the app calls the prediction function of the trained model and displays the predicted price.

Future Work

While the current model provides reasonably accurate predictions, there's always room for improvement. Future work may include using more features for training the model, trying out different machine learning models, or tuning the hyperparameters of the current model for better performance.

Link: http://localhost:8501/
