# RoB NFC tag reader

Android application for reading NFC tags containing person names, maintaining a live attendance list, and exporting the completed daily list to Excel (`.xlsx`).

## Download the latest version

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

Current release: **v1.7.0**

[Version-specific v1.7.0 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v1.7.0.apk)

The previously shared `NFC-People-Logger-latest.apk` link is retained and points to the same current APK.

## Installation

1. Download the APK on an Android phone.
2. Open the downloaded file.
3. When Android asks, allow installation from the browser or file manager being used.
4. Install and open **RoB NFC tag reader**.
5. Enable NFC from the app's **NFC Settings** button when needed.

## Version

- Version: **1.7.0**
- Package: `com.andrei.nfcpeople`
- Minimum Android version: Android 8.0
- SHA-256: `9a2c0b0f59120905293841ae41b77de30c4d1688ae5ca73c809e229969f4de59`

## Changes in v1.7.0

- Renames the launcher and in-app title to **RoB NFC tag reader**.
- Changes the suggested Excel filename to `RoB_NFC_tag_reader_YYYY-MM-DD.xlsx`.
- Allows a started session with zero NFC reads to be closed after confirmation, without creating an Excel file.
- Sessions containing reads keep the existing XLSX export workflow unchanged.
- Retains the Runners of Bucharest launcher icon, NFC reading, live list, vibration behavior, duplicate-tag handling, database, and Excel workbook format.
- Uses the same signing certificate, allowing direct installation over v1.6.0 without uninstalling.

## Notes

This APK is distributed outside Google Play. Android may display a warning before installation. Only install the APK from this repository.
