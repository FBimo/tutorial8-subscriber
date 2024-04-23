# QnA
1. Apa itu amqp?
    - AMQP merupakan singkatan dari Advanced Message Queuing Protocol. Ini adalah protokol lapisan aplikasi standar terbuka untuk _middleware_ berorientasi pesan. Dalam istilah yang lebih sederhana, ini adalah protokol yang memungkinkan sistem perangkat lunak yang berbeda berkomunikasi satu sama lain dengan mengirim dan menerima pesan.

2. Apa arti dari ini? guest:guest@localhost:5672, apa itu guest pertama dan apa maksud dari guest kedua? dan apa arti localhost:5672? 
    - "guest:guest@localhost:5672" adalah format umum yang digunakan untuk mengakses server AMQP. 
    - "guest" pertama adalah nama pengguna (_username_) yang digunakan untuk mengakses server. 
    - "guest" (kedua) adalah kata sandi (_password_) yang terkait dengan nama pengguna tersebut. 
    - "localhost:5672" adalah alamat server dan _port_ tempat server AMQP berjalan. 
    - "localhost" merujuk pada mesin tempat kita menjalankan aplikasi atau layanan AMQP, dan "5672" adalah nomor _port_ default yang digunakan oleh server AMQP. 
    - Jadi, secara keseluruhan, "guest:guest@localhost:5672" mengidentifikasi pengguna yang ingin mengakses server AMQP di mesin lokal (_localhost_) menggunakan nama pengguna "guest" dan kata sandi "guest", yang berjalan di _port_ 5672.
3. _Slow Simulation_
_Queue_ berjumlah 20 karena setiap _run_ akan mengirimkan lima data ke dalam _queue_. 
![slow-simulation](image-1.png)