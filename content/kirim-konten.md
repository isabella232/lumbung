---
title: "Kirim Konten"
layout: "tentang"
---

# Lumbung Gimpscape ID

Lumbung Gimpscape ID (Lumbung), merupakan wadah berbagi sumber daya bebas pakai untuk aplikasi open source. Untuk saat ini kami mengelompokkan sumberdaya ini berdasarkan aplikasi pengolahnya;

- Inkscape
  Sumberdaya bebas pakai untuk aplikasi pengolah vektor Inkscape.
- LibreOffice
  Sumber daya bebas pakai untuk aplikasi perkantoran LibreOffice.
- General
  Sumber daya bebas pakai untuk aplikasi open source lain secara umum.
- Lain-lain
  Sumber daya bebas berupa buku, tutorial, dan lain sebagainya.

## Berbagi Sumber Daya

Untuk Anda yang ingin membagikan sumber daya ke Lumbung, kami telah menyiapkan beberapa metode pengiriman sumber daya.

#### Melalui Pull Request  

Pastikan [Hugo](https://gohugo.io) sudah terpasang di komputer Anda. Selanjutnya fork & clone repositori ini ke akun Github Anda. Kemudian jalankan salah satu perintah berikut.

```bash

# Jika hendak menambah konten untuk kategori Inkscape:
hugo new --kind inkscape 'materi/Judul Sumberdaya'

# Jika hendak menambah konten untuk kategori LibreOffice:
hugo new --kind libreoffice 'templat/Judul Sumberdaya'

# Jika hendak menambah konten untuk kategori General:
hugo new --kind general 'tema/Judul Sumberdaya'

# Jika hendak menambah konten untuk kategori Lain-Lain:
hugo new --kind lain-lain 'tema/Judul Sumberdaya'

```

Langkah selanjutnya adalah melengkapi data konten yang akan ditambahkan. Untuk melakukannya, silakan sunting berkas index.md yang terdapat pada direktori `content/inkscape` misalnya, untuk konten berupa sumberdaya untuk kategori Inkscape.

Jika sudah, silakan buat commit terhadap perubahan Anda, kemudian segera ajukan Pull Request. Pastikan deskripsi commit ditulis dengan ringkas dan jelas. 

Sebelum mendorong perubahan, Anda dapat terlebih dahulu meninjau perubahan yang Anda buat dengan menjalankan Hugo.

```bash
hugo server
```

#### Melalui Formulir Google  

Untuk Anda yang belum terbiasa menggunakan perintah-perintah git, kami telah menyediakan Google Form untuk membantu Anda mengirimkan konten sumber daya yang hendak dibagikan.

Silakan merujuk pada [tautan ini](https://forms.gle/iDNQw9US1yTWfq8U6) untuk mulai mengirim berkas Anda.

## Lisensi
Setiap berkas yang dikirimkan ke Lumbung akan dilisensikan di bawah lisensi [CC by SA 4.0 ](https://creativecommons.org/licenses/by-sa/4.0/deed.id). Apabila Anda tidak berkenan menggunakan lisensi ini, silakan cantumkan jenis lisensi CC lain yang Anda kehendaki pada bagian deskripsi konten.

## Bantuan
Apabila Anda mengalami kesulitan dalam pengiriman konten, silakan untuk melapor ke grup [Telegram Gimpscape](https://t.me/gimpscape).

## Lain-Lain
Laman Lumbung ini masih akan disempurkan dari waktu ke waktu. Silakan berkabar kepada kami bila Anda memiliki ide atau saran untuk memperbaiki layanan ini melalui Issue Github.
