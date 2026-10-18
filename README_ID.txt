FPS BOOST - PROYEK ANDROID NATIVE JAVA
====================================

Ini proyek Android native Java, bukan WebView.

FITUR:
- UI gelap-merah FPS BOOST
- Tombol ON/OFF (status UI lokal saja)
- Pemilih dokumen Android untuk memilih beberapa file
- File yang dipilih disalin ke penyimpanan privat aplikasi: files/imported
- Daftar nama dan ukuran file
- Hapus satu file atau semua file
- Daftar dan status ON/OFF disimpan lokal

BATASAN:
- Tidak menulis ke Android/data/com.dts.freefireth atau gameassetbundles.
- Tombol ON/OFF bukan pengubah FPS sungguhan.
- File impor berada di penyimpanan privat aplikasi dan tidak terlihat sebagai folder umum biasa.

BUILD:
1. Ekstrak ZIP.
2. Buka folder FPS_BOOST di Android Studio atau IDE Android yang mendukung proyek Gradle.
3. Tunggu Gradle sync lalu Build APK.
Proyek memakai Android Gradle Plugin 8.6.1, compileSdk 35, Java bawaan.
