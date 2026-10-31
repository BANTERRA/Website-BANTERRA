# BANTERRA Website — versi demo

Website responsif untuk katalog pupuk granul organik berbasis batang semu pisang, pemesanan WhatsApp, narahubung, serta contoh portal pelanggan dan admin.

## Isi
- `index.html` — website satu halaman, CSS dan JavaScript sudah disertakan.
- Responsif untuk ponsel dan desktop.
- Katalog produk contoh, formulir kontak WhatsApp, portal login/register demo, dashboard admin demo.

## Penting sebelum dipublikasikan
1. Buka `index.html`, cari `const WA_NUMBER = "6281234567890"` lalu ganti dengan nomor WhatsApp resmi BANTERRA (format internasional tanpa `+`).
2. Ganti harga, ukuran, stok, deskripsi, alamat, email, dan seluruh informasi contoh dengan data yang benar.
3. Portal saat ini hanya **prototipe front-end**. Data disimpan di `localStorage` browser masing-masing, tidak tersinkron antar-pengunjung. Login dan kata sandi tidak aman untuk penggunaan nyata. Jangan gunakan untuk menyimpan data pelanggan sungguhan.
4. Untuk portal produksi dengan akun aman, katalog bersama, stok tersinkron, dan pesanan yang tercatat, hubungkan ke backend/auth/database (misalnya Supabase atau Firebase) dan tetapkan aturan keamanan sebelum digunakan.

## Cara mencoba
- Buka `index.html` di browser.
- Klik **Masuk Portal**.
- Admin demo: `admin@banterra.id` / `BanterraDemo!`
- Akun pelanggan: buat melalui menu Daftar.
- Perubahan admin hanya akan tampak di browser yang sama.

## Hosting gratis
### Opsi A — GitHub Pages
1. Buat akun di GitHub dan buat repository baru, misalnya `banterra-website`.
2. Unggah `index.html` ke folder utama repository.
3. Buka **Settings → Pages**.
4. Pilih **Deploy from a branch**, pilih branch `main` dan folder `/ (root)`, lalu simpan.
5. Tunggu proses selesai; GitHub akan memberikan URL publik untuk website.

### Opsi B — Netlify
1. Buka Netlify dan buat akun.
2. Pilih opsi deploy manual / drag-and-drop.
3. Unggah file `index.html` (atau folder yang berisi file tersebut).
4. Netlify akan memberikan URL publik. Kamu dapat mengubah nama subdomain melalui pengaturan situs.

Catatan: hosting statis gratis bisa menerbitkan website publik, tetapi tidak dengan sendirinya menyediakan backend aman untuk portal pelanggan/admin.
