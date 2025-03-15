# 💳 Credit Risk Prediction Using Machine Learning  

## 📌 Project Overview  
Credit risk assessment is a critical task in the financial sector. Incorrectly classifying borrowers can lead to **financial losses for lenders** or **unfair loan denials for applicants**. This project applies **machine learning techniques** to predict whether a borrower will **default on a loan** based on **financial, demographic, and credit history data**.

The model helps **banks and financial institutions** make data-driven lending decisions, minimizing risk while ensuring fair credit distribution.

---

## 📊 Dataset Overview  
- **Total Records**: 100,000  
- **Total Features**: 21 (20 independent variables + 1 target variable)  
- **Target Variable**:  
  - `0` → Loan was **repaid successfully** (No Default).  
  - `1` → Borrower **failed to repay the loan** (Default).  
- **Dataset is balanced**, with an equal distribution of default and non-default cases.  

---

## 🏗️ **Project Workflow & Methodology**  

### **1️⃣ Data Preprocessing & Feature Engineering**  
✅ **Handling missing values** using imputation.  
✅ **Feature scaling & encoding categorical variables** (One-Hot Encoding & Label Encoding).  
✅ **Creating new derived features** (e.g., Debt-to-Income ratio impact).  
✅ **Correlation analysis to remove redundant features.**  

### **2️⃣ Model Selection & Training**  
✅ **Baseline models:** Logistic Regression, Decision Tree.  
✅ **Advanced models:** Random Forest, XGBoost, LightGBM, CatBoost.  
✅ **Hyperparameter tuning** using GridSearchCV for optimal performance.  

### **3️⃣ Model Evaluation & Performance Metrics**  
✅ **Metrics Used:**  
   - **Accuracy**: Overall correctness of predictions.  
   - **Precision**: Fraction of positive predictions that are actually correct.  
   - **Recall (Sensitivity)**: Ability to detect all actual defaulters.  
   - **F1-Score**: Balance between precision & recall.  
   - **ROC-AUC Score**: Ability to distinguish between defaulters and non-defaulters.  

### **4️⃣ Feature Selection & Dimensionality Reduction**  
✅ **Principal Component Analysis (PCA)** to reduce data dimensionality.  
✅ **Recursive Feature Elimination (RFE)** to keep only the most predictive variables.  

---

## ⚙️ **Technologies & Tools Used**  
- **Python** (Programming Language)  
- **Pandas, NumPy** (Data Processing)  
- **Matplotlib, Seaborn** (Data Visualization)  
- **Scikit-Learn** (Machine Learning Models)  
- **XGBoost, LightGBM, CatBoost** (Advanced ML Models)  
- **GridSearchCV, PCA** (Hyperparameter Tuning & Feature Selection)  

---

## 🚀 **Installation & Setup**  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/Credit-Risk-Prediction.git
   cd Credit-Risk-Prediction
   ```
2. **Install dependencies**:
  ```bash
   pip install -r requirements.txt
  ```
3. **Run the model**:
   ```bash
   python credit_risk_prediction.py
   ```

## 🎯 Business Use Cases:
📌 Loan Approval Automation → Predict borrower risk and automate approval decisions.
📌 Credit Scoring Models → Improve existing credit scoring systems with ML predictions.
📌 Risk-Based Interest Rate Adjustments → Charge higher interest rates for high-risk borrowers.
📌 Customer Segmentation → Group borrowers into risk categories for personalized financial products.

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request if you have improvements or new features.

## 📜 License
This project is licensed under the MIT License.

## 📩 Contact & Support
📧 Email: vishal1594@outlook.com
🔗 LinkedIn: https://www.linkedin.com/in/vishal-shivnani-87487110a/
