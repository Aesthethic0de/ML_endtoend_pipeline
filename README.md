# ML_endtoend_pipeline

# Wildfire Prediction Web App

A Flask web application for predicting the severity of wildfires based on environmental factors.

## Overview

This web application uses a Ridge Regressor model along with a Standard Scaler for preprocessing to predict the severity of wildfires. The model takes input for features like Temperature, Relative Humidity, Wind Speed, Rainfall, FFMC (Fine Fuel Moisture Code), DMC (Duff Moisture Code), ISI (Initial Spread Index), Fire Classes, and Geographic Region.

## Getting Started

### Prerequisites

Before running the application, make sure you have the necessary dependencies installed:

- Flask
- NumPy
- Pandas
- Scikit-learn

You can install these packages using the following command:

```bash
pip install Flask numpy pandas scikit-learn

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/wildfire-prediction-webapp.git
Place the Ridge Regressor model file (ridge.pkl) and the Standard Scaler file (scaler.pkl) in the models directory.

Running the Application
Navigate to the project directory:

bash
Copy code
cd wildfire-prediction-webapp
Run the Flask application:

bash
Copy code
python app.py
This will start the development server. You should see output indicating that the app is running, along with an address (e.g., http://127.0.0.1:5000/).

Visit the web app in your browser by going to the provided address.

Usage
Visit the web app in your browser.

Fill in the input fields with the environmental factors.

Click the "Predict" button to get the predicted severity of the wildfire.

Folder Structure
templates: Contains HTML templates for the web pages.
models: Contains pickle files for the Ridge Regressor model and Standard Scaler.
app.py: The main Flask application file.
README.md: Documentation for the repository.
Contributing
If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bug fix.

Make your changes and commit them with a descriptive message.

Push your changes to your fork.

Open a pull request to the main branch of this repository.

License
This project is licensed under the MIT License.
