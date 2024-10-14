
nama  : davina putri izzati gautama
nim   : 2309116064  

MATERI YANG DITERAPKAN PADA MINI PROJECT 2
1. Inheritance
![image](https://github.com/user-attachments/assets/4a9bcc77-050f-4b34-95c3-6382f78df762)
Inheritance dalam pemrograman berorientasi objek adalah konsep di mana sebuah kelas, seperti Potion, dapat mewarisi atribut dan metode dari kelas lain, yaitu BarangSihir. Dalam contoh ini, Potion adalah subclass yang menggunakan konstruktor super() untuk menginisialisasi atribut yang diperlukan, termasuk nama, tipe (ditetapkan sebagai "Potion"), dan jumlah barang. Dengan demikian, Potion tidak perlu mendefinisikan ulang semua sifat yang ada di BarangSihir, yang mengurangi duplikasi kode dan meningkatkan efisiensi. Selain itu, objek Potion dapat diperlakukan sebagai objek BarangSihir, memungkinkan penggunaan polimorfisme yang memudahkan interaksi dalam program. Secara keseluruhan, inheritance membantu menciptakan struktur kode yang lebih terorganisir dan mudah dipelihara.


2. Encapsulation
![image](https://github.com/user-attachments/assets/73463fa5-5d0c-4116-a00e-a0bba358db1b)
Getter dan setter digunakan untuk mengakses dan memodifikasi atribut privat dalam kelas, yang pada umumnya tidak dapat diakses langsung dari luar kelas. Dalam contoh ini, metode getName(), getType(), dan getQuantity() berfungsi sebagai getter yang mengembalikan nilai dari atribut name, type, dan quantity, masing-masing. Sementara itu, metode setQuantity(int quantity) adalah setter yang digunakan untuk mengubah nilai atribut quantity. Dengan menggunakan getter dan setter, encapsulation memastikan bahwa akses ke data dikontrol dengan baik, meningkatkan keamanan data, dan memungkinkan validasi atau manipulasi tambahan saat data diakses atau dimodifikasi. Prinsip ini mendukung pemisahan antara interface dan implementasi, membuat kode lebih mudah dipelihara dan fleksibel.


3. Abstraction
![image](https://github.com/user-attachments/assets/7d3bca1a-a5fd-4883-83aa-8e582fb733d0)
Gambar menunjukkan definisi kelas abstrak BarangSihir dalam Java, yang memiliki tiga atribut privat: name, type, dan quantity. Kelas ini tidak dapat diinstansiasi langsung dan dirancang untuk diwarisi oleh kelas lain, menerapkan prinsip enkapsulasi dengan menyembunyikan detail atribut dari akses langsung. Kelas abstrak ini berfungsi sebagai dasar untuk kelas-kelas spesifik seperti Potion dan Wand.

4. Interface
![image](https://github.com/user-attachments/assets/4a617eac-42b1-4a0e-b746-ff53428f4e7b)
Kelas ManajemenBarang bisa mengimplementasikan interface CrudOperations untuk menyediakan implementasi konkret dari metode-metode yang didefinisikan dalam interface tersebut. Dengan demikian, kelas ManajemenBarang akan bertanggung jawab untuk mengelola koleksi BarangSihir.

PENJELASAN PROGRAM

Pada langkah pertama, pengguna akan disajikan beberapa pilihan terkait operasi CRUD (Create, Read, Update, Delete) yang tersedia. Pengguna kemudian dapat memilih fungsi yang ingin dieksekusi berdasarkan kebutuhan spesifik mereka, apakah itu menambah data baru, melihat daftar item yang ada, memperbarui informasi yang sudah ada, atau menghapus data tertentu dari sistem. Pilihan ini memungkinkan pengguna untuk secara fleksibel mengelola data sesuai dengan tujuan mereka di dalam sistem. maka user memilih opsi 1 untuk menambahkan inventaris

![image](https://github.com/user-attachments/assets/422541f9-9930-4b1f-916d-193d2cde3341)

Pada langkah kedua, pengguna akan memilih opsi kedua yang berfungsi untuk melihat daftar barang yang tersedia dalam program. Dengan memilih opsi ini, pengguna dapat mengakses dan menampilkan informasi lengkap mengenai item-item yang ada di dalam inventaris toko, seperti nama barang, jumlah stok, dan harga masing-masing barang. Fitur ini memudahkan pengguna untuk mendapatkan gambaran umum mengenai ketersediaan produk tanpa harus melakukan perubahan apapun terhadap data yang tersimpan di sistem.

![image](https://github.com/user-attachments/assets/f01fbc2b-bda8-44fb-9970-32d6ea9d90a7)

Pilihan ketiga ini memungkinkan pengguna untuk mencari barang yang terdapat dalam inventaris toko secara lebih spesifik. Dengan menggunakan fitur pencarian ini, pengguna dapat memasukkan nama atau kategori barang yang diinginkan untuk kemudian ditampilkan hasilnya, sehingga mereka dapat mengetahui apakah barang tersebut tersedia atau tidak di dalam sistem.

![image](https://github.com/user-attachments/assets/fa11122f-1385-45d6-97c6-13bd122d05ec)

Pada opsi terakhir, pengguna diberikan pilihan untuk mengakhiri penggunaan program dengan memilih opsi "keluar" dari program. Ketika opsi ini dipilih, program akan secara otomatis menghentikan seluruh proses yang sedang berlangsung dan program selesai.

![image](https://github.com/user-attachments/assets/277a51d4-0854-49dc-a5a8-35d6d8b4615a)


