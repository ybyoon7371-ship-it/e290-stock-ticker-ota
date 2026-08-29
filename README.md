# E290 Stock Ticker OTA

Public HTTPS OTA channel for the Heltec Vision Master E290 stock ticker.

The device reads [`manifest.json`](manifest.json), compares `version` with its
installed firmware, and downloads the release asset over certificate-verified
HTTPS when a newer version is available.

Current release: `v0.4.9`

Firmware SHA-256:

`9fae3b3f793592b9961c7e1b4d6bf3153d9e3a7c09255bdd430f3fbd3c76481b`

The manifest uses a versioned raw firmware URL so ESP32 devices do not need to
follow GitHub release-asset redirects or receive an older cached binary.
