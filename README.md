File Manager berbasis web sederhana yang dapat digunakan untuk mengelola file dan folder di server langsung melalui browser. Ini berguna misalnya untuk:
Mengelola file di server tanpa perlu akses FTP atau SSH.
Upload, edit, hapus, dan rename file secara cepat.
Monitoring kondisi server dan lingkungan PHP.

Fungsi Utama Kode Ini

1.	Menampilkan File dan Folder di Direktori

Kode ini menampilkan daftar file dan folder yang ada di direktori yang dipilih (default direktori kerja saat ini).
Folder dan file ditampilkan dengan ikon berdasarkan ekstensi file (misalnya 🐘 untuk PHP, 🖼 untuk gambar).

2. Navigasi Direktori

Pengguna dapat berpindah-pindah antar direktori dengan memasukkan path baru atau menggunakan breadcrumb navigation.
Ada tombol untuk menuju direktori induk (parent directory) dan direktori home.

3. Operasi File Dasar

Buat File Baru: Bisa membuat file kosong baru di direktori yang sedang dibuka.
Buat Folder Baru: Bisa membuat folder baru.
Upload File: Mengunggah file dari komputer ke server.
Edit File: Mengedit isi file teks (seperti .txt, .php, .html, dll) langsung dari web.
View File: Melihat isi file teks dengan format yang sudah diformat HTML.
Rename File: Mengganti nama file.
Delete File: Menghapus file dengan konfirmasi.
Ubah Permission File (chmod): Mengatur permission file dengan memasukkan nilai octal.

4. Informasi Sistem

Menampilkan informasi server dan PHP, seperti versi PHP, OS, ruang disk, user, penggunaan memori, dan beberapa tool seperti gcc, wget, curl, python, dll apakah tersedia di server.
Informasi ini membantu mengetahui kondisi server dan environment hosting.
