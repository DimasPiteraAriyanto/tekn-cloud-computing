# Perbedaan antara IaaS, PaaS, dan SaaS

* IaaS (Infrastructure-as-a-Service), Layanan cloud yang memungkinkan pengguna mendapatkan akses ke infrastruktur mereka sendiri - komputer, sumber daya jaringan, penyimpanan.Ini biasanya sumber daya virtual, tetapi bisa jadi sumber daya nyata atau fisik.

* PaaS (Platform-as-a-Service), Layanan cloud yang mengabstraksi infrastruktur (pengguna tidak dapat melihatnya di komputer, loadbalancers, dll.) Melainkan menyediakan platform pengembangan perangkat lunak. Dimungkinkan untuk membuat kode dan menjalankan aplikasi pada PaaS dan sistem memastikan bahwa aplikasi memiliki infrastruktur yang diperlukan untuk membuatnya berjalan dan skala.

* SaaS (Software-as-a-Service), Layanan cloud yang memberikan pengguna akses ke perangkat lunak dengan layanan mandiri, sesuai permintaan. Ini bisa berupa aplikasi tunggal atau memberikan katalog perangkat lunak yang dapat dipilih pengguna.

# Arsitektur SAAS
Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal).Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian.Model tradisional ini, setiap versi aplikasi didasarkan pada kode unik.
Perangkat lunak yang telah didistribusikan kepada pelanggan dalam berbagai saluran selama beberapa dekade terakhir. Saluran distribusi yang lebih baru dalam Perangkat Lunak sebagai Layanan (atau SaaS).


Ada dua varietas utama SaaS:

