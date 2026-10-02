# NFC tag reader applications

This repository contains the public Android builds discussed here.

## RoB NFC tag reader

Customized for Runners of Bucharest.

[**Download RoB NFC tag reader — latest APK**](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-latest.apk)

[Version-specific RoB v2.0.6 APK](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/download/RoB-NFC-tag-reader-v2.0.6.apk)

The legacy `NFC-People-Logger-latest.apk` URL downloads the exact same current RoB APK.

### Current RoB version

- Version: **2.0.6**
- Internal version code: **28**
- Package: `com.andrei.nfcpeople`
- SHA-256: `ec9c692dd799aff928a00d5526bdef330985734831afcbdb63fb4fcf6d0c82a6`
- Footer: `Version 2.0.6 • © andreimariuspetre`

### v2.0.6 deletion fix

The remaining deletion crash in v2.0.5 was caused by a concrete SQLite column-name mismatch in the renumbering code. The database schema uses `sequence_number`, but the deletion renumbering path incorrectly referenced `sequence`.

v2.0.6 now uses `sequence_number` consistently for both ordering and updates. After deleting a row, remaining entries are renumbered contiguously.

Example:

`1, 2, 3` → delete entry `1` → remaining entries become `1, 2`.

### Existing behavior preserved

- Single tap on an entry does nothing.
- Long press opens entry actions.
- NFC rows show **Hold for delete entry**.
- Manual rows show **Hold for edit or delete entry**.
- Manual rows offer **EDIT NAME** and **DELETE ENTRY**.
- NFC rows offer **DELETE ENTRY**.
- Manual Add/Edit uses Android word capitalization and autocorrect.
- Deletion uses one confirmation with the selected name bolded.
- Excel title is **RoB presence list — DD.MM.YYYY**, using the session/list date.
- Excel contains a **Source** column with `Scan` or `Manual`.
- RoB Excel output remains Romanian-aware, case-insensitive alphabetical order.
- NFC repeat protection, vibration, live counter, pause/resume, session persistence, empty-session closure, responsive/Fold layouts and finalized-session read-only behavior remain unchanged.

### Upgrade compatibility

- v2.0.5: versionCode **27**
- v2.0.6: versionCode **28**

Both use package `com.andrei.nfcpeople` and the same signing certificate, so v2.0.6 installs directly over v2.0.5 and earlier RoB releases without uninstalling.

[Download RoB v2.0.6 source](https://raw.githubusercontent.com/ampetre/nfc-people-read/main/source/RoB-NFC-tag-reader-v2.0.6-source.zip)

## NFC to Excel tag reader

The generic Google Play variant is maintained separately and was not changed by this RoB v2.0.6 release.

## Privacy and support

### RoB version
- [Privacy policy](PRIVACY.md)
- [Support](SUPPORT.md)

### Generic version
- [Privacy policy](PRIVACY_NFC_TO_EXCEL.md)
- [Support](SUPPORT_NFC_TO_EXCEL.md)
