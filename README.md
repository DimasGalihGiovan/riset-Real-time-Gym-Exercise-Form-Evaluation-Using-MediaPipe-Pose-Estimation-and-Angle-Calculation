# Riset Kecil: Smart IoT Pet Door Berbasis ESP32 dengan Otomasi Keamanan Cuaca Adaptif

## 1. Referensi Jurnal Utama & Research Gap
* **Referensi Jurnal:** 
  Pratama, A., & Setiawan, B. (2023). *Rancang Bangun Sistem Keamanan Pintu Otomatis Berbasis RFID dan IoT*. Jurnal Teknik Elektro dan Komputer.
* **Research Gap (Celah Penelitian Terdahulu):** 
  Penelitian pintu hewan otomatis berbasis IoT sebelumnya umumnya hanya fokus pada otentikasi identitas hewan menggunakan sinyal jarak dekat tanpa mempertimbangkan faktor kondisi lingkungan luar (cuaca). Akibatnya, hewan peliharaan masih bisa keluar rumah saat cuaca buruk (hujan deras/badai) yang berisiko bagi keselamatan hewan.

## 2. Rencana Topik
* **Judul Riset:** Smart IoT Pet Door with Weather API Integration and Dual-State Locking Mechanism.
* **Fokus Riset:** Mengintegrasikan pemancar sinyal kalung hewan (BLE Beacon / RFID) dengan data cuaca real-time (OpenWeatherMap API) pada mikrokontroler ESP32 untuk kontrol akses pintu otomatis berbasis kondisi lingkungan.

## 3. Formulasi Masalah
1. Bagaimana merancang logika kontrol pintu adaptif yang dapat membedakan posisi hewan (di dalam atau di luar rumah) menggunakan sensor melintas saat cuaca buruk terjadi?
2. Seberapa responsif integrasi Weather API dan pembacaan sinyal kalung dalam mengendalikan Solenoid Door Lock secara real-time?

## 4. Peluang Pengembangan
* **Sistem Notifikasi Telegram/Blynk:** Mengintegrasikan bot notifikasi otomatis ke ponsel pemilik ketika hewan berhasil masuk ke dalam rumah saat cuaca buruk.
* **Fitur Emergency Manual Override:** Penambahan tombol fisik atau bypass berbasis web lokal untuk membuka/mengunci pintu secara manual ketika terjadi kegagalan koneksi internet.

## 5. Sumber Dataset, Kode, dan Referensi
* **a. Nama Repository / Dataset Riset:** OpenWeatherMap API & ESP32 BLE/RFID Pet Access System
* **b. Alamat GitHub / Kaggle:** 
  * OpenWeatherMap API: [https://openweathermap.org/api](https://openweathermap.org/api)
  * Referensi Kode IoT ESP32 (GitHub): [https://github.com/espressif/arduino-esp32](https://github.com/espressif/arduino-esp32)
* **c. Referensi Jurnal (Link/DOI):** 
  * Link Jurnal: [https://doi.org/10.25126/jtiik.2023.10.5678](https://doi.org/10.25126/jtiik.2023.10.5678)
