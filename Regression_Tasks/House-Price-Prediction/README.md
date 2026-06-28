# <center> **PROJECT: House Price Prediction**

Regression model for predicting real estate prices based on property characteristics and historical listing data.

---

### **Project Goal**

Develop a reliable service that predicts the market value of houses to help buyers, sellers, and real estate agencies make informed decisions.

---

### **Business Problem**

Create an automated tool for estimating house prices using historical sales data and property features. Such a model can be integrated into real estate platforms, valuation services, or recommendation systems.

---

### **Dataset**

- **Task type**: Regression (predicting house price)
- **Features**: Property characteristics (area, number of rooms, location, floor, year built, condition, etc.), historical market data, and other relevant attributes.

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn`
- `XGBoost`
- `LightAutoML`
- `category_encoders`
- `matplotlib`, `seaborn`, `plotly`
- `pickle` (model serialization)

---

### **Best Model & Results**

| Model                    | RMSLE Train | RMSLE Valid | MAPE Train | MAPE Valid |
|--------------------------|-------------|-------------|------------|------------|
| **RandomForestRegressor**| **0.45**    | **0.49**    | **0.03**   | **0.03**   |

**Best Model**: `RandomForestRegressor` showed the most balanced and stable performance.

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature Engineering and categorical encoding
4. Model training and comparison (Linear Models, Tree-based, Ensemble, AutoML)
5. Hyperparameter tuning
6. Model evaluation using RMSLE and MAPE
7. Final model selection and serialization

---

### **Key Achievements**

- Built a robust house price prediction model with very low **MAPE = 0.03**
- Successfully worked with real estate data and categorical features
- Compared multiple models including LightAutoML and classical approaches
- Achieved good generalization on validation data

---

### **Conclusion**

This project demonstrates strong skills in regression modeling on real estate data. The developed Random Forest model achieves high accuracy (MAPE = 0.03) and can serve as the foundation for a practical house valuation service.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw and processed datasets
- `figures/` — visualizations and model evaluation plots
- `models/` — saved best model (`pickle`)
- `requirements.txt`

---
