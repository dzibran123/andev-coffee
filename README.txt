========================================================================
CATATAN PRAKTIKUM BOOTSTRAP 5 - ANDEV COFFEE
========================================================================
Nama : Dzibran Febryansyah
NIM  : 2511102441026
Tema : Profil UMKM "Andev Coffee" (Semi-Outdoor Coffee & Event Space)

------------------------------------------------------------------------
A. 3 (TIGA) PERUBAHAN & PENGEMBANGAN DARI CONTOH MODUL PRAKTIKUM:
------------------------------------------------------------------------
1. Penambahan Feature Filter Menu Kategori Interaktif:
   Jika pada modul contoh hanya menampilkan card statis sederhana, pada website 
   Andev Coffee dikembangkan sistem filter kategori berbasis Bootstrap Nav-Pills 
   dan JavaScript untuk memilah menu Coffee, Non-Coffee, Snack, dan Main Course.

2. Kustomisasi Komponen Hero Section & Navbar Transparan Dynamic:
   Mengubah navbar biasa dari modul menjadi 'fixed-top' dengan efek perubahan 
   background saat di-scroll, serta membuat bagian Hero Pembuka penuh layar 
   dengan tombol Call-to-Action (CTA) interaktif.

3. Integrasi Section Jadwal Nobar (Nonton Bareng) & Custom Badge:
   Menambahkan section khusus event space lengkap dengan badge status 
   ("LIVE NOBAR", "UPCOMING") dan tata letak jadwal pertandingan untuk 
   menonjolkan keunikan tempat tanpa Wi-Fi namun kaya interaksi sosial.

------------------------------------------------------------------------
B. KENDALA YANG DIHADAPI DAN CARA MENGATASINYA:
------------------------------------------------------------------------
Kendala:
Saat diuji pada ukuran layar seluler (mobile), gambar pada Card Menu dan 
Card Keunggulan mengalami kedistorsian rasio tinggi/lebar (gambar terlihat 
gepeng) serta jarak antar card menjadi terlalu rapat.

Cara Mengatasi:
Memanfaatkan utilitas CSS kustom `object-fit: cover;` pada kelas `.card-img-top` 
serta menerapkan utilitas spacing Bootstrap `g-4` (gutters) dan `mb-4` pada 
wrapper grid kolom agar rasio visual gambar tetap proporsional dan memiliki 
jarak antar komponen yang konsisten di semua resolusi layar.
========================================================================