# Pemograman Web
~~~
Nama  : Arif Samsudin
NIM   : 311910255
Kelas : TI 19 C1
~~~
# Persiapan
Buat folder baru dengan nama lab11_php_ci pada docroot webserver (htdocs)
![1  Buat Folder](https://user-images.githubusercontent.com/81839328/122627002-417a1d00-d0d7-11eb-965f-02dab0d05366.JPG)

# Langkah-langkah Praktikum
Persiapan Sebelum memulai menggunakan Framework Codeigniter, perlu dilakukan konfigurasi pada webserver. Beberapa ekstensi PHP perlu diaktifkan untuk kebutuhan pengembangan Codeigniter 4. 

Berikut beberapa ekstensi yang perlu diaktifkan: 

• php-json ekstension untuk bekerja dengan JSON; 

• php-mysqlnd native driver untuk MySQL; 

• php-xml ekstension untuk bekerja dengan XML; 

• php-intl ekstensi untuk membuat aplikasi multibahasa; 

• libcurl (opsional), jika ingin pakai Curl.

# Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian Apache klik Config -> PHP.ini

![2  XAMPP](https://user-images.githubusercontent.com/81839328/122627304-c3b71100-d0d8-11eb-8bed-0536d9dced44.png)

# Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.

![3  ini](https://user-images.githubusercontent.com/81839328/122627497-0b8a6800-d0da-11eb-9dfa-a3c5fefd6466.JPG)

# Instalasi Codeigniter 4
Untuk melakukan instalasi Codeigniter 4 dapat dilakukan dengan dua cara, yaitu cara manual dan menggunakan composer. Pada praktikum ini kita menggunakan cara manual.

• Unduh Codeigniter dari website https://codeigniter.com/download

• Extrak file zip Codeigniter ke direktori htdocs/lab11_ci.

• Ubah nama direktory framework-4.x.xx menjadi ci4.

• Buka browser dengan alamat http://localhost/lab11_php_ci/ci4/public/






