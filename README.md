# E290 Stock Ticker OTA

Public HTTPS OTA channel for the Heltec Vision Master E290 stock ticker.

The device reads [`manifest.json`](manifest.json), compares `version` with its
installed firmware, and downloads the release asset over certificate-verified
HTTPS when a newer version is available.

Current release: `v0.4.8`

Firmware SHA-256:

`94065bb4148f9ff6a819fa2efb6d85e66e0daa9f18a61e2a039b9f51572e7afa`

The manifest uses the repository's raw `firmware.bin` URL so ESP32 devices do
not need to follow GitHub release-asset redirects during OTA.
