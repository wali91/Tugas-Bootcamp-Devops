5. CI/CD (Continuous Integration/Continuous Development) merupakan hal yang sering ditemui oleh seorang DevOps. Menurut pendapatmu mengapa CI/CD diperlukan, 
   dan berikan gambaran diagram kerjanya (Workflow) ?
   
   jawaban : 
   
   Dalam software development, Version Control System memiliki peranan penting dalam me-maintain progress code kita. Dengan Version Control System, 
   kita juga dapat membuat beberapa environment software seperti production dan deploy. Masing masing environment software terdiri dari beberapa stage 
   yang akan melakukan pekerjaan tertentu.
   Umumnya, ada 3 stages yang ada dalam environment software yaitu : test, build dan deploy. Mengapa kita perlu environment dan stages? 
   karena dengan environment dan stages,kita bisa melakukan pengecekan terhadap software kita sebelum siap dipakai oleh publik. 
   Salah satu pengecekannya adalah dengan melakukan test terhadap software kita.Selain itu, dengan adanya environment dan stages dapat membuat software development
   dan rilis update yang cepat dan kuat.
   
   Proses menjalankan 3 stages di masing masing environment tersebut dikenal dengan Continuous Integration, Continuous Deployment and Continuous Delivery. 
   Namun apa yang membedakan dari ketiga istilah tersebut? berikut gambar terla,pir pada 05.png sekaligus penjelasannya :
   1. Continuous Integration
   
      Continuous Integration adalah software development practice dimana kita build dan test software kita secara otomatis setiap kali melakukan git push ke repositori.
      Untuk setiap commit, CI/CD akan menjalankan unit tests untuk melihat apakah terjadi error. Jika iya, maka di pipeline akan terlihat tanda silang yang 
      menandakan bahwa test gagal atau tanda centang yang menandakan test kita berhasil. Pada Continuous Integration, karena kita tidak melakukan deploy produk kita
      dengan frekuensi yang sering, maka automatic deploy tidak berjalan. Oleh karena itu disebut Continuous Integration karena sudah menjalankan automatic build 
      dan test namun manual deploy.
      
   2. Continuous Delivery
   
      Pada Continuous Delivery, proses automasi hampir dilakukan di semua stage termasuk deployment. Namun, pada kenyataannya masih ada sedikit human intervention 
      pada proses deployment ke production yang membuat Continuous Delivery kadang tidak sepenuhnya bekerja otomatis. Deployment memang masih manual tapi itu 
      digunakan saat approving saja. Berbeda dengan Continuous Integration dimana deployment manual terjadi karena memang harus melewat proses quality assurance 
      yang panjang dan frekuensi deployment yang rendah.
      
   3. Continuous Deployment
      
      Dan yang terakhir adalah Continuous Deployment. Pada Continuous Deployment, semua proses dari test sampai production sudah fully automated 
      tanpa Human Intervention. Satu satunya Human Intervention adalah saat developer melakukan code review saat melakukan merging ke branch master. 
      Continuous Deployment biasanya digunakan oleh industri besar. Namun satu hal yang harus diperhatikan adalah tidak semua sistem 
      mendukung Continuous Deployment. Selain itu, pembuatan proses automasi dari test sampai production juga cukup sulit untuk dibuat.

 
