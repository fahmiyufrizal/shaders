# SlimShaders
Optimized for Diskless - Written using Python and some hopes - 2025

## Special Thanks to
Reesya Natalia [(Facebook)](https://www.facebook.com/reesya.natalia) yang sudah share path shadersnya di grup dan om Kroco Latoz [(Facebook)](https://www.facebook.com/bdstd21) yang sudah bantu develop ini!

## Penjelasan, Requirements, dan Cara Kerja
### Penjelasan
SlimShaders adalah sebuah program "sederhana" yang menjalankan beragam command dari server dan client yang membuat shaders dapat tersimpan di sisi server. Sehingga, client tidak perlu melakukan load ulang yang terlalu lama. 
> **Program ini bukan berarti menghilangkan proses compiling shaders, jadi jangan berekspektasi lebih!**
### Requirements
- Jaringan lokal yang sehat
- Space di gamedisk yang cukup, sangat disarankan memakai gamedisk dengan kapasitas paling besar (dan sehat tentunya)
> Cara menghitung perkiraan space : jumlah client x 2GB\
> Misal 20 client -> 20 x 2GB = 40GB
- Sharing Folders di sisi server dan client yang bekerja optimal
### Cara Kerja
Shaders yang sudah dibuat oleh user sebelumnya, akan ter-load otomatis sehingga tidak melakukan pembuatan shaders berulang (kecuali jika ada update baru yang menyebabkan shaders tercompile ulang)

## Features
- Auto prepare folders Shaders (Server dan Client)

## Compability
### GPU(s)
Tested on :
> NVIDIA
- RTX 2060s
- GTX 1660s
> AMD (Need more data)
- AMD Radeon RX 6600 XT
> Intel ARC
- Untested (ga punya GPU nya gwe bjir)
### Games
- Delta Force Steam
- Delta Force Garena
- Marvel Rivals (masih perlu compile shaders sebentar setelah restart/penggunaan selanjutnya)
- Apex Legends (masih perlu compile shaders sebentar setelah restart/penggunaan selanjutnya)
- Wuthering Waves (masih perlu compile shaders sebentar setelah restart/penggunaan selanjutnya, butuh data lebih valid)
> Fortnite untested
> CoD untested, tapi sudah disupport

## Cara Pasang
1. Download zip di [releases](https://github.com/fahmiyufrizal/shaders/releases) lalu ekstrak ke gamedisk
2. Jalankan Run_SlimShaders_Server.exe di server (dan buat shortcut di startup juga biar ga bolak balik buka saat startup)
3. Buat shortcut Run_SlimShaders_Client.exe di startup client
4. SlimShaders_Client akan terbuka dan menjalankan command otomatis saat client dinyalakan

## Tutorial Video
1. Persiapan Server [(Facebook)](https://www.facebook.com/share/v/1K7zP6ve8U/)
2. Delta Force Steam [(Facebook)](https://www.facebook.com/share/v/1YVtDkx4TT/)
3. Delta Force Garena [(Facebook)](https://www.facebook.com/share/v/1DVkvfpJfS/)
4. Integrasi ClientApp/Startup Script [(Facebook)](https://www.facebook.com/share/v/1ETDGv8gNa/)

## Support
Donasi di [QRIS](https://bit.ly/donate_fahmiyufrizal), [DANA](https://bit.ly/donate_fahmiyufrizal), dan [Paypal](https://paypal.me/fahmiyufrizal) untuk mendukung keberlangsungan project ini!\
Jika ada feedback, silahkan pe-em!

## Last but not least
Thank's to :
- Sena Walker Wibowo
- Ignatius Wisnu
- Hanung Dwi
- AyraGaming Pacitan
- 21Net Madiun
- Orlin Net Manisrejo
