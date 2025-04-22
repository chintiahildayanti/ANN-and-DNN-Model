# ANN-and-DNN-Model
# London Bike Sharing prediction using ANN & DNN

## 📌 Objective

Proyek ini bertujuan untuk menganalisis pola penggunaan sepeda di Kota London selama tahun 2015 dan membangun model prediktif yang mampu memperkirakan jumlah peminjaman sepeda berdasarkan faktor cuaca dan waktu.

Secara khusus, tujuan dari proyek ini meliputi:

- Melakukan **Exploratory Data Analysis (EDA)** untuk memahami pola harian, musiman, dan jam penggunaan sepeda.
- Menganalisis pengaruh **variabel cuaca dan waktu** terhadap permintaan sepeda, termasuk tren, musim, dan anomali.
- Melatih dan mengevaluasi model prediksi:
  - Linear Regression (sebagai baseline sederhana)
  - **Artificial Neural Network (ANN)** untuk menangkap hubungan non-linear
  - **Deep Neural Network (DNN)** untuk memodelkan hubungan kompleks
- Membandingkan performa berbagai model dan memilih pendekatan terbaik untuk prediksi jangka pendek.
- Memberikan **insight strategis** berdasarkan hasil analisis dan model.

## 📂 Dataset

Dataset yang digunakan adalah **London Bike Sharing Dataset (2015)** yang mencakup informasi harian seperti:
- Jumlah peminjaman sepeda
- Variabel cuaca (suhu, kelembapan, kecepatan angin)
- Informasi waktu (bulan, hari, jam)

## 🧠 Models

Model yang dikembangkan:
- **Linear Regression**: sebagai model baseline
- **ANN (Artificial Neural Network)**: jaringan saraf sederhana dengan satu hidden layer
- **DNN (Deep Neural Network)**: jaringan dengan beberapa hidden layers untuk model yang lebih kompleks

Model dibangun menggunakan **TensorFlow/Keras** dan dibandingkan menggunakan metrik evaluasi seperti MAE dan RMSE.

## 📈 Results & Findings

- DNN menunjukkan performa terbaik dalam menangkap pola kompleks pada data.
- Terdapat hubungan signifikan antara jumlah peminjaman sepeda dengan temperatur, waktu (jam), dan hari dalam seminggu.
- Insight: Pengelola dapat menyesuaikan strategi operasional (misalnya distribusi sepeda) berdasarkan prediksi permintaan harian dan cuaca.

## 🚀 How to Run

Clone repository ini, jalankan digoogle colab/Jupyter notebook.

