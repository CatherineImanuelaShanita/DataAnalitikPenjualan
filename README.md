# Data Analitik Penjualan


# Soal atas Dana Analitik Penjualan terkait Analisis Data:

Sebuah perusahaan ritel besar, "Toko Subur Makmur", memiliki beberapa cabang di seluruh kota. Manajer cabang di Kota A ingin menganalisis penjualan barang untuk bulan Mei 2024. Mereka memiliki data penjualan yang mencakup informasi tentang tanggal penjualan, faktur penjualan, jenis kelamin pelanggan, barang yang dibeli, dan total harga barang yang dibeli. Informasi tambahan yang berkaitan dengan Toko Subur Makmur adalah, ada analisis tren yang dilakukan untuk selama 10 hari di periode Bulan Mei 2024.

Berikut adalah informasi lebih rinci terkait perusahaan Toko Subur Makmur adalah:


1. Tabel data penjualan tersedia dalam format CSV (Comma Separated Values).
   tanggal_penjualan;nomor_faktur;jenis_kelamin_pelanggan;jenis_barang;jumlah;total Harga
2024-05-01;F1001;Wanita;Elektronik;2;1200
2024-05-04;F1002;Pria;Pakaian;9;1350
2024-05-04;F1003;Wanita;Makanan;5;150
2024-05-06;F1004;Pria;Elektronik;3;1800
2024-05-10;F1005;Wanita;Pakaian;7;1050
2024-05-17;F1006;Pria;Elektronik;4;2400
2024-05-18;F1007;Pria;Makanan;3;240
2024-05-19;F1008;Pria;Makanan;9;270
2024-05-22;F1009;Wanita;Elektronik;1;600
2024-05-22;F1010;Wanita;Pakaian;8;1200
2024-05-23;F1011;Pria;Elektronik;5;3000
2024-05-26;F1012;Wanita;Pakaian;6;900
2024-05-29;F1013;Pria;Makanan;4;120
2024-05-29;F1014;Wanita;Pakaian;3;450
2024-05-31;F1015;Wanita;Pakaian;2;300

2. Kolom dalam tabel termasuk:
Tanggal Penjualan: Unik untuk setiap transaksi penjualan.
Nomor Faktur: Unik untuk setiap transaksi penjualan.
Jenis Kelamin Pelanggan: Pria atau Wanita.
Jenis Barang: Kategori barang yang dibeli, yaitu: Elektronik, Pakaian, Makanan.
Jumlah: Jumlah barang yang dibeli dalam transaksi tertentu.
Total Harga: Total harga dari transaksi tersebut.


| Tanggal Penjualan  | No. Faktur | Jenis Kelamin Pelanggan | Jenis Barang |
| ------------------ | ---------- | ----------------------- | ------------ |
|     2024-05-01     |    F1001   |         Wanita          |  Elektronik  |
|     2024-05-04     |    F1002   |           Pria          |  Pakaian     |
|     2024-05-04     |    F1003   |         Wanita          |  Makanan     |
|     2024-05-06     |    F1004   |           Pria          |  Elektronik  |
|     2024-05-10     |    F1005   |         Wanita          |  Pakaian     |
|     2024-05-17     |    F1006   |           Pria          |  Elektronik  |
|     2024-05-18     |    F1007   |           Pria          |  Makanan     |
|     2024-05-19     |    F1008   |           Pria          |  Makanan     |
|     2024-05-22     |    F1009   |         Wanita          |  Elektronik  |
|     2024-05-22     |    F1010   |         Wanita          |  Pakaian     |
|     2024-05-23     |    F1011   |           Pria          |  Elektronik  |
|     2024-05-26     |    F1012   |         Wanita          |  Pakaian     |
|     2024-05-29     |    F1013   |           Pria          |  Makanan     |
|     2024-05-29     |    F1014   |         Wanita          |  Pakaian     |
|     2024-05-31     |    F1015   |         Wanita          |  Pakaian     |


