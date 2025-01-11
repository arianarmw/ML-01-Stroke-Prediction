# 🧠 Stroke Prediction Analysis  

## 📝 Overview  
This project applies **Machine Learning** techniques to analyze patient data for stroke prediction using **Clustering** and **Classification**. The goal is to uncover patterns in the data and build an accurate model to predict stroke occurrence.  

---

## 🚀 Project Goals  
### Clustering:  
- Preprocess categorical and numerical data.  
- Achieve a **Silhouette Score** of at least **0.55**.  
- Provide detailed clustering interpretation to explore patient groupings.  

### Classification:  
- Use the stroke attribute (`stroke`) as labels for supervised learning.  
- Achieve **Accuracy** and **F1-Score** of at least **85%** on both **training** and **testing sets**.  

---

## 📊 Key Features  
- **Data Preprocessing**: Handles missing values, categorical encoding, and feature scaling.  
- **Clustering**: Implements algorithms like K-Means to identify distinct patient groups.  
- **Classification**: Models like Logistic Regression, Random Forest, or Gradient Boosting to predict stroke occurrence.  
- **Evaluation**: Metrics include Silhouette Score for clustering and Accuracy/F1-Score for classification.  

---

## 🛠️ Tools & Technologies  
- **Programming Language**: Python  
- **Libraries**:  
  - **scikit-learn**: Model building and evaluation  
  - **pandas**: Data manipulation  
  - **matplotlib** & **seaborn**: Data visualization  
  - **NumPy**: Numerical computations  

---

## 📈 Dataset Overview  
The dataset contains information about patients, including their health status and whether they had a stroke.  
### Attributes:  
1. **id**: Unique identifier  
2. **gender**: "Male", "Female", or "Other"  
3. **age**: Age of the patient  
4. **hypertension**: 0 if no hypertension, 1 if hypertension  
5. **heart_disease**: 0 if no heart disease, 1 if heart disease  
6. **ever_married**: "No" or "Yes"  
7. **work_type**: "children", "Govt_job", "Never_worked", "Private", or "Self-employed"  
8. **Residence_type**: "Rural" or "Urban"  
9. **avg_glucose_level**: Average glucose level in blood  
10. **bmi**: Body mass index  
11. **smoking_status**: "formerly smoked", "never smoked", "smokes", or "Unknown"  
12. **stroke**: 1 if the patient had a stroke, 0 otherwise  

---

## 🚧 Current Status  
The project is under development.
---

## 🤔 Have Questions or Suggestions?  
Feel free to open an issue or reach out for collaboration, bug reports, or feedback! 💬  
