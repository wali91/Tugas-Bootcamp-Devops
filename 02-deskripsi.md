2. Dapatkah kamu menggambarkan diagram alur seorang DevOps di suatu perusahaan, mulai dari tahap pengembangan produk  (development) hingga rilis ke publik  (production)?
    Terdapat beberapa alur didalam melakukan pengembanagan dan sampai produksi di devops diantaranya terdapat gambaranya pada gambar 02.png.
  - continuous development
    Pada fase ini terlibat di dalamnya proses perencanaan dan koding perangkat lunak. Visi proyek disepakati dan ditetapkan pada fase perencanaan kemudian 
    pengembang mulai melakukan koding aplikasi. Tidak ada alat secara khusus untuk melakukan perencanaan, 
    tetapi ada sejumlah alat untuk memelihara kode (kontrol versi),misalnya svn, git, jira dan mercurial. Selain itu alat bantu seperti Maven, Selenium dan Gradle 
    juga dapat dipakai dalam fase ini guna mengemas kode menjadi file yang dapat dieksekusi untuk diteruskan ke fase berikutnya
  - continuous testing
    Pada fase ini perangkat lunak yang dikembangkan akan diuji secara terus menerus setiap kali ada perubahan atau komit dari pengembang. 
    Alat uji yang dapat digunakan seperti TestNG, Selenium, Junit dan sebagainya. Alat-alat ini memungkinkan QA untuk menguji beberapa baris
    kode secara menyeluruh guna memastikan bahwa tidak ada kekurangan dalam fungsionalitas. Dalam fase ini, wadah Docker dapat digunakan untuk
    melakukan simulasi lingkungan pengujian. Seluruh fase pengujian ini dapat diotomatisasi dengan bantuan alat Continuous Integration seperti Gitlab dan Jenkins.
  - continuous integration
    Fase ini merupakan inti dari seluruh siklus hidup DevOps di mana integrasi pengembangan perangkat lunak dan proses operasional dilakukan. 
    Setiap komit yang dilakukan pengembang sedini mungkin harus dideteksi, terlebih jika terdapat bug.Integrasi kode melibatkan kompilasi, ulasan
    kode, unit testing, functional testing, integration testing dan packaging. Alat populer yang bisa dipakai seperti Gitlab dan Jenkins.
  - continuous deployment
    Pada fase ini kode disebarkan ke server produksi. Penting juga untuk memastikan bahwa kode tersebut digunakan dengan benar di semua server.
  - continuous monitoring
    Fase ini sangat penting dari siklus hidup DevOps di mana kinerja aplikasi perlu terus dipantau. Pada fase ini informasi penting terkait 
    penggunaan perangkat lunak perlu dicatat guna mengenali fungsionalitas aplikasi yang tepat. Kesalahan sistem seperti alokasi memori terlalu rendah, 
    server tidak dapat dijangkau, bad gateway, dan sebagainya diselesaikan pada fase ini. Alat yang bisa dipakai pada fase ini seperti 
    Zabbix, PRTG, Nagios, Cacti, Splunk, ELK Stack, Sensu dan NewRelic.
    
