# NFC tag reader applications

This repository provides two Android variants built from the same NFC session and Excel-export foundation.

## 1. RoB NFC tag reader

Customized for Runners of Bucharest:

- RoB name and logo
- NFC reads and manual entries share the same active-session list
- Excel rows sorted alphabetically by the person name
- Romanian-aware, case-insensitive sorting
- Package: `com.andrei.nfcpeople`

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v1.9.0 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v1.9.0.apk)

The previously shared `NFC-People-Logger-latest.apk` URL is retained and downloads the same current RoB APK.

### RoB current version

- Version: **1.9.0**
- Version code: **11**
- SHA-256: `bb1913098742c1b887bb6d8f04e83db8cef2c4725889a54e7a39831867b91e03`
- Footer: `Version 1.9.0 • © andreimariuspetre`

## 2. NFC to Excel tag reader

Generic version prepared for public distribution and Google Play:

- generic NFC-to-Excel name and logo
- NFC reads and manual entries share the same active-session list
- Excel rows retained in chronological/original scan order
- separate package so it can coexist with the RoB app
- Package: `com.andrei.nfctoexceltagreader`

The Google Play candidate has been advanced to **v1.9.0 / versionCode 11**. The standalone GitHub APK link below remains the prior public sideload build until the generic v1.9.0 APK is republished there.

[**Download currently published generic APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/NFC-to-Excel-tag-reader-latest.apk)

## Changes in v1.9.0

- Added **Add manually** on the active reading screen.
- A manually entered person is inserted immediately into the same list and counter as NFC scans.
- Manual entries use the current timestamp and are included in review/history and Excel export.
- No separate manual-attendance list is needed.
- Existing NFC reading, vibration feedback, duplicate-tag handling, empty-session closure and session persistence are preserved.
- RoB retains alphabetical Excel export.
- NFC to Excel retains chronological/original scan-order export.

## Installation

1. Download the required APK on an Android phone.
2. Open the downloaded file.
3. Allow installation from the browser or file manager when Android requests it.
4. Open the app and enable NFC when needed.

Minimum supported version: Android 8.0.

## Privacy and support

### RoB version

- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### NFC to Excel version

- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)

## Notes

These APKs are distributed outside Google Play. Android may display an installation warning. Only install files obtained from this repository.
