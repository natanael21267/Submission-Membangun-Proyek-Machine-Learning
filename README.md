Submission-Membangun-Proyek-Machine-Learning
📊 PROYEK MACHINE LEARNING   ## Clustering dan Klasifikasi untuk Analisis Transaksi Keuangan
# INFORMASI DATASET

Dataset ini menyajikan gambaran mendalam mengenai perilaku transaksi dan pola aktivitas keuangan, sehingga sangat ideal untuk eksplorasi **deteksi penipuan (fraud detection)** dan **identifikasi anomali**. Dataset ini mencakup **2.512 sampel data transaksi**, yang mencakup berbagai atribut transaksi, demografi nasabah, dan pola penggunaan.

Setiap entri memberikan wawasan komprehensif terhadap perilaku transaksi, memungkinkan analisis untuk **keamanan finansial** dan pengembangan model prediktif.

## Tujuan Proyek

Tugas pada proyek ini adalah:

1. Membangun **model Clustering** untuk mengelompokkan pola transaksi
2. Menggunakan hasil clustering sebagai **label Target**
3. Membangun **model Klasifikasi** menggunakan Decision Tree
4. Mengevaluasi performa model klasifikasi

Model clustering akan digunakan untuk menemukan pola tersembunyi dalam data transaksi, kemudian hasil cluster tersebut akan digunakan sebagai label untuk model klasifikasi.

---

## Fitur Utama Dataset

- **TransactionID**: Pengidentifikasi unik alfanumerik untuk setiap transaksi  
- **AccountID**: ID unik untuk setiap akun, dapat memiliki banyak transaksi  
- **TransactionAmount**: Nilai transaksi dalam mata uang  
- **TransactionDate**: Tanggal dan waktu transaksi terjadi  
- **TransactionType**: Tipe transaksi berupa Credit atau Debit  
- **Location**: Lokasi geografis transaksi  
- **DeviceID**: ID perangkat yang digunakan dalam transaksi  
- **IPAddress**: Alamat IPv4 yang digunakan saat transaksi  
- **MerchantID**: ID unik merchant  
- **AccountBalance**: Saldo akun setelah transaksi berlangsung  
- **PreviousTransactionDate**: Tanggal transaksi terakhir pada akun  
- **Channel**: Kanal transaksi seperti Online, ATM, atau Branch  
- **CustomerAge**: Usia pemilik akun  
- **CustomerOccupation**: Profesi pengguna  
- **TransactionDuration**: Lama waktu transaksi (detik)  
- **LoginAttempts**: Jumlah upaya login sebelum transaksi  

---

## Alur Machine Learning

Tahapan yang dilakukan pada proyek ini:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Data Preprocessing
5. Clustering menggunakan K-Means
6. Interpretasi Cluster
7. Menyimpan hasil clustering
8. Klasifikasi menggunakan Decision Tree
9. Evaluasi Model
10. Penyimpanan Model
