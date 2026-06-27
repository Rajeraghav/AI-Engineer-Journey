# Loan Approval Prediction

## Objective

The objective of this project is to build a Machine Learning model that predicts whether a loan application will be **Approved** or **Rejected** based on the applicant's demographic and financial information.

---

## Dataset

**Dataset:** Loan Approval Prediction Dataset

The dataset contains **614 loan applications** with various applicant details and loan information.

### Features

* Loan_ID
* Gender
* Married
* Dependents
* Education
* Self_Employed
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Credit_History
* Property_Area

### Target Variable

* Loan_Status

  * **Y** – Loan Approved
  * **N** – Loan Rejected

---

## Machine Learning Algorithms Used

* Logistic Regression
* Random Forest Classifier

---

## Python Libraries

* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

---

## Project Workflow

### Step 1: Upload Dataset

* Upload the Loan Approval Prediction dataset using Google Colab.

### Step 2: Data Exploration

* Display the first five records
* Check dataset dimensions
* View dataset information
* Identify missing values
* Generate statistical summary

### Step 3: Data Preprocessing

* Handle missing values using:

  * Mode (Categorical Features)
  * Median (Numerical Features)
* Remove unnecessary columns (Loan_ID)
* Convert categorical values into numerical values using Label Encoding

### Step 4: Feature Scaling

* Standardize the feature values using StandardScaler.

### Step 5: Train-Test Split

* Split the dataset into:

  * 80% Training Data
  * 20% Testing Data

### Step 6: Model Training

Train two classification models:

* Logistic Regression
* Random Forest Classifier

### Step 7: Model Evaluation

Evaluate the models using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### Step 8: Model Comparison

Compare the performance of Logistic Regression and Random Forest using a bar chart.

### Step 9: Feature Importance

Identify the most influential features affecting loan approval using the Random Forest model.

### Step 10: Save Predictions

Save the prediction results to:

```
Loan_Approval_Output.csv
```

---

## Results

### Logistic Regression Accuracy

Approximately **78.86%**

### Random Forest Accuracy

Approximately **75.61%**

### Best Performing Model

Logistic Regression performed slightly better than Random Forest on this dataset.

---

## Visualizations

The project generates the following visualizations:

* Model Accuracy Comparison
* Random Forest Confusion Matrix
* Feature Importance Chart

---

## Skills Demonstrated

* Data Exploration
* Data Cleaning
* Missing Value Handling
* Label Encoding
* Feature Scaling
* Classification
* Logistic Regression
* Random Forest
* Model Evaluation
* Feature Importance Analysis
* Data Visualization

---

## Output Files

```
Loan_Approval_Output.csv
```

Contains:

* Actual Loan Status
* Predicted Loan Status

---

## Project Structure

```
Day05
├── Loan_Approval_Prediction.ipynb
├── Loan-Approval-Prediction.csv
├── Loan_Approval_Output.csv
└── README.md
```

---

## Future Improvements

* Hyperparameter Tuning using GridSearchCV
* Cross Validation
* ROC Curve Analysis
* Precision-Recall Curve
* Streamlit Deployment
* Loan Approval Prediction Web Application

---


