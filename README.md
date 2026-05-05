# Pulmonary Disease Risk Prediction System

##  Project Overview
This project aims to develop a predictive system for pulmonary disease using clinical and lifestyle-related data. The goal is to identify high-risk patients by analyzing key health and environmental factors and applying machine learning techniques for accurate prediction.

The system combines exploratory data analysis, clustering techniques, and supervised machine learning models to improve prediction performance and enable personalized risk assessment.

---

##  Exploratory Data Analysis (EDA)
The initial phase focused on descriptive analysis to understand the dataset and identify major risk factors associated with pulmonary disease. Key variables analyzed include:
- Energy level  
- Smoking habits  
- Mental stress  
- Pollution exposure  
- Immune system weakness  
- Family medical history  

These factors were found to significantly influence disease risk.

---

##  Clustering Analysis
To improve prediction accuracy, clustering techniques were applied to segment patients into distinct groups based on similarity in health and lifestyle patterns.

### Key outcome:
- Patients were grouped into **four distinct clusters**
- Each cluster represented a unique risk profile

This segmentation allowed models to capture more specific patterns within each subgroup.

---

##  Machine Learning Models
After clustering, separate machine learning models were trained for each group to improve predictive performance.

### Models used:
- Random Forest Classifier  
- Logistic Regression  

### Performance Summary:
- Random Forest performed best in **three clusters**
- Logistic Regression performed best in **one cluster**

This hybrid approach improved overall model accuracy and robustness.

---

##  Web Application
As a practical implementation, a user-friendly web application was developed to support real-world usage.

### Features:
- Input patient clinical and lifestyle data  
- Predict pulmonary disease risk in real time  
- Supports healthcare professionals in decision-making  

The application demonstrates how machine learning can be applied in healthcare for early detection and risk assessment.

---

##  Conclusion
This project highlights the effectiveness of combining clustering techniques with machine learning models for personalized healthcare prediction. Segmenting patients into meaningful groups significantly improved model performance and interpretability.

The system provides a foundation for future improvements, including integration of deeper learning models and more comprehensive medical datasets.

---

##  Tools & Technologies
- Python / R (depending on implementation)  
- Machine Learning (Random Forest, Logistic Regression)  
- Clustering Techniques  
- Data Preprocessing & EDA  
- Web Application Development  
