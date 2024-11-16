# **Customer Behavior Prediction Using Machine Learning**

---

## 📋 **Problem Statement**

This project focuses on predicting customer behavior based on a dataset of web-browsing patterns. The goal is to:

- Perform **Exploratory Data Analysis (EDA)** to uncover insights and trends.
- Identify important variables influencing customer behavior.
- Develop and evaluate **machine learning models** to predict the **Target variable (binary classification)**.

---

## 🗂 **Dataset Details**

- **File Name**: Dataset.xlsx  
- **Rows**: 12,330  
- **Columns**: 18 (includes both numerical and categorical variables)  
- **Target Variable**: `Target` (binary variable)  

---

## 🚀 **Steps in the Solution**

### **1. Exploratory Data Analysis (EDA)**

- **Distribution analysis** of the Target variable.  
- **Correlation analysis** between features using heatmaps.  
- **Relationship visualization** between key features like `BounceRates` and `ExitRates`.  
- **Histograms**, **pair plots**, and **summary statistics** to understand the data structure.  

### **2. Data Preprocessing**

- **Handling categorical variables**: Applied **One-Hot Encoding**.  
- **Feature scaling**: Used `StandardScaler` to normalize numerical features.  
- **Data Splitting**: Split the dataset into **training (80%)** and **testing (20%)** sets.  

### **3. Model Selection**

- **Logistic Regression**: Used as a baseline model for interpretability.  
- **Random Forest Classifier**: Selected for its ability to handle mixed data types and calculate feature importance.  
- **Support Vector Machine (SVM)**: Included for its performance in high-dimensional spaces.  

### **4. Model Evaluation**

- Generated **accuracy**, **confusion matrix**, and **classification reports** for all models.  
- Performed **ROC AUC score** and **ROC curve analysis** to evaluate classifier performance.  

### **5. Conclusion**

- **Random Forest** emerged as the best model, achieving **92% accuracy**.  
- Feature importance analysis highlighted **less significant features**, offering opportunities for optimization.  

---

## 📈 **Results and Business Impact**

- The model enables businesses to **predict customer behavior**, enhancing user engagement, improving marketing strategies, and increasing conversion rates.  
- **Feature Importance** insights allow businesses to focus on high-impact areas such as `PageValues` and `ProductRelated_Duration`, optimizing website content and layout for better engagement.  
- By addressing the **imbalanced Target variable** and applying **hyperparameter tuning**, model accuracy can be further improved.  

---

## 💡 **Next Steps for Improvement**

1. **Feature Optimization**: Drop features with low importance after consulting domain experts.  
2. **Handling Imbalance**: Use techniques like oversampling or **SMOTE** to balance the Target variable.  
3. **Hyperparameter Tuning**: Further refine model parameters for higher accuracy and efficiency.  
