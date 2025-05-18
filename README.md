
# 💳 Credit Card Default Prediction - Project

## 📘 Overview

 The objective was to predicting customer defaults based on historical demographic and financial data.

Using machine learning models, I built and compared several predictive algorithms to determine the most accurate method for identifying customers at risk of defaulting in the next month. The data used for this analysis includes 30,000 anonymized credit card records over a six-month period.

---

## 📌 Project Details

### 🔍 What the Project Does
This project builds a predictive machine learning model that determines the likelihood of a credit card account holder defaulting in the next month. It uses demographic and financial behavior data to train various classification algorithms and identifies the most accurate approach for predicting customer default risk.

### 💡 Why the Project Is Useful
Credit card companies face significant financial losses due to payment defaults. By leveraging predictive analytics, this project helps proactively identify high-risk customers. This enables companies to take preventive actions such as customer outreach, credit limit adjustment, or targeted support—improving both financial outcomes and customer relationships.

### 🚀 How Users Can Get Started with the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/credit-card-default-prediction.git
   cd credit-card-default-prediction
   ```
2. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook CreditCard.ipynb
   ```
3. **Run the notebook** to explore data preprocessing, model training, evaluation, and results.

### ❓ Where Users Can Get Help with the Project
If you encounter any issues or have questions:
- Open an issue on the [GitHub Issues page](https://github.com/your-username/credit-card-default-prediction/issues)
- Contact the project maintainer (see below)

### 👥 Who Maintains and Contributes to the Project
This project was developed by Nikita Singh 

---

## 🎯 Project Objective

> To construct a predictive model that accurately forecasts the likelihood of a credit card account defaulting in the subsequent month.

Defaulting refers to a customer’s failure to meet the minimum payment requirement.

---

## 🧠 Key Challenges

- Handling imbalanced datasets
- Encoding categorical variables
- Reducing data redundancy
- Streamlining missing or duplicate records

---

## 🛠️ Models Explored

| Model                | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| Decision Tree        | Easy to interpret, splits data based on feature conditions                 |
| Neural Networks      | Inspired by brain neurons, uses backpropagation for training               |
| Random Forest        | Combines multiple decision trees for improved generalization               |
| Support Vector Machine (SVM) | Finds optimal hyperplane separating classes                         |
| Bagging              | Reduces variance by random sampling and ensemble voting                    |
| Boosting (**Best Model**) | Focuses on misclassified cases in iterations, delivers highest accuracy |

✅ **Best Performing Model:** Boosting  
🎯 **Achieved Accuracy:** 83%  
📈 **Improved Over Baseline (Decision Tree):** +5.18%

---

## 📊 Data Summary

- **Source:** UCI Machine Learning Repository (Modified)
- **Rows:** 30,000 unique credit account holders
- **Columns:** 25 features including demographics, payment history, and balance data
- **Target:** Whether the customer defaulted in the next month (binary classification)

---

## 🧰 Technologies Used

| Tool/Library       | Purpose                             |
|--------------------|-------------------------------------|
| Python             | Primary programming language        |
| Pandas & NumPy     | Data manipulation and exploration   |
| Scikit-learn       | ML models and performance metrics   |
| Matplotlib/Seaborn | Data visualization                  |
| Jupyter Notebook   | Code development and documentation  |

---

## 📈 Implementation Strategy

- Train-test split for model evaluation
- Model tuning and optimization via hyperparameter tuning
- Online model deployment simulated through REST API endpoint setup
- Continuous monitoring and team training recommendations

---

## 💡 Key Findings

- Boosting outperformed all other models in terms of predictive accuracy.
- Strategic model deployment via REST APIs enables real-time default risk scoring.
- A data-driven approach improves campaign targeting and reduces financial risk.

---

## 🧠 Learnings

- Hands-on experience with supervised learning for classification
- Tackled real-world class imbalance and feature engineering issues
- Understood deployment strategies and business integration concerns

---

## 🛠 How to Run the Code

```bash
# Clone the repository
git clone https://github.com/your-username/credit-card-default-prediction.git
cd credit-card-default-prediction

# Open the Jupyter Notebook
jupyter notebook CreditCard.ipynb
```

---

## 📄 License

This project is for learning purposes and is not licensed for commercial use.

---

## 📬 Contact

For queries or collaboration opportunities:

**Nikita Singh**  
Email: mail2nikita95@gmail.com  
LinkedIn: [linkedin.com/in/nikitasingh3](https://linkedin.com/in/nikitasingh3)
