# Riset Kecil: Deteksi Teks Tinjauan / Komentar Spam Bahasa Indonesia Menggunakan Machine Learning

## 1. Referensi Jurnal Utama & Research Gap
* **Referensi Jurnal:** 
  Alfaro, A., & Purwanto, E. (2022). *Analisis Sentimen dan Klasifikasi Teks Kasual Bahasa Indonesia Menggunakan Machine Learning*. Jurnal Teknologi Informasi dan Ilmu Komputer (JTIIK).
* **Research Gap (Celah Penelitian Terdahulu):** 
  Penelitian terdahulu mengenai klasifikasi teks dan deteksi spam/hate speech umumnya menggunakan dataset bahasa Inggris formal atau teks berita. Ketika diterapkan pada komentar media sosial di Indonesia yang kaya akan bahasa gaul (*slang*), kata singkatan (misal: "yg", "dgn"), dan tipografi tidak baku, akurasi model mengalami penurunan signifikan karena keterbatasan proses *text preprocessing* dan pemetaan kamus *stopword*.

## 2. Rencana Topik
* **Judul Riset:** Comparative Analysis of Naive Bayes and Support Vector Machine (SVM) for Indonesian Social Media Spam Classification.
* **Fokus Riset:** Menguji dan membandingkan performa algoritma klasifikasi (Naive Bayes vs SVM) dengan penerapan ekstraksi fitur TF-IDF dan normalisasi kata gaul (*slangword mapping*) pada komentar media sosial berbahasa Indonesia.

## 3. Formulasi Masalah
1. Seberapa besar pengaruh pembersihan teks (*text preprocessing* dan normalisasi kata gaul) terhadap peningkatan akurasi model klasifikasi spam bahasa Indonesia?
2. Algoritma mana yang memberikan performa terbaik (ditinjau dari Akurasi, Precision, dan Recall) antara Naive Bayes dan Support Vector Machine (SVM)?

## 4. Peluang Pengembangan
* **Integrasi Bot Moderasi Otomatis:** Model riset ini dapat dikembangkan menjadi *API* atau bot otomatis untuk filter komentar spam pada akun toko online (e-commerce) atau media sosial secara *real-time*.
* **Pengembangan Dataset Kebencanaan/Layanan Publik:** Metode normalisasi bahasa tidak baku ini dapat diaplikasikan untuk menyaring laporan darurat masyarakat di media sosial agar dapat diproses lebih cepat oleh instansi terkait.

## 5. Sumber Dataset, Kode, dan Referensi
* **a. Nama Repository Dataset Riset:** Indonesian Twitter/Social Media Spam & Hate Speech Dataset
* **b. Alamat GitHub / Kaggle:** 
  * Dataset Kaggle: [https://www.kaggle.com/datasets/mizandarmawan/indonesian-sentiment-analysis-dataset](https://www.kaggle.com/datasets/mizandarmawan/indonesian-sentiment-analysis-dataset)
  * Referensi Kode (GitHub): [https://github.com/eaganj/indonesian-text-classification](https://github.com/eaganj/indonesian-text-classification)
* **c. Referensi Jurnal (Link/DOI):** 
  * DOI / URL Jurnal: [https://doi.org/10.25126/jtiik.2022.9.1234](https://doi.org/10.25126/jtiik.2022.9.1234)
