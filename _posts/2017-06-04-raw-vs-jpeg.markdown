---
layout: post
title: "Raw vs JPEG"
date: 2017-06-04 08:00
comments: true
categories:
- editing
---

Bila kita menggunakan kamera DSLR ataupun Mirrorless, biasanya kita akan mendapati pilihan kualitas gambar. Di kamera Nikon, biasanya pilihannya adalah:

* Raw
* Fine
* Normal
* Basic
* Raw + Fine
* Raw + Normal
* Raw + Basic

Fine, Normal, dan Basic akan menghasilkan file berekstensi `JPG`, masing-masing dibedakan dari kualitas pemrosesannya. Fine artinya paling bagus, Normal biasa saja, Basic artinya seadanya. Sedangkan Raw akan menghasilkan file berekstensi `NEF` (Nikon), `CR2` (Canon), `RAF` (Fuji), atau lainnya. Tidak ada pilihan kualitas bagus, sedang, seadanya untuk file Raw.

> Apa itu file Raw?

File raw menyimpan data apa adanya yang ditangkap sensor kamera. Sedangkan file `JPG` adalah file yang sudah diedit atau diolah oleh prosesor kamera. Bila kita ingin mencetak atau sharing foto di medsos, kita membutuhkan file `JPG`. Kita tidak bisa menggunakan file Raw karena ukurannya yang besar (bisa mencapai 40 MB per foto) dan kondisinya yang belum diproses.

> Lalu apa gunanya file Raw? Kenapa kita tidak pakai JPG saja?

Alasan pertama, teknik pemrosesan yang dilakukan oleh kamera belum tentu sesuai dengan keinginan kita. Masalah white balance, sharpening, pewarnaan, exposure, dan sebagainya, adalah masalah selera masing-masing fotografer. Analoginya, kita serahkan foto kita ke editor lain, lalu membiarkan dia mengedit suka-suka selera dia. Nah, editor lain ini adalah para insinyur pabrik kamera. Kalau kita terima beres `jpg` sama saja kita ikut apa selera insinyur Nikon/Canon/Fuji/dsb.

Alasan kedua, file Raw lebih bisa dimanipulasi daripada JPG, karena data yang ada dalam file jauh lebih banyak. Bandingkan saja ukuran filenya. File Raw ukurannya 20-40 MB, sedangkan file JPG hanya 5-10 MB saja. Dengan data yang lebih banyak, maka file bisa diedit dengan lebih ekstrim.

Untuk alasan kedua ini, biasanya untuk keperluan pekerjaan (fotografi yang dibayar client), para fotografer cari selamat dengan menggunakan file Raw. File raw dapat menyelamatkan foto yang tadinya sudah hopeless. Berikut contohnya.

<!--more-->

Foto ini saya buat dengan menggunakan setting Raw + Fine. Artinya kamera akan menyimpan file `NEF` dan `JPG`. Pertama, kita tampilkan `JPG`nya dulu. Ini hasilnya

[![Original JPEG]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021.JPG)]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021.JPG)

Hitam, tidak ada apa-apa di sana. Kalo kita amati dengan seksama, ada sedikit detail di sana, tapi jelas kalau ini foto pekerjaan, tentu tidak bisa kita deliver ke client. Kasus ini sangat mungkin terjadi misalnya bila flash kita gagal menyala.

Sekarang kita load file `NEF` dari foto di atas ke dalam aplikasi. Ada banyak aplikasi yang bisa mengolah file Raw, misalnya yang berbayar Adobe Lightroom, Capture One, dan lainnya. Untuk yang gratisan ada [Darktable](http://darktable.org), [Raw Therapee](http://rawtherapee.com/), [Photivo](http://photivo.org/), [UFRaw](http://ufraw.sourceforge.net/), dan sebagainya. Pada contoh ini, kita akan gunakan RawTherapee.

Berikut tampilannya dalam aplikasi sebelum diedit.

[![Raw Therapee sebelum edit]({{site.url}}/images/2017/raw-vs-jpeg/00-d5600-raw-original.png)]({{site.url}}/images/2017/raw-vs-jpeg/00-d5600-raw-original.png)

Sekarang, kita naikkan exposure 7 stop. Ini kira-kira sama dengan menaikkan ISO dari 100 menjadi 12800. Berikut hasilnya dalam aplikasi

[![Raw Therapee setelah edit]({{site.url}}/images/2017/raw-vs-jpeg/01-d5600-raw-processed.png)]({{site.url}}/images/2017/raw-vs-jpeg/01-d5600-raw-processed.png)

Kalau kita zoom 100% memang akan terlihat banyak noise

[![Zoom 100%]({{site.url}}/images/2017/raw-vs-jpeg/02-d5600-raw-100.png)]({{site.url}}/images/2017/raw-vs-jpeg/02-d5600-raw-100.png)

Tapi tetap lebih baik dibandingkan versi sebelum edit tadi.

Setelah kita export menjadi `JPG`, lumayanlah. Dalam ukuran kecil masih bisa dishare di medsos. Dengan pengeditan lebih lanjut, mungkin ini masih bisa dicetak. Berikut file `JPG` hasil export dari `NEF` tadi.

[![JPG hasil edit]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021-edit.jpg)]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021-edit.jpg)

Menaikkan exposure sampai 7 stop seperti ini tidak mungkin dilakukan bila filenya `JPG`. Silahkan dicoba sendiri kalau tidak percaya 😁. Ini filenya saya kasi:

* [File JPEG asli dari kamera]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021.JPG)
* [File RAW asli dari kamera]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021.NEF)
* [File JPEG hasil export setelah dinaikkan 7 stop]({{site.url}}/images/2017/raw-vs-jpeg/DSC_0021-edit.jpg)

Ini baru memperbaiki exposure. Yang lebih sulit adalah memperbaiki white balance. Bila kita cuma punya `JPG`, apa boleh buat, kita cuma bisa konversi jadi hitam putih. Karena informasi warnanya sudah hilang, tidak bisa dikembalikan lagi. Kalau kita punya RAW, kita bisa dengan mudah mengganti white balance di aplikasi.

Walaupun demikian, untuk pemakaian sehari-hari mungkin tidak mengapa hanya memotret `JPG` saja, soalnya file Raw ukurannya lumayan juga. Kalau satu file 25 MB, sehari piknik (misalnya dapat 100 foto) sudah butuh 2.5 GB.

Silahkan dipertimbangkan sendiri plus-minusnya. Mendingan beli harddisk atau kehilangan foto 😋
