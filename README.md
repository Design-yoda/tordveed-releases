# TordVeed releases

Installers for TordVeed, and the feed the app reads to offer updates.

**Download:** grab the installer for your system from the [latest release](https://github.com/Design-yoda/tordveed-releases/releases/latest).

## For the app

Each release contains `latest.json`, which TordVeed checks to see whether a newer version exists. The app never installs on its own: it asks first, saves your project, then restarts.

Update files are signed. The app only installs an update whose signature matches the public key built into it, so a file that was tampered with, or published by anyone else, is rejected.

This repository holds release files only. It contains no source code.
