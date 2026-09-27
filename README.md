# UTS PBO
## Nama: Muhammad Davi Aditya Pratama
## NIM: 2509119070

### Penjelasan:
Sistem Peminjaman Kamera merupakan Sistem ini merupakan aplikasi berbasis 
konsol (command-line interface) yang dibangun menggunakan bahasa pemrograman Java. 
Aplikasi ini dirancang untuk mengelola proses peminjaman dan pengembalian kamera secara 
terstruktur dengan menerapkan konsep-konsep dasar Object-Oriented Programming (OOP) seperti
Inheritance, Polymorphism, Encapsulation, dan Abstraction. Sistem ini dirancang untuk 
memudahkan tim atau organisasi dalam manajemen kamera yang digunakan.

### Fungsi dan Kegunaan Utama:
1. Manajemen Kategori Kamera: Memisahkan jenis kamera berbasis spesifikasinya (DSLR dan Mirrorless) melalui struktur pewarisan (Inheritance).
2. Pengecekan Ketersediaan Otomatis: Menampilkan daftar unit kamera yang sedang tidak dipinjam
3. Pencatatan Peminjaman: Mencatat transaksi peminjaman baru lengkap dengan ID unik, nama peminjam, nama unit, dan tanggal transaksi secara otomatis.
4. Pengembalian Kamera: Mengubah status peminjaman dari "Dipinjam" menjadi "Selesai" serta mencatat tanggal pengembalian unit.
5. Riwayat Peminjaman: Menampilkan seluruh log peminjaman kamera yang terdaftar di dalam sistem.

### Pilihan menu
<img width="346" height="168" alt="image" src="https://github.com/user-attachments/assets/2c1224a0-64f5-45bb-a515-976d9e06ab16" />

Terdapat 5 pilihan menu pada Sistem Peminjaman Kamera, yaitu:    
1. Lihat Kamera Tersedia  
   <img height="250" alt="image" src="https://github.com/user-attachments/assets/d3f41b56-f903-40e6-905a-86bcdfceceed" />  
   Pada menu ini, kita dapat melihat kamera yang tersedia atau tidak dipinjam beserta tipennya yaitu DSLR atau mirrorless. Pada menu ini tertampil juga 4 Kamera
   yang tersedia beserta kelebihannya masing-masing yaitu Canon EOS 90D, Sony Alpha A7 III, Nikon Z6 dan Canon 600d.
   
2. Pinjam Kamera  
   <img height="350" alt="image" src="https://github.com/user-attachments/assets/ad23780f-e586-4d9c-8164-d43e2d448da7" />  
   Pada menu ini, kita dapat meminjam kamera yang tersedia. Untuk meminjam cukup input nama peminjam, kamera yang ingin dipinjam dan lama peminjaman yang cukup menginput angka saja dengan akumulasi hari.
   <img height="45" alt="image" src="https://github.com/user-attachments/assets/e9582052-ab7c-4807-9ceb-30dc90343234" />  
   Gambar diatas merupakan bukti peminjaman.

3. Kembalikan Kamera  
   <img width="927" height="230" alt="image" src="https://github.com/user-attachments/assets/dd972cb8-2ecb-4f97-965e-a0ba79840965" />  
   Pada menu ini, kita dapat menginput data kamera yang sudah dikembalikan. Untuk mengembalikannya cukup input id peminjaman saja maka sistem akan mengetahui
   kamera mana yang dikembalikan.  
   <img width="987" height="61" alt="image" src="https://github.com/user-attachments/assets/2099255f-edcc-47af-a695-d94199207934" />  
   Gambar diatas merupakan bukti pengembalian kamera dari peminjaman sebelumnya.
   
4. Lihat Semua Peminjaman
   <img width="987" height="200" alt="image" src="https://github.com/user-attachments/assets/d46b2302-6a45-45ff-b604-2cd981f19204" />  
   Pada menu ini akan tertampil kamera yang telah dipinjam. Dimenu ini juga dapat terlihat status dari peminjaman kamera tersebut, apakah selesai atau masih dipinjam.
   
5. Keluar  
   <img width="412" height="148" alt="image" src="https://github.com/user-attachments/assets/035f0125-0fb1-4da6-8b22-4e9536e4dca4" />  
   Menu terakhir pada sistem ini berfungsi untuk keluar pada sistem.
