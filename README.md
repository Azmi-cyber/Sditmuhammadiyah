[README.md](https://github.com/user-attachments/files/29032009/README.md)
# Website SDIT Muhammadiyah Paya Mabar

Landing page satu halaman (single-file HTML) untuk SDIT Muhammadiyah Paya Mabar, dengan desain modern minimalis: banyak whitespace, garis tipis, dan warna flat tanpa gradient berat.

## Struktur File

```
index.html.html   # halaman utama (HTML + CSS + JS dalam satu file)
README.md                           # dokumen ini
```

## Cara Menjalankan

Tidak butuh server atau instalasi apa pun. Cukup buka file `sdit-muhammadiyah-paya-mabar.html` langsung di browser (klik dua kali atau drag ke tab browser).

Kalau ingin hosting online, bisa upload file ini ke layanan static hosting gratis seperti Vercel, Netlify, atau GitHub Pages.

## Isi Halaman

- **Beranda** — hero dengan judul, deskripsi singkat, kutipan filosofi pendidikan, dan statistik sekolah.
- **Profil** — penjelasan tentang visi pendidikan sekolah dan tiga poin utama.
- **Fasilitas** — mesjid, perpustakaan, lapangan olahraga.
- **Program Unggulan** — tahfidz Qur'an, bahasa Arab & Inggris, ekstrakurikuler, pembiasaan ibadah.
- **Tim Futsal** — foto dan deskripsi tim futsal putra sekolah.
- **Jadwal** — masuk sekolah Senin–Sabtu. Senin–Kamis: kelas 1–3 jam 08.00–13.00, kelas 4–6 jam 08.00–14.30. Jumat & Sabtu: seluruh kelas pulang jam 11.30.
- **Gedung Lama** — peta lokasi gedung lama sekolah (Google Maps embed).
- **Kontak** — informasi kontak dan peta lokasi sekolah.

## Yang Perlu Disesuaikan

Beberapa data masih berupa contoh/placeholder dan sebaiknya diganti dengan data asli sekolah sebelum dipublikasikan:

- Alamat lengkap, nomor telepon, dan email di bagian **Kontak**.
- Jumlah siswa, tenaga pendidik, dan tahun berdiri di bagian **Beranda**.
- Logo sekolah dan foto tim futsal diambil dari `https://sditmuhammadiyah.vercel.app/`. Kalau alamat tersebut berubah, ganti URL gambar di file HTML pada bagian `<img src="...">`.
- Peta lokasi pada bagian **Gedung Lama** dan **Kontak** menggunakan kode embed Google Maps yang sama. Kalau lokasi atau gedung berubah (misalnya sudah ada gedung baru), ganti link `src` pada `<iframe>` dengan kode embed baru dari Google Maps (klik Bagikan → Sematkan peta), dan ganti foto/teks bagian "Gedung Lama" sesuai kondisi terbaru.

## Desain

Arah desain: modern minimalis. Palet warna hijau tua (`#14532d`) sebagai aksen utama, krem hangat (`#fbf9f4`) sebagai latar, dan emas pudar (`#b3873e`) sebagai detail kecil (label, garis pemisah). Font judul memakai Fraunces (serif berkarakter), font isi memakai Inter. Kartu fasilitas, program, dan jadwal disusun dalam grid bergaris tipis (bukan kartu melayang dengan shadow besar) untuk kesan rapi dan flat.

## Kredit

Dibuat oleh **Azmi** — Fullstack Developer.

## Teknologi yang Digunakan

- HTML5, CSS3 (tanpa framework), dan JavaScript vanilla.
- Font Google Fonts: Fraunces (judul) dan Inter (teks isi).
- Animasi scroll reveal menggunakan `IntersectionObserver`.
- Navbar responsif dengan menu mobile (hamburger).
