# 🧠 Health Behavior Prediction Using Ensemble Learning

## 📌 Project Overview  
This project demonstrates a hands-on approach to building a predictive model aimed at classifying health-related behaviors—specifically smoking and drinking status—based on physiological and lifestyle features. It follows a complete machine learning pipeline including preprocessing, feature engineering, model building, evaluation, and deployment.

---

## 🔍 Key Highlights

### 📊 Data Preprocessing
- Cleaned dataset and handled missing values
- Encoded categorical variables into numerical format
- Normalized and scaled data for better model performance

### 🧬 Feature Engineering
- Engineered new features like **BMI** from height and weight
- Ranked features based on importance using tree-based models

### 📤 Data Splitting
- Used an 80-20 train-test split to evaluate model generalization

### 🧠 Machine Learning Techniques
- Implemented **Bagging**, **Voting**, **Boosting**, and **Stacking** classifiers
- Evaluated models using **Accuracy**, **ROC-AUC**, and **Confusion Matrix**

### 📈 Hyperparameter Tuning
- Applied **GridSearchCV** to find the best parameter combinations
- Tuned **XGBoost** and **LightGBM** for optimal performance

### 🔁 Cross-Validation
- Used **K-Fold Cross-Validation** on XGBoost for stability and robustness
- Exported the final model as a `.joblib` file for deployment

---

## 🧰 Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, XGBoost, LightGBM  
- **Visualization**: Matplotlib, Seaborn  
- **Model Serialization**: Joblib  

---

## 🎯 Outcome
Trained and evaluated multiple ensemble models. The best-performing model—optimized using hyperparameter tuning and validated with K-Fold CV—was saved for future deployment and prediction tasks.
