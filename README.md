# Tutorial-10
---
#### Nama: Abbilhaidar Farras Zulfikar
#### NPM: 2206026012
#### Kelas: Adpro A
---
### Refleksi
#### 2.1. Original code of broadcast chat.
Server Side <br>
![Server side](assets/images/server1.png) <br>
Client 1 Side <br>
![Client 1 side](assets/images/client1.png) <br>
Client 2 Side <br>
![Client 2 side](assets/images/client2.png) <br>
Client 3 Side <br>
![Client 3 side](assets/images/client3.png) <br>
Setelah server dijalankan dan setiap client (ada 3) dijalankan, dari output di atas dapat terlihat bahwa setiap client dan juga server menerima siaran obrolan dari setiap client. Setiap kali seorang client mengetikkan pesan di baris perintah, string tersebut akan dikirim ke server dan server akan terus mengirimkannya ke semua client yang terhubung dengannya. <br>

#### 2.2. Modifying the websocket port
Ketika client dan server memiliki port yang sama misal 8080, aplikasi akan berjalan dengan lancar seperti sebelumnya, seperti yang terlihat pada gambar di bawah ini. <br>
![Server Side with same port](assets/images/server_same_port.png) <br>
![Client Side with same port](assets/images/client_same_port.png) <br>

Namun, jika misalnya kita hanya mengubah salah satu port, misalnya port server menjadi 8080 dan port client tetap 2000, maka akan terjadi error pada client karena menurut client port tersebut tidak memiliki koneksi dan program akan crash saat dijalankan dalam foto di bawah ini. <br>
![Server Side with different port](assets/images/server_different_port.png) <br>
![Client Side with different port](assets/images/client_different_port.png) <br>