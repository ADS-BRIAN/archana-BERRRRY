# Gacha Design Studio

![Gacha Design Studio](archanaberry/banner.png)

# Tipe cabang (branch) repositori
* DL untuk edisi didownload agar bisa dimainkan resource game nya pakai game browser GachaDesignStudio.apk (com.lunime.githubcollab.archanaberry.gachadesignstudio)
* HS untuk edisi hosting online di vps/panel/termux agar bisa bantu dikembangkan untuk server dan dimainkan dengan bersama kolaborator tetapi harus pakai game browser khusus

# Ikon aplikasi web nya

![Gacha Desing Studio](archanaberry/icon.png)

Gacha Design Studio adalah sebuah game fanmade (buatan dari para penggemar) yang mengambil inspirasi dari Gacha Life 2 yang dikembangkan oleh Lunime. Game ini memungkinkan pemain untuk merancang karakter, memilih pakaian, dan menciptakan desain yang unik.

![Github](archanaberry/github.png)

## Fitur Utama

| Fitur             | Deskripsi                                                                                   |
|-------------------|----------------------------------------------------------------------------------------------|
| Pembuatan Karakter| Buat karakter unik dengan berbagai pilihan wajah, mata, rambut, dan aksesoris.               |
| Desain Pakaian    | Desain pakaian dengan berbagai motif, warna, dan gaya untuk karakter yang dibuat.            |
| Studio Foto       | Ambil foto karakter yang telah dibuat dalam berbagai pose dan latar belakang yang berbeda.  |
| Mode Fashion Show | Tunjukkan desain pakaian terbaik Anda dalam kompetisi mode virtual dengan pemain lain.      |
| Koleksi Item      | Kumpulkan berbagai item fashion dan aksesoris untuk menambah variasi dalam desain Anda.      |
| Berbagi karakter  | Bagikan karakter anda untuk berkolaborasi dengan teman anda lewat kode karakter dan juga impor |
| Aset Vektor       | Menjadikan kualitas gambar di karakter gacha mu jadi tajam dan tanpa penurunan kualitas hanya saja sedikit lagyy |
| Map Vektor        | Sebuah map dunia fiktif permainan yang menjadikan nya sangat luas tanpa penurunan kualitas dan bisa di zoom |
| Studio Pose       | Buatlah pose dengan mudah dengan gaya karakter yang anda inginkan dan animasi pose (untuk animasi ditunggu) |
| Bisa dimainkan secara offline | Kamu bebas memainkan game ini disaat tanpa ada kuota internet dengan sepuas puas nya UwU |

## Link

