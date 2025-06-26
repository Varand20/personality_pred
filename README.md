# Prediksi Tipe Kepribadian Menggunakan Machine Learning

Proyek ini bertujuan untuk memprediksi tipe kepribadian seseorang berdasarkan perilaku sosialnya menggunakan algoritma machine learning. Model-model yang digunakan dilatih pada dataset yang berisi informasi seperti waktu menyendiri, frekuensi menghadiri acara sosial, ukuran lingkaran pertemanan, dan lainnya.

## 📁 Dataset

Dataset yang digunakan: `personality_datasert.csv`, dengan fitur-fitur sebagai berikut:

- **Time_spent_Alone**: Waktu yang dihabiskan sendirian
- **Social_event_attendance**: Frekuensi menghadiri acara sosial
- **Going_outside**: Seberapa sering keluar rumah
- **Friends_circle_size**: Ukuran lingkaran pertemanan
- **Post_frequency**: Frekuensi memposting di media sosial
- **Stage_fear**: Apakah memiliki ketakutan tampil di depan umum
- **Drained_after_socializing**: Apakah merasa lelah setelah bersosialisasi
- **Personality**: Label target (tipe kepribadian)

## 🧪 Metodologi

- **Preprocessing:**
  - Penanganan missing value dan outlier
  - Encoding kolom kategorikal
  - SMOTE untuk menangani data tidak seimbang
  - Feature engineering: rasio, fitur baru, dan polynomial features

- **Model yang Digunakan:**
  - Decision Tree
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - **Stacking Classifier** (gabungan DT + SVM + KNN dengan Logistic Regression sebagai meta-learner)


