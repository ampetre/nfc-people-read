# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.0 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.0.apk)

The previously shared `NFC-People-Logger-latest.apk` URL is retained and downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.0**
- Internal version code: **21**
- Package: `com.andrei.nfcpeople`
- SHA-256: `7379b9ff279c16809a30105984e911851c19435945693b910a43b290d64b7987`
- Footer: `Version 2.0.0 • © andreimariuspetre`

### What is in v2.0.0

- **Add manually** inserts a person directly into the same active list as NFC reads.
- Manual entries use the current timestamp and immediately update the live list and counter.
- Tap an entry while the session is active for correction options.
- **Manual entries can be edited** before the session is finalized.
- **Any non-finalized entry can be deleted**, whether it came from an NFC scan or manual input.
- Deletion uses **one confirmation dialog**.
- The confirmation message is: `Do you want to remove the name "Name" from the list?`, with the selected name shown in **bold**.
- Confirmation buttons are **Yes, remove it from the list** and **No**.
- If a scanned row is deleted, its short NFC repeat guard is cleared so the same tag can be scanned again immediately.
- Finalized sessions remain read-only.
- Excel exports include a **Source** column:
  - `Scan` for NFC entries
  - `Manual` for manually entered entries
- RoB Excel output remains alphabetically sorted by person name using Romanian-aware, case-insensitive sorting.
- Each row keeps its original date and time.
- Existing NFC vibration behavior, rapid reads of different tags, empty-session closing, session persistence, Excel compatibility, RoB branding, responsive/Fold layout, package ID and signing identity are preserved.

### Upgrade compatibility

The regenerated v2.0.0 APK was explicitly checked against the published RoB v1.8.1 APK:

- v1.8.1: package `com.andrei.nfcpeople`, versionCode **10**
- v2.0.0 regenerated build: package `com.andrei.nfcpeople`, versionCode **21**
- Both use the same signing certificate

It can therefore be installed directly over RoB v1.8.x without uninstalling the app, preserving existing app data.

[Download RoB v2.0.0 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.0-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately and is not changed by this RoB release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)

## Installation

Download the RoB APK on Android and install it over the previous RoB version. The package name and signing identity are unchanged, so Android treats this regenerated v2.0.0 as an update and existing RoB application data is preserved.
