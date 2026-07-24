# ☕ Coffee Shop Sales & Performance Analysis

![Data Analysis Project](https://img.shields.io/badge/Data%20Analysis-Excel-green) 
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis data transaksi penjualan *Coffee Shop* guna mengidentifikasi tren penjualan, perilaku pembelian pelanggan, serta performa produk. Melalui proses *data cleaning*, eksplorasi data, dan visualisasi, proyek ini memberikan rekomendasi berbasis data (*data-driven recommendations*) untuk membantu pemilik kedai meningkatkan pendapatan dan efisiensi operasional.

---

## 🛠️ Tools & Technologies
* **Microsoft Excel / Power Query:** Pembersihan data, transformasi kolom, dan penanganan nilai kosong.
* **Pivot Tables & Formulas:** Agregasi data penjualan, perhitungan pendapatan, dan statistik tren harian/bulanan.
* **Excel Dashboard:** Visualisasi data interaktif untuk penyajian insight bisnis.

---

## 🧹 Data Cleaning & Preparation
Sebelum analisis dilakukan, data mentah (`Coffee Shop Sales(before).xlsx`) diproses menjadi data bersih (`after.xlsx`) dengan langkah-langkah berikut:
1. **Handling Missing & Duplicate Data:** Menghapus entri ganda dan menangani nilai yang hilang pada catatan transaksi.
2. **Data Formatting:** Memastikan tipe data pada kolom tanggal, waktu, jumlah (*quantity*), dan harga (*unit price*) sudah sesuai.
3. **Feature Engineering:** Menambahkan kolom baru seperti *Revenue* (`Quantity` × `Unit Price`), *Hour of Day*, dan *Day Name* untuk memudahkan analisis tren waktu.

---

## 📈 Key Insights
Berdasarkan hasil analisis data transaksi, diperoleh beberapa temuan utama:

1. **Produk Terlaris (Top Selling Products):**
   * Kategori minuman kopi (seperti *Latte* dan *Cappuccino*) menyumbang proporsi pendapatan terbesar.
2. **Jam Sibuk Operasional (Peak Hours):**
   * Penjualan tertinggi terjadi pada jam jam sibuk pagi (08:00 - 10:00) dan sore hari (15:00 - 17:00).
3. **Tren Penjualan Harian:**
   * Hari kerja (*weekdays*) mencatatkan volume transaksi minuman yang lebih tinggi dibanding akhir pekan (*weekends*).

---

## 💡 Business Recommendations
Berdasarkan *insights* yang ditemukan, berikut strategi bisnis yang disarankan:
* **Promosi Jam Sibuk:** Buat paket *bundling* kopi + pastry pada jam sibuk pagi untuk meningkatkan *Average Order Value* (AOV).
* **Optimization Staffing:** Alokasikan lebih banyak staf pada jam puncak (08:00 - 10:00) untuk mempercepat pelayanan dan mengurangi antrean.
* **Program Loyalitas Akhir Pekan:** Tawarkan diskon atau *loyalty points* berlipat di akhir pekan untuk meningkatkan volume penjualan saat jam lengang.

---

## 📂 Repository Structure
```text
Coffee Shop Sales/
├── Coffee Shop Sales(before).xlsx   # Data mentah sebelum dibersihkan
├── after.xlsx                        # Data bersih hasil olahan & Pivot
├── Kesimpulan Bisnis.txt             # Teks catatan kesimpulan bisnis
└── README.md                         # Dokumentasi utama proyek
