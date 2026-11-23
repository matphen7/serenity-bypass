# Changelog / Update Logs

Semua catatan pembaruan resmi **Seren1ty Bypasser**.

---

## [v2.0.0] — Release Build

### Keamanan & Proteksi Rilis
- Build rilis ditandatangani dengan **Release Keystore RSA 4096-bit** resmi (`APK Signature Scheme v2`).
- Ditambahkan proteksi **Anti-Decompile, Anti-Tamper, dan Anti-Hook** (verifikasi integritas tanda tangan aplikasi saat runtime, deteksi debugger/hook framework, serta pengacakan bytecode R8/ProGuard).
- Aset antarmuka dan konfigurasi penting terenkripsi dan dimuat aman saat runtime.

### Bypass & Branding
- Pembaruan tampilan kartu **Bypass V1**, **Bypass V2**, dan **Bypass Samsung** (`created by : dr4xcode`).
- Penyederhanaan hasil cek kompatibilitas perangkat (`Supported` / `Not Supported`) dan pembersihan output log agar lebih ringkas.
- Akun tanpa lisensi tetap dapat login dan mengakses tab **Bypass**, sementara tab **Injector** khusus untuk akun berlisensi aktif.

### Root Manager & Izin Aplikasi
- Perbaikan deteksi root manager (`ReSukiSU`, `KernelSU`, `Magisk`) serta alur permintaan izin deteksi aplikasi terpasang.
- Penanganan status superuser saat perangkat belum mendapat akses root atau saat permintaan administrator ditolak.

### Injector, Script Manager & UI
- Perbaikan **Inject WiFi** dengan deteksi otomatis SSID WiFi yang sedang aktif lalu menyimpan pengaturan Proxy Otomatis (PAC).
- Perbaikan kompatibilitas shell pada **Run Script** agar berjalan lancar tanpa dependensi utilitas tambahan yang tidak tersedia di Android.
- Perbaikan konsistensi tata letak UI/navigasi serta penonaktifan long-press / seleksi teks di WebView.
