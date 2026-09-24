Developed a neural network model to predict used-car selling prices using vehicle specifications, location, ownership, and sales-related features.

Key work:
- Performed exploratory data analysis to identify missing values, inconsistent data types, high-cardinality categorical features, and formatting issues.
- Engineered features from unstructured vehicle information, including extracting torque values and RPM ranges and converting torque units from kgm to Nm.
- Preprocessed numerical and categorical features using RobustScaler and OneHotEncoder, with a 70:10:20 train-validation-test split.
- Developed and evaluated a baseline neural network model and a tuned model using TensorFlow/Keras.
- Improved the model using a simpler architecture with 256 neurons, a lower learning rate (0.0005), Huber Loss, and early stopping to improve stability and robustness to outliers.
- Evaluated both models using MAE, RMSE, MAPE, and R². The tuned model achieved an MAE of $943.87, RMSE of $1,669.32, MAPE of 17.19%, and R² of 0.9641 on the test set.
