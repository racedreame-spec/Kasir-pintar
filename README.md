# Kasir QRIS

Aplikasi kasir untuk HP yang jalan di browser dan bisa dipasang seperti aplikasi biasa.

## Fitur
- QRIS dinamis dari QRIS pribadi (nominal terisi otomatis)
- Katalog barang, kelompok, kode barcode, scan produk lewat kamera
- Keranjang, diskon, biaya admin, catatan struk
- Bayar QRIS atau tunai (kembalian otomatis), catat utang
- Struk otomatis: cetak (RawBT, Bluetooth, atau cetak biasa), bagikan foto atau teks
- Riwayat, rekap harian, cek pembayaran
- Impor dan ekspor katalog (Excel/CSV), cadangan lengkap

## Cara memasang di GitHub Pages
1. Unggah semua file di repository ini (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png).
2. Settings -> Pages -> Source: Deploy from a branch -> Branch: main, folder / (root) -> Save.
3. Tunggu beberapa menit, lalu buka alamat `https://NAMA-AKUN.github.io/NAMA-REPOSITORY/`.
4. Di Chrome Android: menu titik tiga -> Instal aplikasi.

## Memperbarui
Unggah file yang baru dengan nama yang sama (Add file -> Upload files) lalu Commit changes. Tutup aplikasi sepenuhnya dan buka lagi.

## Data
Semua data (QRIS, katalog, riwayat, utang) tersimpan di perangkat, bukan di GitHub. Buat cadangan rutin lewat Menu -> Cadangan dan Menu -> Ekspor katalog, lalu simpan di tempat aman.
