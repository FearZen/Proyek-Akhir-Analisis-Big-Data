# 🏨 Hotel Booking Analysis <a name="about"></a>

## **About**

Hotel Booking Analysis adalah proyek yang bertujuan untuk mengeksplorasi dan menganalisis dataset pemesanan hotel untuk mengidentifikasi pola pemesanan, pembatalan, dan faktor yang memengaruhi pendapatan harian rata-rata (_Average Daily Rate/ADR_).

Proyek ini menggunakan pendekatan eksplorasi data untuk memberikan wawasan yang actionable bagi pengelola hotel untuk meningkatkan strategi pemesanan dan pengalaman pelanggan. Semua analisis dilakukan menggunakan Google Colab.

**🌟 1. Pernyataan Masalah**

Dalam industri perhotelan, pemesanan kamar merupakan elemen kunci yang secara langsung memengaruhi tingkat hunian dan pendapatan. Namun, banyak hotel menghadapi tantangan seperti tingginya angka pembatalan, variasi yang signifikan dalam pendapatan harian rata-rata (Average Daily Rate/ADR), serta kesulitan memahami perilaku pelanggan. Tantangan-tantangan ini dapat menghambat kemampuan hotel dalam menetapkan strategi harga yang efektif dan menjaga kepuasan pelanggan. Oleh karena itu, analisis data pemesanan diperlukan untuk mengungkap pola-pola penting dan faktor-faktor yang memengaruhi operasional hotel.

**🛠️ 2. Rencana Mengatasi Masalah**

Untuk mengatasi tantangan ini, kami akan menggunakan dataset pemesanan hotel yang berisi informasi penting, seperti tanggal pemesanan, tipe kamar, lama menginap, dan ADR. Data ini akan diproses dan dianalisis menggunakan metodologi eksplorasi data untuk memahami pola serta tren yang relevan. Kami akan membersihkan dataset, mengelompokkan informasi, dan menerapkan analisis statistik untuk menggali wawasan. Semua langkah ini dilakukan di Google Colab menggunakan pustaka Python seperti Pandas, Matplotlib, dan Seaborn untuk mempermudah pengolahan dan visualisasi data.

**📊 3. Pendekatan/Teknik Analisis**

Pendekatan yang kami gunakan mencakup eksplorasi data untuk mempelajari distribusi variabel penting seperti ADR dan pola pembatalan. Analisis deskriptif dilakukan untuk mendapatkan gambaran umum mengenai tren pelanggan, sementara segmentasi digunakan untuk mengelompokkan pelanggan berdasarkan preferensi tertentu. Visualisasi data menjadi alat utama dalam menyampaikan hasil analisis secara jelas dan mudah dipahami. Pendekatan ini dirancang untuk membantu mengatasi sebagian besar tantangan yang telah diidentifikasi.

**🎯 4. Manfaat Analisis untuk Konsumen**

Hasil analisis ini akan memberikan nilai tambah bagi pengelola hotel. Dengan wawasan tentang tren ADR dan perilaku pelanggan, hotel dapat mengoptimalkan harga kamar untuk meningkatkan pendapatan. Pola pembatalan yang teridentifikasi juga memungkinkan hotel untuk menyusun kebijakan yang lebih baik dalam menangani pembatalan. Selain itu, memahami preferensi pelanggan membantu hotel dalam menawarkan layanan yang lebih personal dan meningkatkan pengalaman pelanggan. Wawasan ini juga dapat digunakan untuk menyusun kampanye pemasaran yang lebih efektif, dengan fokus pada segmen pelanggan yang paling potensial.

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

## 📊 **Dataset** <a name="dataset"></a>

Dataset yang digunakan berasal dari [Kaggle - Hotel Booking Demand](https://www.kaggle.com/jessemostipak/hotel-booking-demand). Dataset ini mencakup 119.390 entri dan 32 kolom, termasuk informasi berikut:

- `hotel`: Jenis hotel (_City Hotel_ atau _Resort Hotel_).
- `is_canceled`: Status pembatalan pemesanan.
- `lead_time`: Waktu antara pemesanan dan tanggal kedatangan.
- `adr`: Pendapatan rata-rata per hari (_Average Daily Rate_).

Dataset ini telah dibersihkan, diolah, dan dianalisis untuk memberikan wawasan yang signifikan.

---

## ⚙️ **Dependencies** <a name="dependencies"></a>

Proyek ini telah diuji pada lingkungan Google Colab. Berikut adalah beberapa library utama yang digunakan:

- pandas
- numpy
- matplotlib
- seaborn

Semua library ini tersedia untuk diinstal melalui pip jika diperlukan di lingkungan lokal.

---

## 🔄 **Getting Started** <a name="getting-started"></a>

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

## 📊 **Findings** <a name="findings"></a>

### **Temuan Utama:**

1. **Distribusi Tipe Hotel:** _City Hotel_ lebih sering dipesan daripada _Resort Hotel_ karena lokasi yang strategis.
2. **Pembatalan Pemesanan:** Sekitar 27,6% pemesanan dibatalkan, yang menunjukkan pentingnya strategi untuk mengurangi pembatalan.
3. **Lead Time dan Pembatalan:** Pemesanan dengan lead time yang lebih panjang memiliki kemungkinan pembatalan lebih tinggi.
4. **Pendapatan Rata-Rata (ADR):** _Resort Hotel_ memiliki ADR lebih tinggi dibandingkan _City Hotel_.

Visualisasi dari temuan ini dapat dilihat di notebook.

---

## 🔒 **License** <a name="license"></a>

Proyek ini dilisensikan di bawah [MIT License](LICENSE), sehingga bebas diakses oleh siapa saja.

---

## 👥 **Team** <a name="team"></a>

- Fernanda Wawang Azraqi [202110370311004]
- Annisa Artanti Widyadhana [202110370311217]

---

## 👏 **Acknowledgments**

Kami mengucapkan terima kasih kepada **Bapak Yuda Munarko, S.Kom., M.Sc** selaku dosen pengampu yang telah memberikan ilmunya untuk keberhasilan proyek ini. Terima kasih juga kepada [Kaggle](https://www.kaggle.com/) atas dataset yang disediakan.
