# Customer Churn Prediction (Binary Classification)

## 📌 Project Overview
This project focuses on predicting customer churn using supervised machine learning techniques. Customer churn prediction is a critical business problem, particularly in banking and subscription-based industries, where retaining existing customers is often more cost-effective than acquiring new ones.

The objective of this project is to build, evaluate, and compare multiple classification models to identify customers who are likely to churn and to extract actionable insights that can support retention strategies.

## 🎯 Business Problem
Customer churn directly impacts revenue and long-term business sustainability. By identifying high-risk customers early, companies can:

- Design targeted retention campaigns
- Improve customer experience
- Reduce customer acquisition costs

This project simulates a real-world churn analysis workflow commonly encountered in data science roles.

## 🗂 Dataset
- [Sumber: Dataset Dicoding](https://drive.google.com/uc?id=19IfOP0QmCHccMu8A6B2fCUpFqZwCxuzO)
- Target Variable: Exited (1 = churn, 0 = non-churn)
- Features:
  - Customer demographics (Age, Gender, Geography)
  - Account information (Balance, Credit Score)
  - Product usage behavior (Number of Products, Active Status)
 
## Project Structure
```binary-classification-churn/
├── notebooks/
│   └── 1_churn_classification.ipynb
|   └── 2_churn_classification(Refractored).ipynb
├── src/
│   ├── preprocessing.py
│   ├── modeling.py
│   └── evaluation.py
├── models/
│   └── churn_model.pkl
├── README.md
└── requirements.txt
```

* notebooks/ : Exploratory analysis and narrative workflow
* src/ : Reusable core logic for preprocessing, modeling, and evaluation
* models/ : Trained machine learning model artifacts

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## 🔬 Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing (modularized)
3. Training multiple classification models
4. Evaluasi Model
5. Model evaluation and comparison
6. Best model selection and persistence

## Models Evaluated

The following models were trained and evaluated:
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Random Forest
* Support Vector Machine (SVM)
* Naive Bayes

## 📊 Metrik Evaluasi
Model performance was assessed using:
- Accuracy
- Confusion Matrix
- Precision, Recall, and F1-Score

These metrics were chosen to ensure balanced evaluation beyond accuracy alone.

## ✅ Hasil
| No | Model                       | Accuracy | Precision | Recall   | F1-Score |
|----|-----------------------------|----------|-----------|----------|----------|
| 0  | K-Nearest Neighbors (KNN)   | 0.8240   | 0.595349  | 0.325700 | 0.421053 |
| 1  | Decision Tree (DT)          | 0.7860   | 0.462203  | 0.544529 | 0.500000 |
| 2  | Random Forest (RF)          | 0.8685   | 0.782609  | 0.458015 | 0.577849 |
| 3  | Support Vector Machine (SVM)| 0.8530   | 0.827815  | 0.318066 | 0.459559 |
| 4  | Naive Bayes (NB)            | 0.8285   | 0.681159  | 0.239186 | 0.354049 |



## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
```
## OR

```Python
!git clone https://github.com/your-username/binary-classification-churn.git
%cd binary-classification-churn
```

## Author
Rifqi Ambari
