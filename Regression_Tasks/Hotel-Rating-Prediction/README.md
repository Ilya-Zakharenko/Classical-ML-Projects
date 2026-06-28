# <center> **PROJECT: Hotel Rating Prediction**

Regression model for predicting hotel ratings to detect potential review manipulation and unfair practices.

---

### **Project Goal**

Develop a regression model that predicts a hotel's rating based on various characteristics. Significant discrepancies between the predicted and actual rating can serve as a signal for further investigation into dishonest practices (e.g., fake reviews).

---

### **Business Problem**

One of the major issues in the hospitality industry is hotels artificially inflating their ratings. This model helps identify suspicious cases by comparing predicted ratings (based on objective features) with actual ratings.

---

### **Dataset**

- **Task type**: Regression (predicting hotel rating, e.g. from 1 to 5)
- **Features**:
  - Hotel characteristics (location, service level, price, etc.)
  - Review text (processed with sentiment analysis)
  - Geographical data
  - Other metadata

---

### **Technologies Used**

- `pandas`, `numpy`
- `LightAutoML` (`TabularAutoML`)
- `scikit-learn`
- `NLTK` + VADER (sentiment analysis of reviews)
- `category_encoders`
- `geopy` (distance calculations)
- `matplotlib`, `seaborn`, `plotly`

---

### **Results**

- **Final MAPE**: **0.1247**
- **MAPE improvement**: **0.0167** (after full preprocessing and modeling)

The model achieved good predictive quality for a regression task on hotel ratings.

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data cleaning and preprocessing
3. Feature Engineering (including text sentiment analysis)
4. Geographical feature processing
5. Model training with LightAutoML and classical models
6. Model evaluation and interpretation
7. Detection logic for suspicious hotels

---

### **Key Achievements**

- Built a strong regression model using AutoML and classical approaches
- Implemented sentiment analysis on hotel reviews
- Developed a practical tool for detecting potential rating manipulation
- Significantly improved prediction quality through careful preprocessing

---

### **Conclusion**

This project demonstrates the application of machine learning to solve a real business problem in the hospitality industry. The developed model not only predicts hotel ratings with high accuracy but also serves as an effective tool for identifying potentially dishonest hotels through significant prediction-actual rating discrepancies.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw and processed datasets
- `figures/` — visualizations and model results
- `requirements.txt`

---
