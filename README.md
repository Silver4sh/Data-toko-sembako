# Data Toko Sembako

 **Sistem pelaporan stok dan penjualan barang di toko sembako.**  
Script ini digunakan untuk **mengolah data pemasukan dan penjualan barang**, serta menghasilkan laporan dalam format **Excel** yang mencakup analisis stok, prediksi habisnya stok, serta tren penjualan.

---

## Fitur Utama
✅ **Pelacakan Stok Barang** → Menampilkan total barang masuk, terjual, dan sisa stok  
✅ **Prediksi Kapan Stok Habis** → Berdasarkan rata-rata penjualan dalam 7 hari terakhir  
✅ **Top 10 Pembeli** → Menampilkan pembeli dengan total pembelian terbesar  
✅ **Laporan Penjualan Harian** → Rekap harian jumlah barang terjual dan total nominal penjualan  
✅ **Barang Terlaris & Tidak Laku** → Menampilkan 5 barang paling laku dan 5 barang yang jarang dibeli  
✅ **Identifikasi Barang Hampir Habis** → Barang dengan stok di bawah **10 unit**  
✅ **Grafik Penjualan Barang Terlaris** → Otomatis disimpan dan dimasukkan ke dalam laporan Excel  

---

## Struktur Output Laporan
Setelah menjalankan script, akan dihasilkan file **`Laporan_Sembako.xlsx`** yang terdiri dari beberapa sheet:

| **Sheet Name**         | **Deskripsi** |
|-----------------------|--------------|
| **Stok Barang**      | Laporan stok barang (Total masuk, terjual, dan sisa) |
| **Top 10 Pembeli**   | Pembeli terbesar berdasarkan total nominal pembelian |
| **Penjualan Harian** | Rekap penjualan harian (nominal & kuantum) |
| **Barang Terlaris**  | 5 barang yang paling banyak terjual |
| **Barang Tidak Laku** | 5 barang yang paling sedikit terjual |
| **Barang Hampir Habis** | Barang dengan stok di bawah batas minimal (10 unit) |
| **Prediksi Stok**    | Estimasi kapan stok akan habis berdasarkan rata-rata penjualan |
| **Grafik Penjualan** | Grafik barang terlaris secara otomatis dimasukkan ke dalam Excel |