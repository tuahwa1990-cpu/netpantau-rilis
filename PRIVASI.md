# Dasar Privasi NetPantau / NetPantau Privacy Policy

Kemas kini terakhir / Last updated: 13 November 2026

## Bahasa Melayu

NetPantau ialah apl pemantau trafik rangkaian untuk Android. Apl ini **tidak mengumpul, menjual atau berkongsi data peribadi anda**.

**Data yang diproses pada peranti anda sahaja**
- Kelajuan dan jumlah trafik rangkaian, penggunaan data setiap aplikasi (melalui "Akses penggunaan" yang anda benarkan sendiri).
- Nama domain yang diminta oleh peranti, jika anda menghidupkan "Pantau domain". Ini menggunakan VPN setempat pada peranti dan hanya melihat pertanyaan DNS (nama domain), bukan kandungan laman atau kata laluan. Senarai domain disimpan dalam memori sahaja dan hilang bila anda mengosongkan atau menutup pemantauan. Pertanyaan DNS diteruskan ke pelayan DNS rangkaian anda sendiri, atau, jika anda hidupkan "DNS disulitkan", ke penyedia pilihan anda (Cloudflare, Quad9 atau Google) melalui HTTPS. Anda boleh menghidupkan "Mod tanpa log" supaya senarai domain tidak disimpan langsung, atau memilih hapus log automatik.
- Cache DNS (hidup secara lalai, boleh dimatikan): jawapan DNS diingat dalam memori sahaja mengikut tempoh sahnya (paling lama 1 jam), tidak ditulis ke storan, dan tidak aktif dalam "Mod tanpa log".
- Laporan privasi: hanya kiraan setiap aplikasi (jumlah pertanyaan dan sekatan) disimpan pada peranti, tanpa nama domain. Anda boleh set semula bila-bila masa.
- Semak pautan: pautan yang anda tampal, atau kongsi kepada NetPantau melalui butang Kongsi, disemak pada peranti berbanding senarai yang telah dimuat turun. Pautan itu tidak dibuka, tidak disimpan dan tidak dihantar.
- Penapis pautan (pilihan): jika anda menjadikan NetPantau pelayar lalai, pautan yang anda tekan disemak pada peranti dahulu, kemudian diserahkan kepada pelayar atau apl pilihan anda. Pautan tidak disimpan dan tidak dihantar.
- Amaran pautan dalam mesej (pilihan, mati secara lalai): dengan akses notifikasi yang anda beri sendiri, NetPantau membaca teks notifikasi mesej baharu di peranti sahaja untuk mencari pautan dan ayat penipuan. Teks mesej tidak disimpan, tidak direkod dan tidak dihantar ke mana-mana; hanya cincangan ringkas disimpan dalam ingatan selama sejam supaya amaran tidak berulang.
- Papan klip: dibaca hanya apabila anda menekan Tampal & semak atau jubin Semak pautan.
- Tetapan anda (tema, kuota, senarai sekat/benarkan) disimpan pada peranti dan disulitkan dengan AES-256-GCM menggunakan kunci dalam Android Keystore.

**Sambungan internet yang dibuat oleh apl**
- Memuat turun senarai domain berbahaya/iklan awam (HaGeZi) dan maklumat kemas kini dari github.com. Fail ini ditandatangani secara digital dan disahkan oleh apl sebelum digunakan. Tiada data anda dihantar.
- Jika anda hidupkan DNS disulitkan: nama domain yang diminta dihantar kepada penyedia yang anda pilih (1.1.1.1, 9.9.9.9 atau 8.8.8.8), tertakluk kepada dasar privasi penyedia itu.
- Ujian kelajuan (hanya bila anda menekan butang) menghubungi speed.cloudflare.com, tertakluk kepada dasar privasi Cloudflare.
- Ujian keselamatan WiFi (hanya bila anda menekan butang) menghubungi connectivitycheck.gstatic.com (Google, melalui HTTP biasa untuk mengesan portal tawanan) dan 1.1.1.1 (Cloudflare). Tiada data peribadi dihantar.
- Pengimbas WiFi (hanya bila anda menekan butang) cuba menyambung kepada peranti dalam rangkaian WiFi anda sendiri sahaja.
- Senarai langganan: jika anda sendiri menambah pautan senarai, apl memuat turun senarai dari pautan itu.
- Pembangun NetPantau tidak mengendalikan sebarang pelayan dan tidak menerima apa-apa data daripada apl.

