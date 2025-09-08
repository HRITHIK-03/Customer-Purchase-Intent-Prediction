# Customer Purchase Intent Prediction  

## 📌 Overview  
This project focuses on predicting the **purchase intent of online shoppers** using a year-long dataset of session data. The aim was to analyze customer interactions and build machine learning models that can accurately classify whether a user is likely to make a purchase.  

## 🎯 Objectives  
- Explore and preprocess **e-commerce session data**.  
- Identify browsing patterns and behaviors that correlate with purchases.  
- Build and evaluate machine learning models for purchase prediction.  
- Derive actionable insights to help optimize marketing strategies and improve conversion rates.  

## 🗂 Dataset  
- **Files:**  
  - `data-train.csv` – training dataset with labeled outcomes  
  - `data-test.csv` – test dataset for model evaluation  
- **Target Variable:** Whether the user made a purchase (`1`) or not (`0`).  
- **Challenges:** Dataset included noisy and inconsistent columns, requiring careful cleaning and feature selection.  

## 📊 Analysis Approach  
1. **Data Cleaning & Preprocessing** – handled missing values, standardized data, and removed inconsistencies.  
2. **Exploratory Data Analysis (EDA)** – explored browsing behavior patterns.  
3. **Feature Engineering** – created meaningful features to strengthen model performance.  
4. **Model Building** – implemented classification models (Logistic Regression, Random Forest, Gradient Boosting, etc.).  
5. **Evaluation** – compared models using metrics such as accuracy, precision, recall, and AUC.  

## 📈 Results and Performance  
- Best-performing model achieved **~78% accuracy** in predicting customer purchase intent.  
- Analysis revealed that factors such as **session activity, visit frequency, and engagement levels** were key drivers of conversion.  

## 🚀 Tech Stack  
- **Python** – core development  
- **Pandas, NumPy** – data preprocessing  
- **Matplotlib, Seaborn** – visualization  
- **Scikit-learn, XGBoost** – modeling & evaluation  

## 📂 Repository Structure  
```
├── data-train.csv           # Training dataset 
├── data-test.csv            # Test dataset 
│
├── E-commerce.ipynb         # Main Jupyter notebook with EDA & modeling
└── README.md                # Project documentation
```  

## ✅ Key Takeaways  
- Demonstrates the use of **machine learning for real-world e-commerce applications**.  
- Highlights the importance of **data preprocessing and feature engineering** in improving predictive performance.  
- Provides insights that can help businesses **optimize marketing strategies and enhance customer experience**.  
