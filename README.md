Link tableau ==> https://public.tableau.com/app/profile/christian.tj/vizzes

# Latar Belakang
Bangkok adalah salah satu kota dengan perkembangan terpesat, dengan ekonomi yang dinamis dan kemasyarakatan yang terus berkembang di Asia Tenggara. Kota ini sedang berkembang menjadi pusat regional yang dapat menyaingi Singapura dan Hong Kong , Airbnb hadir sebagai platform terdepan bagi wisatawan yang mencari akomodasi dengan biaya terjangkau. Namun, dengan semakin banyaknya jumlah unit, pemilik unit menghadapi tantangan dalam menetapkan harga yang kompetitif, memahami dinamika pasar, dan mengoptimalkan unit mereka untuk memaksimalkan tingkat hunian. Analisis ini memanfaatkan wawasan berbasis data untuk membantu pemilik unit Airbnb di Bangkok dalam menghadapi atau beradaptasi dengan kompleksitas pasar. Dengan menganalisis faktor-faktor utama seperti persaingan lokasi dan distribusi geografis, tren harga, tingkat hunian, dan review dari pelanggan,yang mana tujuan akhirnya untuk memberikan strategi yang dapat ditindaklanjuti bagi pemilik unit untuk meningkatkan listing mereka, menarik lebih banyak tamu, dan meningkatkan pendapatan mereka.

# Pernyataan Masalah
Pemilik properti belum memiliki pemahaman yang lebih detail terhadap beberapa hal berikut :

1. Harga Rata - rata per tipe kamar: Bagaimana harga rata - rata per tipe kamar,Tipe mana yang paling mahal/murah?
2. Harga Rata-rata per Kawasan (Neighbourhood): Kawasan mana yang paling premium atau terjangkau?
3. Sebaran Tipe Kamar: Apakah lebih banyak rumah/apartemen seutuhnya atau hanya kamar pribadi?
4. Distribusi Geografis: Apakah listing terkonsentrasi di pusat kota?
5. Persebaran harga berdasarkan lokasi: apakah dapat di ketahui lokasi listing dengan harga tinggi atau rendah.
6. Pemilik dengan banyak Listing : Apakah ada "superhost" yang punya banyak properti?
7. Ketersediaan Properti : Berapa hari dalam setahun properti tersedia untuk disewa?
8. Listing dengan review terbanyak : Mana listing yang paling populer?
9. Review Per Bulan : Apakah ada listing yang sangat aktif dan menarik banyak tamu?

# Pemahaman Data dan Pembersihan Data
Sebelum melakukan analisis data, penting untuk memahami dan menyiapkan data secara menyeluruh. Ini melibatkan pemeriksaan struktur data , identifikasi jenis variabel, dan pengecekan data yang hilang (missing value) atau tidak konsisten. Setelah memperoleh informasi awal melalui statistik deskriptif, pembersihan data perlu dilakukan, seperti nilai yang hilang atau ketidakkonsistenan. Tujuannya untuk memastikan dataset akurat, lengkap, dan siap untuk dianalisis.
Untuk pemahaman yang lebih baik terkait data dictionary yang diperoleh terkait **Airbnb Listings Bangkok** maka berikut penjelasannya:

* id : kode unik atas listing Airbnb
* name : nama dari listing
* host_id : kode unik atas pemilik listing
* host_name : nama dari pemilik listing,biasanya menggunakan nama depan
* neighborhood : lokasi geografis dikodekan menggunakan garis lintang dan garis bujur terhadap lokasi yang diddefenisikan
* latitude : Menggunakan proyeksi Sistem Geodetik Dunia (WGS84) untuk lintang dan bujur
* longitude : Menggunakan proyeksi World Geodetic System (WGS84) untuk lintang dan bujur
* roomtype : terdiri dari --> Entire home/apt, Private room, Shared room, or Hotel
* price : harga sewa per hari dalam mata uang lokal
* minimum_nights : jumlah malam minimal untuk lama menginap / pemesanan
* number_of_reviews : banyaknya ulasan atas listing yang bersangkutan
* last_review : tanggal ulasan terakhir atau dengan kata lain ulasan terbaru
* calculated_host_listings_count : jumlah tempat tinggal dari tuan rumah yang sama
* availability_365 : jumlah hari ketersediaan unit dalam 365 hari
* number_of_reviews_ltm : jumlah ulasan dalam 12 bulan terakhr ( last twelve month )

# Data Analysis
Data Analysis akan di uraikan berdasarkan berbagai hal untuk kemudian diberikan Insight,Strategic Implications,Strategic Recommendations serta Conclusion.
Terdiri dari :
* Analisis Dasar
  1. Harga Rata - rata per tipe kamar
  2. Harga Rata-rata per Kawasan (Neighbourhood)
  3. Sebaran Tipe Kamar
* Analisis Geospasial (Lokasi)
  1. Distribusi Geografis
  2. Persebaran Harga berdasarkan lokasi
* Analisis Host
  1. Pemilik dengan Banyak listing
  2. Ketersediaan Properti
* Analisis Review & Popularitas
  1. Listing dengan Review terbanyak
  2. Review per Bulan

# Insight,Strategic Implications.Strategic Recommendations,Conclusion
Terlampir dalam file project




