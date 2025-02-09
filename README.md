## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🚀 Fraud Detection Using Machine Learning 🛡️
📌 Project Overview
Fraudulent transactions pose a major risk to financial institutions and individuals. This project applies machine learning algorithms to detect and prevent fraudulent transactions efficiently.

🔍 Key Focus Areas:

🔄 Detecting fraudulent transactions with high precision
📊 Handling class imbalance using SMOTE
🏗 Feature engineering & correlation analysis
🎯 Hyperparameter tuning for performance optimization

🛠 Installation
Ensure you have Python 3.8+ and install dependencies:
 numpy
 scikitlearn
 sns seaborn
 pandas
 matplotlib
 
💾 Dataset
📂 Source: Financial Transactions Dataset (Replace with actual source)
📌 Key Features:

🏦 Transaction Type (Cash In, Cash Out, Transfer, etc.)
💰 Transaction Amount
👤 Sender & Receiver Details
⚠️ Fraud Indicator (0 = Legitimate ✅, 1 = Fraud ❌)
🧠 Machine Learning Pipeline

1️⃣ Data Preprocessing:

Handling missing values, encoding categorical features (One-Hot Encoding)
Removing multicollinearity using P-values & correlation matrix

2️⃣ Feature Engineering:

Selecting important features using statistical tests
Normalizing numerical values with StandardScaler

3️⃣ Handling Imbalanced Data:

SMOTE applied to oversample fraud cases ❌

4️⃣ Model Training & Evaluation:

Baseline models: Logistic Regression, Random Forest, XGBoost, KNN
Performance metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

5️⃣ Hyperparameter Tuning:

GridSearchCV & Bayesian Optimization for fine-tuning
🎯 Results & Performance
📊 XGBoost Model Performance:

Metric	Score
Accuracy	99.97%
Precision	99.70%
Recall	99.32%
F1-score	99.50%
AUC-ROC	99.98%
📌 Key Takeaways:
✅ High precision minimizes false fraud detections
✅ High recall ensures fraudulent transactions are effectively caught ❌
✅ Tuned hyperparameters significantly boost performance
