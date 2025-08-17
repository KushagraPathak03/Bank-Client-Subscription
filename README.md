# 🏦 Task 3 - Bank Client Subscription Prediction Model | Data Science Intership @ Prodigy InfoTech
This project is part of Task 3 of my Data Science Internship.
In this project the Bank Marketing Dataset is used to predict whether a customer will subscribe to a bank product/service (Yes/No) based on their demographic and behavioral data.
Implemented a Decision Tree Classifier to analyze customer attributes such as age, job, marital status, balance, housing loan, previous campaign outcomes, and more.


# 🎯 Objective
1. To predict the likelihood of a customer subscribing to a bank product/service.
2. To analyze important features that influence customer decisions.
3. To handle imbalanced data using techniques like SMOTE.


# 📂 Dataset
Source: https://www.kaggle.com/datasets/adityamhaske/bank-marketing-dataset
- Features:
   Demographic: `age`, `job`, `marital`, `education`
   Financial: `balance`, `housing`, `loan`
   Campaign-related: `contact`, `day`, `month`, `duration`, `campaign`, `pdays`, `previous`, `poutcome`
Target: `y` → Whether the client subscribed (yes/no)


# 🛠️ Tools & Technologies
- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning (Decision Tree, Train-Test Split, Evaluation, Cross-Validation)
- **Imbalanced-learn** – SMOTE (Synthetic Minority Over-sampling Technique)


# ⚙️ Workflow
### 1. Data Preprocessing
- Handle missing values
- Convert categorical features using One-Hot Encoding
- Handle data imbalance (SMOTE / class weights)

### 2. Model Building
- Train-Test Split (80/20)
- Decision Tree Classifier
- Hyperparameter tuning (max_depth, min_samples_split)

### 3. Model Evaluation
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score
- Cross Validation

### 4. Visualization
- Decision Tree structure using plot_tree()
- Feature importance ranking


# 📈 Results
- Achieved ~85% accuracy using Decision Tree Classifier  
- Visualized the decision tree for interpretability
- Improved results using SMOTE
- Applied Cross-Validation (k-fold) for robust model performance
- Evaluated with Confusion Matrix & Classification Report
