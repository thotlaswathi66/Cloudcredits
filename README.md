# Customer Churn Prediction

## 📌 Project Description

This project predicts whether a customer is likely to leave (churn) or stay with a telecom company using Machine Learning. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and feature importance analysis.

---

## 📂 Dataset

- **Dataset:** Telco Customer Churn Dataset
- **Rows:** 7043
- **Columns:** 21
- **Target Variable:** Churn

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Project Workflow

1. Load the dataset
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature encoding
5. Train-test split
6. Train Machine Learning models
7. Compare model accuracy
8. Feature importance analysis
9. Save the trained model

---

## 🤖 Machine Learning Models

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 78.75% |
| Decision Tree | 72.49% |
| Random Forest | 78.54% |

**Best Performing Model:** Logistic Regression

---

## ⭐ Important Features

The most important features influencing customer churn are:

- TotalCharges
- MonthlyCharges
- Tenure
- InternetService (Fiber Optic)
- Electronic Check Payment
- Online Security
- Two-Year Contract

---

## 📈 Project Visualizations

### Customer Tenure Distribution

![Customer Tenure](images/Customer_tesnure_Distribution.png)

### Monthly Charges Distribution

![Monthly Charges](images/Monthly_charges_Distribution.png)

### Internet Service Distribution

![Internet Service](images/Internet_Service.png)

### Contract Type

![Contract Type](images/contract_type.png)

### Contract vs Churn

![Contract vs Churn](images/Contract_VS_Churn.png)

### Model Accuracy Comparison

![Accuracy Comparison](images/model_Accuracy_Comparision.png)

### Feature Importance

![Feature Importance](images/Important_Features.png)

---

## 📁 Project Structure

```
Customer-Churn-Predictor/
│
├── dataset/
├── images/
├── models/
├── Customer_Churn.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ How to Run

1. Clone the repository

```
git clone https://github.com/thotlaswathi66/Cloudcredits.git
```

2. Navigate to the project

```
cd Cloudcredits/Customer-Churn-Predictor
```

3. Install dependencies

```
pip install -r requirements.txt
```

4. Open the notebook

```
jupyter notebook Customer_Churn.ipynb
```

---

## 📌 Results

- Successfully analyzed customer churn patterns.
- Compared multiple Machine Learning models.
- Achieved **78.75%** accuracy using Logistic Regression.
- Identified the most important factors affecting customer churn.

---

## 👩‍💻 Author

**Swathi**

GitHub: https://github.com/thotlaswathi66
