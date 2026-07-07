# Algoritma Regresi Linier dengan Python

Repositori ini berisi implementasi algoritma *Supervised Learning*, khususnya **Regresi Linier Sederhana (Simple Linear Regression)** menggunakan bahasa pemrograman Python. Proyek ini dibuat sebagai bagian dari tugas/praktikum mata kuliah Teknik Informatika.

## 📂 Struktur Repositori

Repositori ini terdiri dari dua studi kasus utama:

1. **`LinearRegression_BabyWeight.ipynb`**
   * **Deskripsi:** Model regresi linier untuk memprediksi berat bayi yang akan dilahirkan berdasarkan berat badan ibu hamil.
   * **Dataset:** Dataset sederhana berskala kecil yang dibuat secara manual (*hardcoded*) di dalam *notebook* menggunakan struktur *Dictionary* dan Pandas DataFrame.

2. **`LinearRegression_Salary.ipynb`**
   * **Deskripsi:** Model regresi linier untuk memprediksi besaran gaji (*Salary*) seseorang berdasarkan jumlah tahun pengalaman kerjanya (*Years of Experience*).
   * **Dataset:** Menggunakan *file* eksternal `Salary_Data.csv`. Data dibagi menjadi *Training Set* (70%) dan *Test Set* (30%) untuk menguji keakuratan model.

3. **`Salary_Data.csv`**
   * *File* berekstensi *Comma Separated Values* yang berisi dataset riwayat pengalaman kerja dan gaji.


## 🛠️ Teknologi & Pustaka (Libraries)

Proyek ini menggunakan beberapa pustaka Python standar untuk *Data Science* dan *Machine Learning*:
* **[Python 3](https://www.python.org/)**: Bahasa pemrograman utama.
* **[Jupyter Notebook](https://jupyter.org/)**: Lingkungan kerja interaktif untuk menulis kode dan melihat hasil visualisasi.
* **[Pandas](https://pandas.pydata.org/)**: Untuk manipulasi dan analisis data (DataFrame).
* **[NumPy](https://numpy.org/)**: Untuk komputasi array dan operasi matematika.
* **[Matplotlib](https://matplotlib.org/)**: Untuk membuat visualisasi grafik *scatter plot* dan garis regresi.
* **[Scikit-Learn](https://scikit-learn.org/)**: Untuk memanggil algoritma `LinearRegression` dan membagi dataset (`train_test_split`).

## 🚀 Cara Menjalankan Kode Secara Lokal

Jika Anda ingin menjalankan kode ini di komputer Anda sendiri, ikuti langkah-langkah berikut:

1. *Clone* repositori ini ke komputer lokal Anda:
   ```bash
   git clone https://github.com/zanrizkir/Algoritma-Regresi-Linier
