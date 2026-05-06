# 🏦 Loan Approval Predictor (ML)

A Machine Learning-based classification system designed to predict the risk associated with loan applications. This project focuses on handling highly imbalanced financial data to identify potential defaulters.

## 🚀 Project Overview
In the banking sector, identifying risky customers is crucial. This model analyzes customer demographics (Income, Age, Experience, Profession, etc.) to predict a `Risk_Flag`.

### 🛠️ Tech Stack
* **Language:** Python
* **Data Handling:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Sampling:** Imbalanced-learn (RandomUnderSampler)

## 📊 Key Implementation Details
1. **Data Preprocessing:** Handled categorical variables like City, State, and Profession using `pd.get_dummies` (One-Hot Encoding).
2. **Class Imbalance:** Since the dataset was skewed towards non-defaulters, I implemented **Random Under-Sampling** to balance the classes and prevent model bias.
3. **Model:** Implemented **Logistic Regression** as a baseline classifier.

## 📈 Results
* **Current Accuracy:** 53.71%
* **Focus:** Optimized for a balanced representation of both risk and non-risk classes.

## 📝 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas scikit-learn imblearn matplotlib seaborn`.
3. Run the `LoanApprovalPredictor.ipynb` notebook.
