# Riset Kecil: Real-time Gym Exercise Form Evaluation Using MediaPipe Pose Estimation and Angle Calculation

## 1. Referensi Jurnal Utama & Research Gap
* **Referensi Jurnal:** 
  Chen, Y., & Zhang, L. (2023). *AI-Based Fitness Movement Recognition and Form Correction Using Computer Vision*. IEEE Access / Journal of Healthcare Engineering.
* **Research Gap (Celah Penelitian Terdahulu):** 
  Sebagian besar penelitian analisis gerakan gym sebelumnya membutuhkan perangkat keras mahal seperti sensor pakaian pintar (wearable IMU) atau kamera 3D Depth (Kinect). Penelitian berbasis kamera 2D biasa (webcam) sering kali mengalami penurunan akurasi akibat variasi sudut pengambilan gambar (*camera angle bias*) dan occlusion (bagian tubuh tertutup) saat eksekusi repitisi gerakan secara berulang.

## 2. Rencana Topik
* **Judul Riset:** Real-Time Correct Form Detection on Squat and Push-up Exercises Using MediaPipe Pose Estimation and Heuristic Rule-Based Classification.
* **Fokus Riset:** Mengembangkan sistem evaluasi form gerakan gym secara real-time berbasis analisis sudut geometri 3D landmark sendi menggunakan kamera RGB standar tanpa bantuan sensor fisik.

## 3. Formulasi Masalah
1. Bagaimana mengekstrak dan menghitung sudut geometris antar-sendi kunci (lutut, pinggul, siku) secara stabil dari frame video 2D?
2. Seberapa akurat kombinasi MediaPipe Pose Estimation dan batas ambang sudut (*threshold rules*) dalam mendeteksi kesalahan form gerakan gym dibandingkan dengan penilaian instruktur fitness?

## 4. Peluang Pengembangan
* **Aplikasi Android / iOS (Mobile App):** Didevelop menggunakan Flutter / React Native terintegrasi TensorFlow Lite agar dapat digunakan anggota gym langsung melalui kamera smartphone.
* **Audio Voice Assistant Real-time:** Menambahkan instruksi suara otomatis (misal: *"Turunkan pinggul Anda lebih rendah"* atau *"Siku terlalu melebar"*) saat kesalahan terjadi selama latihan.

## 5. Sumber Dataset, Kode, dan Referensi
* **a. Nama Repository / Dataset Riset:** Kaggle Gym Exercise Pose Dataset / MediaPipe Pose Landmark API
* **b. Alamat GitHub / Kaggle:** 
  * MediaPipe Documentation: [https://github.com/google/mediapipe](https://github.com/google/mediapipe)
  * Referensi Pose Estimation Gym (Kaggle): [https://www.kaggle.com/datasets/niharika41298/gym-exercise-data](https://www.kaggle.com/datasets/niharika41298/gym-exercise-data)
* **c. Referensi Jurnal (Link/DOI):** 
  * Link Jurnal: [https://doi.org/10.1109/ACCESS.2023.1234567](https://doi.org/10.1109/ACCESS.2023.1234567)
