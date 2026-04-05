# <center> **PROJECT: Bayesian vs Classical Linear Regression**  
Apartment Price Prediction (Sberbank Housing Market)

This project is dedicated to comparing **Bayesian linear regression** and classical linear regression (`scikit-learn`) on the task of predicting apartment prices in Moscow and the Moscow region.

---

### **Description**

The project addresses two main objectives:
- **Regression** — predicting apartment price (`price_doc`).
- **Comparison of Bayesian and frequentist approaches** — analysis of model coefficients and their stability.

Special attention is paid to:
- Log-transforming the target variable (`log(price_doc)`) to improve its distribution.
- Building Bayesian linear regression using PyMC.
- Comparing model coefficients and analyzing credible intervals (HDI).

The project demonstrates how close (or different) the results of classical and Bayesian approaches are on real data.

---

### **Dataset**

- **Source**: Sberbank Russian Housing Market (Kaggle)
- **Description**: Data about apartments in Moscow and the surrounding region, including total area, living area, number of rooms, floor, building material, and other characteristics.
- **Target variable**: `price_doc` (apartment price in RUB).

---

### **Key Steps**

1. Exploratory Data Analysis (EDA) and examination of feature distributions.
2. Data preprocessing and Feature Engineering.
3. Log-transformation of the target variable (`log(price_doc)`) for normalization.
4. Building **Bayesian linear regression** (PyMC).
5. Building **classical linear regression** (`sklearn.LinearRegression`).
6. Comparing model coefficients.
7. Results analysis and conclusions.

---

### **Main Results**

Comparison of model coefficients (key features):

| Feature    | Classical Coefficient | Bayesian Mean | HDI 3% | HDI 97% |
|------------|-----------------------|---------------|--------|---------|
| full_sq    | 0.379167             | 0.527        | 0.479  | 0.569   |
| life_sq    | -0.047675            | -0.134       | -0.175 | -0.095  |
| num_room   | 0.043190             | 0.117        | 0.086  | 0.145   |

The coefficients of both models are **very similar**, but the Bayesian approach provides additional information in the form of posterior distributions and credible intervals (HDI).

---

### **Used Tools & Libraries**

- `Python`
- `Pandas`, `NumPy` — data processing
- `Matplotlib`, `Seaborn`, `Plotly` — visualization
- `scikit-learn` — classical linear regression
- `PyMC` — Bayesian modeling and sampling
- `ArviZ` — analysis of Bayesian results (`pm.summary`, trace plots, etc.)

---

### **Project Structure**

- `data/` — raw data (or instructions for downloading from Kaggle)
- `notebooks/` — main Jupyter Notebook with full analysis
- `figures/` — plots and visualizations (distributions, trace plots, posterior distributions)
- `requirements.txt` — list of dependencies