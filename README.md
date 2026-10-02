# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.3 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.3.apk)

The legacy `NFC-People-Logger-latest.apk` URL downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.3**
- Internal version code: **24**
- Package: `com.andrei.nfcpeople`
- SHA-256: `5c8aeafa2eff386ab678fe4be826a2919483eb61d3822fce000cc567eb7496fb`
- Footer: `Version 2.0.3 • © andreimariuspetre`

### v2.0.3 change

- The Excel workbook title in row 1 is now:
  **RoB presence list — DD.MM.YYYY**
- The date is the date of the session/list.
- The previous **NFC People** wording is removed.

### Existing behavior preserved

- Single tap on a row does nothing.
- Long press opens entry actions.
- Manual rows show **EDIT NAME** and **DELETE ENTRY**.
- NFC rows show **DELETE ENTRY**.
- Manual Add/Edit uses Android word capitalization and autocorrect.
- Deletion uses one confirmation with the selected name bolded.
- Excel contains a **Source** column with `Scan` or `Manual`.
- RoB Excel output remains Romanian-aware, case-insensitive alphabetical order.
- Original date/time stays attached to each entry.
- NFC repeat protection, rapid reads of different tags, vibration behavior, live counter, pause/resume, session persistence, empty-session closure, Excel compatibility, RoB branding and responsive/Fold layouts remain unchanged.
- Finalized sessions remain read-only.

### Upgrade compatibility

- v1.8.1: versionCode **10**
- v2.0.2: versionCode **23**
- v2.0.3: versionCode **24**

All use package `com.andrei.nfcpeople` and the same signing certificate, so v2.0.3 installs directly over earlier RoB versions without uninstalling and preserves existing app data.

[Download RoB v2.0.3 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.3-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately and was not changed by this RoB v2.0.3 release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)
