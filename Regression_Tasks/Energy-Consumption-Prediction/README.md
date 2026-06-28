# <center> **PROJECT: Energy Consumption Prediction**

Forecasting energy consumption using historical sustainable energy data (2000–2020) across multiple countries.

---

### **Project Goal**

Build a regression model to predict future energy consumption based on various economic, environmental, and energy-related indicators. The model helps in long-term energy planning and policy development.

---

### **Dataset**

- **Time period**: 2000–2020
- **Scope**: Data across multiple countries
- **Key Features**:
  - Access to electricity
  - Renewable energy share
  - CO₂ emissions
  - Energy intensity
  - GDP and economic growth
  - Financial flows and investments
  - Population and other macroeconomic indicators

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn`
- `XGBoost`, `AutoML`
- `matplotlib`, `seaborn`, `plotly`
- Polynomial Features
- Stacking ensembles

---

### **Models & Results**

| Model                        | Polynomial Features | RMSLE Train | RMSLE Valid |
|-----------------------------|---------------------|-------------|-------------|
| **XGBRegressor**            | Yes                 | **0.01**    | **0.11**    |
| **StackingRegressor**       | Yes                 | **0.03**    | **0.12**    |
| **RandomForestRegressor**   | Yes                 | 0.05        | 0.13        |
| **AutoML**                  | No                  | 0.15        | 0.15        |

**Best Model**: `XGBRegressor` with the lowest RMSLE score.

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature Engineering (including Polynomial Features)
4. Model training and comparison (Linear, Ridge, Tree-based, Ensemble, AutoML)
5. Hyperparameter tuning and model selection
6. Final prediction and interpretation

---

### **Key Results**

- Achieved excellent prediction quality with **RMSLE = 0.11** on validation set using XGBoost
- Identified the most influential factors affecting energy consumption
- Predicted **average energy consumption per person**: **259 kWh**

---

### **Conclusion**

This project demonstrates strong skills in time-series regression and energy forecasting. Using advanced ensemble methods like XGBoost and Stacking, we achieved high prediction accuracy, providing valuable insights for sustainable energy planning and policy-making.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw and processed datasets
- `figures/` — visualizations and model performance plots
- `requirements.txt`

---

