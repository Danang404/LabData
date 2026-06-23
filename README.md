# 🧪 LabData Analytica 

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mobile-lightgrey.svg)

**LabData Analytica** adalah aplikasi *Single Page Application* (SPA) berbasis web yang dirancang khusus untuk memfasilitasi pencatatan, validasi, dan analisis deskriptif data laboratorium pertanian/ilmu tanah secara otomatis. Aplikasi ini dikembangkan untuk mempercepat alur riset tanpa memerlukan koneksi *database* eksternal.

---

## ✨ Fitur Utama (Core Features)

* **📱 Mobile-First UI:** Antarmuka responsif yang sangat nyaman digunakan menggunakan *smartphone* saat berada di dalam laboratorium atau *greenhouse*.
* **🛡️ Scientific Boundary Validation:** Dilengkapi dengan sistem validasi rentang batas ilmiah (misal: penolakan input pH negatif atau > 14) untuk menjaga integritas data riset.
* **📊 Analisis Statistik Deskriptif Otomatis:** Menghitung Rata-rata, Standar Deviasi (SD), dan Koefisien Keragaman (CV%) secara *real-time*.
* **🚨 Outlier Detection:** Sistem *flagging* (peringatan visual) pada kombinasi perlakuan yang memiliki sebaran data varians tinggi (CV > 15%).
* **💾 Local Storage Persistence:** Fitur *auto-save* berbasis memori *browser* yang mencegah data hilang akibat *refresh* tidak sengaja.
* **📄 Export Ready:** Mendukung pencetakan laporan otomatis ke format **PDF** dan **CSV** yang dienkapsulasi dengan aman untuk kompatibilitas Microsoft Excel.

## 🚀 Cara Penggunaan (Quick Start)

Karena aplikasi ini sepenuhnya berjalan di sisi *client* (Client-Side Rendering), Anda tidak perlu melakukan instalasi dependensi *backend*.

1. *Clone repository* ini:
   ```bash
   git clone [https://github.com/Danang404/labdata-analytica.git](https://github.com/Danang404/labdata-analytica.git)
