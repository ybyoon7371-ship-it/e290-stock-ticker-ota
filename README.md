# E290 Stock Ticker OTA

Public HTTPS OTA channel for the Heltec Vision Master E290 stock ticker.

The device reads [`manifest.json`](manifest.json), compares `version` with its
installed firmware, and downloads the release asset over certificate-verified
HTTPS when a newer version is available.

Current release: `v0.3.5`

Firmware SHA-256:

`80e65bf3e5266729d99474c49bb72a985e507a5ef5886ebe5ff2307cd4fe0a30`