1.SaaS Vertikal
Perangkat Lunak yang menjawab kebutuhan industri tertentu (contohnya : Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
2.SaaS Horisontal
Produk-produk yang berfokus pada kategori perangkat lunak (contohnya : pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.

# SaaS (Software as a Service) Platform Architecture.

SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:

* Infrastruktur sebagai Layanan
* Platform sebagai Layanan
* Pembelajaran Mesin sebagai Layanan

Setiap pembaruan atau tambalan untuk aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru suatu produk saat perangkat lunak dikirimkan melalui internet.

Dalam beberapa tahun terakhir telah muncul ribuan produk SaaS yang ditargetkan untuk konsumen seperti:

1. Netflix
2. Microsoft Office 365
3. Amazon Prime
4. Indonesia
5. Facebook
6. Google Documents

Mampu mengaktifkan atau menonaktifkan produk SaaS sesuai permintaan adalah faktor lain yang menarik bagi konsumen, Dan tidak perlu lagi menjatuhkan ratusan dolar pada lisensi perangkat lunak. Sebagian besar produk SaaS memungkinkan pengguna membayar langganan bulanan dengan opsi dan membatalkan kapan pun pengguna inginkan.

## Kerugian dari Platform SaaS

Kurang kontrol
Karena aplikasi SaaS di-host di server web vendor, Anda memiliki sedikit atau tidak ada kontrol atas perangkat lunak yang Anda gunakan. Aplikasi internal atau internal akan memberikan bisnis Anda kontrol lebih besar atas perilakunya, misalnya, aplikasi berbasis Windows mungkin memiliki lebih banyak opsi konfigurasi daripada aplikasi web biasa yang dikirim sebagai aplikasi SaaS.

Ekosistem terbatas
Tidak dapat dipungkiri bahwa SaaS adalah tren yang berkembang sebagai saluran distribusi perangkat lunak. Yang mengatakan, masih banyak aplikasi yang tidak menawarkan versi yang di-host.

Performa
Aplikasi internal, klien kental, atau lokal akan selalu berjalan lebih cepat daripada produk yang dikirim melalui internet.

Kekhawatiran Data
Saat memilih produk SaaS, dan misalnya, dengan munculnya GDPR, bisnis harus memberikan perhatian khusus dalam hal di mana implementasi SaaS menyimpan data di cloud. Setiap yurisdiksi memiliki kebijakan legislatif sendiri dan bertindak ketika data sensitif diproses atau disimpan.

## Komponen Kunci dari Platform SaaS

Keamanan

Melindungi data pelanggan di platform SaaS adalah hal yang paling penting, karena itu, produk SaaS kemungkinan besar akan melayani ratusan, jika tidak ribuan pengguna. Pastikan arsitektur SaaS  memperhitungkannya.

Pribadi

Sementara keamanan terkait dengan penguncian pengguna dan data sensitif, privasi data adalah komponen penting lainnya yang harus dipertimbangkan platform SaaS Perusahaan. Dengan peraturan baru, seperti GDPR, bisnis lebih akuntabel daripada sebelumnya untuk memastikan privasi pengguna dan data tetap terjaga dan dengan temuan dari  KPMG  menyatakan bahwa Privasi Data adalah atribut terpenting kedua yang mereka cari dalam penyedia cloud, privasi merupakan komponen penting untuk pertimbangkan saat membuat produk SaaS sendiri.

Kustomisasi dan Konfigurasi

Sementara, mungkin dapat memberikan solusi SaaS di luar kotak bagi sebagian besar konsumen yang menyertakan serangkaian fitur dan fungsi standar. Perusahaan sering mengharapkan kustomisasi tambahan untuk menangani kasus penggunaan khusus untuk domain masalah khusus mereka. Anjak dalam diperpanjang untuk arsitektur SaaS perusahaan adalah komponen penting lainnya untuk pemilik perusahaan pertimbangkan. Pemilik perusahaan dapat melakukan ini dengan mengirimkan versi "label putih" dari produk SaaS perusahaan atau dengan menerapkan mekanisme plugin yang memungkinkan bisnis dan / atau pengembang untuk memperluas solusi SaaS label putih Perusahaan.

# Cara membangun aplikasi SaaS berbasis cloud

1.Membangun Untuk Cloud
Saat membangun aplikasi SaaS (global), kemungkinan besar user membangunnya di cloud. The cloud memiliki banyak keuntungan - memikirkan skalabilitas - kontras dengan lingkungan server lokal.

## Cara memulai
Membangun produk untuk cloud berarti membangun produk dengan bahasa pemrograman modern .

1. Selain kemampuan dan keterampilan pribadi, pilihan bahasa pemrograman yang akan dipengaruhi oleh kemungkinan masing-masing bahasa. Ada berbagai bahasa pemrograman (modern) di luar sana sehingga sulit untuk memilih yang benar.
Python adalah bahasa pemrograman yang banyak digunakan, dirancang untuk menekankan keterbacaan kode-nya.
Python dapat melakukan banyak hal. Apa pun aplikasi web yang ingin dibangun, kemungkinan ada kerangka untuknya dengan Python.
Kami di Usersnap memiliki cukup pengalaman dengan Python sebelum menggunakannya untuk aplikasi web kami. Seperti disebutkan, fleksibilitas untuk berbagai kasus penggunaan adalah alasan lain bagi kami untuk menggunakan Python.
2. Basis data yang sempurna, Kami merekomendasikan penggunaan basis data berorientasi dokumen . Database dokumen sangat berbeda dengan konsep tradisional database relasional.Mengapa memilih basis data berorientasi dokumen? Database dokumen mendapatkan informasi tipenya dari data itu sendiri. Dengan demikian setiap instance data dapat berbeda dari yang lain.Ini memungkinkan lebih banyak fleksibilitas, terutama ketika berhadapan dengan perubahan. Dan sering mengurangi ukuran basis data. Singkatnya, konsep DOB menawarkan pengalaman yang lebih kaya dengan teknik pemrograman modern.Mengapa kami memilih MongoDB? Karena MongoDB adalah database berorientasi dokumen yang memberikan kinerja tinggi, ketersediaan tinggi, dan skalabilitas mudah. Ya. Selain kinerja (yang menginginkan database yang lambat?), Skalabilitas adalah faktor terpenting bagi kami sebagai bisnis SaaS global .

Banyak pendiri SaaS bertujuan untuk meningkatkan skala bisnis mereka. Selain mengukur produk Anda dari perspektif bisnis, Anda tidak boleh lupa tentang masalah teknis.

Menskalakan teknologi Anda dengan MongoDB cukup mudah (ok, setidaknya lebih mudah dibandingkan dengan database lain). Dengan sharding otomatis, Anda dapat mendistribusikan data di berbagai mesin.

Sharding adalah metode untuk menyimpan data Anda di beberapa mesin. Dan MongoDB menggunakan sharding untuk mendukung penyebaran dengan dataset besar.

3. Mengatur MongoDB untuk aplikasi SaaS 
Kami - di Usersnap - memanfaatkan Amazon Web Services dan karenanya telah membuat instance EC2 di Irlandia, AS, dan Singapura. Memulai dengan MongoDB kami memasang instance MongoDB tunggal pada instance AWS EC2 kami di Irlandia.Dengan meningkatnya jumlah pelanggan AS dan Asia, kami melihat masalah kinerja di area-area dunia. Oleh karena itu, kami memasang arsitektur master / slave dengan master masih di Irlandia dan menambahkan dua instance slave MongoDB di Pantai Barat AS dan Singapura. Kedua DB budak tersebut menggunakan preferensi baca untuk menghindari permintaan di seluruh dunia untuk menjaga keterlambatan jaringan serendah mungkin untuk operasi baca. Menulis masih langsung ke master DB dan mendapatkan replikasi ke budak secara otomatis oleh MongoDB.

4. Sistem antrian
Sistem antrian pesan adalah protokol komunikasi yang tidak sinkron , memungkinkan pengirim dan penerima pesan tidak berinteraksi secara bersamaan.

Juga dikenal sebagai teknologi Antrian Pesan (MSMQ) memungkinkan aplikasi web untuk berjalan pada waktu yang berbeda dan untuk berkomunikasi dengan berbagai integrasi pihak ketiga / API / dan layanan lainnya secara tidak sinkron.

Sebuah pesan (mis. Kueri yang meminta layanan pihak ketiga melalui API) ditempatkan ke antrian. Itu disimpan di sana sampai penerima mengambilnya.

Antrian pesan memiliki batasan mengenai ukuran dan jumlah data yang dikirim dalam antrian. Hal yang hebat tentang sistem antrian modern adalah bahwa mereka dapat diskalakan dengan mudah.

RabbitMQ adalah sistem antrian sumber terbuka yang berjalan pada semua sistem operasi utama.

Kami menjalankan aplikasi web kami di AWS EC2 di mana RabbitMQ dapat dijalankan diinstal dan dijalankan dengan sangat lancar.

### Menginstal RabbitMQ
Python dengan pustaka manajemen tugas seledri open source sangat cocok untuk mendapatkan hasil maksimal dari RabbitMQ. Sangatlah penting untuk memiliki perangkat lunak yang kuat dan terbukti saat ini karena ini membangun tulang punggung infrastruktur kami.

Sebenarnya, kami menggunakan server RabbitMQ tunggal , dengan beberapa titik akhir yang memberi makan antrian dengan tugas (tugas berkala serta tugas yang disebabkan oleh tindakan pengguna) serta titik akhir yang memproses tugas-tugas tersebut (mis. Buat tangkapan layar kami yang terlihat bagus).

The konfigurasi optimal akan mencakup server RabbitMQ kedua tawaran replikasi dan mekanisme failover (dengan menyembunyikan mereka di belakang penyeimbang beban).

### AWS & EC2
Membangun aplikasi web yang skalabel Anda mungkin akan berakhir menggunakan Amazon Web Services cepat atau lambat. Dugaan saya lebih cepat😉

AWS memungkinkan Anda untuk meng-host dan menjalankan aplikasi web Anda serta melakukan pekerjaan batch berkinerja tinggi. Dengan Elastic Compute Cloud (EC2) AWS menyediakan server virtual yang dapat diskalakan untuk setiap bisnis.

Amazon EC2 adalah keharusan dan inti dari sistem kami yang menyediakan kapasitas komputasi yang dapat diubah ukurannya. Kami pada dasarnya telah menyewa server virtual tempat aplikasi web kami berjalan.

Yang hebat di sini adalah, bahwa server-server EC2 tersebar di seluruh dunia. Bergantung pada kebutuhan Anda untuk mengukur dan pasar geografis mana yang menjadi target pertama, Anda dapat memilih di antara berbagai lokasi EC2 Anda.

Saat ini, kami memiliki tiga server EC2 yang berlokasi di AS, Irlandia, dan Singapura. Kami akan terus menambahkan lokasi lebih lanjut (terutama di AS dan Eropa) karena permintaan produk kami terus meningkat. Dengan EC2 terinstal, sangat mudah untuk terus menambahkan server dan sumber daya baru.

### Penyimpanan Web S3
Semakin banyak pengguna yang bergabung dengan produk Anda akan membuat Anda dengan mudah bertanya-tanya tentang penyimpanan web Anda. Dengan layanan penyimpanan Amazon S3, kami memiliki penyimpanan objek yang hebat, dan sangat skalabel terpasang.

Amazon Simple Storage Service (S3) mudah digunakan, menyimpan dan mengambil data dalam jumlah berapa pun. Anda mungkin bertanya-tanya apakah Amazon S3 hanya dapat digunakan dengan layanan AWS lainnya? Jawaban yang bagus adalah: tidak. Ini juga dapat digunakan sendiri atau dengan repositori dan gateway penyimpanan pihak ke-3 lainnya. Dan tentu saja, ini bekerja sangat baik bersama dengan EC2.

Selain menyimpan data aplikasi web Anda dengan S3, ini juga bisa digunakan untuk cadangan, arsip, atau analitik data besar.

Jaringan Pengiriman Konten
Sebuah jaringan pengiriman konten (CDN) pada dasarnya adalah sebuah sistem server didistribusikan yang memungkinkan Anda untuk melayani konten dengan pengguna aplikasi Anda dengan kinerja tinggi dan ketersediaan tinggi.

Mari kita asumsikan Anda memiliki 3 EC2 yang diinstal. Satu di AS, satu di Eropa dan satu di Singapura. Jika seseorang dari New York mengunjungi aplikasi Anda, CDN memungkinkan Anda untuk menayangkan konten kepada pengguna melalui EC2 yang berlokasi di AS.

Jadi, Anda mungkin bertanya-tanya bagaimana menghubungkan titik-titik. Di bawah ini Anda dapat menemukan gambaran umum bagaimana kami di Usersnap telah mengatur aplikasi web kami dan peran EC2, S3, dan CDN.

Rekap: mengatur aplikasi SaaS
Dengan Python, MongoDB - sebagai basis data yang berorientasi pada dokumen, perangkat lunak RabbitMQ sebaiknya dilakukan dengan pengaturan dasar. Namun, ada banyak cara untuk dipikirkan. Dalam posting tindak lanjut kami, kami akan membahas kebutuhan perangkat lunak pemantauan dan analitik yang tepat serta bagaimana prosedur pembayaran dapat berjalan dengan lancar di cloud.

Selanjutnya, kami juga akan menunjukkan kepada Anda beberapa panduan mendalam tentang cara mengatur tumpukan alat Anda untuk menjalankan aplikasi web Anda dalam skala global.

### Mulailah dengan pengujian software sekarang