# E290 Stock Ticker OTA

Public HTTPS OTA channel for the Heltec Vision Master E290 stock ticker.

The device reads [`manifest.json`](manifest.json), compares `version` with its
installed firmware, and downloads the release asset over certificate-verified
HTTPS when a newer version is available.

Current release: `v0.4.7`

Firmware SHA-256:

`7427d546acbf90a618821473ff3a84a817385c57576b640c7d37a643601de294`
