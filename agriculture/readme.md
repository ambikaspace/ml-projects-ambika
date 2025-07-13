# 🌾 Agriculture Crop Yield Prediction

This project predicts **crop yield (tons per hectare)** based on various environmental and farming features using **Linear Regression**.

🔍 Insight
✅ The goal of this project was to build a predictive model that estimates crop yield (in tons per hectare) using environmental and agricultural features such as rainfall, temperature, crop type, soil, irrigation, and fertilizer usage.

This can help farmers, agricultural planners, and decision-makers make more informed choices to maximize yield, minimize risk, and allocate resources efficiently.

🧠 After training a Linear Regression model:

The model achieved a high R² score of 0.913, meaning it can explain 91.3% of the yield variation

The RMSE was only 0.50, showing it predicts yield very closely on unseen data

There were no major outliers, and predicted values clustered tightly around the actual values

🌾 This shows that:

Environmental and farming factors have a strong, predictable relationship with yield

Even a simple model like Linear Regression can be powerful when applied to a clean, structured dataset

The project demonstrates the potential of machine learning in agriculture — especially for yield optimization and decision-making on a large scale

### 📊 Dataset
- 1,000,000 rows
- Features: Region, Soil Type, Crop, Rainfall, Temperature, Fertilizer, Irrigation, Weather, Days to Harvest
- Target: Yield (tons per hectare)

### 🧠 Model
- Algorithm: Linear Regression
- R² Score: **0.913**
- RMSE: **0.50**
- No missing data; used one-hot encoding for categorical columns

### 📈 Visualizations
- Scatter plot of actual vs predicted yields

### 📁 Files
- `agriculture_model.ipynb`: Notebook with full pipeline
- `README.md`: Project summary
