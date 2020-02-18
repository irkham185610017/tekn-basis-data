#LAPORAN PRAKTIKUM TEKNOLOGI BASIS DATA PERTEMUAN KE-2
---
#LATIHAN 1

Install MongoDB seperti halnya aplikasi biasa, dan secara default akan tersimpan di C:\Program and Files\mongodb. Kita bisa mengubah lokasi installnya dengan memilih custom pada saat instalasi. Asumsi MongoDB terinstall di C:\mongodb, dan binary nya berada di folder C:\mongodb\bin.

#Setting MongoDB environment
MongoDB membutuhkan folder data untuk menyimpan database, buatlah folder dengan nama dan lokasi c:\data\db

#Start Server MongoDB
Untuk menjalankan daemon/service MongoDB jalankan peritah di bawah ini lewat Command Prompt :

C:\mongodb\bin\mongod.exe
Perintah diatas akan menjalankan server MongoDB silahkan ditunggu, dan biasanya jika muncul pop up Security Alert dialog box nya Windows tinggal di allow saja.

#Connect ke MonggoDB
Untuk menghubungkan MonggoDB, buka Command Prompt baru lalu jalankan mongo.exe

C:\mongodb\bin>mongo.exe
connecting to: test
>
Jika muncul shell mongoDB seperti di atas berarti kita sudah berhasil terhubung ke server MongoDB dan udah siap pakai mengelola database di MongoDB.


 
#Membuat Config File
Untuk menambahkan file konfigurasi MongoDB buat folder baru c:\data\log terlebih dahulu. Buat sebuah file konfigurasi dengan nama file C:\mongodb\mongod.cfg dan buka file tersebut kemudian masukan konfigurasi systemLog.path dan storage.dbPath.

Isi file mongodb.cfg

systemLog:
    destination: file
    path: c:\data\log\mongod.log
storage:
    dbPath: c:\data\db



---
LISTING LATIHAN 1
![Gambar 1](Screenshot_1.png) ![Gambar 2](Screenshot_2.png) ![Gambar 3](Screenshot_3.png) ![Gambar 4](Screenshot_4.png) ![Gambar 5](Screenshot_5.png) ![Gambar 6](Screenshot_6.png)
![Gambar 7](Screenshot_7.png) ![Gambar 8](Screenshot_8.png) ![Gambar 9](Screenshot_9.png) ![Gambar 10](Screenshot_10.png) ![Gambar 11](Screenshot_11.png) ![Gambar 12](Screenshot_12.png) ![Gambar 13](Screenshot_13.png) ![Gambar 14](Screenshot_14.png) ![Gambar 15](Screenshot_28.png)
---