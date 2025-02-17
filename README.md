# House Price Prediction Project

## Description

This project focuses on predicting house prices using a **Gradient Boosting Regressor** model. The dataset used contains various features of houses, such as size, location, and quality, along with their corresponding sale prices. The project involves:

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
- **Model Training**: Using a pipeline to preprocess data and train a Gradient Boosting Regressor.
- **Hyperparameter Tuning**: Optimizing the model using **GridSearchCV** with cross-validation.
- **Evaluation**: Assessing the model's performance using metrics like **MAE**, **RMSE**, **MAPE**, and **R²** on both training and test datasets.

The final model is trained on the entire dataset for deployment or further use.

---

## How to Run the Project

1. Clone the repository
2. Navigate to the folder containing the files.
3. Install the required libraries `pip install -r requirements.txt`
4. Run the house_price_prediction.ipynb notebook
