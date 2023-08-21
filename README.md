# xGBoost-Sports-betting-Predictor

Sports betting match predictor model based on odds.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
-[Code Overview](code-overview)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This repository contains code for predicting match outcomes using the XGBoost classifier and visualizing the results through various plots. The code involves data 	preprocessing, model training, evaluation, and visualization of the outcomes and betting odds.

## Getting Started

1. Clone this repository to your local machine.

2. Install the required libraries using the following command:

		pip install pandas xgboost seaborn matplotlib scikit-learn

3. Place your match data in the sample_data folder with the filename data_model.csv.

## Code Overview
The provided code performs the following tasks:

1. Data Loading and Preprocessing: The match data is loaded from the CSV file and preprocessed. The 'RESULTS' column is mapped to class labels for classification.

2. Model Training: An XGBoost classifier is trained using the preprocessed data.

3. Model Evaluation: The trained model's accuracy is evaluated on a test set.

4. Predicting New Match Outcome: The trained model is used to predict the outcome of a new match based on the provided match statistics.

5. Visualizing Distribution of Outcomes: The distribution of match outcomes is visualized using a bar plot.

6. Visualizing Betting Odds: The distribution of betting odds for each outcome is visualized using kernel density estimation (KDE) plots.

7. Confusion Matrix Visualization: The confusion matrix is visualized using a heatmap.

8. Classification Report: The classification report containing precision, recall, F1-score, and support for each class is printed.

## Usage
1. Training and Evaluation: After placing the match data in the appropriate location, run the code to train the XGBoost model and evaluate its accuracy.

2. Prediction: Modify the new_match DataFrame to include the statistics of the match you want to predict. Run the code to predict the outcome of the new match using the trained model.

3. Visualization: Run the code to generate visualizations of outcome distribution, betting odds distribution, confusion matrix, and classification report.



## Contributing

Feel free to modify the code to suit your needs. You can adjust model parameters, enhance visualization plots, or expand the code to include additional features.


