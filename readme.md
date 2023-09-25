--- SETUP WORDPRESS ---

1. download wordpress https://id.wordpress.org/download/
2. extract file wordpress
3. rename file wordpress sesuai nama situs yang ingin dibuat
4. copy file wordpress ke folder /Applications/MAMP/htdocs
5. buka url http://localhost/phpmyadmin/
6. buat database
7. buka url http://localhost/nama-folder
8. koneksikan database, yang perlu diisi hanya isi nama basis data dengan nama database yang telah dibuat di phpmyadmin tadi lalu username dan password, jika menggunakan MAMP username dan passwordnya adalah 'root' dan 'root', jika menggunakan WAMP skip kosongkan saja passwordnya
9. klik jalankan pemasangan
10. isi data untuk user admin wordpress, pada bagian 'Ketampakan di Mesin Pencari' di check terlebih dahulu agar tidak terindex google
11. selesai dan login.

--- MEMBUAT TEMA BARU ---

1. buat nama folder tema di dalam folder wordpress yang telah di copy, contoh membuat folder dengan nama tema 'accoiuntingfirm' di folder wordpress accounting-firm/wp-content/themes
2. siapkan file yang dibutuhkan untuk membuat custome theme, filenya :
    1. *style.css*: Ini adalah file utama tema kamu dan harus ada dalam setiap tema WordPress. File ini mengandung informasi tentang tema, seperti nama, deskripsi, versi, penulis, dll. kamu juga dapat menentukan gaya dasar di sini menggunakan CSS.
    index.php: File ini digunakan untuk menampilkan halaman berkamu atau halaman indeks utama.
    2. *header.php*: File ini berisi bagian atas situs, termasuk header, menu navigasi, dan elemen-elemen lain yang ditampilkan di seluruh situs.
    3. *footer.php*: Ini adalah bagian bawah situs kamu yang berisi footer, hak cipta, dan elemen lain yang ditampilkan di seluruh situs.
    4. *sidebar.php*: File ini berisi konten sidebar, jika tema kamu memiliki satu.
    5. *single.php*: Digunakan untuk menampilkan posting blog individual.
    6. *page.php*: Digunakan untuk menampilkan halaman tunggal yang tidak termasuk dalam blog, seperti halaman kontak atau tentang kami.
    7. *archive.php*: Untuk menampilkan arsip berdasarkan tanggal, kategori, atau label.
    8. *search.php*: Digunakan untuk menampilkan hasil pencarian di situs kamu.
    9. *comments.php*: File ini berisi kode untuk menampilkan dan mengelola komentar.
    10. *functions.php*: Ini adalah file yang sangat penting yang berisi fungsi-fungsi tambahan dan penyesuaian tema. kamu dapat menambahkan kode PHP khusus kamu di sini.
    11. *page-template.php*: Jika kamu ingin membuat templat halaman khusus, kamu dapat membuat file ini untuk setiap templat yang kamu inginkan.
3. siapkan plugin yang membantu untuk memudahkan membuat konten di wordpress
    1. *ACF PRO*: plugin untuk membuat field otomatis
    2. *contact form 7*: untuk membuat form pada wordpress
    3. *Lite speed cache*: untuk mengatur cache dan load aset wordpress
    4. *Widget Management*: opsional jika website mempunyai widget

--- KONFIGURASI TEMA ---

1. Konfigurasi style.css: lihat file style.css didalam folder tema
2. Konfigurasi functions.php: lihat file functions.php didalam folder tema
2. Konfigurasi folder pendukung: lihat struktur folder didalam folder tema
3. Konfigurasi file pendukung: lihat struktur file didalam folder tema


--- CHEATSET ---

url : https://developer.wordpress.org/



