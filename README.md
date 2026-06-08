# Data Analytics Project: Aftersales Performance & Financial Revenue Optimization Dashboard

## 📌 Project Background & Business Context
Dalam industri otomotif *aftersales* (bengkel resmi), mengelola efisiensi operasional dan memaksimalkan pendapatan dari setiap unit masuk (*Unit Entry*) adalah kunci profitabilitas. Proyek ini mengembangkan **Sistem Dashboard Analytics Performance terintergrasi** untuk **Toyota Astrido Bekasi**. 

Dashboard ini dirancang secara khusus untuk menjawab tantangan manajemen dalam memantau produktivitas *Service Advisor* (SA), menganalisis penetrasi pasar berdasarkan model dan tahun kendaraan, serta melacak kesehatan finansial melalui visualisasi *Gross Profit (Laba Kotor)* dan analisis *Revenue per Unit*.

---

## 🎯 Project Objectives (Tujuan Proyek)
1. **Performance Monitoring:** Mengukur pencapaian *Unit Entry* dan *CPUS (Capacity Productive Unit Service)* terhadap target bulanan yang ditetapkan diler dan TAM.
2. **Service Advisor Productivity Analysis:** Mengevaluasi kinerja individu *Service Advisor* secara transparan untuk mendorong budaya kerja yang kompetitif dan kompeten (*high-performing culture*).
3. **Revenue & Profitability Optimization:** Menganalisis tren laba kotor bulanan dan kontribusi laba per kelompok pekerjaan guna menetapkan strategi penetapan harga (*pricing strategy*) dan fokus penjualan layanan.
4. **Market & Unit Profiling:** Mengidentifikasi model kendaraan terlaris dan tahun produksi dominan untuk memetakan kebutuhan stok suku cadang (*inventory management*).

---

## 📊 Dashboard Breakdown & Technical Architecture

Proyek ini dibagi menjadi dua modul interaktif utama (Operasional & Finansial):

### Halaman 1: Operasional & Kinerja Unit (Operational Excellence)



#### 1. Key Point Indicators (KPI)
* **Total Unit Entry Vs Target:** Mencapai **967 unit**, melampaui target diler sebesar 412 unit (**+134.71%**).
* **Aktual Unit CPUS Vs Target:** Mencapai **967 unit**, melampaui target kapasitas produktif sebesar 288 unit (**+235.76%**).

#### 2. Pencapaian Unit & CPUS per Service Advisor (SA)
* **Visualisasi:** *Grouped Bar Chart* yang membandingkan pencapaian unit individu terhadap Target Per SA dan Target CPUS Per SA.
* **Insight:** **Ernawan Oktavianus** memimpin produktivitas dengan **686 unit** (target 413), diikuti oleh Slamet Herry (619 unit), Agung Setiawan (599 unit), Dede Arizki (561 unit), dan Renol Sijabat (530 unit). Semua SA berhasil melewati target minimum, menandakan efektivitas distribusi beban kerja.

#### 3. Komposisi Kelompok Pekerjaan
* **Visualisasi:** *Donut Chart* penyerapan jenis servis.
* **Insight:** **Service Berkala Eksternal** mendominasi pasar sebesar **35,19% (1,05K unit)**, diikuti oleh **Light General Repair** sebesar **17,16% (0,51K unit)**. Sisanya terbagi atas program Free Jasa (40K KM & 30K KM) serta Warranty Claim.

#### 4. Top 3 Unit (Tahun & Jenis Kendaraan)
* **Tahun Kendaraan:** Didominasi oleh kendaraan tahun **2023 (551 unit)**, 2024 (474 unit), dan 2025 (378 unit). Hal ini menunjukkan retensi kendaraan baru masih sangat kuat.
* **Jenis Kendaraan:** **AVANZA (544 unit)** dan **RUSH (467 unit)** menjadi penyumbang volume terbesar, disusul oleh CALYA (259 unit).

