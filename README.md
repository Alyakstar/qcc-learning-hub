# QCC Learning Hub

Portal statis untuk pembelajaran QCC: beranda, 8 Step, 7 Tools QC, New 7 Tools, latihan studi kasus, absensi, ekspor Excel, template XLSX, panduan, dan kontak.

## Jalankan
Buka `index.html` dengan VS Code Live Server. Tidak perlu `npm install`.

## Deploy di Vercel
Letakkan seluruh isi folder ini pada root repository. Pilih Framework Preset `Other`; tidak perlu build command. Pastikan `index.html` dan folder `templates/` ikut di-push.

## Sebelum digunakan tim
- Isi email dan PIC yang benar di bagian Kontak pada `index.html`.
- Absensi disimpan dengan `localStorage` pada browser/perangkat masing-masing. Ekspor menghasilkan file `.xls` Excel-compatible (SpreadsheetML). File hanya berisi absensi yang tersimpan pada browser tersebut. Untuk rekap multi-perangkat perlu backend/database, autentikasi, dan kontrol akses.
- Skenario studi kasus bersifat simulasi. Sesuaikan 8 Step dan daftar tool dengan standar internal.
- Tooltip download sukses berarti file telah diminta ke browser; browser dapat mengatur lokasi atau memblokir unduhan.

## Revisi konten dan kontak
Materi Tentang QCC, informasi kontak, dan FAQ mengikuti teks referensi yang diberikan. Verifikasi semua alamat, nomor telepon, nama PIC, dan jadwal sebelum publikasi. Formulir Kontak memakai `mailto:`: tombol menyiapkan pesan di aplikasi email pengguna, bukan mengirim langsung dari server. Gambar pertemuan QCC dimuat dari URL referensi dan membutuhkan internet.
