# Simon-Siska-BTS
Project IoT untuk monitoring keamanan BTS berbasis ESP32

# SIMON SISKA – Sistem Keamanan BTS Berbasis IoT

## 📌 Deskripsi
Simon SISKA adalah sistem keamanan BTS berbasis IoT yang mendeteksi akses ilegal, pencurian, dan vandalisme secara real-time.

## 🔧 Spesifikasi Teknis
- **Mikrokontroler:** ESP32 (NodeMCU ESP-32E & ESP32-CAM)
- **Sensor:** Magnetic Switch, Limit Switch, PIR, Laser + LDR
- **Modul Komunikasi:** Wi-Fi
- **Output:** Sirene, LED, DF Player Mini, ESP32-CAM
- **Database:** MySQL (PHP-MyAdmin)

## 🚀 Cara Kerja
1. Sensor mendeteksi aktivitas mencurigakan.
2. Sistem mengaktifkan alarm (Sirene, LED, Audio).
3. ESP32-CAM mengambil gambar dan menyimpannya.
4. Data dikirim ke server MySQL.
5. (Rencana) Notifikasi dikirim ke Telegram/Web Admin.

## 🛠 Implementasi & Hasil
- **PIR Sensor** mendeteksi gerakan hingga 4.5 meter.
- **ESP32-CAM** menghasilkan foto 1024 x 768 (XGA).
- **Magnetik Switch** responsif pada jarak ≥ 1 cm.

## ⚡ Tantangan & Solusi
- **Masalah komunikasi SIM900A** → Fokus pada Wi-Fi & upgrade ke LTE.
- **Konsumsi daya ESP32-CAM** → Optimasi penggunaan daya.
- **Integrasi multi-sensor** → Pengolahan prioritas deteksi.

## 🔮 Rencana Pengembangan
- **Face Recognition dengan ESP32-CAM**
- **Notifikasi otomatis ke Telegram**
- **Mode Maintenance & Operasional tanpa update kode**

## 📎 Link & Dokumentasi
- **GitHub Repo:** _[link repo]_  
- **Dokumentasi PDF:** _[link PDF]_  
- **Demo Video:** _[link YouTube/Drive]_ 
