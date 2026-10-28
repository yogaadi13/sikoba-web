# SIKOBA Web — Tanpa Database

Proyek demo aplikasi SIKOBA menggunakan HTML, CSS, dan JavaScript. Bisa dibuka di VS Code tanpa XAMPP atau MySQL. Data contoh disimpan di `localStorage` browser.

## Cara menjalankan
1. Ekstrak folder `sikoba_web_tanpa_database`.
2. Buka folder tersebut di VS Code.
3. Buka `index.html` di browser. Disarankan memakai ekstensi **Live Server** di VS Code, lalu klik **Go Live**.
4. Login demo: username `petugas`, password `sikoba123`.

## Fitur demo
- Splash/branding dan halaman login
- Dashboard statistik
- Data obat: tambah, edit, hapus, cari, filter status
- Stok masuk dan stok keluar dengan validasi jumlah
- Riwayat transaksi
- Kontrol kedaluwarsa
- Notifikasi persediaan
- Laporan dan cetak melalui dialog print browser
- Profil petugas
- Ekspor data ke JSON
- Responsif desktop dan mobile

## Catatan
Versi ini sengaja belum memakai PHP maupun database. Login hanya simulasi, bukan autentikasi aman untuk produksi. Data tersimpan di browser/perangkat yang digunakan. Nantinya backend PHP dan MySQL dapat ditambahkan tanpa perlu mendesain ulang seluruh antarmuka.
