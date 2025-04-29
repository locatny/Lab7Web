|Keterangan |Data|
|-------- |-----|
|Nama |Hannifa Indah Rahayu|
|NIM |312310653|
|Kelas |TI.23.A6|
|Matkul | Pemrograman Web 2|

# Praktikum 1
# PHP Framework (_Codeigniter_)
  Langkah-langkah Praktikum Persiapan
Sebelum memulai menggunakan Framework Codeigniter, perlu dilakukan
konfigurasi pada webserver. Beberapa ekstensi PHP perlu diaktifkan untuk
kebutuhan pengembangan Codeigniter 4.
  Berikut beberapa ekstensi yang perlu diaktifkan:
  
    • php-json ekstension untuk bekerja dengan JSON;
    • php-mysqlnd native driver untuk MySQL;
    • php-xml ekstension untuk bekerja dengan XML;
    • php-intl ekstensi untuk membuat aplikasi multibahasa;
    • libcurl (opsional), jika ingin pakai Curl.

Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel,
pada bagian Apache klik Config -> PHP.ini 
![image](https://github.com/user-attachments/assets/1629c0de-04d4-49b4-b53d-fe80335041c6)

  Pada bagian extention, hilangkan tanda ; (_titik koma_)
pada ekstensi yang akan diaktifkan. Kemudian simpan kembali
filenya dan restart Apache web server. 

![image](https://github.com/user-attachments/assets/318607e6-0b04-4682-a2ef-d68db288e13c)

****_Instalasi Codeigniter 4_**** 
  Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu
cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual. 

    • Unduh Codeigniter dari website https://codeigniter.com/download  
    • Extrak file zip Codeigniter ke direktori htdocs/lab11_ci. 
    • Ubah nama direktory framework-4.x.xx menjadi ci4. 
    • Buka browser dengan alamat http://localhost/lab11_ci/ci4/public/ 

![image](https://github.com/user-attachments/assets/244584c2-6ce1-4a73-9f5e-20c90e309b53)

****Menjalankan CLI (_Command Line Interface_)**** 
  Codeigniter 4 menyediakan CLI untuk mempermudah proses development.
Untuk mengakses CLI buka terminal/command prompt.


![image](https://github.com/user-attachments/assets/5d868a62-804d-43ac-9aab-8d90427c431d)

  Arahkan lokasi direktori (xampp/htdocs/lab11_ci/ci4/) sesuai dengan
direktori kerja Perintah yang dapat dijalankan untuk memanggil CLI Codeigniter adalah:
![image](https://github.com/user-attachments/assets/6b3edc4a-78f1-4e24-a864-9ecfee6a391b)

![image](https://github.com/user-attachments/assets/400d6ded-4455-4f70-9ce3-946c8e06bcbf)

****Mengaktifkan Mode _Debugging_****
  Codeigniter 4 menyediakan fitur debugging untuk memudahkan developer
untuk mengetahui pesan error apabila terjadi kesalahan dalam membuat kode program. 
Secara default fitur ini belum aktif. Ketika terjadi error pada aplikasi akan
ditampilkan pesan kesalahan seperti berikut. 

![image](https://github.com/user-attachments/assets/448e19a7-9be2-401d-9b4e-149ac58f3b5b)

Semua jenis error akan ditampilkan sama. Untuk memudahkan mengetahui
jenis errornya, maka perlu diaktifkan mode debugging dengan mengubah
nilai konfigurasi pada environment variable CI_ENVIRINMENT menjadi development. 

![image](https://github.com/user-attachments/assets/2d86cf68-fb1b-443b-bbd6-c9d5b762651b)

Ubah nama file env menjadi .env kemudian buka file tersebut dan
ubah nilai variable CI_ENVIRINMENT menjadi development. 

![image](https://github.com/user-attachments/assets/4e3c6cde-bc1c-4ecf-9c87-e8586e65de5d)


# Praktikum 2

# Framework Lanjutan (CRUD)

# Praktikum 3

# View Layout dan View Cell

# Praktikum 4

# Framework Lanjutan (Modul Login)

# Praktikum 5

# Pagination dan Pencarian

# Praktikum 6

# Upload File Gambar
