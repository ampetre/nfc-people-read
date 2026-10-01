# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.2 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.2.apk)

The legacy `NFC-People-Logger-latest.apk` URL downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.2**
- Internal version code: **23**
- Package: `com.andrei.nfcpeople`
- SHA-256: `83aef519b6f4efd20c58c806a8445cf09a4ff08cd7de4a640e6c129ef05b1c91`
- Footer: `Version 2.0.2 • © andreimariuspetre`

### v2.0.2 fix

- Fixes the long-press action dialog on devices/themes where the previous AlertDialog action list was not rendered.
- The action menu now uses explicit visible buttons instead of `AlertDialog.setItems(...)`.
- Manual entries show **EDIT NAME** and **DELETE ENTRY**.
- NFC-scanned entries show **DELETE ENTRY** only.
- A single tap still does nothing.
- Long-press remains the only way to open entry actions.
- The selected row metadata (Manual entry/NFC scan and timestamp) remains visible above the action buttons.

### Existing behavior preserved

- Manual Add/Edit fields use Android word capitalization and autocorrect.
- Deletion uses the single English confirmation with the selected name bolded.
- Manual entries share the same active list as NFC scans.
- Excel contains a **Source** column with `Scan` or `Manual`.
- RoB Excel output remains Romanian-aware, case-insensitive alphabetical order.
- Original date/time stays attached to each entry.
- NFC repeat protection, rapid reads of different tags, vibration behavior, live counter, pause/resume, session persistence, empty-session closure, Excel compatibility, RoB branding and responsive/Fold layouts remain unchanged.
- Finalized sessions remain read-only.

### Upgrade compatibility

- v1.8.1: versionCode **10**
- v2.0.0: versionCode **21**
- v2.0.1: versionCode **22**
- v2.0.2: versionCode **23**

All use package `com.andrei.nfcpeople` and the same signing certificate, so v2.0.2 installs directly over the earlier RoB versions without uninstalling and preserves existing app data.

[Download RoB v2.0.2 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.2-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately and was not changed by this RoB v2.0.2 release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)
