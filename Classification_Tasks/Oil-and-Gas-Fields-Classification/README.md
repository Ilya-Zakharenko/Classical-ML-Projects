# <center> **PROJECT: Classification of Oil and Gas Fields**

Machine Learning model for classifying oil and gas field locations (onshore vs offshore) based on geological and geophysical parameters.

---

### **Project Goal**

Develop a classification model to determine the type of oil and gas deposit location using geological data. This helps optimize exploration strategies and resource allocation in the oil and gas industry.

---

### **Business Problem**

In the oil and gas industry, accurately determining whether a deposit is located onshore or offshore is critical for planning exploration, drilling, and production. The model automates this classification based on various geological parameters.

---

### **Dataset**

- **Task type**: Multiclass / Binary classification (depending on target encoding)
- **Features**: Geological and geophysical parameters (depth, porosity, pressure, temperature, etc.)
- **Target**: Type of field location

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn`
- `category_encoders`
- `imbalanced-learn` (for oversampling)
- `seaborn`, `matplotlib`, `plotly`
- `joblib` (model saving)

---

### **Models & Results**

| Model                      | Accuracy | Precision | Recall | F1-score |
|----------------------------|----------|-----------|--------|----------|
| **RandomForestClassifier** | **0.839** | **0.839** | **0.839** | **0.839** |
| KNeighborsClassifier       | 0.806    | 0.816     | 0.806  | 0.810    |
| LogisticRegression         | 0.796    | 0.824     | 0.796  | 0.806    |
| DecisionTreeClassifier     | 0.796    | 0.797     | 0.796  | 0.795    |

**Best Model**: `RandomForestClassifier` with balanced performance across all metrics.

---

### **Project Stages**

1. Basic data analysis and familiarization
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Feature Selection
6. Model training and comparison (Logistic Regression, Decision Tree, Random Forest, KNN, etc.)
7. Final evaluation and conclusions

---

### **Key Achievements**

- Successfully performed comprehensive Feature Engineering
- Applied class imbalance handling techniques
- Built and compared multiple classification models
- Achieved strong performance with **Random Forest** (F1-score = 0.839)

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full pipeline
- `data/` — raw and processed datasets
- `figures/` — all visualizations and plots
- `models/` — saved best model (`joblib`)
- `requirements.txt`

---

### **Conclusion**

This project demonstrates practical skills in solving domain-specific classification tasks in the oil and gas industry. The developed Random Forest model provides reliable predictions and can be used to support geological exploration decisions.

---

### **How to run**

```bash
cd Classification_Task.Oil-and-Gas-Fields-Classification

pip install -r requirements.txt

jupyter notebook "PROJECT - Classification of Oil and Gas Fields.ipynb"

---