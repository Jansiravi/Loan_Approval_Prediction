# 📊 Loan Application Status Prediction (Machine Learning Project)

## 🔍 Project Overview

This project builds a **classification model** to predict loan application outcomes such as **Approved / Rejected / Risk Category** using applicant financial and demographic data.

The focus is on applying a **correct ML workflow** (cleaning → encoding → scaling → modeling → evaluation) and improving performance from baseline to a strong final model.

---

## 🎯 Objectives

* Predict loan approval / risk category
* Apply proper preprocessing techniques
* Handle categorical + numerical features
* Improve model performance with correct pipeline
* Validate model reliability (not just accuracy)

---

## 🧾 Dataset Description

Typical features used:

* Age
* Income
* Credit Score
* Loan Amount
* Employment Status
* Assets
* Other financial indicators

🎯 **Target Variable:** Risk Rating / Loan Status

---

## ⚙️ Methodology (What I Did)

### ✅ 1. Data Cleaning

* Handled missing values
* Removed irrelevant/unnecessary columns
* Fixed incorrect data types

### ✅ 2. Exploratory Data Analysis (EDA)

* Used boxplots to detect outliers
* Checked distributions of numerical features
* Observed relationships between variables

### ✅ 3. Feature Engineering

* Converted categorical columns using `pd.get_dummies()`
* Ensured all features are numeric for model compatibility

### ✅ 4. Train-Test Split

* Split dataset into:

  * 80% Training data
  * 20% Testing data

### ✅ 5. Feature Scaling

* Applied **StandardScaler**
* Done **after train-test split** (important to avoid data leakage)
* Normalized large-value columns (income, assets, etc.)

### ✅ 6. Model Building

Implemented:

* Logistic Regression (baseline model)
* Random Forest Classifier (improved performance)

### ✅ 7. Model Evaluation

Evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 📈 Results

* Initial model accuracy: **0.59**
* Final improved accuracy: **0.93** ✅

📌 Performance improved due to:

* Proper preprocessing
* Correct scaling technique
* Better model selection (Random Forest)

---

## ⚠️ Model Validation (Important)

To ensure results are reliable:

* Avoided **data leakage**
* Applied scaling after split
* Evaluated using multiple metrics (not only accuracy)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 How to Run

1. Install dependencies:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

2. Open Jupyter Notebook:

   ```bash
   jupyter notebook Loan_Application_status.ipynb
   ```

3. Run all cells step by step

---

## 📌 Key Learnings

* End-to-end ML workflow
* Importance of preprocessing
* Handling categorical variables correctly
* Feature scaling impact
* Evaluating models beyond accuracy
* Avoiding common ML mistakes (like data leakage)

---

## 🔮 Future Improvements

* Hyperparameter tuning (GridSearchCV)
* Cross-validation
* Try advanced models (XGBoost, Gradient Boosting)
* Handle class imbalance if present
* Feature importance analysis

---

## 👩‍💻 Author

**Jansi R**

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
