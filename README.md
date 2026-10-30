# Catatan Pengairan Jagung

Halaman web satu file (`index.html`) untuk mencatat pengairan 15 varietas jagung: waktu pagi/sore, jumlah baris, durasi, kondisi tanah.

Tanpa server dan tanpa database. Data tersimpan di browser perangkat yang dipakai. Gunakan menu "Cadangan data" untuk mengunduh dan memulihkan data.

## Deploy ke Vercel

### Lewat GitHub (bisa dari HP)
1. Buat repository baru di GitHub.
2. Pilih Add file > Upload files, unggah `index.html`, lalu Commit.
3. Di vercel.com pilih Add New > Project, impor repository itu.
4. Biarkan semua pengaturan bawaan (Framework Preset: Other), lalu Deploy.

### Lewat Vercel CLI (dari komputer)
```
npm i -g vercel
cd pengairan-jagung
vercel --prod
```

Setelah selesai, buka alamat `*.vercel.app` di HP.

## Catatan
- Data tiap perangkat terpisah. Untuk memindahkan data ke perangkat lain: Unduh cadangan, lalu Pulihkan dari file.
- Alamat Vercel bisa dibuka siapa saja yang tahu tautannya, tetapi mereka hanya melihat aplikasi kosong miliknya sendiri. Data Anda tidak ikut terlihat.
