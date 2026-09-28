# android-hermes-ota

Release channel for the private **android-hermes** Ekko Studio Android client.

This repository is **public on purpose**: the in-app updater hands `latest.json`'s `apkUrl`
to the phone's browser, and a private repository would answer anonymous downloads with
HTTP 401.

It contains **no source code and no secrets** — only:

* `latest.json` — the release manifest polled by installed apps
* APK binaries attached as GitHub release assets

Do not commit anything else here. Source lives in the private `android-hermes` repository.
