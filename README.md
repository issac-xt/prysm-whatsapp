# prysm-whatsapp

WhatsApp APK releases used by Prysm's patch flow (arm64-v8a only).

Mirrors the stock, unmodified WhatsApp APK as published by WhatsApp Inc. - no build-time
repackaging is applied (WhatsApp installs as an ordinary `/data/app` package, unlike
[prysm-youtube](https://github.com/issac-xt/prysm-youtube), which requires repackaging since
YouTube ships as a system app). Each release holds exactly one `.apk` asset, fetched by Prysm's
`TargetApkFetcher` via the GitHub Releases API.

Part of [Prysm](https://github.com/issac-xt/prysm) - a personal Xposed module.
