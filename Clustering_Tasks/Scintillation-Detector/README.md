# <center> **PROJECT: Scintillation Detector Signal Clustering**

Unsupervised clustering of signals from a scintillation detector to separate gamma quanta, neutrons, and anomalous signals in nuclear physics experiments.

---

### **Project Goal**

Develop an unsupervised machine learning model to automatically cluster scintillation detector signals into three distinct groups:
- Gamma quanta
- Neutrons  
- Anomalous / unidentifiable signals

---

### **Scientific Problem**

Scintillation detectors based on organic crystals (para-terphenyl) are widely used in nuclear physics, radiation monitoring, and neutron detection. However, manual analysis of tens of thousands of signals is impractical. The task is to automatically distinguish different types of ionizing radiation in the presence of complex background noise.

---

### **Dataset**

- **Number of signals**: 23,479
- **Task type**: Unsupervised clustering (3 clusters)
- **Features**: Various temporal, amplitude, statistical, and derived characteristics of each scintillation signal
- **Clusters**:
  - Cluster 0 & 1 → Gamma quanta and Neutrons (different particle types)
  - Cluster 2 → Anomalous or mixed signals

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn` (clustering algorithms)
- `matplotlib`, `seaborn`, `plotly`
- Feature Engineering
- Dimensionality reduction techniques

---

### **Project Stages**

1. Basic data analysis and familiarization
2. Data cleaning and preprocessing
3. Extensive Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Clustering model training and comparison (K-Means, GMM, DBSCAN, etc.)
6. Cluster interpretation and physical validation
7. Final conclusions and recommendations

---

### **Key Achievements**

- Successfully clustered **23,479** complex scintillation signals
- Applied advanced Feature Engineering specific to physical signal data
- Separated gamma and neutron signals with high quality
- Identified anomalous signals important for detector diagnostics and safety
- Solved a real scientific problem from the field of nuclear physics and radiation detection

---

### **Conclusion**

This project demonstrates the successful application of unsupervised learning to complex physical data in the field of nuclear physics. The developed clustering solution enables automatic separation of gamma and neutron signals and detection of anomalies, contributing to more accurate radiation monitoring and scientific measurements.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — raw signal dataset
- `figures/` — visualizations of clusters and signal characteristics
- `requirements.txt`

---
