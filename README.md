# 📊 Telecom Customer Segmentation & Churn Analysis Prediction

A Python-based data analysis and machine learning project that analyzes telecom customer behavior, identifies important churn patterns, segments customers based on their characteristics, and predicts whether a customer is likely to churn.

The project combines **Exploratory Data Analysis (EDA), Customer Segmentation, Data Preprocessing, Logistic Regression, Random Forest, and Model Evaluation** to generate both technical and business insights.

---

## 🎯 Project Objective

Customer churn is an important challenge for telecom companies because losing existing customers can directly affect revenue.

The main objectives of this project are:

* Analyze telecom customer behavior and characteristics.
* Identify factors associated with customer churn.
* Perform customer segmentation based on customer attributes.
* Prepare and preprocess data for machine learning.
* Build churn prediction models.
* Compare **Logistic Regression** and **Random Forest**.
* Evaluate model performance using appropriate classification metrics.
* Generate actionable business insights for customer retention.

---

## 🛠️ Technologies & Tools

* **Python**
* **Jupyter Notebook**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning
* **Excel/CSV** – Dataset

---

## 📂 Project Structure

```text
Telecom Customer Churn Analysis & Prediction/
│
├── data/
│   └── telecom_customer_churn.csv
│
├── notebooks/
│   └── Telecom_Customer_Churn_Analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis (EDA)
   ↓
Customer Segmentation
   ↓
Feature Selection
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Logistic Regression
   ↓
Random Forest
   ↓
Model Evaluation & Comparison
   ↓
Business Insights
```

---

## 📌 Dataset

The dataset contains information about telecom customers, including demographic details, services used, contract information, tenure, charges, and churn-related information.

### Important Features

Some important features include:

* Customer ID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure Months
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* CLTV
* Churn

> Outcome-related fields such as Churn Label, Churn Value, or Churn Score are not used as input features for the prediction model to avoid data leakage.

---

# 🔍 Exploratory Data Analysis

EDA is performed to understand customer characteristics and identify patterns related to churn.

The analysis includes:

* Churn distribution
* Customer tenure analysis
* Monthly charges analysis
* Contract type vs churn
* Internet service vs churn
* Payment method vs churn
* Tech support and online security vs churn
* Customer demographics
* Service usage patterns
* Correlation analysis

Visualizations are created using **Matplotlib and Seaborn**.

---

# 👥 Customer Segmentation

Customer segmentation is used to group customers based on similar characteristics and behavior.

The analysis can help identify groups such as:

* High-value customers
* Long-term customers
* New customers
* High monthly-charge customers
* Customers with multiple services
* Customers showing higher churn tendencies

The purpose of segmentation is to understand different customer groups and their behavior rather than treating all customers the same.

---

# 🤖 Machine Learning

Two classification algorithms are implemented:

## 1. Logistic Regression

Logistic Regression is used as a simple and interpretable baseline classification model for predicting whether a customer will churn.

It helps understand how different customer features contribute to the probability of churn.

## 2. Random Forest

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to make predictions.

It is useful for capturing more complex relationships between customer characteristics and churn.

---

# ⚙️ Machine Learning Pipeline

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Handling Missing Values
     ↓
Encoding Categorical Features
     ↓
Feature Selection
     ↓
Train-Test Split
     ↓
Model Training
     ↓
Prediction
     ↓
Model Evaluation
```

---

# 📈 Model Evaluation

The models are evaluated using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The models are compared to understand their performance for customer churn prediction.

---

# 💡 Business Insights

The analysis is intended to help telecom companies understand:

* Which customer groups are more likely to churn.
* How contract type affects customer retention.
* Whether higher monthly charges are associated with churn.
* How tenure relates to customer retention.
* Which services are associated with different churn patterns.
* Which customer segments may require targeted retention strategies.

These insights can support data-driven customer retention decisions.

---

# ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the project

```bash
cd "Telecom Customer Churn Analysis & Prediction"
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Navigate to:

```text
notebooks/Telecom_Customer_Churn_Analysis.ipynb
```

Run the notebook cells sequentially.

---

# 📦 Requirements

Example `requirements.txt`:

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
openpyxl
jupyter
```

---

# 📊 Expected Outcome

The project provides:

* Detailed customer churn analysis
* Customer segmentation
* Data visualizations
* Churn prediction models
* Logistic Regression vs Random Forest comparison
* Model evaluation
* Business-oriented customer retention insights

---

# 🚀 Future Improvements

Possible future enhancements include:

* Hyperparameter tuning
* Cross-validation
* Feature importance analysis
* Interactive dashboard using Power BI or Streamlit
* Advanced customer segmentation
* Deployment of the churn prediction model
* Automated customer retention recommendations

---

## 👨‍💻 Author

**Shuvam Saha**

BCA Student
Institute of Engineering and Management (IEM)

---

## ⭐ Project Focus

**Data Analysis | Customer Segmentation | Machine Learning | Churn Prediction | Business Insights**
