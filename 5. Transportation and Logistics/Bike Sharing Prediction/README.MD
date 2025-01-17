# Bike Sharing Prediction using XGBoost

This project focuses on predicting bike sharing demand using machine learning algorithms, specifically **XGBoost**, a powerful gradient boosting technique. The goal is to predict the number of bike rentals based on various features such as weather conditions, time of day, and other factors.

---

## Project Overview

- **Data Analysis**:  
  The project uses a dataset containing information on bike rentals, including time-related features (hour, day, month), weather conditions, and holidays.

- **Feature Engineering**:  
  Several features are processed and engineered to improve model performance, such as encoding categorical variables, handling missing values, and normalizing numerical features.

- **Modeling**:  
  **XGBoost** (Extreme Gradient Boosting) is used to train a predictive model. XGBoost is an efficient and scalable machine learning algorithm that is well-suited for regression and classification tasks.

- **Model Evaluation**:  
  The performance of the model is evaluated using metrics like **RMSE** (Root Mean Squared Error) to assess prediction accuracy.

---

## Technologies Used

- **Python**: Programming language used for development.
- **XGBoost**: Gradient boosting algorithm for predictive modeling.
- **Pandas & NumPy**: Libraries for data manipulation and analysis.
- **Matplotlib & Seaborn**: Libraries for data visualization.
- **Scikit-learn**: Library for machine learning model evaluation and preprocessing.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/mohammadreza-mohammadi94/Data-Analysis-And-Machine-Learning-Projects
   ```

2. Navigate to the directory:
   ```bash
   cd Data-Analysis-And-Machine-Learning-Projects/5.%20Transportation%20and%20Logistics/Bike%20Sharing%20Prediction
   ```

3. Open and run the notebook:
   ```bash
   bike_sharing_boosting_algorithms_xgboost.ipynb
   ```

4. Ensure that the necessary libraries are installed:
   ```bash
   pip install xgboost scikit-learn matplotlib seaborn category_encoders lightgbm
   ```

5. Follow the steps in the notebook to explore the dataset, perform feature engineering, train the XGBoost model, and evaluate its performance.

