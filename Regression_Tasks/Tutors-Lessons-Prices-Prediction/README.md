# <center> **PROJECT: Tutors Lessons Prices Prediction**

Regression model for predicting the average price per minute of private tutoring lessons in Russia.

---

### **Project Goal**

Develop a machine learning model that predicts the fair price of a tutor’s lesson per minute (in RUB) based on their profile characteristics. This tool can help tutoring platforms set competitive and fair prices automatically.

---

### **Business Problem**

Students want to know the cost of lessons in advance, while tutors need transparent and data-driven pricing. The model solves this by predicting reasonable prices based on experience, qualifications, subject, rating, and other profile data.

---

### **Dataset**

- **Task type**: Regression (predicting price per minute in RUB)
- **Key Features**:
  - Tutor experience and qualifications
  - Education and subjects taught
  - Rating and number of reviews
  - Profile description (text features)
  - Location and other metadata

---

### **Technologies Used**

- `pandas`, `numpy`
- `category_encoders`, `imbalanced-learn`
- `scikit-learn` (Linear, Tree-based, Ensemble, SVM, etc.)
- `XGBoost`
- `Optuna` (hyperparameter optimization)
- `seaborn`, `plotly`, `matplotlib`
- `joblib` (model saving)

---

### **Best Models & Results**

| Metric                  | Best Model              | Score     |
|-------------------------|-------------------------|-----------|
| **MSE**                 | RandomForestRegressor   | **0.024** |
| **RMSE**                | RandomForestRegressor   | **0.154** |
| **MAE**                 | Ridge                   | **0.104** |
| **R²**                  | **XGBoost**             | **0.997** |

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature Engineering (including text processing)
4. Feature selection
5. Model training and comparison (Linear Models, Random Forest, XGBoost, etc.)
6. Hyperparameter tuning with Optuna
7. Model evaluation using multiple regression metrics
8. Final model selection and saving

---

### **Key Achievements**

- Built a high-accuracy regression model with **R² = 0.997**
- Performed comprehensive Feature Engineering on tutor profiles
- Compared classical and gradient boosting models
- Achieved very low error rates (especially MAE and RMSE)

---

### **Conclusion**

This project demonstrates strong expertise in regression modeling for pricing tasks. The developed model (especially XGBoost and RandomForest) can be used by tutoring platforms to automatically suggest fair lesson prices, improving transparency and user satisfaction.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw and processed datasets
- `figures/` — visualizations and model performance plots
- `models/` — saved best models (`joblib`)
- `requirements.txt`

---

