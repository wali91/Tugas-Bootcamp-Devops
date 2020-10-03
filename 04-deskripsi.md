4. Seorang DevOps sering menggunakan Virtual Machine dan Docker untuk memudahkan pekerjaannya, menurut pendapatmu mengapa dia harus menggunakan tools tersebut ?
   
   jawaban : 
   
   Virtual Machine :
   
   > Virtual machine (VM) adalah sebuah emulasi dari sebuah sistem komputer. Secara sederhana, virtual machine membuat kita bisa membagi resource hardware dari 
   satu hardware fisik menjadi beberapa sistem komputer. Sebagai contoh, kita memiliki satu PC yang memiliki prosesor dengan 4 core, RAM sebesar 8 GB 
   serta harddisk 500GB misalnya. Tanpa VM tentu kita hanya bisa menginstall 1 OS atau beberapa OS tapi tak bisa berjalan bersamaan. 
   Dengan VM, kita bisa membagi sistem komputer menjadi dua masing-masing memiliki prosesor 2 core,  RAM 4GB, serta harddisk 250GB dan tentu saja 
   pembagian resource hardware tidak harus sama rata. Dengan ini, maka kita dapat menginstall OS di setiap sistem komputer dan dapat menjalankannya secara bersamaan 
   sehingga kita seolah memiliki 2 PC yang berbeda.
   Teknologi ini sering digunakan untuk server dan memunculkan istilah Virtual Private Server (VPS) tapi sedikit pula digunakan oleh app developer 
   karena project yang sedang dikerjakannya memiliki platform yang berbeda dengan platform yang dimiliki.
   
   Keunggulan Virtual Machine :
   - Resource hardware yang eksklusif sehingga tidak terganggu jika ada apps yang lain tiba-tiba membutuhkan resource yang tinggi
   - Memiliki management tools dan security tools yang sudah matang
   - Secara umum memiliki tingkat keamanan sedikit lebih tinggi bila dibandingkan dengan container
   
   
   Docker :
   > Docker atau bisa disebut juga container adalah sebuah virtualisasi OS yang dapat membungkus suatu aplikasi beserta dependency dan environment-nya. 
   Setiap container ini memiliki process yang terisolir sehingga tidak mengganggu host OS ataupun container yang lain. Prinsip container ini mirip dengan kontainer 
   yang ada di kapal kargo di mana kapal kargo tersebut diibaratkan sebagai sistem komputer.Jika dibandingkan dengan VM, secara pengaturan kontainer lebih mudah. 
   Hal ini disebabkan karena konsep berbagi resource hardware dari container lebih fleksibel bila dibandingkan VM. Sebagai contoh, 
   tadi disebutkan bahwa kita mempunyai 1 PC dengan 4 Core, RAM 8 GB, dan storage sebesar 500GB. Katakanlah kita mempunyai 2 container dengan kebutuhan RAM berbeda. 
   Beberapa apps dalam container A membutuhkan RAM 5GB sedangkan apps dalam container B membutuhkan RAM 2GB. Dengan container, kita tak perlu menset kebutuhan hardware
   resource setiap container karena berada dalam satu sistem komputer. Sementara jika kita memakai VM dengan hardware resource yang sudah kita bagi sama rata seperti 
   disebutkan di contoh sebelumnya, kita tidak mungkin memasang apps di container A di salah satu sistem komputer karena RAM maksimal yang bisa kita pakai hanyalah 4GB.
   Faktor portabilitas juga menjadi kelebihan yang dimiliki oleh container. Para developer bisa membagikan container dengan format ISO image ke setiap perangkat 
   yang dia pakai ataupun ke developer lain. 
   
   keunggulan docker atau container :
   - Fleksibel dan scalable
   - Mengurangi resource yang dibutuhkan dalam IT Management
   - Waktu yang dibutuhkan untuk mengemas dan memasang app dalam container lebih cepat bila dibandingkan dengan VM
   
   kesimpulan kenapa 2 tools tersebut penting digunakan :
     karena dengan virtual machine :
      - kita bisa memecah dari 1 resource pc kedalam beberapa resource pc,sehingga kita tidak memerlukan banyak tempat didalam peletakan tempat perangkat.
      - didalam pengoperasiannya yang cukup mudah yang dengan tidak perlu berinteraksi ke perangkat fisiknya pun kita bisa mengoperasikannya.
     
     karena dengan docker atau container : 
      - walupun berjalan di satu OS tapi docker bersifat terisolasi secara terpisah oleh docker. Sehingga para pengguna nya dapat menyesuaikan kebutuhan 
        di setiap aplikasi tanpa perlu mempengaruhi konfigurasi pada aplikasi yang lain.
      - docker juga bisa berjalan pada platfrom multi cloud Docker juga terbukti memiliki fleksibilitas yang tinggi karena bisa berjalan di berbagai 
        platform multi-Cloud. Tidak hanya fleksibel, 
      - Docker juga dikenal memiliki ukuran yang ringan sehingga tidak memerlukan banyak memori.
      