**Lain-lain**
- Tiada iklan, tiada penjejak, tiada analitik, tiada akaun.
- Nama WiFi (SSID) hanya dibaca jika anda memberi kebenaran Lokasi, hanya dipaparkan dalam apl, dan tidak disimpan atau dihantar.
- Sandaran dan laporan yang anda eksport disulitkan dengan kata laluan pilihan anda dan disimpan di tempat yang anda pilih.
- Apl atau laman kerajaan (.gov.my, .mil.my) dan apl yang anda kecualikan (contohnya apl bank) boleh dilepaskan daripada pemantauan dan sekatan.
- Anda boleh memadam semua data dengan menyahpasang apl.
- Untuk mengesahkan bahawa apl yang anda pasang ialah keluaran rasmi, lihat [SAHKAN.md](SAHKAN.md) atau skrin "Perihal dan sahkan apl" dalam apl.

Pertanyaan: buka isu di https://github.com/tuahwa1990-cpu/netpantau-rilis/issues

## English

NetPantau is a network traffic monitor for Android. It **does not collect, sell or share your personal data**.

**Data processed on your device only**
- Network speed and totals, and per-app data usage (via the "Usage access" permission you grant yourself).
- Domain names requested by the device, if you turn on "Monitor domains". This uses a local VPN on the device and sees only DNS queries (domain names), never page content or passwords. The list is kept in memory only and is cleared when you clear or stop monitoring. DNS queries are forwarded to your own network's DNS server or, if you turn on "Encrypted DNS", to your chosen provider (Cloudflare, Quad9 or Google) over HTTPS. You can turn on "No-log mode" so the domain list is never stored, or choose automatic log deletion.
- DNS cache (on by default, can be turned off): DNS answers are remembered in memory only for their validity period (at most 1 hour), never written to storage, and inactive in "No-log mode".
- Privacy report: only per-app counts (number of queries and blocks) are stored on the device, without domain names. You can reset them at any time.
- Link check: links you paste, or share to NetPantau through the Share button, are checked on the device against the lists already downloaded. The link is not opened, not stored and not sent.
- Your settings (theme, quota, block/allow lists) are stored on the device, encrypted with AES-256-GCM using a key held in Android Keystore.

**Internet connections made by the app**
- Downloads public threat/ad domain lists (HaGeZi) and update information from github.com. These files are digitally signed and verified by the app before use. None of your data is sent.
- If you turn on Encrypted DNS: the domain names requested are sent to the provider you choose (1.1.1.1, 9.9.9.9 or 8.8.8.8), subject to that provider's privacy policy.
- The speed test (only when you press the button) contacts speed.cloudflare.com, subject to Cloudflare's privacy policy.
- The WiFi security test (only when you press the button) contacts connectivitycheck.gstatic.com (Google, over plain HTTP to detect captive portals) and 1.1.1.1 (Cloudflare). No personal data is sent.
- The WiFi scanner (only when you press the button) tries to connect to devices on your own WiFi network only.
- Subscribed lists: if you add a list link yourself, the app downloads the list from that link.
- The NetPantau developer runs no servers and receives no data from the app.

**Other**
- No ads, trackers, analytics or accounts.
- The WiFi name (SSID) is read only if you grant Location permission, shown only in the app, and never stored or sent.
- Backups and reports you export are encrypted with a password of your choice and stored where you choose.
- Government sites and apps (.gov.my, .mil.my) and apps you exclude (for example banking apps) can be exempted from monitoring and blocking.
- You can delete all data by uninstalling the app.
- To verify that the app you installed is the official release, see [SAHKAN.md](SAHKAN.md) or the "About and verify app" screen in the app.

Questions: open an issue at https://github.com/tuahwa1990-cpu/netpantau-rilis/issues
