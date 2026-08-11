# E290 Stock Ticker OTA

Public HTTPS OTA channel for the Heltec Vision Master E290 stock ticker.

The device reads [`manifest.json`](manifest.json), compares `version` with its
installed firmware, and downloads the release asset over certificate-verified
HTTPS when a newer version is available.

Current release: `v0.3.6`

Firmware SHA-256:

`cbc56917d0689956f4e0c92200bc962e2616f39bd3bd470a06824bfa1d959bf8`