![Gacha Life 2](archanaberry/gachaassets.png)
Kunjungi [Gacha Life 2 Assets](https://drive.google.com/file/d/1RKEoUYibFckKS10PS7cGm9bbfmgZJIp2/view?usp=drive_link) untuk berkustomisasi karakter yang anda inginkan UwU.

# Untuk saat ini versi aset nya masih v0.01_alpha...

## Cara buka?
Kamu tinggal download repositori ini dengan game browser "GachaDesignStudio.apk" nya, klik setuju pada penyimpanan, lalu tunggu sampai ke download semua resource zip nya.
Setelah berhasil download secara otomatis kebuka game nya di file `mainmenu.html` nya dan langsung rangkai sesuka mu XD
* Ini dia
![Gacha Life 2](archanaberry/downloadrepo.png)

## Cara menambahkan assets karakter ke studio poser
```
---
JavaScript
File: js/poser/main.js
---

const layers = [
    
    // lapisan //
    // Tangan kanan
    new Layer('Lengan atas kanan', 'assets/arm1.svg', 'assets/arm2.svg', {flipX: true}),
    new Layer('Lengan bawah kanan', 'assets/hand1.svg', 'assets/hand2.svg', {flipX: true}),
    new Layer('Tangan kanan', 'assets/finger3.svg', 'assets/finger4.svg', {flipX: true}),

    // Kaki kanan
    new Layer('Paha atas kanan', 'assets/leg1.svg', 'assets/leg2.svg', {flipX: true}),
    new Layer('Kaki kanan', 'assets/foot1.svg', 'assets/foot2.svg', {flipX: true}),

    // Kepala
    new Layer('Badan', 'assets/body1.svg', 'assets/body2.svg'),

    // Badan
    new Layer('Kepala', 'assets/head1.svg', 'assets/head2.svg'),

    // Tangan kiri
    new Layer('Lengan atas kiri', 'assets/arm1.svg', 'assets/arm2.svg'),
    new Layer('Lengan bawah kiri', 'assets/hand1.svg', 'assets/hand2.svg'),
    new Layer('Tangan kiri', 'assets/finger1.svg', 'assets/finger2.svg'),

    // Kaki kiri
    new Layer('Paha atas kiri', 'assets/leg1.svg', 'assets/leg2.svg'),
    new Layer('Kaki kiri', 'assets/foot1.svg', 'assets/foot2.svg'),
    // Lapisan //

// tambahkan dengan format //
// new Layer('Nama anggota tubuh', 'assets/anggotaBadanOutline.svg', 'tambahan...', 'assets/anggotaBadan.svg'),
// Jangan lupa diganti dan disesuaikan
// seperti ini ygy //

];
```

## Kekurangan dan Kendala

* ✅ Berhasil di tangani.
* ❎ Belum di tangani.

| Kekurangan                                    | Deskripsi                                                                                      | Status |
|-----------------------------------------------|------------------------------------------------------------------------------------------------|--------|
| Keterbatasan Aset                             | Saat ini, game masih terbatas dalam jumlah aset yang tersedia karena baru dirilis.             | ❎ |
| Karakter Dummy/Template                       | Karakter dalam game masih dalam bentuk dummy atau template kosong, belum memiliki rambut atau aksesori yang lengkap. | ❎ |
| Zoom Belum Aktif                              | Fitur zoom untuk melihat detail lebih jauh dalam pembuatan karakter atau desain pakaian masih belum aktif. | ✅ |
| Flip Vertikal dan Horizontal Bermasalah      | Fitur flip vertikal dan horizontal saat ini mengalami masalah teknis yang membuatnya ngebug.   | ✅ |
| Selektor Karakter Belum Aktif Sepenuhnya     | Selektor karakter masih belum berfungsi sepenuhnya, sehingga pengguna belum dapat dengan mudah memilih karakter yang ingin dimodifikasi. | ✅ |
| Tidak Ada Fitur Berbagi Karakter dengan Kode atau Upload Aset SVG | Fitur untuk berbagi karakter menggunakan kode atau mengunggah aset SVG sebagai tambahan aset belum ditambahkan. | ❎ |
| Input box Lebar/Width, dan Tinggi/Height nya bermasalah | Ketika bisa diubah nilai nya tetapi tidak mengalami perubahan posisi | ❎ |
| Pengingat jika tidak sengaja ke refresh | Untuk mencegah kehilangan posisi pose ataupun rangkai karakter Gacha mu | ❎ |
| Belum ada main menu | Supaya terkesan ada menu awal permainan | ✅ |
| Belum ada BGM | Fitur untuk menyegarkan suasana dengan musik yang aesthetic agar tidak monoton (hanya saja harus pakai aplikasi apk dikhususkan!) | ✅ |
| Design UI/UX masih berantakan | Untuk menambah ke estetika game ini agar menarik pengunjung :3 | ❎ |
| Loading Main Menu | Berfungsi untuk meload semua source game web ini | ✅ |
| Sudah ditambah ikon thumbnail karakter | Ikon karakter agar mudah dicari dan menambah estetika profile karakter gacha mu :> | ❎ |

## Tangkapan Layar
* Main menu
Tablet 1200x2000 (Portrait mode)
![Gacha Life 2](archanaberry/screenshot3.png)

* Mode Studio Pose
Tablet 2000x1200 (Landscape mode)
![Gacha Life 2](archanaberry/screenshot2.png)
PC/Laptop 1366x768 (Landscape mode)
Diperbarui
![Gacha Life 2](archanaberry/screenshot1.png)

## Bahasa pemrograman yang dipakai
<img src="archanaberry/HTML.png" alt="HTML versi 5" width="192" height="108">
<img src="archanaberry/htmx.png" alt="HTML dengan dukungan JavaScript" width="192" height="108">
<img src="archanaberry/CSS.png" alt="Dukungan CSS" width="192" height="108">
