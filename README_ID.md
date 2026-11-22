# OneState Tools — Samsung Galaxy A52s

Aplikasi pendamping Android sederhana. Tidak memodifikasi OneState dan tidak mengubah data server.

## Fitur
- Pemeriksaan koneksi perangkat (bukan pengujian endpoint server).
- Tombol membuka OneState dengan package `com.Chillgaming.oneState`.
- Informasi perangkat Android.
- Tips optimasi performa yang aman.

## Keamanan
Tidak meminta izin Accessibility, overlay, SMS, kontak, lokasi, atau akses file.
Tidak menyuntikkan kode ke game, tidak mengubah stamina/oksigen/saldo, dan tidak melewati anti-cheat.

## Build APK
1. Buka folder proyek ini di Android Studio.
2. Pastikan Android SDK Platform 35 dan JDK 17 tersedia.
3. Tunggu Gradle Sync selesai.
4. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK debug akan muncul di `app/build/outputs/apk/debug/app-debug.apk`.

Package aplikasi pendamping: `com.sofia.onestatetools`
Minimum Android: 8.0 (API 26)
Target SDK: 35

Catatan: proyek ini belum berupa APK terkompilasi. APK perlu dibangun melalui Android Studio dengan Android SDK.
