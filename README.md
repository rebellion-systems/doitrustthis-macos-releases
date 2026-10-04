# DITT for Mac downloads

Official signed, Apple-notarized DITT for Mac releases from Rebellion Systems.
This repository hosts downloads and signed update metadata. The application source
is maintained separately.

DITT needs macOS 14 or later and supports Apple silicon and Intel Macs.

## Install

Download the ZIP from [Releases](https://github.com/rebellion-systems/doitrustthis-macos-releases/releases),
unzip it, and move **DITT.app** to **Applications**. Quit any older running copy
before replacing it, then open DITT from Applications.

Setup explains the configured defaults and requests permissions individually.
Review privacy settings during setup if you want to change what is checked or
sent to DITT. No monitoring starts before **Start DITT**.

## Updates

In version 0.1.1 and later, use **Settings → Updates**. Daily update checks are on
by default after setup; automatic download and installation are optional and off
by default. Earlier previews need one manual installation to get this updater.

The update feed is available at [doitrustthis.com/mac/appcast.xml](https://doitrustthis.com/mac/appcast.xml).
Update metadata and archives carry Ed25519 signatures, and the app is Developer ID
signed and notarized. Update checks do not send captured content or check history.

[Do I Trust This](https://doitrustthis.com) · [Privacy](https://doitrustthis.com/privacy.html)
