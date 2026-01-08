README
======
Judul:
Sistem Fuzzy Rekomendasi Rumah Menggunakan Metode Mamdani

Deskripsi:
Program ini merupakan implementasi Sistem Fuzzy Logic menggunakan metode Mamdani dan defuzzification Centroid untuk menentukan tingkat kelayakan rumah. Sistem fuzzy dibangun secara manual tanpa menggunakan library fuzzy, dengan tujuan mengubah data numerik properti rumah menjadi keputusan berupa skor kelayakan rumah.

Kasus yang digunakan adalah rekomendasi rumah di wilayah Jabodetabek, dengan output berupa 5 rumah terbaik berdasarkan hasil perhitungan sistem fuzzy.

Dataset:
Dataset yang digunakan adalah dataset harga rumah Jabodetabek
(jabodetabek_house_price.csv).

Atribut input yang digunakan:
1. price_in_rp        (Harga rumah)
2. building_size_m2   (Luas bangunan)
3. bedrooms           (Jumlah kamar tidur)

Metode yang Digunakan:
- Metode Inferensi    : Mamdani
- Operator AND        : Minimum (MIN)
- Agregasi Aturan     : Maximum (MAX)
- Metode Defuzzifikasi: Centroid

Bahasa Pemrograman:
Python

Library yang Digunakan:
- pandas
- numpy

Cara Menjalankan Program:
1. Pastikan Python telah terinstall
2. Install library pandas dan numpy
3. Pastikan semua file berada dalam folder yang sama
4. Jalankan program

Output Program:
Program menghasilkan 5 rumah terbaik berdasarkan skor kelayakan rumah
hasil sistem fuzzy. Output disimpan dalam file top_5_rumah_terbaik.cs.

Output berisi informasi:
- Harga rumah
- Luas bangunan
- Jumlah kamar tidur
- Skor kelayakan rumah

Penulis:
Calya Alesita Putri Irawan (103132400020)
Balqis Awaluna Rahmah (103132430011)