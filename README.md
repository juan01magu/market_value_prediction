# AI-Powered Football Players Market Evaluation Tool

## Description

This project uses machine learning to predict soccer players' market value. It employs both regression and classification models, with Polynomial Regression being the most effective for predicting the `market_value_in_eur` and an MLP Classifier for predicting the `Classification_Label`.

## Features

* Predicts soccer player market value using Polynomial Regression.
* Classifies players based on market value classification labels using an MLP Classifier.
* Utilizes key features: Position, Foot, Height, Age, Highest Market Value, Current Club Competition, and Days Until Expiration.

## Technologies Used

* Python
* Pandas
* Scikit-learn (including PolynomialFeatures, LinearRegression, SVR, MLPClassifier)


## Running the Code

1.  **Run the main script:**
    * You can simply open the file in google collab or VS Code or any other place that is able to open a .ipynb and run the script.
    * The script will train the models and output the results.  Make sure the data is in a folder called `data` in the main directory.

## Data

* The dataset should contain soccer player information, including features like age, position, height, market value, etc.
* Ensure the dataset is stored in a CSV file (e.g., `player_data.csv`).
* Place the CSV file in a directory named "data" in the same directory as the main script.

## Results
The script will output the  R^2 and MSE for the regression model and the F1 score for the classification model.

## Disclaimer
    * This tool provides estimations and should not be used for financial decisions.
