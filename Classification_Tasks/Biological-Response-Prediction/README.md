# <center> **PROJECT: Biological Response Prediction**

Binary classification project to predict the biological activity of molecules based on their chemical composition.

---

### **Project Goal**

Develop models to predict whether a molecule will show biological activity (`Activity = 1`) or not, based on 1776 molecular descriptors. The main focus is on thorough hyperparameter tuning using multiple optimization methods.

---

### **Dataset**

- **Task type**: Binary classification
- **Target**: `Activity` (biological response)
- **Features**: 1776 chemical/molecular descriptors (D1–D1776)
- High-dimensional tabular data

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn` (Logistic Regression, Random Forest)
- Hyperparameter optimization:
  - `GridSearchCV`
  - `RandomizedSearchCV`
  - `Hyperopt`
  - `Optuna`
- `matplotlib`, `seaborn` — visualization

---

### **Models & Results**

**Logistic Regression**

| Optimization   | Train F1 | Test F1 | Test Accuracy | Tuning Time |
|----------------|----------|---------|---------------|-------------|
| Hyperopt       | 0.91     | 0.76    | 0.73          | 4min 27s    |
| Optuna         | 0.99     | 0.76    | 0.73          | 3min 23s    |

**Random Forest**

| Optimization   | Train F1 | Test F1 | Test Accuracy | Tuning Time |
|----------------|----------|---------|---------------|-------------|
| Hyperopt       | 0.99     | **0.81**| **0.79**      | 34.1s       |
| Optuna         | 0.99     | 0.80    | 0.78          | 42.4s       |

**Best Model**: Random Forest + Hyperopt (F1 = 0.81 on test set)

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data preprocessing
3. Baseline model training (Logistic Regression + Random Forest)
4. Hyperparameter tuning using 4 different methods
5. Model comparison and analysis
6. Final conclusions

---

### **Key Achievements**

- Comprehensive comparison of hyperparameter optimization techniques
- Achieved strong classification performance on high-dimensional molecular data
- Demonstrated efficiency differences between GridSearch, RandomizedSearch, Hyperopt, and Optuna

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook
- `data/` — dataset
- `figures/` — visualizations
- `requirements.txt`

---

### **Conclusion**

This project demonstrates solid skills in binary classification on high-dimensional data and deep expertise in hyperparameter optimization. Random Forest combined with Hyperopt showed the best balance of quality and tuning speed.

---