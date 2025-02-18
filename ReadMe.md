# Bank Transaction Fraud Detection using Isolation Forest

This project focuses on detecting fraudulent bank transactions using the Isolation Forest algorithm, an unsupervised machine learning method suitable for anomaly detection.

---

## **Project Overview**
With the increase in digital transactions, detecting fraudulent activities is crucial. This project applies Isolation Forest to detect anomalies in bank transactions, enhancing financial security.

---

## **Dataset**
- **Source**: Synthetic dataset simulating bank transactions.
- **Features**:
  - **Numerical**: TransactionAmount, CustomerAge, TransactionDuration, LoginAttempts, AccountBalance, TransactionFrequency, TransactionHour, TransactionDay, TransactionMonth, TransactionTimeDiff.
  - **Categorical**: TransactionType, Location, Channel, CustomerOccupation (one-hot encoded).

---

## **Technologies Used**
- **Python**: Data processing, modeling, and evaluation.
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
- **Version Control**: Git, GitHub.

---

## **Key Steps**
1. **Data Preprocessing**:
   - Handled missing values, scaled numerical data, and one-hot encoded categorical features.
2. **Exploratory Data Analysis (EDA)**:
   - Visualized transaction amounts, frequencies, and time-based patterns.
3. **Modeling with Isolation Forest**:
   - Tuned hyperparameters using GridSearchCV.
4. **Evaluation**:
   - Assessed model performance using Precision, Recall, F1-score, and ROC-AUC.
5. **Cross-validation**:
   - Ensured model robustness across different data splits.

---

## **Project Structure**
- `project_2.ipynb`: Jupyter Notebook with the full project code.
- `bank_transactions_data.csv`: Dataset used for training and evaluation.

---

## **Future Enhancements**
- Implement additional anomaly detection methods (One-Class SVM, Local Outlier Factor).
- Incorporate domain-specific features.
- Optimize hyperparameters with advanced techniques like Random Search or Bayesian Optimization.
- Enhance model interpretability with SHAP values.

---

## **Contributing**
Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.

---

## **License**
This project is licensed under the MIT License.

---

## **Contact**
Krishna-141  
[GitHub Repository](https://github.com/Krishna-141/Bank_fraud_using_isolation_forest)  
Feel free to reach out for collaboration or queries.

