# <center> **PROJECT: Gender Classification by Voice**

Binary classification model to determine a person's gender (male/female) based on acoustic voice features.

---

### **Project Goal**

Develop a machine learning model capable of accurately classifying gender using only voice characteristics extracted from audio recordings. This type of model can be used in voice processing systems, virtual assistants, and security applications.

---

### **Dataset**

- **Task type**: Binary classification (`male` / `female`)
- **Features**: Acoustic properties of voice, including:
  - Fundamental frequency
  - Amplitude and spectral features
  - Formant frequencies
  - Other voice-derived characteristics

---

### **Technologies Used**

- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`, `plotly`

---

### **Best Model & Results**

| Model                    | Train Accuracy | Test Accuracy |
|--------------------------|----------------|---------------|
| **DecisionTreeClassifier** | **0.996**      | **0.970**     |

The best performance was achieved using a **Decision Tree** model.

---

### **Project Stages**

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and cleaning
3. Feature analysis and selection
4. Model training and comparison
5. Hyperparameter tuning
6. Final evaluation and conclusions

---

### **Key Achievements**

- Achieved very high **test accuracy of 97.0%**
- Successfully worked with acoustic voice features
- Built a simple yet highly effective model using Decision Trees
- Demonstrated strong understanding of classification on audio-derived data

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook with full analysis
- `data/` — dataset with voice features
- `figures/` — visualizations and feature importance plots
- `requirements.txt`

---

### **Conclusion**

This project shows excellent results in voice-based gender classification using classical machine learning. The Decision Tree model achieved 97% accuracy on the test set, proving that acoustic features contain strong predictive signals for gender recognition.

---

### **How to run**

```bash
cd Classification_Task.Gender-Classification-by-Voice

pip install -r requirements.txt

jupyter notebook "PROJECT - Gender Classification by Voice.ipynb"