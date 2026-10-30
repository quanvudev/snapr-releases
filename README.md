# Snapr

Tray screenshot and screen recording app for Windows 10/11.

This repository only hosts release builds. The source code is private.

## Install

Download `Snapr_<version>_x64-setup.exe` from the [latest release](https://github.com/quanvudev/snapr-releases/releases/latest) and run it. It installs for the current user and needs no administrator rights.

Windows SmartScreen may warn that the publisher is unknown, because the installer is not code-signed. Choose **More info**, then **Run anyway**.

### Scoop

Available from Snapr 1.9.0. This repository is also a [Scoop](https://scoop.sh) bucket:

```powershell
scoop bucket add snapr https://github.com/quanvudev/snapr-releases
scoop install snapr/snapr
```

Close Snapr before running `scoop update snapr`. Uninstalling with Scoop keeps your settings and captures.

## Updates

Snapr checks this repository for new versions and offers them from the tray menu and Settings, About. You can turn automatic checks off in Settings, General.
