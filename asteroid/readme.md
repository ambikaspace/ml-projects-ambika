# ☄️ Asteroid Hazard Prediction

A machine learning project to predict whether an asteroid is potentially hazardous based on its physical and orbital characteristics — using Logistic Regression, Random Forest, and XGBoost.

---

## 📊 Dataset

- Source: [GitLab - PHA Dataset](https://gitlab.com/mirsakhawathossain/pha-ml/-/raw/master/Dataset/dataset.csv)
- Total entries: ~950,000+ asteroids
- Features: orbital eccentricity, semi-major axis, inclination, absolute magnitude, and more
- Target: `pha` — whether the asteroid is considered **Potentially Hazardous**

---

## 🧪 Models Used

| Model                | Accuracy     | F1 Score (Hazardous) |
|---------------------|--------------|-----------------------|
| **XGBoost**         | **~0.9997**  | **Excellent**         |

---

## ✅ Best Model: XGBoost

- Achieved **99.97% accuracy**
- Low false negatives (misses very few hazardous objects)
- Important features: `diameter`, `moid`, `H`, `eccentricity`

---

## 📈 Visualizations

- Confusion Matrix
- Feature Importance (bar chart)

---

## 📁 Folder Structure

