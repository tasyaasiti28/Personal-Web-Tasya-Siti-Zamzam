# Personal-Web-Tasya-Siti-Zamzam
Personal Web Tasya Siti Zamzam menggunakan PHP, MYSQL, HTML,  Dan Tailwind CSS

1.Halaman Administrator
   
Halaman administrator ini merupakan antarmuka backend yang dirancang khusus untuk memudahkan pengguna dengan peran admin dalam mengelola konten dan fitur yang ada di dalam sebuah website. Desainnya yang minimalis namun modern, dengan dominasi warna ungu dan putih, memberikan tampilan yang nyaman dan profesional. Halaman ini dibuat dengan tujuan utama memberikan akses cepat dan ringkas untuk melakukan pengelolaan data seperti artikel dan galeri, serta navigasi ke bagian penting lainnya.

a. Tampilan Header

Bagian paling atas halaman ini merupakan header yang mencolok dengan latar belakang warna ungu pekat. Tulisan "Halaman Administrator" berada di tengah dengan font berwarna putih, besar, dan tebal, memberikan kesan formal dan tegas bahwa halaman ini adalah halaman khusus untuk pengguna dengan hak akses admin. Header ini berfungsi sebagai penanda tetap agar pengguna tahu posisi mereka dalam sistem.

b. Navigasi Menu Samping (Sidebar)
Di sisi kiri halaman terdapat sidebar menu yang berfungsi sebagai navigasi utama. Bagian ini diberi judul "MENU" dengan warna ungu terang, diikuti dengan daftar menu navigasi yang terdiri atas:
- Beranda: untuk kembali ke tampilan utama admin.
- Kelola Artikel: mengarahkan admin ke halaman pengelolaan artikel, tempat admin dapat membuat, mengedit, dan menghapus artikel yang akan ditampilkan di website.
- Kelola Gallery: halaman untuk mengatur konten galeri, termasuk menambahkan gambar baru, menghapus, atau memperbarui deskripsi galeri.
- About: menyediakan informasi tentang website atau sistem secara umum.
- Logout: digunakan untuk keluar dari akun administrator, dengan tampilan mencolok berwarna merah sebagai penanda fungsi yang bersifat penting dan langsung.
Menu ini dibuat tetap berada di sisi kiri untuk memudahkan admin mengakses berbagai halaman tanpa harus kembali ke halaman utama terlebih dahulu.

c. Konten Utama (Dashboard Tengah)
Di bagian tengah halaman terdapat panel utama yang menyambut admin dengan sapaan personal:
"Halo, admin! Apa kabar? 😊",
yang bertujuan menciptakan suasana yang hangat dan bersahabat. Di bawah sapaan tersebut, terdapat arahan ringan:
"Silakan gunakan menu di samping untuk mengelola data."
Setelah itu, halaman ini menampilkan dua kartu informasi utama yang menunjukkan jumlah data yang dikelola:
- Kartu Artikel dengan warna garis atas ungu, menampilkan angka 3, yang berarti terdapat 3 artikel yang saat ini sudah ada di sistem.
- Kartu Gallery dengan garis atas berwarna biru, menunjukkan angka 9, menandakan ada 9 entri galeri yang telah dikelola.
Kedua kartu ini dirancang untuk memberikan informasi cepat (quick stats) kepada admin tentang jumlah data yang tersedia tanpa perlu membuka halaman detail terlebih dahulu. Ini juga bisa berfungsi sebagai indikator kebutuhan update atau penambahan data.

d. Footer Halaman
Di bagian paling bawah halaman, terdapat footer dengan latar belakang ungu yang elegan. Isi footer ini adalah informasi hak cipta:
© 2025 | Created by Tasya Siti Zamzam
yang menunjukkan identitas pembuat halaman dan tahun pembuatannya. Elemen ini memberikan kesan personal sekaligus profesional.

