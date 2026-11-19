# Al-Qur'an Digital — Nyyyxyz

Website statis responsif yang bisa langsung di-deploy ke Vercel.

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka folder `al-quran-digital`.
3. Jalankan lokal dengan Live Server, atau deploy folder ini ke Vercel.
4. Untuk Vercel: New Project → Import project / upload folder melalui GitHub → Framework Preset pilih **Other** → Deploy.

## Fitur
- Daftar 114 surat dan pencarian
- Teks Arab, latin, terjemahan Indonesia
- Audio surat dan audio per ayat
- Bookmark ayat dan terakhir dibaca (localStorage)
- Tema gelap/terang
- Jadwal salat berdasarkan kota
- Doa harian (API)
- Tasbih digital
- Halaman donasi QRIS dan WhatsApp Channel
- Responsif untuk HP dan desktop

## Sumber data
- Al-Qur'an, terjemahan, dan audio: EQuran API v2 — https://equran.id/apidev/v2
- Doa harian: endpoint publik IDNBOGOR — https://cdn.idnbogor.id/\n- Asmaul Husna: Aladhan API — https://aladhan.com/prayer-times-api
- Jadwal salat: Aladhan API — https://aladhan.com/prayer-times-api

Data API membutuhkan koneksi internet. Beberapa endpoint pihak ketiga dapat berubah atau tidak tersedia sewaktu-waktu. Website menampilkan pesan jika data gagal dimuat.

## Catatan sebelum publikasi
- Periksa kembali hasil tampilan dan audio pada perangkatmu.
- QRIS disertakan dari gambar yang kamu unggah. Tes pemindaian dengan aplikasi pembayaran sebelum dipublikasikan.
- Ganti nama developer, link, atau aset di `index.html` jika diperlukan.
- Website ini bukan pengganti mushaf cetak atau bimbingan guru/ustaz. Jika menemukan perbedaan teks, verifikasi dengan mushaf dan sumber resmi.
