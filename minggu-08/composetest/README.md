# Latihan Mengerjakan [Getting Started-Docker Compose](https://docs.docker.com/compose/gettingstarted/).

Dalam latihan ini menggunakan Docker Desktop yang harus diinstall terlebih dahulu. Untuk compose sudah terinstall di dalam docker desktop.

* Langkah 1 Setting.
1. Membuat direktori **composetest** dan masuk ke dalam composetest.
![]()
2. Buat file yang disebut **app.py** di direktori proyek.
![]()
3. Buat file lain yang disebut **requirements.txt** di direktori proyek.
![]()

* Langkah 2 Membuat **DockerFile**.
![]()

* Langkah 3: Tentukan layanan dalam file. Buat file yang disebut **docker-compose.yml** di direktori proyek.
![]()

* Langkah 4: Build dan jalankan aplikasi yang telah dibuat dengan Compose.
1. Dari direktori proyek, mulai aplikasi dengan menjalankan **docker-compose up**.
![]()
2. Masukkan **http: // localhost: 5000 /** di browser untuk melihat aplikasi berjalan. Awalnya akan muncul 1 times tetapi belum di screenshot sudah di refresh terlebih dahulu dan akan menampilkan 2 times
3. Refresh Halaman.
![]()
4. Beralih ke jendela terminal lain, dan ketik docker image ls untuk mencantumkan image lokal.
5. Hentikan aplikasi, baik dengan menjalankan d**ocker-compose down** dari dalam direktori proyek Anda di terminal kedua, atau dengan menekan **CTRL + C** di terminal asli tempat Anda memulai aplikasi.

* Langkah 5: Edit file Tulis untuk menambahkan bind mount.
![]()

* Langkah 6: Bangun kembali dan jalankan aplikasi dengan Compose.
![]()

* Langkah 7: Perbarui aplikasi
1. Ubah salam **app.py** dan simpan. Misalnya, ubah Hello World! pesan ke Hello Docker!....... :

2. Segarkan aplikasi di browser. Salam harus diperbarui, dan penghitung masih harus bertambah.

*Langkah 8:  percobaan dengan beberapa perintah lain.
1.  Menjalankan layanan di latar belakang, dapat melewati -d flag (untuk mode "detached").
2.  **Docker-compose ps** untuk melihat apa yang sedang berjalan.
3.  **Docker-compose run** perintah memungkinkan Anda untuk menjalankan satu-off perintah untuk layanan Anda. Misalnya, untuk melihat variabel lingkungan apa yang tersedia untuk weblayanan :.
4. Menjalankan dan melihat variabel yang tersedia menggunakan **docker-compose run web env**
5. Menghentikan aplikasi **docker-compose stop**
6. Menghapus containers **docker-compose down --volumes**