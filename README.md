# Nyyyxyz Qur'an

Website Al-Qur'an digital dengan Next.js, dirancang untuk deploy ke Vercel.

## Fitur yang sudah tersedia
- Daftar 114 surah dari EQuran API v2
- Baca ayat Arab, latin, dan terjemahan Indonesia
- Audio satu surah dan audio per ayat dengan 6 pilihan qari
- Pencarian surah berdasarkan nama, arti, atau nomor
- Bookmark ayat tersimpan di browser
- Simpan posisi terakhir dibaca
- Dark mode
- Atur ukuran teks Arab dan tampil/sembunyikan latin/terjemahan
- Bagikan ayat
- Modal donasi dengan gambar QRIS yang diberikan
- Link saluran WhatsApp
- Responsive untuk HP dan desktop
- Metadata SEO dasar dan manifest PWA

## Menjalankan di komputer
Pastikan Node.js 20 atau lebih baru sudah terpasang.

```bash
npm install
npm run dev
```

Buka http://localhost:3000

## Deploy ke Vercel
1. Ekstrak ZIP ini.
2. Upload folder project ke repository GitHub.
3. Login ke https://vercel.com dan pilih **Add New → Project**.
4. Import repository GitHub tersebut.
5. Framework akan terdeteksi sebagai Next.js. Build command default `next build`.
6. Klik **Deploy**.

Tidak perlu mengisi environment variable untuk versi awal ini.

## Sumber data
Data surat, ayat, terjemahan, tafsir/audio disediakan melalui EQuran API v2:
https://equran.id/apidev/v2

Dokumentasi menyatakan data Al-Qur'an bersumber dari Kementerian Agama RI. Periksa ketentuan penggunaan API dan sumber audio sebelum publikasi.

## Catatan penting
- Bookmark dan riwayat tersimpan di localStorage browser masing-masing, belum tersinkron antarperangkat.
- Jadwal salat, kiblat, Asmaul Husna, doa harian, dan mode offline penuh belum diimplementasikan pada starter ini.
- QRIS disertakan dari gambar yang kamu unggah. Pastikan QR masih aktif dan nominal/identitas penerima sudah benar sebelum website dipublikasikan.
- QRIS pada gambar adalah kode dinamis/nominal terbuka sesuai payload yang tertanam. Lakukan uji scan menggunakan aplikasi pembayaran sendiri sebelum membagikannya.
