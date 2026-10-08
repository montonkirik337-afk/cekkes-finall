CekKes - Web Aplikasi Cek Kesehatan Terpadu

Dokumen ini berisi panduan singkat untuk menjalankan proyek CekKes di komputer lokal Anda menggunakan terminal Visual Studio Code di port http://localhost:3000.

🛠️ Persyaratan Sensus / Prasyarat

Sebelum menjalankan aplikasi, pastikan Anda telah menginstal Node.js di komputer Anda.

Unduh & install Node.js jika belum ada: https://nodejs.org/

🚀 Cara Menjalankan Aplikasi di localhost:3000

Opsi 1: Menggunakan npx serve (Paling Direkomendasikan)

Buka Terminal di VS Code

Tekan Ctrl + ~ (atau Cmd + ~ di Mac) untuk membuka Terminal terintegrasi di VS Code.

Jalankan Perintah Server
Ketikkan perintah berikut di terminal lalu tekan Enter:

npx http-server -p 3000 -o


Buka di Browser
Buka browser favorit Anda dan akses:

akan muncul setelah perintah dijalankan dan pilih salah satu dari dua alamat yang di kassih
untuk menghentikanya klik control-c di terminal


Opsi 2: Menggunakan http-server

Buka Terminal VS Code (Ctrl + ~).

Jalankan perintah:

npx http-server -p 3000


Buka alamat http://localhost:3000 di browser Anda.

Opsi 3: Menggunakan Extension VS Code (Live Server)

Jika Anda tidak ingin menggunakan Node.js/NPM, Anda bisa memakai ekstensi VS Code:

Buka tab Extensions (Ctrl + Shift + X) di VS Code.

Cari dan install ekstensi Live Server (oleh Ritwick Dey).

Buka pengaturan extension (Settings > Search liveServer.settings.port).

Ubah port default dari 5500 menjadi 3000.

Klik kanan pada file index.html lalu pilih "Open with Live Server".

📌 Catatan Tambahan

Untuk menghentikan server yang sedang berjalan di terminal, tekan Ctrl + C pada jendela terminal VS Code.