#### 5. Trend Pencapaian Unit Entry (Daily Trend)
* Line chart harian menunjukkan fluktuasi *Unit Entry* sepanjang bulan Oktober hingga awal November, dengan lonjakan tertinggi (*peak season*) mencapai **65 unit per hari** pada pertengahan bulan.

---

### Halaman 2: Analisis Finansial & Laba Kotor (Financial Performance)

#### 1. Financial High-Level Metrics
* **Total Revenue:** Menghasilkan **Rp5.015.272.585** (Lima Miliar Rupiah+).
* **Total Unit Entry:** Tercatat **2.995 unit** pada periode kumulatif.
* **Revenue / Unit:** Berada di angka rata-rata **Rp1.674.548 per kendaraan**.

#### 2. Total Laba Kotor Trend (MoM Trend)
* **Visualisasi:** *Area Chart* pergerakan laba kotor bulanan (Oktober - Desember 2025).
* **Insight:** Terjadi penurunan laba kotor pada November 2025 ke titik Rp1.634M, namun mengalami **rebound tajam pada Desember 2025 mencapai Rp1.703M** (*end-of-year peak service season*).

#### 3. Laba Kotor Rata-rata / Kelompok Pekerjaan
* **Insight Strategis:** Meskipun *Service Berkala Eksternal* menang secara volume, kontribusi laba tertinggi secara rata-rata per unit dipegang oleh **Heavy General Repair (Rp10.253.547)** dan **Medium General Repair (Rp5.132.623)**. Ini memberikan sinyal berharga bagi marketing untuk meningkatkan konversi unit perbaikan berat.

#### 4. Unit Entry Vs Last Month (Month-over-Month Comparison)
* **Visualisasi:** *Dual Bar Chart* komparatif antara Bulan Berjalan (Biru Muda) dan Bulan Lalu (Biru Tua).
* **Insight:** Terjadi pertumbuhan volume yang masif di hampir semua lini pekerjaan utama (terutama pada segmen Service Berkala dan Light General Repair) dibandingkan bulan sebelumnya.

---

## 📈 Business Impact & Decision Making (Dampak Bisnis)

Implementasi dashboard analitik ini memberikan dampak nyata pada pengambilan kebijakan strategis diler:

* **Incentive & Motivation Management:** Data performa SA yang transparan digunakan manajemen sebagai basis perhitungan bonus performa (*performance-based incentive*), terbukti dengan pencapaian seluruh SA yang melampaui target dasar diler.
* **Inventory & Spareparts Forecasting:** Berdasarkan tren *Top 3 Unit (Avanza, Rush, Calya)* dan dominasi kendaraan tahun 2023-2024, tim parts dapat mengoptimalkan persediaan oli, filter, dan fast-moving parts spesifik model tersebut guna menghindari *stockout* atau *overstock*.
* **Upselling Strategy for High-Margin Services:** Mengetahui bahwa *Heavy General Repair* menghasilkan laba kotor Rp10,2 Juta per unit, tim Service Advisor diarahkan untuk melakukan *general check-up* yang lebih ketat pada kendaraan berumur di atas 3 tahun untuk mendeteksi potensi perbaikan berat.
* **Operational Capacity Planning:** Tren harian membantu kepala bengkel dalam mengatur jadwal libur teknisi (*manpower shifting*) agar kapasitas *stall* tetap maksimal pada hari-hari yang teridentifikasi sebagai *peak days* (berdasarkan grafik tren harian).

---

## 🛠️ Tech Stack & Architecture
* **BI Platform:** Microsoft Power BI / Google Looker Studio
* **Data Source:** Dealer Management System (DMS) Toyota / SQL Server
* **Transformation Tool:** Power Query / DAX Formulas

---
💡 *Proyek analitik ini merefleksikan kompetensi mendalam dalam manajemen operasional otomotif, rekayasa data keuangan, dan visualisasi metrik bisnis untuk diler skala besar.*
