# <center> **PROJECT: Physical Activity Recognition via Clustering**

Unsupervised clustering of sensor data from wearable devices to automatically recognize different types of physical activities.

---

### **Project Goal**

Develop a clustering model that can automatically identify various human physical activities (walking, running, squats, etc.) using data from inertial measurement units (IMU) and heart rate sensors. This solution can be applied in fitness trackers, medical monitoring, and behavioral analysis systems.

---

### **Dataset**

- **Source**: Data from three Inertial Measurement Units (IMU) + pulse oximeter (heart rate)
- **Task type**: Unsupervised clustering
- **Goal**: Group sensor readings into clusters corresponding to different types of physical activity
- **Application**: Personalized fitness tracking, health monitoring, and activity recognition

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn` (clustering algorithms)
- `matplotlib`, `seaborn`, `plotly`
- Feature Engineering
- Dimensionality reduction (if used)

---

### **Models Implemented**

- K-Means
- Hierarchical Clustering
- DBSCAN
- **Gaussian Mixture Models (GMM)** ← Best performer

---

### **Project Stages**

1. Basic data analysis and familiarization
2. Data cleaning and preprocessing
3. Feature Engineering (creating new meaningful features from sensor data)
4. Exploratory Data Analysis (EDA)
5. Clustering model training and comparison
6. Cluster interpretation and visualization
7. Final evaluation and conclusions

---

### **Best Model & Results**

**Gaussian Mixture Models (GMM)** showed the best performance in separating the data into meaningful activity clusters.

---

### **Key Achievements**

- Worked with real multi-sensor time-series data from wearable devices
- Performed extensive Feature Engineering on IMU and heart rate signals
- Successfully applied unsupervised learning for activity recognition
- Identified the most effective clustering algorithm (GMM) for this domain

---

### **Conclusion**

This project demonstrates the application of unsupervised learning to real-world sensor data for human activity recognition. The Gaussian Mixture Model achieved the best results in clustering different types of physical activity, opening possibilities for smart fitness and health monitoring applications.

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full pipeline
- `data/` — raw sensor data
- `figures/` — visualizations of clusters and activity patterns
- `requirements.txt`

---