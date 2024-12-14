# 🏨 Hotel Booking Analysis

## **About**

Hotel Booking Analysis adalah proyek yang bertujuan untuk mengeksplorasi dan menganalisis dataset pemesanan hotel untuk mengidentifikasi pola pemesanan, pembatalan, dan faktor yang memengaruhi pendapatan harian rata-rata (_Average Daily Rate/ADR_).

Proyek ini menggunakan pendekatan eksplorasi data untuk memberikan wawasan yang actionable bagi pengelola hotel untuk meningkatkan strategi pemesanan dan pengalaman pelanggan. Semua analisis dilakukan menggunakan Google Colab.

---

## 🔄 **Table of Content**

1. [About](#about)
2. [Dataset](#dataset)
3. [Dependencies](#dependencies)
4. [Getting Started](#getting-started)
5. [Findings](#findings)
6. [License](#license)
7. [Team](#team)

---

## 📊 **Dataset**

Dataset yang digunakan berasal dari [Kaggle - Hotel Booking Demand](https://www.kaggle.com/jessemostipak/hotel-booking-demand). Dataset ini mencakup 119.390 entri dan 32 kolom, termasuk informasi berikut:

- `hotel`: Jenis hotel (_City Hotel_ atau _Resort Hotel_).
- `is_canceled`: Status pembatalan pemesanan.
- `lead_time`: Waktu antara pemesanan dan tanggal kedatangan.
- `adr`: Pendapatan rata-rata per hari (_Average Daily Rate_).

Dataset ini telah dibersihkan, diolah, dan dianalisis untuk memberikan wawasan yang signifikan.

---

## ⚙️ **Dependencies**

Proyek ini telah diuji pada lingkungan Google Colab. Berikut adalah beberapa library utama yang digunakan:

- pandas
- numpy
- matplotlib
- seaborn

Semua library ini tersedia untuk diinstal melalui pip jika diperlukan di lingkungan lokal.

---

## 🔄 **Getting Started**

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek:

1. Clone repositori ini:

   ```bash
   git clone https://github.com/username/hotel-booking-analysis.git
   ```

2. Buka Google Colab:

   - Upload file notebook (`Hotels Booking Analysis 004 - 217.ipynb`) ke Google Colab.
   - Upload dataset (`hotels.csv`) ke workspace.

3. Jalankan semua sel di notebook untuk mereplikasi hasil analisis.

---

## 📊 **Findings**

### **Temuan Utama:**

1. **Distribusi Tipe Hotel:** _City Hotel_ lebih sering dipesan daripada _Resort Hotel_ karena lokasi yang strategis.
2. **Pembatalan Pemesanan:** Sekitar 27,6% pemesanan dibatalkan, yang menunjukkan pentingnya strategi untuk mengurangi pembatalan.
3. **Lead Time dan Pembatalan:** Pemesanan dengan lead time yang lebih panjang memiliki kemungkinan pembatalan lebih tinggi.
4. **Pendapatan Rata-Rata (ADR):** _Resort Hotel_ memiliki ADR lebih tinggi dibandingkan _City Hotel_.

Visualisasi dari temuan ini dapat dilihat di notebook.

---

## 🔒 **License**

Proyek ini dilisensikan di bawah [MIT License](LICENSE), sehingga bebas diakses oleh siapa saja.

---

## 👥 **Team**

- Fernanda Wawang Azraqi [202110370311004]
- Annisa Artanti Widyadhana [202110370311217]

---

## 👏 **Acknowledgments**

Kami mengucapkan terima kasih kepada dosen dan teman-teman yang telah memberikan bimbingan selama pengerjaan proyek ini. Terima kasih juga kepada [Kaggle](https://www.kaggle.com/) atas dataset yang disediakan.
