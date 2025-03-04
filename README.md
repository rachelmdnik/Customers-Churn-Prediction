# Customers-Churn-Prediction
Pada proyek ini, dilakukan analisis churn untuk memahami faktor-faktor yang menyebabkan pelanggan tidak kembali melakukan transaksi setelah diakuisisi melalui promo oleh tim Marketing. Proses ini mencakup Exploratory Data Analysis (EDA), pembuatan model prediksi churn, serta interpretasi hasil model.
# 🛍️ Fashion Campus - Churn Prediction

## 📌 Overview
Fashion Campus adalah perusahaan fashion e-commerce yang menyasar *Indonesian Young Urbans* (15-35 tahun). Seiring dengan meningkatnya jumlah user, banyak pelanggan yang diakuisisi hanya karena promo tetapi tidak kembali melakukan transaksi (*churn*). Proyek ini bertujuan untuk menganalisis faktor-faktor yang menyebabkan churn dan membangun model prediksi churn untuk membantu tim Marketing merancang strategi retensi yang lebih efektif.

## 📂 Dataset
Dataset terdiri dari beberapa fitur utama:
- **Demografi Pengguna**: Usia, lokasi, dll.
- **Behavior Pengguna**: Jumlah transaksi, total pengeluaran, frekuensi pembelian.
- **Marketing Engagement**: Partisipasi dalam promo, kanal akuisisi.

**Definisi churn:** Pelanggan yang tidak melakukan transaksi dalam periode tertentu setelah akuisisi.

## 🔍 Exploratory Data Analysis (EDA)
- Analisis distribusi user churn vs non-churn.
- Hubungan antara jumlah transaksi, pengeluaran total, dan churn rate.
- Pengaruh jenis promo terhadap retensi pelanggan.
- Visualisasi data menggunakan histogram, boxplot, dan heatmap korelasi.

## 🛠 Data Preprocessing
1. **Handling Missing Values** – Menghapus atau mengimputasi data yang hilang.
2. **Encoding Kategori** – Mengubah variabel kategorikal menjadi numerik.
3. **Feature Scaling** – Normalisasi atau standarisasi fitur numerik.
4. **Feature Engineering** – Membuat variabel baru seperti rata-rata pembelian per bulan, durasi sejak pembelian terakhir, dll.

## 🤖 Model Development
1. **Splitting Data** – Memisahkan dataset menjadi *training* dan *testing set*.
2. **Pemilihan Model**:
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
   - Neural Network (opsional)
3. **Evaluasi Model**:
   - Accuracy, Precision, Recall, F1-score, AUC-ROC.
4. **Hyperparameter Tuning** – Menggunakan GridSearchCV atau RandomizedSearchCV untuk optimasi.

## 📊 Hasil & Insights
- Fitur yang paling berpengaruh terhadap churn.
- Rekomendasi untuk strategi retensi pelanggan:
  - Menargetkan kembali pelanggan berdasarkan pola pembelian mereka.
  - Mengoptimalkan promo agar lebih efektif meningkatkan retensi pelanggan.
  - Implementasi program loyalitas untuk meningkatkan engagement.
