<h1> PRAKTIKUM 1 </h1>
<h2> LANGKAH 1 </h2>
<img width="491" alt="image" src="https://github.com/yurisaprilian/praktik-1/assets/160213851/69ddb122-9de2-46fe-86e9-61cb49fbe6d5">

langkah pertama jalankan Apache dan MySQL pada XAMPP

<h2> LANGKAH 2 </h2>
<img width="469" alt="image" src="https://github.com/yurisaprilian/praktik-1/assets/160213851/6dc52825-59ab-4b30-a385-e1f6f3497039">

ke pencarian lalu masuk ke http://localhost/phpmyadmin dan membuat database baru

<h2> LANGKAH 3 </h2>
<img width="417" alt="image" src="https://github.com/yurisaprilian/praktik-1/assets/160213851/bd87df6c-136e-45e5-a1fb-288950d19d5c">

merestore database penjualan_produk melalui menu inport

<h2> LANGKAH 4 </h2>
<img width="417" alt="image" src="https://github.com/yurisaprilian/praktik-1/assets/160213851/3bdd5f60-0ce3-4053-8db2-34730abde3f6">

tabel akan muncul setelah file selesai di restore

<h1> PRAKTIKUM 2 </h1>
<img width="572" alt="image" src="https://github.com/yurisaprilian/praktik-1/assets/160213851/bae2851d-8ddd-4bcf-a78e-6018602e572c">

Designer Menu 

<h1> PRAKTIKUM 3 </h1>
<h2> QUESTION 1 </h2>
kode_penjualan = 3
tgl = 8 Februari 2021
kasir = Dini
total_penjualan = 10.000

![image](https://github.com/yurisaprilian/praktik-1/assets/160213851/c52e3057-5d30-4f0d-b73c-50711f781666)
Jawaban . Caranya pergi ke menu penjualan lalu insert masukkan data yang ingin ditambahkan 

<h2> QUESTION 2 </h2>

kode_penjualan = 2
tgl = 10 Februari 2021
kasir = Dini
total_penjualan = 20.000

![image](https://github.com/yurisaprilian/praktik-1/assets/160213851/5dab40f6-3759-49e5-87c5-220c601c4ff3)

Jawaban . Caranya tinggal ulangi proses yang sama seperti yang diatas 

<h2> QUESTION 3 </h2>
Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan
![image](https://github.com/yurisaprilian/praktik-1/assets/160213851/dc577c7b-05e1-47e6-a209-2e9af4f53985)


 Jawaban . kode penjualan sudah ada jadi tidak boleh sama, maka pada opsi value diganti 4 agar tidak terjadi error 
 
 <h2> QUESTION 4 </h2>
 kode_penjualan = 2
kode_barang = 3
harga = 5.000
jumlah = 5

![image](https://github.com/yurisaprilian/praktik-1/assets/160213851/05e5bf9b-7a6e-44df-97b4-2e6d3503912d)

Jawaban . Data bisa ditambahkan karena data sudah tervalidasike (kode_penjualan dan kode_barang). Sudah masuk ke dalam tabel, maka data detail_penjualan dan kode_penjualan bisa ditambahkan.

 <h2> QUESTION 5 </h2>
Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan

Jawaban. Memiliki akses ke dalam data, mengetahui tipe data dan nama kolom, cara menambahkannya.
 
 <h2> QUESTION 6 </h2>
 Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data

Jawaban. Kode penjualan “2” digunakan sebanyak dua kali ini dapat membuat kesulitan dalam melacak data yang dibuat

<h1> PRAKTIKUM 4 </h1>

add data "detail_penjualan"
 <h2> QUESTION 7 </h2>
kode_penjualan = 2
kode_barang = 3
harga = 5.000
jumlah = 5

apakah bisa ditambahkan? jelaskan alasannya?


![image](https://github.com/yurisaprilian/praktik-1/assets/160213851/0162a0cd-bf88-4121-894d-c7865d771070)

Jawaban . Tidak bisa ditambahkan, karena data sudah digunakan 

 <h2> DELETING </h2>
![image](https://github.com/yurisaprilian/praktik-1/assets/160213851/d8e079d5-2ddc-496a-a593-7099d73de402)

Jawaban. Tidak bisa ditambahkan lagi, karena relasi antar tabel sudah dihapus, maka kode_pembelian dan detail_penjualan tidak memiliki referensi. 

 <h2> LAST QUESTION </h2>
 Ulangi kembali langkah ke-1 pada praktikum 4. Apakah data dapat ditambahkan? jelaskan alasannya

jawaban. meskipun relasi kedua data dihapus, tetap saja data penjualan ke 2 sudah ada, tetap tidak bisa di tambahkan dengan kode penjualan 2.
