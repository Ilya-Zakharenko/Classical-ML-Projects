# <center> **PROJECT: Bank Deposit Prediction**

Binary classification project to identify clients most likely to open a term deposit, helping to optimize marketing campaign efficiency.

---

### **Project Goal**

Develop a machine learning model that predicts whether a client will subscribe to a bank deposit based on their demographic and behavioral characteristics. This allows the bank to focus marketing efforts on the most promising clients and significantly increase campaign ROI.

---

### **Business Problem**

Banks have large amounts of customer data but contacting all clients is expensive and time-consuming. The task is to build a predictive model to target only those clients who are most likely to respond positively to a deposit offer.

---

### **Dataset**

- **Task type**: Binary classification
- **Target variable**: `deposit` (yes / no)
- **Features**: Client demographics (age, job, marital status, education), financial information, campaign contact details, and previous campaign outcomes.

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`, `plotly`
- `Optuna` (hyperparameter optimization)
- Ensemble methods (Random Forest, Gradient Boosting, Stacking)

---

### **Best Model & Results**

| Model                          | Train F1-score | Test F1-score |
|--------------------------------|----------------|---------------|
| **Stacking Ensemble** (Logistic Regression + others) | **0.85**       | **0.83**      |

The best performance was achieved using an **ensemble model based on Logistic Regression** (Stacking Classifier).

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature Engineering and selection (`SelectKBest`)
4. Handling outliers (`IsolationForest`)
5. Model training and comparison (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting)
6. Hyperparameter tuning with `Optuna` and `GridSearchCV`
7. Stacking ensemble and final evaluation

---

### **Key Achievements**

- Built a robust binary classification pipeline
- Successfully applied feature selection and outlier detection
- Achieved high **F1-score of 0.83** on the test set
- Developed a practical solution for increasing marketing campaign effectiveness

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw dataset
- `figures/` — EDA visualizations and model results
- `requirements.txt`

---

### **Conclusion**

This project demonstrates practical skills in solving real business problems using classical machine learning. The developed model allows the bank to significantly improve the efficiency of marketing campaigns by focusing on clients with the highest probability of opening a deposit.

---

### **How to run**

```bash
cd Classification_Task.Bank-Deposit-Marketing

pip install -r requirements.txt

jupyter notebook "PROJECT - Bank Deposit Prediction.ipynb"

---