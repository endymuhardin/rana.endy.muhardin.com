---
layout: post
title: "Reparasi YongNuo Stuck di Full Power"
date: 2017-06-11 08:00
comments: true
categories:
- gears
---


Flash YongNuo merupakan paket speedlight dan trigger yang murah meriah dan cukup handal. Rekan-rekan saya di Komunitas Fotografi Bogor banyak yang menggunakan paket flash YongNuo di puluhan wedding dan sangat puas dengan hasilnya.

Saya sendiri juga menggunakan flash YongNuo selama 3 tahun lebih. Flash pertama yang saya miliki adalah YongNuo YN560-III yang sudah memiliki built-in wireless receiver. Artinya, kita tidak perlu lagi memasang perangkat tambahan untuk mengontrol power dan zoom flash dari jauh.

[![YongNuo Family]({{site.url}}/images/2017/yn-repair/yn-family.jpg)]({{site.url}}/images/2017/yn-repair/yn-family.jpg)

Setelah itu, saya membeli satu lagi YN560-IV. Versi yang lebih baru ini telah memiliki built-in transmitter dan receiver. Artinya dia bisa mengendalikan power dan zoom flash lain dari jauh.

Walaupun demikian, flash YongNuo ini memiliki satu penyakit yang cukup umum terjadi. Dia seringkali mengalami kerusakan di pengatur kekuatannya. Kalau sudah terjangkit penyakit ini, berapapun nilai power yang kita set di flash, dia akan selalu menyala dengan full power (`1/1`). Termasuk YN560-IV sayapun terjangkit wabah ini. Saking seringnya masalah ini terjadi, kita bisa menemukan banyak referensi di Google.

[![Google YN Stuck on Full Power]({{site.url}}/images/2017/yn-repair/yn-stuck-full-power.png)]({{site.url}}/images/2017/yn-repair/yn-stuck-full-power.png)

Pada artikel kali ini, kita akan mempraktekkan perbaikan YongNuo yang stuck di full power ini dengan mengikuti tutorial dari Youtube.

<!--more-->

