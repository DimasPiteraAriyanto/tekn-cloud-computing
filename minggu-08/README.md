# Latihan Mengerjakan [Getting Started-Docker Compose](https://docs.docker.com/compose/gettingstarted/).

Dalam latihan ini menggunakan Docker Desktop yang harus diinstall terlebih dahulu. Untuk compose sudah terinstall di dalam docker desktop.

* Langkah 1 Setting.
1. Membuat direktori **composetest** dan masuk ke dalam composetest.
![1](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-01.png)
2. Buat file yang disebut **app.py** di direktori proyek.
![8](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-08.png)
3. Buat file lain yang disebut **requirements.txt** di direktori proyek.
![10](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-10.png)

* Langkah 2 Membuat **DockerFile**.
![9](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-09.png)

* Langkah 3: Tentukan layanan dalam file. Buat file yang disebut **docker-compose.yml** di direktori proyek.
![7](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-07.png)

* Langkah 4: Build dan jalankan aplikasi yang telah dibuat dengan Compose.
1. Dari direktori proyek, mulai aplikasi dengan menjalankan **docker-compose up**.
![3](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-03.png)
![4](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-04.png)
![5](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-05.png)
2. Masukkan **http: // localhost: 5000 /** di browser untuk melihat aplikasi berjalan. Awalnya akan muncul 1 times tetapi belum di screenshot sudah di refresh terlebih dahulu dan akan menampilkan 2 times
3. Refresh Halaman.
![2](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-02.png)
4. Beralih ke jendela terminal lain, dan ketik **docker image ls** untuk mencantumkan image lokal.
![6](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-06.png)
5. Hentikan aplikasi, baik dengan menjalankan d**ocker-compose down** dari dalam direktori proyek Anda di terminal kedua, atau dengan menekan **CTRL + C** di terminal asli tempat Anda memulai aplikasi.

* Langkah 5: Edit file Tulis untuk menambahkan bind mount.
![12](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-12.png)

* Langkah 6: Bangun kembali dan jalankan aplikasi dengan Compose.
![11](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-11.png)

* Langkah 7: Perbarui aplikasi
1. Ubah salam **app.py** dan simpan. Misalnya, ubah Hello World! pesan ke Hello Docker!....... :
    ![14](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-14.png)
2. Segarkan aplikasi di browser. Salam harus diperbarui, dan penghitung masih harus bertambah.
        ![13](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-13.png)

* Langkah 8:  percobaan dengan beberapa perintah lain.
1.  Menjalankan layanan di latar belakang, dapat melewati -d flag (untuk mode "detached").
2.  **Docker-compose ps** untuk melihat apa yang sedang berjalan.
3.  **Docker-compose run** perintah memungkinkan Anda untuk menjalankan satu-off perintah untuk layanan Anda. Misalnya, untuk melihat variabel lingkungan apa yang tersedia untuk weblayanan :.
4. Menjalankan dan melihat variabel yang tersedia menggunakan **docker-compose run web env**
5. Menghentikan aplikasi **docker-compose stop**
6. Menghapus containers **docker-compose down --volumes**
	![Perintah Lain](https://github.com/XabaraNeanthal/tekn-cloud-computing/blob/master/minggu-08/gambar-15.png)
