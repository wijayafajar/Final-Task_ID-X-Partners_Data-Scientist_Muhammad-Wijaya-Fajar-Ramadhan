# [Final Task] Prediction Model
### Data Scientist Virtual Internship — ID/X Partners × Rakamin Academy

##  Deskripsi Proyek

Proyek ini merupakan **Final Task (Task 5)** dari program Project-Based Virtual Internship Data Scientist bersama **ID/X Partners** dan **Rakamin Academy**.

Sebagai Data Scientist, saya dilibatkan dalam proyek dari sebuah perusahaan *multifinance* yang ingin meningkatkan keakuratan dalam menilai dan mengelola **risiko kredit**. Solusi yang dibangun berupa model *machine learning* yang mampu memprediksi apakah seorang peminjam termasuk kategori **credit risk GOOD atau BAD**, berdasarkan dataset pinjaman yang disetujui maupun ditolak.


## Tujuan

- Membangun model prediksi credit risk menggunakan pendekatan *supervised learning*
- Mengikuti framework Data Science secara end-to-end
- Membandingkan performa minimal 2 algoritma machine learning
- Menyajikan hasil analisis dalam bentuk infografis yang komunikatif

## Tahapan Pengerjaan

### 1. Data Understanding
- Analisis struktur dataset (jumlah baris & kolom)
- Identifikasi setiap atribut berdasarkan Data Dictionary
- Eksplorasi awal distribusi variabel dan statistik deskriptif

### 2. Exploratory Data Analysis (EDA)
- Visualisasi data menggunakan grafik dan plot
- Analisis korelasi antar fitur
- Analisis univariat dan bivariat

### 3. Data Preparation
- Penanganan *missing values* (drop / imputasi)
- Penanganan *outlier*
- Encoding variabel kategorikal
- Scaling / normalisasi fitur numerik
- Split data → train set & test set

### 4. Data Modelling
- **Logistic Regression** *(wajib)*
- Algoritma ke-2, misal: Random Forest / XGBoost / Decision Tree
- Tuning parameter dengan cross-validation / grid search
- Pengecekan overfitting / underfitting

### 5. Evaluation
- Metrik: Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Perbandingan performa antar model
- Ringkasan hasil evaluasi

##  Dataset

1. | [Loan Dataset (CSV)](https://rakamin-lms.s3.ap-southeast-1.amazonaws.com/vix-assets/idx-partners/loan_data_2007_2014.csv) | Data pinjaman 2007–2014 |
2. | [Data Dictionary (XLSX)](https://docs.google.com/spreadsheets/d/1iT1JNOBwU4l616_rnJpo0iny7blZvNBs/edit) | Penjelasan setiap kolom dataset |

##  Format Submission

-  File Code (`.py`)
-  Python Notebook (`.ipynb`)
-  File Infografis (media presentasi)
-  File Final Submission PPT: `Final Task_ID/X Partners_Data Scientist_<Nama Lengkap>`
