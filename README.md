# Laporan Proyek Machine Learning - Christopher Alvin Buana

## Domain Proyek
Dalam bisnis tentu diperlukan pemahaman terhadap pasar, terutama dalam bisnis asuransi. Menurut [Wikipedia](https://id.wikipedia.org/wiki/Asuransi), Asuransi adalah pertanggungan atau perjanjian antara dua belah pihak, dimana pihak satu berkewajiban membayar iuran/kontribusi/premi. ketika bisnis asuransi sudah bisa dijalankan, kita perlu memahami bagaimana cara menawarkan produk asuransi tersebut kepada pelanggan yang tepat, baik itu adalah pelanggan baru maupun pelanggan lama. Oleh karena itu, sangat penting bagi sebuah perusahaan untuk mengerti pasar yang mereka sedang kuasai. Di dalam projek ini, saya memilih untuk menggunakan data dari sebuah perusahaan asuransi. Data ini berisi tentang data pribadi pelanggan seperti jenis kelamin, usia, kepemilikan sim dan tempat tinggal. Dalam data ini juga terdapat apabila pelanggan sudah mempunyai asuransi kendaraan, umur dari kendaraan pelanggan, konfirmasi bahwa kendaraan tersebut sudah pernah rusak, pembayaran per tahun pelanggan, jumlah hari pelanggan terikat pada perusahaan tersebut,dan respon terhadap hasil tawaran asuransi. Projek ini dibuat dengan tujuan untuk memprediksi pelanggan yang tertarik kepada produk asuransi kendaraan. Untuk menjawab masalah ini, tentu perlu diketahui siapa pelanggan yang tepat untuk menerima respon tawaran ini. Membuat grafik secara manual hanya akan memakan waktu yang cukup lama. Oleh sebab itu, diperlukan solusi dengan cara analisa dan membuat machine learning model untuk menjawab masalah ini.
## Business Understanding

### Problem Statement
membuat prediksi untuk mengetahui pelanggan yang tepat untuk diberi tawaran produk asuransi kendaraan.

### Goals
Meningkatkan pemasukan perusahaan asuransi dan mempersingkat waktu penawaran.

### Solution statements
Untuk menyelesaikan masalah ini, saya akan mengajukan 4 solusi machine learning model yang sederhana. Yaitu :
- **Random Forest** : Random forest merupakan model ensemble atau model gabungan dari beberapa decision tree dimana ini tentu akan memakan waktu yang lebih lama karena model ini akan menggunakan decision tree dalam jumlah yang banyak dan dari hasil tersebut akan dilakukan voting atau dengan membuat rata-rata agar menghasilkan prediksi yang akurat.
- **XGBoosting Algorithm** : XGBoosting merupakan salah satu model gradient boosting yang 
- **Logistic Regression** :
- **Decision Tree** :

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai data yang Anda gunakan dalam proyek. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya, uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

## Data Preparation
Pada bagian ini Anda menjelaskan teknik yang digunakan pada tahapan Data Preparation. 
- Terapkan minimal satu teknik data preparation dan jelaskan proses yang dilakukan.
- Jelaskan alasan mengapa Anda perlu menerapkan teknik tersebut pada tahap Data Preparation. 

## Modeling
Tahapan ini membahas mengenai model machine learning yang digunakan untuk menyelesaikan permasalahan. 

Jelaskan bagaimana Anda melakukan proses modeling dalam proyek. Misalnya, Anda menggunakan satu algoritma kemudian melakukan improvement dari baseline model atau Anda menggunakan dua atau lebih algoritma kemudian membandingkan performanya.

Sajikan model terbaik Anda sebagai solusi.
Jelaskan pula hasil dari model Anda (misal, hasil prediksi).

## Evaluation
Bagian ini menjelaskan mengenai metrik evaluasi yang digunakan untuk mengukur kinerja model. Sebagai contoh, Anda memiih kasus klasifikasi dan menggunakan metrik **akurasi, precision, recall, dan F1 score**. Jelaskan mengenai beberapa hal berikut:
- Penjelasan mengenai metrik yang digunakan dan bagaimana formulanya
- Kelebihan dan kekurangan metrik
- Bagaimana cara menerapkannya ke dalam kode.

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
_Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_

