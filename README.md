🧠 Health Behavior Prediction Using Ensemble Learning
📌 Project Overview
This project presents a hands-on, project-based learning approach focused on building a predictive model to analyze and classify health-related behaviors, particularly smoking and drinking status, using physiological and lifestyle features.

🔍 Key Highlights
📊 Data Preprocessing:

Cleaned and handled missing values

Converted categorical variables to numerical format

Normalized and scaled data for model performance

🧬 Feature Engineering:

Created new features such as BMI from height and weight

Ranked features based on their importance and impact using various models (e.g., feature importance from tree-based models)

📤 Data Splitting:

Reserved 20% of the dataset for testing to evaluate model generalization

🧠 Machine Learning Techniques:

Implemented Bagging, Voting, Boosting, and Stacking classifiers

Evaluated performance through accuracy, ROC-AUC, and confusion matrix

📈 Hyperparameter Tuning:

Applied GridSearchCV for exhaustive search over hyperparameter combinations

Optimized both XGBoost and LightGBM classifiers for best performance

🔁 Cross-Validation:

Used K-Fold Cross-Validation on XGBoost to ensure stable and reliable results

Final model exported as a .joblib file for deployment

🧰 Technologies Used
Python (Pandas, NumPy, Scikit-learn, XGBoost, LightGBM)

Matplotlib & Seaborn (for EDA and visualization)

Joblib (for model serialization)

🎯 Outcome
Successfully trained and evaluated multiple ensemble learning models, selected the best-performing one using k-fold cross-validation and hyperparameter tuning, and saved it for future use.

