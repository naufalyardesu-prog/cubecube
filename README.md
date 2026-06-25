# Sistem Pengolahan Pesanan dengan Python

## Deskripsi Program

Program ini dibuat menggunakan konsep Object-Oriented Programming (OOP) untuk mengelola data pesanan pelanggan. Program dapat menyimpan data pesanan, menghitung total pendapatan (revenue), dan menghitung total pajak berdasarkan persentase yang ditentukan.

Pada program ini terdapat beberapa class yang digunakan untuk merepresentasikan data pesanan dan proses pengolahannya. Data pesanan ditambahkan ke dalam sistem, kemudian program akan menghitung total pendapatan dan total pajak secara otomatis.

## Penerapan Encapsulation

Program ini menerapkan konsep **Encapsulation** dengan cara membungkus data dan fungsi yang berkaitan ke dalam sebuah class.

Penerapan sebagai berikut:

* Class `Order` digunakan untuk menyimpan data pesanan seperti ID pesanan, nama pelanggan, tanggal pesanan, dan total harga.
* Class `OrderProcessor` digunakan untuk mengelola kumpulan data pesanan serta melakukan perhitungan total pendapatan dan pajak.

Dengan Encapsulation, data dan proses pengolahan data menjadi lebih terstruktur, mudah dipelihara, dan aman dari perubahan yang tidak diinginkan.

## Pengujian

Program diuji dengan memasukkan 3 data pesanan yang memiliki total harga keseluruhan sebesar Rp600.000

Hasil pengujian menunjukkan bahwa:

* Total pendapatan berhasil dihitung sebesar Rp600.000.
* Pajak 10% berhasil dihitung secara otomatis sebesar Rp60.000.

Dengan demikian, program berjalan sesuai dengan yang diharapkan dan mampu melakukan perhitungan pendapatan serta pajak secara benar.

