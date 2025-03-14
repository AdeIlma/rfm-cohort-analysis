# README - RFM & COHORT Analysis

## 📌 Deskripsi
Notebook ini berisi analisis RFM (Recency, Frequency, Monetary) dan Cohort Analysis untuk memahami perilaku pelanggan berdasarkan transaksi historis mereka. Analisis ini digunakan untuk segmentasi pelanggan dan mengembangkan strategi bisnis berbasis data.

---

## 📂 Struktur Kode

1. **Import Library**
   - Memuat pustaka yang dibutuhkan seperti pandas, numpy, datetime, dan seaborn untuk analisis dan visualisasi data.

2. **Memuat Dataset**
   - Dataset transaksi pelanggan dimuat dalam format CSV.
   - Data diproses untuk mendapatkan informasi seperti tanggal transaksi, jumlah pembelian, dan total nilai transaksi.

3. **Data Preprocessing**
   - Membersihkan data dengan menghapus nilai yang hilang atau tidak valid.
   - Mengubah format tanggal agar sesuai untuk analisis berbasis waktu.

4. **Analisis RFM**
   - **Recency (R)**: Menghitung hari sejak transaksi terakhir pelanggan.
   - **Frequency (F)**: Menghitung jumlah transaksi per pelanggan.
   - **Monetary (M)**: Menghitung total nilai transaksi pelanggan.
   - Segmentasi pelanggan berdasarkan skor RFM dan pengelompokannya.

5. **Cohort Analysis**
   - Menentukan bulan pertama pelanggan melakukan transaksi.
   - Mengelompokkan pelanggan berdasarkan bulan pertama pembelian mereka.
   - Menghitung tingkat retensi pelanggan dari waktu ke waktu.

6. **Visualisasi Data**
   - Diagram heatmap untuk cohort analysis.
   - Grafik distribusi pelanggan berdasarkan kategori RFM.
   
7. **Kesimpulan & Rekomendasi**
   - Strategi retensi pelanggan berdasarkan hasil Cohort Analysis.
   - Rekomendasi pemasaran untuk setiap segmen pelanggan berdasarkan hasil RFM.

---

## 🚀 Cara Menggunakan

1. **Persiapkan lingkungan Python**
   - Pastikan Anda memiliki Python 3.x terinstal.
   - Install pustaka yang dibutuhkan dengan perintah berikut:
     ```sh
     pip install pandas numpy matplotlib seaborn
     ```

2. **Jalankan Notebook**
   - Buka file `RFM_&_COHORT.ipynb` di Jupyter Notebook atau Google Colab.
   - Eksekusi setiap sel kode untuk menjalankan analisis.

3. **Interpretasi Hasil**
   - Gunakan hasil RFM untuk mengidentifikasi pelanggan potensial.
   - Gunakan Cohort Analysis untuk memahami retensi pelanggan dan menentukan strategi marketing yang tepat.

---

## 📊 Rekomendasi Bisnis
1. **Strategi Pemasaran Berdasarkan RFM**
   - **Pelanggan Loyal**: Berikan penghargaan seperti diskon eksklusif atau program loyalitas.
   - **Pelanggan Baru**: Berikan insentif seperti kupon selamat datang.
   - **Pelanggan yang Mulai Tidak Aktif**: Kirim pengingat atau promo khusus untuk menarik mereka kembali.

2. **Strategi Retensi Berdasarkan Cohort Analysis**
   - Identifikasi bulan dengan retensi pelanggan rendah dan tingkatkan strategi pemasaran pada bulan tersebut.
   - Gunakan program referral untuk meningkatkan retensi pelanggan dalam jangka panjang.

---

## 📌 Catatan Tambahan
- Pastikan dataset yang digunakan memiliki struktur yang sesuai dengan format yang diperlukan oleh analisis ini.
- Anda dapat menyesuaikan batasan skor RFM untuk segmentasi yang lebih spesifik sesuai kebutuhan bisnis Anda.
