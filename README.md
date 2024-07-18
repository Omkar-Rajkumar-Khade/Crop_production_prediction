# Crop Production Prediction App

This app predicts the production of crops in Maharashtra, India, based on user inputs such as district, crop, crop year, season, and area. It uses a trained machine learning model to provide accurate predictions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Crop Production Prediction App aims to help farmers and agricultural planners in Maharashtra by providing predictions of crop production. By inputting specific details about the crop and the conditions, users can obtain an estimate of the expected production.

## Features
- Predicts crop production for various districts in Maharashtra.
- Takes into account the crop type, crop year, season, and area.
- User-friendly interface built with Streamlit.
- Utilizes machine learning models for accurate predictions.

## Installation
To run this app locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/crop-production-prediction-app.git
    cd crop-production-prediction-app
    ```

2. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the dataset:**
   Place the `Maharastra Crop Production final.csv` file in the `dataset` directory.

4. **Run the app:**
    ```bash
    streamlit run app.py
    ```

## Usage
1. Open the app in your browser. You should see a form with fields for district, crop, crop year, season, and area.
2. Fill in the values for the crop you want to predict.
3. Click the "Predict" button to see the predicted production.

## Model Training
The model used in this app is trained using a pipeline that includes preprocessing steps and either a `LinearRegression` or `RandomForestRegressor` model. 

Feel free to reach out if you have any questions or suggestions!
