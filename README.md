# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn prediction is one of the most important applications of Machine Learning in business. This project aims to predict whether a customer is likely to leave a telecom service based on various customer attributes.

By identifying customers who are likely to churn, companies can take proactive measures to improve customer retention and reduce revenue loss.

This project was developed as **Task 1** for the **Artificial Intelligence Internship at Alfido Tech**.

---

## Objective

The objective of this project is to build a machine learning classification model capable of predicting customer churn using customer demographic and service-related information.

---

## Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming Services
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status (Target Variable)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Project Workflow

### 1. Data Loading
- Imported the dataset
- Examined data structure and data types

### 2. Data Preprocessing
- Removed unnecessary columns
- Handled missing values
- Converted data types
- Encoded categorical variables
- Scaled numerical features

### 3. Exploratory Data Analysis (EDA)
- Churn distribution
- Correlation heatmap
- Count plots
- Distribution plots
- Feature analysis

### 4. Model Building

The following Machine Learning models were implemented:

- Logistic Regression
- Random Forest Classifier

### 5. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Cross Validation
- Confusion Matrix
- ROC Curve

### 6. Feature Importance

Random Forest feature importance was analyzed to identify the most influential factors affecting customer churn.

### 7. Model Saving

The trained model was saved using **Joblib** for future use and deployment.

---

## Results

After comparing multiple machine learning models, the **Random Forest Classifier** provided better overall performance for predicting customer churn.

The project successfully demonstrates the complete Machine Learning workflow from data preprocessing to model evaluation.

---

## Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── customer_churn.csv
├── churn_prediction_model.pkl
├── README.md
└── requirements.txt
```

---

## How to Run

### Clone the repository

```bash
git clone https://github.com/yourusername/Customer-Churn-Prediction.git
```

### Navigate to the project

```bash
cd Customer-Churn-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Customer_Churn_Prediction.ipynb
```

---

##  Future Improvements

- Hyperparameter tuning
- XGBoost implementation
- LightGBM implementation
- Model deployment using Streamlit
- Real-time customer churn prediction dashboard

---

## Author

**Jonty Dheer**

B.Tech Computer Science & Engineering (Artificial Intelligence)

Maharaja Agrasen Institute of Technology (MAIT)

Artificial Intelligence Intern at Alfido Tech

GitHub: https://github.com/jonny2711

LinkedIn: https://www.linkedin.com/in/jonty-dheer-b2027a412

---

## License

This project was developed for educational and internship purposes.