# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.1 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.1.apk)

The legacy `NFC-People-Logger-latest.apk` URL downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.1**
- Internal version code: **22**
- Package: `com.andrei.nfcpeople`
- SHA-256: `1101186ca87e7cb9018bc83872fb1e9f5d97b655907d0862992e3bdf1ebe214c`
- Footer: `Version 2.0.1 • © andreimariuspetre`

### v2.0.1 interaction changes

- A **single tap on an entry does nothing**.
- **Long-press an entry** to open its available actions.
- Manual entries offer **Edit name** and **Delete entry**.
- NFC-scanned entries offer **Delete entry** only.
- The same long-press behavior is used while reviewing a non-finalized session.
- Manual Add/Edit fields use Android **capitalize words** input behavior plus autocorrect, so names start with a capital and the keyboard automatically offers a capital after whitespace for the next name part.
- Deletion keeps the single English confirmation dialog with the selected name bolded:
  `Do you want to remove the name "Name" from the list?`
- Confirmation buttons remain **Yes, remove it from the list** and **No**.

### Existing behavior preserved

- Manual entries share the same active list as NFC scans.
- Manual entries can be edited before finalization.
- Scanned and manual rows can both be deleted before finalization.
- Excel contains a **Source** column with `Scan` or `Manual`.
- RoB Excel output remains Romanian-aware, case-insensitive alphabetical order.
- Original date/time stays attached to each entry.
- NFC repeat protection, rapid reads of different tags, vibration behavior, live counter, pause/resume, session persistence, empty-session closure, Excel compatibility, RoB branding and responsive/Fold layouts remain unchanged.
- Finalized sessions remain read-only.

### Upgrade compatibility

The v2.0.1 build was explicitly validated against both previous published builds:

- v1.8.1: versionCode **10**
- v2.0.0: versionCode **21**
- v2.0.1: versionCode **22**

All use package `com.andrei.nfcpeople` and the same signing certificate, so v2.0.1 installs directly over v1.8.x or v2.0.0 without uninstalling and preserves existing app data.

[Download RoB v2.0.1 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.1-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately and was not changed by this RoB v2.0.1 release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)
