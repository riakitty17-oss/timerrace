RaceMeter - proyek Android (WebView)

CARA A - TANPA ANDROID STUDIO (build di cloud, gratis, lewat browser)
1. Buat akun di github.com, lalu buat repository baru (New repository).
2. Ekstrak zip ini. Di halaman repository pilih "uploading an existing file" lalu seret
   SEMUA isi folder RaceMeter (termasuk folder .github yang tersembunyi) dan klik Commit.
   Kalau folder .github tidak ikut terunggah: Add file > Create new file, ketik nama
   .github/workflows/build.yml lalu tempel isi file tersebut dari zip.
3. Buka tab "Actions". Build jalan otomatis (sekitar 3-5 menit). Kalau tidak, pilih
   "Build APK" lalu "Run workflow".
4. Setelah centang hijau, buka run tersebut, turun ke bagian "Artifacts", unduh
   RaceMeter-APK (zip berisi app-debug.apk).
5. Kirim APK ke HP, buka, izinkan pemasangan dari sumber tidak dikenal, dan izinkan lokasi.

CARA B - ANDROID STUDIO
File > Open folder ini, tunggu Gradle sync, Build > Build APK(s).
Hasil: app/build/outputs/apk/debug/app-debug.apk

Mengubah tampilan atau fitur: edit app/src/main/assets/index.html
