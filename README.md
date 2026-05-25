Churnlytics – Customer Churn Prediction & Analytics

## Overview

Churnlytics is a machine learning and analytics project focused on predicting customer churn using customer activity, demographic, and subscription payment history data. The project combines data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, and predictive modeling to identify customers who are likely to churn.

The notebook demonstrates an end-to-end workflow for customer churn analysis using Python and Scikit-learn.

---

## Features

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Feature engineering
* Customer segmentation using K-Means clustering
* Dimensionality reduction using PCA
* Multiple ML models for churn prediction:

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * Gradient Boosting
* Model evaluation using:

  * ROC-AUC
  * Precision-Recall Curve
  * Confusion Matrix
  * Classification Report
* Data visualization using Matplotlib

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## Project Structure

```bash
├── Churnlytics.ipynb
├── customer_churn_data.xlsx
├── demographic_data.csv
├── subscription_payment_history.csv
├── output_images/
└── README.md
```

---

## Dataset Information

The project uses three datasets:

1. **Customer Activity Data**

   * Customer engagement and activity information

2. **Demographic Data**

   * Age, gender, location, and other demographic features

3. **Subscription Payment History**

   * Payment trends and subscription-related information

---

## Machine Learning Workflow

### 1. Data Preprocessing

* Handling missing values
* Label encoding categorical variables
* Feature scaling using `StandardScaler`

### 2. Exploratory Data Analysis

* Customer behavior analysis
* Churn distribution visualization
* Correlation analysis

### 3. Customer Segmentation

* K-Means clustering
* PCA for dimensionality reduction and visualization

### 4. Model Training

The following classification models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Gradient Boosting Classifier

### 5. Model Evaluation

Evaluation metrics used:

* Accuracy
* ROC-AUC Score
* Precision-Recall Curve
* Confusion Matrix
* Classification Report

---

## Installation & Setup

### Clone the Repository

```bash
git clone https://github.com/your-username/churnlytics.git
cd churnlytics
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook Churnlytics.ipynb
```

---

## Example Use Cases

* Telecom customer churn prediction
* SaaS customer retention analysis
* Subscription business analytics
* Customer segmentation and targeting

---

## Future Improvements

* Hyperparameter tuning
* Deep learning-based churn prediction
* Deployment using Flask/Streamlit
* Interactive dashboard integration
* Real-time churn prediction API

---

## Results

The project compares multiple machine learning models to identify the most effective approach for customer churn prediction. Visualizations and evaluation metrics help interpret customer behavior and model performance.

