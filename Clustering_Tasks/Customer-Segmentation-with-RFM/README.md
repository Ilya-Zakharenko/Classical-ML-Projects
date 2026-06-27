# <center> **PROJECT: Customer Segmentation with RFM**

RFM-based customer segmentation for an online store to identify different customer types and develop personalized retention strategies.

---

### **Project Goal**

Perform customer segmentation using **RFM analysis** (Recency, Frequency, Monetary) to understand customer behavior and enable more effective, personalized marketing strategies.

---

### **Business Problem**

Most e-commerce companies rely only on basic web analytics. This project goes deeper by segmenting customers into meaningful groups (Loyal, Promising, New, Sleeping, Churned, etc.) to choose the right communication and retention strategy for each segment.

---

### **Technical Task**

Build a clustering model based on three key RFM metrics:
- **Recency** — how recently a customer made a purchase
- **Frequency** — how often they make purchases
- **Monetary** — how much money they spend

Then interpret the resulting segments and build a classification model to automatically assign new customers to segments.

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn` (clustering and classification)
- `matplotlib`, `seaborn`, `plotly`
- t-SNE for visualization
- Transition from unsupervised (clustering) to supervised (classification) approach

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. RFM features calculation
3. Data scaling and preprocessing
4. Clustering (K-Means and others)
5. Cluster visualization and interpretation (using t-SNE)
6. Building a classification model to predict customer segment
7. Business recommendations for each segment

---

### **Key Achievements**

- Successfully implemented classic **RFM analysis**
- Performed customer segmentation and detailed profile interpretation
- Overcame t-SNE non-parametric limitations and transitioned to a classification model
- Developed an automatic system for assigning new customers to behavioral segments

---

### **Conclusion**

This project demonstrates a complete cycle of customer segmentation: from RFM feature engineering and unsupervised clustering to building a production-ready classification model. The resulting segments allow the company to move from generic marketing to highly personalized strategies, significantly improving customer retention and sales efficiency.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw transactional data
- `figures/` — RFM distributions, cluster visualizations, t-SNE plots
- `requirements.txt`

---
