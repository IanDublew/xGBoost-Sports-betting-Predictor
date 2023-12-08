

Script Details
The main script, predict_version_2.py, defines a function train_best_model that:

Loads the sample data.
Maps actual labels to class labels.
Preprocesses the data.
Iteratively splits the data, standardizes features, and trains an XGBoost model with different random states.
Saves the best model and scaler based on the highest accuracy achieved.
Prints the final result, indicating the highest accuracy and the corresponding random state.
Finally, the script demonstrates how to use the best model and scaler to predict the outcome of a new football match.

Feel free to customize the script parameters and explore different configurations for optimal performance.
		