| Jumlah | Total Harga |
| ------ | ----------- |
|   2    |    1200     |
|   9    |    1350     |
|   5    |     150     |
|   3    |    1800     |
|   7    |    1050     |
|   4    |    2400     |
|   3    |     240     |
|   9    |     270     |
|   1    |     600     |
|   8    |    1200     |
|   5    |    3000     |
|   6    |     900     |
|   4    |     120     |
|   3    |     450     |
|   2    |     300     |
*Tabel dan soal merupakan ilustrasi


Tugas Anda sebagai seorang Data Analyst adalah:

a. Mengimpor data dari file CSV ke dalam program Python.
b. Menggunakan Jupyter Notebook sebagai preferensi dalam membuat analisis data terkait penjualan.
c. Menghitung total penjualan dan rata-rata harga penjualan untuk setiap jenis barang, dan total pembelian pelanggan.
d. Menganalisis total penjualan dan total pendapatan untuk setiap jenis barang, dan total pembelian 
e. Menganalisis preferensi pembelian berdasarkan jenis kelamin pelanggan.
e. Menghasilkan laporan yang mencakup semua analisis di atas.


# Penyelesaian dari Data Analyst

Berikut adalah langkah-langkah yang perlu Anda lakukan dalam analisis ini:
Pengumpulan Data: Memuat data dari file CSV ke dalam Python.
1. Data Cleaning: Membersihkan data dari nilai-nilai yang hilang atau tidak valid.
2. Data Transformation: Mengubah data ke dalam format yang sesuai untuk analisis, seperti mengubah format tanggal, mengkategorikan data, dll.
3. Exploratory Data Analysis (EDA): Melakukan analisis eksploratif untuk memahami distribusi data, outlier, dan hubungan antar variabel.
4. Modeling Data: Membuat model prediktif untuk memprediksi tren penjualan di masa mendatang.
5. Validasi dan Tuning Model: Memvalidasi model dan melakukan tuning untuk meningkatkan kinerjanya.
6. Interpretasi dan Penyajian Hasil: Menginterpretasikan hasil analisis dan menyajikannya dalam bentuk yang mudah dipahami.
7. Deploy dan Monitoring: Men-deploy model ke dalam lingkungan produksi dan memantau kinerjanya.
8. Maintenance dan Iterasi: Melakukan pemeliharaan dan iterasi model berdasarkan data baru dan feedback yang diterima.

# Hasil Analisis

l. Histogram Data Pembelian

![Histogram Data Pembelian](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/1b74b882-9f4f-493f-9727-191b0bf268e9)


2. Total Pendapatan Berdasarkan Jenis Barang
   
![Total Pendapatan Berdasarkan Jenis Barang](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/a56ca0d1-e3bc-4781-9234-30d740e67fa7)

3. Total Pendapatan Berdasarkan Jenis Kelamin

![Total Pendapatan Berdasarkan Jenis Kelamin](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/2ce42573-de1a-4095-96f7-b414be07ff07)

4. Total Penjualan Berdasarkan Jenis Barang

![Total Penjualan Berdasarkan Jenis Barang](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/d2cbd12a-c228-4896-9fc4-a324645b5422)

5. Total Penjualan Berdasarkan Jenis Kelamin

![Total Penjualan Berdasarkan Jenis Kelamin](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/efd0fd3a-2a19-4f81-bf07-cec55486e821)

6. Diagram Scatterplot Jenis Barang

![Diagram Scatterplot Jenis Barang](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/5f0bc17e-17e1-46ad-b970-b0615418e238)

7. Diagram Scatterplot Jumlah Barang

![Diagram Scatterplot Jumlah Barang](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/19faa8d4-8983-4fa2-a3f3-44b2a9566dcf)

8. Analisis Tren Berdasarkan Penjualan Bulan Mei 2024 (Keseluruhan)

![Analisis Tren Berdasarkan Penjualan Bulan Mei Periode Tgl 1-10](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/91fa3012-2c98-4987-95b6-6b065541f6f2)

9. Analisis Tren Berdasarkan Penjualan Bulan Mei 2024 (Tgl 1-10)

![Analisis Tren Berdasarkan Penjualan Bulan Mei 2024](https://github.com/CatherineImanuelaShanita/DataAnalitikPenjualan/assets/167211624/b94ddc8e-de53-44d5-96e9-a2be95d0c7ec)

