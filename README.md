**Credit Card Fraud Detection**

📌 **Project Overview**

The project aims to detect fraudulent credit card transactions using Machine Learning techniques. The model analyzes transaction patterns and classifies them, helping prevent financial fraud.

🛠 **Technologies Used**

Python

Pandas & NumPy (Data Processing)

Scikit-learn (Machine Learning Algorithms)

Matplotlib & Seaborn (Data Visualization)

📂 **Dataset**

The dataset contains anonymized transaction data, including features like transaction amount, time, and anonymized variables.

The target variable indicates whether a transaction is fraudulent (1) or non-fraudulent (0).

🚀 **Implementation Steps**

Data Preprocessing

Handle missing values

Normalize transaction amounts

Address class imbalance using SMOTE (Synthetic Minority Over-sampling Technique)

Exploratory Data Analysis (EDA)

Visualize fraud vs. non-fraud transactions

Identify correlations between features

Model Selection & Training

Train multiple models like Logistic Regression, Decision Trees, Random Forest, and XGBoost

Tune hyperparameters for better accuracy

Evaluation & Results

Assess performance using Confusion Matrix, Accuracy, Precision, Recall, and F1-Score

Compare models to choose the best one

💡 **How to Use**

**Install Dependencies:** 

pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn

**Run the Script:** 

python fraud_detection.py

Evaluate Model Performance

The script will output fraud detection accuracy and confusion matrix.
