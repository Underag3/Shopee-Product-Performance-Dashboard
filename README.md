# 🛒 Shopee Product Performance Dashboard

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Looker Studio](https://img.shields.io/badge/Looker_Studio-Dashboard-4285F4.svg)](https://lookerstudio.google.com/)

**[Lihat Live Dashboard di Sini](https://datastudio.google.com/reporting/526c8331-9037-49aa-9a81-361d86d54bc2)**

## 📌 Gambaran Umum Proyek
Proyek ini bertujuan untuk menganalisis dan memvisualisasikan performa produk di *platform* e-commerce Shopee. Melalui dasbor interaktif yang dibangun menggunakan Google Data Studio (Looker Studio), pengguna dapat memantau berbagai metrik utama bisnis seperti [sebutkan metrik utama, misal: total penjualan, produk terlaris, atau tren pendapatan]. 

Proses persiapan data (pembersihan dan transformasi) dilakukan sepenuhnya menggunakan Python sebelum diimpor ke dalam perangkat visualisasi.

## 🛠️ Alat dan Teknologi
* **Bahasa Pemrograman:** Python (via Jupyter Notebook)
* **Library Pemrosesan Data:** [Sebutkan library, misal: Pandas, NumPy]
* **Visualisasi & Dasbor:** Google Data Studio / Looker Studio
* **Sumber Data:** [Sebutkan asal data, misal: Hasil web scraping, Kaggle, atau dataset internal]

## 📂 Struktur Repositori
* `Data Cleaning.ipynb` : Notebook yang berisi langkah-langkah pembersihan data mentah, penanganan *missing values*, dan transformasi format data agar siap digunakan untuk analisis.
* `[Nama_File_Dataset_Clean.csv]` : *(Opsional - Jika Anda mengunggah datanya)* Dataset hasil pembersihan yang digunakan dalam dasbor.

## 💡 Insight Utama (Key Findings)
1. **Fenomena Impulse Buying & Repeat Order:** Rasio Sales-to-Favorite mencapai 1.27 (127%), menandakan konsumen sering kali langsung melakukan pembelian tanpa melakukan 'bookmarking/favorit' terlebih dahulu, atau melakukan pembelian berulang.
2. **Kategori Home Appliances sebagai Revenue Driver Utama:** Menyumbang pendapatan tertinggi sebesar Rp242,2 Juta meskipun volume penjualannya lebih rendah, mengindikasikan harga rata-rata produk (AOV) yang tinggi namun memerlukan evaluasi ketat pada kualitas karena memiliki rating terendah (4.41).
3. **Tingginya Perilaku Window Shopping pada Fashion Wanita:** Kategori pakaian dan tas wanita memiliki volume minat (Favorite) yang besar, namun memiliki rasio konversi terendah (< 0.75), menunjukkan konsumen membutuhkan stimulus tambahan (seperti voucher atau gratis ongkir) untuk melakukan checkout.
4. **Groceries & Pets Memiliki Loyalitas Tertinggi:** Mencatat rasio Sales/Favorite tertinggi sebesar 2.76, menjadikannya kategori paling potensial untuk program langganan (subscription-based marketing).

## 🚀 Cara Menjalankan Proyek Lokal (Tahap Persiapan Data)
Jika Anda ingin melihat atau memodifikasi proses pembersihan data:

1. Kloning repositori ini:
   ```bash
   git clone [https://github.com/Underag3/Shopee-Product-Performance-Dashboard.git](https://github.com/Underag3/Shopee-Product-Performance-Dashboard.git)

2. Pastikan Anda telah menginstal library yang dibutuhkan. Anda bisa menginstalnya melalui pip:

  ```bash
  pip install pandas numpy jupyter
  ```
3. Jalankan Jupyter Notebook:

  ```
  jupyter notebook
  ```
4. Buka file Data Cleaning.ipynb dan jalankan sel-sel di dalamnya.

## 👤 Author
Mohammad Tyas Subianto