Dari hasil google, kita menemukan ada yang memposting solusinya, yaitu dengan mengganti satu komponen yang disebut IGBT (**bukan LGBT yaa**). Artikelnya bisa dibaca [di sini](https://www.dpreview.com/forums/thread/3778930?page=2#forum-post-56304478). Selain itu, ada juga yang memposting video cara reparasinya.

<div class="video-container">
<iframe width="720" height="405" src="https://www.youtube.com/embed/ycPYUknwNfY?start=219" frameborder="0" allowfullscreen></iframe></div>

Dari artikel tersebut, terlihat bahwa cara perbaikannya sebetulnya tidak sulit. Hambatan utama adalah mencari komponen penggantinya.

Setelah lama mencari, akhirnya saya menemukannya di AliExpress dengan harga $0.8 per unit, minimum pembelian 5 unit. Total harganya menjadi 50 ribuan untuk 5 unit, free ongkir :D

[![AliExpress Sparepart]({{site.url}}/images/2017/yn-repair/aliexpress-yn-part.png)]({{site.url}}/images/2017/yn-repair/aliexpress-yn-part.png)

Silahkan klik [di sini](https://www.aliexpress.com/item/Free-shipping-5PCS-TIG056BF-TIG056-TO-220F-IGBT400V/32443316751.html) untuk membelinya.

Saya order tanggal 18 Agustus 2017, barangnya tiba tanggal 4 September 2017. Lumayanlah untuk free ongkir.

[![Paket AliExpress]({{site.url}}/images/2017/yn-repair/DSC_2623.png)]({{site.url}}/images/2017/yn-repair/DSC_2623.png)

Barangnya tiba, sekarang mari kita bongkar flashnya. Pertama, kita buka dulu plastik penutup di sisi flash. Plastik ini direkatkan dengan lem, jadi bisa dicongkel dengan aman.

[![Sebelum dibongkar]({{site.url}}/images/2017/yn-repair/DSC_2629.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2629.JPG)

Setelah plastik lepas, terlihat ada pengait besi. Ini juga tinggal dicongkel saja pakai obeng. Jangan lupa lepaskan baut di bawah kaca flash.

[![Pengait flash]({{site.url}}/images/2017/yn-repair/DSC_2630.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2630.JPG)

Flash sudah terbuka, kita bisa lihat komponen yang bermasalah.

[![Komponen bermasalah]({{site.url}}/images/2017/yn-repair/DSC_2632.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2632.JPG)

Gunting saja dengan tang, tidak perlu dilepas kakinya karena kita butuh untuk menempelkan kabel. Berikut perbandingannya dengan komponen yang baru kita beli.

[![Komponen lama vs baru]({{site.url}}/images/2017/yn-repair/DSC_2650.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2650.JPG)

Saya menggunakan metode `module unit` seperti yang dicontohkan [di video ini](https://youtu.be/VOXIHqty7Pc?t=2m30s) supaya kalau rusak lagi, tidak perlu bongkar flashnya. Untuk itu, kita membutuhkan socket yang bisa dikanibal dari power supply komputer bekas.

[![Power Supply Computer]({{site.url}}/images/2017/yn-repair/DSC_2634.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2634.JPG)

Socket ini memiliki 4 lubang, kebetulan ukurannya pas sekali dengan komponen pengganti.

[![Pemasangan Socket]({{site.url}}/images/2017/yn-repair/DSC_2638.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2638.JPG)

Untuk memasang socket ini di luar flash, kita harus melubangi casingnya. Selanjutnya solder kabelnya ke tempat komponen asli berada. Lalu rakit kembali.

[![Pemasangan Socket]({{site.url}}/images/2017/yn-repair/DSC_2657.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2657.JPG)

Karena lubang socketnya ada 4, sedangkan kaki komponen hanya 3, pastikan kita foto dulu supaya tidak lupa cara pemasangannya.

[![Pemasangan Socket]({{site.url}}/images/2017/yn-repair/DSC_2659.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2659.JPG)

Mari kita test. Kita akan memotret lensa dengan menggunakan flash yang dipantulkan (bounce) ke tembok.

[![Test Setup]({{site.url}}/images/2017/yn-repair/IMG_4777.JPG)]({{site.url}}/images/2017/yn-repair/IMG_4777.JPG)

Pertama, kita ambil ambient exposure dulu, tanpa flash. Settingnya adalah `1/40`, `f/5.6`, `ISO 100`. Setting yang sama akan kita gunakan selama test. Berikut hasilnya

[![No Flash]({{site.url}}/images/2017/yn-repair/DSC_2660.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2660.JPG)

Flash kita nyalakan dengan power `1/32`

[![Seper tigapuluhdua]({{site.url}}/images/2017/yn-repair/DSC_2662.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2662.JPG)

Flash power `1/16`

[![Seperenambelas]({{site.url}}/images/2017/yn-repair/DSC_2663.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2663.JPG)

Flash power `1/8`

[![Eighth Power]({{site.url}}/images/2017/yn-repair/DSC_2664.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2664.JPG)

Flash power `1/4`

[![Quarter Power]({{site.url}}/images/2017/yn-repair/DSC_2665.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2665.JPG)

Flash power `1/2`

[![Half power]({{site.url}}/images/2017/yn-repair/DSC_2666.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2666.JPG)

Terakhir, flash power `1/1` alias full power

[![Full power]({{site.url}}/images/2017/yn-repair/DSC_2667.JPG)]({{site.url}}/images/2017/yn-repair/DSC_2667.JPG)

Alhamdulillah, seperti kita lihat pada hasil test, komponen baru kita telah bisa mengatur power sehingga output dari flash sama dengan pengaturan di layar LCD flash.

Semoga bermanfaat bagi rekan-rekan yang mengalami masalah serupa. Selamat mencoba.
