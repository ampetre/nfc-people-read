# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.0 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.0.apk)

The previously shared `NFC-People-Logger-latest.apk` URL is retained and downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.0**
- Version code: **20**
- Package: `com.andrei.nfcpeople`
- SHA-256: `5f90b06f2995bb69444f5cfd151fc0e6faf70cf378166092c0a652a56953b085`
- Footer: `Version 2.0.0 • © andreimariuspetre`

### What is new in v2.0.0

- **Add manually** inserts a person directly into the same active list as NFC reads.
- Manual entries use the current timestamp and immediately update the live list and counter.
- Tap an entry while the session is active for correction options.
- **Manual entries can be edited** before the session is finalized.
- **Any non-finalized entry can be deleted**, whether it came from an NFC scan or manual input.
- Deletion always requires **two separate confirmations** before the database row is removed.
- If a scanned row is deleted, its short NFC repeat guard is cleared so the same tag can be scanned again immediately.
- Finalized sessions remain read-only.
- Excel exports now include a **Source** column:
  - `Scan` for NFC entries
  - `Manual` for manually entered entries
- RoB Excel output remains alphabetically sorted by person name using Romanian-aware, case-insensitive sorting.
- Each row keeps its original date and time.
- Existing NFC vibration behavior, rapid reads of different tags, empty-session closing, session persistence, Excel compatibility, RoB branding, responsive/Fold layout, package ID and signing identity are preserved.

[Download RoB v2.0.0 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.0-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately. It was **not** changed by this RoB v2.0.0 release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)

## Installation

Download the RoB APK on Android and install it over the previous RoB version. The package name and signing identity are unchanged, so Android treats v2.0.0 as a normal update and existing RoB application data is preserved.
