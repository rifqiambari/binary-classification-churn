# Klasifikasi-Biner-Churn / Prediksi Customer yang Berhenti Berlangganan

## 📌 Gambaran Umum Proyek
Proyek ini bertujuan untuk membangun model klasifikasi biner untuk memprediksi apakah pelanggan akan berhenti berlangganan atau tidak berdasarkan data pelanggan yang berhenti (Exited) dan tidak.

## 🎯 Tujuan
- Memahami perilaku pelanggan yang berhenti berlangganan (churn)
- Membangun model klasifikasi Machine Learning
- Mengevaluasi kinerja model menggunakan metrik yang sesuai

## 🗂 Dataset
- [Sumber: Dataset Dicoding](https://drive.google.com/uc?id=19IfOP0QmCHccMu8A6B2fCUpFqZwCxuzO)
- Variabel target: `Churn/Exited`
- Fitur termasuk demografi pelanggan dan perilaku penggunaan

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

## 🔬 Workflow
1. Pembersihan & Pra-pemrosesan Data
2. Analisis Data Eksplorasi (EDA)
3. Pelatihan Model
4. Evaluasi Model

## 📊 Metrik Evaluasi
- Akurasi
- Presisi
- Recall
- Skor F1

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
