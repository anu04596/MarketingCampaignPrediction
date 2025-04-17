# 📈 Marketing Campaign Prediction

A machine learning project that predicts whether a customer will subscribe to a term deposit using the Bank Marketing Dataset. This classification task is based on client and campaign attributes collected during direct marketing campaigns.

## 🗂️ Dataset Overview

The dataset includes various customer-related attributes such as:

| Feature     | Description                              |
|-------------|------------------------------------------|
| age         | Age of the client                        |
| job         | Type of job (admin., technician, etc.)   |
| marital     | Marital status                           |
| education   | Education level                          |
| default     | Has credit in default?                   |
| balance     | Average yearly balance (numeric)         |
| housing     | Has housing loan?                        |
| loan        | Has personal loan?                       |
| contact     | Contact communication type               |
| day         | Last contact day of the month            |
| month       | Last contact month of year               |
| duration    | Last contact duration (seconds)          |
| campaign    | Number of contacts during this campaign  |
| pdays       | Days since client was last contacted     |
| previous    | Number of contacts before this campaign  |
| poutcome    | Outcome of previous marketing campaign   |
| deposit     | Target variable (yes/no)                 |

🔎 **Target Variable**: `deposit` — whether the client subscribed to a term deposit.

---

## 📌 Project Goals
- Clean and preprocess data
- Train and evaluate multiple classification models
- Compare Logistic Regression and Decision Tree classifiers
- Select the best-performing model based on evaluation metrics

---

## 🧪 Models Used & Results

### ✅ Logistic Regression
- Accuracy: `74.87%`
- Precision: `74.90%`
- Recall: `71.32%`
- F1 Score: `73.07%`

### 🌳 Decision Tree Classifier
- Accuracy: `77.16%`
- Precision: `76.65%`
- Recall: `75.07%`

> Decision Tree outperformed Logistic Regression based on accuracy, precision, and recall.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn (for visualizations)
- Google Colab

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/marketing-campaign-prediction.git
   cd marketing-campaign-prediction
