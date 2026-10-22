# Analisis Komparatif Platform

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML, CSS, JavaScript/TypeScript (backend: PHP, Python, Node.js, Java) | Java, C#, C++, Python; JavaScript via Electron | Kotlin/Java (Android), Swift (iOS); lintas platform: Flutter (Dart), React Native |
| Arsitektur | Client-server: browser sebagai client, server menyimpan logika dan data | Aplikasi berjalan langsung di sistem operasi dan memakai sumber daya lokal | Aplikasi berjalan di perangkat dengan SDK OS, sering terhubung ke API/server |
| Cara distribusi | Di-deploy ke server/hosting dan diakses lewat URL | Installer (.exe, .msi, .dmg) diunduh atau lewat toko aplikasi | Google Play Store dan Apple App Store |
| Keunggulan | Lintas perangkat tanpa instalasi, update langsung oleh developer, jangkauan luas | Performa tinggi, akses penuh ke file dan perangkat keras, bisa offline | Akses sensor (kamera, GPS), notifikasi, selalu dibawa pengguna |
| Keterbatasan | Butuh internet, bergantung pada kemampuan browser, akses perangkat keras terbatas | Harus diinstal, perlu versi berbeda per OS, update dikelola per pengguna | Review dan aturan toko aplikasi, fragmentasi perangkat, ukuran layar dan baterai terbatas |
| Contoh aplikasi | Google Docs, Tokopedia (versi web), GitHub | Visual Studio Code, Microsoft Word, Adobe Photoshop | WhatsApp, Gojek, Instagram |

# Referensi

1. MDN Web Docs. *Learn web development*. https://developer.mozilla.org/en-US/docs/Learn
2. Electron. *Documentation*. https://www.electronjs.org/docs/latest
3. Android Developers. *Platform architecture*. https://developer.android.com/guide/platform