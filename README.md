# h8dsft_P0W2
Graded Challenge 2 from Hacktiv8 Full Time Data Science

## Assignment Instructions

*Graded Challenge 2* dikerjakan dalam format ***notebook*** dengan beberapa **kriteria wajib** di bawah ini:

1. Gunakan library **Numpy** untuk kebutuhan pengolahan tipe data array dan beberapa operasi matematika.
2. Jika diperlukan, silahkan menggunakan library **Scipy**, **Numpy**, **Sympy** atau lainnya untuk melakukan perhitungan matematika.
3. Gunakan library **PIL** untuk membaca dan pengolahan gambar
4. Untuk visualisasi, gunakan library **Matplotlib**
5. *Objektif* dari project ini adalah mendeteksi edge suatu gambar dan melakukan operasi perkalian matriks. Sebagai clue, berikut langkah-langkah untuk mendeteksi edge:
    1. Hitung vektor gradien (turunan parsial) masing-masing pixel untuk masing-masing sumbu x dan y
    2. Hitung gradient magnitude tiap pixel
    3. Jika nilai magnitude melebihi angka threshold, maka edge terdeteksi (Biasanya threshold ~ 30)
6. Untuk operasi matriks, buat matriks dengan nilai apapun yang bersesuaian dengan ukuran gambar dan sesuai dengan aturan perkalian matriks.
7. **Catatan**: Anda dapat menggunakan metode apapun, baik menggunakan library atau melakukan perhitungan dengan metode numerik.
8. *Project* dinyatakan selesai dan diterima untuk dinilai jika saat dilakukan `Run All` pada *notebook*, semua *cell* berhasil tereksekusi sampai akhir.
9. Isi *notebook* harus mengikuti *outline* di bawah ini:
   1. Perkenalan\
   Bab pengenalan harus diisi dengan identitas, *metode* yang ingin dilakukan guna mencapai tujuan.
   2. *Import* pustaka yang dibutuhkan\
   *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
   3. *Data Loading*\
   Bagian ini berisi proses *data loading* yang kemudian dilanjutkan dengan *explorasi data* secara sederhana.
   4. *Data Preprocessing*\
   Bagian ini berisi proses penyiapan data berupa preprocessing sebelum dilakukan *processing* lebih lanjut. Proses preprocessing dapat berupa filtering komponen warna ataupun ubah gambar warna menjadi grey, dan lain sebagainya.
   5. *Image Processing*\
   Bagian ini berisi kode-kode serta perhitungan-perhitungan untuk mencapai tujuan.
   6. Hasil dan Kesimpulan\
   Pada bab terakhir ini, **harus berisi** kesimpulan yang mencerminkan hasil yang didapat dengan membandingkan hasil untuk beberapa nilai threshold dan juga hasil perkalian matriks yang telah dilakukan (dalam visualisasi gambar).
10. *Notebook* harus diupload dalam akun GitHub masing-masing siswa untuk selanjutnya dinilai.

## Assignment Objectives

*Graded Challenge 2* ini dibuat guna mengevaluasi Linear Algebra dan Calculus sebagai berikut:

- Mampu memuat data gambar
- Mampu melakukan transformasi tipe data gambar ke data yang siap olah
- Mampu melakukan eksplorasi data gambar
- Mampu menerapkan konsep kalkulus pada pengolahan citra menggunakan library atau metode numerik from scratch
- Mampu menerapkan konsep linear algebra pada pengolahan citra menggunakan library atau metode numerik from scratch
- Mampu memvisualisasikan gambar menggunakan matplotlib
