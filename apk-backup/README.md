# APK backup — Agility Companion 2.0.7

Backup of the last release of **Agility Companion** (the Kymco Agility 50 4T companion app),
taken before `kymco-agility-moto` is turned into the generic **Scooter Companion** app.

| | |
|---|---|
| File | `agility-companion-v2.0.7.apk` |
| Source release | https://github.com/achma-learning/kymco-agility-moto/releases/tag/v2.0.7 (published 2026-10-11) |
| Package | `com.example.kymcoagility50` |
| SHA-256 | see `SHA256SUMS` |

## Install

Copy the APK to an Android phone, open it and allow "install unknown apps" once.

## Moving your data to Scooter Companion

Scooter Companion is a new app (new package name and signing key), so it does not update
this one in place. Before switching: **Settings → Export** in Agility Companion, then
**Import** that JSON file in Scooter Companion. Agility v1 backups stay importable.

Verify the file: `sha256sum -c SHA256SUMS`
