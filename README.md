# Final-Project : Implementasi Pipeline Big Data ETL dan ELT pada Studi Kasus Pola Transaksi TransJakarta Periode April 2023 Berdasarkan Kondisi Cuaca

Repository ini berisi implementasi **pipeline Big Data end-to-end** yang mencakup proses **Extract, Transform, Load (ETL)**, **Extract, Load, Transform (ELT)**, perancangan **data warehouse**, serta **visualisasi analitik** pada studi kasus pola transaksi layanan **TransJakarta** berdasarkan **kondisi cuaca** pada periode **April 2023**.

---

## 🎯 Tujuan Proyek
- Mengimplementasikan pipeline **ETL (Extract, Transform, Load)** menggunakan Python
- Mengimplementasikan pendekatan **ELT (Extract, Load, Transform)** pada data warehouse
- Merancang dan membangun **data warehouse berbasis SQLite**
- Mengintegrasikan data transaksi dan data cuaca dalam satu skema terstruktur
- Menghasilkan insight analitik melalui visualisasi data
- Menyediakan media eksplorasi data berbasis waktu dan kondisi

---

## 🧰 Tools & Teknologi
- **Python** (implementasi ETL)
- **SQLite** sebagai data warehouse
- **ODBC SQLite Driver** (open-source)
- **Power BI** sebagai alat visualisasi
- Konsep **ETL & ELT**
- Dataset transaksi TransJakarta dan data cuaca

---

## 🏗️ Arsitektur Sistem
Pipeline Big Data pada proyek ini terdiri dari beberapa tahapan utama sebagai berikut:

1. **Extract**
   - Pengambilan data transaksi TransJakarta
   - Pengambilan data cuaca harian

2. **Transform (ETL)**
   - Pembersihan data
   - Normalisasi format waktu dan numerik
   - Integrasi data transaksi dan cuaca
   - Penentuan kategori kondisi cuaca

3. **Load**
   - Penyimpanan data hasil transformasi ke dalam **SQLite Data Warehouse**

4. **Transform (ELT)**
   - Transformasi lanjutan menggunakan query SQL
   - Agregasi dan perhitungan metrik analitik
   - Pembentukan tabel analitik

5. **Visualisasi**
   - Koneksi Power BI ke SQLite menggunakan ODBC
   - Penyajian hasil analisis dalam bentuk dashboard interaktif

---

## 📌 Output dan Fitur Analitik

### 🔹 Data Warehouse
- Tabel transaksi terintegrasi
- Tabel kondisi cuaca
- Tabel analitik hasil agregasi

### 🔹 Analisis Data
- Analisis jumlah dan nilai transaksi berdasarkan kondisi cuaca
- Analisis tren transaksi berdasarkan waktu
- Perbandingan pola transaksi saat hujan dan tidak hujan
- Analisis aktivitas transaksi pada jam sibuk

### 🔹 Visualisasi
- Key Performance Indicators (KPI)
- Grafik tren dan distribusi
- Filter interaktif berdasarkan waktu, koridor, dan kondisi cuaca

---

## 🚝 Batasan Proyek
- Data terbatas pada periode **April 2023**
- Analisis difokuskan pada hubungan antara transaksi dan kondisi cuaca

---

## 📂 Struktur Repository (Ringkas)
