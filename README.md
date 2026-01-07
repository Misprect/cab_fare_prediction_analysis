---
# Cab Fare Prediction using Machine Learning
---

## Project Overview

This project predicts cab fare prices based on trip distance, time-based features, and passenger details using supervised machine learning models.

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## Models Implemented

- Linear Regression (baseline)
- Random Forest Regressor
- Gradient Boosting Regressor
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV

---

## Evaluation Metrics

- R² Score
- Root Mean Squared Error (RMSE)

---

## Results

The Gradient Boosting model achieved the best performance with:

- R² ≈ 0.77
- Low RMSE indicating accurate fare predictions

---

## Output

Final predictions are saved as:
results/pred_fare_test.csv

---

## How to Run

1. Install dependencies  
   pip install -r requirements.txt
2. Run the notebook  
   notebooks/cab_fare_prediction.ipynb

---

## Conclusion

This project demonstrates an end-to-end machine learning workflow including data preprocessing, feature engineering, model selection, tuning, and deployment-ready predictions.

---

## Dataset

The dataset files are large and are not included in this repository.

Download the dataset from:
🔗 (Kaggle / Google Drive / Internship source)

After downloading, place files as:
train/train_cab.csv
test_cab.csv

---
