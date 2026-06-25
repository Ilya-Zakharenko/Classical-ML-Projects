# <center> **PROJECT: Airline Passenger Satisfaction Prediction**

Binary classification project to predict whether a passenger is satisfied with the flight based on survey data.

---

### **Project Goal**

Build a high-accuracy classification model to predict passenger satisfaction (`satisfied` / `neutral or dissatisfied`) to help the airline improve service quality and customer experience.

---

### **Dataset**

- **Number of observations**: 103,904
- **Number of features**: 25 (5 categorical + 20 numerical)
- **Target variable**: `satisfaction` (binary)

**Key Features:**
- `Gender`, `Customer Type`, `Age`, `Type of Travel`, `Class`
- Service ratings (1–5): WiFi, food, seat comfort, cleanliness, etc.
- Flight distance, departure/arrival delays

---

### **Technologies Used**

- `Python`
- `pandas`, `numpy`
- `scikit-learn`
- `XGBoost`, `CatBoost`
- `matplotlib`, `seaborn`, `plotly`

---

### **Best Models & Results**

| Model                  | Train F1-score | Test F1-score | Error Rate |
|------------------------|----------------|---------------|------------|
| **CatBoostClassifier** | 0.973          | **0.958**     | **2.6%**   |
| **XGBClassifier**      | 0.974          | **0.959**     | **2.6%**   |

**Best models**: `CatBoost` and `XGBoost` showed the highest performance.

---

### **Project Stages**

1. Basic data analysis and exploration
2. Data cleaning and preprocessing
3. Feature Engineering
4. Model training (Logistic Regression, AdaBoost, Gradient Boosting, XGBoost, CatBoost)
5. Hyperparameter tuning and model comparison
6. Final evaluation and conclusions

---

### **Key Achievements**

- Achieved **95.9%** F1-score on the test set
- Successfully handled both categorical and numerical features
- Identified the most important factors affecting passenger satisfaction
- Built high-performance gradient boosting models

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw and processed datasets
- `figures/` — visualizations and feature importance plots
- `requirements.txt`

---

### **Conclusion**

This project demonstrates strong skills in binary classification on real-world tabular data. Using gradient boosting models (XGBoost and CatBoost), we achieved excellent performance with only 2.6% error rate, highlighting the most important service aspects that influence passenger satisfaction.

---

### **How to run**

```bash
cd Classification_Task.Airline-Passenger-Satisfaction-Prediction

pip install -r requirements.txt

jupyter notebook "PROJECT - Airline Passenger Satisfaction Prediction.ipynb"

---