# Dasar Privasi NetPantau / NetPantau Privacy Policy

Kemas kini terakhir / Last updated: 12 November 2026

## Bahasa Melayu

NetPantau ialah apl pemantau trafik rangkaian untuk Android. Apl ini **tidak mengumpul, menjual atau berkongsi data peribadi anda**.

**Data yang diproses pada peranti anda sahaja**
- Kelajuan dan jumlah trafik rangkaian, penggunaan data setiap aplikasi (melalui "Akses penggunaan" yang anda benarkan sendiri).
- Nama domain yang diminta oleh peranti, jika anda menghidupkan "Pantau domain". Ini menggunakan VPN setempat pada peranti dan hanya melihat pertanyaan DNS (nama domain), bukan kandungan laman atau kata laluan. Senarai domain disimpan dalam memori sahaja dan hilang bila anda mengosongkan atau menutup pemantauan. Pertanyaan DNS diteruskan ke pelayan DNS rangkaian anda sendiri.
- Tetapan anda (tema, kuota, senarai sekat/benarkan) disimpan pada peranti dan disulitkan dengan AES-256-GCM menggunakan kunci dalam Android Keystore.

**Sambungan internet yang dibuat oleh apl**
- Memuat turun senarai domain berbahaya/iklan awam (HaGeZi) dari github.com. Tiada data anda dihantar.
- Ujian kelajuan (hanya bila anda menekan butang) menghubungi speed.cloudflare.com, tertakluk kepada dasar privasi Cloudflare.

**Lain-lain**
- Tiada iklan, tiada penjejak, tiada analitik, tiada akaun.
- Nama WiFi (SSID) hanya dibaca jika anda memberi kebenaran Lokasi, hanya dipaparkan dalam apl, dan tidak disimpan atau dihantar.
- Sandaran dan laporan yang anda eksport disulitkan dengan kata laluan pilihan anda dan disimpan di tempat yang anda pilih.
- Anda boleh memadam semua data dengan menyahpasang apl.

Pertanyaan: buka isu di https://github.com/tuahwa1990-cpu/netpantau-rilis/issues

## English

NetPantau is a network traffic monitor for Android. It **does not collect, sell or share your personal data**.

**Data processed on your device only**
- Network speed and totals, and per-app data usage (via the "Usage access" permission you grant yourself).
- Domain names requested by the device, if you turn on "Monitor domains". This uses a local VPN on the device and sees only DNS queries (domain names), never page content or passwords. The list is kept in memory only and is cleared when you clear or stop monitoring. DNS queries are forwarded to your own network's DNS server.
- Your settings (theme, quota, block/allow lists) are stored on the device, encrypted with AES-256-GCM using a key held in Android Keystore.

**Internet connections made by the app**
- Downloads public threat/ad domain lists (HaGeZi) from github.com. None of your data is sent.
- The speed test (only when you press the button) contacts speed.cloudflare.com, subject to Cloudflare's privacy policy.

**Other**
- No ads, trackers, analytics or accounts.
- The WiFi name (SSID) is read only if you grant Location permission, shown only in the app, and never stored or sent.
- Backups and reports you export are encrypted with a password of your choice and stored where you choose.
- You can delete all data by uninstalling the app.

Questions: open an issue at https://github.com/tuahwa1990-cpu/netpantau-rilis/issues
