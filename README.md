# Employee Churn Prediction  

This project focuses on predicting employee churn (whether an employee will leave or not) using **Machine Learning** and **Deep Learning** techniques. The dataset includes demographic, professional, and organizational features such as education, joining year, city, payment tier, age, gender, experience, and bench history.  

## 📊 Project Overview  
- **Goal:** Build a predictive model to determine the likelihood of employee attrition.  
- **Dataset Size:** 4,653 rows × 9 columns.  
- **Target Variable:** `LeaveOrNot` (1 = Employee leaves, 0 = Employee stays).  
- **Approach:**  
  - Data preprocessing (encoding categorical variables, scaling).  
  - Feature engineering using `pandas` and `sklearn`.  
  - Neural network modeling with `TensorFlow/Keras`.  
  - Hyperparameter tuning with **Optuna**.  
  - Model evaluation with ROC-AUC.  

## ⚙️ Tech Stack  
- **Languages & Libraries:**  
  - Python, Pandas, NumPy, Scikit-learn  
  - TensorFlow / Keras  
  - Optuna (hyperparameter optimization)  
- **Environment:** Jupyter Notebook / Python 3.10+  

## 🚀 Results  
- Best model achieved **ROC-AUC ≈ 0.89** after hyperparameter tuning.  
- Neural networks with tuned optimizers (Adam, RMSprop) gave strong performance.  
- Feature scaling significantly improved convergence.  


   git clone https://github.com/yourusername/employee-churn-prediction.git
   cd employee-churn-prediction
