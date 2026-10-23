# Divina releases

Public downloads of Divina, the spatial OS you talk to ([divinaos.site](https://divinaos.site)).

## Obstat edition

The Divina edition that [Obstat](https://obstat.app) installs for free. Each version lives in its own folder, `obstat/<version>/`, with the installer's exact size and SHA-256 (`SHA256SUMS.txt` and a `.json`). Files are never replaced: a new version always gets a new folder and file name.

- Windows 10/11, 64-bit. Installs for the current user, no admin prompt.
- Silent install: `Divina-Obstat-Setup-<version>-x64.exe /S` (optionally `/D=<folder>`).
- Silent uninstall: `"Uninstall Divina.exe" /S` (keeps your settings in `%APPDATA%\Divina`).

© 2026 Sweeney Creative. Divina is not open source; these builds are provided for personal use under the licence agreement included in the installer.
