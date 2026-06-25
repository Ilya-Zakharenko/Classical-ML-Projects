# <center> **PROJECT: Rain Prediction in Australia**

Binary classification project to predict whether it will rain tomorrow in Australia based on meteorological data.

---

### **Project Goal**

Build an accurate machine learning model to forecast rain occurrence (Yes/No) using historical weather observations. The model can be used to improve weather forecasting and support decision-making in agriculture, tourism, and daily planning.

---

### **Dataset**

- **Task type**: Binary classification (`RainTomorrow` — Yes / No)
- **Features**: Meteorological variables including:
  - Temperature (min/max)
  - Humidity, pressure, wind speed and direction
  - Rainfall (today and previous days)
  - Sunshine, cloud cover, evaporation, etc.
- **Location**: Multiple weather stations across Australia

---

### **Technologies Used**

- `pandas`, `numpy`
- `category_encoders`
- `scikit-learn`
- `XGBoost`, `CatBoost`
- `matplotlib`, `seaborn`, `plotly`

---

### **Models Implemented**

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Naive Bayes
- Gradient Boosting (XGBoost, CatBoost)

---

### **Project Stages**

1. Basic data analysis and familiarization
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering and encoding
5. Feature selection
6. Model training and comparison
7. Hyperparameter tuning
8. Final evaluation and conclusions

---

### **Key Achievements**

- Comprehensive preprocessing of meteorological time-series data
- Successful handling of categorical and numerical features
- Comparison of classical and gradient boosting models
- Practical application of weather prediction using ML

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw weather dataset
- `figures/` — EDA plots and model performance visualizations
- `requirements.txt`

---

### **Conclusion**

This project demonstrates skills in solving a real-world binary classification problem with meteorological data. By leveraging various models including XGBoost and CatBoost, the developed solution helps predict rain occurrence more effectively, showcasing practical machine learning application in weather forecasting.

---

### **How to run**

```bash
cd Classification_Task.Rain-Prediction-in-Australia

pip install -r requirements.txt

jupyter notebook "PROJECT - Rain Prediction in Australia.ipynb"

---