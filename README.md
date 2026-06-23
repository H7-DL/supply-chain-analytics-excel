# Supply Chain Analytics Dashboard

Analisis data rantai pasok untuk mengoptimalkan performa supplier, efisiensi logistik, dan manajemen inventaris menggunakan Microsoft Excel tingkat lanjut.

## Business Problem

Dalam industri manufaktur dan retail, pengelolaan rantai pasok yang tidak efisien dapat menyebabkan:
- Penumpukan stok barang yang membebani gudang
- Keterlambatan pengiriman dari supplier
- Tingkat cacat produk yang tinggi
- Biaya logistik yang tidak terkontrol

Proyek ini menganalisis data supply chain dari **100 SKU produk** (haircare, skincare, cosmetics) untuk mengidentifikasi area yang perlu dioptimalkan.

## Tools & Technologies

- **Microsoft Excel** (Advanced)
- **Power Query** (ETL, Data Cleaning, Transformasi Data)
- **Pivot Table & Pivot Chart** (Data Modeling & Aggregation)
- **Slicers** (Interactive Dashboarding)

## Data Processing

1. **Data Import & Cleaning** menggunakan Power Query untuk membersihkan dan mentransformasi data mentah
2. **Data Modeling** dengan Pivot Table untuk menghitung metrik kunci seperti rata-rata defect rate dan lead time per supplier
3. **Visualisasi Interaktif** dengan Slicers yang memungkinkan user memfilter data berdasarkan supplier, jenis produk, atau carrier secara real-time

## Key Insights

### 1. Performa Supplier
Dari 5 supplier (Mumbai, Delhi, Bangalore, Chennai, Kolkata), ditemukan variasi signifikan dalam lead time dan defect rates. Supplier dengan manufacturing cost lebih tinggi tidak selalu menghasilkan defect rate lebih rendah.

### 2. Quality Control
Distribusi inspection results menunjukkan proporsi yang cukup seimbang antara Pass, Fail, dan Pending, mengindikasikan perlunya standardisasi proses quality control yang lebih ketat.

### 3. Efisiensi Pengiriman
Analisis terhadap 3 carrier (Carrier A, B, C) menunjukkan perbedaan signifikan dalam shipping costs dan delivery times, memberikan dasar untuk negosiasi kontrak logistik yang lebih baik.

### 4. Manajemen Inventaris
Produk dengan product type berbeda menunjukkan pola stock turnover yang bervariasi, memerlukan strategi inventory yang disesuaikan per kategori.

## Business Recommendations

- Fokus pada supplier dengan defect rate rendah untuk negosiasi kontrak jangka panjang
- Optimasi penggunaan carrier dengan biaya paling efisien
- Implementasi quality control yang lebih ketat di tahap manufacturing
- Adjust stock levels berdasarkan velocity penjualan per kategori produk

## Repository Structure
supply-chain-analytics-excel/
├── README.md
├── Supply_Chain_Analytics_Dashboard.xlsx (File Excel dengan dashboard interaktif)
└── screenshots/
    ├── dashboard_view.png
    ├── slicer_interaction.png
    └── power_query_steps.png

## Connect With Me

- **LinkedIn:** [Hans Christian](https://www.linkedin.com/in/hanschristian771)
- **GitHub:** [@H7-DL](https://github.com/H7-DL)

---

**Last Updated:** June 2026
