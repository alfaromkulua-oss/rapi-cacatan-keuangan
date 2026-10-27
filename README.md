# Rapi — Catatan Keuangan

Aplikasi web responsif berbahasa Indonesia untuk mencatat pemasukan, pengeluaran, melihat ringkasan dan grafik arus kas, mengatur anggaran bulanan, serta mengunduh catatan sebagai CSV.

## Jalankan di komputer

Buka `index.html` di browser. Untuk fitur instalasi PWA dan mode offline, sajikan folder ini melalui HTTPS atau server lokal.

## Buka dari HP di jaringan Wi-Fi yang sama

Jalankan server web lokal dari folder ini, misalnya `python -m http.server 8000`, lalu buka alamat IP komputer dan port `8000` dari browser HP. Komputer dan HP harus memakai Wi-Fi yang sama.

## Pasang di layar utama HP

Terbitkan aplikasi di hosting HTTPS publik terlebih dahulu. Buka URL-nya dari Chrome di Android atau Safari di iPhone, lalu gunakan menu **Tambahkan ke layar utama / Add to Home Screen**. Pada browser yang mendukung, tombol **Pasang di HP** juga akan muncul. File ZIP yang disediakan adalah paket web, bukan APK Android.

## Bagikan ke semua orang

Unggah seluruh isi folder ini ke hosting web statis yang menyediakan HTTPS. Setelah itu, bagikan URL publik yang diberikan hosting. File statis ini siap diunggah tanpa proses build. Aplikasi belum memiliki URL publik sebelum diunggah.

## Catatan data

Transaksi dan anggaran tersimpan di `localStorage` browser pada masing-masing perangkat. Data tidak tersinkron otomatis dan tidak terlihat oleh pengguna lain. Hapus data browser berarti menghapus catatan lokal. Foto pada halaman diambil dari Unsplash dan memerlukan koneksi internet.
