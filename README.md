# Flight Fare Prediction

> **Note:** This Project was created on Google Colab. If the `.ipynb` file is not working, please refer to the accompanying PDF.

## Project Description

In my final semester of Engineering, I undertook a Machine Learning project with a strong emphasis on Data Science, focused on predicting flight fares. The project began with loading and exploring the dataset using Pandas, followed by thorough data preprocessing steps such as handling missing values, encoding categorical variables, and detecting outliers to ensure data quality. I performed univariate and multivariate analysis to understand the relationships between features and to select the most relevant ones. To enhance model performance and reduce complexity, I applied Principal Component Analysis (PCA) for dimensionality reduction. For model training, I experimented with both Random Forest and K-Nearest Neighbors (KNN) algorithms independently. Model evaluation was conducted using multiple error metrics including RMSE, MSE, and MAE to gauge accuracy and performance. Additionally, I visualized the actual versus predicted fare values using a variety of plots to better understand model behavior. Finally, to interpret the model and explain its predictions, I utilized a SHAP plot, which provided insights into feature contributions and improved the model’s transparency.

## Summary of the Project

1. Loaded the `FlightFare_Dataset` from the project directory using Pandas' `read_excel` method.  
2. Performed feature exploration and engineering to transform the dataset.  
3. Applied feature selection to identify the most important features.  
4. Trained a `RandomForestRegressor` and `KNN`  model.  
5. Interpretted the model with the help of a SHAP Plot.

