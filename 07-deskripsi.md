7. Sebutkan dan jelaskan Jenis-jenis IP beserta kelas-kelasnya yang kamu ketahui (gambarkan ke dalam bentuk tabel)!
   
   jawaban : 
   
   > IP Address terdiri dari 5 kelas, yaitu kelas A, B, C, D, dan E
   
   Dari 5 kelas ip tersebut yang dapat dan sering di implementasikan dalam jaringan pada umumnya adalah kelas A, B, dan C. Berikut penjelasan lebih rinci nya:
   
  - IP Address Kelas A
    IP address kelas A adalah ip address yang paling baik digunakan untuk jaringan berskala besar. Kita ketahui bahwa network id kelas A adalah pada oktet pertama,
    lebih detail nya pada oktet pertama tersebut yang nilainya apabila di konversi ke bilangan biner pasti diawali nilai 0, yang berkisar dari 0-127. 
    Sisa 24 bit dalam 3 oktet berikutnya menjadi range yang kosong yang dijadikan host id. Lebih tepatnya ip address kelas A dimulai dari ip 1.0.0.0 hingga 127.255.255.255 
    seperti pada gambar 07.png. Jumlah jangkauan ip tersebut dapat membentuk 126 kelompok jaringan, dimana setiap kelompok jaringan tersebut dapat 
    menampung hingga 16.777.214 komputer (host). Karena itu ip address kelas A lebih banyak di praktekan dalam ip public yang membutuhkan banyak host
    karena aksesnya yang meliputi WAN.
    
    > Contoh:   Diketahui suatu jaringan menggunakan alamat ip address kelas A 10.0.0.1, maka secara keseluruhan: 
    > ip pertama adalah 10.0.0.1, karena ip 10.0.0.0 adalah alamat network. 
    > ip terakhir adalah 10.255.255.254, karena ip 10.255.255.255 adalah alamat broadcast  
    > Jaringan ini mempunyai host dengan total 224-2 = 16.777.216-2 = 16.777.214 host.
    
  - IP Address Kelas B
    IP address kelas B mempunyai 16 bit untuk net id dan 16 bit untuk host id. Artinya host yang dapat ditampung adalah 216  = 65.536 host termasuk ip network 
    dan ip broadcast, dan akan berjumlah 65.534 setelah untuk ip address yang dapat digunakan sebagai host setelah dikurangi ip network dan ip broadcast.
    Rentang jumlah jaringan yang dapat dibentuk dalam ip address kelas B lebih banyak dibanding ip address kelas A, tapi jumlah host dalam setiap kelompok
    jaringan tersebut lebih sedikit dibanding kelas A.IP address kelas B sangat cocok untuk di implementasi dalam jaringan skala MAN (Metropolitan Area Network) 
    untuk skala jaringan dalam satu kota atau bahkan antar kota, tergantung jumlah host yang ditentukan. Rentang IPv4 pada kelas B dimulai dari 128.0.0.0 
    hingga 191.255.255.255, tapi khusus dua alamat ip tersebut tidak dapat digunakan dalam komputer, karena ip address 128.0.0.0 adalah ip network 
    dalam kelompok jaringan nya, dan ip 191.255.255.255 adalah ip broadcast dalam kelompok jaringan nya.
    
  - IP Address Kelas C
    IP address kelas C adalah ip address yang paling populer dan paling dikenal dalam dunia jaringan, tidak hanya pada level enterprise, tapi bahkan dalam bisnis 
    SOHO kelas ip address yang paling sering digunakan adalah ip kelas C. Salahs atu faktornya, mungkin karena pada setiap perangkat jaringan, yang menjadi 
    ip address default adalah ip address kelas C, contoh nya access point TP-Link, perangkat TP-Link yang penulis miliki mempunyai ip address default 
    192.168.0.254 untuk tp-link seri TL-WA7210N dan 192.168.1.254 untuk seri TL-WA5110G. Kedua ip address tersebut adalah ip address kelas C.
    Dalam konsep pengalamatan ip address kelas C, yang menjadi net id adalah pada 3 oktet pertama, dan yang menjadi host id adalah pada 1 oktet terakhir, 
    analoginya: net-id.net-id.net-id.host-id. Di mulai dari 192.0.0.0 sampai 223.255.255.255. Kenapa ip terakhir berada pada angka 223, perhatikan bahwa :
    > IP Address Kelas C, pada oktet pertama apabila dilihat pada nilai biner, selalu dimulai dengan angka 110 dalam 3 bit pertamanya.
    
    Karena network id nya mempunyai lebih banyak jatah, maka kelompok jaringan yang dapat dibentuk dengan ip address kelas C lebih banyak lagi dari kelas B, 
    tapi jumlah host yang dapat digunakan hanya sampai 256 host termasuk ip network dan ip broadcast, dan bernilai 254 yang bisa di gunakan setelah dikurangi 
    2 untuk ip network dan ip broadcast. Untuk jumlah kelompok jaringan nya, jika dalam ip address kelas A angka 16.777.216 adalah untuk nilai host, 
    maka dalam ip address kelas C angka 16.777.216 adalah nilai untuk jumlah kelompok jaringan yang dapat dibentuk.
    
 - IP Address Kelas D
   IP address kelas D tidak dapat digunakan dalam implementasi seperti pada umumnya seperti ip address kelas A, B, C. Karena ip address kelas D merupakan sebuah ip multicast, 
   artinya : 
> ip address kelas D ditujukan sebagai ip untuk komputer untuk pengiriman satu pesan ataupun satu paket data ke semua komputer dan perangkat terhubung lainnya di dalam suatu jaringan.

  Rentang ip address kelas D seperti pada gambar 5 kelas ip address, dimulai dari 224.0.0.0 hingga 239.255.255.255. Dalam rentang tersebut khusus untuk ip dimulai dari 224.0.0.0 
  hingga 224.0.0.255 tidak dapat digunakan di dalam kelas D untuk keperluan IP Multicast, karena telah ditujukan sebagai ip multicast cadangan.
  
- IP Address Kelas E
  Eksistensi alamat ip kelas E hanya digunakan untuk keperluan riset, begitu menurut referensi yang penulis baca, tak banyak literatur tentang jaringan komputer 
  yang membahas ip address kelas E, tapi pada intinya ip address kelas E sangat jarang digunakan dalam implementasi jaringan komputer.
  Baca juga IP address Private dan IP adress Public sebagai referensi dasar jaringan komputer lain nya.


