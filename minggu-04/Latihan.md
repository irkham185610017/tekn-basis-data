# LATIHAN
---
pada latihan ini yaitu belajar tentang redis untuk menjalankan latihan ini kita bisa menggunakan Docker,fungsi redis yaitu sebagai penyimpanan data nilai utama di dalam memori yang super cepat dengan sumber terbuka untuk digunakan sebagai database, cache, broker pesan, dan antrean. Proyek ini dimulai ketika Salvatore Sanfilippo, pengembang awal Redis, mencoba meningkatkan skalabilitas startup Italia miliknya. Redis kini memberikan respons dalam waktu di bawah satu milidetik yang memungkinkan jutaan permintaan per detik untuk aplikasi real-time pada Permainan, Ad-Tech, Layanan Finansial, Layanan Kesehatan, dan IoT. Redis adalah pilihan populer untuk caching, manajemen sesi, permainan, papan peringkat, analisis real-time, geospasial, tumpangan berkendara, obrolan/perpesanan, streaming media, dan aplikasi pub/sub.


# LATIHAN 1 (MENJALANKAN REDIS SERVER MENGUNAKAN DOCKER)

pertama untuk melakukan penginstallan redis dalam sebuah terminal,kita harus menginput apt install redis tools yang dimana redis akan diinstal 
dan untuk membersihkan file sampah setelah penginstallan,kita harus menginput apt-cache search redis yang bertujuan untuk menghapus file yang sudah tidak diperlukan lagi
! [Gambar 1](Screenshot_3.png)
untuk pengaksesan redis, langkah pertama yang kita harus lakukan yaitu kembali ke direktori dimana redis tersebut terinstall, kemudian kita hubungkan dengan menginputkan redis-cli.
! [Gambar 2](Screenshot_5.png) 


# LATIHAN 2 (Dengan menggunakan Docker, koneksikan redis-cli ke server redis yang anda jalankan pada langkah pertama)

pada latihan 2 ini tidak harus dihubungkan redis-cli dengan server redis,karena sudah terhubung ke terminal linux tersebut

# LATIHAN 3 (Kerjakan Materi dan Penjelasan nomor 4, khusus untuk cli commands serta data types)

- mengentrykan data set pada key
! [Gambar 3](Screenshot_6.png)
- menampilkan data get 
! [Gambar 4](Screenshot_7.png)
- menampilakan jumlah data
- getrange menampilakan titik data poin 
- append menggabungkan data
! [Gambar 5](Screenshot_8.png)