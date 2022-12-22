## Muhamad Fadil Hadiyat
## Muhamad Dinar Salihin
## hassanudin

# Web Server
1. Langkah pertama buka Debian kemudian masuk ke super user dengan command sudo su atau bisa engan su dan masukkan password Linuxnya.

  ![image](https://user-images.githubusercontent.com/112686760/202636659-6ef5928c-8fab-448c-8741-6f49542973ba.png)
  
2. Langkah kedua silahkan install web server dengan mennjalankan command apt-get install apache2

  ![image](https://user-images.githubusercontent.com/112686760/202636722-cc26f02a-0248-47c9-a9e7-0da738283712.png)

3. Langkah ketiga jika sudah berhasil silahkan jalankan penginstalan bahasa pemrograman php dengan command apt-get install php8.1(php8.1 artinya php versi 8.1) jika gagak coba jalankan command sudo apt -y install php8.1

  ![image](https://user-images.githubusercontent.com/112686760/202636814-afd8be8c-b736-48b2-bbca-39015cf9b37d.png)

4. Langkah keempat selanjutnya konfigurasi, kita bisa melihat hasil dengan mengunjungi web browser dan mengetikkan alamat IP server kita (jalankan command ip a untuk melihat IP server) maka akan muncul seperti gambar dibawah ini.

  ![image](https://user-images.githubusercontent.com/112686760/202636921-e6a4c2ee-20d8-4158-a73d-7805ae47f803.png)

  ![image](https://user-images.githubusercontent.com/112686760/202636934-21f7c065-5a42-49d4-a46f-65cd58c46fba.png)

5. Langkah kelima selanjutnya adalah menguji menggunakan script php untuk menampilkan info php pada server kita, Kita akan membuat skrip php pada folder /var/www Jalankan command nano /var/www/html/test/php atau jika gagal nano /var/www/test.php. Setelah itu masukkan skrip seperti gambar dibawah ini

  ![image](https://user-images.githubusercontent.com/112686760/202637002-22ab0b67-6145-4dac-94fb-b3fd4a351f74.png)

6. Langkah keenam yaitu yang langkah terakhir selanjutnya untuk membuka browser dalam linuxnya dan kita ketikan (IP server kalian)/test.php. Maka akan muncul laman tentang info dari php yang kita install pada server.

  ![image](https://user-images.githubusercontent.com/112686760/202637098-ce1598ed-3464-4c45-8f56-112843360c79.png)
