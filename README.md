# 📊 Flipkart CSAT Prediction – Machine Learning Classification Project

## ✅ Overview

This project focuses on predicting **Customer Satisfaction (CSAT)** for Flipkart’s customer service operations using Machine Learning.  
The dataset contains detailed records of customer interactions, agent performance, time metrics, issue categories, and customer feedback across multiple support channels.

The objective is to identify **key drivers of satisfaction**, detect dissatisfied customers early, and enable data-driven improvements in customer service quality.

---

## ✅ Problem Statement

Flipkart aims to improve customer satisfaction by understanding which operational, agent-specific, and issue-specific factors contribute to dissatisfied customer experiences.  
Using historical customer service data, the goal is to build a **multi-class classification model** that predicts CSAT scores (1–5) and provides actionable insights to enhance service performance.

---

## ✅ Business Context

Customer satisfaction is a critical KPI for service-oriented businesses.  
Accurate CSAT prediction enables Flipkart to:

- Detect unhappy customers early  
- Reduce churn and negative reviews  
- Improve agent training and performance management  
- Optimize operational processes like response & handling time  
- Improve overall customer experience and retention  

---

## ✅ Project Workflow

### **1. Data Understanding**
- Dataset loaded and explored  
- Missing values and duplicates handled  
- Categorical and numerical variable assessment  

### **2. Exploratory Data Analysis (EDA)**
- Trend analysis  
- Distribution plots  
- Correlation heatmaps  
- Agent performance insights  
- Customer behavior patterns  

### **3. Feature Engineering**
- Time-based features  
- Log transformations  
- Ratio features  
- Interaction features  
- Categorical encoding (Label Encoding + Frequency Encoding)  
- Handling multicollinearity  

### **4. Data Pre-processing**
- Missing value imputation  
- Outlier handling  
- Text preprocessing (punctuation removal, stopwords, tokenization)  
- Scaling & Transformation  

### **5. Model Development**
Models implemented:
- ✅ Logistic Regression (Baseline)  
- ✅ Random Forest Classifier (Ensemble)  
- ✅ XGBoost Classifier (Final Model)

### **6. Model Selection**
**XGBoost** selected as the final model due to:
- Best weighted F1-score  
- Better handling of non-linearity  
- Better generalization  
- Improved minority-class recall  

### **7. Model Explainability**
Tools used:
- XGBoost Feature Importance  
- SHAP Summary & Force Plots  

Insights highlighted:
- Response time  
- Handling time  
- Issue category  
- Agent tenure & shift  
- Resolution time  

---

## ✅ Final Results

| Model | Accuracy | Weighted F1 | Business Suitability |
|-------|----------|--------------|-----------------------|
| Logistic Regression | Moderate | Low | Weak for imbalance |
| Random Forest | Better | Good | Suitable |
| **XGBoost** ✅ | **Best** | **High** | **Selected Final Model** |

---

## ✅ Repository Structure

