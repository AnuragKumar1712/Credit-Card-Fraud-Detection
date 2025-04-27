# Credit Card Fraud Detection 🚨💳

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning classification techniques.  
A highly accurate **Random Forest Classifier** model was developed and evaluated, and an **advanced Power BI dashboard** was created for intuitive model performance visualization and transaction insights.

---

## Dataset 📂
- **Source:** [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Records:** 284,807 transactions
- **Features:** 30 anonymized numerical variables + `Time`, `Amount`, and `Class` (fraud or not)

---

## Project Steps 🔥
1. **Data Preprocessing**
   - Checked for missing values.
   - Performed train-test split (80%-20%).
   - Maintained class imbalance awareness.
   
2. **Model Building**
   - **Model Used:** Random Forest Classifier
   - **Performance Metrics:**
     - Precision: **96%**
     - Recall: **74%**
     - F1-Score: **84%**
     - AUC Score: **0.9530**
   
3. **Evaluation**
   - Confusion matrix analysis.
   - Classification report for both fraud and non-fraud classes.
   
4. **Power BI Dashboard Development**
   - KPI Cards: Total Transactions, Fraud Transactions, Fraud Percentage, Model Accuracy
   - Visualizations:
     - Transaction Amount Distribution by Class (bar chart)
     - Class Distribution (donut chart)
     - Model Evaluation Metrics (Precision, Recall, F1-Score)
     - Confusion Matrix Table
   - Clean, executive-style layout inspired by modern business dashboards.

---

## Dashboard Preview 📊

![Fraud Detection](https://github.com/user-attachments/assets/7e1fe11f-a21d-4ad5-bb41-c965d8d62306)

---

## How to Run Locally 💻
1. Clone this repository:
   ```bash
   git clone https://github.com/AnuragKumar1712/Credit-Card-Fraud-Detection.git
   ```
2. Open `Jupyter Notebook` to explore the model development (`.ipynb` file).
3. Open the provided `.pbix` file in **Power BI Desktop** to view and customize the dashboard.

---

## Key Insights 💡
- Despite the heavy class imbalance, the Random Forest model achieved **very high accuracy**.
- The fraud detection model maintains a strong **precision-recall balance** — minimizing false positives and false negatives.
- Power BI dashboard makes **model performance** and **transaction trends** easily understandable for business stakeholders.

---

## Tools & Technologies 🛠️
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Power BI (for advanced visualization)
- Jupyter Notebook
- Git and GitHub

---

## Author ✍️
**Anurag Kumar**  
_Data Analyst & Full-Stack Developer_  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/anuragkumar1702/)

---
