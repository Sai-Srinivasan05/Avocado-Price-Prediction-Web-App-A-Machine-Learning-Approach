# Avocado Price Prediction Web App: A Machine Learning Approach

## Overview
This project is a web application for predicting avocado prices based on historical data. It uses machine learning, specifically a Random Forest Regressor, to predict the average price of avocados based on inputs like date, region, and avocado packaging details. The application is built with Flask and utilizes the pre-trained model to make predictions.

## Features
- **User Input**: Users can input the date, region, and avocado packaging details (total volume, small bags, large bags, and extra-large bags).
- **Machine Learning Model**: A Random Forest Regressor model is trained using historical avocado price data.
- **Prediction Output**: The app predicts the average price of avocados based on the input data.
- **Error Handling**: Displays appropriate error messages if input data is invalid.

## Technologies Used
- **Python**: Programming language used for data processing and model training.
- **Flask**: Web framework for building the web application.
- **Random Forest Regressor**: Machine learning model for price prediction.
- **Joblib**: Used to save and load the trained machine learning model.
- **Pandas & Numpy**: Data manipulation and numerical operations.
- **Bootstrap**: For responsive web design.

## Data

The dataset used for training the machine learning model is **avocado.csv**. This file contains historical data on avocado prices and associated features, including:
- Date
- Region
- Total volume
- Packaging details (small, large, extra-large bags)
- Average price

## Model Training

1. To train the model, run the following script:
   ```bash
   python model.py
   ```

2. This script processes the data, tunes the Random Forest Regressor model, and saves the trained model and encoder as `random_forest_model.pkl` and `region_encoder.pkl`.

## Usage

1. Open the web application in your browser.
2. Select the date, region, and avocado packaging details from the form.
3. Click "Predict Price" to get the predicted average price for that date and region.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Co-Authors

- **Thrisheiyan U K** - [@Thrisheiyan U K](https://github.com/ThrisheiyanUK)
