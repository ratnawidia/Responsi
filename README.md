# responsi

Berikut langkah - langkah untuk menjalankanya :

Pada responsi kali ini menggunakan images php:7.4-apache
1. Lakukan git clone pada terminal

            git clone https://github.com/ratnawidia/responsi.git
      
2. Kemudian pull images dari Dockerhub

            docker pull ratnawidia/195410005cloud:latest
            
3. Setelah selesai proses download, kemudian masuk ke directory yang sudah kita buat

            cd responsi
            
4. Selanjutnya menjalankan docker compose dengan command berikut

            docker-compose up -d
            
5. Setelah selesai kemudian buka browser dan masuk ke localhostnya

            localhost
            localhost:8080
            
6. Kemudian login ke database dengan :

            username : root
            password : example
            database : -
         
   - step pertama buat database dengan nama : responsi
   - yang kedua buat tabel dengan nama : tb_mahasiswa
   - dan yang ketiga menentukan filed tabelnya : (id primary key INT, nama VARCHAR [25], nim INT [9])
   - untuk default value nya, cheklist semua