![halaman  administrator](https://github.com/user-attachments/assets/404907f1-7aad-40b5-b29e-06284de51ae3)

Fungsi Keseluruhan Halaman
Halaman administrator ini berfungsi sebagai pusat kendali (control panel) dari sistem website. Semua fitur penting untuk pengelolaan konten dapat diakses dari halaman ini. Fungsinya antara lain:
- Memberikan ringkasan cepat jumlah konten yang tersedia (artikel dan galeri).
- Memungkinkan admin untuk menavigasi dengan cepat ke bagian pengelolaan konten.
- Menyediakan titik awal yang ramah dan informatif untuk aktivitas administratif.
- Menjadi gerbang awal untuk aktivitas CRUD (Create, Read, Update, Delete) terhadap konten website.
- Menyediakan kontrol penuh bagi admin untuk memelihara dan memperbarui informasi yang ditampilkan kepada pengunjung website.
Dengan tampilan sederhana namun informatif ini, halaman administrator mendukung efisiensi kerja admin serta memastikan pengelolaan data berjalan secara sistematis dan terorganisir.

2.Halaman Kelola Artikel "Kelola Artikel"

Halaman "Kelola Artikel" ini merupakan bagian dari panel admin ("HALAMAN ADMIN") yang memungkinkan pengguna untuk mengelola konten artikel yang ditampilkan di situs web.

Elemen-elemen pada Halaman:

a. Header:

- Terdapat tulisan "HALAMAN ADMIN" di bagian atas halaman, menunjukkan bahwa ini adalah antarmuka untuk pengelolaan oleh administrator.

b. Sidebar/Menu Navigasi Kiri:

- Berisi daftar tautan menu yang memungkinkan admin berpindah antar halaman pengelolaan yang berbeda. Menu yang terlihat adalah:

- Beranda

- Kelola Artikel (sedang aktif/terpilih)

- Galeri Kelola

- Tentang

- Keluar

c. Area Konten Utama (Daftar Artikel):

- Judul: "Daftar Artikel" mengindikasikan bahwa area ini menampilkan daftar artikel yang sudah ada.

- Tombol "+ Tambah Artikel": Berada di pojok kanan atas area konten, tombol ini berfungsi untuk mengarahkan admin ke halaman atau formulir untuk menambahkan artikel baru.

- Tabel Daftar Artikel: Menampilkan informasi artikel dalam format tabel dengan kolom-kolom sebagai berikut:

  - NO: Ini adalah kolom untuk nomor urut artikel. Dalam contoh yang diberikan, "1" menunjukkan bahwa ini adalah artikel pertama dalam daftar. Kolom ini berfungsi sebagai penanda urutan artikel yang ditampilkan.
Nama Artikel: Menampilkan judul atau nama dari artikel tersebut. Contohnya: "HIMASI CUP 2025: Great Energy New Synergy".

  - Isi Artikel: Menampilkan sebagian kecil atau ringkasan dari isi artikel. Ini membantu admin mendapatkan gambaran cepat tentang konten artikel tanpa harus membuka detail penuh.

  - Aksi: Kolom ini berisi opsi atau tindakan yang dapat dilakukan admin terhadap artikel tertentu. Dalam contoh ini, terdapat dua opsi:

  - Sunting: Untuk mengedit atau mengubah isi dan detail artikel yang bersangkutan.

  - Hapus: Untuk menghapus artikel dari daftar.

![kelola artikel](https://github.com/user-attachments/assets/b407ee8c-3e96-4632-8c13-3267b257129f)

Fungsi Keseluruhan Halaman "Kelola Artikel":

- Halaman "Kelola Artikel" ini berfungsi sebagai pusat kendali bagi administrator untuk:

- Melihat Daftar Artikel: Menampilkan semua artikel yang telah dipublikasikan atau tersimpan dalam sistem.

- Menambah Artikel Baru: Menyediakan fasilitas untuk membuat dan mengunggah artikel baru ke situs web.

- Mengedit Artikel: Memungkinkan admin untuk memperbarui, mengoreksi, atau mengubah konten, judul, dan detail lain dari artikel yang sudah ada.

- Menghapus Artikel: Memberikan kemampuan untuk menghapus artikel yang sudah tidak relevan atau diinginkan lagi dari situs.

- Memantau Konten: Dengan menampilkan ringkasan isi artikel, admin dapat dengan cepat memantau dan memastikan bahwa konten yang ditampilkan relevan dan akurat.

Secara keseluruhan, halaman ini adalah antarmuka penting bagi admin untuk menjaga konten artikel tetap terkini, relevan, dan terorganisir di situs web.

3.Halaman Kelola Gallery "Kelola Gallery"

Halaman "Kelola Gallery" ini merupakan bagian dari panel administrasi (admin panel) yang dirancang untuk memungkinkan administrator mengelola koleksi gambar atau foto yang ditampilkan dalam sebuah galeri di situs web.

Elemen-elemen pada Halaman:

a. Header:

- Bagian atas halaman menampilkan judul "Kelola Gallery", secara jelas mengidentifikasi fungsi utama halaman ini.

b. Sidebar/Menu Navigasi Kiri:

- Berisi daftar tautan menu yang memfasilitasi navigasi admin ke berbagai area pengelolaan situs. Menu yang terlihat adalah:

  - Beranda

  - Kelola Artikel

  - Kelola Gallery (sedang aktif/terpilih)

  - About

  - Logout

c. Area Konten Utama (Daftar Gallery):

- Judul: "Daftar Gallery" menunjukkan bahwa area ini menampilkan pratinjau dan daftar gambar yang telah diunggah.

- Tombol "+ Tambah Gambar": Berada di pojok kanan atas area konten, tombol ini berfungsi untuk mengarahkan admin ke halaman atau formulir untuk menambahkan gambar baru ke galeri.

- Tampilan Grid Galeri: Gambar-gambar ditampilkan dalam format grid (kotak-kotak) yang rapi, memungkinkan pratinjau visual yang cepat. Setiap item gambar biasanya terdiri dari:

  - Thumbnail/Pratinjau Gambar: Gambar itu sendiri ditampilkan dalam ukuran kecil.

  - Nama/Keterangan Gambar: Teks di bawah gambar, seperti "PKKMB 2024", kemungkinan adalah judul, kategori, atau keterangan singkat dari gambar/album tersebut.

  - Opsi Aksi: Di bawah setiap gambar, terdapat tautan atau tombol untuk melakukan tindakan spesifik pada gambar tersebut:

    - Edit: Untuk mengubah detail gambar (misalnya, keterangan, kategori) atau mungkin mengganti gambar.

    - Hapus: Untuk menghapus gambar tersebut dari galeri.

    ![kelola gallery](https://github.com/user-attachments/assets/a9581701-8bee-40be-af40-99e2cc7ac82d)

Fungsi Keseluruhan Halaman "Kelola Gallery":

Halaman "Kelola Gallery" ini berfungsi sebagai pusat kontrol bagi administrator untuk:

- Melihat dan Meninjau Gambar: Menyediakan pratinjau visual dari semua gambar yang ada di galeri, memudahkan admin untuk meninjau konten.

- Menambah Gambar Baru: Memungkinkan admin untuk mengunggah gambar-gambar baru ke galeri, memperbarui atau memperkaya koleksi visual situs.

- Mengedit Detail Gambar: Memberikan kemampuan untuk mengubah atau memperbarui informasi terkait gambar (seperti judul, deskripsi, atau kategori) setelah diunggah.

- Menghapus Gambar: Memfasilitasi penghapusan gambar yang sudah tidak relevan, usang, atau tidak diinginkan lagi dari galeri.

- Mengelola Portofolio Visual: Secara keseluruhan, halaman ini memungkinkan admin untuk secara efektif mengelola dan memelihara bagian visual atau portofolio gambar di situs web, memastikan konten galeri selalu relevan dan menarik.

Halaman ini esensial untuk situs web yang mengandalkan konten visual, seperti portofolio, event, atau berita berbasis foto, karena memungkinkan pengelolaan gambar yang efisien.  

4.Halaman Kelola Halaman About (About)

Halaman "Kelola Halaman About" ini merupakan bagian dari panel administrasi (admin panel) yang dirancang khusus untuk memungkinkan administrator mengelola dan memperbarui konten yang akan ditampilkan pada halaman "Tentang Kami" atau "About" di situs web. Halaman ini biasanya berisi informasi mengenai individu, organisasi, atau proyek yang relevan dengan situs tersebut.

Elemen-elemen pada Halaman:

a. Header:

- Bagian atas halaman menampilkan judul "Kelola Halaman About", secara jelas mengidentifikasi fungsi utama halaman ini.

b. Sidebar/Menu Navigasi Kiri:

- Berisi daftar tautan menu yang memfasilitasi navigasi admin ke berbagai area pengelolaan situs. Menu yang terlihat adalah:

  - Beranda

  - Kelola Artikel

  - Kelola Gallery

  - About (sedang aktif/terpilih)

  - Logout

c. Area Konten Utama (Tentang Saya):

- Judul: "Tentang Saya" menunjukkan bahwa area ini menampilkan konten yang berkaitan dengan informasi pribadi atau entitas utama situs.

- Tombol "+ Tambah Data": Berada di pojok kanan atas area konten, tombol ini kemungkinan berfungsi untuk menambahkan segmen informasi baru, jika halaman "About" dirancang untuk memiliki beberapa bagian atau entri (meskipun dalam contoh ini, terlihat seperti satu blok teks besar).

- Blok Konten Teks: Area utama menampilkan teks panjang yang merupakan isi dari halaman "About". Dalam contoh, teks tersebut adalah perkenalan diri dan deskripsi mengenai seorang mahasiswa ilmu komputer.

- Opsi Aksi: Di bagian bawah blok teks, terdapat tautan atau tombol untuk melakukan tindakan pada konten tersebut:

  - Edit: Untuk mengedit atau mengubah isi teks yang ditampilkan pada halaman "About". Ini adalah fungsi utama untuk memperbarui informasi.

  - Hapus: Untuk menghapus blok konten "About" tersebut. Ini mungkin digunakan jika ada beberapa "data" yang bisa ditambahkan atau jika admin ingin sepenuhnya menghapus konten "About" untuk sementara.

![kelola about](https://github.com/user-attachments/assets/374cf45f-09b1-461c-8732-fcfd4f0edbff)

Fungsi Keseluruhan Halaman "Kelola Halaman About":

Halaman "Kelola Halaman About" ini berfungsi sebagai pusat kontrol bagi administrator untuk:

- Melihat dan Meninjau Konten "About": Menyediakan tampilan langsung dari teks yang saat ini ada di halaman "About" situs.

- Mengedit Konten "About": Ini adalah fungsi paling krusial, memungkinkan admin untuk memperbarui, mengoreksi, atau mengubah seluruh teks yang ada di halaman "About" agar tetap relevan dan akurat.

- Menambah Data (Opsional): Jika desain halaman "About" memungkinkan beberapa segmen informasi, fungsi ini akan digunakan untuk menambahkan blok teks atau data baru.

- Menghapus Konten: Memberikan kemampuan untuk menghapus bagian atau seluruh konten "About" jika diperlukan.

Secara keseluruhan, halaman ini sangat penting untuk situs web yang ingin menyajikan informasi latar belakang, visi, misi, atau profil kepada pengunjung. Ini memastikan bahwa informasi "Tentang Kami" selalu terkini dan mencerminkan keadaan terbaru dari individu atau entitas yang diwakili.

5.Halaman "Artikel Terbaru" (Home)

Halaman ini berfungsi sebagai halaman beranda (home) dari "Personal Web | Tasya Siti Zamzam", yang berfokus pada menampilkan konten artikel terbaru sebagai daya tarik utamanya. Ini adalah halaman pertama yang kemungkinan besar dilihat oleh pengunjung saat mengakses situs web.

Elemen-elemen pada Halaman:

a. Header Utama (Top Bar):

  - Menampilkan judul situs web: "Personal Web | Tasya Siti Zamzam". Ini memberikan identitas pemilik atau tema utama dari situs.

b. Navigasi Utama (Navbar):

- Terletak tepat di bawah header, bilah navigasi ini memungkinkan pengunjung untuk berpindah antar bagian utama situs. Menu yang tersedia adalah:

  - Artikel: Kemungkinan akan mengarahkan ke daftar lengkap artikel atau kategori artikel.

  - Gallery: Mengarahkan ke halaman galeri foto/gambar.

  - About: Mengarahkan ke halaman "Tentang" (misalnya, tentang Tasya Siti Zamzam).

  - Login: Mengarahkan ke halaman login, kemungkinan untuk administrator atau pengguna terdaftar.

c. Area Konten Utama (Dua Kolom):

- Halaman ini dibagi menjadi dua kolom utama untuk menampilkan konten:

- Kolom Kiri: "Artikel Terbaru"

  - Judul: "Artikel Terbaru" secara jelas menunjukkan fokus konten di bagian ini.

  - Konten Artikel: Menampilkan artikel paling baru secara lengkap atau sebagian besar isinya. Dalam contoh ini, artikel berjudul "HIMASI CUP 2025: Great Energy, New Synergy" ditampilkan dengan teks lengkap. Ini adalah fitur utama halaman beranda untuk menarik perhatian pengunjung dengan konten segar.

- Kolom Kanan: "Daftar Artikel"

  - Judul: "Daftar Artikel" mengindikasikan daftar artikel lain yang tersedia.

  - Daftar Link Artikel: Menampilkan daftar artikel lain dalam format poin-poin (bullet points). Setiap poin adalah judul artikel yang kemungkinan besar dapat diklik untuk membaca artikel secara penuh. Contohnya:

    - "HIMASI CUP 2025: Great Energy, New Synergy" (artikel yang sama dengan yang di kolom kiri, mungkin sebagai tautan referensi)

    - "PKKMB 2024: Awal yang Menghangatkan Hati"

    - "Makrab 3 Hari 2 Malam: Penuh Cerita, Penuh Makna"

![halaman artikel](https://github.com/user-attachments/assets/8e2b0ee6-9935-4187-9c76-9943fc1e1b6d)

Fungsi Keseluruhan Halaman "Artikel Terbaru" (Halaman Beranda/Home):

Halaman ini berfungsi sebagai pintu gerbang utama situs web dengan tujuan:

- Menyajikan Konten Segar: Dengan menampilkan artikel terbaru secara langsung, halaman ini memastikan pengunjung segera melihat informasi atau tulisan terkini.

- Memberikan Gambaran Umum Situs: Melalui bilah navigasi, pengunjung dapat dengan mudah memahami struktur dan jenis konten yang ditawarkan situs (artikel, galeri, tentang).

- Mengarahkan Navigasi: Memfasilitasi pengguna untuk menjelajahi situs lebih lanjut, baik untuk membaca artikel lengkap lainnya melalui "Daftar Artikel" atau untuk beralih ke bagian lain seperti galeri atau halaman "About".

- Branding Personal: Judul "Personal Web | Tasya Siti Zamzam" di header membantu membangun identitas personal pemilik situs.

- Titik Masuk Utama: Sebagai halaman beranda, ini adalah titik akses pertama bagi sebagian besar pengunjung, sehingga dirancang untuk memberikan informasi yang paling relevan dan menarik segera.

Secara ringkas, halaman ini dirancang untuk segera memberikan gambaran konten terkini dan relevan dari Personal Web Tasya Siti Zamzam, sekaligus menyediakan navigasi yang mudah ke bagian-bagian situs lainnya.

6.Halaman "Gallery"

Halaman "Gallery" ini merupakan bagian dari situs "Personal Web | Tasya Siti Zamzam" yang berfungsi untuk menampilkan koleksi gambar atau foto kepada pengunjung. Halaman ini dirancang untuk menyajikan konten visual secara menarik dan mudah diakses.

Elemen-elemen pada Halaman:

a. Header Utama (Top Bar):

- Menampilkan judul situs web: "Gallery | Tasya Siti Zamzam". Ini mengidentifikasi halaman yang sedang diakses dan pemilik situs.

b. Navigasi Utama (Navbar):

- Terletak tepat di bawah header, bilah navigasi ini memungkinkan pengunjung untuk berpindah antar bagian utama situs. Menu yang tersedia adalah:

  - Artikel

  - Gallery (sedang aktif/terpilih)

  - About

  - Login

c. Area Konten Utama (Galeri Foto):

- Judul: "Galeri Foto" secara jelas menunjukkan jenis konten yang ditampilkan di halaman ini.

- Tampilan Grid Gambar: Gambar-gambar ditampilkan dalam format grid (kotak-kotak) yang rapi, memungkinkan pengunjung untuk melihat banyak pratinjau gambar sekaligus. Setiap item gambar biasanya terdiri dari:

  - Thumbnail/Pratinjau Gambar: Gambar itu sendiri ditampilkan dalam ukuran kecil.

  - Keterangan Gambar: Teks di bawah gambar, seperti "PKKMB 2024", kemungkinan adalah judul album, kategori, atau deskripsi singkat dari peristiwa atau tema gambar tersebut.

![halaman gallery](https://github.com/user-attachments/assets/1d05288f-de4e-418a-a2ae-4fdcc71f7a9b)


Fungsi Keseluruhan Halaman "Gallery":

Halaman "Gallery" ini berfungsi sebagai ruang pameran visual di situs web dengan tujuan:

- Menampilkan Portofolio Visual: Menyajikan koleksi foto atau gambar kepada pengunjung, yang bisa berupa dokumentasi acara, proyek, atau momen penting lainnya.

- Memberikan Pengalaman Visual: Memberikan pengalaman penjelajahan yang berpusat pada gambar, memungkinkan pengunjung untuk mengamati detail visual dari setiap foto.

- Dokumentasi: Bertindak sebagai arsip visual yang mendokumentasikan kegiatan, pencapaian, atau pengalaman yang relevan dengan pemilik situs (Tasya Siti Zamzam).

- Meningkatkan Keterlibatan Pengguna: Gambar seringkali lebih menarik daripada teks biasa, sehingga galeri dapat meningkatkan waktu kunjungan dan keterlibatan pengunjung di situs.

- Navigasi Terintegrasi: Terhubung dengan menu navigasi utama, memudahkan pengunjung untuk beralih antara melihat gambar, membaca artikel, atau mencari informasi "About".

Secara ringkas, halaman "Gallery" ini adalah fitur penting yang memperkaya konten situs dengan elemen visual, memungkinkan pengunjung untuk mengeksplorasi dan menikmati momen-momen yang dibagikan melalui foto.

7.Halaman "About" (Tentang Saya)

Halaman "About Me" merupakan segmen krusial dari "Personal Web | Tasya Siti Zamzam" yang berfungsi sebagai jendela utama bagi pengunjung untuk mengenal lebih dalam sosok di balik situs ini, yaitu Tasya Siti Zamzam. Pada halaman ini, pengunjung disajikan dengan teks perkenalan diri yang komprehensif, mencakup identitasnya sebagai seorang mahasiswa program studi Ilmu Komputer, detail mengenai ketertarikan dan motivasinya dalam bidang teknologi digital seperti pemrograman, desain, pengembangan web, dan sistem informasi, serta pandangannya tentang pentingnya pengembangan diri di luar lingkup akademik melalui partisipasi aktif dalam organisasi, kepanitiaan, dan acara kampus. Lebih lanjut, halaman ini juga memaparkan visi Tasya di masa depan untuk menjadi pribadi yang tidak hanya ahli teknologi tetapi juga memberikan dampak positif bagi lingkungan sekitar, yang keseluruhan narasi ini bertujuan untuk membangun koneksi personal yang kuat dengan pengunjung, memberikan gambaran mendalam tentang latar belakang, filosofi, dan aspirasi pemilik situs.

![halaman about](https://github.com/user-attachments/assets/047253e9-7c1a-4672-95c8-9960a246444e)

Secara keseluruhan, halaman "About Me" ini adalah cerminan dari identitas dan tujuan Tasya Siti Zamzam, memberikan konteks personal yang berharga bagi seluruh konten yang ada di Personal Web-nya.

8. Halaman Login Administrator

Halaman "Masuk Administrator" adalah antarmuka khusus yang memungkinkan administrator situs untuk masuk ke panel pengelolaan. Halaman ini memiliki formulir dengan kolom input untuk "Nama belakang" (username) dan "Kata sandi" (password), serta tombol "Login" untuk memproses otentikasi dan tombol "Cancel" untuk membatalkan proses login. 

![halaman login administrator](https://github.com/user-attachments/assets/388beeb4-301c-4be0-8953-0fae81a563bb)

Fungsi Halaman: Masuk ke halaman login untuk admin.
