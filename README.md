🏡 Task 6: House Price Prediction
✨ Objective
The goal of this task is to build a regression model that predicts house prices based on various property features such as size, number of bedrooms, and location. This task includes data preprocessing, model training, prediction, visualization, and evaluation using common regression metrics.

📁 Dataset
Dataset: House Price Prediction Dataset

Source: Kaggle (URL depends on the specific dataset you used)

Description: This dataset typically contains features like square footage, number of bedrooms and bathrooms, lot size, neighborhood information, and the target variable — the house sale price.

✅ Steps Completed
Data Preprocessing

Loaded the dataset using pandas.

Inspected the dataset for missing values and handled them appropriately.

Processed numerical features (e.g., square footage, bedrooms).

Encoded categorical features such as location or neighborhood.

Scaled or normalized features if necessary.

Model Building

Selected a regression model: Linear Regression or Gradient Boosting Regressor.

Split the dataset into training and testing sets.

Trained the model using the training data.

Made price predictions on the test set.

Visualization

Created scatter plots comparing actual vs. predicted house prices to visualize model performance.

Plotted residuals to check for patterns or bias.

Model Evaluation

Evaluated the model using:

Mean Absolute Error (MAE): Average absolute difference between actual and predicted prices.

Root Mean Squared Error (RMSE): Square root of the average squared differences.

Interpreted metrics to assess prediction accuracy.

Tools Used

pandas & NumPy: For data manipulation and cleaning.

scikit-learn: For regression modeling, training, and evaluation.

matplotlib & seaborn: For visualization of results and residuals.
