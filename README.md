<details> <summary>a. What is AMQP?</summary>
AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi standar terbuka yang dirancang untuk layanan perpesanan aplikasi. Protokol ini memungkinkan aplikasi-aplikasi untuk berkomunikasi satu sama lain melalui broker pesan yang mendukung AMQP, terlepas dari bahasa pemrograman atau platform yang digunakan. AMQP biasa digunakan dalam sistem seperti RabbitMQ untuk pengiriman pesan yang andal dan terukur.


</details> <details> <summary>b. Apa arti dari guest:guest@localhost:5672?</summary>
String koneksi "guest:guest@localhost:5672" memiliki beberapa komponen:

- **guest** pertama: Username yang digunakan untuk autentikasi ke server AMQP
- **guest** kedua: Password untuk username tersebut
- **localhost:5672**: Alamat server AMQP dimana:
  - **localhost** adalah nama host server (dalam hal ini mengacu pada komputer lokal)
  - **5672** adalah nomor port standar yang digunakan oleh layanan AMQP
  
Dengan kata lain, string tersebut adalah URL koneksi yang digunakan untuk menghubungkan aplikasi ke server RabbitMQ yang berjalan pada komputer lokal, menggunakan kredensial default (username "guest" dan password "guest").
</details>
