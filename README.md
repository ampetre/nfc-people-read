# RoB NFC tag reader

Android application for reading NFC tags containing person names, maintaining a live attendance list, and exporting the completed daily list to Excel (`.xlsx`).

## Download the latest version

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

Current public sideload release: **v1.8.0**

[Version-specific v1.8.0 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v1.8.0.apk)

The previously shared `NFC-People-Logger-latest.apk` link is retained and points to the same current APK.

## Installation

1. Download the APK on an Android phone.
2. Open the downloaded file.
3. When Android asks, allow installation from the browser or file manager being used.
4. Install and open **RoB NFC tag reader**.
5. Enable NFC from the app's **NFC Settings** button when needed.

## Version

- Version: **1.8.0**
- Package: `com.andrei.nfcpeople`
- Minimum Android version: Android 8.0
- SHA-256: `63e71882313993e6a7fd1081c80c5004aaeb2134c3d46297c6da7b1c551ee6f3`

## Changes in v1.8.0

- Excel rows are sorted alphabetically by the person name read from the NFC tag.
- Sorting is case-insensitive and uses Romanian-aware collation.
- The exported `No.` column is renumbered from 1 to N in alphabetical order.
- Original scan date and time remain attached to each exported person.
- The live reader and review screens remain in chronological scan order.
- NFC reading, vibration feedback, duplicate-tag handling, empty-session closing, database storage, app icon and workbook structure remain unchanged from v1.7.0.
- Uses the same signing certificate, allowing direct installation over v1.7.0 without uninstalling.

## Privacy and support

- [Privacy policy](PRIVACY.md)
- [Support and issue reporting](SUPPORT.md)

## Notes

This APK is distributed outside Google Play. Android may display a warning before installation. Only install the APK from this repository.
