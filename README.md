# Final Project: Diabetes Classification

## Deskripsi
Proyek ini bertujuan memprediksi apakah seseorang berisiko terkena diabetes menggunakan dataset indikator kesehatan dari BRFSS 2015.

## Dataset
- Sumber: [Kaggle](https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset)
- Ukuran: 253.680 data
- Target: `Diabetes_binary` (0 = Tidak diabetes, 1 = Diabetes)

## Teknologi yang Digunakan
- Python 3.11
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, imbalanced-learn

## Alur Analisis
1. **Load dan bersihkan data**
2. **Seleksi fitur terbaik (Top 15)**
3. **Standardisasi data**
4. **Split data train-test (80:20)**
5. **Balancing data dengan SMOTE**
6. **Melatih 3 model:**
   - Logistic Regression
   - Random Forest
   - XGBoost (Best model)

## Hasil Akhir

| Model               | Akurasi |
|---------------------|---------|
| Logistic Regression | ~71.5%  |
| Random Forest       | ~82.5%  |
| XGBoost             | ~85.1%  | memenuhi syarat salah satu >= 85%

## Visualisasi
- Distribusi target
- Correlation heatmap
- Confusion matrix

## Video Penjelasan
(sertakan link YouTube jika sudah diunggah)
