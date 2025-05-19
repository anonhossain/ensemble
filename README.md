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
![Feature Ranking](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/feature_ranking.PNG)

### 📤 Data Splitting
- Used an 80-20 train-test split to evaluate model generalization

### 🧠 Machine Learning Techniques
- Implemented **Bagging**, **Voting**, **Boosting**, and **Stacking** classifiers
- Evaluated models using **Accuracy**, and **Confusion Matrix**
![Voting](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/voting%20result.PNG)
![Boosting](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/boosting_result.PNG)
![CatBoost](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/catBoosting.PNG)
![Stacking](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/stacking.PNG)

### 📈 Hyperparameter Tuning
- Applied **GridSearchCV** to find the best parameter combinations
- Tuned **XGBoost** and **LightGBM** for optimal performance
![Boosting Parameters](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/boosting%20parameters.PNG)

### 🔁 Cross-Validation
- Used **K-Fold Cross-Validation** on XGBoost for stability and robustness
- Exported the final model as a `.joblib` file for deployment

![K fold](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/fold%205%20out%20of%201.PNG)
![Saved](https://github.com/anonhossain/ensemble/blob/main/result/screenshot/saved.PNG)

---

## 🧰 Technologies Used
- **Python**: Pandas, NumPy, Scikit-learn, XGBoost, LightGBM  
- **Visualization**: Matplotlib, Seaborn  
- **Model Serialization**: Joblib  

---

## 🎯 Outcome
Trained and evaluated multiple ensemble models. The best-performing model—optimized using hyperparameter tuning and validated with K-Fold CV—was saved for future deployment and prediction tasks.
