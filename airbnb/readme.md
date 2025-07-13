# 🏡 Airbnb Price Prediction 

A machine learning project that predicts the **price of an Airbnb listing** based on its **location and neighborhood**, using powerful regression techniques and 13 visualizations for exploratory analysis.

---

## 📊 Dataset

- 📎 Source: [Airbnb Dataset](https://github.com/adelnehme/python-for-spreadsheet-users-webinar/blob/master/datasets/airbnb.csv?raw=true)
- Format: CSV file with listing data
- Features include:
  - `latitude`, `longitude`
  - `neighbourhood`, `room_type`
  - `minimum_nights`, `number_of_reviews`
  - `availability_365` and more

---

## 🎯 Goal

> To predict the **Airbnb price** using longitude, latidute and neighbourhood full,and availability_365 helping users estimate cost based on where they stay.

---

## 📊 Exploratory Visualizations

- ✅ 13 visualizations created to understand:
  - Price distributions
  - Location-price patterns
  - Review trends
  - Room type frequency
  - Availability and more

---

## 🧪 Model Used

- ✅ **XGBoost Regressor**
  - Chosen for its performance on structured/tabular data
  - Tuned and trained with default/random parameters

### 📈 Performance:
Mean Absolute Error (MAE): 84.78
Mean Squared Error (MSE): 65704.82
Root Mean Squared Error (RMSE): 256.33



