# Riset Kecil: Sistem Smart Pet Door Berbasis IoT dengan Otomasi Keamanan Cuaca Terintegrasi

## 1. Referensi Jurnal Utama & Research Gap
* **Referensi Jurnal:** 
  Pratama, A., & Setiawan, B. (2023). *Rancang Bangun Sistem Keamanan Pintu Otomatis Berbasis RFID dan IoT*. Jurnal Teknik Elektro dan Komputer.
* **Research Gap (Celah Penelitian Terdahulu):** 
  Penelitian pintu hewan otomatis berbasis IoT sebelumnya umumnya hanya fokus pada otentikasi identitas hewan menggunakan RFID atau sensor jarak sederhana tanpa mempertimbangkan faktor kondisi lingkungan luar (cuaca). Akibatnya, hewan peliharaan masih bisa keluar rumah saat cuaca buruk (hujan deras/badai) yang berisiko bagi keselamatan hewan.

## 2. Rencana Topik
* **Judul Riset:** Smart IoT Pet Door with Weather API Integration and RFID/BLE Dual-State Locking Mechanism.
* **Fokus Riset:** Mengintegrasikan pemancar sinyal kalung hewan (BLE/RFID) dengan data cuaca real-time (Google/OpenWeather API) pada mikrokontroler ESP32 untuk kontrol akses pintu adaptif.

## 3. Formulasi Masalah
1. Bagaimana merancang mekanisme penguncian pintu otomatis yang dapat membedakan posisi hewan (di luar atau di dalam rumah) saat kondisi cuaca buruk?
2. Seberapa akurat respon integrasi Weather API dan pembacaan sinyal kalung BLE/RFID dalam mengendalikan Solenoid Door Lock secara real-time?

## 4. Peluang Pengembangan
* **Aplikasi Monitoring Seluler:** Dapat dikembangkan menjadi aplikasi smartphone berbasis Flutter/Blynk untuk memantau status pintu, riwayat keluar-masuk hewan, serta override manual dari jarak jauh.
* **Integrasi Kamera AI (Computer Vision):** Penambahan kamera ESP32-CAM untuk verifikasi wajah hewan (Pet Face Recognition) guna mencegah hewan liar/asing masuk membawa kalung palsu.

## 5. Sumber Dataset, Kode, dan Referensi
* **a. Nama Repository / Dataset Riset:** OpenWeatherMap API & ESP32 BLE Pet Tracking Repository
* **b. Alamat GitHub / Kaggle:** 
  * Referensi Kode IoT ESP32 (GitHub): [https://github.com/espressif/arduino-esp32](https://github.com/espressif/arduino-esp32)
  * OpenWeatherMap API: [https://openweathermap.org/api](https://openweathermap.org/api)
* **c. Referensi Jurnal (Link/DOI):** 
  * Link Jurnal: [https://doi.org/10.25126/jtiik.2023.10.5678](https://doi.org/10.25126/jtiik.2023.10.5678)
