Anatomy of a Bestseller: Exploratory Data Analysis (2023-2025)

Deskripsi Proyek
Proyek ini adalah portofolio Data Analisis yang bertujuan untuk membedah karakteristik buku-buku laris (*bestseller*) di pasaran. Dengan menggunakan teknik Exploratory Data Analysis (EDA), analisis ini menggali tren terkait genre yang paling diminati, dominasi penulis, serta format fisik buku (jumlah halaman) yang paling sering masuk ke dalam daftar buku terlaris. 

Tujuan utama dari proyek ini adalah untuk memberikan wawasan bisnis (*business insights*) yang dapat digunakan oleh penerbit buku (publisher) atau penulis baru dalam merancang strategi penerbitan mereka.

ertanyaan Bisnis yang Dijawab
1. Genre Dominan: Dari puluhan genre yang ada, genre apa yang paling merajai daftar *bestseller*?
2. Distribusi Penulis: Apakah pasar didominasi oleh segelintir penulis besar yang sama, atau tersebar ke banyak penulis beragam?
3. **Karakteristik Fisik:** Berapa rata-rata ketebalan (jumlah halaman) dari sebuah buku yang sukses menjadi *bestseller*?

Tools & Library yang Digunakan
* **Bahasa Pemrograman:** Python
* **Environment:** Jupyter Notebook
* **Data Manipulation & Cleaning:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn

Proses Data Cleaning
Sebelum dianalisis, dataset mentah melalui beberapa tahap pembersihan untuk memastikan akurasi:
* Menstandarisasi format kolom `Publishing date` dari berbagai format teks menjadi format Datetime standar (`YYYY-MM-DD`).
* Membersihkan kolom `Rating` dan `price` dari format teks/simbol (seperti `$` dan `out of 5 stars`) menjadi tipe data numerik (*float*).
* Menangani nilai yang hilang (*missing values*) pada kolom-kolom krusial untuk menjaga integritas visualisasi data.

Wawasan Utama (Key Insights)
Berdasarkan analisis yang telah dilakukan, ditemukan beberapa poin penting:
* **Peluang Pasar pada Genre Tertentu:** Genre **'Reading & Writing'** terbukti sangat mendominasi daftar *bestseller*. Hal ini menunjukkan permintaan pasar yang tinggi dan bisa menjadi ceruk fokus yang menguntungkan bagi penerbit.
* **Tingkat Keberagaman Penulis yang Sehat:** Pasar tidak dimonopoli oleh segelintir nama. Sebagian besar penulis bintang hanya muncul satu kali dalam daftar ini. Bagi penerbit, ini berarti risiko bisnis lebih rendah karena kesuksesan tidak bergantung mutlak pada satu atau dua penulis saja.
* **Format Pendek Lebih Mendominasi:** Walaupun rata-rata ketebalan buku adalah 122 halaman, nilai tengah (*median*) berada di angka **36 halaman**. Buku dengan format yang sangat pendek (seperti *board books* atau buku anak) terbukti sangat sukses. Ini mengisyaratkan bahwa untuk menjadi *bestseller*, buku tidak harus tebal.

ara Menjalankan Proyek Ini
1. Clone repositori ini ke komputer Anda: `git clone [URL_GITHUB_ANDA]`
2. Pastikan Anda telah menginstal Python dan library yang dibutuhkan (`pandas`, `matplotlib`, `seaborn`, `numpy`).
3. Buka file `Books_Sales.ipynb` menggunakan Jupyter Notebook atau Visual Studio Code.
4. Jalankan setiap sel (*cell*) secara berurutan untuk melihat proses pembersihan data dan hasil visualisasinya.
