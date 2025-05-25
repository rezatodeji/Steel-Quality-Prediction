# Steel-Quality-Prediction
This notebook presents a structured machine learning pipeline to predict the quality of steel products using a hybrid model based on XGBoost regression. The workflow includes:

Data Loading: Reading the training and test datasets.

Data Cleaning and Feature Selection: Removing irrelevant columns such as IDs, timestamps, and categorical identifiers to retain only the predictive features.

Data Splitting: Dividing the training set into train/test subsets for evaluation.

Feature Scaling: Applying standard scaling to normalize the numerical features.

Model Training: Training an XGBoost Regressor model with specified hyperparameters.

Evaluation: Assessing the model’s performance using Mean Squared Error (MSE).

Feature Importance: Visualizing which features most influence the predictions.

Prediction and Submission: Generating predictions on the test set and exporting the results to a CSV file for Kaggle submission
