# Uber-Rides-Predictor
Machine learning-based web application that predicts weekly Uber ride demand using socio-economic and pricing factors. Built with Flask and Scikit-learn, it provides real-time predictions through an interactive user interface.

🚖 Uber Rides Prediction using Machine Learning
📌 Overview
This project is a Machine Learning-based web application that predicts the number of weekly Uber rides based on various socio-economic and pricing factors. It demonstrates an end-to-end workflow, including data processing, model building, and deployment using a web interface.

The application is built using Flask and integrates a trained machine learning model to provide real-time predictions based on user inputs.

🎯 Objective
The main goal of this project is to analyze how factors such as pricing, population, and income influence ride demand and to build a predictive model that can estimate weekly ride counts accurately.

⚙️ Features
- Interactive web interface for user input
- Real-time prediction of weekly Uber rides
- Integration of machine learning model with Flask backend
- Simple and user-friendly UI
- End-to-end ML pipeline demonstration

🧠 Technologies Used
Python – Core programming language
NumPy & Pandas – Data processing and manipulation
Scikit-learn – Machine learning model development
Flask – Web framework for deployment
HTML/CSS – Frontend design
📊 Input Features

The model takes the following inputs from the user:
Price per Week – Cost of the service
Population – Number of people in the area
Monthly Income – Average income of users
Average Parking per Month – Parking cost

🔍 How It Works
- The user enters input values through the web interface.
- The Flask backend collects the input data from the form.
- Input data is converted into a numerical format using NumPy.
- A pre-trained machine learning model (model.pkl) processes the input.
- The model predicts the number of weekly rides.
- The result is displayed dynamically on the web page.

📦 Project Structure

app.py              # Flask application

model.pkl          # Trained machine learning model

requirements.txt   # Dependencies

templates/
   - index.html     # Frontend UI

static/
   - style.css      # Styling
     
notebook.ipynb     # Model training & analysis (optional)

dataset.csv        # Dataset used for training

📌 Conclusion
This project demonstrates how machine learning models can be deployed as a web application to solve real-world prediction problems. It highlights the integration of data science and web development to build practical, user-interactive solutions.
