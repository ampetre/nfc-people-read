# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.4 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.4.apk)

The legacy `NFC-People-Logger-latest.apk` URL downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.4**
- Internal version code: **25**
- Package: `com.andrei.nfcpeople`
- SHA-256: `d2aa95d7ee2ad876bf90c6a3114ad3fb74a152a0caa7b718c62c4166f338ddef`
- Footer: `Version 2.0.4 • © andreimariuspetre`

### v2.0.4 change

Each editable list row now includes its own small contextual guide below the timestamp:

- NFC scan: **Hold for delete entry**
- Manual entry: **Hold for edit or delete entry**

The hint is rendered smaller and in the secondary-text color so it remains visible without dominating the list. The old generic long-press instruction above the list was removed.

Non-finalized review lists show the same hints. Finalized/read-only history does not show action hints.

### Existing behavior preserved

- Single tap on an entry does nothing.
- Long press opens entry actions.
- Manual rows show **EDIT NAME** and **DELETE ENTRY**.
- NFC rows show **DELETE ENTRY**.
- Manual Add/Edit uses Android word capitalization and autocorrect.
- Deletion uses one confirmation with the selected name bolded.
- Excel workbook title is **RoB presence list — DD.MM.YYYY**, using the session/list date.
- Excel contains a **Source** column with `Scan` or `Manual`.
- RoB Excel output remains Romanian-aware, case-insensitive alphabetical order.
- Original date/time stays attached to each entry.
- NFC repeat protection, rapid reads of different tags, vibration behavior, live counter, pause/resume, session persistence, empty-session closure, Excel compatibility, RoB branding and responsive/Fold layouts remain unchanged.
- Finalized sessions remain read-only.

### Upgrade compatibility

- v1.8.1: versionCode **10**
- v2.0.3: versionCode **24**
- v2.0.4: versionCode **25**

All use package `com.andrei.nfcpeople` and the same signing certificate, so v2.0.4 installs directly over the earlier RoB versions without uninstalling and preserves existing app data.

[Download RoB v2.0.4 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.4-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately and was not changed by this RoB v2.0.4 release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)
