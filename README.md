# Weather-Prediction-System-Using-Flask-and-Decision-Tree-Classifier-


A simple web application built with Flask that predicts whether it will rain based on input weather conditions (temperature, humidity, and wind speed). This app uses a Decision Tree Classifier trained on a sample weather dataset to perform the prediction.

Features
Predict Rain: Users can input temperature, humidity, and wind speed to get a prediction on whether it will rain.
Machine Learning Model: A Decision Tree Classifier trained on a sample dataset to predict rain.
Flask Web Interface: User-friendly web interface built with Flask.

How It Works
The app uses a sample dataset containing weather data (temperature, humidity, wind speed, and rain status).
The data is used to train a Decision Tree model.
The trained model makes predictions based on user input from the web interface.

Project Structure
app.py: The main application file with routes and model logic.
templates/: Contains HTML templates for the web pages (index.html and result.html).
index.html: Form page for user input.
result.html: Displays the prediction result.

Getting Started
Prerequisites
Python 
Flask
scikit-learn
pandas
numpy
