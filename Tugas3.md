## NAMA KELOMPOK
## MUHAMMAD FADIL HIDAYAT
## MUHAMMAD DINAR SALIHIN
## HASANUDIN

# Cara Konfigurasi SSH Server dengan Debian
1. Pertama tahap ini silahkan login sebagai user bisa klik su  
2. Kedua Sebelumnya kita akan mengecek kembali, bahwa adapter 1 / eth0 ter bridge ke internet, karena pada saat ini koneksi internet saya menggunakan VirtualBox Host-Only Network #2 , maka disesuaikan dengan adapter nya, oleh karena itu saya menggunakan Intel(R) Wireless-AC 9560 160Mhz
3. ![image](https://user-images.githubusercontent.com/112686760/202431631-21520dc2-5be9-4900-ab1a-d87c82f2c900.png) Jika sudah, saat nya kita lakukan konfigurasi IP Address pada Linux Debian, tapi sebelum itu kita akan mengecek berapakah IP Address Internet yang kita dapatkan dari ISP.Untuk mengecek IP Address di windows, saya menggunakan CMD, lalu ketik ipconfig /all ![image](https://user-images.githubusercontent.com/112686760/202432029-779216a0-6576-45b5-a103-ce1dfedab3da.png)
5. ketiga jika sudah, berikutnya kita akan mengkonfigurasi IP Address pada Linux Debian caranya ketikan perintah nano /etc/network/interfaces , crtl+x dan ctrl+s  
![image](https://user-images.githubusercontent.com/112686760/202432133-fe64a5e6-bf22-4acd-b54b-147ab04bbe5f.png) Jika sudah, silahkan di save dengan cara
ctrl+x lalu y lalu enter atau cara cepatnya ctrl+x y enter
4. Keempat ketikan ip a mengecek konfigurasi IP Address yang sudah kita buat 
![image](https://user-images.githubusercontent.com/112686760/202432242-60b5fa1f-ae2d-4b35-978a-1cb46d77d5d0.png)
Tahap berikutnya adalah, kita akan menginstall SSH atau openssh-server pada Linux Debian kita, Berikut ini adalah cara nya. 
5. Kelima jalankan ketik apt-get install openssh-server
6. Keenam berikutnya kita akan diperintahkan, untuk memasukkan ISO DEBIAN Paket 1  dengan klik devices > optical disk > iso 
![image](https://user-images.githubusercontent.com/112686760/202432346-6d19a191-62a2-4fbb-91e2-01789d06a464.png)
7. Ketujuh silahkan tunggu beberapa saat, jika sudah selesai hal yang akan kita lakukan adalah, mengecek status dari SSH Server yang sudah kita install, dengan perintah ketikan /etc/init.d/ssh status
![image](https://user-images.githubusercontent.com/112686760/202432465-ef97ec4c-e630-4a14-b215-b747f685b9c9.png)
8. buka aplikasi futty masukkan ip 192.168.43.105
![image](https://user-images.githubusercontent.com/112686760/202432563-48616ac7-8387-415d-9a19-a93a545adf06.png)
9. dan akan muncul 
![image](https://user-images.githubusercontent.com/112686760/202432566-e31f7788-0a62-400e-9d8a-2a47c66714de.png)
