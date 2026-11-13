# Sahkan NetPantau / Verify NetPantau

## Bahasa Melayu

Keluaran rasmi NetPantau (muat turun terus) ditandatangani dengan sijil yang mempunyai cap jari SHA-256 berikut:

```
4D:40:37:51:89:3B:B2:56:70:25:AB:0C:8C:72:39:48:33:8E:25:A7:AB:25:8E:00:F8:B3:1F:C3:47:5E:2E:C3
```

**Cara menyemak**

1. Dalam apl: Lagi → Perihal dan sahkan apl. Cap jari yang dipaparkan mesti sama dengan di atas.
2. Dengan komputer: `apksigner verify --print-certs NetPantau.apk` dan bandingkan baris "SHA-256 digest".
3. SHA-256 fail APK terkini disiarkan dalam `version.json` pada [halaman keluaran](https://github.com/tuahwa1990-cpu/netpantau-rilis/releases/tag/latest). Fail itu ditandatangani secara digital, dan apl menyemaknya sebelum memasang sebarang kemas kini.

Jika cap jari berbeza, jangan gunakan apl itu. Nyahpasang dan muat turun semula dari halaman keluaran rasmi sahaja.

Versi Google Play (jika ada) ditandatangani melalui Play App Signing dan boleh mempunyai cap jari yang berbeza.

## English

Official NetPantau releases (direct download) are signed with a certificate that has this SHA-256 fingerprint:

```
4D:40:37:51:89:3B:B2:56:70:25:AB:0C:8C:72:39:48:33:8E:25:A7:AB:25:8E:00:F8:B3:1F:C3:47:5E:2E:C3
```

**How to check**

1. In the app: More → About and verify app. The fingerprint shown must match the one above.
2. On a computer: `apksigner verify --print-certs NetPantau.apk` and compare the "SHA-256 digest" line.
3. The SHA-256 of the latest APK file is published in `version.json` on the [release page](https://github.com/tuahwa1990-cpu/netpantau-rilis/releases/tag/latest). That file is digitally signed, and the app verifies it before installing any update.

If the fingerprint differs, do not use that app. Uninstall it and download again from the official release page only.

The Google Play version (if available) is signed through Play App Signing and may have a different fingerprint.
