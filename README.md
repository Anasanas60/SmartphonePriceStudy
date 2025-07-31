# SmartphonePriceStudy
A machine learning project to predict smartphone prices in the Bangladeshi market using Linear Regression. This project covers data cleaning, feature engineering, and model evaluation.
# Smartphone Price Study for the Bangladeshi Market

This repository contains a machine learning project focused on predicting the price of smartphones based on their specifications. The project uses a dataset of phones available in the Bangladeshi market and applies a Linear Regression model to find the relationship between features and price.

---

## 📋 Project Workflow

This project follows a standard machine learning pipeline:
1.  **Data Collection:** The dataset was sourced from Kaggle and contains information on 3,338 smartphone models.
2.  **Data Cleaning & Preprocessing:** This was the most critical phase.
    - Handled missing values.
    - Cleaned and converted columns like `Price`, `RAM`, and `Battery Capacity` from text to numerical types.
    - Applied **One-Hot Encoding** to categorical features like `Brand` and `OS` to make them usable by the model.
3.  **Model Training:** A **Linear Regression** model was trained on the cleaned dataset.
4.  **Model Evaluation:** The model's performance was assessed using standard regression metrics.

---

## 📊 Results & Evaluation

The trained model was evaluated on a held-out test set.

*   **R-squared (R²):** 0.61
    *   *This indicates that the model is able to explain approximately 61% of the variance in smartphone prices based on the provided features.*
*   **Mean Absolute Error (MAE):** 12,705.10 BDT
    *   *This means that, on average, the model's price predictions are off by about 12,705 Taka.*

**Conclusion:** The model shows a good ability to understand the general trends in the market (a respectable R² score), but there is room for improvement in the precision of its individual price predictions.

---

## 🛠️ Technologies Used

- **Language:** Python
- **Libraries:** Pandas, Scikit-learn, Seaborn, Matplotlib

---

## 🚀 How to Run this Project

1.  Clone this repository to your local machine.
2.  Ensure you have Python and the necessary libraries installed (`pip install pandas scikit-learn seaborn matplotlib`).
3.  Open and run the `smartphone_price_prediction.ipynb` notebook in a Jupyter environment.
